
# Results vs. 3.10.4

- fork: python
- ref: eb3c94ea669561a0dfac
- machine: linux-x86_64
- commit hash: eb3c94e
- commit date: 2023-11-17
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 289 ms: 1.20x faster                                                   |
| chameleon      | 9.84 ms                                                | 7.34 ms: 1.34x faster                                                  |
| docutils       | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                 |
| tornado_http   | 131 ms                                                 | 99.6 ms: 1.31x faster                                                  |
| Geometric mean | (ref)                                                  | 1.26x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 462 ms: 1.59x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 590 ms: 1.47x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.23 sec: 1.46x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 730 ms: 1.38x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.47x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 131 ms: 1.13x faster                                                   |
| float          | 116 ms                                                 | 103 ms: 1.13x faster                                                   |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 160 ms: 1.16x faster                                                   |
| regex_v8       | 26.2 ms                                                | 24.3 ms: 1.08x faster                                                  |
| regex_dna      | 215 ms                                                 | 221 ms: 1.03x slower                                                   |
| regex_effbot   | 3.41 ms                                                | 3.59 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 307 us: 1.57x faster                                                   |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 242 us: 1.35x faster                                                   |
| xml_etree_process    | 79.8 ms                                                | 60.5 ms: 1.32x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 88.7 ms: 1.13x faster                                                  |
| json_loads           | 31.4 us                                                | 28.3 us: 1.11x faster                                                  |
| tomli_loads          | 3.06 sec                                               | 2.77 sec: 1.10x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                                   |
| xml_etree_iterparse  | 116 ms                                                 | 111 ms: 1.05x faster                                                   |
| pickle               | 10.7 us                                                | 11.3 us: 1.06x slower                                                  |
| pickle_dict          | 30.0 us                                                | 34.5 us: 1.15x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                           |

