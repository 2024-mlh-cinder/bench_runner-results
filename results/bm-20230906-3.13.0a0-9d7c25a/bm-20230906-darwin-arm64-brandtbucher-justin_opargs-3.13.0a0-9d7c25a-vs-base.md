
# Results vs. base

- fork: brandtbucher
- ref: justin_opargs
- machine: darwin-arm64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 1.49 sec                                                              | 1.53 sec: 1.02x slower                                               |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 282 ms                                                                | 282 ms: 1.00x faster                                                 |
| float          | 55.5 ms                                                               | 57.0 ms: 1.03x slower                                                |
| nbody          | 71.4 ms                                                               | 76.1 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 2.51 ms                                                               | 2.52 ms: 1.00x slower                                                |
| regex_v8       | 16.2 ms                                                               | 16.4 ms: 1.01x slower                                                |
| regex_dna      | 140 ms                                                                | 142 ms: 1.02x slower                                                 |
| regex_compile  | 77.3 ms                                                               | 80.4 ms: 1.04x slower                                                |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                              | 1.47 sec: 1.05x faster                                               |
| pickle_dict          | 18.0 us                                                               | 17.9 us: 1.01x faster                                                |
| pickle               | 7.42 us                                                               | 7.39 us: 1.00x faster                                                |
| json_dumps           | 6.45 ms                                                               | 6.49 ms: 1.01x slower                                                |
| unpickle_list        | 3.14 us                                                               | 3.16 us: 1.01x slower                                                |
| json_loads           | 17.5 us                                                               | 17.7 us: 1.01x slower                                                |
| pickle_pure_python   | 192 us                                                                | 194 us: 1.01x slower                                                 |
| xml_etree_parse      | 109 ms                                                                | 110 ms: 1.01x slower                                                 |
| unpickle             | 9.10 us                                                               | 9.23 us: 1.01x slower                                                |
| xml_etree_generate   | 57.1 ms                                                               | 58.0 ms: 1.02x slower                                                |
| pickle_list          | 2.85 us                                                               | 2.90 us: 1.02x slower                                                |
| unpickle_pure_python | 158 us                                                                | 161 us: 1.02x slower                                                 |
| xml_etree_process    | 39.3 ms                                                               | 40.1 ms: 1.02x slower                                                |
| xml_etree_iterparse  | 75.3 ms                                                               | 77.2 ms: 1.03x slower                                                |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup | 12.6 ms                                                               | 12.4 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                         |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 7.37 ms                                                               | 7.47 ms: 1.01x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20230905-darwin-arm64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| tomli_loads              | 1.54 sec                                                              | 1.47 sec: 1.05x faster                                               |
| pyflate                  | 342 ms                                                                | 336 ms: 1.02x faster                                                 |
| telco                    | 4.63 ms                                                               | 4.57 ms: 1.01x faster                                                |
| python_startup           | 12.6 ms                                                               | 12.4 ms: 1.01x faster                                                |
| coverage                 | 47.5 ms                                                               | 47.1 ms: 1.01x faster                                                |
| pickle_dict              | 18.0 us                                                               | 17.9 us: 1.01x faster                                                |
| pickle                   | 7.42 us                                                               | 7.39 us: 1.00x faster                                                |
| fannkuch                 | 284 ms                                                                | 283 ms: 1.00x faster                                                 |
| pidigits                 | 282 ms                                                                | 282 ms: 1.00x faster                                                 |
| gc_traversal             | 2.39 ms                                                               | 2.40 ms: 1.00x slower                                                |
| logging_format           | 3.85 us                                                               | 3.86 us: 1.00x slower                                                |
| regex_effbot             | 2.51 ms                                                               | 2.52 ms: 1.00x slower                                                |
| create_gc_cycles         | 694 us                                                                | 697 us: 1.00x slower                                                 |
| logging_simple           | 3.58 us                                                               | 3.60 us: 1.00x slower                                                |
| sqlite_synth             | 1.59 us                                                               | 1.60 us: 1.01x slower                                                |
| json_dumps               | 6.45 ms                                                               | 6.49 ms: 1.01x slower                                                |
| pycparser                | 689 ms                                                                | 694 ms: 1.01x slower                                                 |
| coroutines               | 17.9 ms                                                               | 18.0 ms: 1.01x slower                                                |
| unpickle_list            | 3.14 us                                                               | 3.16 us: 1.01x slower                                                |
| raytrace                 | 179 ms                                                                | 180 ms: 1.01x slower                                                 |
| json                     | 3.00 ms                                                               | 3.03 ms: 1.01x slower                                                |
| logging_silent           | 71.7 ns                                                               | 72.4 ns: 1.01x slower                                                |
| json_loads               | 17.5 us                                                               | 17.7 us: 1.01x slower                                                |
| dask                     | 331 ms                                                                | 335 ms: 1.01x slower                                                 |
| pickle_pure_python       | 192 us                                                                | 194 us: 1.01x slower                                                 |
| richards_super           | 37.3 ms                                                               | 37.7 ms: 1.01x slower                                                |
| async_tree_io            | 683 ms                                                                | 691 ms: 1.01x slower                                                 |
| deepcopy                 | 225 us                                                                | 228 us: 1.01x slower                                                 |
| regex_v8                 | 16.2 ms                                                               | 16.4 ms: 1.01x slower                                                |
| mako                     | 7.37 ms                                                               | 7.47 ms: 1.01x slower                                                |
| unpack_sequence          | 26.0 ns                                                               | 26.4 ns: 1.01x slower                                                |
| xml_etree_parse          | 109 ms                                                                | 110 ms: 1.01x slower                                                 |
| unpickle                 | 9.10 us                                                               | 9.23 us: 1.01x slower                                                |
| richards                 | 33.9 ms                                                               | 34.4 ms: 1.01x slower                                                |
| pprint_safe_repr         | 498 ms                                                                | 505 ms: 1.01x slower                                                 |
| dulwich_log              | 30.5 ms                                                               | 30.9 ms: 1.01x slower                                                |
| xml_etree_generate       | 57.1 ms                                                               | 58.0 ms: 1.02x slower                                                |
| pprint_pformat           | 1.01 sec                                                              | 1.03 sec: 1.02x slower                                               |
| sqlglot_parse            | 804 us                                                                | 817 us: 1.02x slower                                                 |
| deltablue                | 2.46 ms                                                               | 2.50 ms: 1.02x slower                                                |
| pickle_list              | 2.85 us                                                               | 2.90 us: 1.02x slower                                                |
| scimark_monte_carlo      | 45.4 ms                                                               | 46.2 ms: 1.02x slower                                                |
| unpickle_pure_python     | 158 us                                                                | 161 us: 1.02x slower                                                 |
| regex_dna                | 140 ms                                                                | 142 ms: 1.02x slower                                                 |
| typing_runtime_protocols | 92.6 us                                                               | 94.4 us: 1.02x slower                                                |
| scimark_sparse_mat_mult  | 3.11 ms                                                               | 3.17 ms: 1.02x slower                                                |
| xml_etree_process        | 39.3 ms                                                               | 40.1 ms: 1.02x slower                                                |
| sqlglot_transpile        | 978 us                                                                | 998 us: 1.02x slower                                                 |
| generators               | 24.5 ms                                                               | 25.0 ms: 1.02x slower                                                |
| async_generators         | 303 ms                                                                | 310 ms: 1.02x slower                                                 |
| deepcopy_reduce          | 2.00 us                                                               | 2.04 us: 1.02x slower                                                |
| go                       | 105 ms                                                                | 108 ms: 1.02x slower                                                 |
| docutils                 | 1.49 sec                                                              | 1.53 sec: 1.02x slower                                               |
| xml_etree_iterparse      | 75.3 ms                                                               | 77.2 ms: 1.03x slower                                                |
| pathlib                  | 32.0 ms                                                               | 32.8 ms: 1.03x slower                                                |
| float                    | 55.5 ms                                                               | 57.0 ms: 1.03x slower                                                |
| scimark_fft              | 199 ms                                                                | 205 ms: 1.03x slower                                                 |
| scimark_lu               | 70.8 ms                                                               | 72.9 ms: 1.03x slower                                                |
| sqlglot_normalize        | 187 ms                                                                | 193 ms: 1.03x slower                                                 |
| chaos                    | 40.6 ms                                                               | 41.8 ms: 1.03x slower                                                |
| mdp                      | 1.61 sec                                                              | 1.66 sec: 1.03x slower                                               |
| sqlglot_optimize         | 34.2 ms                                                               | 35.3 ms: 1.03x slower                                                |
| crypto_pyaes             | 46.9 ms                                                               | 48.5 ms: 1.03x slower                                                |
| bench_thread_pool        | 482 us                                                                | 500 us: 1.04x slower                                                 |
| bench_mp_pool            | 46.5 ms                                                               | 48.4 ms: 1.04x slower                                                |
| regex_compile            | 77.3 ms                                                               | 80.4 ms: 1.04x slower                                                |
| spectral_norm            | 71.3 ms                                                               | 74.7 ms: 1.05x slower                                                |
| deepcopy_memo            | 24.2 us                                                               | 25.3 us: 1.05x slower                                                |
| meteor_contest           | 73.9 ms                                                               | 78.1 ms: 1.06x slower                                                |
| nbody                    | 71.4 ms                                                               | 76.1 ms: 1.07x slower                                                |
| hexiom                   | 4.72 ms                                                               | 5.10 ms: 1.08x slower                                                |
| nqueens                  | 58.5 ms                                                               | 64.4 ms: 1.10x slower                                                |
| comprehensions           | 14.6 us                                                               | 16.6 us: 1.13x slower                                                |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                         |

Benchmark hidden because not significant (9): asyncio_tcp, scimark_sor, asyncio_tcp_ssl, async_tree_cpu_io_mixed, async_tree_memoization, python_startup_no_site, async_tree_none, tornado_http, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
