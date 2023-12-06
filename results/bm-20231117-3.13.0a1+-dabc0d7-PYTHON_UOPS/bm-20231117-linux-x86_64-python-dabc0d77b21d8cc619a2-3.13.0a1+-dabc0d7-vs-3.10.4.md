
# Results vs. 3.10.4

- fork: python
- ref: dabc0d77b21d8cc619a2
- machine: linux-x86_64
- commit hash: dabc0d7
- commit date: 2023-11-17
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 297 ms: 1.16x faster                                                   |
| chameleon      | 9.84 ms                                                | 7.46 ms: 1.32x faster                                                  |
| docutils       | 3.26 sec                                               | 2.72 sec: 1.20x faster                                                 |
| tornado_http   | 131 ms                                                 | 103 ms: 1.27x faster                                                   |
| Geometric mean | (ref)                                                  | 1.24x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 464 ms: 1.58x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 595 ms: 1.46x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.24 sec: 1.45x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 743 ms: 1.36x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.46x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 142 ms: 1.05x faster                                                   |
| float          | 116 ms                                                 | 119 ms: 1.02x slower                                                   |
| pidigits       | 190 ms                                                 | 198 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 171 ms: 1.08x faster                                                   |
| regex_v8       | 26.2 ms                                                | 24.8 ms: 1.06x faster                                                  |
| regex_dna      | 215 ms                                                 | 216 ms: 1.00x slower                                                   |
| regex_effbot   | 3.41 ms                                                | 3.56 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 308 us: 1.57x faster                                                   |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.3 ms: 1.35x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 252 us: 1.29x faster                                                   |
| xml_etree_generate   | 100.0 ms                                               | 87.8 ms: 1.14x faster                                                  |
| json_loads           | 31.4 us                                                | 28.0 us: 1.12x faster                                                  |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.09x faster                                                   |
| xml_etree_iterparse  | 116 ms                                                 | 114 ms: 1.02x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 3.11 sec: 1.02x slower                                                 |
| unpickle_list        | 5.10 us                                                | 5.29 us: 1.04x slower                                                  |
| pickle               | 10.7 us                                                | 11.1 us: 1.04x slower                                                  |
| pickle_dict          | 30.0 us                                                | 33.5 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                           |

