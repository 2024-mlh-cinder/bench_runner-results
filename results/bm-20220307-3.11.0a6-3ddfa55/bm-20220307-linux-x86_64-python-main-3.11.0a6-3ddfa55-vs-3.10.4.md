
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.28x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 268 ms: 1.29x faster                                  |
| chameleon      | 9.84 ms                                                | 6.93 ms: 1.42x faster                                 |
| html5lib       | 88.1 ms                                                | 68.6 ms: 1.28x faster                                 |
| tornado_http   | 131 ms                                                 | 99.2 ms: 1.32x faster                                 |
| Geometric mean | (ref)                                                  | 1.33x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 148 ms                                                 | 97.7 ms: 1.52x faster                                 |
| float          | 116 ms                                                 | 78.7 ms: 1.48x faster                                 |
| pidigits       | 190 ms                                                 | 208 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.27x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 140 ms: 1.33x faster                                  |
| regex_v8       | 26.2 ms                                                | 23.0 ms: 1.14x faster                                 |
| regex_effbot   | 3.41 ms                                                | 3.49 ms: 1.02x slower                                 |
| regex_dna      | 215 ms                                                 | 221 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 335 us: 1.44x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 56.0 ms: 1.42x faster                                 |
| unpickle_pure_python | 327 us                                                 | 246 us: 1.33x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 79.6 ms: 1.26x faster                                 |
| json_dumps           | 14.3 ms                                                | 12.6 ms: 1.14x faster                                 |
| pickle_list          | 5.05 us                                                | 4.51 us: 1.12x faster                                 |
| json_loads           | 31.4 us                                                | 28.1 us: 1.12x faster                                 |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.11x faster                                  |
| pickle               | 10.7 us                                                | 9.69 us: 1.10x faster                                 |
| xml_etree_parse      | 171 ms                                                 | 156 ms: 1.09x faster                                  |
| pickle_dict          | 30.0 us                                                | 28.1 us: 1.07x faster                                 |
| unpickle             | 14.9 us                                                | 14.2 us: 1.05x faster                                 |
| unpickle_list        | 5.10 us                                                | 4.92 us: 1.04x faster                                 |
| Geometric mean       | (ref)                                                  | 1.17x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.20 ms: 1.75x faster                                 |
| python_startup_no_site | 5.87 ms                                                | 6.07 ms: 1.03x slower                                 |
| Geometric mean         | (ref)                                                  | 1.30x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 16.3 ms                                                | 10.6 ms: 1.54x faster                                 |
| django_template | 47.6 ms                                                | 36.0 ms: 1.32x faster                                 |
| Geometric mean  | (ref)                                                  | 1.42x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-linux-x86_64-python-main-3.11.0a6-3ddfa55 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 4.16 ms: 1.88x faster                                 |
| python_startup          | 14.3 ms                                                | 8.20 ms: 1.75x faster                                 |
| scimark_sor             | 214 ms                                                 | 123 ms: 1.74x faster                                  |
| logging_silent          | 189 ns                                                 | 113 ns: 1.68x faster                                  |
| richards                | 79.4 ms                                                | 48.5 ms: 1.64x faster                                 |
| scimark_monte_carlo     | 118 ms                                                 | 72.9 ms: 1.62x faster                                 |
| go                      | 238 ms                                                 | 148 ms: 1.61x faster                                  |
| raytrace                | 498 ms                                                 | 318 ms: 1.56x faster                                  |
| pyflate                 | 708 ms                                                 | 453 ms: 1.56x faster                                  |
| chaos                   | 114 ms                                                 | 73.5 ms: 1.55x faster                                 |
| mako                    | 16.3 ms                                                | 10.6 ms: 1.54x faster                                 |
| scimark_lu              | 175 ms                                                 | 115 ms: 1.52x faster                                  |
| spectral_norm           | 163 ms                                                 | 107 ms: 1.52x faster                                  |
| nbody                   | 148 ms                                                 | 97.7 ms: 1.52x faster                                 |
| logging_simple          | 8.27 us                                                | 5.52 us: 1.50x faster                                 |
| crypto_pyaes            | 127 ms                                                 | 84.6 ms: 1.50x faster                                 |
| logging_format          | 9.07 us                                                | 6.08 us: 1.49x faster                                 |
| float                   | 116 ms                                                 | 78.7 ms: 1.48x faster                                 |
| hexiom                  | 10.3 ms                                                | 7.04 ms: 1.46x faster                                 |
| pickle_pure_python      | 482 us                                                 | 335 us: 1.44x faster                                  |
| xml_etree_process       | 79.8 ms                                                | 56.0 ms: 1.42x faster                                 |
| chameleon               | 9.84 ms                                                | 6.93 ms: 1.42x faster                                 |
| scimark_fft             | 454 ms                                                 | 336 ms: 1.35x faster                                  |
| thrift                  | 1.06 ms                                                | 789 us: 1.35x faster                                  |
| unpickle_pure_python    | 327 us                                                 | 246 us: 1.33x faster                                  |
| regex_compile           | 186 ms                                                 | 140 ms: 1.33x faster                                  |
| fannkuch                | 527 ms                                                 | 398 ms: 1.32x faster                                  |
| django_template         | 47.6 ms                                                | 36.0 ms: 1.32x faster                                 |
| tornado_http            | 131 ms                                                 | 99.2 ms: 1.32x faster                                 |
| pycparser               | 1.57 sec                                               | 1.21 sec: 1.29x faster                                |
| 2to3                    | 346 ms                                                 | 268 ms: 1.29x faster                                  |
| html5lib                | 88.1 ms                                                | 68.6 ms: 1.28x faster                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.82 ms: 1.26x faster                                 |
| xml_etree_generate      | 100.0 ms                                               | 79.6 ms: 1.26x faster                                 |
| nqueens                 | 107 ms                                                 | 87.0 ms: 1.22x faster                                 |
| sympy_integrate         | 25.4 ms                                                | 20.9 ms: 1.22x faster                                 |
| sqlite_synth            | 3.02 us                                                | 2.51 us: 1.20x faster                                 |
| sympy_sum               | 190 ms                                                 | 163 ms: 1.17x faster                                  |
| sympy_str               | 337 ms                                                 | 289 ms: 1.16x faster                                  |
| sympy_expand            | 558 ms                                                 | 481 ms: 1.16x faster                                  |
| dulwich_log             | 77.0 ms                                                | 66.5 ms: 1.16x faster                                 |
| regex_v8                | 26.2 ms                                                | 23.0 ms: 1.14x faster                                 |
| json_dumps              | 14.3 ms                                                | 12.6 ms: 1.14x faster                                 |
| json                    | 5.67 ms                                                | 5.00 ms: 1.13x faster                                 |
| meteor_contest          | 119 ms                                                 | 106 ms: 1.13x faster                                  |
| pickle_list             | 5.05 us                                                | 4.51 us: 1.12x faster                                 |
| json_loads              | 31.4 us                                                | 28.1 us: 1.12x faster                                 |
| pathlib                 | 20.3 ms                                                | 18.2 ms: 1.12x faster                                 |
| xml_etree_iterparse     | 116 ms                                                 | 105 ms: 1.11x faster                                  |
| pickle                  | 10.7 us                                                | 9.69 us: 1.10x faster                                 |
| xml_etree_parse         | 171 ms                                                 | 156 ms: 1.09x faster                                  |
| pickle_dict             | 30.0 us                                                | 28.1 us: 1.07x faster                                 |
| unpickle                | 14.9 us                                                | 14.2 us: 1.05x faster                                 |
| unpickle_list           | 5.10 us                                                | 4.92 us: 1.04x faster                                 |
| telco                   | 7.01 ms                                                | 6.92 ms: 1.01x faster                                 |
| regex_effbot            | 3.41 ms                                                | 3.49 ms: 1.02x slower                                 |
| regex_dna               | 215 ms                                                 | 221 ms: 1.03x slower                                  |
| python_startup_no_site  | 5.87 ms                                                | 6.07 ms: 1.03x slower                                 |
| pidigits                | 190 ms                                                 | 208 ms: 1.09x slower                                  |
| unpack_sequence         | 65.7 ns                                                | 131 ns: 1.99x slower                                  |
| Geometric mean          | (ref)                                                  | 1.28x faster                                          |
Ignored benchmarks (41) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.22x
