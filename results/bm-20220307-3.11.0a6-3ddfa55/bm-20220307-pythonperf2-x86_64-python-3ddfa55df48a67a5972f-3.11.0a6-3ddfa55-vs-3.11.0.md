
# Results vs. 3.11.0

- fork: python
- ref: 3ddfa55df48a67a5972f
- machine: linux-x86_64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.07x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 286 ms                                                       | 300 ms: 1.05x slower                                                        |
| chameleon      | 7.42 ms                                                      | 8.43 ms: 1.14x slower                                                       |
| docutils       | 2.87 sec                                                     | 2.98 sec: 1.04x slower                                                      |
| html5lib       | 70.7 ms                                                      | 75.6 ms: 1.07x slower                                                       |
| tornado_http   | 125 ms                                                       | 130 ms: 1.04x slower                                                        |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none | 529 ms                                                       | 532 ms: 1.01x slower                                                        |
| Geometric mean  | (ref)                                                        | 1.00x slower                                                                |

Benchmark hidden because not significant (3): async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 251 ms                                                       | 253 ms: 1.01x slower                                                        |
| nbody          | 95.8 ms                                                      | 98.0 ms: 1.02x slower                                                       |
| float          | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                        | 1.02x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                                       |
| regex_compile  | 157 ms                                                       | 161 ms: 1.02x slower                                                        |
| regex_v8       | 23.7 ms                                                      | 26.4 ms: 1.11x slower                                                       |
| regex_dna      | 226 ms                                                       | 257 ms: 1.13x slower                                                        |
| Geometric mean | (ref)                                                        | 1.07x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads           | 29.0 us                                                      | 23.9 us: 1.21x faster                                                       |
| xml_etree_parse      | 159 ms                                                       | 154 ms: 1.03x faster                                                        |
| xml_etree_iterparse  | 106 ms                                                       | 104 ms: 1.02x faster                                                        |
| json_dumps           | 13.5 ms                                                      | 13.6 ms: 1.01x slower                                                       |
| pickle_dict          | 31.8 us                                                      | 32.2 us: 1.02x slower                                                       |
| pickle               | 9.77 us                                                      | 9.96 us: 1.02x slower                                                       |
| unpickle             | 13.2 us                                                      | 13.5 us: 1.02x slower                                                       |
| xml_etree_generate   | 80.5 ms                                                      | 83.5 ms: 1.04x slower                                                       |
| unpickle_list        | 4.47 us                                                      | 4.68 us: 1.05x slower                                                       |
| xml_etree_process    | 56.1 ms                                                      | 59.4 ms: 1.06x slower                                                       |
| pickle_list          | 3.89 us                                                      | 4.28 us: 1.10x slower                                                       |
| pickle_pure_python   | 318 us                                                       | 352 us: 1.11x slower                                                        |
| unpickle_pure_python | 236 us                                                       | 273 us: 1.15x slower                                                        |
| Geometric mean       | (ref)                                                        | 1.02x slower                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 10.8 ms                                                      | 10.4 ms: 1.04x faster                                                       |
| python_startup_no_site | 7.78 ms                                                      | 7.55 ms: 1.03x faster                                                       |
| Geometric mean         | (ref)                                                        | 1.03x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_text     | 26.1 ms                                                      | 26.5 ms: 1.02x slower                                                       |
| mako            | 11.0 ms                                                      | 11.4 ms: 1.04x slower                                                       |
| genshi_xml      | 57.2 ms                                                      | 60.7 ms: 1.06x slower                                                       |
| django_template | 40.4 ms                                                      | 43.8 ms: 1.08x slower                                                       |
| Geometric mean  | (ref)                                                        | 1.05x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-pythonperf2-x86_64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-------------------------|:------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| json_loads              | 29.0 us                                                      | 23.9 us: 1.21x faster                                                       |
| json                    | 5.59 ms                                                      | 5.04 ms: 1.11x faster                                                       |
| python_startup          | 10.8 ms                                                      | 10.4 ms: 1.04x faster                                                       |
| python_startup_no_site  | 7.78 ms                                                      | 7.55 ms: 1.03x faster                                                       |
| xml_etree_parse         | 159 ms                                                       | 154 ms: 1.03x faster                                                        |
| generators              | 56.4 ms                                                      | 54.8 ms: 1.03x faster                                                       |
| logging_simple          | 7.21 us                                                      | 7.08 us: 1.02x faster                                                       |
| xml_etree_iterparse     | 106 ms                                                       | 104 ms: 1.02x faster                                                        |
| fannkuch                | 457 ms                                                       | 453 ms: 1.01x faster                                                        |
| logging_format          | 7.83 us                                                      | 7.75 us: 1.01x faster                                                       |
| async_generators        | 322 ms                                                       | 320 ms: 1.00x faster                                                        |
| async_tree_none         | 529 ms                                                       | 532 ms: 1.01x slower                                                        |
| asyncio_tcp             | 752 ms                                                       | 757 ms: 1.01x slower                                                        |
| pidigits                | 251 ms                                                       | 253 ms: 1.01x slower                                                        |
| gunicorn                | 986 us                                                       | 994 us: 1.01x slower                                                        |
| pathlib                 | 19.1 ms                                                      | 19.3 ms: 1.01x slower                                                       |
| json_dumps              | 13.5 ms                                                      | 13.6 ms: 1.01x slower                                                       |
| nqueens                 | 99.2 ms                                                      | 100 ms: 1.01x slower                                                        |
| sympy_integrate         | 25.6 ms                                                      | 25.9 ms: 1.01x slower                                                       |
| pickle_dict             | 31.8 us                                                      | 32.2 us: 1.02x slower                                                       |
| genshi_text             | 26.1 ms                                                      | 26.5 ms: 1.02x slower                                                       |
| meteor_contest          | 130 ms                                                       | 133 ms: 1.02x slower                                                        |
| aiohttp                 | 984 us                                                       | 1.00 ms: 1.02x slower                                                       |
| sqlite_synth            | 2.49 us                                                      | 2.54 us: 1.02x slower                                                       |
| flaskblogging           | 3.92 ms                                                      | 3.99 ms: 1.02x slower                                                       |
| pickle                  | 9.77 us                                                      | 9.96 us: 1.02x slower                                                       |
| bench_thread_pool       | 1.02 ms                                                      | 1.04 ms: 1.02x slower                                                       |
| sympy_str               | 336 ms                                                       | 343 ms: 1.02x slower                                                        |
| regex_effbot            | 3.42 ms                                                      | 3.49 ms: 1.02x slower                                                       |
| unpickle                | 13.2 us                                                      | 13.5 us: 1.02x slower                                                       |
| nbody                   | 95.8 ms                                                      | 98.0 ms: 1.02x slower                                                       |
| create_gc_cycles        | 1.59 ms                                                      | 1.63 ms: 1.02x slower                                                       |
| regex_compile           | 157 ms                                                       | 161 ms: 1.02x slower                                                        |
| xml_etree_generate      | 80.5 ms                                                      | 83.5 ms: 1.04x slower                                                       |
| bench_mp_pool           | 4.63 ms                                                      | 4.80 ms: 1.04x slower                                                       |
| tornado_http            | 125 ms                                                       | 130 ms: 1.04x slower                                                        |
| docutils                | 2.87 sec                                                     | 2.98 sec: 1.04x slower                                                      |
| mako                    | 11.0 ms                                                      | 11.4 ms: 1.04x slower                                                       |
| float                   | 76.0 ms                                                      | 79.1 ms: 1.04x slower                                                       |
| sympy_expand            | 550 ms                                                       | 573 ms: 1.04x slower                                                        |
| unpickle_list           | 4.47 us                                                      | 4.68 us: 1.05x slower                                                       |
| 2to3                    | 286 ms                                                       | 300 ms: 1.05x slower                                                        |
| sqlalchemy_imperative   | 19.9 ms                                                      | 21.0 ms: 1.05x slower                                                       |
| thrift                  | 941 us                                                       | 991 us: 1.05x slower                                                        |
| scimark_monte_carlo     | 70.6 ms                                                      | 74.4 ms: 1.06x slower                                                       |
| scimark_lu              | 115 ms                                                       | 122 ms: 1.06x slower                                                        |
| sqlalchemy_declarative  | 155 ms                                                       | 164 ms: 1.06x slower                                                        |
| xml_etree_process       | 56.1 ms                                                      | 59.4 ms: 1.06x slower                                                       |
| deepcopy                | 389 us                                                       | 413 us: 1.06x slower                                                        |
| dask                    | 417 ms                                                       | 442 ms: 1.06x slower                                                        |
| genshi_xml              | 57.2 ms                                                      | 60.7 ms: 1.06x slower                                                       |
| html5lib                | 70.7 ms                                                      | 75.6 ms: 1.07x slower                                                       |
| mdp                     | 2.72 sec                                                     | 2.91 sec: 1.07x slower                                                      |
| go                      | 166 ms                                                       | 178 ms: 1.07x slower                                                        |
| sqlglot_normalize       | 122 ms                                                       | 131 ms: 1.07x slower                                                        |
| sqlglot_optimize        | 59.2 ms                                                      | 63.7 ms: 1.08x slower                                                       |
| coroutines              | 27.9 ms                                                      | 30.1 ms: 1.08x slower                                                       |
| dulwich_log             | 68.3 ms                                                      | 73.8 ms: 1.08x slower                                                       |
| chaos                   | 71.6 ms                                                      | 77.5 ms: 1.08x slower                                                       |
| scimark_fft             | 281 ms                                                       | 305 ms: 1.08x slower                                                        |
| django_template         | 40.4 ms                                                      | 43.8 ms: 1.08x slower                                                       |
| pprint_pformat          | 1.63 sec                                                     | 1.77 sec: 1.09x slower                                                      |
| pyflate                 | 453 ms                                                       | 494 ms: 1.09x slower                                                        |
| pprint_safe_repr        | 780 ms                                                       | 853 ms: 1.09x slower                                                        |
| pickle_list             | 3.89 us                                                      | 4.28 us: 1.10x slower                                                       |
| scimark_sor             | 109 ms                                                       | 121 ms: 1.10x slower                                                        |
| pickle_pure_python      | 318 us                                                       | 352 us: 1.11x slower                                                        |
| deepcopy_reduce         | 3.37 us                                                      | 3.73 us: 1.11x slower                                                       |
| hexiom                  | 6.97 ms                                                      | 7.74 ms: 1.11x slower                                                       |
| pycparser               | 1.28 sec                                                     | 1.43 sec: 1.11x slower                                                      |
| regex_v8                | 23.7 ms                                                      | 26.4 ms: 1.11x slower                                                       |
| deltablue               | 4.03 ms                                                      | 4.49 ms: 1.12x slower                                                       |
| raytrace                | 308 ms                                                       | 343 ms: 1.12x slower                                                        |
| deepcopy_memo           | 37.3 us                                                      | 41.7 us: 1.12x slower                                                       |
| richards                | 49.9 ms                                                      | 55.9 ms: 1.12x slower                                                       |
| scimark_sparse_mat_mult | 4.04 ms                                                      | 4.53 ms: 1.12x slower                                                       |
| logging_silent          | 102 ns                                                       | 115 ns: 1.13x slower                                                        |
| regex_dna               | 226 ms                                                       | 257 ms: 1.13x slower                                                        |
| chameleon               | 7.42 ms                                                      | 8.43 ms: 1.14x slower                                                       |
| crypto_pyaes            | 81.8 ms                                                      | 93.5 ms: 1.14x slower                                                       |
| unpickle_pure_python    | 236 us                                                       | 273 us: 1.15x slower                                                        |
| spectral_norm           | 94.0 ms                                                      | 111 ms: 1.18x slower                                                        |
| comprehensions          | 24.8 us                                                      | 29.6 us: 1.19x slower                                                       |
| coverage                | 66.6 ms                                                      | 84.1 ms: 1.26x slower                                                       |
| sqlglot_transpile       | 1.94 ms                                                      | 2.50 ms: 1.29x slower                                                       |
| sqlglot_parse           | 1.55 ms                                                      | 2.13 ms: 1.37x slower                                                       |
| unpack_sequence         | 44.9 ns                                                      | 152 ns: 3.38x slower                                                        |
| Geometric mean          | (ref)                                                        | 1.07x slower                                                                |

Benchmark hidden because not significant (6): gc_traversal, sympy_sum, telco, async_tree_io, async_tree_cpu_io_mixed, async_tree_memoization
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
