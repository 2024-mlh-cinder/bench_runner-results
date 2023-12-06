
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.06x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 266 ms                                                 | 256 ms: 1.04x faster                                  |
| chameleon      | 6.86 ms                                                | 6.57 ms: 1.04x faster                                 |
| html5lib       | 65.0 ms                                                | 60.1 ms: 1.08x faster                                 |
| tornado_http   | 97.7 ms                                                | 94.6 ms: 1.03x faster                                 |
| Geometric mean | (ref)                                                  | 1.05x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 78.9 ms                                                | 72.5 ms: 1.09x faster                                 |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| nbody          | 91.6 ms                                                | 93.1 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 2.93 ms: 1.18x faster                                 |
| regex_v8       | 22.9 ms                                                | 21.6 ms: 1.06x faster                                 |
| regex_compile  | 141 ms                                                 | 135 ms: 1.05x faster                                  |
| regex_dna      | 204 ms                                                 | 204 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 25.6 us: 1.36x faster                                 |
| json_loads           | 29.4 us                                                | 25.4 us: 1.16x faster                                 |
| pickle               | 11.1 us                                                | 9.56 us: 1.16x faster                                 |
| pickle_list          | 4.65 us                                                | 4.26 us: 1.09x faster                                 |
| json_dumps           | 13.5 ms                                                | 12.4 ms: 1.09x faster                                 |
| xml_etree_process    | 56.5 ms                                                | 53.6 ms: 1.05x faster                                 |
| unpickle_pure_python | 241 us                                                 | 229 us: 1.05x faster                                  |
| xml_etree_generate   | 80.4 ms                                                | 76.5 ms: 1.05x faster                                 |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.04x faster                                  |
| xml_etree_iterparse  | 109 ms                                                 | 104 ms: 1.04x faster                                  |
| unpickle             | 13.9 us                                                | 13.4 us: 1.04x faster                                 |
| xml_etree_parse      | 163 ms                                                 | 157 ms: 1.04x faster                                  |
| unpickle_list        | 5.22 us                                                | 5.05 us: 1.03x faster                                 |
| Geometric mean       | (ref)                                                  | 1.09x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.25 ms: 1.05x faster                                 |
| python_startup_no_site | 6.09 ms                                                | 6.16 ms: 1.01x slower                                 |
| Geometric mean         | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.88 ms: 1.10x faster                                 |
| django_template | 33.8 ms                                                | 32.8 ms: 1.03x faster                                 |
| Geometric mean  | (ref)                                                  | 1.06x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_dict             | 34.8 us                                                | 25.6 us: 1.36x faster                                 |
| regex_effbot            | 3.45 ms                                                | 2.93 ms: 1.18x faster                                 |
| json_loads              | 29.4 us                                                | 25.4 us: 1.16x faster                                 |
| pickle                  | 11.1 us                                                | 9.56 us: 1.16x faster                                 |
| logging_silent          | 108 ns                                                 | 98.2 ns: 1.10x faster                                 |
| mako                    | 10.8 ms                                                | 9.88 ms: 1.10x faster                                 |
| pickle_list             | 4.65 us                                                | 4.26 us: 1.09x faster                                 |
| json_dumps              | 13.5 ms                                                | 12.4 ms: 1.09x faster                                 |
| float                   | 78.9 ms                                                | 72.5 ms: 1.09x faster                                 |
| html5lib                | 65.0 ms                                                | 60.1 ms: 1.08x faster                                 |
| scimark_monte_carlo     | 71.8 ms                                                | 66.5 ms: 1.08x faster                                 |
| spectral_norm           | 105 ms                                                 | 97.6 ms: 1.08x faster                                 |
| hexiom                  | 6.74 ms                                                | 6.29 ms: 1.07x faster                                 |
| json                    | 5.24 ms                                                | 4.91 ms: 1.07x faster                                 |
| fannkuch                | 410 ms                                                 | 385 ms: 1.07x faster                                  |
| logging_simple          | 6.24 us                                                | 5.89 us: 1.06x faster                                 |
| scimark_sor             | 121 ms                                                 | 115 ms: 1.06x faster                                  |
| regex_v8                | 22.9 ms                                                | 21.6 ms: 1.06x faster                                 |
| logging_format          | 6.83 us                                                | 6.44 us: 1.06x faster                                 |
| sympy_sum               | 170 ms                                                 | 161 ms: 1.06x faster                                  |
| deltablue               | 3.80 ms                                                | 3.61 ms: 1.05x faster                                 |
| xml_etree_process       | 56.5 ms                                                | 53.6 ms: 1.05x faster                                 |
| sympy_str               | 299 ms                                                 | 284 ms: 1.05x faster                                  |
| unpickle_pure_python    | 241 us                                                 | 229 us: 1.05x faster                                  |
| richards                | 48.9 ms                                                | 46.4 ms: 1.05x faster                                 |
| python_startup          | 8.69 ms                                                | 8.25 ms: 1.05x faster                                 |
| scimark_fft             | 342 ms                                                 | 325 ms: 1.05x faster                                  |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.57 ms: 1.05x faster                                 |
| xml_etree_generate      | 80.4 ms                                                | 76.5 ms: 1.05x faster                                 |
| regex_compile           | 141 ms                                                 | 135 ms: 1.05x faster                                  |
| go                      | 143 ms                                                 | 136 ms: 1.05x faster                                  |
| sympy_expand            | 490 ms                                                 | 468 ms: 1.05x faster                                  |
| pickle_pure_python      | 319 us                                                 | 305 us: 1.04x faster                                  |
| chameleon               | 6.86 ms                                                | 6.57 ms: 1.04x faster                                 |
| sympy_integrate         | 21.4 ms                                                | 20.5 ms: 1.04x faster                                 |
| crypto_pyaes            | 77.5 ms                                                | 74.3 ms: 1.04x faster                                 |
| raytrace                | 306 ms                                                 | 294 ms: 1.04x faster                                  |
| meteor_contest          | 109 ms                                                 | 105 ms: 1.04x faster                                  |
| xml_etree_iterparse     | 109 ms                                                 | 104 ms: 1.04x faster                                  |
| thrift                  | 772 us                                                 | 741 us: 1.04x faster                                  |
| chaos                   | 71.4 ms                                                | 68.6 ms: 1.04x faster                                 |
| 2to3                    | 266 ms                                                 | 256 ms: 1.04x faster                                  |
| unpickle                | 13.9 us                                                | 13.4 us: 1.04x faster                                 |
| pyflate                 | 426 ms                                                 | 411 ms: 1.04x faster                                  |
| xml_etree_parse         | 163 ms                                                 | 157 ms: 1.04x faster                                  |
| dulwich_log             | 64.9 ms                                                | 62.8 ms: 1.03x faster                                 |
| pathlib                 | 18.5 ms                                                | 17.9 ms: 1.03x faster                                 |
| unpickle_list           | 5.22 us                                                | 5.05 us: 1.03x faster                                 |
| tornado_http            | 97.7 ms                                                | 94.6 ms: 1.03x faster                                 |
| django_template         | 33.8 ms                                                | 32.8 ms: 1.03x faster                                 |
| scimark_lu              | 112 ms                                                 | 109 ms: 1.03x faster                                  |
| nqueens                 | 86.8 ms                                                | 84.7 ms: 1.02x faster                                 |
| sqlite_synth            | 2.58 us                                                | 2.53 us: 1.02x faster                                 |
| pycparser               | 1.20 sec                                               | 1.18 sec: 1.01x faster                                |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| regex_dna               | 204 ms                                                 | 204 ms: 1.00x faster                                  |
| python_startup_no_site  | 6.09 ms                                                | 6.16 ms: 1.01x slower                                 |
| nbody                   | 91.6 ms                                                | 93.1 ms: 1.02x slower                                 |
| telco                   | 6.72 ms                                                | 6.84 ms: 1.02x slower                                 |
| unpack_sequence         | 43.3 ns                                                | 44.3 ns: 1.02x slower                                 |
| Geometric mean          | (ref)                                                  | 1.06x faster                                          |
Ignored benchmarks (45) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_io_tg, async_tree_memoization, async_tree_memoization_tg, async_tree_none, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
