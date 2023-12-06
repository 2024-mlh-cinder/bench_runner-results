
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.10x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.70 sec: 1.05x slower                                              |
| tornado_http   | 87.7 ms                                                     | 91.1 ms: 1.04x slower                                               |
| Geometric mean | (ref)                                                       | 1.04x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 52.0 ms: 1.06x faster                                               |
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                                |
| nbody          | 72.6 ms                                                     | 81.7 ms: 1.13x slower                                               |
| Geometric mean | (ref)                                                       | 1.02x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 119 ms: 1.05x faster                                                |
| regex_effbot   | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                               |
| regex_compile  | 88.3 ms                                                     | 95.7 ms: 1.08x slower                                               |
| regex_v8       | 13.9 ms                                                     | 21.4 ms: 1.54x slower                                               |
| Geometric mean | (ref)                                                       | 1.12x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.71 us: 1.03x faster                                               |
| pickle               | 7.13 us                                                     | 7.04 us: 1.01x faster                                               |
| tomli_loads          | 1.37 sec                                                    | 1.38 sec: 1.01x slower                                              |
| json_loads           | 13.4 us                                                     | 13.7 us: 1.02x slower                                               |
| xml_etree_parse      | 89.2 ms                                                     | 92.5 ms: 1.04x slower                                               |
| json_dumps           | 5.60 ms                                                     | 5.98 ms: 1.07x slower                                               |
| xml_etree_iterparse  | 62.5 ms                                                     | 68.1 ms: 1.09x slower                                               |
| xml_etree_generate   | 55.6 ms                                                     | 62.2 ms: 1.12x slower                                               |
| pickle_pure_python   | 196 us                                                      | 227 us: 1.16x slower                                                |
| xml_etree_process    | 38.4 ms                                                     | 44.8 ms: 1.17x slower                                               |
| unpickle_pure_python | 133 us                                                      | 170 us: 1.28x slower                                                |
| Geometric mean       | (ref)                                                       | 1.06x slower                                                        |

