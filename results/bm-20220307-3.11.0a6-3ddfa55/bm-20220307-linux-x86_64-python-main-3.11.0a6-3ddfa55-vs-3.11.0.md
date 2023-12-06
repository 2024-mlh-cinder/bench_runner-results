
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.02x slower \*
- HPT reliability: 83.07%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 266 ms                                                 | 268 ms: 1.01x slower                                  |
| chameleon      | 6.86 ms                                                | 6.93 ms: 1.01x slower                                 |
| html5lib       | 65.0 ms                                                | 68.6 ms: 1.05x slower                                 |
| tornado_http   | 97.7 ms                                                | 99.2 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 91.6 ms                                                | 97.7 ms: 1.07x slower                                 |
| pidigits       | 190 ms                                                 | 208 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                          |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 140 ms: 1.01x faster                                  |
| regex_v8       | 22.9 ms                                                | 23.0 ms: 1.00x slower                                 |
| regex_effbot   | 3.45 ms                                                | 3.49 ms: 1.01x slower                                 |
| regex_dna      | 204 ms                                                 | 221 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 28.1 us: 1.24x faster                                 |
| pickle               | 11.1 us                                                | 9.69 us: 1.14x faster                                 |
| json_dumps           | 13.5 ms                                                | 12.6 ms: 1.07x faster                                 |
| unpickle_list        | 5.22 us                                                | 4.92 us: 1.06x faster                                 |
| json_loads           | 29.4 us                                                | 28.1 us: 1.05x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 156 ms: 1.04x faster                                  |
| xml_etree_iterparse  | 109 ms                                                 | 105 ms: 1.04x faster                                  |
| pickle_list          | 4.65 us                                                | 4.51 us: 1.03x faster                                 |
| xml_etree_generate   | 80.4 ms                                                | 79.6 ms: 1.01x faster                                 |
| xml_etree_process    | 56.5 ms                                                | 56.0 ms: 1.01x faster                                 |
| unpickle_pure_python | 241 us                                                 | 246 us: 1.02x slower                                  |
| pickle_pure_python   | 319 us                                                 | 335 us: 1.05x slower                                  |
| Geometric mean       | (ref)                                                  | 1.04x faster                                          |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.20 ms: 1.06x faster                                 |
| python_startup_no_site | 6.09 ms                                                | 6.07 ms: 1.00x faster                                 |
| Geometric mean         | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 10.8 ms                                                | 10.6 ms: 1.02x faster                                 |
| django_template | 33.8 ms                                                | 36.0 ms: 1.07x slower                                 |
| Geometric mean  | (ref)                                                  | 1.02x slower                                          |

