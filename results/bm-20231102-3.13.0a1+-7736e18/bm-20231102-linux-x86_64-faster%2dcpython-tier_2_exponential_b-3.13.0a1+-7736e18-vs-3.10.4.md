
# Results vs. 3.10.4

- fork: faster-cpython
- ref: tier_2_exponential_b
- machine: linux-x86_64
- commit hash: 7736e18
- commit date: 2023-11-02
- overall geometric mean: 1.27x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 279 ms: 1.24x faster                                                             |
| chameleon      | 9.84 ms                                                | 7.09 ms: 1.39x faster                                                            |
| docutils       | 3.26 sec                                               | 2.71 sec: 1.21x faster                                                           |
| tornado_http   | 131 ms                                                 | 98.0 ms: 1.33x faster                                                            |
| Geometric mean | (ref)                                                  | 1.29x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 452 ms: 1.62x faster                                                             |
| async_tree_memoization  | 867 ms                                                 | 579 ms: 1.50x faster                                                             |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.47x faster                                                           |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 725 ms: 1.39x faster                                                             |
| Geometric mean          | (ref)                                                  | 1.49x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 110 ms: 1.35x faster                                                             |
| float          | 116 ms                                                 | 96.2 ms: 1.21x faster                                                            |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| Geometric mean | (ref)                                                  | 1.17x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 157 ms: 1.18x faster                                                             |
| regex_v8       | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                            |
| regex_dna      | 215 ms                                                 | 211 ms: 1.02x faster                                                             |
| regex_effbot   | 3.41 ms                                                | 3.73 ms: 1.09x slower                                                            |
| Geometric mean | (ref)                                                  | 1.03x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 310 us: 1.56x faster                                                             |
| unpickle_pure_python | 327 us                                                 | 239 us: 1.37x faster                                                             |
| json_dumps           | 14.3 ms                                                | 10.7 ms: 1.34x faster                                                            |
| xml_etree_process    | 79.8 ms                                                | 59.9 ms: 1.33x faster                                                            |
| tomli_loads          | 3.06 sec                                               | 2.49 sec: 1.23x faster                                                           |
| xml_etree_generate   | 100.0 ms                                               | 87.0 ms: 1.15x faster                                                            |
| json_loads           | 31.4 us                                                | 27.7 us: 1.13x faster                                                            |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                             |
| xml_etree_iterparse  | 116 ms                                                 | 111 ms: 1.05x faster                                                             |
| pickle_list          | 5.05 us                                                | 5.10 us: 1.01x slower                                                            |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                                            |
| pickle_dict          | 30.0 us                                                | 32.7 us: 1.09x slower                                                            |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                                     |

