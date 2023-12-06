
# Results vs. 3.11.0

- fork: python
- ref: v3.11.0b3
- machine: linux-x86_64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.04x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 256 ms: 1.04x faster                                       |
| chameleon      | 6.86 ms                                                | 6.42 ms: 1.07x faster                                      |
| docutils       | 2.69 sec                                               | 2.56 sec: 1.05x faster                                     |
| html5lib       | 65.0 ms                                                | 62.8 ms: 1.04x faster                                      |
| tornado_http   | 97.7 ms                                                | 94.7 ms: 1.03x faster                                      |
| Geometric mean | (ref)                                                  | 1.04x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_cpu_io_mixed | 750 ms                                                 | 735 ms: 1.02x faster                                       |
| async_tree_none         | 532 ms                                                 | 525 ms: 1.01x faster                                       |
| Geometric mean          | (ref)                                                  | 1.01x faster                                               |

Benchmark hidden because not significant (2): async_tree_memoization, async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 78.9 ms                                                | 73.9 ms: 1.07x faster                                      |
| pidigits       | 190 ms                                                 | 194 ms: 1.02x slower                                       |
| nbody          | 91.6 ms                                                | 94.9 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                  | 1.00x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 2.92 ms: 1.18x faster                                      |
| regex_v8       | 22.9 ms                                                | 21.4 ms: 1.07x faster                                      |
| regex_dna      | 204 ms                                                 | 194 ms: 1.05x faster                                       |
| regex_compile  | 141 ms                                                 | 136 ms: 1.04x faster                                       |
| Geometric mean | (ref)                                                  | 1.08x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 26.0 us: 1.34x faster                                      |
| json_loads           | 29.4 us                                                | 24.9 us: 1.18x faster                                      |
| pickle               | 11.1 us                                                | 9.37 us: 1.18x faster                                      |
| pickle_list          | 4.65 us                                                | 4.27 us: 1.09x faster                                      |
| json_dumps           | 13.5 ms                                                | 12.7 ms: 1.06x faster                                      |
| unpickle_pure_python | 241 us                                                 | 227 us: 1.06x faster                                       |
| pickle_pure_python   | 319 us                                                 | 301 us: 1.06x faster                                       |
| xml_etree_process    | 56.5 ms                                                | 53.6 ms: 1.05x faster                                      |
| unpickle_list        | 5.22 us                                                | 4.96 us: 1.05x faster                                      |
| xml_etree_generate   | 80.4 ms                                                | 76.7 ms: 1.05x faster                                      |
| unpickle             | 13.9 us                                                | 13.3 us: 1.04x faster                                      |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                       |
| xml_etree_iterparse  | 109 ms                                                 | 108 ms: 1.01x faster                                       |
| Geometric mean       | (ref)                                                  | 1.09x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.51 ms: 1.02x faster                                      |
| python_startup_no_site | 6.09 ms                                                | 6.01 ms: 1.01x faster                                      |
| Geometric mean         | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.99 ms: 1.08x faster                                      |
| genshi_xml      | 54.1 ms                                                | 52.3 ms: 1.03x faster                                      |
| genshi_text     | 22.8 ms                                                | 22.0 ms: 1.03x faster                                      |
| django_template | 33.8 ms                                                | 33.0 ms: 1.02x faster                                      |
| Geometric mean  | (ref)                                                  | 1.04x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict             | 34.8 us                                                | 26.0 us: 1.34x faster                                      |
| json_loads              | 29.4 us                                                | 24.9 us: 1.18x faster                                      |
| pickle                  | 11.1 us                                                | 9.37 us: 1.18x faster                                      |
| regex_effbot            | 3.45 ms                                                | 2.92 ms: 1.18x faster                                      |
| json                    | 5.24 ms                                                | 4.74 ms: 1.10x faster                                      |
| pickle_list             | 4.65 us                                                | 4.27 us: 1.09x faster                                      |
| mako                    | 10.8 ms                                                | 9.99 ms: 1.08x faster                                      |
| richards                | 48.9 ms                                                | 45.3 ms: 1.08x faster                                      |
| spectral_norm           | 105 ms                                                 | 97.5 ms: 1.08x faster                                      |
| scimark_monte_carlo     | 71.8 ms                                                | 66.6 ms: 1.08x faster                                      |
| logging_format          | 6.83 us                                                | 6.35 us: 1.07x faster                                      |
| logging_simple          | 6.24 us                                                | 5.82 us: 1.07x faster                                      |
| logging_silent          | 108 ns                                                 | 101 ns: 1.07x faster                                       |
| pprint_safe_repr        | 743 ms                                                 | 694 ms: 1.07x faster                                       |
| chameleon               | 6.86 ms                                                | 6.42 ms: 1.07x faster                                      |
| float                   | 78.9 ms                                                | 73.9 ms: 1.07x faster                                      |
| regex_v8                | 22.9 ms                                                | 21.4 ms: 1.07x faster                                      |
| gunicorn                | 1.20 ms                                                | 1.12 ms: 1.06x faster                                      |
| json_dumps              | 13.5 ms                                                | 12.7 ms: 1.06x faster                                      |
| scimark_sor             | 121 ms                                                 | 114 ms: 1.06x faster                                       |
| unpickle_pure_python    | 241 us                                                 | 227 us: 1.06x faster                                       |
| deepcopy                | 360 us                                                 | 340 us: 1.06x faster                                       |
| pickle_pure_python      | 319 us                                                 | 301 us: 1.06x faster                                       |
| hexiom                  | 6.74 ms                                                | 6.36 ms: 1.06x faster                                      |
| async_generators        | 375 ms                                                 | 356 ms: 1.06x faster                                       |
| pprint_pformat          | 1.53 sec                                               | 1.45 sec: 1.06x faster                                     |
| xml_etree_process       | 56.5 ms                                                | 53.6 ms: 1.05x faster                                      |
| deepcopy_memo           | 38.9 us                                                | 36.9 us: 1.05x faster                                      |
| unpickle_list           | 5.22 us                                                | 4.96 us: 1.05x faster                                      |
| sympy_sum               | 170 ms                                                 | 162 ms: 1.05x faster                                       |
| aiohttp                 | 1.12 ms                                                | 1.06 ms: 1.05x faster                                      |
| regex_dna               | 204 ms                                                 | 194 ms: 1.05x faster                                       |
| crypto_pyaes            | 77.5 ms                                                | 73.6 ms: 1.05x faster                                      |
| deepcopy_reduce         | 3.14 us                                                | 2.98 us: 1.05x faster                                      |
| docutils                | 2.69 sec                                               | 2.56 sec: 1.05x faster                                     |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.57 ms: 1.05x faster                                      |
| sympy_str               | 299 ms                                                 | 285 ms: 1.05x faster                                       |
| xml_etree_generate      | 80.4 ms                                                | 76.7 ms: 1.05x faster                                      |
| raytrace                | 306 ms                                                 | 292 ms: 1.05x faster                                       |
| chaos                   | 71.4 ms                                                | 68.2 ms: 1.05x faster                                      |
| scimark_lu              | 112 ms                                                 | 107 ms: 1.05x faster                                       |
| sympy_expand            | 490 ms                                                 | 469 ms: 1.04x faster                                       |
| fannkuch                | 410 ms                                                 | 393 ms: 1.04x faster                                       |
| scimark_fft             | 342 ms                                                 | 328 ms: 1.04x faster                                       |
| pyflate                 | 426 ms                                                 | 409 ms: 1.04x faster                                       |
| deltablue               | 3.80 ms                                                | 3.65 ms: 1.04x faster                                      |
| unpickle                | 13.9 us                                                | 13.3 us: 1.04x faster                                      |
| meteor_contest          | 109 ms                                                 | 105 ms: 1.04x faster                                       |
| regex_compile           | 141 ms                                                 | 136 ms: 1.04x faster                                       |
| 2to3                    | 266 ms                                                 | 256 ms: 1.04x faster                                       |
| generators              | 76.5 ms                                                | 73.8 ms: 1.04x faster                                      |
| nqueens                 | 86.8 ms                                                | 83.8 ms: 1.04x faster                                      |
| mdp                     | 2.79 sec                                               | 2.69 sec: 1.04x faster                                     |
| html5lib                | 65.0 ms                                                | 62.8 ms: 1.04x faster                                      |
| genshi_xml              | 54.1 ms                                                | 52.3 ms: 1.03x faster                                      |
| genshi_text             | 22.8 ms                                                | 22.0 ms: 1.03x faster                                      |
| tornado_http            | 97.7 ms                                                | 94.7 ms: 1.03x faster                                      |
| sympy_integrate         | 21.4 ms                                                | 20.7 ms: 1.03x faster                                      |
| dulwich_log             | 64.9 ms                                                | 63.0 ms: 1.03x faster                                      |
| gc_traversal            | 3.90 ms                                                | 3.79 ms: 1.03x faster                                      |
| sqlglot_normalize       | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| pylint                  | 478 ms                                                 | 465 ms: 1.03x faster                                       |
| xml_etree_parse         | 163 ms                                                 | 158 ms: 1.03x faster                                       |
| go                      | 143 ms                                                 | 139 ms: 1.03x faster                                       |
| sqlalchemy_declarative  | 141 ms                                                 | 137 ms: 1.03x faster                                       |
| flaskblogging           | 7.20 ms                                                | 7.04 ms: 1.02x faster                                      |
| django_template         | 33.8 ms                                                | 33.0 ms: 1.02x faster                                      |
| bench_thread_pool       | 833 us                                                 | 816 us: 1.02x faster                                       |
| sqlglot_optimize        | 55.2 ms                                                | 54.0 ms: 1.02x faster                                      |
| sqlalchemy_imperative   | 18.2 ms                                                | 17.8 ms: 1.02x faster                                      |
| python_startup          | 8.69 ms                                                | 8.51 ms: 1.02x faster                                      |
| async_tree_cpu_io_mixed | 750 ms                                                 | 735 ms: 1.02x faster                                       |
| telco                   | 6.72 ms                                                | 6.59 ms: 1.02x faster                                      |
| sqlite_synth            | 2.58 us                                                | 2.53 us: 1.02x faster                                      |
| pathlib                 | 18.5 ms                                                | 18.1 ms: 1.02x faster                                      |
| pycparser               | 1.20 sec                                               | 1.18 sec: 1.02x faster                                     |
| python_startup_no_site  | 6.09 ms                                                | 6.01 ms: 1.01x faster                                      |
| async_tree_none         | 532 ms                                                 | 525 ms: 1.01x faster                                       |
| thrift                  | 772 us                                                 | 763 us: 1.01x faster                                       |
| xml_etree_iterparse     | 109 ms                                                 | 108 ms: 1.01x faster                                       |
| coroutines              | 26.1 ms                                                | 26.0 ms: 1.00x faster                                      |
| dask                    | 365 ms                                                 | 368 ms: 1.01x slower                                       |
| pidigits                | 190 ms                                                 | 194 ms: 1.02x slower                                       |
| create_gc_cycles        | 1.48 ms                                                | 1.51 ms: 1.02x slower                                      |
| nbody                   | 91.6 ms                                                | 94.9 ms: 1.04x slower                                      |
| comprehensions          | 23.6 us                                                | 25.9 us: 1.10x slower                                      |
| unpack_sequence         | 43.3 ns                                                | 48.0 ns: 1.11x slower                                      |
| sqlglot_transpile       | 1.75 ms                                                | 2.04 ms: 1.16x slower                                      |
| sqlglot_parse           | 1.43 ms                                                | 1.75 ms: 1.22x slower                                      |
| Geometric mean          | (ref)                                                  | 1.04x faster                                               |

Benchmark hidden because not significant (6): mypy2, async_tree_memoization, async_tree_io, bench_mp_pool, asyncio_tcp, djangocms
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
