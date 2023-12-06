
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.28x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                  |
| chameleon      | 9.84 ms                                                | 7.44 ms: 1.32x faster                                 |
| html5lib       | 88.1 ms                                                | 68.5 ms: 1.29x faster                                 |
| tornado_http   | 131 ms                                                 | 108 ms: 1.21x faster                                  |
| Geometric mean | (ref)                                                  | 1.28x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 148 ms                                                 | 96.1 ms: 1.54x faster                                 |
| float          | 116 ms                                                 | 79.2 ms: 1.47x faster                                 |
| pidigits       | 190 ms                                                 | 198 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.30x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 139 ms: 1.34x faster                                  |
| regex_v8       | 26.2 ms                                                | 24.5 ms: 1.07x faster                                 |
| regex_effbot   | 3.41 ms                                                | 3.21 ms: 1.06x faster                                 |
| regex_dna      | 215 ms                                                 | 212 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.11x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 347 us: 1.39x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 57.8 ms: 1.38x faster                                 |
| unpickle_pure_python | 327 us                                                 | 251 us: 1.30x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 80.8 ms: 1.24x faster                                 |
| json_loads           | 31.4 us                                                | 25.6 us: 1.23x faster                                 |
| json_dumps           | 14.3 ms                                                | 12.6 ms: 1.13x faster                                 |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.10x faster                                  |
| xml_etree_parse      | 171 ms                                                 | 156 ms: 1.10x faster                                  |
| pickle_dict          | 30.0 us                                                | 27.7 us: 1.08x faster                                 |
| pickle_list          | 5.05 us                                                | 4.68 us: 1.08x faster                                 |
| pickle               | 10.7 us                                                | 9.95 us: 1.07x faster                                 |
| unpickle             | 14.9 us                                                | 14.6 us: 1.02x faster                                 |
| unpickle_list        | 5.10 us                                                | 5.21 us: 1.02x slower                                 |
| Geometric mean       | (ref)                                                  | 1.15x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.00 ms: 1.79x faster                                 |
| python_startup_no_site | 5.87 ms                                                | 5.78 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.35x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 16.3 ms                                                | 11.9 ms: 1.37x faster                                 |
| django_template | 47.6 ms                                                | 36.5 ms: 1.30x faster                                 |
| Geometric mean  | (ref)                                                  | 1.33x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-linux-x86_64-python-main-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup          | 14.3 ms                                                | 8.00 ms: 1.79x faster                                 |
| deltablue               | 7.81 ms                                                | 4.54 ms: 1.72x faster                                 |
| logging_silent          | 189 ns                                                 | 110 ns: 1.71x faster                                  |
| scimark_sor             | 214 ms                                                 | 130 ms: 1.64x faster                                  |
| scimark_monte_carlo     | 118 ms                                                 | 74.0 ms: 1.59x faster                                 |
| spectral_norm           | 163 ms                                                 | 104 ms: 1.58x faster                                  |
| scimark_lu              | 175 ms                                                 | 112 ms: 1.57x faster                                  |
| chaos                   | 114 ms                                                 | 73.9 ms: 1.55x faster                                 |
| nbody                   | 148 ms                                                 | 96.1 ms: 1.54x faster                                 |
| hexiom                  | 10.3 ms                                                | 6.77 ms: 1.52x faster                                 |
| go                      | 238 ms                                                 | 158 ms: 1.51x faster                                  |
| raytrace                | 498 ms                                                 | 333 ms: 1.49x faster                                  |
| pyflate                 | 708 ms                                                 | 477 ms: 1.49x faster                                  |
| float                   | 116 ms                                                 | 79.2 ms: 1.47x faster                                 |
| richards                | 79.4 ms                                                | 54.5 ms: 1.46x faster                                 |
| crypto_pyaes            | 127 ms                                                 | 88.1 ms: 1.44x faster                                 |
| logging_format          | 9.07 us                                                | 6.49 us: 1.40x faster                                 |
| pickle_pure_python      | 482 us                                                 | 347 us: 1.39x faster                                  |
| logging_simple          | 8.27 us                                                | 5.97 us: 1.39x faster                                 |
| xml_etree_process       | 79.8 ms                                                | 57.8 ms: 1.38x faster                                 |
| mako                    | 16.3 ms                                                | 11.9 ms: 1.37x faster                                 |
| scimark_fft             | 454 ms                                                 | 332 ms: 1.37x faster                                  |
| fannkuch                | 527 ms                                                 | 386 ms: 1.37x faster                                  |
| regex_compile           | 186 ms                                                 | 139 ms: 1.34x faster                                  |
| unpack_sequence         | 65.7 ns                                                | 49.2 ns: 1.34x faster                                 |
| chameleon               | 9.84 ms                                                | 7.44 ms: 1.32x faster                                 |
| 2to3                    | 346 ms                                                 | 264 ms: 1.31x faster                                  |
| thrift                  | 1.06 ms                                                | 814 us: 1.31x faster                                  |
| django_template         | 47.6 ms                                                | 36.5 ms: 1.30x faster                                 |
| unpickle_pure_python    | 327 us                                                 | 251 us: 1.30x faster                                  |
| html5lib                | 88.1 ms                                                | 68.5 ms: 1.29x faster                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.77 ms: 1.28x faster                                 |
| pycparser               | 1.57 sec                                               | 1.24 sec: 1.27x faster                                |
| nqueens                 | 107 ms                                                 | 84.6 ms: 1.26x faster                                 |
| xml_etree_generate      | 100.0 ms                                               | 80.8 ms: 1.24x faster                                 |
| json_loads              | 31.4 us                                                | 25.6 us: 1.23x faster                                 |
| tornado_http            | 131 ms                                                 | 108 ms: 1.21x faster                                  |
| json                    | 5.67 ms                                                | 4.83 ms: 1.17x faster                                 |
| sympy_integrate         | 25.4 ms                                                | 21.7 ms: 1.17x faster                                 |
| dulwich_log             | 77.0 ms                                                | 67.2 ms: 1.15x faster                                 |
| meteor_contest          | 119 ms                                                 | 104 ms: 1.14x faster                                  |
| json_dumps              | 14.3 ms                                                | 12.6 ms: 1.13x faster                                 |
| sympy_sum               | 190 ms                                                 | 172 ms: 1.11x faster                                  |
| sqlite_synth            | 3.02 us                                                | 2.74 us: 1.10x faster                                 |
| xml_etree_iterparse     | 116 ms                                                 | 105 ms: 1.10x faster                                  |
| xml_etree_parse         | 171 ms                                                 | 156 ms: 1.10x faster                                  |
| sympy_expand            | 558 ms                                                 | 509 ms: 1.10x faster                                  |
| sympy_str               | 337 ms                                                 | 308 ms: 1.09x faster                                  |
| pickle_dict             | 30.0 us                                                | 27.7 us: 1.08x faster                                 |
| pickle_list             | 5.05 us                                                | 4.68 us: 1.08x faster                                 |
| pickle                  | 10.7 us                                                | 9.95 us: 1.07x faster                                 |
| regex_v8                | 26.2 ms                                                | 24.5 ms: 1.07x faster                                 |
| telco                   | 7.01 ms                                                | 6.56 ms: 1.07x faster                                 |
| regex_effbot            | 3.41 ms                                                | 3.21 ms: 1.06x faster                                 |
| pathlib                 | 20.3 ms                                                | 19.4 ms: 1.04x faster                                 |
| unpickle                | 14.9 us                                                | 14.6 us: 1.02x faster                                 |
| python_startup_no_site  | 5.87 ms                                                | 5.78 ms: 1.02x faster                                 |
| regex_dna               | 215 ms                                                 | 212 ms: 1.01x faster                                  |
| unpickle_list           | 5.10 us                                                | 5.21 us: 1.02x slower                                 |
| pidigits                | 190 ms                                                 | 198 ms: 1.04x slower                                  |
| Geometric mean          | (ref)                                                  | 1.28x faster                                          |
Ignored benchmarks (41) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.20x
