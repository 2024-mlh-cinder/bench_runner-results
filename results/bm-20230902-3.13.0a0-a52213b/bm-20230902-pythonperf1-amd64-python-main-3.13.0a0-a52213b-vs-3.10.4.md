
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.14x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.65 sec: 1.15x faster                                     |
| tornado_http   | 109 ms                                                      | 89.7 ms: 1.22x faster                                      |
| Geometric mean | (ref)                                                       | 1.18x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 56.0 ms: 1.07x faster                                      |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                       |
| nbody          | 69.3 ms                                                     | 78.1 ms: 1.13x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 119 ms: 1.11x faster                                       |
| regex_compile  | 103 ms                                                      | 93.0 ms: 1.11x faster                                      |
| regex_effbot   | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                      |
| regex_v8       | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                       | 1.07x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.88 ms: 1.44x faster                                      |
| pickle_pure_python   | 257 us                                                      | 198 us: 1.30x faster                                       |
| unpickle_pure_python | 171 us                                                      | 143 us: 1.20x faster                                       |
| unpickle             | 9.17 us                                                     | 8.16 us: 1.12x faster                                      |
| xml_etree_process    | 43.4 ms                                                     | 39.0 ms: 1.11x faster                                      |
| xml_etree_parse      | 102 ms                                                      | 92.0 ms: 1.11x faster                                      |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                      |
| tomli_loads          | 1.62 sec                                                    | 1.54 sec: 1.05x faster                                     |
| unpickle_list        | 2.81 us                                                     | 2.72 us: 1.03x faster                                      |
| xml_etree_generate   | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                      |
| xml_etree_iterparse  | 63.5 ms                                                     | 65.6 ms: 1.03x slower                                      |
| pickle               | 6.80 us                                                     | 7.20 us: 1.06x slower                                      |
| pickle_list          | 2.59 us                                                     | 2.79 us: 1.08x slower                                      |
| pickle_dict          | 16.9 us                                                     | 18.7 us: 1.11x slower                                      |
| Geometric mean       | (ref)                                                       | 1.07x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 16.7 ms: 1.07x slower                                      |
| Geometric mean         | (ref)                                                       | 1.03x slower                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.60 ms: 1.16x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-pythonperf1-amd64-python-main-3.13.0a0-a52213b |
|--------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 97.8 us: 3.32x faster                                      |
| deltablue                | 4.17 ms                                                     | 2.29 ms: 1.82x faster                                      |
| mypy2                    | 352 ms                                                      | 220 ms: 1.60x faster                                       |
| async_tree_none          | 420 ms                                                      | 280 ms: 1.50x faster                                       |
| richards_super           | 51.7 ms                                                     | 34.6 ms: 1.49x faster                                      |
| raytrace                 | 271 ms                                                      | 183 ms: 1.48x faster                                       |
| asyncio_tcp              | 712 ms                                                      | 482 ms: 1.48x faster                                       |
| logging_silent           | 96.4 ns                                                     | 65.2 ns: 1.48x faster                                      |
| json_dumps               | 8.50 ms                                                     | 5.88 ms: 1.44x faster                                      |
| sqlglot_parse            | 1.22 ms                                                     | 864 us: 1.41x faster                                       |
| scimark_lu               | 85.4 ms                                                     | 60.8 ms: 1.40x faster                                      |
| async_tree_io            | 1.07 sec                                                    | 759 ms: 1.40x faster                                       |
| async_tree_memoization   | 497 ms                                                      | 358 ms: 1.39x faster                                       |
| go                       | 136 ms                                                      | 98.4 ms: 1.38x faster                                      |
| richards                 | 41.2 ms                                                     | 30.0 ms: 1.37x faster                                      |
| chaos                    | 58.9 ms                                                     | 43.3 ms: 1.36x faster                                      |
| crypto_pyaes             | 62.3 ms                                                     | 46.1 ms: 1.35x faster                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.09 ms: 1.35x faster                                      |
| pickle_pure_python       | 257 us                                                      | 198 us: 1.30x faster                                       |
| generators               | 31.6 ms                                                     | 24.4 ms: 1.30x faster                                      |
| scimark_sor              | 105 ms                                                      | 82.1 ms: 1.28x faster                                      |
| scimark_monte_carlo      | 55.9 ms                                                     | 44.1 ms: 1.27x faster                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 486 ms: 1.25x faster                                       |
| hexiom                   | 5.52 ms                                                     | 4.45 ms: 1.24x faster                                      |
| pyflate                  | 387 ms                                                      | 313 ms: 1.23x faster                                       |
| tornado_http             | 109 ms                                                      | 89.7 ms: 1.22x faster                                      |
| unpickle_pure_python     | 171 us                                                      | 143 us: 1.20x faster                                       |
| spectral_norm            | 78.0 ms                                                     | 65.7 ms: 1.19x faster                                      |
| mdp                      | 1.71 sec                                                    | 1.46 sec: 1.17x faster                                     |
| mako                     | 8.80 ms                                                     | 7.60 ms: 1.16x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.65 sec: 1.15x faster                                     |
| pycparser                | 868 ms                                                      | 755 ms: 1.15x faster                                       |
| deepcopy_memo            | 28.5 us                                                     | 25.0 us: 1.14x faster                                      |
| unpickle                 | 9.17 us                                                     | 8.16 us: 1.12x faster                                      |
| xml_etree_process        | 43.4 ms                                                     | 39.0 ms: 1.11x faster                                      |
| regex_dna                | 132 ms                                                      | 119 ms: 1.11x faster                                       |
| regex_compile            | 103 ms                                                      | 93.0 ms: 1.11x faster                                      |
| bench_thread_pool        | 946 us                                                      | 851 us: 1.11x faster                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.09 sec: 1.11x faster                                     |
| xml_etree_parse          | 102 ms                                                      | 92.0 ms: 1.11x faster                                      |
| pprint_safe_repr         | 589 ms                                                      | 533 ms: 1.11x faster                                       |
| create_gc_cycles         | 782 us                                                      | 726 us: 1.08x faster                                       |
| sqlglot_optimize         | 39.0 ms                                                     | 36.2 ms: 1.08x faster                                      |
| float                    | 60.2 ms                                                     | 56.0 ms: 1.07x faster                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.48 ms: 1.07x faster                                      |
| coroutines               | 15.9 ms                                                     | 15.0 ms: 1.06x faster                                      |
| nqueens                  | 67.0 ms                                                     | 63.2 ms: 1.06x faster                                      |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                      |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.93 sec: 1.06x faster                                     |
| tomli_loads              | 1.62 sec                                                    | 1.54 sec: 1.05x faster                                     |
| scimark_fft              | 193 ms                                                      | 184 ms: 1.05x faster                                       |
| regex_effbot             | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                      |
| sqlite_synth             | 1.84 us                                                     | 1.77 us: 1.04x faster                                      |
| dulwich_log              | 47.6 ms                                                     | 45.7 ms: 1.04x faster                                      |
| sqlglot_normalize        | 202 ms                                                      | 195 ms: 1.04x faster                                       |
| unpickle_list            | 2.81 us                                                     | 2.72 us: 1.03x faster                                      |
| deepcopy                 | 255 us                                                      | 249 us: 1.03x faster                                       |
| json                     | 3.05 ms                                                     | 3.01 ms: 1.01x faster                                      |
| regex_v8                 | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                      |
| xml_etree_generate       | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                      |
| pathlib                  | 77.4 ms                                                     | 79.7 ms: 1.03x slower                                      |
| xml_etree_iterparse      | 63.5 ms                                                     | 65.6 ms: 1.03x slower                                      |
| meteor_contest           | 72.5 ms                                                     | 75.0 ms: 1.03x slower                                      |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                       |
| deepcopy_reduce          | 2.16 us                                                     | 2.27 us: 1.05x slower                                      |
| pickle                   | 6.80 us                                                     | 7.20 us: 1.06x slower                                      |
| unpack_sequence          | 37.8 ns                                                     | 40.2 ns: 1.06x slower                                      |
| logging_format           | 6.66 us                                                     | 7.15 us: 1.07x slower                                      |
| python_startup_no_site   | 15.5 ms                                                     | 16.7 ms: 1.07x slower                                      |
| logging_simple           | 6.20 us                                                     | 6.66 us: 1.08x slower                                      |
| pickle_list              | 2.59 us                                                     | 2.79 us: 1.08x slower                                      |
| async_generators         | 224 ms                                                      | 244 ms: 1.09x slower                                       |
| gc_traversal             | 1.34 ms                                                     | 1.47 ms: 1.10x slower                                      |
| pickle_dict              | 16.9 us                                                     | 18.7 us: 1.11x slower                                      |
| bench_mp_pool            | 60.7 ms                                                     | 67.3 ms: 1.11x slower                                      |
| nbody                    | 69.3 ms                                                     | 78.1 ms: 1.13x slower                                      |
| coverage                 | 40.0 ms                                                     | 47.0 ms: 1.17x slower                                      |
| telco                    | 3.78 ms                                                     | 4.61 ms: 1.22x slower                                      |
| dask                     | 305 ms                                                      | 389 ms: 1.28x slower                                       |
| Geometric mean           | (ref)                                                       | 1.14x faster                                               |

Benchmark hidden because not significant (3): python_startup, fannkuch, comprehensions
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.07x
- 99% likely to have a speedup of 1.06x
