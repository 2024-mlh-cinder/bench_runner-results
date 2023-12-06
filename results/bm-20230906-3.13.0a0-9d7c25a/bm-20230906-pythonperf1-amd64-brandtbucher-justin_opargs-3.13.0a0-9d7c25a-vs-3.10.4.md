
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_opargs
- machine: windows-amd64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.11x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                                    |
| tornado_http   | 109 ms                                                      | 91.7 ms: 1.19x faster                                                     |
| Geometric mean | (ref)                                                       | 1.15x faster                                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 56.9 ms: 1.06x faster                                                     |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                                      |
| nbody          | 69.3 ms                                                     | 76.3 ms: 1.10x slower                                                     |
| Geometric mean | (ref)                                                       | 1.03x slower                                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 118 ms: 1.12x faster                                                      |
| regex_compile  | 103 ms                                                      | 96.1 ms: 1.08x faster                                                     |
| regex_effbot   | 1.66 ms                                                     | 1.56 ms: 1.06x faster                                                     |
| regex_v8       | 15.0 ms                                                     | 15.1 ms: 1.00x slower                                                     |
| Geometric mean | (ref)                                                       | 1.06x faster                                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.84 ms: 1.46x faster                                                     |
| pickle_pure_python   | 257 us                                                      | 199 us: 1.29x faster                                                      |
| unpickle_pure_python | 171 us                                                      | 146 us: 1.17x faster                                                      |
| xml_etree_parse      | 102 ms                                                      | 91.6 ms: 1.11x faster                                                     |
| tomli_loads          | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                    |
| xml_etree_process    | 43.4 ms                                                     | 40.0 ms: 1.09x faster                                                     |
| unpickle             | 9.17 us                                                     | 8.53 us: 1.08x faster                                                     |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                                     |
| unpickle_list        | 2.81 us                                                     | 2.76 us: 1.02x faster                                                     |
| xml_etree_iterparse  | 63.5 ms                                                     | 65.6 ms: 1.03x slower                                                     |
| pickle               | 6.80 us                                                     | 7.12 us: 1.05x slower                                                     |
| xml_etree_generate   | 54.5 ms                                                     | 57.6 ms: 1.06x slower                                                     |
| pickle_dict          | 16.9 us                                                     | 18.1 us: 1.07x slower                                                     |
| pickle_list          | 2.59 us                                                     | 2.91 us: 1.13x slower                                                     |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                     |
| python_startup_no_site | 15.5 ms                                                     | 16.7 ms: 1.08x slower                                                     |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                              |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.81 ms: 1.29x faster                                                     |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf1-amd64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 99.9 us: 3.25x faster                                                     |
| deltablue                | 4.17 ms                                                     | 2.34 ms: 1.78x faster                                                     |
| mypy2                    | 352 ms                                                      | 230 ms: 1.53x faster                                                      |
| asyncio_tcp              | 712 ms                                                      | 478 ms: 1.49x faster                                                      |
| async_tree_none          | 420 ms                                                      | 283 ms: 1.48x faster                                                      |
| logging_silent           | 96.4 ns                                                     | 65.4 ns: 1.47x faster                                                     |
| richards_super           | 51.7 ms                                                     | 35.1 ms: 1.47x faster                                                     |
| json_dumps               | 8.50 ms                                                     | 5.84 ms: 1.46x faster                                                     |
| async_tree_io            | 1.07 sec                                                    | 749 ms: 1.42x faster                                                      |
| raytrace                 | 271 ms                                                      | 191 ms: 1.42x faster                                                      |
| async_tree_memoization   | 497 ms                                                      | 363 ms: 1.37x faster                                                      |
| sqlglot_parse            | 1.22 ms                                                     | 896 us: 1.36x faster                                                      |
| richards                 | 41.2 ms                                                     | 30.5 ms: 1.35x faster                                                     |
| scimark_lu               | 85.4 ms                                                     | 63.6 ms: 1.34x faster                                                     |
| go                       | 136 ms                                                      | 104 ms: 1.31x faster                                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.13 ms: 1.30x faster                                                     |
| mako                     | 8.80 ms                                                     | 6.81 ms: 1.29x faster                                                     |
| pickle_pure_python       | 257 us                                                      | 199 us: 1.29x faster                                                      |
| crypto_pyaes             | 62.3 ms                                                     | 48.5 ms: 1.28x faster                                                     |
| chaos                    | 58.9 ms                                                     | 46.1 ms: 1.28x faster                                                     |
| generators               | 31.6 ms                                                     | 25.1 ms: 1.26x faster                                                     |
| scimark_monte_carlo      | 55.9 ms                                                     | 44.7 ms: 1.25x faster                                                     |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 490 ms: 1.24x faster                                                      |
| scimark_sor              | 105 ms                                                      | 86.1 ms: 1.22x faster                                                     |
| pyflate                  | 387 ms                                                      | 318 ms: 1.22x faster                                                      |
| tornado_http             | 109 ms                                                      | 91.7 ms: 1.19x faster                                                     |
| unpickle_pure_python     | 171 us                                                      | 146 us: 1.17x faster                                                      |
| hexiom                   | 5.52 ms                                                     | 4.77 ms: 1.16x faster                                                     |
| pycparser                | 868 ms                                                      | 752 ms: 1.15x faster                                                      |
| deepcopy_memo            | 28.5 us                                                     | 25.1 us: 1.14x faster                                                     |
| spectral_norm            | 78.0 ms                                                     | 68.7 ms: 1.14x faster                                                     |
| regex_dna                | 132 ms                                                      | 118 ms: 1.12x faster                                                      |
| docutils                 | 1.89 sec                                                    | 1.70 sec: 1.11x faster                                                    |
| xml_etree_parse          | 102 ms                                                      | 91.6 ms: 1.11x faster                                                     |
| mdp                      | 1.71 sec                                                    | 1.55 sec: 1.10x faster                                                    |
| bench_thread_pool        | 946 us                                                      | 860 us: 1.10x faster                                                      |
| tomli_loads              | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                    |
| pprint_safe_repr         | 589 ms                                                      | 542 ms: 1.09x faster                                                      |
| xml_etree_process        | 43.4 ms                                                     | 40.0 ms: 1.09x faster                                                     |
| create_gc_cycles         | 782 us                                                      | 722 us: 1.08x faster                                                      |
| pprint_pformat           | 1.21 sec                                                    | 1.12 sec: 1.08x faster                                                    |
| unpickle                 | 9.17 us                                                     | 8.53 us: 1.08x faster                                                     |
| regex_compile            | 103 ms                                                      | 96.1 ms: 1.08x faster                                                     |
| regex_effbot             | 1.66 ms                                                     | 1.56 ms: 1.06x faster                                                     |
| float                    | 60.2 ms                                                     | 56.9 ms: 1.06x faster                                                     |
| coroutines               | 15.9 ms                                                     | 15.1 ms: 1.05x faster                                                     |
| sqlite_synth             | 1.84 us                                                     | 1.76 us: 1.05x faster                                                     |
| json                     | 3.05 ms                                                     | 2.92 ms: 1.05x faster                                                     |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.55 ms: 1.04x faster                                                     |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                                     |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.97 sec: 1.03x faster                                                    |
| sqlglot_optimize         | 39.0 ms                                                     | 38.1 ms: 1.02x faster                                                     |
| comprehensions           | 16.0 us                                                     | 15.7 us: 1.02x faster                                                     |
| unpickle_list            | 2.81 us                                                     | 2.76 us: 1.02x faster                                                     |
| dulwich_log              | 47.6 ms                                                     | 47.0 ms: 1.01x faster                                                     |
| fannkuch                 | 258 ms                                                      | 254 ms: 1.01x faster                                                      |
| python_startup           | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                     |
| deepcopy                 | 255 us                                                      | 253 us: 1.01x faster                                                      |
| regex_v8                 | 15.0 ms                                                     | 15.1 ms: 1.00x slower                                                     |
| scimark_fft              | 193 ms                                                      | 194 ms: 1.01x slower                                                      |
| sqlglot_normalize        | 202 ms                                                      | 205 ms: 1.01x slower                                                      |
| pathlib                  | 77.4 ms                                                     | 79.3 ms: 1.03x slower                                                     |
| deepcopy_reduce          | 2.16 us                                                     | 2.23 us: 1.03x slower                                                     |
| xml_etree_iterparse      | 63.5 ms                                                     | 65.6 ms: 1.03x slower                                                     |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                                      |
| pickle                   | 6.80 us                                                     | 7.12 us: 1.05x slower                                                     |
| xml_etree_generate       | 54.5 ms                                                     | 57.6 ms: 1.06x slower                                                     |
| pickle_dict              | 16.9 us                                                     | 18.1 us: 1.07x slower                                                     |
| python_startup_no_site   | 15.5 ms                                                     | 16.7 ms: 1.08x slower                                                     |
| meteor_contest           | 72.5 ms                                                     | 79.7 ms: 1.10x slower                                                     |
| nbody                    | 69.3 ms                                                     | 76.3 ms: 1.10x slower                                                     |
| logging_format           | 6.66 us                                                     | 7.35 us: 1.10x slower                                                     |
| logging_simple           | 6.20 us                                                     | 6.87 us: 1.11x slower                                                     |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.12x slower                                                     |
| pickle_list              | 2.59 us                                                     | 2.91 us: 1.13x slower                                                     |
| async_generators         | 224 ms                                                      | 253 ms: 1.13x slower                                                      |
| coverage                 | 40.0 ms                                                     | 46.4 ms: 1.16x slower                                                     |
| bench_mp_pool            | 60.7 ms                                                     | 71.1 ms: 1.17x slower                                                     |
| telco                    | 3.78 ms                                                     | 4.63 ms: 1.22x slower                                                     |
| unpack_sequence          | 37.8 ns                                                     | 48.8 ns: 1.29x slower                                                     |
| dask                     | 305 ms                                                      | 396 ms: 1.30x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.11x faster                                                              |

Benchmark hidden because not significant (1): nqueens
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.07x
- 95% likely to have a speedup of 1.06x
- 99% likely to have a speedup of 1.05x
