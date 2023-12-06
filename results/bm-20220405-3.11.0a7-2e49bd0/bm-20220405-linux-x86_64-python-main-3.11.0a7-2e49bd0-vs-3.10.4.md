
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 2e49bd0
- commit date: 2022-04-05
- overall geometric mean: 1.32x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                  |
| chameleon      | 9.84 ms                                                | 6.87 ms: 1.43x faster                                 |
| html5lib       | 88.1 ms                                                | 65.3 ms: 1.35x faster                                 |
| tornado_http   | 131 ms                                                 | 95.4 ms: 1.37x faster                                 |
| Geometric mean | (ref)                                                  | 1.36x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| float          | 116 ms                                                 | 74.4 ms: 1.56x faster                                 |
| nbody          | 148 ms                                                 | 95.2 ms: 1.56x faster                                 |
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                  |
| Geometric mean | (ref)                                                  | 1.33x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 137 ms: 1.35x faster                                  |
| regex_effbot   | 3.41 ms                                                | 3.34 ms: 1.02x faster                                 |
| regex_v8       | 26.2 ms                                                | 25.9 ms: 1.01x faster                                 |
| regex_dna      | 215 ms                                                 | 231 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 311 us: 1.55x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 55.2 ms: 1.44x faster                                 |
| unpickle_pure_python | 327 us                                                 | 231 us: 1.42x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 78.5 ms: 1.27x faster                                 |
| json_dumps           | 14.3 ms                                                | 12.5 ms: 1.15x faster                                 |
| xml_etree_iterparse  | 116 ms                                                 | 104 ms: 1.12x faster                                  |
| pickle               | 10.7 us                                                | 9.55 us: 1.12x faster                                 |
| json_loads           | 31.4 us                                                | 28.1 us: 1.12x faster                                 |
| pickle_list          | 5.05 us                                                | 4.57 us: 1.11x faster                                 |
| xml_etree_parse      | 171 ms                                                 | 157 ms: 1.09x faster                                  |
| pickle_dict          | 30.0 us                                                | 27.6 us: 1.08x faster                                 |
| unpickle             | 14.9 us                                                | 14.1 us: 1.05x faster                                 |
| unpickle_list        | 5.10 us                                                | 4.97 us: 1.03x faster                                 |
| Geometric mean       | (ref)                                                  | 1.19x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.07 ms: 1.78x faster                                 |
| python_startup_no_site | 5.87 ms                                                | 5.98 ms: 1.02x slower                                 |
| Geometric mean         | (ref)                                                  | 1.32x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|-----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako            | 16.3 ms                                                | 10.2 ms: 1.60x faster                                 |
| django_template | 47.6 ms                                                | 34.3 ms: 1.39x faster                                 |
| Geometric mean  | (ref)                                                  | 1.49x faster                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220405-linux-x86_64-python-main-3.11.0a7-2e49bd0 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.70 ms: 2.11x faster                                 |
| logging_silent          | 189 ns                                                 | 104 ns: 1.82x faster                                  |
| python_startup          | 14.3 ms                                                | 8.07 ms: 1.78x faster                                 |
| scimark_sor             | 214 ms                                                 | 123 ms: 1.74x faster                                  |
| richards                | 79.4 ms                                                | 47.5 ms: 1.67x faster                                 |
| go                      | 238 ms                                                 | 143 ms: 1.67x faster                                  |
| scimark_monte_carlo     | 118 ms                                                 | 70.8 ms: 1.66x faster                                 |
| raytrace                | 498 ms                                                 | 306 ms: 1.63x faster                                  |
| chaos                   | 114 ms                                                 | 70.2 ms: 1.63x faster                                 |
| scimark_lu              | 175 ms                                                 | 108 ms: 1.62x faster                                  |
| pyflate                 | 708 ms                                                 | 438 ms: 1.62x faster                                  |
| mako                    | 16.3 ms                                                | 10.2 ms: 1.60x faster                                 |
| float                   | 116 ms                                                 | 74.4 ms: 1.56x faster                                 |
| spectral_norm           | 163 ms                                                 | 105 ms: 1.56x faster                                  |
| nbody                   | 148 ms                                                 | 95.2 ms: 1.56x faster                                 |
| pickle_pure_python      | 482 us                                                 | 311 us: 1.55x faster                                  |
| crypto_pyaes            | 127 ms                                                 | 82.7 ms: 1.53x faster                                 |
| hexiom                  | 10.3 ms                                                | 6.84 ms: 1.51x faster                                 |
| unpack_sequence         | 65.7 ns                                                | 44.9 ns: 1.46x faster                                 |
| xml_etree_process       | 79.8 ms                                                | 55.2 ms: 1.44x faster                                 |
| chameleon               | 9.84 ms                                                | 6.87 ms: 1.43x faster                                 |
| logging_format          | 9.07 us                                                | 6.35 us: 1.43x faster                                 |
| logging_simple          | 8.27 us                                                | 5.80 us: 1.43x faster                                 |
| unpickle_pure_python    | 327 us                                                 | 231 us: 1.42x faster                                  |
| thrift                  | 1.06 ms                                                | 762 us: 1.40x faster                                  |
| django_template         | 47.6 ms                                                | 34.3 ms: 1.39x faster                                 |
| tornado_http            | 131 ms                                                 | 95.4 ms: 1.37x faster                                 |
| scimark_fft             | 454 ms                                                 | 335 ms: 1.36x faster                                  |
| regex_compile           | 186 ms                                                 | 137 ms: 1.35x faster                                  |
| html5lib                | 88.1 ms                                                | 65.3 ms: 1.35x faster                                 |
| fannkuch                | 527 ms                                                 | 401 ms: 1.32x faster                                  |
| 2to3                    | 346 ms                                                 | 264 ms: 1.31x faster                                  |
| xml_etree_generate      | 100.0 ms                                               | 78.5 ms: 1.27x faster                                 |
| pycparser               | 1.57 sec                                               | 1.24 sec: 1.26x faster                                |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.85 ms: 1.26x faster                                 |
| nqueens                 | 107 ms                                                 | 85.2 ms: 1.25x faster                                 |
| sympy_integrate         | 25.4 ms                                                | 20.5 ms: 1.24x faster                                 |
| dulwich_log             | 77.0 ms                                                | 63.8 ms: 1.21x faster                                 |
| sqlite_synth            | 3.02 us                                                | 2.51 us: 1.20x faster                                 |
| sympy_sum               | 190 ms                                                 | 160 ms: 1.19x faster                                  |
| sympy_expand            | 558 ms                                                 | 476 ms: 1.17x faster                                  |
| sympy_str               | 337 ms                                                 | 287 ms: 1.17x faster                                  |
| json_dumps              | 14.3 ms                                                | 12.5 ms: 1.15x faster                                 |
| xml_etree_iterparse     | 116 ms                                                 | 104 ms: 1.12x faster                                  |
| meteor_contest          | 119 ms                                                 | 107 ms: 1.12x faster                                  |
| json                    | 5.67 ms                                                | 5.07 ms: 1.12x faster                                 |
| pickle                  | 10.7 us                                                | 9.55 us: 1.12x faster                                 |
| json_loads              | 31.4 us                                                | 28.1 us: 1.12x faster                                 |
| pickle_list             | 5.05 us                                                | 4.57 us: 1.11x faster                                 |
| pathlib                 | 20.3 ms                                                | 18.5 ms: 1.10x faster                                 |
| xml_etree_parse         | 171 ms                                                 | 157 ms: 1.09x faster                                  |
| pickle_dict             | 30.0 us                                                | 27.6 us: 1.08x faster                                 |
| telco                   | 7.01 ms                                                | 6.59 ms: 1.06x faster                                 |
| unpickle                | 14.9 us                                                | 14.1 us: 1.05x faster                                 |
| unpickle_list           | 5.10 us                                                | 4.97 us: 1.03x faster                                 |
| regex_effbot            | 3.41 ms                                                | 3.34 ms: 1.02x faster                                 |
| regex_v8                | 26.2 ms                                                | 25.9 ms: 1.01x faster                                 |
| python_startup_no_site  | 5.87 ms                                                | 5.98 ms: 1.02x slower                                 |
| pidigits                | 190 ms                                                 | 197 ms: 1.03x slower                                  |
| regex_dna               | 215 ms                                                 | 231 ms: 1.08x slower                                  |
| Geometric mean          | (ref)                                                  | 1.32x faster                                          |
Ignored benchmarks (41) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, async_generators, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_none, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, bench_mp_pool, bench_thread_pool, comprehensions, coroutines, coverage, create_gc_cycles, dask, deepcopy, deepcopy_memo, deepcopy_reduce, djangocms, docutils, flaskblogging, gc_traversal, generators, genshi_text, genshi_xml, gunicorn, mdp, mypy2, pprint_pformat, pprint_safe_repr, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, sqlglot_normalize, sqlglot_optimize, sqlglot_parse, sqlglot_transpile, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.24x
