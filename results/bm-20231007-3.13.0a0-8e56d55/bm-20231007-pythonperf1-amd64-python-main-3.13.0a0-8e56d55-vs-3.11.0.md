
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.04x faster
- HPT reliability: 74.43%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| tornado_http   | 91.8 ms                                                     | 89.5 ms: 1.03x faster                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                               |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                       |
| nbody          | 70.0 ms                                                     | 73.7 ms: 1.05x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_effbot   | 1.50 ms                                                     | 1.60 ms: 1.07x slower                                      |
| regex_dna      | 115 ms                                                      | 124 ms: 1.08x slower                                       |
| regex_v8       | 13.8 ms                                                     | 15.3 ms: 1.11x slower                                      |
| Geometric mean | (ref)                                                       | 1.06x slower                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.74 ms: 1.32x faster                                      |
| unpickle_pure_python | 152 us                                                      | 138 us: 1.10x faster                                       |
| xml_etree_parse      | 95.9 ms                                                     | 91.8 ms: 1.05x faster                                      |
| pickle_pure_python   | 200 us                                                      | 193 us: 1.04x faster                                       |
| xml_etree_iterparse  | 62.6 ms                                                     | 64.6 ms: 1.03x slower                                      |
| unpickle_list        | 2.55 us                                                     | 2.64 us: 1.04x slower                                      |
| pickle               | 6.61 us                                                     | 6.91 us: 1.05x slower                                      |
| tomli_loads          | 1.41 sec                                                    | 1.48 sec: 1.05x slower                                     |
| xml_etree_process    | 37.1 ms                                                     | 38.9 ms: 1.05x slower                                      |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.06x slower                                      |
| pickle_list          | 2.68 us                                                     | 2.86 us: 1.07x slower                                      |
| xml_etree_generate   | 52.2 ms                                                     | 56.4 ms: 1.08x slower                                      |
| Geometric mean       | (ref)                                                       | 1.00x faster                                               |