Benchmark hidden because not significant (2): pickle_list, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.05 ms: 1.54x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 17.7 ms: 1.09x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 127 us: 4.40x faster                                                   |
| generators               | 78.9 ms                                                | 29.5 ms: 2.68x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 483 ms: 1.90x faster                                                   |
| logging_silent           | 189 ns                                                 | 112 ns: 1.68x faster                                                   |
| richards_super           | 95.6 ms                                                | 59.1 ms: 1.62x faster                                                  |
| async_tree_none          | 732 ms                                                 | 464 ms: 1.58x faster                                                   |
| scimark_sor              | 214 ms                                                 | 137 ms: 1.57x faster                                                   |
| pickle_pure_python       | 482 us                                                 | 308 us: 1.57x faster                                                   |
| coroutines               | 34.5 ms                                                | 22.0 ms: 1.56x faster                                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.38 ms: 1.56x faster                                                  |
| richards                 | 79.4 ms                                                | 52.2 ms: 1.52x faster                                                  |
| raytrace                 | 498 ms                                                 | 328 ms: 1.52x faster                                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.70 ms: 1.50x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 595 ms: 1.46x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.24 sec: 1.45x faster                                                 |
| scimark_lu               | 175 ms                                                 | 122 ms: 1.44x faster                                                   |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.42x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                                 |
| unpack_sequence          | 65.7 ns                                                | 46.7 ns: 1.41x faster                                                  |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| go                       | 238 ms                                                 | 174 ms: 1.37x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 743 ms: 1.36x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 43.6 us: 1.35x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 59.3 ms: 1.35x faster                                                  |
| deepcopy                 | 481 us                                                 | 358 us: 1.34x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.13 us: 1.33x faster                                                  |
| chaos                    | 114 ms                                                 | 85.9 ms: 1.33x faster                                                  |
| logging_simple           | 8.27 us                                                | 6.23 us: 1.33x faster                                                  |
| chameleon                | 9.84 ms                                                | 7.46 ms: 1.32x faster                                                  |
| deltablue                | 7.81 ms                                                | 5.97 ms: 1.31x faster                                                  |
| logging_format           | 9.07 us                                                | 6.98 us: 1.30x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 252 us: 1.29x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 98.1 ms: 1.29x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.22 sec: 1.29x faster                                                 |
| tornado_http             | 131 ms                                                 | 103 ms: 1.27x faster                                                   |
| scimark_monte_carlo      | 118 ms                                                 | 93.5 ms: 1.26x faster                                                  |
| mypy2                    | 442 ms                                                 | 355 ms: 1.25x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 55.3 ms: 1.24x faster                                                  |
| sympy_sum                | 190 ms                                                 | 155 ms: 1.23x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.72 sec: 1.20x faster                                                 |
| pyflate                  | 708 ms                                                 | 593 ms: 1.19x faster                                                   |
| dask                     | 432 ms                                                 | 370 ms: 1.17x faster                                                   |
| sympy_str                | 337 ms                                                 | 290 ms: 1.16x faster                                                   |
| 2to3                     | 346 ms                                                 | 297 ms: 1.16x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 21.9 ms: 1.16x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 879 ms: 1.15x faster                                                   |
| sympy_expand             | 558 ms                                                 | 488 ms: 1.14x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.84 sec: 1.14x faster                                                 |
| xml_etree_generate       | 100.0 ms                                               | 87.8 ms: 1.14x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 860 us: 1.12x faster                                                   |
| json_loads               | 31.4 us                                                | 28.0 us: 1.12x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 68.7 ms: 1.12x faster                                                  |
| json                     | 5.67 ms                                                | 5.19 ms: 1.09x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.09x faster                                                   |
| regex_compile            | 186 ms                                                 | 171 ms: 1.08x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.49 ms: 1.08x faster                                                  |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.75 sec: 1.07x faster                                                 |
| regex_v8                 | 26.2 ms                                                | 24.8 ms: 1.06x faster                                                  |
| comprehensions           | 28.5 us                                                | 27.2 us: 1.05x faster                                                  |
| nbody                    | 148 ms                                                 | 142 ms: 1.05x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.91 us: 1.04x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 114 ms: 1.02x faster                                                   |
| asyncio_websockets       | 558 ms                                                 | 553 ms: 1.01x faster                                                   |
| regex_dna                | 215 ms                                                 | 216 ms: 1.00x slower                                                   |
| fannkuch                 | 527 ms                                                 | 532 ms: 1.01x slower                                                   |
| meteor_contest           | 119 ms                                                 | 121 ms: 1.01x slower                                                   |
| tomli_loads              | 3.06 sec                                               | 3.11 sec: 1.02x slower                                                 |
| float                    | 116 ms                                                 | 119 ms: 1.02x slower                                                   |
| async_generators         | 442 ms                                                 | 457 ms: 1.03x slower                                                   |
| unpickle_list            | 5.10 us                                                | 5.29 us: 1.04x slower                                                  |
| pickle                   | 10.7 us                                                | 11.1 us: 1.04x slower                                                  |
| pidigits                 | 190 ms                                                 | 198 ms: 1.04x slower                                                   |
| regex_effbot             | 3.41 ms                                                | 3.56 ms: 1.04x slower                                                  |
| hexiom                   | 10.3 ms                                                | 10.9 ms: 1.06x slower                                                  |
| nqueens                  | 107 ms                                                 | 115 ms: 1.08x slower                                                   |
| mako                     | 16.3 ms                                                | 17.7 ms: 1.09x slower                                                  |
| pickle_dict              | 30.0 us                                                | 33.5 us: 1.12x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 3.92 ms: 1.14x slower                                                  |
| coverage                 | 82.0 ms                                                | 95.7 ms: 1.17x slower                                                  |
| scimark_fft              | 454 ms                                                 | 540 ms: 1.19x slower                                                   |
| telco                    | 7.01 ms                                                | 8.96 ms: 1.28x slower                                                  |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 7.82 ms: 1.28x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.05 ms: 1.54x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.20x faster                                                           |

Benchmark hidden because not significant (3): bench_mp_pool, pickle_list, unpickle
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231117-3.13.0a1+-dabc0d7-PYTHON_UOPS/bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.11x
