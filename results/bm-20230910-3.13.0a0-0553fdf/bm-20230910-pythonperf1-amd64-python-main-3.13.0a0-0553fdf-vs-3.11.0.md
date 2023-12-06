
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.03x faster
- HPT reliability: 67.06%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.63 sec: 1.01x slower                                     |
| tornado_http   | 91.8 ms                                                     | 90.2 ms: 1.02x faster                                      |
| Geometric mean | (ref)                                                       | 1.00x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 54.6 ms                                                     | 55.6 ms: 1.02x slower                                      |
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                       |
| nbody          | 70.0 ms                                                     | 76.5 ms: 1.09x slower                                      |
| Geometric mean | (ref)                                                       | 1.04x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 92.2 ms: 1.02x slower                                      |
| regex_dna      | 115 ms                                                      | 120 ms: 1.04x slower                                       |
| regex_effbot   | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                      |
| regex_v8       | 13.8 ms                                                     | 15.2 ms: 1.10x slower                                      |
| Geometric mean | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.60 ms: 1.35x faster                                      |
| unpickle_pure_python | 152 us                                                      | 135 us: 1.13x faster                                       |
| xml_etree_parse      | 95.9 ms                                                     | 90.4 ms: 1.06x faster                                      |
| pickle_pure_python   | 200 us                                                      | 190 us: 1.05x faster                                       |
| xml_etree_process    | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                      |
| xml_etree_iterparse  | 62.6 ms                                                     | 64.7 ms: 1.03x slower                                      |
| json_loads           | 12.9 us                                                     | 13.4 us: 1.04x slower                                      |
| unpickle             | 8.09 us                                                     | 8.47 us: 1.05x slower                                      |
| unpickle_list        | 2.55 us                                                     | 2.68 us: 1.05x slower                                      |
| xml_etree_generate   | 52.2 ms                                                     | 55.6 ms: 1.07x slower                                      |
| pickle               | 6.61 us                                                     | 7.08 us: 1.07x slower                                      |
| tomli_loads          | 1.41 sec                                                    | 1.52 sec: 1.07x slower                                     |
| pickle_list          | 2.68 us                                                     | 2.95 us: 1.10x slower                                      |
| Geometric mean       | (ref)                                                       | 1.00x faster                                               |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.3 ms: 1.02x slower                                      |
| python_startup         | 18.7 ms                                                     | 20.2 ms: 1.08x slower                                      |
| Geometric mean         | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.45 ms: 1.03x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 93.6 us: 3.44x faster                                      |
| generators               | 33.8 ms                                                     | 23.4 ms: 1.45x faster                                      |
| asyncio_tcp              | 699 ms                                                      | 489 ms: 1.43x faster                                       |
| json_dumps               | 7.56 ms                                                     | 5.60 ms: 1.35x faster                                      |
| coverage                 | 55.9 ms                                                     | 46.2 ms: 1.21x faster                                      |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.76 sec: 1.20x faster                                     |
| raytrace                 | 211 ms                                                      | 177 ms: 1.19x faster                                       |
| deltablue                | 2.61 ms                                                     | 2.23 ms: 1.17x faster                                      |
| async_tree_none          | 320 ms                                                      | 275 ms: 1.16x faster                                       |
| mdp                      | 1.67 sec                                                    | 1.45 sec: 1.15x faster                                     |
| richards_super           | 37.5 ms                                                     | 32.6 ms: 1.15x faster                                      |
| json                     | 3.25 ms                                                     | 2.84 ms: 1.15x faster                                      |
| unpickle_pure_python     | 152 us                                                      | 135 us: 1.13x faster                                       |
| chaos                    | 47.1 ms                                                     | 41.9 ms: 1.12x faster                                      |
| unpack_sequence          | 46.1 ns                                                     | 41.6 ns: 1.11x faster                                      |
| sqlglot_parse            | 952 us                                                      | 862 us: 1.10x faster                                       |
| logging_silent           | 69.8 ns                                                     | 63.7 ns: 1.10x faster                                      |
| scimark_lu               | 63.5 ms                                                     | 58.4 ms: 1.09x faster                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.08 ms: 1.08x faster                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 41.5 ms: 1.07x faster                                      |
| hexiom                   | 4.55 ms                                                     | 4.29 ms: 1.06x faster                                      |
| xml_etree_parse          | 95.9 ms                                                     | 90.4 ms: 1.06x faster                                      |
| comprehensions           | 15.9 us                                                     | 15.0 us: 1.06x faster                                      |
| spectral_norm            | 67.9 ms                                                     | 64.1 ms: 1.06x faster                                      |
| crypto_pyaes             | 47.6 ms                                                     | 45.0 ms: 1.06x faster                                      |
| richards                 | 30.6 ms                                                     | 29.0 ms: 1.06x faster                                      |
| async_tree_memoization   | 371 ms                                                      | 352 ms: 1.05x faster                                       |
| nqueens                  | 64.9 ms                                                     | 61.6 ms: 1.05x faster                                      |
| pickle_pure_python       | 200 us                                                      | 190 us: 1.05x faster                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.45 ms: 1.05x faster                                      |
| mypy2                    | 229 ms                                                      | 218 ms: 1.05x faster                                       |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 480 ms: 1.04x faster                                       |
| async_tree_io            | 779 ms                                                      | 749 ms: 1.04x faster                                       |
| deepcopy_memo            | 25.2 us                                                     | 24.4 us: 1.03x faster                                      |
| fannkuch                 | 252 ms                                                      | 247 ms: 1.02x faster                                       |
| tornado_http             | 91.8 ms                                                     | 90.2 ms: 1.02x faster                                      |
| deepcopy                 | 246 us                                                      | 241 us: 1.02x faster                                       |
| go                       | 97.3 ms                                                     | 95.6 ms: 1.02x faster                                      |
| logging_simple           | 6.61 us                                                     | 6.53 us: 1.01x faster                                      |
| logging_format           | 7.01 us                                                     | 7.06 us: 1.01x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 515 ms: 1.01x slower                                       |
| scimark_fft              | 178 ms                                                      | 180 ms: 1.01x slower                                       |
| sqlglot_normalize        | 190 ms                                                      | 193 ms: 1.01x slower                                       |
| docutils                 | 1.60 sec                                                    | 1.63 sec: 1.01x slower                                     |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                     |
| sqlglot_optimize         | 34.9 ms                                                     | 35.5 ms: 1.02x slower                                      |
| regex_compile            | 90.6 ms                                                     | 92.2 ms: 1.02x slower                                      |
| float                    | 54.6 ms                                                     | 55.6 ms: 1.02x slower                                      |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                       |
| python_startup_no_site   | 15.9 ms                                                     | 16.3 ms: 1.02x slower                                      |
| mako                     | 7.26 ms                                                     | 7.45 ms: 1.03x slower                                      |
| xml_etree_process        | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                      |
| xml_etree_iterparse      | 62.6 ms                                                     | 64.7 ms: 1.03x slower                                      |
| dulwich_log              | 44.5 ms                                                     | 46.0 ms: 1.03x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.51 ms: 1.04x slower                                      |
| regex_dna                | 115 ms                                                      | 120 ms: 1.04x slower                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.15 us: 1.04x slower                                      |
| sqlite_synth             | 1.68 us                                                     | 1.75 us: 1.04x slower                                      |
| json_loads               | 12.9 us                                                     | 13.4 us: 1.04x slower                                      |
| unpickle                 | 8.09 us                                                     | 8.47 us: 1.05x slower                                      |
| regex_effbot             | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                      |
| unpickle_list            | 2.55 us                                                     | 2.68 us: 1.05x slower                                      |
| xml_etree_generate       | 52.2 ms                                                     | 55.6 ms: 1.07x slower                                      |
| create_gc_cycles         | 693 us                                                      | 739 us: 1.07x slower                                       |
| pickle                   | 6.61 us                                                     | 7.08 us: 1.07x slower                                      |
| tomli_loads              | 1.41 sec                                                    | 1.52 sec: 1.07x slower                                     |
| python_startup           | 18.7 ms                                                     | 20.2 ms: 1.08x slower                                      |
| bench_mp_pool            | 62.5 ms                                                     | 67.7 ms: 1.08x slower                                      |
| nbody                    | 70.0 ms                                                     | 76.5 ms: 1.09x slower                                      |
| regex_v8                 | 13.8 ms                                                     | 15.2 ms: 1.10x slower                                      |
| pickle_list              | 2.68 us                                                     | 2.95 us: 1.10x slower                                      |
| pycparser                | 691 ms                                                      | 765 ms: 1.11x slower                                       |
| pathlib                  | 71.4 ms                                                     | 79.3 ms: 1.11x slower                                      |
| scimark_sor              | 75.6 ms                                                     | 84.7 ms: 1.12x slower                                      |
| telco                    | 3.90 ms                                                     | 4.81 ms: 1.23x slower                                      |
| async_generators         | 178 ms                                                      | 247 ms: 1.39x slower                                       |
| dask                     | 264 ms                                                      | 382 ms: 1.45x slower                                       |
| Geometric mean           | (ref)                                                       | 1.03x faster                                               |

Benchmark hidden because not significant (5): bench_thread_pool, meteor_contest, pyflate, coroutines, pickle_dict
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 67.06% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
