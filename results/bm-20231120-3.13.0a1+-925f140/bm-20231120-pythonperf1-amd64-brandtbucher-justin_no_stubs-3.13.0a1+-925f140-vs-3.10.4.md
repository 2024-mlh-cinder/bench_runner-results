
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_stubs
- machine: windows-amd64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.17x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 227 ms: 1.05x faster                                                         |
| chameleon      | 6.02 ms                                                     | 5.02 ms: 1.20x faster                                                        |
| docutils       | 1.88 sec                                                    | 1.62 sec: 1.16x faster                                                       |
| tornado_http   | 106 ms                                                      | 92.0 ms: 1.15x faster                                                        |
| Geometric mean | (ref)                                                       | 1.14x faster                                                                 |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 281 ms: 1.51x faster                                                         |
| async_tree_memoization  | 505 ms                                                      | 357 ms: 1.41x faster                                                         |
| async_tree_io           | 1.07 sec                                                    | 757 ms: 1.41x faster                                                         |
| async_tree_cpu_io_mixed | 617 ms                                                      | 471 ms: 1.31x faster                                                         |
| Geometric mean          | (ref)                                                       | 1.41x faster                                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 52.7 ms: 1.17x faster                                                        |
| nbody          | 71.0 ms                                                     | 66.3 ms: 1.07x faster                                                        |
| pidigits       | 146 ms                                                      | 152 ms: 1.04x slower                                                         |
| Geometric mean | (ref)                                                       | 1.06x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 83.4 ms: 1.23x faster                                                        |
| regex_dna      | 129 ms                                                      | 122 ms: 1.06x faster                                                         |
| regex_effbot   | 1.56 ms                                                     | 1.71 ms: 1.10x slower                                                        |
| regex_v8       | 15.0 ms                                                     | 21.1 ms: 1.40x slower                                                        |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.98 ms: 1.47x faster                                                        |
| pickle_pure_python   | 259 us                                                      | 184 us: 1.40x faster                                                         |
| unpickle_pure_python | 177 us                                                      | 135 us: 1.31x faster                                                         |
| tomli_loads          | 1.65 sec                                                    | 1.33 sec: 1.24x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 36.8 ms: 1.17x faster                                                        |
| unpickle             | 9.11 us                                                     | 8.26 us: 1.10x faster                                                        |
| xml_etree_parse      | 96.8 ms                                                     | 95.3 ms: 1.02x faster                                                        |
| xml_etree_generate   | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                                        |
| json_loads           | 14.2 us                                                     | 14.6 us: 1.02x slower                                                        |
| pickle               | 6.87 us                                                     | 7.03 us: 1.02x slower                                                        |
| pickle_dict          | 17.1 us                                                     | 19.2 us: 1.12x slower                                                        |
| pickle_list          | 2.69 us                                                     | 3.44 us: 1.28x slower                                                        |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                 |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                                        |
| python_startup_no_site | 15.3 ms                                                     | 19.1 ms: 1.24x slower                                                        |
| Geometric mean         | (ref)                                                       | 1.15x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.28 ms: 1.43x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 77.0 us: 4.37x faster                                                        |
| deltablue                | 4.12 ms                                                     | 2.03 ms: 2.04x faster                                                        |
| richards_super           | 50.3 ms                                                     | 29.1 ms: 1.73x faster                                                        |
| logging_silent           | 93.4 ns                                                     | 58.2 ns: 1.60x faster                                                        |
| richards                 | 40.6 ms                                                     | 26.1 ms: 1.56x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 775 us: 1.55x faster                                                         |
| raytrace                 | 266 ms                                                      | 173 ms: 1.54x faster                                                         |
| async_tree_none          | 424 ms                                                      | 281 ms: 1.51x faster                                                         |
| generators               | 31.8 ms                                                     | 21.3 ms: 1.49x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.98 ms: 1.47x faster                                                        |
| comprehensions           | 16.6 us                                                     | 11.3 us: 1.46x faster                                                        |
| go                       | 135 ms                                                      | 93.1 ms: 1.45x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 58.6 ms: 1.43x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.28 ms: 1.43x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.43x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 502 ms: 1.43x faster                                                         |
| async_tree_memoization   | 505 ms                                                      | 357 ms: 1.41x faster                                                         |
| async_tree_io            | 1.07 sec                                                    | 757 ms: 1.41x faster                                                         |
| pickle_pure_python       | 259 us                                                      | 184 us: 1.40x faster                                                         |
| chaos                    | 59.5 ms                                                     | 42.5 ms: 1.40x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 46.6 ms: 1.35x faster                                                        |
| pyflate                  | 402 ms                                                      | 304 ms: 1.32x faster                                                         |
| unpickle_pure_python     | 177 us                                                      | 135 us: 1.31x faster                                                         |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 471 ms: 1.31x faster                                                         |
| pycparser                | 905 ms                                                      | 692 ms: 1.31x faster                                                         |
| hexiom                   | 5.59 ms                                                     | 4.31 ms: 1.30x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 45.1 ms: 1.29x faster                                                        |
| scimark_sor              | 105 ms                                                      | 82.6 ms: 1.27x faster                                                        |
| deepcopy_memo            | 29.0 us                                                     | 23.0 us: 1.26x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.33 sec: 1.24x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.39 sec: 1.23x faster                                                       |
| regex_compile            | 102 ms                                                      | 83.4 ms: 1.23x faster                                                        |
| sympy_sum                | 105 ms                                                      | 87.3 ms: 1.21x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.57 us: 1.20x faster                                                        |
| chameleon                | 6.02 ms                                                     | 5.02 ms: 1.20x faster                                                        |
| spectral_norm            | 78.9 ms                                                     | 66.9 ms: 1.18x faster                                                        |
| sympy_str                | 193 ms                                                      | 164 ms: 1.18x faster                                                         |
| pprint_pformat           | 1.22 sec                                                    | 1.04 sec: 1.18x faster                                                       |
| xml_etree_process        | 43.1 ms                                                     | 36.8 ms: 1.17x faster                                                        |
| float                    | 61.7 ms                                                     | 52.7 ms: 1.17x faster                                                        |
| docutils                 | 1.88 sec                                                    | 1.62 sec: 1.16x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 513 ms: 1.16x faster                                                         |
| sympy_expand             | 320 ms                                                      | 278 ms: 1.15x faster                                                         |
| tornado_http             | 106 ms                                                      | 92.0 ms: 1.15x faster                                                        |
| deepcopy                 | 259 us                                                      | 226 us: 1.15x faster                                                         |
| sympy_integrate          | 15.0 ms                                                     | 13.1 ms: 1.14x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.83 sec: 1.14x faster                                                       |
| dask                     | 305 ms                                                      | 269 ms: 1.13x faster                                                         |
| nqueens                  | 68.3 ms                                                     | 60.4 ms: 1.13x faster                                                        |
| coroutines               | 15.5 ms                                                     | 13.7 ms: 1.13x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 35.4 ms: 1.11x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 186 ms: 1.11x faster                                                         |
| deepcopy_reduce          | 2.22 us                                                     | 2.01 us: 1.11x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.26 us: 1.10x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 44.3 ms: 1.10x faster                                                        |
| nbody                    | 71.0 ms                                                     | 66.3 ms: 1.07x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 749 us: 1.07x faster                                                         |
| regex_dna                | 129 ms                                                      | 122 ms: 1.06x faster                                                         |
| 2to3                     | 239 ms                                                      | 227 ms: 1.05x faster                                                         |
| bench_thread_pool        | 913 us                                                      | 876 us: 1.04x faster                                                         |
| fannkuch                 | 258 ms                                                      | 250 ms: 1.03x faster                                                         |
| xml_etree_parse          | 96.8 ms                                                     | 95.3 ms: 1.02x faster                                                        |
| xml_etree_generate       | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                                        |
| logging_format           | 6.73 us                                                     | 6.82 us: 1.01x slower                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.71 ms: 1.02x slower                                                        |
| json_loads               | 14.2 us                                                     | 14.6 us: 1.02x slower                                                        |
| pickle                   | 6.87 us                                                     | 7.03 us: 1.02x slower                                                        |
| meteor_contest           | 73.8 ms                                                     | 76.1 ms: 1.03x slower                                                        |
| scimark_fft              | 187 ms                                                      | 194 ms: 1.04x slower                                                         |
| pidigits                 | 146 ms                                                      | 152 ms: 1.04x slower                                                         |
| python_startup           | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.71 ms: 1.10x slower                                                        |
| gc_traversal             | 1.40 ms                                                     | 1.54 ms: 1.10x slower                                                        |
| async_generators         | 219 ms                                                      | 241 ms: 1.10x slower                                                         |
| pathlib                  | 72.8 ms                                                     | 80.6 ms: 1.11x slower                                                        |
| pickle_dict              | 17.1 us                                                     | 19.2 us: 1.12x slower                                                        |
| bench_mp_pool            | 59.9 ms                                                     | 67.5 ms: 1.13x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 19.1 ms: 1.24x slower                                                        |
| telco                    | 3.82 ms                                                     | 4.76 ms: 1.25x slower                                                        |
| pickle_list              | 2.69 us                                                     | 3.44 us: 1.28x slower                                                        |
| coverage                 | 38.4 ms                                                     | 51.3 ms: 1.34x slower                                                        |
| regex_v8                 | 15.0 ms                                                     | 21.1 ms: 1.40x slower                                                        |
| Geometric mean           | (ref)                                                       | 1.17x faster                                                                 |

Benchmark hidden because not significant (6): mypy2, unpack_sequence, json, xml_etree_iterparse, logging_simple, unpickle_list
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-925f140/bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
