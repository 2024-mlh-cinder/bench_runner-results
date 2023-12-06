
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 2b170f6
- commit date: 2023-09-13
- overall geometric mean: 1.04x slower
- HPT reliability: 99.61%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.69 sec: 1.00x faster                                                  |
| tornado_http   | 99.6 ms                                                | 97.4 ms: 1.02x faster                                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 189 ms: 1.02x slower                                                    |
| float          | 80.7 ms                                                | 84.3 ms: 1.04x slower                                                   |
| nbody          | 88.8 ms                                                | 127 ms: 1.43x slower                                                    |
| Geometric mean | (ref)                                                  | 1.15x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                   |
| regex_compile  | 144 ms                                                 | 148 ms: 1.03x slower                                                    |
| regex_v8       | 22.3 ms                                                | 24.1 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 309 us                                                 | 298 us: 1.04x faster                                                    |
| tomli_loads          | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                  |
| xml_etree_process    | 58.6 ms                                                | 57.8 ms: 1.01x faster                                                   |
| xml_etree_generate   | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                   |
| xml_etree_parse      | 154 ms                                                 | 152 ms: 1.01x faster                                                    |
| xml_etree_iterparse  | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| pickle_dict          | 31.6 us                                                | 31.7 us: 1.00x slower                                                   |
| pickle_list          | 4.62 us                                                | 4.67 us: 1.01x slower                                                   |
| json_dumps           | 9.85 ms                                                | 9.96 ms: 1.01x slower                                                   |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                   |
| unpickle             | 15.0 us                                                | 15.5 us: 1.03x slower                                                   |
| unpickle_pure_python | 218 us                                                 | 234 us: 1.07x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.00x slower                                                            |

