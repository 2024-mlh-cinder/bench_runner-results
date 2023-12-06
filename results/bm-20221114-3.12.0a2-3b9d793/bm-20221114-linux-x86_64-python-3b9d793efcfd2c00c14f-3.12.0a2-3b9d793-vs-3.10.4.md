
# Results vs. 3.10.4

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: linux-x86_64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.36x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.30x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 245 ms: 1.41x faster                                                  |
| chameleon      | 9.84 ms                                                | 6.30 ms: 1.56x faster                                                 |
| docutils       | 3.26 sec                                               | 2.50 sec: 1.31x faster                                                |
| html5lib       | 88.1 ms                                                | 58.9 ms: 1.49x faster                                                 |
| tornado_http   | 131 ms                                                 | 93.1 ms: 1.40x faster                                                 |
| Geometric mean | (ref)                                                  | 1.43x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 527 ms: 1.39x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 730 ms: 1.38x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.32 sec: 1.35x faster                                                |
| async_tree_memoization  | 867 ms                                                 | 653 ms: 1.33x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.36x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 116 ms                                                 | 72.0 ms: 1.62x faster                                                 |
| nbody          | 148 ms                                                 | 93.9 ms: 1.58x faster                                                 |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.37x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 127 ms: 1.46x faster                                                  |
| regex_v8       | 26.2 ms                                                | 21.1 ms: 1.25x faster                                                 |
| regex_dna      | 215 ms                                                 | 208 ms: 1.04x faster                                                  |
| regex_effbot   | 3.41 ms                                                | 3.47 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.17x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 283 us: 1.70x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 200 us: 1.64x faster                                                  |
| json_dumps           | 14.3 ms                                                | 9.66 ms: 1.48x faster                                                 |
| xml_etree_process    | 79.8 ms                                                | 53.9 ms: 1.48x faster                                                 |
| json_loads           | 31.4 us                                                | 23.9 us: 1.31x faster                                                 |
| xml_etree_generate   | 100.0 ms                                               | 77.2 ms: 1.30x faster                                                 |
| pickle_list          | 5.05 us                                                | 4.06 us: 1.24x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 149 ms: 1.15x faster                                                  |
| unpickle             | 14.9 us                                                | 12.9 us: 1.15x faster                                                 |
| xml_etree_iterparse  | 116 ms                                                 | 103 ms: 1.13x faster                                                  |
| pickle               | 10.7 us                                                | 9.88 us: 1.08x faster                                                 |
| unpickle_list        | 5.10 us                                                | 4.98 us: 1.02x faster                                                 |
| pickle_dict          | 30.0 us                                                | 30.8 us: 1.03x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.58 ms: 1.67x faster                                                 |
| python_startup_no_site | 5.87 ms                                                | 6.12 ms: 1.04x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.39 ms: 1.74x faster                                                 |
| genshi_text     | 31.7 ms                                                | 20.2 ms: 1.57x faster                                                 |
| django_template | 47.6 ms                                                | 32.8 ms: 1.45x faster                                                 |
| genshi_xml      | 66.0 ms                                                | 47.0 ms: 1.40x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.54x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-linux-x86_64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.22 ms: 2.43x faster                                                 |
| scimark_sor             | 214 ms                                                 | 105 ms: 2.04x faster                                                  |
| logging_silent          | 189 ns                                                 | 93.4 ns: 2.02x faster                                                 |
| richards                | 79.4 ms                                                | 41.8 ms: 1.90x faster                                                 |
| raytrace                | 498 ms                                                 | 277 ms: 1.80x faster                                                  |
| go                      | 238 ms                                                 | 135 ms: 1.77x faster                                                  |
| pyflate                 | 708 ms                                                 | 402 ms: 1.76x faster                                                  |
| deepcopy_memo           | 58.8 us                                                | 33.6 us: 1.75x faster                                                 |
| chaos                   | 114 ms                                                 | 65.8 ms: 1.74x faster                                                 |
| mako                    | 16.3 ms                                                | 9.39 ms: 1.74x faster                                                 |
| scimark_monte_carlo     | 118 ms                                                 | 68.0 ms: 1.73x faster                                                 |
| spectral_norm           | 163 ms                                                 | 94.9 ms: 1.72x faster                                                 |
| hexiom                  | 10.3 ms                                                | 6.04 ms: 1.70x faster                                                 |
| pickle_pure_python      | 482 us                                                 | 283 us: 1.70x faster                                                  |
| crypto_pyaes            | 127 ms                                                 | 74.6 ms: 1.70x faster                                                 |
| python_startup          | 14.3 ms                                                | 8.58 ms: 1.67x faster                                                 |
| unpickle_pure_python    | 327 us                                                 | 200 us: 1.64x faster                                                  |
| scimark_lu              | 175 ms                                                 | 108 ms: 1.62x faster                                                  |
| float                   | 116 ms                                                 | 72.0 ms: 1.62x faster                                                 |
| sqlglot_parse           | 2.15 ms                                                | 1.33 ms: 1.61x faster                                                 |
| nbody                   | 148 ms                                                 | 93.9 ms: 1.58x faster                                                 |
| sqlglot_transpile       | 2.55 ms                                                | 1.62 ms: 1.58x faster                                                 |
| genshi_text             | 31.7 ms                                                | 20.2 ms: 1.57x faster                                                 |
| chameleon               | 9.84 ms                                                | 6.30 ms: 1.56x faster                                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.00 ms: 1.53x faster                                                 |
| pprint_pformat          | 2.10 sec                                               | 1.39 sec: 1.51x faster                                                |
| html5lib                | 88.1 ms                                                | 58.9 ms: 1.49x faster                                                 |
| pprint_safe_repr        | 1.01 sec                                               | 685 ms: 1.48x faster                                                  |
| json_dumps              | 14.3 ms                                                | 9.66 ms: 1.48x faster                                                 |
| xml_etree_process       | 79.8 ms                                                | 53.9 ms: 1.48x faster                                                 |
| scimark_fft             | 454 ms                                                 | 309 ms: 1.47x faster                                                  |
| deepcopy                | 481 us                                                 | 328 us: 1.47x faster                                                  |
| regex_compile           | 186 ms                                                 | 127 ms: 1.46x faster                                                  |
| pycparser               | 1.57 sec                                               | 1.08 sec: 1.46x faster                                                |
| logging_simple          | 8.27 us                                                | 5.70 us: 1.45x faster                                                 |
| django_template         | 47.6 ms                                                | 32.8 ms: 1.45x faster                                                 |
| deepcopy_reduce         | 4.17 us                                                | 2.89 us: 1.44x faster                                                 |
| logging_format          | 9.07 us                                                | 6.30 us: 1.44x faster                                                 |
| unpack_sequence         | 65.7 ns                                                | 45.7 ns: 1.44x faster                                                 |
| fannkuch                | 527 ms                                                 | 369 ms: 1.43x faster                                                  |
| thrift                  | 1.06 ms                                                | 748 us: 1.42x faster                                                  |
| aiohttp                 | 1.41 ms                                                | 999 us: 1.41x faster                                                  |
| 2to3                    | 346 ms                                                 | 245 ms: 1.41x faster                                                  |
| genshi_xml              | 66.0 ms                                                | 47.0 ms: 1.40x faster                                                 |
| tornado_http            | 131 ms                                                 | 93.1 ms: 1.40x faster                                                 |
| coroutines              | 34.5 ms                                                | 24.7 ms: 1.39x faster                                                 |
| async_tree_none         | 732 ms                                                 | 527 ms: 1.39x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 730 ms: 1.38x faster                                                  |
| gunicorn                | 1.48 ms                                                | 1.08 ms: 1.37x faster                                                 |
| mypy2                   | 442 ms                                                 | 325 ms: 1.36x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.32 sec: 1.35x faster                                                |
| sqlglot_optimize        | 68.7 ms                                                | 51.0 ms: 1.35x faster                                                 |
| sqlglot_normalize       | 141 ms                                                 | 105 ms: 1.34x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 653 ms: 1.33x faster                                                  |
| json_loads              | 31.4 us                                                | 23.9 us: 1.31x faster                                                 |
| nqueens                 | 107 ms                                                 | 81.1 ms: 1.31x faster                                                 |
| docutils                | 3.26 sec                                               | 2.50 sec: 1.31x faster                                                |
| xml_etree_generate      | 100.0 ms                                               | 77.2 ms: 1.30x faster                                                 |
| sympy_integrate         | 25.4 ms                                                | 20.4 ms: 1.25x faster                                                 |
| dulwich_log             | 77.0 ms                                                | 61.8 ms: 1.25x faster                                                 |
| regex_v8                | 26.2 ms                                                | 21.1 ms: 1.25x faster                                                 |
| async_generators        | 442 ms                                                 | 355 ms: 1.24x faster                                                  |
| pickle_list             | 5.05 us                                                | 4.06 us: 1.24x faster                                                 |
| bench_thread_pool       | 966 us                                                 | 780 us: 1.24x faster                                                  |
| sympy_expand            | 558 ms                                                 | 456 ms: 1.22x faster                                                  |
| json                    | 5.67 ms                                                | 4.65 ms: 1.22x faster                                                 |
| comprehensions          | 28.5 us                                                | 23.4 us: 1.22x faster                                                 |
| dask                    | 432 ms                                                 | 360 ms: 1.20x faster                                                  |
| sympy_str               | 337 ms                                                 | 282 ms: 1.19x faster                                                  |
| mdp                     | 2.93 sec                                               | 2.48 sec: 1.18x faster                                                |
| meteor_contest          | 119 ms                                                 | 102 ms: 1.17x faster                                                  |
| sqlite_synth            | 3.02 us                                                | 2.60 us: 1.16x faster                                                 |
| sympy_sum               | 190 ms                                                 | 165 ms: 1.15x faster                                                  |
| xml_etree_parse         | 171 ms                                                 | 149 ms: 1.15x faster                                                  |
| unpickle                | 14.9 us                                                | 12.9 us: 1.15x faster                                                 |
| djangocms               | 37.2 us                                                | 32.5 us: 1.15x faster                                                 |
| pathlib                 | 20.3 ms                                                | 17.7 ms: 1.14x faster                                                 |
| xml_etree_iterparse     | 116 ms                                                 | 103 ms: 1.13x faster                                                  |
| create_gc_cycles        | 1.61 ms                                                | 1.46 ms: 1.11x faster                                                 |
| telco                   | 7.01 ms                                                | 6.38 ms: 1.10x faster                                                 |
| pickle                  | 10.7 us                                                | 9.88 us: 1.08x faster                                                 |
| asyncio_tcp             | 918 ms                                                 | 884 ms: 1.04x faster                                                  |
| regex_dna               | 215 ms                                                 | 208 ms: 1.04x faster                                                  |
| unpickle_list           | 5.10 us                                                | 4.98 us: 1.02x faster                                                 |
| generators              | 78.9 ms                                                | 77.4 ms: 1.02x faster                                                 |
| pidigits                | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| regex_effbot            | 3.41 ms                                                | 3.47 ms: 1.02x slower                                                 |
| pickle_dict             | 30.0 us                                                | 30.8 us: 1.03x slower                                                 |
| python_startup_no_site  | 5.87 ms                                                | 6.12 ms: 1.04x slower                                                 |
| gc_traversal            | 3.43 ms                                                | 3.77 ms: 1.10x slower                                                 |
| coverage                | 82.0 ms                                                | 101 ms: 1.23x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.36x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (9) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.34x
- 95% likely to have a speedup of 1.33x
- 99% likely to have a speedup of 1.30x