Benchmark hidden because not significant (3): unpickle, unpickle_list, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.01 ms: 1.53x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 15.6 ms: 1.04x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 128 us: 4.37x faster                                                   |
| generators               | 78.9 ms                                                | 30.4 ms: 2.59x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 496 ms: 1.85x faster                                                   |
| logging_silent           | 189 ns                                                 | 110 ns: 1.72x faster                                                   |
| scimark_sor              | 214 ms                                                 | 127 ms: 1.69x faster                                                   |
| richards_super           | 95.6 ms                                                | 57.0 ms: 1.68x faster                                                  |
| raytrace                 | 498 ms                                                 | 311 ms: 1.60x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.34 ms: 1.60x faster                                                  |
| async_tree_none          | 732 ms                                                 | 462 ms: 1.59x faster                                                   |
| richards                 | 79.4 ms                                                | 50.5 ms: 1.57x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 307 us: 1.57x faster                                                   |
| coroutines               | 34.5 ms                                                | 22.4 ms: 1.54x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.53x faster                                                  |
| deltablue                | 7.81 ms                                                | 5.11 ms: 1.53x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 590 ms: 1.47x faster                                                   |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 86.9 ms: 1.46x faster                                                  |
| async_tree_io            | 1.79 sec                                               | 1.23 sec: 1.46x faster                                                 |
| chaos                    | 114 ms                                                 | 78.6 ms: 1.45x faster                                                  |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.44x faster                                                   |
| go                       | 238 ms                                                 | 166 ms: 1.43x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                                 |
| deepcopy_memo            | 58.8 us                                                | 41.6 us: 1.41x faster                                                  |
| scimark_monte_carlo      | 118 ms                                                 | 84.7 ms: 1.39x faster                                                  |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 730 ms: 1.38x faster                                                   |
| logging_simple           | 8.27 us                                                | 6.10 us: 1.36x faster                                                  |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                                  |
| unpickle_pure_python     | 327 us                                                 | 242 us: 1.35x faster                                                   |
| deepcopy                 | 481 us                                                 | 357 us: 1.35x faster                                                   |
| chameleon                | 9.84 ms                                                | 7.34 ms: 1.34x faster                                                  |
| logging_format           | 9.07 us                                                | 6.82 us: 1.33x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 60.5 ms: 1.32x faster                                                  |
| pyflate                  | 708 ms                                                 | 538 ms: 1.32x faster                                                   |
| sqlglot_normalize        | 141 ms                                                 | 108 ms: 1.32x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.17 us: 1.32x faster                                                  |
| tornado_http             | 131 ms                                                 | 99.6 ms: 1.31x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.31x faster                                                 |
| sqlglot_optimize         | 68.7 ms                                                | 54.7 ms: 1.26x faster                                                  |
| mypy2                    | 442 ms                                                 | 354 ms: 1.25x faster                                                   |
| sympy_sum                | 190 ms                                                 | 154 ms: 1.23x faster                                                   |
| pprint_safe_repr         | 1.01 sec                                               | 825 ms: 1.23x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.73 sec: 1.21x faster                                                 |
| docutils                 | 3.26 sec                                               | 2.70 sec: 1.21x faster                                                 |
| comprehensions           | 28.5 us                                                | 23.7 us: 1.20x faster                                                  |
| 2to3                     | 346 ms                                                 | 289 ms: 1.20x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 21.3 ms: 1.19x faster                                                  |
| sympy_str                | 337 ms                                                 | 283 ms: 1.19x faster                                                   |
| dask                     | 432 ms                                                 | 367 ms: 1.18x faster                                                   |
| sympy_expand             | 558 ms                                                 | 476 ms: 1.17x faster                                                   |
| unpack_sequence          | 65.7 ns                                                | 56.4 ns: 1.17x faster                                                  |
| regex_compile            | 186 ms                                                 | 160 ms: 1.16x faster                                                   |
| bench_thread_pool        | 966 us                                                 | 852 us: 1.13x faster                                                   |
| nbody                    | 148 ms                                                 | 131 ms: 1.13x faster                                                   |
| float                    | 116 ms                                                 | 103 ms: 1.13x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 88.7 ms: 1.13x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 68.5 ms: 1.12x faster                                                  |
| fannkuch                 | 527 ms                                                 | 473 ms: 1.11x faster                                                   |
| json_loads               | 31.4 us                                                | 28.3 us: 1.11x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.77 sec: 1.10x faster                                                 |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                  |
| hexiom                   | 10.3 ms                                                | 9.38 ms: 1.10x faster                                                  |
| json                     | 5.67 ms                                                | 5.19 ms: 1.09x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.69 sec: 1.09x faster                                                 |
| pathlib                  | 20.3 ms                                                | 18.7 ms: 1.09x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                                   |
| regex_v8                 | 26.2 ms                                                | 24.3 ms: 1.08x faster                                                  |
| sqlite_synth             | 3.02 us                                                | 2.88 us: 1.05x faster                                                  |
| nqueens                  | 107 ms                                                 | 102 ms: 1.05x faster                                                   |
| xml_etree_iterparse      | 116 ms                                                 | 111 ms: 1.05x faster                                                   |
| mako                     | 16.3 ms                                                | 15.6 ms: 1.04x faster                                                  |
| meteor_contest           | 119 ms                                                 | 117 ms: 1.02x faster                                                   |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                   |
| regex_dna                | 215 ms                                                 | 221 ms: 1.03x slower                                                   |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.32 ms: 1.04x slower                                                  |
| async_generators         | 442 ms                                                 | 458 ms: 1.04x slower                                                   |
| scimark_fft              | 454 ms                                                 | 476 ms: 1.05x slower                                                   |
| regex_effbot             | 3.41 ms                                                | 3.59 ms: 1.05x slower                                                  |
| pickle                   | 10.7 us                                                | 11.3 us: 1.06x slower                                                  |
| coverage                 | 82.0 ms                                                | 93.7 ms: 1.14x slower                                                  |
| pickle_dict              | 30.0 us                                                | 34.5 us: 1.15x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 4.16 ms: 1.21x slower                                                  |
| telco                    | 7.01 ms                                                | 8.83 ms: 1.26x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.01 ms: 1.53x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                           |

Benchmark hidden because not significant (4): bench_mp_pool, unpickle, unpickle_list, pickle_list
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-eb3c94e-PYTHON_UOPS/bm-20231117-linux-x86_64-python-eb3c94ea669561a0dfac-3.13.0a1+-eb3c94e.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
