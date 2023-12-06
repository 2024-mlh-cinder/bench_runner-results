
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.05x faster
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 215 ms: 1.03x slower                                      |
| chameleon      | 5.35 ms                                                     | 5.23 ms: 1.02x faster                                     |
| docutils       | 1.59 sec                                                    | 1.62 sec: 1.02x slower                                    |
| tornado_http   | 89.9 ms                                                     | 87.5 ms: 1.03x faster                                     |
| Geometric mean | (ref)                                                       | 1.00x slower                                              |

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| async_tree_none            | 314 ms                                                      | 288 ms: 1.09x faster                                      |
| async_tree_memoization     | 367 ms                                                      | 339 ms: 1.08x faster                                      |
| async_tree_memoization_tg  | 380 ms                                                      | 353 ms: 1.08x faster                                      |
| async_tree_none_tg         | 299 ms                                                      | 278 ms: 1.08x faster                                      |
| async_tree_io_tg           | 795 ms                                                      | 746 ms: 1.07x faster                                      |
| async_tree_io              | 753 ms                                                      | 718 ms: 1.05x faster                                      |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 481 ms: 1.03x faster                                      |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 492 ms: 1.02x faster                                      |
| Geometric mean             | (ref)                                                       | 1.06x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 70.3 ms: 1.01x slower                                     |
| pidigits       | 149 ms                                                      | 151 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 89.0 ms: 1.02x faster                                     |
| regex_v8       | 13.7 ms                                                     | 13.9 ms: 1.01x slower                                     |
| regex_effbot   | 1.52 ms                                                     | 1.62 ms: 1.06x slower                                     |
| Geometric mean | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.62 ms: 1.41x faster                                     |
| unpickle_pure_python | 152 us                                                      | 136 us: 1.12x faster                                      |
| pickle_pure_python   | 207 us                                                      | 197 us: 1.05x faster                                      |
| xml_etree_parse      | 94.5 ms                                                     | 92.3 ms: 1.02x faster                                     |
| tomli_loads          | 1.42 sec                                                    | 1.41 sec: 1.01x faster                                    |
| xml_etree_iterparse  | 63.0 ms                                                     | 63.7 ms: 1.01x slower                                     |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                     |
| unpickle             | 7.82 us                                                     | 8.15 us: 1.04x slower                                     |
| xml_etree_process    | 37.0 ms                                                     | 38.7 ms: 1.04x slower                                     |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                     |
| pickle_list          | 2.68 us                                                     | 2.90 us: 1.08x slower                                     |
| unpickle_list        | 2.57 us                                                     | 2.78 us: 1.08x slower                                     |
| xml_etree_generate   | 52.2 ms                                                     | 56.7 ms: 1.09x slower                                     |
| pickle               | 6.53 us                                                     | 7.25 us: 1.11x slower                                     |
| Geometric mean       | (ref)                                                       | 1.00x faster                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 19.9 ms: 1.05x slower                                     |
| python_startup_no_site | 15.5 ms                                                     | 16.5 ms: 1.07x slower                                     |
| Geometric mean         | (ref)                                                       | 1.06x slower                                              |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako            | 7.55 ms                                                     | 6.90 ms: 1.09x faster                                     |
| django_template | 24.0 ms                                                     | 23.3 ms: 1.03x faster                                     |
| Geometric mean  | (ref)                                                       | 1.06x faster                                              |

All benchmarks:
===============

