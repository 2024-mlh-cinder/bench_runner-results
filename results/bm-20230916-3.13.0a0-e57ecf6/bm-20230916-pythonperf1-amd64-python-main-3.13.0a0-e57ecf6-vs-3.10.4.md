
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.16x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                     |
| tornado_http   | 109 ms                                                      | 88.5 ms: 1.23x faster                                      |
| Geometric mean | (ref)                                                       | 1.20x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.5 ms: 1.10x faster                                      |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                       |
| nbody          | 69.3 ms                                                     | 74.9 ms: 1.08x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 90.9 ms: 1.14x faster                                      |
| regex_dna      | 132 ms                                                      | 118 ms: 1.12x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.56 ms: 1.06x faster                                      |
| regex_v8       | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                       | 1.08x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.66 ms: 1.50x faster                                      |
| pickle_pure_python   | 257 us                                                      | 193 us: 1.33x faster                                       |
| unpickle_pure_python | 171 us                                                      | 136 us: 1.26x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 37.9 ms: 1.15x faster                                      |
| xml_etree_parse      | 102 ms                                                      | 91.9 ms: 1.11x faster                                      |
| unpickle             | 9.17 us                                                     | 8.29 us: 1.11x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.48 sec: 1.10x faster                                     |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                      |
| unpickle_list        | 2.81 us                                                     | 2.73 us: 1.03x faster                                      |
| xml_etree_iterparse  | 63.5 ms                                                     | 64.4 ms: 1.01x slower                                      |
| xml_etree_generate   | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                      |
| pickle               | 6.80 us                                                     | 7.24 us: 1.06x slower                                      |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                      |
| pickle_list          | 2.59 us                                                     | 3.35 us: 1.30x slower                                      |
| Geometric mean       | (ref)                                                       | 1.07x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 16.5 ms: 1.06x slower                                      |
| Geometric mean         | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.43 ms: 1.18x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-pythonperf1-amd64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 101 us: 3.20x faster                                       |
| deltablue                | 4.17 ms                                                     | 2.18 ms: 1.91x faster                                      |
| mypy2                    | 352 ms                                                      | 214 ms: 1.65x faster                                       |
| richards_super           | 51.7 ms                                                     | 32.3 ms: 1.60x faster                                      |
| async_tree_none          | 420 ms                                                      | 264 ms: 1.59x faster                                       |
| raytrace                 | 271 ms                                                      | 173 ms: 1.57x faster                                       |
| asyncio_tcp              | 712 ms                                                      | 471 ms: 1.51x faster                                       |
| go                       | 136 ms                                                      | 90.3 ms: 1.51x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.66 ms: 1.50x faster                                      |
| sqlglot_parse            | 1.22 ms                                                     | 814 us: 1.50x faster                                       |
| logging_silent           | 96.4 ns                                                     | 65.0 ns: 1.48x faster                                      |
| async_tree_io            | 1.07 sec                                                    | 728 ms: 1.46x faster                                       |
| async_tree_memoization   | 497 ms                                                      | 346 ms: 1.44x faster                                       |
| scimark_lu               | 85.4 ms                                                     | 59.8 ms: 1.43x faster                                      |
| chaos                    | 58.9 ms                                                     | 41.3 ms: 1.43x faster                                      |
| richards                 | 41.2 ms                                                     | 29.0 ms: 1.42x faster                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.03 ms: 1.42x faster                                      |
| generators               | 31.6 ms                                                     | 22.7 ms: 1.39x faster                                      |
| crypto_pyaes             | 62.3 ms                                                     | 45.1 ms: 1.38x faster                                      |
| pickle_pure_python       | 257 us                                                      | 193 us: 1.33x faster                                       |
| hexiom                   | 5.52 ms                                                     | 4.21 ms: 1.31x faster                                      |
| scimark_sor              | 105 ms                                                      | 80.6 ms: 1.30x faster                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 472 ms: 1.29x faster                                       |
| scimark_monte_carlo      | 55.9 ms                                                     | 43.4 ms: 1.29x faster                                      |
| pyflate                  | 387 ms                                                      | 303 ms: 1.28x faster                                       |
| unpickle_pure_python     | 171 us                                                      | 136 us: 1.26x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.38 sec: 1.24x faster                                     |
| tornado_http             | 109 ms                                                      | 88.5 ms: 1.23x faster                                      |
| spectral_norm            | 78.0 ms                                                     | 63.9 ms: 1.22x faster                                      |
| deepcopy_memo            | 28.5 us                                                     | 24.0 us: 1.19x faster                                      |
| mako                     | 8.80 ms                                                     | 7.43 ms: 1.18x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                     |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.77 sec: 1.15x faster                                     |
| xml_etree_process        | 43.4 ms                                                     | 37.9 ms: 1.15x faster                                      |
| pprint_safe_repr         | 589 ms                                                      | 516 ms: 1.14x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.06 sec: 1.14x faster                                     |
| regex_compile            | 103 ms                                                      | 90.9 ms: 1.14x faster                                      |
| bench_thread_pool        | 946 us                                                      | 837 us: 1.13x faster                                       |
| regex_dna                | 132 ms                                                      | 118 ms: 1.12x faster                                       |
| sqlglot_optimize         | 39.0 ms                                                     | 34.8 ms: 1.12x faster                                      |
| comprehensions           | 16.0 us                                                     | 14.3 us: 1.12x faster                                      |
| xml_etree_parse          | 102 ms                                                      | 91.9 ms: 1.11x faster                                      |
| unpickle                 | 9.17 us                                                     | 8.29 us: 1.11x faster                                      |
| sqlglot_normalize        | 202 ms                                                      | 183 ms: 1.10x faster                                       |
| float                    | 60.2 ms                                                     | 54.5 ms: 1.10x faster                                      |
| tomli_loads              | 1.62 sec                                                    | 1.48 sec: 1.10x faster                                     |
| pycparser                | 868 ms                                                      | 795 ms: 1.09x faster                                       |
| deepcopy                 | 255 us                                                      | 234 us: 1.09x faster                                       |
| nqueens                  | 67.0 ms                                                     | 61.7 ms: 1.09x faster                                      |
| coroutines               | 15.9 ms                                                     | 14.7 ms: 1.08x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.46 ms: 1.08x faster                                      |
| json                     | 3.05 ms                                                     | 2.82 ms: 1.08x faster                                      |
| scimark_fft              | 193 ms                                                      | 179 ms: 1.08x faster                                       |
| regex_effbot             | 1.66 ms                                                     | 1.56 ms: 1.06x faster                                      |
| dulwich_log              | 47.6 ms                                                     | 44.9 ms: 1.06x faster                                      |
| create_gc_cycles         | 782 us                                                      | 739 us: 1.06x faster                                       |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                      |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                      |
| unpickle_list            | 2.81 us                                                     | 2.73 us: 1.03x faster                                      |
| deepcopy_reduce          | 2.16 us                                                     | 2.12 us: 1.02x faster                                      |
| regex_v8                 | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                      |
| pathlib                  | 77.4 ms                                                     | 78.2 ms: 1.01x slower                                      |
| meteor_contest           | 72.5 ms                                                     | 73.5 ms: 1.01x slower                                      |
| xml_etree_iterparse      | 63.5 ms                                                     | 64.4 ms: 1.01x slower                                      |
| xml_etree_generate       | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                      |
| logging_format           | 6.66 us                                                     | 6.84 us: 1.03x slower                                      |
| logging_simple           | 6.20 us                                                     | 6.39 us: 1.03x slower                                      |
| fannkuch                 | 258 ms                                                      | 266 ms: 1.03x slower                                       |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                       |
| unpack_sequence          | 37.8 ns                                                     | 39.4 ns: 1.04x slower                                      |
| pickle                   | 6.80 us                                                     | 7.24 us: 1.06x slower                                      |
| async_generators         | 224 ms                                                      | 238 ms: 1.06x slower                                       |
| python_startup_no_site   | 15.5 ms                                                     | 16.5 ms: 1.06x slower                                      |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                      |
| nbody                    | 69.3 ms                                                     | 74.9 ms: 1.08x slower                                      |
| gc_traversal             | 1.34 ms                                                     | 1.50 ms: 1.11x slower                                      |
| coverage                 | 40.0 ms                                                     | 45.7 ms: 1.14x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 70.6 ms: 1.16x slower                                      |
| dask                     | 305 ms                                                      | 370 ms: 1.21x slower                                       |
| telco                    | 3.78 ms                                                     | 4.80 ms: 1.27x slower                                      |
| pickle_list              | 2.59 us                                                     | 3.35 us: 1.30x slower                                      |
| Geometric mean           | (ref)                                                       | 1.16x faster                                               |

Benchmark hidden because not significant (1): python_startup
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.10x
