
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: 00a506a
- commit date: 2023-11-20
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 212 ms: 1.13x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.89 ms: 1.23x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.56 sec: 1.21x faster                                                      |
| tornado_http   | 106 ms                                                      | 95.4 ms: 1.11x faster                                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 261 ms: 1.62x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 335 ms: 1.51x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 712 ms: 1.50x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 454 ms: 1.36x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.50x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.3 ms: 1.20x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| nbody          | 71.0 ms                                                     | 72.4 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 82.8 ms: 1.23x faster                                                       |
| regex_dna      | 129 ms                                                      | 119 ms: 1.09x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 14.7 ms: 1.03x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.52 ms: 1.59x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 183 us: 1.41x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 130 us: 1.36x faster                                                        |
| tomli_loads          | 1.65 sec                                                    | 1.38 sec: 1.20x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.1 ms: 1.16x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.38 us: 1.09x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.8 ms: 1.01x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.75 us: 1.03x slower                                                       |
| pickle               | 6.87 us                                                     | 7.28 us: 1.06x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.86 us: 1.06x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.6 us: 1.08x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                                |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.8 ms: 1.06x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.2 ms: 1.19x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.12x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.61 ms: 1.36x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 75.1 us: 4.49x faster                                                       |
| deltablue                | 4.12 ms                                                     | 1.99 ms: 2.07x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 55.4 ns: 1.69x faster                                                       |
| raytrace                 | 266 ms                                                      | 163 ms: 1.63x faster                                                        |
| richards_super           | 50.3 ms                                                     | 31.0 ms: 1.62x faster                                                       |
| async_tree_none          | 424 ms                                                      | 261 ms: 1.62x faster                                                        |
| comprehensions           | 16.6 us                                                     | 10.2 us: 1.62x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 754 us: 1.60x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.52 ms: 1.59x faster                                                       |
| go                       | 135 ms                                                      | 85.3 ms: 1.59x faster                                                       |
| chaos                    | 59.5 ms                                                     | 38.7 ms: 1.54x faster                                                       |
| generators               | 31.8 ms                                                     | 21.0 ms: 1.51x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 335 ms: 1.51x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 712 ms: 1.50x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 962 us: 1.50x faster                                                        |
| richards                 | 40.6 ms                                                     | 27.9 ms: 1.45x faster                                                       |
| hexiom                   | 5.59 ms                                                     | 3.86 ms: 1.45x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 44.3 ms: 1.42x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 183 us: 1.41x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 60.2 ms: 1.40x faster                                                       |
| pyflate                  | 402 ms                                                      | 289 ms: 1.39x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 41.8 ms: 1.39x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 454 ms: 1.36x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 130 us: 1.36x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.61 ms: 1.36x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 544 ms: 1.32x faster                                                        |
| scimark_sor              | 105 ms                                                      | 80.3 ms: 1.31x faster                                                       |
| sympy_sum                | 105 ms                                                      | 83.4 ms: 1.26x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 62.7 ms: 1.26x faster                                                       |
| regex_compile            | 102 ms                                                      | 82.8 ms: 1.23x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 993 ms: 1.23x faster                                                        |
| chameleon                | 6.02 ms                                                     | 4.89 ms: 1.23x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.5 us: 1.23x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 12.2 ms: 1.23x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 487 ms: 1.22x faster                                                        |
| pycparser                | 905 ms                                                      | 744 ms: 1.22x faster                                                        |
| mypy2                    | 347 ms                                                      | 287 ms: 1.21x faster                                                        |
| docutils                 | 1.88 sec                                                    | 1.56 sec: 1.21x faster                                                      |
| float                    | 61.7 ms                                                     | 51.3 ms: 1.20x faster                                                       |
| deepcopy                 | 259 us                                                      | 216 us: 1.20x faster                                                        |
| sympy_str                | 193 ms                                                      | 161 ms: 1.20x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.38 sec: 1.20x faster                                                      |
| sqlglot_optimize         | 39.4 ms                                                     | 32.9 ms: 1.20x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.43 sec: 1.20x faster                                                      |
| nqueens                  | 68.3 ms                                                     | 57.3 ms: 1.19x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 175 ms: 1.18x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.1 ms: 1.16x faster                                                       |
| sympy_expand             | 320 ms                                                      | 276 ms: 1.16x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 1.92 us: 1.16x faster                                                       |
| coroutines               | 15.5 ms                                                     | 13.6 ms: 1.14x faster                                                       |
| 2to3                     | 239 ms                                                      | 212 ms: 1.13x faster                                                        |
| dask                     | 305 ms                                                      | 272 ms: 1.12x faster                                                        |
| tornado_http             | 106 ms                                                      | 95.4 ms: 1.11x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.72 us: 1.11x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.90 sec: 1.10x faster                                                      |
| dulwich_log              | 48.6 ms                                                     | 44.4 ms: 1.09x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 732 us: 1.09x faster                                                        |
| regex_dna                | 129 ms                                                      | 119 ms: 1.09x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.38 us: 1.09x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 842 us: 1.08x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.47 ms: 1.08x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.07 us: 1.03x faster                                                       |
| regex_v8                 | 15.0 ms                                                     | 14.7 ms: 1.03x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 71.9 ms: 1.03x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.56 us: 1.03x faster                                                       |
| fannkuch                 | 258 ms                                                      | 252 ms: 1.02x faster                                                        |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.8 ms: 1.01x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| nbody                    | 71.0 ms                                                     | 72.4 ms: 1.02x slower                                                       |
| unpickle_list            | 2.68 us                                                     | 2.75 us: 1.03x slower                                                       |
| scimark_fft              | 187 ms                                                      | 192 ms: 1.03x slower                                                        |
| async_generators         | 219 ms                                                      | 225 ms: 1.03x slower                                                        |
| unpack_sequence          | 40.0 ns                                                     | 41.8 ns: 1.05x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.47 ms: 1.05x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.8 ms: 1.06x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.28 us: 1.06x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.86 us: 1.06x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 64.4 ms: 1.07x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.6 us: 1.08x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 80.6 ms: 1.11x slower                                                       |
| coverage                 | 38.4 ms                                                     | 44.9 ms: 1.17x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.2 ms: 1.19x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.73 ms: 1.24x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                                |

Benchmark hidden because not significant (2): json, xml_etree_generate
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-00a506a/bm-20231120-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-00a506a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.13x
