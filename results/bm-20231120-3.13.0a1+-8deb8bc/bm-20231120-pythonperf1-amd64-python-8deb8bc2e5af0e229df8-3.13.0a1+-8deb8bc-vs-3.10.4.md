
# Results vs. 3.10.4

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: windows-amd64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 212 ms: 1.13x faster                                                        |
| chameleon      | 6.02 ms                                                     | 4.75 ms: 1.27x faster                                                       |
| docutils       | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                      |
| tornado_http   | 106 ms                                                      | 95.6 ms: 1.10x faster                                                       |
| Geometric mean | (ref)                                                       | 1.18x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 264 ms: 1.61x faster                                                        |
| async_tree_io           | 1.07 sec                                                    | 722 ms: 1.48x faster                                                        |
| async_tree_memoization  | 505 ms                                                      | 341 ms: 1.48x faster                                                        |
| async_tree_cpu_io_mixed | 617 ms                                                      | 451 ms: 1.37x faster                                                        |
| Geometric mean          | (ref)                                                       | 1.48x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.5 ms: 1.20x faster                                                       |
| nbody          | 71.0 ms                                                     | 71.3 ms: 1.00x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                                |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 78.7 ms: 1.30x faster                                                       |
| regex_dna      | 129 ms                                                      | 117 ms: 1.10x faster                                                        |
| regex_v8       | 15.0 ms                                                     | 14.6 ms: 1.03x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.55 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.10x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.59 ms: 1.57x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 177 us: 1.46x faster                                                        |
| unpickle_pure_python | 177 us                                                      | 127 us: 1.39x faster                                                        |
| tomli_loads          | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.4 ms: 1.15x faster                                                       |
| unpickle             | 9.11 us                                                     | 8.12 us: 1.12x faster                                                       |
| json_loads           | 14.2 us                                                     | 13.3 us: 1.07x faster                                                       |
| xml_etree_parse      | 96.8 ms                                                     | 92.6 ms: 1.05x faster                                                       |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.8 ms: 1.01x faster                                                       |
| pickle               | 6.87 us                                                     | 7.18 us: 1.04x slower                                                       |
| pickle_list          | 2.69 us                                                     | 2.85 us: 1.06x slower                                                       |
| pickle_dict          | 17.1 us                                                     | 18.9 us: 1.10x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                                |

