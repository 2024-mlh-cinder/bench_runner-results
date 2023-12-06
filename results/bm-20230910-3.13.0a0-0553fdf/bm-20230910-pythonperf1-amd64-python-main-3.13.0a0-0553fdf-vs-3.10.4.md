
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 0553fdf
- commit date: 2023-09-10
- overall geometric mean: 1.15x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                     |
| tornado_http   | 109 ms                                                      | 90.2 ms: 1.21x faster                                      |
| Geometric mean | (ref)                                                       | 1.19x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.6 ms: 1.08x faster                                      |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                       |
| nbody          | 69.3 ms                                                     | 76.5 ms: 1.10x slower                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 92.2 ms: 1.12x faster                                      |
| regex_dna      | 132 ms                                                      | 120 ms: 1.10x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                      |
| regex_v8       | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                      |
| Geometric mean | (ref)                                                       | 1.07x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.60 ms: 1.52x faster                                      |
| pickle_pure_python   | 257 us                                                      | 190 us: 1.35x faster                                       |
| unpickle_pure_python | 171 us                                                      | 135 us: 1.27x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                      |
| xml_etree_parse      | 102 ms                                                      | 90.4 ms: 1.13x faster                                      |
| unpickle             | 9.17 us                                                     | 8.47 us: 1.08x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.52 sec: 1.07x faster                                     |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.05x faster                                      |
| unpickle_list        | 2.81 us                                                     | 2.68 us: 1.05x faster                                      |
| xml_etree_iterparse  | 63.5 ms                                                     | 64.7 ms: 1.02x slower                                      |
| xml_etree_generate   | 54.5 ms                                                     | 55.6 ms: 1.02x slower                                      |
| pickle               | 6.80 us                                                     | 7.08 us: 1.04x slower                                      |
| pickle_dict          | 16.9 us                                                     | 18.7 us: 1.11x slower                                      |
| pickle_list          | 2.59 us                                                     | 2.95 us: 1.14x slower                                      |
| Geometric mean       | (ref)                                                       | 1.09x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 20.2 ms: 1.01x slower                                      |
| python_startup_no_site | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                      |
| Geometric mean         | (ref)                                                       | 1.03x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.45 ms: 1.18x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230910-pythonperf1-amd64-python-main-3.13.0a0-0553fdf |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 93.6 us: 3.47x faster                                      |
| deltablue                | 4.17 ms                                                     | 2.23 ms: 1.87x faster                                      |
| mypy2                    | 352 ms                                                      | 218 ms: 1.61x faster                                       |
| richards_super           | 51.7 ms                                                     | 32.6 ms: 1.58x faster                                      |
| raytrace                 | 271 ms                                                      | 177 ms: 1.53x faster                                       |
| async_tree_none          | 420 ms                                                      | 275 ms: 1.53x faster                                       |
| json_dumps               | 8.50 ms                                                     | 5.60 ms: 1.52x faster                                      |
| logging_silent           | 96.4 ns                                                     | 63.7 ns: 1.51x faster                                      |
| scimark_lu               | 85.4 ms                                                     | 58.4 ms: 1.46x faster                                      |
| asyncio_tcp              | 712 ms                                                      | 489 ms: 1.46x faster                                       |
| go                       | 136 ms                                                      | 95.6 ms: 1.42x faster                                      |
| async_tree_io            | 1.07 sec                                                    | 749 ms: 1.42x faster                                       |
| richards                 | 41.2 ms                                                     | 29.0 ms: 1.42x faster                                      |
| sqlglot_parse            | 1.22 ms                                                     | 862 us: 1.41x faster                                       |
| async_tree_memoization   | 497 ms                                                      | 352 ms: 1.41x faster                                       |
| chaos                    | 58.9 ms                                                     | 41.9 ms: 1.40x faster                                      |
| crypto_pyaes             | 62.3 ms                                                     | 45.0 ms: 1.38x faster                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.08 ms: 1.36x faster                                      |
| generators               | 31.6 ms                                                     | 23.4 ms: 1.35x faster                                      |
| pickle_pure_python       | 257 us                                                      | 190 us: 1.35x faster                                       |
| scimark_monte_carlo      | 55.9 ms                                                     | 41.5 ms: 1.34x faster                                      |
| hexiom                   | 5.52 ms                                                     | 4.29 ms: 1.29x faster                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 480 ms: 1.27x faster                                       |
| unpickle_pure_python     | 171 us                                                      | 135 us: 1.27x faster                                       |
| pyflate                  | 387 ms                                                      | 305 ms: 1.27x faster                                       |
| scimark_sor              | 105 ms                                                      | 84.7 ms: 1.24x faster                                      |
| spectral_norm            | 78.0 ms                                                     | 64.1 ms: 1.22x faster                                      |
| tornado_http             | 109 ms                                                      | 90.2 ms: 1.21x faster                                      |
| mako                     | 8.80 ms                                                     | 7.45 ms: 1.18x faster                                      |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                     |
| deepcopy_memo            | 28.5 us                                                     | 24.4 us: 1.17x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                     |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.76 sec: 1.15x faster                                     |
| pprint_safe_repr         | 589 ms                                                      | 515 ms: 1.14x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.06 sec: 1.14x faster                                     |
| xml_etree_process        | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                      |
| pycparser                | 868 ms                                                      | 765 ms: 1.13x faster                                       |
| xml_etree_parse          | 102 ms                                                      | 90.4 ms: 1.13x faster                                      |
| regex_compile            | 103 ms                                                      | 92.2 ms: 1.12x faster                                      |
| bench_thread_pool        | 946 us                                                      | 847 us: 1.12x faster                                       |
| regex_dna                | 132 ms                                                      | 120 ms: 1.10x faster                                       |
| sqlglot_optimize         | 39.0 ms                                                     | 35.5 ms: 1.10x faster                                      |
| nqueens                  | 67.0 ms                                                     | 61.6 ms: 1.09x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.45 ms: 1.08x faster                                      |
| unpickle                 | 9.17 us                                                     | 8.47 us: 1.08x faster                                      |
| float                    | 60.2 ms                                                     | 55.6 ms: 1.08x faster                                      |
| coroutines               | 15.9 ms                                                     | 14.7 ms: 1.08x faster                                      |
| json                     | 3.05 ms                                                     | 2.84 ms: 1.07x faster                                      |
| scimark_fft              | 193 ms                                                      | 180 ms: 1.07x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.52 sec: 1.07x faster                                     |
| comprehensions           | 16.0 us                                                     | 15.0 us: 1.06x faster                                      |
| regex_effbot             | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                      |
| create_gc_cycles         | 782 us                                                      | 739 us: 1.06x faster                                       |
| deepcopy                 | 255 us                                                      | 241 us: 1.06x faster                                       |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.05x faster                                      |
| unpickle_list            | 2.81 us                                                     | 2.68 us: 1.05x faster                                      |
| sqlite_synth             | 1.84 us                                                     | 1.75 us: 1.05x faster                                      |
| sqlglot_normalize        | 202 ms                                                      | 193 ms: 1.05x faster                                       |
| fannkuch                 | 258 ms                                                      | 247 ms: 1.04x faster                                       |
| dulwich_log              | 47.6 ms                                                     | 46.0 ms: 1.03x faster                                      |
| regex_v8                 | 15.0 ms                                                     | 15.2 ms: 1.01x slower                                      |
| python_startup           | 20.0 ms                                                     | 20.2 ms: 1.01x slower                                      |
| xml_etree_iterparse      | 63.5 ms                                                     | 64.7 ms: 1.02x slower                                      |
| xml_etree_generate       | 54.5 ms                                                     | 55.6 ms: 1.02x slower                                      |
| pathlib                  | 77.4 ms                                                     | 79.3 ms: 1.02x slower                                      |
| meteor_contest           | 72.5 ms                                                     | 74.5 ms: 1.03x slower                                      |
| pickle                   | 6.80 us                                                     | 7.08 us: 1.04x slower                                      |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                       |
| python_startup_no_site   | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                      |
| logging_simple           | 6.20 us                                                     | 6.53 us: 1.05x slower                                      |
| logging_format           | 6.66 us                                                     | 7.06 us: 1.06x slower                                      |
| unpack_sequence          | 37.8 ns                                                     | 41.6 ns: 1.10x slower                                      |
| async_generators         | 224 ms                                                      | 247 ms: 1.10x slower                                       |
| nbody                    | 69.3 ms                                                     | 76.5 ms: 1.10x slower                                      |
| pickle_dict              | 16.9 us                                                     | 18.7 us: 1.11x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 67.7 ms: 1.11x slower                                      |
| gc_traversal             | 1.34 ms                                                     | 1.51 ms: 1.12x slower                                      |
| pickle_list              | 2.59 us                                                     | 2.95 us: 1.14x slower                                      |
| coverage                 | 40.0 ms                                                     | 46.2 ms: 1.15x slower                                      |
| dask                     | 305 ms                                                      | 382 ms: 1.25x slower                                       |
| telco                    | 3.78 ms                                                     | 4.81 ms: 1.27x slower                                      |
| Geometric mean           | (ref)                                                       | 1.15x faster                                               |

Benchmark hidden because not significant (1): deepcopy_reduce
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.08x
