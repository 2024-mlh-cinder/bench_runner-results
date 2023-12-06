
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 9471106
- commit date: 2022-01-13
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                  |
| chameleon      | 9.84 ms                                                | 7.55 ms: 1.30x faster                                 |
| html5lib       | 88.1 ms                                                | 68.1 ms: 1.29x faster                                 |
| tornado_http   | 131 ms                                                 | 107 ms: 1.22x faster                                  |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 148 ms                                                 | 95.1 ms: 1.56x faster                                 |
| float          | 116 ms                                                 | 78.0 ms: 1.49x faster                                 |
| pidigits       | 190 ms                                                 | 194 ms: 1.02x slower                                  |
| Geometric mean | (ref)                                                  | 1.32x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 138 ms: 1.34x faster                                  |
| regex_v8       | 26.2 ms                                                | 24.8 ms: 1.06x faster                                 |
| regex_effbot   | 3.41 ms                                                | 3.25 ms: 1.05x faster                                 |
| regex_dna      | 215 ms                                                 | 212 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.11x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 329 us: 1.46x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 56.9 ms: 1.40x faster                                 |
| unpickle_pure_python | 327 us                                                 | 254 us: 1.29x faster                                  |
| json_loads           | 31.4 us                                                | 25.1 us: 1.25x faster                                 |
| xml_etree_generate   | 100.0 ms                                               | 80.2 ms: 1.25x faster                                 |
| json_dumps           | 14.3 ms                                                | 12.4 ms: 1.16x faster                                 |
| pickle_list          | 5.05 us                                                | 4.37 us: 1.16x faster                                 |
| pickle_dict          | 30.0 us                                                | 26.8 us: 1.12x faster                                 |
| xml_etree_parse      | 171 ms                                                 | 155 ms: 1.11x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 107 ms: 1.08x faster                                  |
| pickle               | 10.7 us                                                | 9.95 us: 1.07x faster                                 |
| unpickle             | 14.9 us                                                | 14.3 us: 1.04x faster                                 |
| unpickle_list        | 5.10 us                                                | 5.20 us: 1.02x slower                                 |
| Geometric mean       | (ref)                                                  | 1.17x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.07 ms: 1.77x faster                                 |
| python_startup_no_site | 5.87 ms                                                | 5.85 ms: 1.00x faster                                 |
| Geometric mean         | (ref)                                                  | 1.33x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 16.3 ms                                                | 11.5 ms: 1.41x faster                                 |
| django_template | 47.6 ms                                                | 35.2 ms: 1.35x faster                                 |
| Geometric mean  | (ref)                                                  | 1.38x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220113-linux-x86_64-python-main-3.11.0a4-9471106 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 4.16 ms: 1.88x faster                                 |
| python_startup          | 14.3 ms                                                | 8.07 ms: 1.77x faster                                 |
| scimark_sor             | 214 ms                                                 | 124 ms: 1.73x faster                                  |
| logging_silent          | 189 ns                                                 | 113 ns: 1.67x faster                                  |
| spectral_norm           | 163 ms                                                 | 99.0 ms: 1.65x faster                                 |
| scimark_monte_carlo     | 118 ms                                                 | 72.7 ms: 1.62x faster                                 |
| go                      | 238 ms                                                 | 148 ms: 1.60x faster                                  |
| pyflate                 | 708 ms                                                 | 444 ms: 1.60x faster                                  |
| chaos                   | 114 ms                                                 | 72.7 ms: 1.57x faster                                 |
| nbody                   | 148 ms                                                 | 95.1 ms: 1.56x faster                                 |
| raytrace                | 498 ms                                                 | 320 ms: 1.55x faster                                  |
| hexiom                  | 10.3 ms                                                | 6.63 ms: 1.55x faster                                 |
| richards                | 79.4 ms                                                | 51.5 ms: 1.54x faster                                 |
| scimark_lu              | 175 ms                                                 | 114 ms: 1.54x faster                                  |
| crypto_pyaes            | 127 ms                                                 | 83.8 ms: 1.51x faster                                 |
| float                   | 116 ms                                                 | 78.0 ms: 1.49x faster                                 |
| unpack_sequence         | 65.7 ns                                                | 44.8 ns: 1.47x faster                                 |
| pickle_pure_python      | 482 us                                                 | 329 us: 1.46x faster                                  |
| mako                    | 16.3 ms                                                | 11.5 ms: 1.41x faster                                 |
| xml_etree_process       | 79.8 ms                                                | 56.9 ms: 1.40x faster                                 |
| logging_format          | 9.07 us                                                | 6.51 us: 1.39x faster                                 |
| logging_simple          | 8.27 us                                                | 5.95 us: 1.39x faster                                 |
| scimark_fft             | 454 ms                                                 | 330 ms: 1.38x faster                                  |
| django_template         | 47.6 ms                                                | 35.2 ms: 1.35x faster                                 |
| fannkuch                | 527 ms                                                 | 392 ms: 1.35x faster                                  |
| pycparser               | 1.57 sec                                               | 1.17 sec: 1.34x faster                                |
| regex_compile           | 186 ms                                                 | 138 ms: 1.34x faster                                  |
| 2to3                    | 346 ms                                                 | 264 ms: 1.31x faster                                  |
| thrift                  | 1.06 ms                                                | 812 us: 1.31x faster                                  |
| chameleon               | 9.84 ms                                                | 7.55 ms: 1.30x faster                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.69 ms: 1.30x faster                                 |
| html5lib                | 88.1 ms                                                | 68.1 ms: 1.29x faster                                 |
| unpickle_pure_python    | 327 us                                                 | 254 us: 1.29x faster                                  |
| nqueens                 | 107 ms                                                 | 84.0 ms: 1.27x faster                                 |
| json_loads              | 31.4 us                                                | 25.1 us: 1.25x faster                                 |
| xml_etree_generate      | 100.0 ms                                               | 80.2 ms: 1.25x faster                                 |
| tornado_http            | 131 ms                                                 | 107 ms: 1.22x faster                                  |
| json                    | 5.67 ms                                                | 4.74 ms: 1.19x faster                                 |
| sympy_integrate         | 25.4 ms                                                | 21.4 ms: 1.19x faster                                 |
| dulwich_log             | 77.0 ms                                                | 65.8 ms: 1.17x faster                                 |
| meteor_contest          | 119 ms                                                 | 103 ms: 1.16x faster                                  |
| json_dumps              | 14.3 ms                                                | 12.4 ms: 1.16x faster                                 |
| pickle_list             | 5.05 us                                                | 4.37 us: 1.16x faster                                 |
| sympy_sum               | 190 ms                                                 | 170 ms: 1.12x faster                                  |
| pickle_dict             | 30.0 us                                                | 26.8 us: 1.12x faster                                 |
| sympy_str               | 337 ms                                                 | 302 ms: 1.12x faster                                  |
| xml_etree_parse         | 171 ms                                                 | 155 ms: 1.11x faster                                  |
| sqlite_synth            | 3.02 us                                                | 2.73 us: 1.11x faster                                 |
| sympy_expand            | 558 ms                                                 | 506 ms: 1.10x faster                                  |
| xml_etree_iterparse     | 116 ms                                                 | 107 ms: 1.08x faster                                  |
| pickle                  | 10.7 us                                                | 9.95 us: 1.07x faster                                 |
| pathlib                 | 20.3 ms                                                | 19.1 ms: 1.06x faster                                 |
| regex_v8                | 26.2 ms                                                | 24.8 ms: 1.06x faster                                 |
| regex_effbot            | 3.41 ms                                                | 3.25 ms: 1.05x faster                                 |
| telco                   | 7.01 ms                                                | 6.69 ms: 1.05x faster                                 |
| unpickle                | 14.9 us                                                | 14.3 us: 1.04x faster                                 |
| regex_dna               | 215 ms                                                 | 212 ms: 1.01x faster                                  |
| python_startup_no_site  | 5.87 ms                                                | 5.85 ms: 1.00x faster                                 |
| pidigits                | 190 ms                                                 | 194 ms: 1.02x slower                                  |
| unpickle_list           | 5.10 us                                                | 5.20 us: 1.02x slower                                 |
| Geometric mean          | (ref)                                                  | 1.30x faster                                          |
Ignored benchmarks (41) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.21x