Benchmark hidden because not significant (2): xml_etree_generate, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.3 ms: 1.03x slower                                                       |
| python_startup_no_site | 15.3 ms                                                     | 18.2 ms: 1.19x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.11x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.45 ms: 1.39x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 76.2 us: 4.42x faster                                                       |
| deltablue                | 4.12 ms                                                     | 2.04 ms: 2.02x faster                                                       |
| logging_silent           | 93.4 ns                                                     | 56.2 ns: 1.66x faster                                                       |
| richards_super           | 50.3 ms                                                     | 31.0 ms: 1.63x faster                                                       |
| async_tree_none          | 424 ms                                                      | 264 ms: 1.61x faster                                                        |
| raytrace                 | 266 ms                                                      | 166 ms: 1.60x faster                                                        |
| comprehensions           | 16.6 us                                                     | 10.5 us: 1.58x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                     | 762 us: 1.58x faster                                                        |
| json_dumps               | 8.77 ms                                                     | 5.59 ms: 1.57x faster                                                       |
| go                       | 135 ms                                                      | 86.8 ms: 1.56x faster                                                       |
| chaos                    | 59.5 ms                                                     | 39.3 ms: 1.51x faster                                                       |
| hexiom                   | 5.59 ms                                                     | 3.74 ms: 1.49x faster                                                       |
| async_tree_io            | 1.07 sec                                                    | 722 ms: 1.48x faster                                                        |
| sqlglot_transpile        | 1.45 ms                                                     | 976 us: 1.48x faster                                                        |
| async_tree_memoization   | 505 ms                                                      | 341 ms: 1.48x faster                                                        |
| scimark_lu               | 84.0 ms                                                     | 56.8 ms: 1.48x faster                                                       |
| pickle_pure_python       | 259 us                                                      | 177 us: 1.46x faster                                                        |
| crypto_pyaes             | 63.1 ms                                                     | 43.2 ms: 1.46x faster                                                       |
| richards                 | 40.6 ms                                                     | 28.5 ms: 1.43x faster                                                       |
| generators               | 31.8 ms                                                     | 22.3 ms: 1.42x faster                                                       |
| scimark_monte_carlo      | 58.0 ms                                                     | 41.2 ms: 1.41x faster                                                       |
| pyflate                  | 402 ms                                                      | 287 ms: 1.40x faster                                                        |
| unpickle_pure_python     | 177 us                                                      | 127 us: 1.39x faster                                                        |
| mako                     | 8.98 ms                                                     | 6.45 ms: 1.39x faster                                                       |
| scimark_sor              | 105 ms                                                      | 76.8 ms: 1.37x faster                                                       |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 451 ms: 1.37x faster                                                        |
| asyncio_tcp              | 717 ms                                                      | 531 ms: 1.35x faster                                                        |
| regex_compile            | 102 ms                                                      | 78.7 ms: 1.30x faster                                                       |
| sympy_sum                | 105 ms                                                      | 82.0 ms: 1.28x faster                                                       |
| chameleon                | 6.02 ms                                                     | 4.75 ms: 1.27x faster                                                       |
| spectral_norm            | 78.9 ms                                                     | 62.4 ms: 1.26x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.38 sec: 1.24x faster                                                      |
| deepcopy_memo            | 29.0 us                                                     | 23.4 us: 1.24x faster                                                       |
| sympy_str                | 193 ms                                                      | 157 ms: 1.23x faster                                                        |
| sympy_integrate          | 15.0 ms                                                     | 12.3 ms: 1.22x faster                                                       |
| sqlite_synth             | 1.90 us                                                     | 1.56 us: 1.21x faster                                                       |
| docutils                 | 1.88 sec                                                    | 1.55 sec: 1.21x faster                                                      |
| pprint_pformat           | 1.22 sec                                                    | 1.01 sec: 1.21x faster                                                      |
| mypy2                    | 347 ms                                                      | 287 ms: 1.21x faster                                                        |
| pprint_safe_repr         | 594 ms                                                      | 493 ms: 1.20x faster                                                        |
| float                    | 61.7 ms                                                     | 51.5 ms: 1.20x faster                                                       |
| sympy_expand             | 320 ms                                                      | 268 ms: 1.19x faster                                                        |
| sqlglot_optimize         | 39.4 ms                                                     | 33.2 ms: 1.19x faster                                                       |
| dulwich_log              | 48.6 ms                                                     | 41.1 ms: 1.18x faster                                                       |
| coroutines               | 15.5 ms                                                     | 13.1 ms: 1.18x faster                                                       |
| sqlglot_normalize        | 207 ms                                                      | 176 ms: 1.17x faster                                                        |
| deepcopy                 | 259 us                                                      | 222 us: 1.17x faster                                                        |
| pycparser                | 905 ms                                                      | 775 ms: 1.17x faster                                                        |
| tomli_loads              | 1.65 sec                                                    | 1.42 sec: 1.16x faster                                                      |
| nqueens                  | 68.3 ms                                                     | 59.1 ms: 1.16x faster                                                       |
| xml_etree_process        | 43.1 ms                                                     | 37.4 ms: 1.15x faster                                                       |
| deepcopy_reduce          | 2.22 us                                                     | 1.96 us: 1.14x faster                                                       |
| dask                     | 305 ms                                                      | 269 ms: 1.13x faster                                                        |
| 2to3                     | 239 ms                                                      | 212 ms: 1.13x faster                                                        |
| unpickle                 | 9.11 us                                                     | 8.12 us: 1.12x faster                                                       |
| tornado_http             | 106 ms                                                      | 95.6 ms: 1.10x faster                                                       |
| regex_dna                | 129 ms                                                      | 117 ms: 1.10x faster                                                        |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.42 ms: 1.10x faster                                                       |
| create_gc_cycles         | 800 us                                                      | 732 us: 1.09x faster                                                        |
| json                     | 3.10 ms                                                     | 2.85 ms: 1.09x faster                                                       |
| scimark_fft              | 187 ms                                                      | 174 ms: 1.08x faster                                                        |
| bench_thread_pool        | 913 us                                                      | 849 us: 1.07x faster                                                        |
| json_loads               | 14.2 us                                                     | 13.3 us: 1.07x faster                                                       |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.99 sec: 1.05x faster                                                      |
| xml_etree_parse          | 96.8 ms                                                     | 92.6 ms: 1.05x faster                                                       |
| unpack_sequence          | 40.0 ns                                                     | 38.5 ns: 1.04x faster                                                       |
| regex_v8                 | 15.0 ms                                                     | 14.6 ms: 1.03x faster                                                       |
| logging_format           | 6.73 us                                                     | 6.51 us: 1.03x faster                                                       |
| logging_simple           | 6.28 us                                                     | 6.12 us: 1.03x faster                                                       |
| fannkuch                 | 258 ms                                                      | 252 ms: 1.02x faster                                                        |
| meteor_contest           | 73.8 ms                                                     | 72.9 ms: 1.01x faster                                                       |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.8 ms: 1.01x faster                                                       |
| regex_effbot             | 1.56 ms                                                     | 1.55 ms: 1.01x faster                                                       |
| nbody                    | 71.0 ms                                                     | 71.3 ms: 1.00x slower                                                       |
| python_startup           | 19.7 ms                                                     | 20.3 ms: 1.03x slower                                                       |
| pickle                   | 6.87 us                                                     | 7.18 us: 1.04x slower                                                       |
| pickle_list              | 2.69 us                                                     | 2.85 us: 1.06x slower                                                       |
| async_generators         | 219 ms                                                      | 233 ms: 1.06x slower                                                        |
| gc_traversal             | 1.40 ms                                                     | 1.50 ms: 1.07x slower                                                       |
| bench_mp_pool            | 59.9 ms                                                     | 64.3 ms: 1.07x slower                                                       |
| pathlib                  | 72.8 ms                                                     | 80.2 ms: 1.10x slower                                                       |
| pickle_dict              | 17.1 us                                                     | 18.9 us: 1.10x slower                                                       |
| coverage                 | 38.4 ms                                                     | 45.3 ms: 1.18x slower                                                       |
| python_startup_no_site   | 15.3 ms                                                     | 18.2 ms: 1.19x slower                                                       |
| telco                    | 3.82 ms                                                     | 4.56 ms: 1.19x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.21x faster                                                                |

Benchmark hidden because not significant (3): pidigits, xml_etree_generate, unpickle_list
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-8deb8bc/bm-20231120-pythonperf1-amd64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.15x
