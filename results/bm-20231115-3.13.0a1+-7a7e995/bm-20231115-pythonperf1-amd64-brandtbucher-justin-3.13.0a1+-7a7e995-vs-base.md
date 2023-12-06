
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.00x faster
- HPT reliability: 75.71%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 209 ms                                                                      | 213 ms: 1.02x slower                                                |
| chameleon      | 4.81 ms                                                                     | 4.74 ms: 1.01x faster                                               |
| docutils       | 1.55 sec                                                                    | 1.57 sec: 1.01x slower                                              |
| Geometric mean | (ref)                                                                       | 1.00x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|--------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none_tg | 280 ms                                                                      | 283 ms: 1.01x slower                                                |
| Geometric mean     | (ref)                                                                       | 1.00x slower                                                        |

Benchmark hidden because not significant (7): async_tree_memoization, async_tree_cpu_io_mixed, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_none, async_tree_io_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 73.4 ms                                                                     | 66.6 ms: 1.10x faster                                               |
| float          | 51.7 ms                                                                     | 50.2 ms: 1.03x faster                                               |
| pidigits       | 147 ms                                                                      | 150 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                                       | 1.03x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 80.1 ms                                                                     | 79.5 ms: 1.01x faster                                               |
| regex_dna      | 121 ms                                                                      | 122 ms: 1.01x slower                                                |
| regex_effbot   | 1.58 ms                                                                     | 1.61 ms: 1.02x slower                                               |
| regex_v8       | 15.0 ms                                                                     | 15.4 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 1.42 sec                                                                    | 1.27 sec: 1.12x faster                                              |
| xml_etree_iterparse  | 64.1 ms                                                                     | 62.1 ms: 1.03x faster                                               |
| xml_etree_generate   | 54.5 ms                                                                     | 53.3 ms: 1.02x faster                                               |
| xml_etree_process    | 36.9 ms                                                                     | 36.2 ms: 1.02x faster                                               |
| pickle_pure_python   | 182 us                                                                      | 180 us: 1.01x faster                                                |
| json_dumps           | 5.60 ms                                                                     | 5.67 ms: 1.01x slower                                               |
| unpickle_pure_python | 128 us                                                                      | 130 us: 1.02x slower                                                |
| unpickle_list        | 2.61 us                                                                     | 2.68 us: 1.03x slower                                               |
| pickle_dict          | 18.1 us                                                                     | 18.6 us: 1.03x slower                                               |
| json_loads           | 13.5 us                                                                     | 13.9 us: 1.03x slower                                               |
| unpickle             | 7.91 us                                                                     | 8.18 us: 1.03x slower                                               |
| pickle               | 6.89 us                                                                     | 7.22 us: 1.05x slower                                               |
| pickle_list          | 2.85 us                                                                     | 3.32 us: 1.16x slower                                               |
| Geometric mean       | (ref)                                                                       | 1.01x slower                                                        |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 17.8 ms                                                                     | 18.2 ms: 1.02x slower                                               |
| python_startup         | 19.8 ms                                                                     | 20.4 ms: 1.03x slower                                               |
| Geometric mean         | (ref)                                                                       | 1.03x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 6.51 ms                                                                     | 6.21 ms: 1.05x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20231115-pythonperf1-amd64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads             | 1.42 sec                                                                    | 1.27 sec: 1.12x faster                                              |
| nbody                   | 73.4 ms                                                                     | 66.6 ms: 1.10x faster                                               |
| deepcopy_memo           | 23.7 us                                                                     | 21.6 us: 1.10x faster                                               |
| richards_super          | 31.7 ms                                                                     | 29.1 ms: 1.09x faster                                               |
| scimark_sparse_mat_mult | 2.51 ms                                                                     | 2.31 ms: 1.08x faster                                               |
| deltablue               | 2.13 ms                                                                     | 1.98 ms: 1.07x faster                                               |
| richards                | 27.8 ms                                                                     | 25.9 ms: 1.07x faster                                               |
| spectral_norm           | 61.7 ms                                                                     | 58.3 ms: 1.06x faster                                               |
| mako                    | 6.51 ms                                                                     | 6.21 ms: 1.05x faster                                               |
| coverage                | 46.1 ms                                                                     | 44.3 ms: 1.04x faster                                               |
| fannkuch                | 248 ms                                                                      | 239 ms: 1.04x faster                                                |
| scimark_lu              | 56.4 ms                                                                     | 54.4 ms: 1.04x faster                                               |
| telco                   | 4.75 ms                                                                     | 4.59 ms: 1.04x faster                                               |
| xml_etree_iterparse     | 64.1 ms                                                                     | 62.1 ms: 1.03x faster                                               |
| coroutines              | 13.4 ms                                                                     | 13.0 ms: 1.03x faster                                               |
| float                   | 51.7 ms                                                                     | 50.2 ms: 1.03x faster                                               |
| scimark_sor             | 80.5 ms                                                                     | 78.3 ms: 1.03x faster                                               |
| sqlglot_transpile       | 992 us                                                                      | 967 us: 1.03x faster                                                |
| sqlglot_parse           | 773 us                                                                      | 754 us: 1.02x faster                                                |
| xml_etree_generate      | 54.5 ms                                                                     | 53.3 ms: 1.02x faster                                               |
| unpack_sequence         | 41.2 ns                                                                     | 40.4 ns: 1.02x faster                                               |
| xml_etree_process       | 36.9 ms                                                                     | 36.2 ms: 1.02x faster                                               |
| dulwich_log             | 41.4 ms                                                                     | 40.7 ms: 1.02x faster                                               |
| chameleon               | 4.81 ms                                                                     | 4.74 ms: 1.01x faster                                               |
| pickle_pure_python      | 182 us                                                                      | 180 us: 1.01x faster                                                |
| sqlite_synth            | 1.57 us                                                                     | 1.55 us: 1.01x faster                                               |
| deepcopy                | 220 us                                                                      | 218 us: 1.01x faster                                                |
| pprint_pformat          | 1.03 sec                                                                    | 1.02 sec: 1.01x faster                                              |
| regex_compile           | 80.1 ms                                                                     | 79.5 ms: 1.01x faster                                               |
| generators              | 21.0 ms                                                                     | 20.8 ms: 1.01x faster                                               |
| pprint_safe_repr        | 502 ms                                                                      | 500 ms: 1.01x faster                                                |
| logging_silent          | 56.1 ns                                                                     | 55.9 ns: 1.00x faster                                               |
| mdp                     | 1.45 sec                                                                    | 1.45 sec: 1.00x faster                                              |
| sympy_expand            | 267 ms                                                                      | 268 ms: 1.00x slower                                                |
| pyflate                 | 291 ms                                                                      | 293 ms: 1.00x slower                                                |
| sqlglot_optimize        | 33.2 ms                                                                     | 33.3 ms: 1.01x slower                                               |
| sympy_str               | 157 ms                                                                      | 158 ms: 1.01x slower                                                |
| regex_dna               | 121 ms                                                                      | 122 ms: 1.01x slower                                                |
| sqlglot_normalize       | 175 ms                                                                      | 177 ms: 1.01x slower                                                |
| gc_traversal            | 1.48 ms                                                                     | 1.50 ms: 1.01x slower                                               |
| sympy_sum               | 82.1 ms                                                                     | 82.9 ms: 1.01x slower                                               |
| dask                    | 252 ms                                                                      | 254 ms: 1.01x slower                                                |
| docutils                | 1.55 sec                                                                    | 1.57 sec: 1.01x slower                                              |
| async_tree_none_tg      | 280 ms                                                                      | 283 ms: 1.01x slower                                                |
| json_dumps              | 5.60 ms                                                                     | 5.67 ms: 1.01x slower                                               |
| meteor_contest          | 73.7 ms                                                                     | 74.7 ms: 1.01x slower                                               |
| logging_simple          | 6.04 us                                                                     | 6.13 us: 1.02x slower                                               |
| 2to3                    | 209 ms                                                                      | 213 ms: 1.02x slower                                                |
| async_generators        | 227 ms                                                                      | 231 ms: 1.02x slower                                                |
| go                      | 87.3 ms                                                                     | 88.8 ms: 1.02x slower                                               |
| regex_effbot            | 1.58 ms                                                                     | 1.61 ms: 1.02x slower                                               |
| unpickle_pure_python    | 128 us                                                                      | 130 us: 1.02x slower                                                |
| logging_format          | 6.46 us                                                                     | 6.58 us: 1.02x slower                                               |
| python_startup_no_site  | 17.8 ms                                                                     | 18.2 ms: 1.02x slower                                               |
| pidigits                | 147 ms                                                                      | 150 ms: 1.02x slower                                                |
| regex_v8                | 15.0 ms                                                                     | 15.4 ms: 1.02x slower                                               |
| unpickle_list           | 2.61 us                                                                     | 2.68 us: 1.03x slower                                               |
| pickle_dict             | 18.1 us                                                                     | 18.6 us: 1.03x slower                                               |
| bench_mp_pool           | 62.7 ms                                                                     | 64.4 ms: 1.03x slower                                               |
| chaos                   | 39.6 ms                                                                     | 40.7 ms: 1.03x slower                                               |
| python_startup          | 19.8 ms                                                                     | 20.4 ms: 1.03x slower                                               |
| json_loads              | 13.5 us                                                                     | 13.9 us: 1.03x slower                                               |
| sympy_integrate         | 12.3 ms                                                                     | 12.7 ms: 1.03x slower                                               |
| unpickle                | 7.91 us                                                                     | 8.18 us: 1.03x slower                                               |
| nqueens                 | 57.2 ms                                                                     | 59.5 ms: 1.04x slower                                               |
| comprehensions          | 10.5 us                                                                     | 11.0 us: 1.05x slower                                               |
| pickle                  | 6.89 us                                                                     | 7.22 us: 1.05x slower                                               |
| raytrace                | 163 ms                                                                      | 173 ms: 1.06x slower                                                |
| crypto_pyaes            | 43.5 ms                                                                     | 46.1 ms: 1.06x slower                                               |
| scimark_monte_carlo     | 41.8 ms                                                                     | 44.4 ms: 1.06x slower                                               |
| hexiom                  | 3.85 ms                                                                     | 4.15 ms: 1.08x slower                                               |
| pickle_list             | 2.85 us                                                                     | 3.32 us: 1.16x slower                                               |
| Geometric mean          | (ref)                                                                       | 1.00x faster                                                        |

Benchmark hidden because not significant (20): pycparser, asyncio_tcp_ssl, async_tree_memoization, async_tree_cpu_io_mixed, deepcopy_reduce, async_tree_memoization_tg, async_tree_cpu_io_mixed_tg, scimark_fft, pathlib, bench_thread_pool, typing_runtime_protocols, xml_etree_parse, async_tree_io, create_gc_cycles, tornado_http, async_tree_none, async_tree_io_tg, mypy2, json, asyncio_tcp


# HPT report

- Reliability score: 75.71% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
