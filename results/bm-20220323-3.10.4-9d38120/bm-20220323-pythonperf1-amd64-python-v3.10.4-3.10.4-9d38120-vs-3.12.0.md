
# Results vs. 3.12.0

- fork: python
- ref: v3.10.4
- machine: windows-amd64
- commit hash: 9d38120
- commit date: 2022-03-23
- overall geometric mean: 1.19x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 239 ms: 1.12x slower                                        |
| chameleon      | 4.95 ms                                                     | 6.02 ms: 1.22x slower                                       |
| docutils       | 1.61 sec                                                    | 1.88 sec: 1.17x slower                                      |
| tornado_http   | 87.2 ms                                                     | 106 ms: 1.21x slower                                        |
| Geometric mean | (ref)                                                       | 1.18x slower                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 617 ms: 1.29x slower                                        |
| async_tree_none         | 286 ms                                                      | 424 ms: 1.48x slower                                        |
| async_tree_io           | 712 ms                                                      | 1.07 sec: 1.50x slower                                      |
| async_tree_memoization  | 333 ms                                                      | 505 ms: 1.52x slower                                        |
| Geometric mean          | (ref)                                                       | 1.45x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 146 ms: 1.03x faster                                        |
| nbody          | 68.8 ms                                                     | 71.0 ms: 1.03x slower                                       |
| float          | 54.7 ms                                                     | 61.7 ms: 1.13x slower                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.56 ms: 1.01x faster                                       |
| regex_dna      | 119 ms                                                      | 129 ms: 1.08x slower                                        |
| regex_v8       | 13.5 ms                                                     | 15.0 ms: 1.11x slower                                       |
| regex_compile  | 87.2 ms                                                     | 102 ms: 1.17x slower                                        |
| Geometric mean | (ref)                                                       | 1.09x slower                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_dict          | 18.9 us                                                     | 17.1 us: 1.11x faster                                       |
| pickle               | 7.38 us                                                     | 6.87 us: 1.07x faster                                       |
| pickle_list          | 2.88 us                                                     | 2.69 us: 1.07x faster                                       |
| xml_etree_generate   | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.5 ms: 1.02x slower                                       |
| json_loads           | 13.6 us                                                     | 14.2 us: 1.04x slower                                       |
| xml_etree_parse      | 90.5 ms                                                     | 96.8 ms: 1.07x slower                                       |
| unpickle             | 8.44 us                                                     | 9.11 us: 1.08x slower                                       |
| xml_etree_process    | 37.6 ms                                                     | 43.1 ms: 1.15x slower                                       |
| tomli_loads          | 1.38 sec                                                    | 1.65 sec: 1.20x slower                                      |
| unpickle_pure_python | 134 us                                                      | 177 us: 1.32x slower                                        |
| pickle_pure_python   | 195 us                                                      | 259 us: 1.33x slower                                        |
| json_dumps           | 5.83 ms                                                     | 8.77 ms: 1.50x slower                                       |
| Geometric mean       | (ref)                                                       | 1.09x slower                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.3 ms: 1.04x faster                                       |
| python_startup         | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                       |
| Geometric mean         | (ref)                                                       | 1.00x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 22.8 ms                                                     | 28.8 ms: 1.26x slower                                       |
| mako            | 7.05 ms                                                     | 8.98 ms: 1.27x slower                                       |
| Geometric mean  | (ref)                                                       | 1.27x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| bench_mp_pool            | 67.2 ms                                                     | 59.9 ms: 1.12x faster                                       |
| pickle_dict              | 18.9 us                                                     | 17.1 us: 1.11x faster                                       |
| pathlib                  | 79.6 ms                                                     | 72.8 ms: 1.09x faster                                       |
| pickle                   | 7.38 us                                                     | 6.87 us: 1.07x faster                                       |
| pickle_list              | 2.88 us                                                     | 2.69 us: 1.07x faster                                       |
| telco                    | 4.08 ms                                                     | 3.82 ms: 1.07x faster                                       |
| gc_traversal             | 1.49 ms                                                     | 1.40 ms: 1.07x faster                                       |
| async_generators         | 230 ms                                                      | 219 ms: 1.05x faster                                        |
| python_startup_no_site   | 15.9 ms                                                     | 15.3 ms: 1.04x faster                                       |
| coverage                 | 39.8 ms                                                     | 38.4 ms: 1.04x faster                                       |
| pidigits                 | 150 ms                                                      | 146 ms: 1.03x faster                                        |
| xml_etree_generate       | 55.8 ms                                                     | 54.5 ms: 1.02x faster                                       |
| regex_effbot             | 1.58 ms                                                     | 1.56 ms: 1.01x faster                                       |
| logging_simple           | 6.21 us                                                     | 6.28 us: 1.01x slower                                       |
| xml_etree_iterparse      | 63.1 ms                                                     | 64.5 ms: 1.02x slower                                       |
| meteor_contest           | 72.1 ms                                                     | 73.8 ms: 1.02x slower                                       |
| nbody                    | 68.8 ms                                                     | 71.0 ms: 1.03x slower                                       |
| scimark_fft              | 181 ms                                                      | 187 ms: 1.04x slower                                        |
| json_loads               | 13.6 us                                                     | 14.2 us: 1.04x slower                                       |
| python_startup           | 18.8 ms                                                     | 19.7 ms: 1.04x slower                                       |
| json                     | 2.94 ms                                                     | 3.10 ms: 1.05x slower                                       |
| fannkuch                 | 244 ms                                                      | 258 ms: 1.06x slower                                        |
| scimark_sparse_mat_mult  | 2.51 ms                                                     | 2.67 ms: 1.06x slower                                       |
| deepcopy_reduce          | 2.08 us                                                     | 2.22 us: 1.07x slower                                       |
| xml_etree_parse          | 90.5 ms                                                     | 96.8 ms: 1.07x slower                                       |
| unpickle                 | 8.44 us                                                     | 9.11 us: 1.08x slower                                       |
| regex_dna                | 119 ms                                                      | 129 ms: 1.08x slower                                        |
| unpack_sequence          | 36.9 ns                                                     | 40.0 ns: 1.08x slower                                       |
| sqlite_synth             | 1.75 us                                                     | 1.90 us: 1.09x slower                                       |
| coroutines               | 14.1 ms                                                     | 15.5 ms: 1.10x slower                                       |
| bench_thread_pool        | 830 us                                                      | 913 us: 1.10x slower                                        |
| create_gc_cycles         | 726 us                                                      | 800 us: 1.10x slower                                        |
| nqueens                  | 61.7 ms                                                     | 68.3 ms: 1.11x slower                                       |
| asyncio_tcp_ssl          | 1.89 sec                                                    | 2.09 sec: 1.11x slower                                      |
| regex_v8                 | 13.5 ms                                                     | 15.0 ms: 1.11x slower                                       |
| deepcopy                 | 233 us                                                      | 259 us: 1.11x slower                                        |
| 2to3                     | 213 ms                                                      | 239 ms: 1.12x slower                                        |
| sqlglot_normalize        | 183 ms                                                      | 207 ms: 1.13x slower                                        |
| sympy_str                | 171 ms                                                      | 193 ms: 1.13x slower                                        |
| float                    | 54.7 ms                                                     | 61.7 ms: 1.13x slower                                       |
| aiohttp                  | 848 us                                                      | 961 us: 1.13x slower                                        |
| dulwich_log              | 42.7 ms                                                     | 48.6 ms: 1.14x slower                                       |
| xml_etree_process        | 37.6 ms                                                     | 43.1 ms: 1.15x slower                                       |
| sympy_expand             | 278 ms                                                      | 320 ms: 1.15x slower                                        |
| sympy_integrate          | 13.0 ms                                                     | 15.0 ms: 1.16x slower                                       |
| sqlglot_optimize         | 34.0 ms                                                     | 39.4 ms: 1.16x slower                                       |
| docutils                 | 1.61 sec                                                    | 1.88 sec: 1.17x slower                                      |
| sqlalchemy_declarative   | 84.5 ms                                                     | 98.6 ms: 1.17x slower                                       |
| sympy_sum                | 90.1 ms                                                     | 105 ms: 1.17x slower                                        |
| pprint_safe_repr         | 508 ms                                                      | 594 ms: 1.17x slower                                        |
| regex_compile            | 87.2 ms                                                     | 102 ms: 1.17x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.22 sec: 1.18x slower                                      |
| comprehensions           | 14.0 us                                                     | 16.6 us: 1.19x slower                                       |
| dask                     | 255 ms                                                      | 305 ms: 1.20x slower                                        |
| tomli_loads              | 1.38 sec                                                    | 1.65 sec: 1.20x slower                                      |
| mdp                      | 1.42 sec                                                    | 1.71 sec: 1.21x slower                                      |
| tornado_http             | 87.2 ms                                                     | 106 ms: 1.21x slower                                        |
| sqlalchemy_imperative    | 9.20 ms                                                     | 11.2 ms: 1.21x slower                                       |
| chameleon                | 4.95 ms                                                     | 6.02 ms: 1.22x slower                                       |
| spectral_norm            | 63.9 ms                                                     | 78.9 ms: 1.23x slower                                       |
| deepcopy_memo            | 23.4 us                                                     | 29.0 us: 1.24x slower                                       |
| django_template          | 22.8 ms                                                     | 28.8 ms: 1.26x slower                                       |
| mako                     | 7.05 ms                                                     | 8.98 ms: 1.27x slower                                       |
| async_tree_cpu_io_mixed  | 477 ms                                                      | 617 ms: 1.29x slower                                        |
| scimark_sor              | 79.8 ms                                                     | 105 ms: 1.32x slower                                        |
| unpickle_pure_python     | 134 us                                                      | 177 us: 1.32x slower                                        |
| pickle_pure_python       | 195 us                                                      | 259 us: 1.33x slower                                        |
| pycparser                | 673 ms                                                      | 905 ms: 1.34x slower                                        |
| scimark_monte_carlo      | 43.0 ms                                                     | 58.0 ms: 1.35x slower                                       |
| crypto_pyaes             | 46.4 ms                                                     | 63.1 ms: 1.36x slower                                       |
| pyflate                  | 294 ms                                                      | 402 ms: 1.37x slower                                        |
| raytrace                 | 192 ms                                                      | 266 ms: 1.38x slower                                        |
| hexiom                   | 4.00 ms                                                     | 5.59 ms: 1.40x slower                                       |
| generators               | 22.6 ms                                                     | 31.8 ms: 1.41x slower                                       |
| chaos                    | 42.1 ms                                                     | 59.5 ms: 1.41x slower                                       |
| sqlglot_transpile        | 1.02 ms                                                     | 1.45 ms: 1.42x slower                                       |
| scimark_lu               | 57.5 ms                                                     | 84.0 ms: 1.46x slower                                       |
| richards                 | 27.6 ms                                                     | 40.6 ms: 1.47x slower                                       |
| async_tree_none          | 286 ms                                                      | 424 ms: 1.48x slower                                        |
| sqlglot_parse            | 802 us                                                      | 1.20 ms: 1.50x slower                                       |
| async_tree_io            | 712 ms                                                      | 1.07 sec: 1.50x slower                                      |
| json_dumps               | 5.83 ms                                                     | 8.77 ms: 1.50x slower                                       |
| async_tree_memoization   | 333 ms                                                      | 505 ms: 1.52x slower                                        |
| go                       | 89.0 ms                                                     | 135 ms: 1.52x slower                                        |
| asyncio_tcp              | 471 ms                                                      | 717 ms: 1.52x slower                                        |
| logging_silent           | 60.5 ns                                                     | 93.4 ns: 1.54x slower                                       |
| richards_super           | 31.2 ms                                                     | 50.3 ms: 1.61x slower                                       |
| mypy2                    | 209 ms                                                      | 347 ms: 1.66x slower                                        |
| deltablue                | 2.12 ms                                                     | 4.12 ms: 1.94x slower                                       |
| typing_runtime_protocols | 96.7 us                                                     | 337 us: 3.48x slower                                        |
| Geometric mean           | (ref)                                                       | 1.19x slower                                                |

Benchmark hidden because not significant (2): unpickle_list, logging_format
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.15x
- 95% likely to have a slowdown of 1.15x
- 99% likely to have a slowdown of 1.13x
