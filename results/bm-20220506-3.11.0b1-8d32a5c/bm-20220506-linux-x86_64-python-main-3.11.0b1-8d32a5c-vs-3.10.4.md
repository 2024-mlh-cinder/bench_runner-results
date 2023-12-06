
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.37x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 256 ms: 1.35x faster                                  |
| chameleon      | 9.84 ms                                                | 6.57 ms: 1.50x faster                                 |
| html5lib       | 88.1 ms                                                | 60.1 ms: 1.46x faster                                 |
| tornado_http   | 131 ms                                                 | 94.6 ms: 1.38x faster                                 |
| Geometric mean | (ref)                                                  | 1.42x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 116 ms                                                 | 72.5 ms: 1.60x faster                                 |
| nbody          | 148 ms                                                 | 93.1 ms: 1.59x faster                                 |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.37x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 135 ms: 1.38x faster                                  |
| regex_v8       | 26.2 ms                                                | 21.6 ms: 1.21x faster                                 |
| regex_effbot   | 3.41 ms                                                | 2.93 ms: 1.16x faster                                 |
| regex_dna      | 215 ms                                                 | 204 ms: 1.05x faster                                  |
| Geometric mean | (ref)                                                  | 1.20x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 53.6 ms: 1.49x faster                                 |
| unpickle_pure_python | 327 us                                                 | 229 us: 1.43x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 76.5 ms: 1.31x faster                                 |
| json_loads           | 31.4 us                                                | 25.4 us: 1.24x faster                                 |
| pickle_list          | 5.05 us                                                | 4.26 us: 1.19x faster                                 |
| pickle_dict          | 30.0 us                                                | 25.6 us: 1.17x faster                                 |
| json_dumps           | 14.3 ms                                                | 12.4 ms: 1.16x faster                                 |
| pickle               | 10.7 us                                                | 9.56 us: 1.12x faster                                 |
| unpickle             | 14.9 us                                                | 13.4 us: 1.11x faster                                 |
| xml_etree_iterparse  | 116 ms                                                 | 104 ms: 1.11x faster                                  |
| xml_etree_parse      | 171 ms                                                 | 157 ms: 1.09x faster                                  |
| unpickle_list        | 5.10 us                                                | 5.05 us: 1.01x faster                                 |
| Geometric mean       | (ref)                                                  | 1.22x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.25 ms: 1.74x faster                                 |
| python_startup_no_site | 5.87 ms                                                | 6.16 ms: 1.05x slower                                 |
| Geometric mean         | (ref)                                                  | 1.29x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.88 ms: 1.65x faster                                 |
| django_template | 47.6 ms                                                | 32.8 ms: 1.45x faster                                 |
| Geometric mean  | (ref)                                                  | 1.55x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-linux-x86_64-python-main-3.11.0b1-8d32a5c |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.61 ms: 2.17x faster                                 |
| logging_silent          | 189 ns                                                 | 98.2 ns: 1.92x faster                                 |
| scimark_sor             | 214 ms                                                 | 115 ms: 1.87x faster                                  |
| scimark_monte_carlo     | 118 ms                                                 | 66.5 ms: 1.77x faster                                 |
| go                      | 238 ms                                                 | 136 ms: 1.75x faster                                  |
| python_startup          | 14.3 ms                                                | 8.25 ms: 1.74x faster                                 |
| pyflate                 | 708 ms                                                 | 411 ms: 1.72x faster                                  |
| richards                | 79.4 ms                                                | 46.4 ms: 1.71x faster                                 |
| crypto_pyaes            | 127 ms                                                 | 74.3 ms: 1.71x faster                                 |
| raytrace                | 498 ms                                                 | 294 ms: 1.69x faster                                  |
| spectral_norm           | 163 ms                                                 | 97.6 ms: 1.67x faster                                 |
| chaos                   | 114 ms                                                 | 68.6 ms: 1.67x faster                                 |
| mako                    | 16.3 ms                                                | 9.88 ms: 1.65x faster                                 |
| hexiom                  | 10.3 ms                                                | 6.29 ms: 1.64x faster                                 |
| scimark_lu              | 175 ms                                                 | 109 ms: 1.61x faster                                  |
| float                   | 116 ms                                                 | 72.5 ms: 1.60x faster                                 |
| nbody                   | 148 ms                                                 | 93.1 ms: 1.59x faster                                 |
| pickle_pure_python      | 482 us                                                 | 305 us: 1.58x faster                                  |
| chameleon               | 9.84 ms                                                | 6.57 ms: 1.50x faster                                 |
| xml_etree_process       | 79.8 ms                                                | 53.6 ms: 1.49x faster                                 |
| unpack_sequence         | 65.7 ns                                                | 44.3 ns: 1.48x faster                                 |
| html5lib                | 88.1 ms                                                | 60.1 ms: 1.46x faster                                 |
| django_template         | 47.6 ms                                                | 32.8 ms: 1.45x faster                                 |
| thrift                  | 1.06 ms                                                | 741 us: 1.44x faster                                  |
| unpickle_pure_python    | 327 us                                                 | 229 us: 1.43x faster                                  |
| logging_format          | 9.07 us                                                | 6.44 us: 1.41x faster                                 |
| logging_simple          | 8.27 us                                                | 5.89 us: 1.41x faster                                 |
| scimark_fft             | 454 ms                                                 | 325 ms: 1.40x faster                                  |
| tornado_http            | 131 ms                                                 | 94.6 ms: 1.38x faster                                 |
| regex_compile           | 186 ms                                                 | 135 ms: 1.38x faster                                  |
| fannkuch                | 527 ms                                                 | 385 ms: 1.37x faster                                  |
| 2to3                    | 346 ms                                                 | 256 ms: 1.35x faster                                  |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.57 ms: 1.33x faster                                 |
| pycparser               | 1.57 sec                                               | 1.18 sec: 1.32x faster                                |
| xml_etree_generate      | 100.0 ms                                               | 76.5 ms: 1.31x faster                                 |
| nqueens                 | 107 ms                                                 | 84.7 ms: 1.26x faster                                 |
| sympy_integrate         | 25.4 ms                                                | 20.5 ms: 1.24x faster                                 |
| json_loads              | 31.4 us                                                | 25.4 us: 1.24x faster                                 |
| dulwich_log             | 77.0 ms                                                | 62.8 ms: 1.23x faster                                 |
| regex_v8                | 26.2 ms                                                | 21.6 ms: 1.21x faster                                 |
| sqlite_synth            | 3.02 us                                                | 2.53 us: 1.20x faster                                 |
| sympy_expand            | 558 ms                                                 | 468 ms: 1.19x faster                                  |
| sympy_str               | 337 ms                                                 | 284 ms: 1.19x faster                                  |
| pickle_list             | 5.05 us                                                | 4.26 us: 1.19x faster                                 |
| sympy_sum               | 190 ms                                                 | 161 ms: 1.18x faster                                  |
| pickle_dict             | 30.0 us                                                | 25.6 us: 1.17x faster                                 |
| regex_effbot            | 3.41 ms                                                | 2.93 ms: 1.16x faster                                 |
| json_dumps              | 14.3 ms                                                | 12.4 ms: 1.16x faster                                 |
| json                    | 5.67 ms                                                | 4.91 ms: 1.16x faster                                 |
| meteor_contest          | 119 ms                                                 | 105 ms: 1.14x faster                                  |
| pathlib                 | 20.3 ms                                                | 17.9 ms: 1.13x faster                                 |
| pickle                  | 10.7 us                                                | 9.56 us: 1.12x faster                                 |
| unpickle                | 14.9 us                                                | 13.4 us: 1.11x faster                                 |
| xml_etree_iterparse     | 116 ms                                                 | 104 ms: 1.11x faster                                  |
| xml_etree_parse         | 171 ms                                                 | 157 ms: 1.09x faster                                  |
| regex_dna               | 215 ms                                                 | 204 ms: 1.05x faster                                  |
| telco                   | 7.01 ms                                                | 6.84 ms: 1.03x faster                                 |
| unpickle_list           | 5.10 us                                                | 5.05 us: 1.01x faster                                 |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| python_startup_no_site  | 5.87 ms                                                | 6.16 ms: 1.05x slower                                 |
| Geometric mean          | (ref)                                                  | 1.37x faster                                          |
Ignored benchmarks (41) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.31x
- 95% likely to have a speedup of 1.30x
- 99% likely to have a speedup of 1.25x
