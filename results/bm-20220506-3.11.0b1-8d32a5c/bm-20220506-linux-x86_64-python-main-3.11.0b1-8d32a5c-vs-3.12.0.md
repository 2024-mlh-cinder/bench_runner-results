
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 256 ms: 1.07x faster                                  |
| chameleon      | 7.41 ms                                                | 6.57 ms: 1.13x faster                                 |
| tornado_http   | 101 ms                                                 | 94.6 ms: 1.06x faster                                 |
| Geometric mean | (ref)                                                  | 1.09x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 83.3 ms                                                | 72.5 ms: 1.15x faster                                 |
| nbody          | 92.2 ms                                                | 93.1 ms: 1.01x slower                                 |
| pidigits       | 187 ms                                                 | 190 ms: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 2.93 ms: 1.22x faster                                 |
| regex_compile  | 148 ms                                                 | 135 ms: 1.10x faster                                  |
| regex_v8       | 22.7 ms                                                | 21.6 ms: 1.05x faster                                 |
| regex_dna      | 209 ms                                                 | 204 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 25.6 us: 1.31x faster                                 |
| unpickle             | 15.8 us                                                | 13.4 us: 1.18x faster                                 |
| pickle               | 11.2 us                                                | 9.56 us: 1.17x faster                                 |
| xml_etree_generate   | 88.7 ms                                                | 76.5 ms: 1.16x faster                                 |
| xml_etree_process    | 61.2 ms                                                | 53.6 ms: 1.14x faster                                 |
| json_loads           | 28.4 us                                                | 25.4 us: 1.12x faster                                 |
| pickle_list          | 4.67 us                                                | 4.26 us: 1.10x faster                                 |
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                  |
| xml_etree_parse      | 159 ms                                                 | 157 ms: 1.01x faster                                  |
| xml_etree_iterparse  | 106 ms                                                 | 104 ms: 1.01x faster                                  |
| unpickle_pure_python | 230 us                                                 | 229 us: 1.00x faster                                  |
| json_dumps           | 10.6 ms                                                | 12.4 ms: 1.17x slower                                 |
| Geometric mean       | (ref)                                                  | 1.08x faster                                          |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 8.25 ms: 1.16x faster                                 |
| python_startup_no_site | 6.92 ms                                                | 6.16 ms: 1.12x faster                                 |
| Geometric mean         | (ref)                                                  | 1.14x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.88 ms: 1.16x faster                                 |
| django_template | 35.0 ms                                                | 32.8 ms: 1.07x faster                                 |
| Geometric mean  | (ref)                                                  | 1.11x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 33.5 us                                                | 25.6 us: 1.31x faster                                 |
| unpack_sequence         | 54.2 ns                                                | 44.3 ns: 1.22x faster                                 |
| regex_effbot            | 3.57 ms                                                | 2.93 ms: 1.22x faster                                 |
| unpickle                | 15.8 us                                                | 13.4 us: 1.18x faster                                 |
| spectral_norm           | 115 ms                                                 | 97.6 ms: 1.18x faster                                 |
| pickle                  | 11.2 us                                                | 9.56 us: 1.17x faster                                 |
| scimark_fft             | 381 ms                                                 | 325 ms: 1.17x faster                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.57 ms: 1.17x faster                                 |
| mako                    | 11.5 ms                                                | 9.88 ms: 1.16x faster                                 |
| xml_etree_generate      | 88.7 ms                                                | 76.5 ms: 1.16x faster                                 |
| python_startup          | 9.53 ms                                                | 8.25 ms: 1.16x faster                                 |
| float                   | 83.3 ms                                                | 72.5 ms: 1.15x faster                                 |
| pyflate                 | 471 ms                                                 | 411 ms: 1.15x faster                                  |
| xml_etree_process       | 61.2 ms                                                | 53.6 ms: 1.14x faster                                 |
| chameleon               | 7.41 ms                                                | 6.57 ms: 1.13x faster                                 |
| scimark_sor             | 129 ms                                                 | 115 ms: 1.13x faster                                  |
| crypto_pyaes            | 83.6 ms                                                | 74.3 ms: 1.13x faster                                 |
| python_startup_no_site  | 6.92 ms                                                | 6.16 ms: 1.12x faster                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 66.5 ms: 1.12x faster                                 |
| sqlite_synth            | 2.83 us                                                | 2.53 us: 1.12x faster                                 |
| json_loads              | 28.4 us                                                | 25.4 us: 1.12x faster                                 |
| scimark_lu              | 120 ms                                                 | 109 ms: 1.10x faster                                  |
| logging_format          | 7.10 us                                                | 6.44 us: 1.10x faster                                 |
| regex_compile           | 148 ms                                                 | 135 ms: 1.10x faster                                  |
| pickle_list             | 4.67 us                                                | 4.26 us: 1.10x faster                                 |
| logging_silent          | 108 ns                                                 | 98.2 ns: 1.10x faster                                 |
| dulwich_log             | 68.7 ms                                                | 62.8 ms: 1.10x faster                                 |
| logging_simple          | 6.38 us                                                | 5.89 us: 1.08x faster                                 |
| 2to3                    | 274 ms                                                 | 256 ms: 1.07x faster                                  |
| pickle_pure_python      | 326 us                                                 | 305 us: 1.07x faster                                  |
| django_template         | 35.0 ms                                                | 32.8 ms: 1.07x faster                                 |
| fannkuch                | 410 ms                                                 | 385 ms: 1.07x faster                                  |
| json                    | 5.22 ms                                                | 4.91 ms: 1.06x faster                                 |
| tornado_http            | 101 ms                                                 | 94.6 ms: 1.06x faster                                 |
| pathlib                 | 18.9 ms                                                | 17.9 ms: 1.06x faster                                 |
| telco                   | 7.18 ms                                                | 6.84 ms: 1.05x faster                                 |
| meteor_contest          | 110 ms                                                 | 105 ms: 1.05x faster                                  |
| regex_v8                | 22.7 ms                                                | 21.6 ms: 1.05x faster                                 |
| raytrace                | 308 ms                                                 | 294 ms: 1.05x faster                                  |
| sympy_str               | 296 ms                                                 | 284 ms: 1.04x faster                                  |
| hexiom                  | 6.54 ms                                                | 6.29 ms: 1.04x faster                                 |
| sympy_sum               | 167 ms                                                 | 161 ms: 1.04x faster                                  |
| sympy_integrate         | 21.2 ms                                                | 20.5 ms: 1.04x faster                                 |
| go                      | 140 ms                                                 | 136 ms: 1.03x faster                                  |
| deltablue               | 3.71 ms                                                | 3.61 ms: 1.03x faster                                 |
| regex_dna               | 209 ms                                                 | 204 ms: 1.02x faster                                  |
| sympy_expand            | 476 ms                                                 | 468 ms: 1.02x faster                                  |
| nqueens                 | 86.2 ms                                                | 84.7 ms: 1.02x faster                                 |
| xml_etree_parse         | 159 ms                                                 | 157 ms: 1.01x faster                                  |
| xml_etree_iterparse     | 106 ms                                                 | 104 ms: 1.01x faster                                  |
| unpickle_pure_python    | 230 us                                                 | 229 us: 1.00x faster                                  |
| richards                | 46.0 ms                                                | 46.4 ms: 1.01x slower                                 |
| nbody                   | 92.2 ms                                                | 93.1 ms: 1.01x slower                                 |
| pycparser               | 1.17 sec                                               | 1.18 sec: 1.01x slower                                |
| pidigits                | 187 ms                                                 | 190 ms: 1.01x slower                                  |
| chaos                   | 67.5 ms                                                | 68.6 ms: 1.02x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.4 ms: 1.17x slower                                 |
| Geometric mean          | (ref)                                                  | 1.08x faster                                          |

Benchmark hidden because not significant (1): unpickle_list
Ignored benchmarks (40) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, docutils, gc_traversal, generators, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
Ignored benchmarks (2) of results/bm-20220506-3.11.0b1-8d32a5c/bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c.json: html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.04x
