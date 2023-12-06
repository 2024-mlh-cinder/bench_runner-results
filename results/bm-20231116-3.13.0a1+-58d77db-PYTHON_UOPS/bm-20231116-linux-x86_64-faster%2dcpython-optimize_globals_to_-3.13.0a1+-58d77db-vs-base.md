
# Results vs. base

- fork: faster-cpython
- ref: optimize_globals_to_
- machine: linux-x86_64
- commit hash: 58d77db
- commit date: 2023-11-16
- overall geometric mean: 1.01x slower
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| chameleon      | 7.48 ms                                                                | 7.40 ms: 1.01x faster                                                            |
| docutils       | 2.69 sec                                                               | 2.70 sec: 1.01x slower                                                           |
| tornado_http   | 99.2 ms                                                                | 99.9 ms: 1.01x slower                                                            |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                                     |

Benchmark hidden because not significant (1): 2to3

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|--------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none_tg | 473 ms                                                                 | 470 ms: 1.01x faster                                                             |
| async_tree_io_tg   | 1.25 sec                                                               | 1.26 sec: 1.00x slower                                                           |
| async_tree_io      | 1.22 sec                                                               | 1.23 sec: 1.01x slower                                                           |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                                     |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_memoization, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| pidigits       | 188 ms                                                                 | 188 ms: 1.00x slower                                                             |
| nbody          | 113 ms                                                                 | 114 ms: 1.01x slower                                                             |
| float          | 98.3 ms                                                                | 101 ms: 1.03x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_v8       | 26.0 ms                                                                | 24.8 ms: 1.05x faster                                                            |
| regex_effbot   | 3.67 ms                                                                | 3.62 ms: 1.01x faster                                                            |
| regex_dna      | 216 ms                                                                 | 217 ms: 1.00x slower                                                             |
| regex_compile  | 159 ms                                                                 | 162 ms: 1.02x slower                                                             |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| xml_etree_process    | 60.2 ms                                                                | 59.4 ms: 1.01x faster                                                            |
| xml_etree_parse      | 160 ms                                                                 | 159 ms: 1.01x faster                                                             |
| unpickle_list        | 5.10 us                                                                | 5.06 us: 1.01x faster                                                            |
| xml_etree_generate   | 88.1 ms                                                                | 87.7 ms: 1.00x faster                                                            |
| unpickle             | 14.8 us                                                                | 14.8 us: 1.00x slower                                                            |
| pickle_pure_python   | 305 us                                                                 | 308 us: 1.01x slower                                                             |
| pickle_list          | 5.03 us                                                                | 5.08 us: 1.01x slower                                                            |
| unpickle_pure_python | 244 us                                                                 | 248 us: 1.01x slower                                                             |
| tomli_loads          | 2.77 sec                                                               | 2.86 sec: 1.03x slower                                                           |
| pickle_dict          | 34.4 us                                                                | 36.3 us: 1.06x slower                                                            |
| Geometric mean       | (ref)                                                                  | 1.01x slower                                                                     |

Benchmark hidden because not significant (4): json_dumps, json_loads, pickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup_no_site | 9.09 ms                                                                | 9.08 ms: 1.00x faster                                                            |
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.00x faster                                                            |
| Geometric mean         | (ref)                                                                  | 1.00x faster                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                                | 14.7 ms: 1.00x slower                                                            |

All benchmarks:
===============

