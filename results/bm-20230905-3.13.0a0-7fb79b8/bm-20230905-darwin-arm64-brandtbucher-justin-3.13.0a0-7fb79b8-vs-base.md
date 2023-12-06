
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 1.49 sec                                                              | 1.52 sec: 1.02x slower                                        |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 282 ms                                                                | 282 ms: 1.00x faster                                          |
| float          | 55.4 ms                                                               | 57.1 ms: 1.03x slower                                         |
| nbody          | 71.2 ms                                                               | 78.8 ms: 1.11x slower                                         |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_effbot   | 2.50 ms                                                               | 2.51 ms: 1.00x slower                                         |
| regex_v8       | 16.2 ms                                                               | 16.3 ms: 1.01x slower                                         |
| regex_compile  | 77.2 ms                                                               | 81.5 ms: 1.06x slower                                         |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                              | 1.52 sec: 1.02x faster                                        |
| pickle_dict          | 18.1 us                                                               | 17.8 us: 1.02x faster                                         |
| unpickle             | 9.13 us                                                               | 9.10 us: 1.00x faster                                         |
| pickle_pure_python   | 193 us                                                                | 195 us: 1.01x slower                                          |
| json_loads           | 17.4 us                                                               | 17.6 us: 1.01x slower                                         |
| json_dumps           | 6.41 ms                                                               | 6.48 ms: 1.01x slower                                         |
| xml_etree_process    | 39.5 ms                                                               | 39.9 ms: 1.01x slower                                         |
| xml_etree_generate   | 57.3 ms                                                               | 58.0 ms: 1.01x slower                                         |
| unpickle_list        | 3.14 us                                                               | 3.18 us: 1.01x slower                                         |
| pickle_list          | 2.86 us                                                               | 2.93 us: 1.03x slower                                         |
| xml_etree_iterparse  | 75.3 ms                                                               | 77.3 ms: 1.03x slower                                         |
| unpickle_pure_python | 158 us                                                                | 164 us: 1.04x slower                                          |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                  |

Benchmark hidden because not significant (2): pickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                               | 11.7 ms: 1.00x slower                                         |
| python_startup_no_site | 9.54 ms                                                               | 9.58 ms: 1.00x slower                                         |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 7.47 ms                                                               | 7.66 ms: 1.03x slower                                         |

All benchmarks:
===============

