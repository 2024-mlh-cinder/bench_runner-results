
# Results vs. 3.10.4

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: linux-x86_64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.35x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.28x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 246 ms: 1.41x faster                                                  |
| chameleon      | 9.84 ms                                                | 6.45 ms: 1.53x faster                                                 |
| docutils       | 3.26 sec                                               | 2.57 sec: 1.27x faster                                                |
| html5lib       | 88.1 ms                                                | 59.7 ms: 1.48x faster                                                 |
| Geometric mean | (ref)                                                  | 1.42x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 536 ms: 1.36x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.34 sec: 1.34x faster                                                |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 769 ms: 1.31x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 665 ms: 1.30x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.33x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 116 ms                                                 | 73.2 ms: 1.59x faster                                                 |
| nbody          | 148 ms                                                 | 94.0 ms: 1.58x faster                                                 |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.36x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 129 ms: 1.44x faster                                                  |
| regex_v8       | 26.2 ms                                                | 22.3 ms: 1.18x faster                                                 |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                                  |
| regex_effbot   | 3.41 ms                                                | 3.63 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                  | 1.12x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 282 us: 1.71x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 200 us: 1.63x faster                                                  |
| json_dumps           | 14.3 ms                                                | 9.52 ms: 1.50x faster                                                 |
| xml_etree_process    | 79.8 ms                                                | 53.7 ms: 1.49x faster                                                 |
| json_loads           | 31.4 us                                                | 23.8 us: 1.32x faster                                                 |
| xml_etree_generate   | 100.0 ms                                               | 76.9 ms: 1.30x faster                                                 |
| pickle_list          | 5.05 us                                                | 3.95 us: 1.28x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 148 ms: 1.15x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 104 ms: 1.11x faster                                                  |
| unpickle             | 14.9 us                                                | 13.3 us: 1.11x faster                                                 |
| pickle               | 10.7 us                                                | 10.1 us: 1.05x faster                                                 |
| unpickle_list        | 5.10 us                                                | 4.97 us: 1.03x faster                                                 |
| pickle_dict          | 30.0 us                                                | 31.5 us: 1.05x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.52 ms: 1.68x faster                                                 |
| python_startup_no_site | 5.87 ms                                                | 6.07 ms: 1.03x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.43 ms: 1.73x faster                                                 |
| genshi_text     | 31.7 ms                                                | 20.9 ms: 1.52x faster                                                 |
| django_template | 47.6 ms                                                | 33.0 ms: 1.44x faster                                                 |
| genshi_xml      | 66.0 ms                                                | 48.0 ms: 1.37x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.51x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.22 ms: 2.43x faster                                                 |
| logging_silent          | 189 ns                                                 | 90.9 ns: 2.08x faster                                                 |
| scimark_sor             | 214 ms                                                 | 105 ms: 2.04x faster                                                  |
| richards                | 79.4 ms                                                | 42.0 ms: 1.89x faster                                                 |
| scimark_monte_carlo     | 118 ms                                                 | 65.4 ms: 1.80x faster                                                 |
| raytrace                | 498 ms                                                 | 281 ms: 1.77x faster                                                  |
| go                      | 238 ms                                                 | 136 ms: 1.75x faster                                                  |
| pyflate                 | 708 ms                                                 | 405 ms: 1.75x faster                                                  |
| mako                    | 16.3 ms                                                | 9.43 ms: 1.73x faster                                                 |
| deepcopy_memo           | 58.8 us                                                | 34.2 us: 1.72x faster                                                 |
| chaos                   | 114 ms                                                 | 66.9 ms: 1.71x faster                                                 |
| pickle_pure_python      | 482 us                                                 | 282 us: 1.71x faster                                                  |
| spectral_norm           | 163 ms                                                 | 96.0 ms: 1.70x faster                                                 |
| hexiom                  | 10.3 ms                                                | 6.08 ms: 1.69x faster                                                 |
| crypto_pyaes            | 127 ms                                                 | 75.3 ms: 1.68x faster                                                 |
| python_startup          | 14.3 ms                                                | 8.52 ms: 1.68x faster                                                 |
| scimark_lu              | 175 ms                                                 | 106 ms: 1.65x faster                                                  |
| unpickle_pure_python    | 327 us                                                 | 200 us: 1.63x faster                                                  |
| sqlglot_parse           | 2.15 ms                                                | 1.34 ms: 1.60x faster                                                 |
| float                   | 116 ms                                                 | 73.2 ms: 1.59x faster                                                 |
| nbody                   | 148 ms                                                 | 94.0 ms: 1.58x faster                                                 |
| sqlglot_transpile       | 2.55 ms                                                | 1.63 ms: 1.56x faster                                                 |
| chameleon               | 9.84 ms                                                | 6.45 ms: 1.53x faster                                                 |
| unpack_sequence         | 65.7 ns                                                | 43.1 ns: 1.52x faster                                                 |
| genshi_text             | 31.7 ms                                                | 20.9 ms: 1.52x faster                                                 |
| json_dumps              | 14.3 ms                                                | 9.52 ms: 1.50x faster                                                 |
| xml_etree_process       | 79.8 ms                                                | 53.7 ms: 1.49x faster                                                 |
| pprint_pformat          | 2.10 sec                                               | 1.41 sec: 1.48x faster                                                |
| pprint_safe_repr        | 1.01 sec                                               | 686 ms: 1.48x faster                                                  |
| html5lib                | 88.1 ms                                                | 59.7 ms: 1.48x faster                                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.20 ms: 1.45x faster                                                 |
| deepcopy                | 481 us                                                 | 332 us: 1.45x faster                                                  |
| scimark_fft             | 454 ms                                                 | 314 ms: 1.45x faster                                                  |
| django_template         | 47.6 ms                                                | 33.0 ms: 1.44x faster                                                 |
| regex_compile           | 186 ms                                                 | 129 ms: 1.44x faster                                                  |
| pycparser               | 1.57 sec                                               | 1.09 sec: 1.43x faster                                                |
| thrift                  | 1.06 ms                                                | 751 us: 1.42x faster                                                  |
| logging_format          | 9.07 us                                                | 6.41 us: 1.42x faster                                                 |
| logging_simple          | 8.27 us                                                | 5.88 us: 1.41x faster                                                 |
| 2to3                    | 346 ms                                                 | 246 ms: 1.41x faster                                                  |
| deepcopy_reduce         | 4.17 us                                                | 2.97 us: 1.40x faster                                                 |
| fannkuch                | 527 ms                                                 | 379 ms: 1.39x faster                                                  |
| coroutines              | 34.5 ms                                                | 25.0 ms: 1.38x faster                                                 |
| genshi_xml              | 66.0 ms                                                | 48.0 ms: 1.37x faster                                                 |
| async_tree_none         | 732 ms                                                 | 536 ms: 1.36x faster                                                  |
| sqlglot_optimize        | 68.7 ms                                                | 50.6 ms: 1.36x faster                                                 |
| sqlglot_normalize       | 141 ms                                                 | 105 ms: 1.35x faster                                                  |
| mypy2                   | 442 ms                                                 | 329 ms: 1.35x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.34 sec: 1.34x faster                                                |
| nqueens                 | 107 ms                                                 | 80.1 ms: 1.33x faster                                                 |
| json_loads              | 31.4 us                                                | 23.8 us: 1.32x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 769 ms: 1.31x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 665 ms: 1.30x faster                                                  |
| xml_etree_generate      | 100.0 ms                                               | 76.9 ms: 1.30x faster                                                 |
| pickle_list             | 5.05 us                                                | 3.95 us: 1.28x faster                                                 |
| docutils                | 3.26 sec                                               | 2.57 sec: 1.27x faster                                                |
| async_generators        | 442 ms                                                 | 354 ms: 1.25x faster                                                  |
| sympy_integrate         | 25.4 ms                                                | 20.4 ms: 1.24x faster                                                 |
| bench_thread_pool       | 966 us                                                 | 778 us: 1.24x faster                                                  |
| dulwich_log             | 77.0 ms                                                | 62.5 ms: 1.23x faster                                                 |
| sympy_expand            | 558 ms                                                 | 458 ms: 1.22x faster                                                  |
| json                    | 5.67 ms                                                | 4.67 ms: 1.21x faster                                                 |
| comprehensions          | 28.5 us                                                | 23.5 us: 1.21x faster                                                 |
| dask                    | 432 ms                                                 | 360 ms: 1.20x faster                                                  |
| sympy_str               | 337 ms                                                 | 283 ms: 1.19x faster                                                  |
| regex_v8                | 26.2 ms                                                | 22.3 ms: 1.18x faster                                                 |
| mdp                     | 2.93 sec                                               | 2.50 sec: 1.17x faster                                                |
| sqlite_synth            | 3.02 us                                                | 2.58 us: 1.17x faster                                                 |
| sympy_sum               | 190 ms                                                 | 164 ms: 1.16x faster                                                  |
| xml_etree_parse         | 171 ms                                                 | 148 ms: 1.15x faster                                                  |
| meteor_contest          | 119 ms                                                 | 104 ms: 1.15x faster                                                  |
| djangocms               | 37.2 us                                                | 32.6 us: 1.14x faster                                                 |
| create_gc_cycles        | 1.61 ms                                                | 1.44 ms: 1.12x faster                                                 |
| xml_etree_iterparse     | 116 ms                                                 | 104 ms: 1.11x faster                                                  |
| unpickle                | 14.9 us                                                | 13.3 us: 1.11x faster                                                 |
| pathlib                 | 20.3 ms                                                | 18.3 ms: 1.11x faster                                                 |
| telco                   | 7.01 ms                                                | 6.46 ms: 1.09x faster                                                 |
| pickle                  | 10.7 us                                                | 10.1 us: 1.05x faster                                                 |
| asyncio_tcp             | 918 ms                                                 | 890 ms: 1.03x faster                                                  |
| unpickle_list           | 5.10 us                                                | 4.97 us: 1.03x faster                                                 |
| pidigits                | 190 ms                                                 | 189 ms: 1.01x faster                                                  |
| generators              | 78.9 ms                                                | 79.1 ms: 1.00x slower                                                 |
| regex_dna               | 215 ms                                                 | 217 ms: 1.01x slower                                                  |
| python_startup_no_site  | 5.87 ms                                                | 6.07 ms: 1.03x slower                                                 |
| pickle_dict             | 30.0 us                                                | 31.5 us: 1.05x slower                                                 |
| regex_effbot            | 3.41 ms                                                | 3.63 ms: 1.06x slower                                                 |
| gc_traversal            | 3.43 ms                                                | 3.81 ms: 1.11x slower                                                 |
| coverage                | 82.0 ms                                                | 102 ms: 1.25x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.35x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.32x
- 95% likely to have a speedup of 1.31x
- 99% likely to have a speedup of 1.28x
