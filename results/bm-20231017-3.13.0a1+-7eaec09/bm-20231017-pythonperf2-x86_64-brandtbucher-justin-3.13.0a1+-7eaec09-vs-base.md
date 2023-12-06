
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.88 sec                                                                     | 2.92 sec: 1.01x slower                                               |
| Geometric mean | (ref)                                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 81.4 ms                                                                      | 78.4 ms: 1.04x faster                                                |
| pidigits       | 265 ms                                                                       | 264 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                                        | 1.01x faster                                                         |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 147 ms                                                                       | 150 ms: 1.02x slower                                                 |
| regex_v8       | 24.9 ms                                                                      | 25.5 ms: 1.02x slower                                                |
| regex_dna      | 238 ms                                                                       | 247 ms: 1.04x slower                                                 |
| Geometric mean | (ref)                                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| xml_etree_iterparse  | 107 ms                                                                       | 105 ms: 1.01x faster                                                 |
| pickle_dict          | 32.0 us                                                                      | 31.8 us: 1.01x faster                                                |
| pickle_pure_python   | 314 us                                                                       | 315 us: 1.00x slower                                                 |
| pickle               | 10.3 us                                                                      | 10.3 us: 1.01x slower                                                |
| xml_etree_generate   | 86.5 ms                                                                      | 87.1 ms: 1.01x slower                                                |
| json_dumps           | 10.5 ms                                                                      | 10.6 ms: 1.01x slower                                                |
| json_loads           | 24.0 us                                                                      | 24.4 us: 1.01x slower                                                |
| xml_etree_process    | 58.8 ms                                                                      | 59.8 ms: 1.02x slower                                                |
| tomli_loads          | 2.23 sec                                                                     | 2.27 sec: 1.02x slower                                               |
| unpickle             | 14.4 us                                                                      | 14.7 us: 1.02x slower                                                |
| unpickle_list        | 4.65 us                                                                      | 4.75 us: 1.02x slower                                                |
| xml_etree_parse      | 146 ms                                                                       | 150 ms: 1.03x slower                                                 |
| unpickle_pure_python | 225 us                                                                       | 237 us: 1.05x slower                                                 |
| Geometric mean       | (ref)                                                                        | 1.01x slower                                                         |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                                      | 12.7 ms: 1.01x slower                                                |
| python_startup_no_site | 8.68 ms                                                                      | 8.75 ms: 1.01x slower                                                |
| Geometric mean         | (ref)                                                                        | 1.01x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.2 ms                                                                      | 10.6 ms: 1.03x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231016-pythonperf2-x86_64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:----------------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| create_gc_cycles         | 1.59 ms                                                                      | 1.53 ms: 1.04x faster                                                |
| float                    | 81.4 ms                                                                      | 78.4 ms: 1.04x faster                                                |
| logging_simple           | 6.92 us                                                                      | 6.73 us: 1.03x faster                                                |
| pycparser                | 1.34 sec                                                                     | 1.31 sec: 1.03x faster                                               |
| richards_super           | 59.3 ms                                                                      | 58.1 ms: 1.02x faster                                                |
| xml_etree_iterparse      | 107 ms                                                                       | 105 ms: 1.01x faster                                                 |
| richards                 | 52.7 ms                                                                      | 51.9 ms: 1.01x faster                                                |
| pyflate                  | 529 ms                                                                       | 523 ms: 1.01x faster                                                 |
| scimark_sor              | 147 ms                                                                       | 146 ms: 1.01x faster                                                 |
| pickle_dict              | 32.0 us                                                                      | 31.8 us: 1.01x faster                                                |
| deltablue                | 3.73 ms                                                                      | 3.72 ms: 1.00x faster                                                |
| go                       | 170 ms                                                                       | 170 ms: 1.00x faster                                                 |
| pidigits                 | 265 ms                                                                       | 264 ms: 1.00x faster                                                 |
| pickle_pure_python       | 314 us                                                                       | 315 us: 1.00x slower                                                 |
| python_startup           | 12.6 ms                                                                      | 12.7 ms: 1.01x slower                                                |
| pprint_safe_repr         | 832 ms                                                                       | 836 ms: 1.01x slower                                                 |
| pickle                   | 10.3 us                                                                      | 10.3 us: 1.01x slower                                                |
| sqlglot_transpile        | 1.83 ms                                                                      | 1.84 ms: 1.01x slower                                                |
| deepcopy_memo            | 38.0 us                                                                      | 38.2 us: 1.01x slower                                                |
| xml_etree_generate       | 86.5 ms                                                                      | 87.1 ms: 1.01x slower                                                |
| sqlglot_parse            | 1.42 ms                                                                      | 1.43 ms: 1.01x slower                                                |
| python_startup_no_site   | 8.68 ms                                                                      | 8.75 ms: 1.01x slower                                                |
| fannkuch                 | 396 ms                                                                       | 400 ms: 1.01x slower                                                 |
| asyncio_tcp              | 366 ms                                                                       | 369 ms: 1.01x slower                                                 |
| dulwich_log              | 69.1 ms                                                                      | 69.7 ms: 1.01x slower                                                |
| json_dumps               | 10.5 ms                                                                      | 10.6 ms: 1.01x slower                                                |
| deepcopy_reduce          | 3.31 us                                                                      | 3.35 us: 1.01x slower                                                |
| json                     | 5.06 ms                                                                      | 5.12 ms: 1.01x slower                                                |
| spectral_norm            | 91.7 ms                                                                      | 92.8 ms: 1.01x slower                                                |
| telco                    | 8.06 ms                                                                      | 8.16 ms: 1.01x slower                                                |
| docutils                 | 2.88 sec                                                                     | 2.92 sec: 1.01x slower                                               |
| json_loads               | 24.0 us                                                                      | 24.4 us: 1.01x slower                                                |
| pathlib                  | 19.3 ms                                                                      | 19.6 ms: 1.02x slower                                                |
| xml_etree_process        | 58.8 ms                                                                      | 59.8 ms: 1.02x slower                                                |
| tomli_loads              | 2.23 sec                                                                     | 2.27 sec: 1.02x slower                                               |
| unpickle                 | 14.4 us                                                                      | 14.7 us: 1.02x slower                                                |
| regex_compile            | 147 ms                                                                       | 150 ms: 1.02x slower                                                 |
| unpickle_list            | 4.65 us                                                                      | 4.75 us: 1.02x slower                                                |
| regex_v8                 | 24.9 ms                                                                      | 25.5 ms: 1.02x slower                                                |
| xml_etree_parse          | 146 ms                                                                       | 150 ms: 1.03x slower                                                 |
| meteor_contest           | 129 ms                                                                       | 132 ms: 1.03x slower                                                 |
| sqlglot_normalize        | 115 ms                                                                       | 118 ms: 1.03x slower                                                 |
| sqlglot_optimize         | 58.5 ms                                                                      | 60.1 ms: 1.03x slower                                                |
| mdp                      | 2.51 sec                                                                     | 2.59 sec: 1.03x slower                                               |
| deepcopy                 | 369 us                                                                       | 381 us: 1.03x slower                                                 |
| coroutines               | 22.4 ms                                                                      | 23.1 ms: 1.03x slower                                                |
| mako                     | 10.2 ms                                                                      | 10.6 ms: 1.03x slower                                                |
| regex_dna                | 238 ms                                                                       | 247 ms: 1.04x slower                                                 |
| gc_traversal             | 3.53 ms                                                                      | 3.66 ms: 1.04x slower                                                |
| generators               | 34.9 ms                                                                      | 36.3 ms: 1.04x slower                                                |
| mypy2                    | 369 ms                                                                       | 384 ms: 1.04x slower                                                 |
| typing_runtime_protocols | 151 us                                                                       | 157 us: 1.04x slower                                                 |
| scimark_lu               | 101 ms                                                                       | 106 ms: 1.05x slower                                                 |
| unpickle_pure_python     | 225 us                                                                       | 237 us: 1.05x slower                                                 |
| scimark_monte_carlo      | 68.3 ms                                                                      | 71.8 ms: 1.05x slower                                                |
| crypto_pyaes             | 72.6 ms                                                                      | 76.3 ms: 1.05x slower                                                |
| scimark_sparse_mat_mult  | 4.22 ms                                                                      | 4.45 ms: 1.05x slower                                                |
| async_generators         | 382 ms                                                                       | 403 ms: 1.06x slower                                                 |
| raytrace                 | 271 ms                                                                       | 286 ms: 1.06x slower                                                 |
| chaos                    | 63.4 ms                                                                      | 67.1 ms: 1.06x slower                                                |
| scimark_fft              | 319 ms                                                                       | 341 ms: 1.07x slower                                                 |
| bench_mp_pool            | 4.59 ms                                                                      | 4.97 ms: 1.08x slower                                                |
| nqueens                  | 89.2 ms                                                                      | 98.0 ms: 1.10x slower                                                |
| unpack_sequence          | 46.9 ns                                                                      | 52.5 ns: 1.12x slower                                                |
| hexiom                   | 6.40 ms                                                                      | 7.42 ms: 1.16x slower                                                |
| comprehensions           | 21.6 us                                                                      | 25.2 us: 1.17x slower                                                |
| Geometric mean           | (ref)                                                                        | 1.02x slower                                                         |

Benchmark hidden because not significant (15): logging_format, logging_silent, async_tree_cpu_io_mixed, nbody, async_tree_memoization, async_tree_io, coverage, asyncio_tcp_ssl, regex_effbot, sqlite_synth, pprint_pformat, pickle_list, async_tree_none, tornado_http, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
