
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: c4e4b91
- commit date: 2022-02-03
- overall geometric mean: 1.00x slower \*
- HPT reliability: 96.98%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 266 ms                                                 | 267 ms: 1.00x slower                                  |
| chameleon      | 6.86 ms                                                | 6.95 ms: 1.01x slower                                 |
| html5lib       | 65.0 ms                                                | 67.9 ms: 1.04x slower                                 |
| tornado_http   | 97.7 ms                                                | 106 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 78.9 ms                                                | 77.5 ms: 1.02x faster                                 |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| nbody          | 91.6 ms                                                | 94.7 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.14 ms: 1.10x faster                                 |
| regex_compile  | 141 ms                                                 | 140 ms: 1.01x faster                                  |
| regex_dna      | 204 ms                                                 | 213 ms: 1.04x slower                                  |
| regex_v8       | 22.9 ms                                                | 24.0 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 28.1 us: 1.24x faster                                 |
| pickle               | 11.1 us                                                | 9.93 us: 1.12x faster                                 |
| json_loads           | 29.4 us                                                | 26.7 us: 1.10x faster                                 |
| json_dumps           | 13.5 ms                                                | 12.2 ms: 1.10x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.07x faster                                  |
| pickle_list          | 4.65 us                                                | 4.47 us: 1.04x faster                                 |
| unpickle             | 13.9 us                                                | 13.4 us: 1.03x faster                                 |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.02x faster                                  |
| xml_etree_generate   | 80.4 ms                                                | 79.6 ms: 1.01x faster                                 |
| xml_etree_process    | 56.5 ms                                                | 57.0 ms: 1.01x slower                                 |
| unpickle_pure_python | 241 us                                                 | 249 us: 1.03x slower                                  |
| pickle_pure_python   | 319 us                                                 | 334 us: 1.05x slower                                  |
| Geometric mean       | (ref)                                                  | 1.05x faster                                          |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.13 ms: 1.07x faster                                 |
| python_startup_no_site | 6.09 ms                                                | 5.92 ms: 1.03x faster                                 |
| Geometric mean         | (ref)                                                  | 1.05x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 10.8 ms                                                | 10.5 ms: 1.03x faster                                 |
| django_template | 33.8 ms                                                | 35.4 ms: 1.05x slower                                 |
| Geometric mean  | (ref)                                                  | 1.01x slower                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 34.8 us                                                | 28.1 us: 1.24x faster                                 |
| pickle                  | 11.1 us                                                | 9.93 us: 1.12x faster                                 |
| json_loads              | 29.4 us                                                | 26.7 us: 1.10x faster                                 |
| json_dumps              | 13.5 ms                                                | 12.2 ms: 1.10x faster                                 |
| regex_effbot            | 3.45 ms                                                | 3.14 ms: 1.10x faster                                 |
| json                    | 5.24 ms                                                | 4.84 ms: 1.08x faster                                 |
| logging_format          | 6.83 us                                                | 6.37 us: 1.07x faster                                 |
| logging_simple          | 6.24 us                                                | 5.84 us: 1.07x faster                                 |
| python_startup          | 8.69 ms                                                | 8.13 ms: 1.07x faster                                 |
| xml_etree_parse         | 163 ms                                                 | 153 ms: 1.07x faster                                  |
| pickle_list             | 4.65 us                                                | 4.47 us: 1.04x faster                                 |
| meteor_contest          | 109 ms                                                 | 105 ms: 1.04x faster                                  |
| mako                    | 10.8 ms                                                | 10.5 ms: 1.03x faster                                 |
| unpickle                | 13.9 us                                                | 13.4 us: 1.03x faster                                 |
| python_startup_no_site  | 6.09 ms                                                | 5.92 ms: 1.03x faster                                 |
| fannkuch                | 410 ms                                                 | 400 ms: 1.02x faster                                  |
| xml_etree_iterparse     | 109 ms                                                 | 106 ms: 1.02x faster                                  |
| float                   | 78.9 ms                                                | 77.5 ms: 1.02x faster                                 |
| xml_etree_generate      | 80.4 ms                                                | 79.6 ms: 1.01x faster                                 |
| regex_compile           | 141 ms                                                 | 140 ms: 1.01x faster                                  |
| spectral_norm           | 105 ms                                                 | 104 ms: 1.01x faster                                  |
| sympy_integrate         | 21.4 ms                                                | 21.3 ms: 1.00x faster                                 |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| hexiom                  | 6.74 ms                                                | 6.76 ms: 1.00x slower                                 |
| 2to3                    | 266 ms                                                 | 267 ms: 1.00x slower                                  |
| xml_etree_process       | 56.5 ms                                                | 57.0 ms: 1.01x slower                                 |
| dulwich_log             | 64.9 ms                                                | 65.7 ms: 1.01x slower                                 |
| scimark_monte_carlo     | 71.8 ms                                                | 72.6 ms: 1.01x slower                                 |
| chameleon               | 6.86 ms                                                | 6.95 ms: 1.01x slower                                 |
| scimark_fft             | 342 ms                                                 | 347 ms: 1.01x slower                                  |
| sympy_str               | 299 ms                                                 | 304 ms: 1.02x slower                                  |
| sympy_expand            | 490 ms                                                 | 503 ms: 1.03x slower                                  |
| go                      | 143 ms                                                 | 147 ms: 1.03x slower                                  |
| unpickle_pure_python    | 241 us                                                 | 249 us: 1.03x slower                                  |
| nbody                   | 91.6 ms                                                | 94.7 ms: 1.03x slower                                 |
| richards                | 48.9 ms                                                | 50.8 ms: 1.04x slower                                 |
| logging_silent          | 108 ns                                                 | 113 ns: 1.04x slower                                  |
| regex_dna               | 204 ms                                                 | 213 ms: 1.04x slower                                  |
| html5lib                | 65.0 ms                                                | 67.9 ms: 1.04x slower                                 |
| raytrace                | 306 ms                                                 | 321 ms: 1.05x slower                                  |
| pickle_pure_python      | 319 us                                                 | 334 us: 1.05x slower                                  |
| django_template         | 33.8 ms                                                | 35.4 ms: 1.05x slower                                 |
| regex_v8                | 22.9 ms                                                | 24.0 ms: 1.05x slower                                 |
| sqlite_synth            | 2.58 us                                                | 2.71 us: 1.05x slower                                 |
| chaos                   | 71.4 ms                                                | 74.9 ms: 1.05x slower                                 |
| thrift                  | 772 us                                                 | 815 us: 1.06x slower                                  |
| scimark_sor             | 121 ms                                                 | 129 ms: 1.06x slower                                  |
| unpack_sequence         | 43.3 ns                                                | 46.0 ns: 1.06x slower                                 |
| scimark_lu              | 112 ms                                                 | 120 ms: 1.07x slower                                  |
| scimark_sparse_mat_mult | 4.80 ms                                                | 5.14 ms: 1.07x slower                                 |
| pyflate                 | 426 ms                                                 | 459 ms: 1.08x slower                                  |
| tornado_http            | 97.7 ms                                                | 106 ms: 1.08x slower                                  |
| crypto_pyaes            | 77.5 ms                                                | 83.8 ms: 1.08x slower                                 |
| deltablue               | 3.80 ms                                                | 4.13 ms: 1.09x slower                                 |
| Geometric mean          | (ref)                                                  | 1.00x slower                                          |

Benchmark hidden because not significant (6): sympy_sum, telco, pycparser, pathlib, nqueens, unpickle_list
Ignored benchmarks (45) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 96.98% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
