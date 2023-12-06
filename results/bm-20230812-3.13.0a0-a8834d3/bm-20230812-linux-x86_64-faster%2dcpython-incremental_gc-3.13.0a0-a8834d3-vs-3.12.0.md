
# Results vs. 3.12.0

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: a8834d3
- commit date: 2023-08-12
- overall geometric mean: 1.04x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-a8834d3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.70 sec                                               | 2.37 sec: 1.14x faster                                                    |
| tornado_http   | 99.6 ms                                                | 94.0 ms: 1.06x faster                                                     |
| Geometric mean | (ref)                                                  | 1.10x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-a8834d3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.7 ms                                                | 70.9 ms: 1.14x faster                                                     |
| pidigits       | 187 ms                                                 | 201 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-a8834d3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_compile  | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| regex_effbot   | 3.55 ms                                                | 3.43 ms: 1.03x faster                                                     |
| regex_v8       | 22.3 ms                                                | 21.7 ms: 1.03x faster                                                     |
| regex_dna      | 209 ms                                                 | 204 ms: 1.02x faster                                                      |
| Geometric mean | (ref)                                                  | 1.04x faster                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-a8834d3 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 94.1 ms: 1.10x faster                                                     |
| xml_etree_parse      | 154 ms                                                 | 139 ms: 1.10x faster                                                      |
| xml_etree_generate   | 84.8 ms                                                | 80.5 ms: 1.05x faster                                                     |
| xml_etree_process    | 58.6 ms                                                | 56.0 ms: 1.05x faster                                                     |
| pickle_pure_python   | 309 us                                                 | 297 us: 1.04x faster                                                      |
| unpickle_pure_python | 218 us                                                 | 212 us: 1.03x faster                                                      |
| pickle_list          | 4.62 us                                                | 4.52 us: 1.02x faster                                                     |
| unpickle             | 15.0 us                                                | 14.7 us: 1.02x faster                                                     |
| json_dumps           | 9.85 ms                                                | 9.76 ms: 1.01x faster                                                     |
| json_loads           | 25.2 us                                                | 25.7 us: 1.02x slower                                                     |
| pickle               | 10.6 us                                                | 10.8 us: 1.02x slower                                                     |
| tomli_loads          | 2.22 sec                                               | 2.31 sec: 1.04x slower                                                    |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                              |

