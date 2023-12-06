
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.01x faster \*
- HPT reliability: 94.24%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 268 ms: 1.02x faster                                  |
| chameleon      | 7.41 ms                                                | 6.93 ms: 1.07x faster                                 |
| tornado_http   | 101 ms                                                 | 99.2 ms: 1.01x faster                                 |
| Geometric mean | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 83.3 ms                                                | 78.7 ms: 1.06x faster                                 |
| nbody          | 92.2 ms                                                | 97.7 ms: 1.06x slower                                 |
| pidigits       | 187 ms                                                 | 208 ms: 1.11x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 140 ms: 1.06x faster                                  |
| regex_effbot   | 3.57 ms                                                | 3.49 ms: 1.02x faster                                 |
| regex_v8       | 22.7 ms                                                | 23.0 ms: 1.01x slower                                 |
| regex_dna      | 209 ms                                                 | 221 ms: 1.06x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 28.1 us: 1.19x faster                                 |
| pickle               | 11.2 us                                                | 9.69 us: 1.16x faster                                 |
| xml_etree_generate   | 88.7 ms                                                | 79.6 ms: 1.11x faster                                 |
| unpickle             | 15.8 us                                                | 14.2 us: 1.11x faster                                 |
| xml_etree_process    | 61.2 ms                                                | 56.0 ms: 1.09x faster                                 |
| pickle_list          | 4.67 us                                                | 4.51 us: 1.04x faster                                 |
| unpickle_list        | 5.04 us                                                | 4.92 us: 1.03x faster                                 |
| xml_etree_parse      | 159 ms                                                 | 156 ms: 1.02x faster                                  |
| json_loads           | 28.4 us                                                | 28.1 us: 1.01x faster                                 |
| xml_etree_iterparse  | 106 ms                                                 | 105 ms: 1.01x faster                                  |
| pickle_pure_python   | 326 us                                                 | 335 us: 1.03x slower                                  |
| unpickle_pure_python | 230 us                                                 | 246 us: 1.07x slower                                  |
| json_dumps           | 10.6 ms                                                | 12.6 ms: 1.19x slower                                 |
| Geometric mean       | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 8.20 ms: 1.16x faster                                 |
| python_startup_no_site | 6.92 ms                                                | 6.07 ms: 1.14x faster                                 |
| Geometric mean         | (ref)                                                  | 1.15x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 11.5 ms                                                | 10.6 ms: 1.08x faster                                 |
| django_template | 35.0 ms                                                | 36.0 ms: 1.03x slower                                 |
| Geometric mean  | (ref)                                                  | 1.03x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 33.5 us                                                | 28.1 us: 1.19x faster                                 |
| logging_format          | 7.10 us                                                | 6.08 us: 1.17x faster                                 |
| python_startup          | 9.53 ms                                                | 8.20 ms: 1.16x faster                                 |
| pickle                  | 11.2 us                                                | 9.69 us: 1.16x faster                                 |
| logging_simple          | 6.38 us                                                | 5.52 us: 1.16x faster                                 |
| python_startup_no_site  | 6.92 ms                                                | 6.07 ms: 1.14x faster                                 |
| scimark_fft             | 381 ms                                                 | 336 ms: 1.13x faster                                  |
| sqlite_synth            | 2.83 us                                                | 2.51 us: 1.13x faster                                 |
| xml_etree_generate      | 88.7 ms                                                | 79.6 ms: 1.11x faster                                 |
| unpickle                | 15.8 us                                                | 14.2 us: 1.11x faster                                 |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.82 ms: 1.11x faster                                 |
| xml_etree_process       | 61.2 ms                                                | 56.0 ms: 1.09x faster                                 |
| mako                    | 11.5 ms                                                | 10.6 ms: 1.08x faster                                 |
| chameleon               | 7.41 ms                                                | 6.93 ms: 1.07x faster                                 |
| spectral_norm           | 115 ms                                                 | 107 ms: 1.07x faster                                  |
| regex_compile           | 148 ms                                                 | 140 ms: 1.06x faster                                  |
| float                   | 83.3 ms                                                | 78.7 ms: 1.06x faster                                 |
| scimark_sor             | 129 ms                                                 | 123 ms: 1.05x faster                                  |
| json                    | 5.22 ms                                                | 5.00 ms: 1.04x faster                                 |
| scimark_lu              | 120 ms                                                 | 115 ms: 1.04x faster                                  |
| pyflate                 | 471 ms                                                 | 453 ms: 1.04x faster                                  |
| pathlib                 | 18.9 ms                                                | 18.2 ms: 1.04x faster                                 |
| meteor_contest          | 110 ms                                                 | 106 ms: 1.04x faster                                  |
| telco                   | 7.18 ms                                                | 6.92 ms: 1.04x faster                                 |
| pickle_list             | 4.67 us                                                | 4.51 us: 1.04x faster                                 |
| dulwich_log             | 68.7 ms                                                | 66.5 ms: 1.03x faster                                 |
| fannkuch                | 410 ms                                                 | 398 ms: 1.03x faster                                  |
| sympy_sum               | 167 ms                                                 | 163 ms: 1.03x faster                                  |
| unpickle_list           | 5.04 us                                                | 4.92 us: 1.03x faster                                 |
| 2to3                    | 274 ms                                                 | 268 ms: 1.02x faster                                  |
| regex_effbot            | 3.57 ms                                                | 3.49 ms: 1.02x faster                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 72.9 ms: 1.02x faster                                 |
| sympy_str               | 296 ms                                                 | 289 ms: 1.02x faster                                  |
| xml_etree_parse         | 159 ms                                                 | 156 ms: 1.02x faster                                  |
| sympy_integrate         | 21.2 ms                                                | 20.9 ms: 1.02x faster                                 |
| tornado_http            | 101 ms                                                 | 99.2 ms: 1.01x faster                                 |
| json_loads              | 28.4 us                                                | 28.1 us: 1.01x faster                                 |
| xml_etree_iterparse     | 106 ms                                                 | 105 ms: 1.01x faster                                  |
| nqueens                 | 86.2 ms                                                | 87.0 ms: 1.01x slower                                 |
| sympy_expand            | 476 ms                                                 | 481 ms: 1.01x slower                                  |
| crypto_pyaes            | 83.6 ms                                                | 84.6 ms: 1.01x slower                                 |
| regex_v8                | 22.7 ms                                                | 23.0 ms: 1.01x slower                                 |
| pickle_pure_python      | 326 us                                                 | 335 us: 1.03x slower                                  |
| django_template         | 35.0 ms                                                | 36.0 ms: 1.03x slower                                 |
| raytrace                | 308 ms                                                 | 318 ms: 1.03x slower                                  |
| pycparser               | 1.17 sec                                               | 1.21 sec: 1.04x slower                                |
| logging_silent          | 108 ns                                                 | 113 ns: 1.05x slower                                  |
| go                      | 140 ms                                                 | 148 ms: 1.05x slower                                  |
| richards                | 46.0 ms                                                | 48.5 ms: 1.05x slower                                 |
| regex_dna               | 209 ms                                                 | 221 ms: 1.06x slower                                  |
| nbody                   | 92.2 ms                                                | 97.7 ms: 1.06x slower                                 |
| unpickle_pure_python    | 230 us                                                 | 246 us: 1.07x slower                                  |
| hexiom                  | 6.54 ms                                                | 7.04 ms: 1.08x slower                                 |
| chaos                   | 67.5 ms                                                | 73.5 ms: 1.09x slower                                 |
| pidigits                | 187 ms                                                 | 208 ms: 1.11x slower                                  |
| deltablue               | 3.71 ms                                                | 4.16 ms: 1.12x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.6 ms: 1.19x slower                                 |
| unpack_sequence         | 54.2 ns                                                | 131 ns: 2.42x slower                                  |
| Geometric mean          | (ref)                                                  | 1.01x faster                                          |
Ignored benchmarks (40) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, docutils, gc_traversal, generators, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
Ignored benchmarks (2) of results/bm-20220307-3.11.0a6-3ddfa55/bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55.json: html5lib, thrift


# HPT report

- Reliability score: 94.24% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
