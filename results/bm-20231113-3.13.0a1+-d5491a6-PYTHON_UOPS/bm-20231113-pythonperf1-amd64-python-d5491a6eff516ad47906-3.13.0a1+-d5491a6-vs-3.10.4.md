
# Results vs. 3.10.4

- fork: python
- ref: d5491a6eff516ad47906
- machine: windows-amd64
- commit hash: d5491a6
- commit date: 2023-11-13
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.09 ms: 1.18x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.60 sec: 1.17x faster                                                      |
| tornado_http   | 106 ms                                                      | 89.8 ms: 1.18x faster                                                       |
| Geometric mean | (ref)                                                       | 1.15x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 279 ms: 1.52x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 734 ms: 1.46x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 354 ms: 1.43x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 468 ms: 1.32x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.43x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| float          | 61.7 ms                                                     | 66.0 ms: 1.07x slower                                                       |
| nbody          | 71.0 ms                                                     | 86.6 ms: 1.22x slower                                                       |
| Geometric mean | (ref)                                                       | 1.10x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 129 ms                                                      | 118 ms: 1.10x faster                                                        |
| regex_compile  | 102 ms                                                      | 95.5 ms: 1.07x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.56 ms: 1.00x faster                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.73 ms: 1.53x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 182 us: 1.42x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 147 us: 1.20x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 37.1 ms: 1.16x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.27 us: 1.10x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.60 us: 1.03x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                                       |
| pickle               | 6.87 us                                                     | 7.01 us: 1.02x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.85 us: 1.06x slower                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.75 sec: 1.06x slower                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 68.7 ms: 1.07x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 8.56 ms: 1.05x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 79.2 us: 4.25x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 58.8 ns: 1.59x faster                                                       |
| richards_super           | 50.3 ms                                                     | 32.1 ms: 1.57x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 5.73 ms: 1.53x faster                                                       |
| async_tree_none          | 424 ms                                                      | 279 ms: 1.52x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 475 ms: 1.51x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 800 us: 1.50x faster                                                        |
| generators               | 31.8 ms                                                     | 21.2 ms: 1.50x faster                                                       |
| raytrace                 | 266 ms                                                      | 178 ms: 1.50x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 734 ms: 1.46x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 354 ms: 1.43x faster                                                        |
| pickle_pure_python       | 259 us                                                      | 182 us: 1.42x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.02 ms: 1.42x faster                                                       |
| richards                 | 40.6 ms                                                     | 28.8 ms: 1.41x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 60.1 ms: 1.40x faster                                                       |
| go                       | 135 ms                                                      | 101 ms: 1.34x faster                                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 468 ms: 1.32x faster                                                        |
| deltablue                | 4.12 ms                                                     | 3.15 ms: 1.31x faster                                                       |
| chaos                    | 59.5 ms                                                     | 45.9 ms: 1.30x faster                                                       |
| scimark_sor              | 105 ms                                                      | 82.3 ms: 1.28x faster                                                       |
| pycparser                | 905 ms                                                      | 731 ms: 1.24x faster                                                        |
| sympy_sum                | 105 ms                                                      | 85.5 ms: 1.23x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 65.1 ms: 1.21x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 147 us: 1.20x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.58 us: 1.20x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 52.9 ms: 1.19x faster                                                       |
| mypy2                    | 347 ms                                                      | 293 ms: 1.18x faster                                                        |
| chameleon                | 6.02 ms                                                     | 5.09 ms: 1.18x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                                      |
| scimark_monte_carlo      | 58.0 ms                                                     | 49.2 ms: 1.18x faster                                                       |
| tornado_http             | 106 ms                                                      | 89.8 ms: 1.18x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 33.7 ms: 1.17x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.60 sec: 1.17x faster                                                      |
| xml_etree_process        | 43.1 ms                                                     | 37.1 ms: 1.16x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 25.0 us: 1.16x faster                                                       |
| pyflate                  | 402 ms                                                      | 347 ms: 1.16x faster                                                        |
| deepcopy                 | 259 us                                                      | 224 us: 1.16x faster                                                        |
| sympy_str                | 193 ms                                                      | 167 ms: 1.15x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 180 ms: 1.15x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 42.5 ms: 1.14x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.83 sec: 1.14x faster                                                      |
| deepcopy_reduce          | 2.22 us                                                     | 1.96 us: 1.13x faster                                                       |
| coroutines               | 15.5 ms                                                     | 13.8 ms: 1.13x faster                                                       |
| sympy_expand             | 320 ms                                                      | 285 ms: 1.13x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 722 us: 1.11x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.27 us: 1.10x faster                                                       |
| regex_dna                | 129 ms                                                      | 118 ms: 1.10x faster                                                        |
| regex_compile            | 102 ms                                                      | 95.5 ms: 1.07x faster                                                       |
| 2to3                     | 239 ms                                                      | 223 ms: 1.07x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 857 us: 1.07x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.15 sec: 1.06x faster                                                      |
| pprint_safe_repr         | 594 ms                                                      | 562 ms: 1.06x faster                                                        |
| mako                     | 8.98 ms                                                     | 8.56 ms: 1.05x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 92.8 ms: 1.04x faster                                                       |
| unpickle_list            | 2.68 us                                                     | 2.60 us: 1.03x faster                                                       |
| comprehensions           | 16.6 us                                                     | 16.5 us: 1.01x faster                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.56 ms: 1.00x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| xml_etree_generate       | 54.5 ms                                                     | 55.0 ms: 1.01x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.01 us: 1.02x slower                                                       |
| logging_format           | 6.73 us                                                     | 7.09 us: 1.05x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.4 ms: 1.06x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.85 us: 1.06x slower                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.75 sec: 1.06x slower                                                      |
| xml_etree_iterparse      | 64.5 ms                                                     | 68.7 ms: 1.07x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.70 us: 1.07x slower                                                       |
| float                    | 61.7 ms                                                     | 66.0 ms: 1.07x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.3 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.08x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 78.5 ms: 1.08x slower                                                       |
| async_generators         | 219 ms                                                      | 237 ms: 1.08x slower                                                        |
| nqueens                  | 68.3 ms                                                     | 74.2 ms: 1.09x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 80.3 ms: 1.09x slower                                                       |
| hexiom                   | 5.59 ms                                                     | 6.30 ms: 1.13x slower                                                       |
| scimark_fft              | 187 ms                                                      | 220 ms: 1.17x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                       |
| coverage                 | 38.4 ms                                                     | 45.4 ms: 1.18x slower                                                       |
| fannkuch                 | 258 ms                                                      | 313 ms: 1.21x slower                                                        |
| nbody                    | 71.0 ms                                                     | 86.6 ms: 1.22x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.74 ms: 1.24x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.63 ms: 1.36x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.13x faster                                                                |

Benchmark hidden because not significant (4): json, regex_v8, python_startup, unpack_sequence
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231113-3.13.0a1+-d5491a6-PYTHON_UOPS/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.06x
