
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0b3
- machine: linux-x86_64
- commit hash: eb0004c
- commit date: 2022-06-01
- overall geometric mean: 1.32x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 256 ms: 1.35x faster                                       |
| chameleon      | 9.84 ms                                                | 6.42 ms: 1.53x faster                                      |
| docutils       | 3.26 sec                                               | 2.56 sec: 1.27x faster                                     |
| html5lib       | 88.1 ms                                                | 62.8 ms: 1.40x faster                                      |
| tornado_http   | 131 ms                                                 | 94.7 ms: 1.38x faster                                      |
| Geometric mean | (ref)                                                  | 1.38x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 525 ms: 1.39x faster                                       |
| async_tree_io           | 1.79 sec                                               | 1.30 sec: 1.37x faster                                     |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 735 ms: 1.37x faster                                       |
| async_tree_memoization  | 867 ms                                                 | 636 ms: 1.36x faster                                       |
| Geometric mean          | (ref)                                                  | 1.37x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| float          | 116 ms                                                 | 73.9 ms: 1.58x faster                                      |
| nbody          | 148 ms                                                 | 94.9 ms: 1.56x faster                                      |
| pidigits       | 190 ms                                                 | 194 ms: 1.02x slower                                       |
| Geometric mean | (ref)                                                  | 1.34x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 136 ms: 1.36x faster                                       |
| regex_v8       | 26.2 ms                                                | 21.4 ms: 1.22x faster                                      |
| regex_effbot   | 3.41 ms                                                | 2.92 ms: 1.17x faster                                      |
| regex_dna      | 215 ms                                                 | 194 ms: 1.11x faster                                       |
| Geometric mean | (ref)                                                  | 1.21x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 301 us: 1.60x faster                                       |
| xml_etree_process    | 79.8 ms                                                | 53.6 ms: 1.49x faster                                      |
| unpickle_pure_python | 327 us                                                 | 227 us: 1.44x faster                                       |
| xml_etree_generate   | 100.0 ms                                               | 76.7 ms: 1.30x faster                                      |
| json_loads           | 31.4 us                                                | 24.9 us: 1.26x faster                                      |
| pickle_list          | 5.05 us                                                | 4.27 us: 1.18x faster                                      |
| pickle_dict          | 30.0 us                                                | 26.0 us: 1.15x faster                                      |
| pickle               | 10.7 us                                                | 9.37 us: 1.14x faster                                      |
| json_dumps           | 14.3 ms                                                | 12.7 ms: 1.13x faster                                      |
| unpickle             | 14.9 us                                                | 13.3 us: 1.11x faster                                      |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                       |
| xml_etree_iterparse  | 116 ms                                                 | 108 ms: 1.08x faster                                       |
| unpickle_list        | 5.10 us                                                | 4.96 us: 1.03x faster                                      |
| Geometric mean       | (ref)                                                  | 1.22x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.51 ms: 1.68x faster                                      |
| python_startup_no_site | 5.87 ms                                                | 6.01 ms: 1.02x slower                                      |
| Geometric mean         | (ref)                                                  | 1.28x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.99 ms: 1.63x faster                                      |
| django_template | 47.6 ms                                                | 33.0 ms: 1.44x faster                                      |
| genshi_text     | 31.7 ms                                                | 22.0 ms: 1.44x faster                                      |
| genshi_xml      | 66.0 ms                                                | 52.3 ms: 1.26x faster                                      |
| Geometric mean  | (ref)                                                  | 1.44x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220601-linux-x86_64-python-v3.11.0b3-3.11.0b3-eb0004c |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.65 ms: 2.14x faster                                      |
| scimark_sor             | 214 ms                                                 | 114 ms: 1.87x faster                                       |
| logging_silent          | 189 ns                                                 | 101 ns: 1.87x faster                                       |
| scimark_monte_carlo     | 118 ms                                                 | 66.6 ms: 1.77x faster                                      |
| richards                | 79.4 ms                                                | 45.3 ms: 1.75x faster                                      |
| pyflate                 | 708 ms                                                 | 409 ms: 1.73x faster                                       |
| crypto_pyaes            | 127 ms                                                 | 73.6 ms: 1.72x faster                                      |
| go                      | 238 ms                                                 | 139 ms: 1.71x faster                                       |
| raytrace                | 498 ms                                                 | 292 ms: 1.70x faster                                       |
| python_startup          | 14.3 ms                                                | 8.51 ms: 1.68x faster                                      |
| chaos                   | 114 ms                                                 | 68.2 ms: 1.68x faster                                      |
| spectral_norm           | 163 ms                                                 | 97.5 ms: 1.67x faster                                      |
| scimark_lu              | 175 ms                                                 | 107 ms: 1.63x faster                                       |
| mako                    | 16.3 ms                                                | 9.99 ms: 1.63x faster                                      |
| hexiom                  | 10.3 ms                                                | 6.36 ms: 1.62x faster                                      |
| pickle_pure_python      | 482 us                                                 | 301 us: 1.60x faster                                       |
| deepcopy_memo           | 58.8 us                                                | 36.9 us: 1.59x faster                                      |
| float                   | 116 ms                                                 | 73.9 ms: 1.58x faster                                      |
| nbody                   | 148 ms                                                 | 94.9 ms: 1.56x faster                                      |
| chameleon               | 9.84 ms                                                | 6.42 ms: 1.53x faster                                      |
| xml_etree_process       | 79.8 ms                                                | 53.6 ms: 1.49x faster                                      |
| pprint_safe_repr        | 1.01 sec                                               | 694 ms: 1.46x faster                                       |
| pprint_pformat          | 2.10 sec                                               | 1.45 sec: 1.45x faster                                     |
| django_template         | 47.6 ms                                                | 33.0 ms: 1.44x faster                                      |
| unpickle_pure_python    | 327 us                                                 | 227 us: 1.44x faster                                       |
| genshi_text             | 31.7 ms                                                | 22.0 ms: 1.44x faster                                      |
| logging_format          | 9.07 us                                                | 6.35 us: 1.43x faster                                      |
| logging_simple          | 8.27 us                                                | 5.82 us: 1.42x faster                                      |
| deepcopy                | 481 us                                                 | 340 us: 1.42x faster                                       |
| html5lib                | 88.1 ms                                                | 62.8 ms: 1.40x faster                                      |
| deepcopy_reduce         | 4.17 us                                                | 2.98 us: 1.40x faster                                      |
| thrift                  | 1.06 ms                                                | 763 us: 1.39x faster                                       |
| async_tree_none         | 732 ms                                                 | 525 ms: 1.39x faster                                       |
| scimark_fft             | 454 ms                                                 | 328 ms: 1.38x faster                                       |
| tornado_http            | 131 ms                                                 | 94.7 ms: 1.38x faster                                      |
| async_tree_io           | 1.79 sec                                               | 1.30 sec: 1.37x faster                                     |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 735 ms: 1.37x faster                                       |
| unpack_sequence         | 65.7 ns                                                | 48.0 ns: 1.37x faster                                      |
| async_tree_memoization  | 867 ms                                                 | 636 ms: 1.36x faster                                       |
| regex_compile           | 186 ms                                                 | 136 ms: 1.36x faster                                       |
| 2to3                    | 346 ms                                                 | 256 ms: 1.35x faster                                       |
| fannkuch                | 527 ms                                                 | 393 ms: 1.34x faster                                       |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.57 ms: 1.33x faster                                      |
| aiohttp                 | 1.41 ms                                                | 1.06 ms: 1.33x faster                                      |
| pycparser               | 1.57 sec                                               | 1.18 sec: 1.33x faster                                     |
| coroutines              | 34.5 ms                                                | 26.0 ms: 1.32x faster                                      |
| gunicorn                | 1.48 ms                                                | 1.12 ms: 1.32x faster                                      |
| xml_etree_generate      | 100.0 ms                                               | 76.7 ms: 1.30x faster                                      |
| sqlglot_normalize       | 141 ms                                                 | 109 ms: 1.30x faster                                       |
| docutils                | 3.26 sec                                               | 2.56 sec: 1.27x faster                                     |
| sqlglot_optimize        | 68.7 ms                                                | 54.0 ms: 1.27x faster                                      |
| nqueens                 | 107 ms                                                 | 83.8 ms: 1.27x faster                                      |
| json_loads              | 31.4 us                                                | 24.9 us: 1.26x faster                                      |
| genshi_xml              | 66.0 ms                                                | 52.3 ms: 1.26x faster                                      |
| sqlglot_transpile       | 2.55 ms                                                | 2.04 ms: 1.25x faster                                      |
| async_generators        | 442 ms                                                 | 356 ms: 1.24x faster                                       |
| sqlalchemy_declarative  | 170 ms                                                 | 137 ms: 1.24x faster                                       |
| sqlalchemy_imperative   | 21.9 ms                                                | 17.8 ms: 1.23x faster                                      |
| sympy_integrate         | 25.4 ms                                                | 20.7 ms: 1.23x faster                                      |
| sqlglot_parse           | 2.15 ms                                                | 1.75 ms: 1.22x faster                                      |
| regex_v8                | 26.2 ms                                                | 21.4 ms: 1.22x faster                                      |
| dulwich_log             | 77.0 ms                                                | 63.0 ms: 1.22x faster                                      |
| flaskblogging           | 8.42 ms                                                | 7.04 ms: 1.20x faster                                      |
| json                    | 5.67 ms                                                | 4.74 ms: 1.19x faster                                      |
| sqlite_synth            | 3.02 us                                                | 2.53 us: 1.19x faster                                      |
| sympy_expand            | 558 ms                                                 | 469 ms: 1.19x faster                                       |
| bench_thread_pool       | 966 us                                                 | 816 us: 1.18x faster                                       |
| sympy_str               | 337 ms                                                 | 285 ms: 1.18x faster                                       |
| pickle_list             | 5.05 us                                                | 4.27 us: 1.18x faster                                      |
| sympy_sum               | 190 ms                                                 | 162 ms: 1.18x faster                                       |
| dask                    | 432 ms                                                 | 368 ms: 1.17x faster                                       |
| regex_effbot            | 3.41 ms                                                | 2.92 ms: 1.17x faster                                      |
| pickle_dict             | 30.0 us                                                | 26.0 us: 1.15x faster                                      |
| pylint                  | 534 ms                                                 | 465 ms: 1.15x faster                                       |
| pickle                  | 10.7 us                                                | 9.37 us: 1.14x faster                                      |
| meteor_contest          | 119 ms                                                 | 105 ms: 1.14x faster                                       |
| json_dumps              | 14.3 ms                                                | 12.7 ms: 1.13x faster                                      |
| djangocms               | 37.2 us                                                | 33.2 us: 1.12x faster                                      |
| pathlib                 | 20.3 ms                                                | 18.1 ms: 1.12x faster                                      |
| unpickle                | 14.9 us                                                | 13.3 us: 1.11x faster                                      |
| regex_dna               | 215 ms                                                 | 194 ms: 1.11x faster                                       |
| comprehensions          | 28.5 us                                                | 25.9 us: 1.10x faster                                      |
| mdp                     | 2.93 sec                                               | 2.69 sec: 1.09x faster                                     |
| xml_etree_parse         | 171 ms                                                 | 158 ms: 1.08x faster                                       |
| xml_etree_iterparse     | 116 ms                                                 | 108 ms: 1.08x faster                                       |
| generators              | 78.9 ms                                                | 73.8 ms: 1.07x faster                                      |
| create_gc_cycles        | 1.61 ms                                                | 1.51 ms: 1.07x faster                                      |
| telco                   | 7.01 ms                                                | 6.59 ms: 1.06x faster                                      |
| asyncio_tcp             | 918 ms                                                 | 888 ms: 1.03x faster                                       |
| unpickle_list           | 5.10 us                                                | 4.96 us: 1.03x faster                                      |
| pidigits                | 190 ms                                                 | 194 ms: 1.02x slower                                       |
| python_startup_no_site  | 5.87 ms                                                | 6.01 ms: 1.02x slower                                      |
| gc_traversal            | 3.43 ms                                                | 3.79 ms: 1.11x slower                                      |
| Geometric mean          | (ref)                                                  | 1.32x faster                                               |

Benchmark hidden because not significant (2): mypy2, bench_mp_pool
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, coverage, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