Benchmark hidden because not significant (2): pickle_dict, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                      |
| python_startup         | 18.7 ms                                                     | 19.9 ms: 1.07x slower                                      |
| Geometric mean         | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.43 ms: 1.02x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 95.2 us: 3.38x faster                                      |
| asyncio_tcp              | 699 ms                                                      | 476 ms: 1.47x faster                                       |
| generators               | 33.8 ms                                                     | 23.2 ms: 1.46x faster                                      |
| json_dumps               | 7.56 ms                                                     | 5.74 ms: 1.32x faster                                      |
| raytrace                 | 211 ms                                                      | 172 ms: 1.23x faster                                       |
| coverage                 | 55.9 ms                                                     | 46.1 ms: 1.21x faster                                      |
| deltablue                | 2.61 ms                                                     | 2.18 ms: 1.20x faster                                      |
| async_tree_none          | 320 ms                                                      | 270 ms: 1.19x faster                                       |
| mdp                      | 1.67 sec                                                    | 1.41 sec: 1.18x faster                                     |
| unpack_sequence          | 46.1 ns                                                     | 39.4 ns: 1.17x faster                                      |
| richards_super           | 37.5 ms                                                     | 32.1 ms: 1.17x faster                                      |
| sqlglot_parse            | 952 us                                                      | 825 us: 1.15x faster                                       |
| chaos                    | 47.1 ms                                                     | 41.6 ms: 1.13x faster                                      |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.87 sec: 1.13x faster                                     |
| json                     | 3.25 ms                                                     | 2.89 ms: 1.13x faster                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.05 ms: 1.11x faster                                      |
| logging_silent           | 69.8 ns                                                     | 63.4 ns: 1.10x faster                                      |
| unpickle_pure_python     | 152 us                                                      | 138 us: 1.10x faster                                       |
| hexiom                   | 4.55 ms                                                     | 4.16 ms: 1.09x faster                                      |
| scimark_lu               | 63.5 ms                                                     | 58.8 ms: 1.08x faster                                      |
| async_tree_memoization   | 371 ms                                                      | 346 ms: 1.07x faster                                       |
| go                       | 97.3 ms                                                     | 91.0 ms: 1.07x faster                                      |
| comprehensions           | 15.9 us                                                     | 14.9 us: 1.07x faster                                      |
| mypy2                    | 229 ms                                                      | 215 ms: 1.07x faster                                       |
| async_tree_io            | 779 ms                                                      | 733 ms: 1.06x faster                                       |
| nqueens                  | 64.9 ms                                                     | 61.1 ms: 1.06x faster                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 473 ms: 1.06x faster                                       |
| crypto_pyaes             | 47.6 ms                                                     | 44.9 ms: 1.06x faster                                      |
| deepcopy                 | 246 us                                                      | 233 us: 1.06x faster                                       |
| richards                 | 30.6 ms                                                     | 29.0 ms: 1.05x faster                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.5 ms: 1.05x faster                                      |
| xml_etree_parse          | 95.9 ms                                                     | 91.8 ms: 1.05x faster                                      |
| deepcopy_memo            | 25.2 us                                                     | 24.2 us: 1.04x faster                                      |
| pickle_pure_python       | 200 us                                                      | 193 us: 1.04x faster                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.48 ms: 1.04x faster                                      |
| sqlglot_normalize        | 190 ms                                                      | 184 ms: 1.03x faster                                       |
| tornado_http             | 91.8 ms                                                     | 89.5 ms: 1.03x faster                                      |
| logging_simple           | 6.61 us                                                     | 6.48 us: 1.02x faster                                      |
| spectral_norm            | 67.9 ms                                                     | 67.2 ms: 1.01x faster                                      |
| logging_format           | 7.01 us                                                     | 6.96 us: 1.01x faster                                      |
| meteor_contest           | 74.7 ms                                                     | 74.4 ms: 1.00x faster                                      |
| sqlglot_optimize         | 34.9 ms                                                     | 35.2 ms: 1.01x slower                                      |
| bench_mp_pool            | 62.5 ms                                                     | 63.3 ms: 1.01x slower                                      |
| dulwich_log              | 44.5 ms                                                     | 45.1 ms: 1.01x slower                                      |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                       |
| coroutines               | 14.6 ms                                                     | 14.9 ms: 1.02x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.48 ms: 1.02x slower                                      |
| fannkuch                 | 252 ms                                                      | 257 ms: 1.02x slower                                       |
| mako                     | 7.26 ms                                                     | 7.43 ms: 1.02x slower                                      |
| create_gc_cycles         | 693 us                                                      | 714 us: 1.03x slower                                       |
| python_startup_no_site   | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                      |
| xml_etree_iterparse      | 62.6 ms                                                     | 64.6 ms: 1.03x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 529 ms: 1.03x slower                                       |
| unpickle_list            | 2.55 us                                                     | 2.64 us: 1.04x slower                                      |
| scimark_fft              | 178 ms                                                      | 185 ms: 1.04x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.08 sec: 1.04x slower                                     |
| sqlite_synth             | 1.68 us                                                     | 1.76 us: 1.04x slower                                      |
| pickle                   | 6.61 us                                                     | 6.91 us: 1.05x slower                                      |
| tomli_loads              | 1.41 sec                                                    | 1.48 sec: 1.05x slower                                     |
| xml_etree_process        | 37.1 ms                                                     | 38.9 ms: 1.05x slower                                      |
| nbody                    | 70.0 ms                                                     | 73.7 ms: 1.05x slower                                      |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.06x slower                                      |
| pickle_list              | 2.68 us                                                     | 2.86 us: 1.07x slower                                      |
| python_startup           | 18.7 ms                                                     | 19.9 ms: 1.07x slower                                      |
| regex_effbot             | 1.50 ms                                                     | 1.60 ms: 1.07x slower                                      |
| regex_dna                | 115 ms                                                      | 124 ms: 1.08x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 56.4 ms: 1.08x slower                                      |
| scimark_sor              | 75.6 ms                                                     | 82.6 ms: 1.09x slower                                      |
| pathlib                  | 71.4 ms                                                     | 78.0 ms: 1.09x slower                                      |
| regex_v8                 | 13.8 ms                                                     | 15.3 ms: 1.11x slower                                      |
| telco                    | 3.90 ms                                                     | 4.73 ms: 1.21x slower                                      |
| pycparser                | 691 ms                                                      | 861 ms: 1.25x slower                                       |
| async_generators         | 178 ms                                                      | 240 ms: 1.35x slower                                       |
| Geometric mean           | (ref)                                                       | 1.04x faster                                               |

Benchmark hidden because not significant (8): pickle_dict, deepcopy_reduce, pyflate, regex_compile, unpickle, float, docutils, bench_thread_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 74.43% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
