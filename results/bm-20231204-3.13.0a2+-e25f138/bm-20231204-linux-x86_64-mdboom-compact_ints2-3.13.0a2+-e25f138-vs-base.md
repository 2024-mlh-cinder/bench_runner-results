
# Results vs. base

- fork: mdboom
- ref: compact_ints2
- machine: linux-x86_64
- commit hash: e25f138
- commit date: 2023-12-04
- overall geometric mean: 1.00x faster
- HPT reliability: 86.81%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| chameleon      | 6.88 ms                                                                | 7.01 ms: 1.02x slower                                           |
| tornado_http   | 96.0 ms                                                                | 94.6 ms: 1.01x faster                                           |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                    |

Benchmark hidden because not significant (2): 2to3, docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark      | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_io  | 1.18 sec                                                               | 1.19 sec: 1.01x slower                                          |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                    |

Benchmark hidden because not significant (7): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none_tg, async_tree_io_tg, async_tree_none, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 92.3 ms                                                                | 90.1 ms: 1.02x faster                                           |
| pidigits       | 187 ms                                                                 | 187 ms: 1.00x faster                                            |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                    |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_v8       | 26.1 ms                                                                | 26.4 ms: 1.01x slower                                           |
| regex_compile  | 133 ms                                                                 | 135 ms: 1.02x slower                                            |
| regex_dna      | 214 ms                                                                 | 220 ms: 1.03x slower                                            |
| regex_effbot   | 3.59 ms                                                                | 3.71 ms: 1.03x slower                                           |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                    |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|----------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| unpickle_list        | 5.23 us                                                                | 4.98 us: 1.05x faster                                           |
| pickle_pure_python   | 305 us                                                                 | 302 us: 1.01x faster                                            |
| json_loads           | 28.3 us                                                                | 28.0 us: 1.01x faster                                           |
| pickle_list          | 4.91 us                                                                | 4.88 us: 1.01x faster                                           |
| unpickle_pure_python | 217 us                                                                 | 218 us: 1.01x slower                                            |
| xml_etree_iterparse  | 105 ms                                                                 | 106 ms: 1.01x slower                                            |
| tomli_loads          | 2.19 sec                                                               | 2.23 sec: 1.02x slower                                          |
| pickle_dict          | 33.0 us                                                                | 33.7 us: 1.02x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.00x faster                                                    |

Benchmark hidden because not significant (6): unpickle, xml_etree_generate, json_dumps, xml_etree_process, pickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                           |
| python_startup_no_site | 8.95 ms                                                                | 8.99 ms: 1.00x slower                                           |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                    |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|-----------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| mako      | 11.1 ms                                                                | 11.3 ms: 1.02x slower                                           |

All benchmarks:
===============

