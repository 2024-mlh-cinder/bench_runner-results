
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                             |
| Geometric mean | (ref)                                                       | 1.03x slower                                                       |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 70.0 ms                                                     | 59.1 ms: 1.18x faster                                              |
| pidigits       | 148 ms                                                      | 152 ms: 1.03x slower                                               |
| float          | 54.6 ms                                                     | 65.9 ms: 1.21x slower                                              |
| Geometric mean | (ref)                                                       | 1.02x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 118 ms: 1.02x slower                                               |
| regex_effbot   | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                              |
| regex_v8       | 13.8 ms                                                     | 15.1 ms: 1.09x slower                                              |
| regex_compile  | 90.6 ms                                                     | 102 ms: 1.12x slower                                               |
| Geometric mean | (ref)                                                       | 1.07x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 6.06 ms: 1.25x faster                                              |
| xml_etree_parse      | 95.9 ms                                                     | 93.6 ms: 1.02x faster                                              |
| unpickle             | 8.09 us                                                     | 8.33 us: 1.03x slower                                              |
| json_loads           | 12.9 us                                                     | 13.8 us: 1.07x slower                                              |
| pickle               | 6.61 us                                                     | 7.16 us: 1.08x slower                                              |
| unpickle_list        | 2.55 us                                                     | 2.79 us: 1.09x slower                                              |
| pickle_pure_python   | 200 us                                                      | 223 us: 1.11x slower                                               |
| unpickle_pure_python | 152 us                                                      | 171 us: 1.13x slower                                               |
| xml_etree_iterparse  | 62.6 ms                                                     | 72.0 ms: 1.15x slower                                              |
| xml_etree_generate   | 52.2 ms                                                     | 62.1 ms: 1.19x slower                                              |
| xml_etree_process    | 37.1 ms                                                     | 44.8 ms: 1.21x slower                                              |
| pickle_list          | 2.68 us                                                     | 3.40 us: 1.27x slower                                              |
| Geometric mean       | (ref)                                                       | 1.07x slower                                                       |

