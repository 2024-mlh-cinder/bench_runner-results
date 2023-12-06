
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.04x faster
- HPT reliability: 82.78%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                     |
| tornado_http   | 91.8 ms                                                     | 88.5 ms: 1.04x faster                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                       |
| nbody          | 70.0 ms                                                     | 74.9 ms: 1.07x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 118 ms: 1.02x slower                                       |
| regex_effbot   | 1.50 ms                                                     | 1.56 ms: 1.04x slower                                      |
| regex_v8       | 13.8 ms                                                     | 14.9 ms: 1.08x slower                                      |
| Geometric mean | (ref)                                                       | 1.04x slower                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.66 ms: 1.33x faster                                      |
| unpickle_pure_python | 152 us                                                      | 136 us: 1.11x faster                                       |
| xml_etree_parse      | 95.9 ms                                                     | 91.9 ms: 1.04x faster                                      |
| pickle_pure_python   | 200 us                                                      | 193 us: 1.04x faster                                       |
| xml_etree_process    | 37.1 ms                                                     | 37.9 ms: 1.02x slower                                      |
| unpickle             | 8.09 us                                                     | 8.29 us: 1.02x slower                                      |
| xml_etree_iterparse  | 62.6 ms                                                     | 64.4 ms: 1.03x slower                                      |
| tomli_loads          | 1.41 sec                                                    | 1.48 sec: 1.04x slower                                     |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                      |
| xml_etree_generate   | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                      |
| unpickle_list        | 2.55 us                                                     | 2.73 us: 1.07x slower                                      |
| pickle               | 6.61 us                                                     | 7.24 us: 1.09x slower                                      |
| pickle_list          | 2.68 us                                                     | 3.35 us: 1.25x slower                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                      |
| python_startup         | 18.7 ms                                                     | 20.0 ms: 1.07x slower                                      |
| Geometric mean         | (ref)                                                       | 1.05x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.43 ms: 1.02x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 101 us: 3.17x faster                                       |
| generators               | 33.8 ms                                                     | 22.7 ms: 1.49x faster                                      |
| asyncio_tcp              | 699 ms                                                      | 471 ms: 1.48x faster                                       |
| json_dumps               | 7.56 ms                                                     | 5.66 ms: 1.33x faster                                      |
| coverage                 | 55.9 ms                                                     | 45.7 ms: 1.22x faster                                      |
| raytrace                 | 211 ms                                                      | 173 ms: 1.22x faster                                       |
| async_tree_none          | 320 ms                                                      | 264 ms: 1.21x faster                                       |
| mdp                      | 1.67 sec                                                    | 1.38 sec: 1.21x faster                                     |
| deltablue                | 2.61 ms                                                     | 2.18 ms: 1.20x faster                                      |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.77 sec: 1.19x faster                                     |
| sqlglot_parse            | 952 us                                                      | 814 us: 1.17x faster                                       |
| unpack_sequence          | 46.1 ns                                                     | 39.4 ns: 1.17x faster                                      |
| richards_super           | 37.5 ms                                                     | 32.3 ms: 1.16x faster                                      |
| json                     | 3.25 ms                                                     | 2.82 ms: 1.15x faster                                      |
| chaos                    | 47.1 ms                                                     | 41.3 ms: 1.14x faster                                      |
| sqlglot_transpile        | 1.16 ms                                                     | 1.03 ms: 1.13x faster                                      |
| unpickle_pure_python     | 152 us                                                      | 136 us: 1.11x faster                                       |
| comprehensions           | 15.9 us                                                     | 14.3 us: 1.11x faster                                      |
| hexiom                   | 4.55 ms                                                     | 4.21 ms: 1.08x faster                                      |
| go                       | 97.3 ms                                                     | 90.3 ms: 1.08x faster                                      |
| logging_silent           | 69.8 ns                                                     | 65.0 ns: 1.07x faster                                      |
| mypy2                    | 229 ms                                                      | 214 ms: 1.07x faster                                       |
| async_tree_memoization   | 371 ms                                                      | 346 ms: 1.07x faster                                       |
| async_tree_io            | 779 ms                                                      | 728 ms: 1.07x faster                                       |
| spectral_norm            | 67.9 ms                                                     | 63.9 ms: 1.06x faster                                      |
| scimark_lu               | 63.5 ms                                                     | 59.8 ms: 1.06x faster                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 472 ms: 1.06x faster                                       |
| richards                 | 30.6 ms                                                     | 29.0 ms: 1.05x faster                                      |
| crypto_pyaes             | 47.6 ms                                                     | 45.1 ms: 1.05x faster                                      |
| nqueens                  | 64.9 ms                                                     | 61.7 ms: 1.05x faster                                      |
| deepcopy_memo            | 25.2 us                                                     | 24.0 us: 1.05x faster                                      |
| deepcopy                 | 246 us                                                      | 234 us: 1.05x faster                                       |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.46 ms: 1.05x faster                                      |
| xml_etree_parse          | 95.9 ms                                                     | 91.9 ms: 1.04x faster                                      |
| sqlglot_normalize        | 190 ms                                                      | 183 ms: 1.04x faster                                       |
| tornado_http             | 91.8 ms                                                     | 88.5 ms: 1.04x faster                                      |
| pickle_pure_python       | 200 us                                                      | 193 us: 1.04x faster                                       |
| logging_simple           | 6.61 us                                                     | 6.39 us: 1.03x faster                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 43.4 ms: 1.03x faster                                      |
| logging_format           | 7.01 us                                                     | 6.84 us: 1.03x faster                                      |
| bench_thread_pool        | 852 us                                                      | 837 us: 1.02x faster                                       |
| meteor_contest           | 74.7 ms                                                     | 73.5 ms: 1.02x faster                                      |
| scimark_fft              | 178 ms                                                      | 179 ms: 1.01x slower                                       |
| pprint_safe_repr         | 512 ms                                                      | 516 ms: 1.01x slower                                       |
| dulwich_log              | 44.5 ms                                                     | 44.9 ms: 1.01x slower                                      |
| docutils                 | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                     |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                     |
| regex_dna                | 115 ms                                                      | 118 ms: 1.02x slower                                       |
| xml_etree_process        | 37.1 ms                                                     | 37.9 ms: 1.02x slower                                      |
| deepcopy_reduce          | 2.07 us                                                     | 2.12 us: 1.02x slower                                      |
| mako                     | 7.26 ms                                                     | 7.43 ms: 1.02x slower                                      |
| unpickle                 | 8.09 us                                                     | 8.29 us: 1.02x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                      |
| xml_etree_iterparse      | 62.6 ms                                                     | 64.4 ms: 1.03x slower                                      |
| python_startup_no_site   | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                      |
| sqlite_synth             | 1.68 us                                                     | 1.75 us: 1.04x slower                                      |
| regex_effbot             | 1.50 ms                                                     | 1.56 ms: 1.04x slower                                      |
| tomli_loads              | 1.41 sec                                                    | 1.48 sec: 1.04x slower                                     |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                      |
| fannkuch                 | 252 ms                                                      | 266 ms: 1.05x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 55.4 ms: 1.06x slower                                      |
| scimark_sor              | 75.6 ms                                                     | 80.6 ms: 1.07x slower                                      |
| create_gc_cycles         | 693 us                                                      | 739 us: 1.07x slower                                       |
| python_startup           | 18.7 ms                                                     | 20.0 ms: 1.07x slower                                      |
| nbody                    | 70.0 ms                                                     | 74.9 ms: 1.07x slower                                      |
| unpickle_list            | 2.55 us                                                     | 2.73 us: 1.07x slower                                      |
| regex_v8                 | 13.8 ms                                                     | 14.9 ms: 1.08x slower                                      |
| pickle                   | 6.61 us                                                     | 7.24 us: 1.09x slower                                      |
| pathlib                  | 71.4 ms                                                     | 78.2 ms: 1.10x slower                                      |
| bench_mp_pool            | 62.5 ms                                                     | 70.6 ms: 1.13x slower                                      |
| pycparser                | 691 ms                                                      | 795 ms: 1.15x slower                                       |
| telco                    | 3.90 ms                                                     | 4.80 ms: 1.23x slower                                      |
| pickle_list              | 2.68 us                                                     | 3.35 us: 1.25x slower                                      |
| async_generators         | 178 ms                                                      | 238 ms: 1.34x slower                                       |
| dask                     | 264 ms                                                      | 370 ms: 1.40x slower                                       |
| Geometric mean           | (ref)                                                       | 1.04x faster                                               |

Benchmark hidden because not significant (6): pickle_dict, sqlglot_optimize, pyflate, float, regex_compile, coroutines
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 82.78% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
