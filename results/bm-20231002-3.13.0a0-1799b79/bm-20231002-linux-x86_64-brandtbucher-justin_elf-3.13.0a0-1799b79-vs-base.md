
# Results vs. base

- fork: brandtbucher
- ref: justin_elf
- machine: linux-x86_64
- commit hash: 1799b79
- commit date: 2023-10-02
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.63 sec                                                              | 2.66 sec: 1.01x slower                                            |
| tornado_http   | 94.8 ms                                                               | 96.7 ms: 1.02x slower                                             |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                              |
| float          | 79.1 ms                                                               | 84.0 ms: 1.06x slower                                             |
| nbody          | 89.3 ms                                                               | 105 ms: 1.18x slower                                              |
| Geometric mean | (ref)                                                                 | 1.08x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_effbot   | 3.51 ms                                                               | 3.39 ms: 1.03x faster                                             |
| regex_dna      | 216 ms                                                                | 210 ms: 1.03x faster                                              |
| regex_v8       | 25.1 ms                                                               | 24.5 ms: 1.02x faster                                             |
| regex_compile  | 133 ms                                                                | 143 ms: 1.07x slower                                              |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_list          | 4.90 us                                                               | 4.70 us: 1.04x faster                                             |
| unpickle_list        | 4.92 us                                                               | 4.86 us: 1.01x faster                                             |
| pickle               | 10.5 us                                                               | 10.4 us: 1.01x faster                                             |
| pickle_dict          | 32.0 us                                                               | 31.9 us: 1.00x faster                                             |
| xml_etree_generate   | 83.5 ms                                                               | 83.9 ms: 1.00x slower                                             |
| json_dumps           | 9.85 ms                                                               | 9.94 ms: 1.01x slower                                             |
| json_loads           | 25.8 us                                                               | 26.1 us: 1.01x slower                                             |
| xml_etree_parse      | 151 ms                                                                | 153 ms: 1.01x slower                                              |
| xml_etree_iterparse  | 102 ms                                                                | 105 ms: 1.03x slower                                              |
| unpickle_pure_python | 213 us                                                                | 225 us: 1.06x slower                                              |
| tomli_loads          | 2.02 sec                                                              | 2.20 sec: 1.09x slower                                            |
| unpickle             | 14.3 us                                                               | 16.5 us: 1.16x slower                                             |
| Geometric mean       | (ref)                                                                 | 1.02x slower                                                      |

