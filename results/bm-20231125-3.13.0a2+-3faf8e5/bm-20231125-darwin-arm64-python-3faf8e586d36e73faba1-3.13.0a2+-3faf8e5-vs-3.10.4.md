
# Results vs. 3.10.4

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 174 ms: 1.08x faster                                                   |
| chameleon      | 6.00 ms                                                             | 5.13 ms: 1.17x faster                                                  |
| docutils       | 1.71 sec                                                            | 1.51 sec: 1.13x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 71.9 ms: 1.24x faster                                                  |
| Geometric mean | (ref)                                                               | 1.15x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 381 ms                                                              | 254 ms: 1.50x faster                                                   |
| async_tree_memoization  | 466 ms                                                              | 331 ms: 1.41x faster                                                   |
| async_tree_io           | 972 ms                                                              | 704 ms: 1.38x faster                                                   |
| async_tree_cpu_io_mixed | 640 ms                                                              | 526 ms: 1.22x faster                                                   |
| Geometric mean          | (ref)                                                               | 1.37x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 66.8 ms                                                             | 58.1 ms: 1.15x faster                                                  |
| nbody          | 88.4 ms                                                             | 81.9 ms: 1.08x faster                                                  |
| pidigits       | 281 ms                                                              | 282 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                               | 1.07x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 79.5 ms: 1.17x faster                                                  |
| regex_dna      | 173 ms                                                              | 152 ms: 1.14x faster                                                   |
| regex_v8       | 17.2 ms                                                             | 16.9 ms: 1.02x faster                                                  |
| regex_effbot   | 2.46 ms                                                             | 2.64 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                               | 1.06x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 209 us: 1.31x faster                                                   |
| json_dumps           | 7.95 ms                                                             | 6.55 ms: 1.21x faster                                                  |
| unpickle_pure_python | 190 us                                                              | 165 us: 1.15x faster                                                   |
| xml_etree_process    | 45.8 ms                                                             | 40.6 ms: 1.13x faster                                                  |
| tomli_loads          | 1.66 sec                                                            | 1.60 sec: 1.04x faster                                                 |
| xml_etree_parse      | 108 ms                                                              | 107 ms: 1.01x faster                                                   |
| unpickle             | 8.88 us                                                             | 9.08 us: 1.02x slower                                                  |
| pickle               | 7.01 us                                                             | 7.41 us: 1.06x slower                                                  |
| xml_etree_iterparse  | 71.9 ms                                                             | 76.4 ms: 1.06x slower                                                  |
| pickle_dict          | 16.9 us                                                             | 18.0 us: 1.07x slower                                                  |
| json_loads           | 16.3 us                                                             | 17.4 us: 1.07x slower                                                  |
| pickle_list          | 2.70 us                                                             | 2.89 us: 1.07x slower                                                  |
| unpickle_list        | 2.86 us                                                             | 3.13 us: 1.10x slower                                                  |
| xml_etree_generate   | 52.4 ms                                                             | 58.2 ms: 1.11x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 11.6 ms: 1.02x faster                                                  |
| python_startup_no_site | 8.83 ms                                                             | 10.1 ms: 1.15x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.06x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.78 ms                                                             | 7.78 ms: 1.26x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 335 us                                                              | 77.6 us: 4.32x faster                                                  |
| deltablue                | 4.93 ms                                                             | 2.45 ms: 2.01x faster                                                  |
| raytrace                 | 293 ms                                                              | 183 ms: 1.61x faster                                                   |
| logging_silent           | 114 ns                                                              | 71.4 ns: 1.60x faster                                                  |
| asyncio_tcp              | 682 ms                                                              | 430 ms: 1.59x faster                                                   |
| async_tree_none          | 381 ms                                                              | 254 ms: 1.50x faster                                                   |
| chaos                    | 64.0 ms                                                             | 43.0 ms: 1.49x faster                                                  |
| richards_super           | 57.4 ms                                                             | 38.9 ms: 1.48x faster                                                  |
| sqlglot_parse            | 1.20 ms                                                             | 834 us: 1.44x faster                                                   |
| crypto_pyaes             | 70.7 ms                                                             | 49.2 ms: 1.44x faster                                                  |
| async_tree_memoization   | 466 ms                                                              | 331 ms: 1.41x faster                                                   |
| go                       | 148 ms                                                              | 106 ms: 1.40x faster                                                   |
| sqlglot_transpile        | 1.40 ms                                                             | 1.01 ms: 1.38x faster                                                  |
| async_tree_io            | 972 ms                                                              | 704 ms: 1.38x faster                                                   |
| richards                 | 47.7 ms                                                             | 34.8 ms: 1.37x faster                                                  |
| scimark_lu               | 102 ms                                                              | 74.8 ms: 1.36x faster                                                  |
| spectral_norm            | 101 ms                                                              | 75.1 ms: 1.35x faster                                                  |
| unpack_sequence          | 38.7 ns                                                             | 29.0 ns: 1.34x faster                                                  |
| comprehensions           | 16.8 us                                                             | 12.6 us: 1.34x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 209 us: 1.31x faster                                                   |
| scimark_monte_carlo      | 63.2 ms                                                             | 48.6 ms: 1.30x faster                                                  |
| deepcopy_memo            | 33.2 us                                                             | 26.0 us: 1.28x faster                                                  |
| mako                     | 9.78 ms                                                             | 7.78 ms: 1.26x faster                                                  |
| scimark_sor              | 134 ms                                                              | 107 ms: 1.25x faster                                                   |
| tornado_http             | 89.1 ms                                                             | 71.9 ms: 1.24x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 704 us: 1.24x faster                                                   |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.31 sec: 1.23x faster                                                 |
| generators               | 32.1 ms                                                             | 26.1 ms: 1.23x faster                                                  |
| pyflate                  | 420 ms                                                              | 344 ms: 1.22x faster                                                   |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 526 ms: 1.22x faster                                                   |
| json_dumps               | 7.95 ms                                                             | 6.55 ms: 1.21x faster                                                  |
| pycparser                | 863 ms                                                              | 712 ms: 1.21x faster                                                   |
| hexiom                   | 6.05 ms                                                             | 5.03 ms: 1.20x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 76.6 ms: 1.19x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 1.09 sec: 1.17x faster                                                 |
| logging_simple           | 4.25 us                                                             | 3.63 us: 1.17x faster                                                  |
| chameleon                | 6.00 ms                                                             | 5.13 ms: 1.17x faster                                                  |
| pprint_safe_repr         | 625 ms                                                              | 535 ms: 1.17x faster                                                   |
| regex_compile            | 92.8 ms                                                             | 79.5 ms: 1.17x faster                                                  |
| logging_format           | 4.59 us                                                             | 3.95 us: 1.16x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 30.1 ms: 1.16x faster                                                  |
| unpickle_pure_python     | 190 us                                                              | 165 us: 1.15x faster                                                   |
| sympy_integrate          | 12.9 ms                                                             | 11.2 ms: 1.15x faster                                                  |
| deepcopy                 | 269 us                                                              | 234 us: 1.15x faster                                                   |
| float                    | 66.8 ms                                                             | 58.1 ms: 1.15x faster                                                  |
| mdp                      | 1.87 sec                                                            | 1.64 sec: 1.14x faster                                                 |
| regex_dna                | 173 ms                                                              | 152 ms: 1.14x faster                                                   |
| docutils                 | 1.71 sec                                                            | 1.51 sec: 1.13x faster                                                 |
| mypy2                    | 294 ms                                                              | 260 ms: 1.13x faster                                                   |
| xml_etree_process        | 45.8 ms                                                             | 40.6 ms: 1.13x faster                                                  |
| sympy_str                | 165 ms                                                              | 148 ms: 1.12x faster                                                   |
| dask                     | 251 ms                                                              | 229 ms: 1.10x faster                                                   |
| deepcopy_reduce          | 2.27 us                                                             | 2.08 us: 1.09x faster                                                  |
| 2to3                     | 189 ms                                                              | 174 ms: 1.08x faster                                                   |
| nbody                    | 88.4 ms                                                             | 81.9 ms: 1.08x faster                                                  |
| sympy_expand             | 268 ms                                                              | 256 ms: 1.04x faster                                                   |
| tomli_loads              | 1.66 sec                                                            | 1.60 sec: 1.04x faster                                                 |
| bench_thread_pool        | 534 us                                                              | 516 us: 1.03x faster                                                   |
| meteor_contest           | 77.6 ms                                                             | 75.8 ms: 1.02x faster                                                  |
| coroutines               | 19.7 ms                                                             | 19.2 ms: 1.02x faster                                                  |
| fannkuch                 | 295 ms                                                              | 288 ms: 1.02x faster                                                   |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 3.17 ms: 1.02x faster                                                  |
| regex_v8                 | 17.2 ms                                                             | 16.9 ms: 1.02x faster                                                  |
| python_startup           | 11.8 ms                                                             | 11.6 ms: 1.02x faster                                                  |
| scimark_fft              | 216 ms                                                              | 213 ms: 1.02x faster                                                   |
| sqlglot_optimize         | 36.3 ms                                                             | 35.8 ms: 1.01x faster                                                  |
| json                     | 3.04 ms                                                             | 3.01 ms: 1.01x faster                                                  |
| xml_etree_parse          | 108 ms                                                              | 107 ms: 1.01x faster                                                   |
| pidigits                 | 281 ms                                                              | 282 ms: 1.00x slower                                                   |
| asyncio_websockets       | 408 ms                                                              | 409 ms: 1.00x slower                                                   |
| nqueens                  | 62.5 ms                                                             | 62.6 ms: 1.00x slower                                                  |
| gc_traversal             | 2.38 ms                                                             | 2.40 ms: 1.01x slower                                                  |
| unpickle                 | 8.88 us                                                             | 9.08 us: 1.02x slower                                                  |
| sqlglot_normalize        | 187 ms                                                              | 192 ms: 1.03x slower                                                   |
| pathlib                  | 24.0 ms                                                             | 24.8 ms: 1.03x slower                                                  |
| pickle                   | 7.01 us                                                             | 7.41 us: 1.06x slower                                                  |
| xml_etree_iterparse      | 71.9 ms                                                             | 76.4 ms: 1.06x slower                                                  |
| pickle_dict              | 16.9 us                                                             | 18.0 us: 1.07x slower                                                  |
| json_loads               | 16.3 us                                                             | 17.4 us: 1.07x slower                                                  |
| pickle_list              | 2.70 us                                                             | 2.89 us: 1.07x slower                                                  |
| regex_effbot             | 2.46 ms                                                             | 2.64 ms: 1.07x slower                                                  |
| bench_mp_pool            | 40.0 ms                                                             | 43.8 ms: 1.09x slower                                                  |
| unpickle_list            | 2.86 us                                                             | 3.13 us: 1.10x slower                                                  |
| xml_etree_generate       | 52.4 ms                                                             | 58.2 ms: 1.11x slower                                                  |
| sqlite_synth             | 1.45 us                                                             | 1.64 us: 1.14x slower                                                  |
| python_startup_no_site   | 8.83 ms                                                             | 10.1 ms: 1.15x slower                                                  |
| coverage                 | 41.0 ms                                                             | 47.9 ms: 1.17x slower                                                  |
| async_generators         | 230 ms                                                              | 304 ms: 1.32x slower                                                   |
| telco                    | 3.41 ms                                                             | 4.65 ms: 1.36x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.15x faster                                                           |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231125-3.13.0a2+-3faf8e5/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.08x
