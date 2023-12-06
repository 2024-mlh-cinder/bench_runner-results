
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.02x faster
- HPT reliability: 83.59%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                     |
| tornado_http   | 91.8 ms                                                     | 89.7 ms: 1.02x faster                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                       |
| float          | 54.6 ms                                                     | 56.0 ms: 1.03x slower                                      |
| nbody          | 70.0 ms                                                     | 78.1 ms: 1.12x slower                                      |
| Geometric mean | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 93.0 ms: 1.03x slower                                      |
| regex_dna      | 115 ms                                                      | 119 ms: 1.03x slower                                       |
| regex_effbot   | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                      |
| regex_v8       | 13.8 ms                                                     | 14.9 ms: 1.08x slower                                      |
| Geometric mean | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.88 ms: 1.28x faster                                      |
| unpickle_pure_python | 152 us                                                      | 143 us: 1.06x faster                                       |
| xml_etree_parse      | 95.9 ms                                                     | 92.0 ms: 1.04x faster                                      |
| pickle_pure_python   | 200 us                                                      | 198 us: 1.01x faster                                       |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                      |
| pickle_list          | 2.68 us                                                     | 2.79 us: 1.04x slower                                      |
| xml_etree_iterparse  | 62.6 ms                                                     | 65.6 ms: 1.05x slower                                      |
| xml_etree_process    | 37.1 ms                                                     | 39.0 ms: 1.05x slower                                      |
| unpickle_list        | 2.55 us                                                     | 2.72 us: 1.07x slower                                      |
| xml_etree_generate   | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                      |
| tomli_loads          | 1.41 sec                                                    | 1.54 sec: 1.09x slower                                     |
| pickle               | 6.61 us                                                     | 7.20 us: 1.09x slower                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (2): unpickle, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                      |
| python_startup         | 18.7 ms                                                     | 19.9 ms: 1.06x slower                                      |
| Geometric mean         | (ref)                                                       | 1.06x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.60 ms: 1.05x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 97.8 us: 3.29x faster                                      |
| asyncio_tcp              | 699 ms                                                      | 482 ms: 1.45x faster                                       |
| generators               | 33.8 ms                                                     | 24.4 ms: 1.39x faster                                      |
| json_dumps               | 7.56 ms                                                     | 5.88 ms: 1.28x faster                                      |
| coverage                 | 55.9 ms                                                     | 47.0 ms: 1.19x faster                                      |
| raytrace                 | 211 ms                                                      | 183 ms: 1.15x faster                                       |
| unpack_sequence          | 46.1 ns                                                     | 40.2 ns: 1.15x faster                                      |
| mdp                      | 1.67 sec                                                    | 1.46 sec: 1.14x faster                                     |
| async_tree_none          | 320 ms                                                      | 280 ms: 1.14x faster                                       |
| deltablue                | 2.61 ms                                                     | 2.29 ms: 1.14x faster                                      |
| sqlglot_parse            | 952 us                                                      | 864 us: 1.10x faster                                       |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.93 sec: 1.10x faster                                     |
| chaos                    | 47.1 ms                                                     | 43.3 ms: 1.09x faster                                      |
| richards_super           | 37.5 ms                                                     | 34.6 ms: 1.08x faster                                      |
| json                     | 3.25 ms                                                     | 3.01 ms: 1.08x faster                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.09 ms: 1.07x faster                                      |
| logging_silent           | 69.8 ns                                                     | 65.2 ns: 1.07x faster                                      |
| unpickle_pure_python     | 152 us                                                      | 143 us: 1.06x faster                                       |
| scimark_lu               | 63.5 ms                                                     | 60.8 ms: 1.04x faster                                      |
| mypy2                    | 229 ms                                                      | 220 ms: 1.04x faster                                       |
| xml_etree_parse          | 95.9 ms                                                     | 92.0 ms: 1.04x faster                                      |
| async_tree_memoization   | 371 ms                                                      | 358 ms: 1.04x faster                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.48 ms: 1.04x faster                                      |
| spectral_norm            | 67.9 ms                                                     | 65.7 ms: 1.03x faster                                      |
| crypto_pyaes             | 47.6 ms                                                     | 46.1 ms: 1.03x faster                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 486 ms: 1.03x faster                                       |
| nqueens                  | 64.9 ms                                                     | 63.2 ms: 1.03x faster                                      |
| async_tree_io            | 779 ms                                                      | 759 ms: 1.03x faster                                       |
| hexiom                   | 4.55 ms                                                     | 4.45 ms: 1.02x faster                                      |
| tornado_http             | 91.8 ms                                                     | 89.7 ms: 1.02x faster                                      |
| richards                 | 30.6 ms                                                     | 30.0 ms: 1.02x faster                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 44.1 ms: 1.01x faster                                      |
| pickle_pure_python       | 200 us                                                      | 198 us: 1.01x faster                                       |
| deepcopy_memo            | 25.2 us                                                     | 25.0 us: 1.01x faster                                      |
| meteor_contest           | 74.7 ms                                                     | 75.0 ms: 1.00x slower                                      |
| logging_simple           | 6.61 us                                                     | 6.66 us: 1.01x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.47 ms: 1.01x slower                                      |
| go                       | 97.3 ms                                                     | 98.4 ms: 1.01x slower                                      |
| deepcopy                 | 246 us                                                      | 249 us: 1.01x slower                                       |
| fannkuch                 | 252 ms                                                      | 257 ms: 1.02x slower                                       |
| logging_format           | 7.01 us                                                     | 7.15 us: 1.02x slower                                      |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                       |
| sqlglot_normalize        | 190 ms                                                      | 195 ms: 1.02x slower                                       |
| coroutines               | 14.6 ms                                                     | 15.0 ms: 1.02x slower                                      |
| float                    | 54.6 ms                                                     | 56.0 ms: 1.03x slower                                      |
| regex_compile            | 90.6 ms                                                     | 93.0 ms: 1.03x slower                                      |
| docutils                 | 1.60 sec                                                    | 1.65 sec: 1.03x slower                                     |
| dulwich_log              | 44.5 ms                                                     | 45.7 ms: 1.03x slower                                      |
| regex_dna                | 115 ms                                                      | 119 ms: 1.03x slower                                       |
| scimark_fft              | 178 ms                                                      | 184 ms: 1.03x slower                                       |
| pyflate                  | 304 ms                                                      | 313 ms: 1.03x slower                                       |
| json_loads               | 12.9 us                                                     | 13.4 us: 1.04x slower                                      |
| sqlglot_optimize         | 34.9 ms                                                     | 36.2 ms: 1.04x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 533 ms: 1.04x slower                                       |
| pickle_list              | 2.68 us                                                     | 2.79 us: 1.04x slower                                      |
| mako                     | 7.26 ms                                                     | 7.60 ms: 1.05x slower                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.09 sec: 1.05x slower                                     |
| create_gc_cycles         | 693 us                                                      | 726 us: 1.05x slower                                       |
| xml_etree_iterparse      | 62.6 ms                                                     | 65.6 ms: 1.05x slower                                      |
| sqlite_synth             | 1.68 us                                                     | 1.77 us: 1.05x slower                                      |
| python_startup_no_site   | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                      |
| xml_etree_process        | 37.1 ms                                                     | 39.0 ms: 1.05x slower                                      |
| regex_effbot             | 1.50 ms                                                     | 1.59 ms: 1.06x slower                                      |
| python_startup           | 18.7 ms                                                     | 19.9 ms: 1.06x slower                                      |
| unpickle_list            | 2.55 us                                                     | 2.72 us: 1.07x slower                                      |
| xml_etree_generate       | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                      |
| regex_v8                 | 13.8 ms                                                     | 14.9 ms: 1.08x slower                                      |
| bench_mp_pool            | 62.5 ms                                                     | 67.3 ms: 1.08x slower                                      |
| scimark_sor              | 75.6 ms                                                     | 82.1 ms: 1.09x slower                                      |
| tomli_loads              | 1.41 sec                                                    | 1.54 sec: 1.09x slower                                     |
| pickle                   | 6.61 us                                                     | 7.20 us: 1.09x slower                                      |
| pycparser                | 691 ms                                                      | 755 ms: 1.09x slower                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.27 us: 1.09x slower                                      |
| nbody                    | 70.0 ms                                                     | 78.1 ms: 1.12x slower                                      |
| pathlib                  | 71.4 ms                                                     | 79.7 ms: 1.12x slower                                      |
| telco                    | 3.90 ms                                                     | 4.61 ms: 1.18x slower                                      |
| async_generators         | 178 ms                                                      | 244 ms: 1.37x slower                                       |
| dask                     | 264 ms                                                      | 389 ms: 1.47x slower                                       |
| Geometric mean           | (ref)                                                       | 1.02x faster                                               |

Benchmark hidden because not significant (4): bench_thread_pool, comprehensions, unpickle, pickle_dict
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 83.59% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