| Benchmark               | bm-20231117-linux-x86_64-python-0ee2d77331f2362fcaab-3.13.0a1+-0ee2d77 | bm-20231116-linux-x86_64-faster%2dcpython-optimize_globals_to_-3.13.0a1+-58d77db |
|-------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| gc_traversal            | 4.32 ms                                                                | 3.82 ms: 1.13x faster                                                            |
| regex_v8                | 26.0 ms                                                                | 24.8 ms: 1.05x faster                                                            |
| unpack_sequence         | 48.9 ns                                                                | 47.3 ns: 1.03x faster                                                            |
| pycparser               | 1.25 sec                                                               | 1.21 sec: 1.03x faster                                                           |
| pathlib                 | 18.9 ms                                                                | 18.5 ms: 1.02x faster                                                            |
| pyflate                 | 543 ms                                                                 | 535 ms: 1.02x faster                                                             |
| regex_effbot            | 3.67 ms                                                                | 3.62 ms: 1.01x faster                                                            |
| xml_etree_process       | 60.2 ms                                                                | 59.4 ms: 1.01x faster                                                            |
| xml_etree_parse         | 160 ms                                                                 | 159 ms: 1.01x faster                                                             |
| chameleon               | 7.48 ms                                                                | 7.40 ms: 1.01x faster                                                            |
| create_gc_cycles        | 1.49 ms                                                                | 1.48 ms: 1.01x faster                                                            |
| unpickle_list           | 5.10 us                                                                | 5.06 us: 1.01x faster                                                            |
| async_tree_none_tg      | 473 ms                                                                 | 470 ms: 1.01x faster                                                             |
| scimark_fft             | 430 ms                                                                 | 427 ms: 1.01x faster                                                             |
| asyncio_tcp_ssl         | 1.81 sec                                                               | 1.80 sec: 1.01x faster                                                           |
| xml_etree_generate      | 88.1 ms                                                                | 87.7 ms: 1.00x faster                                                            |
| python_startup_no_site  | 9.09 ms                                                                | 9.08 ms: 1.00x faster                                                            |
| python_startup          | 10.4 ms                                                                | 10.4 ms: 1.00x faster                                                            |
| pidigits                | 188 ms                                                                 | 188 ms: 1.00x slower                                                             |
| mako                    | 14.7 ms                                                                | 14.7 ms: 1.00x slower                                                            |
| asyncio_tcp             | 494 ms                                                                 | 496 ms: 1.00x slower                                                             |
| async_tree_io_tg        | 1.25 sec                                                               | 1.26 sec: 1.00x slower                                                           |
| sqlglot_optimize        | 54.5 ms                                                                | 54.7 ms: 1.00x slower                                                            |
| regex_dna               | 216 ms                                                                 | 217 ms: 1.00x slower                                                             |
| unpickle                | 14.8 us                                                                | 14.8 us: 1.00x slower                                                            |
| docutils                | 2.69 sec                                                               | 2.70 sec: 1.01x slower                                                           |
| deltablue               | 4.95 ms                                                                | 4.98 ms: 1.01x slower                                                            |
| async_tree_io           | 1.22 sec                                                               | 1.23 sec: 1.01x slower                                                           |
| tornado_http            | 99.2 ms                                                                | 99.9 ms: 1.01x slower                                                            |
| nbody                   | 113 ms                                                                 | 114 ms: 1.01x slower                                                             |
| richards_super          | 56.9 ms                                                                | 57.4 ms: 1.01x slower                                                            |
| pickle_pure_python      | 305 us                                                                 | 308 us: 1.01x slower                                                             |
| scimark_monte_carlo     | 81.5 ms                                                                | 82.2 ms: 1.01x slower                                                            |
| pickle_list             | 5.03 us                                                                | 5.08 us: 1.01x slower                                                            |
| sqlite_synth            | 2.88 us                                                                | 2.91 us: 1.01x slower                                                            |
| sympy_sum               | 153 ms                                                                 | 154 ms: 1.01x slower                                                             |
| deepcopy                | 351 us                                                                 | 355 us: 1.01x slower                                                             |
| sympy_integrate         | 21.2 ms                                                                | 21.5 ms: 1.01x slower                                                            |
| spectral_norm           | 112 ms                                                                 | 113 ms: 1.01x slower                                                             |
| sqlglot_parse           | 1.33 ms                                                                | 1.34 ms: 1.01x slower                                                            |
| dulwich_log             | 68.4 ms                                                                | 69.2 ms: 1.01x slower                                                            |
| deepcopy_reduce         | 3.12 us                                                                | 3.16 us: 1.01x slower                                                            |
| sqlglot_transpile       | 1.65 ms                                                                | 1.67 ms: 1.01x slower                                                            |
| sympy_expand            | 474 ms                                                                 | 480 ms: 1.01x slower                                                             |
| pprint_pformat          | 1.66 sec                                                               | 1.68 sec: 1.01x slower                                                           |
| generators              | 29.8 ms                                                                | 30.2 ms: 1.01x slower                                                            |
| unpickle_pure_python    | 244 us                                                                 | 248 us: 1.01x slower                                                             |
| coroutines              | 22.0 ms                                                                | 22.3 ms: 1.01x slower                                                            |
| sqlglot_normalize       | 107 ms                                                                 | 109 ms: 1.02x slower                                                             |
| crypto_pyaes            | 83.6 ms                                                                | 84.9 ms: 1.02x slower                                                            |
| coverage                | 95.2 ms                                                                | 96.8 ms: 1.02x slower                                                            |
| logging_format          | 6.84 us                                                                | 6.96 us: 1.02x slower                                                            |
| logging_simple          | 6.10 us                                                                | 6.22 us: 1.02x slower                                                            |
| pprint_safe_repr        | 807 ms                                                                 | 822 ms: 1.02x slower                                                             |
| async_generators        | 456 ms                                                                 | 464 ms: 1.02x slower                                                             |
| regex_compile           | 159 ms                                                                 | 162 ms: 1.02x slower                                                             |
| scimark_sor             | 126 ms                                                                 | 129 ms: 1.03x slower                                                             |
| fannkuch                | 480 ms                                                                 | 492 ms: 1.03x slower                                                             |
| float                   | 98.3 ms                                                                | 101 ms: 1.03x slower                                                             |
| meteor_contest          | 115 ms                                                                 | 118 ms: 1.03x slower                                                             |
| tomli_loads             | 2.77 sec                                                               | 2.86 sec: 1.03x slower                                                           |
| deepcopy_memo           | 41.5 us                                                                | 43.1 us: 1.04x slower                                                            |
| comprehensions          | 23.3 us                                                                | 24.3 us: 1.04x slower                                                            |
| pickle_dict             | 34.4 us                                                                | 36.3 us: 1.06x slower                                                            |
| hexiom                  | 9.27 ms                                                                | 9.84 ms: 1.06x slower                                                            |
| scimark_sparse_mat_mult | 6.33 ms                                                                | 6.94 ms: 1.10x slower                                                            |
| go                      | 163 ms                                                                 | 186 ms: 1.14x slower                                                             |
| Geometric mean          | (ref)                                                                  | 1.01x slower                                                                     |

Benchmark hidden because not significant (26): raytrace, typing_runtime_protocols, telco, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, json_dumps, bench_thread_pool, asyncio_websockets, dask, scimark_lu, 2to3, bench_mp_pool, json_loads, chaos, mdp, json, logging_silent, richards, pickle, xml_etree_iterparse, async_tree_memoization, mypy2, async_tree_none, sympy_str, nqueens


# HPT report

- Reliability score: 99.98% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
