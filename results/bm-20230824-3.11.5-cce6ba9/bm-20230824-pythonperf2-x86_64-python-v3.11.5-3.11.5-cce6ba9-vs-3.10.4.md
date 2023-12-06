
# Results vs. 3.10.4

- fork: python
- ref: v3.11.5
- machine: linux-x86_64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.21x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 285 ms: 1.23x faster                                         |
| chameleon      | 9.72 ms                                                      | 7.28 ms: 1.34x faster                                        |
| docutils       | 3.40 sec                                                     | 2.84 sec: 1.20x faster                                       |
| html5lib       | 94.6 ms                                                      | 71.4 ms: 1.33x faster                                        |
| tornado_http   | 152 ms                                                       | 124 ms: 1.23x faster                                         |
| Geometric mean | (ref)                                                        | 1.26x faster                                                 |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 90.5 ms: 1.52x faster                                        |
| float          | 110 ms                                                       | 74.3 ms: 1.48x faster                                        |
| pidigits       | 271 ms                                                       | 251 ms: 1.08x faster                                         |
| Geometric mean | (ref)                                                        | 1.34x faster                                                 |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 155 ms: 1.25x faster                                         |
| regex_dna      | 259 ms                                                       | 227 ms: 1.14x faster                                         |
| regex_v8       | 26.6 ms                                                      | 24.2 ms: 1.10x faster                                        |
| regex_effbot   | 2.99 ms                                                      | 3.31 ms: 1.11x slower                                        |
| Geometric mean | (ref)                                                        | 1.09x faster                                                 |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 320 us: 1.43x faster                                         |
| xml_etree_process    | 76.0 ms                                                      | 56.1 ms: 1.35x faster                                        |
| unpickle_pure_python | 321 us                                                       | 241 us: 1.33x faster                                         |
| tomli_loads          | 2.97 sec                                                     | 2.30 sec: 1.29x faster                                       |
| xml_etree_generate   | 94.6 ms                                                      | 80.8 ms: 1.17x faster                                        |
| json_loads           | 30.0 us                                                      | 27.9 us: 1.07x faster                                        |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.07x faster                                         |
| unpickle             | 14.2 us                                                      | 13.3 us: 1.07x faster                                        |
| json_dumps           | 14.2 ms                                                      | 13.5 ms: 1.05x faster                                        |
| pickle_list          | 4.11 us                                                      | 3.94 us: 1.04x faster                                        |
| xml_etree_parse      | 162 ms                                                       | 157 ms: 1.03x faster                                         |
| pickle               | 9.94 us                                                      | 9.98 us: 1.00x slower                                        |
| unpickle_list        | 4.49 us                                                      | 4.63 us: 1.03x slower                                        |
| pickle_dict          | 30.0 us                                                      | 33.1 us: 1.10x slower                                        |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                 |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 10.8 ms: 1.06x faster                                        |
| python_startup_no_site | 7.32 ms                                                      | 7.79 ms: 1.06x slower                                        |
| Geometric mean         | (ref)                                                        | 1.00x faster                                                 |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|-----------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| mako            | 14.7 ms                                                      | 10.6 ms: 1.38x faster                                        |
| django_template | 51.5 ms                                                      | 40.7 ms: 1.27x faster                                        |
| genshi_text     | 31.5 ms                                                      | 25.5 ms: 1.24x faster                                        |
| genshi_xml      | 64.7 ms                                                      | 55.7 ms: 1.16x faster                                        |
| Geometric mean  | (ref)                                                        | 1.26x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf2-x86_64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------:|
| deltablue                | 7.47 ms                                                      | 4.03 ms: 1.85x faster                                        |
| logging_silent           | 166 ns                                                       | 100 ns: 1.66x faster                                         |
| scimark_sor              | 177 ms                                                       | 111 ms: 1.59x faster                                         |
| go                       | 259 ms                                                       | 163 ms: 1.59x faster                                         |
| scimark_monte_carlo      | 109 ms                                                       | 69.0 ms: 1.59x faster                                        |
| pyflate                  | 697 ms                                                       | 441 ms: 1.58x faster                                         |
| raytrace                 | 488 ms                                                       | 318 ms: 1.53x faster                                         |
| nbody                    | 137 ms                                                       | 90.5 ms: 1.52x faster                                        |
| bench_mp_pool            | 7.18 ms                                                      | 4.75 ms: 1.51x faster                                        |
| float                    | 110 ms                                                       | 74.3 ms: 1.48x faster                                        |
| sqlglot_parse            | 2.26 ms                                                      | 1.54 ms: 1.47x faster                                        |
| spectral_norm            | 136 ms                                                       | 93.3 ms: 1.46x faster                                        |
| crypto_pyaes             | 118 ms                                                       | 81.7 ms: 1.45x faster                                        |
| scimark_lu               | 164 ms                                                       | 113 ms: 1.44x faster                                         |
| richards                 | 74.1 ms                                                      | 51.6 ms: 1.44x faster                                        |
| pickle_pure_python       | 457 us                                                       | 320 us: 1.43x faster                                         |
| sqlglot_transpile        | 2.71 ms                                                      | 1.91 ms: 1.42x faster                                        |
| richards_super           | 90.8 ms                                                      | 64.3 ms: 1.41x faster                                        |
| mako                     | 14.7 ms                                                      | 10.6 ms: 1.38x faster                                        |
| async_tree_io            | 1.61 sec                                                     | 1.17 sec: 1.37x faster                                       |
| chaos                    | 107 ms                                                       | 79.1 ms: 1.35x faster                                        |
| xml_etree_process        | 76.0 ms                                                      | 56.1 ms: 1.35x faster                                        |
| pprint_safe_repr         | 1.05 sec                                                     | 775 ms: 1.35x faster                                         |
| async_tree_none          | 700 ms                                                       | 518 ms: 1.35x faster                                         |
| pprint_pformat           | 2.15 sec                                                     | 1.61 sec: 1.34x faster                                       |
| chameleon                | 9.72 ms                                                      | 7.28 ms: 1.34x faster                                        |
| unpickle_pure_python     | 321 us                                                       | 241 us: 1.33x faster                                         |
| async_generators         | 422 ms                                                       | 318 ms: 1.33x faster                                         |
| html5lib                 | 94.6 ms                                                      | 71.4 ms: 1.33x faster                                        |
| async_tree_memoization   | 824 ms                                                       | 624 ms: 1.32x faster                                         |
| hexiom                   | 9.52 ms                                                      | 7.21 ms: 1.32x faster                                        |
| deepcopy_memo            | 48.9 us                                                      | 37.4 us: 1.31x faster                                        |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.00 ms: 1.30x faster                                        |
| tomli_loads              | 2.97 sec                                                     | 2.30 sec: 1.29x faster                                       |
| scimark_fft              | 359 ms                                                       | 280 ms: 1.28x faster                                         |
| unpack_sequence          | 59.5 ns                                                      | 46.9 ns: 1.27x faster                                        |
| django_template          | 51.5 ms                                                      | 40.7 ms: 1.27x faster                                        |
| pycparser                | 1.66 sec                                                     | 1.32 sec: 1.26x faster                                       |
| regex_compile            | 194 ms                                                       | 155 ms: 1.25x faster                                         |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 765 ms: 1.24x faster                                         |
| genshi_text              | 31.5 ms                                                      | 25.5 ms: 1.24x faster                                        |
| tornado_http             | 152 ms                                                       | 124 ms: 1.23x faster                                         |
| 2to3                     | 350 ms                                                       | 285 ms: 1.23x faster                                         |
| dulwich_log              | 80.1 ms                                                      | 65.3 ms: 1.23x faster                                        |
| logging_format           | 9.57 us                                                      | 7.83 us: 1.22x faster                                        |
| aiohttp                  | 1.21 ms                                                      | 991 us: 1.22x faster                                         |
| logging_simple           | 8.90 us                                                      | 7.33 us: 1.21x faster                                        |
| sqlalchemy_declarative   | 187 ms                                                       | 154 ms: 1.21x faster                                         |
| docutils                 | 3.40 sec                                                     | 2.84 sec: 1.20x faster                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 58.9 ms: 1.19x faster                                        |
| deepcopy_reduce          | 4.03 us                                                      | 3.40 us: 1.18x faster                                        |
| thrift                   | 1.16 ms                                                      | 986 us: 1.18x faster                                         |
| gunicorn                 | 1.17 ms                                                      | 999 us: 1.17x faster                                         |
| xml_etree_generate       | 94.6 ms                                                      | 80.8 ms: 1.17x faster                                        |
| genshi_xml               | 64.7 ms                                                      | 55.7 ms: 1.16x faster                                        |
| sqlite_synth             | 2.97 us                                                      | 2.55 us: 1.16x faster                                        |
| sqlglot_normalize        | 144 ms                                                       | 124 ms: 1.16x faster                                         |
| sqlalchemy_imperative    | 22.6 ms                                                      | 19.5 ms: 1.16x faster                                        |
| bench_thread_pool        | 1.14 ms                                                      | 989 us: 1.15x faster                                         |
| deepcopy                 | 454 us                                                       | 396 us: 1.15x faster                                         |
| flaskblogging            | 4.39 ms                                                      | 3.83 ms: 1.15x faster                                        |
| regex_dna                | 259 ms                                                       | 227 ms: 1.14x faster                                         |
| pathlib                  | 21.7 ms                                                      | 19.0 ms: 1.14x faster                                        |
| dask                     | 463 ms                                                       | 409 ms: 1.13x faster                                         |
| create_gc_cycles         | 1.82 ms                                                      | 1.62 ms: 1.12x faster                                        |
| nqueens                  | 112 ms                                                       | 102 ms: 1.11x faster                                         |
| regex_v8                 | 26.6 ms                                                      | 24.2 ms: 1.10x faster                                        |
| coroutines               | 30.4 ms                                                      | 27.7 ms: 1.10x faster                                        |
| sympy_integrate          | 28.1 ms                                                      | 25.6 ms: 1.10x faster                                        |
| mdp                      | 3.03 sec                                                     | 2.78 sec: 1.09x faster                                       |
| pylint                   | 562 ms                                                       | 517 ms: 1.09x faster                                         |
| sympy_expand             | 599 ms                                                       | 555 ms: 1.08x faster                                         |
| pidigits                 | 271 ms                                                       | 251 ms: 1.08x faster                                         |
| comprehensions           | 26.9 us                                                      | 25.0 us: 1.08x faster                                        |
| json_loads               | 30.0 us                                                      | 27.9 us: 1.07x faster                                        |
| json                     | 5.96 ms                                                      | 5.55 ms: 1.07x faster                                        |
| xml_etree_iterparse      | 110 ms                                                       | 103 ms: 1.07x faster                                         |
| unpickle                 | 14.2 us                                                      | 13.3 us: 1.07x faster                                        |
| python_startup           | 11.5 ms                                                      | 10.8 ms: 1.06x faster                                        |
| sympy_str                | 358 ms                                                       | 336 ms: 1.06x faster                                         |
| telco                    | 7.14 ms                                                      | 6.75 ms: 1.06x faster                                        |
| fannkuch                 | 496 ms                                                       | 470 ms: 1.05x faster                                         |
| json_dumps               | 14.2 ms                                                      | 13.5 ms: 1.05x faster                                        |
| generators               | 58.0 ms                                                      | 55.4 ms: 1.05x faster                                        |
| sympy_sum                | 193 ms                                                       | 184 ms: 1.05x faster                                         |
| meteor_contest           | 137 ms                                                       | 131 ms: 1.04x faster                                         |
| pickle_list              | 4.11 us                                                      | 3.94 us: 1.04x faster                                        |
| asyncio_tcp              | 782 ms                                                       | 753 ms: 1.04x faster                                         |
| xml_etree_parse          | 162 ms                                                       | 157 ms: 1.03x faster                                         |
| typing_runtime_protocols | 523 us                                                       | 518 us: 1.01x faster                                         |
| pickle                   | 9.94 us                                                      | 9.98 us: 1.00x slower                                        |
| unpickle_list            | 4.49 us                                                      | 4.63 us: 1.03x slower                                        |
| python_startup_no_site   | 7.32 ms                                                      | 7.79 ms: 1.06x slower                                        |
| gc_traversal             | 3.45 ms                                                      | 3.77 ms: 1.09x slower                                        |
| pickle_dict              | 30.0 us                                                      | 33.1 us: 1.10x slower                                        |
| regex_effbot             | 2.99 ms                                                      | 3.31 ms: 1.11x slower                                        |
| mypy2                    | 466 ms                                                       | 537 ms: 1.15x slower                                         |
| Geometric mean           | (ref)                                                        | 1.21x faster                                                 |

Benchmark hidden because not significant (1): asyncio_tcp_ssl
Ignored benchmarks (1) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: coverage


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
