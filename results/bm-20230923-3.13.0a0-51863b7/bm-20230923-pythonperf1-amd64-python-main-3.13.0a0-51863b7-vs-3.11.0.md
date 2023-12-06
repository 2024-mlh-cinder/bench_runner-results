
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.04x faster
- HPT reliability: 88.40%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| tornado_http   | 91.8 ms                                                     | 88.1 ms: 1.04x faster                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                               |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                       |
| nbody          | 70.0 ms                                                     | 76.0 ms: 1.09x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 90.1 ms: 1.01x faster                                      |
| regex_dna      | 115 ms                                                      | 122 ms: 1.05x slower                                       |
| regex_v8       | 13.8 ms                                                     | 14.8 ms: 1.07x slower                                      |
| regex_effbot   | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                      |
| Geometric mean | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.74 ms: 1.32x faster                                      |
| unpickle_pure_python | 152 us                                                      | 136 us: 1.11x faster                                       |
| pickle_pure_python   | 200 us                                                      | 192 us: 1.04x faster                                       |
| xml_etree_parse      | 95.9 ms                                                     | 93.1 ms: 1.03x faster                                      |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.8 ms: 1.02x slower                                      |
| unpickle             | 8.09 us                                                     | 8.29 us: 1.02x slower                                      |
| xml_etree_process    | 37.1 ms                                                     | 38.5 ms: 1.04x slower                                      |
| unpickle_list        | 2.55 us                                                     | 2.65 us: 1.04x slower                                      |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                      |
| tomli_loads          | 1.41 sec                                                    | 1.49 sec: 1.06x slower                                     |
| pickle               | 6.61 us                                                     | 7.13 us: 1.08x slower                                      |
| xml_etree_generate   | 52.2 ms                                                     | 56.7 ms: 1.09x slower                                      |
| pickle_list          | 2.68 us                                                     | 3.38 us: 1.26x slower                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                      |
| python_startup         | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                      |
| Geometric mean         | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.39 ms: 1.02x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-pythonperf1-amd64-python-main-3.13.0a0-51863b7 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 96.0 us: 3.35x faster                                      |
| generators               | 33.8 ms                                                     | 22.9 ms: 1.47x faster                                      |
| asyncio_tcp              | 699 ms                                                      | 482 ms: 1.45x faster                                       |
| json_dumps               | 7.56 ms                                                     | 5.74 ms: 1.32x faster                                      |
| async_tree_none          | 320 ms                                                      | 262 ms: 1.22x faster                                       |
| coverage                 | 55.9 ms                                                     | 45.9 ms: 1.22x faster                                      |
| deltablue                | 2.61 ms                                                     | 2.18 ms: 1.20x faster                                      |
| raytrace                 | 211 ms                                                      | 177 ms: 1.19x faster                                       |
| sqlglot_parse            | 952 us                                                      | 805 us: 1.18x faster                                       |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.79 sec: 1.18x faster                                     |
| unpack_sequence          | 46.1 ns                                                     | 39.2 ns: 1.18x faster                                      |
| richards_super           | 37.5 ms                                                     | 32.0 ms: 1.17x faster                                      |
| chaos                    | 47.1 ms                                                     | 41.4 ms: 1.14x faster                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.02 ms: 1.14x faster                                      |
| mdp                      | 1.67 sec                                                    | 1.47 sec: 1.14x faster                                     |
| unpickle_pure_python     | 152 us                                                      | 136 us: 1.11x faster                                       |
| comprehensions           | 15.9 us                                                     | 14.3 us: 1.11x faster                                      |
| json                     | 3.25 ms                                                     | 2.95 ms: 1.10x faster                                      |
| logging_silent           | 69.8 ns                                                     | 63.7 ns: 1.10x faster                                      |
| hexiom                   | 4.55 ms                                                     | 4.21 ms: 1.08x faster                                      |
| async_tree_io            | 779 ms                                                      | 722 ms: 1.08x faster                                       |
| async_tree_memoization   | 371 ms                                                      | 344 ms: 1.08x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 63.0 ms: 1.08x faster                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 466 ms: 1.08x faster                                       |
| mypy2                    | 229 ms                                                      | 214 ms: 1.07x faster                                       |
| scimark_monte_carlo      | 44.6 ms                                                     | 41.7 ms: 1.07x faster                                      |
| nqueens                  | 64.9 ms                                                     | 60.8 ms: 1.07x faster                                      |
| scimark_lu               | 63.5 ms                                                     | 59.8 ms: 1.06x faster                                      |
| go                       | 97.3 ms                                                     | 91.6 ms: 1.06x faster                                      |
| richards                 | 30.6 ms                                                     | 28.8 ms: 1.06x faster                                      |
| logging_simple           | 6.61 us                                                     | 6.28 us: 1.05x faster                                      |
| deepcopy                 | 246 us                                                      | 234 us: 1.05x faster                                       |
| tornado_http             | 91.8 ms                                                     | 88.1 ms: 1.04x faster                                      |
| deepcopy_memo            | 25.2 us                                                     | 24.1 us: 1.04x faster                                      |
| logging_format           | 7.01 us                                                     | 6.73 us: 1.04x faster                                      |
| crypto_pyaes             | 47.6 ms                                                     | 45.7 ms: 1.04x faster                                      |
| pickle_pure_python       | 200 us                                                      | 192 us: 1.04x faster                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.48 ms: 1.04x faster                                      |
| sqlglot_normalize        | 190 ms                                                      | 184 ms: 1.04x faster                                       |
| xml_etree_parse          | 95.9 ms                                                     | 93.1 ms: 1.03x faster                                      |
| meteor_contest           | 74.7 ms                                                     | 72.8 ms: 1.03x faster                                      |
| bench_thread_pool        | 852 us                                                      | 834 us: 1.02x faster                                       |
| pyflate                  | 304 ms                                                      | 300 ms: 1.01x faster                                       |
| sqlglot_optimize         | 34.9 ms                                                     | 34.7 ms: 1.01x faster                                      |
| regex_compile            | 90.6 ms                                                     | 90.1 ms: 1.01x faster                                      |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                       |
| dulwich_log              | 44.5 ms                                                     | 45.2 ms: 1.02x slower                                      |
| mako                     | 7.26 ms                                                     | 7.39 ms: 1.02x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 521 ms: 1.02x slower                                       |
| fannkuch                 | 252 ms                                                      | 257 ms: 1.02x slower                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.11 us: 1.02x slower                                      |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.8 ms: 1.02x slower                                      |
| scimark_fft              | 178 ms                                                      | 183 ms: 1.02x slower                                       |
| unpickle                 | 8.09 us                                                     | 8.29 us: 1.02x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.07 sec: 1.03x slower                                     |
| python_startup_no_site   | 15.9 ms                                                     | 16.4 ms: 1.03x slower                                      |
| xml_etree_process        | 37.1 ms                                                     | 38.5 ms: 1.04x slower                                      |
| unpickle_list            | 2.55 us                                                     | 2.65 us: 1.04x slower                                      |
| json_loads               | 12.9 us                                                     | 13.4 us: 1.04x slower                                      |
| regex_dna                | 115 ms                                                      | 122 ms: 1.05x slower                                       |
| tomli_loads              | 1.41 sec                                                    | 1.49 sec: 1.06x slower                                     |
| python_startup           | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                      |
| sqlite_synth             | 1.68 us                                                     | 1.79 us: 1.07x slower                                      |
| create_gc_cycles         | 693 us                                                      | 739 us: 1.07x slower                                       |
| scimark_sor              | 75.6 ms                                                     | 80.8 ms: 1.07x slower                                      |
| regex_v8                 | 13.8 ms                                                     | 14.8 ms: 1.07x slower                                      |
| regex_effbot             | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                      |
| pickle                   | 6.61 us                                                     | 7.13 us: 1.08x slower                                      |
| nbody                    | 70.0 ms                                                     | 76.0 ms: 1.09x slower                                      |
| xml_etree_generate       | 52.2 ms                                                     | 56.7 ms: 1.09x slower                                      |
| pathlib                  | 71.4 ms                                                     | 78.7 ms: 1.10x slower                                      |
| bench_mp_pool            | 62.5 ms                                                     | 70.6 ms: 1.13x slower                                      |
| pycparser                | 691 ms                                                      | 796 ms: 1.15x slower                                       |
| telco                    | 3.90 ms                                                     | 4.77 ms: 1.22x slower                                      |
| pickle_list              | 2.68 us                                                     | 3.38 us: 1.26x slower                                      |
| async_generators         | 178 ms                                                      | 240 ms: 1.35x slower                                       |
| dask                     | 264 ms                                                      | 368 ms: 1.39x slower                                       |
| Geometric mean           | (ref)                                                       | 1.04x faster                                               |

Benchmark hidden because not significant (4): coroutines, docutils, float, pickle_dict
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 88.40% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
