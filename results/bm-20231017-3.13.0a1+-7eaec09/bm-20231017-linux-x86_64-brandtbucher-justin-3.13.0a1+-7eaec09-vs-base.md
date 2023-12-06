
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 2.67 sec                                                               | 2.70 sec: 1.01x slower                                         |
| tornado_http   | 96.3 ms                                                                | 98.0 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 94.4 ms                                                                | 91.9 ms: 1.03x faster                                          |
| pidigits       | 196 ms                                                                 | 195 ms: 1.00x faster                                           |
| float          | 80.6 ms                                                                | 82.4 ms: 1.02x slower                                          |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 4.14 ms                                                                | 3.51 ms: 1.18x faster                                          |
| regex_dna      | 218 ms                                                                 | 215 ms: 1.01x faster                                           |
| regex_v8       | 25.5 ms                                                                | 25.2 ms: 1.01x faster                                          |
| regex_compile  | 138 ms                                                                 | 143 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                                  | 1.04x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.16 sec                                                               | 2.06 sec: 1.05x faster                                         |
| pickle_list          | 5.13 us                                                                | 5.00 us: 1.03x faster                                          |
| pickle               | 11.5 us                                                                | 11.3 us: 1.01x faster                                          |
| json_loads           | 27.8 us                                                                | 28.0 us: 1.01x slower                                          |
| pickle_dict          | 33.6 us                                                                | 34.0 us: 1.01x slower                                          |
| pickle_pure_python   | 305 us                                                                 | 310 us: 1.01x slower                                           |
| unpickle_list        | 5.10 us                                                                | 5.17 us: 1.01x slower                                          |
| unpickle             | 15.0 us                                                                | 15.2 us: 1.01x slower                                          |
| xml_etree_generate   | 87.0 ms                                                                | 88.3 ms: 1.01x slower                                          |
| xml_etree_parse      | 158 ms                                                                 | 161 ms: 1.02x slower                                           |
| xml_etree_process    | 59.9 ms                                                                | 61.0 ms: 1.02x slower                                          |
| xml_etree_iterparse  | 106 ms                                                                 | 109 ms: 1.03x slower                                           |
| unpickle_pure_python | 223 us                                                                 | 235 us: 1.06x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                                | 10.2 ms: 1.01x slower                                          |
| python_startup_no_site | 6.85 ms                                                                | 6.94 ms: 1.01x slower                                          |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 11.7 ms                                                                | 11.5 ms: 1.01x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20231016-linux-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot             | 4.14 ms                                                                | 3.51 ms: 1.18x faster                                          |
| tomli_loads              | 2.16 sec                                                               | 2.06 sec: 1.05x faster                                         |
| scimark_fft              | 381 ms                                                                 | 365 ms: 1.04x faster                                           |
| pickle_list              | 5.13 us                                                                | 5.00 us: 1.03x faster                                          |
| nbody                    | 94.4 ms                                                                | 91.9 ms: 1.03x faster                                          |
| fannkuch                 | 418 ms                                                                 | 412 ms: 1.02x faster                                           |
| mako                     | 11.7 ms                                                                | 11.5 ms: 1.01x faster                                          |
| deepcopy_reduce          | 3.20 us                                                                | 3.16 us: 1.01x faster                                          |
| pickle                   | 11.5 us                                                                | 11.3 us: 1.01x faster                                          |
| regex_dna                | 218 ms                                                                 | 215 ms: 1.01x faster                                           |
| richards                 | 48.2 ms                                                                | 47.6 ms: 1.01x faster                                          |
| regex_v8                 | 25.5 ms                                                                | 25.2 ms: 1.01x faster                                          |
| spectral_norm            | 118 ms                                                                 | 117 ms: 1.01x faster                                           |
| sqlite_synth             | 2.84 us                                                                | 2.82 us: 1.01x faster                                          |
| coverage                 | 90.3 ms                                                                | 89.9 ms: 1.00x faster                                          |
| pidigits                 | 196 ms                                                                 | 195 ms: 1.00x faster                                           |
| asyncio_tcp_ssl          | 1.78 sec                                                               | 1.79 sec: 1.00x slower                                         |
| async_tree_io            | 1.18 sec                                                               | 1.19 sec: 1.01x slower                                         |
| json_loads               | 27.8 us                                                                | 28.0 us: 1.01x slower                                          |
| pathlib                  | 19.0 ms                                                                | 19.2 ms: 1.01x slower                                          |
| sqlglot_normalize        | 107 ms                                                                 | 109 ms: 1.01x slower                                           |
| coroutines               | 22.7 ms                                                                | 23.0 ms: 1.01x slower                                          |
| sqlglot_parse            | 1.29 ms                                                                | 1.31 ms: 1.01x slower                                          |
| python_startup           | 10.1 ms                                                                | 10.2 ms: 1.01x slower                                          |
| create_gc_cycles         | 1.45 ms                                                                | 1.46 ms: 1.01x slower                                          |
| pickle_dict              | 33.6 us                                                                | 34.0 us: 1.01x slower                                          |
| scimark_sparse_mat_mult  | 4.93 ms                                                                | 5.00 ms: 1.01x slower                                          |
| python_startup_no_site   | 6.85 ms                                                                | 6.94 ms: 1.01x slower                                          |
| async_tree_cpu_io_mixed  | 711 ms                                                                 | 720 ms: 1.01x slower                                           |
| docutils                 | 2.67 sec                                                               | 2.70 sec: 1.01x slower                                         |
| pickle_pure_python       | 305 us                                                                 | 310 us: 1.01x slower                                           |
| unpickle_list            | 5.10 us                                                                | 5.17 us: 1.01x slower                                          |
| unpickle                 | 15.0 us                                                                | 15.2 us: 1.01x slower                                          |
| xml_etree_generate       | 87.0 ms                                                                | 88.3 ms: 1.01x slower                                          |
| asyncio_tcp              | 484 ms                                                                 | 492 ms: 1.02x slower                                           |
| tornado_http             | 96.3 ms                                                                | 98.0 ms: 1.02x slower                                          |
| xml_etree_parse          | 158 ms                                                                 | 161 ms: 1.02x slower                                           |
| xml_etree_process        | 59.9 ms                                                                | 61.0 ms: 1.02x slower                                          |
| sqlglot_transpile        | 1.61 ms                                                                | 1.64 ms: 1.02x slower                                          |
| sqlglot_optimize         | 53.7 ms                                                                | 54.7 ms: 1.02x slower                                          |
| float                    | 80.6 ms                                                                | 82.4 ms: 1.02x slower                                          |
| dulwich_log              | 66.7 ms                                                                | 68.3 ms: 1.02x slower                                          |
| meteor_contest           | 109 ms                                                                 | 111 ms: 1.02x slower                                           |
| crypto_pyaes             | 72.4 ms                                                                | 74.2 ms: 1.03x slower                                          |
| telco                    | 8.34 ms                                                                | 8.56 ms: 1.03x slower                                          |
| deepcopy                 | 352 us                                                                 | 362 us: 1.03x slower                                           |
| scimark_sor              | 127 ms                                                                 | 131 ms: 1.03x slower                                           |
| xml_etree_iterparse      | 106 ms                                                                 | 109 ms: 1.03x slower                                           |
| logging_silent           | 108 ns                                                                 | 112 ns: 1.03x slower                                           |
| mdp                      | 2.53 sec                                                               | 2.61 sec: 1.03x slower                                         |
| logging_simple           | 5.89 us                                                                | 6.10 us: 1.03x slower                                          |
| mypy2                    | 343 ms                                                                 | 356 ms: 1.04x slower                                           |
| bench_thread_pool        | 812 us                                                                 | 844 us: 1.04x slower                                           |
| regex_compile            | 138 ms                                                                 | 143 ms: 1.04x slower                                           |
| chaos                    | 62.4 ms                                                                | 65.0 ms: 1.04x slower                                          |
| async_generators         | 460 ms                                                                 | 482 ms: 1.05x slower                                           |
| scimark_lu               | 116 ms                                                                 | 122 ms: 1.05x slower                                           |
| go                       | 143 ms                                                                 | 151 ms: 1.06x slower                                           |
| unpickle_pure_python     | 223 us                                                                 | 235 us: 1.06x slower                                           |
| scimark_monte_carlo      | 69.2 ms                                                                | 73.4 ms: 1.06x slower                                          |
| generators               | 29.6 ms                                                                | 31.4 ms: 1.06x slower                                          |
| pyflate                  | 468 ms                                                                 | 497 ms: 1.06x slower                                           |
| typing_runtime_protocols | 152 us                                                                 | 161 us: 1.06x slower                                           |
| logging_format           | 6.43 us                                                                | 6.85 us: 1.06x slower                                          |
| raytrace                 | 275 ms                                                                 | 293 ms: 1.07x slower                                           |
| pprint_pformat           | 1.52 sec                                                               | 1.62 sec: 1.07x slower                                         |
| pprint_safe_repr         | 744 ms                                                                 | 801 ms: 1.08x slower                                           |
| gc_traversal             | 3.63 ms                                                                | 3.95 ms: 1.09x slower                                          |
| deepcopy_memo            | 38.7 us                                                                | 42.5 us: 1.10x slower                                          |
| nqueens                  | 79.5 ms                                                                | 87.6 ms: 1.10x slower                                          |
| comprehensions           | 20.7 us                                                                | 22.9 us: 1.11x slower                                          |
| hexiom                   | 6.21 ms                                                                | 7.09 ms: 1.14x slower                                          |
| deltablue                | 3.34 ms                                                                | 3.86 ms: 1.16x slower                                          |
| unpack_sequence          | 47.1 ns                                                                | 58.0 ns: 1.23x slower                                          |
| Geometric mean           | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (7): richards_super, bench_mp_pool, json_dumps, pycparser, async_tree_memoization, json, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
