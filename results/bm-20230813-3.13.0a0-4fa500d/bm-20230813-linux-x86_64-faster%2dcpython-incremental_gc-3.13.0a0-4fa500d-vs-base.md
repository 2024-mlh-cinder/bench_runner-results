
# Results vs. base

- fork: faster-cpython
- ref: incremental_gc
- machine: linux-x86_64
- commit hash: 4fa500d
- commit date: 2023-08-13
- overall geometric mean: 1.03x faster
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230823-linux-x86_64-python-2135bcd3ca9538c67821-3.13.0a0-2135bcd | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 2.64 sec                                                              | 2.39 sec: 1.11x faster                                                    |
| tornado_http   | 95.6 ms                                                               | 93.4 ms: 1.02x faster                                                     |
| Geometric mean | (ref)                                                                 | 1.06x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230823-linux-x86_64-python-2135bcd3ca9538c67821-3.13.0a0-2135bcd | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 80.6 ms                                                               | 76.0 ms: 1.06x faster                                                     |
| nbody          | 91.7 ms                                                               | 88.9 ms: 1.03x faster                                                     |
| pidigits       | 189 ms                                                                | 201 ms: 1.06x slower                                                      |
| Geometric mean | (ref)                                                                 | 1.01x faster                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230823-linux-x86_64-python-2135bcd3ca9538c67821-3.13.0a0-2135bcd | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_effbot   | 3.72 ms                                                               | 3.69 ms: 1.01x faster                                                     |
| regex_v8       | 24.5 ms                                                               | 26.5 ms: 1.08x slower                                                     |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                              |

Benchmark hidden because not significant (2): regex_compile, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230823-linux-x86_64-python-2135bcd3ca9538c67821-3.13.0a0-2135bcd | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| pickle               | 10.7 us                                                               | 10.3 us: 1.05x faster                                                     |
| xml_etree_iterparse  | 103 ms                                                                | 98.6 ms: 1.04x faster                                                     |
| pickle_list          | 4.65 us                                                               | 4.56 us: 1.02x faster                                                     |
| unpickle_pure_python | 216 us                                                                | 212 us: 1.02x faster                                                      |
| xml_etree_generate   | 83.1 ms                                                               | 81.9 ms: 1.01x faster                                                     |
| pickle_pure_python   | 301 us                                                                | 298 us: 1.01x faster                                                      |
| pickle_dict          | 31.7 us                                                               | 31.4 us: 1.01x faster                                                     |
| xml_etree_process    | 57.3 ms                                                               | 56.8 ms: 1.01x faster                                                     |
| tomli_loads          | 2.12 sec                                                              | 2.10 sec: 1.01x faster                                                    |
| json_loads           | 25.3 us                                                               | 25.2 us: 1.00x faster                                                     |
| json_dumps           | 9.68 ms                                                               | 9.82 ms: 1.01x slower                                                     |
| unpickle_list        | 4.93 us                                                               | 5.15 us: 1.04x slower                                                     |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                              |

