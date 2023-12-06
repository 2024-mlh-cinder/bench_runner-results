
# Results vs. 3.10.4

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: windows-amd64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.80 ms: 1.25x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| tornado_http   | 106 ms                                                      | 87.5 ms: 1.21x faster                                                       |
| Geometric mean | (ref)                                                       | 1.20x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 266 ms: 1.60x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 714 ms: 1.50x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 339 ms: 1.49x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 447 ms: 1.38x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.49x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 52.3 ms: 1.18x faster                                                       |
| nbody          | 71.0 ms                                                     | 74.3 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 79.2 ms: 1.29x faster                                                       |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| regex_effbot   | 1.56 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.69 ms: 1.54x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 179 us: 1.45x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 130 us: 1.37x faster                                                        |
| tomli_loads          | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.2 ms: 1.16x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.19 us: 1.11x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 91.0 ms: 1.06x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                                       |
| xml_etree_generate   | 54.5 ms                                                     | 54.2 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 6.96 us: 1.01x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.86 us: 1.06x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.2 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.12x faster                                                                |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.3 ms: 1.03x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.3 ms: 1.19x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.46 ms: 1.39x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 75.9 us: 4.44x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.06 ms: 2.01x faster                                                       |
| raytrace                 | 266 ms                                                      | 162 ms: 1.65x faster                                                        |
| richards_super           | 50.3 ms                                                     | 30.9 ms: 1.63x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 57.6 ns: 1.62x faster                                                       |
| async_tree_none          | 424 ms                                                      | 266 ms: 1.60x faster                                                        |
| sqlglot_parse            | 1.20 ms                                                     | 759 us: 1.59x faster                                                        |
| comprehensions           | 16.6 us                                                     | 10.6 us: 1.56x faster                                                       |
| go                       | 135 ms                                                      | 86.5 ms: 1.56x faster                                                       |
| scimark_lu               | 84.0 ms                                                     | 54.4 ms: 1.54x faster                                                       |
| json_dumps               | 8.77 ms                                                     | 5.69 ms: 1.54x faster                                                       |
| asyncio_tcp              | 717 ms                                                      | 470 ms: 1.53x faster                                                        |
| async_tree_io            | 1.07 sec                                                    | 714 ms: 1.50x faster                                                        |
| generators               | 31.8 ms                                                     | 21.3 ms: 1.49x faster                                                       |
| async_tree_memoization   | 505 ms                                                      | 339 ms: 1.49x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 974 us: 1.48x faster                                                        |
| chaos                    | 59.5 ms                                                     | 40.6 ms: 1.47x faster                                                       |
| richards                 | 40.6 ms                                                     | 27.7 ms: 1.46x faster                                                       |
| hexiom                   | 5.59 ms                                                     | 3.85 ms: 1.45x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 179 us: 1.45x faster                                                        |
| scimark_monte_carlo      | 58.0 ms                                                     | 40.3 ms: 1.44x faster                                                       |
| crypto_pyaes             | 63.1 ms                                                     | 44.6 ms: 1.42x faster                                                       |
| mako                     | 8.98 ms                                                     | 6.46 ms: 1.39x faster                                                       |
| pyflate                  | 402 ms                                                      | 291 ms: 1.38x faster                                                        |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 447 ms: 1.38x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 130 us: 1.37x faster                                                        |
| scimark_sor              | 105 ms                                                      | 80.7 ms: 1.30x faster                                                       |
| regex_compile            | 102 ms                                                      | 79.2 ms: 1.29x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.35 sec: 1.27x faster                                                      |
| sympy_sum                | 105 ms                                                      | 82.8 ms: 1.27x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 62.8 ms: 1.26x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.80 ms: 1.25x faster                                                       |
| sympy_str                | 193 ms                                                      | 158 ms: 1.22x faster                                                        |
| sqlite_synth             | 1.90 us                                                     | 1.55 us: 1.22x faster                                                       |
| sympy_integrate          | 15.0 ms                                                     | 12.3 ms: 1.22x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.54 sec: 1.22x faster                                                      |
| deepcopy_memo            | 29.0 us                                                     | 23.8 us: 1.22x faster                                                       |
| mypy2                    | 347 ms                                                      | 286 ms: 1.21x faster                                                        |
| pprint_pformat           | 1.22 sec                                                    | 1.01 sec: 1.21x faster                                                      |
| tornado_http             | 106 ms                                                      | 87.5 ms: 1.21x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 40.5 ms: 1.20x faster                                                       |
| pprint_safe_repr         | 594 ms                                                      | 496 ms: 1.20x faster                                                        |
| nqueens                  | 68.3 ms                                                     | 57.4 ms: 1.19x faster                                                       |
| sqlglot_optimize         | 39.4 ms                                                     | 33.2 ms: 1.19x faster                                                       |
| sympy_expand             | 320 ms                                                      | 271 ms: 1.18x faster                                                        |
| float                    | 61.7 ms                                                     | 52.3 ms: 1.18x faster                                                       |
| deepcopy                 | 259 us                                                      | 219 us: 1.18x faster                                                        |
| sqlglot_normalize        | 207 ms                                                      | 175 ms: 1.18x faster                                                        |
| coroutines               | 15.5 ms                                                     | 13.3 ms: 1.16x faster                                                       |
| tomli_loads              | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                                      |
| xml_etree_process        | 43.1 ms                                                     | 37.2 ms: 1.16x faster                                                       |
| 2to3                     | 239 ms                                                      | 209 ms: 1.14x faster                                                        |
| deepcopy_reduce          | 2.22 us                                                     | 1.95 us: 1.14x faster                                                       |
| pycparser                | 905 ms                                                      | 802 ms: 1.13x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.38 ms: 1.12x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 718 us: 1.11x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.19 us: 1.11x faster                                                       |
| bench_thread_pool        | 913 us                                                      | 830 us: 1.10x faster                                                        |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.92 sec: 1.09x faster                                                      |
| scimark_fft              | 187 ms                                                      | 174 ms: 1.08x faster                                                        |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                                        |
| xml_etree_parse          | 96.8 ms                                                     | 91.0 ms: 1.06x faster                                                       |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                       |
| fannkuch                 | 258 ms                                                      | 246 ms: 1.05x faster                                                        |
| logging_format           | 6.73 us                                                     | 6.48 us: 1.04x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.07 us: 1.03x faster                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                                       |
| xml_etree_generate       | 54.5 ms                                                     | 54.2 ms: 1.01x faster                                                       |
| meteor_contest           | 73.8 ms                                                     | 74.1 ms: 1.00x slower                                                       |
| pickle                   | 6.87 us                                                     | 6.96 us: 1.01x slower                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.59 ms: 1.01x slower                                                       |
| regex_v8                 | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                                       |
| async_generators         | 219 ms                                                      | 226 ms: 1.03x slower                                                        |
| python_startup           | 19.7 ms                                                     | 20.3 ms: 1.03x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 62.4 ms: 1.04x slower                                                       |
| nbody                    | 71.0 ms                                                     | 74.3 ms: 1.05x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.86 us: 1.06x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.2 us: 1.06x slower                                                       |
| gc_traversal             | 1.40 ms                                                     | 1.51 ms: 1.08x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 79.0 ms: 1.08x slower                                                       |
| unpack_sequence          | 40.0 ns                                                     | 47.3 ns: 1.18x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.3 ms: 1.19x slower                                                       |
| coverage                 | 38.4 ms                                                     | 46.1 ms: 1.20x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.76 ms: 1.25x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                                |

Benchmark hidden because not significant (3): json, unpickle_list, pidigits
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-fa84e5f/bm-20231111-pythonperf1-amd64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
