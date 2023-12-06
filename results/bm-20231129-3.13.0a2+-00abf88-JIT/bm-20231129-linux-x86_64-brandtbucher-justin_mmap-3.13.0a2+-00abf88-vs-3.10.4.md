
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_mmap
- machine: linux-x86_64
- commit hash: 00abf88
- commit date: 2023-11-29
- overall geometric mean: 1.27x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 277 ms: 1.25x faster                                                |
| chameleon      | 9.84 ms                                                | 7.08 ms: 1.39x faster                                               |
| docutils       | 3.26 sec                                               | 2.69 sec: 1.21x faster                                              |
| tornado_http   | 131 ms                                                 | 97.4 ms: 1.34x faster                                               |
| Geometric mean | (ref)                                                  | 1.30x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 442 ms: 1.65x faster                                                |
| async_tree_memoization  | 867 ms                                                 | 574 ms: 1.51x faster                                                |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                              |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 713 ms: 1.41x faster                                                |
| Geometric mean          | (ref)                                                  | 1.52x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 101 ms: 1.46x faster                                                |
| float          | 116 ms                                                 | 85.5 ms: 1.36x faster                                               |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                  | 1.26x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 146 ms: 1.27x faster                                                |
| regex_v8       | 26.2 ms                                                | 26.0 ms: 1.01x faster                                               |
| regex_dna      | 215 ms                                                 | 222 ms: 1.03x slower                                                |
| regex_effbot   | 3.41 ms                                                | 3.73 ms: 1.09x slower                                               |
| Geometric mean | (ref)                                                  | 1.03x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 307 us: 1.57x faster                                                |
| unpickle_pure_python | 327 us                                                 | 233 us: 1.40x faster                                                |
| tomli_loads          | 3.06 sec                                               | 2.22 sec: 1.38x faster                                              |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                               |
| xml_etree_process    | 79.8 ms                                                | 61.4 ms: 1.30x faster                                               |
| xml_etree_generate   | 100.0 ms                                               | 89.4 ms: 1.12x faster                                               |
| json_loads           | 31.4 us                                                | 28.1 us: 1.12x faster                                               |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.07x faster                                                |
| xml_etree_iterparse  | 116 ms                                                 | 111 ms: 1.04x faster                                                |
| unpickle             | 14.9 us                                                | 15.5 us: 1.05x slower                                               |
| pickle               | 10.7 us                                                | 11.7 us: 1.10x slower                                               |
| pickle_dict          | 30.0 us                                                | 35.6 us: 1.19x slower                                               |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                        |