All benchmarks:
===============

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict            | 34.8 us                                                | 28.1 us: 1.24x faster                                 |
| pickle                 | 11.1 us                                                | 9.69 us: 1.14x faster                                 |
| logging_simple         | 6.24 us                                                | 5.52 us: 1.13x faster                                 |
| logging_format         | 6.83 us                                                | 6.08 us: 1.12x faster                                 |
| json_dumps             | 13.5 ms                                                | 12.6 ms: 1.07x faster                                 |
| unpickle_list          | 5.22 us                                                | 4.92 us: 1.06x faster                                 |
| python_startup         | 8.69 ms                                                | 8.20 ms: 1.06x faster                                 |
| json                   | 5.24 ms                                                | 5.00 ms: 1.05x faster                                 |
| json_loads             | 29.4 us                                                | 28.1 us: 1.05x faster                                 |
| sympy_sum              | 170 ms                                                 | 163 ms: 1.04x faster                                  |
| xml_etree_parse        | 163 ms                                                 | 156 ms: 1.04x faster                                  |
| xml_etree_iterparse    | 109 ms                                                 | 105 ms: 1.04x faster                                  |
| sympy_str              | 299 ms                                                 | 289 ms: 1.03x faster                                  |
| pickle_list            | 4.65 us                                                | 4.51 us: 1.03x faster                                 |
| meteor_contest         | 109 ms                                                 | 106 ms: 1.03x faster                                  |
| fannkuch               | 410 ms                                                 | 398 ms: 1.03x faster                                  |
| sqlite_synth           | 2.58 us                                                | 2.51 us: 1.03x faster                                 |
| sympy_integrate        | 21.4 ms                                                | 20.9 ms: 1.02x faster                                 |
| mako                   | 10.8 ms                                                | 10.6 ms: 1.02x faster                                 |
| sympy_expand           | 490 ms                                                 | 481 ms: 1.02x faster                                  |
| scimark_fft            | 342 ms                                                 | 336 ms: 1.02x faster                                  |
| pathlib                | 18.5 ms                                                | 18.2 ms: 1.02x faster                                 |
| regex_compile          | 141 ms                                                 | 140 ms: 1.01x faster                                  |
| xml_etree_generate     | 80.4 ms                                                | 79.6 ms: 1.01x faster                                 |
| xml_etree_process      | 56.5 ms                                                | 56.0 ms: 1.01x faster                                 |
| python_startup_no_site | 6.09 ms                                                | 6.07 ms: 1.00x faster                                 |
| regex_v8               | 22.9 ms                                                | 23.0 ms: 1.00x slower                                 |
| 2to3                   | 266 ms                                                 | 268 ms: 1.01x slower                                  |
| chameleon              | 6.86 ms                                                | 6.93 ms: 1.01x slower                                 |
| regex_effbot           | 3.45 ms                                                | 3.49 ms: 1.01x slower                                 |
| pycparser              | 1.20 sec                                               | 1.21 sec: 1.01x slower                                |
| tornado_http           | 97.7 ms                                                | 99.2 ms: 1.02x slower                                 |
| scimark_monte_carlo    | 71.8 ms                                                | 72.9 ms: 1.02x slower                                 |
| scimark_sor            | 121 ms                                                 | 123 ms: 1.02x slower                                  |
| unpickle_pure_python   | 241 us                                                 | 246 us: 1.02x slower                                  |
| spectral_norm          | 105 ms                                                 | 107 ms: 1.02x slower                                  |
| thrift                 | 772 us                                                 | 789 us: 1.02x slower                                  |
| dulwich_log            | 64.9 ms                                                | 66.5 ms: 1.02x slower                                 |
| scimark_lu             | 112 ms                                                 | 115 ms: 1.03x slower                                  |
| chaos                  | 71.4 ms                                                | 73.5 ms: 1.03x slower                                 |
| telco                  | 6.72 ms                                                | 6.92 ms: 1.03x slower                                 |
| go                     | 143 ms                                                 | 148 ms: 1.03x slower                                  |
| raytrace               | 306 ms                                                 | 318 ms: 1.04x slower                                  |
| logging_silent         | 108 ns                                                 | 113 ns: 1.04x slower                                  |
| hexiom                 | 6.74 ms                                                | 7.04 ms: 1.04x slower                                 |
| pickle_pure_python     | 319 us                                                 | 335 us: 1.05x slower                                  |
| html5lib               | 65.0 ms                                                | 68.6 ms: 1.05x slower                                 |
| pyflate                | 426 ms                                                 | 453 ms: 1.06x slower                                  |
| django_template        | 33.8 ms                                                | 36.0 ms: 1.07x slower                                 |
| nbody                  | 91.6 ms                                                | 97.7 ms: 1.07x slower                                 |
| regex_dna              | 204 ms                                                 | 221 ms: 1.08x slower                                  |
| crypto_pyaes           | 77.5 ms                                                | 84.6 ms: 1.09x slower                                 |
| pidigits               | 190 ms                                                 | 208 ms: 1.09x slower                                  |
| deltablue              | 3.80 ms                                                | 4.16 ms: 1.09x slower                                 |
| unpack_sequence        | 43.3 ns                                                | 131 ns: 3.02x slower                                  |
| Geometric mean         | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (5): richards, float, nqueens, scimark_sparse_mat_mult, unpickle
Ignored benchmarks (45) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 83.07% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
