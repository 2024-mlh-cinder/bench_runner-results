
# Results vs. 3.11.0

- fork: brandtbucher
- ref: 5e9259d5db5f6e94cadc
- machine: linux-x86_64
- commit hash: 5e9259d
- commit date: 2023-09-24
- overall geometric mean: 1.03x faster
- HPT reliability: 79.80%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.63 sec                                               | 2.67 sec: 1.02x slower                                                      |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 198 ms                                                 | 187 ms: 1.06x faster                                                        |
| nbody          | 93.1 ms                                                | 91.7 ms: 1.02x faster                                                       |
| float          | 77.2 ms                                                | 81.0 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                       |
| regex_compile  | 138 ms                                                 | 140 ms: 1.01x slower                                                        |
| regex_dna      | 204 ms                                                 | 210 ms: 1.03x slower                                                        |
| regex_v8       | 22.0 ms                                                | 23.2 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                  | 1.01x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|---------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps          | 12.6 ms                                                | 9.80 ms: 1.28x faster                                                       |
| tomli_loads         | 2.22 sec                                               | 2.01 sec: 1.10x faster                                                      |
| xml_etree_parse     | 158 ms                                                 | 150 ms: 1.05x faster                                                        |
| json_loads          | 26.5 us                                                | 25.6 us: 1.04x faster                                                       |
| unpickle_list       | 4.91 us                                                | 4.76 us: 1.03x faster                                                       |
| pickle_pure_python  | 306 us                                                 | 300 us: 1.02x faster                                                        |
| xml_etree_iterparse | 104 ms                                                 | 102 ms: 1.02x faster                                                        |
| pickle_dict         | 31.1 us                                                | 30.8 us: 1.01x faster                                                       |
| pickle              | 10.1 us                                                | 10.3 us: 1.02x slower                                                       |
| unpickle            | 13.7 us                                                | 14.3 us: 1.04x slower                                                       |
| xml_etree_process   | 53.9 ms                                                | 58.0 ms: 1.08x slower                                                       |
| xml_etree_generate  | 76.2 ms                                                | 84.0 ms: 1.10x slower                                                       |
| pickle_list         | 4.11 us                                                | 4.63 us: 1.13x slower                                                       |
| Geometric mean      | (ref)                                                  | 1.01x faster                                                                |

