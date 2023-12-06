
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.01x slower
- HPT reliability: 92.81%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                     |
| tornado_http   | 87.7 ms                                                     | 88.4 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 55.1 ms                                                     | 54.4 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                               |

Benchmark hidden because not significant (2): nbody, pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 120 ms: 1.03x faster                                       |
| regex_effbot   | 1.62 ms                                                     | 1.60 ms: 1.01x faster                                      |
| regex_compile  | 88.3 ms                                                     | 89.1 ms: 1.01x slower                                      |
| regex_v8       | 13.9 ms                                                     | 15.7 ms: 1.13x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.63 us: 1.06x faster                                      |
| pickle_dict          | 19.3 us                                                     | 18.4 us: 1.05x faster                                      |
| pickle_pure_python   | 196 us                                                      | 190 us: 1.03x faster                                       |
| xml_etree_process    | 38.4 ms                                                     | 38.2 ms: 1.01x faster                                      |
| pickle               | 7.13 us                                                     | 7.10 us: 1.00x faster                                      |
| unpickle_pure_python | 133 us                                                      | 134 us: 1.01x slower                                       |
| json_loads           | 13.4 us                                                     | 13.7 us: 1.02x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.1 ms: 1.02x slower                                      |
| json_dumps           | 5.60 ms                                                     | 5.76 ms: 1.03x slower                                      |
| unpickle             | 8.16 us                                                     | 8.40 us: 1.03x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 91.8 ms: 1.03x slower                                      |
| tomli_loads          | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| pickle_list          | 2.86 us                                                     | 3.21 us: 1.12x slower                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup | 19.5 ms                                                     | 19.6 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.33 ms: 1.06x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230930-pythonperf1-amd64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| raytrace                 | 191 ms                                                      | 174 ms: 1.10x faster                                       |
| coverage                 | 51.5 ms                                                     | 46.9 ms: 1.10x faster                                      |
| async_tree_none          | 294 ms                                                      | 269 ms: 1.09x faster                                       |
| scimark_monte_carlo      | 43.7 ms                                                     | 40.6 ms: 1.08x faster                                      |
| chaos                    | 42.8 ms                                                     | 40.4 ms: 1.06x faster                                      |
| unpickle_list            | 2.78 us                                                     | 2.63 us: 1.06x faster                                      |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.86 sec: 1.06x faster                                     |
| crypto_pyaes             | 47.4 ms                                                     | 45.0 ms: 1.05x faster                                      |
| pickle_dict              | 19.3 us                                                     | 18.4 us: 1.05x faster                                      |
| deepcopy                 | 240 us                                                      | 231 us: 1.04x faster                                       |
| scimark_sor              | 79.6 ms                                                     | 76.8 ms: 1.04x faster                                      |
| deepcopy_reduce          | 2.13 us                                                     | 2.06 us: 1.03x faster                                      |
| regex_dna                | 124 ms                                                      | 120 ms: 1.03x faster                                       |
| pickle_pure_python       | 196 us                                                      | 190 us: 1.03x faster                                       |
| scimark_fft              | 180 ms                                                      | 175 ms: 1.03x faster                                       |
| docutils                 | 1.63 sec                                                    | 1.60 sec: 1.02x faster                                     |
| nqueens                  | 61.2 ms                                                     | 60.2 ms: 1.02x faster                                      |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 471 ms: 1.02x faster                                       |
| typing_runtime_protocols | 95.2 us                                                     | 93.7 us: 1.02x faster                                      |
| regex_effbot             | 1.62 ms                                                     | 1.60 ms: 1.01x faster                                      |
| float                    | 55.1 ms                                                     | 54.4 ms: 1.01x faster                                      |
| sqlglot_normalize        | 185 ms                                                      | 183 ms: 1.01x faster                                       |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.45 ms: 1.01x faster                                      |
| sqlglot_parse            | 820 us                                                      | 810 us: 1.01x faster                                       |
| sqlite_synth             | 1.76 us                                                     | 1.75 us: 1.01x faster                                      |
| sqlglot_transpile        | 1.04 ms                                                     | 1.03 ms: 1.01x faster                                      |
| xml_etree_process        | 38.4 ms                                                     | 38.2 ms: 1.01x faster                                      |
| comprehensions           | 14.1 us                                                     | 14.1 us: 1.00x faster                                      |
| pickle                   | 7.13 us                                                     | 7.10 us: 1.00x faster                                      |
| async_generators         | 235 ms                                                      | 236 ms: 1.00x slower                                       |
| meteor_contest           | 73.1 ms                                                     | 73.4 ms: 1.00x slower                                      |
| unpickle_pure_python     | 133 us                                                      | 134 us: 1.01x slower                                       |
| pyflate                  | 297 ms                                                      | 299 ms: 1.01x slower                                       |
| mdp                      | 1.44 sec                                                    | 1.46 sec: 1.01x slower                                     |
| tornado_http             | 87.7 ms                                                     | 88.4 ms: 1.01x slower                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 34.7 ms: 1.01x slower                                      |
| regex_compile            | 88.3 ms                                                     | 89.1 ms: 1.01x slower                                      |
| python_startup           | 19.5 ms                                                     | 19.6 ms: 1.01x slower                                      |
| go                       | 88.5 ms                                                     | 89.5 ms: 1.01x slower                                      |
| json                     | 2.86 ms                                                     | 2.90 ms: 1.01x slower                                      |
| pprint_safe_repr         | 512 ms                                                      | 519 ms: 1.01x slower                                       |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.01x slower                                     |
| json_loads               | 13.4 us                                                     | 13.7 us: 1.02x slower                                      |
| pathlib                  | 77.1 ms                                                     | 78.7 ms: 1.02x slower                                      |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.02x slower                                      |
| generators               | 22.7 ms                                                     | 23.2 ms: 1.02x slower                                      |
| deltablue                | 2.14 ms                                                     | 2.19 ms: 1.02x slower                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.1 ms: 1.02x slower                                      |
| async_tree_memoization   | 336 ms                                                      | 344 ms: 1.02x slower                                       |
| hexiom                   | 4.03 ms                                                     | 4.13 ms: 1.03x slower                                      |
| logging_format           | 6.67 us                                                     | 6.85 us: 1.03x slower                                      |
| mypy2                    | 207 ms                                                      | 213 ms: 1.03x slower                                       |
| json_dumps               | 5.60 ms                                                     | 5.76 ms: 1.03x slower                                      |
| unpickle                 | 8.16 us                                                     | 8.40 us: 1.03x slower                                      |
| xml_etree_parse          | 89.2 ms                                                     | 91.8 ms: 1.03x slower                                      |
| unpack_sequence          | 37.5 ns                                                     | 38.6 ns: 1.03x slower                                      |
| bench_mp_pool            | 66.4 ms                                                     | 68.6 ms: 1.03x slower                                      |
| logging_simple           | 6.21 us                                                     | 6.44 us: 1.04x slower                                      |
| richards_super           | 30.5 ms                                                     | 31.7 ms: 1.04x slower                                      |
| fannkuch                 | 237 ms                                                      | 246 ms: 1.04x slower                                       |
| coroutines               | 14.0 ms                                                     | 14.6 ms: 1.05x slower                                      |
| logging_silent           | 60.6 ns                                                     | 63.5 ns: 1.05x slower                                      |
| richards                 | 26.9 ms                                                     | 28.4 ms: 1.06x slower                                      |
| mako                     | 6.93 ms                                                     | 7.33 ms: 1.06x slower                                      |
| dulwich_log              | 42.4 ms                                                     | 44.9 ms: 1.06x slower                                      |
| tomli_loads              | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| pickle_list              | 2.86 us                                                     | 3.21 us: 1.12x slower                                      |
| regex_v8                 | 13.9 ms                                                     | 15.7 ms: 1.13x slower                                      |
| pycparser                | 673 ms                                                      | 775 ms: 1.15x slower                                       |
| telco                    | 4.09 ms                                                     | 4.91 ms: 1.20x slower                                      |
| Geometric mean           | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (11): asyncio_tcp, scimark_lu, nbody, pidigits, xml_etree_generate, bench_thread_pool, spectral_norm, deepcopy_memo, async_tree_io, create_gc_cycles, python_startup_no_site
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 92.81% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
