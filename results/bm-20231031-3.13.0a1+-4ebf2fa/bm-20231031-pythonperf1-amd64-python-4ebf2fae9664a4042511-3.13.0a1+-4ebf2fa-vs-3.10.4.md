
# Results vs. 3.10.4

- fork: python
- ref: 4ebf2fae9664a4042511
- machine: windows-amd64
- commit hash: 4ebf2fa
- commit date: 2023-10-31
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 222 ms: 1.08x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.37 ms: 1.12x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.65 sec: 1.14x faster                                                      |
| tornado_http   | 106 ms                                                      | 89.9 ms: 1.17x faster                                                       |
| Geometric mean | (ref)                                                       | 1.13x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 281 ms: 1.51x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 755 ms: 1.42x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 360 ms: 1.40x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 474 ms: 1.30x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.41x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.4 ms: 1.13x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 74.6 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 92.6 ms: 1.10x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 15.5 ms: 1.03x slower                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.84 ms: 1.50x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 200 us: 1.29x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 139 us: 1.28x faster                                                        |
| unpickle             | 9.11 us                                                     | 8.17 us: 1.11x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 39.4 ms: 1.09x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.55 sec: 1.06x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 92.5 ms: 1.05x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.8 us: 1.03x faster                                                       |
| pickle               | 6.87 us                                                     | 6.91 us: 1.01x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 56.4 ms: 1.04x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.80 us: 1.04x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.1 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.0 ms: 1.01x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.0 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.09x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.14 ms: 1.26x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 97.6 us: 3.45x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.23 ms: 1.85x faster                                                       |
| mypy2                    | 347 ms                                                      | 218 ms: 1.59x faster                                                        |
| async_tree_none          | 424 ms                                                      | 281 ms: 1.51x faster                                                        |
| richards_super           | 50.3 ms                                                     | 33.4 ms: 1.51x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 5.84 ms: 1.50x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 62.6 ns: 1.49x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 484 ms: 1.48x faster                                                        |
| comprehensions           | 16.6 us                                                     | 11.2 us: 1.48x faster                                                       |
| raytrace                 | 266 ms                                                      | 182 ms: 1.46x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 755 ms: 1.42x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 360 ms: 1.40x faster                                                        |
| generators               | 31.8 ms                                                     | 22.7 ms: 1.40x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 861 us: 1.40x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 45.3 ms: 1.39x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 60.3 ms: 1.39x faster                                                       |
| go                       | 135 ms                                                      | 98.2 ms: 1.38x faster                                                       |
| richards                 | 40.6 ms                                                     | 29.8 ms: 1.36x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.8 ms: 1.36x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.09 ms: 1.33x faster                                                       |
| chaos                    | 59.5 ms                                                     | 45.0 ms: 1.32x faster                                                       |
| pyflate                  | 402 ms                                                      | 306 ms: 1.31x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 4.27 ms: 1.31x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 474 ms: 1.30x faster                                                        |
| pickle_pure_python       | 259 us                                                      | 200 us: 1.29x faster                                                        |
| scimark_sor              | 105 ms                                                      | 81.9 ms: 1.29x faster                                                       |
| unpickle_pure_python     | 177 us                                                      | 139 us: 1.28x faster                                                        |
| mako                     | 8.98 ms                                                     | 7.14 ms: 1.26x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 63.7 ms: 1.24x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.22x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.42 sec: 1.21x faster                                                      |
| sympy_sum                | 105 ms                                                      | 88.3 ms: 1.19x faster                                                       |
| tornado_http             | 106 ms                                                      | 89.9 ms: 1.17x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.1 ms: 1.14x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 25.4 us: 1.14x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.65 sec: 1.14x faster                                                      |
| float                    | 61.7 ms                                                     | 54.4 ms: 1.13x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.37 ms: 1.12x faster                                                       |
| sympy_str                | 193 ms                                                      | 173 ms: 1.12x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.17 us: 1.11x faster                                                       |
| regex_compile            | 102 ms                                                      | 92.6 ms: 1.10x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 728 us: 1.10x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.12 sec: 1.10x faster                                                      |
| xml_etree_process        | 43.1 ms                                                     | 39.4 ms: 1.09x faster                                                       |
| nqueens                  | 68.3 ms                                                     | 62.5 ms: 1.09x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 546 ms: 1.09x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 36.3 ms: 1.09x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 844 us: 1.08x faster                                                        |
| sympy_expand             | 320 ms                                                      | 296 ms: 1.08x faster                                                        |
| 2to3                     | 239 ms                                                      | 222 ms: 1.08x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 45.2 ms: 1.07x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.96 sec: 1.07x faster                                                      |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.50 ms: 1.07x faster                                                       |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 194 ms: 1.06x faster                                                        |
| coroutines               | 15.5 ms                                                     | 14.6 ms: 1.06x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.55 sec: 1.06x faster                                                      |
| pycparser                | 905 ms                                                      | 852 ms: 1.06x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 92.5 ms: 1.05x faster                                                       |
| fannkuch                 | 258 ms                                                      | 249 ms: 1.03x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.8 us: 1.03x faster                                                       |
| deepcopy                 | 259 us                                                      | 255 us: 1.02x faster                                                        |
| scimark_fft              | 187 ms                                                      | 188 ms: 1.00x slower                                                        |
| pidigits                 | 146 ms                                                      | 147 ms: 1.01x slower                                                        |
| pickle                   | 6.87 us                                                     | 6.91 us: 1.01x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.0 ms: 1.01x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 15.5 ms: 1.03x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 75.9 ms: 1.03x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.61 ms: 1.03x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 56.4 ms: 1.04x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.80 us: 1.04x slower                                                       |
| nbody                    | 71.0 ms                                                     | 74.6 ms: 1.05x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 62.9 ms: 1.05x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.1 us: 1.06x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.48 ms: 1.06x slower                                                       |
| async_generators         | 219 ms                                                      | 237 ms: 1.08x slower                                                        |
| pathlib                  | 72.8 ms                                                     | 79.7 ms: 1.09x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.89 us: 1.10x slower                                                       |
| logging_format           | 6.73 us                                                     | 7.38 us: 1.10x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.0 ms: 1.17x slower                                                       |
| coverage                 | 38.4 ms                                                     | 45.5 ms: 1.19x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.85 ms: 1.27x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.15x faster                                                                |

Benchmark hidden because not significant (5): json, unpack_sequence, xml_etree_iterparse, unpickle_list, deepcopy_reduce
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231031-3.13.0a1+-4ebf2fa/bm-20231031-pythonperf1-amd64-python-4ebf2fae9664a4042511-3.13.0a1+-4ebf2fa.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.07x