Benchmark hidden because not significant (1): unpickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                       |
| python_startup         | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.1 ms                                                | 10.8 ms: 1.07x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 486 us                                                 | 145 us: 3.35x faster                                                        |
| generators               | 73.5 ms                                                | 28.5 ms: 2.58x faster                                                       |
| asyncio_tcp              | 922 ms                                                 | 497 ms: 1.85x faster                                                        |
| asyncio_tcp_ssl          | 3.14 sec                                               | 1.79 sec: 1.75x faster                                                      |
| json_dumps               | 12.6 ms                                                | 9.80 ms: 1.28x faster                                                       |
| mypy2                    | 420 ms                                                 | 348 ms: 1.21x faster                                                        |
| coverage                 | 100 ms                                                 | 84.5 ms: 1.18x faster                                                       |
| async_tree_none          | 526 ms                                                 | 445 ms: 1.18x faster                                                        |
| coroutines               | 25.5 ms                                                | 22.4 ms: 1.14x faster                                                       |
| regex_effbot             | 3.99 ms                                                | 3.57 ms: 1.12x faster                                                       |
| async_tree_memoization   | 627 ms                                                 | 569 ms: 1.10x faster                                                        |
| tomli_loads              | 2.22 sec                                               | 2.01 sec: 1.10x faster                                                      |
| async_tree_io            | 1.30 sec                                               | 1.19 sec: 1.09x faster                                                      |
| sqlglot_parse            | 1.40 ms                                                | 1.29 ms: 1.09x faster                                                       |
| raytrace                 | 297 ms                                                 | 274 ms: 1.08x faster                                                        |
| deltablue                | 3.67 ms                                                | 3.40 ms: 1.08x faster                                                       |
| chaos                    | 69.2 ms                                                | 64.7 ms: 1.07x faster                                                       |
| pidigits                 | 198 ms                                                 | 187 ms: 1.06x faster                                                        |
| sqlglot_transpile        | 1.70 ms                                                | 1.61 ms: 1.06x faster                                                       |
| crypto_pyaes             | 74.7 ms                                                | 70.9 ms: 1.05x faster                                                       |
| xml_etree_parse          | 158 ms                                                 | 150 ms: 1.05x faster                                                        |
| richards_super           | 56.8 ms                                                | 54.3 ms: 1.04x faster                                                       |
| async_tree_cpu_io_mixed  | 739 ms                                                 | 712 ms: 1.04x faster                                                        |
| json_loads               | 26.5 us                                                | 25.6 us: 1.04x faster                                                       |
| unpickle_list            | 4.91 us                                                | 4.76 us: 1.03x faster                                                       |
| scimark_sparse_mat_mult  | 4.50 ms                                                | 4.37 ms: 1.03x faster                                                       |
| unpack_sequence          | 43.1 ns                                                | 42.0 ns: 1.03x faster                                                       |
| pickle_pure_python       | 306 us                                                 | 300 us: 1.02x faster                                                        |
| xml_etree_iterparse      | 104 ms                                                 | 102 ms: 1.02x faster                                                        |
| nbody                    | 93.1 ms                                                | 91.7 ms: 1.02x faster                                                       |
| pickle_dict              | 31.1 us                                                | 30.8 us: 1.01x faster                                                       |
| sqlglot_normalize        | 108 ms                                                 | 107 ms: 1.01x faster                                                        |
| scimark_monte_carlo      | 68.1 ms                                                | 67.6 ms: 1.01x faster                                                       |
| logging_silent           | 101 ns                                                 | 102 ns: 1.01x slower                                                        |
| regex_compile            | 138 ms                                                 | 140 ms: 1.01x slower                                                        |
| bench_thread_pool        | 819 us                                                 | 829 us: 1.01x slower                                                        |
| create_gc_cycles         | 1.49 ms                                                | 1.51 ms: 1.01x slower                                                       |
| sqlglot_optimize         | 53.1 ms                                                | 53.8 ms: 1.01x slower                                                       |
| logging_simple           | 6.03 us                                                | 6.13 us: 1.02x slower                                                       |
| comprehensions           | 22.4 us                                                | 22.8 us: 1.02x slower                                                       |
| docutils                 | 2.63 sec                                               | 2.67 sec: 1.02x slower                                                      |
| meteor_contest           | 107 ms                                                 | 108 ms: 1.02x slower                                                        |
| fannkuch                 | 388 ms                                                 | 395 ms: 1.02x slower                                                        |
| scimark_sor              | 118 ms                                                 | 121 ms: 1.02x slower                                                        |
| pickle                   | 10.1 us                                                | 10.3 us: 1.02x slower                                                       |
| nqueens                  | 83.4 ms                                                | 85.3 ms: 1.02x slower                                                       |
| pathlib                  | 18.2 ms                                                | 18.7 ms: 1.03x slower                                                       |
| regex_dna                | 204 ms                                                 | 210 ms: 1.03x slower                                                        |
| scimark_lu               | 110 ms                                                 | 113 ms: 1.03x slower                                                        |
| scimark_fft              | 328 ms                                                 | 340 ms: 1.04x slower                                                        |
| deepcopy_memo            | 37.0 us                                                | 38.4 us: 1.04x slower                                                       |
| deepcopy                 | 342 us                                                 | 355 us: 1.04x slower                                                        |
| hexiom                   | 6.37 ms                                                | 6.64 ms: 1.04x slower                                                       |
| unpickle                 | 13.7 us                                                | 14.3 us: 1.04x slower                                                       |
| pprint_pformat           | 1.46 sec                                               | 1.52 sec: 1.04x slower                                                      |
| gc_traversal             | 4.02 ms                                                | 4.21 ms: 1.05x slower                                                       |
| float                    | 77.2 ms                                                | 81.0 ms: 1.05x slower                                                       |
| pprint_safe_repr         | 701 ms                                                 | 738 ms: 1.05x slower                                                        |
| mdp                      | 2.62 sec                                               | 2.75 sec: 1.05x slower                                                      |
| regex_v8                 | 22.0 ms                                                | 23.2 ms: 1.05x slower                                                       |
| go                       | 140 ms                                                 | 147 ms: 1.05x slower                                                        |
| richards                 | 45.7 ms                                                | 48.4 ms: 1.06x slower                                                       |
| dulwich_log              | 63.7 ms                                                | 67.5 ms: 1.06x slower                                                       |
| mako                     | 10.1 ms                                                | 10.8 ms: 1.07x slower                                                       |
| xml_etree_process        | 53.9 ms                                                | 58.0 ms: 1.08x slower                                                       |
| spectral_norm            | 100 ms                                                 | 108 ms: 1.08x slower                                                        |
| deepcopy_reduce          | 2.94 us                                                | 3.19 us: 1.09x slower                                                       |
| pyflate                  | 418 ms                                                 | 459 ms: 1.10x slower                                                        |
| xml_etree_generate       | 76.2 ms                                                | 84.0 ms: 1.10x slower                                                       |
| sqlite_synth             | 2.52 us                                                | 2.79 us: 1.11x slower                                                       |
| pickle_list              | 4.11 us                                                | 4.63 us: 1.13x slower                                                       |
| python_startup_no_site   | 6.01 ms                                                | 6.87 ms: 1.14x slower                                                       |
| python_startup           | 8.52 ms                                                | 10.1 ms: 1.18x slower                                                       |
| telco                    | 6.58 ms                                                | 8.13 ms: 1.24x slower                                                       |
| async_generators         | 368 ms                                                 | 464 ms: 1.26x slower                                                        |
| dask                     | 360 ms                                                 | 531 ms: 1.48x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.03x faster                                                                |

Benchmark hidden because not significant (6): unpickle_pure_python, json, tornado_http, bench_mp_pool, pycparser, logging_format
Ignored benchmarks (18) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 79.80% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
