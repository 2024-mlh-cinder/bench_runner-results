
# Results vs. 3.11.0

- fork: python
- ref: v3.11.2
- machine: linux-x86_64
- commit hash: 878ead1
- commit date: 2023-02-07
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 257 ms: 1.03x faster                                   |
| chameleon      | 6.86 ms                                                | 6.49 ms: 1.06x faster                                  |
| docutils       | 2.69 sec                                               | 2.55 sec: 1.06x faster                                 |
| html5lib       | 65.0 ms                                                | 64.0 ms: 1.02x faster                                  |
| tornado_http   | 97.7 ms                                                | 96.1 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_memoization  | 640 ms                                                 | 628 ms: 1.02x faster                                   |
| async_tree_none         | 532 ms                                                 | 524 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed | 750 ms                                                 | 740 ms: 1.01x faster                                   |
| async_tree_io           | 1.31 sec                                               | 1.30 sec: 1.01x faster                                 |
| Geometric mean          | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 78.9 ms                                                | 76.6 ms: 1.03x faster                                  |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| nbody          | 91.6 ms                                                | 93.0 ms: 1.02x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_v8       | 22.9 ms                                                | 21.3 ms: 1.07x faster                                  |
| regex_dna      | 204 ms                                                 | 192 ms: 1.06x faster                                   |
| regex_compile  | 141 ms                                                 | 138 ms: 1.02x faster                                   |
| regex_effbot   | 3.45 ms                                                | 3.39 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_loads           | 29.4 us                                                | 26.2 us: 1.13x faster                                  |
| pickle_list          | 4.65 us                                                | 4.16 us: 1.12x faster                                  |
| pickle               | 11.1 us                                                | 10.00 us: 1.11x faster                                 |
| pickle_dict          | 34.8 us                                                | 31.4 us: 1.11x faster                                  |
| json_dumps           | 13.5 ms                                                | 12.5 ms: 1.08x faster                                  |
| unpickle_list        | 5.22 us                                                | 4.94 us: 1.06x faster                                  |
| unpickle_pure_python | 241 us                                                 | 228 us: 1.06x faster                                   |
| xml_etree_generate   | 80.4 ms                                                | 76.5 ms: 1.05x faster                                  |
| xml_etree_process    | 56.5 ms                                                | 53.8 ms: 1.05x faster                                  |
| unpickle             | 13.9 us                                                | 13.2 us: 1.05x faster                                  |
| xml_etree_iterparse  | 109 ms                                                 | 104 ms: 1.05x faster                                   |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.04x faster                                   |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.02x faster                                   |
| Geometric mean       | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.47 ms: 1.03x faster                                  |
| python_startup_no_site | 6.09 ms                                                | 5.97 ms: 1.02x faster                                  |
| Geometric mean         | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.83 ms: 1.10x faster                                  |
| genshi_text     | 22.8 ms                                                | 21.7 ms: 1.05x faster                                  |
| genshi_xml      | 54.1 ms                                                | 51.5 ms: 1.05x faster                                  |
| django_template | 33.8 ms                                                | 32.7 ms: 1.03x faster                                  |
| Geometric mean  | (ref)                                                  | 1.06x faster                                           |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_loads              | 29.4 us                                                | 26.2 us: 1.13x faster                                  |
| pickle_list             | 4.65 us                                                | 4.16 us: 1.12x faster                                  |
| pickle                  | 11.1 us                                                | 10.00 us: 1.11x faster                                 |
| pickle_dict             | 34.8 us                                                | 31.4 us: 1.11x faster                                  |
| mako                    | 10.8 ms                                                | 9.83 ms: 1.10x faster                                  |
| logging_silent          | 108 ns                                                 | 99.8 ns: 1.09x faster                                  |
| json_dumps              | 13.5 ms                                                | 12.5 ms: 1.08x faster                                  |
| pycparser               | 1.20 sec                                               | 1.11 sec: 1.08x faster                                 |
| regex_v8                | 22.9 ms                                                | 21.3 ms: 1.07x faster                                  |
| richards                | 48.9 ms                                                | 45.6 ms: 1.07x faster                                  |
| spectral_norm           | 105 ms                                                 | 98.4 ms: 1.07x faster                                  |
| pprint_safe_repr        | 743 ms                                                 | 697 ms: 1.07x faster                                   |
| aiohttp                 | 1.12 ms                                                | 1.05 ms: 1.06x faster                                  |
| json                    | 5.24 ms                                                | 4.92 ms: 1.06x faster                                  |
| regex_dna               | 204 ms                                                 | 192 ms: 1.06x faster                                   |
| scimark_monte_carlo     | 71.8 ms                                                | 67.7 ms: 1.06x faster                                  |
| hexiom                  | 6.74 ms                                                | 6.36 ms: 1.06x faster                                  |
| scimark_sor             | 121 ms                                                 | 115 ms: 1.06x faster                                   |
| gunicorn                | 1.20 ms                                                | 1.13 ms: 1.06x faster                                  |
| deepcopy_memo           | 38.9 us                                                | 36.8 us: 1.06x faster                                  |
| chameleon               | 6.86 ms                                                | 6.49 ms: 1.06x faster                                  |
| unpickle_list           | 5.22 us                                                | 4.94 us: 1.06x faster                                  |
| unpickle_pure_python    | 241 us                                                 | 228 us: 1.06x faster                                   |
| docutils                | 2.69 sec                                               | 2.55 sec: 1.06x faster                                 |
| pprint_pformat          | 1.53 sec                                               | 1.45 sec: 1.06x faster                                 |
| raytrace                | 306 ms                                                 | 291 ms: 1.05x faster                                   |
| sqlglot_transpile       | 1.75 ms                                                | 1.67 ms: 1.05x faster                                  |
| async_generators        | 375 ms                                                 | 357 ms: 1.05x faster                                   |
| logging_format          | 6.83 us                                                | 6.49 us: 1.05x faster                                  |
| xml_etree_generate      | 80.4 ms                                                | 76.5 ms: 1.05x faster                                  |
| scimark_lu              | 112 ms                                                 | 107 ms: 1.05x faster                                   |
| genshi_text             | 22.8 ms                                                | 21.7 ms: 1.05x faster                                  |
| crypto_pyaes            | 77.5 ms                                                | 73.8 ms: 1.05x faster                                  |
| xml_etree_process       | 56.5 ms                                                | 53.8 ms: 1.05x faster                                  |
| genshi_xml              | 54.1 ms                                                | 51.5 ms: 1.05x faster                                  |
| unpickle                | 13.9 us                                                | 13.2 us: 1.05x faster                                  |
| sqlite_synth            | 2.58 us                                                | 2.46 us: 1.05x faster                                  |
| sympy_expand            | 490 ms                                                 | 468 ms: 1.05x faster                                   |
| chaos                   | 71.4 ms                                                | 68.2 ms: 1.05x faster                                  |
| fannkuch                | 410 ms                                                 | 392 ms: 1.05x faster                                   |
| xml_etree_iterparse     | 109 ms                                                 | 104 ms: 1.05x faster                                   |
| logging_simple          | 6.24 us                                                | 5.97 us: 1.05x faster                                  |
| scimark_fft             | 342 ms                                                 | 327 ms: 1.05x faster                                   |
| nqueens                 | 86.8 ms                                                | 83.1 ms: 1.05x faster                                  |
| pickle_pure_python      | 319 us                                                 | 305 us: 1.04x faster                                   |
| meteor_contest          | 109 ms                                                 | 105 ms: 1.04x faster                                   |
| sqlglot_parse           | 1.43 ms                                                | 1.38 ms: 1.04x faster                                  |
| sympy_str               | 299 ms                                                 | 288 ms: 1.04x faster                                   |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.63 ms: 1.04x faster                                  |
| pathlib                 | 18.5 ms                                                | 17.8 ms: 1.04x faster                                  |
| deepcopy                | 360 us                                                 | 348 us: 1.04x faster                                   |
| sqlglot_optimize        | 55.2 ms                                                | 53.3 ms: 1.04x faster                                  |
| deltablue               | 3.80 ms                                                | 3.68 ms: 1.04x faster                                  |
| 2to3                    | 266 ms                                                 | 257 ms: 1.03x faster                                   |
| sqlglot_normalize       | 112 ms                                                 | 109 ms: 1.03x faster                                   |
| django_template         | 33.8 ms                                                | 32.7 ms: 1.03x faster                                  |
| deepcopy_reduce         | 3.14 us                                                | 3.04 us: 1.03x faster                                  |
| generators              | 76.5 ms                                                | 74.1 ms: 1.03x faster                                  |
| float                   | 78.9 ms                                                | 76.6 ms: 1.03x faster                                  |
| sympy_sum               | 170 ms                                                 | 166 ms: 1.03x faster                                   |
| flaskblogging           | 7.20 ms                                                | 7.02 ms: 1.03x faster                                  |
| python_startup          | 8.69 ms                                                | 8.47 ms: 1.03x faster                                  |
| bench_thread_pool       | 833 us                                                 | 812 us: 1.03x faster                                   |
| regex_compile           | 141 ms                                                 | 138 ms: 1.02x faster                                   |
| sympy_integrate         | 21.4 ms                                                | 20.8 ms: 1.02x faster                                  |
| djangocms               | 33.1 us                                                | 32.3 us: 1.02x faster                                  |
| pyflate                 | 426 ms                                                 | 417 ms: 1.02x faster                                   |
| xml_etree_parse         | 163 ms                                                 | 159 ms: 1.02x faster                                   |
| coroutines              | 26.1 ms                                                | 25.6 ms: 1.02x faster                                  |
| python_startup_no_site  | 6.09 ms                                                | 5.97 ms: 1.02x faster                                  |
| async_tree_memoization  | 640 ms                                                 | 628 ms: 1.02x faster                                   |
| dulwich_log             | 64.9 ms                                                | 63.7 ms: 1.02x faster                                  |
| telco                   | 6.72 ms                                                | 6.59 ms: 1.02x faster                                  |
| regex_effbot            | 3.45 ms                                                | 3.39 ms: 1.02x faster                                  |
| tornado_http            | 97.7 ms                                                | 96.1 ms: 1.02x faster                                  |
| html5lib                | 65.0 ms                                                | 64.0 ms: 1.02x faster                                  |
| async_tree_none         | 532 ms                                                 | 524 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed | 750 ms                                                 | 740 ms: 1.01x faster                                   |
| go                      | 143 ms                                                 | 141 ms: 1.01x faster                                   |
| async_tree_io           | 1.31 sec                                               | 1.30 sec: 1.01x faster                                 |
| mdp                     | 2.79 sec                                               | 2.77 sec: 1.01x faster                                 |
| asyncio_tcp             | 887 ms                                                 | 884 ms: 1.00x faster                                   |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| create_gc_cycles        | 1.48 ms                                                | 1.49 ms: 1.01x slower                                  |
| nbody                   | 91.6 ms                                                | 93.0 ms: 1.02x slower                                  |
| gc_traversal            | 3.90 ms                                                | 4.15 ms: 1.06x slower                                  |
| unpack_sequence         | 43.3 ns                                                | 48.8 ns: 1.13x slower                                  |
| coverage                | 81.2 ms                                                | 103 ms: 1.27x slower                                   |
| Geometric mean          | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (7): mypy2, pylint, thrift, sqlalchemy_imperative, dask, bench_mp_pool, sqlalchemy_declarative
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
