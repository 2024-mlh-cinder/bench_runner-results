
# Results vs. base

- fork: brandtbucher
- ref: justin_no_pic
- machine: darwin-arm64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 1.49 sec                                                              | 1.53 sec: 1.03x slower                                               |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 282 ms                                                                | 282 ms: 1.00x slower                                                 |
| float          | 55.4 ms                                                               | 57.1 ms: 1.03x slower                                                |
| nbody          | 71.4 ms                                                               | 78.8 ms: 1.10x slower                                                |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_dna      | 140 ms                                                                | 140 ms: 1.00x slower                                                 |
| regex_effbot   | 2.51 ms                                                               | 2.51 ms: 1.00x slower                                                |
| regex_v8       | 16.2 ms                                                               | 16.5 ms: 1.02x slower                                                |
| regex_compile  | 77.1 ms                                                               | 81.8 ms: 1.06x slower                                                |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle               | 7.47 us                                                               | 7.40 us: 1.01x faster                                                |
| tomli_loads          | 1.54 sec                                                              | 1.53 sec: 1.01x faster                                               |
| pickle_dict          | 18.0 us                                                               | 17.9 us: 1.00x faster                                                |
| unpickle             | 9.11 us                                                               | 9.18 us: 1.01x slower                                                |
| unpickle_list        | 3.14 us                                                               | 3.18 us: 1.01x slower                                                |
| json_loads           | 17.4 us                                                               | 17.6 us: 1.01x slower                                                |
| pickle_pure_python   | 192 us                                                                | 195 us: 1.01x slower                                                 |
| xml_etree_generate   | 57.5 ms                                                               | 58.2 ms: 1.01x slower                                                |
| xml_etree_parse      | 109 ms                                                                | 110 ms: 1.01x slower                                                 |
| xml_etree_process    | 39.4 ms                                                               | 40.0 ms: 1.01x slower                                                |
| pickle_list          | 2.85 us                                                               | 2.90 us: 1.02x slower                                                |
| json_dumps           | 6.43 ms                                                               | 6.53 ms: 1.02x slower                                                |
| xml_etree_iterparse  | 75.4 ms                                                               | 77.2 ms: 1.02x slower                                                |
| unpickle_pure_python | 158 us                                                                | 164 us: 1.04x slower                                                 |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                               | 12.6 ms: 1.06x slower                                                |
| python_startup_no_site | 9.73 ms                                                               | 10.5 ms: 1.08x slower                                                |
| Geometric mean         | (ref)                                                                 | 1.07x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 7.37 ms                                                               | 7.66 ms: 1.04x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| asyncio_tcp              | 440 ms                                                                | 413 ms: 1.07x faster                                                 |
| pickle                   | 7.47 us                                                               | 7.40 us: 1.01x faster                                                |
| telco                    | 4.65 ms                                                               | 4.62 ms: 1.01x faster                                                |
| pyflate                  | 343 ms                                                                | 341 ms: 1.01x faster                                                 |
| tomli_loads              | 1.54 sec                                                              | 1.53 sec: 1.01x faster                                               |
| pickle_dict              | 18.0 us                                                               | 17.9 us: 1.00x faster                                                |
| regex_dna                | 140 ms                                                                | 140 ms: 1.00x slower                                                 |
| pidigits                 | 282 ms                                                                | 282 ms: 1.00x slower                                                 |
| regex_effbot             | 2.51 ms                                                               | 2.51 ms: 1.00x slower                                                |
| logging_simple           | 3.60 us                                                               | 3.63 us: 1.01x slower                                                |
| coroutines               | 17.9 ms                                                               | 18.0 ms: 1.01x slower                                                |
| create_gc_cycles         | 694 us                                                                | 699 us: 1.01x slower                                                 |
| scimark_sor              | 106 ms                                                                | 106 ms: 1.01x slower                                                 |
| unpickle                 | 9.11 us                                                               | 9.18 us: 1.01x slower                                                |
| pycparser                | 690 ms                                                                | 696 ms: 1.01x slower                                                 |
| json                     | 2.99 ms                                                               | 3.01 ms: 1.01x slower                                                |
| async_tree_io            | 684 ms                                                                | 691 ms: 1.01x slower                                                 |
| logging_silent           | 71.6 ns                                                               | 72.3 ns: 1.01x slower                                                |
| dask                     | 331 ms                                                                | 334 ms: 1.01x slower                                                 |
| sqlite_synth             | 1.59 us                                                               | 1.61 us: 1.01x slower                                                |
| unpickle_list            | 3.14 us                                                               | 3.18 us: 1.01x slower                                                |
| json_loads               | 17.4 us                                                               | 17.6 us: 1.01x slower                                                |
| pickle_pure_python       | 192 us                                                                | 195 us: 1.01x slower                                                 |
| xml_etree_generate       | 57.5 ms                                                               | 58.2 ms: 1.01x slower                                                |
| xml_etree_parse          | 109 ms                                                                | 110 ms: 1.01x slower                                                 |
| deepcopy                 | 226 us                                                                | 229 us: 1.01x slower                                                 |
| xml_etree_process        | 39.4 ms                                                               | 40.0 ms: 1.01x slower                                                |
| dulwich_log              | 30.6 ms                                                               | 31.0 ms: 1.02x slower                                                |
| pprint_safe_repr         | 500 ms                                                                | 507 ms: 1.02x slower                                                 |
| raytrace                 | 178 ms                                                                | 180 ms: 1.02x slower                                                 |
| pickle_list              | 2.85 us                                                               | 2.90 us: 1.02x slower                                                |
| json_dumps               | 6.43 ms                                                               | 6.53 ms: 1.02x slower                                                |
| richards_super           | 37.4 ms                                                               | 38.0 ms: 1.02x slower                                                |
| regex_v8                 | 16.2 ms                                                               | 16.5 ms: 1.02x slower                                                |
| deepcopy_reduce          | 2.01 us                                                               | 2.04 us: 1.02x slower                                                |
| sqlglot_parse            | 803 us                                                                | 818 us: 1.02x slower                                                 |
| async_generators         | 306 ms                                                                | 312 ms: 1.02x slower                                                 |
| unpack_sequence          | 26.4 ns                                                               | 26.9 ns: 1.02x slower                                                |
| fannkuch                 | 283 ms                                                                | 289 ms: 1.02x slower                                                 |
| pprint_pformat           | 1.01 sec                                                              | 1.03 sec: 1.02x slower                                               |
| sqlglot_transpile        | 979 us                                                                | 999 us: 1.02x slower                                                 |
| generators               | 24.5 ms                                                               | 25.0 ms: 1.02x slower                                                |
| richards                 | 34.0 ms                                                               | 34.7 ms: 1.02x slower                                                |
| scimark_monte_carlo      | 45.3 ms                                                               | 46.3 ms: 1.02x slower                                                |
| xml_etree_iterparse      | 75.4 ms                                                               | 77.2 ms: 1.02x slower                                                |
| docutils                 | 1.49 sec                                                              | 1.53 sec: 1.03x slower                                               |
| mdp                      | 1.61 sec                                                              | 1.66 sec: 1.03x slower                                               |
| go                       | 105 ms                                                                | 108 ms: 1.03x slower                                                 |
| deltablue                | 2.43 ms                                                               | 2.50 ms: 1.03x slower                                                |
| typing_runtime_protocols | 92.4 us                                                               | 95.1 us: 1.03x slower                                                |
| float                    | 55.4 ms                                                               | 57.1 ms: 1.03x slower                                                |
| sqlglot_normalize        | 187 ms                                                                | 193 ms: 1.03x slower                                                 |
| scimark_lu               | 70.7 ms                                                               | 73.1 ms: 1.03x slower                                                |
| sqlglot_optimize         | 34.2 ms                                                               | 35.4 ms: 1.04x slower                                                |
| crypto_pyaes             | 47.0 ms                                                               | 48.6 ms: 1.04x slower                                                |
| bench_mp_pool            | 46.4 ms                                                               | 48.1 ms: 1.04x slower                                                |
| mako                     | 7.37 ms                                                               | 7.66 ms: 1.04x slower                                                |
| unpickle_pure_python     | 158 us                                                                | 164 us: 1.04x slower                                                 |
| spectral_norm            | 71.4 ms                                                               | 74.4 ms: 1.04x slower                                                |
| chaos                    | 40.5 ms                                                               | 42.3 ms: 1.04x slower                                                |
| bench_thread_pool        | 481 us                                                                | 503 us: 1.04x slower                                                 |
| scimark_fft              | 200 ms                                                                | 210 ms: 1.05x slower                                                 |
| deepcopy_memo            | 24.2 us                                                               | 25.5 us: 1.05x slower                                                |
| python_startup           | 11.9 ms                                                               | 12.6 ms: 1.06x slower                                                |
| meteor_contest           | 74.1 ms                                                               | 78.3 ms: 1.06x slower                                                |
| regex_compile            | 77.1 ms                                                               | 81.8 ms: 1.06x slower                                                |
| python_startup_no_site   | 9.73 ms                                                               | 10.5 ms: 1.08x slower                                                |
| scimark_sparse_mat_mult  | 3.10 ms                                                               | 3.35 ms: 1.08x slower                                                |
| hexiom                   | 4.73 ms                                                               | 5.19 ms: 1.10x slower                                                |
| nqueens                  | 58.5 ms                                                               | 64.5 ms: 1.10x slower                                                |
| nbody                    | 71.4 ms                                                               | 78.8 ms: 1.10x slower                                                |
| comprehensions           | 14.7 us                                                               | 16.7 us: 1.14x slower                                                |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                         |

Benchmark hidden because not significant (10): gc_traversal, logging_format, tornado_http, coverage, pathlib, asyncio_tcp_ssl, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