Benchmark hidden because not significant (2): xml_etree_parse, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230823-linux-x86_64-python-2135bcd3ca9538c67821-3.13.0a0-2135bcd | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup_no_site | 6.85 ms                                                               | 6.72 ms: 1.02x faster                                                     |
| python_startup         | 9.34 ms                                                               | 9.20 ms: 1.02x faster                                                     |
| Geometric mean         | (ref)                                                                 | 1.02x faster                                                              |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20230823-linux-x86_64-python-2135bcd3ca9538c67821-3.13.0a0-2135bcd | bm-20230813-linux-x86_64-faster%2dcpython-incremental_gc-3.13.0a0-4fa500d |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------------:|
| async_tree_io            | 1.19 sec                                                              | 608 ms: 1.96x faster                                                      |
| async_tree_memoization   | 568 ms                                                                | 383 ms: 1.48x faster                                                      |
| async_tree_none          | 441 ms                                                                | 313 ms: 1.41x faster                                                      |
| async_tree_cpu_io_mixed  | 700 ms                                                                | 531 ms: 1.32x faster                                                      |
| gc_traversal             | 4.32 ms                                                               | 3.66 ms: 1.18x faster                                                     |
| docutils                 | 2.64 sec                                                              | 2.39 sec: 1.11x faster                                                    |
| float                    | 80.6 ms                                                               | 76.0 ms: 1.06x faster                                                     |
| async_generators         | 455 ms                                                                | 429 ms: 1.06x faster                                                      |
| dask                     | 527 ms                                                                | 501 ms: 1.05x faster                                                      |
| pickle                   | 10.7 us                                                               | 10.3 us: 1.05x faster                                                     |
| xml_etree_iterparse      | 103 ms                                                                | 98.6 ms: 1.04x faster                                                     |
| create_gc_cycles         | 1.50 ms                                                               | 1.44 ms: 1.04x faster                                                     |
| typing_runtime_protocols | 148 us                                                                | 143 us: 1.03x faster                                                      |
| nbody                    | 91.7 ms                                                               | 88.9 ms: 1.03x faster                                                     |
| comprehensions           | 21.1 us                                                               | 20.5 us: 1.03x faster                                                     |
| mdp                      | 2.59 sec                                                              | 2.52 sec: 1.03x faster                                                    |
| richards                 | 48.7 ms                                                               | 47.4 ms: 1.03x faster                                                     |
| scimark_monte_carlo      | 67.1 ms                                                               | 65.5 ms: 1.02x faster                                                     |
| tornado_http             | 95.6 ms                                                               | 93.4 ms: 1.02x faster                                                     |
| scimark_sparse_mat_mult  | 4.93 ms                                                               | 4.83 ms: 1.02x faster                                                     |
| python_startup_no_site   | 6.85 ms                                                               | 6.72 ms: 1.02x faster                                                     |
| pickle_list              | 4.65 us                                                               | 4.56 us: 1.02x faster                                                     |
| json                     | 4.88 ms                                                               | 4.79 ms: 1.02x faster                                                     |
| python_startup           | 9.34 ms                                                               | 9.20 ms: 1.02x faster                                                     |
| unpickle_pure_python     | 216 us                                                                | 212 us: 1.02x faster                                                      |
| deltablue                | 3.31 ms                                                               | 3.26 ms: 1.01x faster                                                     |
| xml_etree_generate       | 83.1 ms                                                               | 81.9 ms: 1.01x faster                                                     |
| scimark_sor              | 122 ms                                                                | 121 ms: 1.01x faster                                                      |
| sqlite_synth             | 2.76 us                                                               | 2.74 us: 1.01x faster                                                     |
| pyflate                  | 453 ms                                                                | 448 ms: 1.01x faster                                                      |
| sqlglot_parse            | 1.27 ms                                                               | 1.26 ms: 1.01x faster                                                     |
| scimark_fft              | 356 ms                                                                | 353 ms: 1.01x faster                                                      |
| pickle_pure_python       | 301 us                                                                | 298 us: 1.01x faster                                                      |
| pickle_dict              | 31.7 us                                                               | 31.4 us: 1.01x faster                                                     |
| regex_effbot             | 3.72 ms                                                               | 3.69 ms: 1.01x faster                                                     |
| xml_etree_process        | 57.3 ms                                                               | 56.8 ms: 1.01x faster                                                     |
| pathlib                  | 18.6 ms                                                               | 18.5 ms: 1.01x faster                                                     |
| tomli_loads              | 2.12 sec                                                              | 2.10 sec: 1.01x faster                                                    |
| deepcopy_reduce          | 3.18 us                                                               | 3.16 us: 1.01x faster                                                     |
| json_loads               | 25.3 us                                                               | 25.2 us: 1.00x faster                                                     |
| asyncio_tcp              | 476 ms                                                                | 475 ms: 1.00x faster                                                      |
| bench_thread_pool        | 817 us                                                                | 814 us: 1.00x faster                                                      |
| hexiom                   | 6.00 ms                                                               | 5.98 ms: 1.00x faster                                                     |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.79 sec: 1.00x faster                                                    |
| dulwich_log              | 66.0 ms                                                               | 66.2 ms: 1.00x slower                                                     |
| go                       | 140 ms                                                                | 141 ms: 1.00x slower                                                      |
| pprint_pformat           | 1.49 sec                                                              | 1.49 sec: 1.00x slower                                                    |
| meteor_contest           | 105 ms                                                                | 106 ms: 1.01x slower                                                      |
| chaos                    | 59.3 ms                                                               | 59.7 ms: 1.01x slower                                                     |
| raytrace                 | 272 ms                                                                | 273 ms: 1.01x slower                                                      |
| sqlglot_normalize        | 104 ms                                                                | 105 ms: 1.01x slower                                                      |
| fannkuch                 | 391 ms                                                                | 394 ms: 1.01x slower                                                      |
| crypto_pyaes             | 68.6 ms                                                               | 69.2 ms: 1.01x slower                                                     |
| spectral_norm            | 104 ms                                                                | 105 ms: 1.01x slower                                                      |
| sqlglot_optimize         | 52.2 ms                                                               | 52.7 ms: 1.01x slower                                                     |
| deepcopy                 | 349 us                                                                | 353 us: 1.01x slower                                                      |
| logging_silent           | 104 ns                                                                | 105 ns: 1.01x slower                                                      |
| telco                    | 7.98 ms                                                               | 8.09 ms: 1.01x slower                                                     |
| json_dumps               | 9.68 ms                                                               | 9.82 ms: 1.01x slower                                                     |
| unpack_sequence          | 45.3 ns                                                               | 46.1 ns: 1.02x slower                                                     |
| deepcopy_memo            | 36.9 us                                                               | 37.6 us: 1.02x slower                                                     |
| nqueens                  | 78.9 ms                                                               | 80.7 ms: 1.02x slower                                                     |
| mypy2                    | 338 ms                                                                | 347 ms: 1.03x slower                                                      |
| unpickle_list            | 4.93 us                                                               | 5.15 us: 1.04x slower                                                     |
| pidigits                 | 189 ms                                                                | 201 ms: 1.06x slower                                                      |
| regex_v8                 | 24.5 ms                                                               | 26.5 ms: 1.08x slower                                                     |
| Geometric mean           | (ref)                                                                 | 1.03x faster                                                              |

Benchmark hidden because not significant (16): xml_etree_parse, richards_super, logging_simple, unpickle, regex_compile, pycparser, pprint_safe_repr, coroutines, regex_dna, mako, bench_mp_pool, sqlglot_transpile, logging_format, coverage, scimark_lu, generators


# HPT report

- Reliability score: 99.93% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
