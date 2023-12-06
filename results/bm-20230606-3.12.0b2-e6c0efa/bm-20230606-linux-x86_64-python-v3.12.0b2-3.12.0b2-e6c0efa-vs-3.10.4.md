
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0b2
- machine: linux-x86_64
- commit hash: e6c0efa
- commit date: 2023-06-06
- overall geometric mean: 1.33x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 269 ms: 1.29x faster                                       |
| docutils       | 3.26 sec                                               | 2.72 sec: 1.20x faster                                     |
| tornado_http   | 131 ms                                                 | 99.3 ms: 1.32x faster                                      |
| Geometric mean | (ref)                                                  | 1.27x faster                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 468 ms: 1.56x faster                                       |
| async_tree_io           | 1.79 sec                                               | 1.15 sec: 1.55x faster                                     |
| async_tree_memoization  | 867 ms                                                 | 570 ms: 1.52x faster                                       |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 708 ms: 1.42x faster                                       |
| Geometric mean          | (ref)                                                  | 1.51x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 148 ms                                                 | 89.7 ms: 1.65x faster                                      |
| float          | 116 ms                                                 | 80.3 ms: 1.45x faster                                      |
| pidigits       | 190 ms                                                 | 197 ms: 1.04x slower                                       |
| Geometric mean | (ref)                                                  | 1.32x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 145 ms: 1.28x faster                                       |
| regex_v8       | 26.2 ms                                                | 22.9 ms: 1.14x faster                                      |
| regex_dna      | 215 ms                                                 | 202 ms: 1.06x faster                                       |
| regex_effbot   | 3.41 ms                                                | 3.83 ms: 1.12x slower                                      |
| Geometric mean | (ref)                                                  | 1.09x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 314 us: 1.53x faster                                       |
| unpickle_pure_python | 327 us                                                 | 217 us: 1.51x faster                                       |
| json_dumps           | 14.3 ms                                                | 9.69 ms: 1.48x faster                                      |
| tomli_loads          | 3.06 sec                                               | 2.24 sec: 1.37x faster                                     |
| xml_etree_process    | 79.8 ms                                                | 59.1 ms: 1.35x faster                                      |
| json_loads           | 31.4 us                                                | 25.1 us: 1.25x faster                                      |
| xml_etree_generate   | 100.0 ms                                               | 85.6 ms: 1.17x faster                                      |
| xml_etree_iterparse  | 116 ms                                                 | 104 ms: 1.11x faster                                       |
| xml_etree_parse      | 171 ms                                                 | 156 ms: 1.10x faster                                       |
| pickle_list          | 5.05 us                                                | 4.75 us: 1.06x faster                                      |
| unpickle_list        | 5.10 us                                                | 4.90 us: 1.04x faster                                      |
| pickle               | 10.7 us                                                | 10.9 us: 1.02x slower                                      |
| pickle_dict          | 30.0 us                                                | 31.3 us: 1.05x slower                                      |
| Geometric mean       | (ref)                                                  | 1.19x faster                                               |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 9.30 ms: 1.54x faster                                      |
| python_startup_no_site | 5.87 ms                                                | 6.76 ms: 1.15x slower                                      |
| Geometric mean         | (ref)                                                  | 1.16x faster                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 16.3 ms                                                | 10.6 ms: 1.54x faster                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.12.0b2-3.12.0b2-e6c0efa |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 148 us: 3.79x faster                                       |
| generators               | 78.9 ms                                                | 31.6 ms: 2.50x faster                                      |
| deltablue                | 7.81 ms                                                | 3.46 ms: 2.26x faster                                      |
| richards_super           | 95.6 ms                                                | 48.9 ms: 1.96x faster                                      |
| richards                 | 79.4 ms                                                | 43.1 ms: 1.84x faster                                      |
| logging_silent           | 189 ns                                                 | 103 ns: 1.84x faster                                       |
| chaos                    | 114 ms                                                 | 63.6 ms: 1.80x faster                                      |
| asyncio_tcp              | 918 ms                                                 | 511 ms: 1.80x faster                                       |
| scimark_sor              | 214 ms                                                 | 120 ms: 1.78x faster                                       |
| go                       | 238 ms                                                 | 136 ms: 1.75x faster                                       |
| raytrace                 | 498 ms                                                 | 296 ms: 1.68x faster                                       |
| hexiom                   | 10.3 ms                                                | 6.19 ms: 1.66x faster                                      |
| scimark_monte_carlo      | 118 ms                                                 | 71.3 ms: 1.65x faster                                      |
| nbody                    | 148 ms                                                 | 89.7 ms: 1.65x faster                                      |
| crypto_pyaes             | 127 ms                                                 | 78.0 ms: 1.62x faster                                      |
| sqlglot_parse            | 2.15 ms                                                | 1.35 ms: 1.59x faster                                      |
| pyflate                  | 708 ms                                                 | 448 ms: 1.58x faster                                       |
| async_tree_none          | 732 ms                                                 | 468 ms: 1.56x faster                                       |
| spectral_norm            | 163 ms                                                 | 104 ms: 1.56x faster                                       |
| coroutines               | 34.5 ms                                                | 22.1 ms: 1.56x faster                                      |
| scimark_lu               | 175 ms                                                 | 113 ms: 1.55x faster                                       |
| async_tree_io            | 1.79 sec                                               | 1.15 sec: 1.55x faster                                     |
| deepcopy_memo            | 58.8 us                                                | 38.1 us: 1.54x faster                                      |
| python_startup           | 14.3 ms                                                | 9.30 ms: 1.54x faster                                      |
| mako                     | 16.3 ms                                                | 10.6 ms: 1.54x faster                                      |
| pickle_pure_python       | 482 us                                                 | 314 us: 1.53x faster                                       |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.52x faster                                      |
| async_tree_memoization   | 867 ms                                                 | 570 ms: 1.52x faster                                       |
| unpickle_pure_python     | 327 us                                                 | 217 us: 1.51x faster                                       |
| json_dumps               | 14.3 ms                                                | 9.69 ms: 1.48x faster                                      |
| float                    | 116 ms                                                 | 80.3 ms: 1.45x faster                                      |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                     |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 708 ms: 1.42x faster                                       |
| unpack_sequence          | 65.7 ns                                                | 46.7 ns: 1.41x faster                                      |
| pprint_pformat           | 2.10 sec                                               | 1.51 sec: 1.39x faster                                     |
| pprint_safe_repr         | 1.01 sec                                               | 735 ms: 1.38x faster                                       |
| tomli_loads              | 3.06 sec                                               | 2.24 sec: 1.37x faster                                     |
| comprehensions           | 28.5 us                                                | 20.9 us: 1.36x faster                                      |
| xml_etree_process        | 79.8 ms                                                | 59.1 ms: 1.35x faster                                      |
| deepcopy                 | 481 us                                                 | 359 us: 1.34x faster                                       |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.34x faster                                     |
| logging_simple           | 8.27 us                                                | 6.24 us: 1.33x faster                                      |
| fannkuch                 | 527 ms                                                 | 398 ms: 1.32x faster                                       |
| tornado_http             | 131 ms                                                 | 99.3 ms: 1.32x faster                                      |
| deepcopy_reduce          | 4.17 us                                                | 3.19 us: 1.31x faster                                      |
| logging_format           | 9.07 us                                                | 6.96 us: 1.30x faster                                      |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                       |
| nqueens                  | 107 ms                                                 | 82.6 ms: 1.29x faster                                      |
| 2to3                     | 346 ms                                                 | 269 ms: 1.29x faster                                       |
| regex_compile            | 186 ms                                                 | 145 ms: 1.28x faster                                       |
| scimark_fft              | 454 ms                                                 | 358 ms: 1.27x faster                                       |
| sqlglot_optimize         | 68.7 ms                                                | 54.2 ms: 1.27x faster                                      |
| json_loads               | 31.4 us                                                | 25.1 us: 1.25x faster                                      |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.89 ms: 1.25x faster                                      |
| docutils                 | 3.26 sec                                               | 2.72 sec: 1.20x faster                                     |
| json                     | 5.67 ms                                                | 4.76 ms: 1.19x faster                                      |
| sqlalchemy_declarative   | 170 ms                                                 | 145 ms: 1.17x faster                                       |
| xml_etree_generate       | 100.0 ms                                               | 85.6 ms: 1.17x faster                                      |
| bench_thread_pool        | 966 us                                                 | 829 us: 1.17x faster                                       |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.8 ms: 1.16x faster                                      |
| mdp                      | 2.93 sec                                               | 2.55 sec: 1.15x faster                                     |
| regex_v8                 | 26.2 ms                                                | 22.9 ms: 1.14x faster                                      |
| meteor_contest           | 119 ms                                                 | 106 ms: 1.13x faster                                       |
| dulwich_log              | 77.0 ms                                                | 68.4 ms: 1.13x faster                                      |
| xml_etree_iterparse      | 116 ms                                                 | 104 ms: 1.11x faster                                       |
| sqlite_synth             | 3.02 us                                                | 2.73 us: 1.11x faster                                      |
| xml_etree_parse          | 171 ms                                                 | 156 ms: 1.10x faster                                       |
| pathlib                  | 20.3 ms                                                | 18.8 ms: 1.08x faster                                      |
| pickle_list              | 5.05 us                                                | 4.75 us: 1.06x faster                                      |
| regex_dna                | 215 ms                                                 | 202 ms: 1.06x faster                                       |
| create_gc_cycles         | 1.61 ms                                                | 1.52 ms: 1.06x faster                                      |
| unpickle_list            | 5.10 us                                                | 4.90 us: 1.04x faster                                      |
| telco                    | 7.01 ms                                                | 6.83 ms: 1.03x faster                                      |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x faster                                      |
| async_generators         | 442 ms                                                 | 450 ms: 1.02x slower                                       |
| pickle                   | 10.7 us                                                | 10.9 us: 1.02x slower                                      |
| pidigits                 | 190 ms                                                 | 197 ms: 1.04x slower                                       |
| pickle_dict              | 30.0 us                                                | 31.3 us: 1.05x slower                                      |
| regex_effbot             | 3.41 ms                                                | 3.83 ms: 1.12x slower                                      |
| coverage                 | 82.0 ms                                                | 93.8 ms: 1.14x slower                                      |
| python_startup_no_site   | 5.87 ms                                                | 6.76 ms: 1.15x slower                                      |
| gc_traversal             | 3.43 ms                                                | 4.25 ms: 1.24x slower                                      |
| dask                     | 432 ms                                                 | 536 ms: 1.24x slower                                       |
| Geometric mean           | (ref)                                                  | 1.33x faster                                               |

Benchmark hidden because not significant (2): unpickle, mypy2
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
