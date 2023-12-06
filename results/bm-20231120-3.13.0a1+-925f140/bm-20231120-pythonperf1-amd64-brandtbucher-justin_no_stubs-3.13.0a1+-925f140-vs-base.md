
# Results vs. base

- fork: brandtbucher
- ref: justin_no_stubs
- machine: windows-amd64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.01x slower
- HPT reliability: 99.34%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| 2to3           | 219 ms                                                                      | 227 ms: 1.03x slower                                                         |
| docutils       | 1.59 sec                                                                    | 1.62 sec: 1.02x slower                                                       |
| tornado_http   | 86.9 ms                                                                     | 92.0 ms: 1.06x slower                                                        |
| Geometric mean | (ref)                                                                       | 1.03x slower                                                                 |

Benchmark hidden because not significant (1): chameleon

Benchmarks with tag 'asyncio':
==============================

| Benchmark                  | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| async_tree_io_tg           | 809 ms                                                                      | 798 ms: 1.01x faster                                                         |
| async_tree_none_tg         | 295 ms                                                                      | 298 ms: 1.01x slower                                                         |
| async_tree_cpu_io_mixed_tg | 500 ms                                                                      | 512 ms: 1.02x slower                                                         |
| Geometric mean             | (ref)                                                                       | 1.00x slower                                                                 |

Benchmark hidden because not significant (5): async_tree_memoization_tg, async_tree_memoization, async_tree_io, async_tree_cpu_io_mixed, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| nbody          | 75.2 ms                                                                     | 66.3 ms: 1.13x faster                                                        |
| float          | 54.1 ms                                                                     | 52.7 ms: 1.03x faster                                                        |
| pidigits       | 150 ms                                                                      | 152 ms: 1.01x slower                                                         |
| Geometric mean | (ref)                                                                       | 1.05x faster                                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| regex_compile  | 80.6 ms                                                                     | 83.4 ms: 1.03x slower                                                        |
| regex_dna      | 116 ms                                                                      | 122 ms: 1.05x slower                                                         |
| regex_effbot   | 1.58 ms                                                                     | 1.71 ms: 1.09x slower                                                        |
| regex_v8       | 15.5 ms                                                                     | 21.1 ms: 1.36x slower                                                        |
| Geometric mean | (ref)                                                                       | 1.13x slower                                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| tomli_loads          | 1.45 sec                                                                    | 1.33 sec: 1.09x faster                                                       |
| xml_etree_process    | 38.4 ms                                                                     | 36.8 ms: 1.05x faster                                                        |
| pickle               | 7.33 us                                                                     | 7.03 us: 1.04x faster                                                        |
| xml_etree_generate   | 55.9 ms                                                                     | 55.0 ms: 1.02x faster                                                        |
| xml_etree_iterparse  | 65.4 ms                                                                     | 64.5 ms: 1.01x faster                                                        |
| pickle_dict          | 19.0 us                                                                     | 19.2 us: 1.01x slower                                                        |
| unpickle_pure_python | 133 us                                                                      | 135 us: 1.01x slower                                                         |
| unpickle_list        | 2.67 us                                                                     | 2.74 us: 1.02x slower                                                        |
| xml_etree_parse      | 92.0 ms                                                                     | 95.3 ms: 1.04x slower                                                        |
| json_loads           | 14.0 us                                                                     | 14.6 us: 1.04x slower                                                        |
| json_dumps           | 5.69 ms                                                                     | 5.98 ms: 1.05x slower                                                        |
| pickle_list          | 2.92 us                                                                     | 3.44 us: 1.18x slower                                                        |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                                 |

Benchmark hidden because not significant (2): unpickle, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                                     | 20.7 ms: 1.03x slower                                                        |
| python_startup_no_site | 18.0 ms                                                                     | 19.1 ms: 1.06x slower                                                        |
| Geometric mean         | (ref)                                                                       | 1.05x slower                                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| mako      | 6.69 ms                                                                     | 6.28 ms: 1.07x faster                                                        |

All benchmarks:
===============

