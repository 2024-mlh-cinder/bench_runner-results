
# Results vs. 3.11.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: linux-x86_64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 299 ms: 1.05x slower                                                        |
| chameleon      | 7.42 ms                                                      | 9.27 ms: 1.25x slower                                                       |
| docutils       | 2.87 sec                                                     | 3.05 sec: 1.06x slower                                                      |
| html5lib       | 70.7 ms                                                      | 80.0 ms: 1.13x slower                                                       |
| tornado_http   | 125 ms                                                       | 136 ms: 1.08x slower                                                        |
| Geometric mean | (ref)                                                        | 1.11x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_memoization  | 648 ms                                                       | 668 ms: 1.03x slower                                                        |
| async_tree_io           | 1.19 sec                                                     | 1.27 sec: 1.06x slower                                                      |
| async_tree_cpu_io_mixed | 762 ms                                                       | 818 ms: 1.07x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.04x slower                                                                |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| float          | 76.0 ms                                                      | 86.1 ms: 1.13x slower                                                       |
| nbody          | 95.8 ms                                                      | 113 ms: 1.18x slower                                                        |
| Geometric mean | (ref)                                                        | 1.12x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.06 ms: 1.12x faster                                                       |
| regex_compile  | 157 ms                                                       | 158 ms: 1.01x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 25.8 ms: 1.09x slower                                                       |
| regex_dna      | 226 ms                                                       | 262 ms: 1.16x slower                                                        |
| Geometric mean | (ref)                                                        | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads           | 29.0 us                                                      | 24.7 us: 1.18x faster                                                       |
| pickle_dict          | 31.8 us                                                      | 30.2 us: 1.05x faster                                                       |
| xml_etree_iterparse  | 106 ms                                                       | 107 ms: 1.01x slower                                                        |
| unpickle             | 13.2 us                                                      | 13.4 us: 1.01x slower                                                       |
| unpickle_list        | 4.47 us                                                      | 4.55 us: 1.02x slower                                                       |
| pickle               | 9.77 us                                                      | 10.3 us: 1.05x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                                       |
| pickle_list          | 3.89 us                                                      | 4.17 us: 1.07x slower                                                       |
| xml_etree_process    | 56.1 ms                                                      | 61.7 ms: 1.10x slower                                                       |
| unpickle_pure_python | 236 us                                                       | 277 us: 1.17x slower                                                        |
| pickle_pure_python   | 318 us                                                       | 386 us: 1.21x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.04x slower                                                                |

