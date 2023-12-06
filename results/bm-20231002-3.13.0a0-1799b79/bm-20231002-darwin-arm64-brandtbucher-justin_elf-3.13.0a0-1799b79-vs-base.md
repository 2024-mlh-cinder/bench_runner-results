
# Results vs. base

- fork: brandtbucher
- ref: justin_elf
- machine: darwin-arm64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 1.50 sec                                                              | 1.52 sec: 1.01x slower                                            |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                      |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 282 ms                                                                | 283 ms: 1.00x slower                                              |
| float          | 53.6 ms                                                               | 57.0 ms: 1.06x slower                                             |
| nbody          | 66.1 ms                                                               | 79.6 ms: 1.20x slower                                             |
| Geometric mean | (ref)                                                                 | 1.09x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_dna      | 140 ms                                                                | 140 ms: 1.00x slower                                              |
| regex_effbot   | 2.52 ms                                                               | 2.54 ms: 1.01x slower                                             |
| regex_v8       | 16.2 ms                                                               | 16.4 ms: 1.01x slower                                             |
| regex_compile  | 75.7 ms                                                               | 81.3 ms: 1.07x slower                                             |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                              | 1.39 sec: 1.11x faster                                            |
| json_dumps           | 6.76 ms                                                               | 6.53 ms: 1.04x faster                                             |
| pickle_list          | 2.86 us                                                               | 2.85 us: 1.01x faster                                             |
| unpickle_list        | 3.14 us                                                               | 3.16 us: 1.01x slower                                             |
| xml_etree_iterparse  | 75.9 ms                                                               | 76.5 ms: 1.01x slower                                             |
| xml_etree_process    | 39.3 ms                                                               | 39.6 ms: 1.01x slower                                             |
| json_loads           | 17.5 us                                                               | 17.7 us: 1.01x slower                                             |
| pickle               | 7.38 us                                                               | 7.47 us: 1.01x slower                                             |
| pickle_pure_python   | 193 us                                                                | 197 us: 1.02x slower                                              |
| xml_etree_generate   | 56.2 ms                                                               | 57.7 ms: 1.03x slower                                             |
| unpickle_pure_python | 154 us                                                                | 160 us: 1.04x slower                                              |
| Geometric mean       | (ref)                                                                 | 1.00x faster                                                      |

