
# Results vs. 3.10.4

- fork: python
- ref: v3.11.6
- machine: windows-amd64
- commit hash: 8b6ee5b
- commit date: 2023-10-02
- overall geometric mean: 1.11x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| 2to3           | 237 ms                                                      | 207 ms: 1.14x faster                                        |
| chameleon      | 5.92 ms                                                     | 5.24 ms: 1.13x faster                                       |
| docutils       | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                      |
| html5lib       | 46.5 ms                                                     | 38.9 ms: 1.19x faster                                       |
| tornado_http   | 109 ms                                                      | 90.5 ms: 1.21x faster                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 54.3 ms: 1.11x faster                                       |
| pidigits       | 145 ms                                                      | 148 ms: 1.02x slower                                        |
| Geometric mean | (ref)                                                       | 1.03x faster                                                |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 91.7 ms: 1.13x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.53 ms: 1.09x faster                                       |
| regex_dna      | 132 ms                                                      | 122 ms: 1.08x faster                                        |
| regex_v8       | 15.0 ms                                                     | 14.2 ms: 1.06x faster                                       |
| Geometric mean | (ref)                                                       | 1.09x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| pickle_pure_python   | 257 us                                                      | 203 us: 1.26x faster                                        |
| unpickle             | 9.17 us                                                     | 7.67 us: 1.20x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 37.8 ms: 1.15x faster                                       |
| tomli_loads          | 1.62 sec                                                    | 1.42 sec: 1.15x faster                                      |
| unpickle_pure_python | 171 us                                                      | 151 us: 1.13x faster                                        |
| json_dumps           | 8.50 ms                                                     | 7.74 ms: 1.10x faster                                       |
| json_loads           | 14.2 us                                                     | 13.2 us: 1.07x faster                                       |
| unpickle_list        | 2.81 us                                                     | 2.64 us: 1.06x faster                                       |
| xml_etree_parse      | 102 ms                                                      | 97.3 ms: 1.05x faster                                       |
| xml_etree_generate   | 54.5 ms                                                     | 52.9 ms: 1.03x faster                                       |
| pickle               | 6.80 us                                                     | 6.67 us: 1.02x faster                                       |
| pickle_list          | 2.59 us                                                     | 2.70 us: 1.04x slower                                       |
| pickle_dict          | 16.9 us                                                     | 18.4 us: 1.09x slower                                       |
| Geometric mean       | (ref)                                                       | 1.07x faster                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup | 20.0 ms                                                     | 18.6 ms: 1.08x faster                                       |
| Geometric mean | (ref)                                                       | 1.03x faster                                                |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|-----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako            | 8.80 ms                                                     | 7.31 ms: 1.20x faster                                       |
| django_template | 28.2 ms                                                     | 23.6 ms: 1.20x faster                                       |
| genshi_text     | 19.0 ms                                                     | 17.2 ms: 1.11x faster                                       |
| genshi_xml      | 40.5 ms                                                     | 38.1 ms: 1.06x faster                                       |
| Geometric mean  | (ref)                                                       | 1.14x faster                                                |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b |
|-------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| deltablue               | 4.17 ms                                                     | 2.63 ms: 1.59x faster                                       |
| scimark_lu              | 85.4 ms                                                     | 61.9 ms: 1.38x faster                                       |
| async_tree_io           | 1.07 sec                                                    | 778 ms: 1.37x faster                                        |
| scimark_sor             | 105 ms                                                      | 76.8 ms: 1.37x faster                                       |
| logging_silent          | 96.4 ns                                                     | 70.7 ns: 1.36x faster                                       |
| async_tree_none         | 420 ms                                                      | 311 ms: 1.35x faster                                        |
| richards_super          | 51.7 ms                                                     | 38.4 ms: 1.35x faster                                       |
| richards                | 41.2 ms                                                     | 30.6 ms: 1.34x faster                                       |
| raytrace                | 271 ms                                                      | 203 ms: 1.34x faster                                        |
| go                      | 136 ms                                                      | 102 ms: 1.34x faster                                        |
| async_tree_memoization  | 497 ms                                                      | 375 ms: 1.33x faster                                        |
| sqlglot_parse           | 1.22 ms                                                     | 938 us: 1.30x faster                                        |
| sqlglot_transpile       | 1.46 ms                                                     | 1.14 ms: 1.28x faster                                       |
| mypy2                   | 352 ms                                                      | 277 ms: 1.27x faster                                        |
| pyflate                 | 387 ms                                                      | 305 ms: 1.27x faster                                        |
| crypto_pyaes            | 62.3 ms                                                     | 49.3 ms: 1.26x faster                                       |
| pickle_pure_python      | 257 us                                                      | 203 us: 1.26x faster                                        |
| thrift                  | 615 us                                                      | 487 us: 1.26x faster                                        |
| async_generators        | 224 ms                                                      | 179 ms: 1.25x faster                                        |
| pycparser               | 868 ms                                                      | 694 ms: 1.25x faster                                        |
| hexiom                  | 5.52 ms                                                     | 4.55 ms: 1.21x faster                                       |
| scimark_monte_carlo     | 55.9 ms                                                     | 46.3 ms: 1.21x faster                                       |
| tornado_http            | 109 ms                                                      | 90.5 ms: 1.21x faster                                       |
| mako                    | 8.80 ms                                                     | 7.31 ms: 1.20x faster                                       |
| django_template         | 28.2 ms                                                     | 23.6 ms: 1.20x faster                                       |
| unpickle                | 9.17 us                                                     | 7.67 us: 1.20x faster                                       |
| html5lib                | 46.5 ms                                                     | 38.9 ms: 1.19x faster                                       |
| chaos                   | 58.9 ms                                                     | 49.7 ms: 1.18x faster                                       |
| async_tree_cpu_io_mixed | 609 ms                                                      | 515 ms: 1.18x faster                                        |
| aiohttp                 | 1.01 ms                                                     | 853 us: 1.18x faster                                        |
| docutils                | 1.89 sec                                                    | 1.60 sec: 1.18x faster                                      |
| dask                    | 305 ms                                                      | 263 ms: 1.16x faster                                        |
| spectral_norm           | 78.0 ms                                                     | 67.5 ms: 1.16x faster                                       |
| xml_etree_process       | 43.4 ms                                                     | 37.8 ms: 1.15x faster                                       |
| tomli_loads             | 1.62 sec                                                    | 1.42 sec: 1.15x faster                                      |
| 2to3                    | 237 ms                                                      | 207 ms: 1.14x faster                                        |
| pprint_safe_repr        | 589 ms                                                      | 517 ms: 1.14x faster                                        |
| sqlalchemy_declarative  | 95.4 ms                                                     | 83.8 ms: 1.14x faster                                       |
| pprint_pformat          | 1.21 sec                                                    | 1.06 sec: 1.14x faster                                      |
| unpickle_pure_python    | 171 us                                                      | 151 us: 1.13x faster                                        |
| chameleon               | 5.92 ms                                                     | 5.24 ms: 1.13x faster                                       |
| deepcopy_memo           | 28.5 us                                                     | 25.3 us: 1.13x faster                                       |
| pathlib                 | 77.4 ms                                                     | 68.5 ms: 1.13x faster                                       |
| regex_compile           | 103 ms                                                      | 91.7 ms: 1.13x faster                                       |
| bench_thread_pool       | 946 us                                                      | 852 us: 1.11x faster                                        |
| sqlglot_optimize        | 39.0 ms                                                     | 35.1 ms: 1.11x faster                                       |
| genshi_text             | 19.0 ms                                                     | 17.2 ms: 1.11x faster                                       |
| float                   | 60.2 ms                                                     | 54.3 ms: 1.11x faster                                       |
| create_gc_cycles        | 782 us                                                      | 708 us: 1.10x faster                                        |
| json_dumps              | 8.50 ms                                                     | 7.74 ms: 1.10x faster                                       |
| pylint                  | 347 ms                                                      | 318 ms: 1.09x faster                                        |
| regex_effbot            | 1.66 ms                                                     | 1.53 ms: 1.09x faster                                       |
| coroutines              | 15.9 ms                                                     | 14.7 ms: 1.09x faster                                       |
| regex_dna               | 132 ms                                                      | 122 ms: 1.08x faster                                        |
| python_startup          | 20.0 ms                                                     | 18.6 ms: 1.08x faster                                       |
| json_loads              | 14.2 us                                                     | 13.2 us: 1.07x faster                                       |
| sympy_integrate         | 14.8 ms                                                     | 13.8 ms: 1.07x faster                                       |
| fannkuch                | 258 ms                                                      | 241 ms: 1.07x faster                                        |
| sqlite_synth            | 1.84 us                                                     | 1.72 us: 1.07x faster                                       |
| sqlalchemy_imperative   | 11.0 ms                                                     | 10.3 ms: 1.07x faster                                       |
| scimark_fft             | 193 ms                                                      | 181 ms: 1.07x faster                                        |
| unpickle_list           | 2.81 us                                                     | 2.64 us: 1.06x faster                                       |
| genshi_xml              | 40.5 ms                                                     | 38.1 ms: 1.06x faster                                       |
| regex_v8                | 15.0 ms                                                     | 14.2 ms: 1.06x faster                                       |
| dulwich_log             | 47.6 ms                                                     | 45.0 ms: 1.06x faster                                       |
| sqlglot_normalize       | 202 ms                                                      | 192 ms: 1.05x faster                                        |
| nqueens                 | 67.0 ms                                                     | 63.7 ms: 1.05x faster                                       |
| xml_etree_parse         | 102 ms                                                      | 97.3 ms: 1.05x faster                                       |
| scimark_sparse_mat_mult | 2.66 ms                                                     | 2.55 ms: 1.04x faster                                       |
| deepcopy                | 255 us                                                      | 246 us: 1.04x faster                                        |
| bench_mp_pool           | 60.7 ms                                                     | 58.7 ms: 1.03x faster                                       |
| sympy_expand            | 315 ms                                                      | 305 ms: 1.03x faster                                        |
| xml_etree_generate      | 54.5 ms                                                     | 52.9 ms: 1.03x faster                                       |
| deepcopy_reduce         | 2.16 us                                                     | 2.10 us: 1.03x faster                                       |
| sympy_sum               | 104 ms                                                      | 102 ms: 1.02x faster                                        |
| pickle                  | 6.80 us                                                     | 6.67 us: 1.02x faster                                       |
| comprehensions          | 16.0 us                                                     | 15.7 us: 1.02x faster                                       |
| flaskblogging           | 2.04 sec                                                    | 2.03 sec: 1.01x faster                                      |
| sympy_str               | 188 ms                                                      | 187 ms: 1.00x faster                                        |
| pidigits                | 145 ms                                                      | 148 ms: 1.02x slower                                        |
| telco                   | 3.78 ms                                                     | 3.93 ms: 1.04x slower                                       |
| pickle_list             | 2.59 us                                                     | 2.70 us: 1.04x slower                                       |
| meteor_contest          | 72.5 ms                                                     | 76.1 ms: 1.05x slower                                       |
| generators              | 31.6 ms                                                     | 33.7 ms: 1.07x slower                                       |
| logging_format          | 6.66 us                                                     | 7.18 us: 1.08x slower                                       |
| logging_simple          | 6.20 us                                                     | 6.72 us: 1.08x slower                                       |
| pickle_dict             | 16.9 us                                                     | 18.4 us: 1.09x slower                                       |
| gc_traversal            | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                       |
| unpack_sequence         | 37.8 ns                                                     | 46.3 ns: 1.22x slower                                       |
| coverage                | 40.0 ms                                                     | 53.6 ms: 1.34x slower                                       |
| Geometric mean          | (ref)                                                       | 1.11x faster                                                |

Benchmark hidden because not significant (8): json, xml_etree_iterparse, typing_runtime_protocols, mdp, python_startup_no_site, nbody, asyncio_tcp_ssl, asyncio_tcp


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.07x
