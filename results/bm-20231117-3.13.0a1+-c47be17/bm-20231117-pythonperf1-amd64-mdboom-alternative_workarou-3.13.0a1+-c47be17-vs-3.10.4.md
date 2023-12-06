
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: windows-amd64
- commit hash: c47be17
- commit date: 2023-11-17
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 210 ms: 1.14x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.90 ms: 1.23x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                      |
| tornado_http   | 106 ms                                                      | 86.9 ms: 1.22x faster                                                       |
| Geometric mean | (ref)                                                       | 1.20x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 720 ms: 1.49x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 343 ms: 1.47x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 454 ms: 1.36x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.5 ms: 1.20x faster                                                       |
| pidigits       | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| nbody          | 71.0 ms                                                     | 73.5 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.05x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 83.7 ms: 1.22x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.59 ms: 1.57x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 183 us: 1.41x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 132 us: 1.34x faster                                                        |
| tomli_loads          | 1.65 sec                                                    | 1.37 sec: 1.20x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.3 ms: 1.16x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.04 us: 1.13x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 93.3 ms: 1.04x faster                                                       |
| unpickle_list        | 2.68 us                                                     | 2.61 us: 1.03x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.7 ms: 1.01x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 54.2 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 7.17 us: 1.04x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.89 us: 1.08x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.6 us: 1.09x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.3 ms                                                     | 17.8 ms: 1.16x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.08x slower                                                                |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.59 ms: 1.36x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 74.1 us: 4.54x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.05 ms: 2.01x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 57.1 ns: 1.64x faster                                                       |
| comprehensions           | 16.6 us                                                     | 10.3 us: 1.62x faster                                                       |
| async_tree_none          | 424 ms                                                      | 265 ms: 1.60x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 763 us: 1.58x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.59 ms: 1.57x faster                                                       |
| richards_super           | 50.3 ms                                                     | 32.2 ms: 1.56x faster                                                       |
| raytrace                 | 266 ms                                                      | 171 ms: 1.55x faster                                                        |
| go                       | 135 ms                                                      | 87.4 ms: 1.55x faster                                                       |
| generators               | 31.8 ms                                                     | 21.0 ms: 1.52x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 477 ms: 1.50x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 969 us: 1.49x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 720 ms: 1.49x faster                                                        |
| chaos                    | 59.5 ms                                                     | 40.2 ms: 1.48x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 343 ms: 1.47x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 43.4 ms: 1.45x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 40.5 ms: 1.43x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 183 us: 1.41x faster                                                        |
| hexiom                   | 5.59 ms                                                     | 3.97 ms: 1.41x faster                                                       |
| richards                 | 40.6 ms                                                     | 29.0 ms: 1.40x faster                                                       |
| pyflate                  | 402 ms                                                      | 288 ms: 1.39x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 60.9 ms: 1.38x faster                                                       |
| mako                     | 8.98 ms                                                     | 6.59 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 454 ms: 1.36x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 132 us: 1.34x faster                                                        |
| spectral_norm            | 78.9 ms                                                     | 60.6 ms: 1.30x faster                                                       |
| scimark_sor              | 105 ms                                                      | 81.4 ms: 1.29x faster                                                       |
| sympy_sum                | 105 ms                                                      | 82.8 ms: 1.27x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 12.1 ms: 1.24x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.90 ms: 1.23x faster                                                       |
| pprint_pformat           | 1.22 sec                                                    | 997 ms: 1.23x faster                                                        |
| regex_compile            | 102 ms                                                      | 83.7 ms: 1.22x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.22x faster                                                       |
| tornado_http             | 106 ms                                                      | 86.9 ms: 1.22x faster                                                       |
| deepcopy_memo            | 29.0 us                                                     | 23.8 us: 1.22x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 490 ms: 1.21x faster                                                        |
| docutils                 | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                      |
| mypy2                    | 347 ms                                                      | 287 ms: 1.21x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.37 sec: 1.20x faster                                                      |
| float                    | 61.7 ms                                                     | 51.5 ms: 1.20x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 32.9 ms: 1.20x faster                                                       |
| sympy_str                | 193 ms                                                      | 161 ms: 1.20x faster                                                        |
| mdp                      | 1.71 sec                                                    | 1.44 sec: 1.19x faster                                                      |
| sqlglot_normalize        | 207 ms                                                      | 173 ms: 1.19x faster                                                        |
| deepcopy                 | 259 us                                                      | 219 us: 1.19x faster                                                        |
| dask                     | 305 ms                                                      | 257 ms: 1.18x faster                                                        |
| sympy_expand             | 320 ms                                                      | 276 ms: 1.16x faster                                                        |
| xml_etree_process        | 43.1 ms                                                     | 37.3 ms: 1.16x faster                                                       |
| nqueens                  | 68.3 ms                                                     | 59.3 ms: 1.15x faster                                                       |
| 2to3                     | 239 ms                                                      | 210 ms: 1.14x faster                                                        |
| pycparser                | 905 ms                                                      | 795 ms: 1.14x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 1.95 us: 1.14x faster                                                       |
| unpickle                 | 9.11 us                                                     | 8.04 us: 1.13x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 43.1 ms: 1.13x faster                                                       |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.39 ms: 1.12x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.89 sec: 1.11x faster                                                      |
| coroutines               | 15.5 ms                                                     | 14.0 ms: 1.10x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 830 us: 1.10x faster                                                        |
| create_gc_cycles         | 800 us                                                      | 742 us: 1.08x faster                                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| unpack_sequence          | 40.0 ns                                                     | 37.6 ns: 1.06x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                                       |
| xml_etree_parse          | 96.8 ms                                                     | 93.3 ms: 1.04x faster                                                       |
| scimark_fft              | 187 ms                                                      | 181 ms: 1.04x faster                                                        |
| logging_simple           | 6.28 us                                                     | 6.07 us: 1.03x faster                                                       |
| unpickle_list            | 2.68 us                                                     | 2.61 us: 1.03x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.56 us: 1.02x faster                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.7 ms: 1.01x faster                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 54.2 ms: 1.01x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 73.5 ms: 1.01x faster                                                       |
| pidigits                 | 146 ms                                                      | 147 ms: 1.00x slower                                                        |
| regex_effbot             | 1.56 ms                                                     | 1.58 ms: 1.01x slower                                                       |
| fannkuch                 | 258 ms                                                      | 261 ms: 1.01x slower                                                        |
| regex_v8                 | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 74.5 ms: 1.02x slower                                                       |
| nbody                    | 71.0 ms                                                     | 73.5 ms: 1.04x slower                                                       |
| async_generators         | 219 ms                                                      | 228 ms: 1.04x slower                                                        |
| bench_mp_pool            | 59.9 ms                                                     | 62.4 ms: 1.04x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.17 us: 1.04x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.89 us: 1.08x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.6 us: 1.09x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 17.8 ms: 1.16x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.62 ms: 1.21x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.7 ms: 1.22x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                                |

Benchmark hidden because not significant (2): json, python_startup
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-c47be17/bm-20231117-pythonperf1-amd64-mdboom-alternative_workarou-3.13.0a1+-c47be17.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
