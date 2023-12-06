
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.17x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.61 sec: 1.17x faster                                     |
| tornado_http   | 109 ms                                                      | 89.5 ms: 1.22x faster                                      |
| Geometric mean | (ref)                                                       | 1.20x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.8 ms: 1.10x faster                                      |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                       |
| nbody          | 69.3 ms                                                     | 73.7 ms: 1.06x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 90.7 ms: 1.14x faster                                      |
| regex_dna      | 132 ms                                                      | 124 ms: 1.06x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.60 ms: 1.04x faster                                      |
| regex_v8       | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                       | 1.05x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.74 ms: 1.48x faster                                      |
| pickle_pure_python   | 257 us                                                      | 193 us: 1.33x faster                                       |
| unpickle_pure_python | 171 us                                                      | 138 us: 1.24x faster                                       |
| unpickle             | 9.17 us                                                     | 8.12 us: 1.13x faster                                      |
| xml_etree_process    | 43.4 ms                                                     | 38.9 ms: 1.12x faster                                      |
| xml_etree_parse      | 102 ms                                                      | 91.8 ms: 1.11x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.48 sec: 1.09x faster                                     |
| unpickle_list        | 2.81 us                                                     | 2.64 us: 1.06x faster                                      |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                      |
| pickle               | 6.80 us                                                     | 6.91 us: 1.02x slower                                      |
| xml_etree_iterparse  | 63.5 ms                                                     | 64.6 ms: 1.02x slower                                      |
| xml_etree_generate   | 54.5 ms                                                     | 56.4 ms: 1.03x slower                                      |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                      |
| pickle_list          | 2.59 us                                                     | 2.86 us: 1.10x slower                                      |
| Geometric mean       | (ref)                                                       | 1.09x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                      |
| Geometric mean         | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.43 ms: 1.18x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 95.2 us: 3.41x faster                                      |
| deltablue                | 4.17 ms                                                     | 2.18 ms: 1.92x faster                                      |
| mypy2                    | 352 ms                                                      | 215 ms: 1.64x faster                                       |
| richards_super           | 51.7 ms                                                     | 32.1 ms: 1.61x faster                                      |
| raytrace                 | 271 ms                                                      | 172 ms: 1.58x faster                                       |
| async_tree_none          | 420 ms                                                      | 270 ms: 1.56x faster                                       |
| logging_silent           | 96.4 ns                                                     | 63.4 ns: 1.52x faster                                      |
| asyncio_tcp              | 712 ms                                                      | 476 ms: 1.50x faster                                       |
| go                       | 136 ms                                                      | 91.0 ms: 1.50x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.74 ms: 1.48x faster                                      |
| sqlglot_parse            | 1.22 ms                                                     | 825 us: 1.48x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 733 ms: 1.45x faster                                       |
| scimark_lu               | 85.4 ms                                                     | 58.8 ms: 1.45x faster                                      |
| async_tree_memoization   | 497 ms                                                      | 346 ms: 1.44x faster                                       |
| richards                 | 41.2 ms                                                     | 29.0 ms: 1.42x faster                                      |
| chaos                    | 58.9 ms                                                     | 41.6 ms: 1.42x faster                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.05 ms: 1.40x faster                                      |
| crypto_pyaes             | 62.3 ms                                                     | 44.9 ms: 1.39x faster                                      |
| generators               | 31.6 ms                                                     | 23.2 ms: 1.36x faster                                      |
| pickle_pure_python       | 257 us                                                      | 193 us: 1.33x faster                                       |
| hexiom                   | 5.52 ms                                                     | 4.16 ms: 1.33x faster                                      |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.5 ms: 1.31x faster                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 473 ms: 1.29x faster                                       |
| pyflate                  | 387 ms                                                      | 304 ms: 1.27x faster                                       |
| scimark_sor              | 105 ms                                                      | 82.6 ms: 1.27x faster                                      |
| unpickle_pure_python     | 171 us                                                      | 138 us: 1.24x faster                                       |
| tornado_http             | 109 ms                                                      | 89.5 ms: 1.22x faster                                      |
| mdp                      | 1.71 sec                                                    | 1.41 sec: 1.21x faster                                     |
| mako                     | 8.80 ms                                                     | 7.43 ms: 1.18x faster                                      |
| deepcopy_memo            | 28.5 us                                                     | 24.2 us: 1.18x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.61 sec: 1.17x faster                                     |
| spectral_norm            | 78.0 ms                                                     | 67.2 ms: 1.16x faster                                      |
| regex_compile            | 103 ms                                                      | 90.7 ms: 1.14x faster                                      |
| unpickle                 | 9.17 us                                                     | 8.12 us: 1.13x faster                                      |
| xml_etree_process        | 43.4 ms                                                     | 38.9 ms: 1.12x faster                                      |
| pprint_pformat           | 1.21 sec                                                    | 1.08 sec: 1.11x faster                                     |
| pprint_safe_repr         | 589 ms                                                      | 529 ms: 1.11x faster                                       |
| xml_etree_parse          | 102 ms                                                      | 91.8 ms: 1.11x faster                                      |
| sqlglot_optimize         | 39.0 ms                                                     | 35.2 ms: 1.11x faster                                      |
| bench_thread_pool        | 946 us                                                      | 857 us: 1.10x faster                                       |
| deepcopy                 | 255 us                                                      | 233 us: 1.10x faster                                       |
| float                    | 60.2 ms                                                     | 54.8 ms: 1.10x faster                                      |
| sqlglot_normalize        | 202 ms                                                      | 184 ms: 1.10x faster                                       |
| nqueens                  | 67.0 ms                                                     | 61.1 ms: 1.10x faster                                      |
| create_gc_cycles         | 782 us                                                      | 714 us: 1.10x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.48 sec: 1.09x faster                                     |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.87 sec: 1.09x faster                                     |
| comprehensions           | 16.0 us                                                     | 14.9 us: 1.07x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.48 ms: 1.07x faster                                      |
| coroutines               | 15.9 ms                                                     | 14.9 ms: 1.07x faster                                      |
| unpickle_list            | 2.81 us                                                     | 2.64 us: 1.06x faster                                      |
| regex_dna                | 132 ms                                                      | 124 ms: 1.06x faster                                       |
| dulwich_log              | 47.6 ms                                                     | 45.1 ms: 1.06x faster                                      |
| json                     | 3.05 ms                                                     | 2.89 ms: 1.05x faster                                      |
| sqlite_synth             | 1.84 us                                                     | 1.76 us: 1.05x faster                                      |
| deepcopy_reduce          | 2.16 us                                                     | 2.07 us: 1.04x faster                                      |
| scimark_fft              | 193 ms                                                      | 185 ms: 1.04x faster                                       |
| regex_effbot             | 1.66 ms                                                     | 1.60 ms: 1.04x faster                                      |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                      |
| pickle                   | 6.80 us                                                     | 6.91 us: 1.02x slower                                      |
| xml_etree_iterparse      | 63.5 ms                                                     | 64.6 ms: 1.02x slower                                      |
| regex_v8                 | 15.0 ms                                                     | 15.3 ms: 1.02x slower                                      |
| meteor_contest           | 72.5 ms                                                     | 74.4 ms: 1.03x slower                                      |
| xml_etree_generate       | 54.5 ms                                                     | 56.4 ms: 1.03x slower                                      |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                       |
| unpack_sequence          | 37.8 ns                                                     | 39.4 ns: 1.04x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 63.3 ms: 1.04x slower                                      |
| logging_simple           | 6.20 us                                                     | 6.48 us: 1.04x slower                                      |
| logging_format           | 6.66 us                                                     | 6.96 us: 1.05x slower                                      |
| python_startup_no_site   | 15.5 ms                                                     | 16.4 ms: 1.06x slower                                      |
| nbody                    | 69.3 ms                                                     | 73.7 ms: 1.06x slower                                      |
| async_generators         | 224 ms                                                      | 240 ms: 1.07x slower                                       |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                      |
| gc_traversal             | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                      |
| pickle_list              | 2.59 us                                                     | 2.86 us: 1.10x slower                                      |
| coverage                 | 40.0 ms                                                     | 46.1 ms: 1.15x slower                                      |
| telco                    | 3.78 ms                                                     | 4.73 ms: 1.25x slower                                      |
| Geometric mean           | (ref)                                                       | 1.17x faster                                               |

Benchmark hidden because not significant (4): pycparser, python_startup, fannkuch, pathlib
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.09x
