
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: darwin-arm64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.02x slower
- HPT reliability: 99.81%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.53 sec: 1.00x faster                                               |
| Geometric mean | (ref)                                                  | 1.01x faster                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 58.2 ms                                                | 57.1 ms: 1.02x faster                                                |
| nbody          | 68.6 ms                                                | 78.8 ms: 1.15x slower                                                |
| Geometric mean | (ref)                                                  | 1.04x slower                                                         |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 140 ms: 1.08x faster                                                 |
| regex_effbot   | 2.58 ms                                                | 2.51 ms: 1.03x faster                                                |
| regex_v8       | 16.0 ms                                                | 16.5 ms: 1.03x slower                                                |
| regex_compile  | 75.8 ms                                                | 81.8 ms: 1.08x slower                                                |
| Geometric mean | (ref)                                                  | 1.00x slower                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 3.18 us: 1.01x faster                                                |
| pickle_list          | 2.92 us                                                | 2.90 us: 1.01x faster                                                |
| unpickle             | 9.26 us                                                | 9.18 us: 1.01x faster                                                |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                                |
| pickle               | 7.45 us                                                | 7.40 us: 1.01x faster                                                |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                                 |
| json_dumps           | 6.43 ms                                                | 6.53 ms: 1.02x slower                                                |
| pickle_pure_python   | 188 us                                                 | 195 us: 1.04x slower                                                 |
| xml_etree_process    | 38.5 ms                                                | 40.0 ms: 1.04x slower                                                |
| xml_etree_iterparse  | 74.3 ms                                                | 77.2 ms: 1.04x slower                                                |
| xml_etree_generate   | 55.8 ms                                                | 58.2 ms: 1.04x slower                                                |
| tomli_loads          | 1.39 sec                                               | 1.53 sec: 1.10x slower                                               |
| unpickle_pure_python | 145 us                                                 | 164 us: 1.14x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                         |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                | 12.6 ms: 1.09x slower                                                |
| python_startup_no_site | 9.43 ms                                                | 10.5 ms: 1.11x slower                                                |
| Geometric mean         | (ref)                                                  | 1.10x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.66 ms: 1.01x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 180 ms: 1.36x faster                                                 |
| generators               | 28.5 ms                                                | 25.0 ms: 1.14x faster                                                |
| asyncio_tcp              | 460 ms                                                 | 413 ms: 1.12x faster                                                 |
| sqlglot_parse            | 898 us                                                 | 818 us: 1.10x faster                                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 46.3 ms: 1.08x faster                                                |
| regex_dna                | 151 ms                                                 | 140 ms: 1.08x faster                                                 |
| crypto_pyaes             | 52.3 ms                                                | 48.6 ms: 1.07x faster                                                |
| sqlglot_transpile        | 1.07 ms                                                | 999 us: 1.07x faster                                                 |
| unpack_sequence          | 28.8 ns                                                | 26.9 ns: 1.07x faster                                                |
| chaos                    | 45.2 ms                                                | 42.3 ms: 1.07x faster                                                |
| coverage                 | 51.0 ms                                                | 47.9 ms: 1.07x faster                                                |
| deltablue                | 2.59 ms                                                | 2.50 ms: 1.04x faster                                                |
| async_tree_none          | 262 ms                                                 | 254 ms: 1.03x faster                                                 |
| regex_effbot             | 2.58 ms                                                | 2.51 ms: 1.03x faster                                                |
| logging_format           | 3.97 us                                                | 3.88 us: 1.02x faster                                                |
| float                    | 58.2 ms                                                | 57.1 ms: 1.02x faster                                                |
| logging_simple           | 3.69 us                                                | 3.63 us: 1.02x faster                                                |
| unpickle_list            | 3.22 us                                                | 3.18 us: 1.01x faster                                                |
| json                     | 3.05 ms                                                | 3.01 ms: 1.01x faster                                                |
| coroutines               | 18.2 ms                                                | 18.0 ms: 1.01x faster                                                |
| mdp                      | 1.68 sec                                               | 1.66 sec: 1.01x faster                                               |
| pickle_list              | 2.92 us                                                | 2.90 us: 1.01x faster                                                |
| unpickle                 | 9.26 us                                                | 9.18 us: 1.01x faster                                                |
| spectral_norm            | 75.0 ms                                                | 74.4 ms: 1.01x faster                                                |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                                |
| pickle                   | 7.45 us                                                | 7.40 us: 1.01x faster                                                |
| create_gc_cycles         | 702 us                                                 | 699 us: 1.00x faster                                                 |
| docutils                 | 1.54 sec                                               | 1.53 sec: 1.00x faster                                               |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                                |
| go                       | 107 ms                                                 | 108 ms: 1.01x slower                                                 |
| deepcopy_reduce          | 2.02 us                                                | 2.04 us: 1.01x slower                                                |
| mako                     | 7.57 ms                                                | 7.66 ms: 1.01x slower                                                |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.01x slower                                                 |
| sqlite_synth             | 1.58 us                                                | 1.61 us: 1.01x slower                                                |
| json_dumps               | 6.43 ms                                                | 6.53 ms: 1.02x slower                                                |
| scimark_lu               | 71.7 ms                                                | 73.1 ms: 1.02x slower                                                |
| dulwich_log              | 30.3 ms                                                | 31.0 ms: 1.02x slower                                                |
| deepcopy                 | 224 us                                                 | 229 us: 1.03x slower                                                 |
| bench_thread_pool        | 489 us                                                 | 503 us: 1.03x slower                                                 |
| pprint_safe_repr         | 493 ms                                                 | 507 ms: 1.03x slower                                                 |
| async_generators         | 303 ms                                                 | 312 ms: 1.03x slower                                                 |
| regex_v8                 | 16.0 ms                                                | 16.5 ms: 1.03x slower                                                |
| pprint_pformat           | 1.00 sec                                               | 1.03 sec: 1.03x slower                                               |
| sqlglot_optimize         | 34.3 ms                                                | 35.4 ms: 1.03x slower                                                |
| async_tree_io            | 669 ms                                                 | 691 ms: 1.03x slower                                                 |
| pickle_pure_python       | 188 us                                                 | 195 us: 1.04x slower                                                 |
| pyflate                  | 329 ms                                                 | 341 ms: 1.04x slower                                                 |
| xml_etree_process        | 38.5 ms                                                | 40.0 ms: 1.04x slower                                                |
| pycparser                | 670 ms                                                 | 696 ms: 1.04x slower                                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 77.2 ms: 1.04x slower                                                |
| sqlglot_normalize        | 186 ms                                                 | 193 ms: 1.04x slower                                                 |
| deepcopy_memo            | 24.5 us                                                | 25.5 us: 1.04x slower                                                |
| xml_etree_generate       | 55.8 ms                                                | 58.2 ms: 1.04x slower                                                |
| typing_runtime_protocols | 90.7 us                                                | 95.1 us: 1.05x slower                                                |
| bench_mp_pool            | 45.9 ms                                                | 48.1 ms: 1.05x slower                                                |
| scimark_fft              | 198 ms                                                 | 210 ms: 1.06x slower                                                 |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.35 ms: 1.06x slower                                                |
| comprehensions           | 15.7 us                                                | 16.7 us: 1.06x slower                                                |
| nqueens                  | 60.6 ms                                                | 64.5 ms: 1.07x slower                                                |
| logging_silent           | 67.7 ns                                                | 72.3 ns: 1.07x slower                                                |
| async_tree_memoization   | 309 ms                                                 | 331 ms: 1.07x slower                                                 |
| meteor_contest           | 72.9 ms                                                | 78.3 ms: 1.07x slower                                                |
| regex_compile            | 75.8 ms                                                | 81.8 ms: 1.08x slower                                                |
| fannkuch                 | 267 ms                                                 | 289 ms: 1.08x slower                                                 |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.36 sec: 1.08x slower                                               |
| richards_super           | 34.9 ms                                                | 38.0 ms: 1.09x slower                                                |
| python_startup           | 11.5 ms                                                | 12.6 ms: 1.09x slower                                                |
| tomli_loads              | 1.39 sec                                               | 1.53 sec: 1.10x slower                                               |
| python_startup_no_site   | 9.43 ms                                                | 10.5 ms: 1.11x slower                                                |
| pathlib                  | 28.8 ms                                                | 32.1 ms: 1.11x slower                                                |
| richards                 | 31.1 ms                                                | 34.7 ms: 1.12x slower                                                |
| scimark_sor              | 94.1 ms                                                | 106 ms: 1.13x slower                                                 |
| unpickle_pure_python     | 145 us                                                 | 164 us: 1.14x slower                                                 |
| nbody                    | 68.6 ms                                                | 78.8 ms: 1.15x slower                                                |
| telco                    | 3.82 ms                                                | 4.62 ms: 1.21x slower                                                |
| hexiom                   | 4.24 ms                                                | 5.19 ms: 1.22x slower                                                |
| dask                     | 228 ms                                                 | 334 ms: 1.47x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.02x slower                                                         |

Benchmark hidden because not significant (5): tornado_http, async_tree_cpu_io_mixed, pidigits, json_loads, mypy2
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.81% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
