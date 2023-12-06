
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 66bea25
- commit date: 2023-10-29
- overall geometric mean: 1.16x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 223 ms: 1.07x faster                                        |
| chameleon      | 6.02 ms                                                     | 5.27 ms: 1.14x faster                                       |
| docutils       | 1.88 sec                                                    | 1.63 sec: 1.15x faster                                      |
| tornado_http   | 106 ms                                                      | 90.7 ms: 1.16x faster                                       |
| Geometric mean | (ref)                                                       | 1.13x faster                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 283 ms: 1.50x faster                                        |
| async_tree_io           | 1.07 sec                                                    | 763 ms: 1.40x faster                                        |
| async_tree_memoization  | 505 ms                                                      | 363 ms: 1.39x faster                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 477 ms: 1.29x faster                                        |
| Geometric mean          | (ref)                                                       | 1.40x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.7 ms: 1.13x faster                                       |
| nbody          | 71.0 ms                                                     | 72.9 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 93.3 ms: 1.10x faster                                       |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                        |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                       |
| regex_effbot   | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.85 ms: 1.50x faster                                       |
| pickle_pure_python   | 259 us                                                      | 200 us: 1.30x faster                                        |
| unpickle_pure_python | 177 us                                                      | 140 us: 1.26x faster                                        |
| unpickle             | 9.11 us                                                     | 8.17 us: 1.12x faster                                       |
| xml_etree_process    | 43.1 ms                                                     | 39.5 ms: 1.09x faster                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.9 ms: 1.04x faster                                       |
| tomli_loads          | 1.65 sec                                                    | 1.59 sec: 1.04x faster                                      |
| json_loads           | 14.2 us                                                     | 13.8 us: 1.03x faster                                       |
| pickle               | 6.87 us                                                     | 7.25 us: 1.05x slower                                       |
| xml_etree_generate   | 54.5 ms                                                     | 57.5 ms: 1.06x slower                                       |
| pickle_list          | 2.69 us                                                     | 2.84 us: 1.06x slower                                       |
| pickle_dict          | 17.1 us                                                     | 18.5 us: 1.08x slower                                       |
| Geometric mean       | (ref)                                                       | 1.07x faster                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 19.9 ms: 1.01x slower                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.0 ms: 1.18x slower                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.17 ms: 1.25x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 97.9 us: 3.44x faster                                       |
| deltablue                | 4.12 ms                                                     | 2.24 ms: 1.84x faster                                       |
| mypy2                    | 347 ms                                                      | 220 ms: 1.57x faster                                        |
| richards_super           | 50.3 ms                                                     | 32.8 ms: 1.54x faster                                       |
| async_tree_none          | 424 ms                                                      | 283 ms: 1.50x faster                                        |
| json_dumps               | 8.77 ms                                                     | 5.85 ms: 1.50x faster                                       |
| logging_silent           | 93.4 ns                                                     | 62.6 ns: 1.49x faster                                       |
| asyncio_tcp              | 717 ms                                                      | 485 ms: 1.48x faster                                        |
| scimark_lu               | 84.0 ms                                                     | 57.5 ms: 1.46x faster                                       |
| raytrace                 | 266 ms                                                      | 183 ms: 1.45x faster                                        |
| go                       | 135 ms                                                      | 94.1 ms: 1.44x faster                                       |
| comprehensions           | 16.6 us                                                     | 11.8 us: 1.41x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 763 ms: 1.40x faster                                        |
| richards                 | 40.6 ms                                                     | 29.0 ms: 1.40x faster                                       |
| async_tree_memoization   | 505 ms                                                      | 363 ms: 1.39x faster                                        |
| sqlglot_parse            | 1.20 ms                                                     | 866 us: 1.39x faster                                        |
| crypto_pyaes             | 63.1 ms                                                     | 45.7 ms: 1.38x faster                                       |
| generators               | 31.8 ms                                                     | 23.1 ms: 1.38x faster                                       |
| chaos                    | 59.5 ms                                                     | 43.4 ms: 1.37x faster                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 43.2 ms: 1.35x faster                                       |
| pyflate                  | 402 ms                                                      | 305 ms: 1.32x faster                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.10 ms: 1.32x faster                                       |
| hexiom                   | 5.59 ms                                                     | 4.28 ms: 1.31x faster                                       |
| pickle_pure_python       | 259 us                                                      | 200 us: 1.30x faster                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 477 ms: 1.29x faster                                        |
| scimark_sor              | 105 ms                                                      | 81.6 ms: 1.29x faster                                       |
| unpickle_pure_python     | 177 us                                                      | 140 us: 1.26x faster                                        |
| mako                     | 8.98 ms                                                     | 7.17 ms: 1.25x faster                                       |
| spectral_norm            | 78.9 ms                                                     | 63.5 ms: 1.24x faster                                       |
| sqlite_synth             | 1.90 us                                                     | 1.57 us: 1.21x faster                                       |
| sympy_sum                | 105 ms                                                      | 88.5 ms: 1.19x faster                                       |
| tornado_http             | 106 ms                                                      | 90.7 ms: 1.16x faster                                       |
| docutils                 | 1.88 sec                                                    | 1.63 sec: 1.15x faster                                      |
| chameleon                | 6.02 ms                                                     | 5.27 ms: 1.14x faster                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.1 ms: 1.14x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.51 sec: 1.14x faster                                      |
| float                    | 61.7 ms                                                     | 54.7 ms: 1.13x faster                                       |
| deepcopy_memo            | 29.0 us                                                     | 25.9 us: 1.12x faster                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.10 sec: 1.12x faster                                      |
| unpickle                 | 9.11 us                                                     | 8.17 us: 1.12x faster                                       |
| sympy_str                | 193 ms                                                      | 174 ms: 1.11x faster                                        |
| pprint_safe_repr         | 594 ms                                                      | 535 ms: 1.11x faster                                        |
| create_gc_cycles         | 800 us                                                      | 721 us: 1.11x faster                                        |
| regex_compile            | 102 ms                                                      | 93.3 ms: 1.10x faster                                       |
| bench_thread_pool        | 913 us                                                      | 835 us: 1.09x faster                                        |
| xml_etree_process        | 43.1 ms                                                     | 39.5 ms: 1.09x faster                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 36.3 ms: 1.09x faster                                       |
| regex_dna                | 129 ms                                                      | 120 ms: 1.08x faster                                        |
| coroutines               | 15.5 ms                                                     | 14.4 ms: 1.07x faster                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.95 sec: 1.07x faster                                      |
| sympy_expand             | 320 ms                                                      | 299 ms: 1.07x faster                                        |
| sqlglot_normalize        | 207 ms                                                      | 193 ms: 1.07x faster                                        |
| 2to3                     | 239 ms                                                      | 223 ms: 1.07x faster                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.50 ms: 1.07x faster                                       |
| dulwich_log              | 48.6 ms                                                     | 45.7 ms: 1.06x faster                                       |
| unpack_sequence          | 40.0 ns                                                     | 37.6 ns: 1.06x faster                                       |
| nqueens                  | 68.3 ms                                                     | 64.3 ms: 1.06x faster                                       |
| json                     | 3.10 ms                                                     | 2.98 ms: 1.04x faster                                       |
| xml_etree_parse          | 96.8 ms                                                     | 92.9 ms: 1.04x faster                                       |
| tomli_loads              | 1.65 sec                                                    | 1.59 sec: 1.04x faster                                      |
| scimark_fft              | 187 ms                                                      | 180 ms: 1.04x faster                                        |
| deepcopy                 | 259 us                                                      | 252 us: 1.03x faster                                        |
| json_loads               | 14.2 us                                                     | 13.8 us: 1.03x faster                                       |
| fannkuch                 | 258 ms                                                      | 254 ms: 1.01x faster                                        |
| regex_v8                 | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                       |
| python_startup           | 19.7 ms                                                     | 19.9 ms: 1.01x slower                                       |
| deepcopy_reduce          | 2.22 us                                                     | 2.26 us: 1.02x slower                                       |
| meteor_contest           | 73.8 ms                                                     | 75.4 ms: 1.02x slower                                       |
| regex_effbot             | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                       |
| nbody                    | 71.0 ms                                                     | 72.9 ms: 1.03x slower                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.2 ms: 1.05x slower                                       |
| pickle                   | 6.87 us                                                     | 7.25 us: 1.05x slower                                       |
| xml_etree_generate       | 54.5 ms                                                     | 57.5 ms: 1.06x slower                                       |
| pickle_list              | 2.69 us                                                     | 2.84 us: 1.06x slower                                       |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.07x slower                                       |
| pickle_dict              | 17.1 us                                                     | 18.5 us: 1.08x slower                                       |
| logging_format           | 6.73 us                                                     | 7.37 us: 1.10x slower                                       |
| pathlib                  | 72.8 ms                                                     | 80.0 ms: 1.10x slower                                       |
| logging_simple           | 6.28 us                                                     | 6.90 us: 1.10x slower                                       |
| async_generators         | 219 ms                                                      | 246 ms: 1.12x slower                                        |
| python_startup_no_site   | 15.3 ms                                                     | 18.0 ms: 1.18x slower                                       |
| telco                    | 3.82 ms                                                     | 4.84 ms: 1.27x slower                                       |
| Geometric mean           | (ref)                                                       | 1.16x faster                                                |

Benchmark hidden because not significant (4): xml_etree_iterparse, pidigits, unpickle_list, pycparser
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, coverage, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231029-3.13.0a1+-66bea25/bm-20231029-pythonperf1-amd64-python-main-3.13.0a1+-66bea25.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.07x
