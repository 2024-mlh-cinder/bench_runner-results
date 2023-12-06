
# Results vs. base

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: darwin-arm64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.00x faster
- HPT reliability: 99.77%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231031-darwin-arm64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| chameleon      | 4.66 ms                                                                | 4.63 ms: 1.01x faster                                                  |
| docutils       | 1.50 sec                                                               | 1.49 sec: 1.01x faster                                                 |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                           |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231031-darwin-arm64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|--------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none_tg | 263 ms                                                                 | 265 ms: 1.01x slower                                                   |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (7): async_tree_io_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231031-darwin-arm64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 54.7 ms                                                                | 54.4 ms: 1.01x faster                                                  |
| nbody          | 70.7 ms                                                                | 70.4 ms: 1.00x faster                                                  |
| pidigits       | 283 ms                                                                 | 283 ms: 1.00x faster                                                   |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231031-darwin-arm64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 75.6 ms                                                                | 75.3 ms: 1.00x faster                                                  |
| regex_effbot   | 2.58 ms                                                                | 2.60 ms: 1.01x slower                                                  |
| regex_dna      | 149 ms                                                                 | 151 ms: 1.01x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231031-darwin-arm64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| xml_etree_parse      | 113 ms                                                                 | 110 ms: 1.02x faster                                                   |
| unpickle_list        | 3.17 us                                                                | 3.13 us: 1.01x faster                                                  |
| unpickle_pure_python | 157 us                                                                 | 155 us: 1.01x faster                                                   |
| pickle               | 7.35 us                                                                | 7.31 us: 1.01x faster                                                  |
| xml_etree_process    | 39.0 ms                                                                | 38.9 ms: 1.00x faster                                                  |
| unpickle             | 9.14 us                                                                | 9.12 us: 1.00x faster                                                  |
| pickle_pure_python   | 193 us                                                                 | 193 us: 1.00x faster                                                   |
| json_dumps           | 6.46 ms                                                                | 6.44 ms: 1.00x faster                                                  |
| xml_etree_generate   | 57.3 ms                                                                | 57.1 ms: 1.00x faster                                                  |
| pickle_dict          | 17.9 us                                                                | 18.0 us: 1.00x slower                                                  |
| pickle_list          | 2.85 us                                                                | 2.90 us: 1.02x slower                                                  |
| Geometric mean       | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (3): xml_etree_iterparse, json_loads, tomli_loads

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231031-darwin-arm64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup | 12.8 ms                                                                | 12.8 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark               | bm-20231031-darwin-arm64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| xml_etree_parse         | 113 ms                                                                 | 110 ms: 1.02x faster                                                   |
| deepcopy_reduce         | 2.01 us                                                                | 1.98 us: 1.02x faster                                                  |
| sqlite_synth            | 1.63 us                                                                | 1.61 us: 1.01x faster                                                  |
| logging_format          | 3.85 us                                                                | 3.80 us: 1.01x faster                                                  |
| docutils                | 1.50 sec                                                               | 1.49 sec: 1.01x faster                                                 |
| unpickle_list           | 3.17 us                                                                | 3.13 us: 1.01x faster                                                  |
| logging_simple          | 3.57 us                                                                | 3.54 us: 1.01x faster                                                  |
| unpickle_pure_python    | 157 us                                                                 | 155 us: 1.01x faster                                                   |
| sqlglot_optimize        | 34.1 ms                                                                | 33.8 ms: 1.01x faster                                                  |
| pprint_safe_repr        | 497 ms                                                                 | 493 ms: 1.01x faster                                                   |
| richards_super          | 36.2 ms                                                                | 35.9 ms: 1.01x faster                                                  |
| richards                | 32.6 ms                                                                | 32.4 ms: 1.01x faster                                                  |
| pprint_pformat          | 1.01 sec                                                               | 1.00 sec: 1.01x faster                                                 |
| sqlglot_transpile       | 969 us                                                                 | 962 us: 1.01x faster                                                   |
| coverage                | 46.4 ms                                                                | 46.1 ms: 1.01x faster                                                  |
| deepcopy_memo           | 24.0 us                                                                | 23.8 us: 1.01x faster                                                  |
| crypto_pyaes            | 47.1 ms                                                                | 46.7 ms: 1.01x faster                                                  |
| scimark_fft             | 199 ms                                                                 | 197 ms: 1.01x faster                                                   |
| chameleon               | 4.66 ms                                                                | 4.63 ms: 1.01x faster                                                  |
| sqlglot_normalize       | 183 ms                                                                 | 182 ms: 1.01x faster                                                   |
| sqlglot_parse           | 794 us                                                                 | 790 us: 1.01x faster                                                   |
| pickle                  | 7.35 us                                                                | 7.31 us: 1.01x faster                                                  |
| float                   | 54.7 ms                                                                | 54.4 ms: 1.01x faster                                                  |
| sympy_sum               | 73.8 ms                                                                | 73.4 ms: 1.00x faster                                                  |
| deepcopy                | 222 us                                                                 | 221 us: 1.00x faster                                                   |
| spectral_norm           | 70.6 ms                                                                | 70.3 ms: 1.00x faster                                                  |
| regex_compile           | 75.6 ms                                                                | 75.3 ms: 1.00x faster                                                  |
| go                      | 103 ms                                                                 | 102 ms: 1.00x faster                                                   |
| nbody                   | 70.7 ms                                                                | 70.4 ms: 1.00x faster                                                  |
| fannkuch                | 280 ms                                                                 | 279 ms: 1.00x faster                                                   |
| hexiom                  | 4.59 ms                                                                | 4.58 ms: 1.00x faster                                                  |
| comprehensions          | 11.5 us                                                                | 11.5 us: 1.00x faster                                                  |
| xml_etree_process       | 39.0 ms                                                                | 38.9 ms: 1.00x faster                                                  |
| scimark_lu              | 70.2 ms                                                                | 69.9 ms: 1.00x faster                                                  |
| unpickle                | 9.14 us                                                                | 9.12 us: 1.00x faster                                                  |
| scimark_sparse_mat_mult | 3.06 ms                                                                | 3.06 ms: 1.00x faster                                                  |
| pickle_pure_python      | 193 us                                                                 | 193 us: 1.00x faster                                                   |
| pyflate                 | 334 ms                                                                 | 333 ms: 1.00x faster                                                   |
| sympy_str               | 141 ms                                                                 | 141 ms: 1.00x faster                                                   |
| json_dumps              | 6.46 ms                                                                | 6.44 ms: 1.00x faster                                                  |
| deltablue               | 2.32 ms                                                                | 2.32 ms: 1.00x faster                                                  |
| xml_etree_generate      | 57.3 ms                                                                | 57.1 ms: 1.00x faster                                                  |
| raytrace                | 172 ms                                                                 | 172 ms: 1.00x faster                                                   |
| meteor_contest          | 73.9 ms                                                                | 73.8 ms: 1.00x faster                                                  |
| pidigits                | 283 ms                                                                 | 283 ms: 1.00x faster                                                   |
| scimark_sor             | 103 ms                                                                 | 103 ms: 1.00x slower                                                   |
| python_startup          | 12.8 ms                                                                | 12.8 ms: 1.00x slower                                                  |
| scimark_monte_carlo     | 44.8 ms                                                                | 44.9 ms: 1.00x slower                                                  |
| pickle_dict             | 17.9 us                                                                | 18.0 us: 1.00x slower                                                  |
| bench_thread_pool       | 476 us                                                                 | 478 us: 1.00x slower                                                   |
| async_tree_none_tg      | 263 ms                                                                 | 265 ms: 1.01x slower                                                   |
| json                    | 2.99 ms                                                                | 3.00 ms: 1.01x slower                                                  |
| regex_effbot            | 2.58 ms                                                                | 2.60 ms: 1.01x slower                                                  |
| mdp                     | 1.60 sec                                                               | 1.61 sec: 1.01x slower                                                 |
| regex_dna               | 149 ms                                                                 | 151 ms: 1.01x slower                                                   |
| pickle_list             | 2.85 us                                                                | 2.90 us: 1.02x slower                                                  |
| telco                   | 4.62 ms                                                                | 4.74 ms: 1.03x slower                                                  |
| Geometric mean          | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (35): tornado_http, unpack_sequence, pycparser, xml_etree_iterparse, asyncio_tcp, bench_mp_pool, pathlib, json_loads, sympy_integrate, create_gc_cycles, gc_traversal, mypy2, sympy_expand, async_tree_io_tg, generators, mako, logging_silent, asyncio_websockets, python_startup_no_site, chaos, 2to3, asyncio_tcp_ssl, dulwich_log, async_generators, coroutines, async_tree_cpu_io_mixed_tg, tomli_loads, nqueens, async_tree_memoization_tg, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, regex_v8, typing_runtime_protocols, async_tree_none


# HPT report

- Reliability score: 99.77% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
