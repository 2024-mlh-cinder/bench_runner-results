
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.01x faster
- HPT reliability: 83.34%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 1.54 sec                                               | 1.49 sec: 1.03x faster                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 58.2 ms                                                | 55.0 ms: 1.06x faster                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| nbody          | 68.6 ms                                                | 71.3 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 151 ms                                                 | 149 ms: 1.01x faster                                   |
| regex_effbot   | 2.58 ms                                                | 2.62 ms: 1.02x slower                                  |
| regex_v8       | 16.0 ms                                                | 16.8 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle_list        | 3.22 us                                                | 3.14 us: 1.03x faster                                  |
| unpickle             | 9.26 us                                                | 9.12 us: 1.02x faster                                  |
| pickle_list          | 2.92 us                                                | 2.89 us: 1.01x faster                                  |
| json_loads           | 17.6 us                                                | 17.5 us: 1.01x faster                                  |
| pickle               | 7.45 us                                                | 7.41 us: 1.01x faster                                  |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                  |
| xml_etree_process    | 38.5 ms                                                | 38.8 ms: 1.01x slower                                  |
| xml_etree_parse      | 109 ms                                                 | 111 ms: 1.02x slower                                   |
| xml_etree_generate   | 55.8 ms                                                | 57.1 ms: 1.02x slower                                  |
| xml_etree_iterparse  | 74.3 ms                                                | 76.4 ms: 1.03x slower                                  |
| pickle_pure_python   | 188 us                                                 | 195 us: 1.04x slower                                   |
| unpickle_pure_python | 145 us                                                 | 156 us: 1.08x slower                                   |
| tomli_loads          | 1.39 sec                                               | 1.54 sec: 1.11x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x slower                                           |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 9.43 ms                                                | 8.50 ms: 1.11x faster                                  |
| python_startup         | 11.5 ms                                                | 11.1 ms: 1.04x faster                                  |
| Geometric mean         | (ref)                                                  | 1.08x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 7.57 ms                                                | 7.35 ms: 1.03x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| raytrace                 | 246 ms                                                 | 173 ms: 1.42x faster                                   |
| generators               | 28.5 ms                                                | 24.0 ms: 1.19x faster                                  |
| sqlglot_parse            | 898 us                                                 | 794 us: 1.13x faster                                   |
| chaos                    | 45.2 ms                                                | 40.1 ms: 1.13x faster                                  |
| crypto_pyaes             | 52.3 ms                                                | 46.7 ms: 1.12x faster                                  |
| scimark_monte_carlo      | 50.1 ms                                                | 44.9 ms: 1.12x faster                                  |
| sqlglot_transpile        | 1.07 ms                                                | 967 us: 1.11x faster                                   |
| deltablue                | 2.59 ms                                                | 2.34 ms: 1.11x faster                                  |
| python_startup_no_site   | 9.43 ms                                                | 8.50 ms: 1.11x faster                                  |
| unpack_sequence          | 28.8 ns                                                | 26.4 ns: 1.09x faster                                  |
| coverage                 | 51.0 ms                                                | 46.8 ms: 1.09x faster                                  |
| comprehensions           | 15.7 us                                                | 14.6 us: 1.08x faster                                  |
| spectral_norm            | 75.0 ms                                                | 70.7 ms: 1.06x faster                                  |
| nqueens                  | 60.6 ms                                                | 57.2 ms: 1.06x faster                                  |
| float                    | 58.2 ms                                                | 55.0 ms: 1.06x faster                                  |
| async_tree_none          | 262 ms                                                 | 251 ms: 1.04x faster                                   |
| python_startup           | 11.5 ms                                                | 11.1 ms: 1.04x faster                                  |
| mdp                      | 1.68 sec                                               | 1.61 sec: 1.04x faster                                 |
| go                       | 107 ms                                                 | 103 ms: 1.04x faster                                   |
| bench_mp_pool            | 45.9 ms                                                | 44.1 ms: 1.04x faster                                  |
| coroutines               | 18.2 ms                                                | 17.5 ms: 1.04x faster                                  |
| logging_simple           | 3.69 us                                                | 3.57 us: 1.04x faster                                  |
| scimark_sparse_mat_mult  | 3.16 ms                                                | 3.06 ms: 1.03x faster                                  |
| mako                     | 7.57 ms                                                | 7.35 ms: 1.03x faster                                  |
| docutils                 | 1.54 sec                                               | 1.49 sec: 1.03x faster                                 |
| unpickle_list            | 3.22 us                                                | 3.14 us: 1.03x faster                                  |
| logging_format           | 3.97 us                                                | 3.87 us: 1.03x faster                                  |
| bench_thread_pool        | 489 us                                                 | 478 us: 1.02x faster                                   |
| deepcopy_reduce          | 2.02 us                                                | 1.97 us: 1.02x faster                                  |
| json                     | 3.05 ms                                                | 2.98 ms: 1.02x faster                                  |
| deepcopy_memo            | 24.5 us                                                | 24.0 us: 1.02x faster                                  |
| sqlglot_normalize        | 186 ms                                                 | 182 ms: 1.02x faster                                   |
| deepcopy                 | 224 us                                                 | 220 us: 1.02x faster                                   |
| unpickle                 | 9.26 us                                                | 9.12 us: 1.02x faster                                  |
| scimark_lu               | 71.7 ms                                                | 70.6 ms: 1.02x faster                                  |
| sqlglot_optimize         | 34.3 ms                                                | 33.8 ms: 1.01x faster                                  |
| pickle_list              | 2.92 us                                                | 2.89 us: 1.01x faster                                  |
| async_generators         | 303 ms                                                 | 300 ms: 1.01x faster                                   |
| regex_dna                | 151 ms                                                 | 149 ms: 1.01x faster                                   |
| json_loads               | 17.6 us                                                | 17.5 us: 1.01x faster                                  |
| pickle                   | 7.45 us                                                | 7.41 us: 1.01x faster                                  |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                  |
| scimark_fft              | 198 ms                                                 | 197 ms: 1.00x faster                                   |
| create_gc_cycles         | 702 us                                                 | 699 us: 1.00x faster                                   |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| dulwich_log              | 30.3 ms                                                | 30.4 ms: 1.00x slower                                  |
| logging_silent           | 67.7 ns                                                | 67.9 ns: 1.00x slower                                  |
| xml_etree_process        | 38.5 ms                                                | 38.8 ms: 1.01x slower                                  |
| meteor_contest           | 72.9 ms                                                | 74.0 ms: 1.01x slower                                  |
| typing_runtime_protocols | 90.7 us                                                | 92.0 us: 1.01x slower                                  |
| pprint_pformat           | 1.00 sec                                               | 1.02 sec: 1.01x slower                                 |
| regex_effbot             | 2.58 ms                                                | 2.62 ms: 1.02x slower                                  |
| pyflate                  | 329 ms                                                 | 334 ms: 1.02x slower                                   |
| pprint_safe_repr         | 493 ms                                                 | 504 ms: 1.02x slower                                   |
| xml_etree_parse          | 109 ms                                                 | 111 ms: 1.02x slower                                   |
| xml_etree_generate       | 55.8 ms                                                | 57.1 ms: 1.02x slower                                  |
| sqlite_synth             | 1.58 us                                                | 1.63 us: 1.03x slower                                  |
| pathlib                  | 28.8 ms                                                | 29.6 ms: 1.03x slower                                  |
| xml_etree_iterparse      | 74.3 ms                                                | 76.4 ms: 1.03x slower                                  |
| pycparser                | 670 ms                                                 | 691 ms: 1.03x slower                                   |
| asyncio_tcp_ssl          | 1.26 sec                                               | 1.30 sec: 1.03x slower                                 |
| pickle_pure_python       | 188 us                                                 | 195 us: 1.04x slower                                   |
| nbody                    | 68.6 ms                                                | 71.3 ms: 1.04x slower                                  |
| richards_super           | 34.9 ms                                                | 36.4 ms: 1.04x slower                                  |
| async_tree_io            | 669 ms                                                 | 698 ms: 1.04x slower                                   |
| regex_v8                 | 16.0 ms                                                | 16.8 ms: 1.05x slower                                  |
| fannkuch                 | 267 ms                                                 | 283 ms: 1.06x slower                                   |
| richards                 | 31.1 ms                                                | 33.0 ms: 1.06x slower                                  |
| async_tree_memoization   | 309 ms                                                 | 329 ms: 1.06x slower                                   |
| unpickle_pure_python     | 145 us                                                 | 156 us: 1.08x slower                                   |
| hexiom                   | 4.24 ms                                                | 4.59 ms: 1.08x slower                                  |
| scimark_sor              | 94.1 ms                                                | 103 ms: 1.10x slower                                   |
| tomli_loads              | 1.39 sec                                               | 1.54 sec: 1.11x slower                                 |
| telco                    | 3.82 ms                                                | 4.65 ms: 1.22x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (7): asyncio_tcp, tornado_http, async_tree_cpu_io_mixed, mypy2, gc_traversal, json_dumps, regex_compile
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 83.34% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