Benchmark hidden because not significant (3): xml_etree_parse, unpickle, pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup_no_site | 8.86 ms                                                               | 8.62 ms: 1.03x faster                                             |
| python_startup         | 11.4 ms                                                               | 11.2 ms: 1.02x faster                                             |
| Geometric mean         | (ref)                                                                 | 1.02x faster                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 7.29 ms                                                               | 7.56 ms: 1.04x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-darwin-arm64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| tomli_loads              | 1.54 sec                                                              | 1.39 sec: 1.11x faster                                            |
| asyncio_tcp              | 461 ms                                                                | 421 ms: 1.10x faster                                              |
| richards                 | 34.2 ms                                                               | 31.9 ms: 1.07x faster                                             |
| richards_super           | 37.8 ms                                                               | 35.6 ms: 1.06x faster                                             |
| json_dumps               | 6.76 ms                                                               | 6.53 ms: 1.04x faster                                             |
| python_startup_no_site   | 8.86 ms                                                               | 8.62 ms: 1.03x faster                                             |
| python_startup           | 11.4 ms                                                               | 11.2 ms: 1.02x faster                                             |
| generators               | 25.4 ms                                                               | 25.1 ms: 1.01x faster                                             |
| pickle_list              | 2.86 us                                                               | 2.85 us: 1.01x faster                                             |
| logging_format           | 3.92 us                                                               | 3.91 us: 1.00x faster                                             |
| logging_simple           | 3.63 us                                                               | 3.62 us: 1.00x faster                                             |
| regex_dna                | 140 ms                                                                | 140 ms: 1.00x slower                                              |
| pidigits                 | 282 ms                                                                | 283 ms: 1.00x slower                                              |
| unpickle_list            | 3.14 us                                                               | 3.16 us: 1.01x slower                                             |
| xml_etree_iterparse      | 75.9 ms                                                               | 76.5 ms: 1.01x slower                                             |
| xml_etree_process        | 39.3 ms                                                               | 39.6 ms: 1.01x slower                                             |
| regex_effbot             | 2.52 ms                                                               | 2.54 ms: 1.01x slower                                             |
| json_loads               | 17.5 us                                                               | 17.7 us: 1.01x slower                                             |
| docutils                 | 1.50 sec                                                              | 1.52 sec: 1.01x slower                                            |
| pickle                   | 7.38 us                                                               | 7.47 us: 1.01x slower                                             |
| deepcopy_reduce          | 1.97 us                                                               | 2.00 us: 1.01x slower                                             |
| regex_v8                 | 16.2 ms                                                               | 16.4 ms: 1.01x slower                                             |
| pycparser                | 688 ms                                                                | 698 ms: 1.02x slower                                              |
| coverage                 | 46.1 ms                                                               | 46.9 ms: 1.02x slower                                             |
| deepcopy                 | 222 us                                                                | 226 us: 1.02x slower                                              |
| pickle_pure_python       | 193 us                                                                | 197 us: 1.02x slower                                              |
| dulwich_log              | 30.4 ms                                                               | 31.1 ms: 1.02x slower                                             |
| sqlglot_transpile        | 969 us                                                                | 990 us: 1.02x slower                                              |
| bench_mp_pool            | 45.6 ms                                                               | 46.6 ms: 1.02x slower                                             |
| coroutines               | 17.6 ms                                                               | 18.0 ms: 1.02x slower                                             |
| sqlglot_normalize        | 182 ms                                                                | 186 ms: 1.02x slower                                              |
| typing_runtime_protocols | 92.3 us                                                               | 94.6 us: 1.02x slower                                             |
| sqlglot_parse            | 793 us                                                                | 813 us: 1.02x slower                                              |
| sqlglot_optimize         | 34.0 ms                                                               | 34.8 ms: 1.02x slower                                             |
| xml_etree_generate       | 56.2 ms                                                               | 57.7 ms: 1.03x slower                                             |
| bench_thread_pool        | 479 us                                                                | 494 us: 1.03x slower                                              |
| scimark_sor              | 103 ms                                                                | 106 ms: 1.03x slower                                              |
| fannkuch                 | 283 ms                                                                | 294 ms: 1.04x slower                                              |
| mako                     | 7.29 ms                                                               | 7.56 ms: 1.04x slower                                             |
| unpack_sequence          | 26.3 ns                                                               | 27.3 ns: 1.04x slower                                             |
| sqlite_synth             | 1.57 us                                                               | 1.63 us: 1.04x slower                                             |
| crypto_pyaes             | 46.9 ms                                                               | 48.7 ms: 1.04x slower                                             |
| unpickle_pure_python     | 154 us                                                                | 160 us: 1.04x slower                                              |
| telco                    | 4.55 ms                                                               | 4.74 ms: 1.04x slower                                             |
| mdp                      | 1.61 sec                                                              | 1.68 sec: 1.05x slower                                            |
| async_generators         | 296 ms                                                                | 311 ms: 1.05x slower                                              |
| spectral_norm            | 69.6 ms                                                               | 73.0 ms: 1.05x slower                                             |
| scimark_lu               | 70.0 ms                                                               | 73.4 ms: 1.05x slower                                             |
| go                       | 103 ms                                                                | 108 ms: 1.05x slower                                              |
| float                    | 53.6 ms                                                               | 57.0 ms: 1.06x slower                                             |
| meteor_contest           | 73.4 ms                                                               | 78.1 ms: 1.06x slower                                             |
| scimark_monte_carlo      | 44.2 ms                                                               | 47.3 ms: 1.07x slower                                             |
| regex_compile            | 75.7 ms                                                               | 81.3 ms: 1.07x slower                                             |
| deltablue                | 2.35 ms                                                               | 2.53 ms: 1.08x slower                                             |
| logging_silent           | 67.5 ns                                                               | 72.6 ns: 1.08x slower                                             |
| deepcopy_memo            | 23.7 us                                                               | 25.6 us: 1.08x slower                                             |
| raytrace                 | 171 ms                                                                | 185 ms: 1.08x slower                                              |
| scimark_sparse_mat_mult  | 2.99 ms                                                               | 3.26 ms: 1.09x slower                                             |
| chaos                    | 39.7 ms                                                               | 43.9 ms: 1.11x slower                                             |
| scimark_fft              | 193 ms                                                                | 215 ms: 1.12x slower                                              |
| comprehensions           | 14.8 us                                                               | 16.5 us: 1.12x slower                                             |
| nqueens                  | 56.7 ms                                                               | 64.0 ms: 1.13x slower                                             |
| hexiom                   | 4.63 ms                                                               | 5.29 ms: 1.14x slower                                             |
| nbody                    | 66.1 ms                                                               | 79.6 ms: 1.20x slower                                             |
| Geometric mean           | (ref)                                                                 | 1.03x slower                                                      |

Benchmark hidden because not significant (15): xml_etree_parse, unpickle, json, create_gc_cycles, gc_traversal, pickle_dict, pyflate, mypy2, async_tree_io, asyncio_tcp_ssl, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none, pathlib, tornado_http
Ignored benchmarks (2) of results/bm-20231002-3.13.0a0-4596c76/bm-20231002-darwin-arm64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76.json: pprint_pformat, pprint_safe_repr


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
