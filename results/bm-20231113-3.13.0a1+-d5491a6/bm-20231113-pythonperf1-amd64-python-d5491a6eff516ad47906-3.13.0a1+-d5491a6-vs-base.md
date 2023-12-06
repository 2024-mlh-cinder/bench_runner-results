
# Results vs. base

- fork: python
- ref: d5491a6eff516ad47906
- machine: windows-amd64
- commit hash: d5491a6
- commit date: 2023-11-13
- overall geometric mean: 1.01x slower
- HPT reliability: 99.99%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

Benchmark hidden because not significant (4): 2to3, chameleon, docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

Benchmark hidden because not significant (8): async_tree_cpu_io_mixed_tg, async_tree_none, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_none_tg, async_tree_io_tg, async_tree_io, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | results/bm-20231113-3.13.0a1+-d5491a6-PYTHON_UOPS/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json | results/bm-20231113-3.13.0a1+-d5491a6/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| pidigits       | 147 ms                                                                                                                             | 146 ms: 1.01x faster                                                                                                   |
| float          | 52.2 ms                                                                                                                            | 53.0 ms: 1.02x slower                                                                                                  |
| nbody          | 72.6 ms                                                                                                                            | 73.8 ms: 1.02x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                                              | 1.01x slower                                                                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | results/bm-20231113-3.13.0a1+-d5491a6-PYTHON_UOPS/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json | results/bm-20231113-3.13.0a1+-d5491a6/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json |
|----------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| regex_compile  | 79.0 ms                                                                                                                            | 79.4 ms: 1.00x slower                                                                                                  |
| regex_effbot   | 1.56 ms                                                                                                                            | 1.58 ms: 1.01x slower                                                                                                  |
| regex_dna      | 118 ms                                                                                                                             | 121 ms: 1.02x slower                                                                                                   |
| regex_v8       | 14.6 ms                                                                                                                            | 15.1 ms: 1.03x slower                                                                                                  |
| Geometric mean | (ref)                                                                                                                              | 1.02x slower                                                                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | results/bm-20231113-3.13.0a1+-d5491a6-PYTHON_UOPS/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json | results/bm-20231113-3.13.0a1+-d5491a6/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json |
|----------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| unpickle_list        | 2.65 us                                                                                                                            | 2.61 us: 1.01x faster                                                                                                  |
| unpickle_pure_python | 128 us                                                                                                                             | 127 us: 1.01x faster                                                                                                   |
| pickle_list          | 2.87 us                                                                                                                            | 2.89 us: 1.01x slower                                                                                                  |
| json_dumps           | 5.62 ms                                                                                                                            | 5.66 ms: 1.01x slower                                                                                                  |
| xml_etree_generate   | 53.6 ms                                                                                                                            | 54.1 ms: 1.01x slower                                                                                                  |
| json_loads           | 13.5 us                                                                                                                            | 13.6 us: 1.01x slower                                                                                                  |
| tomli_loads          | 1.42 sec                                                                                                                           | 1.45 sec: 1.03x slower                                                                                                 |
| pickle               | 6.95 us                                                                                                                            | 7.21 us: 1.04x slower                                                                                                  |
| pickle_dict          | 18.5 us                                                                                                                            | 19.4 us: 1.05x slower                                                                                                  |
| Geometric mean       | (ref)                                                                                                                              | 1.01x slower                                                                                                           |

