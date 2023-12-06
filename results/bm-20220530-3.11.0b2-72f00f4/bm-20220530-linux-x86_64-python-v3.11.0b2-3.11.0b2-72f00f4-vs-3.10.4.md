
# Results vs. 3.10.4

- fork: python
- ref: v3.11.0b2
- machine: linux-x86_64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.31x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 256 ms: 1.35x faster                                       |
| chameleon      | 9.84 ms                                                | 6.62 ms: 1.49x faster                                      |
| docutils       | 3.26 sec                                               | 2.56 sec: 1.28x faster                                     |
| html5lib       | 88.1 ms                                                | 63.7 ms: 1.38x faster                                      |
| tornado_http   | 131 ms                                                 | 94.9 ms: 1.38x faster                                      |
| Geometric mean | (ref)                                                  | 1.37x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 526 ms: 1.39x faster                                       |
| async_tree_memoization  | 867 ms                                                 | 628 ms: 1.38x faster                                       |
| async_tree_io           | 1.79 sec                                               | 1.31 sec: 1.37x faster                                     |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 743 ms: 1.36x faster                                       |
| Geometric mean          | (ref)                                                  | 1.37x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 148 ms                                                 | 92.0 ms: 1.61x faster                                      |
| float          | 116 ms                                                 | 74.4 ms: 1.56x faster                                      |
| pidigits       | 190 ms                                                 | 199 ms: 1.05x slower                                       |
| Geometric mean | (ref)                                                  | 1.34x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 138 ms: 1.35x faster                                       |
| regex_v8       | 26.2 ms                                                | 22.0 ms: 1.19x faster                                      |
| regex_effbot   | 3.41 ms                                                | 3.11 ms: 1.10x faster                                      |
| regex_dna      | 215 ms                                                 | 196 ms: 1.10x faster                                       |
| Geometric mean | (ref)                                                  | 1.18x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                       |
| xml_etree_process    | 79.8 ms                                                | 53.4 ms: 1.49x faster                                      |
| unpickle_pure_python | 327 us                                                 | 227 us: 1.44x faster                                       |
| xml_etree_generate   | 100.0 ms                                               | 76.1 ms: 1.31x faster                                      |
| json_loads           | 31.4 us                                                | 25.0 us: 1.25x faster                                      |
| pickle_list          | 5.05 us                                                | 4.30 us: 1.17x faster                                      |
| pickle_dict          | 30.0 us                                                | 26.4 us: 1.13x faster                                      |
| pickle               | 10.7 us                                                | 9.44 us: 1.13x faster                                      |
| json_dumps           | 14.3 ms                                                | 12.8 ms: 1.12x faster                                      |
| unpickle             | 14.9 us                                                | 13.3 us: 1.12x faster                                      |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.10x faster                                       |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                       |
| unpickle_list        | 5.10 us                                                | 5.00 us: 1.02x faster                                      |
| Geometric mean       | (ref)                                                  | 1.22x faster                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.49 ms: 1.69x faster                                      |
| python_startup_no_site | 5.87 ms                                                | 5.99 ms: 1.02x slower                                      |
| Geometric mean         | (ref)                                                  | 1.29x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.96 ms: 1.64x faster                                      |
| genshi_text     | 31.7 ms                                                | 21.5 ms: 1.47x faster                                      |
| django_template | 47.6 ms                                                | 32.6 ms: 1.46x faster                                      |
| genshi_xml      | 66.0 ms                                                | 52.4 ms: 1.26x faster                                      |
| Geometric mean  | (ref)                                                  | 1.45x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20220530-linux-x86_64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.84 ms: 2.03x faster                                      |
| scimark_sor             | 214 ms                                                 | 115 ms: 1.87x faster                                       |
| logging_silent          | 189 ns                                                 | 103 ns: 1.84x faster                                       |
| scimark_monte_carlo     | 118 ms                                                 | 66.0 ms: 1.79x faster                                      |
| richards                | 79.4 ms                                                | 44.5 ms: 1.79x faster                                      |
| raytrace                | 498 ms                                                 | 287 ms: 1.73x faster                                       |
| pyflate                 | 708 ms                                                 | 413 ms: 1.72x faster                                       |
| go                      | 238 ms                                                 | 139 ms: 1.71x faster                                       |
| chaos                   | 114 ms                                                 | 67.3 ms: 1.70x faster                                      |
| crypto_pyaes            | 127 ms                                                 | 74.8 ms: 1.69x faster                                      |
| python_startup          | 14.3 ms                                                | 8.49 ms: 1.69x faster                                      |
| spectral_norm           | 163 ms                                                 | 97.3 ms: 1.68x faster                                      |
| hexiom                  | 10.3 ms                                                | 6.27 ms: 1.64x faster                                      |
| deepcopy_memo           | 58.8 us                                                | 35.9 us: 1.64x faster                                      |
| mako                    | 16.3 ms                                                | 9.96 ms: 1.64x faster                                      |
| nbody                   | 148 ms                                                 | 92.0 ms: 1.61x faster                                      |
| scimark_lu              | 175 ms                                                 | 109 ms: 1.61x faster                                       |
| pickle_pure_python      | 482 us                                                 | 305 us: 1.58x faster                                       |
| float                   | 116 ms                                                 | 74.4 ms: 1.56x faster                                      |
| xml_etree_process       | 79.8 ms                                                | 53.4 ms: 1.49x faster                                      |
| chameleon               | 9.84 ms                                                | 6.62 ms: 1.49x faster                                      |
| genshi_text             | 31.7 ms                                                | 21.5 ms: 1.47x faster                                      |
| django_template         | 47.6 ms                                                | 32.6 ms: 1.46x faster                                      |
| pprint_safe_repr        | 1.01 sec                                               | 699 ms: 1.45x faster                                       |
| pprint_pformat          | 2.10 sec                                               | 1.45 sec: 1.45x faster                                     |
| unpickle_pure_python    | 327 us                                                 | 227 us: 1.44x faster                                       |
| logging_simple          | 8.27 us                                                | 5.74 us: 1.44x faster                                      |
| logging_format          | 9.07 us                                                | 6.34 us: 1.43x faster                                      |
| unpack_sequence         | 65.7 ns                                                | 46.2 ns: 1.42x faster                                      |
| thrift                  | 1.06 ms                                                | 750 us: 1.42x faster                                       |
| deepcopy                | 481 us                                                 | 340 us: 1.42x faster                                       |
| async_tree_none         | 732 ms                                                 | 526 ms: 1.39x faster                                       |
| html5lib                | 88.1 ms                                                | 63.7 ms: 1.38x faster                                      |
| scimark_fft             | 454 ms                                                 | 329 ms: 1.38x faster                                       |
| async_tree_memoization  | 867 ms                                                 | 628 ms: 1.38x faster                                       |
| tornado_http            | 131 ms                                                 | 94.9 ms: 1.38x faster                                      |
| deepcopy_reduce         | 4.17 us                                                | 3.03 us: 1.38x faster                                      |
| pycparser               | 1.57 sec                                               | 1.14 sec: 1.37x faster                                     |
| async_tree_io           | 1.79 sec                                               | 1.31 sec: 1.37x faster                                     |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 743 ms: 1.36x faster                                       |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.51 ms: 1.35x faster                                      |
| 2to3                    | 346 ms                                                 | 256 ms: 1.35x faster                                       |
| regex_compile           | 186 ms                                                 | 138 ms: 1.35x faster                                       |
| coroutines              | 34.5 ms                                                | 25.7 ms: 1.34x faster                                      |
| aiohttp                 | 1.41 ms                                                | 1.06 ms: 1.34x faster                                      |
| xml_etree_generate      | 100.0 ms                                               | 76.1 ms: 1.31x faster                                      |
| gunicorn                | 1.48 ms                                                | 1.13 ms: 1.31x faster                                      |
| fannkuch                | 527 ms                                                 | 403 ms: 1.31x faster                                       |
| sqlglot_normalize       | 141 ms                                                 | 110 ms: 1.29x faster                                       |
| docutils                | 3.26 sec                                               | 2.56 sec: 1.28x faster                                     |
| sqlglot_optimize        | 68.7 ms                                                | 53.9 ms: 1.28x faster                                      |
| nqueens                 | 107 ms                                                 | 84.2 ms: 1.27x faster                                      |
| genshi_xml              | 66.0 ms                                                | 52.4 ms: 1.26x faster                                      |
| json_loads              | 31.4 us                                                | 25.0 us: 1.25x faster                                      |
| async_generators        | 442 ms                                                 | 354 ms: 1.25x faster                                       |
| sqlglot_transpile       | 2.55 ms                                                | 2.05 ms: 1.25x faster                                      |
| sqlalchemy_declarative  | 170 ms                                                 | 137 ms: 1.24x faster                                       |
| sympy_integrate         | 25.4 ms                                                | 20.7 ms: 1.23x faster                                      |
| sqlglot_parse           | 2.15 ms                                                | 1.75 ms: 1.22x faster                                      |
| sqlalchemy_imperative   | 21.9 ms                                                | 17.9 ms: 1.22x faster                                      |
| dulwich_log             | 77.0 ms                                                | 63.1 ms: 1.22x faster                                      |
| sqlite_synth            | 3.02 us                                                | 2.52 us: 1.20x faster                                      |
| regex_v8                | 26.2 ms                                                | 22.0 ms: 1.19x faster                                      |
| json                    | 5.67 ms                                                | 4.75 ms: 1.19x faster                                      |
| bench_thread_pool       | 966 us                                                 | 811 us: 1.19x faster                                       |
| sympy_sum               | 190 ms                                                 | 161 ms: 1.18x faster                                       |
| sympy_expand            | 558 ms                                                 | 475 ms: 1.18x faster                                       |
| dask                    | 432 ms                                                 | 368 ms: 1.18x faster                                       |
| pickle_list             | 5.05 us                                                | 4.30 us: 1.17x faster                                      |
| sympy_str               | 337 ms                                                 | 288 ms: 1.17x faster                                       |
| pylint                  | 534 ms                                                 | 462 ms: 1.16x faster                                       |
| meteor_contest          | 119 ms                                                 | 104 ms: 1.14x faster                                       |
| pickle_dict             | 30.0 us                                                | 26.4 us: 1.13x faster                                      |
| pickle                  | 10.7 us                                                | 9.44 us: 1.13x faster                                      |
| pathlib                 | 20.3 ms                                                | 18.1 ms: 1.12x faster                                      |
| json_dumps              | 14.3 ms                                                | 12.8 ms: 1.12x faster                                      |
| unpickle                | 14.9 us                                                | 13.3 us: 1.12x faster                                      |
| djangocms               | 37.2 us                                                | 33.5 us: 1.11x faster                                      |
| xml_etree_iterparse     | 116 ms                                                 | 105 ms: 1.10x faster                                       |
| comprehensions          | 28.5 us                                                | 26.0 us: 1.10x faster                                      |
| mdp                     | 2.93 sec                                               | 2.67 sec: 1.10x faster                                     |
| regex_effbot            | 3.41 ms                                                | 3.11 ms: 1.10x faster                                      |
| regex_dna               | 215 ms                                                 | 196 ms: 1.10x faster                                       |
| xml_etree_parse         | 171 ms                                                 | 159 ms: 1.08x faster                                       |
| telco                   | 7.01 ms                                                | 6.54 ms: 1.07x faster                                      |
| create_gc_cycles        | 1.61 ms                                                | 1.51 ms: 1.07x faster                                      |
| generators              | 78.9 ms                                                | 74.4 ms: 1.06x faster                                      |
| asyncio_tcp             | 918 ms                                                 | 890 ms: 1.03x faster                                       |
| unpickle_list           | 5.10 us                                                | 5.00 us: 1.02x faster                                      |
| python_startup_no_site  | 5.87 ms                                                | 5.99 ms: 1.02x slower                                      |
| pidigits                | 190 ms                                                 | 199 ms: 1.05x slower                                       |
| gc_traversal            | 3.43 ms                                                | 4.21 ms: 1.23x slower                                      |
| Geometric mean          | (ref)                                                  | 1.31x faster                                               |

Benchmark hidden because not significant (2): mypy2, bench_mp_pool
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, coverage, flaskblogging, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.25x
