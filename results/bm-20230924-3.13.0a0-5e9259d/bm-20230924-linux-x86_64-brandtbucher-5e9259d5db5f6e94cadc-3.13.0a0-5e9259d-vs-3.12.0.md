
# Results vs. 3.12.0

- fork: brandtbucher
- ref: 5e9259d5db5f6e94cadc
- machine: linux-x86_64
- commit hash: 5e9259d
- commit date: 2023-09-24
- overall geometric mean: 1.01x slower
- HPT reliability: 85.56%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.67 sec: 1.01x faster                                                      |
| tornado_http   | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                  | 1.03x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                                        |
| nbody          | 88.8 ms                                                | 91.7 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 140 ms: 1.03x faster                                                        |
| regex_dna      | 209 ms                                                 | 210 ms: 1.00x slower                                                        |
| regex_effbot   | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                       |
| regex_v8       | 22.3 ms                                                | 23.2 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                  | 1.00x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.01 sec: 1.10x faster                                                      |
| unpickle             | 15.0 us                                                | 14.3 us: 1.05x faster                                                       |
| unpickle_list        | 4.95 us                                                | 4.76 us: 1.04x faster                                                       |
| pickle_pure_python   | 309 us                                                 | 300 us: 1.03x faster                                                        |
| pickle               | 10.6 us                                                | 10.3 us: 1.03x faster                                                       |
| pickle_dict          | 31.6 us                                                | 30.8 us: 1.03x faster                                                       |
| xml_etree_parse      | 154 ms                                                 | 150 ms: 1.02x faster                                                        |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                        |
| xml_etree_generate   | 84.8 ms                                                | 84.0 ms: 1.01x faster                                                       |
| xml_etree_process    | 58.6 ms                                                | 58.0 ms: 1.01x faster                                                       |
| json_loads           | 25.2 us                                                | 25.6 us: 1.01x slower                                                       |
| unpickle_pure_python | 218 us                                                 | 227 us: 1.04x slower                                                        |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                                |

