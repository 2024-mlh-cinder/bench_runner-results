
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.66 sec: 1.02x slower                                      |
| tornado_http   | 87.7 ms                                                     | 90.6 ms: 1.03x slower                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                        |
| float          | 55.1 ms                                                     | 58.0 ms: 1.05x slower                                       |
| nbody          | 72.6 ms                                                     | 83.3 ms: 1.15x slower                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 121 ms: 1.03x faster                                        |
| regex_effbot   | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                       |
| regex_compile  | 88.3 ms                                                     | 93.6 ms: 1.06x slower                                       |
| regex_v8       | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.60 us: 1.07x faster                                       |
| pickle_dict          | 19.3 us                                                     | 18.1 us: 1.06x faster                                       |
| pickle               | 7.13 us                                                     | 6.92 us: 1.03x faster                                       |
| pickle_list          | 2.86 us                                                     | 2.80 us: 1.02x faster                                       |
| pickle_pure_python   | 196 us                                                      | 193 us: 1.01x faster                                        |
| unpickle             | 8.16 us                                                     | 8.05 us: 1.01x faster                                       |
| xml_etree_generate   | 55.6 ms                                                     | 56.3 ms: 1.01x slower                                       |
| json_dumps           | 5.60 ms                                                     | 5.70 ms: 1.02x slower                                       |
| json_loads           | 13.4 us                                                     | 13.9 us: 1.03x slower                                       |
| xml_etree_process    | 38.4 ms                                                     | 39.8 ms: 1.04x slower                                       |
| xml_etree_parse      | 89.2 ms                                                     | 92.7 ms: 1.04x slower                                       |
| xml_etree_iterparse  | 62.5 ms                                                     | 65.7 ms: 1.05x slower                                       |
| unpickle_pure_python | 133 us                                                      | 141 us: 1.06x slower                                        |
| tomli_loads          | 1.37 sec                                                    | 1.56 sec: 1.14x slower                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                |

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.69 ms: 1.11x slower                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-pythonperf1-amd64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 44.6 ms: 1.15x faster                                       |
| sqlite_synth             | 1.76 us                                                     | 1.58 us: 1.11x faster                                       |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.84 sec: 1.07x faster                                      |
| unpickle_list            | 2.78 us                                                     | 2.60 us: 1.07x faster                                       |
| pickle_dict              | 19.3 us                                                     | 18.1 us: 1.06x faster                                       |
| crypto_pyaes             | 47.4 ms                                                     | 44.7 ms: 1.06x faster                                       |
| async_tree_none          | 294 ms                                                      | 281 ms: 1.04x faster                                        |
| bench_mp_pool            | 66.4 ms                                                     | 64.3 ms: 1.03x faster                                       |
| pickle                   | 7.13 us                                                     | 6.92 us: 1.03x faster                                       |
| regex_dna                | 124 ms                                                      | 121 ms: 1.03x faster                                        |
| pickle_list              | 2.86 us                                                     | 2.80 us: 1.02x faster                                       |
| regex_effbot             | 1.62 ms                                                     | 1.59 ms: 1.02x faster                                       |
| pidigits                 | 150 ms                                                      | 147 ms: 1.02x faster                                        |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 468 ms: 1.02x faster                                        |
| unpack_sequence          | 37.5 ns                                                     | 36.7 ns: 1.02x faster                                       |
| raytrace                 | 191 ms                                                      | 188 ms: 1.02x faster                                        |
| scimark_monte_carlo      | 43.7 ms                                                     | 42.9 ms: 1.02x faster                                       |
| pickle_pure_python       | 196 us                                                      | 193 us: 1.01x faster                                        |
| unpickle                 | 8.16 us                                                     | 8.05 us: 1.01x faster                                       |
| pprint_safe_repr         | 512 ms                                                      | 517 ms: 1.01x slower                                        |
| xml_etree_generate       | 55.6 ms                                                     | 56.3 ms: 1.01x slower                                       |
| meteor_contest           | 73.1 ms                                                     | 74.2 ms: 1.01x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                      |
| docutils                 | 1.63 sec                                                    | 1.66 sec: 1.02x slower                                      |
| scimark_fft              | 180 ms                                                      | 183 ms: 1.02x slower                                        |
| typing_runtime_protocols | 95.2 us                                                     | 96.8 us: 1.02x slower                                       |
| json_dumps               | 5.60 ms                                                     | 5.70 ms: 1.02x slower                                       |
| chaos                    | 42.8 ms                                                     | 43.6 ms: 1.02x slower                                       |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.02x slower                                       |
| mdp                      | 1.44 sec                                                    | 1.48 sec: 1.03x slower                                      |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.55 ms: 1.03x slower                                       |
| spectral_norm            | 63.2 ms                                                     | 65.1 ms: 1.03x slower                                       |
| pathlib                  | 77.1 ms                                                     | 79.6 ms: 1.03x slower                                       |
| tornado_http             | 87.7 ms                                                     | 90.6 ms: 1.03x slower                                       |
| json_loads               | 13.4 us                                                     | 13.9 us: 1.03x slower                                       |
| xml_etree_process        | 38.4 ms                                                     | 39.8 ms: 1.04x slower                                       |
| scimark_lu               | 58.1 ms                                                     | 60.3 ms: 1.04x slower                                       |
| sqlglot_normalize        | 185 ms                                                      | 192 ms: 1.04x slower                                        |
| xml_etree_parse          | 89.2 ms                                                     | 92.7 ms: 1.04x slower                                       |
| asyncio_tcp              | 472 ms                                                      | 490 ms: 1.04x slower                                        |
| scimark_sor              | 79.6 ms                                                     | 82.9 ms: 1.04x slower                                       |
| nqueens                  | 61.2 ms                                                     | 63.8 ms: 1.04x slower                                       |
| deepcopy                 | 240 us                                                      | 251 us: 1.05x slower                                        |
| pyflate                  | 297 ms                                                      | 312 ms: 1.05x slower                                        |
| deepcopy_reduce          | 2.13 us                                                     | 2.24 us: 1.05x slower                                       |
| xml_etree_iterparse      | 62.5 ms                                                     | 65.7 ms: 1.05x slower                                       |
| float                    | 55.1 ms                                                     | 58.0 ms: 1.05x slower                                       |
| sqlglot_parse            | 820 us                                                      | 863 us: 1.05x slower                                        |
| async_tree_io            | 720 ms                                                      | 759 ms: 1.05x slower                                        |
| async_generators         | 235 ms                                                      | 248 ms: 1.05x slower                                        |
| sqlglot_transpile        | 1.04 ms                                                     | 1.09 ms: 1.05x slower                                       |
| unpickle_pure_python     | 133 us                                                      | 141 us: 1.06x slower                                        |
| regex_compile            | 88.3 ms                                                     | 93.6 ms: 1.06x slower                                       |
| sqlglot_optimize         | 34.4 ms                                                     | 36.5 ms: 1.06x slower                                       |
| async_tree_memoization   | 336 ms                                                      | 357 ms: 1.06x slower                                        |
| logging_format           | 6.67 us                                                     | 7.10 us: 1.06x slower                                       |
| mypy2                    | 207 ms                                                      | 221 ms: 1.07x slower                                        |
| logging_simple           | 6.21 us                                                     | 6.63 us: 1.07x slower                                       |
| fannkuch                 | 237 ms                                                      | 253 ms: 1.07x slower                                        |
| comprehensions           | 14.1 us                                                     | 15.1 us: 1.07x slower                                       |
| regex_v8                 | 13.9 ms                                                     | 15.0 ms: 1.08x slower                                       |
| dulwich_log              | 42.4 ms                                                     | 46.0 ms: 1.08x slower                                       |
| go                       | 88.5 ms                                                     | 96.8 ms: 1.09x slower                                       |
| hexiom                   | 4.03 ms                                                     | 4.42 ms: 1.10x slower                                       |
| deepcopy_memo            | 23.8 us                                                     | 26.3 us: 1.11x slower                                       |
| mako                     | 6.93 ms                                                     | 7.69 ms: 1.11x slower                                       |
| richards_super           | 30.5 ms                                                     | 33.8 ms: 1.11x slower                                       |
| deltablue                | 2.14 ms                                                     | 2.37 ms: 1.11x slower                                       |
| coroutines               | 14.0 ms                                                     | 15.6 ms: 1.11x slower                                       |
| generators               | 22.7 ms                                                     | 25.4 ms: 1.12x slower                                       |
| richards                 | 26.9 ms                                                     | 30.2 ms: 1.12x slower                                       |
| tomli_loads              | 1.37 sec                                                    | 1.56 sec: 1.14x slower                                      |
| logging_silent           | 60.6 ns                                                     | 69.4 ns: 1.15x slower                                       |
| nbody                    | 72.6 ms                                                     | 83.3 ms: 1.15x slower                                       |
| telco                    | 4.09 ms                                                     | 4.84 ms: 1.18x slower                                       |
| pycparser                | 673 ms                                                      | 864 ms: 1.28x slower                                        |
| Geometric mean           | (ref)                                                       | 1.03x slower                                                |

Benchmark hidden because not significant (5): create_gc_cycles, python_startup_no_site, bench_thread_pool, python_startup, json
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
