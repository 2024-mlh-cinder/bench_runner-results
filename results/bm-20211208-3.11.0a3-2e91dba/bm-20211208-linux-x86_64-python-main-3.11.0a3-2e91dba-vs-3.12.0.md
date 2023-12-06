
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.01x faster \*
- HPT reliability: 71.01%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                  |
| chameleon      | 7.41 ms                                                | 7.44 ms: 1.00x slower                                 |
| tornado_http   | 101 ms                                                 | 108 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 83.3 ms                                                | 79.2 ms: 1.05x faster                                 |
| nbody          | 92.2 ms                                                | 96.1 ms: 1.04x slower                                 |
| pidigits       | 187 ms                                                 | 198 ms: 1.06x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.21 ms: 1.11x faster                                 |
| regex_compile  | 148 ms                                                 | 139 ms: 1.07x faster                                  |
| regex_dna      | 209 ms                                                 | 212 ms: 1.02x slower                                  |
| regex_v8       | 22.7 ms                                                | 24.5 ms: 1.08x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 27.7 us: 1.21x faster                                 |
| pickle               | 11.2 us                                                | 9.95 us: 1.13x faster                                 |
| json_loads           | 28.4 us                                                | 25.6 us: 1.11x faster                                 |
| xml_etree_generate   | 88.7 ms                                                | 80.8 ms: 1.10x faster                                 |
| unpickle             | 15.8 us                                                | 14.6 us: 1.08x faster                                 |
| xml_etree_process    | 61.2 ms                                                | 57.8 ms: 1.06x faster                                 |
| xml_etree_parse      | 159 ms                                                 | 156 ms: 1.02x faster                                  |
| unpickle_list        | 5.04 us                                                | 5.21 us: 1.03x slower                                 |
| pickle_pure_python   | 326 us                                                 | 347 us: 1.06x slower                                  |
| unpickle_pure_python | 230 us                                                 | 251 us: 1.09x slower                                  |
| json_dumps           | 10.6 ms                                                | 12.6 ms: 1.19x slower                                 |
| Geometric mean       | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.78 ms: 1.20x faster                                 |
| python_startup         | 9.53 ms                                                | 8.00 ms: 1.19x faster                                 |
| Geometric mean         | (ref)                                                  | 1.19x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 11.5 ms                                                | 11.9 ms: 1.04x slower                                 |
| django_template | 35.0 ms                                                | 36.5 ms: 1.04x slower                                 |
| Geometric mean  | (ref)                                                  | 1.04x slower                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 33.5 us                                                | 27.7 us: 1.21x faster                                 |
| python_startup_no_site  | 6.92 ms                                                | 5.78 ms: 1.20x faster                                 |
| python_startup          | 9.53 ms                                                | 8.00 ms: 1.19x faster                                 |
| scimark_fft             | 381 ms                                                 | 332 ms: 1.15x faster                                  |
| pickle                  | 11.2 us                                                | 9.95 us: 1.13x faster                                 |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.77 ms: 1.12x faster                                 |
| regex_effbot            | 3.57 ms                                                | 3.21 ms: 1.11x faster                                 |
| spectral_norm           | 115 ms                                                 | 104 ms: 1.11x faster                                  |
| json_loads              | 28.4 us                                                | 25.6 us: 1.11x faster                                 |
| unpack_sequence         | 54.2 ns                                                | 49.2 ns: 1.10x faster                                 |
| xml_etree_generate      | 88.7 ms                                                | 80.8 ms: 1.10x faster                                 |
| telco                   | 7.18 ms                                                | 6.56 ms: 1.09x faster                                 |
| logging_format          | 7.10 us                                                | 6.49 us: 1.09x faster                                 |
| unpickle                | 15.8 us                                                | 14.6 us: 1.08x faster                                 |
| json                    | 5.22 ms                                                | 4.83 ms: 1.08x faster                                 |
| scimark_lu              | 120 ms                                                 | 112 ms: 1.08x faster                                  |
| logging_simple          | 6.38 us                                                | 5.97 us: 1.07x faster                                 |
| regex_compile           | 148 ms                                                 | 139 ms: 1.07x faster                                  |
| fannkuch                | 410 ms                                                 | 386 ms: 1.06x faster                                  |
| xml_etree_process       | 61.2 ms                                                | 57.8 ms: 1.06x faster                                 |
| float                   | 83.3 ms                                                | 79.2 ms: 1.05x faster                                 |
| meteor_contest          | 110 ms                                                 | 104 ms: 1.05x faster                                  |
| 2to3                    | 274 ms                                                 | 264 ms: 1.04x faster                                  |
| sqlite_synth            | 2.83 us                                                | 2.74 us: 1.04x faster                                 |
| xml_etree_parse         | 159 ms                                                 | 156 ms: 1.02x faster                                  |
| dulwich_log             | 68.7 ms                                                | 67.2 ms: 1.02x faster                                 |
| nqueens                 | 86.2 ms                                                | 84.6 ms: 1.02x faster                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 74.0 ms: 1.01x faster                                 |
| chameleon               | 7.41 ms                                                | 7.44 ms: 1.00x slower                                 |
| scimark_sor             | 129 ms                                                 | 130 ms: 1.01x slower                                  |
| pyflate                 | 471 ms                                                 | 477 ms: 1.01x slower                                  |
| regex_dna               | 209 ms                                                 | 212 ms: 1.02x slower                                  |
| logging_silent          | 108 ns                                                 | 110 ns: 1.03x slower                                  |
| sympy_integrate         | 21.2 ms                                                | 21.7 ms: 1.03x slower                                 |
| sympy_sum               | 167 ms                                                 | 172 ms: 1.03x slower                                  |
| pathlib                 | 18.9 ms                                                | 19.4 ms: 1.03x slower                                 |
| unpickle_list           | 5.04 us                                                | 5.21 us: 1.03x slower                                 |
| hexiom                  | 6.54 ms                                                | 6.77 ms: 1.03x slower                                 |
| mako                    | 11.5 ms                                                | 11.9 ms: 1.04x slower                                 |
| sympy_str               | 296 ms                                                 | 308 ms: 1.04x slower                                  |
| nbody                   | 92.2 ms                                                | 96.1 ms: 1.04x slower                                 |
| django_template         | 35.0 ms                                                | 36.5 ms: 1.04x slower                                 |
| crypto_pyaes            | 83.6 ms                                                | 88.1 ms: 1.05x slower                                 |
| pycparser               | 1.17 sec                                               | 1.24 sec: 1.06x slower                                |
| pidigits                | 187 ms                                                 | 198 ms: 1.06x slower                                  |
| pickle_pure_python      | 326 us                                                 | 347 us: 1.06x slower                                  |
| sympy_expand            | 476 ms                                                 | 509 ms: 1.07x slower                                  |
| tornado_http            | 101 ms                                                 | 108 ms: 1.07x slower                                  |
| regex_v8                | 22.7 ms                                                | 24.5 ms: 1.08x slower                                 |
| raytrace                | 308 ms                                                 | 333 ms: 1.08x slower                                  |
| unpickle_pure_python    | 230 us                                                 | 251 us: 1.09x slower                                  |
| chaos                   | 67.5 ms                                                | 73.9 ms: 1.09x slower                                 |
| go                      | 140 ms                                                 | 158 ms: 1.12x slower                                  |
| richards                | 46.0 ms                                                | 54.5 ms: 1.18x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.6 ms: 1.19x slower                                 |
| deltablue               | 3.71 ms                                                | 4.54 ms: 1.22x slower                                 |
| Geometric mean          | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle_list
Ignored benchmarks (40) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, docutils, gc_traversal, generators, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
Ignored benchmarks (2) of results/bm-20211208-3.11.0a3-2e91dba/bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba.json: html5lib, thrift


# HPT report

- Reliability score: 71.01% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
