
# Results vs. 3.10.4

- fork: faster-cpython
- ref: deopts_with_ip
- machine: linux-x86_64
- commit hash: 4d1e295
- commit date: 2023-11-12
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 286 ms: 1.21x faster                                                       |
| chameleon      | 9.84 ms                                                | 7.42 ms: 1.33x faster                                                      |
| docutils       | 3.26 sec                                               | 2.73 sec: 1.20x faster                                                     |
| tornado_http   | 131 ms                                                 | 99.3 ms: 1.32x faster                                                      |
| Geometric mean | (ref)                                                  | 1.26x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 462 ms: 1.58x faster                                                       |
| async_tree_memoization  | 867 ms                                                 | 589 ms: 1.47x faster                                                       |
| async_tree_io           | 1.79 sec                                               | 1.23 sec: 1.45x faster                                                     |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 739 ms: 1.36x faster                                                       |
| Geometric mean          | (ref)                                                  | 1.47x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 114 ms: 1.30x faster                                                       |
| float          | 116 ms                                                 | 98.5 ms: 1.18x faster                                                      |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                  | 1.16x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 160 ms: 1.16x faster                                                       |
| regex_v8       | 26.2 ms                                                | 26.1 ms: 1.00x faster                                                      |
| regex_dna      | 215 ms                                                 | 221 ms: 1.03x slower                                                       |
| regex_effbot   | 3.41 ms                                                | 3.73 ms: 1.09x slower                                                      |
| Geometric mean | (ref)                                                  | 1.01x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 314 us: 1.54x faster                                                       |
| json_dumps           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                      |
| xml_etree_process    | 79.8 ms                                                | 60.0 ms: 1.33x faster                                                      |
| unpickle_pure_python | 327 us                                                 | 246 us: 1.33x faster                                                       |
| xml_etree_generate   | 100.0 ms                                               | 88.2 ms: 1.13x faster                                                      |
| tomli_loads          | 3.06 sec                                               | 2.76 sec: 1.11x faster                                                     |
| json_loads           | 31.4 us                                                | 28.4 us: 1.11x faster                                                      |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                       |
| xml_etree_iterparse  | 116 ms                                                 | 112 ms: 1.04x faster                                                       |
| unpickle             | 14.9 us                                                | 15.0 us: 1.01x slower                                                      |
| unpickle_list        | 5.10 us                                                | 5.16 us: 1.01x slower                                                      |
| pickle_list          | 5.05 us                                                | 5.22 us: 1.03x slower                                                      |
| pickle               | 10.7 us                                                | 11.5 us: 1.08x slower                                                      |
| pickle_dict          | 30.0 us                                                | 34.3 us: 1.15x slower                                                      |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                      |
| python_startup_no_site | 5.87 ms                                                | 9.04 ms: 1.54x slower                                                      |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 14.8 ms: 1.10x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 128 us: 4.38x faster                                                       |
| generators               | 78.9 ms                                                | 29.8 ms: 2.65x faster                                                      |
| asyncio_tcp              | 918 ms                                                 | 495 ms: 1.86x faster                                                       |
| logging_silent           | 189 ns                                                 | 111 ns: 1.70x faster                                                       |
| richards_super           | 95.6 ms                                                | 56.9 ms: 1.68x faster                                                      |
| scimark_sor              | 214 ms                                                 | 130 ms: 1.65x faster                                                       |
| raytrace                 | 498 ms                                                 | 304 ms: 1.64x faster                                                       |
| deltablue                | 7.81 ms                                                | 4.90 ms: 1.59x faster                                                      |
| richards                 | 79.4 ms                                                | 50.0 ms: 1.59x faster                                                      |
| async_tree_none          | 732 ms                                                 | 462 ms: 1.58x faster                                                       |
| sqlglot_parse            | 2.15 ms                                                | 1.36 ms: 1.58x faster                                                      |
| chaos                    | 114 ms                                                 | 73.5 ms: 1.55x faster                                                      |
| coroutines               | 34.5 ms                                                | 22.2 ms: 1.55x faster                                                      |
| pickle_pure_python       | 482 us                                                 | 314 us: 1.54x faster                                                       |
| crypto_pyaes             | 127 ms                                                 | 83.0 ms: 1.53x faster                                                      |
| sqlglot_transpile        | 2.55 ms                                                | 1.68 ms: 1.52x faster                                                      |
| spectral_norm            | 163 ms                                                 | 109 ms: 1.49x faster                                                       |
| async_tree_memoization   | 867 ms                                                 | 589 ms: 1.47x faster                                                       |
| async_tree_io            | 1.79 sec                                               | 1.23 sec: 1.45x faster                                                     |
| unpack_sequence          | 65.7 ns                                                | 45.3 ns: 1.45x faster                                                      |
| go                       | 238 ms                                                 | 164 ms: 1.45x faster                                                       |
| scimark_monte_carlo      | 118 ms                                                 | 81.5 ms: 1.45x faster                                                      |
| scimark_lu               | 175 ms                                                 | 121 ms: 1.45x faster                                                       |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                                     |
| deepcopy_memo            | 58.8 us                                                | 42.5 us: 1.38x faster                                                      |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                      |
| json_dumps               | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                      |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 739 ms: 1.36x faster                                                       |
| deepcopy                 | 481 us                                                 | 356 us: 1.35x faster                                                       |
| logging_simple           | 8.27 us                                                | 6.18 us: 1.34x faster                                                      |
| xml_etree_process        | 79.8 ms                                                | 60.0 ms: 1.33x faster                                                      |
| unpickle_pure_python     | 327 us                                                 | 246 us: 1.33x faster                                                       |
| chameleon                | 9.84 ms                                                | 7.42 ms: 1.33x faster                                                      |
| sqlglot_normalize        | 141 ms                                                 | 107 ms: 1.32x faster                                                       |
| deepcopy_reduce          | 4.17 us                                                | 3.16 us: 1.32x faster                                                      |
| tornado_http             | 131 ms                                                 | 99.3 ms: 1.32x faster                                                      |
| logging_format           | 9.07 us                                                | 6.92 us: 1.31x faster                                                      |
| nbody                    | 148 ms                                                 | 114 ms: 1.30x faster                                                       |
| pyflate                  | 708 ms                                                 | 548 ms: 1.29x faster                                                       |
| sqlglot_optimize         | 68.7 ms                                                | 54.6 ms: 1.26x faster                                                      |
| mypy2                    | 442 ms                                                 | 354 ms: 1.25x faster                                                       |
| pycparser                | 1.57 sec                                               | 1.25 sec: 1.25x faster                                                     |
| pprint_pformat           | 2.10 sec                                               | 1.68 sec: 1.25x faster                                                     |
| pprint_safe_repr         | 1.01 sec                                               | 815 ms: 1.24x faster                                                       |
| sympy_sum                | 190 ms                                                 | 155 ms: 1.23x faster                                                       |
| 2to3                     | 346 ms                                                 | 286 ms: 1.21x faster                                                       |
| comprehensions           | 28.5 us                                                | 23.8 us: 1.20x faster                                                      |
| docutils                 | 3.26 sec                                               | 2.73 sec: 1.20x faster                                                     |
| sympy_integrate          | 25.4 ms                                                | 21.3 ms: 1.19x faster                                                      |
| sympy_str                | 337 ms                                                 | 284 ms: 1.19x faster                                                       |
| float                    | 116 ms                                                 | 98.5 ms: 1.18x faster                                                      |
| sympy_expand             | 558 ms                                                 | 477 ms: 1.17x faster                                                       |
| regex_compile            | 186 ms                                                 | 160 ms: 1.16x faster                                                       |
| xml_etree_generate       | 100.0 ms                                               | 88.2 ms: 1.13x faster                                                      |
| bench_thread_pool        | 966 us                                                 | 858 us: 1.13x faster                                                       |
| dulwich_log              | 77.0 ms                                                | 69.0 ms: 1.12x faster                                                      |
| tomli_loads              | 3.06 sec                                               | 2.76 sec: 1.11x faster                                                     |
| json_loads               | 31.4 us                                                | 28.4 us: 1.11x faster                                                      |
| mako                     | 16.3 ms                                                | 14.8 ms: 1.10x faster                                                      |
| fannkuch                 | 527 ms                                                 | 479 ms: 1.10x faster                                                       |
| hexiom                   | 10.3 ms                                                | 9.40 ms: 1.09x faster                                                      |
| json                     | 5.67 ms                                                | 5.20 ms: 1.09x faster                                                      |
| create_gc_cycles         | 1.61 ms                                                | 1.49 ms: 1.08x faster                                                      |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                       |
| mdp                      | 2.93 sec                                               | 2.74 sec: 1.07x faster                                                     |
| pathlib                  | 20.3 ms                                                | 19.0 ms: 1.07x faster                                                      |
| scimark_fft              | 454 ms                                                 | 427 ms: 1.06x faster                                                       |
| nqueens                  | 107 ms                                                 | 101 ms: 1.05x faster                                                       |
| xml_etree_iterparse      | 116 ms                                                 | 112 ms: 1.04x faster                                                       |
| sqlite_synth             | 3.02 us                                                | 2.92 us: 1.04x faster                                                      |
| meteor_contest           | 119 ms                                                 | 117 ms: 1.02x faster                                                       |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                       |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                       |
| regex_v8                 | 26.2 ms                                                | 26.1 ms: 1.00x faster                                                      |
| unpickle                 | 14.9 us                                                | 15.0 us: 1.01x slower                                                      |
| unpickle_list            | 5.10 us                                                | 5.16 us: 1.01x slower                                                      |
| regex_dna                | 215 ms                                                 | 221 ms: 1.03x slower                                                       |
| pickle_list              | 5.05 us                                                | 5.22 us: 1.03x slower                                                      |
| async_generators         | 442 ms                                                 | 459 ms: 1.04x slower                                                       |
| pickle                   | 10.7 us                                                | 11.5 us: 1.08x slower                                                      |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.58 ms: 1.08x slower                                                      |
| regex_effbot             | 3.41 ms                                                | 3.73 ms: 1.09x slower                                                      |
| gc_traversal             | 3.43 ms                                                | 3.83 ms: 1.12x slower                                                      |
| pickle_dict              | 30.0 us                                                | 34.3 us: 1.15x slower                                                      |
| coverage                 | 82.0 ms                                                | 95.4 ms: 1.16x slower                                                      |
| telco                    | 7.01 ms                                                | 8.95 ms: 1.28x slower                                                      |
| python_startup_no_site   | 5.87 ms                                                | 9.04 ms: 1.54x slower                                                      |
| Geometric mean           | (ref)                                                  | 1.24x faster                                                               |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231112-3.13.0a1+-4d1e295-PYTHON_UOPS/bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
