
# Results vs. base

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: darwin-arm64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.00x slower
- HPT reliability: 99.69%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 170 ms                                                                 | 170 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (3): chameleon, docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (8): async_tree_memoization_tg, async_tree_none_tg, async_tree_io, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization, async_tree_io_tg, async_tree_cpu_io_mixed_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 70.4 ms                                                                | 70.9 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (2): pidigits, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 151 ms                                                                 | 149 ms: 1.01x faster                                                   |
| regex_effbot   | 2.60 ms                                                                | 2.58 ms: 1.01x faster                                                  |
| regex_v8       | 16.9 ms                                                                | 16.8 ms: 1.01x faster                                                  |
| regex_compile  | 75.3 ms                                                                | 75.4 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.01x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| unpickle_pure_python | 155 us                                                                 | 155 us: 1.00x slower                                                   |
| xml_etree_generate   | 57.1 ms                                                                | 57.3 ms: 1.00x slower                                                  |
| xml_etree_process    | 38.9 ms                                                                | 39.0 ms: 1.00x slower                                                  |
| json_dumps           | 6.44 ms                                                                | 6.48 ms: 1.01x slower                                                  |
| unpickle_list        | 3.13 us                                                                | 3.19 us: 1.02x slower                                                  |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (9): pickle_dict, json_loads, tomli_loads, pickle_pure_python, pickle, pickle_list, xml_etree_iterparse, unpickle, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 12.8 ms                                                                | 12.7 ms: 1.01x faster                                                  |
| python_startup_no_site | 11.5 ms                                                                | 11.3 ms: 1.01x faster                                                  |
| Geometric mean         | (ref)                                                                  | 1.01x faster                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.34 ms                                                                | 7.30 ms: 1.01x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna                | 151 ms                                                                 | 149 ms: 1.01x faster                                                   |
| python_startup           | 12.8 ms                                                                | 12.7 ms: 1.01x faster                                                  |
| python_startup_no_site   | 11.5 ms                                                                | 11.3 ms: 1.01x faster                                                  |
| typing_runtime_protocols | 92.7 us                                                                | 92.0 us: 1.01x faster                                                  |
| regex_effbot             | 2.60 ms                                                                | 2.58 ms: 1.01x faster                                                  |
| regex_v8                 | 16.9 ms                                                                | 16.8 ms: 1.01x faster                                                  |
| mako                     | 7.34 ms                                                                | 7.30 ms: 1.01x faster                                                  |
| scimark_sor              | 103 ms                                                                 | 103 ms: 1.00x faster                                                   |
| telco                    | 4.74 ms                                                                | 4.73 ms: 1.00x faster                                                  |
| dulwich_log              | 30.5 ms                                                                | 30.4 ms: 1.00x faster                                                  |
| hexiom                   | 4.58 ms                                                                | 4.58 ms: 1.00x slower                                                  |
| unpickle_pure_python     | 155 us                                                                 | 155 us: 1.00x slower                                                   |
| raytrace                 | 172 ms                                                                 | 172 ms: 1.00x slower                                                   |
| scimark_sparse_mat_mult  | 3.06 ms                                                                | 3.06 ms: 1.00x slower                                                  |
| xml_etree_generate       | 57.1 ms                                                                | 57.3 ms: 1.00x slower                                                  |
| regex_compile            | 75.3 ms                                                                | 75.4 ms: 1.00x slower                                                  |
| deepcopy_memo            | 23.8 us                                                                | 23.9 us: 1.00x slower                                                  |
| chaos                    | 40.0 ms                                                                | 40.1 ms: 1.00x slower                                                  |
| 2to3                     | 170 ms                                                                 | 170 ms: 1.00x slower                                                   |
| pyflate                  | 333 ms                                                                 | 334 ms: 1.00x slower                                                   |
| comprehensions           | 11.5 us                                                                | 11.5 us: 1.00x slower                                                  |
| richards_super           | 35.9 ms                                                                | 36.0 ms: 1.00x slower                                                  |
| sympy_str                | 141 ms                                                                 | 141 ms: 1.00x slower                                                   |
| logging_silent           | 66.6 ns                                                                | 66.8 ns: 1.00x slower                                                  |
| sympy_integrate          | 10.8 ms                                                                | 10.8 ms: 1.00x slower                                                  |
| xml_etree_process        | 38.9 ms                                                                | 39.0 ms: 1.00x slower                                                  |
| deltablue                | 2.32 ms                                                                | 2.33 ms: 1.00x slower                                                  |
| scimark_fft              | 197 ms                                                                 | 198 ms: 1.00x slower                                                   |
| generators               | 24.6 ms                                                                | 24.7 ms: 1.00x slower                                                  |
| sqlglot_optimize         | 33.8 ms                                                                | 33.9 ms: 1.00x slower                                                  |
| crypto_pyaes             | 46.7 ms                                                                | 47.0 ms: 1.01x slower                                                  |
| sqlite_synth             | 1.61 us                                                                | 1.62 us: 1.01x slower                                                  |
| json_dumps               | 6.44 ms                                                                | 6.48 ms: 1.01x slower                                                  |
| nbody                    | 70.4 ms                                                                | 70.9 ms: 1.01x slower                                                  |
| meteor_contest           | 73.8 ms                                                                | 74.4 ms: 1.01x slower                                                  |
| coverage                 | 46.1 ms                                                                | 46.5 ms: 1.01x slower                                                  |
| richards                 | 32.4 ms                                                                | 32.7 ms: 1.01x slower                                                  |
| deepcopy_reduce          | 1.98 us                                                                | 2.00 us: 1.01x slower                                                  |
| pprint_safe_repr         | 493 ms                                                                 | 498 ms: 1.01x slower                                                   |
| pprint_pformat           | 1.00 sec                                                               | 1.01 sec: 1.01x slower                                                 |
| unpickle_list            | 3.13 us                                                                | 3.19 us: 1.02x slower                                                  |
| unpack_sequence          | 26.1 ns                                                                | 26.7 ns: 1.02x slower                                                  |
| Geometric mean           | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (50): asyncio_tcp, tornado_http, json, async_tree_memoization_tg, async_tree_none_tg, async_tree_io, bench_thread_pool, sqlglot_parse, pickle_dict, async_tree_cpu_io_mixed, fannkuch, go, async_tree_none, scimark_monte_carlo, async_tree_memoization, sympy_sum, pidigits, nqueens, gc_traversal, create_gc_cycles, async_tree_io_tg, json_loads, async_tree_cpu_io_mixed_tg, asyncio_websockets, logging_format, coroutines, float, sqlglot_normalize, sqlglot_transpile, mdp, async_generators, mypy2, scimark_lu, deepcopy, docutils, sympy_expand, spectral_norm, chameleon, tomli_loads, pickle_pure_python, pickle, logging_simple, pickle_list, xml_etree_iterparse, unpickle, bench_mp_pool, asyncio_tcp_ssl, pycparser, xml_etree_parse, pathlib


# HPT report

- Reliability score: 99.69% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
