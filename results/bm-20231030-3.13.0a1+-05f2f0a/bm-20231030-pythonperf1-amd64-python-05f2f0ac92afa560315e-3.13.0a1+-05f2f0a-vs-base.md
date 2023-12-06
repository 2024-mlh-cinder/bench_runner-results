
# Results vs. base

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: windows-amd64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.00x slower
- HPT reliability: 99.09%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (4): 2to3, chameleon, docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io_tg | 781 ms                                                                      | 791 ms: 1.01x slower                                                        |
| async_tree_io    | 755 ms                                                                      | 767 ms: 1.02x slower                                                        |
| Geometric mean   | (ref)                                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (6): async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_none_tg, async_tree_none, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 147 ms                                                                      | 148 ms: 1.00x slower                                                        |
| Geometric mean | (ref)                                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (2): nbody, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_v8       | 15.5 ms                                                                     | 15.2 ms: 1.02x faster                                                       |
| regex_effbot   | 1.61 ms                                                                     | 1.60 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (2): regex_dna, regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|---------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps          | 5.84 ms                                                                     | 5.73 ms: 1.02x faster                                                       |
| unpickle_list       | 2.68 us                                                                     | 2.64 us: 1.01x faster                                                       |
| json_loads          | 13.8 us                                                                     | 13.6 us: 1.01x faster                                                       |
| tomli_loads         | 1.55 sec                                                                    | 1.56 sec: 1.01x slower                                                      |
| pickle              | 6.91 us                                                                     | 6.98 us: 1.01x slower                                                       |
| xml_etree_process   | 39.4 ms                                                                     | 39.9 ms: 1.01x slower                                                       |
| pickle_list         | 2.80 us                                                                     | 2.84 us: 1.01x slower                                                       |
| xml_etree_iterparse | 64.3 ms                                                                     | 65.4 ms: 1.02x slower                                                       |
| unpickle            | 8.17 us                                                                     | 8.31 us: 1.02x slower                                                       |
| pickle_dict         | 18.1 us                                                                     | 18.8 us: 1.03x slower                                                       |
| Geometric mean      | (ref)                                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (4): pickle_pure_python, unpickle_pure_python, xml_etree_generate, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup | 20.0 ms                                                                     | 20.6 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                                |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|--------------------------|:---------------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence          | 39.9 ns                                                                     | 37.8 ns: 1.05x faster                                                       |
| json                     | 3.01 ms                                                                     | 2.89 ms: 1.04x faster                                                       |
| scimark_lu               | 60.3 ms                                                                     | 58.0 ms: 1.04x faster                                                       |
| chaos                    | 45.0 ms                                                                     | 43.3 ms: 1.04x faster                                                       |
| crypto_pyaes             | 45.3 ms                                                                     | 44.2 ms: 1.03x faster                                                       |
| go                       | 98.2 ms                                                                     | 95.9 ms: 1.02x faster                                                       |
| logging_simple           | 6.89 us                                                                     | 6.75 us: 1.02x faster                                                       |
| regex_v8                 | 15.5 ms                                                                     | 15.2 ms: 1.02x faster                                                       |
| json_dumps               | 5.84 ms                                                                     | 5.73 ms: 1.02x faster                                                       |
| deepcopy                 | 255 us                                                                      | 250 us: 1.02x faster                                                        |
| scimark_sor              | 81.9 ms                                                                     | 80.6 ms: 1.02x faster                                                       |
| unpickle_list            | 2.68 us                                                                     | 2.64 us: 1.01x faster                                                       |
| pprint_pformat           | 1.12 sec                                                                    | 1.10 sec: 1.01x faster                                                      |
| telco                    | 4.85 ms                                                                     | 4.79 ms: 1.01x faster                                                       |
| scimark_monte_carlo      | 42.8 ms                                                                     | 42.3 ms: 1.01x faster                                                       |
| pprint_safe_repr         | 546 ms                                                                      | 540 ms: 1.01x faster                                                        |
| scimark_fft              | 188 ms                                                                      | 186 ms: 1.01x faster                                                        |
| raytrace                 | 182 ms                                                                      | 180 ms: 1.01x faster                                                        |
| logging_format           | 7.38 us                                                                     | 7.31 us: 1.01x faster                                                       |
| json_loads               | 13.8 us                                                                     | 13.6 us: 1.01x faster                                                       |
| regex_effbot             | 1.61 ms                                                                     | 1.60 ms: 1.01x faster                                                       |
| meteor_contest           | 75.9 ms                                                                     | 75.6 ms: 1.00x faster                                                       |
| pidigits                 | 147 ms                                                                      | 148 ms: 1.00x slower                                                        |
| spectral_norm            | 63.7 ms                                                                     | 63.9 ms: 1.00x slower                                                       |
| tomli_loads              | 1.55 sec                                                                    | 1.56 sec: 1.01x slower                                                      |
| deepcopy_reduce          | 2.24 us                                                                     | 2.25 us: 1.01x slower                                                       |
| async_generators         | 237 ms                                                                      | 238 ms: 1.01x slower                                                        |
| deltablue                | 2.23 ms                                                                     | 2.25 ms: 1.01x slower                                                       |
| nqueens                  | 62.5 ms                                                                     | 63.0 ms: 1.01x slower                                                       |
| dulwich_log              | 45.2 ms                                                                     | 45.6 ms: 1.01x slower                                                       |
| pickle                   | 6.91 us                                                                     | 6.98 us: 1.01x slower                                                       |
| comprehensions           | 11.2 us                                                                     | 11.3 us: 1.01x slower                                                       |
| sqlglot_optimize         | 36.3 ms                                                                     | 36.7 ms: 1.01x slower                                                       |
| richards_super           | 33.4 ms                                                                     | 33.8 ms: 1.01x slower                                                       |
| coroutines               | 14.6 ms                                                                     | 14.7 ms: 1.01x slower                                                       |
| gc_traversal             | 1.48 ms                                                                     | 1.50 ms: 1.01x slower                                                       |
| async_tree_io_tg         | 781 ms                                                                      | 791 ms: 1.01x slower                                                        |
| sympy_str                | 173 ms                                                                      | 175 ms: 1.01x slower                                                        |
| xml_etree_process        | 39.4 ms                                                                     | 39.9 ms: 1.01x slower                                                       |
| pickle_list              | 2.80 us                                                                     | 2.84 us: 1.01x slower                                                       |
| coverage                 | 45.5 ms                                                                     | 46.1 ms: 1.01x slower                                                       |
| async_tree_io            | 755 ms                                                                      | 767 ms: 1.02x slower                                                        |
| richards                 | 29.8 ms                                                                     | 30.3 ms: 1.02x slower                                                       |
| sqlglot_normalize        | 194 ms                                                                      | 197 ms: 1.02x slower                                                        |
| xml_etree_iterparse      | 64.3 ms                                                                     | 65.4 ms: 1.02x slower                                                       |
| unpickle                 | 8.17 us                                                                     | 8.31 us: 1.02x slower                                                       |
| sympy_expand             | 296 ms                                                                      | 305 ms: 1.03x slower                                                        |
| python_startup           | 20.0 ms                                                                     | 20.6 ms: 1.03x slower                                                       |
| typing_runtime_protocols | 97.6 us                                                                     | 101 us: 1.03x slower                                                        |
| pickle_dict              | 18.1 us                                                                     | 18.8 us: 1.03x slower                                                       |
| generators               | 22.7 ms                                                                     | 23.5 ms: 1.03x slower                                                       |
| scimark_sparse_mat_mult  | 2.50 ms                                                                     | 2.60 ms: 1.04x slower                                                       |
| fannkuch                 | 249 ms                                                                      | 261 ms: 1.05x slower                                                        |
| mdp                      | 1.42 sec                                                                    | 1.49 sec: 1.05x slower                                                      |
| Geometric mean           | (ref)                                                                       | 1.00x slower                                                                |

Benchmark hidden because not significant (37): pycparser, asyncio_tcp, chameleon, deepcopy_memo, mako, nbody, sqlglot_transpile, async_tree_cpu_io_mixed, pathlib, sympy_sum, sympy_integrate, mypy2, float, regex_dna, bench_thread_pool, pickle_pure_python, sqlglot_parse, unpickle_pure_python, create_gc_cycles, async_tree_cpu_io_mixed_tg, docutils, logging_silent, sqlite_synth, regex_compile, hexiom, pyflate, python_startup_no_site, 2to3, bench_mp_pool, xml_etree_generate, tornado_http, xml_etree_parse, async_tree_memoization, async_tree_none_tg, async_tree_none, asyncio_tcp_ssl, async_tree_memoization_tg


# HPT report

- Reliability score: 99.09% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