Benchmark hidden because not significant (2): unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.89 ms: 1.00x faster                                                   |
| python_startup         | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.7 ms: 1.10x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| generators               | 31.1 ms                                                | 27.8 ms: 1.12x faster                                                   |
| coverage                 | 94.2 ms                                                | 86.8 ms: 1.08x faster                                                   |
| asyncio_tcp              | 526 ms                                                 | 490 ms: 1.07x faster                                                    |
| raytrace                 | 294 ms                                                 | 277 ms: 1.06x faster                                                    |
| scimark_monte_carlo      | 71.0 ms                                                | 67.5 ms: 1.05x faster                                                   |
| async_tree_none          | 469 ms                                                 | 450 ms: 1.04x faster                                                    |
| gc_traversal             | 3.84 ms                                                | 3.69 ms: 1.04x faster                                                   |
| pickle_pure_python       | 309 us                                                 | 298 us: 1.04x faster                                                    |
| crypto_pyaes             | 77.2 ms                                                | 74.7 ms: 1.03x faster                                                   |
| logging_format           | 6.90 us                                                | 6.71 us: 1.03x faster                                                   |
| logging_simple           | 6.18 us                                                | 6.03 us: 1.02x faster                                                   |
| tornado_http             | 99.6 ms                                                | 97.4 ms: 1.02x faster                                                   |
| tomli_loads              | 2.22 sec                                               | 2.18 sec: 1.02x faster                                                  |
| coroutines               | 22.4 ms                                                | 22.1 ms: 1.01x faster                                                   |
| xml_etree_process        | 58.6 ms                                                | 57.8 ms: 1.01x faster                                                   |
| xml_etree_generate       | 84.8 ms                                                | 83.7 ms: 1.01x faster                                                   |
| create_gc_cycles         | 1.52 ms                                                | 1.50 ms: 1.01x faster                                                   |
| xml_etree_parse          | 154 ms                                                 | 152 ms: 1.01x faster                                                    |
| sqlglot_parse            | 1.32 ms                                                | 1.31 ms: 1.01x faster                                                   |
| deltablue                | 3.52 ms                                                | 3.48 ms: 1.01x faster                                                   |
| sqlglot_transpile        | 1.64 ms                                                | 1.63 ms: 1.01x faster                                                   |
| xml_etree_iterparse      | 104 ms                                                 | 103 ms: 1.01x faster                                                    |
| docutils                 | 2.70 sec                                               | 2.69 sec: 1.00x faster                                                  |
| python_startup_no_site   | 6.90 ms                                                | 6.89 ms: 1.00x faster                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                                  |
| pickle_dict              | 31.6 us                                                | 31.7 us: 1.00x slower                                                   |
| regex_effbot             | 3.55 ms                                                | 3.57 ms: 1.01x slower                                                   |
| pprint_pformat           | 1.50 sec                                               | 1.51 sec: 1.01x slower                                                  |
| pprint_safe_repr         | 735 ms                                                 | 741 ms: 1.01x slower                                                    |
| sqlglot_optimize         | 53.3 ms                                                | 53.8 ms: 1.01x slower                                                   |
| pickle_list              | 4.62 us                                                | 4.67 us: 1.01x slower                                                   |
| json_dumps               | 9.85 ms                                                | 9.96 ms: 1.01x slower                                                   |
| bench_thread_pool        | 827 us                                                 | 838 us: 1.01x slower                                                    |
| dulwich_log              | 67.9 ms                                                | 69.0 ms: 1.02x slower                                                   |
| pidigits                 | 187 ms                                                 | 189 ms: 1.02x slower                                                    |
| sqlite_synth             | 2.76 us                                                | 2.81 us: 1.02x slower                                                   |
| deepcopy                 | 355 us                                                 | 362 us: 1.02x slower                                                    |
| pickle                   | 10.6 us                                                | 10.8 us: 1.02x slower                                                   |
| mdp                      | 2.57 sec                                               | 2.63 sec: 1.02x slower                                                  |
| deepcopy_reduce          | 3.14 us                                                | 3.22 us: 1.03x slower                                                   |
| pathlib                  | 18.5 ms                                                | 19.0 ms: 1.03x slower                                                   |
| unpickle                 | 15.0 us                                                | 15.5 us: 1.03x slower                                                   |
| regex_compile            | 144 ms                                                 | 148 ms: 1.03x slower                                                    |
| mypy2                    | 344 ms                                                 | 358 ms: 1.04x slower                                                    |
| async_tree_io            | 1.16 sec                                               | 1.21 sec: 1.04x slower                                                  |
| float                    | 80.7 ms                                                | 84.3 ms: 1.04x slower                                                   |
| spectral_norm            | 106 ms                                                 | 112 ms: 1.05x slower                                                    |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.05x slower                                                  |
| meteor_contest           | 105 ms                                                 | 111 ms: 1.06x slower                                                    |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                                    |
| pyflate                  | 450 ms                                                 | 477 ms: 1.06x slower                                                    |
| typing_runtime_protocols | 146 us                                                 | 155 us: 1.06x slower                                                    |
| python_startup           | 9.47 ms                                                | 10.1 ms: 1.07x slower                                                   |
| async_generators         | 440 ms                                                 | 470 ms: 1.07x slower                                                    |
| deepcopy_memo            | 37.4 us                                                | 40.1 us: 1.07x slower                                                   |
| unpickle_pure_python     | 218 us                                                 | 234 us: 1.07x slower                                                    |
| scimark_fft              | 358 ms                                                 | 386 ms: 1.08x slower                                                    |
| regex_v8                 | 22.3 ms                                                | 24.1 ms: 1.08x slower                                                   |
| mako                     | 10.7 ms                                                | 11.7 ms: 1.10x slower                                                   |
| go                       | 136 ms                                                 | 151 ms: 1.11x slower                                                    |
| richards                 | 43.2 ms                                                | 48.4 ms: 1.12x slower                                                   |
| fannkuch                 | 387 ms                                                 | 435 ms: 1.12x slower                                                    |
| richards_super           | 49.0 ms                                                | 55.4 ms: 1.13x slower                                                   |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.38 ms: 1.13x slower                                                   |
| chaos                    | 63.5 ms                                                | 72.7 ms: 1.14x slower                                                   |
| nqueens                  | 81.1 ms                                                | 95.7 ms: 1.18x slower                                                   |
| telco                    | 6.87 ms                                                | 8.13 ms: 1.18x slower                                                   |
| hexiom                   | 6.12 ms                                                | 7.28 ms: 1.19x slower                                                   |
| unpack_sequence          | 44.8 ns                                                | 55.2 ns: 1.23x slower                                                   |
| comprehensions           | 20.4 us                                                | 25.4 us: 1.24x slower                                                   |
| nbody                    | 88.8 ms                                                | 127 ms: 1.43x slower                                                    |
| dask                     | 365 ms                                                 | 535 ms: 1.47x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                            |

Benchmark hidden because not significant (10): scimark_lu, scimark_sor, async_tree_cpu_io_mixed, async_tree_memoization, unpickle_list, bench_mp_pool, sqlglot_normalize, regex_dna, json_loads, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 99.61% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