| Benchmark                  | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols   | 320 us                                                      | 95.9 us: 3.34x faster                                     |
| generators                 | 34.0 ms                                                     | 22.5 ms: 1.51x faster                                     |
| json_dumps                 | 7.90 ms                                                     | 5.62 ms: 1.41x faster                                     |
| asyncio_tcp                | 614 ms                                                      | 474 ms: 1.30x faster                                      |
| deltablue                  | 2.63 ms                                                     | 2.16 ms: 1.22x faster                                     |
| richards_super             | 37.9 ms                                                     | 31.5 ms: 1.20x faster                                     |
| mdp                        | 1.73 sec                                                    | 1.46 sec: 1.18x faster                                    |
| logging_silent             | 70.7 ns                                                     | 61.1 ns: 1.16x faster                                     |
| sqlglot_parse              | 939 us                                                      | 815 us: 1.15x faster                                      |
| sympy_sum                  | 100.0 ms                                                    | 87.9 ms: 1.14x faster                                     |
| sqlalchemy_imperative      | 10.5 ms                                                     | 9.25 ms: 1.14x faster                                     |
| unpack_sequence            | 47.0 ns                                                     | 41.4 ns: 1.13x faster                                     |
| unpickle_pure_python       | 152 us                                                      | 136 us: 1.12x faster                                      |
| sqlglot_transpile          | 1.15 ms                                                     | 1.03 ms: 1.12x faster                                     |
| richards                   | 30.8 ms                                                     | 27.8 ms: 1.11x faster                                     |
| coverage                   | 43.0 ms                                                     | 38.8 ms: 1.11x faster                                     |
| go                         | 98.8 ms                                                     | 89.8 ms: 1.10x faster                                     |
| mako                       | 7.55 ms                                                     | 6.90 ms: 1.09x faster                                     |
| sympy_str                  | 184 ms                                                      | 169 ms: 1.09x faster                                      |
| async_tree_none            | 314 ms                                                      | 288 ms: 1.09x faster                                      |
| spectral_norm              | 69.9 ms                                                     | 64.5 ms: 1.08x faster                                     |
| mypy2                      | 226 ms                                                      | 209 ms: 1.08x faster                                      |
| async_tree_memoization     | 367 ms                                                      | 339 ms: 1.08x faster                                      |
| hexiom                     | 4.51 ms                                                     | 4.18 ms: 1.08x faster                                     |
| async_tree_memoization_tg  | 380 ms                                                      | 353 ms: 1.08x faster                                      |
| async_tree_none_tg         | 299 ms                                                      | 278 ms: 1.08x faster                                      |
| comprehensions             | 15.6 us                                                     | 14.5 us: 1.07x faster                                     |
| sympy_integrate            | 13.7 ms                                                     | 12.8 ms: 1.07x faster                                     |
| raytrace                   | 211 ms                                                      | 198 ms: 1.07x faster                                      |
| async_tree_io_tg           | 795 ms                                                      | 746 ms: 1.07x faster                                      |
| nqueens                    | 66.1 ms                                                     | 62.4 ms: 1.06x faster                                     |
| sympy_expand               | 299 ms                                                      | 282 ms: 1.06x faster                                      |
| chaos                      | 46.8 ms                                                     | 44.3 ms: 1.06x faster                                     |
| scimark_sparse_mat_mult    | 2.59 ms                                                     | 2.46 ms: 1.05x faster                                     |
| pickle_pure_python         | 207 us                                                      | 197 us: 1.05x faster                                      |
| async_tree_io              | 753 ms                                                      | 718 ms: 1.05x faster                                      |
| deepcopy_memo              | 25.5 us                                                     | 24.4 us: 1.05x faster                                     |
| coroutines                 | 14.7 ms                                                     | 14.1 ms: 1.04x faster                                     |
| sqlglot_normalize          | 191 ms                                                      | 184 ms: 1.04x faster                                      |
| logging_simple             | 6.60 us                                                     | 6.37 us: 1.04x faster                                     |
| logging_format             | 7.06 us                                                     | 6.83 us: 1.03x faster                                     |
| bench_thread_pool          | 847 us                                                      | 820 us: 1.03x faster                                      |
| dulwich_log                | 44.1 ms                                                     | 42.6 ms: 1.03x faster                                     |
| pycparser                  | 705 ms                                                      | 683 ms: 1.03x faster                                      |
| django_template            | 24.0 ms                                                     | 23.3 ms: 1.03x faster                                     |
| sqlite_synth               | 1.79 us                                                     | 1.74 us: 1.03x faster                                     |
| async_tree_cpu_io_mixed    | 495 ms                                                      | 481 ms: 1.03x faster                                      |
| tornado_http               | 89.9 ms                                                     | 87.5 ms: 1.03x faster                                     |
| xml_etree_parse            | 94.5 ms                                                     | 92.3 ms: 1.02x faster                                     |
| chameleon                  | 5.35 ms                                                     | 5.23 ms: 1.02x faster                                     |
| dask                       | 262 ms                                                      | 257 ms: 1.02x faster                                      |
| regex_compile              | 90.8 ms                                                     | 89.0 ms: 1.02x faster                                     |
| async_tree_cpu_io_mixed_tg | 503 ms                                                      | 492 ms: 1.02x faster                                      |
| pyflate                    | 305 ms                                                      | 299 ms: 1.02x faster                                      |
| sqlglot_optimize           | 35.1 ms                                                     | 34.4 ms: 1.02x faster                                     |
| scimark_lu                 | 62.3 ms                                                     | 61.3 ms: 1.02x faster                                     |
| tomli_loads                | 1.42 sec                                                    | 1.41 sec: 1.01x faster                                    |
| crypto_pyaes               | 48.2 ms                                                     | 47.7 ms: 1.01x faster                                     |
| deepcopy                   | 242 us                                                      | 240 us: 1.01x faster                                      |
| pprint_pformat             | 1.06 sec                                                    | 1.06 sec: 1.00x faster                                    |
| pprint_safe_repr           | 519 ms                                                      | 522 ms: 1.01x slower                                      |
| sqlalchemy_declarative     | 83.9 ms                                                     | 84.7 ms: 1.01x slower                                     |
| xml_etree_iterparse        | 63.0 ms                                                     | 63.7 ms: 1.01x slower                                     |
| fannkuch                   | 248 ms                                                      | 251 ms: 1.01x slower                                      |
| regex_v8                   | 13.7 ms                                                     | 13.9 ms: 1.01x slower                                     |
| nbody                      | 69.3 ms                                                     | 70.3 ms: 1.01x slower                                     |
| pidigits                   | 149 ms                                                      | 151 ms: 1.02x slower                                      |
| scimark_monte_carlo        | 44.6 ms                                                     | 45.4 ms: 1.02x slower                                     |
| gc_traversal               | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                     |
| docutils                   | 1.59 sec                                                    | 1.62 sec: 1.02x slower                                    |
| create_gc_cycles           | 706 us                                                      | 725 us: 1.03x slower                                      |
| pickle_dict                | 17.8 us                                                     | 18.3 us: 1.03x slower                                     |
| telco                      | 3.93 ms                                                     | 4.05 ms: 1.03x slower                                     |
| deepcopy_reduce            | 2.07 us                                                     | 2.14 us: 1.03x slower                                     |
| bench_mp_pool              | 61.1 ms                                                     | 63.2 ms: 1.03x slower                                     |
| 2to3                       | 207 ms                                                      | 215 ms: 1.03x slower                                      |
| scimark_fft                | 181 ms                                                      | 189 ms: 1.04x slower                                      |
| unpickle                   | 7.82 us                                                     | 8.15 us: 1.04x slower                                     |
| xml_etree_process          | 37.0 ms                                                     | 38.7 ms: 1.04x slower                                     |
| json_loads                 | 12.9 us                                                     | 13.5 us: 1.05x slower                                     |
| python_startup             | 18.8 ms                                                     | 19.9 ms: 1.05x slower                                     |
| regex_effbot               | 1.52 ms                                                     | 1.62 ms: 1.06x slower                                     |
| python_startup_no_site     | 15.5 ms                                                     | 16.5 ms: 1.07x slower                                     |
| pickle_list                | 2.68 us                                                     | 2.90 us: 1.08x slower                                     |
| unpickle_list              | 2.57 us                                                     | 2.78 us: 1.08x slower                                     |
| xml_etree_generate         | 52.2 ms                                                     | 56.7 ms: 1.09x slower                                     |
| scimark_sor                | 76.4 ms                                                     | 84.2 ms: 1.10x slower                                     |
| pickle                     | 6.53 us                                                     | 7.25 us: 1.11x slower                                     |
| pathlib                    | 69.4 ms                                                     | 79.1 ms: 1.14x slower                                     |
| async_generators           | 181 ms                                                      | 234 ms: 1.29x slower                                      |
| Geometric mean             | (ref)                                                       | 1.05x faster                                              |

Benchmark hidden because not significant (6): asyncio_tcp_ssl, json, regex_dna, meteor_contest, float, aiohttp
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.93% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
