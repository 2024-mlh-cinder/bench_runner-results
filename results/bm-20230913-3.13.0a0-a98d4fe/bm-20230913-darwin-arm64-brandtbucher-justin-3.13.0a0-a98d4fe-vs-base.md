
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 1.49 sec                                                              | 1.53 sec: 1.03x slower                                        |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| pidigits       | 282 ms                                                                | 282 ms: 1.00x slower                                          |
| float          | 55.5 ms                                                               | 56.8 ms: 1.02x slower                                         |
| nbody          | 70.8 ms                                                               | 82.4 ms: 1.16x slower                                         |
| Geometric mean | (ref)                                                                 | 1.06x slower                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_v8       | 16.4 ms                                                               | 16.4 ms: 1.00x slower                                         |
| regex_compile  | 77.0 ms                                                               | 82.1 ms: 1.07x slower                                         |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (2): regex_dna, regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                              | 1.41 sec: 1.10x faster                                        |
| pickle_dict          | 18.0 us                                                               | 17.9 us: 1.01x faster                                         |
| xml_etree_process    | 39.2 ms                                                               | 39.4 ms: 1.01x slower                                         |
| xml_etree_generate   | 57.3 ms                                                               | 57.7 ms: 1.01x slower                                         |
| pickle_list          | 2.83 us                                                               | 2.87 us: 1.01x slower                                         |
| unpickle             | 9.09 us                                                               | 9.21 us: 1.01x slower                                         |
| pickle               | 7.35 us                                                               | 7.45 us: 1.01x slower                                         |
| xml_etree_parse      | 109 ms                                                                | 111 ms: 1.02x slower                                          |
| xml_etree_iterparse  | 75.3 ms                                                               | 76.8 ms: 1.02x slower                                         |
| unpickle_list        | 3.16 us                                                               | 3.24 us: 1.02x slower                                         |
| unpickle_pure_python | 158 us                                                                | 165 us: 1.04x slower                                          |
| Geometric mean       | (ref)                                                                 | 1.00x slower                                                  |

Benchmark hidden because not significant (3): pickle_pure_python, json_loads, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 12.0 ms                                                               | 12.1 ms: 1.01x slower                                         |
| python_startup_no_site | 9.35 ms                                                               | 9.45 ms: 1.01x slower                                         |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 7.24 ms                                                               | 7.67 ms: 1.06x slower                                         |

All benchmarks:
===============

