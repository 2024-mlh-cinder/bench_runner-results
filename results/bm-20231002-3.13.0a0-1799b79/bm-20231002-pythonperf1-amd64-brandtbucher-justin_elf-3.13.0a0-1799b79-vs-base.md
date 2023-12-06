
# Results vs. base

- fork: brandtbucher
- ref: justin_elf
- machine: windows-amd64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.10x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 1.62 sec                                                                   | 1.70 sec: 1.05x slower                                                 |
| tornado_http   | 88.6 ms                                                                    | 91.4 ms: 1.03x slower                                                  |
| Geometric mean | (ref)                                                                      | 1.04x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 76.1 ms                                                                    | 73.8 ms: 1.03x faster                                                  |
| pidigits       | 150 ms                                                                     | 150 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                                      | 1.01x faster                                                           |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 122 ms                                                                     | 121 ms: 1.01x faster                                                   |
| regex_effbot   | 1.60 ms                                                                    | 1.62 ms: 1.01x slower                                                  |
| regex_compile  | 89.4 ms                                                                    | 100 ms: 1.12x slower                                                   |
| regex_v8       | 15.1 ms                                                                    | 17.2 ms: 1.14x slower                                                  |
| Geometric mean | (ref)                                                                      | 1.07x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_list          | 3.01 us                                                                    | 2.84 us: 1.06x faster                                                  |
| tomli_loads          | 1.49 sec                                                                   | 1.43 sec: 1.04x faster                                                 |
| pickle_dict          | 18.3 us                                                                    | 18.2 us: 1.01x faster                                                  |
| pickle               | 7.13 us                                                                    | 7.09 us: 1.01x faster                                                  |
| unpickle_list        | 2.70 us                                                                    | 2.73 us: 1.01x slower                                                  |
| json_loads           | 13.5 us                                                                    | 13.9 us: 1.02x slower                                                  |
| xml_etree_parse      | 91.6 ms                                                                    | 93.9 ms: 1.03x slower                                                  |
| xml_etree_iterparse  | 64.0 ms                                                                    | 68.3 ms: 1.07x slower                                                  |
| json_dumps           | 5.64 ms                                                                    | 6.01 ms: 1.07x slower                                                  |
| unpickle             | 8.08 us                                                                    | 8.62 us: 1.07x slower                                                  |
| xml_etree_generate   | 55.8 ms                                                                    | 62.7 ms: 1.12x slower                                                  |
| xml_etree_process    | 38.6 ms                                                                    | 45.1 ms: 1.17x slower                                                  |
| pickle_pure_python   | 191 us                                                                     | 225 us: 1.18x slower                                                   |
| unpickle_pure_python | 136 us                                                                     | 174 us: 1.27x slower                                                   |
| Geometric mean       | (ref)                                                                      | 1.06x slower                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup | 19.4 ms                                                                    | 19.8 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                                      | 1.02x slower                                                           |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.44 ms                                                                    | 7.99 ms: 1.07x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-pythonperf1-amd64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:--------------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| asyncio_tcp_ssl          | 1.85 sec                                                                   | 1.73 sec: 1.07x faster                                                 |
| pickle_list              | 3.01 us                                                                    | 2.84 us: 1.06x faster                                                  |
| tomli_loads              | 1.49 sec                                                                   | 1.43 sec: 1.04x faster                                                 |
| nbody                    | 76.1 ms                                                                    | 73.8 ms: 1.03x faster                                                  |
| regex_dna                | 122 ms                                                                     | 121 ms: 1.01x faster                                                   |
| pickle_dict              | 18.3 us                                                                    | 18.2 us: 1.01x faster                                                  |
| pickle                   | 7.13 us                                                                    | 7.09 us: 1.01x faster                                                  |
| pidigits                 | 150 ms                                                                     | 150 ms: 1.00x slower                                                   |
| gc_traversal             | 1.49 ms                                                                    | 1.51 ms: 1.01x slower                                                  |
| json                     | 2.92 ms                                                                    | 2.95 ms: 1.01x slower                                                  |
| sqlite_synth             | 1.77 us                                                                    | 1.79 us: 1.01x slower                                                  |
| pathlib                  | 77.3 ms                                                                    | 78.2 ms: 1.01x slower                                                  |
| unpickle_list            | 2.70 us                                                                    | 2.73 us: 1.01x slower                                                  |
| regex_effbot             | 1.60 ms                                                                    | 1.62 ms: 1.01x slower                                                  |
| scimark_sparse_mat_mult  | 2.46 ms                                                                    | 2.51 ms: 1.02x slower                                                  |
| python_startup           | 19.4 ms                                                                    | 19.8 ms: 1.02x slower                                                  |
| json_loads               | 13.5 us                                                                    | 13.9 us: 1.02x slower                                                  |
| dulwich_log              | 44.7 ms                                                                    | 45.8 ms: 1.02x slower                                                  |
| xml_etree_parse          | 91.6 ms                                                                    | 93.9 ms: 1.03x slower                                                  |
| tornado_http             | 88.6 ms                                                                    | 91.4 ms: 1.03x slower                                                  |
| bench_thread_pool        | 847 us                                                                     | 878 us: 1.04x slower                                                   |
| bench_mp_pool            | 64.9 ms                                                                    | 68.0 ms: 1.05x slower                                                  |
| coverage                 | 45.0 ms                                                                    | 47.2 ms: 1.05x slower                                                  |
| docutils                 | 1.62 sec                                                                   | 1.70 sec: 1.05x slower                                                 |
| async_tree_cpu_io_mixed  | 472 ms                                                                     | 497 ms: 1.05x slower                                                   |
| asyncio_tcp              | 462 ms                                                                     | 488 ms: 1.06x slower                                                   |
| telco                    | 4.78 ms                                                                    | 5.07 ms: 1.06x slower                                                  |
| xml_etree_iterparse      | 64.0 ms                                                                    | 68.3 ms: 1.07x slower                                                  |
| json_dumps               | 5.64 ms                                                                    | 6.01 ms: 1.07x slower                                                  |
| unpickle                 | 8.08 us                                                                    | 8.62 us: 1.07x slower                                                  |
| fannkuch                 | 254 ms                                                                     | 273 ms: 1.07x slower                                                   |
| mako                     | 7.44 ms                                                                    | 7.99 ms: 1.07x slower                                                  |
| async_tree_io            | 728 ms                                                                     | 782 ms: 1.07x slower                                                   |
| mdp                      | 1.43 sec                                                                   | 1.54 sec: 1.07x slower                                                 |
| mypy2                    | 214 ms                                                                     | 230 ms: 1.08x slower                                                   |
| async_tree_memoization   | 344 ms                                                                     | 370 ms: 1.08x slower                                                   |
| crypto_pyaes             | 45.5 ms                                                                    | 49.2 ms: 1.08x slower                                                  |
| async_tree_none          | 269 ms                                                                     | 292 ms: 1.08x slower                                                   |
| meteor_contest           | 73.8 ms                                                                    | 80.5 ms: 1.09x slower                                                  |
| typing_runtime_protocols | 95.0 us                                                                    | 104 us: 1.09x slower                                                   |
| async_generators         | 241 ms                                                                     | 267 ms: 1.11x slower                                                   |
| sqlglot_optimize         | 34.9 ms                                                                    | 38.9 ms: 1.11x slower                                                  |
| regex_compile            | 89.4 ms                                                                    | 100 ms: 1.12x slower                                                   |
| unpack_sequence          | 42.7 ns                                                                    | 48.0 ns: 1.12x slower                                                  |
| logging_simple           | 6.35 us                                                                    | 7.14 us: 1.12x slower                                                  |
| xml_etree_generate       | 55.8 ms                                                                    | 62.7 ms: 1.12x slower                                                  |
| comprehensions           | 14.6 us                                                                    | 16.4 us: 1.13x slower                                                  |
| logging_format           | 6.77 us                                                                    | 7.64 us: 1.13x slower                                                  |
| sqlglot_normalize        | 183 ms                                                                     | 207 ms: 1.13x slower                                                   |
| pprint_safe_repr         | 525 ms                                                                     | 600 ms: 1.14x slower                                                   |
| regex_v8                 | 15.1 ms                                                                    | 17.2 ms: 1.14x slower                                                  |
| deepcopy_reduce          | 2.08 us                                                                    | 2.39 us: 1.15x slower                                                  |
| nqueens                  | 61.0 ms                                                                    | 69.9 ms: 1.15x slower                                                  |
| scimark_fft              | 181 ms                                                                     | 208 ms: 1.15x slower                                                   |
| deepcopy                 | 236 us                                                                     | 272 us: 1.15x slower                                                   |
| pprint_pformat           | 1.07 sec                                                                   | 1.24 sec: 1.16x slower                                                 |
| sqlglot_transpile        | 1.04 ms                                                                    | 1.21 ms: 1.16x slower                                                  |
| xml_etree_process        | 38.6 ms                                                                    | 45.1 ms: 1.17x slower                                                  |
| pickle_pure_python       | 191 us                                                                     | 225 us: 1.18x slower                                                   |
| pyflate                  | 300 ms                                                                     | 356 ms: 1.19x slower                                                   |
| sqlglot_parse            | 814 us                                                                     | 983 us: 1.21x slower                                                   |
| chaos                    | 41.2 ms                                                                    | 50.0 ms: 1.21x slower                                                  |
| go                       | 91.5 ms                                                                    | 112 ms: 1.22x slower                                                   |
| scimark_lu               | 60.4 ms                                                                    | 74.0 ms: 1.22x slower                                                  |
| raytrace                 | 176 ms                                                                     | 216 ms: 1.23x slower                                                   |
| richards_super           | 31.9 ms                                                                    | 39.2 ms: 1.23x slower                                                  |
| hexiom                   | 4.18 ms                                                                    | 5.16 ms: 1.24x slower                                                  |
| richards                 | 28.8 ms                                                                    | 35.7 ms: 1.24x slower                                                  |
| scimark_sor              | 83.2 ms                                                                    | 104 ms: 1.25x slower                                                   |
| scimark_monte_carlo      | 42.2 ms                                                                    | 52.9 ms: 1.25x slower                                                  |
| spectral_norm            | 64.1 ms                                                                    | 80.7 ms: 1.26x slower                                                  |
| unpickle_pure_python     | 136 us                                                                     | 174 us: 1.27x slower                                                   |
| deltablue                | 2.20 ms                                                                    | 2.81 ms: 1.28x slower                                                  |
| deepcopy_memo            | 24.3 us                                                                    | 31.1 us: 1.28x slower                                                  |
| coroutines               | 14.6 ms                                                                    | 18.8 ms: 1.29x slower                                                  |
| logging_silent           | 64.6 ns                                                                    | 92.1 ns: 1.42x slower                                                  |
| generators               | 23.1 ms                                                                    | 33.5 ms: 1.45x slower                                                  |
| Geometric mean           | (ref)                                                                      | 1.10x slower                                                           |

Benchmark hidden because not significant (4): pycparser, float, create_gc_cycles, python_startup_no_site


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.06x
