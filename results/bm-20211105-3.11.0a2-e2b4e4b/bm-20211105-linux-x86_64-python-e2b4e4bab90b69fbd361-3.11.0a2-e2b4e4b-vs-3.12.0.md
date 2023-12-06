
# Results vs. 3.12.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: linux-x86_64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 274 ms: 1.00x faster                                                  |
| chameleon      | 7.41 ms                                                | 7.46 ms: 1.01x slower                                                 |
| docutils       | 2.75 sec                                               | 2.79 sec: 1.01x slower                                                |
| tornado_http   | 101 ms                                                 | 111 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 475 ms                                                 | 518 ms: 1.09x slower                                                  |
| async_tree_cpu_io_mixed | 724 ms                                                 | 818 ms: 1.13x slower                                                  |
| async_tree_memoization  | 580 ms                                                 | 676 ms: 1.17x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.41 sec: 1.21x slower                                                |
| Geometric mean          | (ref)                                                  | 1.15x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 187 ms                                                 | 188 ms: 1.00x slower                                                  |
| nbody          | 92.2 ms                                                | 112 ms: 1.21x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x slower                                                          |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.26 ms: 1.09x faster                                                 |
| regex_compile  | 148 ms                                                 | 145 ms: 1.02x faster                                                  |
| regex_v8       | 22.7 ms                                                | 23.7 ms: 1.05x slower                                                 |
| regex_dna      | 209 ms                                                 | 219 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 28.6 us: 1.17x faster                                                 |
| unpickle             | 15.8 us                                                | 13.7 us: 1.15x faster                                                 |
| pickle               | 11.2 us                                                | 10.1 us: 1.12x faster                                                 |
| json_loads           | 28.4 us                                                | 25.9 us: 1.10x faster                                                 |
| xml_etree_generate   | 88.7 ms                                                | 81.6 ms: 1.09x faster                                                 |
| xml_etree_process    | 61.2 ms                                                | 59.6 ms: 1.03x faster                                                 |
| unpickle_list        | 5.04 us                                                | 5.13 us: 1.02x slower                                                 |
| xml_etree_iterparse  | 106 ms                                                 | 110 ms: 1.05x slower                                                  |
| pickle_pure_python   | 326 us                                                 | 364 us: 1.12x slower                                                  |
| json_dumps           | 10.6 ms                                                | 12.4 ms: 1.17x slower                                                 |
| unpickle_pure_python | 230 us                                                 | 271 us: 1.18x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (2): xml_etree_parse, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.77 ms: 1.20x faster                                                 |
| python_startup         | 9.53 ms                                                | 14.6 ms: 1.53x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.13x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 11.5 ms                                                | 12.1 ms: 1.05x slower                                                 |
| django_template | 35.0 ms                                                | 37.9 ms: 1.08x slower                                                 |
| Geometric mean  | (ref)                                                  | 1.07x slower                                                          |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators        | 459 ms                                                 | 361 ms: 1.27x faster                                                  |
| unpack_sequence         | 54.2 ns                                                | 43.6 ns: 1.24x faster                                                 |
| python_startup_no_site  | 6.92 ms                                                | 5.77 ms: 1.20x faster                                                 |
| pickle_dict             | 33.5 us                                                | 28.6 us: 1.17x faster                                                 |
| unpickle                | 15.8 us                                                | 13.7 us: 1.15x faster                                                 |
| pickle                  | 11.2 us                                                | 10.1 us: 1.12x faster                                                 |
| telco                   | 7.18 ms                                                | 6.50 ms: 1.10x faster                                                 |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.86 ms: 1.10x faster                                                 |
| json_loads              | 28.4 us                                                | 25.9 us: 1.10x faster                                                 |
| regex_effbot            | 3.57 ms                                                | 3.26 ms: 1.09x faster                                                 |
| xml_etree_generate      | 88.7 ms                                                | 81.6 ms: 1.09x faster                                                 |
| spectral_norm           | 115 ms                                                 | 106 ms: 1.09x faster                                                  |
| gunicorn                | 1.24 ms                                                | 1.15 ms: 1.08x faster                                                 |
| scimark_fft             | 381 ms                                                 | 355 ms: 1.07x faster                                                  |
| json                    | 5.22 ms                                                | 4.91 ms: 1.06x faster                                                 |
| logging_format          | 7.10 us                                                | 6.71 us: 1.06x faster                                                 |
| logging_simple          | 6.38 us                                                | 6.07 us: 1.05x faster                                                 |
| meteor_contest          | 110 ms                                                 | 106 ms: 1.03x faster                                                  |
| xml_etree_process       | 61.2 ms                                                | 59.6 ms: 1.03x faster                                                 |
| sqlite_synth            | 2.83 us                                                | 2.76 us: 1.03x faster                                                 |
| regex_compile           | 148 ms                                                 | 145 ms: 1.02x faster                                                  |
| sqlalchemy_declarative  | 147 ms                                                 | 145 ms: 1.01x faster                                                  |
| dulwich_log             | 68.7 ms                                                | 68.3 ms: 1.01x faster                                                 |
| 2to3                    | 274 ms                                                 | 274 ms: 1.00x faster                                                  |
| pidigits                | 187 ms                                                 | 188 ms: 1.00x slower                                                  |
| chameleon               | 7.41 ms                                                | 7.46 ms: 1.01x slower                                                 |
| coverage                | 75.1 ms                                                | 75.8 ms: 1.01x slower                                                 |
| pathlib                 | 18.9 ms                                                | 19.1 ms: 1.01x slower                                                 |
| sqlalchemy_imperative   | 18.5 ms                                                | 18.8 ms: 1.01x slower                                                 |
| deepcopy_reduce         | 3.23 us                                                | 3.27 us: 1.01x slower                                                 |
| docutils                | 2.75 sec                                               | 2.79 sec: 1.01x slower                                                |
| unpickle_list           | 5.04 us                                                | 5.13 us: 1.02x slower                                                 |
| sympy_sum               | 167 ms                                                 | 170 ms: 1.02x slower                                                  |
| deepcopy_memo           | 39.7 us                                                | 40.4 us: 1.02x slower                                                 |
| pprint_pformat          | 1.55 sec                                               | 1.58 sec: 1.02x slower                                                |
| sympy_str               | 296 ms                                                 | 306 ms: 1.03x slower                                                  |
| fannkuch                | 410 ms                                                 | 427 ms: 1.04x slower                                                  |
| xml_etree_iterparse     | 106 ms                                                 | 110 ms: 1.05x slower                                                  |
| regex_v8                | 22.7 ms                                                | 23.7 ms: 1.05x slower                                                 |
| sympy_integrate         | 21.2 ms                                                | 22.2 ms: 1.05x slower                                                 |
| regex_dna               | 209 ms                                                 | 219 ms: 1.05x slower                                                  |
| scimark_monte_carlo     | 74.6 ms                                                | 78.4 ms: 1.05x slower                                                 |
| mako                    | 11.5 ms                                                | 12.1 ms: 1.05x slower                                                 |
| deepcopy                | 363 us                                                 | 382 us: 1.05x slower                                                  |
| mdp                     | 2.57 sec                                               | 2.71 sec: 1.06x slower                                                |
| bench_thread_pool       | 845 us                                                 | 892 us: 1.06x slower                                                  |
| raytrace                | 308 ms                                                 | 326 ms: 1.06x slower                                                  |
| nqueens                 | 86.2 ms                                                | 91.4 ms: 1.06x slower                                                 |
| sympy_expand            | 476 ms                                                 | 505 ms: 1.06x slower                                                  |
| sqlglot_optimize        | 54.8 ms                                                | 58.4 ms: 1.07x slower                                                 |
| sqlglot_normalize       | 112 ms                                                 | 119 ms: 1.07x slower                                                  |
| pycparser               | 1.17 sec                                               | 1.26 sec: 1.07x slower                                                |
| crypto_pyaes            | 83.6 ms                                                | 90.2 ms: 1.08x slower                                                 |
| django_template         | 35.0 ms                                                | 37.9 ms: 1.08x slower                                                 |
| logging_silent          | 108 ns                                                 | 117 ns: 1.09x slower                                                  |
| async_tree_none         | 475 ms                                                 | 518 ms: 1.09x slower                                                  |
| tornado_http            | 101 ms                                                 | 111 ms: 1.10x slower                                                  |
| pickle_pure_python      | 326 us                                                 | 364 us: 1.12x slower                                                  |
| async_tree_cpu_io_mixed | 724 ms                                                 | 818 ms: 1.13x slower                                                  |
| scimark_lu              | 120 ms                                                 | 136 ms: 1.13x slower                                                  |
| hexiom                  | 6.54 ms                                                | 7.42 ms: 1.13x slower                                                 |
| chaos                   | 67.5 ms                                                | 77.1 ms: 1.14x slower                                                 |
| pyflate                 | 471 ms                                                 | 541 ms: 1.15x slower                                                  |
| async_tree_memoization  | 580 ms                                                 | 676 ms: 1.17x slower                                                  |
| json_dumps              | 10.6 ms                                                | 12.4 ms: 1.17x slower                                                 |
| unpickle_pure_python    | 230 us                                                 | 271 us: 1.18x slower                                                  |
| go                      | 140 ms                                                 | 167 ms: 1.19x slower                                                  |
| scimark_sor             | 129 ms                                                 | 156 ms: 1.21x slower                                                  |
| async_tree_io           | 1.16 sec                                               | 1.41 sec: 1.21x slower                                                |
| richards                | 46.0 ms                                                | 55.7 ms: 1.21x slower                                                 |
| nbody                   | 92.2 ms                                                | 112 ms: 1.21x slower                                                  |
| coroutines              | 23.5 ms                                                | 28.8 ms: 1.23x slower                                                 |
| deltablue               | 3.71 ms                                                | 4.86 ms: 1.31x slower                                                 |
| sqlglot_transpile       | 1.68 ms                                                | 2.37 ms: 1.41x slower                                                 |
| sqlglot_parse           | 1.35 ms                                                | 2.06 ms: 1.53x slower                                                 |
| python_startup          | 9.53 ms                                                | 14.6 ms: 1.53x slower                                                 |
| generators              | 32.5 ms                                                | 57.4 ms: 1.77x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.05x slower                                                          |

Benchmark hidden because not significant (5): xml_etree_parse, pprint_safe_repr, float, bench_mp_pool, pickle_list
Ignored benchmarks (16) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, comprehensions, create_gc_cycles, dask, gc_traversal, mypy2, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20211105-3.11.0a2-e2b4e4b/bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
