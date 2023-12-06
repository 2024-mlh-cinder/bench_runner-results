
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_os
- machine: windows-amd64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                                |
| tornado_http   | 91.8 ms                                                     | 92.9 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                       | 1.04x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                                  |
| float          | 54.6 ms                                                     | 55.6 ms: 1.02x slower                                                 |
| nbody          | 70.0 ms                                                     | 87.3 ms: 1.25x slower                                                 |
| Geometric mean | (ref)                                                       | 1.09x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 124 ms: 1.08x slower                                                  |
| regex_compile  | 90.6 ms                                                     | 99.7 ms: 1.10x slower                                                 |
| regex_effbot   | 1.50 ms                                                     | 1.67 ms: 1.12x slower                                                 |
| regex_v8       | 13.8 ms                                                     | 18.8 ms: 1.36x slower                                                 |
| Geometric mean | (ref)                                                       | 1.16x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 6.11 ms: 1.24x faster                                                 |
| xml_etree_parse      | 95.9 ms                                                     | 92.6 ms: 1.04x faster                                                 |
| unpickle_list        | 2.55 us                                                     | 2.67 us: 1.05x slower                                                 |
| tomli_loads          | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                                |
| json_loads           | 12.9 us                                                     | 13.7 us: 1.06x slower                                                 |
| pickle               | 6.61 us                                                     | 7.08 us: 1.07x slower                                                 |
| pickle_list          | 2.68 us                                                     | 2.88 us: 1.07x slower                                                 |
| xml_etree_iterparse  | 62.6 ms                                                     | 67.8 ms: 1.08x slower                                                 |
| pickle_pure_python   | 200 us                                                      | 227 us: 1.14x slower                                                  |
| unpickle_pure_python | 152 us                                                      | 173 us: 1.14x slower                                                  |
| xml_etree_generate   | 52.2 ms                                                     | 62.3 ms: 1.19x slower                                                 |
| xml_etree_process    | 37.1 ms                                                     | 44.7 ms: 1.21x slower                                                 |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                          |

