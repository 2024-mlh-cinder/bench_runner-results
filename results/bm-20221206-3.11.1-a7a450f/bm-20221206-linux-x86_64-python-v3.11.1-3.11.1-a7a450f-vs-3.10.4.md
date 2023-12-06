
# Results vs. 3.10.4

- fork: python
- ref: v3.11.1
- machine: linux-x86_64
- commit hash: a7a450f
- commit date: 2022-12-06
- overall geometric mean: 1.31x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 258 ms: 1.34x faster                                   |
| chameleon      | 9.84 ms                                                | 6.63 ms: 1.49x faster                                  |
| docutils       | 3.26 sec                                               | 2.57 sec: 1.27x faster                                 |
| html5lib       | 88.1 ms                                                | 63.4 ms: 1.39x faster                                  |
| tornado_http   | 131 ms                                                 | 99.8 ms: 1.31x faster                                  |
| Geometric mean | (ref)                                                  | 1.36x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 523 ms: 1.40x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 627 ms: 1.38x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.31 sec: 1.37x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 742 ms: 1.36x faster                                   |
| Geometric mean          | (ref)                                                  | 1.38x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 148 ms                                                 | 95.4 ms: 1.55x faster                                  |
| float          | 116 ms                                                 | 76.0 ms: 1.53x faster                                  |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.34x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 137 ms: 1.35x faster                                   |
| regex_v8       | 26.2 ms                                                | 22.3 ms: 1.18x faster                                  |
| regex_dna      | 215 ms                                                 | 200 ms: 1.07x faster                                   |
| regex_effbot   | 3.41 ms                                                | 3.31 ms: 1.03x faster                                  |
| Geometric mean | (ref)                                                  | 1.15x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 310 us: 1.56x faster                                   |
| xml_etree_process    | 79.8 ms                                                | 53.7 ms: 1.48x faster                                  |
| unpickle_pure_python | 327 us                                                 | 229 us: 1.43x faster                                   |
| json_loads           | 31.4 us                                                | 24.0 us: 1.31x faster                                  |
| xml_etree_generate   | 100.0 ms                                               | 76.6 ms: 1.31x faster                                  |
| pickle_list          | 5.05 us                                                | 4.17 us: 1.21x faster                                  |
| json_dumps           | 14.3 ms                                                | 12.6 ms: 1.13x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 103 ms: 1.12x faster                                   |
| unpickle             | 14.9 us                                                | 13.4 us: 1.11x faster                                  |
| pickle               | 10.7 us                                                | 9.72 us: 1.10x faster                                  |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.09x faster                                   |
| unpickle_list        | 5.10 us                                                | 4.95 us: 1.03x faster                                  |
| pickle_dict          | 30.0 us                                                | 31.1 us: 1.04x slower                                  |
| Geometric mean       | (ref)                                                  | 1.21x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.49 ms: 1.69x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 5.98 ms: 1.02x slower                                  |
| Geometric mean         | (ref)                                                  | 1.29x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.92 ms: 1.64x faster                                  |
| django_template | 47.6 ms                                                | 33.2 ms: 1.43x faster                                  |
| genshi_text     | 31.7 ms                                                | 22.1 ms: 1.43x faster                                  |
| genshi_xml      | 66.0 ms                                                | 52.5 ms: 1.26x faster                                  |
| Geometric mean  | (ref)                                                  | 1.43x faster                                           |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.67 ms: 2.13x faster                                  |
| logging_silent          | 189 ns                                                 | 102 ns: 1.85x faster                                   |
| scimark_sor             | 214 ms                                                 | 116 ms: 1.85x faster                                   |
| crypto_pyaes            | 127 ms                                                 | 72.6 ms: 1.74x faster                                  |
| scimark_monte_carlo     | 118 ms                                                 | 68.4 ms: 1.72x faster                                  |
| pyflate                 | 708 ms                                                 | 415 ms: 1.71x faster                                   |
| go                      | 238 ms                                                 | 140 ms: 1.70x faster                                   |
| raytrace                | 498 ms                                                 | 294 ms: 1.69x faster                                   |
| richards                | 79.4 ms                                                | 46.9 ms: 1.69x faster                                  |
| python_startup          | 14.3 ms                                                | 8.49 ms: 1.69x faster                                  |
| mako                    | 16.3 ms                                                | 9.92 ms: 1.64x faster                                  |
| chaos                   | 114 ms                                                 | 69.6 ms: 1.64x faster                                  |
| scimark_lu              | 175 ms                                                 | 107 ms: 1.63x faster                                   |
| spectral_norm           | 163 ms                                                 | 101 ms: 1.61x faster                                   |
| hexiom                  | 10.3 ms                                                | 6.46 ms: 1.59x faster                                  |
| deepcopy_memo           | 58.8 us                                                | 37.2 us: 1.58x faster                                  |
| sqlglot_parse           | 2.15 ms                                                | 1.38 ms: 1.56x faster                                  |
| pickle_pure_python      | 482 us                                                 | 310 us: 1.56x faster                                   |
| nbody                   | 148 ms                                                 | 95.4 ms: 1.55x faster                                  |
| float                   | 116 ms                                                 | 76.0 ms: 1.53x faster                                  |
| sqlglot_transpile       | 2.55 ms                                                | 1.68 ms: 1.52x faster                                  |
| chameleon               | 9.84 ms                                                | 6.63 ms: 1.49x faster                                  |
| xml_etree_process       | 79.8 ms                                                | 53.7 ms: 1.48x faster                                  |
| unpack_sequence         | 65.7 ns                                                | 44.6 ns: 1.47x faster                                  |
| pprint_pformat          | 2.10 sec                                               | 1.44 sec: 1.46x faster                                 |
| pprint_safe_repr        | 1.01 sec                                               | 700 ms: 1.45x faster                                   |
| django_template         | 47.6 ms                                                | 33.2 ms: 1.43x faster                                  |
| genshi_text             | 31.7 ms                                                | 22.1 ms: 1.43x faster                                  |
| unpickle_pure_python    | 327 us                                                 | 229 us: 1.43x faster                                   |
| async_tree_none         | 732 ms                                                 | 523 ms: 1.40x faster                                   |
| thrift                  | 1.06 ms                                                | 765 us: 1.39x faster                                   |
| logging_simple          | 8.27 us                                                | 5.95 us: 1.39x faster                                  |
| html5lib                | 88.1 ms                                                | 63.4 ms: 1.39x faster                                  |
| logging_format          | 9.07 us                                                | 6.54 us: 1.39x faster                                  |
| scimark_fft             | 454 ms                                                 | 327 ms: 1.39x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 627 ms: 1.38x faster                                   |
| deepcopy                | 481 us                                                 | 349 us: 1.38x faster                                   |
| fannkuch                | 527 ms                                                 | 384 ms: 1.37x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.31 sec: 1.37x faster                                 |
| coroutines              | 34.5 ms                                                | 25.3 ms: 1.36x faster                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 742 ms: 1.36x faster                                   |
| regex_compile           | 186 ms                                                 | 137 ms: 1.35x faster                                   |
| deepcopy_reduce         | 4.17 us                                                | 3.09 us: 1.35x faster                                  |
| aiohttp                 | 1.41 ms                                                | 1.05 ms: 1.35x faster                                  |
| pycparser               | 1.57 sec                                               | 1.16 sec: 1.35x faster                                 |
| 2to3                    | 346 ms                                                 | 258 ms: 1.34x faster                                   |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.59 ms: 1.33x faster                                  |
| gunicorn                | 1.48 ms                                                | 1.13 ms: 1.31x faster                                  |
| tornado_http            | 131 ms                                                 | 99.8 ms: 1.31x faster                                  |
| json_loads              | 31.4 us                                                | 24.0 us: 1.31x faster                                  |
| sqlglot_normalize       | 141 ms                                                 | 108 ms: 1.31x faster                                   |
| xml_etree_generate      | 100.0 ms                                               | 76.6 ms: 1.31x faster                                  |
| sqlglot_optimize        | 68.7 ms                                                | 53.3 ms: 1.29x faster                                  |
| docutils                | 3.26 sec                                               | 2.57 sec: 1.27x faster                                 |
| genshi_xml              | 66.0 ms                                                | 52.5 ms: 1.26x faster                                  |
| nqueens                 | 107 ms                                                 | 85.0 ms: 1.25x faster                                  |
| async_generators        | 442 ms                                                 | 358 ms: 1.23x faster                                   |
| json                    | 5.67 ms                                                | 4.63 ms: 1.23x faster                                  |
| sqlite_synth            | 3.02 us                                                | 2.47 us: 1.22x faster                                  |
| sqlalchemy_imperative   | 21.9 ms                                                | 18.0 ms: 1.22x faster                                  |
| dulwich_log             | 77.0 ms                                                | 63.5 ms: 1.21x faster                                  |
| pickle_list             | 5.05 us                                                | 4.17 us: 1.21x faster                                  |
| sympy_integrate         | 25.4 ms                                                | 21.0 ms: 1.21x faster                                  |
| sqlalchemy_declarative  | 170 ms                                                 | 141 ms: 1.20x faster                                   |
| flaskblogging           | 8.42 ms                                                | 7.07 ms: 1.19x faster                                  |
| bench_thread_pool       | 966 us                                                 | 813 us: 1.19x faster                                   |
| dask                    | 432 ms                                                 | 365 ms: 1.18x faster                                   |
| sympy_expand            | 558 ms                                                 | 472 ms: 1.18x faster                                   |
| regex_v8                | 26.2 ms                                                | 22.3 ms: 1.18x faster                                  |
| sympy_str               | 337 ms                                                 | 289 ms: 1.17x faster                                   |
| pylint                  | 534 ms                                                 | 461 ms: 1.16x faster                                   |
| sympy_sum               | 190 ms                                                 | 166 ms: 1.15x faster                                   |
| json_dumps              | 14.3 ms                                                | 12.6 ms: 1.13x faster                                  |
| meteor_contest          | 119 ms                                                 | 106 ms: 1.13x faster                                   |
| djangocms               | 37.2 us                                                | 33.1 us: 1.12x faster                                  |
| xml_etree_iterparse     | 116 ms                                                 | 103 ms: 1.12x faster                                   |
| pathlib                 | 20.3 ms                                                | 18.1 ms: 1.12x faster                                  |
| mdp                     | 2.93 sec                                               | 2.64 sec: 1.11x faster                                 |
| unpickle                | 14.9 us                                                | 13.4 us: 1.11x faster                                  |
| pickle                  | 10.7 us                                                | 9.72 us: 1.10x faster                                  |
| create_gc_cycles        | 1.61 ms                                                | 1.48 ms: 1.09x faster                                  |
| xml_etree_parse         | 171 ms                                                 | 158 ms: 1.09x faster                                   |
| generators              | 78.9 ms                                                | 73.3 ms: 1.08x faster                                  |
| regex_dna               | 215 ms                                                 | 200 ms: 1.07x faster                                   |
| telco                   | 7.01 ms                                                | 6.66 ms: 1.05x faster                                  |
| asyncio_tcp             | 918 ms                                                 | 889 ms: 1.03x faster                                   |
| regex_effbot            | 3.41 ms                                                | 3.31 ms: 1.03x faster                                  |
| unpickle_list           | 5.10 us                                                | 4.95 us: 1.03x faster                                  |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| python_startup_no_site  | 5.87 ms                                                | 5.98 ms: 1.02x slower                                  |
| pickle_dict             | 30.0 us                                                | 31.1 us: 1.04x slower                                  |
| gc_traversal            | 3.43 ms                                                | 4.26 ms: 1.24x slower                                  |
| coverage                | 82.0 ms                                                | 104 ms: 1.27x slower                                   |
| Geometric mean          | (ref)                                                  | 1.31x faster                                           |

Benchmark hidden because not significant (2): mypy2, bench_mp_pool
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
