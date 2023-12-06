
# Results vs. 3.11.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: linux-x86_64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 245 ms: 1.08x faster                                                  |
| chameleon      | 6.86 ms                                                | 6.30 ms: 1.09x faster                                                 |
| docutils       | 2.69 sec                                               | 2.50 sec: 1.08x faster                                                |
| html5lib       | 65.0 ms                                                | 58.9 ms: 1.10x faster                                                 |
| tornado_http   | 97.7 ms                                                | 93.1 ms: 1.05x faster                                                 |
| Geometric mean | (ref)                                                  | 1.08x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 750 ms                                                 | 730 ms: 1.03x faster                                                  |
| async_tree_io           | 1.31 sec                                               | 1.32 sec: 1.01x slower                                                |
| async_tree_memoization  | 640 ms                                                 | 653 ms: 1.02x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.00x faster                                                          |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 78.9 ms                                                | 72.0 ms: 1.10x faster                                                 |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| nbody          | 91.6 ms                                                | 93.9 ms: 1.03x slower                                                 |
| Geometric mean | (ref)                                                  | 1.02x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 127 ms: 1.11x faster                                                  |
| regex_v8       | 22.9 ms                                                | 21.1 ms: 1.09x faster                                                 |
| regex_effbot   | 3.45 ms                                                | 3.47 ms: 1.01x slower                                                 |
| regex_dna      | 204 ms                                                 | 208 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps           | 13.5 ms                                                | 9.66 ms: 1.39x faster                                                 |
| json_loads           | 29.4 us                                                | 23.9 us: 1.23x faster                                                 |
| unpickle_pure_python | 241 us                                                 | 200 us: 1.21x faster                                                  |
| pickle_list          | 4.65 us                                                | 4.06 us: 1.14x faster                                                 |
| pickle_dict          | 34.8 us                                                | 30.8 us: 1.13x faster                                                 |
| pickle_pure_python   | 319 us                                                 | 283 us: 1.13x faster                                                  |
| pickle               | 11.1 us                                                | 9.88 us: 1.12x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 149 ms: 1.09x faster                                                  |
| unpickle             | 13.9 us                                                | 12.9 us: 1.07x faster                                                 |
| xml_etree_iterparse  | 109 ms                                                 | 103 ms: 1.05x faster                                                  |
| unpickle_list        | 5.22 us                                                | 4.98 us: 1.05x faster                                                 |
| xml_etree_process    | 56.5 ms                                                | 53.9 ms: 1.05x faster                                                 |
| xml_etree_generate   | 80.4 ms                                                | 77.2 ms: 1.04x faster                                                 |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.58 ms: 1.01x faster                                                 |
| python_startup_no_site | 6.09 ms                                                | 6.12 ms: 1.00x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.00x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.39 ms: 1.15x faster                                                 |
| genshi_xml      | 54.1 ms                                                | 47.0 ms: 1.15x faster                                                 |
| genshi_text     | 22.8 ms                                                | 20.2 ms: 1.13x faster                                                 |
| django_template | 33.8 ms                                                | 32.8 ms: 1.03x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.11x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| json_dumps              | 13.5 ms                                                | 9.66 ms: 1.39x faster                                                 |
| mypy2                   | 427 ms                                                 | 325 ms: 1.31x faster                                                  |
| json_loads              | 29.4 us                                                | 23.9 us: 1.23x faster                                                 |
| unpickle_pure_python    | 241 us                                                 | 200 us: 1.21x faster                                                  |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.00 ms: 1.20x faster                                                 |
| deltablue               | 3.80 ms                                                | 3.22 ms: 1.18x faster                                                 |
| richards                | 48.9 ms                                                | 41.8 ms: 1.17x faster                                                 |
| logging_silent          | 108 ns                                                 | 93.4 ns: 1.16x faster                                                 |
| scimark_sor             | 121 ms                                                 | 105 ms: 1.16x faster                                                  |
| deepcopy_memo           | 38.9 us                                                | 33.6 us: 1.16x faster                                                 |
| mako                    | 10.8 ms                                                | 9.39 ms: 1.15x faster                                                 |
| genshi_xml              | 54.1 ms                                                | 47.0 ms: 1.15x faster                                                 |
| pickle_list             | 4.65 us                                                | 4.06 us: 1.14x faster                                                 |
| pickle_dict             | 34.8 us                                                | 30.8 us: 1.13x faster                                                 |
| genshi_text             | 22.8 ms                                                | 20.2 ms: 1.13x faster                                                 |
| json                    | 5.24 ms                                                | 4.65 ms: 1.13x faster                                                 |
| pickle_pure_python      | 319 us                                                 | 283 us: 1.13x faster                                                  |
| mdp                     | 2.79 sec                                               | 2.48 sec: 1.12x faster                                                |
| pickle                  | 11.1 us                                                | 9.88 us: 1.12x faster                                                 |
| aiohttp                 | 1.12 ms                                                | 999 us: 1.12x faster                                                  |
| hexiom                  | 6.74 ms                                                | 6.04 ms: 1.12x faster                                                 |
| regex_compile           | 141 ms                                                 | 127 ms: 1.11x faster                                                  |
| fannkuch                | 410 ms                                                 | 369 ms: 1.11x faster                                                  |
| pycparser               | 1.20 sec                                               | 1.08 sec: 1.11x faster                                                |
| scimark_fft             | 342 ms                                                 | 309 ms: 1.11x faster                                                  |
| gunicorn                | 1.20 ms                                                | 1.08 ms: 1.11x faster                                                 |
| spectral_norm           | 105 ms                                                 | 94.9 ms: 1.11x faster                                                 |
| raytrace                | 306 ms                                                 | 277 ms: 1.11x faster                                                  |
| html5lib                | 65.0 ms                                                | 58.9 ms: 1.10x faster                                                 |
| deepcopy                | 360 us                                                 | 328 us: 1.10x faster                                                  |
| pprint_pformat          | 1.53 sec                                               | 1.39 sec: 1.10x faster                                                |
| logging_simple          | 6.24 us                                                | 5.70 us: 1.10x faster                                                 |
| float                   | 78.9 ms                                                | 72.0 ms: 1.10x faster                                                 |
| xml_etree_parse         | 163 ms                                                 | 149 ms: 1.09x faster                                                  |
| chameleon               | 6.86 ms                                                | 6.30 ms: 1.09x faster                                                 |
| regex_v8                | 22.9 ms                                                | 21.1 ms: 1.09x faster                                                 |
| deepcopy_reduce         | 3.14 us                                                | 2.89 us: 1.09x faster                                                 |
| sqlglot_transpile       | 1.75 ms                                                | 1.62 ms: 1.09x faster                                                 |
| chaos                   | 71.4 ms                                                | 65.8 ms: 1.08x faster                                                 |
| pprint_safe_repr        | 743 ms                                                 | 685 ms: 1.08x faster                                                  |
| 2to3                    | 266 ms                                                 | 245 ms: 1.08x faster                                                  |
| logging_format          | 6.83 us                                                | 6.30 us: 1.08x faster                                                 |
| sqlglot_optimize        | 55.2 ms                                                | 51.0 ms: 1.08x faster                                                 |
| sqlglot_parse           | 1.43 ms                                                | 1.33 ms: 1.08x faster                                                 |
| docutils                | 2.69 sec                                               | 2.50 sec: 1.08x faster                                                |
| sympy_expand            | 490 ms                                                 | 456 ms: 1.07x faster                                                  |
| unpickle                | 13.9 us                                                | 12.9 us: 1.07x faster                                                 |
| nqueens                 | 86.8 ms                                                | 81.1 ms: 1.07x faster                                                 |
| meteor_contest          | 109 ms                                                 | 102 ms: 1.07x faster                                                  |
| bench_thread_pool       | 833 us                                                 | 780 us: 1.07x faster                                                  |
| sqlglot_normalize       | 112 ms                                                 | 105 ms: 1.07x faster                                                  |
| go                      | 143 ms                                                 | 135 ms: 1.06x faster                                                  |
| sympy_str               | 299 ms                                                 | 282 ms: 1.06x faster                                                  |
| pyflate                 | 426 ms                                                 | 402 ms: 1.06x faster                                                  |
| async_generators        | 375 ms                                                 | 355 ms: 1.06x faster                                                  |
| coroutines              | 26.1 ms                                                | 24.7 ms: 1.06x faster                                                 |
| scimark_monte_carlo     | 71.8 ms                                                | 68.0 ms: 1.06x faster                                                 |
| xml_etree_iterparse     | 109 ms                                                 | 103 ms: 1.05x faster                                                  |
| telco                   | 6.72 ms                                                | 6.38 ms: 1.05x faster                                                 |
| dulwich_log             | 64.9 ms                                                | 61.8 ms: 1.05x faster                                                 |
| tornado_http            | 97.7 ms                                                | 93.1 ms: 1.05x faster                                                 |
| sympy_integrate         | 21.4 ms                                                | 20.4 ms: 1.05x faster                                                 |
| unpickle_list           | 5.22 us                                                | 4.98 us: 1.05x faster                                                 |
| xml_etree_process       | 56.5 ms                                                | 53.9 ms: 1.05x faster                                                 |
| xml_etree_generate      | 80.4 ms                                                | 77.2 ms: 1.04x faster                                                 |
| pathlib                 | 18.5 ms                                                | 17.7 ms: 1.04x faster                                                 |
| scimark_lu              | 112 ms                                                 | 108 ms: 1.04x faster                                                  |
| crypto_pyaes            | 77.5 ms                                                | 74.6 ms: 1.04x faster                                                 |
| gc_traversal            | 3.90 ms                                                | 3.77 ms: 1.03x faster                                                 |
| sympy_sum               | 170 ms                                                 | 165 ms: 1.03x faster                                                  |
| thrift                  | 772 us                                                 | 748 us: 1.03x faster                                                  |
| django_template         | 33.8 ms                                                | 32.8 ms: 1.03x faster                                                 |
| async_tree_cpu_io_mixed | 750 ms                                                 | 730 ms: 1.03x faster                                                  |
| djangocms               | 33.1 us                                                | 32.5 us: 1.02x faster                                                 |
| create_gc_cycles        | 1.48 ms                                                | 1.46 ms: 1.01x faster                                                 |
| dask                    | 365 ms                                                 | 360 ms: 1.01x faster                                                  |
| python_startup          | 8.69 ms                                                | 8.58 ms: 1.01x faster                                                 |
| pidigits                | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| comprehensions          | 23.6 us                                                | 23.4 us: 1.00x faster                                                 |
| asyncio_tcp             | 887 ms                                                 | 884 ms: 1.00x faster                                                  |
| python_startup_no_site  | 6.09 ms                                                | 6.12 ms: 1.00x slower                                                 |
| regex_effbot            | 3.45 ms                                                | 3.47 ms: 1.01x slower                                                 |
| async_tree_io           | 1.31 sec                                               | 1.32 sec: 1.01x slower                                                |
| sqlite_synth            | 2.58 us                                                | 2.60 us: 1.01x slower                                                 |
| generators              | 76.5 ms                                                | 77.4 ms: 1.01x slower                                                 |
| regex_dna               | 204 ms                                                 | 208 ms: 1.02x slower                                                  |
| async_tree_memoization  | 640 ms                                                 | 653 ms: 1.02x slower                                                  |
| nbody                   | 91.6 ms                                                | 93.9 ms: 1.03x slower                                                 |
| unpack_sequence         | 43.3 ns                                                | 45.7 ns: 1.06x slower                                                 |
| coverage                | 81.2 ms                                                | 101 ms: 1.24x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.07x faster                                                          |

Benchmark hidden because not significant (2): async_tree_none, bench_mp_pool
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
