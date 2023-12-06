
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.63 sec: 1.00x faster                                     |
| tornado_http   | 87.7 ms                                                     | 90.2 ms: 1.03x slower                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                       |
| float          | 55.1 ms                                                     | 55.6 ms: 1.01x slower                                      |
| nbody          | 72.6 ms                                                     | 76.5 ms: 1.05x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 120 ms: 1.04x faster                                       |
| regex_effbot   | 1.62 ms                                                     | 1.57 ms: 1.04x faster                                      |
| regex_compile  | 88.3 ms                                                     | 92.2 ms: 1.04x slower                                      |
| regex_v8       | 13.9 ms                                                     | 15.2 ms: 1.09x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.68 us: 1.04x faster                                      |
| pickle_pure_python   | 196 us                                                      | 190 us: 1.03x faster                                       |
| pickle_dict          | 19.3 us                                                     | 18.7 us: 1.03x faster                                      |
| pickle               | 7.13 us                                                     | 7.08 us: 1.01x faster                                      |
| xml_etree_process    | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                      |
| unpickle_pure_python | 133 us                                                      | 135 us: 1.01x slower                                       |
| xml_etree_parse      | 89.2 ms                                                     | 90.4 ms: 1.01x slower                                      |
| pickle_list          | 2.86 us                                                     | 2.95 us: 1.03x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.7 ms: 1.03x slower                                      |
| unpickle             | 8.16 us                                                     | 8.47 us: 1.04x slower                                      |
| tomli_loads          | 1.37 sec                                                    | 1.52 sec: 1.11x slower                                     |
| Geometric mean       | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (3): json_loads, json_dumps, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup | 19.5 ms                                                     | 20.2 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.45 ms: 1.07x slower                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.2 ms: 1.12x faster                                      |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.76 sec: 1.12x faster                                     |
| raytrace                 | 191 ms                                                      | 177 ms: 1.08x faster                                       |
| async_tree_none          | 294 ms                                                      | 275 ms: 1.07x faster                                       |
| crypto_pyaes             | 47.4 ms                                                     | 45.0 ms: 1.05x faster                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 41.5 ms: 1.05x faster                                      |
| unpickle_list            | 2.78 us                                                     | 2.68 us: 1.04x faster                                      |
| regex_dna                | 124 ms                                                      | 120 ms: 1.04x faster                                       |
| regex_effbot             | 1.62 ms                                                     | 1.57 ms: 1.04x faster                                      |
| pickle_pure_python       | 196 us                                                      | 190 us: 1.03x faster                                       |
| pickle_dict              | 19.3 us                                                     | 18.7 us: 1.03x faster                                      |
| chaos                    | 42.8 ms                                                     | 41.9 ms: 1.02x faster                                      |
| typing_runtime_protocols | 95.2 us                                                     | 93.6 us: 1.02x faster                                      |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.45 ms: 1.01x faster                                      |
| json                     | 2.86 ms                                                     | 2.84 ms: 1.01x faster                                      |
| pickle                   | 7.13 us                                                     | 7.08 us: 1.01x faster                                      |
| xml_etree_process        | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                      |
| docutils                 | 1.63 sec                                                    | 1.63 sec: 1.00x faster                                     |
| sqlite_synth             | 1.76 us                                                     | 1.75 us: 1.00x faster                                      |
| scimark_lu               | 58.1 ms                                                     | 58.4 ms: 1.00x slower                                      |
| mdp                      | 1.44 sec                                                    | 1.45 sec: 1.01x slower                                     |
| pprint_safe_repr         | 512 ms                                                      | 515 ms: 1.01x slower                                       |
| nqueens                  | 61.2 ms                                                     | 61.6 ms: 1.01x slower                                      |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                       |
| float                    | 55.1 ms                                                     | 55.6 ms: 1.01x slower                                      |
| deepcopy_reduce          | 2.13 us                                                     | 2.15 us: 1.01x slower                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.01x slower                                     |
| unpickle_pure_python     | 133 us                                                      | 135 us: 1.01x slower                                       |
| xml_etree_parse          | 89.2 ms                                                     | 90.4 ms: 1.01x slower                                      |
| spectral_norm            | 63.2 ms                                                     | 64.1 ms: 1.02x slower                                      |
| create_gc_cycles         | 727 us                                                      | 739 us: 1.02x slower                                       |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.02x slower                                      |
| bench_mp_pool            | 66.4 ms                                                     | 67.7 ms: 1.02x slower                                      |
| meteor_contest           | 73.1 ms                                                     | 74.5 ms: 1.02x slower                                      |
| deepcopy_memo            | 23.8 us                                                     | 24.4 us: 1.03x slower                                      |
| pathlib                  | 77.1 ms                                                     | 79.3 ms: 1.03x slower                                      |
| generators               | 22.7 ms                                                     | 23.4 ms: 1.03x slower                                      |
| pyflate                  | 297 ms                                                      | 305 ms: 1.03x slower                                       |
| tornado_http             | 87.7 ms                                                     | 90.2 ms: 1.03x slower                                      |
| pickle_list              | 2.86 us                                                     | 2.95 us: 1.03x slower                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 35.5 ms: 1.03x slower                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.7 ms: 1.03x slower                                      |
| asyncio_tcp              | 472 ms                                                      | 489 ms: 1.04x slower                                       |
| sqlglot_transpile        | 1.04 ms                                                     | 1.08 ms: 1.04x slower                                      |
| python_startup           | 19.5 ms                                                     | 20.2 ms: 1.04x slower                                      |
| unpickle                 | 8.16 us                                                     | 8.47 us: 1.04x slower                                      |
| sqlglot_normalize        | 185 ms                                                      | 193 ms: 1.04x slower                                       |
| async_tree_io            | 720 ms                                                      | 749 ms: 1.04x slower                                       |
| deltablue                | 2.14 ms                                                     | 2.23 ms: 1.04x slower                                      |
| fannkuch                 | 237 ms                                                      | 247 ms: 1.04x slower                                       |
| regex_compile            | 88.3 ms                                                     | 92.2 ms: 1.04x slower                                      |
| async_tree_memoization   | 336 ms                                                      | 352 ms: 1.05x slower                                       |
| async_generators         | 235 ms                                                      | 247 ms: 1.05x slower                                       |
| logging_simple           | 6.21 us                                                     | 6.53 us: 1.05x slower                                      |
| logging_silent           | 60.6 ns                                                     | 63.7 ns: 1.05x slower                                      |
| sqlglot_parse            | 820 us                                                      | 862 us: 1.05x slower                                       |
| coroutines               | 14.0 ms                                                     | 14.7 ms: 1.05x slower                                      |
| nbody                    | 72.6 ms                                                     | 76.5 ms: 1.05x slower                                      |
| mypy2                    | 207 ms                                                      | 218 ms: 1.05x slower                                       |
| logging_format           | 6.67 us                                                     | 7.06 us: 1.06x slower                                      |
| comprehensions           | 14.1 us                                                     | 15.0 us: 1.06x slower                                      |
| scimark_sor              | 79.6 ms                                                     | 84.7 ms: 1.06x slower                                      |
| hexiom                   | 4.03 ms                                                     | 4.29 ms: 1.06x slower                                      |
| richards_super           | 30.5 ms                                                     | 32.6 ms: 1.07x slower                                      |
| mako                     | 6.93 ms                                                     | 7.45 ms: 1.07x slower                                      |
| richards                 | 26.9 ms                                                     | 29.0 ms: 1.08x slower                                      |
| go                       | 88.5 ms                                                     | 95.6 ms: 1.08x slower                                      |
| dulwich_log              | 42.4 ms                                                     | 46.0 ms: 1.08x slower                                      |
| regex_v8                 | 13.9 ms                                                     | 15.2 ms: 1.09x slower                                      |
| tomli_loads              | 1.37 sec                                                    | 1.52 sec: 1.11x slower                                     |
| unpack_sequence          | 37.5 ns                                                     | 41.6 ns: 1.11x slower                                      |
| pycparser                | 673 ms                                                      | 765 ms: 1.14x slower                                       |
| telco                    | 4.09 ms                                                     | 4.81 ms: 1.18x slower                                      |
| dask                     | 259 ms                                                      | 382 ms: 1.47x slower                                       |
| Geometric mean           | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (8): json_loads, scimark_fft, json_dumps, xml_etree_generate, async_tree_cpu_io_mixed, deepcopy, bench_thread_pool, python_startup_no_site
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
