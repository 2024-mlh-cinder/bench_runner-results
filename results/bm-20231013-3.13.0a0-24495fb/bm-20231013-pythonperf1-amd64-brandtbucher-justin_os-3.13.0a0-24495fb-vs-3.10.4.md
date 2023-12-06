
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_os
- machine: windows-amd64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.06x faster
- HPT reliability: 97.03%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                                |
| tornado_http   | 109 ms                                                      | 92.9 ms: 1.17x faster                                                 |
| Geometric mean | (ref)                                                       | 1.14x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.6 ms: 1.08x faster                                                 |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                                  |
| nbody          | 69.3 ms                                                     | 87.3 ms: 1.26x slower                                                 |
| Geometric mean | (ref)                                                       | 1.06x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 124 ms: 1.06x faster                                                  |
| regex_compile  | 103 ms                                                      | 99.7 ms: 1.04x faster                                                 |
| regex_effbot   | 1.66 ms                                                     | 1.67 ms: 1.01x slower                                                 |
| regex_v8       | 15.0 ms                                                     | 18.8 ms: 1.25x slower                                                 |
| Geometric mean | (ref)                                                       | 1.03x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 6.11 ms: 1.39x faster                                                 |
| unpickle             | 9.17 us                                                     | 8.10 us: 1.13x faster                                                 |
| pickle_pure_python   | 257 us                                                      | 227 us: 1.13x faster                                                  |
| xml_etree_parse      | 102 ms                                                      | 92.6 ms: 1.10x faster                                                 |
| tomli_loads          | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                                |
| unpickle_list        | 2.81 us                                                     | 2.67 us: 1.05x faster                                                 |
| json_loads           | 14.2 us                                                     | 13.7 us: 1.04x faster                                                 |
| unpickle_pure_python | 171 us                                                      | 173 us: 1.01x slower                                                  |
| xml_etree_process    | 43.4 ms                                                     | 44.7 ms: 1.03x slower                                                 |
| pickle               | 6.80 us                                                     | 7.08 us: 1.04x slower                                                 |
| xml_etree_iterparse  | 63.5 ms                                                     | 67.8 ms: 1.07x slower                                                 |
| pickle_list          | 2.59 us                                                     | 2.88 us: 1.11x slower                                                 |
| pickle_dict          | 16.9 us                                                     | 18.8 us: 1.11x slower                                                 |
| xml_etree_generate   | 54.5 ms                                                     | 62.3 ms: 1.14x slower                                                 |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.5 ms: 1.03x faster                                                 |
| python_startup_no_site | 15.5 ms                                                     | 16.0 ms: 1.03x slower                                                 |
| Geometric mean         | (ref)                                                       | 1.00x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.74 ms: 1.31x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 103 us: 3.16x faster                                                  |
| mypy2                    | 352 ms                                                      | 230 ms: 1.53x faster                                                  |
| async_tree_none          | 420 ms                                                      | 287 ms: 1.46x faster                                                  |
| asyncio_tcp              | 712 ms                                                      | 488 ms: 1.46x faster                                                  |
| deltablue                | 4.17 ms                                                     | 2.86 ms: 1.46x faster                                                 |
| json_dumps               | 8.50 ms                                                     | 6.11 ms: 1.39x faster                                                 |
| async_tree_io            | 1.07 sec                                                    | 773 ms: 1.38x faster                                                  |
| async_tree_memoization   | 497 ms                                                      | 368 ms: 1.35x faster                                                  |
| richards_super           | 51.7 ms                                                     | 39.2 ms: 1.32x faster                                                 |
| mako                     | 8.80 ms                                                     | 6.74 ms: 1.31x faster                                                 |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 477 ms: 1.28x faster                                                  |
| raytrace                 | 271 ms                                                      | 213 ms: 1.27x faster                                                  |
| sqlglot_parse            | 1.22 ms                                                     | 990 us: 1.23x faster                                                  |
| crypto_pyaes             | 62.3 ms                                                     | 50.9 ms: 1.23x faster                                                 |
| go                       | 136 ms                                                      | 113 ms: 1.21x faster                                                  |
| sqlglot_transpile        | 1.46 ms                                                     | 1.23 ms: 1.19x faster                                                 |
| chaos                    | 58.9 ms                                                     | 49.7 ms: 1.18x faster                                                 |
| tornado_http             | 109 ms                                                      | 92.9 ms: 1.17x faster                                                 |
| richards                 | 41.2 ms                                                     | 35.7 ms: 1.15x faster                                                 |
| scimark_lu               | 85.4 ms                                                     | 75.0 ms: 1.14x faster                                                 |
| unpickle                 | 9.17 us                                                     | 8.10 us: 1.13x faster                                                 |
| pickle_pure_python       | 257 us                                                      | 227 us: 1.13x faster                                                  |
| pyflate                  | 387 ms                                                      | 343 ms: 1.13x faster                                                  |
| mdp                      | 1.71 sec                                                    | 1.53 sec: 1.12x faster                                                |
| docutils                 | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                                |
| pycparser                | 868 ms                                                      | 780 ms: 1.11x faster                                                  |
| xml_etree_parse          | 102 ms                                                      | 92.6 ms: 1.10x faster                                                 |
| tomli_loads              | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                                |
| float                    | 60.2 ms                                                     | 55.6 ms: 1.08x faster                                                 |
| create_gc_cycles         | 782 us                                                      | 725 us: 1.08x faster                                                  |
| bench_thread_pool        | 946 us                                                      | 879 us: 1.08x faster                                                  |
| hexiom                   | 5.52 ms                                                     | 5.13 ms: 1.07x faster                                                 |
| scimark_monte_carlo      | 55.9 ms                                                     | 52.0 ms: 1.07x faster                                                 |
| sqlite_synth             | 1.84 us                                                     | 1.71 us: 1.07x faster                                                 |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.91 sec: 1.07x faster                                                |
| regex_dna                | 132 ms                                                      | 124 ms: 1.06x faster                                                  |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.52 ms: 1.05x faster                                                 |
| unpickle_list            | 2.81 us                                                     | 2.67 us: 1.05x faster                                                 |
| logging_silent           | 96.4 ns                                                     | 92.7 ns: 1.04x faster                                                 |
| regex_compile            | 103 ms                                                      | 99.7 ms: 1.04x faster                                                 |
| json_loads               | 14.2 us                                                     | 13.7 us: 1.04x faster                                                 |
| dulwich_log              | 47.6 ms                                                     | 46.1 ms: 1.03x faster                                                 |
| python_startup           | 20.0 ms                                                     | 19.5 ms: 1.03x faster                                                 |
| json                     | 3.05 ms                                                     | 2.97 ms: 1.02x faster                                                 |
| scimark_sor              | 105 ms                                                      | 103 ms: 1.01x faster                                                  |
| regex_effbot             | 1.66 ms                                                     | 1.67 ms: 1.01x slower                                                 |
| pprint_safe_repr         | 589 ms                                                      | 594 ms: 1.01x slower                                                  |
| unpickle_pure_python     | 171 us                                                      | 173 us: 1.01x slower                                                  |
| pathlib                  | 77.4 ms                                                     | 79.1 ms: 1.02x slower                                                 |
| xml_etree_process        | 43.4 ms                                                     | 44.7 ms: 1.03x slower                                                 |
| spectral_norm            | 78.0 ms                                                     | 80.2 ms: 1.03x slower                                                 |
| sqlglot_normalize        | 202 ms                                                      | 209 ms: 1.03x slower                                                  |
| python_startup_no_site   | 15.5 ms                                                     | 16.0 ms: 1.03x slower                                                 |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                                  |
| pickle                   | 6.80 us                                                     | 7.08 us: 1.04x slower                                                 |
| comprehensions           | 16.0 us                                                     | 16.7 us: 1.05x slower                                                 |
| fannkuch                 | 258 ms                                                      | 272 ms: 1.05x slower                                                  |
| scimark_fft              | 193 ms                                                      | 205 ms: 1.06x slower                                                  |
| xml_etree_iterparse      | 63.5 ms                                                     | 67.8 ms: 1.07x slower                                                 |
| deepcopy                 | 255 us                                                      | 275 us: 1.08x slower                                                  |
| generators               | 31.6 ms                                                     | 34.0 ms: 1.08x slower                                                 |
| bench_mp_pool            | 60.7 ms                                                     | 66.0 ms: 1.09x slower                                                 |
| deepcopy_reduce          | 2.16 us                                                     | 2.36 us: 1.10x slower                                                 |
| deepcopy_memo            | 28.5 us                                                     | 31.4 us: 1.10x slower                                                 |
| meteor_contest           | 72.5 ms                                                     | 80.3 ms: 1.11x slower                                                 |
| pickle_list              | 2.59 us                                                     | 2.88 us: 1.11x slower                                                 |
| gc_traversal             | 1.34 ms                                                     | 1.50 ms: 1.11x slower                                                 |
| pickle_dict              | 16.9 us                                                     | 18.8 us: 1.11x slower                                                 |
| logging_format           | 6.66 us                                                     | 7.53 us: 1.13x slower                                                 |
| coverage                 | 40.0 ms                                                     | 45.5 ms: 1.14x slower                                                 |
| xml_etree_generate       | 54.5 ms                                                     | 62.3 ms: 1.14x slower                                                 |
| logging_simple           | 6.20 us                                                     | 7.09 us: 1.14x slower                                                 |
| coroutines               | 15.9 ms                                                     | 18.8 ms: 1.18x slower                                                 |
| async_generators         | 224 ms                                                      | 270 ms: 1.21x slower                                                  |
| regex_v8                 | 15.0 ms                                                     | 18.8 ms: 1.25x slower                                                 |
| nbody                    | 69.3 ms                                                     | 87.3 ms: 1.26x slower                                                 |
| telco                    | 3.78 ms                                                     | 4.84 ms: 1.28x slower                                                 |
| unpack_sequence          | 37.8 ns                                                     | 48.8 ns: 1.29x slower                                                 |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                          |

Benchmark hidden because not significant (3): pprint_pformat, nqueens, sqlglot_optimize
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.03% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
