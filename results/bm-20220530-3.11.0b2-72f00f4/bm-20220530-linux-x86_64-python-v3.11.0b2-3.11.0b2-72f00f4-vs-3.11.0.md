
# Results vs. 3.11.0

- fork: python
- ref: v3.11.0b2
- machine: linux-x86_64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.04x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 256 ms: 1.04x faster                                       |
| chameleon      | 6.86 ms                                                | 6.62 ms: 1.04x faster                                      |
| docutils       | 2.69 sec                                               | 2.56 sec: 1.05x faster                                     |
| html5lib       | 65.0 ms                                                | 63.7 ms: 1.02x faster                                      |
| tornado_http   | 97.7 ms                                                | 94.9 ms: 1.03x faster                                      |
| Geometric mean | (ref)                                                  | 1.04x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_memoization  | 640 ms                                                 | 628 ms: 1.02x faster                                       |
| async_tree_none         | 532 ms                                                 | 526 ms: 1.01x faster                                       |
| async_tree_cpu_io_mixed | 750 ms                                                 | 743 ms: 1.01x faster                                       |
| Geometric mean          | (ref)                                                  | 1.01x faster                                               |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 78.9 ms                                                | 74.4 ms: 1.06x faster                                      |
| pidigits       | 190 ms                                                 | 199 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                  | 1.00x faster                                               |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.11 ms: 1.11x faster                                      |
| regex_v8       | 22.9 ms                                                | 22.0 ms: 1.04x faster                                      |
| regex_dna      | 204 ms                                                 | 196 ms: 1.04x faster                                       |
| regex_compile  | 141 ms                                                 | 138 ms: 1.03x faster                                       |
| Geometric mean | (ref)                                                  | 1.05x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 26.4 us: 1.32x faster                                      |
| json_loads           | 29.4 us                                                | 25.0 us: 1.18x faster                                      |
| pickle               | 11.1 us                                                | 9.44 us: 1.17x faster                                      |
| pickle_list          | 4.65 us                                                | 4.30 us: 1.08x faster                                      |
| unpickle_pure_python | 241 us                                                 | 227 us: 1.06x faster                                       |
| xml_etree_process    | 56.5 ms                                                | 53.4 ms: 1.06x faster                                      |
| xml_etree_generate   | 80.4 ms                                                | 76.1 ms: 1.06x faster                                      |
| json_dumps           | 13.5 ms                                                | 12.8 ms: 1.05x faster                                      |
| pickle_pure_python   | 319 us                                                 | 305 us: 1.05x faster                                       |
| unpickle_list        | 5.22 us                                                | 5.00 us: 1.04x faster                                      |
| unpickle             | 13.9 us                                                | 13.3 us: 1.04x faster                                      |
| xml_etree_iterparse  | 109 ms                                                 | 105 ms: 1.03x faster                                       |
| xml_etree_parse      | 163 ms                                                 | 159 ms: 1.03x faster                                       |
| Geometric mean       | (ref)                                                  | 1.09x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.49 ms: 1.02x faster                                      |
| python_startup_no_site | 6.09 ms                                                | 5.99 ms: 1.02x faster                                      |
| Geometric mean         | (ref)                                                  | 1.02x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.96 ms: 1.09x faster                                      |
| genshi_text     | 22.8 ms                                                | 21.5 ms: 1.06x faster                                      |
| django_template | 33.8 ms                                                | 32.6 ms: 1.04x faster                                      |
| genshi_xml      | 54.1 ms                                                | 52.4 ms: 1.03x faster                                      |
| Geometric mean  | (ref)                                                  | 1.05x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_dict             | 34.8 us                                                | 26.4 us: 1.32x faster                                      |
| json_loads              | 29.4 us                                                | 25.0 us: 1.18x faster                                      |
| pickle                  | 11.1 us                                                | 9.44 us: 1.17x faster                                      |
| regex_effbot            | 3.45 ms                                                | 3.11 ms: 1.11x faster                                      |
| json                    | 5.24 ms                                                | 4.75 ms: 1.10x faster                                      |
| richards                | 48.9 ms                                                | 44.5 ms: 1.10x faster                                      |
| mako                    | 10.8 ms                                                | 9.96 ms: 1.09x faster                                      |
| logging_simple          | 6.24 us                                                | 5.74 us: 1.09x faster                                      |
| scimark_monte_carlo     | 71.8 ms                                                | 66.0 ms: 1.09x faster                                      |
| deepcopy_memo           | 38.9 us                                                | 35.9 us: 1.09x faster                                      |
| pickle_list             | 4.65 us                                                | 4.30 us: 1.08x faster                                      |
| spectral_norm           | 105 ms                                                 | 97.3 ms: 1.08x faster                                      |
| logging_format          | 6.83 us                                                | 6.34 us: 1.08x faster                                      |
| hexiom                  | 6.74 ms                                                | 6.27 ms: 1.08x faster                                      |
| raytrace                | 306 ms                                                 | 287 ms: 1.07x faster                                       |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.51 ms: 1.06x faster                                      |
| unpickle_pure_python    | 241 us                                                 | 227 us: 1.06x faster                                       |
| pprint_safe_repr        | 743 ms                                                 | 699 ms: 1.06x faster                                       |
| gunicorn                | 1.20 ms                                                | 1.13 ms: 1.06x faster                                      |
| deepcopy                | 360 us                                                 | 340 us: 1.06x faster                                       |
| async_generators        | 375 ms                                                 | 354 ms: 1.06x faster                                       |
| float                   | 78.9 ms                                                | 74.4 ms: 1.06x faster                                      |
| chaos                   | 71.4 ms                                                | 67.3 ms: 1.06x faster                                      |
| xml_etree_process       | 56.5 ms                                                | 53.4 ms: 1.06x faster                                      |
| scimark_sor             | 121 ms                                                 | 115 ms: 1.06x faster                                       |
| xml_etree_generate      | 80.4 ms                                                | 76.1 ms: 1.06x faster                                      |
| genshi_text             | 22.8 ms                                                | 21.5 ms: 1.06x faster                                      |
| aiohttp                 | 1.12 ms                                                | 1.06 ms: 1.06x faster                                      |
| logging_silent          | 108 ns                                                 | 103 ns: 1.06x faster                                       |
| sympy_sum               | 170 ms                                                 | 161 ms: 1.06x faster                                       |
| pprint_pformat          | 1.53 sec                                               | 1.45 sec: 1.05x faster                                     |
| json_dumps              | 13.5 ms                                                | 12.8 ms: 1.05x faster                                      |
| docutils                | 2.69 sec                                               | 2.56 sec: 1.05x faster                                     |
| pycparser               | 1.20 sec                                               | 1.14 sec: 1.05x faster                                     |
| pickle_pure_python      | 319 us                                                 | 305 us: 1.05x faster                                       |
| unpickle_list           | 5.22 us                                                | 5.00 us: 1.04x faster                                      |
| meteor_contest          | 109 ms                                                 | 104 ms: 1.04x faster                                       |
| mdp                     | 2.79 sec                                               | 2.67 sec: 1.04x faster                                     |
| regex_v8                | 22.9 ms                                                | 22.0 ms: 1.04x faster                                      |
| unpickle                | 13.9 us                                                | 13.3 us: 1.04x faster                                      |
| scimark_fft             | 342 ms                                                 | 329 ms: 1.04x faster                                       |
| regex_dna               | 204 ms                                                 | 196 ms: 1.04x faster                                       |
| 2to3                    | 266 ms                                                 | 256 ms: 1.04x faster                                       |
| sympy_str               | 299 ms                                                 | 288 ms: 1.04x faster                                       |
| django_template         | 33.8 ms                                                | 32.6 ms: 1.04x faster                                      |
| chameleon               | 6.86 ms                                                | 6.62 ms: 1.04x faster                                      |
| crypto_pyaes            | 77.5 ms                                                | 74.8 ms: 1.04x faster                                      |
| deepcopy_reduce         | 3.14 us                                                | 3.03 us: 1.04x faster                                      |
| pylint                  | 478 ms                                                 | 462 ms: 1.03x faster                                       |
| sympy_integrate         | 21.4 ms                                                | 20.7 ms: 1.03x faster                                      |
| sympy_expand            | 490 ms                                                 | 475 ms: 1.03x faster                                       |
| pyflate                 | 426 ms                                                 | 413 ms: 1.03x faster                                       |
| genshi_xml              | 54.1 ms                                                | 52.4 ms: 1.03x faster                                      |
| nqueens                 | 86.8 ms                                                | 84.2 ms: 1.03x faster                                      |
| xml_etree_iterparse     | 109 ms                                                 | 105 ms: 1.03x faster                                       |
| scimark_lu              | 112 ms                                                 | 109 ms: 1.03x faster                                       |
| go                      | 143 ms                                                 | 139 ms: 1.03x faster                                       |
| thrift                  | 772 us                                                 | 750 us: 1.03x faster                                       |
| tornado_http            | 97.7 ms                                                | 94.9 ms: 1.03x faster                                      |
| dulwich_log             | 64.9 ms                                                | 63.1 ms: 1.03x faster                                      |
| sqlalchemy_declarative  | 141 ms                                                 | 137 ms: 1.03x faster                                       |
| regex_compile           | 141 ms                                                 | 138 ms: 1.03x faster                                       |
| generators              | 76.5 ms                                                | 74.4 ms: 1.03x faster                                      |
| bench_thread_pool       | 833 us                                                 | 811 us: 1.03x faster                                       |
| telco                   | 6.72 ms                                                | 6.54 ms: 1.03x faster                                      |
| xml_etree_parse         | 163 ms                                                 | 159 ms: 1.03x faster                                       |
| sqlglot_optimize        | 55.2 ms                                                | 53.9 ms: 1.02x faster                                      |
| sqlite_synth            | 2.58 us                                                | 2.52 us: 1.02x faster                                      |
| python_startup          | 8.69 ms                                                | 8.49 ms: 1.02x faster                                      |
| pathlib                 | 18.5 ms                                                | 18.1 ms: 1.02x faster                                      |
| sqlglot_normalize       | 112 ms                                                 | 110 ms: 1.02x faster                                       |
| html5lib                | 65.0 ms                                                | 63.7 ms: 1.02x faster                                      |
| async_tree_memoization  | 640 ms                                                 | 628 ms: 1.02x faster                                       |
| sqlalchemy_imperative   | 18.2 ms                                                | 17.9 ms: 1.02x faster                                      |
| coroutines              | 26.1 ms                                                | 25.7 ms: 1.02x faster                                      |
| fannkuch                | 410 ms                                                 | 403 ms: 1.02x faster                                       |
| python_startup_no_site  | 6.09 ms                                                | 5.99 ms: 1.02x faster                                      |
| async_tree_none         | 532 ms                                                 | 526 ms: 1.01x faster                                       |
| async_tree_cpu_io_mixed | 750 ms                                                 | 743 ms: 1.01x faster                                       |
| asyncio_tcp             | 887 ms                                                 | 890 ms: 1.00x slower                                       |
| deltablue               | 3.80 ms                                                | 3.84 ms: 1.01x slower                                      |
| create_gc_cycles        | 1.48 ms                                                | 1.51 ms: 1.02x slower                                      |
| pidigits                | 190 ms                                                 | 199 ms: 1.05x slower                                       |
| unpack_sequence         | 43.3 ns                                                | 46.2 ns: 1.07x slower                                      |
| gc_traversal            | 3.90 ms                                                | 4.21 ms: 1.08x slower                                      |
| comprehensions          | 23.6 us                                                | 26.0 us: 1.10x slower                                      |
| sqlglot_transpile       | 1.75 ms                                                | 2.05 ms: 1.17x slower                                      |
| sqlglot_parse           | 1.43 ms                                                | 1.75 ms: 1.22x slower                                      |
| Geometric mean          | (ref)                                                  | 1.04x faster                                               |

Benchmark hidden because not significant (6): mypy2, async_tree_io, bench_mp_pool, nbody, dask, djangocms
Ignored benchmarks (11) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, coverage, flaskblogging, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
