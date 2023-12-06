
# Results vs. 3.11.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: linux-x86_64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 253 ms: 1.05x faster                                                  |
| chameleon      | 6.86 ms                                                | 6.46 ms: 1.06x faster                                                 |
| docutils       | 2.69 sec                                               | 2.48 sec: 1.08x faster                                                |
| html5lib       | 65.0 ms                                                | 59.8 ms: 1.09x faster                                                 |
| Geometric mean | (ref)                                                  | 1.07x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization | 640 ms                                                 | 616 ms: 1.04x faster                                                  |
| async_tree_none        | 532 ms                                                 | 521 ms: 1.02x faster                                                  |
| async_tree_io          | 1.31 sec                                               | 1.30 sec: 1.01x faster                                                |
| Geometric mean         | (ref)                                                  | 1.02x faster                                                          |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 78.9 ms                                                | 72.2 ms: 1.09x faster                                                 |
| pidigits       | 190 ms                                                 | 192 ms: 1.01x slower                                                  |
| nbody          | 91.6 ms                                                | 93.1 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_v8       | 22.9 ms                                                | 21.1 ms: 1.09x faster                                                 |
| regex_compile  | 141 ms                                                 | 132 ms: 1.07x faster                                                  |
| regex_effbot   | 3.45 ms                                                | 3.49 ms: 1.01x slower                                                 |
| regex_dna      | 204 ms                                                 | 209 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.54 ms: 1.41x faster                                                 |
| json_loads           | 29.4 us                                                | 24.3 us: 1.21x faster                                                 |
| unpickle_pure_python | 241 us                                                 | 200 us: 1.21x faster                                                  |
| pickle_dict          | 34.8 us                                                | 30.0 us: 1.16x faster                                                 |
| pickle_list          | 4.65 us                                                | 4.02 us: 1.16x faster                                                 |
| pickle_pure_python   | 319 us                                                 | 285 us: 1.12x faster                                                  |
| pickle               | 11.1 us                                                | 10.0 us: 1.11x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 149 ms: 1.09x faster                                                  |
| unpickle             | 13.9 us                                                | 13.0 us: 1.07x faster                                                 |
| unpickle_list        | 5.22 us                                                | 4.96 us: 1.05x faster                                                 |
| xml_etree_process    | 56.5 ms                                                | 53.9 ms: 1.05x faster                                                 |
| xml_etree_generate   | 80.4 ms                                                | 77.5 ms: 1.04x faster                                                 |
| xml_etree_iterparse  | 109 ms                                                 | 106 ms: 1.02x faster                                                  |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.54 ms: 1.02x faster                                                 |
| python_startup_no_site | 6.09 ms                                                | 6.09 ms: 1.00x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| genshi_xml      | 54.1 ms                                                | 46.5 ms: 1.16x faster                                                 |
| mako            | 10.8 ms                                                | 9.74 ms: 1.11x faster                                                 |
| genshi_text     | 22.8 ms                                                | 20.8 ms: 1.10x faster                                                 |
| django_template | 33.8 ms                                                | 32.6 ms: 1.04x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.10x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| asyncio_tcp             | 887 ms                                                 | 504 ms: 1.76x faster                                                  |
| json_dumps              | 13.5 ms                                                | 9.54 ms: 1.41x faster                                                 |
| mypy2                   | 427 ms                                                 | 332 ms: 1.29x faster                                                  |
| json_loads              | 29.4 us                                                | 24.3 us: 1.21x faster                                                 |
| unpickle_pure_python    | 241 us                                                 | 200 us: 1.21x faster                                                  |
| deltablue               | 3.80 ms                                                | 3.25 ms: 1.17x faster                                                 |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.13 ms: 1.16x faster                                                 |
| genshi_xml              | 54.1 ms                                                | 46.5 ms: 1.16x faster                                                 |
| pickle_dict             | 34.8 us                                                | 30.0 us: 1.16x faster                                                 |
| logging_silent          | 108 ns                                                 | 93.5 ns: 1.16x faster                                                 |
| pickle_list             | 4.65 us                                                | 4.02 us: 1.16x faster                                                 |
| richards                | 48.9 ms                                                | 42.3 ms: 1.15x faster                                                 |
| fannkuch                | 410 ms                                                 | 362 ms: 1.13x faster                                                  |
| hexiom                  | 6.74 ms                                                | 5.98 ms: 1.13x faster                                                 |
| deepcopy_memo           | 38.9 us                                                | 34.7 us: 1.12x faster                                                 |
| scimark_sor             | 121 ms                                                 | 108 ms: 1.12x faster                                                  |
| pickle_pure_python      | 319 us                                                 | 285 us: 1.12x faster                                                  |
| nqueens                 | 86.8 ms                                                | 78.0 ms: 1.11x faster                                                 |
| mako                    | 10.8 ms                                                | 9.74 ms: 1.11x faster                                                 |
| pickle                  | 11.1 us                                                | 10.0 us: 1.11x faster                                                 |
| spectral_norm           | 105 ms                                                 | 95.0 ms: 1.11x faster                                                 |
| pycparser               | 1.20 sec                                               | 1.08 sec: 1.11x faster                                                |
| pprint_pformat          | 1.53 sec                                               | 1.38 sec: 1.10x faster                                                |
| json                    | 5.24 ms                                                | 4.74 ms: 1.10x faster                                                 |
| genshi_text             | 22.8 ms                                                | 20.8 ms: 1.10x faster                                                 |
| gc_traversal            | 3.90 ms                                                | 3.57 ms: 1.09x faster                                                 |
| scimark_monte_carlo     | 71.8 ms                                                | 65.7 ms: 1.09x faster                                                 |
| float                   | 78.9 ms                                                | 72.2 ms: 1.09x faster                                                 |
| pprint_safe_repr        | 743 ms                                                 | 680 ms: 1.09x faster                                                  |
| xml_etree_parse         | 163 ms                                                 | 149 ms: 1.09x faster                                                  |
| scimark_fft             | 342 ms                                                 | 314 ms: 1.09x faster                                                  |
| sqlglot_optimize        | 55.2 ms                                                | 50.7 ms: 1.09x faster                                                 |
| html5lib                | 65.0 ms                                                | 59.8 ms: 1.09x faster                                                 |
| regex_v8                | 22.9 ms                                                | 21.1 ms: 1.09x faster                                                 |
| docutils                | 2.69 sec                                               | 2.48 sec: 1.08x faster                                                |
| logging_simple          | 6.24 us                                                | 5.77 us: 1.08x faster                                                 |
| sqlglot_normalize       | 112 ms                                                 | 104 ms: 1.08x faster                                                  |
| raytrace                | 306 ms                                                 | 284 ms: 1.08x faster                                                  |
| sympy_expand            | 490 ms                                                 | 455 ms: 1.08x faster                                                  |
| logging_format          | 6.83 us                                                | 6.35 us: 1.07x faster                                                 |
| pyflate                 | 426 ms                                                 | 397 ms: 1.07x faster                                                  |
| regex_compile           | 141 ms                                                 | 132 ms: 1.07x faster                                                  |
| telco                   | 6.72 ms                                                | 6.26 ms: 1.07x faster                                                 |
| unpickle                | 13.9 us                                                | 13.0 us: 1.07x faster                                                 |
| djangocms               | 33.1 us                                                | 30.9 us: 1.07x faster                                                 |
| bench_thread_pool       | 833 us                                                 | 782 us: 1.07x faster                                                  |
| deepcopy                | 360 us                                                 | 339 us: 1.06x faster                                                  |
| chameleon               | 6.86 ms                                                | 6.46 ms: 1.06x faster                                                 |
| sympy_str               | 299 ms                                                 | 282 ms: 1.06x faster                                                  |
| async_generators        | 375 ms                                                 | 354 ms: 1.06x faster                                                  |
| go                      | 143 ms                                                 | 135 ms: 1.06x faster                                                  |
| chaos                   | 71.4 ms                                                | 67.7 ms: 1.05x faster                                                 |
| 2to3                    | 266 ms                                                 | 253 ms: 1.05x faster                                                  |
| unpickle_list           | 5.22 us                                                | 4.96 us: 1.05x faster                                                 |
| sympy_integrate         | 21.4 ms                                                | 20.3 ms: 1.05x faster                                                 |
| deepcopy_reduce         | 3.14 us                                                | 2.99 us: 1.05x faster                                                 |
| mdp                     | 2.79 sec                                               | 2.66 sec: 1.05x faster                                                |
| xml_etree_process       | 56.5 ms                                                | 53.9 ms: 1.05x faster                                                 |
| dulwich_log             | 64.9 ms                                                | 62.1 ms: 1.05x faster                                                 |
| sympy_sum               | 170 ms                                                 | 163 ms: 1.05x faster                                                  |
| scimark_lu              | 112 ms                                                 | 107 ms: 1.05x faster                                                  |
| unpack_sequence         | 43.3 ns                                                | 41.4 ns: 1.05x faster                                                 |
| meteor_contest          | 109 ms                                                 | 104 ms: 1.05x faster                                                  |
| async_tree_memoization  | 640 ms                                                 | 616 ms: 1.04x faster                                                  |
| xml_etree_generate      | 80.4 ms                                                | 77.5 ms: 1.04x faster                                                 |
| django_template         | 33.8 ms                                                | 32.6 ms: 1.04x faster                                                 |
| sqlglot_transpile       | 1.75 ms                                                | 1.69 ms: 1.04x faster                                                 |
| coroutines              | 26.1 ms                                                | 25.4 ms: 1.03x faster                                                 |
| dask                    | 365 ms                                                 | 355 ms: 1.03x faster                                                  |
| thrift                  | 772 us                                                 | 752 us: 1.03x faster                                                  |
| pathlib                 | 18.5 ms                                                | 18.0 ms: 1.02x faster                                                 |
| crypto_pyaes            | 77.5 ms                                                | 75.7 ms: 1.02x faster                                                 |
| async_tree_none         | 532 ms                                                 | 521 ms: 1.02x faster                                                  |
| xml_etree_iterparse     | 109 ms                                                 | 106 ms: 1.02x faster                                                  |
| sqlglot_parse           | 1.43 ms                                                | 1.41 ms: 1.02x faster                                                 |
| python_startup          | 8.69 ms                                                | 8.54 ms: 1.02x faster                                                 |
| create_gc_cycles        | 1.48 ms                                                | 1.45 ms: 1.02x faster                                                 |
| async_tree_io           | 1.31 sec                                               | 1.30 sec: 1.01x faster                                                |
| python_startup_no_site  | 6.09 ms                                                | 6.09 ms: 1.00x faster                                                 |
| comprehensions          | 23.6 us                                                | 23.7 us: 1.01x slower                                                 |
| pidigits                | 190 ms                                                 | 192 ms: 1.01x slower                                                  |
| regex_effbot            | 3.45 ms                                                | 3.49 ms: 1.01x slower                                                 |
| nbody                   | 91.6 ms                                                | 93.1 ms: 1.02x slower                                                 |
| regex_dna               | 204 ms                                                 | 209 ms: 1.02x slower                                                  |
| generators              | 76.5 ms                                                | 79.1 ms: 1.03x slower                                                 |
| coverage                | 81.2 ms                                                | 99.0 ms: 1.22x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.08x faster                                                          |

Benchmark hidden because not significant (3): sqlite_synth, async_tree_cpu_io_mixed, bench_mp_pool
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
