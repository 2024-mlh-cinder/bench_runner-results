
# Results vs. 3.10.4

- fork: gvanrossum
- ref: faster_uops
- machine: linux-x86_64
- commit hash: a2c4f00
- commit date: 2023-11-19
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 290 ms: 1.19x faster                                              |
| chameleon      | 9.84 ms                                                | 7.36 ms: 1.34x faster                                             |
| docutils       | 3.26 sec                                               | 2.73 sec: 1.20x faster                                            |
| tornado_http   | 131 ms                                                 | 103 ms: 1.27x faster                                              |
| Geometric mean | (ref)                                                  | 1.25x faster                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 460 ms: 1.59x faster                                              |
| async_tree_memoization  | 867 ms                                                 | 587 ms: 1.48x faster                                              |
| async_tree_io           | 1.79 sec                                               | 1.22 sec: 1.46x faster                                            |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 731 ms: 1.38x faster                                              |
| Geometric mean          | (ref)                                                  | 1.47x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| float          | 116 ms                                                 | 103 ms: 1.13x faster                                              |
| nbody          | 148 ms                                                 | 138 ms: 1.07x faster                                              |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                              |
| Geometric mean | (ref)                                                  | 1.07x faster                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 161 ms: 1.15x faster                                              |
| regex_v8       | 26.2 ms                                                | 24.9 ms: 1.05x faster                                             |
| regex_effbot   | 3.41 ms                                                | 3.52 ms: 1.03x slower                                             |
| regex_dna      | 215 ms                                                 | 222 ms: 1.03x slower                                              |
| Geometric mean | (ref)                                                  | 1.03x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 308 us: 1.56x faster                                              |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                             |
| unpickle_pure_python | 327 us                                                 | 245 us: 1.33x faster                                              |
| xml_etree_process    | 79.8 ms                                                | 62.9 ms: 1.27x faster                                             |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                             |
| tomli_loads          | 3.06 sec                                               | 2.77 sec: 1.11x faster                                            |
| xml_etree_generate   | 100.0 ms                                               | 91.3 ms: 1.10x faster                                             |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                              |
| xml_etree_iterparse  | 116 ms                                                 | 114 ms: 1.02x faster                                              |
| unpickle_list        | 5.10 us                                                | 5.03 us: 1.01x faster                                             |
| pickle_list          | 5.05 us                                                | 5.11 us: 1.01x slower                                             |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                             |
| pickle_dict          | 30.0 us                                                | 34.5 us: 1.15x slower                                             |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                      |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.5 ms: 1.37x faster                                             |
| python_startup_no_site | 5.87 ms                                                | 9.10 ms: 1.55x slower                                             |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 15.1 ms: 1.08x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 126 us: 4.46x faster                                              |
| generators               | 78.9 ms                                                | 29.8 ms: 2.65x faster                                             |
| asyncio_tcp              | 918 ms                                                 | 499 ms: 1.84x faster                                              |
| logging_silent           | 189 ns                                                 | 111 ns: 1.70x faster                                              |
| scimark_sor              | 214 ms                                                 | 126 ms: 1.70x faster                                              |
| richards_super           | 95.6 ms                                                | 58.3 ms: 1.64x faster                                             |
| async_tree_none          | 732 ms                                                 | 460 ms: 1.59x faster                                              |
| raytrace                 | 498 ms                                                 | 317 ms: 1.57x faster                                              |
| pickle_pure_python       | 482 us                                                 | 308 us: 1.56x faster                                              |
| richards                 | 79.4 ms                                                | 51.0 ms: 1.56x faster                                             |
| coroutines               | 34.5 ms                                                | 22.3 ms: 1.54x faster                                             |
| sqlglot_parse            | 2.15 ms                                                | 1.39 ms: 1.54x faster                                             |
| deltablue                | 7.81 ms                                                | 5.11 ms: 1.53x faster                                             |
| sqlglot_transpile        | 2.55 ms                                                | 1.72 ms: 1.48x faster                                             |
| async_tree_memoization   | 867 ms                                                 | 587 ms: 1.48x faster                                              |
| chaos                    | 114 ms                                                 | 78.0 ms: 1.46x faster                                             |
| async_tree_io            | 1.79 sec                                               | 1.22 sec: 1.46x faster                                            |
| scimark_lu               | 175 ms                                                 | 121 ms: 1.45x faster                                              |
| go                       | 238 ms                                                 | 164 ms: 1.44x faster                                              |
| crypto_pyaes             | 127 ms                                                 | 87.8 ms: 1.44x faster                                             |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                            |
| deepcopy_memo            | 58.8 us                                                | 41.6 us: 1.41x faster                                             |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 731 ms: 1.38x faster                                              |
| python_startup           | 14.3 ms                                                | 10.5 ms: 1.37x faster                                             |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                             |
| chameleon                | 9.84 ms                                                | 7.36 ms: 1.34x faster                                             |
| unpickle_pure_python     | 327 us                                                 | 245 us: 1.33x faster                                              |
| logging_simple           | 8.27 us                                                | 6.21 us: 1.33x faster                                             |
| scimark_monte_carlo      | 118 ms                                                 | 88.6 ms: 1.33x faster                                             |
| deepcopy                 | 481 us                                                 | 363 us: 1.33x faster                                              |
| deepcopy_reduce          | 4.17 us                                                | 3.14 us: 1.33x faster                                             |
| logging_format           | 9.07 us                                                | 6.98 us: 1.30x faster                                             |
| pyflate                  | 708 ms                                                 | 546 ms: 1.30x faster                                              |
| pycparser                | 1.57 sec                                               | 1.22 sec: 1.29x faster                                            |
| tornado_http             | 131 ms                                                 | 103 ms: 1.27x faster                                              |
| xml_etree_process        | 79.8 ms                                                | 62.9 ms: 1.27x faster                                             |
| unpack_sequence          | 65.7 ns                                                | 52.6 ns: 1.25x faster                                             |
| mypy2                    | 442 ms                                                 | 358 ms: 1.24x faster                                              |
| comprehensions           | 28.5 us                                                | 23.3 us: 1.22x faster                                             |
| sqlglot_normalize        | 141 ms                                                 | 117 ms: 1.21x faster                                              |
| docutils                 | 3.26 sec                                               | 2.73 sec: 1.20x faster                                            |
| 2to3                     | 346 ms                                                 | 290 ms: 1.19x faster                                              |
| pprint_safe_repr         | 1.01 sec                                               | 853 ms: 1.19x faster                                              |
| pprint_pformat           | 2.10 sec                                               | 1.78 sec: 1.18x faster                                            |
| sympy_integrate          | 25.4 ms                                                | 21.7 ms: 1.17x faster                                             |
| dask                     | 432 ms                                                 | 371 ms: 1.16x faster                                              |
| sympy_sum                | 190 ms                                                 | 163 ms: 1.16x faster                                              |
| sqlglot_optimize         | 68.7 ms                                                | 59.5 ms: 1.16x faster                                             |
| regex_compile            | 186 ms                                                 | 161 ms: 1.15x faster                                              |
| fannkuch                 | 527 ms                                                 | 463 ms: 1.14x faster                                              |
| float                    | 116 ms                                                 | 103 ms: 1.13x faster                                              |
| sympy_expand             | 558 ms                                                 | 496 ms: 1.13x faster                                              |
| sympy_str                | 337 ms                                                 | 300 ms: 1.12x faster                                              |
| hexiom                   | 10.3 ms                                                | 9.16 ms: 1.12x faster                                             |
| bench_thread_pool        | 966 us                                                 | 861 us: 1.12x faster                                              |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                             |
| tomli_loads              | 3.06 sec                                               | 2.77 sec: 1.11x faster                                            |
| dulwich_log              | 77.0 ms                                                | 69.9 ms: 1.10x faster                                             |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                             |
| spectral_norm            | 163 ms                                                 | 149 ms: 1.10x faster                                              |
| xml_etree_generate       | 100.0 ms                                               | 91.3 ms: 1.10x faster                                             |
| json                     | 5.67 ms                                                | 5.22 ms: 1.09x faster                                             |
| pathlib                  | 20.3 ms                                                | 18.7 ms: 1.09x faster                                             |
| nqueens                  | 107 ms                                                 | 98.3 ms: 1.08x faster                                             |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                              |
| mako                     | 16.3 ms                                                | 15.1 ms: 1.08x faster                                             |
| nbody                    | 148 ms                                                 | 138 ms: 1.07x faster                                              |
| regex_v8                 | 26.2 ms                                                | 24.9 ms: 1.05x faster                                             |
| mdp                      | 2.93 sec                                               | 2.82 sec: 1.04x faster                                            |
| sqlite_synth             | 3.02 us                                                | 2.92 us: 1.03x faster                                             |
| meteor_contest           | 119 ms                                                 | 117 ms: 1.02x faster                                              |
| xml_etree_iterparse      | 116 ms                                                 | 114 ms: 1.02x faster                                              |
| unpickle_list            | 5.10 us                                                | 5.03 us: 1.01x faster                                             |
| asyncio_websockets       | 558 ms                                                 | 553 ms: 1.01x faster                                              |
| pidigits                 | 190 ms                                                 | 190 ms: 1.00x faster                                              |
| pickle_list              | 5.05 us                                                | 5.11 us: 1.01x slower                                             |
| regex_effbot             | 3.41 ms                                                | 3.52 ms: 1.03x slower                                             |
| regex_dna                | 215 ms                                                 | 222 ms: 1.03x slower                                              |
| async_generators         | 442 ms                                                 | 458 ms: 1.04x slower                                              |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.37 ms: 1.05x slower                                             |
| gc_traversal             | 3.43 ms                                                | 3.65 ms: 1.06x slower                                             |
| scimark_fft              | 454 ms                                                 | 488 ms: 1.07x slower                                              |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                             |
| pickle_dict              | 30.0 us                                                | 34.5 us: 1.15x slower                                             |
| coverage                 | 82.0 ms                                                | 95.2 ms: 1.16x slower                                             |
| telco                    | 7.01 ms                                                | 8.70 ms: 1.24x slower                                             |
| python_startup_no_site   | 5.87 ms                                                | 9.10 ms: 1.55x slower                                             |
| Geometric mean           | (ref)                                                  | 1.22x faster                                                      |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231119-3.13.0a1+-a2c4f00-PYTHON_UOPS/bm-20231119-linux-x86_64-gvanrossum-faster_uops-3.13.0a1+-a2c4f00.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.13x
