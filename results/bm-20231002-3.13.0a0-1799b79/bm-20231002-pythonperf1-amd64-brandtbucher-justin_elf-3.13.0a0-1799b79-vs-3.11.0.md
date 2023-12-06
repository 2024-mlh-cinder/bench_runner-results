
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_elf
- machine: windows-amd64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.06x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                                 |
| Geometric mean | (ref)                                                       | 1.03x slower                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                                   |
| nbody          | 70.0 ms                                                     | 73.8 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                       | 1.02x slower                                                           |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 121 ms: 1.05x slower                                                   |
| regex_effbot   | 1.50 ms                                                     | 1.62 ms: 1.08x slower                                                  |
| regex_compile  | 90.6 ms                                                     | 100 ms: 1.11x slower                                                   |
| regex_v8       | 13.8 ms                                                     | 17.2 ms: 1.24x slower                                                  |
| Geometric mean | (ref)                                                       | 1.12x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 6.01 ms: 1.26x faster                                                  |
| xml_etree_parse      | 95.9 ms                                                     | 93.9 ms: 1.02x faster                                                  |
| pickle_dict          | 18.5 us                                                     | 18.2 us: 1.02x faster                                                  |
| tomli_loads          | 1.41 sec                                                    | 1.43 sec: 1.01x slower                                                 |
| pickle_list          | 2.68 us                                                     | 2.84 us: 1.06x slower                                                  |
| unpickle             | 8.09 us                                                     | 8.62 us: 1.07x slower                                                  |
| unpickle_list        | 2.55 us                                                     | 2.73 us: 1.07x slower                                                  |
| pickle               | 6.61 us                                                     | 7.09 us: 1.07x slower                                                  |
| json_loads           | 12.9 us                                                     | 13.9 us: 1.08x slower                                                  |
| xml_etree_iterparse  | 62.6 ms                                                     | 68.3 ms: 1.09x slower                                                  |
| pickle_pure_python   | 200 us                                                      | 225 us: 1.12x slower                                                   |
| unpickle_pure_python | 152 us                                                      | 174 us: 1.14x slower                                                   |
| xml_etree_generate   | 52.2 ms                                                     | 62.7 ms: 1.20x slower                                                  |
| xml_etree_process    | 37.1 ms                                                     | 45.1 ms: 1.22x slower                                                  |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.3 ms: 1.03x slower                                                  |
| python_startup         | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                  |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.99 ms: 1.10x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 104 us: 3.11x faster                                                   |
| asyncio_tcp              | 699 ms                                                      | 488 ms: 1.43x faster                                                   |
| json_dumps               | 7.56 ms                                                     | 6.01 ms: 1.26x faster                                                  |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.73 sec: 1.22x faster                                                 |
| coverage                 | 55.9 ms                                                     | 47.2 ms: 1.18x faster                                                  |
| json                     | 3.25 ms                                                     | 2.95 ms: 1.10x faster                                                  |
| async_tree_none          | 320 ms                                                      | 292 ms: 1.10x faster                                                   |
| mdp                      | 1.67 sec                                                    | 1.54 sec: 1.09x faster                                                 |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.51 ms: 1.02x faster                                                  |
| xml_etree_parse          | 95.9 ms                                                     | 93.9 ms: 1.02x faster                                                  |
| pickle_dict              | 18.5 us                                                     | 18.2 us: 1.02x faster                                                  |
| mypy2                    | 229 ms                                                      | 230 ms: 1.01x slower                                                   |
| tomli_loads              | 1.41 sec                                                    | 1.43 sec: 1.01x slower                                                 |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                                   |
| raytrace                 | 211 ms                                                      | 216 ms: 1.02x slower                                                   |
| dulwich_log              | 44.5 ms                                                     | 45.8 ms: 1.03x slower                                                  |
| comprehensions           | 15.9 us                                                     | 16.4 us: 1.03x slower                                                  |
| python_startup_no_site   | 15.9 ms                                                     | 16.3 ms: 1.03x slower                                                  |
| bench_thread_pool        | 852 us                                                      | 878 us: 1.03x slower                                                   |
| sqlglot_parse            | 952 us                                                      | 983 us: 1.03x slower                                                   |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.03x slower                                                  |
| crypto_pyaes             | 47.6 ms                                                     | 49.2 ms: 1.04x slower                                                  |
| sqlglot_transpile        | 1.16 ms                                                     | 1.21 ms: 1.04x slower                                                  |
| unpack_sequence          | 46.1 ns                                                     | 48.0 ns: 1.04x slower                                                  |
| richards_super           | 37.5 ms                                                     | 39.2 ms: 1.05x slower                                                  |
| regex_dna                | 115 ms                                                      | 121 ms: 1.05x slower                                                   |
| nbody                    | 70.0 ms                                                     | 73.8 ms: 1.05x slower                                                  |
| pickle_list              | 2.68 us                                                     | 2.84 us: 1.06x slower                                                  |
| create_gc_cycles         | 693 us                                                      | 734 us: 1.06x slower                                                   |
| python_startup           | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                  |
| chaos                    | 47.1 ms                                                     | 50.0 ms: 1.06x slower                                                  |
| docutils                 | 1.60 sec                                                    | 1.70 sec: 1.06x slower                                                 |
| sqlite_synth             | 1.68 us                                                     | 1.79 us: 1.06x slower                                                  |
| unpickle                 | 8.09 us                                                     | 8.62 us: 1.07x slower                                                  |
| unpickle_list            | 2.55 us                                                     | 2.73 us: 1.07x slower                                                  |
| pickle                   | 6.61 us                                                     | 7.09 us: 1.07x slower                                                  |
| json_loads               | 12.9 us                                                     | 13.9 us: 1.08x slower                                                  |
| deltablue                | 2.61 ms                                                     | 2.81 ms: 1.08x slower                                                  |
| meteor_contest           | 74.7 ms                                                     | 80.5 ms: 1.08x slower                                                  |
| nqueens                  | 64.9 ms                                                     | 69.9 ms: 1.08x slower                                                  |
| logging_simple           | 6.61 us                                                     | 7.14 us: 1.08x slower                                                  |
| fannkuch                 | 252 ms                                                      | 273 ms: 1.08x slower                                                   |
| regex_effbot             | 1.50 ms                                                     | 1.62 ms: 1.08x slower                                                  |
| sqlglot_normalize        | 190 ms                                                      | 207 ms: 1.09x slower                                                   |
| bench_mp_pool            | 62.5 ms                                                     | 68.0 ms: 1.09x slower                                                  |
| logging_format           | 7.01 us                                                     | 7.64 us: 1.09x slower                                                  |
| xml_etree_iterparse      | 62.6 ms                                                     | 68.3 ms: 1.09x slower                                                  |
| pathlib                  | 71.4 ms                                                     | 78.2 ms: 1.10x slower                                                  |
| mako                     | 7.26 ms                                                     | 7.99 ms: 1.10x slower                                                  |
| regex_compile            | 90.6 ms                                                     | 100 ms: 1.11x slower                                                   |
| deepcopy                 | 246 us                                                      | 272 us: 1.11x slower                                                   |
| sqlglot_optimize         | 34.9 ms                                                     | 38.9 ms: 1.11x slower                                                  |
| pickle_pure_python       | 200 us                                                      | 225 us: 1.12x slower                                                   |
| hexiom                   | 4.55 ms                                                     | 5.16 ms: 1.13x slower                                                  |
| unpickle_pure_python     | 152 us                                                      | 174 us: 1.14x slower                                                   |
| deepcopy_reduce          | 2.07 us                                                     | 2.39 us: 1.15x slower                                                  |
| go                       | 97.3 ms                                                     | 112 ms: 1.15x slower                                                   |
| scimark_lu               | 63.5 ms                                                     | 74.0 ms: 1.16x slower                                                  |
| scimark_fft              | 178 ms                                                      | 208 ms: 1.17x slower                                                   |
| richards                 | 30.6 ms                                                     | 35.7 ms: 1.17x slower                                                  |
| pyflate                  | 304 ms                                                      | 356 ms: 1.17x slower                                                   |
| pprint_safe_repr         | 512 ms                                                      | 600 ms: 1.17x slower                                                   |
| scimark_monte_carlo      | 44.6 ms                                                     | 52.9 ms: 1.18x slower                                                  |
| spectral_norm            | 67.9 ms                                                     | 80.7 ms: 1.19x slower                                                  |
| pprint_pformat           | 1.04 sec                                                    | 1.24 sec: 1.19x slower                                                 |
| xml_etree_generate       | 52.2 ms                                                     | 62.7 ms: 1.20x slower                                                  |
| xml_etree_process        | 37.1 ms                                                     | 45.1 ms: 1.22x slower                                                  |
| deepcopy_memo            | 25.2 us                                                     | 31.1 us: 1.23x slower                                                  |
| regex_v8                 | 13.8 ms                                                     | 17.2 ms: 1.24x slower                                                  |
| pycparser                | 691 ms                                                      | 873 ms: 1.26x slower                                                   |
| coroutines               | 14.6 ms                                                     | 18.8 ms: 1.28x slower                                                  |
| telco                    | 3.90 ms                                                     | 5.07 ms: 1.30x slower                                                  |
| logging_silent           | 69.8 ns                                                     | 92.1 ns: 1.32x slower                                                  |
| scimark_sor              | 75.6 ms                                                     | 104 ms: 1.37x slower                                                   |
| async_generators         | 178 ms                                                      | 267 ms: 1.51x slower                                                   |
| Geometric mean           | (ref)                                                       | 1.06x slower                                                           |

Benchmark hidden because not significant (6): generators, async_tree_cpu_io_mixed, tornado_http, async_tree_memoization, float, async_tree_io
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
