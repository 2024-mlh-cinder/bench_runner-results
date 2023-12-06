
# Results vs. 3.12.0

- fork: python
- ref: v3.11.4
- machine: windows-amd64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 221 ms: 1.04x slower                                        |
| chameleon      | 4.95 ms                                                     | 5.44 ms: 1.10x slower                                       |
| docutils       | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                      |
| tornado_http   | 87.2 ms                                                     | 103 ms: 1.19x slower                                        |
| Geometric mean | (ref)                                                       | 1.09x slower                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 522 ms: 1.09x slower                                        |
| async_tree_io           | 712 ms                                                      | 813 ms: 1.14x slower                                        |
| async_tree_none         | 286 ms                                                      | 334 ms: 1.17x slower                                        |
| async_tree_memoization  | 333 ms                                                      | 392 ms: 1.18x slower                                        |
| Geometric mean          | (ref)                                                       | 1.15x slower                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.01x slower                                        |
| nbody          | 68.8 ms                                                     | 70.4 ms: 1.02x slower                                       |
| float          | 54.7 ms                                                     | 56.7 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.52 ms: 1.04x faster                                       |
| regex_v8       | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                       |
| regex_compile  | 87.2 ms                                                     | 92.8 ms: 1.06x slower                                       |
| Geometric mean | (ref)                                                       | 1.01x slower                                                |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.74 us: 1.09x faster                                       |
| pickle_list          | 2.88 us                                                     | 2.78 us: 1.04x faster                                       |
| xml_etree_generate   | 55.8 ms                                                     | 53.8 ms: 1.04x faster                                       |
| unpickle             | 8.44 us                                                     | 8.15 us: 1.03x faster                                       |
| json_loads           | 13.6 us                                                     | 13.3 us: 1.03x faster                                       |
| pickle_dict          | 18.9 us                                                     | 18.8 us: 1.01x faster                                       |
| xml_etree_process    | 37.6 ms                                                     | 37.9 ms: 1.01x slower                                       |
| unpickle_list        | 2.69 us                                                     | 2.73 us: 1.01x slower                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 64.8 ms: 1.03x slower                                       |
| pickle_pure_python   | 195 us                                                      | 201 us: 1.03x slower                                        |
| tomli_loads          | 1.38 sec                                                    | 1.43 sec: 1.04x slower                                      |
| xml_etree_parse      | 90.5 ms                                                     | 96.4 ms: 1.06x slower                                       |
| unpickle_pure_python | 134 us                                                      | 153 us: 1.14x slower                                        |
| json_dumps           | 5.83 ms                                                     | 7.92 ms: 1.36x slower                                       |
| Geometric mean       | (ref)                                                       | 1.03x slower                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                       |
| python_startup_no_site | 15.9 ms                                                     | 17.5 ms: 1.10x slower                                       |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 22.8 ms                                                     | 24.5 ms: 1.07x slower                                       |
| mako            | 7.05 ms                                                     | 7.67 ms: 1.09x slower                                       |
| Geometric mean  | (ref)                                                       | 1.08x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_generators         | 230 ms                                                      | 184 ms: 1.25x faster                                        |
| pickle                   | 7.38 us                                                     | 6.74 us: 1.09x faster                                       |
| regex_effbot             | 1.58 ms                                                     | 1.52 ms: 1.04x faster                                       |
| scimark_sor              | 79.8 ms                                                     | 76.9 ms: 1.04x faster                                       |
| pickle_list              | 2.88 us                                                     | 2.78 us: 1.04x faster                                       |
| xml_etree_generate       | 55.8 ms                                                     | 53.8 ms: 1.04x faster                                       |
| unpickle                 | 8.44 us                                                     | 8.15 us: 1.03x faster                                       |
| json_loads               | 13.6 us                                                     | 13.3 us: 1.03x faster                                       |
| pathlib                  | 79.6 ms                                                     | 77.5 ms: 1.03x faster                                       |
| sqlalchemy_declarative   | 84.5 ms                                                     | 82.7 ms: 1.02x faster                                       |
| telco                    | 4.08 ms                                                     | 4.00 ms: 1.02x faster                                       |
| bench_mp_pool            | 67.2 ms                                                     | 66.1 ms: 1.02x faster                                       |
| pickle_dict              | 18.9 us                                                     | 18.8 us: 1.01x faster                                       |
| pidigits                 | 150 ms                                                      | 151 ms: 1.01x slower                                        |
| xml_etree_process        | 37.6 ms                                                     | 37.9 ms: 1.01x slower                                       |
| sqlite_synth             | 1.75 us                                                     | 1.76 us: 1.01x slower                                       |
| pprint_safe_repr         | 508 ms                                                      | 513 ms: 1.01x slower                                        |
| unpickle_list            | 2.69 us                                                     | 2.73 us: 1.01x slower                                       |
| scimark_fft              | 181 ms                                                      | 184 ms: 1.01x slower                                        |
| pprint_pformat           | 1.04 sec                                                    | 1.05 sec: 1.01x slower                                      |
| gc_traversal             | 1.49 ms                                                     | 1.52 ms: 1.02x slower                                       |
| create_gc_cycles         | 726 us                                                      | 740 us: 1.02x slower                                        |
| nbody                    | 68.8 ms                                                     | 70.4 ms: 1.02x slower                                       |
| xml_etree_iterparse      | 63.1 ms                                                     | 64.8 ms: 1.03x slower                                       |
| regex_v8                 | 13.5 ms                                                     | 13.9 ms: 1.03x slower                                       |
| docutils                 | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                      |
| pickle_pure_python       | 195 us                                                      | 201 us: 1.03x slower                                        |
| sqlglot_optimize         | 34.0 ms                                                     | 35.2 ms: 1.04x slower                                       |
| float                    | 54.7 ms                                                     | 56.7 ms: 1.04x slower                                       |
| scimark_sparse_mat_mult  | 2.51 ms                                                     | 2.60 ms: 1.04x slower                                       |
| tomli_loads              | 1.38 sec                                                    | 1.43 sec: 1.04x slower                                      |
| 2to3                     | 213 ms                                                      | 221 ms: 1.04x slower                                        |
| scimark_monte_carlo      | 43.0 ms                                                     | 45.1 ms: 1.05x slower                                       |
| coroutines               | 14.1 ms                                                     | 14.8 ms: 1.05x slower                                       |
| sqlglot_normalize        | 183 ms                                                      | 193 ms: 1.05x slower                                        |
| nqueens                  | 61.7 ms                                                     | 65.1 ms: 1.05x slower                                       |
| pyflate                  | 294 ms                                                      | 310 ms: 1.06x slower                                        |
| deepcopy                 | 233 us                                                      | 246 us: 1.06x slower                                        |
| regex_compile            | 87.2 ms                                                     | 92.8 ms: 1.06x slower                                       |
| xml_etree_parse          | 90.5 ms                                                     | 96.4 ms: 1.06x slower                                       |
| crypto_pyaes             | 46.4 ms                                                     | 49.7 ms: 1.07x slower                                       |
| meteor_contest           | 72.1 ms                                                     | 77.4 ms: 1.07x slower                                       |
| django_template          | 22.8 ms                                                     | 24.5 ms: 1.07x slower                                       |
| sympy_integrate          | 13.0 ms                                                     | 13.9 ms: 1.07x slower                                       |
| sympy_expand             | 278 ms                                                      | 299 ms: 1.08x slower                                        |
| raytrace                 | 192 ms                                                      | 208 ms: 1.08x slower                                        |
| pycparser                | 673 ms                                                      | 726 ms: 1.08x slower                                        |
| fannkuch                 | 244 ms                                                      | 263 ms: 1.08x slower                                        |
| logging_format           | 6.72 us                                                     | 7.26 us: 1.08x slower                                       |
| logging_simple           | 6.21 us                                                     | 6.71 us: 1.08x slower                                       |
| dulwich_log              | 42.7 ms                                                     | 46.4 ms: 1.09x slower                                       |
| mako                     | 7.05 ms                                                     | 7.67 ms: 1.09x slower                                       |
| sympy_str                | 171 ms                                                      | 187 ms: 1.09x slower                                        |
| deepcopy_memo            | 23.4 us                                                     | 25.6 us: 1.09x slower                                       |
| async_tree_cpu_io_mixed  | 477 ms                                                      | 522 ms: 1.09x slower                                        |
| python_startup           | 18.8 ms                                                     | 20.6 ms: 1.10x slower                                       |
| chameleon                | 4.95 ms                                                     | 5.44 ms: 1.10x slower                                       |
| python_startup_no_site   | 15.9 ms                                                     | 17.5 ms: 1.10x slower                                       |
| scimark_lu               | 57.5 ms                                                     | 63.4 ms: 1.10x slower                                       |
| aiohttp                  | 848 us                                                      | 936 us: 1.10x slower                                        |
| comprehensions           | 14.0 us                                                     | 15.6 us: 1.12x slower                                       |
| richards                 | 27.6 ms                                                     | 31.0 ms: 1.12x slower                                       |
| dask                     | 255 ms                                                      | 287 ms: 1.12x slower                                        |
| go                       | 89.0 ms                                                     | 100 ms: 1.13x slower                                        |
| sqlglot_transpile        | 1.02 ms                                                     | 1.15 ms: 1.13x slower                                       |
| sqlalchemy_imperative    | 9.20 ms                                                     | 10.4 ms: 1.13x slower                                       |
| bench_thread_pool        | 830 us                                                      | 941 us: 1.13x slower                                        |
| unpickle_pure_python     | 134 us                                                      | 153 us: 1.14x slower                                        |
| hexiom                   | 4.00 ms                                                     | 4.55 ms: 1.14x slower                                       |
| sympy_sum                | 90.1 ms                                                     | 103 ms: 1.14x slower                                        |
| async_tree_io            | 712 ms                                                      | 813 ms: 1.14x slower                                        |
| chaos                    | 42.1 ms                                                     | 48.8 ms: 1.16x slower                                       |
| sqlglot_parse            | 802 us                                                      | 936 us: 1.17x slower                                        |
| async_tree_none          | 286 ms                                                      | 334 ms: 1.17x slower                                        |
| spectral_norm            | 63.9 ms                                                     | 74.7 ms: 1.17x slower                                       |
| async_tree_memoization   | 333 ms                                                      | 392 ms: 1.18x slower                                        |
| tornado_http             | 87.2 ms                                                     | 103 ms: 1.19x slower                                        |
| json                     | 2.94 ms                                                     | 3.51 ms: 1.19x slower                                       |
| logging_silent           | 60.5 ns                                                     | 72.1 ns: 1.19x slower                                       |
| mdp                      | 1.42 sec                                                    | 1.76 sec: 1.24x slower                                      |
| richards_super           | 31.2 ms                                                     | 38.6 ms: 1.24x slower                                       |
| asyncio_tcp_ssl          | 1.89 sec                                                    | 2.41 sec: 1.28x slower                                      |
| deltablue                | 2.12 ms                                                     | 2.71 ms: 1.28x slower                                       |
| unpack_sequence          | 36.9 ns                                                     | 48.1 ns: 1.30x slower                                       |
| json_dumps               | 5.83 ms                                                     | 7.92 ms: 1.36x slower                                       |
| mypy2                    | 209 ms                                                      | 290 ms: 1.39x slower                                        |
| coverage                 | 39.8 ms                                                     | 55.6 ms: 1.40x slower                                       |
| generators               | 22.6 ms                                                     | 34.5 ms: 1.53x slower                                       |
| asyncio_tcp              | 471 ms                                                      | 932 ms: 1.98x slower                                        |
| typing_runtime_protocols | 96.7 us                                                     | 326 us: 3.37x slower                                        |
| Geometric mean           | (ref)                                                       | 1.10x slower                                                |

Benchmark hidden because not significant (2): deepcopy_reduce, regex_dna
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
Ignored benchmarks (6) of results/bm-20230606-3.11.4-d2340ef/bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.05x
