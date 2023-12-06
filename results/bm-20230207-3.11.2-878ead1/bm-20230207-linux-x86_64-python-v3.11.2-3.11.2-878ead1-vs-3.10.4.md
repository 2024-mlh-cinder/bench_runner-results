
# Results vs. 3.10.4

- fork: python
- ref: v3.11.2
- machine: linux-x86_64
- commit hash: 878ead1
- commit date: 2023-02-07
- overall geometric mean: 1.31x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 257 ms: 1.34x faster                                   |
| chameleon      | 9.84 ms                                                | 6.49 ms: 1.52x faster                                  |
| docutils       | 3.26 sec                                               | 2.55 sec: 1.28x faster                                 |
| html5lib       | 88.1 ms                                                | 64.0 ms: 1.38x faster                                  |
| tornado_http   | 131 ms                                                 | 96.1 ms: 1.36x faster                                  |
| Geometric mean | (ref)                                                  | 1.37x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 524 ms: 1.40x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 628 ms: 1.38x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.30 sec: 1.38x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 740 ms: 1.36x faster                                   |
| Geometric mean          | (ref)                                                  | 1.38x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 148 ms                                                 | 93.0 ms: 1.59x faster                                  |
| float          | 116 ms                                                 | 76.6 ms: 1.52x faster                                  |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.34x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 138 ms: 1.34x faster                                   |
| regex_v8       | 26.2 ms                                                | 21.3 ms: 1.23x faster                                  |
| regex_dna      | 215 ms                                                 | 192 ms: 1.12x faster                                   |
| regex_effbot   | 3.41 ms                                                | 3.39 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.17x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 305 us: 1.58x faster                                   |
| xml_etree_process    | 79.8 ms                                                | 53.8 ms: 1.48x faster                                  |
| unpickle_pure_python | 327 us                                                 | 228 us: 1.43x faster                                   |
| xml_etree_generate   | 100.0 ms                                               | 76.5 ms: 1.31x faster                                  |
| pickle_list          | 5.05 us                                                | 4.16 us: 1.21x faster                                  |
| json_loads           | 31.4 us                                                | 26.2 us: 1.20x faster                                  |
| json_dumps           | 14.3 ms                                                | 12.5 ms: 1.15x faster                                  |
| unpickle             | 14.9 us                                                | 13.2 us: 1.12x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 104 ms: 1.12x faster                                   |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.07x faster                                   |
| pickle               | 10.7 us                                                | 10.00 us: 1.07x faster                                 |
| unpickle_list        | 5.10 us                                                | 4.94 us: 1.03x faster                                  |
| pickle_dict          | 30.0 us                                                | 31.4 us: 1.05x slower                                  |
| Geometric mean       | (ref)                                                  | 1.20x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.47 ms: 1.69x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 5.97 ms: 1.02x slower                                  |
| Geometric mean         | (ref)                                                  | 1.29x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.83 ms: 1.66x faster                                  |
| genshi_text     | 31.7 ms                                                | 21.7 ms: 1.46x faster                                  |
| django_template | 47.6 ms                                                | 32.7 ms: 1.45x faster                                  |
| genshi_xml      | 66.0 ms                                                | 51.5 ms: 1.28x faster                                  |
| Geometric mean  | (ref)                                                  | 1.46x faster                                           |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-linux-x86_64-python-v3.11.2-3.11.2-878ead1 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.68 ms: 2.13x faster                                  |
| logging_silent          | 189 ns                                                 | 99.8 ns: 1.89x faster                                  |
| scimark_sor             | 214 ms                                                 | 115 ms: 1.87x faster                                   |
| richards                | 79.4 ms                                                | 45.6 ms: 1.74x faster                                  |
| scimark_monte_carlo     | 118 ms                                                 | 67.7 ms: 1.74x faster                                  |
| crypto_pyaes            | 127 ms                                                 | 73.8 ms: 1.72x faster                                  |
| raytrace                | 498 ms                                                 | 291 ms: 1.71x faster                                   |
| pyflate                 | 708 ms                                                 | 417 ms: 1.70x faster                                   |
| python_startup          | 14.3 ms                                                | 8.47 ms: 1.69x faster                                  |
| go                      | 238 ms                                                 | 141 ms: 1.68x faster                                   |
| chaos                   | 114 ms                                                 | 68.2 ms: 1.68x faster                                  |
| mako                    | 16.3 ms                                                | 9.83 ms: 1.66x faster                                  |
| spectral_norm           | 163 ms                                                 | 98.4 ms: 1.66x faster                                  |
| scimark_lu              | 175 ms                                                 | 107 ms: 1.64x faster                                   |
| hexiom                  | 10.3 ms                                                | 6.36 ms: 1.62x faster                                  |
| deepcopy_memo           | 58.8 us                                                | 36.8 us: 1.60x faster                                  |
| nbody                   | 148 ms                                                 | 93.0 ms: 1.59x faster                                  |
| pickle_pure_python      | 482 us                                                 | 305 us: 1.58x faster                                   |
| sqlglot_parse           | 2.15 ms                                                | 1.38 ms: 1.56x faster                                  |
| sqlglot_transpile       | 2.55 ms                                                | 1.67 ms: 1.53x faster                                  |
| float                   | 116 ms                                                 | 76.6 ms: 1.52x faster                                  |
| chameleon               | 9.84 ms                                                | 6.49 ms: 1.52x faster                                  |
| xml_etree_process       | 79.8 ms                                                | 53.8 ms: 1.48x faster                                  |
| genshi_text             | 31.7 ms                                                | 21.7 ms: 1.46x faster                                  |
| pprint_safe_repr        | 1.01 sec                                               | 697 ms: 1.46x faster                                   |
| django_template         | 47.6 ms                                                | 32.7 ms: 1.45x faster                                  |
| pprint_pformat          | 2.10 sec                                               | 1.45 sec: 1.45x faster                                 |
| unpickle_pure_python    | 327 us                                                 | 228 us: 1.43x faster                                   |
| pycparser               | 1.57 sec                                               | 1.11 sec: 1.41x faster                                 |
| logging_format          | 9.07 us                                                | 6.49 us: 1.40x faster                                  |
| async_tree_none         | 732 ms                                                 | 524 ms: 1.40x faster                                   |
| scimark_fft             | 454 ms                                                 | 327 ms: 1.39x faster                                   |
| logging_simple          | 8.27 us                                                | 5.97 us: 1.39x faster                                  |
| deepcopy                | 481 us                                                 | 348 us: 1.38x faster                                   |
| thrift                  | 1.06 ms                                                | 770 us: 1.38x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 628 ms: 1.38x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.30 sec: 1.38x faster                                 |
| html5lib                | 88.1 ms                                                | 64.0 ms: 1.38x faster                                  |
| deepcopy_reduce         | 4.17 us                                                | 3.04 us: 1.37x faster                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 740 ms: 1.36x faster                                   |
| tornado_http            | 131 ms                                                 | 96.1 ms: 1.36x faster                                  |
| aiohttp                 | 1.41 ms                                                | 1.05 ms: 1.35x faster                                  |
| unpack_sequence         | 65.7 ns                                                | 48.8 ns: 1.35x faster                                  |
| fannkuch                | 527 ms                                                 | 392 ms: 1.35x faster                                   |
| coroutines              | 34.5 ms                                                | 25.6 ms: 1.35x faster                                  |
| regex_compile           | 186 ms                                                 | 138 ms: 1.34x faster                                   |
| 2to3                    | 346 ms                                                 | 257 ms: 1.34x faster                                   |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.63 ms: 1.32x faster                                  |
| gunicorn                | 1.48 ms                                                | 1.13 ms: 1.31x faster                                  |
| xml_etree_generate      | 100.0 ms                                               | 76.5 ms: 1.31x faster                                  |
| sqlglot_normalize       | 141 ms                                                 | 109 ms: 1.30x faster                                   |
| sqlglot_optimize        | 68.7 ms                                                | 53.3 ms: 1.29x faster                                  |
| nqueens                 | 107 ms                                                 | 83.1 ms: 1.28x faster                                  |
| docutils                | 3.26 sec                                               | 2.55 sec: 1.28x faster                                 |
| genshi_xml              | 66.0 ms                                                | 51.5 ms: 1.28x faster                                  |
| async_generators        | 442 ms                                                 | 357 ms: 1.24x faster                                   |
| regex_v8                | 26.2 ms                                                | 21.3 ms: 1.23x faster                                  |
| sqlite_synth            | 3.02 us                                                | 2.46 us: 1.23x faster                                  |
| sympy_integrate         | 25.4 ms                                                | 20.8 ms: 1.22x faster                                  |
| pickle_list             | 5.05 us                                                | 4.16 us: 1.21x faster                                  |
| dulwich_log             | 77.0 ms                                                | 63.7 ms: 1.21x faster                                  |
| sqlalchemy_imperative   | 21.9 ms                                                | 18.2 ms: 1.20x faster                                  |
| sqlalchemy_declarative  | 170 ms                                                 | 141 ms: 1.20x faster                                   |
| json_loads              | 31.4 us                                                | 26.2 us: 1.20x faster                                  |
| flaskblogging           | 8.42 ms                                                | 7.02 ms: 1.20x faster                                  |
| sympy_expand            | 558 ms                                                 | 468 ms: 1.19x faster                                   |
| bench_thread_pool       | 966 us                                                 | 812 us: 1.19x faster                                   |
| dask                    | 432 ms                                                 | 365 ms: 1.19x faster                                   |
| sympy_str               | 337 ms                                                 | 288 ms: 1.17x faster                                   |
| json                    | 5.67 ms                                                | 4.92 ms: 1.15x faster                                  |
| djangocms               | 37.2 us                                                | 32.3 us: 1.15x faster                                  |
| sympy_sum               | 190 ms                                                 | 166 ms: 1.15x faster                                   |
| json_dumps              | 14.3 ms                                                | 12.5 ms: 1.15x faster                                  |
| meteor_contest          | 119 ms                                                 | 105 ms: 1.14x faster                                   |
| pathlib                 | 20.3 ms                                                | 17.8 ms: 1.14x faster                                  |
| pylint                  | 534 ms                                                 | 475 ms: 1.13x faster                                   |
| unpickle                | 14.9 us                                                | 13.2 us: 1.12x faster                                  |
| xml_etree_iterparse     | 116 ms                                                 | 104 ms: 1.12x faster                                   |
| regex_dna               | 215 ms                                                 | 192 ms: 1.12x faster                                   |
| create_gc_cycles        | 1.61 ms                                                | 1.49 ms: 1.08x faster                                  |
| xml_etree_parse         | 171 ms                                                 | 159 ms: 1.07x faster                                   |
| pickle                  | 10.7 us                                                | 10.00 us: 1.07x faster                                 |
| generators              | 78.9 ms                                                | 74.1 ms: 1.06x faster                                  |
| telco                   | 7.01 ms                                                | 6.59 ms: 1.06x faster                                  |
| mdp                     | 2.93 sec                                               | 2.77 sec: 1.06x faster                                 |
| asyncio_tcp             | 918 ms                                                 | 884 ms: 1.04x faster                                   |
| unpickle_list           | 5.10 us                                                | 4.94 us: 1.03x faster                                  |
| regex_effbot            | 3.41 ms                                                | 3.39 ms: 1.01x faster                                  |
| pidigits                | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| python_startup_no_site  | 5.87 ms                                                | 5.97 ms: 1.02x slower                                  |
| pickle_dict             | 30.0 us                                                | 31.4 us: 1.05x slower                                  |
| gc_traversal            | 3.43 ms                                                | 4.15 ms: 1.21x slower                                  |
| coverage                | 82.0 ms                                                | 103 ms: 1.26x slower                                   |
| Geometric mean          | (ref)                                                  | 1.31x faster                                           |

Benchmark hidden because not significant (2): mypy2, bench_mp_pool
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.25x
