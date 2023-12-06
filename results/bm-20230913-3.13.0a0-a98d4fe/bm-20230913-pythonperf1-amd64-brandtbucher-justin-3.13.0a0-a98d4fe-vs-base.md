
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: a98d4fe
- commit date: 2023-09-13
- overall geometric mean: 1.10x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.62 sec                                                                   | 1.70 sec: 1.05x slower                                             |
| tornado_http   | 89.3 ms                                                                    | 91.7 ms: 1.03x slower                                              |
| Geometric mean | (ref)                                                                      | 1.04x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 74.6 ms                                                                    | 59.1 ms: 1.26x faster                                              |
| pidigits       | 151 ms                                                                     | 152 ms: 1.01x slower                                               |
| float          | 55.8 ms                                                                    | 65.9 ms: 1.18x slower                                              |
| Geometric mean | (ref)                                                                      | 1.02x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 118 ms                                                                     | 118 ms: 1.01x faster                                               |
| regex_effbot   | 1.57 ms                                                                    | 1.58 ms: 1.01x slower                                              |
| regex_v8       | 14.9 ms                                                                    | 15.1 ms: 1.01x slower                                              |
| regex_compile  | 90.2 ms                                                                    | 102 ms: 1.13x slower                                               |
| Geometric mean | (ref)                                                                      | 1.03x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| tomli_loads          | 1.49 sec                                                                   | 1.42 sec: 1.05x faster                                             |
| pickle               | 7.34 us                                                                    | 7.16 us: 1.03x faster                                              |
| pickle_dict          | 18.6 us                                                                    | 18.2 us: 1.02x faster                                              |
| xml_etree_parse      | 92.6 ms                                                                    | 93.6 ms: 1.01x slower                                              |
| unpickle             | 8.21 us                                                                    | 8.33 us: 1.01x slower                                              |
| unpickle_list        | 2.73 us                                                                    | 2.79 us: 1.02x slower                                              |
| json_loads           | 13.5 us                                                                    | 13.8 us: 1.02x slower                                              |
| json_dumps           | 5.64 ms                                                                    | 6.06 ms: 1.07x slower                                              |
| xml_etree_generate   | 55.8 ms                                                                    | 62.1 ms: 1.11x slower                                              |
| xml_etree_iterparse  | 64.3 ms                                                                    | 72.0 ms: 1.12x slower                                              |
| pickle_pure_python   | 193 us                                                                     | 223 us: 1.15x slower                                               |
| xml_etree_process    | 38.1 ms                                                                    | 44.8 ms: 1.17x slower                                              |
| unpickle_pure_python | 137 us                                                                     | 171 us: 1.25x slower                                               |
| Geometric mean       | (ref)                                                                      | 1.06x slower                                                       |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup | 19.8 ms                                                                    | 20.1 ms: 1.01x slower                                              |
| Geometric mean | (ref)                                                                      | 1.01x slower                                                       |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|-----------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.41 ms                                                                    | 7.80 ms: 1.05x slower                                              |

All benchmarks:
===============

