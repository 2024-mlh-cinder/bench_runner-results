
# Results vs. base

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 30e5f4b
- commit date: 2023-11-04
- overall geometric mean: 1.00x faster
- HPT reliability: 51.09%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| 2to3           | 290 ms                                                                       | 292 ms: 1.01x slower                                                                   |
| chameleon      | 7.24 ms                                                                      | 7.41 ms: 1.02x slower                                                                  |
| docutils       | 2.82 sec                                                                     | 2.82 sec: 1.00x faster                                                                 |
| Geometric mean | (ref)                                                                        | 1.01x slower                                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|--------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| async_tree_none_tg | 444 ms                                                                       | 440 ms: 1.01x faster                                                                   |
| async_tree_io      | 1.08 sec                                                                     | 1.07 sec: 1.01x faster                                                                 |
| async_tree_io_tg   | 1.10 sec                                                                     | 1.09 sec: 1.01x faster                                                                 |
| Geometric mean     | (ref)                                                                        | 1.00x faster                                                                           |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| nbody          | 85.0 ms                                                                      | 83.7 ms: 1.02x faster                                                                  |
| pidigits       | 265 ms                                                                       | 264 ms: 1.00x faster                                                                   |
| float          | 79.1 ms                                                                      | 80.0 ms: 1.01x slower                                                                  |
| Geometric mean | (ref)                                                                        | 1.00x faster                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| regex_dna      | 253 ms                                                                       | 241 ms: 1.05x faster                                                                   |
| regex_effbot   | 3.61 ms                                                                      | 3.47 ms: 1.04x faster                                                                  |
| regex_v8       | 25.2 ms                                                                      | 24.4 ms: 1.03x faster                                                                  |
| regex_compile  | 146 ms                                                                       | 145 ms: 1.00x faster                                                                   |
| Geometric mean | (ref)                                                                        | 1.03x faster                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|----------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| unpickle_pure_python | 231 us                                                                       | 221 us: 1.05x faster                                                                   |
| unpickle             | 14.8 us                                                                      | 14.3 us: 1.03x faster                                                                  |
| tomli_loads          | 2.35 sec                                                                     | 2.29 sec: 1.02x faster                                                                 |
| xml_etree_generate   | 86.7 ms                                                                      | 85.0 ms: 1.02x faster                                                                  |
| unpickle_list        | 4.71 us                                                                      | 4.63 us: 1.02x faster                                                                  |
| xml_etree_process    | 58.7 ms                                                                      | 57.8 ms: 1.02x faster                                                                  |
| pickle_pure_python   | 310 us                                                                       | 307 us: 1.01x faster                                                                   |
| pickle               | 10.2 us                                                                      | 10.1 us: 1.01x faster                                                                  |
| pickle_dict          | 33.0 us                                                                      | 33.0 us: 1.00x faster                                                                  |
| json_dumps           | 10.3 ms                                                                      | 10.3 ms: 1.01x slower                                                                  |
| pickle_list          | 4.41 us                                                                      | 4.46 us: 1.01x slower                                                                  |
| xml_etree_parse      | 147 ms                                                                       | 151 ms: 1.03x slower                                                                   |
| xml_etree_iterparse  | 104 ms                                                                       | 108 ms: 1.03x slower                                                                   |
| Geometric mean       | (ref)                                                                        | 1.01x faster                                                                           |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| python_startup_no_site | 11.3 ms                                                                      | 11.3 ms: 1.00x slower                                                                  |
| python_startup         | 12.8 ms                                                                      | 12.8 ms: 1.00x slower                                                                  |
| Geometric mean         | (ref)                                                                        | 1.00x slower                                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|-----------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                      | 10.2 ms: 1.01x faster                                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231107-pythonperf2-x86_64-python-931f4438c92ec0eb2aa8-3.13.0a1+-931f443 | bm-20231104-pythonperf2-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-30e5f4b |
|--------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------------------------:|
| gc_traversal             | 3.78 ms                                                                      | 3.52 ms: 1.07x faster                                                                  |
| regex_dna                | 253 ms                                                                       | 241 ms: 1.05x faster                                                                   |
| unpickle_pure_python     | 231 us                                                                       | 221 us: 1.05x faster                                                                   |
| regex_effbot             | 3.61 ms                                                                      | 3.47 ms: 1.04x faster                                                                  |
| scimark_monte_carlo      | 69.2 ms                                                                      | 66.8 ms: 1.04x faster                                                                  |
| unpickle                 | 14.8 us                                                                      | 14.3 us: 1.03x faster                                                                  |
| fannkuch                 | 396 ms                                                                       | 384 ms: 1.03x faster                                                                   |
| regex_v8                 | 25.2 ms                                                                      | 24.4 ms: 1.03x faster                                                                  |
| mdp                      | 2.57 sec                                                                     | 2.50 sec: 1.03x faster                                                                 |
| generators               | 35.2 ms                                                                      | 34.3 ms: 1.03x faster                                                                  |
| tomli_loads              | 2.35 sec                                                                     | 2.29 sec: 1.02x faster                                                                 |
| xml_etree_generate       | 86.7 ms                                                                      | 85.0 ms: 1.02x faster                                                                  |
| unpickle_list            | 4.71 us                                                                      | 4.63 us: 1.02x faster                                                                  |
| logging_format           | 7.42 us                                                                      | 7.30 us: 1.02x faster                                                                  |
| nbody                    | 85.0 ms                                                                      | 83.7 ms: 1.02x faster                                                                  |
| xml_etree_process        | 58.7 ms                                                                      | 57.8 ms: 1.02x faster                                                                  |
| unpack_sequence          | 52.2 ns                                                                      | 51.5 ns: 1.01x faster                                                                  |
| crypto_pyaes             | 71.6 ms                                                                      | 70.7 ms: 1.01x faster                                                                  |
| nqueens                  | 88.9 ms                                                                      | 88.0 ms: 1.01x faster                                                                  |
| async_tree_none_tg       | 444 ms                                                                       | 440 ms: 1.01x faster                                                                   |
| pickle_pure_python       | 310 us                                                                       | 307 us: 1.01x faster                                                                   |
| mako                     | 10.2 ms                                                                      | 10.2 ms: 1.01x faster                                                                  |
| pathlib                  | 19.7 ms                                                                      | 19.5 ms: 1.01x faster                                                                  |
| async_tree_io            | 1.08 sec                                                                     | 1.07 sec: 1.01x faster                                                                 |
| hexiom                   | 6.46 ms                                                                      | 6.41 ms: 1.01x faster                                                                  |
| async_tree_io_tg         | 1.10 sec                                                                     | 1.09 sec: 1.01x faster                                                                 |
| pyflate                  | 505 ms                                                                       | 501 ms: 1.01x faster                                                                   |
| deepcopy                 | 365 us                                                                       | 362 us: 1.01x faster                                                                   |
| pickle                   | 10.2 us                                                                      | 10.1 us: 1.01x faster                                                                  |
| sqlite_synth             | 2.65 us                                                                      | 2.64 us: 1.01x faster                                                                  |
| pidigits                 | 265 ms                                                                       | 264 ms: 1.00x faster                                                                   |
| sympy_integrate          | 23.0 ms                                                                      | 22.9 ms: 1.00x faster                                                                  |
| regex_compile            | 146 ms                                                                       | 145 ms: 1.00x faster                                                                   |
| meteor_contest           | 129 ms                                                                       | 128 ms: 1.00x faster                                                                   |
| pickle_dict              | 33.0 us                                                                      | 33.0 us: 1.00x faster                                                                  |
| docutils                 | 2.82 sec                                                                     | 2.82 sec: 1.00x faster                                                                 |
| python_startup_no_site   | 11.3 ms                                                                      | 11.3 ms: 1.00x slower                                                                  |
| python_startup           | 12.8 ms                                                                      | 12.8 ms: 1.00x slower                                                                  |
| json_dumps               | 10.3 ms                                                                      | 10.3 ms: 1.01x slower                                                                  |
| json                     | 5.10 ms                                                                      | 5.13 ms: 1.01x slower                                                                  |
| comprehensions           | 16.3 us                                                                      | 16.4 us: 1.01x slower                                                                  |
| sympy_str                | 288 ms                                                                       | 289 ms: 1.01x slower                                                                   |
| pprint_safe_repr         | 792 ms                                                                       | 798 ms: 1.01x slower                                                                   |
| 2to3                     | 290 ms                                                                       | 292 ms: 1.01x slower                                                                   |
| sympy_sum                | 150 ms                                                                       | 151 ms: 1.01x slower                                                                   |
| deepcopy_reduce          | 3.24 us                                                                      | 3.27 us: 1.01x slower                                                                  |
| scimark_sor              | 146 ms                                                                       | 147 ms: 1.01x slower                                                                   |
| pprint_pformat           | 1.62 sec                                                                     | 1.63 sec: 1.01x slower                                                                 |
| coroutines               | 22.4 ms                                                                      | 22.6 ms: 1.01x slower                                                                  |
| async_generators         | 359 ms                                                                       | 363 ms: 1.01x slower                                                                   |
| richards                 | 53.2 ms                                                                      | 53.7 ms: 1.01x slower                                                                  |
| float                    | 79.1 ms                                                                      | 80.0 ms: 1.01x slower                                                                  |
| pickle_list              | 4.41 us                                                                      | 4.46 us: 1.01x slower                                                                  |
| mypy2                    | 364 ms                                                                       | 368 ms: 1.01x slower                                                                   |
| scimark_fft              | 300 ms                                                                       | 304 ms: 1.01x slower                                                                   |
| sqlglot_optimize         | 57.8 ms                                                                      | 58.5 ms: 1.01x slower                                                                  |
| go                       | 170 ms                                                                       | 172 ms: 1.01x slower                                                                   |
| typing_runtime_protocols | 121 us                                                                       | 122 us: 1.01x slower                                                                   |
| sqlglot_transpile        | 1.80 ms                                                                      | 1.83 ms: 1.02x slower                                                                  |
| deepcopy_memo            | 36.6 us                                                                      | 37.3 us: 1.02x slower                                                                  |
| sqlglot_parse            | 1.40 ms                                                                      | 1.42 ms: 1.02x slower                                                                  |
| richards_super           | 58.3 ms                                                                      | 59.4 ms: 1.02x slower                                                                  |
| sqlglot_normalize        | 114 ms                                                                       | 116 ms: 1.02x slower                                                                   |
| pycparser                | 1.28 sec                                                                     | 1.30 sec: 1.02x slower                                                                 |
| sympy_expand             | 485 ms                                                                       | 494 ms: 1.02x slower                                                                   |
| scimark_sparse_mat_mult  | 4.20 ms                                                                      | 4.29 ms: 1.02x slower                                                                  |
| create_gc_cycles         | 1.55 ms                                                                      | 1.58 ms: 1.02x slower                                                                  |
| chameleon                | 7.24 ms                                                                      | 7.41 ms: 1.02x slower                                                                  |
| deltablue                | 3.66 ms                                                                      | 3.76 ms: 1.03x slower                                                                  |
| scimark_lu               | 99.5 ms                                                                      | 102 ms: 1.03x slower                                                                   |
| xml_etree_parse          | 147 ms                                                                       | 151 ms: 1.03x slower                                                                   |
| xml_etree_iterparse      | 104 ms                                                                       | 108 ms: 1.03x slower                                                                   |
| Geometric mean           | (ref)                                                                        | 1.00x faster                                                                           |

Benchmark hidden because not significant (20): async_tree_cpu_io_mixed_tg, logging_simple, async_tree_none, asyncio_websockets, bench_thread_pool, async_tree_cpu_io_mixed, coverage, json_loads, spectral_norm, asyncio_tcp_ssl, telco, logging_silent, async_tree_memoization, raytrace, dulwich_log, chaos, asyncio_tcp, async_tree_memoization_tg, tornado_http, bench_mp_pool


# HPT report

- Reliability score: 51.09% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