Benchmark hidden because not significant (2): pickle_dict, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.4 ms: 1.04x slower                                              |
| python_startup         | 18.7 ms                                                     | 20.1 ms: 1.07x slower                                              |
| Geometric mean         | (ref)                                                       | 1.05x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.80 ms: 1.07x slower                                              |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 104 us: 3.10x faster                                               |
| asyncio_tcp              | 699 ms                                                      | 483 ms: 1.45x faster                                               |
| json_dumps               | 7.56 ms                                                     | 6.06 ms: 1.25x faster                                              |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.70 sec: 1.24x faster                                             |
| nbody                    | 70.0 ms                                                     | 59.1 ms: 1.18x faster                                              |
| mdp                      | 1.67 sec                                                    | 1.45 sec: 1.15x faster                                             |
| coverage                 | 55.9 ms                                                     | 48.9 ms: 1.14x faster                                              |
| json                     | 3.25 ms                                                     | 2.96 ms: 1.10x faster                                              |
| async_tree_none          | 320 ms                                                      | 294 ms: 1.09x faster                                               |
| xml_etree_parse          | 95.9 ms                                                     | 93.6 ms: 1.02x faster                                              |
| generators               | 33.8 ms                                                     | 33.3 ms: 1.01x faster                                              |
| mypy2                    | 229 ms                                                      | 233 ms: 1.02x slower                                               |
| regex_dna                | 115 ms                                                      | 118 ms: 1.02x slower                                               |
| nqueens                  | 64.9 ms                                                     | 66.4 ms: 1.02x slower                                              |
| raytrace                 | 211 ms                                                      | 216 ms: 1.02x slower                                               |
| pidigits                 | 148 ms                                                      | 152 ms: 1.03x slower                                               |
| unpickle                 | 8.09 us                                                     | 8.33 us: 1.03x slower                                              |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.04x slower                                              |
| python_startup_no_site   | 15.9 ms                                                     | 16.4 ms: 1.04x slower                                              |
| dulwich_log              | 44.5 ms                                                     | 46.2 ms: 1.04x slower                                              |
| bench_thread_pool        | 852 us                                                      | 886 us: 1.04x slower                                               |
| unpack_sequence          | 46.1 ns                                                     | 47.9 ns: 1.04x slower                                              |
| comprehensions           | 15.9 us                                                     | 16.6 us: 1.04x slower                                              |
| scimark_fft              | 178 ms                                                      | 186 ms: 1.04x slower                                               |
| crypto_pyaes             | 47.6 ms                                                     | 49.6 ms: 1.04x slower                                              |
| sqlglot_parse            | 952 us                                                      | 996 us: 1.05x slower                                               |
| chaos                    | 47.1 ms                                                     | 49.3 ms: 1.05x slower                                              |
| create_gc_cycles         | 693 us                                                      | 725 us: 1.05x slower                                               |
| meteor_contest           | 74.7 ms                                                     | 78.2 ms: 1.05x slower                                              |
| fannkuch                 | 252 ms                                                      | 264 ms: 1.05x slower                                               |
| regex_effbot             | 1.50 ms                                                     | 1.58 ms: 1.06x slower                                              |
| sqlite_synth             | 1.68 us                                                     | 1.78 us: 1.06x slower                                              |
| docutils                 | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                             |
| sqlglot_transpile        | 1.16 ms                                                     | 1.24 ms: 1.07x slower                                              |
| richards_super           | 37.5 ms                                                     | 40.1 ms: 1.07x slower                                              |
| json_loads               | 12.9 us                                                     | 13.8 us: 1.07x slower                                              |
| logging_simple           | 6.61 us                                                     | 7.10 us: 1.07x slower                                              |
| mako                     | 7.26 ms                                                     | 7.80 ms: 1.07x slower                                              |
| python_startup           | 18.7 ms                                                     | 20.1 ms: 1.07x slower                                              |
| logging_format           | 7.01 us                                                     | 7.59 us: 1.08x slower                                              |
| pickle                   | 6.61 us                                                     | 7.16 us: 1.08x slower                                              |
| regex_v8                 | 13.8 ms                                                     | 15.1 ms: 1.09x slower                                              |
| unpickle_list            | 2.55 us                                                     | 2.79 us: 1.09x slower                                              |
| sqlglot_normalize        | 190 ms                                                      | 210 ms: 1.10x slower                                               |
| deepcopy                 | 246 us                                                      | 273 us: 1.11x slower                                               |
| pickle_pure_python       | 200 us                                                      | 223 us: 1.11x slower                                               |
| pathlib                  | 71.4 ms                                                     | 79.5 ms: 1.11x slower                                              |
| deltablue                | 2.61 ms                                                     | 2.92 ms: 1.12x slower                                              |
| sqlglot_optimize         | 34.9 ms                                                     | 39.1 ms: 1.12x slower                                              |
| regex_compile            | 90.6 ms                                                     | 102 ms: 1.12x slower                                               |
| unpickle_pure_python     | 152 us                                                      | 171 us: 1.13x slower                                               |
| bench_mp_pool            | 62.5 ms                                                     | 70.6 ms: 1.13x slower                                              |
| hexiom                   | 4.55 ms                                                     | 5.18 ms: 1.14x slower                                              |
| pyflate                  | 304 ms                                                      | 347 ms: 1.14x slower                                               |
| xml_etree_iterparse      | 62.6 ms                                                     | 72.0 ms: 1.15x slower                                              |
| deepcopy_reduce          | 2.07 us                                                     | 2.39 us: 1.15x slower                                              |
| go                       | 97.3 ms                                                     | 113 ms: 1.16x slower                                               |
| pprint_safe_repr         | 512 ms                                                      | 597 ms: 1.17x slower                                               |
| richards                 | 30.6 ms                                                     | 35.9 ms: 1.18x slower                                              |
| scimark_monte_carlo      | 44.6 ms                                                     | 52.5 ms: 1.18x slower                                              |
| pprint_pformat           | 1.04 sec                                                    | 1.23 sec: 1.18x slower                                             |
| spectral_norm            | 67.9 ms                                                     | 80.3 ms: 1.18x slower                                              |
| xml_etree_generate       | 52.2 ms                                                     | 62.1 ms: 1.19x slower                                              |
| pycparser                | 691 ms                                                      | 825 ms: 1.19x slower                                               |
| float                    | 54.6 ms                                                     | 65.9 ms: 1.21x slower                                              |
| deepcopy_memo            | 25.2 us                                                     | 30.4 us: 1.21x slower                                              |
| xml_etree_process        | 37.1 ms                                                     | 44.8 ms: 1.21x slower                                              |
| scimark_lu               | 63.5 ms                                                     | 76.9 ms: 1.21x slower                                              |
| pickle_list              | 2.68 us                                                     | 3.40 us: 1.27x slower                                              |
| telco                    | 3.90 ms                                                     | 4.98 ms: 1.28x slower                                              |
| coroutines               | 14.6 ms                                                     | 18.8 ms: 1.28x slower                                              |
| logging_silent           | 69.8 ns                                                     | 91.9 ns: 1.32x slower                                              |
| scimark_sor              | 75.6 ms                                                     | 103 ms: 1.36x slower                                               |
| async_generators         | 178 ms                                                      | 274 ms: 1.54x slower                                               |
| dask                     | 264 ms                                                      | 409 ms: 1.55x slower                                               |
| Geometric mean           | (ref)                                                       | 1.06x slower                                                       |

Benchmark hidden because not significant (7): pickle_dict, async_tree_cpu_io_mixed, tornado_http, async_tree_memoization, async_tree_io, tomli_loads, scimark_sparse_mat_mult
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