| Benchmark                | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 | bm-20230913-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-a98d4fe |
|--------------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody                    | 74.6 ms                                                                    | 59.1 ms: 1.26x faster                                              |
| pycparser                | 894 ms                                                                     | 825 ms: 1.08x faster                                               |
| asyncio_tcp_ssl          | 1.84 sec                                                                   | 1.70 sec: 1.08x faster                                             |
| tomli_loads              | 1.49 sec                                                                   | 1.42 sec: 1.05x faster                                             |
| pickle                   | 7.34 us                                                                    | 7.16 us: 1.03x faster                                              |
| pickle_dict              | 18.6 us                                                                    | 18.2 us: 1.02x faster                                              |
| mdp                      | 1.47 sec                                                                   | 1.45 sec: 1.01x faster                                             |
| regex_dna                | 118 ms                                                                     | 118 ms: 1.01x faster                                               |
| regex_effbot             | 1.57 ms                                                                    | 1.58 ms: 1.01x slower                                              |
| pidigits                 | 151 ms                                                                     | 152 ms: 1.01x slower                                               |
| gc_traversal             | 1.49 ms                                                                    | 1.51 ms: 1.01x slower                                              |
| xml_etree_parse          | 92.6 ms                                                                    | 93.6 ms: 1.01x slower                                              |
| scimark_fft              | 184 ms                                                                     | 186 ms: 1.01x slower                                               |
| fannkuch                 | 261 ms                                                                     | 264 ms: 1.01x slower                                               |
| dulwich_log              | 45.6 ms                                                                    | 46.2 ms: 1.01x slower                                              |
| regex_v8                 | 14.9 ms                                                                    | 15.1 ms: 1.01x slower                                              |
| unpickle                 | 8.21 us                                                                    | 8.33 us: 1.01x slower                                              |
| python_startup           | 19.8 ms                                                                    | 20.1 ms: 1.01x slower                                              |
| pathlib                  | 78.3 ms                                                                    | 79.5 ms: 1.02x slower                                              |
| unpickle_list            | 2.73 us                                                                    | 2.79 us: 1.02x slower                                              |
| sqlite_synth             | 1.74 us                                                                    | 1.78 us: 1.02x slower                                              |
| json_loads               | 13.5 us                                                                    | 13.8 us: 1.02x slower                                              |
| tornado_http             | 89.3 ms                                                                    | 91.7 ms: 1.03x slower                                              |
| asyncio_tcp              | 471 ms                                                                     | 483 ms: 1.03x slower                                               |
| telco                    | 4.79 ms                                                                    | 4.98 ms: 1.04x slower                                              |
| typing_runtime_protocols | 99.4 us                                                                    | 104 us: 1.04x slower                                               |
| bench_mp_pool            | 67.7 ms                                                                    | 70.6 ms: 1.04x slower                                              |
| scimark_sparse_mat_mult  | 2.46 ms                                                                    | 2.58 ms: 1.05x slower                                              |
| bench_thread_pool        | 842 us                                                                     | 886 us: 1.05x slower                                               |
| mako                     | 7.41 ms                                                                    | 7.80 ms: 1.05x slower                                              |
| docutils                 | 1.62 sec                                                                   | 1.70 sec: 1.05x slower                                             |
| async_tree_cpu_io_mixed  | 471 ms                                                                     | 498 ms: 1.06x slower                                               |
| meteor_contest           | 73.6 ms                                                                    | 78.2 ms: 1.06x slower                                              |
| json_dumps               | 5.64 ms                                                                    | 6.06 ms: 1.07x slower                                              |
| async_tree_io            | 724 ms                                                                     | 778 ms: 1.07x slower                                               |
| async_tree_memoization   | 343 ms                                                                     | 371 ms: 1.08x slower                                               |
| crypto_pyaes             | 45.7 ms                                                                    | 49.6 ms: 1.09x slower                                              |
| nqueens                  | 61.0 ms                                                                    | 66.4 ms: 1.09x slower                                              |
| mypy2                    | 214 ms                                                                     | 233 ms: 1.09x slower                                               |
| async_tree_none          | 269 ms                                                                     | 294 ms: 1.09x slower                                               |
| coverage                 | 44.5 ms                                                                    | 48.9 ms: 1.10x slower                                              |
| dask                     | 370 ms                                                                     | 409 ms: 1.10x slower                                               |
| logging_format           | 6.82 us                                                                    | 7.59 us: 1.11x slower                                              |
| xml_etree_generate       | 55.8 ms                                                                    | 62.1 ms: 1.11x slower                                              |
| async_generators         | 246 ms                                                                     | 274 ms: 1.11x slower                                               |
| logging_simple           | 6.36 us                                                                    | 7.10 us: 1.12x slower                                              |
| xml_etree_iterparse      | 64.3 ms                                                                    | 72.0 ms: 1.12x slower                                              |
| regex_compile            | 90.2 ms                                                                    | 102 ms: 1.13x slower                                               |
| sqlglot_optimize         | 34.5 ms                                                                    | 39.1 ms: 1.13x slower                                              |
| deepcopy_reduce          | 2.10 us                                                                    | 2.39 us: 1.14x slower                                              |
| pyflate                  | 304 ms                                                                     | 347 ms: 1.14x slower                                               |
| sqlglot_normalize        | 183 ms                                                                     | 210 ms: 1.15x slower                                               |
| pickle_pure_python       | 193 us                                                                     | 223 us: 1.15x slower                                               |
| pprint_safe_repr         | 517 ms                                                                     | 597 ms: 1.15x slower                                               |
| pprint_pformat           | 1.06 sec                                                                   | 1.23 sec: 1.15x slower                                             |
| comprehensions           | 14.2 us                                                                    | 16.6 us: 1.17x slower                                              |
| deepcopy                 | 234 us                                                                     | 273 us: 1.17x slower                                               |
| xml_etree_process        | 38.1 ms                                                                    | 44.8 ms: 1.17x slower                                              |
| float                    | 55.8 ms                                                                    | 65.9 ms: 1.18x slower                                              |
| sqlglot_transpile        | 1.04 ms                                                                    | 1.24 ms: 1.20x slower                                              |
| chaos                    | 40.9 ms                                                                    | 49.3 ms: 1.21x slower                                              |
| sqlglot_parse            | 815 us                                                                     | 996 us: 1.22x slower                                               |
| scimark_monte_carlo      | 42.9 ms                                                                    | 52.5 ms: 1.22x slower                                              |
| richards_super           | 32.7 ms                                                                    | 40.1 ms: 1.23x slower                                              |
| spectral_norm            | 65.2 ms                                                                    | 80.3 ms: 1.23x slower                                              |
| go                       | 91.3 ms                                                                    | 113 ms: 1.23x slower                                               |
| unpack_sequence          | 38.8 ns                                                                    | 47.9 ns: 1.24x slower                                              |
| hexiom                   | 4.18 ms                                                                    | 5.18 ms: 1.24x slower                                              |
| scimark_sor              | 82.8 ms                                                                    | 103 ms: 1.24x slower                                               |
| unpickle_pure_python     | 137 us                                                                     | 171 us: 1.25x slower                                               |
| richards                 | 28.5 ms                                                                    | 35.9 ms: 1.26x slower                                              |
| raytrace                 | 171 ms                                                                     | 216 ms: 1.26x slower                                               |
| scimark_lu               | 60.8 ms                                                                    | 76.9 ms: 1.26x slower                                              |
| deepcopy_memo            | 24.0 us                                                                    | 30.4 us: 1.27x slower                                              |
| coroutines               | 14.6 ms                                                                    | 18.8 ms: 1.28x slower                                              |
| deltablue                | 2.20 ms                                                                    | 2.92 ms: 1.33x slower                                              |
| logging_silent           | 63.5 ns                                                                    | 91.9 ns: 1.45x slower                                              |
| generators               | 22.7 ms                                                                    | 33.3 ms: 1.47x slower                                              |
| Geometric mean           | (ref)                                                                      | 1.10x slower                                                       |

Benchmark hidden because not significant (4): pickle_list, create_gc_cycles, python_startup_no_site, json


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.07x
- 95% likely to have a slowdown of 1.06x
- 99% likely to have a slowdown of 1.05x
