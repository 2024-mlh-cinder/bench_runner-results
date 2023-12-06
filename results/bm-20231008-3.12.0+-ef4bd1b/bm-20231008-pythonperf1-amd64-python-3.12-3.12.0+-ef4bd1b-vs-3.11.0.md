
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.06x faster
- HPT reliability: 99.99%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 209 ms                                                      | 214 ms: 1.02x slower                                      |
| docutils       | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                    |
| tornado_http   | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                     |
| Geometric mean | (ref)                                                       | 1.00x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 54.6 ms                                                     | 55.4 ms: 1.01x slower                                     |
| pidigits       | 148 ms                                                      | 150 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                              |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_v8       | 13.8 ms                                                     | 13.2 ms: 1.05x faster                                     |
| regex_compile  | 90.6 ms                                                     | 88.1 ms: 1.03x faster                                     |
| regex_dna      | 115 ms                                                      | 117 ms: 1.01x slower                                      |
| regex_effbot   | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                     |
| Geometric mean | (ref)                                                       | 1.00x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.71 ms: 1.32x faster                                     |
| unpickle_pure_python | 152 us                                                      | 134 us: 1.13x faster                                      |
| xml_etree_parse      | 95.9 ms                                                     | 90.6 ms: 1.06x faster                                     |
| tomli_loads          | 1.41 sec                                                    | 1.37 sec: 1.03x faster                                    |
| pickle_pure_python   | 200 us                                                      | 194 us: 1.03x faster                                      |
| xml_etree_iterparse  | 62.6 ms                                                     | 63.3 ms: 1.01x slower                                     |
| xml_etree_process    | 37.1 ms                                                     | 38.4 ms: 1.04x slower                                     |
| pickle_list          | 2.68 us                                                     | 2.80 us: 1.04x slower                                     |
| pickle               | 6.61 us                                                     | 6.90 us: 1.04x slower                                     |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.05x slower                                     |
| xml_etree_generate   | 52.2 ms                                                     | 56.3 ms: 1.08x slower                                     |
| unpickle_list        | 2.55 us                                                     | 2.78 us: 1.09x slower                                     |
| Geometric mean       | (ref)                                                       | 1.01x faster                                              |