Benchmark hidden because not significant (2): pickle_dict, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-a8834d3 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| python_startup_no_site | 6.90 ms                                                | 6.80 ms: 1.01x faster                                                     |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230812-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-a8834d3 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io           | 1.16 sec                                               | 565 ms: 2.05x faster                                                      |
| async_tree_none         | 469 ms                                                 | 276 ms: 1.70x faster                                                      |
| async_tree_memoization  | 573 ms                                                 | 343 ms: 1.67x faster                                                      |
| async_tree_cpu_io_mixed | 714 ms                                                 | 505 ms: 1.41x faster                                                      |
| float                   | 80.7 ms                                                | 70.9 ms: 1.14x faster                                                     |
| docutils                | 2.70 sec                                               | 2.37 sec: 1.14x faster                                                    |
| deltablue               | 3.52 ms                                                | 3.13 ms: 1.12x faster                                                     |
| crypto_pyaes            | 77.2 ms                                                | 69.3 ms: 1.11x faster                                                     |
| raytrace                | 294 ms                                                 | 267 ms: 1.10x faster                                                      |
| generators              | 31.1 ms                                                | 28.2 ms: 1.10x faster                                                     |
| xml_etree_iterparse     | 104 ms                                                 | 94.1 ms: 1.10x faster                                                     |
| xml_etree_parse         | 154 ms                                                 | 139 ms: 1.10x faster                                                      |
| chaos                   | 63.5 ms                                                | 58.7 ms: 1.08x faster                                                     |
| asyncio_tcp             | 526 ms                                                 | 486 ms: 1.08x faster                                                      |
| logging_format          | 6.90 us                                                | 6.44 us: 1.07x faster                                                     |
| scimark_monte_carlo     | 71.0 ms                                                | 66.4 ms: 1.07x faster                                                     |
| create_gc_cycles        | 1.52 ms                                                | 1.42 ms: 1.07x faster                                                     |
| tornado_http            | 99.6 ms                                                | 94.0 ms: 1.06x faster                                                     |
| regex_compile           | 144 ms                                                 | 136 ms: 1.06x faster                                                      |
| xml_etree_generate      | 84.8 ms                                                | 80.5 ms: 1.05x faster                                                     |
| logging_simple          | 6.18 us                                                | 5.88 us: 1.05x faster                                                     |
| xml_etree_process       | 58.6 ms                                                | 56.0 ms: 1.05x faster                                                     |
| gc_traversal            | 3.84 ms                                                | 3.68 ms: 1.04x faster                                                     |
| scimark_sor             | 125 ms                                                 | 119 ms: 1.04x faster                                                      |
| pickle_pure_python      | 309 us                                                 | 297 us: 1.04x faster                                                      |
| sqlglot_parse           | 1.32 ms                                                | 1.27 ms: 1.04x faster                                                     |
| regex_effbot            | 3.55 ms                                                | 3.43 ms: 1.03x faster                                                     |
| async_generators        | 440 ms                                                 | 426 ms: 1.03x faster                                                      |
| dulwich_log             | 67.9 ms                                                | 65.7 ms: 1.03x faster                                                     |
| sqlglot_transpile       | 1.64 ms                                                | 1.59 ms: 1.03x faster                                                     |
| unpickle_pure_python    | 218 us                                                 | 212 us: 1.03x faster                                                      |
| regex_v8                | 22.3 ms                                                | 21.7 ms: 1.03x faster                                                     |
| sqlglot_normalize       | 107 ms                                                 | 104 ms: 1.03x faster                                                      |
| pprint_pformat          | 1.50 sec                                               | 1.47 sec: 1.02x faster                                                    |
| pycparser               | 1.15 sec                                               | 1.12 sec: 1.02x faster                                                    |
| pickle_list             | 4.62 us                                                | 4.52 us: 1.02x faster                                                     |
| python_startup          | 9.47 ms                                                | 9.27 ms: 1.02x faster                                                     |
| scimark_lu              | 114 ms                                                 | 112 ms: 1.02x faster                                                      |
| regex_dna               | 209 ms                                                 | 204 ms: 1.02x faster                                                      |
| unpickle                | 15.0 us                                                | 14.7 us: 1.02x faster                                                     |
| pprint_safe_repr        | 735 ms                                                 | 722 ms: 1.02x faster                                                      |
| hexiom                  | 6.12 ms                                                | 6.02 ms: 1.02x faster                                                     |
| mypy2                   | 344 ms                                                 | 338 ms: 1.02x faster                                                      |
| sqlglot_optimize        | 53.3 ms                                                | 52.5 ms: 1.02x faster                                                     |
| python_startup_no_site  | 6.90 ms                                                | 6.80 ms: 1.01x faster                                                     |
| coverage                | 94.2 ms                                                | 92.9 ms: 1.01x faster                                                     |
| coroutines              | 22.4 ms                                                | 22.2 ms: 1.01x faster                                                     |
| json_dumps              | 9.85 ms                                                | 9.76 ms: 1.01x faster                                                     |
| asyncio_tcp_ssl         | 1.79 sec                                               | 1.78 sec: 1.01x faster                                                    |
| pathlib                 | 18.5 ms                                                | 18.4 ms: 1.01x faster                                                     |
| nqueens                 | 81.1 ms                                                | 80.7 ms: 1.01x faster                                                     |
| pyflate                 | 450 ms                                                 | 453 ms: 1.01x slower                                                      |
| go                      | 136 ms                                                 | 137 ms: 1.01x slower                                                      |
| scimark_sparse_mat_mult | 4.74 ms                                                | 4.79 ms: 1.01x slower                                                     |
| meteor_contest          | 105 ms                                                 | 106 ms: 1.01x slower                                                      |
| spectral_norm           | 106 ms                                                 | 107 ms: 1.01x slower                                                      |
| sqlite_synth            | 2.76 us                                                | 2.80 us: 1.01x slower                                                     |
| json                    | 4.77 ms                                                | 4.86 ms: 1.02x slower                                                     |
| json_loads              | 25.2 us                                                | 25.7 us: 1.02x slower                                                     |
| logging_silent          | 99.1 ns                                                | 101 ns: 1.02x slower                                                      |
| pickle                  | 10.6 us                                                | 10.8 us: 1.02x slower                                                     |
| unpack_sequence         | 44.8 ns                                                | 46.1 ns: 1.03x slower                                                     |
| tomli_loads             | 2.22 sec                                               | 2.31 sec: 1.04x slower                                                    |
| mdp                     | 2.57 sec                                               | 2.72 sec: 1.06x slower                                                    |
| pidigits                | 187 ms                                                 | 201 ms: 1.08x slower                                                      |
| richards_super          | 49.0 ms                                                | 53.2 ms: 1.09x slower                                                     |
| richards                | 43.2 ms                                                | 47.4 ms: 1.10x slower                                                     |
| telco                   | 6.87 ms                                                | 7.94 ms: 1.16x slower                                                     |
| dask                    | 365 ms                                                 | 486 ms: 1.33x slower                                                      |
| Geometric mean          | (ref)                                                  | 1.04x faster                                                              |

Benchmark hidden because not significant (13): nbody, mako, typing_runtime_protocols, bench_thread_pool, pickle_dict, comprehensions, deepcopy, scimark_fft, deepcopy_memo, bench_mp_pool, fannkuch, deepcopy_reduce, unpickle_list
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.01x
