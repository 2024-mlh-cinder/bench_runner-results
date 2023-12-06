
# Results vs. 3.12.0

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: windows-amd64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.02x slower
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                                     |
| tornado_http   | 87.7 ms                                                     | 89.3 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                                       |
| float          | 55.1 ms                                                     | 55.8 ms: 1.01x slower                                                      |
| nbody          | 72.6 ms                                                     | 74.6 ms: 1.03x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 124 ms                                                      | 118 ms: 1.05x faster                                                       |
| regex_effbot   | 1.62 ms                                                     | 1.57 ms: 1.04x faster                                                      |
| regex_compile  | 88.3 ms                                                     | 90.2 ms: 1.02x slower                                                      |
| regex_v8       | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.6 us: 1.04x faster                                                      |
| unpickle_list        | 2.78 us                                                     | 2.73 us: 1.02x faster                                                      |
| pickle_pure_python   | 196 us                                                      | 193 us: 1.01x faster                                                       |
| xml_etree_process    | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                                      |
| xml_etree_generate   | 55.6 ms                                                     | 55.8 ms: 1.00x slower                                                      |
| json_dumps           | 5.60 ms                                                     | 5.64 ms: 1.01x slower                                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.3 ms: 1.03x slower                                                      |
| pickle               | 7.13 us                                                     | 7.34 us: 1.03x slower                                                      |
| unpickle_pure_python | 133 us                                                      | 137 us: 1.03x slower                                                       |
| xml_etree_parse      | 89.2 ms                                                     | 92.6 ms: 1.04x slower                                                      |
| tomli_loads          | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                     |
| pickle_list          | 2.86 us                                                     | 3.43 us: 1.20x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (2): json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                      |
| python_startup_no_site | 16.1 ms                                                     | 16.5 ms: 1.02x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.41 ms: 1.07x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 44.5 ms: 1.16x faster                                                      |
| raytrace                 | 191 ms                                                      | 171 ms: 1.12x faster                                                       |
| async_tree_none          | 294 ms                                                      | 269 ms: 1.09x faster                                                       |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.84 sec: 1.07x faster                                                     |
| regex_dna                | 124 ms                                                      | 118 ms: 1.05x faster                                                       |
| chaos                    | 42.8 ms                                                     | 40.9 ms: 1.05x faster                                                      |
| crypto_pyaes             | 47.4 ms                                                     | 45.7 ms: 1.04x faster                                                      |
| pickle_dict              | 19.3 us                                                     | 18.6 us: 1.04x faster                                                      |
| regex_effbot             | 1.62 ms                                                     | 1.57 ms: 1.04x faster                                                      |
| deepcopy                 | 240 us                                                      | 234 us: 1.03x faster                                                       |
| unpickle_list            | 2.78 us                                                     | 2.73 us: 1.02x faster                                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 42.9 ms: 1.02x faster                                                      |
| deepcopy_reduce          | 2.13 us                                                     | 2.10 us: 1.02x faster                                                      |
| sqlglot_normalize        | 185 ms                                                      | 183 ms: 1.02x faster                                                       |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 471 ms: 1.02x faster                                                       |
| pickle_pure_python       | 196 us                                                      | 193 us: 1.01x faster                                                       |
| scimark_sparse_mat_mult  | 2.48 ms                                                     | 2.46 ms: 1.01x faster                                                      |
| docutils                 | 1.63 sec                                                    | 1.62 sec: 1.01x faster                                                     |
| xml_etree_process        | 38.4 ms                                                     | 38.1 ms: 1.01x faster                                                      |
| sqlite_synth             | 1.76 us                                                     | 1.74 us: 1.01x faster                                                      |
| sqlglot_parse            | 820 us                                                      | 815 us: 1.01x faster                                                       |
| nqueens                  | 61.2 ms                                                     | 61.0 ms: 1.00x faster                                                      |
| xml_etree_generate       | 55.6 ms                                                     | 55.8 ms: 1.00x slower                                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 34.5 ms: 1.00x slower                                                      |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                                       |
| meteor_contest           | 73.1 ms                                                     | 73.6 ms: 1.01x slower                                                      |
| comprehensions           | 14.1 us                                                     | 14.2 us: 1.01x slower                                                      |
| json_dumps               | 5.60 ms                                                     | 5.64 ms: 1.01x slower                                                      |
| deepcopy_memo            | 23.8 us                                                     | 24.0 us: 1.01x slower                                                      |
| pprint_safe_repr         | 512 ms                                                      | 517 ms: 1.01x slower                                                       |
| float                    | 55.1 ms                                                     | 55.8 ms: 1.01x slower                                                      |
| pathlib                  | 77.1 ms                                                     | 78.3 ms: 1.02x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                                     |
| mdp                      | 1.44 sec                                                    | 1.47 sec: 1.02x slower                                                     |
| python_startup           | 19.5 ms                                                     | 19.8 ms: 1.02x slower                                                      |
| tornado_http             | 87.7 ms                                                     | 89.3 ms: 1.02x slower                                                      |
| bench_mp_pool            | 66.4 ms                                                     | 67.7 ms: 1.02x slower                                                      |
| async_tree_memoization   | 336 ms                                                      | 343 ms: 1.02x slower                                                       |
| scimark_fft              | 180 ms                                                      | 184 ms: 1.02x slower                                                       |
| logging_format           | 6.67 us                                                     | 6.82 us: 1.02x slower                                                      |
| python_startup_no_site   | 16.1 ms                                                     | 16.5 ms: 1.02x slower                                                      |
| regex_compile            | 88.3 ms                                                     | 90.2 ms: 1.02x slower                                                      |
| logging_simple           | 6.21 us                                                     | 6.36 us: 1.02x slower                                                      |
| pyflate                  | 297 ms                                                      | 304 ms: 1.02x slower                                                       |
| nbody                    | 72.6 ms                                                     | 74.6 ms: 1.03x slower                                                      |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.3 ms: 1.03x slower                                                      |
| pickle                   | 7.13 us                                                     | 7.34 us: 1.03x slower                                                      |
| deltablue                | 2.14 ms                                                     | 2.20 ms: 1.03x slower                                                      |
| unpickle_pure_python     | 133 us                                                      | 137 us: 1.03x slower                                                       |
| go                       | 88.5 ms                                                     | 91.3 ms: 1.03x slower                                                      |
| spectral_norm            | 63.2 ms                                                     | 65.2 ms: 1.03x slower                                                      |
| mypy2                    | 207 ms                                                      | 214 ms: 1.03x slower                                                       |
| unpack_sequence          | 37.5 ns                                                     | 38.8 ns: 1.03x slower                                                      |
| hexiom                   | 4.03 ms                                                     | 4.18 ms: 1.04x slower                                                      |
| xml_etree_parse          | 89.2 ms                                                     | 92.6 ms: 1.04x slower                                                      |
| scimark_sor              | 79.6 ms                                                     | 82.8 ms: 1.04x slower                                                      |
| async_generators         | 235 ms                                                      | 246 ms: 1.04x slower                                                       |
| typing_runtime_protocols | 95.2 us                                                     | 99.4 us: 1.04x slower                                                      |
| coroutines               | 14.0 ms                                                     | 14.6 ms: 1.05x slower                                                      |
| scimark_lu               | 58.1 ms                                                     | 60.8 ms: 1.05x slower                                                      |
| logging_silent           | 60.6 ns                                                     | 63.5 ns: 1.05x slower                                                      |
| richards                 | 26.9 ms                                                     | 28.5 ms: 1.06x slower                                                      |
| mako                     | 6.93 ms                                                     | 7.41 ms: 1.07x slower                                                      |
| regex_v8                 | 13.9 ms                                                     | 14.9 ms: 1.07x slower                                                      |
| richards_super           | 30.5 ms                                                     | 32.7 ms: 1.07x slower                                                      |
| dulwich_log              | 42.4 ms                                                     | 45.6 ms: 1.07x slower                                                      |
| tomli_loads              | 1.37 sec                                                    | 1.49 sec: 1.09x slower                                                     |
| fannkuch                 | 237 ms                                                      | 261 ms: 1.10x slower                                                       |
| telco                    | 4.09 ms                                                     | 4.79 ms: 1.17x slower                                                      |
| pickle_list              | 2.86 us                                                     | 3.43 us: 1.20x slower                                                      |
| pycparser                | 673 ms                                                      | 894 ms: 1.33x slower                                                       |
| dask                     | 259 ms                                                      | 370 ms: 1.43x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (10): asyncio_tcp, bench_thread_pool, generators, json_loads, sqlglot_transpile, create_gc_cycles, async_tree_io, gc_traversal, unpickle, json
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp


# HPT report

- Reliability score: 99.96% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
