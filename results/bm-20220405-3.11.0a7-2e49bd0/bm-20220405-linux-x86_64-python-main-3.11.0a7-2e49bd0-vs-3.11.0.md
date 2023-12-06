
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.87%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 266 ms                                                 | 264 ms: 1.01x faster                                  |
| tornado_http   | 97.7 ms                                                | 95.4 ms: 1.02x faster                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (2): chameleon, html5lib

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 78.9 ms                                                | 74.4 ms: 1.06x faster                                 |
| pidigits       | 190 ms                                                 | 197 ms: 1.04x slower                                  |
| nbody          | 91.6 ms                                                | 95.2 ms: 1.04x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.34 ms: 1.03x faster                                 |
| regex_compile  | 141 ms                                                 | 137 ms: 1.03x faster                                  |
| regex_v8       | 22.9 ms                                                | 25.9 ms: 1.13x slower                                 |
| regex_dna      | 204 ms                                                 | 231 ms: 1.13x slower                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 27.6 us: 1.26x faster                                 |
| pickle               | 11.1 us                                                | 9.55 us: 1.16x faster                                 |
| json_dumps           | 13.5 ms                                                | 12.5 ms: 1.08x faster                                 |
| unpickle_list        | 5.22 us                                                | 4.97 us: 1.05x faster                                 |
| xml_etree_iterparse  | 109 ms                                                 | 104 ms: 1.05x faster                                  |
| json_loads           | 29.4 us                                                | 28.1 us: 1.05x faster                                 |
| unpickle_pure_python | 241 us                                                 | 231 us: 1.04x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 157 ms: 1.04x faster                                  |
| xml_etree_generate   | 80.4 ms                                                | 78.5 ms: 1.03x faster                                 |
| pickle_pure_python   | 319 us                                                 | 311 us: 1.02x faster                                  |
| xml_etree_process    | 56.5 ms                                                | 55.2 ms: 1.02x faster                                 |
| pickle_list          | 4.65 us                                                | 4.57 us: 1.02x faster                                 |
| Geometric mean       | (ref)                                                  | 1.06x faster                                          |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.07 ms: 1.08x faster                                 |
| python_startup_no_site | 6.09 ms                                                | 5.98 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.05x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 10.8 ms                                                | 10.2 ms: 1.07x faster                                 |
| django_template | 33.8 ms                                                | 34.3 ms: 1.01x slower                                 |
| Geometric mean  | (ref)                                                  | 1.02x faster                                          |