| Benchmark               | bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a | bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2+-e25f138 |
|-------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------:|
| unpack_sequence         | 51.6 ns                                                                | 45.8 ns: 1.13x faster                                           |
| unpickle_list           | 5.23 us                                                                | 4.98 us: 1.05x faster                                           |
| gc_traversal            | 4.29 ms                                                                | 4.17 ms: 1.03x faster                                           |
| nbody                   | 92.3 ms                                                                | 90.1 ms: 1.02x faster                                           |
| pprint_safe_repr        | 748 ms                                                                 | 732 ms: 1.02x faster                                            |
| dulwich_log             | 65.9 ms                                                                | 64.9 ms: 1.02x faster                                           |
| sqlglot_parse           | 1.28 ms                                                                | 1.26 ms: 1.01x faster                                           |
| tornado_http            | 96.0 ms                                                                | 94.6 ms: 1.01x faster                                           |
| nqueens                 | 80.7 ms                                                                | 79.6 ms: 1.01x faster                                           |
| pathlib                 | 18.2 ms                                                                | 17.9 ms: 1.01x faster                                           |
| pprint_pformat          | 1.52 sec                                                               | 1.50 sec: 1.01x faster                                          |
| crypto_pyaes            | 71.8 ms                                                                | 71.0 ms: 1.01x faster                                           |
| sympy_sum               | 148 ms                                                                 | 147 ms: 1.01x faster                                            |
| sqlglot_transpile       | 1.60 ms                                                                | 1.58 ms: 1.01x faster                                           |
| pickle_pure_python      | 305 us                                                                 | 302 us: 1.01x faster                                            |
| scimark_lu              | 116 ms                                                                 | 115 ms: 1.01x faster                                            |
| json_loads              | 28.3 us                                                                | 28.0 us: 1.01x faster                                           |
| sympy_integrate         | 19.6 ms                                                                | 19.4 ms: 1.01x faster                                           |
| chaos                   | 61.9 ms                                                                | 61.4 ms: 1.01x faster                                           |
| asyncio_tcp             | 488 ms                                                                 | 484 ms: 1.01x faster                                            |
| sqlite_synth            | 2.82 us                                                                | 2.80 us: 1.01x faster                                           |
| sqlglot_normalize       | 106 ms                                                                 | 105 ms: 1.01x faster                                            |
| spectral_norm           | 114 ms                                                                 | 113 ms: 1.01x faster                                            |
| fannkuch                | 398 ms                                                                 | 395 ms: 1.01x faster                                            |
| pickle_list             | 4.91 us                                                                | 4.88 us: 1.01x faster                                           |
| meteor_contest          | 108 ms                                                                 | 107 ms: 1.01x faster                                            |
| deepcopy                | 349 us                                                                 | 347 us: 1.01x faster                                            |
| sympy_expand            | 453 ms                                                                 | 451 ms: 1.00x faster                                            |
| async_generators        | 445 ms                                                                 | 443 ms: 1.00x faster                                            |
| pyflate                 | 467 ms                                                                 | 465 ms: 1.00x faster                                            |
| asyncio_tcp_ssl         | 1.79 sec                                                               | 1.78 sec: 1.00x faster                                          |
| logging_silent          | 108 ns                                                                 | 107 ns: 1.00x faster                                            |
| hexiom                  | 6.19 ms                                                                | 6.18 ms: 1.00x faster                                           |
| pidigits                | 187 ms                                                                 | 187 ms: 1.00x faster                                            |
| python_startup          | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                           |
| python_startup_no_site  | 8.95 ms                                                                | 8.99 ms: 1.00x slower                                           |
| scimark_monte_carlo     | 68.5 ms                                                                | 68.8 ms: 1.00x slower                                           |
| logging_simple          | 5.68 us                                                                | 5.71 us: 1.01x slower                                           |
| create_gc_cycles        | 1.46 ms                                                                | 1.47 ms: 1.01x slower                                           |
| unpickle_pure_python    | 217 us                                                                 | 218 us: 1.01x slower                                            |
| raytrace                | 275 ms                                                                 | 277 ms: 1.01x slower                                            |
| async_tree_io           | 1.18 sec                                                               | 1.19 sec: 1.01x slower                                          |
| go                      | 140 ms                                                                 | 142 ms: 1.01x slower                                            |
| xml_etree_iterparse     | 105 ms                                                                 | 106 ms: 1.01x slower                                            |
| regex_v8                | 26.1 ms                                                                | 26.4 ms: 1.01x slower                                           |
| deltablue               | 3.28 ms                                                                | 3.33 ms: 1.01x slower                                           |
| coroutines              | 21.7 ms                                                                | 22.0 ms: 1.02x slower                                           |
| tomli_loads             | 2.19 sec                                                               | 2.23 sec: 1.02x slower                                          |
| regex_compile           | 133 ms                                                                 | 135 ms: 1.02x slower                                            |
| chameleon               | 6.88 ms                                                                | 7.01 ms: 1.02x slower                                           |
| deepcopy_memo           | 38.2 us                                                                | 39.0 us: 1.02x slower                                           |
| pickle_dict             | 33.0 us                                                                | 33.7 us: 1.02x slower                                           |
| mako                    | 11.1 ms                                                                | 11.3 ms: 1.02x slower                                           |
| scimark_sparse_mat_mult | 4.81 ms                                                                | 4.92 ms: 1.02x slower                                           |
| comprehensions          | 16.0 us                                                                | 16.4 us: 1.03x slower                                           |
| regex_dna               | 214 ms                                                                 | 220 ms: 1.03x slower                                            |
| generators              | 28.3 ms                                                                | 29.2 ms: 1.03x slower                                           |
| regex_effbot            | 3.59 ms                                                                | 3.71 ms: 1.03x slower                                           |
| mdp                     | 2.56 sec                                                               | 2.81 sec: 1.10x slower                                          |
| Geometric mean          | (ref)                                                                  | 1.00x faster                                                    |

Benchmark hidden because not significant (33): unpickle, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, richards, float, docutils, bench_thread_pool, xml_etree_generate, json, asyncio_websockets, telco, sympy_str, mypy2, typing_runtime_protocols, json_dumps, bench_mp_pool, async_tree_memoization, 2to3, scimark_fft, async_tree_none_tg, xml_etree_process, sqlglot_optimize, async_tree_io_tg, deepcopy_reduce, scimark_sor, logging_format, richards_super, async_tree_none, pycparser, pickle, coverage, xml_etree_parse, async_tree_memoization_tg
Ignored benchmarks (1) of results/bm-20231201-3.13.0a2+-05a370a/bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2+-05a370a.json: dask


# HPT report

- Reliability score: 86.81% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