Benchmark hidden because not significant (2): unpickle, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.0 ms: 1.01x slower                                                 |
| python_startup         | 18.7 ms                                                     | 19.5 ms: 1.04x slower                                                 |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.74 ms: 1.08x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 103 us: 3.13x faster                                                  |
| asyncio_tcp              | 699 ms                                                      | 488 ms: 1.43x faster                                                  |
| json_dumps               | 7.56 ms                                                     | 6.11 ms: 1.24x faster                                                 |
| coverage                 | 55.9 ms                                                     | 45.5 ms: 1.23x faster                                                 |
| async_tree_none          | 320 ms                                                      | 287 ms: 1.11x faster                                                  |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.91 sec: 1.11x faster                                                |
| mdp                      | 1.67 sec                                                    | 1.53 sec: 1.09x faster                                                |
| json                     | 3.25 ms                                                     | 2.97 ms: 1.09x faster                                                 |
| mako                     | 7.26 ms                                                     | 6.74 ms: 1.08x faster                                                 |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 477 ms: 1.05x faster                                                  |
| xml_etree_parse          | 95.9 ms                                                     | 92.6 ms: 1.04x faster                                                 |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.52 ms: 1.02x faster                                                 |
| mypy2                    | 229 ms                                                      | 230 ms: 1.01x slower                                                  |
| python_startup_no_site   | 15.9 ms                                                     | 16.0 ms: 1.01x slower                                                 |
| raytrace                 | 211 ms                                                      | 213 ms: 1.01x slower                                                  |
| tornado_http             | 91.8 ms                                                     | 92.9 ms: 1.01x slower                                                 |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                                  |
| float                    | 54.6 ms                                                     | 55.6 ms: 1.02x slower                                                 |
| sqlite_synth             | 1.68 us                                                     | 1.71 us: 1.02x slower                                                 |
| gc_traversal             | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                                 |
| bench_thread_pool        | 852 us                                                      | 879 us: 1.03x slower                                                  |
| nqueens                  | 64.9 ms                                                     | 67.0 ms: 1.03x slower                                                 |
| dulwich_log              | 44.5 ms                                                     | 46.1 ms: 1.04x slower                                                 |
| sqlglot_parse            | 952 us                                                      | 990 us: 1.04x slower                                                  |
| python_startup           | 18.7 ms                                                     | 19.5 ms: 1.04x slower                                                 |
| richards_super           | 37.5 ms                                                     | 39.2 ms: 1.05x slower                                                 |
| create_gc_cycles         | 693 us                                                      | 725 us: 1.05x slower                                                  |
| unpickle_list            | 2.55 us                                                     | 2.67 us: 1.05x slower                                                 |
| comprehensions           | 15.9 us                                                     | 16.7 us: 1.05x slower                                                 |
| sqlglot_transpile        | 1.16 ms                                                     | 1.23 ms: 1.05x slower                                                 |
| chaos                    | 47.1 ms                                                     | 49.7 ms: 1.06x slower                                                 |
| bench_mp_pool            | 62.5 ms                                                     | 66.0 ms: 1.06x slower                                                 |
| tomli_loads              | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                                |
| json_loads               | 12.9 us                                                     | 13.7 us: 1.06x slower                                                 |
| unpack_sequence          | 46.1 ns                                                     | 48.8 ns: 1.06x slower                                                 |
| docutils                 | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                                |
| crypto_pyaes             | 47.6 ms                                                     | 50.9 ms: 1.07x slower                                                 |
| pickle                   | 6.61 us                                                     | 7.08 us: 1.07x slower                                                 |
| logging_simple           | 6.61 us                                                     | 7.09 us: 1.07x slower                                                 |
| pickle_list              | 2.68 us                                                     | 2.88 us: 1.07x slower                                                 |
| logging_format           | 7.01 us                                                     | 7.53 us: 1.07x slower                                                 |
| meteor_contest           | 74.7 ms                                                     | 80.3 ms: 1.07x slower                                                 |
| regex_dna                | 115 ms                                                      | 124 ms: 1.08x slower                                                  |
| fannkuch                 | 252 ms                                                      | 272 ms: 1.08x slower                                                  |
| xml_etree_iterparse      | 62.6 ms                                                     | 67.8 ms: 1.08x slower                                                 |
| sqlglot_normalize        | 190 ms                                                      | 209 ms: 1.10x slower                                                  |
| deltablue                | 2.61 ms                                                     | 2.86 ms: 1.10x slower                                                 |
| regex_compile            | 90.6 ms                                                     | 99.7 ms: 1.10x slower                                                 |
| pathlib                  | 71.4 ms                                                     | 79.1 ms: 1.11x slower                                                 |
| sqlglot_optimize         | 34.9 ms                                                     | 39.0 ms: 1.12x slower                                                 |
| deepcopy                 | 246 us                                                      | 275 us: 1.12x slower                                                  |
| regex_effbot             | 1.50 ms                                                     | 1.67 ms: 1.12x slower                                                 |
| hexiom                   | 4.55 ms                                                     | 5.13 ms: 1.13x slower                                                 |
| pyflate                  | 304 ms                                                      | 343 ms: 1.13x slower                                                  |
| pycparser                | 691 ms                                                      | 780 ms: 1.13x slower                                                  |
| pickle_pure_python       | 200 us                                                      | 227 us: 1.14x slower                                                  |
| deepcopy_reduce          | 2.07 us                                                     | 2.36 us: 1.14x slower                                                 |
| unpickle_pure_python     | 152 us                                                      | 173 us: 1.14x slower                                                  |
| scimark_fft              | 178 ms                                                      | 205 ms: 1.15x slower                                                  |
| go                       | 97.3 ms                                                     | 113 ms: 1.16x slower                                                  |
| pprint_pformat           | 1.04 sec                                                    | 1.21 sec: 1.16x slower                                                |
| pprint_safe_repr         | 512 ms                                                      | 594 ms: 1.16x slower                                                  |
| scimark_monte_carlo      | 44.6 ms                                                     | 52.0 ms: 1.16x slower                                                 |
| richards                 | 30.6 ms                                                     | 35.7 ms: 1.17x slower                                                 |
| spectral_norm            | 67.9 ms                                                     | 80.2 ms: 1.18x slower                                                 |
| scimark_lu               | 63.5 ms                                                     | 75.0 ms: 1.18x slower                                                 |
| xml_etree_generate       | 52.2 ms                                                     | 62.3 ms: 1.19x slower                                                 |
| xml_etree_process        | 37.1 ms                                                     | 44.7 ms: 1.21x slower                                                 |
| telco                    | 3.90 ms                                                     | 4.84 ms: 1.24x slower                                                 |
| deepcopy_memo            | 25.2 us                                                     | 31.4 us: 1.25x slower                                                 |
| nbody                    | 70.0 ms                                                     | 87.3 ms: 1.25x slower                                                 |
| coroutines               | 14.6 ms                                                     | 18.8 ms: 1.28x slower                                                 |
| logging_silent           | 69.8 ns                                                     | 92.7 ns: 1.33x slower                                                 |
| regex_v8                 | 13.8 ms                                                     | 18.8 ms: 1.36x slower                                                 |
| scimark_sor              | 75.6 ms                                                     | 103 ms: 1.37x slower                                                  |
| async_generators         | 178 ms                                                      | 270 ms: 1.52x slower                                                  |
| Geometric mean           | (ref)                                                       | 1.05x slower                                                          |

Benchmark hidden because not significant (5): async_tree_memoization, async_tree_io, unpickle, generators, pickle_dict
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