Benchmark hidden because not significant (5): xml_etree_parse, unpickle, xml_etree_iterparse, pickle_pure_python, xml_etree_process

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | results/bm-20231113-3.13.0a1+-d5491a6-PYTHON_UOPS/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json | results/bm-20231113-3.13.0a1+-d5491a6/bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1+-d5491a6.json |
|--------------------------|:----------------------------------------------------------------------------------------------------------------------------------:|:----------------------------------------------------------------------------------------------------------------------:|
| deepcopy_memo            | 24.4 us                                                                                                                            | 23.4 us: 1.04x faster                                                                                                  |
| deepcopy_reduce          | 1.99 us                                                                                                                            | 1.95 us: 1.02x faster                                                                                                  |
| deepcopy                 | 223 us                                                                                                                             | 219 us: 1.02x faster                                                                                                   |
| unpickle_list            | 2.65 us                                                                                                                            | 2.61 us: 1.01x faster                                                                                                  |
| unpickle_pure_python     | 128 us                                                                                                                             | 127 us: 1.01x faster                                                                                                   |
| go                       | 86.5 ms                                                                                                                            | 86.0 ms: 1.01x faster                                                                                                  |
| pidigits                 | 147 ms                                                                                                                             | 146 ms: 1.01x faster                                                                                                   |
| deltablue                | 2.06 ms                                                                                                                            | 2.04 ms: 1.01x faster                                                                                                  |
| pprint_pformat           | 1.02 sec                                                                                                                           | 1.01 sec: 1.00x faster                                                                                                 |
| meteor_contest           | 74.2 ms                                                                                                                            | 74.4 ms: 1.00x slower                                                                                                  |
| dulwich_log              | 40.5 ms                                                                                                                            | 40.6 ms: 1.00x slower                                                                                                  |
| coverage                 | 44.8 ms                                                                                                                            | 45.0 ms: 1.00x slower                                                                                                  |
| scimark_fft              | 181 ms                                                                                                                             | 181 ms: 1.00x slower                                                                                                   |
| pprint_safe_repr         | 493 ms                                                                                                                             | 496 ms: 1.00x slower                                                                                                   |
| regex_compile            | 79.0 ms                                                                                                                            | 79.4 ms: 1.00x slower                                                                                                  |
| crypto_pyaes             | 44.1 ms                                                                                                                            | 44.3 ms: 1.01x slower                                                                                                  |
| pickle_list              | 2.87 us                                                                                                                            | 2.89 us: 1.01x slower                                                                                                  |
| scimark_lu               | 56.8 ms                                                                                                                            | 57.1 ms: 1.01x slower                                                                                                  |
| sympy_integrate          | 12.3 ms                                                                                                                            | 12.4 ms: 1.01x slower                                                                                                  |
| json_dumps               | 5.62 ms                                                                                                                            | 5.66 ms: 1.01x slower                                                                                                  |
| scimark_sor              | 80.1 ms                                                                                                                            | 80.7 ms: 1.01x slower                                                                                                  |
| sqlglot_optimize         | 33.3 ms                                                                                                                            | 33.6 ms: 1.01x slower                                                                                                  |
| coroutines               | 13.5 ms                                                                                                                            | 13.6 ms: 1.01x slower                                                                                                  |
| pathlib                  | 78.0 ms                                                                                                                            | 78.6 ms: 1.01x slower                                                                                                  |
| xml_etree_generate       | 53.6 ms                                                                                                                            | 54.1 ms: 1.01x slower                                                                                                  |
| json_loads               | 13.5 us                                                                                                                            | 13.6 us: 1.01x slower                                                                                                  |
| regex_effbot             | 1.56 ms                                                                                                                            | 1.58 ms: 1.01x slower                                                                                                  |
| logging_format           | 6.53 us                                                                                                                            | 6.62 us: 1.01x slower                                                                                                  |
| sympy_expand             | 268 ms                                                                                                                             | 272 ms: 1.01x slower                                                                                                   |
| scimark_sparse_mat_mult  | 2.39 ms                                                                                                                            | 2.43 ms: 1.02x slower                                                                                                  |
| float                    | 52.2 ms                                                                                                                            | 53.0 ms: 1.02x slower                                                                                                  |
| typing_runtime_protocols | 73.4 us                                                                                                                            | 74.5 us: 1.02x slower                                                                                                  |
| hexiom                   | 3.79 ms                                                                                                                            | 3.85 ms: 1.02x slower                                                                                                  |
| spectral_norm            | 61.1 ms                                                                                                                            | 62.0 ms: 1.02x slower                                                                                                  |
| async_generators         | 224 ms                                                                                                                             | 228 ms: 1.02x slower                                                                                                   |
| nbody                    | 72.6 ms                                                                                                                            | 73.8 ms: 1.02x slower                                                                                                  |
| sympy_str                | 156 ms                                                                                                                             | 159 ms: 1.02x slower                                                                                                   |
| sqlite_synth             | 1.55 us                                                                                                                            | 1.58 us: 1.02x slower                                                                                                  |
| sympy_sum                | 82.0 ms                                                                                                                            | 83.5 ms: 1.02x slower                                                                                                  |
| chaos                    | 39.2 ms                                                                                                                            | 40.1 ms: 1.02x slower                                                                                                  |
| scimark_monte_carlo      | 41.8 ms                                                                                                                            | 42.8 ms: 1.02x slower                                                                                                  |
| regex_dna                | 118 ms                                                                                                                             | 121 ms: 1.02x slower                                                                                                   |
| raytrace                 | 162 ms                                                                                                                             | 166 ms: 1.02x slower                                                                                                   |
| unpack_sequence          | 42.9 ns                                                                                                                            | 44.0 ns: 1.03x slower                                                                                                  |
| logging_simple           | 6.06 us                                                                                                                            | 6.22 us: 1.03x slower                                                                                                  |
| tomli_loads              | 1.42 sec                                                                                                                           | 1.45 sec: 1.03x slower                                                                                                 |
| regex_v8                 | 14.6 ms                                                                                                                            | 15.1 ms: 1.03x slower                                                                                                  |
| nqueens                  | 56.8 ms                                                                                                                            | 58.6 ms: 1.03x slower                                                                                                  |
| pickle                   | 6.95 us                                                                                                                            | 7.21 us: 1.04x slower                                                                                                  |
| comprehensions           | 10.3 us                                                                                                                            | 10.8 us: 1.04x slower                                                                                                  |
| mdp                      | 1.38 sec                                                                                                                           | 1.44 sec: 1.04x slower                                                                                                 |
| pickle_dict              | 18.5 us                                                                                                                            | 19.4 us: 1.05x slower                                                                                                  |
| Geometric mean           | (ref)                                                                                                                              | 1.01x slower                                                                                                           |

Benchmark hidden because not significant (39): asyncio_tcp_ssl, async_tree_cpu_io_mixed_tg, asyncio_tcp, async_tree_none, tornado_http, xml_etree_parse, chameleon, richards_super, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_none_tg, unpickle, generators, bench_mp_pool, async_tree_io_tg, xml_etree_iterparse, pyflate, async_tree_io, pickle_pure_python, sqlglot_transpile, logging_silent, sqlglot_normalize, sqlglot_parse, richards, fannkuch, telco, gc_traversal, docutils, 2to3, xml_etree_process, python_startup, async_tree_memoization_tg, mako, mypy2, python_startup_no_site, create_gc_cycles, pycparser, bench_thread_pool, json


# HPT report

- Reliability score: 99.99% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
