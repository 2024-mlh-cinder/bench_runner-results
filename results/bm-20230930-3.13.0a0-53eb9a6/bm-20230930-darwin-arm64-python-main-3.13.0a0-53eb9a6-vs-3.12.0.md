
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.02x faster
- HPT reliability: 95.15%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.49 sec: 1.03x faster                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 58.2 ms                                                | 53.4 ms: 1.09x faster                                 |
| nbody          | 68.6 ms                                                | 66.1 ms: 1.04x faster                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 140 ms: 1.08x faster                                  |
| regex_effbot   | 2.58 ms                                                | 2.51 ms: 1.03x faster                                 |
| regex_v8       | 16.0 ms                                                | 16.1 ms: 1.01x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 3.12 us: 1.03x faster                                 |
| unpickle             | 9.26 us                                                | 9.11 us: 1.02x faster                                 |
| pickle               | 7.45 us                                                | 7.33 us: 1.02x faster                                 |
| pickle_list          | 2.92 us                                                | 2.90 us: 1.01x faster                                 |
| json_loads           | 17.6 us                                                | 17.5 us: 1.00x faster                                 |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x faster                                 |
| xml_etree_generate   | 55.8 ms                                                | 56.1 ms: 1.01x slower                                 |
| xml_etree_iterparse  | 74.3 ms                                                | 75.0 ms: 1.01x slower                                 |
| xml_etree_process    | 38.5 ms                                                | 39.0 ms: 1.01x slower                                 |
| pickle_pure_python   | 188 us                                                 | 193 us: 1.02x slower                                  |
| json_dumps           | 6.43 ms                                                | 6.67 ms: 1.04x slower                                 |
| unpickle_pure_python | 145 us                                                 | 154 us: 1.07x slower                                  |
| tomli_loads          | 1.39 sec                                               | 1.53 sec: 1.10x slower                                |
| Geometric mean       | (ref)                                                  | 1.01x slower                                          |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.35 ms: 1.01x faster                                 |
| python_startup         | 11.5 ms                                                | 12.0 ms: 1.04x slower                                 |
| Geometric mean         | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.23 ms: 1.05x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 171 ms: 1.44x faster                                  |
| mypy2                    | 259 ms                                                 | 191 ms: 1.36x faster                                  |
| generators               | 28.5 ms                                                | 24.7 ms: 1.15x faster                                 |
| chaos                    | 45.2 ms                                                | 39.7 ms: 1.14x faster                                 |
| sqlglot_parse            | 898 us                                                 | 792 us: 1.13x faster                                  |
| scimark_monte_carlo      | 50.1 ms                                                | 44.2 ms: 1.13x faster                                 |
| crypto_pyaes             | 52.3 ms                                                | 46.4 ms: 1.13x faster                                 |
| sqlglot_transpile        | 1.07 ms                                                | 963 us: 1.11x faster                                  |
| deltablue                | 2.59 ms                                                | 2.34 ms: 1.11x faster                                 |
| coverage                 | 51.0 ms                                                | 46.2 ms: 1.10x faster                                 |
| unpack_sequence          | 28.8 ns                                                | 26.2 ns: 1.10x faster                                 |
| float                    | 58.2 ms                                                | 53.4 ms: 1.09x faster                                 |
| spectral_norm            | 75.0 ms                                                | 69.1 ms: 1.08x faster                                 |
| regex_dna                | 151 ms                                                 | 140 ms: 1.08x faster                                  |
| asyncio_tcp              | 460 ms                                                 | 433 ms: 1.06x faster                                  |
| comprehensions           | 15.7 us                                                | 14.8 us: 1.06x faster                                 |
| nqueens                  | 60.6 ms                                                | 57.2 ms: 1.06x faster                                 |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.00 ms: 1.05x faster                                 |
| async_tree_none          | 262 ms                                                 | 250 ms: 1.05x faster                                  |
| mako                     | 7.57 ms                                                | 7.23 ms: 1.05x faster                                 |
| mdp                      | 1.68 sec                                               | 1.60 sec: 1.05x faster                                |
| go                       | 107 ms                                                 | 103 ms: 1.04x faster                                  |
| nbody                    | 68.6 ms                                                | 66.1 ms: 1.04x faster                                 |
| docutils                 | 1.54 sec                                               | 1.49 sec: 1.03x faster                                |
| unpickle_list            | 3.22 us                                                | 3.12 us: 1.03x faster                                 |
| scimark_lu               | 71.7 ms                                                | 69.5 ms: 1.03x faster                                 |
| coroutines               | 18.2 ms                                                | 17.7 ms: 1.03x faster                                 |
| regex_effbot             | 2.58 ms                                                | 2.51 ms: 1.03x faster                                 |
| async_generators         | 303 ms                                                 | 295 ms: 1.02x faster                                  |
| deepcopy_memo            | 24.5 us                                                | 23.9 us: 1.02x faster                                 |
| scimark_fft              | 198 ms                                                 | 194 ms: 1.02x faster                                  |
| deepcopy_reduce          | 2.02 us                                                | 1.98 us: 1.02x faster                                 |
| unpickle                 | 9.26 us                                                | 9.11 us: 1.02x faster                                 |
| logging_simple           | 3.69 us                                                | 3.64 us: 1.02x faster                                 |
| pickle                   | 7.45 us                                                | 7.33 us: 1.02x faster                                 |
| sqlglot_normalize        | 186 ms                                                 | 183 ms: 1.01x faster                                  |
| logging_format           | 3.97 us                                                | 3.92 us: 1.01x faster                                 |
| bench_thread_pool        | 489 us                                                 | 483 us: 1.01x faster                                  |
| json                     | 3.05 ms                                                | 3.01 ms: 1.01x faster                                 |
| async_tree_cpu_io_mixed  | 526 ms                                                 | 521 ms: 1.01x faster                                  |
| pickle_list              | 2.92 us                                                | 2.90 us: 1.01x faster                                 |
| deepcopy                 | 224 us                                                 | 222 us: 1.01x faster                                  |
| python_startup_no_site   | 9.43 ms                                                | 9.35 ms: 1.01x faster                                 |
| sqlglot_optimize         | 34.3 ms                                                | 34.2 ms: 1.00x faster                                 |
| json_loads               | 17.6 us                                                | 17.5 us: 1.00x faster                                 |
| pidigits                 | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| logging_silent           | 67.7 ns                                                | 67.4 ns: 1.00x faster                                 |
| pickle_dict              | 18.0 us                                                | 18.0 us: 1.00x faster                                 |
| dulwich_log              | 30.3 ms                                                | 30.2 ms: 1.00x faster                                 |
| create_gc_cycles         | 702 us                                                 | 703 us: 1.00x slower                                  |
| sqlite_synth             | 1.58 us                                                | 1.59 us: 1.00x slower                                 |
| xml_etree_generate       | 55.8 ms                                                | 56.1 ms: 1.01x slower                                 |
| meteor_contest           | 72.9 ms                                                | 73.5 ms: 1.01x slower                                 |
| xml_etree_iterparse      | 74.3 ms                                                | 75.0 ms: 1.01x slower                                 |
| pprint_pformat           | 1.00 sec                                               | 1.01 sec: 1.01x slower                                |
| regex_v8                 | 16.0 ms                                                | 16.1 ms: 1.01x slower                                 |
| xml_etree_process        | 38.5 ms                                                | 39.0 ms: 1.01x slower                                 |
| pprint_safe_repr         | 493 ms                                                 | 500 ms: 1.01x slower                                  |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.27 sec: 1.01x slower                                |
| pyflate                  | 329 ms                                                 | 335 ms: 1.02x slower                                  |
| pycparser                | 670 ms                                                 | 683 ms: 1.02x slower                                  |
| bench_mp_pool            | 45.9 ms                                                | 46.9 ms: 1.02x slower                                 |
| pickle_pure_python       | 188 us                                                 | 193 us: 1.02x slower                                  |
| typing_runtime_protocols | 90.7 us                                                | 93.0 us: 1.02x slower                                 |
| python_startup           | 11.5 ms                                                | 12.0 ms: 1.04x slower                                 |
| json_dumps               | 6.43 ms                                                | 6.67 ms: 1.04x slower                                 |
| async_tree_io            | 669 ms                                                 | 696 ms: 1.04x slower                                  |
| async_tree_memoization   | 309 ms                                                 | 326 ms: 1.05x slower                                  |
| fannkuch                 | 267 ms                                                 | 285 ms: 1.07x slower                                  |
| unpickle_pure_python     | 145 us                                                 | 154 us: 1.07x slower                                  |
| richards_super           | 34.9 ms                                                | 37.9 ms: 1.09x slower                                 |
| hexiom                   | 4.24 ms                                                | 4.61 ms: 1.09x slower                                 |
| scimark_sor              | 94.1 ms                                                | 103 ms: 1.09x slower                                  |
| tomli_loads              | 1.39 sec                                               | 1.53 sec: 1.10x slower                                |
| richards                 | 31.1 ms                                                | 34.4 ms: 1.11x slower                                 |
| pathlib                  | 28.8 ms                                                | 33.6 ms: 1.17x slower                                 |
| telco                    | 3.82 ms                                                | 4.62 ms: 1.21x slower                                 |
| Geometric mean           | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (4): tornado_http, regex_compile, gc_traversal, xml_etree_parse
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 95.15% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
