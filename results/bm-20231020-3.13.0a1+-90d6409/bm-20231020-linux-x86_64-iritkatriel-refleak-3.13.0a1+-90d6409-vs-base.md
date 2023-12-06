
# Results vs. base

- fork: iritkatriel
- ref: refleak
- machine: linux-x86_64
- commit hash: 90d6409
- commit date: 2023-10-20
- overall geometric mean: 1.01x faster
- HPT reliability: 99.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.67 sec                                                               | 2.65 sec: 1.01x faster                                         |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 187 ms: 1.04x faster                                           |
| float          | 81.7 ms                                                                | 80.2 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                                  | 1.02x faster                                                   |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.63 ms                                                                | 3.52 ms: 1.03x faster                                          |
| regex_dna      | 221 ms                                                                 | 214 ms: 1.03x faster                                           |
| regex_compile  | 137 ms                                                                 | 137 ms: 1.00x slower                                           |
| regex_v8       | 24.5 ms                                                                | 25.4 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| unpickle             | 15.0 us                                                                | 14.6 us: 1.03x faster                                          |
| pickle_dict          | 36.1 us                                                                | 35.3 us: 1.02x faster                                          |
| pickle               | 11.5 us                                                                | 11.3 us: 1.01x faster                                          |
| unpickle_pure_python | 223 us                                                                 | 220 us: 1.01x faster                                           |
| tomli_loads          | 2.15 sec                                                               | 2.12 sec: 1.01x faster                                         |
| xml_etree_process    | 59.7 ms                                                                | 59.1 ms: 1.01x faster                                          |
| json_dumps           | 10.5 ms                                                                | 10.4 ms: 1.01x faster                                          |
| xml_etree_iterparse  | 106 ms                                                                 | 105 ms: 1.01x faster                                           |
| xml_etree_parse      | 159 ms                                                                 | 158 ms: 1.01x faster                                           |
| pickle_list          | 5.14 us                                                                | 5.16 us: 1.01x slower                                          |
| pickle_pure_python   | 306 us                                                                 | 309 us: 1.01x slower                                           |
| unpickle_list        | 5.08 us                                                                | 5.18 us: 1.02x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (2): json_loads, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                                | 10.0 ms: 1.01x faster                                          |
| python_startup_no_site | 6.90 ms                                                                | 6.85 ms: 1.01x faster                                          |
| Geometric mean         | (ref)                                                                  | 1.01x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.7 ms                                                                | 11.6 ms: 1.01x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20231019-linux-x86_64-python-e9b5399bee7106beeeb3-3.13.0a1+-e9b5399 | bm-20231020-linux-x86_64-iritkatriel-refleak-3.13.0a1+-90d6409 |
|--------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| comprehensions           | 20.7 us                                                                | 16.6 us: 1.24x faster                                          |
| unpack_sequence          | 51.3 ns                                                                | 44.3 ns: 1.16x faster                                          |
| pyflate                  | 470 ms                                                                 | 451 ms: 1.04x faster                                           |
| pidigits                 | 195 ms                                                                 | 187 ms: 1.04x faster                                           |
| meteor_contest           | 110 ms                                                                 | 106 ms: 1.04x faster                                           |
| spectral_norm            | 113 ms                                                                 | 110 ms: 1.03x faster                                           |
| regex_effbot             | 3.63 ms                                                                | 3.52 ms: 1.03x faster                                          |
| regex_dna                | 221 ms                                                                 | 214 ms: 1.03x faster                                           |
| unpickle                 | 15.0 us                                                                | 14.6 us: 1.03x faster                                          |
| typing_runtime_protocols | 155 us                                                                 | 151 us: 1.03x faster                                           |
| pickle_dict              | 36.1 us                                                                | 35.3 us: 1.02x faster                                          |
| pprint_safe_repr         | 749 ms                                                                 | 734 ms: 1.02x faster                                           |
| raytrace                 | 278 ms                                                                 | 273 ms: 1.02x faster                                           |
| float                    | 81.7 ms                                                                | 80.2 ms: 1.02x faster                                          |
| richards                 | 48.4 ms                                                                | 47.5 ms: 1.02x faster                                          |
| chaos                    | 62.3 ms                                                                | 61.3 ms: 1.02x faster                                          |
| scimark_monte_carlo      | 69.5 ms                                                                | 68.5 ms: 1.02x faster                                          |
| sqlite_synth             | 2.85 us                                                                | 2.81 us: 1.01x faster                                          |
| pickle                   | 11.5 us                                                                | 11.3 us: 1.01x faster                                          |
| pprint_pformat           | 1.52 sec                                                               | 1.50 sec: 1.01x faster                                         |
| unpickle_pure_python     | 223 us                                                                 | 220 us: 1.01x faster                                           |
| tomli_loads              | 2.15 sec                                                               | 2.12 sec: 1.01x faster                                         |
| hexiom                   | 6.15 ms                                                                | 6.08 ms: 1.01x faster                                          |
| xml_etree_process        | 59.7 ms                                                                | 59.1 ms: 1.01x faster                                          |
| mako                     | 11.7 ms                                                                | 11.6 ms: 1.01x faster                                          |
| nqueens                  | 79.4 ms                                                                | 78.6 ms: 1.01x faster                                          |
| json_dumps               | 10.5 ms                                                                | 10.4 ms: 1.01x faster                                          |
| richards_super           | 54.3 ms                                                                | 53.7 ms: 1.01x faster                                          |
| fannkuch                 | 410 ms                                                                 | 406 ms: 1.01x faster                                           |
| xml_etree_iterparse      | 106 ms                                                                 | 105 ms: 1.01x faster                                           |
| python_startup           | 10.1 ms                                                                | 10.0 ms: 1.01x faster                                          |
| pathlib                  | 19.0 ms                                                                | 18.9 ms: 1.01x faster                                          |
| python_startup_no_site   | 6.90 ms                                                                | 6.85 ms: 1.01x faster                                          |
| docutils                 | 2.67 sec                                                               | 2.65 sec: 1.01x faster                                         |
| mdp                      | 2.55 sec                                                               | 2.54 sec: 1.01x faster                                         |
| xml_etree_parse          | 159 ms                                                                 | 158 ms: 1.01x faster                                           |
| dulwich_log              | 67.4 ms                                                                | 67.1 ms: 1.00x faster                                          |
| sqlglot_parse            | 1.29 ms                                                                | 1.28 ms: 1.00x faster                                          |
| crypto_pyaes             | 72.2 ms                                                                | 71.8 ms: 1.00x faster                                          |
| mypy2                    | 344 ms                                                                 | 342 ms: 1.00x faster                                           |
| sqlglot_normalize        | 107 ms                                                                 | 106 ms: 1.00x faster                                           |
| sqlglot_optimize         | 53.7 ms                                                                | 53.5 ms: 1.00x faster                                          |
| create_gc_cycles         | 1.47 ms                                                                | 1.47 ms: 1.00x faster                                          |
| generators               | 29.8 ms                                                                | 29.7 ms: 1.00x faster                                          |
| gc_traversal             | 3.87 ms                                                                | 3.87 ms: 1.00x slower                                          |
| asyncio_tcp_ssl          | 1.78 sec                                                               | 1.78 sec: 1.00x slower                                         |
| regex_compile            | 137 ms                                                                 | 137 ms: 1.00x slower                                           |
| asyncio_tcp              | 477 ms                                                                 | 480 ms: 1.00x slower                                           |
| pickle_list              | 5.14 us                                                                | 5.16 us: 1.01x slower                                          |
| deepcopy                 | 356 us                                                                 | 357 us: 1.01x slower                                           |
| async_generators         | 452 ms                                                                 | 454 ms: 1.01x slower                                           |
| scimark_lu               | 115 ms                                                                 | 115 ms: 1.01x slower                                           |
| go                       | 143 ms                                                                 | 144 ms: 1.01x slower                                           |
| pickle_pure_python       | 306 us                                                                 | 309 us: 1.01x slower                                           |
| async_tree_io            | 1.18 sec                                                               | 1.19 sec: 1.01x slower                                         |
| logging_simple           | 5.80 us                                                                | 5.87 us: 1.01x slower                                          |
| deltablue                | 3.32 ms                                                                | 3.36 ms: 1.01x slower                                          |
| unpickle_list            | 5.08 us                                                                | 5.18 us: 1.02x slower                                          |
| coroutines               | 22.3 ms                                                                | 22.9 ms: 1.03x slower                                          |
| scimark_sparse_mat_mult  | 4.63 ms                                                                | 4.76 ms: 1.03x slower                                          |
| regex_v8                 | 24.5 ms                                                                | 25.4 ms: 1.04x slower                                          |
| pycparser                | 1.17 sec                                                               | 1.21 sec: 1.04x slower                                         |
| Geometric mean           | (ref)                                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (19): logging_silent, telco, nbody, tornado_http, json_loads, logging_format, async_tree_cpu_io_mixed, sqlglot_transpile, bench_thread_pool, deepcopy_memo, xml_etree_generate, coverage, bench_mp_pool, async_tree_none, deepcopy_reduce, scimark_fft, scimark_sor, json, async_tree_memoization


# HPT report

- Reliability score: 99.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
