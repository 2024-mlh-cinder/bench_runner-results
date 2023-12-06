
# Results vs. 3.10.4

- fork: mdboom
- ref: pogo2
- machine: windows-amd64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.14x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 222 ms: 1.07x faster                                         |
| chameleon      | 6.02 ms                                                     | 4.92 ms: 1.22x faster                                        |
| docutils       | 1.88 sec                                                    | 1.61 sec: 1.16x faster                                       |
| tornado_http   | 106 ms                                                      | 101 ms: 1.05x faster                                         |
| Geometric mean | (ref)                                                       | 1.12x faster                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 272 ms: 1.56x faster                                         |
| async_tree_io           | 1.07 sec                                                    | 732 ms: 1.46x faster                                         |
| async_tree_memoization  | 505 ms                                                      | 350 ms: 1.44x faster                                         |
| async_tree_cpu_io_mixed | 617 ms                                                      | 461 ms: 1.34x faster                                         |
| Geometric mean          | (ref)                                                       | 1.45x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 58.2 ms: 1.06x faster                                        |
| pidigits       | 146 ms                                                      | 148 ms: 1.01x slower                                         |
| nbody          | 71.0 ms                                                     | 85.2 ms: 1.20x slower                                        |
| Geometric mean | (ref)                                                       | 1.05x slower                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 91.7 ms: 1.12x faster                                        |
| regex_dna      | 129 ms                                                      | 122 ms: 1.06x faster                                         |
| regex_effbot   | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                        |
| regex_v8       | 15.0 ms                                                     | 23.6 ms: 1.57x slower                                        |
| Geometric mean | (ref)                                                       | 1.08x slower                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.73 ms: 1.53x faster                                        |
| pickle_pure_python   | 259 us                                                      | 181 us: 1.43x faster                                         |
| unpickle_pure_python | 177 us                                                      | 139 us: 1.27x faster                                         |
| unpickle             | 9.11 us                                                     | 8.20 us: 1.11x faster                                        |
| xml_etree_process    | 43.1 ms                                                     | 38.9 ms: 1.11x faster                                        |
| tomli_loads          | 1.65 sec                                                    | 1.51 sec: 1.09x faster                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.06x faster                                        |
| xml_etree_parse      | 96.8 ms                                                     | 92.2 ms: 1.05x faster                                        |
| pickle               | 6.87 us                                                     | 7.02 us: 1.02x slower                                        |
| xml_etree_generate   | 54.5 ms                                                     | 56.1 ms: 1.03x slower                                        |
| xml_etree_iterparse  | 64.5 ms                                                     | 67.3 ms: 1.04x slower                                        |
| pickle_dict          | 17.1 us                                                     | 18.6 us: 1.09x slower                                        |
| pickle_list          | 2.69 us                                                     | 3.31 us: 1.23x slower                                        |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                 |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.5 ms: 1.04x slower                                        |
| python_startup_no_site | 15.3 ms                                                     | 18.5 ms: 1.20x slower                                        |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.65 ms: 1.17x faster                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 80.3 us: 4.19x faster                                        |
| logging_silent           | 93.4 ns                                                     | 56.9 ns: 1.64x faster                                        |
| richards_super           | 50.3 ms                                                     | 30.9 ms: 1.63x faster                                        |
| async_tree_none          | 424 ms                                                      | 272 ms: 1.56x faster                                         |
| deltablue                | 4.12 ms                                                     | 2.67 ms: 1.54x faster                                        |
| json_dumps               | 8.77 ms                                                     | 5.73 ms: 1.53x faster                                        |
| generators               | 31.8 ms                                                     | 20.9 ms: 1.52x faster                                        |
| sqlglot_parse            | 1.20 ms                                                     | 793 us: 1.52x faster                                         |
| raytrace                 | 266 ms                                                      | 179 ms: 1.49x faster                                         |
| scimark_lu               | 84.0 ms                                                     | 56.9 ms: 1.48x faster                                        |
| async_tree_io            | 1.07 sec                                                    | 732 ms: 1.46x faster                                         |
| richards                 | 40.6 ms                                                     | 27.9 ms: 1.46x faster                                        |
| async_tree_memoization   | 505 ms                                                      | 350 ms: 1.44x faster                                         |
| pickle_pure_python       | 259 us                                                      | 181 us: 1.43x faster                                         |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.43x faster                                        |
| go                       | 135 ms                                                      | 95.3 ms: 1.42x faster                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 461 ms: 1.34x faster                                         |
| scimark_sor              | 105 ms                                                      | 78.9 ms: 1.33x faster                                        |
| asyncio_tcp              | 717 ms                                                      | 540 ms: 1.33x faster                                         |
| chaos                    | 59.5 ms                                                     | 45.5 ms: 1.31x faster                                        |
| crypto_pyaes             | 63.1 ms                                                     | 49.4 ms: 1.28x faster                                        |
| unpickle_pure_python     | 177 us                                                      | 139 us: 1.27x faster                                         |
| pycparser                | 905 ms                                                      | 715 ms: 1.27x faster                                         |
| deepcopy_memo            | 29.0 us                                                     | 23.4 us: 1.24x faster                                        |
| comprehensions           | 16.6 us                                                     | 13.4 us: 1.24x faster                                        |
| pyflate                  | 402 ms                                                      | 326 ms: 1.23x faster                                         |
| chameleon                | 6.02 ms                                                     | 4.92 ms: 1.22x faster                                        |
| sqlite_synth             | 1.90 us                                                     | 1.58 us: 1.20x faster                                        |
| sympy_sum                | 105 ms                                                      | 88.7 ms: 1.19x faster                                        |
| mypy2                    | 347 ms                                                      | 295 ms: 1.18x faster                                         |
| mako                     | 8.98 ms                                                     | 7.65 ms: 1.17x faster                                        |
| docutils                 | 1.88 sec                                                    | 1.61 sec: 1.16x faster                                       |
| coroutines               | 15.5 ms                                                     | 13.3 ms: 1.16x faster                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 50.7 ms: 1.14x faster                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.84 sec: 1.14x faster                                       |
| deepcopy                 | 259 us                                                      | 229 us: 1.13x faster                                         |
| dask                     | 305 ms                                                      | 271 ms: 1.13x faster                                         |
| sympy_str                | 193 ms                                                      | 172 ms: 1.12x faster                                         |
| sympy_integrate          | 15.0 ms                                                     | 13.4 ms: 1.12x faster                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 35.3 ms: 1.12x faster                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.10 sec: 1.12x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.54 sec: 1.12x faster                                       |
| sqlglot_normalize        | 207 ms                                                      | 185 ms: 1.12x faster                                         |
| regex_compile            | 102 ms                                                      | 91.7 ms: 1.12x faster                                        |
| pprint_safe_repr         | 594 ms                                                      | 534 ms: 1.11x faster                                         |
| deepcopy_reduce          | 2.22 us                                                     | 2.00 us: 1.11x faster                                        |
| unpickle                 | 9.11 us                                                     | 8.20 us: 1.11x faster                                        |
| sympy_expand             | 320 ms                                                      | 289 ms: 1.11x faster                                         |
| xml_etree_process        | 43.1 ms                                                     | 38.9 ms: 1.11x faster                                        |
| dulwich_log              | 48.6 ms                                                     | 44.1 ms: 1.10x faster                                        |
| hexiom                   | 5.59 ms                                                     | 5.10 ms: 1.10x faster                                        |
| tomli_loads              | 1.65 sec                                                    | 1.51 sec: 1.09x faster                                       |
| create_gc_cycles         | 800 us                                                      | 732 us: 1.09x faster                                         |
| bench_thread_pool        | 913 us                                                      | 850 us: 1.07x faster                                         |
| 2to3                     | 239 ms                                                      | 222 ms: 1.07x faster                                         |
| json                     | 3.10 ms                                                     | 2.92 ms: 1.06x faster                                        |
| regex_dna                | 129 ms                                                      | 122 ms: 1.06x faster                                         |
| float                    | 61.7 ms                                                     | 58.2 ms: 1.06x faster                                        |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.06x faster                                        |
| xml_etree_parse          | 96.8 ms                                                     | 92.2 ms: 1.05x faster                                        |
| tornado_http             | 106 ms                                                      | 101 ms: 1.05x faster                                         |
| nqueens                  | 68.3 ms                                                     | 65.9 ms: 1.04x faster                                        |
| pidigits                 | 146 ms                                                      | 148 ms: 1.01x slower                                         |
| pickle                   | 6.87 us                                                     | 7.02 us: 1.02x slower                                        |
| logging_format           | 6.73 us                                                     | 6.91 us: 1.03x slower                                        |
| xml_etree_generate       | 54.5 ms                                                     | 56.1 ms: 1.03x slower                                        |
| logging_simple           | 6.28 us                                                     | 6.46 us: 1.03x slower                                        |
| regex_effbot             | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                        |
| xml_etree_iterparse      | 64.5 ms                                                     | 67.3 ms: 1.04x slower                                        |
| python_startup           | 19.7 ms                                                     | 20.5 ms: 1.04x slower                                        |
| meteor_contest           | 73.8 ms                                                     | 79.0 ms: 1.07x slower                                        |
| async_generators         | 219 ms                                                      | 235 ms: 1.07x slower                                         |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.08x slower                                        |
| pickle_dict              | 17.1 us                                                     | 18.6 us: 1.09x slower                                        |
| fannkuch                 | 258 ms                                                      | 282 ms: 1.09x slower                                         |
| bench_mp_pool            | 59.9 ms                                                     | 66.0 ms: 1.10x slower                                        |
| spectral_norm            | 78.9 ms                                                     | 87.4 ms: 1.11x slower                                        |
| pathlib                  | 72.8 ms                                                     | 81.0 ms: 1.11x slower                                        |
| scimark_fft              | 187 ms                                                      | 219 ms: 1.17x slower                                         |
| nbody                    | 71.0 ms                                                     | 85.2 ms: 1.20x slower                                        |
| python_startup_no_site   | 15.3 ms                                                     | 18.5 ms: 1.20x slower                                        |
| coverage                 | 38.4 ms                                                     | 46.3 ms: 1.21x slower                                        |
| telco                    | 3.82 ms                                                     | 4.62 ms: 1.21x slower                                        |
| pickle_list              | 2.69 us                                                     | 3.31 us: 1.23x slower                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.29 ms: 1.23x slower                                        |
| regex_v8                 | 15.0 ms                                                     | 23.6 ms: 1.57x slower                                        |
| Geometric mean           | (ref)                                                       | 1.14x faster                                                 |

Benchmark hidden because not significant (2): unpickle_list, unpack_sequence
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-69004d6-PYTHON_UOPS/bm-20231120-pythonperf1-amd64-mdboom-pogo2-3.13.0a1+-69004d6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.08x
