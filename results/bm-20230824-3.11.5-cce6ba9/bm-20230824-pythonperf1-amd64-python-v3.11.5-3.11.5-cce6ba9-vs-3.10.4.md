
# Results vs. 3.10.4

- fork: python
- ref: v3.11.5
- machine: windows-amd64
- commit hash: cce6ba9
- commit date: 2023-08-24
- overall geometric mean: 1.11x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 208 ms: 1.14x faster                                        |
| chameleon      | 5.92 ms                                                     | 5.27 ms: 1.13x faster                                       |
| docutils       | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                      |
| html5lib       | 46.5 ms                                                     | 38.8 ms: 1.20x faster                                       |
| tornado_http   | 109 ms                                                      | 90.6 ms: 1.20x faster                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 53.9 ms: 1.12x faster                                       |
| nbody          | 69.3 ms                                                     | 70.1 ms: 1.01x slower                                       |
| pidigits       | 145 ms                                                      | 148 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                       | 1.03x faster                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 91.3 ms: 1.13x faster                                       |
| regex_dna      | 132 ms                                                      | 117 ms: 1.12x faster                                        |
| regex_effbot   | 1.66 ms                                                     | 1.49 ms: 1.12x faster                                       |
| regex_v8       | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                       |
| Geometric mean | (ref)                                                       | 1.12x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 257 us                                                      | 202 us: 1.27x faster                                        |
| xml_etree_process    | 43.4 ms                                                     | 36.9 ms: 1.18x faster                                       |
| unpickle             | 9.17 us                                                     | 7.92 us: 1.16x faster                                       |
| tomli_loads          | 1.62 sec                                                    | 1.41 sec: 1.15x faster                                      |
| unpickle_pure_python | 171 us                                                      | 151 us: 1.13x faster                                        |
| json_dumps           | 8.50 ms                                                     | 7.63 ms: 1.11x faster                                       |
| json_loads           | 14.2 us                                                     | 13.0 us: 1.09x faster                                       |
| unpickle_list        | 2.81 us                                                     | 2.60 us: 1.08x faster                                       |
| xml_etree_generate   | 54.5 ms                                                     | 51.8 ms: 1.05x faster                                       |
| xml_etree_parse      | 102 ms                                                      | 97.0 ms: 1.05x faster                                       |
| pickle               | 6.80 us                                                     | 6.86 us: 1.01x slower                                       |
| pickle_list          | 2.59 us                                                     | 2.75 us: 1.06x slower                                       |
| pickle_dict          | 16.9 us                                                     | 18.5 us: 1.09x slower                                       |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                       |
| python_startup_no_site | 15.5 ms                                                     | 16.5 ms: 1.06x slower                                       |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| django_template | 28.2 ms                                                     | 23.9 ms: 1.18x faster                                       |
| mako            | 8.80 ms                                                     | 7.44 ms: 1.18x faster                                       |
| genshi_text     | 19.0 ms                                                     | 17.5 ms: 1.09x faster                                       |
| genshi_xml      | 40.5 ms                                                     | 38.0 ms: 1.07x faster                                       |
| Geometric mean  | (ref)                                                       | 1.13x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230824-pythonperf1-amd64-python-v3.11.5-3.11.5-cce6ba9 |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| deltablue                | 4.17 ms                                                     | 2.61 ms: 1.60x faster                                       |
| go                       | 136 ms                                                      | 98.8 ms: 1.38x faster                                       |
| logging_silent           | 96.4 ns                                                     | 70.0 ns: 1.38x faster                                       |
| scimark_sor              | 105 ms                                                      | 76.5 ms: 1.37x faster                                       |
| richards                 | 41.2 ms                                                     | 30.1 ms: 1.37x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 779 ms: 1.37x faster                                        |
| scimark_lu               | 85.4 ms                                                     | 62.7 ms: 1.36x faster                                       |
| richards_super           | 51.7 ms                                                     | 38.0 ms: 1.36x faster                                       |
| async_tree_none          | 420 ms                                                      | 311 ms: 1.35x faster                                        |
| raytrace                 | 271 ms                                                      | 203 ms: 1.33x faster                                        |
| async_tree_memoization   | 497 ms                                                      | 375 ms: 1.33x faster                                        |
| sqlglot_parse            | 1.22 ms                                                     | 928 us: 1.31x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 48.1 ms: 1.30x faster                                       |
| sqlglot_transpile        | 1.46 ms                                                     | 1.13 ms: 1.29x faster                                       |
| pyflate                  | 387 ms                                                      | 302 ms: 1.28x faster                                        |
| mypy2                    | 352 ms                                                      | 275 ms: 1.28x faster                                        |
| pickle_pure_python       | 257 us                                                      | 202 us: 1.27x faster                                        |
| thrift                   | 615 us                                                      | 488 us: 1.26x faster                                        |
| async_generators         | 224 ms                                                      | 180 ms: 1.24x faster                                        |
| pycparser                | 868 ms                                                      | 699 ms: 1.24x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.55 ms: 1.21x faster                                       |
| tornado_http             | 109 ms                                                      | 90.6 ms: 1.20x faster                                       |
| scimark_monte_carlo      | 55.9 ms                                                     | 46.5 ms: 1.20x faster                                       |
| html5lib                 | 46.5 ms                                                     | 38.8 ms: 1.20x faster                                       |
| chaos                    | 58.9 ms                                                     | 49.5 ms: 1.19x faster                                       |
| django_template          | 28.2 ms                                                     | 23.9 ms: 1.18x faster                                       |
| mako                     | 8.80 ms                                                     | 7.44 ms: 1.18x faster                                       |
| docutils                 | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                      |
| aiohttp                  | 1.01 ms                                                     | 853 us: 1.18x faster                                        |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 516 ms: 1.18x faster                                        |
| xml_etree_process        | 43.4 ms                                                     | 36.9 ms: 1.18x faster                                       |
| unpickle                 | 9.17 us                                                     | 7.92 us: 1.16x faster                                       |
| spectral_norm            | 78.0 ms                                                     | 67.5 ms: 1.16x faster                                       |
| tomli_loads              | 1.62 sec                                                    | 1.41 sec: 1.15x faster                                      |
| deepcopy_memo            | 28.5 us                                                     | 24.7 us: 1.15x faster                                       |
| dask                     | 305 ms                                                      | 265 ms: 1.15x faster                                        |
| pprint_safe_repr         | 589 ms                                                      | 513 ms: 1.15x faster                                        |
| pprint_pformat           | 1.21 sec                                                    | 1.05 sec: 1.15x faster                                      |
| sqlalchemy_declarative   | 95.4 ms                                                     | 83.8 ms: 1.14x faster                                       |
| 2to3                     | 237 ms                                                      | 208 ms: 1.14x faster                                        |
| unpickle_pure_python     | 171 us                                                      | 151 us: 1.13x faster                                        |
| regex_compile            | 103 ms                                                      | 91.3 ms: 1.13x faster                                       |
| sqlglot_optimize         | 39.0 ms                                                     | 34.5 ms: 1.13x faster                                       |
| chameleon                | 5.92 ms                                                     | 5.27 ms: 1.13x faster                                       |
| regex_dna                | 132 ms                                                      | 117 ms: 1.12x faster                                        |
| regex_effbot             | 1.66 ms                                                     | 1.49 ms: 1.12x faster                                       |
| float                    | 60.2 ms                                                     | 53.9 ms: 1.12x faster                                       |
| json_dumps               | 8.50 ms                                                     | 7.63 ms: 1.11x faster                                       |
| pathlib                  | 77.4 ms                                                     | 69.7 ms: 1.11x faster                                       |
| create_gc_cycles         | 782 us                                                      | 709 us: 1.10x faster                                        |
| coroutines               | 15.9 ms                                                     | 14.5 ms: 1.10x faster                                       |
| bench_thread_pool        | 946 us                                                      | 863 us: 1.10x faster                                        |
| regex_v8                 | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                       |
| json_loads               | 14.2 us                                                     | 13.0 us: 1.09x faster                                       |
| dulwich_log              | 47.6 ms                                                     | 43.6 ms: 1.09x faster                                       |
| genshi_text              | 19.0 ms                                                     | 17.5 ms: 1.09x faster                                       |
| pylint                   | 347 ms                                                      | 320 ms: 1.08x faster                                        |
| unpickle_list            | 2.81 us                                                     | 2.60 us: 1.08x faster                                       |
| sympy_integrate          | 14.8 ms                                                     | 13.7 ms: 1.08x faster                                       |
| nqueens                  | 67.0 ms                                                     | 62.3 ms: 1.08x faster                                       |
| sqlite_synth             | 1.84 us                                                     | 1.72 us: 1.07x faster                                       |
| genshi_xml               | 40.5 ms                                                     | 38.0 ms: 1.07x faster                                       |
| scimark_fft              | 193 ms                                                      | 181 ms: 1.06x faster                                        |
| sqlglot_normalize        | 202 ms                                                      | 190 ms: 1.06x faster                                        |
| deepcopy                 | 255 us                                                      | 241 us: 1.06x faster                                        |
| sympy_expand             | 315 ms                                                      | 299 ms: 1.05x faster                                        |
| sqlalchemy_imperative    | 11.0 ms                                                     | 10.4 ms: 1.05x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.63 sec: 1.05x faster                                      |
| xml_etree_generate       | 54.5 ms                                                     | 51.8 ms: 1.05x faster                                       |
| xml_etree_parse          | 102 ms                                                      | 97.0 ms: 1.05x faster                                       |
| deepcopy_reduce          | 2.16 us                                                     | 2.06 us: 1.05x faster                                       |
| sympy_sum                | 104 ms                                                      | 100 ms: 1.04x faster                                        |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.57 ms: 1.03x faster                                       |
| python_startup           | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                       |
| sympy_str                | 188 ms                                                      | 183 ms: 1.03x faster                                        |
| flaskblogging            | 2.04 sec                                                    | 2.03 sec: 1.00x faster                                      |
| pickle                   | 6.80 us                                                     | 6.86 us: 1.01x slower                                       |
| typing_runtime_protocols | 325 us                                                      | 327 us: 1.01x slower                                        |
| nbody                    | 69.3 ms                                                     | 70.1 ms: 1.01x slower                                       |
| bench_mp_pool            | 60.7 ms                                                     | 61.5 ms: 1.01x slower                                       |
| pidigits                 | 145 ms                                                      | 148 ms: 1.02x slower                                        |
| fannkuch                 | 258 ms                                                      | 268 ms: 1.04x slower                                        |
| telco                    | 3.78 ms                                                     | 3.96 ms: 1.05x slower                                       |
| meteor_contest           | 72.5 ms                                                     | 76.8 ms: 1.06x slower                                       |
| logging_simple           | 6.20 us                                                     | 6.56 us: 1.06x slower                                       |
| logging_format           | 6.66 us                                                     | 7.06 us: 1.06x slower                                       |
| pickle_list              | 2.59 us                                                     | 2.75 us: 1.06x slower                                       |
| python_startup_no_site   | 15.5 ms                                                     | 16.5 ms: 1.06x slower                                       |
| generators               | 31.6 ms                                                     | 33.8 ms: 1.07x slower                                       |
| pickle_dict              | 16.9 us                                                     | 18.5 us: 1.09x slower                                       |
| gc_traversal             | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                       |
| unpack_sequence          | 37.8 ns                                                     | 45.5 ns: 1.20x slower                                       |
| coverage                 | 40.0 ms                                                     | 54.3 ms: 1.36x slower                                       |
| Geometric mean           | (ref)                                                       | 1.11x faster                                                |

Benchmark hidden because not significant (5): asyncio_tcp, comprehensions, xml_etree_iterparse, json, asyncio_tcp_ssl


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
