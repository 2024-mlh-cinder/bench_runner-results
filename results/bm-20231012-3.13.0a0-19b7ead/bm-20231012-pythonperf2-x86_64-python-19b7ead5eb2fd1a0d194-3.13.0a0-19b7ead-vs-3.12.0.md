
# Results vs. 3.12.0

- fork: python
- ref: 19b7ead5eb2fd1a0d194
- machine: linux-x86_64
- commit hash: 19b7ead
- commit date: 2023-10-12
- overall geometric mean: 1.01x slower
- HPT reliability: 71.80%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                      |
| tornado_http   | 122 ms                                                       | 120 ms: 1.02x faster                                                        |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 88.5 ms: 1.06x faster                                                       |
| pidigits       | 264 ms                                                       | 264 ms: 1.00x slower                                                        |
| float          | 78.5 ms                                                      | 80.3 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 241 ms                                                       | 238 ms: 1.01x faster                                                        |
| regex_v8       | 25.0 ms                                                      | 24.9 ms: 1.00x faster                                                       |
| regex_compile  | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                        | 1.00x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 14.8 us                                                      | 14.1 us: 1.05x faster                                                       |
| pickle_pure_python   | 323 us                                                       | 312 us: 1.04x faster                                                        |
| xml_etree_generate   | 86.1 ms                                                      | 84.8 ms: 1.02x faster                                                       |
| unpickle_list        | 4.77 us                                                      | 4.73 us: 1.01x faster                                                       |
| xml_etree_process    | 58.3 ms                                                      | 58.0 ms: 1.01x faster                                                       |
| json_loads           | 24.3 us                                                      | 24.2 us: 1.00x faster                                                       |
| pickle               | 10.1 us                                                      | 10.2 us: 1.01x slower                                                       |
| pickle_list          | 4.39 us                                                      | 4.45 us: 1.01x slower                                                       |
| xml_etree_parse      | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| pickle_dict          | 31.7 us                                                      | 32.5 us: 1.02x slower                                                       |
| json_dumps           | 10.2 ms                                                      | 10.5 ms: 1.02x slower                                                       |
| xml_etree_iterparse  | 103 ms                                                       | 107 ms: 1.04x slower                                                        |
| tomli_loads          | 2.20 sec                                                     | 2.36 sec: 1.07x slower                                                      |
| unpickle_pure_python | 207 us                                                       | 227 us: 1.10x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.01x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                        | 1.04x slower                                                                |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|-----------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.3 ms: 1.03x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231012-pythonperf2-x86_64-python-19b7ead5eb2fd1a0d194-3.13.0a0-19b7ead |
|--------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| bench_mp_pool            | 5.34 ms                                                      | 4.67 ms: 1.14x faster                                                       |
| crypto_pyaes             | 80.9 ms                                                      | 72.1 ms: 1.12x faster                                                       |
| coverage                 | 89.6 ms                                                      | 82.5 ms: 1.09x faster                                                       |
| raytrace                 | 302 ms                                                       | 279 ms: 1.08x faster                                                        |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.12 ms: 1.07x faster                                                       |
| nbody                    | 94.1 ms                                                      | 88.5 ms: 1.06x faster                                                       |
| async_tree_none          | 459 ms                                                       | 437 ms: 1.05x faster                                                        |
| unpickle                 | 14.8 us                                                      | 14.1 us: 1.05x faster                                                       |
| asyncio_tcp              | 381 ms                                                       | 366 ms: 1.04x faster                                                        |
| generators               | 36.7 ms                                                      | 35.2 ms: 1.04x faster                                                       |
| scimark_monte_carlo      | 72.4 ms                                                      | 69.8 ms: 1.04x faster                                                       |
| pickle_pure_python       | 323 us                                                       | 312 us: 1.04x faster                                                        |
| chaos                    | 62.9 ms                                                      | 61.2 ms: 1.03x faster                                                       |
| deepcopy_reduce          | 3.46 us                                                      | 3.37 us: 1.03x faster                                                       |
| nqueens                  | 90.1 ms                                                      | 88.1 ms: 1.02x faster                                                       |
| scimark_fft              | 304 ms                                                       | 298 ms: 1.02x faster                                                        |
| create_gc_cycles         | 1.67 ms                                                      | 1.64 ms: 1.02x faster                                                       |
| tornado_http             | 122 ms                                                       | 120 ms: 1.02x faster                                                        |
| pprint_safe_repr         | 823 ms                                                       | 809 ms: 1.02x faster                                                        |
| xml_etree_generate       | 86.1 ms                                                      | 84.8 ms: 1.02x faster                                                       |
| pathlib                  | 19.8 ms                                                      | 19.5 ms: 1.02x faster                                                       |
| pprint_pformat           | 1.67 sec                                                     | 1.65 sec: 1.01x faster                                                      |
| async_tree_cpu_io_mixed  | 706 ms                                                       | 699 ms: 1.01x faster                                                        |
| regex_dna                | 241 ms                                                       | 238 ms: 1.01x faster                                                        |
| deepcopy_memo            | 37.4 us                                                      | 37.0 us: 1.01x faster                                                       |
| sqlglot_normalize        | 117 ms                                                       | 116 ms: 1.01x faster                                                        |
| unpickle_list            | 4.77 us                                                      | 4.73 us: 1.01x faster                                                       |
| typing_runtime_protocols | 151 us                                                       | 150 us: 1.01x faster                                                        |
| xml_etree_process        | 58.3 ms                                                      | 58.0 ms: 1.01x faster                                                       |
| json_loads               | 24.3 us                                                      | 24.2 us: 1.00x faster                                                       |
| mdp                      | 2.53 sec                                                     | 2.52 sec: 1.00x faster                                                      |
| regex_v8                 | 25.0 ms                                                      | 24.9 ms: 1.00x faster                                                       |
| docutils                 | 2.89 sec                                                     | 2.88 sec: 1.00x faster                                                      |
| pidigits                 | 264 ms                                                       | 264 ms: 1.00x slower                                                        |
| sqlite_synth             | 2.70 us                                                      | 2.71 us: 1.00x slower                                                       |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.58 sec: 1.00x slower                                                      |
| comprehensions           | 21.9 us                                                      | 22.0 us: 1.01x slower                                                       |
| sqlglot_parse            | 1.40 ms                                                      | 1.41 ms: 1.01x slower                                                       |
| mypy2                    | 368 ms                                                       | 371 ms: 1.01x slower                                                        |
| sqlglot_transpile        | 1.80 ms                                                      | 1.82 ms: 1.01x slower                                                       |
| pickle                   | 10.1 us                                                      | 10.2 us: 1.01x slower                                                       |
| sqlglot_optimize         | 57.8 ms                                                      | 58.4 ms: 1.01x slower                                                       |
| scimark_lu               | 101 ms                                                       | 102 ms: 1.01x slower                                                        |
| pickle_list              | 4.39 us                                                      | 4.45 us: 1.01x slower                                                       |
| pycparser                | 1.27 sec                                                     | 1.29 sec: 1.01x slower                                                      |
| unpack_sequence          | 53.3 ns                                                      | 54.1 ns: 1.02x slower                                                       |
| logging_silent           | 95.6 ns                                                      | 97.3 ns: 1.02x slower                                                       |
| logging_format           | 7.37 us                                                      | 7.50 us: 1.02x slower                                                       |
| xml_etree_parse          | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| coroutines               | 23.0 ms                                                      | 23.5 ms: 1.02x slower                                                       |
| logging_simple           | 6.73 us                                                      | 6.88 us: 1.02x slower                                                       |
| float                    | 78.5 ms                                                      | 80.3 ms: 1.02x slower                                                       |
| pickle_dict              | 31.7 us                                                      | 32.5 us: 1.02x slower                                                       |
| regex_compile            | 146 ms                                                       | 149 ms: 1.02x slower                                                        |
| json_dumps               | 10.2 ms                                                      | 10.5 ms: 1.02x slower                                                       |
| async_tree_io            | 1.06 sec                                                     | 1.09 sec: 1.03x slower                                                      |
| mako                     | 9.94 ms                                                      | 10.3 ms: 1.03x slower                                                       |
| xml_etree_iterparse      | 103 ms                                                       | 107 ms: 1.04x slower                                                        |
| meteor_contest           | 128 ms                                                       | 133 ms: 1.04x slower                                                        |
| gc_traversal             | 3.54 ms                                                      | 3.71 ms: 1.05x slower                                                       |
| dulwich_log              | 65.3 ms                                                      | 70.0 ms: 1.07x slower                                                       |
| hexiom                   | 5.96 ms                                                      | 6.39 ms: 1.07x slower                                                       |
| tomli_loads              | 2.20 sec                                                     | 2.36 sec: 1.07x slower                                                      |
| python_startup           | 11.7 ms                                                      | 12.6 ms: 1.08x slower                                                       |
| unpickle_pure_python     | 207 us                                                       | 227 us: 1.10x slower                                                        |
| deltablue                | 3.29 ms                                                      | 3.66 ms: 1.11x slower                                                       |
| fannkuch                 | 350 ms                                                       | 392 ms: 1.12x slower                                                        |
| go                       | 150 ms                                                       | 170 ms: 1.13x slower                                                        |
| pyflate                  | 447 ms                                                       | 514 ms: 1.15x slower                                                        |
| richards_super           | 51.7 ms                                                      | 60.2 ms: 1.16x slower                                                       |
| telco                    | 6.96 ms                                                      | 8.20 ms: 1.18x slower                                                       |
| richards                 | 45.0 ms                                                      | 54.9 ms: 1.22x slower                                                       |
| scimark_sor              | 110 ms                                                       | 149 ms: 1.36x slower                                                        |
| Geometric mean           | (ref)                                                        | 1.01x slower                                                                |

Benchmark hidden because not significant (8): bench_thread_pool, json, async_tree_memoization, regex_effbot, deepcopy, python_startup_no_site, spectral_norm, async_generators
Ignored benchmarks (2) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask


# HPT report

- Reliability score: 71.80% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
