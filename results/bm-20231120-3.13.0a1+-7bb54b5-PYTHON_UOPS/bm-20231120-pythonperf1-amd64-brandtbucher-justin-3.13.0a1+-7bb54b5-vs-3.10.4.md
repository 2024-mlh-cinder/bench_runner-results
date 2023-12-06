
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 218 ms: 1.10x faster                                                |
| chameleon      | 6.02 ms                                                     | 4.89 ms: 1.23x faster                                               |
| docutils       | 1.88 sec                                                    | 1.57 sec: 1.19x faster                                              |
| tornado_http   | 106 ms                                                      | 97.5 ms: 1.08x faster                                               |
| Geometric mean | (ref)                                                       | 1.15x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 263 ms: 1.61x faster                                                |
| async_tree_memoization  | 505 ms                                                      | 338 ms: 1.49x faster                                                |
| async_tree_io           | 1.07 sec                                                    | 721 ms: 1.48x faster                                                |
| async_tree_cpu_io_mixed | 617 ms                                                      | 450 ms: 1.37x faster                                                |
| Geometric mean          | (ref)                                                       | 1.49x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.3 ms: 1.20x faster                                               |
| nbody          | 71.0 ms                                                     | 64.6 ms: 1.10x faster                                               |
| pidigits       | 146 ms                                                      | 150 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                       | 1.09x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 81.1 ms: 1.26x faster                                               |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                                |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                               |
| regex_v8       | 15.0 ms                                                     | 17.9 ms: 1.19x slower                                               |
| Geometric mean | (ref)                                                       | 1.03x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.64 ms: 1.55x faster                                               |
| pickle_pure_python   | 259 us                                                      | 184 us: 1.41x faster                                                |
| unpickle_pure_python | 177 us                                                      | 132 us: 1.35x faster                                                |
| tomli_loads          | 1.65 sec                                                    | 1.28 sec: 1.29x faster                                              |
| xml_etree_process    | 43.1 ms                                                     | 36.8 ms: 1.17x faster                                               |
| unpickle             | 9.11 us                                                     | 8.17 us: 1.12x faster                                               |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                               |
| xml_etree_parse      | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                               |
| xml_etree_iterparse  | 64.5 ms                                                     | 61.5 ms: 1.05x faster                                               |
| pickle               | 6.87 us                                                     | 6.86 us: 1.00x faster                                               |
| pickle_dict          | 17.1 us                                                     | 18.1 us: 1.06x slower                                               |
| pickle_list          | 2.69 us                                                     | 3.19 us: 1.19x slower                                               |
| Geometric mean       | (ref)                                                       | 1.12x faster                                                        |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                               |
| python_startup_no_site | 15.3 ms                                                     | 18.7 ms: 1.22x slower                                               |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.19 ms: 1.45x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 74.3 us: 4.53x faster                                               |
| deltablue                | 4.12 ms                                                     | 2.01 ms: 2.05x faster                                               |
| richards_super           | 50.3 ms                                                     | 30.4 ms: 1.66x faster                                               |
| logging_silent           | 93.4 ns                                                     | 56.6 ns: 1.65x faster                                               |
| async_tree_none          | 424 ms                                                      | 263 ms: 1.61x faster                                                |
| sqlglot_parse            | 1.20 ms                                                     | 768 us: 1.57x faster                                                |
| json_dumps               | 8.77 ms                                                     | 5.64 ms: 1.55x faster                                               |
| raytrace                 | 266 ms                                                      | 173 ms: 1.54x faster                                                |
| generators               | 31.8 ms                                                     | 20.6 ms: 1.54x faster                                               |
| richards                 | 40.6 ms                                                     | 26.7 ms: 1.52x faster                                               |
| async_tree_memoization   | 505 ms                                                      | 338 ms: 1.49x faster                                                |
| async_tree_io            | 1.07 sec                                                    | 721 ms: 1.48x faster                                                |
| go                       | 135 ms                                                      | 91.3 ms: 1.48x faster                                               |
| comprehensions           | 16.6 us                                                     | 11.2 us: 1.48x faster                                               |
| sqlglot_transpile        | 1.45 ms                                                     | 993 us: 1.46x faster                                                |
| mako                     | 8.98 ms                                                     | 6.19 ms: 1.45x faster                                               |
| scimark_lu               | 84.0 ms                                                     | 59.1 ms: 1.42x faster                                               |
| chaos                    | 59.5 ms                                                     | 42.0 ms: 1.42x faster                                               |
| pickle_pure_python       | 259 us                                                      | 184 us: 1.41x faster                                                |
| crypto_pyaes             | 63.1 ms                                                     | 45.1 ms: 1.40x faster                                               |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 450 ms: 1.37x faster                                                |
| asyncio_tcp              | 717 ms                                                      | 524 ms: 1.37x faster                                                |
| pyflate                  | 402 ms                                                      | 295 ms: 1.36x faster                                                |
| spectral_norm            | 78.9 ms                                                     | 58.6 ms: 1.35x faster                                               |
| unpickle_pure_python     | 177 us                                                      | 132 us: 1.35x faster                                                |
| hexiom                   | 5.59 ms                                                     | 4.18 ms: 1.34x faster                                               |
| pycparser                | 905 ms                                                      | 682 ms: 1.33x faster                                                |
| deepcopy_memo            | 29.0 us                                                     | 22.1 us: 1.31x faster                                               |
| scimark_sor              | 105 ms                                                      | 80.7 ms: 1.30x faster                                               |
| tomli_loads              | 1.65 sec                                                    | 1.28 sec: 1.29x faster                                              |
| scimark_monte_carlo      | 58.0 ms                                                     | 45.4 ms: 1.28x faster                                               |
| regex_compile            | 102 ms                                                      | 81.1 ms: 1.26x faster                                               |
| sympy_sum                | 105 ms                                                      | 84.6 ms: 1.24x faster                                               |
| mdp                      | 1.71 sec                                                    | 1.38 sec: 1.24x faster                                              |
| chameleon                | 6.02 ms                                                     | 4.89 ms: 1.23x faster                                               |
| sqlite_synth             | 1.90 us                                                     | 1.55 us: 1.22x faster                                               |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.72 sec: 1.22x faster                                              |
| float                    | 61.7 ms                                                     | 51.3 ms: 1.20x faster                                               |
| sympy_str                | 193 ms                                                      | 161 ms: 1.20x faster                                                |
| pprint_pformat           | 1.22 sec                                                    | 1.02 sec: 1.20x faster                                              |
| docutils                 | 1.88 sec                                                    | 1.57 sec: 1.19x faster                                              |
| pprint_safe_repr         | 594 ms                                                      | 498 ms: 1.19x faster                                                |
| sympy_expand             | 320 ms                                                      | 269 ms: 1.19x faster                                                |
| mypy2                    | 347 ms                                                      | 294 ms: 1.18x faster                                                |
| dulwich_log              | 48.6 ms                                                     | 41.4 ms: 1.17x faster                                               |
| xml_etree_process        | 43.1 ms                                                     | 36.8 ms: 1.17x faster                                               |
| sympy_integrate          | 15.0 ms                                                     | 12.9 ms: 1.16x faster                                               |
| coroutines               | 15.5 ms                                                     | 13.4 ms: 1.16x faster                                               |
| deepcopy                 | 259 us                                                      | 224 us: 1.16x faster                                                |
| sqlglot_optimize         | 39.4 ms                                                     | 34.6 ms: 1.14x faster                                               |
| sqlglot_normalize        | 207 ms                                                      | 182 ms: 1.13x faster                                                |
| nqueens                  | 68.3 ms                                                     | 60.9 ms: 1.12x faster                                               |
| unpickle                 | 9.11 us                                                     | 8.17 us: 1.12x faster                                               |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.40 ms: 1.11x faster                                               |
| dask                     | 305 ms                                                      | 275 ms: 1.11x faster                                                |
| deepcopy_reduce          | 2.22 us                                                     | 2.01 us: 1.11x faster                                               |
| nbody                    | 71.0 ms                                                     | 64.6 ms: 1.10x faster                                               |
| 2to3                     | 239 ms                                                      | 218 ms: 1.10x faster                                                |
| create_gc_cycles         | 800 us                                                      | 732 us: 1.09x faster                                                |
| tornado_http             | 106 ms                                                      | 97.5 ms: 1.08x faster                                               |
| regex_dna                | 129 ms                                                      | 120 ms: 1.08x faster                                                |
| fannkuch                 | 258 ms                                                      | 242 ms: 1.06x faster                                                |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                               |
| xml_etree_parse          | 96.8 ms                                                     | 91.6 ms: 1.06x faster                                               |
| bench_thread_pool        | 913 us                                                      | 869 us: 1.05x faster                                                |
| xml_etree_iterparse      | 64.5 ms                                                     | 61.5 ms: 1.05x faster                                               |
| logging_format           | 6.73 us                                                     | 6.53 us: 1.03x faster                                               |
| logging_simple           | 6.28 us                                                     | 6.12 us: 1.03x faster                                               |
| pickle                   | 6.87 us                                                     | 6.86 us: 1.00x faster                                               |
| scimark_fft              | 187 ms                                                      | 188 ms: 1.00x slower                                                |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                               |
| meteor_contest           | 73.8 ms                                                     | 75.4 ms: 1.02x slower                                               |
| pidigits                 | 146 ms                                                      | 150 ms: 1.02x slower                                                |
| python_startup           | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                               |
| pickle_dict              | 17.1 us                                                     | 18.1 us: 1.06x slower                                               |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.06x slower                                               |
| async_generators         | 219 ms                                                      | 236 ms: 1.08x slower                                                |
| unpack_sequence          | 40.0 ns                                                     | 43.5 ns: 1.09x slower                                               |
| bench_mp_pool            | 59.9 ms                                                     | 66.1 ms: 1.10x slower                                               |
| pathlib                  | 72.8 ms                                                     | 81.0 ms: 1.11x slower                                               |
| pickle_list              | 2.69 us                                                     | 3.19 us: 1.19x slower                                               |
| regex_v8                 | 15.0 ms                                                     | 17.9 ms: 1.19x slower                                               |
| coverage                 | 38.4 ms                                                     | 45.9 ms: 1.20x slower                                               |
| telco                    | 3.82 ms                                                     | 4.64 ms: 1.22x slower                                               |
| python_startup_no_site   | 15.3 ms                                                     | 18.7 ms: 1.22x slower                                               |
| Geometric mean           | (ref)                                                       | 1.20x faster                                                        |

Benchmark hidden because not significant (3): unpickle_list, json, xml_etree_generate
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-7bb54b5-PYTHON_UOPS/bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.14x