Benchmark hidden because not significant (2): unpickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| python_startup_no_site | 5.87 ms                                                | 9.00 ms: 1.53x slower                                                            |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 14.0 ms: 1.16x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 125 us: 4.50x faster                                                             |
| generators               | 78.9 ms                                                | 29.6 ms: 2.67x faster                                                            |
| asyncio_tcp              | 918 ms                                                 | 493 ms: 1.86x faster                                                             |
| logging_silent           | 189 ns                                                 | 108 ns: 1.75x faster                                                             |
| raytrace                 | 498 ms                                                 | 289 ms: 1.72x faster                                                             |
| deltablue                | 7.81 ms                                                | 4.58 ms: 1.71x faster                                                            |
| crypto_pyaes             | 127 ms                                                 | 75.5 ms: 1.68x faster                                                            |
| chaos                    | 114 ms                                                 | 68.2 ms: 1.68x faster                                                            |
| richards_super           | 95.6 ms                                                | 57.6 ms: 1.66x faster                                                            |
| scimark_sor              | 214 ms                                                 | 132 ms: 1.63x faster                                                             |
| async_tree_none          | 732 ms                                                 | 452 ms: 1.62x faster                                                             |
| scimark_monte_carlo      | 118 ms                                                 | 72.9 ms: 1.62x faster                                                            |
| sqlglot_parse            | 2.15 ms                                                | 1.34 ms: 1.60x faster                                                            |
| richards                 | 79.4 ms                                                | 50.4 ms: 1.58x faster                                                            |
| pickle_pure_python       | 482 us                                                 | 310 us: 1.56x faster                                                             |
| coroutines               | 34.5 ms                                                | 22.3 ms: 1.54x faster                                                            |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.52x faster                                                            |
| async_tree_memoization   | 867 ms                                                 | 579 ms: 1.50x faster                                                             |
| go                       | 238 ms                                                 | 159 ms: 1.49x faster                                                             |
| scimark_lu               | 175 ms                                                 | 119 ms: 1.48x faster                                                             |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.47x faster                                                           |
| spectral_norm            | 163 ms                                                 | 112 ms: 1.45x faster                                                             |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                                           |
| deepcopy_memo            | 58.8 us                                                | 41.4 us: 1.42x faster                                                            |
| logging_format           | 9.07 us                                                | 6.45 us: 1.41x faster                                                            |
| logging_simple           | 8.27 us                                                | 5.94 us: 1.39x faster                                                            |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 725 ms: 1.39x faster                                                             |
| chameleon                | 9.84 ms                                                | 7.09 ms: 1.39x faster                                                            |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                            |
| pyflate                  | 708 ms                                                 | 514 ms: 1.38x faster                                                             |
| unpickle_pure_python     | 327 us                                                 | 239 us: 1.37x faster                                                             |
| deepcopy_reduce          | 4.17 us                                                | 3.05 us: 1.36x faster                                                            |
| deepcopy                 | 481 us                                                 | 353 us: 1.36x faster                                                             |
| nbody                    | 148 ms                                                 | 110 ms: 1.35x faster                                                             |
| json_dumps               | 14.3 ms                                                | 10.7 ms: 1.34x faster                                                            |
| tornado_http             | 131 ms                                                 | 98.0 ms: 1.33x faster                                                            |
| xml_etree_process        | 79.8 ms                                                | 59.9 ms: 1.33x faster                                                            |
| unpack_sequence          | 65.7 ns                                                | 49.4 ns: 1.33x faster                                                            |
| sqlglot_normalize        | 141 ms                                                 | 107 ms: 1.32x faster                                                             |
| comprehensions           | 28.5 us                                                | 22.2 us: 1.29x faster                                                            |
| pycparser                | 1.57 sec                                               | 1.22 sec: 1.28x faster                                                           |
| pprint_safe_repr         | 1.01 sec                                               | 804 ms: 1.26x faster                                                             |
| sqlglot_optimize         | 68.7 ms                                                | 54.5 ms: 1.26x faster                                                            |
| fannkuch                 | 527 ms                                                 | 420 ms: 1.26x faster                                                             |
| pprint_pformat           | 2.10 sec                                               | 1.67 sec: 1.25x faster                                                           |
| mypy2                    | 442 ms                                                 | 354 ms: 1.25x faster                                                             |
| sympy_sum                | 190 ms                                                 | 153 ms: 1.24x faster                                                             |
| 2to3                     | 346 ms                                                 | 279 ms: 1.24x faster                                                             |
| tomli_loads              | 3.06 sec                                               | 2.49 sec: 1.23x faster                                                           |
| sympy_integrate          | 25.4 ms                                                | 21.0 ms: 1.21x faster                                                            |
| float                    | 116 ms                                                 | 96.2 ms: 1.21x faster                                                            |
| docutils                 | 3.26 sec                                               | 2.71 sec: 1.21x faster                                                           |
| sympy_str                | 337 ms                                                 | 281 ms: 1.20x faster                                                             |
| regex_compile            | 186 ms                                                 | 157 ms: 1.18x faster                                                             |
| hexiom                   | 10.3 ms                                                | 8.74 ms: 1.18x faster                                                            |
| sympy_expand             | 558 ms                                                 | 476 ms: 1.17x faster                                                             |
| mako                     | 16.3 ms                                                | 14.0 ms: 1.16x faster                                                            |
| bench_thread_pool        | 966 us                                                 | 835 us: 1.16x faster                                                             |
| xml_etree_generate       | 100.0 ms                                               | 87.0 ms: 1.15x faster                                                            |
| dulwich_log              | 77.0 ms                                                | 67.2 ms: 1.15x faster                                                            |
| scimark_fft              | 454 ms                                                 | 398 ms: 1.14x faster                                                             |
| json_loads               | 31.4 us                                                | 27.7 us: 1.13x faster                                                            |
| nqueens                  | 107 ms                                                 | 95.9 ms: 1.11x faster                                                            |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.51 ms: 1.11x faster                                                            |
| json                     | 5.67 ms                                                | 5.15 ms: 1.10x faster                                                            |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                                            |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                             |
| sqlite_synth             | 3.02 us                                                | 2.88 us: 1.05x faster                                                            |
| xml_etree_iterparse      | 116 ms                                                 | 111 ms: 1.05x faster                                                             |
| meteor_contest           | 119 ms                                                 | 115 ms: 1.04x faster                                                             |
| mdp                      | 2.93 sec                                               | 2.84 sec: 1.03x faster                                                           |
| pathlib                  | 20.3 ms                                                | 19.7 ms: 1.03x faster                                                            |
| regex_v8                 | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                            |
| regex_dna                | 215 ms                                                 | 211 ms: 1.02x faster                                                             |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                             |
| pickle_list              | 5.05 us                                                | 5.10 us: 1.01x slower                                                            |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                                             |
| async_generators         | 442 ms                                                 | 455 ms: 1.03x slower                                                             |
| gc_traversal             | 3.43 ms                                                | 3.57 ms: 1.04x slower                                                            |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                                            |
| pickle_dict              | 30.0 us                                                | 32.7 us: 1.09x slower                                                            |
| regex_effbot             | 3.41 ms                                                | 3.73 ms: 1.09x slower                                                            |
| coverage                 | 82.0 ms                                                | 93.5 ms: 1.14x slower                                                            |
| telco                    | 7.01 ms                                                | 8.37 ms: 1.19x slower                                                            |
| python_startup_no_site   | 5.87 ms                                                | 9.00 ms: 1.53x slower                                                            |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                                     |

Benchmark hidden because not significant (3): unpickle_list, bench_mp_pool, unpickle
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-7736e18/bm-20231102-linux-x86_64-faster%2dcpython-tier_2_exponential_b-3.13.0a1+-7736e18.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.20x
