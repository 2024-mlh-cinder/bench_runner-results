
# Results vs. 3.10.4

- fork: mdboom
- ref: test_branch2
- machine: linux-x86_64
- commit hash: f9d458f
- commit date: 2023-11-20
- overall geometric mean: 1.19x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 295 ms: 1.17x faster                                           |
| chameleon      | 9.84 ms                                                | 7.47 ms: 1.32x faster                                          |
| docutils       | 3.26 sec                                               | 2.75 sec: 1.19x faster                                         |
| tornado_http   | 131 ms                                                 | 103 ms: 1.27x faster                                           |
| Geometric mean | (ref)                                                  | 1.24x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 464 ms: 1.58x faster                                           |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.48x faster                                         |
| async_tree_memoization  | 867 ms                                                 | 587 ms: 1.48x faster                                           |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 733 ms: 1.38x faster                                           |
| Geometric mean          | (ref)                                                  | 1.48x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 141 ms: 1.05x faster                                           |
| float          | 116 ms                                                 | 115 ms: 1.01x faster                                           |
| pidigits       | 190 ms                                                 | 197 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 169 ms: 1.10x faster                                           |
| regex_v8       | 26.2 ms                                                | 25.9 ms: 1.01x faster                                          |
| regex_dna      | 215 ms                                                 | 218 ms: 1.02x slower                                           |
| regex_effbot   | 3.41 ms                                                | 3.69 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                  | 1.00x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 307 us: 1.57x faster                                           |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| unpickle_pure_python | 327 us                                                 | 252 us: 1.30x faster                                           |
| xml_etree_process    | 79.8 ms                                                | 64.5 ms: 1.24x faster                                          |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                           |
| xml_etree_generate   | 100.0 ms                                               | 94.5 ms: 1.06x faster                                          |
| tomli_loads          | 3.06 sec                                               | 2.97 sec: 1.03x faster                                         |
| unpickle             | 14.9 us                                                | 14.5 us: 1.02x faster                                          |
| pickle_list          | 5.05 us                                                | 5.11 us: 1.01x slower                                          |
| xml_etree_iterparse  | 116 ms                                                 | 118 ms: 1.02x slower                                           |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| pickle_dict          | 30.0 us                                                | 33.7 us: 1.13x slower                                          |
| Geometric mean       | (ref)                                                  | 1.10x faster                                                   |

