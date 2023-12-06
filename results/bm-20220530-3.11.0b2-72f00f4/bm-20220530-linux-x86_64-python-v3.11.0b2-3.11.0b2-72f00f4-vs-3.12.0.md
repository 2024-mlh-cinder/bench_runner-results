
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0b2
- machine: linux-x86_64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 256 ms: 1.07x faster                                       |
| chameleon      | 7.41 ms                                                | 6.62 ms: 1.12x faster                                      |
| docutils       | 2.75 sec                                               | 2.56 sec: 1.08x faster                                     |
| tornado_http   | 101 ms                                                 | 94.9 ms: 1.06x faster                                      |
| Geometric mean | (ref)                                                  | 1.08x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 743 ms: 1.03x slower                                       |
| async_tree_memoization  | 580 ms                                                 | 628 ms: 1.08x slower                                       |
| async_tree_none         | 475 ms                                                 | 526 ms: 1.11x slower                                       |
| async_tree_io           | 1.16 sec                                               | 1.31 sec: 1.12x slower                                     |
| Geometric mean          | (ref)                                                  | 1.08x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 83.3 ms                                                | 74.4 ms: 1.12x faster                                      |
| pidigits       | 187 ms                                                 | 199 ms: 1.06x slower                                       |
| Geometric mean | (ref)                                                  | 1.02x faster                                               |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                | 3.11 ms: 1.15x faster                                      |
| regex_compile  | 148 ms                                                 | 138 ms: 1.08x faster                                       |
| regex_dna      | 209 ms                                                 | 196 ms: 1.06x faster                                       |
| regex_v8       | 22.7 ms                                                | 22.0 ms: 1.03x faster                                      |
| Geometric mean | (ref)                                                  | 1.08x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict          | 33.5 us                                                | 26.4 us: 1.27x faster                                      |
| pickle               | 11.2 us                                                | 9.44 us: 1.19x faster                                      |
| unpickle             | 15.8 us                                                | 13.3 us: 1.18x faster                                      |
| xml_etree_generate   | 88.7 ms                                                | 76.1 ms: 1.17x faster                                      |
| xml_etree_process    | 61.2 ms                                                | 53.4 ms: 1.15x faster                                      |
| json_loads           | 28.4 us                                                | 25.0 us: 1.13x faster                                      |
| pickle_list          | 4.67 us                                                | 4.30 us: 1.09x faster                                      |
| pickle_pure_python   | 326 us                                                 | 305 us: 1.07x faster                                       |
| unpickle_pure_python | 230 us                                                 | 227 us: 1.01x faster                                       |
| unpickle_list        | 5.04 us                                                | 5.00 us: 1.01x faster                                      |
| json_dumps           | 10.6 ms                                                | 12.8 ms: 1.21x slower                                      |
| Geometric mean       | (ref)                                                  | 1.08x faster                                               |

