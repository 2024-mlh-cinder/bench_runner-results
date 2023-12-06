
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_elf
- machine: windows-amd64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.06x faster
- HPT reliability: 97.82%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                                 |
| tornado_http   | 109 ms                                                      | 91.4 ms: 1.19x faster                                                  |
| Geometric mean | (ref)                                                       | 1.15x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.8 ms: 1.10x faster                                                  |
| pidigits       | 145 ms                                                      | 150 ms: 1.04x slower                                                   |
| nbody          | 69.3 ms                                                     | 73.8 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                       | 1.00x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 121 ms: 1.09x faster                                                   |
| regex_compile  | 103 ms                                                      | 100 ms: 1.03x faster                                                   |
| regex_effbot   | 1.66 ms                                                     | 1.62 ms: 1.03x faster                                                  |
| regex_v8       | 15.0 ms                                                     | 17.2 ms: 1.15x slower                                                  |
| Geometric mean | (ref)                                                       | 1.00x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 6.01 ms: 1.41x faster                                                  |
| pickle_pure_python   | 257 us                                                      | 225 us: 1.14x faster                                                   |
| tomli_loads          | 1.62 sec                                                    | 1.43 sec: 1.13x faster                                                 |
| xml_etree_parse      | 102 ms                                                      | 93.9 ms: 1.08x faster                                                  |
| unpickle             | 9.17 us                                                     | 8.62 us: 1.06x faster                                                  |
| unpickle_list        | 2.81 us                                                     | 2.73 us: 1.03x faster                                                  |
| json_loads           | 14.2 us                                                     | 13.9 us: 1.02x faster                                                  |
| unpickle_pure_python | 171 us                                                      | 174 us: 1.01x slower                                                   |
| xml_etree_process    | 43.4 ms                                                     | 45.1 ms: 1.04x slower                                                  |
| pickle               | 6.80 us                                                     | 7.09 us: 1.04x slower                                                  |
| pickle_dict          | 16.9 us                                                     | 18.2 us: 1.07x slower                                                  |
| xml_etree_iterparse  | 63.5 ms                                                     | 68.3 ms: 1.08x slower                                                  |
| pickle_list          | 2.59 us                                                     | 2.84 us: 1.10x slower                                                  |
| xml_etree_generate   | 54.5 ms                                                     | 62.7 ms: 1.15x slower                                                  |
| Geometric mean       | (ref)                                                       | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                  |
| python_startup_no_site | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                                  |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.99 ms: 1.10x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 104 us: 3.13x faster                                                   |
| mypy2                    | 352 ms                                                      | 230 ms: 1.53x faster                                                   |
| deltablue                | 4.17 ms                                                     | 2.81 ms: 1.49x faster                                                  |
| asyncio_tcp              | 712 ms                                                      | 488 ms: 1.46x faster                                                   |
| async_tree_none          | 420 ms                                                      | 292 ms: 1.44x faster                                                   |
| json_dumps               | 8.50 ms                                                     | 6.01 ms: 1.41x faster                                                  |
| async_tree_io            | 1.07 sec                                                    | 782 ms: 1.36x faster                                                   |
| async_tree_memoization   | 497 ms                                                      | 370 ms: 1.34x faster                                                   |
| richards_super           | 51.7 ms                                                     | 39.2 ms: 1.32x faster                                                  |
| crypto_pyaes             | 62.3 ms                                                     | 49.2 ms: 1.27x faster                                                  |
| raytrace                 | 271 ms                                                      | 216 ms: 1.26x faster                                                   |
| sqlglot_parse            | 1.22 ms                                                     | 983 us: 1.24x faster                                                   |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 497 ms: 1.23x faster                                                   |
| go                       | 136 ms                                                      | 112 ms: 1.22x faster                                                   |
| sqlglot_transpile        | 1.46 ms                                                     | 1.21 ms: 1.21x faster                                                  |
| tornado_http             | 109 ms                                                      | 91.4 ms: 1.19x faster                                                  |
| chaos                    | 58.9 ms                                                     | 50.0 ms: 1.18x faster                                                  |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.73 sec: 1.17x faster                                                 |
| scimark_lu               | 85.4 ms                                                     | 74.0 ms: 1.15x faster                                                  |
| richards                 | 41.2 ms                                                     | 35.7 ms: 1.15x faster                                                  |
| pickle_pure_python       | 257 us                                                      | 225 us: 1.14x faster                                                   |
| tomli_loads              | 1.62 sec                                                    | 1.43 sec: 1.13x faster                                                 |
| mdp                      | 1.71 sec                                                    | 1.54 sec: 1.12x faster                                                 |
| docutils                 | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                                 |
| mako                     | 8.80 ms                                                     | 7.99 ms: 1.10x faster                                                  |
| float                    | 60.2 ms                                                     | 54.8 ms: 1.10x faster                                                  |
| regex_dna                | 132 ms                                                      | 121 ms: 1.09x faster                                                   |
| pyflate                  | 387 ms                                                      | 356 ms: 1.09x faster                                                   |
| xml_etree_parse          | 102 ms                                                      | 93.9 ms: 1.08x faster                                                  |
| bench_thread_pool        | 946 us                                                      | 878 us: 1.08x faster                                                   |
| hexiom                   | 5.52 ms                                                     | 5.16 ms: 1.07x faster                                                  |
| create_gc_cycles         | 782 us                                                      | 734 us: 1.07x faster                                                   |
| unpickle                 | 9.17 us                                                     | 8.62 us: 1.06x faster                                                  |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.51 ms: 1.06x faster                                                  |
| scimark_monte_carlo      | 55.9 ms                                                     | 52.9 ms: 1.06x faster                                                  |
| logging_silent           | 96.4 ns                                                     | 92.1 ns: 1.05x faster                                                  |
| dulwich_log              | 47.6 ms                                                     | 45.8 ms: 1.04x faster                                                  |
| json                     | 3.05 ms                                                     | 2.95 ms: 1.03x faster                                                  |
| regex_compile            | 103 ms                                                      | 100 ms: 1.03x faster                                                   |
| unpickle_list            | 2.81 us                                                     | 2.73 us: 1.03x faster                                                  |
| regex_effbot             | 1.66 ms                                                     | 1.62 ms: 1.03x faster                                                  |
| sqlite_synth             | 1.84 us                                                     | 1.79 us: 1.03x faster                                                  |
| json_loads               | 14.2 us                                                     | 13.9 us: 1.02x faster                                                  |
| scimark_sor              | 105 ms                                                      | 104 ms: 1.01x faster                                                   |
| python_startup           | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                  |
| pathlib                  | 77.4 ms                                                     | 78.2 ms: 1.01x slower                                                  |
| unpickle_pure_python     | 171 us                                                      | 174 us: 1.01x slower                                                   |
| pprint_safe_repr         | 589 ms                                                      | 600 ms: 1.02x slower                                                   |
| sqlglot_normalize        | 202 ms                                                      | 207 ms: 1.02x slower                                                   |
| pprint_pformat           | 1.21 sec                                                    | 1.24 sec: 1.03x slower                                                 |
| comprehensions           | 16.0 us                                                     | 16.4 us: 1.03x slower                                                  |
| spectral_norm            | 78.0 ms                                                     | 80.7 ms: 1.03x slower                                                  |
| pidigits                 | 145 ms                                                      | 150 ms: 1.04x slower                                                   |
| xml_etree_process        | 43.4 ms                                                     | 45.1 ms: 1.04x slower                                                  |
| pickle                   | 6.80 us                                                     | 7.09 us: 1.04x slower                                                  |
| nqueens                  | 67.0 ms                                                     | 69.9 ms: 1.04x slower                                                  |
| python_startup_no_site   | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                                  |
| fannkuch                 | 258 ms                                                      | 273 ms: 1.06x slower                                                   |
| generators               | 31.6 ms                                                     | 33.5 ms: 1.06x slower                                                  |
| nbody                    | 69.3 ms                                                     | 73.8 ms: 1.06x slower                                                  |
| deepcopy                 | 255 us                                                      | 272 us: 1.07x slower                                                   |
| pickle_dict              | 16.9 us                                                     | 18.2 us: 1.07x slower                                                  |
| xml_etree_iterparse      | 63.5 ms                                                     | 68.3 ms: 1.08x slower                                                  |
| scimark_fft              | 193 ms                                                      | 208 ms: 1.08x slower                                                   |
| deepcopy_memo            | 28.5 us                                                     | 31.1 us: 1.09x slower                                                  |
| pickle_list              | 2.59 us                                                     | 2.84 us: 1.10x slower                                                  |
| deepcopy_reduce          | 2.16 us                                                     | 2.39 us: 1.11x slower                                                  |
| meteor_contest           | 72.5 ms                                                     | 80.5 ms: 1.11x slower                                                  |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.12x slower                                                  |
| bench_mp_pool            | 60.7 ms                                                     | 68.0 ms: 1.12x slower                                                  |
| regex_v8                 | 15.0 ms                                                     | 17.2 ms: 1.15x slower                                                  |
| logging_format           | 6.66 us                                                     | 7.64 us: 1.15x slower                                                  |
| logging_simple           | 6.20 us                                                     | 7.14 us: 1.15x slower                                                  |
| xml_etree_generate       | 54.5 ms                                                     | 62.7 ms: 1.15x slower                                                  |
| coroutines               | 15.9 ms                                                     | 18.8 ms: 1.18x slower                                                  |
| coverage                 | 40.0 ms                                                     | 47.2 ms: 1.18x slower                                                  |
| async_generators         | 224 ms                                                      | 267 ms: 1.19x slower                                                   |
| unpack_sequence          | 37.8 ns                                                     | 48.0 ns: 1.27x slower                                                  |
| telco                    | 3.78 ms                                                     | 5.07 ms: 1.34x slower                                                  |
| Geometric mean           | (ref)                                                       | 1.06x faster                                                           |

Benchmark hidden because not significant (2): sqlglot_optimize, pycparser
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 97.82% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
