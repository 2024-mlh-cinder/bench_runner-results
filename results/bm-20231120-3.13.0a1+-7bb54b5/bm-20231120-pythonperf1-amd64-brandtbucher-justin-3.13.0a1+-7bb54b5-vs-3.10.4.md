
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
| 2to3           | 239 ms                                                      | 219 ms: 1.09x faster                                                |
| chameleon      | 6.02 ms                                                     | 4.93 ms: 1.22x faster                                               |
| docutils       | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                              |
| tornado_http   | 106 ms                                                      | 97.4 ms: 1.08x faster                                               |
| Geometric mean | (ref)                                                       | 1.15x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 269 ms: 1.58x faster                                                |
| async_tree_memoization  | 505 ms                                                      | 342 ms: 1.48x faster                                                |
| async_tree_io           | 1.07 sec                                                    | 725 ms: 1.48x faster                                                |
| async_tree_cpu_io_mixed | 617 ms                                                      | 458 ms: 1.35x faster                                                |
| Geometric mean          | (ref)                                                       | 1.47x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 50.5 ms: 1.22x faster                                               |
| nbody          | 71.0 ms                                                     | 65.2 ms: 1.09x faster                                               |
| pidigits       | 146 ms                                                      | 151 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                       | 1.09x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 80.2 ms: 1.28x faster                                               |
| regex_dna      | 129 ms                                                      | 116 ms: 1.12x faster                                                |
| regex_v8       | 15.0 ms                                                     | 17.9 ms: 1.19x slower                                               |
| Geometric mean | (ref)                                                       | 1.05x faster                                                        |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.68 ms: 1.54x faster                                               |
| pickle_pure_python   | 259 us                                                      | 181 us: 1.43x faster                                                |
| unpickle_pure_python | 177 us                                                      | 133 us: 1.33x faster                                                |
| tomli_loads          | 1.65 sec                                                    | 1.29 sec: 1.28x faster                                              |
| xml_etree_process    | 43.1 ms                                                     | 37.3 ms: 1.15x faster                                               |
| unpickle             | 9.11 us                                                     | 8.38 us: 1.09x faster                                               |
| xml_etree_parse      | 96.8 ms                                                     | 91.4 ms: 1.06x faster                                               |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.5 ms: 1.03x faster                                               |
| json_loads           | 14.2 us                                                     | 13.9 us: 1.02x faster                                               |
| pickle               | 6.87 us                                                     | 7.11 us: 1.03x slower                                               |
| pickle_dict          | 17.1 us                                                     | 18.9 us: 1.10x slower                                               |
| pickle_list          | 2.69 us                                                     | 3.07 us: 1.14x slower                                               |
| Geometric mean       | (ref)                                                       | 1.10x faster                                                        |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                               |
| python_startup_no_site | 15.3 ms                                                     | 18.6 ms: 1.21x slower                                               |
| Geometric mean         | (ref)                                                       | 1.13x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.21 ms: 1.45x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 77.3 us: 4.36x faster                                               |
| deltablue                | 4.12 ms                                                     | 1.99 ms: 2.08x faster                                               |
| richards_super           | 50.3 ms                                                     | 29.5 ms: 1.71x faster                                               |
| logging_silent           | 93.4 ns                                                     | 56.5 ns: 1.65x faster                                               |
| async_tree_none          | 424 ms                                                      | 269 ms: 1.58x faster                                                |
| sqlglot_parse            | 1.20 ms                                                     | 764 us: 1.58x faster                                                |
| raytrace                 | 266 ms                                                      | 170 ms: 1.57x faster                                                |
| richards                 | 40.6 ms                                                     | 26.2 ms: 1.55x faster                                               |
| json_dumps               | 8.77 ms                                                     | 5.68 ms: 1.54x faster                                               |
| generators               | 31.8 ms                                                     | 21.1 ms: 1.50x faster                                               |
| go                       | 135 ms                                                      | 90.3 ms: 1.50x faster                                               |
| async_tree_memoization   | 505 ms                                                      | 342 ms: 1.48x faster                                                |
| async_tree_io            | 1.07 sec                                                    | 725 ms: 1.48x faster                                                |
| comprehensions           | 16.6 us                                                     | 11.3 us: 1.47x faster                                               |
| sqlglot_transpile        | 1.45 ms                                                     | 988 us: 1.46x faster                                                |
| mako                     | 8.98 ms                                                     | 6.21 ms: 1.45x faster                                               |
| scimark_lu               | 84.0 ms                                                     | 58.1 ms: 1.45x faster                                               |
| pickle_pure_python       | 259 us                                                      | 181 us: 1.43x faster                                                |
| chaos                    | 59.5 ms                                                     | 41.9 ms: 1.42x faster                                               |
| crypto_pyaes             | 63.1 ms                                                     | 44.9 ms: 1.40x faster                                               |
| pyflate                  | 402 ms                                                      | 293 ms: 1.37x faster                                                |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 458 ms: 1.35x faster                                                |
| scimark_sor              | 105 ms                                                      | 78.3 ms: 1.34x faster                                               |
| pycparser                | 905 ms                                                      | 674 ms: 1.34x faster                                                |
| asyncio_tcp              | 717 ms                                                      | 539 ms: 1.33x faster                                                |
| unpickle_pure_python     | 177 us                                                      | 133 us: 1.33x faster                                                |
| spectral_norm            | 78.9 ms                                                     | 59.8 ms: 1.32x faster                                               |
| hexiom                   | 5.59 ms                                                     | 4.24 ms: 1.32x faster                                               |
| deepcopy_memo            | 29.0 us                                                     | 22.0 us: 1.31x faster                                               |
| scimark_monte_carlo      | 58.0 ms                                                     | 44.9 ms: 1.29x faster                                               |
| tomli_loads              | 1.65 sec                                                    | 1.29 sec: 1.28x faster                                              |
| regex_compile            | 102 ms                                                      | 80.2 ms: 1.28x faster                                               |
| sympy_sum                | 105 ms                                                      | 84.1 ms: 1.25x faster                                               |
| mdp                      | 1.71 sec                                                    | 1.38 sec: 1.24x faster                                              |
| sqlite_synth             | 1.90 us                                                     | 1.55 us: 1.23x faster                                               |
| float                    | 61.7 ms                                                     | 50.5 ms: 1.22x faster                                               |
| chameleon                | 6.02 ms                                                     | 4.93 ms: 1.22x faster                                               |
| sympy_str                | 193 ms                                                      | 159 ms: 1.21x faster                                                |
| docutils                 | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                              |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.19x faster                                              |
| sympy_expand             | 320 ms                                                      | 269 ms: 1.19x faster                                                |
| pprint_safe_repr         | 594 ms                                                      | 503 ms: 1.18x faster                                                |
| coroutines               | 15.5 ms                                                     | 13.1 ms: 1.18x faster                                               |
| mypy2                    | 347 ms                                                      | 295 ms: 1.18x faster                                                |
| dulwich_log              | 48.6 ms                                                     | 41.4 ms: 1.18x faster                                               |
| deepcopy                 | 259 us                                                      | 222 us: 1.17x faster                                                |
| sympy_integrate          | 15.0 ms                                                     | 12.9 ms: 1.16x faster                                               |
| sqlglot_optimize         | 39.4 ms                                                     | 34.1 ms: 1.16x faster                                               |
| xml_etree_process        | 43.1 ms                                                     | 37.3 ms: 1.15x faster                                               |
| sqlglot_normalize        | 207 ms                                                      | 179 ms: 1.15x faster                                                |
| nqueens                  | 68.3 ms                                                     | 59.8 ms: 1.14x faster                                               |
| deepcopy_reduce          | 2.22 us                                                     | 1.95 us: 1.14x faster                                               |
| dask                     | 305 ms                                                      | 271 ms: 1.12x faster                                                |
| regex_dna                | 129 ms                                                      | 116 ms: 1.12x faster                                                |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.87 sec: 1.12x faster                                              |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.39 ms: 1.12x faster                                               |
| create_gc_cycles         | 800 us                                                      | 731 us: 1.09x faster                                                |
| 2to3                     | 239 ms                                                      | 219 ms: 1.09x faster                                                |
| nbody                    | 71.0 ms                                                     | 65.2 ms: 1.09x faster                                               |
| unpickle                 | 9.11 us                                                     | 8.38 us: 1.09x faster                                               |
| tornado_http             | 106 ms                                                      | 97.4 ms: 1.08x faster                                               |
| fannkuch                 | 258 ms                                                      | 241 ms: 1.07x faster                                                |
| bench_thread_pool        | 913 us                                                      | 859 us: 1.06x faster                                                |
| xml_etree_parse          | 96.8 ms                                                     | 91.4 ms: 1.06x faster                                               |
| json                     | 3.10 ms                                                     | 2.97 ms: 1.04x faster                                               |
| xml_etree_iterparse      | 64.5 ms                                                     | 62.5 ms: 1.03x faster                                               |
| json_loads               | 14.2 us                                                     | 13.9 us: 1.02x faster                                               |
| logging_format           | 6.73 us                                                     | 6.59 us: 1.02x faster                                               |
| logging_simple           | 6.28 us                                                     | 6.17 us: 1.02x faster                                               |
| meteor_contest           | 73.8 ms                                                     | 75.4 ms: 1.02x slower                                               |
| pidigits                 | 146 ms                                                      | 151 ms: 1.03x slower                                                |
| pickle                   | 6.87 us                                                     | 7.11 us: 1.03x slower                                               |
| python_startup           | 19.7 ms                                                     | 20.7 ms: 1.05x slower                                               |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                               |
| async_generators         | 219 ms                                                      | 235 ms: 1.08x slower                                                |
| pathlib                  | 72.8 ms                                                     | 79.8 ms: 1.10x slower                                               |
| bench_mp_pool            | 59.9 ms                                                     | 65.7 ms: 1.10x slower                                               |
| pickle_dict              | 17.1 us                                                     | 18.9 us: 1.10x slower                                               |
| pickle_list              | 2.69 us                                                     | 3.07 us: 1.14x slower                                               |
| coverage                 | 38.4 ms                                                     | 45.2 ms: 1.18x slower                                               |
| regex_v8                 | 15.0 ms                                                     | 17.9 ms: 1.19x slower                                               |
| python_startup_no_site   | 15.3 ms                                                     | 18.6 ms: 1.21x slower                                               |
| telco                    | 3.82 ms                                                     | 4.68 ms: 1.23x slower                                               |
| Geometric mean           | (ref)                                                       | 1.20x faster                                                        |

Benchmark hidden because not significant (5): unpack_sequence, regex_effbot, scimark_fft, unpickle_list, xml_etree_generate
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-7bb54b5/bm-20231120-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7bb54b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.14x