All benchmarks:
===============

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict            | 34.8 us                                                | 27.6 us: 1.26x faster                                 |
| pickle                 | 11.1 us                                                | 9.55 us: 1.16x faster                                 |
| json_dumps             | 13.5 ms                                                | 12.5 ms: 1.08x faster                                 |
| python_startup         | 8.69 ms                                                | 8.07 ms: 1.08x faster                                 |
| logging_simple         | 6.24 us                                                | 5.80 us: 1.08x faster                                 |
| logging_format         | 6.83 us                                                | 6.35 us: 1.07x faster                                 |
| mako                   | 10.8 ms                                                | 10.2 ms: 1.07x faster                                 |
| sympy_sum              | 170 ms                                                 | 160 ms: 1.06x faster                                  |
| float                  | 78.9 ms                                                | 74.4 ms: 1.06x faster                                 |
| unpickle_list          | 5.22 us                                                | 4.97 us: 1.05x faster                                 |
| xml_etree_iterparse    | 109 ms                                                 | 104 ms: 1.05x faster                                  |
| json_loads             | 29.4 us                                                | 28.1 us: 1.05x faster                                 |
| logging_silent         | 108 ns                                                 | 104 ns: 1.05x faster                                  |
| unpickle_pure_python   | 241 us                                                 | 231 us: 1.04x faster                                  |
| sympy_integrate        | 21.4 ms                                                | 20.5 ms: 1.04x faster                                 |
| sympy_str              | 299 ms                                                 | 287 ms: 1.04x faster                                  |
| xml_etree_parse        | 163 ms                                                 | 157 ms: 1.04x faster                                  |
| scimark_lu             | 112 ms                                                 | 108 ms: 1.04x faster                                  |
| regex_effbot           | 3.45 ms                                                | 3.34 ms: 1.03x faster                                 |
| json                   | 5.24 ms                                                | 5.07 ms: 1.03x faster                                 |
| sympy_expand           | 490 ms                                                 | 476 ms: 1.03x faster                                  |
| regex_compile          | 141 ms                                                 | 137 ms: 1.03x faster                                  |
| sqlite_synth           | 2.58 us                                                | 2.51 us: 1.03x faster                                 |
| richards               | 48.9 ms                                                | 47.5 ms: 1.03x faster                                 |
| deltablue              | 3.80 ms                                                | 3.70 ms: 1.03x faster                                 |
| xml_etree_generate     | 80.4 ms                                                | 78.5 ms: 1.03x faster                                 |
| tornado_http           | 97.7 ms                                                | 95.4 ms: 1.02x faster                                 |
| pickle_pure_python     | 319 us                                                 | 311 us: 1.02x faster                                  |
| xml_etree_process      | 56.5 ms                                                | 55.2 ms: 1.02x faster                                 |
| fannkuch               | 410 ms                                                 | 401 ms: 1.02x faster                                  |
| meteor_contest         | 109 ms                                                 | 107 ms: 1.02x faster                                  |
| scimark_fft            | 342 ms                                                 | 335 ms: 1.02x faster                                  |
| telco                  | 6.72 ms                                                | 6.59 ms: 1.02x faster                                 |
| nqueens                | 86.8 ms                                                | 85.2 ms: 1.02x faster                                 |
| pickle_list            | 4.65 us                                                | 4.57 us: 1.02x faster                                 |
| python_startup_no_site | 6.09 ms                                                | 5.98 ms: 1.02x faster                                 |
| dulwich_log            | 64.9 ms                                                | 63.8 ms: 1.02x faster                                 |
| chaos                  | 71.4 ms                                                | 70.2 ms: 1.02x faster                                 |
| scimark_monte_carlo    | 71.8 ms                                                | 70.8 ms: 1.01x faster                                 |
| thrift                 | 772 us                                                 | 762 us: 1.01x faster                                  |
| 2to3                   | 266 ms                                                 | 264 ms: 1.01x faster                                  |
| go                     | 143 ms                                                 | 143 ms: 1.00x faster                                  |
| raytrace               | 306 ms                                                 | 306 ms: 1.00x faster                                  |
| scimark_sor            | 121 ms                                                 | 123 ms: 1.01x slower                                  |
| django_template        | 33.8 ms                                                | 34.3 ms: 1.01x slower                                 |
| hexiom                 | 6.74 ms                                                | 6.84 ms: 1.01x slower                                 |
| pyflate                | 426 ms                                                 | 438 ms: 1.03x slower                                  |
| pidigits               | 190 ms                                                 | 197 ms: 1.04x slower                                  |
| pycparser              | 1.20 sec                                               | 1.24 sec: 1.04x slower                                |
| unpack_sequence        | 43.3 ns                                                | 44.9 ns: 1.04x slower                                 |
| nbody                  | 91.6 ms                                                | 95.2 ms: 1.04x slower                                 |
| crypto_pyaes           | 77.5 ms                                                | 82.7 ms: 1.07x slower                                 |
| regex_v8               | 22.9 ms                                                | 25.9 ms: 1.13x slower                                 |
| regex_dna              | 204 ms                                                 | 231 ms: 1.13x slower                                  |
| Geometric mean         | (ref)                                                  | 1.02x faster                                          |

Benchmark hidden because not significant (6): spectral_norm, pathlib, chameleon, html5lib, scimark_sparse_mat_mult, unpickle
Ignored benchmarks (45) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 99.87% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
