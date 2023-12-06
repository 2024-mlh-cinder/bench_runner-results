
# Results vs. 3.11.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: linux-x86_64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.06x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 246 ms: 1.08x faster                                                  |
| chameleon      | 6.86 ms                                                | 6.45 ms: 1.06x faster                                                 |
| docutils       | 2.69 sec                                               | 2.57 sec: 1.05x faster                                                |
| html5lib       | 65.0 ms                                                | 59.7 ms: 1.09x faster                                                 |
| Geometric mean | (ref)                                                  | 1.07x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io           | 1.31 sec                                               | 1.34 sec: 1.02x slower                                                |
| async_tree_cpu_io_mixed | 750 ms                                                 | 769 ms: 1.03x slower                                                  |
| async_tree_memoization  | 640 ms                                                 | 665 ms: 1.04x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.02x slower                                                          |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 78.9 ms                                                | 73.2 ms: 1.08x faster                                                 |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                                  |
| nbody          | 91.6 ms                                                | 94.0 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 129 ms: 1.10x faster                                                  |
| regex_v8       | 22.9 ms                                                | 22.3 ms: 1.03x faster                                                 |
| regex_effbot   | 3.45 ms                                                | 3.63 ms: 1.05x slower                                                 |
| regex_dna      | 204 ms                                                 | 217 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.52 ms: 1.41x faster                                                 |
| json_loads           | 29.4 us                                                | 23.8 us: 1.24x faster                                                 |
| unpickle_pure_python | 241 us                                                 | 200 us: 1.20x faster                                                  |
| pickle_list          | 4.65 us                                                | 3.95 us: 1.18x faster                                                 |
| pickle_pure_python   | 319 us                                                 | 282 us: 1.13x faster                                                  |
| pickle_dict          | 34.8 us                                                | 31.5 us: 1.10x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 148 ms: 1.10x faster                                                  |
| pickle               | 11.1 us                                                | 10.1 us: 1.09x faster                                                 |
| xml_etree_process    | 56.5 ms                                                | 53.7 ms: 1.05x faster                                                 |
| unpickle_list        | 5.22 us                                                | 4.97 us: 1.05x faster                                                 |
| xml_etree_generate   | 80.4 ms                                                | 76.9 ms: 1.05x faster                                                 |
| xml_etree_iterparse  | 109 ms                                                 | 104 ms: 1.04x faster                                                  |
| unpickle             | 13.9 us                                                | 13.3 us: 1.04x faster                                                 |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.52 ms: 1.02x faster                                                 |
| python_startup_no_site | 6.09 ms                                                | 6.07 ms: 1.00x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.43 ms: 1.15x faster                                                 |
| genshi_xml      | 54.1 ms                                                | 48.0 ms: 1.13x faster                                                 |
| genshi_text     | 22.8 ms                                                | 20.9 ms: 1.09x faster                                                 |
| django_template | 33.8 ms                                                | 33.0 ms: 1.03x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.10x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps              | 13.5 ms                                                | 9.52 ms: 1.41x faster                                                 |
| mypy2                   | 427 ms                                                 | 329 ms: 1.30x faster                                                  |
| json_loads              | 29.4 us                                                | 23.8 us: 1.24x faster                                                 |
| unpickle_pure_python    | 241 us                                                 | 200 us: 1.20x faster                                                  |
| logging_silent          | 108 ns                                                 | 90.9 ns: 1.19x faster                                                 |
| deltablue               | 3.80 ms                                                | 3.22 ms: 1.18x faster                                                 |
| pickle_list             | 4.65 us                                                | 3.95 us: 1.18x faster                                                 |
| richards                | 48.9 ms                                                | 42.0 ms: 1.17x faster                                                 |
| scimark_sor             | 121 ms                                                 | 105 ms: 1.16x faster                                                  |
| mako                    | 10.8 ms                                                | 9.43 ms: 1.15x faster                                                 |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.20 ms: 1.14x faster                                                 |
| deepcopy_memo           | 38.9 us                                                | 34.2 us: 1.14x faster                                                 |
| pickle_pure_python      | 319 us                                                 | 282 us: 1.13x faster                                                  |
| genshi_xml              | 54.1 ms                                                | 48.0 ms: 1.13x faster                                                 |
| json                    | 5.24 ms                                                | 4.67 ms: 1.12x faster                                                 |
| mdp                     | 2.79 sec                                               | 2.50 sec: 1.12x faster                                                |
| hexiom                  | 6.74 ms                                                | 6.08 ms: 1.11x faster                                                 |
| pickle_dict             | 34.8 us                                                | 31.5 us: 1.10x faster                                                 |
| scimark_monte_carlo     | 71.8 ms                                                | 65.4 ms: 1.10x faster                                                 |
| xml_etree_parse         | 163 ms                                                 | 148 ms: 1.10x faster                                                  |
| regex_compile           | 141 ms                                                 | 129 ms: 1.10x faster                                                  |
| spectral_norm           | 105 ms                                                 | 96.0 ms: 1.10x faster                                                 |
| pickle                  | 11.1 us                                                | 10.1 us: 1.09x faster                                                 |
| pycparser               | 1.20 sec                                               | 1.09 sec: 1.09x faster                                                |
| raytrace                | 306 ms                                                 | 281 ms: 1.09x faster                                                  |
| genshi_text             | 22.8 ms                                                | 20.9 ms: 1.09x faster                                                 |
| scimark_fft             | 342 ms                                                 | 314 ms: 1.09x faster                                                  |
| html5lib                | 65.0 ms                                                | 59.7 ms: 1.09x faster                                                 |
| sqlglot_optimize        | 55.2 ms                                                | 50.6 ms: 1.09x faster                                                 |
| nqueens                 | 86.8 ms                                                | 80.1 ms: 1.08x faster                                                 |
| deepcopy                | 360 us                                                 | 332 us: 1.08x faster                                                  |
| pprint_safe_repr        | 743 ms                                                 | 686 ms: 1.08x faster                                                  |
| fannkuch                | 410 ms                                                 | 379 ms: 1.08x faster                                                  |
| 2to3                    | 266 ms                                                 | 246 ms: 1.08x faster                                                  |
| pprint_pformat          | 1.53 sec                                               | 1.41 sec: 1.08x faster                                                |
| float                   | 78.9 ms                                                | 73.2 ms: 1.08x faster                                                 |
| sqlglot_transpile       | 1.75 ms                                                | 1.63 ms: 1.07x faster                                                 |
| sqlglot_normalize       | 112 ms                                                 | 105 ms: 1.07x faster                                                  |
| sympy_expand            | 490 ms                                                 | 458 ms: 1.07x faster                                                  |
| bench_thread_pool       | 833 us                                                 | 778 us: 1.07x faster                                                  |
| sqlglot_parse           | 1.43 ms                                                | 1.34 ms: 1.07x faster                                                 |
| chaos                   | 71.4 ms                                                | 66.9 ms: 1.07x faster                                                 |
| logging_format          | 6.83 us                                                | 6.41 us: 1.06x faster                                                 |
| chameleon               | 6.86 ms                                                | 6.45 ms: 1.06x faster                                                 |
| logging_simple          | 6.24 us                                                | 5.88 us: 1.06x faster                                                 |
| async_generators        | 375 ms                                                 | 354 ms: 1.06x faster                                                  |
| deepcopy_reduce         | 3.14 us                                                | 2.97 us: 1.06x faster                                                 |
| scimark_lu              | 112 ms                                                 | 106 ms: 1.06x faster                                                  |
| sympy_str               | 299 ms                                                 | 283 ms: 1.06x faster                                                  |
| go                      | 143 ms                                                 | 136 ms: 1.05x faster                                                  |
| xml_etree_process       | 56.5 ms                                                | 53.7 ms: 1.05x faster                                                 |
| unpickle_list           | 5.22 us                                                | 4.97 us: 1.05x faster                                                 |
| pyflate                 | 426 ms                                                 | 405 ms: 1.05x faster                                                  |
| coroutines              | 26.1 ms                                                | 25.0 ms: 1.05x faster                                                 |
| meteor_contest          | 109 ms                                                 | 104 ms: 1.05x faster                                                  |
| xml_etree_generate      | 80.4 ms                                                | 76.9 ms: 1.05x faster                                                 |
| docutils                | 2.69 sec                                               | 2.57 sec: 1.05x faster                                                |
| sympy_integrate         | 21.4 ms                                                | 20.4 ms: 1.05x faster                                                 |
| xml_etree_iterparse     | 109 ms                                                 | 104 ms: 1.04x faster                                                  |
| telco                   | 6.72 ms                                                | 6.46 ms: 1.04x faster                                                 |
| unpickle                | 13.9 us                                                | 13.3 us: 1.04x faster                                                 |
| dulwich_log             | 64.9 ms                                                | 62.5 ms: 1.04x faster                                                 |
| sympy_sum               | 170 ms                                                 | 164 ms: 1.04x faster                                                  |
| crypto_pyaes            | 77.5 ms                                                | 75.3 ms: 1.03x faster                                                 |
| thrift                  | 772 us                                                 | 751 us: 1.03x faster                                                  |
| create_gc_cycles        | 1.48 ms                                                | 1.44 ms: 1.03x faster                                                 |
| regex_v8                | 22.9 ms                                                | 22.3 ms: 1.03x faster                                                 |
| django_template         | 33.8 ms                                                | 33.0 ms: 1.03x faster                                                 |
| gc_traversal            | 3.90 ms                                                | 3.81 ms: 1.02x faster                                                 |
| python_startup          | 8.69 ms                                                | 8.52 ms: 1.02x faster                                                 |
| dask                    | 365 ms                                                 | 360 ms: 1.01x faster                                                  |
| pathlib                 | 18.5 ms                                                | 18.3 ms: 1.01x faster                                                 |
| pidigits                | 190 ms                                                 | 189 ms: 1.00x faster                                                  |
| python_startup_no_site  | 6.09 ms                                                | 6.07 ms: 1.00x faster                                                 |
| asyncio_tcp             | 887 ms                                                 | 890 ms: 1.00x slower                                                  |
| async_tree_io           | 1.31 sec                                               | 1.34 sec: 1.02x slower                                                |
| async_tree_cpu_io_mixed | 750 ms                                                 | 769 ms: 1.03x slower                                                  |
| nbody                   | 91.6 ms                                                | 94.0 ms: 1.03x slower                                                 |
| generators              | 76.5 ms                                                | 79.1 ms: 1.03x slower                                                 |
| async_tree_memoization  | 640 ms                                                 | 665 ms: 1.04x slower                                                  |
| regex_effbot            | 3.45 ms                                                | 3.63 ms: 1.05x slower                                                 |
| regex_dna               | 204 ms                                                 | 217 ms: 1.06x slower                                                  |
| coverage                | 81.2 ms                                                | 102 ms: 1.26x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.06x faster                                                          |

Benchmark hidden because not significant (6): djangocms, unpack_sequence, comprehensions, sqlite_synth, bench_mp_pool, async_tree_none
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.04x