Benchmark hidden because not significant (2): json_dumps, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                       |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 10.8 ms: 1.00x slower                                                       |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-5e9259d5db5f6e94cadc-3.13.0a0-5e9259d |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| coverage                | 94.2 ms                                                | 84.5 ms: 1.11x faster                                                       |
| tomli_loads             | 2.22 sec                                               | 2.01 sec: 1.10x faster                                                      |
| generators              | 31.1 ms                                                | 28.5 ms: 1.09x faster                                                       |
| crypto_pyaes            | 77.2 ms                                                | 70.9 ms: 1.09x faster                                                       |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.37 ms: 1.09x faster                                                       |
| raytrace                | 294 ms                                                 | 274 ms: 1.07x faster                                                        |
| unpack_sequence         | 44.8 ns                                                | 42.0 ns: 1.07x faster                                                       |
| asyncio_tcp             | 526 ms                                                 | 497 ms: 1.06x faster                                                        |
| async_tree_none         | 469 ms                                                 | 445 ms: 1.06x faster                                                        |
| scimark_fft             | 358 ms                                                 | 340 ms: 1.05x faster                                                        |
| unpickle                | 15.0 us                                                | 14.3 us: 1.05x faster                                                       |
| scimark_monte_carlo     | 71.0 ms                                                | 67.6 ms: 1.05x faster                                                       |
| unpickle_list           | 4.95 us                                                | 4.76 us: 1.04x faster                                                       |
| tornado_http            | 99.6 ms                                                | 95.9 ms: 1.04x faster                                                       |
| deltablue               | 3.52 ms                                                | 3.40 ms: 1.03x faster                                                       |
| scimark_sor             | 125 ms                                                 | 121 ms: 1.03x faster                                                        |
| regex_compile           | 144 ms                                                 | 140 ms: 1.03x faster                                                        |
| pickle_pure_python      | 309 us                                                 | 300 us: 1.03x faster                                                        |
| pickle                  | 10.6 us                                                | 10.3 us: 1.03x faster                                                       |
| logging_format          | 6.90 us                                                | 6.72 us: 1.03x faster                                                       |
| pickle_dict             | 31.6 us                                                | 30.8 us: 1.03x faster                                                       |
| sqlglot_parse           | 1.32 ms                                                | 1.29 ms: 1.02x faster                                                       |
| xml_etree_parse         | 154 ms                                                 | 150 ms: 1.02x faster                                                        |
| sqlglot_transpile       | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                       |
| xml_etree_iterparse     | 104 ms                                                 | 102 ms: 1.01x faster                                                        |
| docutils                | 2.70 sec                                               | 2.67 sec: 1.01x faster                                                      |
| create_gc_cycles        | 1.52 ms                                                | 1.51 ms: 1.01x faster                                                       |
| xml_etree_generate      | 84.8 ms                                                | 84.0 ms: 1.01x faster                                                       |
| xml_etree_process       | 58.6 ms                                                | 58.0 ms: 1.01x faster                                                       |
| logging_simple          | 6.18 us                                                | 6.13 us: 1.01x faster                                                       |
| dulwich_log             | 67.9 ms                                                | 67.5 ms: 1.01x faster                                                       |
| python_startup_no_site  | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                       |
| sqlglot_normalize       | 107 ms                                                 | 107 ms: 1.00x faster                                                        |
| bench_thread_pool       | 827 us                                                 | 829 us: 1.00x slower                                                        |
| pprint_safe_repr        | 735 ms                                                 | 738 ms: 1.00x slower                                                        |
| pidigits                | 187 ms                                                 | 187 ms: 1.00x slower                                                        |
| mako                    | 10.7 ms                                                | 10.8 ms: 1.00x slower                                                       |
| regex_dna               | 209 ms                                                 | 210 ms: 1.00x slower                                                        |
| regex_effbot            | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                       |
| sqlglot_optimize        | 53.3 ms                                                | 53.8 ms: 1.01x slower                                                       |
| sqlite_synth            | 2.76 us                                                | 2.79 us: 1.01x slower                                                       |
| pathlib                 | 18.5 ms                                                | 18.7 ms: 1.01x slower                                                       |
| json_loads              | 25.2 us                                                | 25.6 us: 1.01x slower                                                       |
| mypy2                   | 344 ms                                                 | 348 ms: 1.01x slower                                                        |
| pprint_pformat          | 1.50 sec                                               | 1.52 sec: 1.01x slower                                                      |
| deepcopy_reduce         | 3.14 us                                                | 3.19 us: 1.02x slower                                                       |
| chaos                   | 63.5 ms                                                | 64.7 ms: 1.02x slower                                                       |
| pyflate                 | 450 ms                                                 | 459 ms: 1.02x slower                                                        |
| fannkuch                | 387 ms                                                 | 395 ms: 1.02x slower                                                        |
| spectral_norm           | 106 ms                                                 | 108 ms: 1.02x slower                                                        |
| deepcopy_memo           | 37.4 us                                                | 38.4 us: 1.03x slower                                                       |
| async_tree_io           | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                      |
| pycparser               | 1.15 sec                                               | 1.18 sec: 1.03x slower                                                      |
| logging_silent          | 99.1 ns                                                | 102 ns: 1.03x slower                                                        |
| json                    | 4.77 ms                                                | 4.92 ms: 1.03x slower                                                       |
| nbody                   | 88.8 ms                                                | 91.7 ms: 1.03x slower                                                       |
| meteor_contest          | 105 ms                                                 | 108 ms: 1.03x slower                                                        |
| unpickle_pure_python    | 218 us                                                 | 227 us: 1.04x slower                                                        |
| regex_v8                | 22.3 ms                                                | 23.2 ms: 1.04x slower                                                       |
| nqueens                 | 81.1 ms                                                | 85.3 ms: 1.05x slower                                                       |
| async_generators        | 440 ms                                                 | 464 ms: 1.05x slower                                                        |
| python_startup          | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                       |
| mdp                     | 2.57 sec                                               | 2.75 sec: 1.07x slower                                                      |
| hexiom                  | 6.12 ms                                                | 6.64 ms: 1.08x slower                                                       |
| go                      | 136 ms                                                 | 147 ms: 1.09x slower                                                        |
| gc_traversal            | 3.84 ms                                                | 4.21 ms: 1.10x slower                                                       |
| richards_super          | 49.0 ms                                                | 54.3 ms: 1.11x slower                                                       |
| comprehensions          | 20.4 us                                                | 22.8 us: 1.11x slower                                                       |
| richards                | 43.2 ms                                                | 48.4 ms: 1.12x slower                                                       |
| telco                   | 6.87 ms                                                | 8.13 ms: 1.18x slower                                                       |
| dask                    | 365 ms                                                 | 531 ms: 1.46x slower                                                        |
| Geometric mean          | (ref)                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (11): async_tree_memoization, scimark_lu, json_dumps, typing_runtime_protocols, async_tree_cpu_io_mixed, coroutines, deepcopy, asyncio_tcp_ssl, bench_mp_pool, float, pickle_list
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 85.56% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
