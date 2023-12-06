
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.01x faster
- HPT reliability: 93.73%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.68 sec: 1.05x slower                                             |
| tornado_http   | 91.8 ms                                                     | 90.9 ms: 1.01x faster                                              |
| Geometric mean | (ref)                                                       | 1.02x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                               |
| float          | 54.6 ms                                                     | 55.8 ms: 1.02x slower                                              |
| nbody          | 70.0 ms                                                     | 76.8 ms: 1.10x slower                                              |
| Geometric mean | (ref)                                                       | 1.04x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 119 ms: 1.03x slower                                               |
| regex_effbot   | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                              |
| regex_compile  | 90.6 ms                                                     | 95.9 ms: 1.06x slower                                              |
| regex_v8       | 13.8 ms                                                     | 15.0 ms: 1.09x slower                                              |
| Geometric mean | (ref)                                                       | 1.06x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.97 ms: 1.27x faster                                              |
| unpickle_pure_python | 152 us                                                      | 147 us: 1.03x faster                                               |
| xml_etree_parse      | 95.9 ms                                                     | 93.2 ms: 1.03x faster                                              |
| pickle_pure_python   | 200 us                                                      | 196 us: 1.02x faster                                               |
| unpickle             | 8.09 us                                                     | 8.31 us: 1.03x slower                                              |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.06x slower                                              |
| pickle_list          | 2.68 us                                                     | 2.83 us: 1.06x slower                                              |
| tomli_loads          | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                             |
| xml_etree_iterparse  | 62.6 ms                                                     | 66.5 ms: 1.06x slower                                              |
| pickle               | 6.61 us                                                     | 7.09 us: 1.07x slower                                              |
| xml_etree_process    | 37.1 ms                                                     | 40.1 ms: 1.08x slower                                              |
| unpickle_list        | 2.55 us                                                     | 2.76 us: 1.08x slower                                              |
| xml_etree_generate   | 52.2 ms                                                     | 57.6 ms: 1.10x slower                                              |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                       |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                              |
| python_startup         | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                              |
| Geometric mean         | (ref)                                                       | 1.05x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 6.79 ms: 1.07x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 101 us: 3.20x faster                                               |
| asyncio_tcp              | 699 ms                                                      | 475 ms: 1.47x faster                                               |
| generators               | 33.8 ms                                                     | 24.9 ms: 1.36x faster                                              |
| json_dumps               | 7.56 ms                                                     | 5.97 ms: 1.27x faster                                              |
| unpack_sequence          | 46.1 ns                                                     | 37.1 ns: 1.24x faster                                              |
| coverage                 | 55.9 ms                                                     | 46.7 ms: 1.20x faster                                              |
| mdp                      | 1.67 sec                                                    | 1.45 sec: 1.15x faster                                             |
| async_tree_none          | 320 ms                                                      | 279 ms: 1.15x faster                                               |
| raytrace                 | 211 ms                                                      | 187 ms: 1.13x faster                                               |
| richards_super           | 37.5 ms                                                     | 33.5 ms: 1.12x faster                                              |
| deltablue                | 2.61 ms                                                     | 2.34 ms: 1.12x faster                                              |
| json                     | 3.25 ms                                                     | 2.94 ms: 1.11x faster                                              |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.93 sec: 1.10x faster                                             |
| logging_silent           | 69.8 ns                                                     | 65.0 ns: 1.07x faster                                              |
| mako                     | 7.26 ms                                                     | 6.79 ms: 1.07x faster                                              |
| async_tree_io            | 779 ms                                                      | 732 ms: 1.06x faster                                               |
| scimark_lu               | 63.5 ms                                                     | 60.1 ms: 1.06x faster                                              |
| sqlglot_parse            | 952 us                                                      | 912 us: 1.04x faster                                               |
| chaos                    | 47.1 ms                                                     | 45.5 ms: 1.04x faster                                              |
| sqlglot_transpile        | 1.16 ms                                                     | 1.12 ms: 1.04x faster                                              |
| async_tree_memoization   | 371 ms                                                      | 359 ms: 1.03x faster                                               |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 485 ms: 1.03x faster                                               |
| unpickle_pure_python     | 152 us                                                      | 147 us: 1.03x faster                                               |
| xml_etree_parse          | 95.9 ms                                                     | 93.2 ms: 1.03x faster                                              |
| richards                 | 30.6 ms                                                     | 29.9 ms: 1.02x faster                                              |
| crypto_pyaes             | 47.6 ms                                                     | 46.5 ms: 1.02x faster                                              |
| fannkuch                 | 252 ms                                                      | 247 ms: 1.02x faster                                               |
| pickle_pure_python       | 200 us                                                      | 196 us: 1.02x faster                                               |
| deepcopy_memo            | 25.2 us                                                     | 24.8 us: 1.02x faster                                              |
| tornado_http             | 91.8 ms                                                     | 90.9 ms: 1.01x faster                                              |
| mypy2                    | 229 ms                                                      | 227 ms: 1.01x faster                                               |
| scimark_monte_carlo      | 44.6 ms                                                     | 44.3 ms: 1.01x faster                                              |
| nqueens                  | 64.9 ms                                                     | 65.2 ms: 1.00x slower                                              |
| logging_simple           | 6.61 us                                                     | 6.66 us: 1.01x slower                                              |
| logging_format           | 7.01 us                                                     | 7.11 us: 1.01x slower                                              |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                               |
| deepcopy                 | 246 us                                                      | 250 us: 1.02x slower                                               |
| bench_thread_pool        | 852 us                                                      | 869 us: 1.02x slower                                               |
| float                    | 54.6 ms                                                     | 55.8 ms: 1.02x slower                                              |
| unpickle                 | 8.09 us                                                     | 8.31 us: 1.03x slower                                              |
| regex_dna                | 115 ms                                                      | 119 ms: 1.03x slower                                               |
| gc_traversal             | 1.46 ms                                                     | 1.50 ms: 1.03x slower                                              |
| pyflate                  | 304 ms                                                      | 313 ms: 1.03x slower                                               |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.66 ms: 1.03x slower                                              |
| create_gc_cycles         | 693 us                                                      | 724 us: 1.05x slower                                               |
| hexiom                   | 4.55 ms                                                     | 4.77 ms: 1.05x slower                                              |
| sqlglot_normalize        | 190 ms                                                      | 199 ms: 1.05x slower                                               |
| regex_effbot             | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                              |
| python_startup_no_site   | 15.9 ms                                                     | 16.7 ms: 1.05x slower                                              |
| dulwich_log              | 44.5 ms                                                     | 46.7 ms: 1.05x slower                                              |
| docutils                 | 1.60 sec                                                    | 1.68 sec: 1.05x slower                                             |
| python_startup           | 18.7 ms                                                     | 19.6 ms: 1.05x slower                                              |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.06x slower                                              |
| pickle_list              | 2.68 us                                                     | 2.83 us: 1.06x slower                                              |
| tomli_loads              | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                             |
| pprint_safe_repr         | 512 ms                                                      | 541 ms: 1.06x slower                                               |
| regex_compile            | 90.6 ms                                                     | 95.9 ms: 1.06x slower                                              |
| meteor_contest           | 74.7 ms                                                     | 79.3 ms: 1.06x slower                                              |
| scimark_fft              | 178 ms                                                      | 189 ms: 1.06x slower                                               |
| sqlglot_optimize         | 34.9 ms                                                     | 37.0 ms: 1.06x slower                                              |
| go                       | 97.3 ms                                                     | 103 ms: 1.06x slower                                               |
| xml_etree_iterparse      | 62.6 ms                                                     | 66.5 ms: 1.06x slower                                              |
| sqlite_synth             | 1.68 us                                                     | 1.79 us: 1.06x slower                                              |
| deepcopy_reduce          | 2.07 us                                                     | 2.21 us: 1.06x slower                                              |
| pprint_pformat           | 1.04 sec                                                    | 1.11 sec: 1.07x slower                                             |
| pickle                   | 6.61 us                                                     | 7.09 us: 1.07x slower                                              |
| xml_etree_process        | 37.1 ms                                                     | 40.1 ms: 1.08x slower                                              |
| unpickle_list            | 2.55 us                                                     | 2.76 us: 1.08x slower                                              |
| regex_v8                 | 13.8 ms                                                     | 15.0 ms: 1.09x slower                                              |
| nbody                    | 70.0 ms                                                     | 76.8 ms: 1.10x slower                                              |
| xml_etree_generate       | 52.2 ms                                                     | 57.6 ms: 1.10x slower                                              |
| scimark_sor              | 75.6 ms                                                     | 83.6 ms: 1.11x slower                                              |
| pycparser                | 691 ms                                                      | 765 ms: 1.11x slower                                               |
| pathlib                  | 71.4 ms                                                     | 79.3 ms: 1.11x slower                                              |
| bench_mp_pool            | 62.5 ms                                                     | 70.2 ms: 1.12x slower                                              |
| telco                    | 3.90 ms                                                     | 4.87 ms: 1.25x slower                                              |
| async_generators         | 178 ms                                                      | 257 ms: 1.45x slower                                               |
| dask                     | 264 ms                                                      | 391 ms: 1.48x slower                                               |
| Geometric mean           | (ref)                                                       | 1.01x faster                                                       |

Benchmark hidden because not significant (4): pickle_dict, comprehensions, spectral_norm, coroutines
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 93.73% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
