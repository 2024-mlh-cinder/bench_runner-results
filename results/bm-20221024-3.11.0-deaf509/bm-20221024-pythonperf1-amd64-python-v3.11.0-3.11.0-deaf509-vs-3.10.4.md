
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0
- machine: windows-amd64
- commit hash: deaf509
- commit date: 2022-10-24
- overall geometric mean: 1.12x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 207 ms: 1.15x faster                                        |
| chameleon      | 6.02 ms                                                     | 5.35 ms: 1.12x faster                                       |
| docutils       | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                      |
| html5lib       | 47.5 ms                                                     | 38.6 ms: 1.23x faster                                       |
| tornado_http   | 106 ms                                                      | 89.9 ms: 1.17x faster                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 753 ms: 1.42x faster                                        |
| async_tree_memoization  | 505 ms                                                      | 367 ms: 1.38x faster                                        |
| async_tree_none         | 424 ms                                                      | 314 ms: 1.35x faster                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 495 ms: 1.25x faster                                        |
| Geometric mean          | (ref)                                                       | 1.35x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.4 ms: 1.14x faster                                       |
| nbody          | 71.0 ms                                                     | 69.3 ms: 1.03x faster                                       |
| pidigits       | 146 ms                                                      | 149 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                       | 1.05x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 90.8 ms: 1.13x faster                                       |
| regex_v8       | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                        |
| regex_effbot   | 1.56 ms                                                     | 1.52 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 207 us: 1.25x faster                                        |
| xml_etree_process    | 43.1 ms                                                     | 37.0 ms: 1.16x faster                                       |
| unpickle             | 9.11 us                                                     | 7.82 us: 1.16x faster                                       |
| unpickle_pure_python | 177 us                                                      | 152 us: 1.16x faster                                        |
| tomli_loads          | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                      |
| json_dumps           | 8.77 ms                                                     | 7.90 ms: 1.11x faster                                       |
| json_loads           | 14.2 us                                                     | 12.9 us: 1.10x faster                                       |
| pickle               | 6.87 us                                                     | 6.53 us: 1.05x faster                                       |
| xml_etree_generate   | 54.5 ms                                                     | 52.2 ms: 1.04x faster                                       |
| unpickle_list        | 2.68 us                                                     | 2.57 us: 1.04x faster                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                       |
| xml_etree_parse      | 96.8 ms                                                     | 94.5 ms: 1.02x faster                                       |
| pickle_list          | 2.69 us                                                     | 2.68 us: 1.00x faster                                       |
| pickle_dict          | 17.1 us                                                     | 17.8 us: 1.04x slower                                       |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 18.8 ms: 1.04x faster                                       |
| python_startup_no_site | 15.3 ms                                                     | 15.5 ms: 1.01x slower                                       |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 28.8 ms                                                     | 24.0 ms: 1.20x faster                                       |
| mako            | 8.98 ms                                                     | 7.55 ms: 1.19x faster                                       |
| genshi_text     | 18.8 ms                                                     | 17.7 ms: 1.07x faster                                       |
| genshi_xml      | 39.4 ms                                                     | 40.5 ms: 1.03x slower                                       |
| Geometric mean  | (ref)                                                       | 1.10x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| deltablue                | 4.12 ms                                                     | 2.63 ms: 1.57x faster                                       |
| mypy2                    | 347 ms                                                      | 226 ms: 1.53x faster                                        |
| async_tree_io            | 1.07 sec                                                    | 753 ms: 1.42x faster                                        |
| scimark_sor              | 105 ms                                                      | 76.4 ms: 1.38x faster                                       |
| async_tree_memoization   | 505 ms                                                      | 367 ms: 1.38x faster                                        |
| go                       | 135 ms                                                      | 98.8 ms: 1.37x faster                                       |
| async_tree_none          | 424 ms                                                      | 314 ms: 1.35x faster                                        |
| scimark_lu               | 84.0 ms                                                     | 62.3 ms: 1.35x faster                                       |
| richards_super           | 50.3 ms                                                     | 37.9 ms: 1.33x faster                                       |
| logging_silent           | 93.4 ns                                                     | 70.7 ns: 1.32x faster                                       |
| pyflate                  | 402 ms                                                      | 305 ms: 1.32x faster                                        |
| richards                 | 40.6 ms                                                     | 30.8 ms: 1.32x faster                                       |
| crypto_pyaes             | 63.1 ms                                                     | 48.2 ms: 1.31x faster                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 44.6 ms: 1.30x faster                                       |
| pycparser                | 905 ms                                                      | 705 ms: 1.28x faster                                        |
| sqlglot_parse            | 1.20 ms                                                     | 939 us: 1.28x faster                                        |
| chaos                    | 59.5 ms                                                     | 46.8 ms: 1.27x faster                                       |
| raytrace                 | 266 ms                                                      | 211 ms: 1.26x faster                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.15 ms: 1.26x faster                                       |
| pickle_pure_python       | 259 us                                                      | 207 us: 1.25x faster                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 495 ms: 1.25x faster                                        |
| thrift                   | 623 us                                                      | 501 us: 1.24x faster                                        |
| hexiom                   | 5.59 ms                                                     | 4.51 ms: 1.24x faster                                       |
| html5lib                 | 47.5 ms                                                     | 38.6 ms: 1.23x faster                                       |
| async_generators         | 219 ms                                                      | 181 ms: 1.21x faster                                        |
| django_template          | 28.8 ms                                                     | 24.0 ms: 1.20x faster                                       |
| mako                     | 8.98 ms                                                     | 7.55 ms: 1.19x faster                                       |
| docutils                 | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                      |
| sqlalchemy_declarative   | 98.6 ms                                                     | 83.9 ms: 1.18x faster                                       |
| tornado_http             | 106 ms                                                      | 89.9 ms: 1.17x faster                                       |
| asyncio_tcp              | 717 ms                                                      | 614 ms: 1.17x faster                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.0 ms: 1.16x faster                                       |
| unpickle                 | 9.11 us                                                     | 7.82 us: 1.16x faster                                       |
| unpickle_pure_python     | 177 us                                                      | 152 us: 1.16x faster                                        |
| dask                     | 305 ms                                                      | 262 ms: 1.16x faster                                        |
| tomli_loads              | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                      |
| 2to3                     | 239 ms                                                      | 207 ms: 1.15x faster                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.06 sec: 1.15x faster                                      |
| pprint_safe_repr         | 594 ms                                                      | 519 ms: 1.15x faster                                        |
| deepcopy_memo            | 29.0 us                                                     | 25.5 us: 1.14x faster                                       |
| float                    | 61.7 ms                                                     | 54.4 ms: 1.14x faster                                       |
| create_gc_cycles         | 800 us                                                      | 706 us: 1.13x faster                                        |
| spectral_norm            | 78.9 ms                                                     | 69.9 ms: 1.13x faster                                       |
| regex_compile            | 102 ms                                                      | 90.8 ms: 1.13x faster                                       |
| aiohttp                  | 961 us                                                      | 854 us: 1.13x faster                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 35.1 ms: 1.12x faster                                       |
| chameleon                | 6.02 ms                                                     | 5.35 ms: 1.12x faster                                       |
| json_dumps               | 8.77 ms                                                     | 7.90 ms: 1.11x faster                                       |
| json_loads               | 14.2 us                                                     | 12.9 us: 1.10x faster                                       |
| dulwich_log              | 48.6 ms                                                     | 44.1 ms: 1.10x faster                                       |
| regex_v8                 | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.7 ms: 1.09x faster                                       |
| sqlglot_normalize        | 207 ms                                                      | 191 ms: 1.08x faster                                        |
| bench_thread_pool        | 913 us                                                      | 847 us: 1.08x faster                                        |
| pylint                   | 341 ms                                                      | 317 ms: 1.07x faster                                        |
| sympy_expand             | 320 ms                                                      | 299 ms: 1.07x faster                                        |
| deepcopy_reduce          | 2.22 us                                                     | 2.07 us: 1.07x faster                                       |
| deepcopy                 | 259 us                                                      | 242 us: 1.07x faster                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                        |
| comprehensions           | 16.6 us                                                     | 15.6 us: 1.07x faster                                       |
| genshi_text              | 18.8 ms                                                     | 17.7 ms: 1.07x faster                                       |
| sqlalchemy_imperative    | 11.2 ms                                                     | 10.5 ms: 1.06x faster                                       |
| sqlite_synth             | 1.90 us                                                     | 1.79 us: 1.06x faster                                       |
| coroutines               | 15.5 ms                                                     | 14.7 ms: 1.06x faster                                       |
| sympy_sum                | 105 ms                                                      | 100.0 ms: 1.05x faster                                      |
| typing_runtime_protocols | 337 us                                                      | 320 us: 1.05x faster                                        |
| pickle                   | 6.87 us                                                     | 6.53 us: 1.05x faster                                       |
| pathlib                  | 72.8 ms                                                     | 69.4 ms: 1.05x faster                                       |
| sympy_str                | 193 ms                                                      | 184 ms: 1.05x faster                                        |
| python_startup           | 19.7 ms                                                     | 18.8 ms: 1.04x faster                                       |
| xml_etree_generate       | 54.5 ms                                                     | 52.2 ms: 1.04x faster                                       |
| unpickle_list            | 2.68 us                                                     | 2.57 us: 1.04x faster                                       |
| fannkuch                 | 258 ms                                                      | 248 ms: 1.04x faster                                        |
| nqueens                  | 68.3 ms                                                     | 66.1 ms: 1.03x faster                                       |
| scimark_fft              | 187 ms                                                      | 181 ms: 1.03x faster                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.59 ms: 1.03x faster                                       |
| regex_effbot             | 1.56 ms                                                     | 1.52 ms: 1.03x faster                                       |
| nbody                    | 71.0 ms                                                     | 69.3 ms: 1.03x faster                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                       |
| xml_etree_parse          | 96.8 ms                                                     | 94.5 ms: 1.02x faster                                       |
| pickle_list              | 2.69 us                                                     | 2.68 us: 1.00x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.73 sec: 1.01x slower                                      |
| python_startup_no_site   | 15.3 ms                                                     | 15.5 ms: 1.01x slower                                       |
| pidigits                 | 146 ms                                                      | 149 ms: 1.02x slower                                        |
| meteor_contest           | 73.8 ms                                                     | 75.0 ms: 1.02x slower                                       |
| bench_mp_pool            | 59.9 ms                                                     | 61.1 ms: 1.02x slower                                       |
| genshi_xml               | 39.4 ms                                                     | 40.5 ms: 1.03x slower                                       |
| telco                    | 3.82 ms                                                     | 3.93 ms: 1.03x slower                                       |
| pickle_dict              | 17.1 us                                                     | 17.8 us: 1.04x slower                                       |
| gc_traversal             | 1.40 ms                                                     | 1.46 ms: 1.04x slower                                       |
| logging_format           | 6.73 us                                                     | 7.06 us: 1.05x slower                                       |
| logging_simple           | 6.28 us                                                     | 6.60 us: 1.05x slower                                       |
| generators               | 31.8 ms                                                     | 34.0 ms: 1.07x slower                                       |
| coverage                 | 38.4 ms                                                     | 43.0 ms: 1.12x slower                                       |
| unpack_sequence          | 40.0 ns                                                     | 47.0 ns: 1.17x slower                                       |
| Geometric mean           | (ref)                                                       | 1.12x faster                                                |

Benchmark hidden because not significant (3): json, asyncio_tcp_ssl, flaskblogging
Ignored benchmarks (4) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
