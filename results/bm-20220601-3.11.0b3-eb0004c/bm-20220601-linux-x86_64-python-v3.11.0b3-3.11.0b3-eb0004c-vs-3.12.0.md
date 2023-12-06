
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0b3
- machine: linux-x86_64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 256 ms: 1.07x faster                                       |
| chameleon      | 7.41 ms                                                | 6.42 ms: 1.15x faster                                      |
| docutils       | 2.75 sec                                               | 2.56 sec: 1.07x faster                                     |
| tornado_http   | 101 ms                                                 | 94.7 ms: 1.06x faster                                      |
| Geometric mean | (ref)                                                  | 1.09x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 735 ms: 1.02x slower                                       |
| async_tree_memoization  | 580 ms                                                 | 636 ms: 1.10x slower                                       |
| async_tree_none         | 475 ms                                                 | 525 ms: 1.11x slower                                       |
| async_tree_io           | 1.16 sec                                               | 1.30 sec: 1.12x slower                                     |
| Geometric mean          | (ref)                                                  | 1.08x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 83.3 ms                                                | 73.9 ms: 1.13x faster                                      |
| nbody          | 92.2 ms                                                | 94.9 ms: 1.03x slower                                      |
| pidigits       | 187 ms                                                 | 194 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 2.92 ms: 1.22x faster                                      |
| regex_compile  | 148 ms                                                 | 136 ms: 1.09x faster                                       |
| regex_dna      | 209 ms                                                 | 194 ms: 1.07x faster                                       |
| regex_v8       | 22.7 ms                                                | 21.4 ms: 1.06x faster                                      |
| Geometric mean | (ref)                                                  | 1.11x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 26.0 us: 1.29x faster                                      |
| pickle               | 11.2 us                                                | 9.37 us: 1.20x faster                                      |
| unpickle             | 15.8 us                                                | 13.3 us: 1.18x faster                                      |
| xml_etree_generate   | 88.7 ms                                                | 76.7 ms: 1.16x faster                                      |
| xml_etree_process    | 61.2 ms                                                | 53.6 ms: 1.14x faster                                      |
| json_loads           | 28.4 us                                                | 24.9 us: 1.14x faster                                      |
| pickle_list          | 4.67 us                                                | 4.27 us: 1.09x faster                                      |
| pickle_pure_python   | 326 us                                                 | 301 us: 1.08x faster                                       |
| unpickle_list        | 5.04 us                                                | 4.96 us: 1.02x faster                                      |
| unpickle_pure_python | 230 us                                                 | 227 us: 1.01x faster                                       |
| xml_etree_iterparse  | 106 ms                                                 | 108 ms: 1.02x slower                                       |
| json_dumps           | 10.6 ms                                                | 12.7 ms: 1.20x slower                                      |
| Geometric mean       | (ref)                                                  | 1.08x faster                                               |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.01 ms: 1.15x faster                                      |
| python_startup         | 9.53 ms                                                | 8.51 ms: 1.12x faster                                      |
| Geometric mean         | (ref)                                                  | 1.14x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.99 ms: 1.15x faster                                      |
| django_template | 35.0 ms                                                | 33.0 ms: 1.06x faster                                      |
| Geometric mean  | (ref)                                                  | 1.10x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_generators        | 459 ms                                                 | 356 ms: 1.29x faster                                       |
| pickle_dict             | 33.5 us                                                | 26.0 us: 1.29x faster                                      |
| regex_effbot            | 3.57 ms                                                | 2.92 ms: 1.22x faster                                      |
| pickle                  | 11.2 us                                                | 9.37 us: 1.20x faster                                      |
| unpickle                | 15.8 us                                                | 13.3 us: 1.18x faster                                      |
| spectral_norm           | 115 ms                                                 | 97.5 ms: 1.18x faster                                      |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.57 ms: 1.17x faster                                      |
| scimark_fft             | 381 ms                                                 | 328 ms: 1.16x faster                                       |
| xml_etree_generate      | 88.7 ms                                                | 76.7 ms: 1.16x faster                                      |
| chameleon               | 7.41 ms                                                | 6.42 ms: 1.15x faster                                      |
| python_startup_no_site  | 6.92 ms                                                | 6.01 ms: 1.15x faster                                      |
| pyflate                 | 471 ms                                                 | 409 ms: 1.15x faster                                       |
| mako                    | 11.5 ms                                                | 9.99 ms: 1.15x faster                                      |
| xml_etree_process       | 61.2 ms                                                | 53.6 ms: 1.14x faster                                      |
| json_loads              | 28.4 us                                                | 24.9 us: 1.14x faster                                      |
| crypto_pyaes            | 83.6 ms                                                | 73.6 ms: 1.13x faster                                      |
| unpack_sequence         | 54.2 ns                                                | 48.0 ns: 1.13x faster                                      |
| scimark_sor             | 129 ms                                                 | 114 ms: 1.13x faster                                       |
| gc_traversal            | 4.28 ms                                                | 3.79 ms: 1.13x faster                                      |
| float                   | 83.3 ms                                                | 73.9 ms: 1.13x faster                                      |
| scimark_lu              | 120 ms                                                 | 107 ms: 1.12x faster                                       |
| scimark_monte_carlo     | 74.6 ms                                                | 66.6 ms: 1.12x faster                                      |
| python_startup          | 9.53 ms                                                | 8.51 ms: 1.12x faster                                      |
| sqlite_synth            | 2.83 us                                                | 2.53 us: 1.12x faster                                      |
| logging_format          | 7.10 us                                                | 6.35 us: 1.12x faster                                      |
| gunicorn                | 1.24 ms                                                | 1.12 ms: 1.10x faster                                      |
| pprint_safe_repr        | 765 ms                                                 | 694 ms: 1.10x faster                                       |
| json                    | 5.22 ms                                                | 4.74 ms: 1.10x faster                                      |
| logging_simple          | 6.38 us                                                | 5.82 us: 1.10x faster                                      |
| pickle_list             | 4.67 us                                                | 4.27 us: 1.09x faster                                      |
| dulwich_log             | 68.7 ms                                                | 63.0 ms: 1.09x faster                                      |
| telco                   | 7.18 ms                                                | 6.59 ms: 1.09x faster                                      |
| aiohttp                 | 1.15 ms                                                | 1.06 ms: 1.09x faster                                      |
| regex_compile           | 148 ms                                                 | 136 ms: 1.09x faster                                       |
| pickle_pure_python      | 326 us                                                 | 301 us: 1.08x faster                                       |
| deepcopy_reduce         | 3.23 us                                                | 2.98 us: 1.08x faster                                      |
| deepcopy_memo           | 39.7 us                                                | 36.9 us: 1.08x faster                                      |
| docutils                | 2.75 sec                                               | 2.56 sec: 1.07x faster                                     |
| regex_dna               | 209 ms                                                 | 194 ms: 1.07x faster                                       |
| pprint_pformat          | 1.55 sec                                               | 1.45 sec: 1.07x faster                                     |
| sqlalchemy_declarative  | 147 ms                                                 | 137 ms: 1.07x faster                                       |
| 2to3                    | 274 ms                                                 | 256 ms: 1.07x faster                                       |
| deepcopy                | 363 us                                                 | 340 us: 1.07x faster                                       |
| tornado_http            | 101 ms                                                 | 94.7 ms: 1.06x faster                                      |
| logging_silent          | 108 ns                                                 | 101 ns: 1.06x faster                                       |
| django_template         | 35.0 ms                                                | 33.0 ms: 1.06x faster                                      |
| regex_v8                | 22.7 ms                                                | 21.4 ms: 1.06x faster                                      |
| raytrace                | 308 ms                                                 | 292 ms: 1.05x faster                                       |
| meteor_contest          | 110 ms                                                 | 105 ms: 1.05x faster                                       |
| fannkuch                | 410 ms                                                 | 393 ms: 1.04x faster                                       |
| pathlib                 | 18.9 ms                                                | 18.1 ms: 1.04x faster                                      |
| sympy_str               | 296 ms                                                 | 285 ms: 1.04x faster                                       |
| sqlalchemy_imperative   | 18.5 ms                                                | 17.8 ms: 1.04x faster                                      |
| bench_thread_pool       | 845 us                                                 | 816 us: 1.04x faster                                       |
| sympy_sum               | 167 ms                                                 | 162 ms: 1.03x faster                                       |
| hexiom                  | 6.54 ms                                                | 6.36 ms: 1.03x faster                                      |
| nqueens                 | 86.2 ms                                                | 83.8 ms: 1.03x faster                                      |
| sympy_integrate         | 21.2 ms                                                | 20.7 ms: 1.02x faster                                      |
| sqlglot_normalize       | 112 ms                                                 | 109 ms: 1.02x faster                                       |
| unpickle_list           | 5.04 us                                                | 4.96 us: 1.02x faster                                      |
| deltablue               | 3.71 ms                                                | 3.65 ms: 1.02x faster                                      |
| richards                | 46.0 ms                                                | 45.3 ms: 1.01x faster                                      |
| sqlglot_optimize        | 54.8 ms                                                | 54.0 ms: 1.01x faster                                      |
| sympy_expand            | 476 ms                                                 | 469 ms: 1.01x faster                                       |
| unpickle_pure_python    | 230 us                                                 | 227 us: 1.01x faster                                       |
| go                      | 140 ms                                                 | 139 ms: 1.01x faster                                       |
| chaos                   | 67.5 ms                                                | 68.2 ms: 1.01x slower                                      |
| async_tree_cpu_io_mixed | 724 ms                                                 | 735 ms: 1.02x slower                                       |
| xml_etree_iterparse     | 106 ms                                                 | 108 ms: 1.02x slower                                       |
| nbody                   | 92.2 ms                                                | 94.9 ms: 1.03x slower                                      |
| pidigits                | 187 ms                                                 | 194 ms: 1.04x slower                                       |
| create_gc_cycles        | 1.45 ms                                                | 1.51 ms: 1.04x slower                                      |
| mdp                     | 2.57 sec                                               | 2.69 sec: 1.05x slower                                     |
| async_tree_memoization  | 580 ms                                                 | 636 ms: 1.10x slower                                       |
| async_tree_none         | 475 ms                                                 | 525 ms: 1.11x slower                                       |
| coroutines              | 23.5 ms                                                | 26.0 ms: 1.11x slower                                      |
| async_tree_io           | 1.16 sec                                               | 1.30 sec: 1.12x slower                                     |
| mypy2                   | 351 ms                                                 | 419 ms: 1.19x slower                                       |
| json_dumps              | 10.6 ms                                                | 12.7 ms: 1.20x slower                                      |
| sqlglot_transpile       | 1.68 ms                                                | 2.04 ms: 1.22x slower                                      |
| comprehensions          | 20.9 us                                                | 25.9 us: 1.24x slower                                      |
| sqlglot_parse           | 1.35 ms                                                | 1.75 ms: 1.30x slower                                      |
| asyncio_tcp             | 506 ms                                                 | 888 ms: 1.76x slower                                       |
| generators              | 32.5 ms                                                | 73.8 ms: 2.27x slower                                      |
| Geometric mean          | (ref)                                                  | 1.03x faster                                               |

Benchmark hidden because not significant (4): xml_etree_parse, dask, bench_mp_pool, pycparser
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (7) of results/bm-20220601-3.11.0b3-eb0004c/bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