| Benchmark                | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| unpack_sequence          | 28.8 ns                                                               | 26.4 ns: 1.09x faster                                         |
| tomli_loads              | 1.54 sec                                                              | 1.52 sec: 1.02x faster                                        |
| pickle_dict              | 18.1 us                                                               | 17.8 us: 1.02x faster                                         |
| telco                    | 4.65 ms                                                               | 4.59 ms: 1.01x faster                                         |
| pyflate                  | 342 ms                                                                | 340 ms: 1.00x faster                                          |
| unpickle                 | 9.13 us                                                               | 9.10 us: 1.00x faster                                         |
| pidigits                 | 282 ms                                                                | 282 ms: 1.00x faster                                          |
| create_gc_cycles         | 697 us                                                                | 698 us: 1.00x slower                                          |
| python_startup           | 11.7 ms                                                               | 11.7 ms: 1.00x slower                                         |
| regex_effbot             | 2.50 ms                                                               | 2.51 ms: 1.00x slower                                         |
| sqlite_synth             | 1.60 us                                                               | 1.61 us: 1.00x slower                                         |
| python_startup_no_site   | 9.54 ms                                                               | 9.58 ms: 1.00x slower                                         |
| logging_silent           | 71.9 ns                                                               | 72.4 ns: 1.01x slower                                         |
| logging_format           | 3.87 us                                                               | 3.89 us: 1.01x slower                                         |
| coroutines               | 17.9 ms                                                               | 18.0 ms: 1.01x slower                                         |
| pickle_pure_python       | 193 us                                                                | 195 us: 1.01x slower                                          |
| logging_simple           | 3.59 us                                                               | 3.62 us: 1.01x slower                                         |
| richards_super           | 37.4 ms                                                               | 37.7 ms: 1.01x slower                                         |
| json_loads               | 17.4 us                                                               | 17.6 us: 1.01x slower                                         |
| json_dumps               | 6.41 ms                                                               | 6.48 ms: 1.01x slower                                         |
| regex_v8                 | 16.2 ms                                                               | 16.3 ms: 1.01x slower                                         |
| richards                 | 33.9 ms                                                               | 34.2 ms: 1.01x slower                                         |
| async_tree_io            | 682 ms                                                                | 690 ms: 1.01x slower                                          |
| deepcopy_reduce          | 2.01 us                                                               | 2.03 us: 1.01x slower                                         |
| xml_etree_process        | 39.5 ms                                                               | 39.9 ms: 1.01x slower                                         |
| xml_etree_generate       | 57.3 ms                                                               | 58.0 ms: 1.01x slower                                         |
| unpickle_list            | 3.14 us                                                               | 3.18 us: 1.01x slower                                         |
| json                     | 2.99 ms                                                               | 3.03 ms: 1.01x slower                                         |
| scimark_sor              | 105 ms                                                                | 107 ms: 1.01x slower                                          |
| dulwich_log              | 30.5 ms                                                               | 31.0 ms: 1.01x slower                                         |
| raytrace                 | 177 ms                                                                | 180 ms: 1.02x slower                                          |
| fannkuch                 | 284 ms                                                                | 289 ms: 1.02x slower                                          |
| sqlglot_transpile        | 981 us                                                                | 997 us: 1.02x slower                                          |
| sqlglot_parse            | 805 us                                                                | 819 us: 1.02x slower                                          |
| deepcopy                 | 225 us                                                                | 229 us: 1.02x slower                                          |
| async_generators         | 307 ms                                                                | 312 ms: 1.02x slower                                          |
| docutils                 | 1.49 sec                                                              | 1.52 sec: 1.02x slower                                        |
| generators               | 24.5 ms                                                               | 25.1 ms: 1.02x slower                                         |
| pprint_safe_repr         | 496 ms                                                                | 508 ms: 1.02x slower                                          |
| mako                     | 7.47 ms                                                               | 7.66 ms: 1.03x slower                                         |
| scimark_monte_carlo      | 45.3 ms                                                               | 46.5 ms: 1.03x slower                                         |
| pickle_list              | 2.86 us                                                               | 2.93 us: 1.03x slower                                         |
| xml_etree_iterparse      | 75.3 ms                                                               | 77.3 ms: 1.03x slower                                         |
| pprint_pformat           | 1.01 sec                                                              | 1.04 sec: 1.03x slower                                        |
| go                       | 105 ms                                                                | 108 ms: 1.03x slower                                          |
| float                    | 55.4 ms                                                               | 57.1 ms: 1.03x slower                                         |
| deltablue                | 2.43 ms                                                               | 2.50 ms: 1.03x slower                                         |
| sqlglot_normalize        | 187 ms                                                                | 193 ms: 1.03x slower                                          |
| mdp                      | 1.61 sec                                                              | 1.66 sec: 1.03x slower                                        |
| scimark_lu               | 70.8 ms                                                               | 73.2 ms: 1.03x slower                                         |
| sqlglot_optimize         | 34.2 ms                                                               | 35.4 ms: 1.03x slower                                         |
| crypto_pyaes             | 46.9 ms                                                               | 48.6 ms: 1.04x slower                                         |
| typing_runtime_protocols | 92.1 us                                                               | 95.7 us: 1.04x slower                                         |
| bench_mp_pool            | 45.8 ms                                                               | 47.6 ms: 1.04x slower                                         |
| unpickle_pure_python     | 158 us                                                                | 164 us: 1.04x slower                                          |
| spectral_norm            | 71.3 ms                                                               | 74.3 ms: 1.04x slower                                         |
| chaos                    | 40.5 ms                                                               | 42.3 ms: 1.04x slower                                         |
| deepcopy_memo            | 24.3 us                                                               | 25.5 us: 1.05x slower                                         |
| scimark_fft              | 199 ms                                                                | 209 ms: 1.05x slower                                          |
| regex_compile            | 77.2 ms                                                               | 81.5 ms: 1.06x slower                                         |
| meteor_contest           | 74.1 ms                                                               | 78.5 ms: 1.06x slower                                         |
| bench_thread_pool        | 481 us                                                                | 512 us: 1.07x slower                                          |
| scimark_sparse_mat_mult  | 3.11 ms                                                               | 3.35 ms: 1.08x slower                                         |
| hexiom                   | 4.72 ms                                                               | 5.20 ms: 1.10x slower                                         |
| nqueens                  | 58.6 ms                                                               | 64.7 ms: 1.10x slower                                         |
| nbody                    | 71.2 ms                                                               | 78.8 ms: 1.11x slower                                         |
| comprehensions           | 14.6 us                                                               | 16.8 us: 1.14x slower                                         |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (15): asyncio_tcp, coverage, pickle, gc_traversal, regex_dna, asyncio_tcp_ssl, dask, pycparser, async_tree_cpu_io_mixed, pathlib, xml_etree_parse, async_tree_memoization, async_tree_none, tornado_http, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
