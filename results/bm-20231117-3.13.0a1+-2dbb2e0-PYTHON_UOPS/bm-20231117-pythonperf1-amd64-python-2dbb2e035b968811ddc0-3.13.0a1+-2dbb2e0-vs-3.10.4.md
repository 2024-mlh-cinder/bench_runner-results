
# Results vs. 3.10.4

- fork: python
- ref: 2dbb2e035b968811ddc0
- machine: windows-amd64
- commit hash: 2dbb2e0
- commit date: 2023-11-17
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 218 ms: 1.09x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.95 ms: 1.22x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                      |
| tornado_http   | 106 ms                                                      | 89.9 ms: 1.17x faster                                                       |
| Geometric mean | (ref)                                                       | 1.16x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 276 ms: 1.54x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 348 ms: 1.45x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 739 ms: 1.45x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 461 ms: 1.34x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.44x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 59.8 ms: 1.03x faster                                                       |
| pidigits       | 146 ms                                                      | 148 ms: 1.01x slower                                                        |
| nbody          | 71.0 ms                                                     | 78.6 ms: 1.11x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 91.4 ms: 1.12x faster                                                       |
| regex_dna      | 129 ms                                                      | 120 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 15.4 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.75 ms: 1.53x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 180 us: 1.44x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 142 us: 1.25x faster                                                        |
| xml_etree_process    | 43.1 ms                                                     | 37.3 ms: 1.16x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.17 us: 1.11x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.05x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.5 ms: 1.05x faster                                                       |
| tomli_loads          | 1.65 sec                                                    | 1.59 sec: 1.04x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 65.7 ms: 1.02x slower                                                       |
| pickle               | 6.87 us                                                     | 7.13 us: 1.04x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.7 us: 1.09x slower                                                       |
| pickle_list          | 2.69 us                                                     | 3.04 us: 1.13x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                                |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.7 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.07x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 8.30 ms: 1.08x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 80.2 us: 4.20x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.4 ms: 1.60x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 58.7 ns: 1.59x faster                                                       |
| generators               | 31.8 ms                                                     | 20.6 ms: 1.54x faster                                                       |
| async_tree_none          | 424 ms                                                      | 276 ms: 1.54x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 787 us: 1.53x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.75 ms: 1.53x faster                                                       |
| raytrace                 | 266 ms                                                      | 177 ms: 1.51x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 480 ms: 1.49x faster                                                        |
| richards                 | 40.6 ms                                                     | 27.9 ms: 1.45x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 348 ms: 1.45x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 739 ms: 1.45x faster                                                        |
| pickle_pure_python       | 259 us                                                      | 180 us: 1.44x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 1.00 ms: 1.44x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 58.6 ms: 1.43x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.96 ms: 1.39x faster                                                       |
| go                       | 135 ms                                                      | 99.2 ms: 1.36x faster                                                       |
| scimark_sor              | 105 ms                                                      | 77.6 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 461 ms: 1.34x faster                                                        |
| chaos                    | 59.5 ms                                                     | 45.0 ms: 1.32x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 59.7 ms: 1.32x faster                                                       |
| pycparser                | 905 ms                                                      | 703 ms: 1.29x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 142 us: 1.25x faster                                                        |
| sympy_sum                | 105 ms                                                      | 84.6 ms: 1.24x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 51.2 ms: 1.23x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.7 us: 1.22x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.95 ms: 1.22x faster                                                       |
| pyflate                  | 402 ms                                                      | 333 ms: 1.21x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.58 us: 1.20x faster                                                       |
| dask                     | 305 ms                                                      | 256 ms: 1.19x faster                                                        |
| mypy2                    | 347 ms                                                      | 293 ms: 1.18x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 49.0 ms: 1.18x faster                                                       |
| coroutines               | 15.5 ms                                                     | 13.1 ms: 1.18x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                      |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.78 sec: 1.18x faster                                                      |
| sqlglot_optimize         | 39.4 ms                                                     | 33.6 ms: 1.17x faster                                                       |
| tornado_http             | 106 ms                                                      | 89.9 ms: 1.17x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 177 ms: 1.17x faster                                                        |
| sympy_str                | 193 ms                                                      | 165 ms: 1.17x faster                                                        |
| deepcopy                 | 259 us                                                      | 222 us: 1.17x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.3 ms: 1.16x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 42.3 ms: 1.15x faster                                                       |
| sympy_expand             | 320 ms                                                      | 280 ms: 1.14x faster                                                        |
| mdp                      | 1.71 sec                                                    | 1.52 sec: 1.13x faster                                                      |
| sympy_integrate          | 15.0 ms                                                     | 13.4 ms: 1.12x faster                                                       |
| regex_compile            | 102 ms                                                      | 91.4 ms: 1.12x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.99 us: 1.12x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.17 us: 1.11x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 1.11 sec: 1.11x faster                                                      |
| pprint_safe_repr         | 594 ms                                                      | 538 ms: 1.10x faster                                                        |
| 2to3                     | 239 ms                                                      | 218 ms: 1.09x faster                                                        |
| mako                     | 8.98 ms                                                     | 8.30 ms: 1.08x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 744 us: 1.08x faster                                                        |
| regex_dna                | 129 ms                                                      | 120 ms: 1.07x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 854 us: 1.07x faster                                                        |
| comprehensions           | 16.6 us                                                     | 15.5 us: 1.07x faster                                                       |
| unpack_sequence          | 40.0 ns                                                     | 38.0 ns: 1.05x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.05x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 92.5 ms: 1.05x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.59 sec: 1.04x faster                                                      |
| float                    | 61.7 ms                                                     | 59.8 ms: 1.03x faster                                                       |
| pidigits                 | 146 ms                                                      | 148 ms: 1.01x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 65.7 ms: 1.02x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 15.4 ms: 1.02x slower                                                       |
| logging_simple           | 6.28 us                                                     | 6.43 us: 1.02x slower                                                       |
| logging_format           | 6.73 us                                                     | 6.89 us: 1.02x slower                                                       |
| nqueens                  | 68.3 ms                                                     | 70.4 ms: 1.03x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 75.1 ms: 1.03x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.13 us: 1.04x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 63.3 ms: 1.06x slower                                                       |
| hexiom                   | 5.59 ms                                                     | 5.96 ms: 1.07x slower                                                       |
| async_generators         | 219 ms                                                      | 233 ms: 1.07x slower                                                        |
| meteor_contest           | 73.8 ms                                                     | 79.0 ms: 1.07x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.51 ms: 1.08x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.7 us: 1.09x slower                                                       |
| nbody                    | 71.0 ms                                                     | 78.6 ms: 1.11x slower                                                       |
| pickle_list              | 2.69 us                                                     | 3.04 us: 1.13x slower                                                       |
| scimark_fft              | 187 ms                                                      | 213 ms: 1.14x slower                                                        |
| fannkuch                 | 258 ms                                                      | 294 ms: 1.14x slower                                                        |
| python_startup_no_site   | 15.3 ms                                                     | 17.7 ms: 1.16x slower                                                       |
| coverage                 | 38.4 ms                                                     | 45.3 ms: 1.18x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.87 ms: 1.28x slower                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 3.88 ms: 1.46x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.15x faster                                                                |

Benchmark hidden because not significant (4): json, unpickle_list, python_startup, xml_etree_generate
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-2dbb2e0-PYTHON_UOPS/bm-20231117-pythonperf1-amd64-python-2dbb2e035b968811ddc0-3.13.0a1+-2dbb2e0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
