
# Results vs. 3.11.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: linux-x86_64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 249 ms: 1.07x faster                                                  |
| chameleon      | 6.86 ms                                                | 6.51 ms: 1.05x faster                                                 |
| docutils       | 2.69 sec                                               | 2.52 sec: 1.07x faster                                                |
| html5lib       | 65.0 ms                                                | 59.9 ms: 1.08x faster                                                 |
| tornado_http   | 97.7 ms                                                | 93.7 ms: 1.04x faster                                                 |
| Geometric mean | (ref)                                                  | 1.06x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 750 ms                                                 | 730 ms: 1.03x faster                                                  |
| async_tree_io           | 1.31 sec                                               | 1.33 sec: 1.01x slower                                                |
| async_tree_memoization  | 640 ms                                                 | 656 ms: 1.02x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.00x slower                                                          |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 78.9 ms                                                | 71.4 ms: 1.10x faster                                                 |
| pidigits       | 190 ms                                                 | 198 ms: 1.04x slower                                                  |
| nbody          | 91.6 ms                                                | 96.6 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                  | 1.00x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 127 ms: 1.11x faster                                                  |
| regex_v8       | 22.9 ms                                                | 21.4 ms: 1.07x faster                                                 |
| regex_effbot   | 3.45 ms                                                | 3.37 ms: 1.02x faster                                                 |
| regex_dna      | 204 ms                                                 | 201 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.36 ms: 1.44x faster                                                 |
| json_loads           | 29.4 us                                                | 23.5 us: 1.25x faster                                                 |
| unpickle_pure_python | 241 us                                                 | 202 us: 1.19x faster                                                  |
| pickle_dict          | 34.8 us                                                | 31.1 us: 1.12x faster                                                 |
| pickle_pure_python   | 319 us                                                 | 285 us: 1.12x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 145 ms: 1.12x faster                                                  |
| pickle_list          | 4.65 us                                                | 4.19 us: 1.11x faster                                                 |
| pickle               | 11.1 us                                                | 10.1 us: 1.09x faster                                                 |
| xml_etree_iterparse  | 109 ms                                                 | 101 ms: 1.08x faster                                                  |
| unpickle_list        | 5.22 us                                                | 4.91 us: 1.06x faster                                                 |
| xml_etree_generate   | 80.4 ms                                                | 76.0 ms: 1.06x faster                                                 |
| xml_etree_process    | 56.5 ms                                                | 53.4 ms: 1.06x faster                                                 |
| unpickle             | 13.9 us                                                | 13.2 us: 1.05x faster                                                 |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.42 ms: 1.03x faster                                                 |
| python_startup_no_site | 6.09 ms                                                | 5.93 ms: 1.03x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.64 ms: 1.12x faster                                                 |
| genshi_xml      | 54.1 ms                                                | 50.0 ms: 1.08x faster                                                 |
| genshi_text     | 22.8 ms                                                | 21.5 ms: 1.06x faster                                                 |
| django_template | 33.8 ms                                                | 33.0 ms: 1.02x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.07x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps              | 13.5 ms                                                | 9.36 ms: 1.44x faster                                                 |
| mypy2                   | 427 ms                                                 | 328 ms: 1.30x faster                                                  |
| json_loads              | 29.4 us                                                | 23.5 us: 1.25x faster                                                 |
| unpickle_pure_python    | 241 us                                                 | 202 us: 1.19x faster                                                  |
| logging_silent          | 108 ns                                                 | 91.6 ns: 1.18x faster                                                 |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.13 ms: 1.16x faster                                                 |
| deltablue               | 3.80 ms                                                | 3.30 ms: 1.15x faster                                                 |
| richards                | 48.9 ms                                                | 42.4 ms: 1.15x faster                                                 |
| json                    | 5.24 ms                                                | 4.55 ms: 1.15x faster                                                 |
| scimark_sor             | 121 ms                                                 | 106 ms: 1.15x faster                                                  |
| deepcopy_memo           | 38.9 us                                                | 34.4 us: 1.13x faster                                                 |
| mako                    | 10.8 ms                                                | 9.64 ms: 1.12x faster                                                 |
| mdp                     | 2.79 sec                                               | 2.48 sec: 1.12x faster                                                |
| pickle_dict             | 34.8 us                                                | 31.1 us: 1.12x faster                                                 |
| pickle_pure_python      | 319 us                                                 | 285 us: 1.12x faster                                                  |
| xml_etree_parse         | 163 ms                                                 | 145 ms: 1.12x faster                                                  |
| pprint_safe_repr        | 743 ms                                                 | 665 ms: 1.12x faster                                                  |
| gunicorn                | 1.20 ms                                                | 1.07 ms: 1.12x faster                                                 |
| regex_compile           | 141 ms                                                 | 127 ms: 1.11x faster                                                  |
| aiohttp                 | 1.12 ms                                                | 1.00 ms: 1.11x faster                                                 |
| pprint_pformat          | 1.53 sec                                               | 1.38 sec: 1.11x faster                                                |
| pickle_list             | 4.65 us                                                | 4.19 us: 1.11x faster                                                 |
| fannkuch                | 410 ms                                                 | 370 ms: 1.11x faster                                                  |
| float                   | 78.9 ms                                                | 71.4 ms: 1.10x faster                                                 |
| spectral_norm           | 105 ms                                                 | 95.2 ms: 1.10x faster                                                 |
| comprehensions          | 23.6 us                                                | 21.3 us: 1.10x faster                                                 |
| hexiom                  | 6.74 ms                                                | 6.11 ms: 1.10x faster                                                 |
| gc_traversal            | 3.90 ms                                                | 3.55 ms: 1.10x faster                                                 |
| scimark_fft             | 342 ms                                                 | 312 ms: 1.10x faster                                                  |
| pickle                  | 11.1 us                                                | 10.1 us: 1.09x faster                                                 |
| html5lib                | 65.0 ms                                                | 59.9 ms: 1.08x faster                                                 |
| raytrace                | 306 ms                                                 | 282 ms: 1.08x faster                                                  |
| deepcopy                | 360 us                                                 | 333 us: 1.08x faster                                                  |
| genshi_xml              | 54.1 ms                                                | 50.0 ms: 1.08x faster                                                 |
| xml_etree_iterparse     | 109 ms                                                 | 101 ms: 1.08x faster                                                  |
| deepcopy_reduce         | 3.14 us                                                | 2.91 us: 1.08x faster                                                 |
| sympy_expand            | 490 ms                                                 | 455 ms: 1.08x faster                                                  |
| logging_simple          | 6.24 us                                                | 5.80 us: 1.08x faster                                                 |
| scimark_monte_carlo     | 71.8 ms                                                | 66.6 ms: 1.08x faster                                                 |
| nqueens                 | 86.8 ms                                                | 80.7 ms: 1.08x faster                                                 |
| sqlglot_optimize        | 55.2 ms                                                | 51.2 ms: 1.08x faster                                                 |
| sqlglot_normalize       | 112 ms                                                 | 104 ms: 1.08x faster                                                  |
| async_generators        | 375 ms                                                 | 349 ms: 1.08x faster                                                  |
| sqlglot_transpile       | 1.75 ms                                                | 1.63 ms: 1.08x faster                                                 |
| regex_v8                | 22.9 ms                                                | 21.4 ms: 1.07x faster                                                 |
| sqlglot_parse           | 1.43 ms                                                | 1.34 ms: 1.07x faster                                                 |
| pycparser               | 1.20 sec                                               | 1.12 sec: 1.07x faster                                                |
| logging_format          | 6.83 us                                                | 6.38 us: 1.07x faster                                                 |
| docutils                | 2.69 sec                                               | 2.52 sec: 1.07x faster                                                |
| 2to3                    | 266 ms                                                 | 249 ms: 1.07x faster                                                  |
| bench_thread_pool       | 833 us                                                 | 780 us: 1.07x faster                                                  |
| chaos                   | 71.4 ms                                                | 67.1 ms: 1.06x faster                                                 |
| unpickle_list           | 5.22 us                                                | 4.91 us: 1.06x faster                                                 |
| genshi_text             | 22.8 ms                                                | 21.5 ms: 1.06x faster                                                 |
| coroutines              | 26.1 ms                                                | 24.7 ms: 1.06x faster                                                 |
| xml_etree_generate      | 80.4 ms                                                | 76.0 ms: 1.06x faster                                                 |
| xml_etree_process       | 56.5 ms                                                | 53.4 ms: 1.06x faster                                                 |
| sympy_str               | 299 ms                                                 | 283 ms: 1.06x faster                                                  |
| go                      | 143 ms                                                 | 135 ms: 1.06x faster                                                  |
| chameleon               | 6.86 ms                                                | 6.51 ms: 1.05x faster                                                 |
| unpickle                | 13.9 us                                                | 13.2 us: 1.05x faster                                                 |
| pyflate                 | 426 ms                                                 | 407 ms: 1.05x faster                                                  |
| meteor_contest          | 109 ms                                                 | 104 ms: 1.05x faster                                                  |
| sympy_integrate         | 21.4 ms                                                | 20.4 ms: 1.04x faster                                                 |
| pylint                  | 478 ms                                                 | 458 ms: 1.04x faster                                                  |
| tornado_http            | 97.7 ms                                                | 93.7 ms: 1.04x faster                                                 |
| dulwich_log             | 64.9 ms                                                | 62.4 ms: 1.04x faster                                                 |
| sympy_sum               | 170 ms                                                 | 164 ms: 1.04x faster                                                  |
| crypto_pyaes            | 77.5 ms                                                | 74.8 ms: 1.04x faster                                                 |
| scimark_lu              | 112 ms                                                 | 108 ms: 1.04x faster                                                  |
| thrift                  | 772 us                                                 | 746 us: 1.03x faster                                                  |
| python_startup          | 8.69 ms                                                | 8.42 ms: 1.03x faster                                                 |
| generators              | 76.5 ms                                                | 74.1 ms: 1.03x faster                                                 |
| pathlib                 | 18.5 ms                                                | 17.9 ms: 1.03x faster                                                 |
| async_tree_cpu_io_mixed | 750 ms                                                 | 730 ms: 1.03x faster                                                  |
| python_startup_no_site  | 6.09 ms                                                | 5.93 ms: 1.03x faster                                                 |
| telco                   | 6.72 ms                                                | 6.55 ms: 1.02x faster                                                 |
| django_template         | 33.8 ms                                                | 33.0 ms: 1.02x faster                                                 |
| regex_effbot            | 3.45 ms                                                | 3.37 ms: 1.02x faster                                                 |
| djangocms               | 33.1 us                                                | 32.5 us: 1.02x faster                                                 |
| regex_dna               | 204 ms                                                 | 201 ms: 1.01x faster                                                  |
| create_gc_cycles        | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                 |
| dask                    | 365 ms                                                 | 360 ms: 1.01x faster                                                  |
| asyncio_tcp             | 887 ms                                                 | 890 ms: 1.00x slower                                                  |
| async_tree_io           | 1.31 sec                                               | 1.33 sec: 1.01x slower                                                |
| sqlite_synth            | 2.58 us                                                | 2.62 us: 1.02x slower                                                 |
| unpack_sequence         | 43.3 ns                                                | 44.1 ns: 1.02x slower                                                 |
| async_tree_memoization  | 640 ms                                                 | 656 ms: 1.02x slower                                                  |
| pidigits                | 190 ms                                                 | 198 ms: 1.04x slower                                                  |
| nbody                   | 91.6 ms                                                | 96.6 ms: 1.06x slower                                                 |
| coverage                | 81.2 ms                                                | 102 ms: 1.25x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.07x faster                                                          |

Benchmark hidden because not significant (2): async_tree_none, bench_mp_pool
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