Benchmark hidden because not significant (2): unpickle, pickle_dict

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.97 ms: 1.04x faster                                     |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231008-pythonperf1-amd64-python-3.12-3.12.0+-ef4bd1b |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 99.7 us: 3.23x faster                                     |
| generators               | 33.8 ms                                                     | 22.5 ms: 1.50x faster                                     |
| asyncio_tcp              | 699 ms                                                      | 473 ms: 1.48x faster                                      |
| json_dumps               | 7.56 ms                                                     | 5.71 ms: 1.32x faster                                     |
| richards_super           | 37.5 ms                                                     | 30.2 ms: 1.24x faster                                     |
| deltablue                | 2.61 ms                                                     | 2.13 ms: 1.22x faster                                     |
| mdp                      | 1.67 sec                                                    | 1.37 sec: 1.22x faster                                    |
| unpack_sequence          | 46.1 ns                                                     | 38.3 ns: 1.20x faster                                     |
| sqlglot_parse            | 952 us                                                      | 806 us: 1.18x faster                                      |
| logging_silent           | 69.8 ns                                                     | 60.5 ns: 1.16x faster                                     |
| richards                 | 30.6 ms                                                     | 26.5 ms: 1.15x faster                                     |
| sqlglot_transpile        | 1.16 ms                                                     | 1.02 ms: 1.14x faster                                     |
| unpickle_pure_python     | 152 us                                                      | 134 us: 1.13x faster                                      |
| hexiom                   | 4.55 ms                                                     | 4.05 ms: 1.13x faster                                     |
| json                     | 3.25 ms                                                     | 2.90 ms: 1.12x faster                                     |
| comprehensions           | 15.9 us                                                     | 14.3 us: 1.11x faster                                     |
| async_tree_none          | 320 ms                                                      | 288 ms: 1.11x faster                                      |
| chaos                    | 47.1 ms                                                     | 42.7 ms: 1.10x faster                                     |
| async_tree_memoization   | 371 ms                                                      | 337 ms: 1.10x faster                                      |
| mypy2                    | 229 ms                                                      | 208 ms: 1.10x faster                                      |
| async_tree_io            | 779 ms                                                      | 713 ms: 1.09x faster                                      |
| coverage                 | 55.9 ms                                                     | 51.3 ms: 1.09x faster                                     |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.94 sec: 1.09x faster                                    |
| scimark_lu               | 63.5 ms                                                     | 58.8 ms: 1.08x faster                                     |
| spectral_norm            | 67.9 ms                                                     | 63.1 ms: 1.08x faster                                     |
| go                       | 97.3 ms                                                     | 90.5 ms: 1.08x faster                                     |
| raytrace                 | 211 ms                                                      | 196 ms: 1.07x faster                                      |
| deepcopy_memo            | 25.2 us                                                     | 23.7 us: 1.06x faster                                     |
| xml_etree_parse          | 95.9 ms                                                     | 90.6 ms: 1.06x faster                                     |
| logging_simple           | 6.61 us                                                     | 6.28 us: 1.05x faster                                     |
| dulwich_log              | 44.5 ms                                                     | 42.5 ms: 1.05x faster                                     |
| regex_v8                 | 13.8 ms                                                     | 13.2 ms: 1.05x faster                                     |
| coroutines               | 14.6 ms                                                     | 14.0 ms: 1.05x faster                                     |
| aiohttp                  | 899 us                                                      | 861 us: 1.04x faster                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 480 ms: 1.04x faster                                      |
| mako                     | 7.26 ms                                                     | 6.97 ms: 1.04x faster                                     |
| crypto_pyaes             | 47.6 ms                                                     | 45.8 ms: 1.04x faster                                     |
| tornado_http             | 91.8 ms                                                     | 88.4 ms: 1.04x faster                                     |
| pyflate                  | 304 ms                                                      | 293 ms: 1.04x faster                                      |
| tomli_loads              | 1.41 sec                                                    | 1.37 sec: 1.03x faster                                    |
| dask                     | 264 ms                                                      | 256 ms: 1.03x faster                                      |
| pickle_pure_python       | 200 us                                                      | 194 us: 1.03x faster                                      |
| logging_format           | 7.01 us                                                     | 6.80 us: 1.03x faster                                     |
| regex_compile            | 90.6 ms                                                     | 88.1 ms: 1.03x faster                                     |
| sqlglot_normalize        | 190 ms                                                      | 185 ms: 1.03x faster                                      |
| bench_thread_pool        | 852 us                                                      | 830 us: 1.03x faster                                      |
| deepcopy                 | 246 us                                                      | 240 us: 1.03x faster                                      |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.51 ms: 1.02x faster                                     |
| fannkuch                 | 252 ms                                                      | 246 ms: 1.02x faster                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 43.7 ms: 1.02x faster                                     |
| sqlglot_optimize         | 34.9 ms                                                     | 34.3 ms: 1.02x faster                                     |
| pprint_safe_repr         | 512 ms                                                      | 506 ms: 1.01x faster                                      |
| meteor_contest           | 74.7 ms                                                     | 74.1 ms: 1.01x faster                                     |
| pprint_pformat           | 1.04 sec                                                    | 1.04 sec: 1.00x faster                                    |
| bench_mp_pool            | 62.5 ms                                                     | 62.9 ms: 1.01x slower                                     |
| regex_dna                | 115 ms                                                      | 117 ms: 1.01x slower                                      |
| xml_etree_iterparse      | 62.6 ms                                                     | 63.3 ms: 1.01x slower                                     |
| docutils                 | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                    |
| float                    | 54.6 ms                                                     | 55.4 ms: 1.01x slower                                     |
| pidigits                 | 148 ms                                                      | 150 ms: 1.02x slower                                      |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                     |
| 2to3                     | 209 ms                                                      | 214 ms: 1.02x slower                                      |
| deepcopy_reduce          | 2.07 us                                                     | 2.14 us: 1.03x slower                                     |
| xml_etree_process        | 37.1 ms                                                     | 38.4 ms: 1.04x slower                                     |
| sqlite_synth             | 1.68 us                                                     | 1.75 us: 1.04x slower                                     |
| pickle_list              | 2.68 us                                                     | 2.80 us: 1.04x slower                                     |
| pickle                   | 6.61 us                                                     | 6.90 us: 1.04x slower                                     |
| create_gc_cycles         | 693 us                                                      | 724 us: 1.05x slower                                      |
| telco                    | 3.90 ms                                                     | 4.08 ms: 1.05x slower                                     |
| regex_effbot             | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                     |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.05x slower                                     |
| scimark_sor              | 75.6 ms                                                     | 79.6 ms: 1.05x slower                                     |
| xml_etree_generate       | 52.2 ms                                                     | 56.3 ms: 1.08x slower                                     |
| pathlib                  | 71.4 ms                                                     | 77.8 ms: 1.09x slower                                     |
| unpickle_list            | 2.55 us                                                     | 2.78 us: 1.09x slower                                     |
| async_generators         | 178 ms                                                      | 235 ms: 1.32x slower                                      |
| Geometric mean           | (ref)                                                       | 1.06x faster                                              |

Benchmark hidden because not significant (8): nqueens, pycparser, unpickle, pickle_dict, scimark_fft, nbody, python_startup_no_site, python_startup
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 99.99% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
