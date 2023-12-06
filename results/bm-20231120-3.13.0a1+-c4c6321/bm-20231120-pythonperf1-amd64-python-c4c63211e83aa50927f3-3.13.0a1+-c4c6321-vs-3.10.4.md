
# Results vs. 3.10.4

- fork: python
- ref: c4c63211e83aa50927f3
- machine: windows-amd64
- commit hash: c4c6321
- commit date: 2023-11-20
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 212 ms: 1.12x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.88 ms: 1.23x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.56 sec: 1.21x faster                                                      |
| tornado_http   | 106 ms                                                      | 95.6 ms: 1.11x faster                                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 269 ms: 1.58x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 715 ms: 1.50x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 342 ms: 1.47x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 452 ms: 1.36x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 52.1 ms: 1.19x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 75.5 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 80.4 ms: 1.27x faster                                                       |
| regex_dna      | 129 ms                                                      | 117 ms: 1.11x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 14.6 ms: 1.03x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.09x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.65 ms: 1.55x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 181 us: 1.43x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 130 us: 1.36x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 37.8 ms: 1.14x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.45 sec: 1.13x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.12 us: 1.12x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 90.1 ms: 1.07x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.06x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.6 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.86 us: 1.06x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                                |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.3 ms: 1.03x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.53 ms: 1.37x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 77.0 us: 4.37x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.13 ms: 1.93x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 56.1 ns: 1.67x faster                                                       |
| raytrace                 | 266 ms                                                      | 165 ms: 1.61x faster                                                        |
| comprehensions           | 16.6 us                                                     | 10.3 us: 1.61x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.3 ms: 1.61x faster                                                       |
| async_tree_none          | 424 ms                                                      | 269 ms: 1.58x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 768 us: 1.57x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.65 ms: 1.55x faster                                                       |
| go                       | 135 ms                                                      | 88.4 ms: 1.53x faster                                                       |
| async_tree_io            | 1.07 sec                                                    | 715 ms: 1.50x faster                                                        |
| generators               | 31.8 ms                                                     | 21.4 ms: 1.48x faster                                                       |
| chaos                    | 59.5 ms                                                     | 40.2 ms: 1.48x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 342 ms: 1.47x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 988 us: 1.46x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 57.6 ms: 1.46x faster                                                       |
| hexiom                   | 5.59 ms                                                     | 3.87 ms: 1.44x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 43.7 ms: 1.44x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 181 us: 1.43x faster                                                        |
| richards                 | 40.6 ms                                                     | 28.8 ms: 1.41x faster                                                       |
| pyflate                  | 402 ms                                                      | 292 ms: 1.38x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.53 ms: 1.37x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 452 ms: 1.36x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 130 us: 1.36x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 545 ms: 1.32x faster                                                        |
| scimark_sor              | 105 ms                                                      | 80.9 ms: 1.30x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 44.8 ms: 1.30x faster                                                       |
| sympy_sum                | 105 ms                                                      | 81.8 ms: 1.29x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.34 sec: 1.28x faster                                                      |
| regex_compile            | 102 ms                                                      | 80.4 ms: 1.27x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 62.3 ms: 1.27x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.88 ms: 1.23x faster                                                       |
| sympy_str                | 193 ms                                                      | 157 ms: 1.23x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.21x faster                                                       |
| mypy2                    | 347 ms                                                      | 286 ms: 1.21x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 12.4 ms: 1.21x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.56 sec: 1.21x faster                                                      |
| pycparser                | 905 ms                                                      | 751 ms: 1.21x faster                                                        |
| pprint_safe_repr         | 594 ms                                                      | 496 ms: 1.20x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.02 sec: 1.20x faster                                                      |
| sympy_expand             | 320 ms                                                      | 268 ms: 1.19x faster                                                        |
| float                    | 61.7 ms                                                     | 52.1 ms: 1.19x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 24.5 us: 1.18x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 33.3 ms: 1.18x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 41.4 ms: 1.17x faster                                                       |
| coroutines               | 15.5 ms                                                     | 13.2 ms: 1.17x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 177 ms: 1.17x faster                                                        |
| nqueens                  | 68.3 ms                                                     | 59.4 ms: 1.15x faster                                                       |
| deepcopy                 | 259 us                                                      | 226 us: 1.15x faster                                                        |
| dask                     | 305 ms                                                      | 266 ms: 1.14x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.8 ms: 1.14x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.45 sec: 1.13x faster                                                      |
| 2to3                     | 239 ms                                                      | 212 ms: 1.12x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.12 us: 1.12x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.98 us: 1.12x faster                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.40 ms: 1.11x faster                                                       |
| regex_dna                | 129 ms                                                      | 117 ms: 1.11x faster                                                        |
| tornado_http             | 106 ms                                                      | 95.6 ms: 1.11x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 739 us: 1.08x faster                                                        |
| json                     | 3.10 ms                                                     | 2.87 ms: 1.08x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 847 us: 1.08x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 90.1 ms: 1.07x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.98 sec: 1.06x faster                                                      |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.06x faster                                                       |
| scimark_fft              | 187 ms                                                      | 178 ms: 1.05x faster                                                        |
| regex_v8                 | 15.0 ms                                                     | 14.6 ms: 1.03x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.13 us: 1.02x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.59 us: 1.02x faster                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.6 ms: 1.01x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 73.3 ms: 1.01x faster                                                       |
| fannkuch                 | 258 ms                                                      | 256 ms: 1.01x faster                                                        |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.03 us: 1.02x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.3 ms: 1.03x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 41.9 ns: 1.05x slower                                                       |
| async_generators         | 219 ms                                                      | 229 ms: 1.05x slower                                                        |
| nbody                    | 71.0 ms                                                     | 75.5 ms: 1.06x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.86 us: 1.06x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.9 ms: 1.07x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.4 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.51 ms: 1.08x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 79.8 ms: 1.10x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.0 ms: 1.20x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.66 ms: 1.22x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.20x faster                                                                |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_generate
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-c4c6321/bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.13x
