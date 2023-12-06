
# Results vs. 3.10.4

- fork: python
- ref: 2dbb2e035b968811ddc0
- machine: windows-amd64
- commit hash: 2dbb2e0
- commit date: 2023-11-17
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.78 ms: 1.26x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| tornado_http   | 106 ms                                                      | 86.8 ms: 1.22x faster                                                       |
| Geometric mean | (ref)                                                       | 1.21x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 338 ms: 1.50x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 728 ms: 1.47x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 453 ms: 1.36x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.8 ms: 1.19x faster                                                       |
| nbody          | 71.0 ms                                                     | 74.6 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 80.5 ms: 1.27x faster                                                       |
| regex_dna      | 129 ms                                                      | 118 ms: 1.09x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.09x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.64 ms: 1.55x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 184 us: 1.41x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 133 us: 1.33x faster                                                        |
| tomli_loads          | 1.65 sec                                                    | 1.43 sec: 1.16x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.7 ms: 1.14x faster                                                       |
| unpickle             | 9.11 us                                                     | 7.99 us: 1.14x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.3 us: 1.07x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.2 ms: 1.05x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.6 ms: 1.01x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 54.8 ms: 1.00x slower                                                       |
| pickle               | 6.87 us                                                     | 7.02 us: 1.02x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.87 us: 1.07x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 19.2 us: 1.12x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 19.5 ms: 1.01x faster                                                       |
| python_startup_no_site | 15.3 ms                                                     | 17.7 ms: 1.15x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.49 ms: 1.38x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 74.8 us: 4.50x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.13 ms: 1.93x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 55.7 ns: 1.68x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.3 ms: 1.61x faster                                                       |
| async_tree_none          | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| raytrace                 | 266 ms                                                      | 167 ms: 1.59x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 766 us: 1.57x faster                                                        |
| comprehensions           | 16.6 us                                                     | 10.6 us: 1.57x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 459 ms: 1.56x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.64 ms: 1.55x faster                                                       |
| go                       | 135 ms                                                      | 88.0 ms: 1.54x faster                                                       |
| generators               | 31.8 ms                                                     | 20.7 ms: 1.53x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 338 ms: 1.50x faster                                                        |
| chaos                    | 59.5 ms                                                     | 40.1 ms: 1.49x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 56.9 ms: 1.48x faster                                                       |
| async_tree_io            | 1.07 sec                                                    | 728 ms: 1.47x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 986 us: 1.47x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 3.88 ms: 1.44x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 44.0 ms: 1.43x faster                                                       |
| richards                 | 40.6 ms                                                     | 28.7 ms: 1.41x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 184 us: 1.41x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 41.8 ms: 1.39x faster                                                       |
| mako                     | 8.98 ms                                                     | 6.49 ms: 1.38x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 453 ms: 1.36x faster                                                        |
| pyflate                  | 402 ms                                                      | 298 ms: 1.35x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 133 us: 1.33x faster                                                        |
| scimark_sor              | 105 ms                                                      | 81.8 ms: 1.29x faster                                                       |
| regex_compile            | 102 ms                                                      | 80.5 ms: 1.27x faster                                                       |
| sympy_sum                | 105 ms                                                      | 83.1 ms: 1.27x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.78 ms: 1.26x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.37 sec: 1.25x faster                                                      |
| spectral_norm            | 78.9 ms                                                     | 63.4 ms: 1.24x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.22x faster                                                       |
| tornado_http             | 106 ms                                                      | 86.8 ms: 1.22x faster                                                       |
| sympy_str                | 193 ms                                                      | 159 ms: 1.22x faster                                                        |
| deepcopy_memo            | 29.0 us                                                     | 23.9 us: 1.21x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 12.4 ms: 1.21x faster                                                       |
| mypy2                    | 347 ms                                                      | 287 ms: 1.21x faster                                                        |
| pycparser                | 905 ms                                                      | 751 ms: 1.20x faster                                                        |
| dask                     | 305 ms                                                      | 254 ms: 1.20x faster                                                        |
| nqueens                  | 68.3 ms                                                     | 57.3 ms: 1.19x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 40.8 ms: 1.19x faster                                                       |
| float                    | 61.7 ms                                                     | 51.8 ms: 1.19x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.18x faster                                                      |
| sqlglot_optimize         | 39.4 ms                                                     | 33.6 ms: 1.17x faster                                                       |
| deepcopy                 | 259 us                                                      | 221 us: 1.17x faster                                                        |
| sympy_expand             | 320 ms                                                      | 274 ms: 1.17x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 177 ms: 1.17x faster                                                        |
| pprint_safe_repr         | 594 ms                                                      | 510 ms: 1.17x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.80 sec: 1.16x faster                                                      |
| tomli_loads              | 1.65 sec                                                    | 1.43 sec: 1.16x faster                                                      |
| 2to3                     | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.7 ms: 1.14x faster                                                       |
| unpickle                 | 9.11 us                                                     | 7.99 us: 1.14x faster                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.37 ms: 1.13x faster                                                       |
| coroutines               | 15.5 ms                                                     | 13.8 ms: 1.12x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.98 us: 1.12x faster                                                       |
| json                     | 3.10 ms                                                     | 2.81 ms: 1.11x faster                                                       |
| regex_dna                | 129 ms                                                      | 118 ms: 1.09x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 741 us: 1.08x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 847 us: 1.08x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.3 us: 1.07x faster                                                       |
| scimark_fft              | 187 ms                                                      | 178 ms: 1.05x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 92.2 ms: 1.05x faster                                                       |
| fannkuch                 | 258 ms                                                      | 251 ms: 1.03x faster                                                        |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.6 ms: 1.01x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.21 us: 1.01x faster                                                       |
| python_startup           | 19.7 ms                                                     | 19.5 ms: 1.01x faster                                                       |
| regex_v8                 | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.68 us: 1.01x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 74.2 ms: 1.00x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 54.8 ms: 1.00x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.02 us: 1.02x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 75.5 ms: 1.04x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 62.6 ms: 1.04x slower                                                       |
| async_generators         | 219 ms                                                      | 229 ms: 1.05x slower                                                        |
| nbody                    | 71.0 ms                                                     | 74.6 ms: 1.05x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.87 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 19.2 us: 1.12x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 17.7 ms: 1.15x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.57 ms: 1.20x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.6 ms: 1.22x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 50.7 ns: 1.27x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                                |

Benchmark hidden because not significant (2): unpickle_list, pidigits
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-2dbb2e0/bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.15x