Benchmark hidden because not significant (2): pickle_list, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.5 ms: 1.37x faster                                               |
| python_startup_no_site | 5.87 ms                                                | 9.13 ms: 1.55x slower                                               |
| Geometric mean         | (ref)                                                  | 1.07x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.3 ms: 1.32x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 119 us: 4.69x faster                                                |
| generators               | 78.9 ms                                                | 28.8 ms: 2.74x faster                                               |
| deltablue                | 7.81 ms                                                | 4.10 ms: 1.91x faster                                               |
| asyncio_tcp              | 918 ms                                                 | 489 ms: 1.88x faster                                                |
| richards_super           | 95.6 ms                                                | 53.3 ms: 1.79x faster                                               |
| logging_silent           | 189 ns                                                 | 109 ns: 1.73x faster                                                |
| raytrace                 | 498 ms                                                 | 289 ms: 1.72x faster                                                |
| scimark_sor              | 214 ms                                                 | 125 ms: 1.71x faster                                                |
| richards                 | 79.4 ms                                                | 46.9 ms: 1.69x faster                                               |
| async_tree_none          | 732 ms                                                 | 442 ms: 1.65x faster                                                |
| chaos                    | 114 ms                                                 | 70.1 ms: 1.63x faster                                               |
| sqlglot_parse            | 2.15 ms                                                | 1.32 ms: 1.62x faster                                               |
| crypto_pyaes             | 127 ms                                                 | 79.0 ms: 1.60x faster                                               |
| go                       | 238 ms                                                 | 151 ms: 1.57x faster                                                |
| pickle_pure_python       | 482 us                                                 | 307 us: 1.57x faster                                                |
| sqlglot_transpile        | 2.55 ms                                                | 1.65 ms: 1.55x faster                                               |
| scimark_monte_carlo      | 118 ms                                                 | 76.9 ms: 1.53x faster                                               |
| coroutines               | 34.5 ms                                                | 22.6 ms: 1.53x faster                                               |
| async_tree_memoization   | 867 ms                                                 | 574 ms: 1.51x faster                                                |
| scimark_lu               | 175 ms                                                 | 116 ms: 1.51x faster                                                |
| deepcopy_memo            | 58.8 us                                                | 39.0 us: 1.51x faster                                               |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                              |
| comprehensions           | 28.5 us                                                | 19.5 us: 1.46x faster                                               |
| nbody                    | 148 ms                                                 | 101 ms: 1.46x faster                                                |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                              |
| logging_simple           | 8.27 us                                                | 5.82 us: 1.42x faster                                               |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 713 ms: 1.41x faster                                                |
| pyflate                  | 708 ms                                                 | 501 ms: 1.41x faster                                                |
| logging_format           | 9.07 us                                                | 6.45 us: 1.41x faster                                               |
| unpickle_pure_python     | 327 us                                                 | 233 us: 1.40x faster                                                |
| chameleon                | 9.84 ms                                                | 7.08 ms: 1.39x faster                                               |
| tomli_loads              | 3.06 sec                                               | 2.22 sec: 1.38x faster                                              |
| python_startup           | 14.3 ms                                                | 10.5 ms: 1.37x faster                                               |
| deepcopy                 | 481 us                                                 | 353 us: 1.36x faster                                                |
| float                    | 116 ms                                                 | 85.5 ms: 1.36x faster                                               |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                               |
| tornado_http             | 131 ms                                                 | 97.4 ms: 1.34x faster                                               |
| deepcopy_reduce          | 4.17 us                                                | 3.14 us: 1.33x faster                                               |
| mako                     | 16.3 ms                                                | 12.3 ms: 1.32x faster                                               |
| xml_etree_process        | 79.8 ms                                                | 61.4 ms: 1.30x faster                                               |
| pprint_pformat           | 2.10 sec                                               | 1.62 sec: 1.30x faster                                              |
| hexiom                   | 10.3 ms                                                | 7.94 ms: 1.30x faster                                               |
| pprint_safe_repr         | 1.01 sec                                               | 785 ms: 1.29x faster                                                |
| pycparser                | 1.57 sec                                               | 1.22 sec: 1.28x faster                                              |
| regex_compile            | 186 ms                                                 | 146 ms: 1.27x faster                                                |
| sqlglot_normalize        | 141 ms                                                 | 111 ms: 1.27x faster                                                |
| 2to3                     | 346 ms                                                 | 277 ms: 1.25x faster                                                |
| docutils                 | 3.26 sec                                               | 2.69 sec: 1.21x faster                                              |
| sqlglot_optimize         | 68.7 ms                                                | 56.7 ms: 1.21x faster                                               |
| fannkuch                 | 527 ms                                                 | 438 ms: 1.20x faster                                                |
| sympy_integrate          | 25.4 ms                                                | 21.2 ms: 1.20x faster                                               |
| sympy_sum                | 190 ms                                                 | 160 ms: 1.19x faster                                                |
| scimark_fft              | 454 ms                                                 | 384 ms: 1.18x faster                                                |
| dask                     | 432 ms                                                 | 367 ms: 1.18x faster                                                |
| sympy_str                | 337 ms                                                 | 288 ms: 1.17x faster                                                |
| sympy_expand             | 558 ms                                                 | 479 ms: 1.16x faster                                                |
| spectral_norm            | 163 ms                                                 | 141 ms: 1.16x faster                                                |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.28 ms: 1.16x faster                                               |
| dulwich_log              | 77.0 ms                                                | 67.5 ms: 1.14x faster                                               |
| bench_thread_pool        | 966 us                                                 | 852 us: 1.13x faster                                                |
| unpack_sequence          | 65.7 ns                                                | 58.1 ns: 1.13x faster                                               |
| nqueens                  | 107 ms                                                 | 94.4 ms: 1.13x faster                                               |
| xml_etree_generate       | 100.0 ms                                               | 89.4 ms: 1.12x faster                                               |
| json_loads               | 31.4 us                                                | 28.1 us: 1.12x faster                                               |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                               |
| json                     | 5.67 ms                                                | 5.22 ms: 1.09x faster                                               |
| pathlib                  | 20.3 ms                                                | 18.7 ms: 1.09x faster                                               |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.07x faster                                                |
| sqlite_synth             | 3.02 us                                                | 2.83 us: 1.07x faster                                               |
| meteor_contest           | 119 ms                                                 | 112 ms: 1.07x faster                                                |
| xml_etree_iterparse      | 116 ms                                                 | 111 ms: 1.04x faster                                                |
| mdp                      | 2.93 sec                                               | 2.82 sec: 1.04x faster                                              |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                                |
| regex_v8                 | 26.2 ms                                                | 26.0 ms: 1.01x faster                                               |
| regex_dna                | 215 ms                                                 | 222 ms: 1.03x slower                                                |
| unpickle                 | 14.9 us                                                | 15.5 us: 1.05x slower                                               |
| async_generators         | 442 ms                                                 | 463 ms: 1.05x slower                                                |
| regex_effbot             | 3.41 ms                                                | 3.73 ms: 1.09x slower                                               |
| pickle                   | 10.7 us                                                | 11.7 us: 1.10x slower                                               |
| coverage                 | 82.0 ms                                                | 96.2 ms: 1.17x slower                                               |
| pickle_dict              | 30.0 us                                                | 35.6 us: 1.19x slower                                               |
| telco                    | 7.01 ms                                                | 8.51 ms: 1.21x slower                                               |
| gc_traversal             | 3.43 ms                                                | 4.16 ms: 1.21x slower                                               |
| python_startup_no_site   | 5.87 ms                                                | 9.13 ms: 1.55x slower                                               |
| mypy2                    | 442 ms                                                 | 870 ms: 1.97x slower                                                |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                        |

Benchmark hidden because not significant (3): bench_mp_pool, pickle_list, unpickle_list
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231129-3.13.0a2+-00abf88-JIT/bm-20231129-linux-x86_64-brandtbucher-justin_mmap-3.13.0a2+-00abf88.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.18x
