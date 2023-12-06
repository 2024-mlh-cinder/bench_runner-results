
# Results vs. 3.10.4

- fork: python
- ref: ce6a533c4bf1afa3775d
- machine: windows-amd64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.14x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.00 ms: 1.21x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.60 sec: 1.17x faster                                                      |
| tornado_http   | 106 ms                                                      | 90.0 ms: 1.17x faster                                                       |
| Geometric mean | (ref)                                                       | 1.15x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 275 ms: 1.54x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 745 ms: 1.44x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 353 ms: 1.43x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 458 ms: 1.35x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.44x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 85.1 ms: 1.20x slower                                                       |
| Geometric mean | (ref)                                                       | 1.07x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 93.6 ms: 1.09x faster                                                       |
| regex_dna      | 129 ms                                                      | 123 ms: 1.05x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 15.7 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.68 ms: 1.54x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 181 us: 1.43x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 144 us: 1.23x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 37.0 ms: 1.17x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.25 us: 1.10x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.3 us: 1.07x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 95.9 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.72 sec: 1.04x slower                                                      |
| pickle_list          | 2.69 us                                                     | 2.87 us: 1.06x slower                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 69.0 ms: 1.07x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_generate, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.9 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 8.46 ms: 1.06x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 78.2 us: 4.31x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 57.4 ns: 1.63x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.9 ms: 1.58x faster                                                       |
| async_tree_none          | 424 ms                                                      | 275 ms: 1.54x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.68 ms: 1.54x faster                                                       |
| generators               | 31.8 ms                                                     | 20.8 ms: 1.53x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 788 us: 1.53x faster                                                        |
| raytrace                 | 266 ms                                                      | 176 ms: 1.51x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 57.9 ms: 1.45x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 496 ms: 1.45x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 745 ms: 1.44x faster                                                        |
| pickle_pure_python       | 259 us                                                      | 181 us: 1.43x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 353 ms: 1.43x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.43x faster                                                       |
| richards                 | 40.6 ms                                                     | 28.5 ms: 1.42x faster                                                       |
| deltablue                | 4.12 ms                                                     | 3.00 ms: 1.37x faster                                                       |
| go                       | 135 ms                                                      | 99.8 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 458 ms: 1.35x faster                                                        |
| spectral_norm            | 78.9 ms                                                     | 58.5 ms: 1.35x faster                                                       |
| chaos                    | 59.5 ms                                                     | 45.3 ms: 1.31x faster                                                       |
| scimark_sor              | 105 ms                                                      | 80.2 ms: 1.31x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 50.6 ms: 1.25x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 144 us: 1.23x faster                                                        |
| sympy_sum                | 105 ms                                                      | 85.5 ms: 1.23x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 48.0 ms: 1.21x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.00 ms: 1.21x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.58 us: 1.20x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 24.1 us: 1.20x faster                                                       |
| mypy2                    | 347 ms                                                      | 295 ms: 1.18x faster                                                        |
| docutils                 | 1.88 sec                                                    | 1.60 sec: 1.17x faster                                                      |
| tornado_http             | 106 ms                                                      | 90.0 ms: 1.17x faster                                                       |
| pyflate                  | 402 ms                                                      | 344 ms: 1.17x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 33.7 ms: 1.17x faster                                                       |
| pycparser                | 905 ms                                                      | 776 ms: 1.17x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.0 ms: 1.17x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 178 ms: 1.16x faster                                                        |
| deepcopy                 | 259 us                                                      | 224 us: 1.16x faster                                                        |
| coroutines               | 15.5 ms                                                     | 13.4 ms: 1.15x faster                                                       |
| sympy_str                | 193 ms                                                      | 168 ms: 1.15x faster                                                        |
| mdp                      | 1.71 sec                                                    | 1.50 sec: 1.14x faster                                                      |
| dulwich_log              | 48.6 ms                                                     | 42.9 ms: 1.13x faster                                                       |
| sympy_expand             | 320 ms                                                      | 286 ms: 1.12x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 1.98 us: 1.12x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.25 us: 1.10x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.12 sec: 1.10x faster                                                      |
| pprint_safe_repr         | 594 ms                                                      | 543 ms: 1.09x faster                                                        |
| regex_compile            | 102 ms                                                      | 93.6 ms: 1.09x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 737 us: 1.08x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.94 sec: 1.08x faster                                                      |
| bench_thread_pool        | 913 us                                                      | 850 us: 1.07x faster                                                        |
| 2to3                     | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| json                     | 3.10 ms                                                     | 2.91 ms: 1.07x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.3 us: 1.07x faster                                                       |
| mako                     | 8.98 ms                                                     | 8.46 ms: 1.06x faster                                                       |
| regex_dna                | 129 ms                                                      | 123 ms: 1.05x faster                                                        |
| comprehensions           | 16.6 us                                                     | 16.0 us: 1.03x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 95.9 ms: 1.01x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| pickle                   | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                                       |
| logging_format           | 6.73 us                                                     | 6.98 us: 1.04x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.53 us: 1.04x slower                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.72 sec: 1.04x slower                                                      |
| regex_v8                 | 15.0 ms                                                     | 15.7 ms: 1.05x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.3 ms: 1.06x slower                                                       |
| nqueens                  | 68.3 ms                                                     | 72.6 ms: 1.06x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.87 us: 1.06x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 69.0 ms: 1.07x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 79.5 ms: 1.08x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.51 ms: 1.08x slower                                                       |
| async_generators         | 219 ms                                                      | 237 ms: 1.08x slower                                                        |
| pathlib                  | 72.8 ms                                                     | 79.2 ms: 1.09x slower                                                       |
| hexiom                   | 5.59 ms                                                     | 6.15 ms: 1.10x slower                                                       |
| scimark_fft              | 187 ms                                                      | 217 ms: 1.16x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 17.9 ms: 1.17x slower                                                       |
| fannkuch                 | 258 ms                                                      | 307 ms: 1.19x slower                                                        |
| nbody                    | 71.0 ms                                                     | 85.1 ms: 1.20x slower                                                       |
| coverage                 | 38.4 ms                                                     | 47.0 ms: 1.23x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.82 ms: 1.26x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.64 ms: 1.36x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.14x faster                                                                |

Benchmark hidden because not significant (5): python_startup, xml_etree_generate, float, unpack_sequence, unpickle_list
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231112-3.13.0a1+-ce6a533-PYTHON_UOPS/bm-20231112-pythonperf1-amd64-python-ce6a533c4bf1afa3775d-3.13.0a1+-ce6a533.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.06x