Benchmark hidden because not significant (3): pickle_dict, pickle_list, unpickle

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup_no_site, python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.39 ms: 1.09x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 45.8 ms: 1.13x faster                                               |
| mako                     | 6.93 ms                                                     | 6.39 ms: 1.09x faster                                               |
| float                    | 55.1 ms                                                     | 52.0 ms: 1.06x faster                                               |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.34 ms: 1.06x faster                                               |
| sqlite_synth             | 1.76 us                                                     | 1.66 us: 1.05x faster                                               |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.87 sec: 1.05x faster                                              |
| regex_dna                | 124 ms                                                      | 119 ms: 1.05x faster                                                |
| unpickle_list            | 2.78 us                                                     | 2.71 us: 1.03x faster                                               |
| crypto_pyaes             | 47.4 ms                                                     | 46.6 ms: 1.02x faster                                               |
| pickle                   | 7.13 us                                                     | 7.04 us: 1.01x faster                                               |
| regex_effbot             | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                               |
| mdp                      | 1.44 sec                                                    | 1.44 sec: 1.00x faster                                              |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                                |
| tomli_loads              | 1.37 sec                                                    | 1.38 sec: 1.01x slower                                              |
| json_loads               | 13.4 us                                                     | 13.7 us: 1.02x slower                                               |
| gc_traversal             | 1.48 ms                                                     | 1.51 ms: 1.02x slower                                               |
| pathlib                  | 77.1 ms                                                     | 79.8 ms: 1.03x slower                                               |
| xml_etree_parse          | 89.2 ms                                                     | 92.5 ms: 1.04x slower                                               |
| bench_thread_pool        | 844 us                                                      | 877 us: 1.04x slower                                                |
| tornado_http             | 87.7 ms                                                     | 91.1 ms: 1.04x slower                                               |
| docutils                 | 1.63 sec                                                    | 1.70 sec: 1.05x slower                                              |
| json                     | 2.86 ms                                                     | 3.00 ms: 1.05x slower                                               |
| fannkuch                 | 237 ms                                                      | 249 ms: 1.05x slower                                                |
| meteor_contest           | 73.1 ms                                                     | 77.6 ms: 1.06x slower                                               |
| async_tree_io            | 720 ms                                                      | 767 ms: 1.06x slower                                                |
| scimark_fft              | 180 ms                                                      | 192 ms: 1.07x slower                                                |
| nqueens                  | 61.2 ms                                                     | 65.4 ms: 1.07x slower                                               |
| json_dumps               | 5.60 ms                                                     | 5.98 ms: 1.07x slower                                               |
| comprehensions           | 14.1 us                                                     | 15.3 us: 1.08x slower                                               |
| regex_compile            | 88.3 ms                                                     | 95.7 ms: 1.08x slower                                               |
| xml_etree_iterparse      | 62.5 ms                                                     | 68.1 ms: 1.09x slower                                               |
| dulwich_log              | 42.4 ms                                                     | 46.3 ms: 1.09x slower                                               |
| raytrace                 | 191 ms                                                      | 209 ms: 1.09x slower                                                |
| deltablue                | 2.14 ms                                                     | 2.34 ms: 1.09x slower                                               |
| async_tree_memoization   | 336 ms                                                      | 368 ms: 1.10x slower                                                |
| logging_format           | 6.67 us                                                     | 7.41 us: 1.11x slower                                               |
| mypy2                    | 207 ms                                                      | 230 ms: 1.11x slower                                                |
| pyflate                  | 297 ms                                                      | 331 ms: 1.11x slower                                                |
| sqlglot_normalize        | 185 ms                                                      | 207 ms: 1.12x slower                                                |
| logging_simple           | 6.21 us                                                     | 6.95 us: 1.12x slower                                               |
| pprint_pformat           | 1.04 sec                                                    | 1.17 sec: 1.12x slower                                              |
| xml_etree_generate       | 55.6 ms                                                     | 62.2 ms: 1.12x slower                                               |
| nbody                    | 72.6 ms                                                     | 81.7 ms: 1.13x slower                                               |
| pprint_safe_repr         | 512 ms                                                      | 577 ms: 1.13x slower                                                |
| typing_runtime_protocols | 95.2 us                                                     | 107 us: 1.13x slower                                                |
| deepcopy_reduce          | 2.13 us                                                     | 2.41 us: 1.13x slower                                               |
| sqlglot_optimize         | 34.4 ms                                                     | 38.9 ms: 1.13x slower                                               |
| hexiom                   | 4.03 ms                                                     | 4.58 ms: 1.13x slower                                               |
| chaos                    | 42.8 ms                                                     | 48.6 ms: 1.14x slower                                               |
| telco                    | 4.09 ms                                                     | 4.69 ms: 1.15x slower                                               |
| scimark_monte_carlo      | 43.7 ms                                                     | 50.1 ms: 1.15x slower                                               |
| deepcopy                 | 240 us                                                      | 277 us: 1.15x slower                                                |
| pickle_pure_python       | 196 us                                                      | 227 us: 1.16x slower                                                |
| async_generators         | 235 ms                                                      | 274 ms: 1.16x slower                                                |
| xml_etree_process        | 38.4 ms                                                     | 44.8 ms: 1.17x slower                                               |
| sqlglot_transpile        | 1.04 ms                                                     | 1.22 ms: 1.18x slower                                               |
| sqlglot_parse            | 820 us                                                      | 979 us: 1.19x slower                                                |
| pycparser                | 673 ms                                                      | 808 ms: 1.20x slower                                                |
| go                       | 88.5 ms                                                     | 109 ms: 1.23x slower                                                |
| richards_super           | 30.5 ms                                                     | 38.4 ms: 1.26x slower                                               |
| spectral_norm            | 63.2 ms                                                     | 80.1 ms: 1.27x slower                                               |
| deepcopy_memo            | 23.8 us                                                     | 30.2 us: 1.27x slower                                               |
| unpickle_pure_python     | 133 us                                                      | 170 us: 1.28x slower                                                |
| richards                 | 26.9 ms                                                     | 34.5 ms: 1.28x slower                                               |
| unpack_sequence          | 37.5 ns                                                     | 48.4 ns: 1.29x slower                                               |
| scimark_lu               | 58.1 ms                                                     | 75.3 ms: 1.30x slower                                               |
| scimark_sor              | 79.6 ms                                                     | 105 ms: 1.31x slower                                                |
| coroutines               | 14.0 ms                                                     | 19.4 ms: 1.39x slower                                               |
| generators               | 22.7 ms                                                     | 33.5 ms: 1.47x slower                                               |
| logging_silent           | 60.6 ns                                                     | 92.1 ns: 1.52x slower                                               |
| regex_v8                 | 13.9 ms                                                     | 21.4 ms: 1.54x slower                                               |
| Geometric mean           | (ref)                                                       | 1.10x slower                                                        |

Benchmark hidden because not significant (10): pickle_dict, async_tree_none, async_tree_cpu_io_mixed, python_startup_no_site, bench_mp_pool, pickle_list, unpickle, create_gc_cycles, python_startup, asyncio_tcp
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