Benchmark hidden because not significant (2): pickle_pure_python, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 9.96 ms                                                               | 10.1 ms: 1.01x slower                                             |
| python_startup_no_site | 6.80 ms                                                               | 6.92 ms: 1.02x slower                                             |
| Geometric mean         | (ref)                                                                 | 1.02x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.4 ms                                                               | 11.1 ms: 1.06x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-4596c76d1a7650fd4650-3.13.0a0-4596c76 | bm-20231002-linux-x86_64-brandtbucher-justin_elf-3.13.0a0-1799b79 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| scimark_sor              | 127 ms                                                                | 121 ms: 1.05x faster                                              |
| pickle_list              | 4.90 us                                                               | 4.70 us: 1.04x faster                                             |
| regex_effbot             | 3.51 ms                                                               | 3.39 ms: 1.03x faster                                             |
| regex_dna                | 216 ms                                                                | 210 ms: 1.03x faster                                              |
| spectral_norm            | 107 ms                                                                | 104 ms: 1.03x faster                                              |
| regex_v8                 | 25.1 ms                                                               | 24.5 ms: 1.02x faster                                             |
| sqlite_synth             | 2.78 us                                                               | 2.73 us: 1.02x faster                                             |
| deepcopy_reduce          | 3.07 us                                                               | 3.03 us: 1.01x faster                                             |
| generators               | 28.9 ms                                                               | 28.5 ms: 1.01x faster                                             |
| unpickle_list            | 4.92 us                                                               | 4.86 us: 1.01x faster                                             |
| pickle                   | 10.5 us                                                               | 10.4 us: 1.01x faster                                             |
| coverage                 | 85.9 ms                                                               | 85.3 ms: 1.01x faster                                             |
| pickle_dict              | 32.0 us                                                               | 31.9 us: 1.00x faster                                             |
| gc_traversal             | 4.35 ms                                                               | 4.36 ms: 1.00x slower                                             |
| xml_etree_generate       | 83.5 ms                                                               | 83.9 ms: 1.00x slower                                             |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                              |
| json_dumps               | 9.85 ms                                                               | 9.94 ms: 1.01x slower                                             |
| sqlglot_parse            | 1.26 ms                                                               | 1.27 ms: 1.01x slower                                             |
| sqlglot_transpile        | 1.58 ms                                                               | 1.60 ms: 1.01x slower                                             |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.82 sec: 1.01x slower                                            |
| docutils                 | 2.63 sec                                                              | 2.66 sec: 1.01x slower                                            |
| json_loads               | 25.8 us                                                               | 26.1 us: 1.01x slower                                             |
| asyncio_tcp              | 503 ms                                                                | 509 ms: 1.01x slower                                              |
| python_startup           | 9.96 ms                                                               | 10.1 ms: 1.01x slower                                             |
| xml_etree_parse          | 151 ms                                                                | 153 ms: 1.01x slower                                              |
| scimark_fft              | 352 ms                                                                | 357 ms: 1.02x slower                                              |
| python_startup_no_site   | 6.80 ms                                                               | 6.92 ms: 1.02x slower                                             |
| deepcopy                 | 343 us                                                                | 349 us: 1.02x slower                                              |
| create_gc_cycles         | 1.51 ms                                                               | 1.54 ms: 1.02x slower                                             |
| pathlib                  | 18.7 ms                                                               | 19.1 ms: 1.02x slower                                             |
| tornado_http             | 94.8 ms                                                               | 96.7 ms: 1.02x slower                                             |
| logging_simple           | 5.91 us                                                               | 6.04 us: 1.02x slower                                             |
| sqlglot_normalize        | 104 ms                                                                | 107 ms: 1.02x slower                                              |
| sqlglot_optimize         | 52.3 ms                                                               | 53.6 ms: 1.03x slower                                             |
| telco                    | 8.03 ms                                                               | 8.24 ms: 1.03x slower                                             |
| async_tree_io            | 1.18 sec                                                              | 1.22 sec: 1.03x slower                                            |
| xml_etree_iterparse      | 102 ms                                                                | 105 ms: 1.03x slower                                              |
| dulwich_log              | 65.8 ms                                                               | 67.9 ms: 1.03x slower                                             |
| coroutines               | 21.8 ms                                                               | 22.6 ms: 1.04x slower                                             |
| logging_format           | 6.45 us                                                               | 6.68 us: 1.04x slower                                             |
| crypto_pyaes             | 68.3 ms                                                               | 70.9 ms: 1.04x slower                                             |
| mdp                      | 2.55 sec                                                              | 2.65 sec: 1.04x slower                                            |
| mypy2                    | 335 ms                                                                | 349 ms: 1.04x slower                                              |
| async_generators         | 440 ms                                                                | 458 ms: 1.04x slower                                              |
| async_tree_cpu_io_mixed  | 698 ms                                                                | 727 ms: 1.04x slower                                              |
| meteor_contest           | 106 ms                                                                | 111 ms: 1.04x slower                                              |
| bench_thread_pool        | 806 us                                                                | 841 us: 1.04x slower                                              |
| scimark_lu               | 110 ms                                                                | 115 ms: 1.04x slower                                              |
| typing_runtime_protocols | 141 us                                                                | 148 us: 1.05x slower                                              |
| async_tree_none          | 435 ms                                                                | 457 ms: 1.05x slower                                              |
| async_tree_memoization   | 559 ms                                                                | 589 ms: 1.05x slower                                              |
| go                       | 140 ms                                                                | 147 ms: 1.05x slower                                              |
| unpickle_pure_python     | 213 us                                                                | 225 us: 1.06x slower                                              |
| mako                     | 10.4 ms                                                               | 11.1 ms: 1.06x slower                                             |
| pycparser                | 1.16 sec                                                              | 1.22 sec: 1.06x slower                                            |
| scimark_sparse_mat_mult  | 4.67 ms                                                               | 4.95 ms: 1.06x slower                                             |
| float                    | 79.1 ms                                                               | 84.0 ms: 1.06x slower                                             |
| deepcopy_memo            | 36.6 us                                                               | 38.9 us: 1.06x slower                                             |
| regex_compile            | 133 ms                                                                | 143 ms: 1.07x slower                                              |
| raytrace                 | 267 ms                                                                | 289 ms: 1.08x slower                                              |
| tomli_loads              | 2.02 sec                                                              | 2.20 sec: 1.09x slower                                            |
| unpack_sequence          | 47.5 ns                                                               | 51.9 ns: 1.09x slower                                             |
| fannkuch                 | 383 ms                                                                | 419 ms: 1.09x slower                                              |
| deltablue                | 3.30 ms                                                               | 3.61 ms: 1.10x slower                                             |
| pyflate                  | 448 ms                                                                | 502 ms: 1.12x slower                                              |
| scimark_monte_carlo      | 65.0 ms                                                               | 73.0 ms: 1.12x slower                                             |
| unpickle                 | 14.3 us                                                               | 16.5 us: 1.16x slower                                             |
| chaos                    | 59.8 ms                                                               | 70.5 ms: 1.18x slower                                             |
| nbody                    | 89.3 ms                                                               | 105 ms: 1.18x slower                                              |
| pprint_safe_repr         | 719 ms                                                                | 855 ms: 1.19x slower                                              |
| nqueens                  | 78.9 ms                                                               | 94.6 ms: 1.20x slower                                             |
| comprehensions           | 20.2 us                                                               | 24.3 us: 1.20x slower                                             |
| pprint_pformat           | 1.46 sec                                                              | 1.79 sec: 1.22x slower                                            |
| hexiom                   | 5.97 ms                                                               | 7.71 ms: 1.29x slower                                             |
| Geometric mean           | (ref)                                                                 | 1.04x slower                                                      |

Benchmark hidden because not significant (7): richards_super, logging_silent, pickle_pure_python, bench_mp_pool, xml_etree_process, richards, json


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
