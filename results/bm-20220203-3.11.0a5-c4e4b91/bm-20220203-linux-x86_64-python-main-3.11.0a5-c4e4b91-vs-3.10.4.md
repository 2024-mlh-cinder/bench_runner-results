
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: c4e4b91
- commit date: 2022-02-03
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 267 ms: 1.29x faster                                  |
| chameleon      | 9.84 ms                                                | 6.95 ms: 1.42x faster                                 |
| html5lib       | 88.1 ms                                                | 67.9 ms: 1.30x faster                                 |
| tornado_http   | 131 ms                                                 | 106 ms: 1.24x faster                                  |
| Geometric mean | (ref)                                                  | 1.31x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 148 ms                                                 | 94.7 ms: 1.56x faster                                 |
| float          | 116 ms                                                 | 77.5 ms: 1.50x faster                                 |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 140 ms: 1.32x faster                                  |
| regex_v8       | 26.2 ms                                                | 24.0 ms: 1.09x faster                                 |
| regex_effbot   | 3.41 ms                                                | 3.14 ms: 1.09x faster                                 |
| regex_dna      | 215 ms                                                 | 213 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.12x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 334 us: 1.44x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 57.0 ms: 1.40x faster                                 |
| unpickle_pure_python | 327 us                                                 | 249 us: 1.31x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 79.6 ms: 1.26x faster                                 |
| json_loads           | 31.4 us                                                | 26.7 us: 1.18x faster                                 |
| json_dumps           | 14.3 ms                                                | 12.2 ms: 1.17x faster                                 |
| pickle_list          | 5.05 us                                                | 4.47 us: 1.13x faster                                 |
| xml_etree_parse      | 171 ms                                                 | 153 ms: 1.12x faster                                  |
| unpickle             | 14.9 us                                                | 13.4 us: 1.10x faster                                 |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.09x faster                                  |
| pickle               | 10.7 us                                                | 9.93 us: 1.08x faster                                 |
| pickle_dict          | 30.0 us                                                | 28.1 us: 1.07x faster                                 |
| unpickle_list        | 5.10 us                                                | 5.26 us: 1.03x slower                                 |
| Geometric mean       | (ref)                                                  | 1.17x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.13 ms: 1.76x faster                                 |
| python_startup_no_site | 5.87 ms                                                | 5.92 ms: 1.01x slower                                 |
| Geometric mean         | (ref)                                                  | 1.32x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 16.3 ms                                                | 10.5 ms: 1.55x faster                                 |
| django_template | 47.6 ms                                                | 35.4 ms: 1.34x faster                                 |
| Geometric mean  | (ref)                                                  | 1.45x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220203-linux-x86_64-python-main-3.11.0a5-c4e4b91 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 4.13 ms: 1.89x faster                                 |
| python_startup          | 14.3 ms                                                | 8.13 ms: 1.76x faster                                 |
| logging_silent          | 189 ns                                                 | 113 ns: 1.67x faster                                  |
| scimark_sor             | 214 ms                                                 | 129 ms: 1.66x faster                                  |
| scimark_monte_carlo     | 118 ms                                                 | 72.6 ms: 1.63x faster                                 |
| go                      | 238 ms                                                 | 147 ms: 1.61x faster                                  |
| nbody                   | 148 ms                                                 | 94.7 ms: 1.56x faster                                 |
| richards                | 79.4 ms                                                | 50.8 ms: 1.56x faster                                 |
| spectral_norm           | 163 ms                                                 | 104 ms: 1.56x faster                                  |
| mako                    | 16.3 ms                                                | 10.5 ms: 1.55x faster                                 |
| raytrace                | 498 ms                                                 | 321 ms: 1.55x faster                                  |
| pyflate                 | 708 ms                                                 | 459 ms: 1.54x faster                                  |
| chaos                   | 114 ms                                                 | 74.9 ms: 1.53x faster                                 |
| hexiom                  | 10.3 ms                                                | 6.76 ms: 1.52x faster                                 |
| crypto_pyaes            | 127 ms                                                 | 83.8 ms: 1.51x faster                                 |
| float                   | 116 ms                                                 | 77.5 ms: 1.50x faster                                 |
| scimark_lu              | 175 ms                                                 | 120 ms: 1.46x faster                                  |
| pickle_pure_python      | 482 us                                                 | 334 us: 1.44x faster                                  |
| unpack_sequence         | 65.7 ns                                                | 46.0 ns: 1.43x faster                                 |
| logging_format          | 9.07 us                                                | 6.37 us: 1.42x faster                                 |
| logging_simple          | 8.27 us                                                | 5.84 us: 1.42x faster                                 |
| chameleon               | 9.84 ms                                                | 6.95 ms: 1.42x faster                                 |
| xml_etree_process       | 79.8 ms                                                | 57.0 ms: 1.40x faster                                 |
| django_template         | 47.6 ms                                                | 35.4 ms: 1.34x faster                                 |
| regex_compile           | 186 ms                                                 | 140 ms: 1.32x faster                                  |
| fannkuch                | 527 ms                                                 | 400 ms: 1.32x faster                                  |
| pycparser               | 1.57 sec                                               | 1.19 sec: 1.31x faster                                |
| unpickle_pure_python    | 327 us                                                 | 249 us: 1.31x faster                                  |
| scimark_fft             | 454 ms                                                 | 347 ms: 1.31x faster                                  |
| thrift                  | 1.06 ms                                                | 815 us: 1.31x faster                                  |
| html5lib                | 88.1 ms                                                | 67.9 ms: 1.30x faster                                 |
| 2to3                    | 346 ms                                                 | 267 ms: 1.29x faster                                  |
| xml_etree_generate      | 100.0 ms                                               | 79.6 ms: 1.26x faster                                 |
| tornado_http            | 131 ms                                                 | 106 ms: 1.24x faster                                  |
| nqueens                 | 107 ms                                                 | 87.2 ms: 1.22x faster                                 |
| sympy_integrate         | 25.4 ms                                                | 21.3 ms: 1.19x faster                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 5.14 ms: 1.19x faster                                 |
| json_loads              | 31.4 us                                                | 26.7 us: 1.18x faster                                 |
| dulwich_log             | 77.0 ms                                                | 65.7 ms: 1.17x faster                                 |
| json_dumps              | 14.3 ms                                                | 12.2 ms: 1.17x faster                                 |
| json                    | 5.67 ms                                                | 4.84 ms: 1.17x faster                                 |
| meteor_contest          | 119 ms                                                 | 105 ms: 1.14x faster                                  |
| pickle_list             | 5.05 us                                                | 4.47 us: 1.13x faster                                 |
| xml_etree_parse         | 171 ms                                                 | 153 ms: 1.12x faster                                  |
| sympy_sum               | 190 ms                                                 | 170 ms: 1.12x faster                                  |
| sqlite_synth            | 3.02 us                                                | 2.71 us: 1.12x faster                                 |
| sympy_expand            | 558 ms                                                 | 503 ms: 1.11x faster                                  |
| sympy_str               | 337 ms                                                 | 304 ms: 1.11x faster                                  |
| unpickle                | 14.9 us                                                | 13.4 us: 1.10x faster                                 |
| pathlib                 | 20.3 ms                                                | 18.5 ms: 1.10x faster                                 |
| regex_v8                | 26.2 ms                                                | 24.0 ms: 1.09x faster                                 |
| xml_etree_iterparse     | 116 ms                                                 | 106 ms: 1.09x faster                                  |
| regex_effbot            | 3.41 ms                                                | 3.14 ms: 1.09x faster                                 |
| pickle                  | 10.7 us                                                | 9.93 us: 1.08x faster                                 |
| pickle_dict             | 30.0 us                                                | 28.1 us: 1.07x faster                                 |
| telco                   | 7.01 ms                                                | 6.70 ms: 1.05x faster                                 |
| regex_dna               | 215 ms                                                 | 213 ms: 1.01x faster                                  |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                  |
| python_startup_no_site  | 5.87 ms                                                | 5.92 ms: 1.01x slower                                 |
| unpickle_list           | 5.10 us                                                | 5.26 us: 1.03x slower                                 |
| Geometric mean          | (ref)                                                  | 1.29x faster                                          |
Ignored benchmarks (41) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.21x
