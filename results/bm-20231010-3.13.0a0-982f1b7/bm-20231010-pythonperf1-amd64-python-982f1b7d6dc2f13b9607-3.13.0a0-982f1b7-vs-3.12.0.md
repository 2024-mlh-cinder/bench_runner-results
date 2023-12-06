
# Results vs. 3.12.0

- fork: python
- ref: 982f1b7d6dc2f13b9607
- machine: windows-amd64
- commit hash: 982f1b7
- commit date: 2023-10-10
- overall geometric mean: 1.02x slower
- HPT reliability: 99.97%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| tornado_http   | 87.7 ms                                                     | 89.2 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 150 ms: 1.00x faster                                                       |
| nbody          | 72.6 ms                                                     | 75.1 ms: 1.03x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                                      |
| regex_dna      | 124 ms                                                      | 123 ms: 1.01x faster                                                       |
| regex_compile  | 88.3 ms                                                     | 92.4 ms: 1.05x slower                                                      |
| regex_v8       | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                                      |
| unpickle_list        | 2.78 us                                                     | 2.71 us: 1.02x faster                                                      |
| pickle_pure_python   | 196 us                                                      | 197 us: 1.01x slower                                                       |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.01x slower                                                      |
| pickle               | 7.13 us                                                     | 7.26 us: 1.02x slower                                                      |
| xml_etree_generate   | 55.6 ms                                                     | 56.9 ms: 1.02x slower                                                      |
| xml_etree_parse      | 89.2 ms                                                     | 91.8 ms: 1.03x slower                                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.4 ms: 1.03x slower                                                      |
| xml_etree_process    | 38.4 ms                                                     | 39.6 ms: 1.03x slower                                                      |
| json_dumps           | 5.60 ms                                                     | 5.81 ms: 1.04x slower                                                      |
| unpickle_pure_python | 133 us                                                      | 141 us: 1.06x slower                                                       |
| tomli_loads          | 1.37 sec                                                    | 1.50 sec: 1.09x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (2): unpickle, pickle_list

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.19 ms: 1.04x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| coverage                 | 51.5 ms                                                     | 46.2 ms: 1.12x faster                                                      |
| asyncio_tcp_ssl          | 1.96 sec                                                    | 1.77 sec: 1.11x faster                                                     |
| async_tree_none          | 294 ms                                                      | 271 ms: 1.09x faster                                                       |
| raytrace                 | 191 ms                                                      | 178 ms: 1.08x faster                                                       |
| crypto_pyaes             | 47.4 ms                                                     | 44.7 ms: 1.06x faster                                                      |
| pickle_dict              | 19.3 us                                                     | 18.3 us: 1.05x faster                                                      |
| async_tree_cpu_io_mixed  | 479 ms                                                      | 455 ms: 1.05x faster                                                       |
| bench_mp_pool            | 66.4 ms                                                     | 63.7 ms: 1.04x faster                                                      |
| sqlite_synth             | 1.76 us                                                     | 1.70 us: 1.03x faster                                                      |
| unpickle_list            | 2.78 us                                                     | 2.71 us: 1.02x faster                                                      |
| generators               | 22.7 ms                                                     | 22.4 ms: 1.01x faster                                                      |
| scimark_monte_carlo      | 43.7 ms                                                     | 43.1 ms: 1.01x faster                                                      |
| chaos                    | 42.8 ms                                                     | 42.4 ms: 1.01x faster                                                      |
| regex_effbot             | 1.62 ms                                                     | 1.61 ms: 1.01x faster                                                      |
| regex_dna                | 124 ms                                                      | 123 ms: 1.01x faster                                                       |
| mdp                      | 1.44 sec                                                    | 1.43 sec: 1.01x faster                                                     |
| pidigits                 | 150 ms                                                      | 150 ms: 1.00x faster                                                       |
| pickle_pure_python       | 196 us                                                      | 197 us: 1.01x slower                                                       |
| deepcopy                 | 240 us                                                      | 242 us: 1.01x slower                                                       |
| pathlib                  | 77.1 ms                                                     | 77.8 ms: 1.01x slower                                                      |
| sqlglot_parse            | 820 us                                                      | 828 us: 1.01x slower                                                       |
| async_tree_io            | 720 ms                                                      | 729 ms: 1.01x slower                                                       |
| scimark_fft              | 180 ms                                                      | 183 ms: 1.01x slower                                                       |
| json_loads               | 13.4 us                                                     | 13.6 us: 1.01x slower                                                      |
| tornado_http             | 87.7 ms                                                     | 89.2 ms: 1.02x slower                                                      |
| pickle                   | 7.13 us                                                     | 7.26 us: 1.02x slower                                                      |
| json                     | 2.86 ms                                                     | 2.92 ms: 1.02x slower                                                      |
| sqlglot_transpile        | 1.04 ms                                                     | 1.06 ms: 1.02x slower                                                      |
| sqlglot_optimize         | 34.4 ms                                                     | 35.2 ms: 1.02x slower                                                      |
| xml_etree_generate       | 55.6 ms                                                     | 56.9 ms: 1.02x slower                                                      |
| pyflate                  | 297 ms                                                      | 304 ms: 1.02x slower                                                       |
| comprehensions           | 14.1 us                                                     | 14.5 us: 1.03x slower                                                      |
| xml_etree_parse          | 89.2 ms                                                     | 91.8 ms: 1.03x slower                                                      |
| deepcopy_reduce          | 2.13 us                                                     | 2.20 us: 1.03x slower                                                      |
| async_tree_memoization   | 336 ms                                                      | 346 ms: 1.03x slower                                                       |
| xml_etree_iterparse      | 62.5 ms                                                     | 64.4 ms: 1.03x slower                                                      |
| deltablue                | 2.14 ms                                                     | 2.20 ms: 1.03x slower                                                      |
| xml_etree_process        | 38.4 ms                                                     | 39.6 ms: 1.03x slower                                                      |
| nbody                    | 72.6 ms                                                     | 75.1 ms: 1.03x slower                                                      |
| go                       | 88.5 ms                                                     | 91.8 ms: 1.04x slower                                                      |
| mako                     | 6.93 ms                                                     | 7.19 ms: 1.04x slower                                                      |
| meteor_contest           | 73.1 ms                                                     | 75.9 ms: 1.04x slower                                                      |
| json_dumps               | 5.60 ms                                                     | 5.81 ms: 1.04x slower                                                      |
| spectral_norm            | 63.2 ms                                                     | 65.6 ms: 1.04x slower                                                      |
| scimark_lu               | 58.1 ms                                                     | 60.4 ms: 1.04x slower                                                      |
| async_generators         | 235 ms                                                      | 245 ms: 1.04x slower                                                       |
| logging_format           | 6.67 us                                                     | 6.96 us: 1.04x slower                                                      |
| deepcopy_memo            | 23.8 us                                                     | 24.9 us: 1.05x slower                                                      |
| hexiom                   | 4.03 ms                                                     | 4.22 ms: 1.05x slower                                                      |
| mypy2                    | 207 ms                                                      | 217 ms: 1.05x slower                                                       |
| regex_compile            | 88.3 ms                                                     | 92.4 ms: 1.05x slower                                                      |
| pprint_safe_repr         | 512 ms                                                      | 536 ms: 1.05x slower                                                       |
| logging_silent           | 60.6 ns                                                     | 63.6 ns: 1.05x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.10 sec: 1.05x slower                                                     |
| logging_simple           | 6.21 us                                                     | 6.55 us: 1.05x slower                                                      |
| coroutines               | 14.0 ms                                                     | 14.8 ms: 1.05x slower                                                      |
| unpickle_pure_python     | 133 us                                                      | 141 us: 1.06x slower                                                       |
| scimark_sor              | 79.6 ms                                                     | 85.0 ms: 1.07x slower                                                      |
| richards_super           | 30.5 ms                                                     | 32.5 ms: 1.07x slower                                                      |
| dulwich_log              | 42.4 ms                                                     | 45.4 ms: 1.07x slower                                                      |
| richards                 | 26.9 ms                                                     | 28.9 ms: 1.07x slower                                                      |
| typing_runtime_protocols | 95.2 us                                                     | 103 us: 1.08x slower                                                       |
| regex_v8                 | 13.9 ms                                                     | 15.1 ms: 1.09x slower                                                      |
| tomli_loads              | 1.37 sec                                                    | 1.50 sec: 1.09x slower                                                     |
| fannkuch                 | 237 ms                                                      | 260 ms: 1.10x slower                                                       |
| unpack_sequence          | 37.5 ns                                                     | 41.2 ns: 1.10x slower                                                      |
| telco                    | 4.09 ms                                                     | 4.72 ms: 1.15x slower                                                      |
| pycparser                | 673 ms                                                      | 901 ms: 1.34x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (13): create_gc_cycles, bench_thread_pool, python_startup, unpickle, python_startup_no_site, docutils, nqueens, gc_traversal, scimark_sparse_mat_mult, pickle_list, float, sqlglot_normalize, asyncio_tcp
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 99.97% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
