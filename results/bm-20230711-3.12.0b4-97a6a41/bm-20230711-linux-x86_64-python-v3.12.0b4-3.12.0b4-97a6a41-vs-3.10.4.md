
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b4
- machine: linux-x86_64
- commit hash: 97a6a41
- commit date: 2023-07-11
- overall geometric mean: 1.34x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 267 ms: 1.29x faster                                       |
| docutils       | 3.26 sec                                               | 2.70 sec: 1.21x faster                                     |
| tornado_http   | 131 ms                                                 | 99.1 ms: 1.32x faster                                      |
| Geometric mean | (ref)                                                  | 1.27x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 472 ms: 1.55x faster                                       |
| async_tree_io           | 1.79 sec                                               | 1.16 sec: 1.54x faster                                     |
| async_tree_memoization  | 867 ms                                                 | 573 ms: 1.51x faster                                       |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 715 ms: 1.41x faster                                       |
| Geometric mean          | (ref)                                                  | 1.50x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 148 ms                                                 | 89.2 ms: 1.66x faster                                      |
| float          | 116 ms                                                 | 80.7 ms: 1.44x faster                                      |
| pidigits       | 190 ms                                                 | 192 ms: 1.01x slower                                       |
| Geometric mean | (ref)                                                  | 1.34x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 142 ms: 1.30x faster                                       |
| regex_v8       | 26.2 ms                                                | 23.0 ms: 1.14x faster                                      |
| regex_dna      | 215 ms                                                 | 207 ms: 1.04x faster                                       |
| regex_effbot   | 3.41 ms                                                | 3.57 ms: 1.05x slower                                      |
| Geometric mean | (ref)                                                  | 1.10x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 306 us: 1.58x faster                                       |
| unpickle_pure_python | 327 us                                                 | 217 us: 1.51x faster                                       |
| json_dumps           | 14.3 ms                                                | 9.66 ms: 1.48x faster                                      |
| tomli_loads          | 3.06 sec                                               | 2.23 sec: 1.37x faster                                     |
| xml_etree_process    | 79.8 ms                                                | 59.4 ms: 1.34x faster                                      |
| json_loads           | 31.4 us                                                | 25.7 us: 1.22x faster                                      |
| xml_etree_generate   | 100.0 ms                                               | 85.0 ms: 1.18x faster                                      |
| xml_etree_iterparse  | 116 ms                                                 | 102 ms: 1.14x faster                                       |
| xml_etree_parse      | 171 ms                                                 | 152 ms: 1.12x faster                                       |
| pickle_list          | 5.05 us                                                | 4.59 us: 1.10x faster                                      |
| unpickle_list        | 5.10 us                                                | 4.95 us: 1.03x faster                                      |
| unpickle             | 14.9 us                                                | 15.1 us: 1.01x slower                                      |
| pickle_dict          | 30.0 us                                                | 31.6 us: 1.05x slower                                      |
| Geometric mean       | (ref)                                                  | 1.20x faster                                               |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 9.35 ms: 1.53x faster                                      |
| python_startup_no_site | 5.87 ms                                                | 6.79 ms: 1.16x slower                                      |
| Geometric mean         | (ref)                                                  | 1.15x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 16.3 ms                                                | 10.9 ms: 1.50x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230711-linux-x86_64-python-v3.12.0b4-3.12.0b4-97a6a41 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 145 us: 3.87x faster                                       |
| generators               | 78.9 ms                                                | 30.5 ms: 2.58x faster                                      |
| deltablue                | 7.81 ms                                                | 3.49 ms: 2.24x faster                                      |
| richards_super           | 95.6 ms                                                | 49.2 ms: 1.94x faster                                      |
| logging_silent           | 189 ns                                                 | 97.8 ns: 1.93x faster                                      |
| richards                 | 79.4 ms                                                | 43.3 ms: 1.84x faster                                      |
| chaos                    | 114 ms                                                 | 62.7 ms: 1.82x faster                                      |
| scimark_sor              | 214 ms                                                 | 119 ms: 1.80x faster                                       |
| asyncio_tcp              | 918 ms                                                 | 517 ms: 1.77x faster                                       |
| go                       | 238 ms                                                 | 135 ms: 1.76x faster                                       |
| hexiom                   | 10.3 ms                                                | 6.05 ms: 1.70x faster                                      |
| raytrace                 | 498 ms                                                 | 293 ms: 1.70x faster                                       |
| nbody                    | 148 ms                                                 | 89.2 ms: 1.66x faster                                      |
| crypto_pyaes             | 127 ms                                                 | 77.2 ms: 1.64x faster                                      |
| pyflate                  | 708 ms                                                 | 434 ms: 1.63x faster                                       |
| scimark_monte_carlo      | 118 ms                                                 | 72.4 ms: 1.63x faster                                      |
| sqlglot_parse            | 2.15 ms                                                | 1.33 ms: 1.62x faster                                      |
| spectral_norm            | 163 ms                                                 | 102 ms: 1.60x faster                                       |
| pickle_pure_python       | 482 us                                                 | 306 us: 1.58x faster                                       |
| scimark_lu               | 175 ms                                                 | 112 ms: 1.56x faster                                       |
| sqlglot_transpile        | 2.55 ms                                                | 1.64 ms: 1.55x faster                                      |
| deepcopy_memo            | 58.8 us                                                | 37.9 us: 1.55x faster                                      |
| async_tree_none          | 732 ms                                                 | 472 ms: 1.55x faster                                       |
| async_tree_io            | 1.79 sec                                               | 1.16 sec: 1.54x faster                                     |
| python_startup           | 14.3 ms                                                | 9.35 ms: 1.53x faster                                      |
| coroutines               | 34.5 ms                                                | 22.5 ms: 1.53x faster                                      |
| async_tree_memoization   | 867 ms                                                 | 573 ms: 1.51x faster                                       |
| unpickle_pure_python     | 327 us                                                 | 217 us: 1.51x faster                                       |
| mako                     | 16.3 ms                                                | 10.9 ms: 1.50x faster                                      |
| json_dumps               | 14.3 ms                                                | 9.66 ms: 1.48x faster                                      |
| float                    | 116 ms                                                 | 80.7 ms: 1.44x faster                                      |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                     |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 715 ms: 1.41x faster                                       |
| pprint_pformat           | 2.10 sec                                               | 1.49 sec: 1.41x faster                                     |
| pprint_safe_repr         | 1.01 sec                                               | 731 ms: 1.39x faster                                       |
| comprehensions           | 28.5 us                                                | 20.7 us: 1.38x faster                                      |
| tomli_loads              | 3.06 sec                                               | 2.23 sec: 1.37x faster                                     |
| fannkuch                 | 527 ms                                                 | 385 ms: 1.37x faster                                       |
| deepcopy                 | 481 us                                                 | 355 us: 1.36x faster                                       |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.34x faster                                     |
| xml_etree_process        | 79.8 ms                                                | 59.4 ms: 1.34x faster                                      |
| unpack_sequence          | 65.7 ns                                                | 48.9 ns: 1.34x faster                                      |
| deepcopy_reduce          | 4.17 us                                                | 3.11 us: 1.34x faster                                      |
| logging_simple           | 8.27 us                                                | 6.21 us: 1.33x faster                                      |
| tornado_http             | 131 ms                                                 | 99.1 ms: 1.32x faster                                      |
| nqueens                  | 107 ms                                                 | 80.9 ms: 1.32x faster                                      |
| logging_format           | 9.07 us                                                | 6.93 us: 1.31x faster                                      |
| regex_compile            | 186 ms                                                 | 142 ms: 1.30x faster                                       |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                       |
| 2to3                     | 346 ms                                                 | 267 ms: 1.29x faster                                       |
| mypy2                    | 442 ms                                                 | 343 ms: 1.29x faster                                       |
| sqlglot_optimize         | 68.7 ms                                                | 53.9 ms: 1.27x faster                                      |
| scimark_fft              | 454 ms                                                 | 358 ms: 1.27x faster                                       |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.91 ms: 1.24x faster                                      |
| json_loads               | 31.4 us                                                | 25.7 us: 1.22x faster                                      |
| docutils                 | 3.26 sec                                               | 2.70 sec: 1.21x faster                                     |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.5 ms: 1.18x faster                                      |
| sqlalchemy_declarative   | 170 ms                                                 | 144 ms: 1.18x faster                                       |
| xml_etree_generate       | 100.0 ms                                               | 85.0 ms: 1.18x faster                                      |
| bench_thread_pool        | 966 us                                                 | 827 us: 1.17x faster                                       |
| json                     | 5.67 ms                                                | 4.95 ms: 1.15x faster                                      |
| meteor_contest           | 119 ms                                                 | 104 ms: 1.14x faster                                       |
| regex_v8                 | 26.2 ms                                                | 23.0 ms: 1.14x faster                                      |
| xml_etree_iterparse      | 116 ms                                                 | 102 ms: 1.14x faster                                       |
| dulwich_log              | 77.0 ms                                                | 67.9 ms: 1.13x faster                                      |
| xml_etree_parse          | 171 ms                                                 | 152 ms: 1.12x faster                                       |
| sqlite_synth             | 3.02 us                                                | 2.74 us: 1.11x faster                                      |
| pickle_list              | 5.05 us                                                | 4.59 us: 1.10x faster                                      |
| pathlib                  | 20.3 ms                                                | 18.8 ms: 1.08x faster                                      |
| mdp                      | 2.93 sec                                               | 2.73 sec: 1.08x faster                                     |
| create_gc_cycles         | 1.61 ms                                                | 1.51 ms: 1.06x faster                                      |
| regex_dna                | 215 ms                                                 | 207 ms: 1.04x faster                                       |
| unpickle_list            | 5.10 us                                                | 4.95 us: 1.03x faster                                      |
| telco                    | 7.01 ms                                                | 6.83 ms: 1.03x faster                                      |
| pidigits                 | 190 ms                                                 | 192 ms: 1.01x slower                                       |
| async_generators         | 442 ms                                                 | 448 ms: 1.01x slower                                       |
| unpickle                 | 14.9 us                                                | 15.1 us: 1.01x slower                                      |
| regex_effbot             | 3.41 ms                                                | 3.57 ms: 1.05x slower                                      |
| pickle_dict              | 30.0 us                                                | 31.6 us: 1.05x slower                                      |
| gc_traversal             | 3.43 ms                                                | 3.91 ms: 1.14x slower                                      |
| coverage                 | 82.0 ms                                                | 93.5 ms: 1.14x slower                                      |
| python_startup_no_site   | 5.87 ms                                                | 6.79 ms: 1.16x slower                                      |
| dask                     | 432 ms                                                 | 535 ms: 1.24x slower                                       |
| Geometric mean           | (ref)                                                  | 1.34x faster                                               |

Benchmark hidden because not significant (2): pickle, bench_mp_pool
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.30x
- 95% likely to have a speedup of 1.29x
- 99% likely to have a speedup of 1.26x
