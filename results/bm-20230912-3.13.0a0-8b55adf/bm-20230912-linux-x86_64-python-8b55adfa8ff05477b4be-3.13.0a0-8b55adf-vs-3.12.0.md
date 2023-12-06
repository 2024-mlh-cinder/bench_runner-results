
# Results vs. 3.12.0

- fork: python
- ref: 8b55adfa8ff05477b4be
- machine: linux-x86_64
- commit hash: 8b55adf
- commit date: 2023-09-12
- overall geometric mean: 1.00x faster
- HPT reliability: 96.48%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.61 sec: 1.04x faster                                                |
| tornado_http   | 99.6 ms                                                | 95.4 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| nbody          | 88.8 ms                                                | 89.8 ms: 1.01x slower                                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                                          |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 135 ms: 1.06x faster                                                  |
| regex_effbot   | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                 |
| regex_dna      | 209 ms                                                 | 214 ms: 1.03x slower                                                  |
| regex_v8       | 22.3 ms                                                | 24.6 ms: 1.10x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.07 sec: 1.07x faster                                                |
| unpickle             | 15.0 us                                                | 14.5 us: 1.03x faster                                                 |
| unpickle_list        | 4.95 us                                                | 4.82 us: 1.03x faster                                                 |
| pickle_pure_python   | 309 us                                                 | 302 us: 1.02x faster                                                  |
| pickle_list          | 4.62 us                                                | 4.53 us: 1.02x faster                                                 |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                  |
| xml_etree_process    | 58.6 ms                                                | 58.0 ms: 1.01x faster                                                 |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                  |
| unpickle_pure_python | 218 us                                                 | 221 us: 1.01x slower                                                  |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                 |
| pickle_dict          | 31.6 us                                                | 32.5 us: 1.03x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (3): xml_etree_generate, json_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.85 ms: 1.01x faster                                                 |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                 |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230912-linux-x86_64-python-8b55adfa8ff05477b4be-3.13.0a0-8b55adf |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| crypto_pyaes            | 77.2 ms                                                | 69.9 ms: 1.10x faster                                                 |
| coverage                | 94.2 ms                                                | 85.7 ms: 1.10x faster                                                 |
| raytrace                | 294 ms                                                 | 270 ms: 1.09x faster                                                  |
| tomli_loads             | 2.22 sec                                               | 2.07 sec: 1.07x faster                                                |
| async_tree_none         | 469 ms                                                 | 438 ms: 1.07x faster                                                  |
| asyncio_tcp             | 526 ms                                                 | 491 ms: 1.07x faster                                                  |
| scimark_monte_carlo     | 71.0 ms                                                | 66.4 ms: 1.07x faster                                                 |
| generators              | 31.1 ms                                                | 29.1 ms: 1.07x faster                                                 |
| regex_compile           | 144 ms                                                 | 135 ms: 1.06x faster                                                  |
| deltablue               | 3.52 ms                                                | 3.32 ms: 1.06x faster                                                 |
| chaos                   | 63.5 ms                                                | 60.6 ms: 1.05x faster                                                 |
| scimark_lu              | 114 ms                                                 | 109 ms: 1.05x faster                                                  |
| tornado_http            | 99.6 ms                                                | 95.4 ms: 1.04x faster                                                 |
| sqlglot_parse           | 1.32 ms                                                | 1.27 ms: 1.04x faster                                                 |
| logging_format          | 6.90 us                                                | 6.63 us: 1.04x faster                                                 |
| sqlglot_transpile       | 1.64 ms                                                | 1.58 ms: 1.04x faster                                                 |
| docutils                | 2.70 sec                                               | 2.61 sec: 1.04x faster                                                |
| logging_simple          | 6.18 us                                                | 5.98 us: 1.03x faster                                                 |
| unpickle                | 15.0 us                                                | 14.5 us: 1.03x faster                                                 |
| deepcopy                | 355 us                                                 | 345 us: 1.03x faster                                                  |
| unpickle_list           | 4.95 us                                                | 4.82 us: 1.03x faster                                                 |
| sqlglot_normalize       | 107 ms                                                 | 104 ms: 1.03x faster                                                  |
| pprint_pformat          | 1.50 sec                                               | 1.46 sec: 1.02x faster                                                |
| bench_thread_pool       | 827 us                                                 | 809 us: 1.02x faster                                                  |
| pickle_pure_python      | 309 us                                                 | 302 us: 1.02x faster                                                  |
| nqueens                 | 81.1 ms                                                | 79.5 ms: 1.02x faster                                                 |
| pprint_safe_repr        | 735 ms                                                 | 721 ms: 1.02x faster                                                  |
| pickle_list             | 4.62 us                                                | 4.53 us: 1.02x faster                                                 |
| dulwich_log             | 67.9 ms                                                | 66.6 ms: 1.02x faster                                                 |
| deepcopy_memo           | 37.4 us                                                | 36.8 us: 1.02x faster                                                 |
| hexiom                  | 6.12 ms                                                | 6.03 ms: 1.01x faster                                                 |
| scimark_fft             | 358 ms                                                 | 353 ms: 1.01x faster                                                  |
| mypy2                   | 344 ms                                                 | 339 ms: 1.01x faster                                                  |
| mdp                     | 2.57 sec                                               | 2.53 sec: 1.01x faster                                                |
| deepcopy_reduce         | 3.14 us                                                | 3.10 us: 1.01x faster                                                 |
| sqlglot_optimize        | 53.3 ms                                                | 52.6 ms: 1.01x faster                                                 |
| xml_etree_iterparse     | 104 ms                                                 | 102 ms: 1.01x faster                                                  |
| scimark_sor             | 125 ms                                                 | 123 ms: 1.01x faster                                                  |
| async_tree_memoization  | 573 ms                                                 | 567 ms: 1.01x faster                                                  |
| pathlib                 | 18.5 ms                                                | 18.3 ms: 1.01x faster                                                 |
| coroutines              | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                 |
| xml_etree_process       | 58.6 ms                                                | 58.0 ms: 1.01x faster                                                 |
| xml_etree_parse         | 154 ms                                                 | 152 ms: 1.01x faster                                                  |
| python_startup_no_site  | 6.90 ms                                                | 6.85 ms: 1.01x faster                                                 |
| comprehensions          | 20.4 us                                                | 20.3 us: 1.01x faster                                                 |
| pidigits                | 187 ms                                                 | 187 ms: 1.00x slower                                                  |
| unpack_sequence         | 44.8 ns                                                | 45.0 ns: 1.00x slower                                                 |
| async_generators        | 440 ms                                                 | 443 ms: 1.01x slower                                                  |
| create_gc_cycles        | 1.52 ms                                                | 1.53 ms: 1.01x slower                                                 |
| regex_effbot            | 3.55 ms                                                | 3.58 ms: 1.01x slower                                                 |
| meteor_contest          | 105 ms                                                 | 106 ms: 1.01x slower                                                  |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.79 ms: 1.01x slower                                                 |
| nbody                   | 88.8 ms                                                | 89.8 ms: 1.01x slower                                                 |
| unpickle_pure_python    | 218 us                                                 | 221 us: 1.01x slower                                                  |
| mako                    | 10.7 ms                                                | 10.9 ms: 1.02x slower                                                 |
| fannkuch                | 387 ms                                                 | 395 ms: 1.02x slower                                                  |
| pyflate                 | 450 ms                                                 | 459 ms: 1.02x slower                                                  |
| pickle                  | 10.6 us                                                | 10.8 us: 1.02x slower                                                 |
| logging_silent          | 99.1 ns                                                | 102 ns: 1.03x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                |
| regex_dna               | 209 ms                                                 | 214 ms: 1.03x slower                                                  |
| pickle_dict             | 31.6 us                                                | 32.5 us: 1.03x slower                                                 |
| go                      | 136 ms                                                 | 140 ms: 1.03x slower                                                  |
| pycparser               | 1.15 sec                                               | 1.19 sec: 1.04x slower                                                |
| gc_traversal            | 3.84 ms                                                | 4.00 ms: 1.04x slower                                                 |
| python_startup          | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                 |
| richards                | 43.2 ms                                                | 47.6 ms: 1.10x slower                                                 |
| regex_v8                | 22.3 ms                                                | 24.6 ms: 1.10x slower                                                 |
| richards_super          | 49.0 ms                                                | 54.8 ms: 1.12x slower                                                 |
| telco                   | 6.87 ms                                                | 8.23 ms: 1.20x slower                                                 |
| dask                    | 365 ms                                                 | 526 ms: 1.44x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (11): async_tree_cpu_io_mixed, float, xml_etree_generate, spectral_norm, asyncio_tcp_ssl, bench_mp_pool, json_loads, typing_runtime_protocols, json_dumps, json, sqlite_synth
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 96.48% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
