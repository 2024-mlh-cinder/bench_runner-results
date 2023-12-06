
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.13x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.68 sec: 1.12x faster                                             |
| tornado_http   | 109 ms                                                      | 90.9 ms: 1.20x faster                                              |
| Geometric mean | (ref)                                                       | 1.16x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.8 ms: 1.08x faster                                              |
| pidigits       | 145 ms                                                      | 150 ms: 1.04x slower                                               |
| nbody          | 69.3 ms                                                     | 76.8 ms: 1.11x slower                                              |
| Geometric mean | (ref)                                                       | 1.02x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 119 ms: 1.11x faster                                               |
| regex_compile  | 103 ms                                                      | 95.9 ms: 1.08x faster                                              |
| regex_effbot   | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                              |
| Geometric mean | (ref)                                                       | 1.06x faster                                                       |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.97 ms: 1.42x faster                                              |
| pickle_pure_python   | 257 us                                                      | 196 us: 1.31x faster                                               |
| unpickle_pure_python | 171 us                                                      | 147 us: 1.16x faster                                               |
| unpickle             | 9.17 us                                                     | 8.31 us: 1.10x faster                                              |
| xml_etree_parse      | 102 ms                                                      | 93.2 ms: 1.09x faster                                              |
| tomli_loads          | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                             |
| xml_etree_process    | 43.4 ms                                                     | 40.1 ms: 1.08x faster                                              |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                              |
| unpickle_list        | 2.81 us                                                     | 2.76 us: 1.02x faster                                              |
| pickle               | 6.80 us                                                     | 7.09 us: 1.04x slower                                              |
| xml_etree_iterparse  | 63.5 ms                                                     | 66.5 ms: 1.05x slower                                              |
| xml_etree_generate   | 54.5 ms                                                     | 57.6 ms: 1.06x slower                                              |
| pickle_dict          | 16.9 us                                                     | 18.5 us: 1.09x slower                                              |
| pickle_list          | 2.59 us                                                     | 2.83 us: 1.09x slower                                              |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                              |
| python_startup_no_site | 15.5 ms                                                     | 16.7 ms: 1.07x slower                                              |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 6.79 ms: 1.30x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 101 us: 3.23x faster                                               |
| deltablue                | 4.17 ms                                                     | 2.34 ms: 1.78x faster                                              |
| mypy2                    | 352 ms                                                      | 227 ms: 1.55x faster                                               |
| richards_super           | 51.7 ms                                                     | 33.5 ms: 1.55x faster                                              |
| async_tree_none          | 420 ms                                                      | 279 ms: 1.50x faster                                               |
| asyncio_tcp              | 712 ms                                                      | 475 ms: 1.50x faster                                               |
| logging_silent           | 96.4 ns                                                     | 65.0 ns: 1.48x faster                                              |
| async_tree_io            | 1.07 sec                                                    | 732 ms: 1.46x faster                                               |
| raytrace                 | 271 ms                                                      | 187 ms: 1.45x faster                                               |
| json_dumps               | 8.50 ms                                                     | 5.97 ms: 1.42x faster                                              |
| scimark_lu               | 85.4 ms                                                     | 60.1 ms: 1.42x faster                                              |
| async_tree_memoization   | 497 ms                                                      | 359 ms: 1.39x faster                                               |
| richards                 | 41.2 ms                                                     | 29.9 ms: 1.38x faster                                              |
| crypto_pyaes             | 62.3 ms                                                     | 46.5 ms: 1.34x faster                                              |
| sqlglot_parse            | 1.22 ms                                                     | 912 us: 1.34x faster                                               |
| go                       | 136 ms                                                      | 103 ms: 1.32x faster                                               |
| pickle_pure_python       | 257 us                                                      | 196 us: 1.31x faster                                               |
| sqlglot_transpile        | 1.46 ms                                                     | 1.12 ms: 1.30x faster                                              |
| mako                     | 8.80 ms                                                     | 6.79 ms: 1.30x faster                                              |
| chaos                    | 58.9 ms                                                     | 45.5 ms: 1.29x faster                                              |
| generators               | 31.6 ms                                                     | 24.9 ms: 1.27x faster                                              |
| scimark_monte_carlo      | 55.9 ms                                                     | 44.3 ms: 1.26x faster                                              |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 485 ms: 1.26x faster                                               |
| scimark_sor              | 105 ms                                                      | 83.6 ms: 1.25x faster                                              |
| pyflate                  | 387 ms                                                      | 313 ms: 1.23x faster                                               |
| tornado_http             | 109 ms                                                      | 90.9 ms: 1.20x faster                                              |
| mdp                      | 1.71 sec                                                    | 1.45 sec: 1.18x faster                                             |
| unpickle_pure_python     | 171 us                                                      | 147 us: 1.16x faster                                               |
| hexiom                   | 5.52 ms                                                     | 4.77 ms: 1.16x faster                                              |
| deepcopy_memo            | 28.5 us                                                     | 24.8 us: 1.15x faster                                              |
| spectral_norm            | 78.0 ms                                                     | 68.1 ms: 1.15x faster                                              |
| pycparser                | 868 ms                                                      | 765 ms: 1.14x faster                                               |
| docutils                 | 1.89 sec                                                    | 1.68 sec: 1.12x faster                                             |
| regex_dna                | 132 ms                                                      | 119 ms: 1.11x faster                                               |
| unpickle                 | 9.17 us                                                     | 8.31 us: 1.10x faster                                              |
| xml_etree_parse          | 102 ms                                                      | 93.2 ms: 1.09x faster                                              |
| pprint_safe_repr         | 589 ms                                                      | 541 ms: 1.09x faster                                               |
| bench_thread_pool        | 946 us                                                      | 869 us: 1.09x faster                                               |
| tomli_loads              | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                             |
| pprint_pformat           | 1.21 sec                                                    | 1.11 sec: 1.08x faster                                             |
| xml_etree_process        | 43.4 ms                                                     | 40.1 ms: 1.08x faster                                              |
| coroutines               | 15.9 ms                                                     | 14.7 ms: 1.08x faster                                              |
| float                    | 60.2 ms                                                     | 55.8 ms: 1.08x faster                                              |
| create_gc_cycles         | 782 us                                                      | 724 us: 1.08x faster                                               |
| regex_compile            | 103 ms                                                      | 95.9 ms: 1.08x faster                                              |
| regex_effbot             | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                              |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.93 sec: 1.06x faster                                             |
| sqlglot_optimize         | 39.0 ms                                                     | 37.0 ms: 1.05x faster                                              |
| fannkuch                 | 258 ms                                                      | 247 ms: 1.04x faster                                               |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                              |
| json                     | 3.05 ms                                                     | 2.94 ms: 1.04x faster                                              |
| nqueens                  | 67.0 ms                                                     | 65.2 ms: 1.03x faster                                              |
| sqlite_synth             | 1.84 us                                                     | 1.79 us: 1.03x faster                                              |
| scimark_fft              | 193 ms                                                      | 189 ms: 1.02x faster                                               |
| deepcopy                 | 255 us                                                      | 250 us: 1.02x faster                                               |
| unpickle_list            | 2.81 us                                                     | 2.76 us: 1.02x faster                                              |
| unpack_sequence          | 37.8 ns                                                     | 37.1 ns: 1.02x faster                                              |
| dulwich_log              | 47.6 ms                                                     | 46.7 ms: 1.02x faster                                              |
| python_startup           | 20.0 ms                                                     | 19.6 ms: 1.02x faster                                              |
| sqlglot_normalize        | 202 ms                                                      | 199 ms: 1.02x faster                                               |
| deepcopy_reduce          | 2.16 us                                                     | 2.21 us: 1.02x slower                                              |
| pathlib                  | 77.4 ms                                                     | 79.3 ms: 1.02x slower                                              |
| pidigits                 | 145 ms                                                      | 150 ms: 1.04x slower                                               |
| pickle                   | 6.80 us                                                     | 7.09 us: 1.04x slower                                              |
| xml_etree_iterparse      | 63.5 ms                                                     | 66.5 ms: 1.05x slower                                              |
| xml_etree_generate       | 54.5 ms                                                     | 57.6 ms: 1.06x slower                                              |
| logging_format           | 6.66 us                                                     | 7.11 us: 1.07x slower                                              |
| python_startup_no_site   | 15.5 ms                                                     | 16.7 ms: 1.07x slower                                              |
| logging_simple           | 6.20 us                                                     | 6.66 us: 1.07x slower                                              |
| pickle_dict              | 16.9 us                                                     | 18.5 us: 1.09x slower                                              |
| meteor_contest           | 72.5 ms                                                     | 79.3 ms: 1.09x slower                                              |
| pickle_list              | 2.59 us                                                     | 2.83 us: 1.09x slower                                              |
| nbody                    | 69.3 ms                                                     | 76.8 ms: 1.11x slower                                              |
| gc_traversal             | 1.34 ms                                                     | 1.50 ms: 1.12x slower                                              |
| async_generators         | 224 ms                                                      | 257 ms: 1.15x slower                                               |
| bench_mp_pool            | 60.7 ms                                                     | 70.2 ms: 1.16x slower                                              |
| coverage                 | 40.0 ms                                                     | 46.7 ms: 1.17x slower                                              |
| dask                     | 305 ms                                                      | 391 ms: 1.28x slower                                               |
| telco                    | 3.78 ms                                                     | 4.87 ms: 1.29x slower                                              |
| Geometric mean           | (ref)                                                       | 1.13x faster                                                       |

Benchmark hidden because not significant (3): comprehensions, scimark_sparse_mat_mult, regex_v8
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.08x
- 95% likely to have a speedup of 1.07x
- 99% likely to have a speedup of 1.06x
