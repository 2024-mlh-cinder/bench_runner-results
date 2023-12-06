
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: c4e4b91
- commit date: 2022-02-03
- overall geometric mean: 1.02x faster \*
- HPT reliability: 72.83%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 267 ms: 1.03x faster                                  |
| chameleon      | 7.41 ms                                                | 6.95 ms: 1.07x faster                                 |
| tornado_http   | 101 ms                                                 | 106 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 83.3 ms                                                | 77.5 ms: 1.07x faster                                 |
| pidigits       | 187 ms                                                 | 190 ms: 1.01x slower                                  |
| nbody          | 92.2 ms                                                | 94.7 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.14 ms: 1.14x faster                                 |
| regex_compile  | 148 ms                                                 | 140 ms: 1.06x faster                                  |
| regex_dna      | 209 ms                                                 | 213 ms: 1.02x slower                                  |
| regex_v8       | 22.7 ms                                                | 24.0 ms: 1.06x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 28.1 us: 1.19x faster                                 |
| unpickle             | 15.8 us                                                | 13.4 us: 1.17x faster                                 |
| pickle               | 11.2 us                                                | 9.93 us: 1.13x faster                                 |
| xml_etree_generate   | 88.7 ms                                                | 79.6 ms: 1.12x faster                                 |
| xml_etree_process    | 61.2 ms                                                | 57.0 ms: 1.08x faster                                 |
| json_loads           | 28.4 us                                                | 26.7 us: 1.06x faster                                 |
| pickle_list          | 4.67 us                                                | 4.47 us: 1.05x faster                                 |
| xml_etree_parse      | 159 ms                                                 | 153 ms: 1.04x faster                                  |
| xml_etree_iterparse  | 106 ms                                                 | 106 ms: 1.01x slower                                  |
| pickle_pure_python   | 326 us                                                 | 334 us: 1.02x slower                                  |
| unpickle_list        | 5.04 us                                                | 5.26 us: 1.04x slower                                 |
| unpickle_pure_python | 230 us                                                 | 249 us: 1.09x slower                                  |
| json_dumps           | 10.6 ms                                                | 12.2 ms: 1.16x slower                                 |
| Geometric mean       | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 8.13 ms: 1.17x faster                                 |
| python_startup_no_site | 6.92 ms                                                | 5.92 ms: 1.17x faster                                 |
| Geometric mean         | (ref)                                                  | 1.17x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 11.5 ms                                                | 10.5 ms: 1.10x faster                                 |
| django_template | 35.0 ms                                                | 35.4 ms: 1.01x slower                                 |
| Geometric mean  | (ref)                                                  | 1.04x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 33.5 us                                                | 28.1 us: 1.19x faster                                 |
| unpack_sequence         | 54.2 ns                                                | 46.0 ns: 1.18x faster                                 |
| python_startup          | 9.53 ms                                                | 8.13 ms: 1.17x faster                                 |
| unpickle                | 15.8 us                                                | 13.4 us: 1.17x faster                                 |
| python_startup_no_site  | 6.92 ms                                                | 5.92 ms: 1.17x faster                                 |
| regex_effbot            | 3.57 ms                                                | 3.14 ms: 1.14x faster                                 |
| pickle                  | 11.2 us                                                | 9.93 us: 1.13x faster                                 |
| xml_etree_generate      | 88.7 ms                                                | 79.6 ms: 1.12x faster                                 |
| logging_format          | 7.10 us                                                | 6.37 us: 1.11x faster                                 |
| spectral_norm           | 115 ms                                                 | 104 ms: 1.10x faster                                  |
| mako                    | 11.5 ms                                                | 10.5 ms: 1.10x faster                                 |
| scimark_fft             | 381 ms                                                 | 347 ms: 1.10x faster                                  |
| logging_simple          | 6.38 us                                                | 5.84 us: 1.09x faster                                 |
| json                    | 5.22 ms                                                | 4.84 ms: 1.08x faster                                 |
| xml_etree_process       | 61.2 ms                                                | 57.0 ms: 1.08x faster                                 |
| float                   | 83.3 ms                                                | 77.5 ms: 1.07x faster                                 |
| telco                   | 7.18 ms                                                | 6.70 ms: 1.07x faster                                 |
| chameleon               | 7.41 ms                                                | 6.95 ms: 1.07x faster                                 |
| json_loads              | 28.4 us                                                | 26.7 us: 1.06x faster                                 |
| regex_compile           | 148 ms                                                 | 140 ms: 1.06x faster                                  |
| dulwich_log             | 68.7 ms                                                | 65.7 ms: 1.05x faster                                 |
| sqlite_synth            | 2.83 us                                                | 2.71 us: 1.05x faster                                 |
| meteor_contest          | 110 ms                                                 | 105 ms: 1.05x faster                                  |
| pickle_list             | 4.67 us                                                | 4.47 us: 1.05x faster                                 |
| xml_etree_parse         | 159 ms                                                 | 153 ms: 1.04x faster                                  |
| scimark_sparse_mat_mult | 5.33 ms                                                | 5.14 ms: 1.04x faster                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 72.6 ms: 1.03x faster                                 |
| 2to3                    | 274 ms                                                 | 267 ms: 1.03x faster                                  |
| fannkuch                | 410 ms                                                 | 400 ms: 1.02x faster                                  |
| pyflate                 | 471 ms                                                 | 459 ms: 1.02x faster                                  |
| pathlib                 | 18.9 ms                                                | 18.5 ms: 1.02x faster                                 |
| sympy_integrate         | 21.2 ms                                                | 21.3 ms: 1.00x slower                                 |
| xml_etree_iterparse     | 106 ms                                                 | 106 ms: 1.01x slower                                  |
| django_template         | 35.0 ms                                                | 35.4 ms: 1.01x slower                                 |
| nqueens                 | 86.2 ms                                                | 87.2 ms: 1.01x slower                                 |
| pidigits                | 187 ms                                                 | 190 ms: 1.01x slower                                  |
| sympy_sum               | 167 ms                                                 | 170 ms: 1.02x slower                                  |
| pycparser               | 1.17 sec                                               | 1.19 sec: 1.02x slower                                |
| regex_dna               | 209 ms                                                 | 213 ms: 1.02x slower                                  |
| pickle_pure_python      | 326 us                                                 | 334 us: 1.02x slower                                  |
| sympy_str               | 296 ms                                                 | 304 ms: 1.03x slower                                  |
| nbody                   | 92.2 ms                                                | 94.7 ms: 1.03x slower                                 |
| hexiom                  | 6.54 ms                                                | 6.76 ms: 1.03x slower                                 |
| raytrace                | 308 ms                                                 | 321 ms: 1.04x slower                                  |
| unpickle_list           | 5.04 us                                                | 5.26 us: 1.04x slower                                 |
| logging_silent          | 108 ns                                                 | 113 ns: 1.05x slower                                  |
| tornado_http            | 101 ms                                                 | 106 ms: 1.05x slower                                  |
| go                      | 140 ms                                                 | 147 ms: 1.05x slower                                  |
| sympy_expand            | 476 ms                                                 | 503 ms: 1.06x slower                                  |
| regex_v8                | 22.7 ms                                                | 24.0 ms: 1.06x slower                                 |
| unpickle_pure_python    | 230 us                                                 | 249 us: 1.09x slower                                  |
| richards                | 46.0 ms                                                | 50.8 ms: 1.10x slower                                 |
| chaos                   | 67.5 ms                                                | 74.9 ms: 1.11x slower                                 |
| deltablue               | 3.71 ms                                                | 4.13 ms: 1.11x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.2 ms: 1.16x slower                                 |
| Geometric mean          | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (3): scimark_lu, scimark_sor, crypto_pyaes
Ignored benchmarks (40) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, docutils, gc_traversal, generators, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
Ignored benchmarks (2) of results/bm-20220203-3.11.0a5-c4e4b91/bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91.json: html5lib, thrift


# HPT report

- Reliability score: 72.83% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
