
# Results vs. 3.10.4

- fork: python
- ref: v3.11.4
- machine: windows-amd64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 221 ms: 1.08x faster                                        |
| chameleon      | 6.02 ms                                                     | 5.44 ms: 1.11x faster                                       |
| docutils       | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                      |
| html5lib       | 47.5 ms                                                     | 39.4 ms: 1.21x faster                                       |
| tornado_http   | 106 ms                                                      | 103 ms: 1.02x faster                                        |
| Geometric mean | (ref)                                                       | 1.11x faster                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 813 ms: 1.32x faster                                        |
| async_tree_memoization  | 505 ms                                                      | 392 ms: 1.29x faster                                        |
| async_tree_none         | 424 ms                                                      | 334 ms: 1.27x faster                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 522 ms: 1.18x faster                                        |
| Geometric mean          | (ref)                                                       | 1.26x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 61.7 ms                                                     | 56.7 ms: 1.09x faster                                       |
| nbody          | 71.0 ms                                                     | 70.4 ms: 1.01x faster                                       |
| pidigits       | 146 ms                                                      | 151 ms: 1.03x slower                                        |
| Geometric mean | (ref)                                                       | 1.02x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 92.8 ms: 1.10x faster                                       |
| regex_v8       | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                       |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                        |
| regex_effbot   | 1.56 ms                                                     | 1.52 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                       | 1.07x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 201 us: 1.29x faster                                        |
| unpickle_pure_python | 177 us                                                      | 153 us: 1.16x faster                                        |
| tomli_loads          | 1.65 sec                                                    | 1.43 sec: 1.15x faster                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.9 ms: 1.14x faster                                       |
| unpickle             | 9.11 us                                                     | 8.15 us: 1.12x faster                                       |
| json_dumps           | 8.77 ms                                                     | 7.92 ms: 1.11x faster                                       |
| json_loads           | 14.2 us                                                     | 13.3 us: 1.07x faster                                       |
| pickle               | 6.87 us                                                     | 6.74 us: 1.02x faster                                       |
| xml_etree_generate   | 54.5 ms                                                     | 53.8 ms: 1.01x faster                                       |
| pickle_list          | 2.69 us                                                     | 2.78 us: 1.03x slower                                       |
| pickle_dict          | 17.1 us                                                     | 18.8 us: 1.10x slower                                       |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                |

