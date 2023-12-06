
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin_os
- machine: windows-amd64
- commit hash: 24495fb
- commit date: 2023-10-13
- overall geometric mean: 1.12x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                                |
| tornado_http   | 87.7 ms                                                     | 92.9 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                       | 1.05x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.00x slower                                                  |
| float          | 55.1 ms                                                     | 55.6 ms: 1.01x slower                                                 |
| nbody          | 72.6 ms                                                     | 87.3 ms: 1.20x slower                                                 |
| Geometric mean | (ref)                                                       | 1.07x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.67 ms: 1.03x slower                                                 |
| regex_compile  | 88.3 ms                                                     | 99.7 ms: 1.13x slower                                                 |
| regex_v8       | 13.9 ms                                                     | 18.8 ms: 1.35x slower                                                 |
| Geometric mean | (ref)                                                       | 1.12x slower                                                          |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.67 us: 1.04x faster                                                 |
| pickle_dict          | 19.3 us                                                     | 18.8 us: 1.02x faster                                                 |
| pickle               | 7.13 us                                                     | 7.08 us: 1.01x faster                                                 |
| unpickle             | 8.16 us                                                     | 8.10 us: 1.01x faster                                                 |
| pickle_list          | 2.86 us                                                     | 2.88 us: 1.01x slower                                                 |
| json_loads           | 13.4 us                                                     | 13.7 us: 1.02x slower                                                 |
| xml_etree_parse      | 89.2 ms                                                     | 92.6 ms: 1.04x slower                                                 |
| xml_etree_iterparse  | 62.5 ms                                                     | 67.8 ms: 1.09x slower                                                 |
| json_dumps           | 5.60 ms                                                     | 6.11 ms: 1.09x slower                                                 |
| tomli_loads          | 1.37 sec                                                    | 1.50 sec: 1.09x slower                                                |
| xml_etree_generate   | 55.6 ms                                                     | 62.3 ms: 1.12x slower                                                 |
| pickle_pure_python   | 196 us                                                      | 227 us: 1.16x slower                                                  |
| xml_etree_process    | 38.4 ms                                                     | 44.7 ms: 1.16x slower                                                 |
| unpickle_pure_python | 133 us                                                      | 173 us: 1.30x slower                                                  |
| Geometric mean       | (ref)                                                       | 1.07x slower                                                          |

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.74 ms: 1.03x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231013-pythonperf1-amd64-brandtbucher-justin_os-3.13.0a0-24495fb |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 45.5 ms: 1.13x faster                                                 |
| unpickle_list            | 2.78 us                                                     | 2.67 us: 1.04x faster                                                 |
| mako                     | 6.93 ms                                                     | 6.74 ms: 1.03x faster                                                 |
| sqlite_synth             | 1.76 us                                                     | 1.71 us: 1.02x faster                                                 |
| pickle_dict              | 19.3 us                                                     | 18.8 us: 1.02x faster                                                 |
| pickle                   | 7.13 us                                                     | 7.08 us: 1.01x faster                                                 |
| unpickle                 | 8.16 us                                                     | 8.10 us: 1.01x faster                                                 |
| bench_mp_pool            | 66.4 ms                                                     | 66.0 ms: 1.01x faster                                                 |
| pidigits                 | 150 ms                                                      | 151 ms: 1.00x slower                                                  |
| pickle_list              | 2.86 us                                                     | 2.88 us: 1.01x slower                                                 |
| gc_traversal             | 1.48 ms                                                     | 1.50 ms: 1.01x slower                                                 |
| float                    | 55.1 ms                                                     | 55.6 ms: 1.01x slower                                                 |
| json_loads               | 13.4 us                                                     | 13.7 us: 1.02x slower                                                 |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.52 ms: 1.02x slower                                                 |
| pathlib                  | 77.1 ms                                                     | 79.1 ms: 1.03x slower                                                 |
| regex_effbot             | 1.62 ms                                                     | 1.67 ms: 1.03x slower                                                 |
| asyncio_tcp              | 472 ms                                                      | 488 ms: 1.04x slower                                                  |
| xml_etree_parse          | 89.2 ms                                                     | 92.6 ms: 1.04x slower                                                 |
| json                     | 2.86 ms                                                     | 2.97 ms: 1.04x slower                                                 |
| docutils                 | 1.63 sec                                                    | 1.70 sec: 1.04x slower                                                |
| bench_thread_pool        | 844 us                                                      | 879 us: 1.04x slower                                                  |
| mdp                      | 1.44 sec                                                    | 1.53 sec: 1.06x slower                                                |
| tornado_http             | 87.7 ms                                                     | 92.9 ms: 1.06x slower                                                 |
| crypto_pyaes             | 47.4 ms                                                     | 50.9 ms: 1.07x slower                                                 |
| async_tree_io            | 720 ms                                                      | 773 ms: 1.07x slower                                                  |
| typing_runtime_protocols | 95.2 us                                                     | 103 us: 1.08x slower                                                  |
| xml_etree_iterparse      | 62.5 ms                                                     | 67.8 ms: 1.09x slower                                                 |
| dulwich_log              | 42.4 ms                                                     | 46.1 ms: 1.09x slower                                                 |
| json_dumps               | 5.60 ms                                                     | 6.11 ms: 1.09x slower                                                 |
| tomli_loads              | 1.37 sec                                                    | 1.50 sec: 1.09x slower                                                |
| nqueens                  | 61.2 ms                                                     | 67.0 ms: 1.09x slower                                                 |
| async_tree_memoization   | 336 ms                                                      | 368 ms: 1.10x slower                                                  |
| meteor_contest           | 73.1 ms                                                     | 80.3 ms: 1.10x slower                                                 |
| deepcopy_reduce          | 2.13 us                                                     | 2.36 us: 1.11x slower                                                 |
| mypy2                    | 207 ms                                                      | 230 ms: 1.11x slower                                                  |
| raytrace                 | 191 ms                                                      | 213 ms: 1.11x slower                                                  |
| xml_etree_generate       | 55.6 ms                                                     | 62.3 ms: 1.12x slower                                                 |
| sqlglot_normalize        | 185 ms                                                      | 209 ms: 1.12x slower                                                  |
| logging_format           | 6.67 us                                                     | 7.53 us: 1.13x slower                                                 |
| regex_compile            | 88.3 ms                                                     | 99.7 ms: 1.13x slower                                                 |
| sqlglot_optimize         | 34.4 ms                                                     | 39.0 ms: 1.13x slower                                                 |
| scimark_fft              | 180 ms                                                      | 205 ms: 1.14x slower                                                  |
| logging_simple           | 6.21 us                                                     | 7.09 us: 1.14x slower                                                 |
| deepcopy                 | 240 us                                                      | 275 us: 1.14x slower                                                  |
| fannkuch                 | 237 ms                                                      | 272 ms: 1.15x slower                                                  |
| async_generators         | 235 ms                                                      | 270 ms: 1.15x slower                                                  |
| pprint_pformat           | 1.04 sec                                                    | 1.21 sec: 1.15x slower                                                |
| pyflate                  | 297 ms                                                      | 343 ms: 1.16x slower                                                  |
| pycparser                | 673 ms                                                      | 780 ms: 1.16x slower                                                  |
| pickle_pure_python       | 196 us                                                      | 227 us: 1.16x slower                                                  |
| pprint_safe_repr         | 512 ms                                                      | 594 ms: 1.16x slower                                                  |
| chaos                    | 42.8 ms                                                     | 49.7 ms: 1.16x slower                                                 |
| xml_etree_process        | 38.4 ms                                                     | 44.7 ms: 1.16x slower                                                 |
| comprehensions           | 14.1 us                                                     | 16.7 us: 1.18x slower                                                 |
| telco                    | 4.09 ms                                                     | 4.84 ms: 1.18x slower                                                 |
| sqlglot_transpile        | 1.04 ms                                                     | 1.23 ms: 1.18x slower                                                 |
| scimark_monte_carlo      | 43.7 ms                                                     | 52.0 ms: 1.19x slower                                                 |
| nbody                    | 72.6 ms                                                     | 87.3 ms: 1.20x slower                                                 |
| sqlglot_parse            | 820 us                                                      | 990 us: 1.21x slower                                                  |
| spectral_norm            | 63.2 ms                                                     | 80.2 ms: 1.27x slower                                                 |
| hexiom                   | 4.03 ms                                                     | 5.13 ms: 1.27x slower                                                 |
| go                       | 88.5 ms                                                     | 113 ms: 1.28x slower                                                  |
| richards_super           | 30.5 ms                                                     | 39.2 ms: 1.29x slower                                                 |
| scimark_lu               | 58.1 ms                                                     | 75.0 ms: 1.29x slower                                                 |
| scimark_sor              | 79.6 ms                                                     | 103 ms: 1.30x slower                                                  |
| unpickle_pure_python     | 133 us                                                      | 173 us: 1.30x slower                                                  |
| unpack_sequence          | 37.5 ns                                                     | 48.8 ns: 1.30x slower                                                 |
| deepcopy_memo            | 23.8 us                                                     | 31.4 us: 1.32x slower                                                 |
| richards                 | 26.9 ms                                                     | 35.7 ms: 1.33x slower                                                 |
| deltablue                | 2.14 ms                                                     | 2.86 ms: 1.34x slower                                                 |
| coroutines               | 14.0 ms                                                     | 18.8 ms: 1.34x slower                                                 |
| regex_v8                 | 13.9 ms                                                     | 18.8 ms: 1.35x slower                                                 |
| generators               | 22.7 ms                                                     | 34.0 ms: 1.49x slower                                                 |
| logging_silent           | 60.6 ns                                                     | 92.7 ns: 1.53x slower                                                 |
| Geometric mean           | (ref)                                                       | 1.12x slower                                                          |

Benchmark hidden because not significant (7): asyncio_tcp_ssl, async_tree_none, python_startup_no_site, async_tree_cpu_io_mixed, create_gc_cycles, regex_dna, python_startup
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.08x
- 95% likely to have a slowdown of 1.08x
- 99% likely to have a slowdown of 1.07x
