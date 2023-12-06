
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0
- machine: windows-amd64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 213 ms: 1.12x faster                                        |
| chameleon      | 6.02 ms                                                     | 4.95 ms: 1.22x faster                                       |
| docutils       | 1.88 sec                                                    | 1.61 sec: 1.17x faster                                      |
| tornado_http   | 106 ms                                                      | 87.2 ms: 1.21x faster                                       |
| Geometric mean | (ref)                                                       | 1.18x faster                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_memoization  | 505 ms                                                      | 333 ms: 1.52x faster                                        |
| async_tree_io           | 1.07 sec                                                    | 712 ms: 1.50x faster                                        |
| async_tree_none         | 424 ms                                                      | 286 ms: 1.48x faster                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 477 ms: 1.29x faster                                        |
| Geometric mean          | (ref)                                                       | 1.45x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.7 ms: 1.13x faster                                       |
| nbody          | 71.0 ms                                                     | 68.8 ms: 1.03x faster                                       |
| pidigits       | 146 ms                                                      | 150 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                       | 1.04x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 87.2 ms: 1.17x faster                                       |
| regex_v8       | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                       |
| regex_dna      | 129 ms                                                      | 119 ms: 1.08x faster                                        |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                       |
| Geometric mean | (ref)                                                       | 1.09x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.83 ms: 1.50x faster                                       |
| pickle_pure_python   | 259 us                                                      | 195 us: 1.33x faster                                        |
| unpickle_pure_python | 177 us                                                      | 134 us: 1.32x faster                                        |
| tomli_loads          | 1.65 sec                                                    | 1.38 sec: 1.20x faster                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                       |
| unpickle             | 9.11 us                                                     | 8.44 us: 1.08x faster                                       |
| xml_etree_parse      | 96.8 ms                                                     | 90.5 ms: 1.07x faster                                       |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.1 ms: 1.02x faster                                       |
| xml_etree_generate   | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                       |
| pickle_list          | 2.69 us                                                     | 2.88 us: 1.07x slower                                       |
| pickle               | 6.87 us                                                     | 7.38 us: 1.07x slower                                       |
| pickle_dict          | 17.1 us                                                     | 18.9 us: 1.11x slower                                       |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 18.8 ms: 1.04x faster                                       |
| python_startup_no_site | 15.3 ms                                                     | 15.9 ms: 1.04x slower                                       |
| Geometric mean         | (ref)                                                       | 1.00x faster                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.05 ms: 1.27x faster                                       |
| django_template | 28.8 ms                                                     | 22.8 ms: 1.26x faster                                       |
| Geometric mean  | (ref)                                                       | 1.27x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 96.7 us: 3.48x faster                                       |
| deltablue                | 4.12 ms                                                     | 2.12 ms: 1.94x faster                                       |
| mypy2                    | 347 ms                                                      | 209 ms: 1.66x faster                                        |
| richards_super           | 50.3 ms                                                     | 31.2 ms: 1.61x faster                                       |
| logging_silent           | 93.4 ns                                                     | 60.5 ns: 1.54x faster                                       |
| asyncio_tcp              | 717 ms                                                      | 471 ms: 1.52x faster                                        |
| go                       | 135 ms                                                      | 89.0 ms: 1.52x faster                                       |
| async_tree_memoization   | 505 ms                                                      | 333 ms: 1.52x faster                                        |
| json_dumps               | 8.77 ms                                                     | 5.83 ms: 1.50x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 712 ms: 1.50x faster                                        |
| sqlglot_parse            | 1.20 ms                                                     | 802 us: 1.50x faster                                        |
| async_tree_none          | 424 ms                                                      | 286 ms: 1.48x faster                                        |
| richards                 | 40.6 ms                                                     | 27.6 ms: 1.47x faster                                       |
| scimark_lu               | 84.0 ms                                                     | 57.5 ms: 1.46x faster                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.02 ms: 1.42x faster                                       |
| chaos                    | 59.5 ms                                                     | 42.1 ms: 1.41x faster                                       |
| generators               | 31.8 ms                                                     | 22.6 ms: 1.41x faster                                       |
| hexiom                   | 5.59 ms                                                     | 4.00 ms: 1.40x faster                                       |
| raytrace                 | 266 ms                                                      | 192 ms: 1.38x faster                                        |
| pyflate                  | 402 ms                                                      | 294 ms: 1.37x faster                                        |
| crypto_pyaes             | 63.1 ms                                                     | 46.4 ms: 1.36x faster                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 43.0 ms: 1.35x faster                                       |
| pycparser                | 905 ms                                                      | 673 ms: 1.34x faster                                        |
| pickle_pure_python       | 259 us                                                      | 195 us: 1.33x faster                                        |
| unpickle_pure_python     | 177 us                                                      | 134 us: 1.32x faster                                        |
| scimark_sor              | 105 ms                                                      | 79.8 ms: 1.32x faster                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 477 ms: 1.29x faster                                        |
| mako                     | 8.98 ms                                                     | 7.05 ms: 1.27x faster                                       |
| django_template          | 28.8 ms                                                     | 22.8 ms: 1.26x faster                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.4 us: 1.24x faster                                       |
| spectral_norm            | 78.9 ms                                                     | 63.9 ms: 1.23x faster                                       |
| chameleon                | 6.02 ms                                                     | 4.95 ms: 1.22x faster                                       |
| sqlalchemy_imperative    | 11.2 ms                                                     | 9.20 ms: 1.21x faster                                       |
| tornado_http             | 106 ms                                                      | 87.2 ms: 1.21x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.42 sec: 1.21x faster                                      |
| tomli_loads              | 1.65 sec                                                    | 1.38 sec: 1.20x faster                                      |
| dask                     | 305 ms                                                      | 255 ms: 1.20x faster                                        |
| comprehensions           | 16.6 us                                                     | 14.0 us: 1.19x faster                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.04 sec: 1.18x faster                                      |
| regex_compile            | 102 ms                                                      | 87.2 ms: 1.17x faster                                       |
| pprint_safe_repr         | 594 ms                                                      | 508 ms: 1.17x faster                                        |
| sympy_sum                | 105 ms                                                      | 90.1 ms: 1.17x faster                                       |
| sqlalchemy_declarative   | 98.6 ms                                                     | 84.5 ms: 1.17x faster                                       |
| docutils                 | 1.88 sec                                                    | 1.61 sec: 1.17x faster                                      |
| sqlglot_optimize         | 39.4 ms                                                     | 34.0 ms: 1.16x faster                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.0 ms: 1.16x faster                                       |
| sympy_expand             | 320 ms                                                      | 278 ms: 1.15x faster                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                       |
| dulwich_log              | 48.6 ms                                                     | 42.7 ms: 1.14x faster                                       |
| aiohttp                  | 961 us                                                      | 848 us: 1.13x faster                                        |
| float                    | 61.7 ms                                                     | 54.7 ms: 1.13x faster                                       |
| sympy_str                | 193 ms                                                      | 171 ms: 1.13x faster                                        |
| sqlglot_normalize        | 207 ms                                                      | 183 ms: 1.13x faster                                        |
| 2to3                     | 239 ms                                                      | 213 ms: 1.12x faster                                        |
| deepcopy                 | 259 us                                                      | 233 us: 1.11x faster                                        |
| regex_v8                 | 15.0 ms                                                     | 13.5 ms: 1.11x faster                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.89 sec: 1.11x faster                                      |
| nqueens                  | 68.3 ms                                                     | 61.7 ms: 1.11x faster                                       |
| create_gc_cycles         | 800 us                                                      | 726 us: 1.10x faster                                        |
| bench_thread_pool        | 913 us                                                      | 830 us: 1.10x faster                                        |
| coroutines               | 15.5 ms                                                     | 14.1 ms: 1.10x faster                                       |
| sqlite_synth             | 1.90 us                                                     | 1.75 us: 1.09x faster                                       |
| unpack_sequence          | 40.0 ns                                                     | 36.9 ns: 1.08x faster                                       |
| regex_dna                | 129 ms                                                      | 119 ms: 1.08x faster                                        |
| unpickle                 | 9.11 us                                                     | 8.44 us: 1.08x faster                                       |
| xml_etree_parse          | 96.8 ms                                                     | 90.5 ms: 1.07x faster                                       |
| deepcopy_reduce          | 2.22 us                                                     | 2.08 us: 1.07x faster                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.51 ms: 1.06x faster                                       |
| fannkuch                 | 258 ms                                                      | 244 ms: 1.06x faster                                        |
| json                     | 3.10 ms                                                     | 2.94 ms: 1.05x faster                                       |
| python_startup           | 19.7 ms                                                     | 18.8 ms: 1.04x faster                                       |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                       |
| scimark_fft              | 187 ms                                                      | 181 ms: 1.04x faster                                        |
| nbody                    | 71.0 ms                                                     | 68.8 ms: 1.03x faster                                       |
| meteor_contest           | 73.8 ms                                                     | 72.1 ms: 1.02x faster                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.1 ms: 1.02x faster                                       |
| logging_simple           | 6.28 us                                                     | 6.21 us: 1.01x faster                                       |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                       |
| xml_etree_generate       | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                       |
| pidigits                 | 146 ms                                                      | 150 ms: 1.03x slower                                        |
| coverage                 | 38.4 ms                                                     | 39.8 ms: 1.04x slower                                       |
| python_startup_no_site   | 15.3 ms                                                     | 15.9 ms: 1.04x slower                                       |
| async_generators         | 219 ms                                                      | 230 ms: 1.05x slower                                        |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.07x slower                                       |
| telco                    | 3.82 ms                                                     | 4.08 ms: 1.07x slower                                       |
| pickle_list              | 2.69 us                                                     | 2.88 us: 1.07x slower                                       |
| pickle                   | 6.87 us                                                     | 7.38 us: 1.07x slower                                       |
| pathlib                  | 72.8 ms                                                     | 79.6 ms: 1.09x slower                                       |
| pickle_dict              | 17.1 us                                                     | 18.9 us: 1.11x slower                                       |
| bench_mp_pool            | 59.9 ms                                                     | 67.2 ms: 1.12x slower                                       |
| Geometric mean           | (ref)                                                       | 1.19x faster                                                |

Benchmark hidden because not significant (2): logging_format, unpickle_list
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.13x
