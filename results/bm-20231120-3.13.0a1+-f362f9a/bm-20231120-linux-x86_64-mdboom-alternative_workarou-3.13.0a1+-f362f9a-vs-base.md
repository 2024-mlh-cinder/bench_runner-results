
# Results vs. base

- fork: mdboom
- ref: alternative_workarou
- machine: linux-x86_64
- commit hash: f362f9a
- commit date: 2023-11-20
- overall geometric mean: 1.00x faster
- HPT reliability: 99.85%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 264 ms                                                                 | 264 ms: 1.00x faster                                                   |
| chameleon      | 7.02 ms                                                                | 6.93 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_io_tg       | 1.23 sec                                                               | 1.21 sec: 1.02x faster                                                 |
| async_tree_io          | 1.20 sec                                                               | 1.18 sec: 1.02x faster                                                 |
| async_tree_memoization | 565 ms                                                                 | 559 ms: 1.01x faster                                                   |
| async_tree_none_tg     | 457 ms                                                                 | 454 ms: 1.01x faster                                                   |
| Geometric mean         | (ref)                                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (4): async_tree_none, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 90.8 ms                                                                | 89.9 ms: 1.01x faster                                                  |
| pidigits       | 195 ms                                                                 | 195 ms: 1.00x faster                                                   |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 3.72 ms                                                                | 3.64 ms: 1.02x faster                                                  |
| regex_compile  | 135 ms                                                                 | 133 ms: 1.02x faster                                                   |
| regex_dna      | 217 ms                                                                 | 215 ms: 1.01x faster                                                   |
| regex_v8       | 25.5 ms                                                                | 25.6 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| tomli_loads          | 2.17 sec                                                               | 2.15 sec: 1.01x faster                                                 |
| json_loads           | 28.2 us                                                                | 28.1 us: 1.01x faster                                                  |
| unpickle_pure_python | 220 us                                                                 | 221 us: 1.00x slower                                                   |
| xml_etree_iterparse  | 105 ms                                                                 | 106 ms: 1.01x slower                                                   |
| unpickle_list        | 5.10 us                                                                | 5.15 us: 1.01x slower                                                  |
| pickle_list          | 4.92 us                                                                | 4.97 us: 1.01x slower                                                  |
| xml_etree_process    | 59.5 ms                                                                | 60.1 ms: 1.01x slower                                                  |
| pickle_dict          | 32.4 us                                                                | 33.3 us: 1.03x slower                                                  |
| pickle               | 11.0 us                                                                | 11.4 us: 1.04x slower                                                  |
| unpickle             | 14.3 us                                                                | 15.9 us: 1.11x slower                                                  |
| Geometric mean       | (ref)                                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (4): xml_etree_parse, pickle_pure_python, xml_etree_generate, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                  |
| python_startup_no_site | 8.97 ms                                                                | 9.03 ms: 1.01x slower                                                  |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.6 ms                                                                | 11.4 ms: 1.02x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| logging_silent           | 110 ns                                                                 | 105 ns: 1.05x faster                                                   |
| richards                 | 48.5 ms                                                                | 47.1 ms: 1.03x faster                                                  |
| richards_super           | 54.6 ms                                                                | 53.3 ms: 1.03x faster                                                  |
| meteor_contest           | 109 ms                                                                 | 107 ms: 1.03x faster                                                   |
| typing_runtime_protocols | 119 us                                                                 | 116 us: 1.02x faster                                                   |
| regex_effbot             | 3.72 ms                                                                | 3.64 ms: 1.02x faster                                                  |
| unpack_sequence          | 46.3 ns                                                                | 45.3 ns: 1.02x faster                                                  |
| mako                     | 11.6 ms                                                                | 11.4 ms: 1.02x faster                                                  |
| async_tree_io_tg         | 1.23 sec                                                               | 1.21 sec: 1.02x faster                                                 |
| nqueens                  | 82.1 ms                                                                | 80.7 ms: 1.02x faster                                                  |
| async_tree_io            | 1.20 sec                                                               | 1.18 sec: 1.02x faster                                                 |
| regex_compile            | 135 ms                                                                 | 133 ms: 1.02x faster                                                   |
| logging_simple           | 5.77 us                                                                | 5.68 us: 1.02x faster                                                  |
| spectral_norm            | 115 ms                                                                 | 113 ms: 1.01x faster                                                   |
| logging_format           | 6.31 us                                                                | 6.23 us: 1.01x faster                                                  |
| comprehensions           | 16.7 us                                                                | 16.5 us: 1.01x faster                                                  |
| chameleon                | 7.02 ms                                                                | 6.93 ms: 1.01x faster                                                  |
| async_generators         | 448 ms                                                                 | 443 ms: 1.01x faster                                                   |
| async_tree_memoization   | 565 ms                                                                 | 559 ms: 1.01x faster                                                   |
| pprint_pformat           | 1.51 sec                                                               | 1.49 sec: 1.01x faster                                                 |
| pprint_safe_repr         | 740 ms                                                                 | 732 ms: 1.01x faster                                                   |
| sympy_expand             | 455 ms                                                                 | 450 ms: 1.01x faster                                                   |
| go                       | 142 ms                                                                 | 141 ms: 1.01x faster                                                   |
| tomli_loads              | 2.17 sec                                                               | 2.15 sec: 1.01x faster                                                 |
| nbody                    | 90.8 ms                                                                | 89.9 ms: 1.01x faster                                                  |
| hexiom                   | 6.23 ms                                                                | 6.18 ms: 1.01x faster                                                  |
| regex_dna                | 217 ms                                                                 | 215 ms: 1.01x faster                                                   |
| async_tree_none_tg       | 457 ms                                                                 | 454 ms: 1.01x faster                                                   |
| deepcopy                 | 349 us                                                                 | 346 us: 1.01x faster                                                   |
| coroutines               | 22.0 ms                                                                | 21.8 ms: 1.01x faster                                                  |
| mdp                      | 2.74 sec                                                               | 2.72 sec: 1.01x faster                                                 |
| sqlglot_parse            | 1.28 ms                                                                | 1.27 ms: 1.01x faster                                                  |
| json_loads               | 28.2 us                                                                | 28.1 us: 1.01x faster                                                  |
| sqlglot_optimize         | 53.7 ms                                                                | 53.4 ms: 1.01x faster                                                  |
| json                     | 5.12 ms                                                                | 5.10 ms: 1.01x faster                                                  |
| sympy_integrate          | 19.5 ms                                                                | 19.5 ms: 1.00x faster                                                  |
| asyncio_tcp              | 488 ms                                                                 | 486 ms: 1.00x faster                                                   |
| pyflate                  | 469 ms                                                                 | 468 ms: 1.00x faster                                                   |
| 2to3                     | 264 ms                                                                 | 264 ms: 1.00x faster                                                   |
| sqlglot_normalize        | 106 ms                                                                 | 105 ms: 1.00x faster                                                   |
| pidigits                 | 195 ms                                                                 | 195 ms: 1.00x faster                                                   |
| bench_thread_pool        | 834 us                                                                 | 836 us: 1.00x slower                                                   |
| fannkuch                 | 398 ms                                                                 | 399 ms: 1.00x slower                                                   |
| unpickle_pure_python     | 220 us                                                                 | 221 us: 1.00x slower                                                   |
| python_startup           | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                  |
| telco                    | 8.32 ms                                                                | 8.37 ms: 1.01x slower                                                  |
| xml_etree_iterparse      | 105 ms                                                                 | 106 ms: 1.01x slower                                                   |
| regex_v8                 | 25.5 ms                                                                | 25.6 ms: 1.01x slower                                                  |
| python_startup_no_site   | 8.97 ms                                                                | 9.03 ms: 1.01x slower                                                  |
| scimark_sor              | 123 ms                                                                 | 124 ms: 1.01x slower                                                   |
| scimark_monte_carlo      | 67.9 ms                                                                | 68.4 ms: 1.01x slower                                                  |
| deepcopy_reduce          | 3.05 us                                                                | 3.08 us: 1.01x slower                                                  |
| generators               | 29.7 ms                                                                | 30.0 ms: 1.01x slower                                                  |
| unpickle_list            | 5.10 us                                                                | 5.15 us: 1.01x slower                                                  |
| pickle_list              | 4.92 us                                                                | 4.97 us: 1.01x slower                                                  |
| xml_etree_process        | 59.5 ms                                                                | 60.1 ms: 1.01x slower                                                  |
| scimark_fft              | 364 ms                                                                 | 368 ms: 1.01x slower                                                   |
| coverage                 | 94.8 ms                                                                | 96.3 ms: 1.02x slower                                                  |
| scimark_lu               | 114 ms                                                                 | 116 ms: 1.02x slower                                                   |
| pickle_dict              | 32.4 us                                                                | 33.3 us: 1.03x slower                                                  |
| pycparser                | 1.17 sec                                                               | 1.21 sec: 1.03x slower                                                 |
| pickle                   | 11.0 us                                                                | 11.4 us: 1.04x slower                                                  |
| gc_traversal             | 3.51 ms                                                                | 3.64 ms: 1.04x slower                                                  |
| scimark_sparse_mat_mult  | 4.63 ms                                                                | 4.97 ms: 1.07x slower                                                  |
| unpickle                 | 14.3 us                                                                | 15.9 us: 1.11x slower                                                  |
| Geometric mean           | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (28): async_tree_none, async_tree_memoization_tg, deepcopy_memo, float, sympy_str, pathlib, sympy_sum, mypy2, sqlglot_transpile, create_gc_cycles, xml_etree_parse, dulwich_log, pickle_pure_python, xml_etree_generate, docutils, crypto_pyaes, bench_mp_pool, asyncio_tcp_ssl, raytrace, asyncio_websockets, deltablue, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, sqlite_synth, chaos, dask, json_dumps, tornado_http


# HPT report

- Reliability score: 99.85% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