| Benchmark               | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-darwin-arm64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------:|
| tomli_loads             | 1.54 sec                                                              | 1.41 sec: 1.10x faster                                        |
| pyflate                 | 341 ms                                                                | 338 ms: 1.01x faster                                          |
| deepcopy_reduce         | 2.04 us                                                               | 2.02 us: 1.01x faster                                         |
| pickle_dict             | 18.0 us                                                               | 17.9 us: 1.01x faster                                         |
| pprint_safe_repr        | 507 ms                                                                | 504 ms: 1.00x faster                                          |
| richards                | 34.2 ms                                                               | 34.0 ms: 1.00x faster                                         |
| deepcopy                | 227 us                                                                | 226 us: 1.00x faster                                          |
| logging_simple          | 3.60 us                                                               | 3.59 us: 1.00x faster                                         |
| pidigits                | 282 ms                                                                | 282 ms: 1.00x slower                                          |
| pprint_pformat          | 1.03 sec                                                              | 1.03 sec: 1.00x slower                                        |
| logging_silent          | 70.9 ns                                                               | 71.1 ns: 1.00x slower                                         |
| regex_v8                | 16.4 ms                                                               | 16.4 ms: 1.00x slower                                         |
| async_tree_io           | 695 ms                                                                | 697 ms: 1.00x slower                                          |
| telco                   | 4.68 ms                                                               | 4.71 ms: 1.01x slower                                         |
| pycparser               | 688 ms                                                                | 692 ms: 1.01x slower                                          |
| xml_etree_process       | 39.2 ms                                                               | 39.4 ms: 1.01x slower                                         |
| sqlglot_parse           | 802 us                                                                | 808 us: 1.01x slower                                          |
| python_startup          | 12.0 ms                                                               | 12.1 ms: 1.01x slower                                         |
| xml_etree_generate      | 57.3 ms                                                               | 57.7 ms: 1.01x slower                                         |
| sqlglot_normalize       | 184 ms                                                                | 185 ms: 1.01x slower                                          |
| scimark_sor             | 105 ms                                                                | 106 ms: 1.01x slower                                          |
| unpack_sequence         | 26.8 ns                                                               | 27.0 ns: 1.01x slower                                         |
| dulwich_log             | 30.5 ms                                                               | 30.8 ms: 1.01x slower                                         |
| python_startup_no_site  | 9.35 ms                                                               | 9.45 ms: 1.01x slower                                         |
| pickle_list             | 2.83 us                                                               | 2.87 us: 1.01x slower                                         |
| sqlite_synth            | 1.58 us                                                               | 1.60 us: 1.01x slower                                         |
| sqlglot_transpile       | 976 us                                                                | 987 us: 1.01x slower                                          |
| raytrace                | 177 ms                                                                | 179 ms: 1.01x slower                                          |
| unpickle                | 9.09 us                                                               | 9.21 us: 1.01x slower                                         |
| pickle                  | 7.35 us                                                               | 7.45 us: 1.01x slower                                         |
| pathlib                 | 32.0 ms                                                               | 32.5 ms: 1.01x slower                                         |
| scimark_lu              | 71.6 ms                                                               | 72.7 ms: 1.01x slower                                         |
| richards_super          | 37.1 ms                                                               | 37.7 ms: 1.02x slower                                         |
| generators              | 24.5 ms                                                               | 24.9 ms: 1.02x slower                                         |
| xml_etree_parse         | 109 ms                                                                | 111 ms: 1.02x slower                                          |
| sqlglot_optimize        | 34.0 ms                                                               | 34.6 ms: 1.02x slower                                         |
| xml_etree_iterparse     | 75.3 ms                                                               | 76.8 ms: 1.02x slower                                         |
| scimark_monte_carlo     | 45.1 ms                                                               | 46.0 ms: 1.02x slower                                         |
| spectral_norm           | 71.5 ms                                                               | 73.1 ms: 1.02x slower                                         |
| float                   | 55.5 ms                                                               | 56.8 ms: 1.02x slower                                         |
| bench_mp_pool           | 46.5 ms                                                               | 47.6 ms: 1.02x slower                                         |
| unpickle_list           | 3.16 us                                                               | 3.24 us: 1.02x slower                                         |
| mdp                     | 1.63 sec                                                              | 1.67 sec: 1.03x slower                                        |
| docutils                | 1.49 sec                                                              | 1.53 sec: 1.03x slower                                        |
| bench_thread_pool       | 477 us                                                                | 492 us: 1.03x slower                                          |
| async_generators        | 302 ms                                                                | 311 ms: 1.03x slower                                          |
| mypy2                   | 189 ms                                                                | 196 ms: 1.04x slower                                          |
| deltablue               | 2.42 ms                                                               | 2.51 ms: 1.04x slower                                         |
| go                      | 104 ms                                                                | 109 ms: 1.04x slower                                          |
| fannkuch                | 280 ms                                                                | 291 ms: 1.04x slower                                          |
| unpickle_pure_python    | 158 us                                                                | 165 us: 1.04x slower                                          |
| crypto_pyaes            | 47.1 ms                                                               | 49.1 ms: 1.04x slower                                         |
| meteor_contest          | 73.6 ms                                                               | 77.2 ms: 1.05x slower                                         |
| deepcopy_memo           | 24.6 us                                                               | 25.9 us: 1.05x slower                                         |
| chaos                   | 40.3 ms                                                               | 42.5 ms: 1.05x slower                                         |
| mako                    | 7.24 ms                                                               | 7.67 ms: 1.06x slower                                         |
| regex_compile           | 77.0 ms                                                               | 82.1 ms: 1.07x slower                                         |
| scimark_sparse_mat_mult | 3.06 ms                                                               | 3.35 ms: 1.10x slower                                         |
| hexiom                  | 4.68 ms                                                               | 5.15 ms: 1.10x slower                                         |
| nqueens                 | 57.7 ms                                                               | 64.4 ms: 1.11x slower                                         |
| scimark_fft             | 197 ms                                                                | 221 ms: 1.12x slower                                          |
| comprehensions          | 14.6 us                                                               | 16.8 us: 1.16x slower                                         |
| nbody                   | 70.8 ms                                                               | 82.4 ms: 1.16x slower                                         |
| Geometric mean          | (ref)                                                                 | 1.02x slower                                                  |

Benchmark hidden because not significant (19): asyncio_tcp_ssl, typing_runtime_protocols, create_gc_cycles, coroutines, regex_dna, pickle_pure_python, logging_format, json_loads, regex_effbot, gc_traversal, coverage, json_dumps, json, asyncio_tcp, async_tree_cpu_io_mixed, dask, async_tree_memoization, async_tree_none, tornado_http


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
