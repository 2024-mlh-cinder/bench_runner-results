
# Results vs. 3.11.0

- fork: python
- ref: v3.11.1
- machine: linux-x86_64
- commit hash: a7a450f
- commit date: 2022-12-06
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 258 ms: 1.03x faster                                   |
| chameleon      | 6.86 ms                                                | 6.63 ms: 1.04x faster                                  |
| docutils       | 2.69 sec                                               | 2.57 sec: 1.05x faster                                 |
| html5lib       | 65.0 ms                                                | 63.4 ms: 1.03x faster                                  |
| tornado_http   | 97.7 ms                                                | 99.8 ms: 1.02x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_memoization  | 640 ms                                                 | 627 ms: 1.02x faster                                   |
| async_tree_none         | 532 ms                                                 | 523 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed | 750 ms                                                 | 742 ms: 1.01x faster                                   |
| Geometric mean          | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 78.9 ms                                                | 76.0 ms: 1.04x faster                                  |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| nbody          | 91.6 ms                                                | 95.4 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.31 ms: 1.04x faster                                  |
| regex_compile  | 141 ms                                                 | 137 ms: 1.03x faster                                   |
| regex_v8       | 22.9 ms                                                | 22.3 ms: 1.03x faster                                  |
| regex_dna      | 204 ms                                                 | 200 ms: 1.02x faster                                   |
| Geometric mean | (ref)                                                  | 1.03x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_loads           | 29.4 us                                                | 24.0 us: 1.23x faster                                  |
| pickle               | 11.1 us                                                | 9.72 us: 1.14x faster                                  |
| pickle_dict          | 34.8 us                                                | 31.1 us: 1.12x faster                                  |
| pickle_list          | 4.65 us                                                | 4.17 us: 1.12x faster                                  |
| json_dumps           | 13.5 ms                                                | 12.6 ms: 1.07x faster                                  |
| unpickle_list        | 5.22 us                                                | 4.95 us: 1.06x faster                                  |
| unpickle_pure_python | 241 us                                                 | 229 us: 1.05x faster                                   |
| xml_etree_iterparse  | 109 ms                                                 | 103 ms: 1.05x faster                                   |
| xml_etree_process    | 56.5 ms                                                | 53.7 ms: 1.05x faster                                  |
| xml_etree_generate   | 80.4 ms                                                | 76.6 ms: 1.05x faster                                  |
| unpickle             | 13.9 us                                                | 13.4 us: 1.04x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| pickle_pure_python   | 319 us                                                 | 310 us: 1.03x faster                                   |
| Geometric mean       | (ref)                                                  | 1.08x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.49 ms: 1.02x faster                                  |
| python_startup_no_site | 6.09 ms                                                | 5.98 ms: 1.02x faster                                  |
| Geometric mean         | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.92 ms: 1.09x faster                                  |
| genshi_xml      | 54.1 ms                                                | 52.5 ms: 1.03x faster                                  |
| genshi_text     | 22.8 ms                                                | 22.1 ms: 1.03x faster                                  |
| django_template | 33.8 ms                                                | 33.2 ms: 1.02x faster                                  |
| Geometric mean  | (ref)                                                  | 1.04x faster                                           |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_loads              | 29.4 us                                                | 24.0 us: 1.23x faster                                  |
| pickle                  | 11.1 us                                                | 9.72 us: 1.14x faster                                  |
| json                    | 5.24 ms                                                | 4.63 ms: 1.13x faster                                  |
| pickle_dict             | 34.8 us                                                | 31.1 us: 1.12x faster                                  |
| pickle_list             | 4.65 us                                                | 4.17 us: 1.12x faster                                  |
| mako                    | 10.8 ms                                                | 9.92 ms: 1.09x faster                                  |
| fannkuch                | 410 ms                                                 | 384 ms: 1.07x faster                                   |
| json_dumps              | 13.5 ms                                                | 12.6 ms: 1.07x faster                                  |
| crypto_pyaes            | 77.5 ms                                                | 72.6 ms: 1.07x faster                                  |
| logging_silent          | 108 ns                                                 | 102 ns: 1.06x faster                                   |
| aiohttp                 | 1.12 ms                                                | 1.05 ms: 1.06x faster                                  |
| gunicorn                | 1.20 ms                                                | 1.13 ms: 1.06x faster                                  |
| pprint_pformat          | 1.53 sec                                               | 1.44 sec: 1.06x faster                                 |
| pprint_safe_repr        | 743 ms                                                 | 700 ms: 1.06x faster                                   |
| mdp                     | 2.79 sec                                               | 2.64 sec: 1.06x faster                                 |
| unpickle_list           | 5.22 us                                                | 4.95 us: 1.06x faster                                  |
| unpickle_pure_python    | 241 us                                                 | 229 us: 1.05x faster                                   |
| xml_etree_iterparse     | 109 ms                                                 | 103 ms: 1.05x faster                                   |
| xml_etree_process       | 56.5 ms                                                | 53.7 ms: 1.05x faster                                  |
| xml_etree_generate      | 80.4 ms                                                | 76.6 ms: 1.05x faster                                  |
| logging_simple          | 6.24 us                                                | 5.95 us: 1.05x faster                                  |
| scimark_monte_carlo     | 71.8 ms                                                | 68.4 ms: 1.05x faster                                  |
| async_generators        | 375 ms                                                 | 358 ms: 1.05x faster                                   |
| scimark_sor             | 121 ms                                                 | 116 ms: 1.05x faster                                   |
| docutils                | 2.69 sec                                               | 2.57 sec: 1.05x faster                                 |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.59 ms: 1.05x faster                                  |
| scimark_lu              | 112 ms                                                 | 107 ms: 1.05x faster                                   |
| deepcopy_memo           | 38.9 us                                                | 37.2 us: 1.05x faster                                  |
| sqlglot_transpile       | 1.75 ms                                                | 1.68 ms: 1.05x faster                                  |
| sqlite_synth            | 2.58 us                                                | 2.47 us: 1.05x faster                                  |
| scimark_fft             | 342 ms                                                 | 327 ms: 1.05x faster                                   |
| hexiom                  | 6.74 ms                                                | 6.46 ms: 1.04x faster                                  |
| generators              | 76.5 ms                                                | 73.3 ms: 1.04x faster                                  |
| logging_format          | 6.83 us                                                | 6.54 us: 1.04x faster                                  |
| regex_effbot            | 3.45 ms                                                | 3.31 ms: 1.04x faster                                  |
| raytrace                | 306 ms                                                 | 294 ms: 1.04x faster                                   |
| richards                | 48.9 ms                                                | 46.9 ms: 1.04x faster                                  |
| sqlglot_parse           | 1.43 ms                                                | 1.38 ms: 1.04x faster                                  |
| float                   | 78.9 ms                                                | 76.0 ms: 1.04x faster                                  |
| unpickle                | 13.9 us                                                | 13.4 us: 1.04x faster                                  |
| sympy_expand            | 490 ms                                                 | 472 ms: 1.04x faster                                   |
| deltablue               | 3.80 ms                                                | 3.67 ms: 1.04x faster                                  |
| spectral_norm           | 105 ms                                                 | 101 ms: 1.04x faster                                   |
| sqlglot_normalize       | 112 ms                                                 | 108 ms: 1.04x faster                                   |
| pylint                  | 478 ms                                                 | 461 ms: 1.04x faster                                   |
| sqlglot_optimize        | 55.2 ms                                                | 53.3 ms: 1.04x faster                                  |
| chameleon               | 6.86 ms                                                | 6.63 ms: 1.04x faster                                  |
| sympy_str               | 299 ms                                                 | 289 ms: 1.03x faster                                   |
| coroutines              | 26.1 ms                                                | 25.3 ms: 1.03x faster                                  |
| deepcopy                | 360 us                                                 | 349 us: 1.03x faster                                   |
| regex_compile           | 141 ms                                                 | 137 ms: 1.03x faster                                   |
| xml_etree_parse         | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| genshi_xml              | 54.1 ms                                                | 52.5 ms: 1.03x faster                                  |
| 2to3                    | 266 ms                                                 | 258 ms: 1.03x faster                                   |
| pickle_pure_python      | 319 us                                                 | 310 us: 1.03x faster                                   |
| genshi_text             | 22.8 ms                                                | 22.1 ms: 1.03x faster                                  |
| meteor_contest          | 109 ms                                                 | 106 ms: 1.03x faster                                   |
| pycparser               | 1.20 sec                                               | 1.16 sec: 1.03x faster                                 |
| regex_v8                | 22.9 ms                                                | 22.3 ms: 1.03x faster                                  |
| sympy_sum               | 170 ms                                                 | 166 ms: 1.03x faster                                   |
| pyflate                 | 426 ms                                                 | 415 ms: 1.03x faster                                   |
| html5lib                | 65.0 ms                                                | 63.4 ms: 1.03x faster                                  |
| bench_thread_pool       | 833 us                                                 | 813 us: 1.03x faster                                   |
| chaos                   | 71.4 ms                                                | 69.6 ms: 1.02x faster                                  |
| go                      | 143 ms                                                 | 140 ms: 1.02x faster                                   |
| python_startup          | 8.69 ms                                                | 8.49 ms: 1.02x faster                                  |
| dulwich_log             | 64.9 ms                                                | 63.5 ms: 1.02x faster                                  |
| nqueens                 | 86.8 ms                                                | 85.0 ms: 1.02x faster                                  |
| pathlib                 | 18.5 ms                                                | 18.1 ms: 1.02x faster                                  |
| regex_dna               | 204 ms                                                 | 200 ms: 1.02x faster                                   |
| async_tree_memoization  | 640 ms                                                 | 627 ms: 1.02x faster                                   |
| flaskblogging           | 7.20 ms                                                | 7.07 ms: 1.02x faster                                  |
| python_startup_no_site  | 6.09 ms                                                | 5.98 ms: 1.02x faster                                  |
| sympy_integrate         | 21.4 ms                                                | 21.0 ms: 1.02x faster                                  |
| django_template         | 33.8 ms                                                | 33.2 ms: 1.02x faster                                  |
| async_tree_none         | 532 ms                                                 | 523 ms: 1.02x faster                                   |
| deepcopy_reduce         | 3.14 us                                                | 3.09 us: 1.01x faster                                  |
| sqlalchemy_imperative   | 18.2 ms                                                | 18.0 ms: 1.01x faster                                  |
| async_tree_cpu_io_mixed | 750 ms                                                 | 742 ms: 1.01x faster                                   |
| telco                   | 6.72 ms                                                | 6.66 ms: 1.01x faster                                  |
| thrift                  | 772 us                                                 | 765 us: 1.01x faster                                   |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| asyncio_tcp             | 887 ms                                                 | 889 ms: 1.00x slower                                   |
| create_gc_cycles        | 1.48 ms                                                | 1.48 ms: 1.00x slower                                  |
| tornado_http            | 97.7 ms                                                | 99.8 ms: 1.02x slower                                  |
| unpack_sequence         | 43.3 ns                                                | 44.6 ns: 1.03x slower                                  |
| nbody                   | 91.6 ms                                                | 95.4 ms: 1.04x slower                                  |
| gc_traversal            | 3.90 ms                                                | 4.26 ms: 1.09x slower                                  |
| coverage                | 81.2 ms                                                | 104 ms: 1.28x slower                                   |
| Geometric mean          | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (6): mypy2, async_tree_io, bench_mp_pool, djangocms, dask, sqlalchemy_declarative
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