Benchmark hidden because not significant (2): xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 7.78 ms                                                      | 7.43 ms: 1.05x faster                                                       |
| python_startup         | 10.8 ms                                                      | 11.2 ms: 1.03x slower                                                       |
| Geometric mean         | (ref)                                                        | 1.01x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_xml      | 57.2 ms                                                      | 57.9 ms: 1.01x slower                                                       |
| genshi_text     | 26.1 ms                                                      | 28.2 ms: 1.08x slower                                                       |
| django_template | 40.4 ms                                                      | 47.4 ms: 1.17x slower                                                       |
| mako            | 11.0 ms                                                      | 12.9 ms: 1.17x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.11x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf2-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads              | 29.0 us                                                      | 24.7 us: 1.18x faster                                                       |
| regex_effbot            | 3.42 ms                                                      | 3.06 ms: 1.12x faster                                                       |
| gc_traversal            | 4.06 ms                                                      | 3.77 ms: 1.08x faster                                                       |
| json                    | 5.59 ms                                                      | 5.19 ms: 1.08x faster                                                       |
| generators              | 56.4 ms                                                      | 52.7 ms: 1.07x faster                                                       |
| pickle_dict             | 31.8 us                                                      | 30.2 us: 1.05x faster                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.43 ms: 1.05x faster                                                       |
| meteor_contest          | 130 ms                                                       | 128 ms: 1.02x faster                                                        |
| telco                   | 6.91 ms                                                      | 6.81 ms: 1.02x faster                                                       |
| sympy_sum               | 184 ms                                                       | 183 ms: 1.01x faster                                                        |
| regex_compile           | 157 ms                                                       | 158 ms: 1.01x slower                                                        |
| xml_etree_iterparse     | 106 ms                                                       | 107 ms: 1.01x slower                                                        |
| async_generators        | 322 ms                                                       | 325 ms: 1.01x slower                                                        |
| genshi_xml              | 57.2 ms                                                      | 57.9 ms: 1.01x slower                                                       |
| unpickle                | 13.2 us                                                      | 13.4 us: 1.01x slower                                                       |
| sympy_str               | 336 ms                                                       | 340 ms: 1.01x slower                                                        |
| unpickle_list           | 4.47 us                                                      | 4.55 us: 1.02x slower                                                       |
| logging_simple          | 7.21 us                                                      | 7.35 us: 1.02x slower                                                       |
| thrift                  | 941 us                                                       | 961 us: 1.02x slower                                                        |
| sympy_expand            | 550 ms                                                       | 563 ms: 1.02x slower                                                        |
| unpack_sequence         | 44.9 ns                                                      | 46.0 ns: 1.03x slower                                                       |
| nqueens                 | 99.2 ms                                                      | 102 ms: 1.03x slower                                                        |
| bench_thread_pool       | 1.02 ms                                                      | 1.05 ms: 1.03x slower                                                       |
| async_tree_memoization  | 648 ms                                                       | 668 ms: 1.03x slower                                                        |
| coverage                | 66.6 ms                                                      | 68.7 ms: 1.03x slower                                                       |
| python_startup          | 10.8 ms                                                      | 11.2 ms: 1.03x slower                                                       |
| logging_format          | 7.83 us                                                      | 8.08 us: 1.03x slower                                                       |
| sympy_integrate         | 25.6 ms                                                      | 26.5 ms: 1.04x slower                                                       |
| 2to3                    | 286 ms                                                       | 299 ms: 1.05x slower                                                        |
| pathlib                 | 19.1 ms                                                      | 20.0 ms: 1.05x slower                                                       |
| create_gc_cycles        | 1.59 ms                                                      | 1.67 ms: 1.05x slower                                                       |
| pickle                  | 9.77 us                                                      | 10.3 us: 1.05x slower                                                       |
| pidigits                | 251 ms                                                       | 264 ms: 1.05x slower                                                        |
| mdp                     | 2.72 sec                                                     | 2.87 sec: 1.06x slower                                                      |
| coroutines              | 27.9 ms                                                      | 29.5 ms: 1.06x slower                                                       |
| dulwich_log             | 68.3 ms                                                      | 72.4 ms: 1.06x slower                                                       |
| docutils                | 2.87 sec                                                     | 3.05 sec: 1.06x slower                                                      |
| async_tree_io           | 1.19 sec                                                     | 1.27 sec: 1.06x slower                                                      |
| xml_etree_generate      | 80.5 ms                                                      | 85.8 ms: 1.07x slower                                                       |
| dask                    | 417 ms                                                       | 445 ms: 1.07x slower                                                        |
| pickle_list             | 3.89 us                                                      | 4.17 us: 1.07x slower                                                       |
| async_tree_cpu_io_mixed | 762 ms                                                       | 818 ms: 1.07x slower                                                        |
| genshi_text             | 26.1 ms                                                      | 28.2 ms: 1.08x slower                                                       |
| bench_mp_pool           | 4.63 ms                                                      | 5.01 ms: 1.08x slower                                                       |
| tornado_http            | 125 ms                                                       | 136 ms: 1.08x slower                                                        |
| sqlglot_normalize       | 122 ms                                                       | 132 ms: 1.09x slower                                                        |
| regex_v8                | 23.7 ms                                                      | 25.8 ms: 1.09x slower                                                       |
| sqlglot_optimize        | 59.2 ms                                                      | 64.9 ms: 1.10x slower                                                       |
| deepcopy                | 389 us                                                       | 428 us: 1.10x slower                                                        |
| xml_etree_process       | 56.1 ms                                                      | 61.7 ms: 1.10x slower                                                       |
| scimark_fft             | 281 ms                                                       | 311 ms: 1.10x slower                                                        |
| sqlite_synth            | 2.49 us                                                      | 2.75 us: 1.11x slower                                                       |
| chaos                   | 71.6 ms                                                      | 79.2 ms: 1.11x slower                                                       |
| spectral_norm           | 94.0 ms                                                      | 104 ms: 1.11x slower                                                        |
| pprint_pformat          | 1.63 sec                                                     | 1.82 sec: 1.12x slower                                                      |
| pprint_safe_repr        | 780 ms                                                       | 877 ms: 1.13x slower                                                        |
| scimark_monte_carlo     | 70.6 ms                                                      | 79.5 ms: 1.13x slower                                                       |
| hexiom                  | 6.97 ms                                                      | 7.87 ms: 1.13x slower                                                       |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.56 ms: 1.13x slower                                                       |
| deepcopy_reduce         | 3.37 us                                                      | 3.81 us: 1.13x slower                                                       |
| html5lib                | 70.7 ms                                                      | 80.0 ms: 1.13x slower                                                       |
| float                   | 76.0 ms                                                      | 86.1 ms: 1.13x slower                                                       |
| raytrace                | 308 ms                                                       | 349 ms: 1.14x slower                                                        |
| scimark_lu              | 115 ms                                                       | 132 ms: 1.15x slower                                                        |
| deepcopy_memo           | 37.3 us                                                      | 42.9 us: 1.15x slower                                                       |
| pycparser               | 1.28 sec                                                     | 1.48 sec: 1.16x slower                                                      |
| regex_dna               | 226 ms                                                       | 262 ms: 1.16x slower                                                        |
| comprehensions          | 24.8 us                                                      | 28.8 us: 1.16x slower                                                       |
| crypto_pyaes            | 81.8 ms                                                      | 94.9 ms: 1.16x slower                                                       |
| go                      | 166 ms                                                       | 194 ms: 1.17x slower                                                        |
| django_template         | 40.4 ms                                                      | 47.4 ms: 1.17x slower                                                       |
| mako                    | 11.0 ms                                                      | 12.9 ms: 1.17x slower                                                       |
| unpickle_pure_python    | 236 us                                                       | 277 us: 1.17x slower                                                        |
| nbody                   | 95.8 ms                                                      | 113 ms: 1.18x slower                                                        |
| logging_silent          | 102 ns                                                       | 121 ns: 1.18x slower                                                        |
| richards                | 49.9 ms                                                      | 59.0 ms: 1.18x slower                                                       |
| pickle_pure_python      | 318 us                                                       | 386 us: 1.21x slower                                                        |
| flaskblogging           | 3.92 ms                                                      | 4.84 ms: 1.24x slower                                                       |
| chameleon               | 7.42 ms                                                      | 9.27 ms: 1.25x slower                                                       |
| deltablue               | 4.03 ms                                                      | 5.07 ms: 1.26x slower                                                       |
| scimark_sor             | 109 ms                                                       | 140 ms: 1.28x slower                                                        |
| pyflate                 | 453 ms                                                       | 582 ms: 1.28x slower                                                        |
| sqlglot_transpile       | 1.94 ms                                                      | 2.63 ms: 1.36x slower                                                       |
| sqlglot_parse           | 1.55 ms                                                      | 2.24 ms: 1.44x slower                                                       |
| Geometric mean          | (ref)                                                        | 1.08x slower                                                                |

Benchmark hidden because not significant (5): xml_etree_parse, gunicorn, json_dumps, fannkuch, async_tree_none
Ignored benchmarks (15) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.06x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.05x
