
# Results vs. 3.10.4

- fork: python
- ref: 3faf8e586d36e73faba1
- machine: darwin-arm64
- commit hash: 3faf8e5
- commit date: 2023-11-25
- overall geometric mean: 1.09x faster
- HPT reliability: 99.77%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 182 ms: 1.04x faster                                                   |
| chameleon      | 6.00 ms                                                             | 5.28 ms: 1.14x faster                                                  |
| docutils       | 1.71 sec                                                            | 1.55 sec: 1.10x faster                                                 |
| tornado_http   | 89.1 ms                                                             | 73.5 ms: 1.21x faster                                                  |
| Geometric mean | (ref)                                                               | 1.12x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 381 ms                                                              | 264 ms: 1.44x faster                                                   |
| async_tree_memoization  | 466 ms                                                              | 340 ms: 1.37x faster                                                   |
| async_tree_io           | 972 ms                                                              | 718 ms: 1.35x faster                                                   |
| async_tree_cpu_io_mixed | 640 ms                                                              | 535 ms: 1.20x faster                                                   |
| Geometric mean          | (ref)                                                               | 1.34x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 281 ms                                                              | 283 ms: 1.01x slower                                                   |
| nbody          | 88.4 ms                                                             | 91.1 ms: 1.03x slower                                                  |
| float          | 66.8 ms                                                             | 70.6 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                               | 1.03x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 173 ms                                                              | 152 ms: 1.14x faster                                                   |
| regex_compile  | 92.8 ms                                                             | 89.9 ms: 1.03x faster                                                  |
| regex_v8       | 17.2 ms                                                             | 17.1 ms: 1.01x faster                                                  |
| regex_effbot   | 2.46 ms                                                             | 2.60 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                               | 1.03x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|----------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 210 us: 1.30x faster                                                   |
| json_dumps           | 7.95 ms                                                             | 6.64 ms: 1.20x faster                                                  |
| xml_etree_process    | 45.8 ms                                                             | 42.5 ms: 1.08x faster                                                  |
| unpickle_pure_python | 190 us                                                              | 178 us: 1.07x faster                                                   |
| unpickle             | 8.88 us                                                             | 9.11 us: 1.03x slower                                                  |
| tomli_loads          | 1.66 sec                                                            | 1.71 sec: 1.03x slower                                                 |
| pickle               | 7.01 us                                                             | 7.41 us: 1.06x slower                                                  |
| pickle_dict          | 16.9 us                                                             | 17.9 us: 1.06x slower                                                  |
| json_loads           | 16.3 us                                                             | 17.4 us: 1.07x slower                                                  |
| pickle_list          | 2.70 us                                                             | 2.95 us: 1.09x slower                                                  |
| unpickle_list        | 2.86 us                                                             | 3.14 us: 1.10x slower                                                  |
| xml_etree_iterparse  | 71.9 ms                                                             | 81.5 ms: 1.13x slower                                                  |
| xml_etree_generate   | 52.4 ms                                                             | 62.7 ms: 1.20x slower                                                  |
| Geometric mean       | (ref)                                                               | 1.01x slower                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 8.83 ms                                                             | 10.4 ms: 1.18x slower                                                  |
| Geometric mean         | (ref)                                                               | 1.08x slower                                                           |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|-----------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.78 ms                                                             | 9.81 ms: 1.00x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5 |
|--------------------------|:-------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 335 us                                                              | 81.6 us: 4.11x faster                                                  |
| asyncio_tcp              | 682 ms                                                              | 405 ms: 1.68x faster                                                   |
| logging_silent           | 114 ns                                                              | 73.2 ns: 1.56x faster                                                  |
| richards_super           | 57.4 ms                                                             | 38.0 ms: 1.51x faster                                                  |
| raytrace                 | 293 ms                                                              | 199 ms: 1.47x faster                                                   |
| async_tree_none          | 381 ms                                                              | 264 ms: 1.44x faster                                                   |
| richards                 | 47.7 ms                                                             | 34.1 ms: 1.40x faster                                                  |
| sqlglot_parse            | 1.20 ms                                                             | 867 us: 1.39x faster                                                   |
| async_tree_memoization   | 466 ms                                                              | 340 ms: 1.37x faster                                                   |
| deltablue                | 4.93 ms                                                             | 3.63 ms: 1.36x faster                                                  |
| unpack_sequence          | 38.7 ns                                                             | 28.6 ns: 1.35x faster                                                  |
| async_tree_io            | 972 ms                                                              | 718 ms: 1.35x faster                                                   |
| sqlglot_transpile        | 1.40 ms                                                             | 1.05 ms: 1.33x faster                                                  |
| go                       | 148 ms                                                              | 113 ms: 1.31x faster                                                   |
| scimark_lu               | 102 ms                                                              | 78.4 ms: 1.30x faster                                                  |
| pickle_pure_python       | 272 us                                                              | 210 us: 1.30x faster                                                   |
| chaos                    | 64.0 ms                                                             | 49.7 ms: 1.29x faster                                                  |
| crypto_pyaes             | 70.7 ms                                                             | 55.7 ms: 1.27x faster                                                  |
| create_gc_cycles         | 870 us                                                              | 703 us: 1.24x faster                                                   |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.31 sec: 1.23x faster                                                 |
| generators               | 32.1 ms                                                             | 26.0 ms: 1.23x faster                                                  |
| scimark_sor              | 134 ms                                                              | 109 ms: 1.23x faster                                                   |
| tornado_http             | 89.1 ms                                                             | 73.5 ms: 1.21x faster                                                  |
| pycparser                | 863 ms                                                              | 719 ms: 1.20x faster                                                   |
| json_dumps               | 7.95 ms                                                             | 6.64 ms: 1.20x faster                                                  |
| deepcopy_memo            | 33.2 us                                                             | 27.8 us: 1.20x faster                                                  |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 535 ms: 1.20x faster                                                   |
| logging_simple           | 4.25 us                                                             | 3.71 us: 1.15x faster                                                  |
| logging_format           | 4.59 us                                                             | 4.02 us: 1.14x faster                                                  |
| dulwich_log              | 34.9 ms                                                             | 30.6 ms: 1.14x faster                                                  |
| regex_dna                | 173 ms                                                              | 152 ms: 1.14x faster                                                   |
| chameleon                | 6.00 ms                                                             | 5.28 ms: 1.14x faster                                                  |
| deepcopy                 | 269 us                                                              | 239 us: 1.13x faster                                                   |
| pyflate                  | 420 ms                                                              | 378 ms: 1.11x faster                                                   |
| docutils                 | 1.71 sec                                                            | 1.55 sec: 1.10x faster                                                 |
| mdp                      | 1.87 sec                                                            | 1.73 sec: 1.08x faster                                                 |
| xml_etree_process        | 45.8 ms                                                             | 42.5 ms: 1.08x faster                                                  |
| dask                     | 251 ms                                                              | 233 ms: 1.08x faster                                                   |
| deepcopy_reduce          | 2.27 us                                                             | 2.11 us: 1.08x faster                                                  |
| sympy_sum                | 91.1 ms                                                             | 84.8 ms: 1.07x faster                                                  |
| unpickle_pure_python     | 190 us                                                              | 178 us: 1.07x faster                                                   |
| sympy_integrate          | 12.9 ms                                                             | 12.3 ms: 1.05x faster                                                  |
| pprint_safe_repr         | 625 ms                                                              | 596 ms: 1.05x faster                                                   |
| scimark_monte_carlo      | 63.2 ms                                                             | 60.3 ms: 1.05x faster                                                  |
| pprint_pformat           | 1.28 sec                                                            | 1.23 sec: 1.04x faster                                                 |
| 2to3                     | 189 ms                                                              | 182 ms: 1.04x faster                                                   |
| regex_compile            | 92.8 ms                                                             | 89.9 ms: 1.03x faster                                                  |
| sympy_str                | 165 ms                                                              | 160 ms: 1.03x faster                                                   |
| comprehensions           | 16.8 us                                                             | 16.5 us: 1.02x faster                                                  |
| sympy_expand             | 268 ms                                                              | 264 ms: 1.01x faster                                                   |
| regex_v8                 | 17.2 ms                                                             | 17.1 ms: 1.01x faster                                                  |
| asyncio_websockets       | 408 ms                                                              | 409 ms: 1.00x slower                                                   |
| mako                     | 9.78 ms                                                             | 9.81 ms: 1.00x slower                                                  |
| pidigits                 | 281 ms                                                              | 283 ms: 1.01x slower                                                   |
| gc_traversal             | 2.38 ms                                                             | 2.41 ms: 1.01x slower                                                  |
| unpickle                 | 8.88 us                                                             | 9.11 us: 1.03x slower                                                  |
| nbody                    | 88.4 ms                                                             | 91.1 ms: 1.03x slower                                                  |
| tomli_loads              | 1.66 sec                                                            | 1.71 sec: 1.03x slower                                                 |
| pathlib                  | 24.0 ms                                                             | 24.9 ms: 1.04x slower                                                  |
| hexiom                   | 6.05 ms                                                             | 6.31 ms: 1.04x slower                                                  |
| sqlglot_optimize         | 36.3 ms                                                             | 38.2 ms: 1.05x slower                                                  |
| meteor_contest           | 77.6 ms                                                             | 82.0 ms: 1.06x slower                                                  |
| regex_effbot             | 2.46 ms                                                             | 2.60 ms: 1.06x slower                                                  |
| pickle                   | 7.01 us                                                             | 7.41 us: 1.06x slower                                                  |
| float                    | 66.8 ms                                                             | 70.6 ms: 1.06x slower                                                  |
| pickle_dict              | 16.9 us                                                             | 17.9 us: 1.06x slower                                                  |
| json_loads               | 16.3 us                                                             | 17.4 us: 1.07x slower                                                  |
| sqlglot_normalize        | 187 ms                                                              | 204 ms: 1.09x slower                                                   |
| pickle_list              | 2.70 us                                                             | 2.95 us: 1.09x slower                                                  |
| unpickle_list            | 2.86 us                                                             | 3.14 us: 1.10x slower                                                  |
| bench_mp_pool            | 40.0 ms                                                             | 44.6 ms: 1.11x slower                                                  |
| xml_etree_iterparse      | 71.9 ms                                                             | 81.5 ms: 1.13x slower                                                  |
| nqueens                  | 62.5 ms                                                             | 71.9 ms: 1.15x slower                                                  |
| coverage                 | 41.0 ms                                                             | 47.9 ms: 1.17x slower                                                  |
| fannkuch                 | 295 ms                                                              | 345 ms: 1.17x slower                                                   |
| python_startup_no_site   | 8.83 ms                                                             | 10.4 ms: 1.18x slower                                                  |
| scimark_fft              | 216 ms                                                              | 256 ms: 1.18x slower                                                   |
| sqlite_synth             | 1.45 us                                                             | 1.71 us: 1.18x slower                                                  |
| xml_etree_generate       | 52.4 ms                                                             | 62.7 ms: 1.20x slower                                                  |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 4.30 ms: 1.33x slower                                                  |
| async_generators         | 230 ms                                                              | 313 ms: 1.36x slower                                                   |
| telco                    | 3.41 ms                                                             | 4.86 ms: 1.43x slower                                                  |
| Geometric mean           | (ref)                                                               | 1.09x faster                                                           |

Benchmark hidden because not significant (7): mypy2, xml_etree_parse, python_startup, bench_thread_pool, json, coroutines, spectral_norm
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231125-3.13.0a2+-3faf8e5-PYTHON_UOPS/bm-20231125-darwin-arm64-python-3faf8e586d36e73faba1-3.13.0a2+-3faf8e5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 99.77% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
