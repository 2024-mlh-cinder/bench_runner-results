
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 272 ms: 1.27x faster                                           |
| chameleon      | 9.84 ms                                                | 7.34 ms: 1.34x faster                                          |
| docutils       | 3.26 sec                                               | 2.65 sec: 1.23x faster                                         |
| tornado_http   | 131 ms                                                 | 96.5 ms: 1.35x faster                                          |
| Geometric mean | (ref)                                                  | 1.30x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 442 ms: 1.66x faster                                           |
| async_tree_memoization  | 867 ms                                                 | 569 ms: 1.52x faster                                           |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.49x faster                                         |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 715 ms: 1.41x faster                                           |
| Geometric mean          | (ref)                                                  | 1.52x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 97.3 ms: 1.52x faster                                          |
| float          | 116 ms                                                 | 86.5 ms: 1.35x faster                                          |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                           |
| Geometric mean | (ref)                                                  | 1.26x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 141 ms: 1.32x faster                                           |
| regex_v8       | 26.2 ms                                                | 25.7 ms: 1.02x faster                                          |
| regex_dna      | 215 ms                                                 | 214 ms: 1.00x faster                                           |
| regex_effbot   | 3.41 ms                                                | 3.56 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.07x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                           |
| unpickle_pure_python | 327 us                                                 | 231 us: 1.42x faster                                           |
| tomli_loads          | 3.06 sec                                               | 2.23 sec: 1.37x faster                                         |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| xml_etree_process    | 79.8 ms                                                | 60.0 ms: 1.33x faster                                          |
| xml_etree_generate   | 100.0 ms                                               | 87.8 ms: 1.14x faster                                          |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 108 ms: 1.07x faster                                           |
| pickle_list          | 5.05 us                                                | 4.90 us: 1.03x faster                                          |
| unpickle             | 14.9 us                                                | 14.9 us: 1.01x slower                                          |
| pickle               | 10.7 us                                                | 11.1 us: 1.04x slower                                          |
| unpickle_list        | 5.10 us                                                | 5.36 us: 1.05x slower                                          |
| pickle_dict          | 30.0 us                                                | 34.2 us: 1.14x slower                                          |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                          |
| python_startup_no_site | 5.87 ms                                                | 9.10 ms: 1.55x slower                                          |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.3 ms: 1.33x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 122 us: 4.61x faster                                           |
| generators               | 78.9 ms                                                | 29.2 ms: 2.71x faster                                          |
| deltablue                | 7.81 ms                                                | 4.00 ms: 1.95x faster                                          |
| asyncio_tcp              | 918 ms                                                 | 496 ms: 1.85x faster                                           |
| richards_super           | 95.6 ms                                                | 52.8 ms: 1.81x faster                                          |
| logging_silent           | 189 ns                                                 | 107 ns: 1.76x faster                                           |
| chaos                    | 114 ms                                                 | 65.8 ms: 1.74x faster                                          |
| raytrace                 | 498 ms                                                 | 287 ms: 1.73x faster                                           |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.73x faster                                           |
| richards                 | 79.4 ms                                                | 46.9 ms: 1.69x faster                                          |
| async_tree_none          | 732 ms                                                 | 442 ms: 1.66x faster                                           |
| sqlglot_parse            | 2.15 ms                                                | 1.30 ms: 1.65x faster                                          |
| crypto_pyaes             | 127 ms                                                 | 77.1 ms: 1.64x faster                                          |
| scimark_monte_carlo      | 118 ms                                                 | 74.0 ms: 1.59x faster                                          |
| go                       | 238 ms                                                 | 149 ms: 1.59x faster                                           |
| pickle_pure_python       | 482 us                                                 | 305 us: 1.58x faster                                           |
| coroutines               | 34.5 ms                                                | 21.9 ms: 1.58x faster                                          |
| sqlglot_transpile        | 2.55 ms                                                | 1.62 ms: 1.57x faster                                          |
| async_tree_memoization   | 867 ms                                                 | 569 ms: 1.52x faster                                           |
| nbody                    | 148 ms                                                 | 97.3 ms: 1.52x faster                                          |
| scimark_lu               | 175 ms                                                 | 118 ms: 1.49x faster                                           |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.49x faster                                         |
| spectral_norm            | 163 ms                                                 | 110 ms: 1.48x faster                                           |
| comprehensions           | 28.5 us                                                | 19.3 us: 1.48x faster                                          |
| deepcopy_memo            | 58.8 us                                                | 40.1 us: 1.47x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                         |
| unpickle_pure_python     | 327 us                                                 | 231 us: 1.42x faster                                           |
| logging_simple           | 8.27 us                                                | 5.85 us: 1.41x faster                                          |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 715 ms: 1.41x faster                                           |
| logging_format           | 9.07 us                                                | 6.46 us: 1.40x faster                                          |
| pyflate                  | 708 ms                                                 | 513 ms: 1.38x faster                                           |
| tomli_loads              | 3.06 sec                                               | 2.23 sec: 1.37x faster                                         |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                          |
| deepcopy                 | 481 us                                                 | 353 us: 1.36x faster                                           |
| hexiom                   | 10.3 ms                                                | 7.59 ms: 1.36x faster                                          |
| tornado_http             | 131 ms                                                 | 96.5 ms: 1.35x faster                                          |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| float                    | 116 ms                                                 | 86.5 ms: 1.35x faster                                          |
| chameleon                | 9.84 ms                                                | 7.34 ms: 1.34x faster                                          |
| deepcopy_reduce          | 4.17 us                                                | 3.13 us: 1.33x faster                                          |
| mako                     | 16.3 ms                                                | 12.3 ms: 1.33x faster                                          |
| xml_etree_process        | 79.8 ms                                                | 60.0 ms: 1.33x faster                                          |
| sqlglot_normalize        | 141 ms                                                 | 107 ms: 1.33x faster                                           |
| unpack_sequence          | 65.7 ns                                                | 49.9 ns: 1.32x faster                                          |
| regex_compile            | 186 ms                                                 | 141 ms: 1.32x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.62 sec: 1.29x faster                                         |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.29x faster                                         |
| pprint_safe_repr         | 1.01 sec                                               | 798 ms: 1.27x faster                                           |
| 2to3                     | 346 ms                                                 | 272 ms: 1.27x faster                                           |
| sqlglot_optimize         | 68.7 ms                                                | 54.1 ms: 1.27x faster                                          |
| sympy_sum                | 190 ms                                                 | 150 ms: 1.27x faster                                           |
| mypy2                    | 442 ms                                                 | 350 ms: 1.26x faster                                           |
| sympy_integrate          | 25.4 ms                                                | 20.5 ms: 1.24x faster                                          |
| sympy_str                | 337 ms                                                 | 273 ms: 1.23x faster                                           |
| docutils                 | 3.26 sec                                               | 2.65 sec: 1.23x faster                                         |
| fannkuch                 | 527 ms                                                 | 430 ms: 1.22x faster                                           |
| sympy_expand             | 558 ms                                                 | 463 ms: 1.21x faster                                           |
| dask                     | 432 ms                                                 | 364 ms: 1.19x faster                                           |
| scimark_fft              | 454 ms                                                 | 383 ms: 1.19x faster                                           |
| nqueens                  | 107 ms                                                 | 90.9 ms: 1.17x faster                                          |
| dulwich_log              | 77.0 ms                                                | 66.6 ms: 1.16x faster                                          |
| bench_thread_pool        | 966 us                                                 | 845 us: 1.14x faster                                           |
| xml_etree_generate       | 100.0 ms                                               | 87.8 ms: 1.14x faster                                          |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.45 ms: 1.12x faster                                          |
| mdp                      | 2.93 sec                                               | 2.63 sec: 1.12x faster                                         |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                          |
| pathlib                  | 20.3 ms                                                | 18.5 ms: 1.10x faster                                          |
| json                     | 5.67 ms                                                | 5.18 ms: 1.09x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.08x faster                                          |
| meteor_contest           | 119 ms                                                 | 110 ms: 1.08x faster                                           |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                           |
| sqlite_synth             | 3.02 us                                                | 2.80 us: 1.08x faster                                          |
| xml_etree_iterparse      | 116 ms                                                 | 108 ms: 1.07x faster                                           |
| pickle_list              | 5.05 us                                                | 4.90 us: 1.03x faster                                          |
| regex_v8                 | 26.2 ms                                                | 25.7 ms: 1.02x faster                                          |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                           |
| regex_dna                | 215 ms                                                 | 214 ms: 1.00x faster                                           |
| unpickle                 | 14.9 us                                                | 14.9 us: 1.01x slower                                          |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                           |
| pickle                   | 10.7 us                                                | 11.1 us: 1.04x slower                                          |
| async_generators         | 442 ms                                                 | 461 ms: 1.04x slower                                           |
| regex_effbot             | 3.41 ms                                                | 3.56 ms: 1.05x slower                                          |
| unpickle_list            | 5.10 us                                                | 5.36 us: 1.05x slower                                          |
| gc_traversal             | 3.43 ms                                                | 3.82 ms: 1.11x slower                                          |
| pickle_dict              | 30.0 us                                                | 34.2 us: 1.14x slower                                          |
| coverage                 | 82.0 ms                                                | 94.7 ms: 1.16x slower                                          |
| telco                    | 7.01 ms                                                | 8.44 ms: 1.20x slower                                          |
| python_startup_no_site   | 5.87 ms                                                | 9.10 ms: 1.55x slower                                          |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                   |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-7a7e995/bm-20231115-linux-x86_64-brandtbucher-justin-3.13.0a1+-7a7e995.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.23x