Benchmark hidden because not significant (3): xml_etree_parse, xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.6 ms: 1.05x slower                                       |
| python_startup_no_site | 15.3 ms                                                     | 17.5 ms: 1.14x slower                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 28.8 ms                                                     | 24.5 ms: 1.18x faster                                       |
| mako            | 8.98 ms                                                     | 7.67 ms: 1.17x faster                                       |
| genshi_text     | 18.8 ms                                                     | 17.8 ms: 1.06x faster                                       |
| genshi_xml      | 39.4 ms                                                     | 38.6 ms: 1.02x faster                                       |
| Geometric mean  | (ref)                                                       | 1.11x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| deltablue                | 4.12 ms                                                     | 2.71 ms: 1.52x faster                                       |
| scimark_sor              | 105 ms                                                      | 76.9 ms: 1.37x faster                                       |
| go                       | 135 ms                                                      | 100 ms: 1.35x faster                                        |
| scimark_lu               | 84.0 ms                                                     | 63.4 ms: 1.33x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 813 ms: 1.32x faster                                        |
| richards                 | 40.6 ms                                                     | 31.0 ms: 1.31x faster                                       |
| richards_super           | 50.3 ms                                                     | 38.6 ms: 1.30x faster                                       |
| logging_silent           | 93.4 ns                                                     | 72.1 ns: 1.30x faster                                       |
| pyflate                  | 402 ms                                                      | 310 ms: 1.30x faster                                        |
| pickle_pure_python       | 259 us                                                      | 201 us: 1.29x faster                                        |
| async_tree_memoization   | 505 ms                                                      | 392 ms: 1.29x faster                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 45.1 ms: 1.29x faster                                       |
| sqlglot_parse            | 1.20 ms                                                     | 936 us: 1.29x faster                                        |
| thrift                   | 623 us                                                      | 486 us: 1.28x faster                                        |
| raytrace                 | 266 ms                                                      | 208 ms: 1.28x faster                                        |
| crypto_pyaes             | 63.1 ms                                                     | 49.7 ms: 1.27x faster                                       |
| async_tree_none          | 424 ms                                                      | 334 ms: 1.27x faster                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.15 ms: 1.26x faster                                       |
| pycparser                | 905 ms                                                      | 726 ms: 1.25x faster                                        |
| hexiom                   | 5.59 ms                                                     | 4.55 ms: 1.23x faster                                       |
| chaos                    | 59.5 ms                                                     | 48.8 ms: 1.22x faster                                       |
| html5lib                 | 47.5 ms                                                     | 39.4 ms: 1.21x faster                                       |
| mypy2                    | 347 ms                                                      | 290 ms: 1.19x faster                                        |
| sqlalchemy_declarative   | 98.6 ms                                                     | 82.7 ms: 1.19x faster                                       |
| async_generators         | 219 ms                                                      | 184 ms: 1.19x faster                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 522 ms: 1.18x faster                                        |
| django_template          | 28.8 ms                                                     | 24.5 ms: 1.18x faster                                       |
| mako                     | 8.98 ms                                                     | 7.67 ms: 1.17x faster                                       |
| unpickle_pure_python     | 177 us                                                      | 153 us: 1.16x faster                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.05 sec: 1.16x faster                                      |
| pprint_safe_repr         | 594 ms                                                      | 513 ms: 1.16x faster                                        |
| tomli_loads              | 1.65 sec                                                    | 1.43 sec: 1.15x faster                                      |
| xml_etree_process        | 43.1 ms                                                     | 37.9 ms: 1.14x faster                                       |
| deepcopy_memo            | 29.0 us                                                     | 25.6 us: 1.13x faster                                       |
| docutils                 | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                      |
| sqlglot_optimize         | 39.4 ms                                                     | 35.2 ms: 1.12x faster                                       |
| unpickle                 | 9.11 us                                                     | 8.15 us: 1.12x faster                                       |
| chameleon                | 6.02 ms                                                     | 5.44 ms: 1.11x faster                                       |
| json_dumps               | 8.77 ms                                                     | 7.92 ms: 1.11x faster                                       |
| regex_compile            | 102 ms                                                      | 92.8 ms: 1.10x faster                                       |
| float                    | 61.7 ms                                                     | 56.7 ms: 1.09x faster                                       |
| regex_v8                 | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                       |
| 2to3                     | 239 ms                                                      | 221 ms: 1.08x faster                                        |
| create_gc_cycles         | 800 us                                                      | 740 us: 1.08x faster                                        |
| regex_dna                | 129 ms                                                      | 120 ms: 1.08x faster                                        |
| sqlite_synth             | 1.90 us                                                     | 1.76 us: 1.08x faster                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                       |
| json_loads               | 14.2 us                                                     | 13.3 us: 1.07x faster                                       |
| sqlglot_normalize        | 207 ms                                                      | 193 ms: 1.07x faster                                        |
| sqlalchemy_imperative    | 11.2 ms                                                     | 10.4 ms: 1.07x faster                                       |
| sympy_expand             | 320 ms                                                      | 299 ms: 1.07x faster                                        |
| dask                     | 305 ms                                                      | 287 ms: 1.06x faster                                        |
| deepcopy_reduce          | 2.22 us                                                     | 2.09 us: 1.06x faster                                       |
| comprehensions           | 16.6 us                                                     | 15.6 us: 1.06x faster                                       |
| genshi_text              | 18.8 ms                                                     | 17.8 ms: 1.06x faster                                       |
| spectral_norm            | 78.9 ms                                                     | 74.7 ms: 1.06x faster                                       |
| deepcopy                 | 259 us                                                      | 246 us: 1.06x faster                                        |
| nqueens                  | 68.3 ms                                                     | 65.1 ms: 1.05x faster                                       |
| dulwich_log              | 48.6 ms                                                     | 46.4 ms: 1.05x faster                                       |
| coroutines               | 15.5 ms                                                     | 14.8 ms: 1.04x faster                                       |
| typing_runtime_protocols | 337 us                                                      | 326 us: 1.03x faster                                        |
| sympy_str                | 193 ms                                                      | 187 ms: 1.03x faster                                        |
| regex_effbot             | 1.56 ms                                                     | 1.52 ms: 1.03x faster                                       |
| pylint                   | 341 ms                                                      | 331 ms: 1.03x faster                                        |
| aiohttp                  | 961 us                                                      | 936 us: 1.03x faster                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.60 ms: 1.02x faster                                       |
| sympy_sum                | 105 ms                                                      | 103 ms: 1.02x faster                                        |
| genshi_xml               | 39.4 ms                                                     | 38.6 ms: 1.02x faster                                       |
| tornado_http             | 106 ms                                                      | 103 ms: 1.02x faster                                        |
| scimark_fft              | 187 ms                                                      | 184 ms: 1.02x faster                                        |
| pickle                   | 6.87 us                                                     | 6.74 us: 1.02x faster                                       |
| xml_etree_generate       | 54.5 ms                                                     | 53.8 ms: 1.01x faster                                       |
| nbody                    | 71.0 ms                                                     | 70.4 ms: 1.01x faster                                       |
| flaskblogging            | 2.04 sec                                                    | 2.05 sec: 1.00x slower                                      |
| fannkuch                 | 258 ms                                                      | 263 ms: 1.02x slower                                        |
| mdp                      | 1.71 sec                                                    | 1.76 sec: 1.03x slower                                      |
| pidigits                 | 146 ms                                                      | 151 ms: 1.03x slower                                        |
| pickle_list              | 2.69 us                                                     | 2.78 us: 1.03x slower                                       |
| meteor_contest           | 73.8 ms                                                     | 77.4 ms: 1.05x slower                                       |
| telco                    | 3.82 ms                                                     | 4.00 ms: 1.05x slower                                       |
| python_startup           | 19.7 ms                                                     | 20.6 ms: 1.05x slower                                       |
| pathlib                  | 72.8 ms                                                     | 77.5 ms: 1.06x slower                                       |
| logging_simple           | 6.28 us                                                     | 6.71 us: 1.07x slower                                       |
| logging_format           | 6.73 us                                                     | 7.26 us: 1.08x slower                                       |
| generators               | 31.8 ms                                                     | 34.5 ms: 1.09x slower                                       |
| gc_traversal             | 1.40 ms                                                     | 1.52 ms: 1.09x slower                                       |
| pickle_dict              | 17.1 us                                                     | 18.8 us: 1.10x slower                                       |
| bench_mp_pool            | 59.9 ms                                                     | 66.1 ms: 1.10x slower                                       |
| json                     | 3.10 ms                                                     | 3.51 ms: 1.13x slower                                       |
| python_startup_no_site   | 15.3 ms                                                     | 17.5 ms: 1.14x slower                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 2.41 sec: 1.15x slower                                      |
| unpack_sequence          | 40.0 ns                                                     | 48.1 ns: 1.20x slower                                       |
| asyncio_tcp              | 717 ms                                                      | 932 ms: 1.30x slower                                        |
| coverage                 | 38.4 ms                                                     | 55.6 ms: 1.45x slower                                       |
| Geometric mean           | (ref)                                                       | 1.08x faster                                                |

Benchmark hidden because not significant (4): xml_etree_parse, xml_etree_iterparse, unpickle_list, bench_thread_pool


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.06x
- 95% likely to have a speedup of 1.06x
- 99% likely to have a speedup of 1.05x
