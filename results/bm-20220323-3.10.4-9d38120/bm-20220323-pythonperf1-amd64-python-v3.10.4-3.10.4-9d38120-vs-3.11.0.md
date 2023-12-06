
# Results vs. 3.11.0

- fork: python
- ref: v3.10.4
- machine: windows-amd64
- commit hash: 9d38120
- commit date: 2022-03-23
- overall geometric mean: 1.12x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 239 ms: 1.15x slower                                        |
| chameleon      | 5.35 ms                                                     | 6.02 ms: 1.12x slower                                       |
| docutils       | 1.59 sec                                                    | 1.88 sec: 1.18x slower                                      |
| html5lib       | 38.6 ms                                                     | 47.5 ms: 1.23x slower                                       |
| tornado_http   | 89.9 ms                                                     | 106 ms: 1.17x slower                                        |
| Geometric mean | (ref)                                                       | 1.17x slower                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 495 ms                                                      | 617 ms: 1.25x slower                                        |
| async_tree_none         | 314 ms                                                      | 424 ms: 1.35x slower                                        |
| async_tree_memoization  | 367 ms                                                      | 505 ms: 1.38x slower                                        |
| async_tree_io           | 753 ms                                                      | 1.07 sec: 1.42x slower                                      |
| Geometric mean          | (ref)                                                       | 1.35x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 146 ms: 1.02x faster                                        |
| nbody          | 69.3 ms                                                     | 71.0 ms: 1.03x slower                                       |
| float          | 54.4 ms                                                     | 61.7 ms: 1.14x slower                                       |
| Geometric mean | (ref)                                                       | 1.05x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 1.52 ms                                                     | 1.56 ms: 1.03x slower                                       |
| regex_dna      | 121 ms                                                      | 129 ms: 1.07x slower                                        |
| regex_v8       | 13.7 ms                                                     | 15.0 ms: 1.10x slower                                       |
| regex_compile  | 90.8 ms                                                     | 102 ms: 1.13x slower                                        |
| Geometric mean | (ref)                                                       | 1.08x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_dict          | 17.8 us                                                     | 17.1 us: 1.04x faster                                       |
| pickle_list          | 2.68 us                                                     | 2.69 us: 1.00x slower                                       |
| xml_etree_parse      | 94.5 ms                                                     | 96.8 ms: 1.02x slower                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 64.5 ms: 1.02x slower                                       |
| unpickle_list        | 2.57 us                                                     | 2.68 us: 1.04x slower                                       |
| xml_etree_generate   | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                       |
| pickle               | 6.53 us                                                     | 6.87 us: 1.05x slower                                       |
| json_loads           | 12.9 us                                                     | 14.2 us: 1.10x slower                                       |
| json_dumps           | 7.90 ms                                                     | 8.77 ms: 1.11x slower                                       |
| tomli_loads          | 1.42 sec                                                    | 1.65 sec: 1.16x slower                                      |
| unpickle_pure_python | 152 us                                                      | 177 us: 1.16x slower                                        |
| unpickle             | 7.82 us                                                     | 9.11 us: 1.16x slower                                       |
| xml_etree_process    | 37.0 ms                                                     | 43.1 ms: 1.16x slower                                       |
| pickle_pure_python   | 207 us                                                      | 259 us: 1.25x slower                                        |
| Geometric mean       | (ref)                                                       | 1.09x slower                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 15.3 ms: 1.01x faster                                       |
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                       |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| genshi_xml      | 40.5 ms                                                     | 39.4 ms: 1.03x faster                                       |
| genshi_text     | 17.7 ms                                                     | 18.8 ms: 1.07x slower                                       |
| mako            | 7.55 ms                                                     | 8.98 ms: 1.19x slower                                       |
| django_template | 24.0 ms                                                     | 28.8 ms: 1.20x slower                                       |
| Geometric mean  | (ref)                                                       | 1.10x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| unpack_sequence          | 47.0 ns                                                     | 40.0 ns: 1.17x faster                                       |
| coverage                 | 43.0 ms                                                     | 38.4 ms: 1.12x faster                                       |
| generators               | 34.0 ms                                                     | 31.8 ms: 1.07x faster                                       |
| logging_simple           | 6.60 us                                                     | 6.28 us: 1.05x faster                                       |
| logging_format           | 7.06 us                                                     | 6.73 us: 1.05x faster                                       |
| gc_traversal             | 1.46 ms                                                     | 1.40 ms: 1.04x faster                                       |
| pickle_dict              | 17.8 us                                                     | 17.1 us: 1.04x faster                                       |
| telco                    | 3.93 ms                                                     | 3.82 ms: 1.03x faster                                       |
| genshi_xml               | 40.5 ms                                                     | 39.4 ms: 1.03x faster                                       |
| bench_mp_pool            | 61.1 ms                                                     | 59.9 ms: 1.02x faster                                       |
| meteor_contest           | 75.0 ms                                                     | 73.8 ms: 1.02x faster                                       |
| pidigits                 | 149 ms                                                      | 146 ms: 1.02x faster                                        |
| python_startup_no_site   | 15.5 ms                                                     | 15.3 ms: 1.01x faster                                       |
| mdp                      | 1.73 sec                                                    | 1.71 sec: 1.01x faster                                      |
| pickle_list              | 2.68 us                                                     | 2.69 us: 1.00x slower                                       |
| xml_etree_parse          | 94.5 ms                                                     | 96.8 ms: 1.02x slower                                       |
| xml_etree_iterparse      | 63.0 ms                                                     | 64.5 ms: 1.02x slower                                       |
| nbody                    | 69.3 ms                                                     | 71.0 ms: 1.03x slower                                       |
| regex_effbot             | 1.52 ms                                                     | 1.56 ms: 1.03x slower                                       |
| scimark_sparse_mat_mult  | 2.59 ms                                                     | 2.67 ms: 1.03x slower                                       |
| scimark_fft              | 181 ms                                                      | 187 ms: 1.03x slower                                        |
| nqueens                  | 66.1 ms                                                     | 68.3 ms: 1.03x slower                                       |
| fannkuch                 | 248 ms                                                      | 258 ms: 1.04x slower                                        |
| unpickle_list            | 2.57 us                                                     | 2.68 us: 1.04x slower                                       |
| xml_etree_generate       | 52.2 ms                                                     | 54.5 ms: 1.04x slower                                       |
| python_startup           | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                       |
| sympy_str                | 184 ms                                                      | 193 ms: 1.05x slower                                        |
| pathlib                  | 69.4 ms                                                     | 72.8 ms: 1.05x slower                                       |
| pickle                   | 6.53 us                                                     | 6.87 us: 1.05x slower                                       |
| typing_runtime_protocols | 320 us                                                      | 337 us: 1.05x slower                                        |
| sympy_sum                | 100.0 ms                                                    | 105 ms: 1.05x slower                                        |
| coroutines               | 14.7 ms                                                     | 15.5 ms: 1.06x slower                                       |
| sqlite_synth             | 1.79 us                                                     | 1.90 us: 1.06x slower                                       |
| sqlalchemy_imperative    | 10.5 ms                                                     | 11.2 ms: 1.06x slower                                       |
| genshi_text              | 17.7 ms                                                     | 18.8 ms: 1.07x slower                                       |
| comprehensions           | 15.6 us                                                     | 16.6 us: 1.07x slower                                       |
| regex_dna                | 121 ms                                                      | 129 ms: 1.07x slower                                        |
| deepcopy                 | 242 us                                                      | 259 us: 1.07x slower                                        |
| deepcopy_reduce          | 2.07 us                                                     | 2.22 us: 1.07x slower                                       |
| sympy_expand             | 299 ms                                                      | 320 ms: 1.07x slower                                        |
| pylint                   | 317 ms                                                      | 341 ms: 1.07x slower                                        |
| bench_thread_pool        | 847 us                                                      | 913 us: 1.08x slower                                        |
| sqlglot_normalize        | 191 ms                                                      | 207 ms: 1.08x slower                                        |
| sympy_integrate          | 13.7 ms                                                     | 15.0 ms: 1.09x slower                                       |
| regex_v8                 | 13.7 ms                                                     | 15.0 ms: 1.10x slower                                       |
| dulwich_log              | 44.1 ms                                                     | 48.6 ms: 1.10x slower                                       |
| json_loads               | 12.9 us                                                     | 14.2 us: 1.10x slower                                       |
| json_dumps               | 7.90 ms                                                     | 8.77 ms: 1.11x slower                                       |
| chameleon                | 5.35 ms                                                     | 6.02 ms: 1.12x slower                                       |
| sqlglot_optimize         | 35.1 ms                                                     | 39.4 ms: 1.12x slower                                       |
| aiohttp                  | 854 us                                                      | 961 us: 1.13x slower                                        |
| regex_compile            | 90.8 ms                                                     | 102 ms: 1.13x slower                                        |
| spectral_norm            | 69.9 ms                                                     | 78.9 ms: 1.13x slower                                       |
| create_gc_cycles         | 706 us                                                      | 800 us: 1.13x slower                                        |
| float                    | 54.4 ms                                                     | 61.7 ms: 1.14x slower                                       |
| deepcopy_memo            | 25.5 us                                                     | 29.0 us: 1.14x slower                                       |
| pprint_safe_repr         | 519 ms                                                      | 594 ms: 1.15x slower                                        |
| pprint_pformat           | 1.06 sec                                                    | 1.22 sec: 1.15x slower                                      |
| 2to3                     | 207 ms                                                      | 239 ms: 1.15x slower                                        |
| tomli_loads              | 1.42 sec                                                    | 1.65 sec: 1.16x slower                                      |
| dask                     | 262 ms                                                      | 305 ms: 1.16x slower                                        |
| unpickle_pure_python     | 152 us                                                      | 177 us: 1.16x slower                                        |
| unpickle                 | 7.82 us                                                     | 9.11 us: 1.16x slower                                       |
| xml_etree_process        | 37.0 ms                                                     | 43.1 ms: 1.16x slower                                       |
| asyncio_tcp              | 614 ms                                                      | 717 ms: 1.17x slower                                        |
| tornado_http             | 89.9 ms                                                     | 106 ms: 1.17x slower                                        |
| sqlalchemy_declarative   | 83.9 ms                                                     | 98.6 ms: 1.18x slower                                       |
| docutils                 | 1.59 sec                                                    | 1.88 sec: 1.18x slower                                      |
| mako                     | 7.55 ms                                                     | 8.98 ms: 1.19x slower                                       |
| django_template          | 24.0 ms                                                     | 28.8 ms: 1.20x slower                                       |
| async_generators         | 181 ms                                                      | 219 ms: 1.21x slower                                        |
| html5lib                 | 38.6 ms                                                     | 47.5 ms: 1.23x slower                                       |
| hexiom                   | 4.51 ms                                                     | 5.59 ms: 1.24x slower                                       |
| thrift                   | 501 us                                                      | 623 us: 1.24x slower                                        |
| async_tree_cpu_io_mixed  | 495 ms                                                      | 617 ms: 1.25x slower                                        |
| pickle_pure_python       | 207 us                                                      | 259 us: 1.25x slower                                        |
| sqlglot_transpile        | 1.15 ms                                                     | 1.45 ms: 1.26x slower                                       |
| raytrace                 | 211 ms                                                      | 266 ms: 1.26x slower                                        |
| chaos                    | 46.8 ms                                                     | 59.5 ms: 1.27x slower                                       |
| sqlglot_parse            | 939 us                                                      | 1.20 ms: 1.28x slower                                       |
| pycparser                | 705 ms                                                      | 905 ms: 1.28x slower                                        |
| scimark_monte_carlo      | 44.6 ms                                                     | 58.0 ms: 1.30x slower                                       |
| crypto_pyaes             | 48.2 ms                                                     | 63.1 ms: 1.31x slower                                       |
| richards                 | 30.8 ms                                                     | 40.6 ms: 1.32x slower                                       |
| pyflate                  | 305 ms                                                      | 402 ms: 1.32x slower                                        |
| logging_silent           | 70.7 ns                                                     | 93.4 ns: 1.32x slower                                       |
| richards_super           | 37.9 ms                                                     | 50.3 ms: 1.33x slower                                       |
| scimark_lu               | 62.3 ms                                                     | 84.0 ms: 1.35x slower                                       |
| async_tree_none          | 314 ms                                                      | 424 ms: 1.35x slower                                        |
| go                       | 98.8 ms                                                     | 135 ms: 1.37x slower                                        |
| async_tree_memoization   | 367 ms                                                      | 505 ms: 1.38x slower                                        |
| scimark_sor              | 76.4 ms                                                     | 105 ms: 1.38x slower                                        |
| async_tree_io            | 753 ms                                                      | 1.07 sec: 1.42x slower                                      |
| mypy2                    | 226 ms                                                      | 347 ms: 1.53x slower                                        |
| deltablue                | 2.63 ms                                                     | 4.12 ms: 1.57x slower                                       |
| Geometric mean           | (ref)                                                       | 1.12x slower                                                |

Benchmark hidden because not significant (3): flaskblogging, asyncio_tcp_ssl, json
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.10x
- 95% likely to have a slowdown of 1.09x
- 99% likely to have a slowdown of 1.08x
