
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_opargs
- machine: darwin-arm64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.02x slower
- HPT reliability: 99.55%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.53 sec: 1.01x faster                                               |
| Geometric mean | (ref)                                                  | 1.00x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 58.2 ms                                                | 57.0 ms: 1.02x faster                                                |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| nbody          | 68.6 ms                                                | 76.1 ms: 1.11x slower                                                |
| Geometric mean | (ref)                                                  | 1.03x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 142 ms: 1.06x faster                                                 |
| regex_effbot   | 2.58 ms                                                | 2.52 ms: 1.03x faster                                                |
| regex_v8       | 16.0 ms                                                | 16.4 ms: 1.02x slower                                                |
| regex_compile  | 75.8 ms                                                | 80.4 ms: 1.06x slower                                                |
| Geometric mean | (ref)                                                  | 1.00x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 3.16 us: 1.02x faster                                                |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                                |
| pickle_list          | 2.92 us                                                | 2.90 us: 1.01x faster                                                |
| pickle               | 7.45 us                                                | 7.39 us: 1.01x faster                                                |
| unpickle             | 9.26 us                                                | 9.23 us: 1.00x faster                                                |
| json_loads           | 17.6 us                                                | 17.7 us: 1.00x slower                                                |
| json_dumps           | 6.43 ms                                                | 6.49 ms: 1.01x slower                                                |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.02x slower                                                 |
| pickle_pure_python   | 188 us                                                 | 194 us: 1.03x slower                                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 77.2 ms: 1.04x slower                                                |
| xml_etree_process    | 38.5 ms                                                | 40.1 ms: 1.04x slower                                                |
| xml_etree_generate   | 55.8 ms                                                | 58.0 ms: 1.04x slower                                                |
| tomli_loads          | 1.39 sec                                               | 1.47 sec: 1.06x slower                                               |
| unpickle_pure_python | 145 us                                                 | 161 us: 1.11x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 12.4 ms: 1.08x slower                                                |
| python_startup_no_site | 9.43 ms                                                | 10.5 ms: 1.11x slower                                                |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.47 ms: 1.01x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 180 ms: 1.37x faster                                                 |
| generators               | 28.5 ms                                                | 25.0 ms: 1.14x faster                                                |
| sqlglot_parse            | 898 us                                                 | 817 us: 1.10x faster                                                 |
| unpack_sequence          | 28.8 ns                                                | 26.4 ns: 1.09x faster                                                |
| scimark_monte_carlo      | 50.1 ms                                                | 46.2 ms: 1.08x faster                                                |
| coverage                 | 51.0 ms                                                | 47.1 ms: 1.08x faster                                                |
| chaos                    | 45.2 ms                                                | 41.8 ms: 1.08x faster                                                |
| crypto_pyaes             | 52.3 ms                                                | 48.5 ms: 1.08x faster                                                |
| sqlglot_transpile        | 1.07 ms                                                | 998 us: 1.08x faster                                                 |
| asyncio_tcp              | 460 ms                                                 | 430 ms: 1.07x faster                                                 |
| regex_dna                | 151 ms                                                 | 142 ms: 1.06x faster                                                 |
| deltablue                | 2.59 ms                                                | 2.50 ms: 1.04x faster                                                |
| async_tree_none          | 262 ms                                                 | 254 ms: 1.03x faster                                                 |
| logging_format           | 3.97 us                                                | 3.86 us: 1.03x faster                                                |
| regex_effbot             | 2.58 ms                                                | 2.52 ms: 1.03x faster                                                |
| logging_simple           | 3.69 us                                                | 3.60 us: 1.03x faster                                                |
| float                    | 58.2 ms                                                | 57.0 ms: 1.02x faster                                                |
| unpickle_list            | 3.22 us                                                | 3.16 us: 1.02x faster                                                |
| mako                     | 7.57 ms                                                | 7.47 ms: 1.01x faster                                                |
| mdp                      | 1.68 sec                                               | 1.66 sec: 1.01x faster                                               |
| coroutines               | 18.2 ms                                                | 18.0 ms: 1.01x faster                                                |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                                |
| pickle_list              | 2.92 us                                                | 2.90 us: 1.01x faster                                                |
| pickle                   | 7.45 us                                                | 7.39 us: 1.01x faster                                                |
| create_gc_cycles         | 702 us                                                 | 697 us: 1.01x faster                                                 |
| json                     | 3.05 ms                                                | 3.03 ms: 1.01x faster                                                |
| docutils                 | 1.54 sec                                               | 1.53 sec: 1.01x faster                                               |
| spectral_norm            | 75.0 ms                                                | 74.7 ms: 1.00x faster                                                |
| unpickle                 | 9.26 us                                                | 9.23 us: 1.00x faster                                                |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                                |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.17 ms: 1.00x slower                                                |
| go                       | 107 ms                                                 | 108 ms: 1.00x slower                                                 |
| json_loads               | 17.6 us                                                | 17.7 us: 1.00x slower                                                |
| sqlite_synth             | 1.58 us                                                | 1.60 us: 1.01x slower                                                |
| json_dumps               | 6.43 ms                                                | 6.49 ms: 1.01x slower                                                |
| deepcopy_reduce          | 2.02 us                                                | 2.04 us: 1.01x slower                                                |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.02x slower                                                 |
| scimark_lu               | 71.7 ms                                                | 72.9 ms: 1.02x slower                                                |
| deepcopy                 | 224 us                                                 | 228 us: 1.02x slower                                                 |
| dulwich_log              | 30.3 ms                                                | 30.9 ms: 1.02x slower                                                |
| pyflate                  | 329 ms                                                 | 336 ms: 1.02x slower                                                 |
| bench_thread_pool        | 489 us                                                 | 500 us: 1.02x slower                                                 |
| async_generators         | 303 ms                                                 | 310 ms: 1.02x slower                                                 |
| pprint_pformat           | 1.00 sec                                               | 1.03 sec: 1.02x slower                                               |
| regex_v8                 | 16.0 ms                                                | 16.4 ms: 1.02x slower                                                |
| pprint_safe_repr         | 493 ms                                                 | 505 ms: 1.02x slower                                                 |
| sqlglot_optimize         | 34.3 ms                                                | 35.3 ms: 1.03x slower                                                |
| pickle_pure_python       | 188 us                                                 | 194 us: 1.03x slower                                                 |
| async_tree_io            | 669 ms                                                 | 691 ms: 1.03x slower                                                 |
| deepcopy_memo            | 24.5 us                                                | 25.3 us: 1.03x slower                                                |
| pycparser                | 670 ms                                                 | 694 ms: 1.03x slower                                                 |
| scimark_fft              | 198 ms                                                 | 205 ms: 1.04x slower                                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 77.2 ms: 1.04x slower                                                |
| xml_etree_process        | 38.5 ms                                                | 40.1 ms: 1.04x slower                                                |
| typing_runtime_protocols | 90.7 us                                                | 94.4 us: 1.04x slower                                                |
| xml_etree_generate       | 55.8 ms                                                | 58.0 ms: 1.04x slower                                                |
| sqlglot_normalize        | 186 ms                                                 | 193 ms: 1.04x slower                                                 |
| comprehensions           | 15.7 us                                                | 16.6 us: 1.05x slower                                                |
| bench_mp_pool            | 45.9 ms                                                | 48.4 ms: 1.06x slower                                                |
| tomli_loads              | 1.39 sec                                               | 1.47 sec: 1.06x slower                                               |
| regex_compile            | 75.8 ms                                                | 80.4 ms: 1.06x slower                                                |
| fannkuch                 | 267 ms                                                 | 283 ms: 1.06x slower                                                 |
| nqueens                  | 60.6 ms                                                | 64.4 ms: 1.06x slower                                                |
| async_tree_memoization   | 309 ms                                                 | 329 ms: 1.06x slower                                                 |
| logging_silent           | 67.7 ns                                                | 72.4 ns: 1.07x slower                                                |
| meteor_contest           | 72.9 ms                                                | 78.1 ms: 1.07x slower                                                |
| python_startup           | 11.5 ms                                                | 12.4 ms: 1.08x slower                                                |
| richards_super           | 34.9 ms                                                | 37.7 ms: 1.08x slower                                                |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.36 sec: 1.08x slower                                               |
| richards                 | 31.1 ms                                                | 34.4 ms: 1.11x slower                                                |
| nbody                    | 68.6 ms                                                | 76.1 ms: 1.11x slower                                                |
| python_startup_no_site   | 9.43 ms                                                | 10.5 ms: 1.11x slower                                                |
| unpickle_pure_python     | 145 us                                                 | 161 us: 1.11x slower                                                 |
| scimark_sor              | 94.1 ms                                                | 106 ms: 1.13x slower                                                 |
| pathlib                  | 28.8 ms                                                | 32.8 ms: 1.14x slower                                                |
| telco                    | 3.82 ms                                                | 4.57 ms: 1.20x slower                                                |
| hexiom                   | 4.24 ms                                                | 5.10 ms: 1.20x slower                                                |
| dask                     | 228 ms                                                 | 335 ms: 1.47x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                         |

Benchmark hidden because not significant (3): async_tree_cpu_io_mixed, tornado_http, mypy2
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.55% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