| Benchmark                  | bm-20231120-pythonperf1-amd64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-pythonperf1-amd64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------------|:---------------------------------------------------------------------------:|:----------------------------------------------------------------------------:|
| pycparser                  | 794 ms                                                                      | 692 ms: 1.15x faster                                                         |
| nbody                      | 75.2 ms                                                                     | 66.3 ms: 1.13x faster                                                        |
| richards                   | 29.2 ms                                                                     | 26.1 ms: 1.12x faster                                                        |
| richards_super             | 32.0 ms                                                                     | 29.1 ms: 1.10x faster                                                        |
| tomli_loads                | 1.45 sec                                                                    | 1.33 sec: 1.09x faster                                                       |
| asyncio_tcp_ssl            | 1.97 sec                                                                    | 1.83 sec: 1.08x faster                                                       |
| mako                       | 6.69 ms                                                                     | 6.28 ms: 1.07x faster                                                        |
| unpack_sequence            | 42.2 ns                                                                     | 40.0 ns: 1.06x faster                                                        |
| xml_etree_process          | 38.4 ms                                                                     | 36.8 ms: 1.05x faster                                                        |
| deepcopy_memo              | 24.0 us                                                                     | 23.0 us: 1.04x faster                                                        |
| pickle                     | 7.33 us                                                                     | 7.03 us: 1.04x faster                                                        |
| fannkuch                   | 260 ms                                                                      | 250 ms: 1.04x faster                                                         |
| deltablue                  | 2.11 ms                                                                     | 2.03 ms: 1.04x faster                                                        |
| float                      | 54.1 ms                                                                     | 52.7 ms: 1.03x faster                                                        |
| scimark_lu                 | 59.9 ms                                                                     | 58.6 ms: 1.02x faster                                                        |
| create_gc_cycles           | 764 us                                                                      | 749 us: 1.02x faster                                                         |
| generators                 | 21.7 ms                                                                     | 21.3 ms: 1.02x faster                                                        |
| xml_etree_generate         | 55.9 ms                                                                     | 55.0 ms: 1.02x faster                                                        |
| async_tree_io_tg           | 809 ms                                                                      | 798 ms: 1.01x faster                                                         |
| xml_etree_iterparse        | 65.4 ms                                                                     | 64.5 ms: 1.01x faster                                                        |
| pprint_safe_repr           | 520 ms                                                                      | 513 ms: 1.01x faster                                                         |
| sqlglot_parse              | 783 us                                                                      | 775 us: 1.01x faster                                                         |
| pprint_pformat             | 1.05 sec                                                                    | 1.04 sec: 1.01x faster                                                       |
| scimark_sor                | 81.9 ms                                                                     | 82.6 ms: 1.01x slower                                                        |
| gc_traversal               | 1.52 ms                                                                     | 1.54 ms: 1.01x slower                                                        |
| sympy_expand               | 276 ms                                                                      | 278 ms: 1.01x slower                                                         |
| meteor_contest             | 75.4 ms                                                                     | 76.1 ms: 1.01x slower                                                        |
| pickle_dict                | 19.0 us                                                                     | 19.2 us: 1.01x slower                                                        |
| sqlglot_transpile          | 1.00 ms                                                                     | 1.01 ms: 1.01x slower                                                        |
| pyflate                    | 300 ms                                                                      | 304 ms: 1.01x slower                                                         |
| async_tree_none_tg         | 295 ms                                                                      | 298 ms: 1.01x slower                                                         |
| typing_runtime_protocols   | 76.0 us                                                                     | 77.0 us: 1.01x slower                                                        |
| sqlite_synth               | 1.55 us                                                                     | 1.57 us: 1.01x slower                                                        |
| unpickle_pure_python       | 133 us                                                                      | 135 us: 1.01x slower                                                         |
| pidigits                   | 150 ms                                                                      | 152 ms: 1.01x slower                                                         |
| logging_format             | 6.71 us                                                                     | 6.82 us: 1.02x slower                                                        |
| raytrace                   | 170 ms                                                                      | 173 ms: 1.02x slower                                                         |
| logging_simple             | 6.22 us                                                                     | 6.32 us: 1.02x slower                                                        |
| docutils                   | 1.59 sec                                                                    | 1.62 sec: 1.02x slower                                                       |
| coroutines                 | 13.4 ms                                                                     | 13.7 ms: 1.02x slower                                                        |
| async_tree_cpu_io_mixed_tg | 500 ms                                                                      | 512 ms: 1.02x slower                                                         |
| unpickle_list              | 2.67 us                                                                     | 2.74 us: 1.02x slower                                                        |
| crypto_pyaes               | 45.4 ms                                                                     | 46.6 ms: 1.02x slower                                                        |
| sqlglot_normalize          | 181 ms                                                                      | 186 ms: 1.03x slower                                                         |
| telco                      | 4.64 ms                                                                     | 4.76 ms: 1.03x slower                                                        |
| deepcopy                   | 220 us                                                                      | 226 us: 1.03x slower                                                         |
| sympy_str                  | 160 ms                                                                      | 164 ms: 1.03x slower                                                         |
| nqueens                    | 58.7 ms                                                                     | 60.4 ms: 1.03x slower                                                        |
| bench_mp_pool              | 65.3 ms                                                                     | 67.5 ms: 1.03x slower                                                        |
| python_startup             | 20.0 ms                                                                     | 20.7 ms: 1.03x slower                                                        |
| regex_compile              | 80.6 ms                                                                     | 83.4 ms: 1.03x slower                                                        |
| 2to3                       | 219 ms                                                                      | 227 ms: 1.03x slower                                                         |
| xml_etree_parse            | 92.0 ms                                                                     | 95.3 ms: 1.04x slower                                                        |
| logging_silent             | 56.1 ns                                                                     | 58.2 ns: 1.04x slower                                                        |
| sympy_sum                  | 84.1 ms                                                                     | 87.3 ms: 1.04x slower                                                        |
| json_loads                 | 14.0 us                                                                     | 14.6 us: 1.04x slower                                                        |
| dulwich_log                | 42.6 ms                                                                     | 44.3 ms: 1.04x slower                                                        |
| sqlglot_optimize           | 34.0 ms                                                                     | 35.4 ms: 1.04x slower                                                        |
| dask                       | 259 ms                                                                      | 269 ms: 1.04x slower                                                         |
| regex_dna                  | 116 ms                                                                      | 122 ms: 1.05x slower                                                         |
| json_dumps                 | 5.69 ms                                                                     | 5.98 ms: 1.05x slower                                                        |
| scimark_monte_carlo        | 42.9 ms                                                                     | 45.1 ms: 1.05x slower                                                        |
| sympy_integrate            | 12.4 ms                                                                     | 13.1 ms: 1.05x slower                                                        |
| go                         | 88.4 ms                                                                     | 93.1 ms: 1.05x slower                                                        |
| async_generators           | 229 ms                                                                      | 241 ms: 1.05x slower                                                         |
| chaos                      | 40.2 ms                                                                     | 42.5 ms: 1.06x slower                                                        |
| tornado_http               | 86.9 ms                                                                     | 92.0 ms: 1.06x slower                                                        |
| python_startup_no_site     | 18.0 ms                                                                     | 19.1 ms: 1.06x slower                                                        |
| spectral_norm              | 62.4 ms                                                                     | 66.9 ms: 1.07x slower                                                        |
| coverage                   | 47.7 ms                                                                     | 51.3 ms: 1.08x slower                                                        |
| comprehensions             | 10.5 us                                                                     | 11.3 us: 1.08x slower                                                        |
| scimark_fft                | 180 ms                                                                      | 194 ms: 1.08x slower                                                         |
| regex_effbot               | 1.58 ms                                                                     | 1.71 ms: 1.09x slower                                                        |
| hexiom                     | 3.91 ms                                                                     | 4.31 ms: 1.10x slower                                                        |
| scimark_sparse_mat_mult    | 2.45 ms                                                                     | 2.71 ms: 1.11x slower                                                        |
| pickle_list                | 2.92 us                                                                     | 3.44 us: 1.18x slower                                                        |
| regex_v8                   | 15.5 ms                                                                     | 21.1 ms: 1.36x slower                                                        |
| Geometric mean             | (ref)                                                                       | 1.01x slower                                                                 |

Benchmark hidden because not significant (15): json, chameleon, async_tree_memoization_tg, async_tree_memoization, unpickle, async_tree_io, async_tree_cpu_io_mixed, bench_thread_pool, pickle_pure_python, mdp, pathlib, deepcopy_reduce, asyncio_tcp, async_tree_none, mypy2


# HPT report

- Reliability score: 99.34% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
