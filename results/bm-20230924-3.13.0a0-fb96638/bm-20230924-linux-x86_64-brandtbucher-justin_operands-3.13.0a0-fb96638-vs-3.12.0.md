
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_operands
- machine: linux-x86_64
- commit hash: fb96638
- commit date: 2023-09-24
- overall geometric mean: 1.02x slower
- HPT reliability: 99.66%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 97.1 ms: 1.03x faster                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.01x slower                                                   |
| float          | 80.7 ms                                                | 83.1 ms: 1.03x slower                                                  |
| nbody          | 88.8 ms                                                | 97.5 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                 | 206 ms: 1.01x faster                                                   |
| regex_compile  | 144 ms                                                 | 145 ms: 1.01x slower                                                   |
| regex_v8       | 22.3 ms                                                | 23.6 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle               | 10.6 us                                                | 10.1 us: 1.05x faster                                                  |
| tomli_loads          | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                 |
| pickle_dict          | 31.6 us                                                | 30.7 us: 1.03x faster                                                  |
| unpickle             | 15.0 us                                                | 14.5 us: 1.03x faster                                                  |
| pickle_pure_python   | 309 us                                                 | 300 us: 1.03x faster                                                   |
| xml_etree_process    | 58.6 ms                                                | 57.6 ms: 1.02x faster                                                  |
| xml_etree_generate   | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                  |
| xml_etree_iterparse  | 104 ms                                                 | 102 ms: 1.01x faster                                                   |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                   |
| unpickle_list        | 4.95 us                                                | 4.91 us: 1.01x faster                                                  |
| json_loads           | 25.2 us                                                | 25.5 us: 1.01x slower                                                  |
| json_dumps           | 9.85 ms                                                | 9.93 ms: 1.01x slower                                                  |
| unpickle_pure_python | 218 us                                                 | 230 us: 1.05x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                  |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.0 ms: 1.03x slower                                                  |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| coverage                | 94.2 ms                                                | 84.8 ms: 1.11x faster                                                  |
| crypto_pyaes            | 77.2 ms                                                | 71.5 ms: 1.08x faster                                                  |
| generators              | 31.1 ms                                                | 29.0 ms: 1.07x faster                                                  |
| raytrace                | 294 ms                                                 | 276 ms: 1.07x faster                                                   |
| async_tree_none         | 469 ms                                                 | 443 ms: 1.06x faster                                                   |
| asyncio_tcp             | 526 ms                                                 | 502 ms: 1.05x faster                                                   |
| pickle                  | 10.6 us                                                | 10.1 us: 1.05x faster                                                  |
| tomli_loads             | 2.22 sec                                               | 2.12 sec: 1.05x faster                                                 |
| sqlglot_parse           | 1.32 ms                                                | 1.28 ms: 1.03x faster                                                  |
| pickle_dict             | 31.6 us                                                | 30.7 us: 1.03x faster                                                  |
| unpickle                | 15.0 us                                                | 14.5 us: 1.03x faster                                                  |
| pickle_pure_python      | 309 us                                                 | 300 us: 1.03x faster                                                   |
| tornado_http            | 99.6 ms                                                | 97.1 ms: 1.03x faster                                                  |
| deltablue               | 3.52 ms                                                | 3.45 ms: 1.02x faster                                                  |
| sqlglot_transpile       | 1.64 ms                                                | 1.61 ms: 1.02x faster                                                  |
| scimark_monte_carlo     | 71.0 ms                                                | 69.8 ms: 1.02x faster                                                  |
| xml_etree_process       | 58.6 ms                                                | 57.6 ms: 1.02x faster                                                  |
| scimark_sor             | 125 ms                                                 | 123 ms: 1.01x faster                                                   |
| logging_simple          | 6.18 us                                                | 6.09 us: 1.01x faster                                                  |
| xml_etree_generate      | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                  |
| xml_etree_iterparse     | 104 ms                                                 | 102 ms: 1.01x faster                                                   |
| xml_etree_parse         | 154 ms                                                 | 152 ms: 1.01x faster                                                   |
| regex_dna               | 209 ms                                                 | 206 ms: 1.01x faster                                                   |
| logging_format          | 6.90 us                                                | 6.85 us: 1.01x faster                                                  |
| unpickle_list           | 4.95 us                                                | 4.91 us: 1.01x faster                                                  |
| python_startup_no_site  | 6.90 ms                                                | 6.87 ms: 1.00x faster                                                  |
| deepcopy                | 355 us                                                 | 357 us: 1.00x slower                                                   |
| sqlglot_normalize       | 107 ms                                                 | 108 ms: 1.00x slower                                                   |
| gc_traversal            | 3.84 ms                                                | 3.86 ms: 1.01x slower                                                  |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.81 sec: 1.01x slower                                                 |
| bench_thread_pool       | 827 us                                                 | 834 us: 1.01x slower                                                   |
| json_loads              | 25.2 us                                                | 25.5 us: 1.01x slower                                                  |
| json_dumps              | 9.85 ms                                                | 9.93 ms: 1.01x slower                                                  |
| sqlite_synth            | 2.76 us                                                | 2.78 us: 1.01x slower                                                  |
| coroutines              | 22.4 ms                                                | 22.7 ms: 1.01x slower                                                  |
| pidigits                | 187 ms                                                 | 189 ms: 1.01x slower                                                   |
| pprint_pformat          | 1.50 sec                                               | 1.52 sec: 1.01x slower                                                 |
| regex_compile           | 144 ms                                                 | 145 ms: 1.01x slower                                                   |
| mdp                     | 2.57 sec                                               | 2.60 sec: 1.01x slower                                                 |
| dulwich_log             | 67.9 ms                                                | 69.0 ms: 1.02x slower                                                  |
| deepcopy_reduce         | 3.14 us                                                | 3.19 us: 1.02x slower                                                  |
| spectral_norm           | 106 ms                                                 | 108 ms: 1.02x slower                                                   |
| pprint_safe_repr        | 735 ms                                                 | 748 ms: 1.02x slower                                                   |
| sqlglot_optimize        | 53.3 ms                                                | 54.3 ms: 1.02x slower                                                  |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.84 ms: 1.02x slower                                                  |
| mypy2                   | 344 ms                                                 | 351 ms: 1.02x slower                                                   |
| pyflate                 | 450 ms                                                 | 461 ms: 1.02x slower                                                   |
| mako                    | 10.7 ms                                                | 11.0 ms: 1.03x slower                                                  |
| float                   | 80.7 ms                                                | 83.1 ms: 1.03x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.19 sec: 1.03x slower                                                 |
| async_generators        | 440 ms                                                 | 457 ms: 1.04x slower                                                   |
| pycparser               | 1.15 sec                                               | 1.20 sec: 1.04x slower                                                 |
| json                    | 4.77 ms                                                | 4.97 ms: 1.04x slower                                                  |
| chaos                   | 63.5 ms                                                | 66.6 ms: 1.05x slower                                                  |
| deepcopy_memo           | 37.4 us                                                | 39.2 us: 1.05x slower                                                  |
| fannkuch                | 387 ms                                                 | 408 ms: 1.05x slower                                                   |
| unpickle_pure_python    | 218 us                                                 | 230 us: 1.05x slower                                                   |
| regex_v8                | 22.3 ms                                                | 23.6 ms: 1.05x slower                                                  |
| logging_silent          | 99.1 ns                                                | 105 ns: 1.06x slower                                                   |
| python_startup          | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                  |
| meteor_contest          | 105 ms                                                 | 112 ms: 1.07x slower                                                   |
| go                      | 136 ms                                                 | 146 ms: 1.08x slower                                                   |
| unpack_sequence         | 44.8 ns                                                | 49.0 ns: 1.09x slower                                                  |
| nbody                   | 88.8 ms                                                | 97.5 ms: 1.10x slower                                                  |
| nqueens                 | 81.1 ms                                                | 89.4 ms: 1.10x slower                                                  |
| richards_super          | 49.0 ms                                                | 54.4 ms: 1.11x slower                                                  |
| richards                | 43.2 ms                                                | 48.0 ms: 1.11x slower                                                  |
| hexiom                  | 6.12 ms                                                | 6.89 ms: 1.13x slower                                                  |
| comprehensions          | 20.4 us                                                | 23.1 us: 1.13x slower                                                  |
| telco                   | 6.87 ms                                                | 8.22 ms: 1.20x slower                                                  |
| dask                    | 365 ms                                                 | 532 ms: 1.46x slower                                                   |
| Geometric mean          | (ref)                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (11): async_tree_cpu_io_mixed, async_tree_memoization, typing_runtime_protocols, scimark_fft, regex_effbot, bench_mp_pool, create_gc_cycles, pathlib, docutils, scimark_lu, pickle_list
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.66% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