Benchmark hidden because not significant (1): unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| python_startup_no_site | 5.87 ms                                                | 9.00 ms: 1.53x slower                                          |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 17.2 ms: 1.06x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 123 us: 4.56x faster                                           |
| generators               | 78.9 ms                                                | 29.4 ms: 2.69x faster                                          |
| asyncio_tcp              | 918 ms                                                 | 490 ms: 1.87x faster                                           |
| logging_silent           | 189 ns                                                 | 109 ns: 1.73x faster                                           |
| scimark_sor              | 214 ms                                                 | 126 ms: 1.70x faster                                           |
| richards_super           | 95.6 ms                                                | 58.3 ms: 1.64x faster                                          |
| async_tree_none          | 732 ms                                                 | 464 ms: 1.58x faster                                           |
| pickle_pure_python       | 482 us                                                 | 307 us: 1.57x faster                                           |
| coroutines               | 34.5 ms                                                | 22.2 ms: 1.55x faster                                          |
| richards                 | 79.4 ms                                                | 51.2 ms: 1.55x faster                                          |
| raytrace                 | 498 ms                                                 | 324 ms: 1.54x faster                                           |
| sqlglot_parse            | 2.15 ms                                                | 1.42 ms: 1.52x faster                                          |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.48x faster                                         |
| async_tree_memoization   | 867 ms                                                 | 587 ms: 1.48x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.74 ms: 1.46x faster                                          |
| scimark_lu               | 175 ms                                                 | 122 ms: 1.44x faster                                           |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                         |
| go                       | 238 ms                                                 | 171 ms: 1.39x faster                                           |
| deepcopy_memo            | 58.8 us                                                | 42.5 us: 1.38x faster                                          |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| chaos                    | 114 ms                                                 | 82.8 ms: 1.38x faster                                          |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 733 ms: 1.38x faster                                           |
| deltablue                | 7.81 ms                                                | 5.73 ms: 1.36x faster                                          |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                          |
| crypto_pyaes             | 127 ms                                                 | 93.9 ms: 1.35x faster                                          |
| logging_simple           | 8.27 us                                                | 6.20 us: 1.33x faster                                          |
| deepcopy                 | 481 us                                                 | 363 us: 1.33x faster                                           |
| scimark_monte_carlo      | 118 ms                                                 | 89.2 ms: 1.32x faster                                          |
| deepcopy_reduce          | 4.17 us                                                | 3.16 us: 1.32x faster                                          |
| chameleon                | 9.84 ms                                                | 7.47 ms: 1.32x faster                                          |
| logging_format           | 9.07 us                                                | 7.00 us: 1.30x faster                                          |
| unpickle_pure_python     | 327 us                                                 | 252 us: 1.30x faster                                           |
| unpack_sequence          | 65.7 ns                                                | 50.8 ns: 1.29x faster                                          |
| tornado_http             | 131 ms                                                 | 103 ms: 1.27x faster                                           |
| xml_etree_process        | 79.8 ms                                                | 64.5 ms: 1.24x faster                                          |
| pycparser                | 1.57 sec                                               | 1.27 sec: 1.24x faster                                         |
| mypy2                    | 442 ms                                                 | 359 ms: 1.23x faster                                           |
| pyflate                  | 708 ms                                                 | 592 ms: 1.20x faster                                           |
| sqlglot_normalize        | 141 ms                                                 | 119 ms: 1.19x faster                                           |
| docutils                 | 3.26 sec                                               | 2.75 sec: 1.19x faster                                         |
| pprint_safe_repr         | 1.01 sec                                               | 861 ms: 1.18x faster                                           |
| 2to3                     | 346 ms                                                 | 295 ms: 1.17x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.79 sec: 1.17x faster                                         |
| dask                     | 432 ms                                                 | 370 ms: 1.17x faster                                           |
| sympy_sum                | 190 ms                                                 | 165 ms: 1.15x faster                                           |
| sympy_integrate          | 25.4 ms                                                | 22.1 ms: 1.15x faster                                          |
| sqlglot_optimize         | 68.7 ms                                                | 60.7 ms: 1.13x faster                                          |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                          |
| bench_thread_pool        | 966 us                                                 | 868 us: 1.11x faster                                           |
| sympy_str                | 337 ms                                                 | 304 ms: 1.11x faster                                           |
| sympy_expand             | 558 ms                                                 | 504 ms: 1.11x faster                                           |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                          |
| dulwich_log              | 77.0 ms                                                | 69.9 ms: 1.10x faster                                          |
| regex_compile            | 186 ms                                                 | 169 ms: 1.10x faster                                           |
| comprehensions           | 28.5 us                                                | 26.3 us: 1.08x faster                                          |
| fannkuch                 | 527 ms                                                 | 490 ms: 1.08x faster                                           |
| json                     | 5.67 ms                                                | 5.27 ms: 1.08x faster                                          |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                           |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                          |
| xml_etree_generate       | 100.0 ms                                               | 94.5 ms: 1.06x faster                                          |
| nbody                    | 148 ms                                                 | 141 ms: 1.05x faster                                           |
| tomli_loads              | 3.06 sec                                               | 2.97 sec: 1.03x faster                                         |
| unpickle                 | 14.9 us                                                | 14.5 us: 1.02x faster                                          |
| sqlite_synth             | 3.02 us                                                | 2.98 us: 1.02x faster                                          |
| regex_v8                 | 26.2 ms                                                | 25.9 ms: 1.01x faster                                          |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                           |
| float                    | 116 ms                                                 | 115 ms: 1.01x faster                                           |
| mdp                      | 2.93 sec                                               | 2.91 sec: 1.01x faster                                         |
| pickle_list              | 5.05 us                                                | 5.11 us: 1.01x slower                                          |
| regex_dna                | 215 ms                                                 | 218 ms: 1.02x slower                                           |
| xml_etree_iterparse      | 116 ms                                                 | 118 ms: 1.02x slower                                           |
| nqueens                  | 107 ms                                                 | 110 ms: 1.03x slower                                           |
| meteor_contest           | 119 ms                                                 | 123 ms: 1.03x slower                                           |
| pidigits                 | 190 ms                                                 | 197 ms: 1.04x slower                                           |
| spectral_norm            | 163 ms                                                 | 169 ms: 1.04x slower                                           |
| async_generators         | 442 ms                                                 | 461 ms: 1.04x slower                                           |
| mako                     | 16.3 ms                                                | 17.2 ms: 1.06x slower                                          |
| regex_effbot             | 3.41 ms                                                | 3.69 ms: 1.08x slower                                          |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| gc_traversal             | 3.43 ms                                                | 3.81 ms: 1.11x slower                                          |
| pickle_dict              | 30.0 us                                                | 33.7 us: 1.13x slower                                          |
| coverage                 | 82.0 ms                                                | 94.7 ms: 1.15x slower                                          |
| scimark_fft              | 454 ms                                                 | 525 ms: 1.16x slower                                           |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 7.47 ms: 1.23x slower                                          |
| telco                    | 7.01 ms                                                | 8.92 ms: 1.27x slower                                          |
| python_startup_no_site   | 5.87 ms                                                | 9.00 ms: 1.53x slower                                          |
| Geometric mean           | (ref)                                                  | 1.19x faster                                                   |

Benchmark hidden because not significant (3): bench_mp_pool, unpickle_list, hexiom
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-f9d458f-PYTHON_UOPS/bm-20231120-linux-x86_64-mdboom-test_branch2-3.13.0a1+-f9d458f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.09x
