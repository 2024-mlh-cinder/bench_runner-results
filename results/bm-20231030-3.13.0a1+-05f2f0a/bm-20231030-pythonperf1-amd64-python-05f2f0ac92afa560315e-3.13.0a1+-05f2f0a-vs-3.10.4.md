
# Results vs. 3.10.4

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: windows-amd64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 222 ms: 1.07x faster                                                        |
| chameleon      | 6.02 ms                                                     | 5.27 ms: 1.14x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.65 sec: 1.14x faster                                                      |
| tornado_http   | 106 ms                                                      | 90.3 ms: 1.17x faster                                                       |
| Geometric mean | (ref)                                                       | 1.13x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 283 ms: 1.50x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 767 ms: 1.40x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 362 ms: 1.39x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 473 ms: 1.31x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.40x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.4 ms: 1.14x faster                                                       |
| pidigits       | 146 ms                                                      | 148 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 74.3 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 92.8 ms: 1.10x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.73 ms: 1.53x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 200 us: 1.29x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 139 us: 1.28x faster                                                        |
| unpickle             | 9.11 us                                                     | 8.31 us: 1.10x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 39.9 ms: 1.08x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.56 sec: 1.06x faster                                                      |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 93.0 ms: 1.04x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 65.4 ms: 1.01x slower                                                       |
| pickle               | 6.87 us                                                     | 6.98 us: 1.01x slower                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 56.7 ms: 1.04x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.84 us: 1.05x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.8 us: 1.09x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.6 ms: 1.05x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 7.09 ms: 1.27x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 101 us: 3.35x faster                                                        |
| deltablue                | 4.12 ms                                                     | 2.25 ms: 1.83x faster                                                       |
| mypy2                    | 347 ms                                                      | 218 ms: 1.59x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.73 ms: 1.53x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 474 ms: 1.51x faster                                                        |
| async_tree_none          | 424 ms                                                      | 283 ms: 1.50x faster                                                        |
| logging_silent           | 93.4 ns                                                     | 62.7 ns: 1.49x faster                                                       |
| richards_super           | 50.3 ms                                                     | 33.8 ms: 1.49x faster                                                       |
| raytrace                 | 266 ms                                                      | 180 ms: 1.48x faster                                                        |
| comprehensions           | 16.6 us                                                     | 11.3 us: 1.47x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 58.0 ms: 1.45x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 44.2 ms: 1.43x faster                                                       |
| go                       | 135 ms                                                      | 95.9 ms: 1.41x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 862 us: 1.40x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 767 ms: 1.40x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 362 ms: 1.39x faster                                                        |
| chaos                    | 59.5 ms                                                     | 43.3 ms: 1.37x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 42.3 ms: 1.37x faster                                                       |
| generators               | 31.8 ms                                                     | 23.5 ms: 1.35x faster                                                       |
| richards                 | 40.6 ms                                                     | 30.3 ms: 1.34x faster                                                       |
| sqlglot_transpile        | 1.45 ms                                                     | 1.08 ms: 1.33x faster                                                       |
| pyflate                  | 402 ms                                                      | 307 ms: 1.31x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 4.28 ms: 1.31x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 473 ms: 1.31x faster                                                        |
| scimark_sor              | 105 ms                                                      | 80.6 ms: 1.31x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 200 us: 1.29x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 139 us: 1.28x faster                                                        |
| mako                     | 8.98 ms                                                     | 7.09 ms: 1.27x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 63.9 ms: 1.23x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.21x faster                                                       |
| sympy_sum                | 105 ms                                                      | 88.1 ms: 1.19x faster                                                       |
| tornado_http             | 106 ms                                                      | 90.3 ms: 1.17x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.49 sec: 1.15x faster                                                      |
| deepcopy_memo            | 29.0 us                                                     | 25.2 us: 1.15x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 13.1 ms: 1.15x faster                                                       |
| chameleon                | 6.02 ms                                                     | 5.27 ms: 1.14x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.65 sec: 1.14x faster                                                      |
| float                    | 61.7 ms                                                     | 54.4 ms: 1.14x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.10 sec: 1.11x faster                                                      |
| pycparser                | 905 ms                                                      | 818 ms: 1.11x faster                                                        |
| sympy_str                | 193 ms                                                      | 175 ms: 1.10x faster                                                        |
| regex_compile            | 102 ms                                                      | 92.8 ms: 1.10x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 540 ms: 1.10x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 729 us: 1.10x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.31 us: 1.10x faster                                                       |
| nqueens                  | 68.3 ms                                                     | 63.0 ms: 1.08x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 844 us: 1.08x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 39.9 ms: 1.08x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 36.7 ms: 1.07x faster                                                       |
| json                     | 3.10 ms                                                     | 2.89 ms: 1.07x faster                                                       |
| 2to3                     | 239 ms                                                      | 222 ms: 1.07x faster                                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| dulwich_log              | 48.6 ms                                                     | 45.6 ms: 1.06x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.56 sec: 1.06x faster                                                      |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.98 sec: 1.06x faster                                                      |
| unpack_sequence          | 40.0 ns                                                     | 37.8 ns: 1.06x faster                                                       |
| coroutines               | 15.5 ms                                                     | 14.7 ms: 1.05x faster                                                       |
| sympy_expand             | 320 ms                                                      | 305 ms: 1.05x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 197 ms: 1.05x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 93.0 ms: 1.04x faster                                                       |
| deepcopy                 | 259 us                                                      | 250 us: 1.04x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.60 ms: 1.03x faster                                                       |
| scimark_fft              | 187 ms                                                      | 186 ms: 1.01x faster                                                        |
| regex_v8                 | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                       |
| pidigits                 | 146 ms                                                      | 148 ms: 1.01x slower                                                        |
| fannkuch                 | 258 ms                                                      | 261 ms: 1.01x slower                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 2.25 us: 1.01x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 65.4 ms: 1.01x slower                                                       |
| pickle                   | 6.87 us                                                     | 6.98 us: 1.01x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.60 ms: 1.02x slower                                                       |
| meteor_contest           | 73.8 ms                                                     | 75.6 ms: 1.02x slower                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 56.7 ms: 1.04x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.6 ms: 1.05x slower                                                       |
| nbody                    | 71.0 ms                                                     | 74.3 ms: 1.05x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.1 ms: 1.05x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.84 us: 1.05x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.75 us: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.08x slower                                                       |
| logging_format           | 6.73 us                                                     | 7.31 us: 1.09x slower                                                       |
| async_generators         | 219 ms                                                      | 238 ms: 1.09x slower                                                        |
| pathlib                  | 72.8 ms                                                     | 79.6 ms: 1.09x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.8 us: 1.09x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.1 ms: 1.20x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.79 ms: 1.26x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.15x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231030-3.13.0a1+-05f2f0a/bm-20231030-pythonperf1-amd64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.07x