Benchmark hidden because not significant (2): xml_etree_parse, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 5.99 ms: 1.15x faster                                      |
| python_startup         | 9.53 ms                                                | 8.49 ms: 1.12x faster                                      |
| Geometric mean         | (ref)                                                  | 1.14x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.96 ms: 1.15x faster                                      |
| django_template | 35.0 ms                                                | 32.6 ms: 1.08x faster                                      |
| Geometric mean  | (ref)                                                  | 1.11x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_generators        | 459 ms                                                 | 354 ms: 1.30x faster                                       |
| pickle_dict             | 33.5 us                                                | 26.4 us: 1.27x faster                                      |
| pickle                  | 11.2 us                                                | 9.44 us: 1.19x faster                                      |
| unpickle                | 15.8 us                                                | 13.3 us: 1.18x faster                                      |
| scimark_sparse_mat_mult | 5.33 ms                                                | 4.51 ms: 1.18x faster                                      |
| spectral_norm           | 115 ms                                                 | 97.3 ms: 1.18x faster                                      |
| unpack_sequence         | 54.2 ns                                                | 46.2 ns: 1.17x faster                                      |
| xml_etree_generate      | 88.7 ms                                                | 76.1 ms: 1.17x faster                                      |
| scimark_fft             | 381 ms                                                 | 329 ms: 1.16x faster                                       |
| mako                    | 11.5 ms                                                | 9.96 ms: 1.15x faster                                      |
| python_startup_no_site  | 6.92 ms                                                | 5.99 ms: 1.15x faster                                      |
| regex_effbot            | 3.57 ms                                                | 3.11 ms: 1.15x faster                                      |
| xml_etree_process       | 61.2 ms                                                | 53.4 ms: 1.15x faster                                      |
| pyflate                 | 471 ms                                                 | 413 ms: 1.14x faster                                       |
| json_loads              | 28.4 us                                                | 25.0 us: 1.13x faster                                      |
| scimark_monte_carlo     | 74.6 ms                                                | 66.0 ms: 1.13x faster                                      |
| scimark_sor             | 129 ms                                                 | 115 ms: 1.13x faster                                       |
| sqlite_synth            | 2.83 us                                                | 2.52 us: 1.12x faster                                      |
| python_startup          | 9.53 ms                                                | 8.49 ms: 1.12x faster                                      |
| chameleon               | 7.41 ms                                                | 6.62 ms: 1.12x faster                                      |
| float                   | 83.3 ms                                                | 74.4 ms: 1.12x faster                                      |
| logging_format          | 7.10 us                                                | 6.34 us: 1.12x faster                                      |
| crypto_pyaes            | 83.6 ms                                                | 74.8 ms: 1.12x faster                                      |
| logging_simple          | 6.38 us                                                | 5.74 us: 1.11x faster                                      |
| deepcopy_memo           | 39.7 us                                                | 35.9 us: 1.11x faster                                      |
| scimark_lu              | 120 ms                                                 | 109 ms: 1.10x faster                                       |
| gunicorn                | 1.24 ms                                                | 1.13 ms: 1.10x faster                                      |
| json                    | 5.22 ms                                                | 4.75 ms: 1.10x faster                                      |
| telco                   | 7.18 ms                                                | 6.54 ms: 1.10x faster                                      |
| pprint_safe_repr        | 765 ms                                                 | 699 ms: 1.09x faster                                       |
| aiohttp                 | 1.15 ms                                                | 1.06 ms: 1.09x faster                                      |
| dulwich_log             | 68.7 ms                                                | 63.1 ms: 1.09x faster                                      |
| pickle_list             | 4.67 us                                                | 4.30 us: 1.09x faster                                      |
| docutils                | 2.75 sec                                               | 2.56 sec: 1.08x faster                                     |
| regex_compile           | 148 ms                                                 | 138 ms: 1.08x faster                                       |
| django_template         | 35.0 ms                                                | 32.6 ms: 1.08x faster                                      |
| raytrace                | 308 ms                                                 | 287 ms: 1.07x faster                                       |
| sqlalchemy_declarative  | 147 ms                                                 | 137 ms: 1.07x faster                                       |
| 2to3                    | 274 ms                                                 | 256 ms: 1.07x faster                                       |
| pprint_pformat          | 1.55 sec                                               | 1.45 sec: 1.07x faster                                     |
| pickle_pure_python      | 326 us                                                 | 305 us: 1.07x faster                                       |
| deepcopy                | 363 us                                                 | 340 us: 1.07x faster                                       |
| deepcopy_reduce         | 3.23 us                                                | 3.03 us: 1.07x faster                                      |
| regex_dna               | 209 ms                                                 | 196 ms: 1.06x faster                                       |
| tornado_http            | 101 ms                                                 | 94.9 ms: 1.06x faster                                      |
| meteor_contest          | 110 ms                                                 | 104 ms: 1.05x faster                                       |
| logging_silent          | 108 ns                                                 | 103 ns: 1.05x faster                                       |
| pathlib                 | 18.9 ms                                                | 18.1 ms: 1.05x faster                                      |
| hexiom                  | 6.54 ms                                                | 6.27 ms: 1.04x faster                                      |
| bench_thread_pool       | 845 us                                                 | 811 us: 1.04x faster                                       |
| sympy_sum               | 167 ms                                                 | 161 ms: 1.04x faster                                       |
| sqlalchemy_imperative   | 18.5 ms                                                | 17.9 ms: 1.04x faster                                      |
| richards                | 46.0 ms                                                | 44.5 ms: 1.03x faster                                      |
| regex_v8                | 22.7 ms                                                | 22.0 ms: 1.03x faster                                      |
| sympy_str               | 296 ms                                                 | 288 ms: 1.03x faster                                       |
| pycparser               | 1.17 sec                                               | 1.14 sec: 1.03x faster                                     |
| sympy_integrate         | 21.2 ms                                                | 20.7 ms: 1.03x faster                                      |
| nqueens                 | 86.2 ms                                                | 84.2 ms: 1.02x faster                                      |
| sqlglot_optimize        | 54.8 ms                                                | 53.9 ms: 1.02x faster                                      |
| fannkuch                | 410 ms                                                 | 403 ms: 1.02x faster                                       |
| gc_traversal            | 4.28 ms                                                | 4.21 ms: 1.02x faster                                      |
| sqlglot_normalize       | 112 ms                                                 | 110 ms: 1.01x faster                                       |
| unpickle_pure_python    | 230 us                                                 | 227 us: 1.01x faster                                       |
| go                      | 140 ms                                                 | 139 ms: 1.01x faster                                       |
| unpickle_list           | 5.04 us                                                | 5.00 us: 1.01x faster                                      |
| async_tree_cpu_io_mixed | 724 ms                                                 | 743 ms: 1.03x slower                                       |
| deltablue               | 3.71 ms                                                | 3.84 ms: 1.04x slower                                      |
| mdp                     | 2.57 sec                                               | 2.67 sec: 1.04x slower                                     |
| create_gc_cycles        | 1.45 ms                                                | 1.51 ms: 1.04x slower                                      |
| pidigits                | 187 ms                                                 | 199 ms: 1.06x slower                                       |
| async_tree_memoization  | 580 ms                                                 | 628 ms: 1.08x slower                                       |
| coroutines              | 23.5 ms                                                | 25.7 ms: 1.10x slower                                      |
| async_tree_none         | 475 ms                                                 | 526 ms: 1.11x slower                                       |
| async_tree_io           | 1.16 sec                                               | 1.31 sec: 1.12x slower                                     |
| mypy2                   | 351 ms                                                 | 420 ms: 1.20x slower                                       |
| json_dumps              | 10.6 ms                                                | 12.8 ms: 1.21x slower                                      |
| sqlglot_transpile       | 1.68 ms                                                | 2.05 ms: 1.22x slower                                      |
| comprehensions          | 20.9 us                                                | 26.0 us: 1.24x slower                                      |
| sqlglot_parse           | 1.35 ms                                                | 1.75 ms: 1.30x slower                                      |
| asyncio_tcp             | 506 ms                                                 | 890 ms: 1.76x slower                                       |
| generators              | 32.5 ms                                                | 74.4 ms: 2.29x slower                                      |
| Geometric mean          | (ref)                                                  | 1.03x faster                                               |

Benchmark hidden because not significant (7): xml_etree_parse, dask, chaos, xml_etree_iterparse, nbody, sympy_expand, bench_mp_pool
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220530-3.11.0b2-72f00f4/bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4.json: djangocms, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
