
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.05x faster \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 274 ms                                                 | 264 ms: 1.04x faster                                  |
| chameleon      | 7.41 ms                                                | 6.87 ms: 1.08x faster                                 |
| tornado_http   | 101 ms                                                 | 95.4 ms: 1.06x faster                                 |
| Geometric mean | (ref)                                                  | 1.06x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 83.3 ms                                                | 74.4 ms: 1.12x faster                                 |
| nbody          | 92.2 ms                                                | 95.2 ms: 1.03x slower                                 |
| pidigits       | 187 ms                                                 | 197 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 137 ms: 1.08x faster                                  |
| regex_effbot   | 3.57 ms                                                | 3.34 ms: 1.07x faster                                 |
| regex_dna      | 209 ms                                                 | 231 ms: 1.11x slower                                  |
| regex_v8       | 22.7 ms                                                | 25.9 ms: 1.14x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 27.6 us: 1.21x faster                                 |
| pickle               | 11.2 us                                                | 9.55 us: 1.17x faster                                 |
| xml_etree_generate   | 88.7 ms                                                | 78.5 ms: 1.13x faster                                 |
| unpickle             | 15.8 us                                                | 14.1 us: 1.12x faster                                 |
| xml_etree_process    | 61.2 ms                                                | 55.2 ms: 1.11x faster                                 |
| pickle_pure_python   | 326 us                                                 | 311 us: 1.05x faster                                  |
| pickle_list          | 4.67 us                                                | 4.57 us: 1.02x faster                                 |
| xml_etree_iterparse  | 106 ms                                                 | 104 ms: 1.02x faster                                  |
| xml_etree_parse      | 159 ms                                                 | 157 ms: 1.02x faster                                  |
| unpickle_list        | 5.04 us                                                | 4.97 us: 1.02x faster                                 |
| json_loads           | 28.4 us                                                | 28.1 us: 1.01x faster                                 |
| unpickle_pure_python | 230 us                                                 | 231 us: 1.00x slower                                  |
| json_dumps           | 10.6 ms                                                | 12.5 ms: 1.18x slower                                 |
| Geometric mean       | (ref)                                                  | 1.05x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 9.53 ms                                                | 8.07 ms: 1.18x faster                                 |
| python_startup_no_site | 6.92 ms                                                | 5.98 ms: 1.16x faster                                 |
| Geometric mean         | (ref)                                                  | 1.17x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 11.5 ms                                                | 10.2 ms: 1.13x faster                                 |
| django_template | 35.0 ms                                                | 34.3 ms: 1.02x faster                                 |
| Geometric mean  | (ref)                                                  | 1.07x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 33.5 us                                                | 27.6 us: 1.21x faster                                 |
| unpack_sequence         | 54.2 ns                                                | 44.9 ns: 1.21x faster                                 |
| python_startup          | 9.53 ms                                                | 8.07 ms: 1.18x faster                                 |
| pickle                  | 11.2 us                                                | 9.55 us: 1.17x faster                                 |
| python_startup_no_site  | 6.92 ms                                                | 5.98 ms: 1.16x faster                                 |
| scimark_fft             | 381 ms                                                 | 335 ms: 1.14x faster                                  |
| xml_etree_generate      | 88.7 ms                                                | 78.5 ms: 1.13x faster                                 |
| sqlite_synth            | 2.83 us                                                | 2.51 us: 1.13x faster                                 |
| mako                    | 11.5 ms                                                | 10.2 ms: 1.13x faster                                 |
| float                   | 83.3 ms                                                | 74.4 ms: 1.12x faster                                 |
| unpickle                | 15.8 us                                                | 14.1 us: 1.12x faster                                 |
| logging_format          | 7.10 us                                                | 6.35 us: 1.12x faster                                 |
| scimark_lu              | 120 ms                                                 | 108 ms: 1.11x faster                                  |
| xml_etree_process       | 61.2 ms                                                | 55.2 ms: 1.11x faster                                 |
| logging_simple          | 6.38 us                                                | 5.80 us: 1.10x faster                                 |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.85 ms: 1.10x faster                                 |
| spectral_norm           | 115 ms                                                 | 105 ms: 1.10x faster                                  |
| telco                   | 7.18 ms                                                | 6.59 ms: 1.09x faster                                 |
| chameleon               | 7.41 ms                                                | 6.87 ms: 1.08x faster                                 |
| regex_compile           | 148 ms                                                 | 137 ms: 1.08x faster                                  |
| dulwich_log             | 68.7 ms                                                | 63.8 ms: 1.08x faster                                 |
| pyflate                 | 471 ms                                                 | 438 ms: 1.07x faster                                  |
| regex_effbot            | 3.57 ms                                                | 3.34 ms: 1.07x faster                                 |
| tornado_http            | 101 ms                                                 | 95.4 ms: 1.06x faster                                 |
| scimark_monte_carlo     | 74.6 ms                                                | 70.8 ms: 1.05x faster                                 |
| scimark_sor             | 129 ms                                                 | 123 ms: 1.05x faster                                  |
| pickle_pure_python      | 326 us                                                 | 311 us: 1.05x faster                                  |
| sympy_sum               | 167 ms                                                 | 160 ms: 1.05x faster                                  |
| 2to3                    | 274 ms                                                 | 264 ms: 1.04x faster                                  |
| logging_silent          | 108 ns                                                 | 104 ns: 1.04x faster                                  |
| sympy_integrate         | 21.2 ms                                                | 20.5 ms: 1.04x faster                                 |
| json                    | 5.22 ms                                                | 5.07 ms: 1.03x faster                                 |
| sympy_str               | 296 ms                                                 | 287 ms: 1.03x faster                                  |
| meteor_contest          | 110 ms                                                 | 107 ms: 1.03x faster                                  |
| fannkuch                | 410 ms                                                 | 401 ms: 1.02x faster                                  |
| pickle_list             | 4.67 us                                                | 4.57 us: 1.02x faster                                 |
| pathlib                 | 18.9 ms                                                | 18.5 ms: 1.02x faster                                 |
| django_template         | 35.0 ms                                                | 34.3 ms: 1.02x faster                                 |
| xml_etree_iterparse     | 106 ms                                                 | 104 ms: 1.02x faster                                  |
| xml_etree_parse         | 159 ms                                                 | 157 ms: 1.02x faster                                  |
| unpickle_list           | 5.04 us                                                | 4.97 us: 1.02x faster                                 |
| nqueens                 | 86.2 ms                                                | 85.2 ms: 1.01x faster                                 |
| crypto_pyaes            | 83.6 ms                                                | 82.7 ms: 1.01x faster                                 |
| json_loads              | 28.4 us                                                | 28.1 us: 1.01x faster                                 |
| raytrace                | 308 ms                                                 | 306 ms: 1.01x faster                                  |
| unpickle_pure_python    | 230 us                                                 | 231 us: 1.00x slower                                  |
| go                      | 140 ms                                                 | 143 ms: 1.02x slower                                  |
| richards                | 46.0 ms                                                | 47.5 ms: 1.03x slower                                 |
| nbody                   | 92.2 ms                                                | 95.2 ms: 1.03x slower                                 |
| chaos                   | 67.5 ms                                                | 70.2 ms: 1.04x slower                                 |
| hexiom                  | 6.54 ms                                                | 6.84 ms: 1.05x slower                                 |
| pidigits                | 187 ms                                                 | 197 ms: 1.05x slower                                  |
| pycparser               | 1.17 sec                                               | 1.24 sec: 1.06x slower                                |
| regex_dna               | 209 ms                                                 | 231 ms: 1.11x slower                                  |
| regex_v8                | 22.7 ms                                                | 25.9 ms: 1.14x slower                                 |
| json_dumps              | 10.6 ms                                                | 12.5 ms: 1.18x slower                                 |
| Geometric mean          | (ref)                                                  | 1.05x faster                                          |

Benchmark hidden because not significant (2): deltablue, sympy_expand
Ignored benchmarks (40) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, docutils, gc_traversal, generators, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols
Ignored benchmarks (2) of results/bm-20220405-3.11.0a7-2e49bd0/bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0.json: html5lib, thrift


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.01x
