
# Results vs. 3.12.0

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: darwin-arm64
- commit hash: 0bed3bc
- commit date: 2023-08-28
- overall geometric mean: 1.01x slower
- HPT reliability: 98.83%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.52 sec: 1.01x faster                                                      |
| Geometric mean | (ref)                                                  | 1.00x faster                                                                |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 58.2 ms                                                | 56.7 ms: 1.03x faster                                                       |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                        |
| nbody          | 68.6 ms                                                | 72.0 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                                        |
| regex_compile  | 75.8 ms                                                | 79.1 ms: 1.04x slower                                                       |
| regex_v8       | 16.0 ms                                                | 17.0 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                  | 1.02x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_list          | 2.92 us                                                | 2.86 us: 1.02x faster                                                       |
| unpickle             | 9.26 us                                                | 9.11 us: 1.02x faster                                                       |
| unpickle_list        | 3.22 us                                                | 3.18 us: 1.01x faster                                                       |
| json_loads           | 17.6 us                                                | 17.5 us: 1.01x faster                                                       |
| pickle               | 7.45 us                                                | 7.41 us: 1.01x faster                                                       |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                                       |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                                        |
| json_dumps           | 6.43 ms                                                | 6.49 ms: 1.01x slower                                                       |
| xml_etree_iterparse  | 74.3 ms                                                | 76.1 ms: 1.02x slower                                                       |
| xml_etree_generate   | 55.8 ms                                                | 58.8 ms: 1.05x slower                                                       |
| xml_etree_process    | 38.5 ms                                                | 40.8 ms: 1.06x slower                                                       |
| pickle_pure_python   | 188 us                                                 | 200 us: 1.06x slower                                                        |
| tomli_loads          | 1.39 sec                                               | 1.55 sec: 1.11x slower                                                      |
| unpickle_pure_python | 145 us                                                 | 162 us: 1.12x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 9.15 ms: 1.03x faster                                                       |
| python_startup         | 11.5 ms                                                | 11.8 ms: 1.02x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.00x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.43 ms: 1.02x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230828-darwin-arm64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mypy2                    | 259 ms                                                 | 193 ms: 1.34x faster                                                        |
| raytrace                 | 246 ms                                                 | 189 ms: 1.30x faster                                                        |
| crypto_pyaes             | 52.3 ms                                                | 47.7 ms: 1.09x faster                                                       |
| generators               | 28.5 ms                                                | 26.2 ms: 1.09x faster                                                       |
| scimark_monte_carlo      | 50.1 ms                                                | 46.2 ms: 1.08x faster                                                       |
| chaos                    | 45.2 ms                                                | 41.9 ms: 1.08x faster                                                       |
| coverage                 | 51.0 ms                                                | 47.3 ms: 1.08x faster                                                       |
| sqlglot_parse            | 898 us                                                 | 832 us: 1.08x faster                                                        |
| sqlglot_transpile        | 1.07 ms                                                | 1.01 ms: 1.06x faster                                                       |
| comprehensions           | 15.7 us                                                | 14.9 us: 1.05x faster                                                       |
| unpack_sequence          | 28.8 ns                                                | 27.9 ns: 1.03x faster                                                       |
| python_startup_no_site   | 9.43 ms                                                | 9.15 ms: 1.03x faster                                                       |
| float                    | 58.2 ms                                                | 56.7 ms: 1.03x faster                                                       |
| async_tree_none          | 262 ms                                                 | 256 ms: 1.02x faster                                                        |
| pickle_list              | 2.92 us                                                | 2.86 us: 1.02x faster                                                       |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.09 ms: 1.02x faster                                                       |
| nqueens                  | 60.6 ms                                                | 59.2 ms: 1.02x faster                                                       |
| mdp                      | 1.68 sec                                               | 1.64 sec: 1.02x faster                                                      |
| mako                     | 7.57 ms                                                | 7.43 ms: 1.02x faster                                                       |
| unpickle                 | 9.26 us                                                | 9.11 us: 1.02x faster                                                       |
| deltablue                | 2.59 ms                                                | 2.55 ms: 1.01x faster                                                       |
| docutils                 | 1.54 sec                                               | 1.52 sec: 1.01x faster                                                      |
| spectral_norm            | 75.0 ms                                                | 74.0 ms: 1.01x faster                                                       |
| unpickle_list            | 3.22 us                                                | 3.18 us: 1.01x faster                                                       |
| json                     | 3.05 ms                                                | 3.01 ms: 1.01x faster                                                       |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                                        |
| json_loads               | 17.6 us                                                | 17.5 us: 1.01x faster                                                       |
| pickle                   | 7.45 us                                                | 7.41 us: 1.01x faster                                                       |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                                       |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                                        |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                                       |
| logging_format           | 3.97 us                                                | 3.99 us: 1.00x slower                                                       |
| create_gc_cycles         | 702 us                                                 | 708 us: 1.01x slower                                                        |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.01x slower                                                        |
| json_dumps               | 6.43 ms                                                | 6.49 ms: 1.01x slower                                                       |
| sqlite_synth             | 1.58 us                                                | 1.60 us: 1.01x slower                                                       |
| bench_mp_pool            | 45.9 ms                                                | 46.4 ms: 1.01x slower                                                       |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.27 sec: 1.01x slower                                                      |
| logging_simple           | 3.69 us                                                | 3.74 us: 1.01x slower                                                       |
| meteor_contest           | 72.9 ms                                                | 74.1 ms: 1.02x slower                                                       |
| go                       | 107 ms                                                 | 109 ms: 1.02x slower                                                        |
| scimark_fft              | 198 ms                                                 | 201 ms: 1.02x slower                                                        |
| dulwich_log              | 30.3 ms                                                | 30.9 ms: 1.02x slower                                                       |
| async_generators         | 303 ms                                                 | 309 ms: 1.02x slower                                                        |
| python_startup           | 11.5 ms                                                | 11.8 ms: 1.02x slower                                                       |
| sqlglot_optimize         | 34.3 ms                                                | 35.1 ms: 1.02x slower                                                       |
| deepcopy_memo            | 24.5 us                                                | 25.0 us: 1.02x slower                                                       |
| xml_etree_iterparse      | 74.3 ms                                                | 76.1 ms: 1.02x slower                                                       |
| sqlglot_normalize        | 186 ms                                                 | 191 ms: 1.03x slower                                                        |
| coroutines               | 18.2 ms                                                | 18.8 ms: 1.03x slower                                                       |
| deepcopy_reduce          | 2.02 us                                                | 2.09 us: 1.03x slower                                                       |
| deepcopy                 | 224 us                                                 | 231 us: 1.03x slower                                                        |
| typing_runtime_protocols | 90.7 us                                                | 94.0 us: 1.04x slower                                                       |
| pprint_safe_repr         | 493 ms                                                 | 512 ms: 1.04x slower                                                        |
| pprint_pformat           | 1.00 sec                                               | 1.04 sec: 1.04x slower                                                      |
| regex_compile            | 75.8 ms                                                | 79.1 ms: 1.04x slower                                                       |
| pycparser                | 670 ms                                                 | 701 ms: 1.05x slower                                                        |
| nbody                    | 68.6 ms                                                | 72.0 ms: 1.05x slower                                                       |
| async_tree_io            | 669 ms                                                 | 704 ms: 1.05x slower                                                        |
| xml_etree_generate       | 55.8 ms                                                | 58.8 ms: 1.05x slower                                                       |
| pyflate                  | 329 ms                                                 | 348 ms: 1.06x slower                                                        |
| xml_etree_process        | 38.5 ms                                                | 40.8 ms: 1.06x slower                                                       |
| scimark_lu               | 71.7 ms                                                | 76.2 ms: 1.06x slower                                                       |
| pickle_pure_python       | 188 us                                                 | 200 us: 1.06x slower                                                        |
| regex_v8                 | 16.0 ms                                                | 17.0 ms: 1.07x slower                                                       |
| async_tree_memoization   | 309 ms                                                 | 331 ms: 1.07x slower                                                        |
| fannkuch                 | 267 ms                                                 | 287 ms: 1.07x slower                                                        |
| richards_super           | 34.9 ms                                                | 38.7 ms: 1.11x slower                                                       |
| tomli_loads              | 1.39 sec                                               | 1.55 sec: 1.11x slower                                                      |
| logging_silent           | 67.7 ns                                                | 75.6 ns: 1.12x slower                                                       |
| unpickle_pure_python     | 145 us                                                 | 162 us: 1.12x slower                                                        |
| pathlib                  | 28.8 ms                                                | 32.4 ms: 1.12x slower                                                       |
| richards                 | 31.1 ms                                                | 35.5 ms: 1.14x slower                                                       |
| hexiom                   | 4.24 ms                                                | 4.86 ms: 1.15x slower                                                       |
| scimark_sor              | 94.1 ms                                                | 108 ms: 1.15x slower                                                        |
| telco                    | 3.82 ms                                                | 4.57 ms: 1.20x slower                                                       |
| dask                     | 228 ms                                                 | 337 ms: 1.48x slower                                                        |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (5): asyncio_tcp, regex_effbot, async_tree_cpu_io_mixed, bench_thread_pool, tornado_http
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 98.83% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
