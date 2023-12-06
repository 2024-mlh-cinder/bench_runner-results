
# Results vs. 3.10.4

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: linux-x86_64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.36x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.29x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 249 ms: 1.39x faster                                                  |
| chameleon      | 9.84 ms                                                | 6.51 ms: 1.51x faster                                                 |
| docutils       | 3.26 sec                                               | 2.52 sec: 1.30x faster                                                |
| html5lib       | 88.1 ms                                                | 59.9 ms: 1.47x faster                                                 |
| tornado_http   | 131 ms                                                 | 93.7 ms: 1.39x faster                                                 |
| Geometric mean | (ref)                                                  | 1.41x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 529 ms: 1.38x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 730 ms: 1.38x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.33 sec: 1.35x faster                                                |
| async_tree_memoization  | 867 ms                                                 | 656 ms: 1.32x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.36x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 116 ms                                                 | 71.4 ms: 1.63x faster                                                 |
| nbody          | 148 ms                                                 | 96.6 ms: 1.53x faster                                                 |
| pidigits       | 190 ms                                                 | 198 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                  | 1.34x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 127 ms: 1.46x faster                                                  |
| regex_v8       | 26.2 ms                                                | 21.4 ms: 1.23x faster                                                 |
| regex_dna      | 215 ms                                                 | 201 ms: 1.07x faster                                                  |
| regex_effbot   | 3.41 ms                                                | 3.37 ms: 1.01x faster                                                 |
| Geometric mean | (ref)                                                  | 1.18x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 285 us: 1.69x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 202 us: 1.62x faster                                                  |
| json_dumps           | 14.3 ms                                                | 9.36 ms: 1.53x faster                                                 |
| xml_etree_process    | 79.8 ms                                                | 53.4 ms: 1.49x faster                                                 |
| json_loads           | 31.4 us                                                | 23.5 us: 1.34x faster                                                 |
| xml_etree_generate   | 100.0 ms                                               | 76.0 ms: 1.32x faster                                                 |
| pickle_list          | 5.05 us                                                | 4.19 us: 1.20x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 145 ms: 1.18x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 101 ms: 1.15x faster                                                  |
| unpickle             | 14.9 us                                                | 13.2 us: 1.13x faster                                                 |
| pickle               | 10.7 us                                                | 10.1 us: 1.05x faster                                                 |
| unpickle_list        | 5.10 us                                                | 4.91 us: 1.04x faster                                                 |
| pickle_dict          | 30.0 us                                                | 31.1 us: 1.04x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.42 ms: 1.70x faster                                                 |
| python_startup_no_site | 5.87 ms                                                | 5.93 ms: 1.01x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.30x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.64 ms: 1.69x faster                                                 |
| genshi_text     | 31.7 ms                                                | 21.5 ms: 1.48x faster                                                 |
| django_template | 47.6 ms                                                | 33.0 ms: 1.44x faster                                                 |
| genshi_xml      | 66.0 ms                                                | 50.0 ms: 1.32x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.48x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-linux-x86_64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.30 ms: 2.37x faster                                                 |
| logging_silent          | 189 ns                                                 | 91.6 ns: 2.06x faster                                                 |
| scimark_sor             | 214 ms                                                 | 106 ms: 2.03x faster                                                  |
| richards                | 79.4 ms                                                | 42.4 ms: 1.87x faster                                                 |
| scimark_monte_carlo     | 118 ms                                                 | 66.6 ms: 1.77x faster                                                 |
| raytrace                | 498 ms                                                 | 282 ms: 1.76x faster                                                  |
| go                      | 238 ms                                                 | 135 ms: 1.76x faster                                                  |
| pyflate                 | 708 ms                                                 | 407 ms: 1.74x faster                                                  |
| spectral_norm           | 163 ms                                                 | 95.2 ms: 1.71x faster                                                 |
| deepcopy_memo           | 58.8 us                                                | 34.4 us: 1.71x faster                                                 |
| chaos                   | 114 ms                                                 | 67.1 ms: 1.70x faster                                                 |
| python_startup          | 14.3 ms                                                | 8.42 ms: 1.70x faster                                                 |
| crypto_pyaes            | 127 ms                                                 | 74.8 ms: 1.69x faster                                                 |
| pickle_pure_python      | 482 us                                                 | 285 us: 1.69x faster                                                  |
| mako                    | 16.3 ms                                                | 9.64 ms: 1.69x faster                                                 |
| hexiom                  | 10.3 ms                                                | 6.11 ms: 1.69x faster                                                 |
| float                   | 116 ms                                                 | 71.4 ms: 1.63x faster                                                 |
| unpickle_pure_python    | 327 us                                                 | 202 us: 1.62x faster                                                  |
| scimark_lu              | 175 ms                                                 | 108 ms: 1.62x faster                                                  |
| sqlglot_parse           | 2.15 ms                                                | 1.34 ms: 1.60x faster                                                 |
| sqlglot_transpile       | 2.55 ms                                                | 1.63 ms: 1.56x faster                                                 |
| nbody                   | 148 ms                                                 | 96.6 ms: 1.53x faster                                                 |
| json_dumps              | 14.3 ms                                                | 9.36 ms: 1.53x faster                                                 |
| pprint_safe_repr        | 1.01 sec                                               | 665 ms: 1.53x faster                                                  |
| pprint_pformat          | 2.10 sec                                               | 1.38 sec: 1.52x faster                                                |
| chameleon               | 9.84 ms                                                | 6.51 ms: 1.51x faster                                                 |
| xml_etree_process       | 79.8 ms                                                | 53.4 ms: 1.49x faster                                                 |
| unpack_sequence         | 65.7 ns                                                | 44.1 ns: 1.49x faster                                                 |
| genshi_text             | 31.7 ms                                                | 21.5 ms: 1.48x faster                                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.13 ms: 1.48x faster                                                 |
| html5lib                | 88.1 ms                                                | 59.9 ms: 1.47x faster                                                 |
| regex_compile           | 186 ms                                                 | 127 ms: 1.46x faster                                                  |
| scimark_fft             | 454 ms                                                 | 312 ms: 1.46x faster                                                  |
| deepcopy                | 481 us                                                 | 333 us: 1.45x faster                                                  |
| django_template         | 47.6 ms                                                | 33.0 ms: 1.44x faster                                                 |
| deepcopy_reduce         | 4.17 us                                                | 2.91 us: 1.43x faster                                                 |
| logging_simple          | 8.27 us                                                | 5.80 us: 1.43x faster                                                 |
| thrift                  | 1.06 ms                                                | 746 us: 1.43x faster                                                  |
| fannkuch                | 527 ms                                                 | 370 ms: 1.42x faster                                                  |
| logging_format          | 9.07 us                                                | 6.38 us: 1.42x faster                                                 |
| aiohttp                 | 1.41 ms                                                | 1.00 ms: 1.41x faster                                                 |
| pycparser               | 1.57 sec                                               | 1.12 sec: 1.40x faster                                                |
| coroutines              | 34.5 ms                                                | 24.7 ms: 1.40x faster                                                 |
| tornado_http            | 131 ms                                                 | 93.7 ms: 1.39x faster                                                 |
| 2to3                    | 346 ms                                                 | 249 ms: 1.39x faster                                                  |
| async_tree_none         | 732 ms                                                 | 529 ms: 1.38x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 730 ms: 1.38x faster                                                  |
| gunicorn                | 1.48 ms                                                | 1.07 ms: 1.38x faster                                                 |
| sqlglot_normalize       | 141 ms                                                 | 104 ms: 1.36x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.33 sec: 1.35x faster                                                |
| mypy2                   | 442 ms                                                 | 328 ms: 1.35x faster                                                  |
| sqlglot_optimize        | 68.7 ms                                                | 51.2 ms: 1.34x faster                                                 |
| json_loads              | 31.4 us                                                | 23.5 us: 1.34x faster                                                 |
| comprehensions          | 28.5 us                                                | 21.3 us: 1.34x faster                                                 |
| async_tree_memoization  | 867 ms                                                 | 656 ms: 1.32x faster                                                  |
| nqueens                 | 107 ms                                                 | 80.7 ms: 1.32x faster                                                 |
| genshi_xml              | 66.0 ms                                                | 50.0 ms: 1.32x faster                                                 |
| xml_etree_generate      | 100.0 ms                                               | 76.0 ms: 1.32x faster                                                 |
| docutils                | 3.26 sec                                               | 2.52 sec: 1.30x faster                                                |
| async_generators        | 442 ms                                                 | 349 ms: 1.27x faster                                                  |
| json                    | 5.67 ms                                                | 4.55 ms: 1.25x faster                                                 |
| sympy_integrate         | 25.4 ms                                                | 20.4 ms: 1.24x faster                                                 |
| bench_thread_pool       | 966 us                                                 | 780 us: 1.24x faster                                                  |
| dulwich_log             | 77.0 ms                                                | 62.4 ms: 1.23x faster                                                 |
| sympy_expand            | 558 ms                                                 | 455 ms: 1.23x faster                                                  |
| regex_v8                | 26.2 ms                                                | 21.4 ms: 1.23x faster                                                 |
| pickle_list             | 5.05 us                                                | 4.19 us: 1.20x faster                                                 |
| dask                    | 432 ms                                                 | 360 ms: 1.20x faster                                                  |
| sympy_str               | 337 ms                                                 | 283 ms: 1.19x faster                                                  |
| mdp                     | 2.93 sec                                               | 2.48 sec: 1.18x faster                                                |
| xml_etree_parse         | 171 ms                                                 | 145 ms: 1.18x faster                                                  |
| pylint                  | 534 ms                                                 | 458 ms: 1.17x faster                                                  |
| sympy_sum               | 190 ms                                                 | 164 ms: 1.16x faster                                                  |
| xml_etree_iterparse     | 116 ms                                                 | 101 ms: 1.15x faster                                                  |
| sqlite_synth            | 3.02 us                                                | 2.62 us: 1.15x faster                                                 |
| meteor_contest          | 119 ms                                                 | 104 ms: 1.15x faster                                                  |
| djangocms               | 37.2 us                                                | 32.5 us: 1.14x faster                                                 |
| pathlib                 | 20.3 ms                                                | 17.9 ms: 1.13x faster                                                 |
| unpickle                | 14.9 us                                                | 13.2 us: 1.13x faster                                                 |
| create_gc_cycles        | 1.61 ms                                                | 1.46 ms: 1.11x faster                                                 |
| telco                   | 7.01 ms                                                | 6.55 ms: 1.07x faster                                                 |
| regex_dna               | 215 ms                                                 | 201 ms: 1.07x faster                                                  |
| generators              | 78.9 ms                                                | 74.1 ms: 1.06x faster                                                 |
| pickle                  | 10.7 us                                                | 10.1 us: 1.05x faster                                                 |
| unpickle_list           | 5.10 us                                                | 4.91 us: 1.04x faster                                                 |
| asyncio_tcp             | 918 ms                                                 | 890 ms: 1.03x faster                                                  |
| regex_effbot            | 3.41 ms                                                | 3.37 ms: 1.01x faster                                                 |
| python_startup_no_site  | 5.87 ms                                                | 5.93 ms: 1.01x slower                                                 |
| gc_traversal            | 3.43 ms                                                | 3.55 ms: 1.04x slower                                                 |
| pickle_dict             | 30.0 us                                                | 31.1 us: 1.04x slower                                                 |
| pidigits                | 190 ms                                                 | 198 ms: 1.04x slower                                                  |
| coverage                | 82.0 ms                                                | 102 ms: 1.24x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.36x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (8) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, flaskblogging, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.33x
- 95% likely to have a speedup of 1.32x
- 99% likely to have a speedup of 1.29x
