
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 9471106
- commit date: 2022-01-13
- overall geometric mean: 1.00x faster \*
- HPT reliability: 83.26%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 266 ms                                                 | 264 ms: 1.01x faster                                  |
| chameleon      | 6.86 ms                                                | 7.55 ms: 1.10x slower                                 |
| html5lib       | 65.0 ms                                                | 68.1 ms: 1.05x slower                                 |
| tornado_http   | 97.7 ms                                                | 107 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.06x slower                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 78.9 ms                                                | 78.0 ms: 1.01x faster                                 |
| pidigits       | 190 ms                                                 | 194 ms: 1.02x slower                                  |
| nbody          | 91.6 ms                                                | 95.1 ms: 1.04x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.25 ms: 1.06x faster                                 |
| regex_compile  | 141 ms                                                 | 138 ms: 1.02x faster                                  |
| regex_dna      | 204 ms                                                 | 212 ms: 1.04x slower                                  |
| regex_v8       | 22.9 ms                                                | 24.8 ms: 1.08x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 26.8 us: 1.30x faster                                 |
| json_loads           | 29.4 us                                                | 25.1 us: 1.17x faster                                 |
| pickle               | 11.1 us                                                | 9.95 us: 1.11x faster                                 |
| json_dumps           | 13.5 ms                                                | 12.4 ms: 1.09x faster                                 |
| pickle_list          | 4.65 us                                                | 4.37 us: 1.06x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 155 ms: 1.05x faster                                  |
| xml_etree_iterparse  | 109 ms                                                 | 107 ms: 1.01x faster                                  |
| xml_etree_generate   | 80.4 ms                                                | 80.2 ms: 1.00x faster                                 |
| xml_etree_process    | 56.5 ms                                                | 56.9 ms: 1.01x slower                                 |
| unpickle             | 13.9 us                                                | 14.3 us: 1.03x slower                                 |
| pickle_pure_python   | 319 us                                                 | 329 us: 1.03x slower                                  |
| unpickle_pure_python | 241 us                                                 | 254 us: 1.05x slower                                  |
| Geometric mean       | (ref)                                                  | 1.05x faster                                          |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.07 ms: 1.08x faster                                 |
| python_startup_no_site | 6.09 ms                                                | 5.85 ms: 1.04x faster                                 |
| Geometric mean         | (ref)                                                  | 1.06x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| django_template | 33.8 ms                                                | 35.2 ms: 1.04x slower                                 |
| mako            | 10.8 ms                                                | 11.5 ms: 1.06x slower                                 |
| Geometric mean  | (ref)                                                  | 1.05x slower                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 34.8 us                                                | 26.8 us: 1.30x faster                                 |
| json_loads              | 29.4 us                                                | 25.1 us: 1.17x faster                                 |
| pickle                  | 11.1 us                                                | 9.95 us: 1.11x faster                                 |
| json                    | 5.24 ms                                                | 4.74 ms: 1.10x faster                                 |
| json_dumps              | 13.5 ms                                                | 12.4 ms: 1.09x faster                                 |
| python_startup          | 8.69 ms                                                | 8.07 ms: 1.08x faster                                 |
| pickle_list             | 4.65 us                                                | 4.37 us: 1.06x faster                                 |
| regex_effbot            | 3.45 ms                                                | 3.25 ms: 1.06x faster                                 |
| spectral_norm           | 105 ms                                                 | 99.0 ms: 1.06x faster                                 |
| meteor_contest          | 109 ms                                                 | 103 ms: 1.06x faster                                  |
| xml_etree_parse         | 163 ms                                                 | 155 ms: 1.05x faster                                  |
| logging_simple          | 6.24 us                                                | 5.95 us: 1.05x faster                                 |
| logging_format          | 6.83 us                                                | 6.51 us: 1.05x faster                                 |
| fannkuch                | 410 ms                                                 | 392 ms: 1.05x faster                                  |
| python_startup_no_site  | 6.09 ms                                                | 5.85 ms: 1.04x faster                                 |
| scimark_fft             | 342 ms                                                 | 330 ms: 1.04x faster                                  |
| nqueens                 | 86.8 ms                                                | 84.0 ms: 1.03x faster                                 |
| pycparser               | 1.20 sec                                               | 1.17 sec: 1.03x faster                                |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.69 ms: 1.02x faster                                 |
| regex_compile           | 141 ms                                                 | 138 ms: 1.02x faster                                  |
| hexiom                  | 6.74 ms                                                | 6.63 ms: 1.02x faster                                 |
| xml_etree_iterparse     | 109 ms                                                 | 107 ms: 1.01x faster                                  |
| float                   | 78.9 ms                                                | 78.0 ms: 1.01x faster                                 |
| 2to3                    | 266 ms                                                 | 264 ms: 1.01x faster                                  |
| sympy_sum               | 170 ms                                                 | 170 ms: 1.00x faster                                  |
| xml_etree_generate      | 80.4 ms                                                | 80.2 ms: 1.00x faster                                 |
| xml_etree_process       | 56.5 ms                                                | 56.9 ms: 1.01x slower                                 |
| sympy_str               | 299 ms                                                 | 302 ms: 1.01x slower                                  |
| dulwich_log             | 64.9 ms                                                | 65.8 ms: 1.01x slower                                 |
| scimark_lu              | 112 ms                                                 | 114 ms: 1.01x slower                                  |
| scimark_monte_carlo     | 71.8 ms                                                | 72.7 ms: 1.01x slower                                 |
| chaos                   | 71.4 ms                                                | 72.7 ms: 1.02x slower                                 |
| pidigits                | 190 ms                                                 | 194 ms: 1.02x slower                                  |
| scimark_sor             | 121 ms                                                 | 124 ms: 1.02x slower                                  |
| unpickle                | 13.9 us                                                | 14.3 us: 1.03x slower                                 |
| sympy_expand            | 490 ms                                                 | 506 ms: 1.03x slower                                  |
| pickle_pure_python      | 319 us                                                 | 329 us: 1.03x slower                                  |
| pathlib                 | 18.5 ms                                                | 19.1 ms: 1.03x slower                                 |
| unpack_sequence         | 43.3 ns                                                | 44.8 ns: 1.03x slower                                 |
| go                      | 143 ms                                                 | 148 ms: 1.04x slower                                  |
| regex_dna               | 204 ms                                                 | 212 ms: 1.04x slower                                  |
| nbody                   | 91.6 ms                                                | 95.1 ms: 1.04x slower                                 |
| pyflate                 | 426 ms                                                 | 444 ms: 1.04x slower                                  |
| django_template         | 33.8 ms                                                | 35.2 ms: 1.04x slower                                 |
| raytrace                | 306 ms                                                 | 320 ms: 1.05x slower                                  |
| logging_silent          | 108 ns                                                 | 113 ns: 1.05x slower                                  |
| html5lib                | 65.0 ms                                                | 68.1 ms: 1.05x slower                                 |
| thrift                  | 772 us                                                 | 812 us: 1.05x slower                                  |
| unpickle_pure_python    | 241 us                                                 | 254 us: 1.05x slower                                  |
| richards                | 48.9 ms                                                | 51.5 ms: 1.05x slower                                 |
| sqlite_synth            | 2.58 us                                                | 2.73 us: 1.06x slower                                 |
| mako                    | 10.8 ms                                                | 11.5 ms: 1.06x slower                                 |
| crypto_pyaes            | 77.5 ms                                                | 83.8 ms: 1.08x slower                                 |
| regex_v8                | 22.9 ms                                                | 24.8 ms: 1.08x slower                                 |
| tornado_http            | 97.7 ms                                                | 107 ms: 1.09x slower                                  |
| deltablue               | 3.80 ms                                                | 4.16 ms: 1.09x slower                                 |
| chameleon               | 6.86 ms                                                | 7.55 ms: 1.10x slower                                 |
| Geometric mean          | (ref)                                                  | 1.00x faster                                          |

Benchmark hidden because not significant (3): unpickle_list, telco, sympy_integrate
Ignored benchmarks (45) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 83.26% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
