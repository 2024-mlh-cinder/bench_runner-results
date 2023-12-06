
# Results vs. 3.10.4

- fork: python
- ref: d5491a6eff516ad47906
- machine: windows-amd64
- commit hash: d5491a6
- commit date: 2023-11-13
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 210 ms: 1.14x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.82 ms: 1.25x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| tornado_http   | 106 ms                                                      | 86.4 ms: 1.22x faster                                                       |
| Geometric mean | (ref)                                                       | 1.21x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 340 ms: 1.49x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 722 ms: 1.48x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 449 ms: 1.38x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.0 ms: 1.17x faster                                                       |
| nbody          | 71.0 ms                                                     | 73.8 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 79.4 ms: 1.29x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.66 ms: 1.55x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 180 us: 1.44x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 127 us: 1.39x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 36.9 ms: 1.17x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.45 sec: 1.13x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.13 us: 1.12x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 90.7 ms: 1.07x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.8 ms: 1.03x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.61 us: 1.02x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 54.1 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 7.21 us: 1.05x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.89 us: 1.07x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 19.4 us: 1.13x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.9 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.49 ms: 1.38x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 74.5 us: 4.52x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.04 ms: 2.02x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 55.9 ns: 1.67x faster                                                       |
| richards_super           | 50.3 ms                                                     | 30.6 ms: 1.65x faster                                                       |
| raytrace                 | 266 ms                                                      | 166 ms: 1.61x faster                                                        |
| async_tree_none          | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| go                       | 135 ms                                                      | 86.0 ms: 1.57x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 766 us: 1.57x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.66 ms: 1.55x faster                                                       |
| comprehensions           | 16.6 us                                                     | 10.8 us: 1.54x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 472 ms: 1.52x faster                                                        |
| generators               | 31.8 ms                                                     | 20.9 ms: 1.52x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 340 ms: 1.49x faster                                                        |
| chaos                    | 59.5 ms                                                     | 40.1 ms: 1.49x faster                                                       |
| async_tree_io            | 1.07 sec                                                    | 722 ms: 1.48x faster                                                        |
| richards                 | 40.6 ms                                                     | 27.5 ms: 1.48x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 981 us: 1.47x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 57.1 ms: 1.47x faster                                                       |
| hexiom                   | 5.59 ms                                                     | 3.85 ms: 1.45x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 180 us: 1.44x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 44.3 ms: 1.42x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 127 us: 1.39x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.49 ms: 1.38x faster                                                       |
| pyflate                  | 402 ms                                                      | 291 ms: 1.38x faster                                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 449 ms: 1.38x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.8 ms: 1.36x faster                                                       |
| scimark_sor              | 105 ms                                                      | 80.7 ms: 1.30x faster                                                       |
| regex_compile            | 102 ms                                                      | 79.4 ms: 1.29x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 62.0 ms: 1.27x faster                                                       |
| sympy_sum                | 105 ms                                                      | 83.5 ms: 1.26x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.82 ms: 1.25x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.4 us: 1.24x faster                                                       |
| tornado_http             | 106 ms                                                      | 86.4 ms: 1.22x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| sympy_str                | 193 ms                                                      | 159 ms: 1.21x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 12.4 ms: 1.21x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.01 sec: 1.21x faster                                                      |
| mypy2                    | 347 ms                                                      | 287 ms: 1.21x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.58 us: 1.20x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 496 ms: 1.20x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 40.6 ms: 1.20x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.44 sec: 1.19x faster                                                      |
| deepcopy                 | 259 us                                                      | 219 us: 1.19x faster                                                        |
| sympy_expand             | 320 ms                                                      | 272 ms: 1.18x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 33.6 ms: 1.17x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 176 ms: 1.17x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 36.9 ms: 1.17x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.79 sec: 1.17x faster                                                      |
| float                    | 61.7 ms                                                     | 53.0 ms: 1.17x faster                                                       |
| nqueens                  | 68.3 ms                                                     | 58.6 ms: 1.17x faster                                                       |
| pycparser                | 905 ms                                                      | 784 ms: 1.15x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 1.95 us: 1.14x faster                                                       |
| coroutines               | 15.5 ms                                                     | 13.6 ms: 1.14x faster                                                       |
| 2to3                     | 239 ms                                                      | 210 ms: 1.14x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.45 sec: 1.13x faster                                                      |
| unpickle                 | 9.11 us                                                     | 8.13 us: 1.12x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 724 us: 1.11x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.43 ms: 1.10x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 844 us: 1.08x faster                                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 90.7 ms: 1.07x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                                       |
| fannkuch                 | 258 ms                                                      | 248 ms: 1.04x faster                                                        |
| scimark_fft              | 187 ms                                                      | 181 ms: 1.03x faster                                                        |
| xml_etree_iterparse      | 64.5 ms                                                     | 62.8 ms: 1.03x faster                                                       |
| unpickle_list            | 2.68 us                                                     | 2.61 us: 1.02x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.62 us: 1.02x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.22 us: 1.01x faster                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 54.1 ms: 1.01x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 74.4 ms: 1.01x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| nbody                    | 71.0 ms                                                     | 73.8 ms: 1.04x slower                                                       |
| async_generators         | 219 ms                                                      | 228 ms: 1.04x slower                                                        |
| bench_mp_pool            | 59.9 ms                                                     | 62.7 ms: 1.05x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.21 us: 1.05x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.89 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 78.6 ms: 1.08x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 44.0 ns: 1.10x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 19.4 us: 1.13x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 17.9 ms: 1.16x slower                                                       |
| coverage                 | 38.4 ms                                                     | 45.0 ms: 1.17x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.68 ms: 1.23x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                                |

Benchmark hidden because not significant (4): json, python_startup, pidigits, regex_v8
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231113-3.13.0a1+-d5491a6/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.14x
