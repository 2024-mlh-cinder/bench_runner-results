
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_stubs
- machine: linux-x86_64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 274 ms: 1.26x faster                                                    |
| chameleon      | 9.84 ms                                                | 7.15 ms: 1.38x faster                                                   |
| docutils       | 3.26 sec                                               | 2.66 sec: 1.23x faster                                                  |
| tornado_http   | 131 ms                                                 | 96.5 ms: 1.35x faster                                                   |
| Geometric mean | (ref)                                                  | 1.30x faster                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 444 ms: 1.65x faster                                                    |
| async_tree_memoization  | 867 ms                                                 | 568 ms: 1.53x faster                                                    |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 720 ms: 1.40x faster                                                    |
| Geometric mean          | (ref)                                                  | 1.52x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 98.9 ms: 1.50x faster                                                   |
| float          | 116 ms                                                 | 84.9 ms: 1.37x faster                                                   |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                                    |
| Geometric mean | (ref)                                                  | 1.26x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 144 ms: 1.29x faster                                                    |
| regex_v8       | 26.2 ms                                                | 24.0 ms: 1.09x faster                                                   |
| regex_dna      | 215 ms                                                 | 221 ms: 1.03x slower                                                    |
| regex_effbot   | 3.41 ms                                                | 3.58 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 312 us: 1.54x faster                                                    |
| tomli_loads          | 3.06 sec                                               | 2.16 sec: 1.41x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 234 us: 1.40x faster                                                    |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                                   |
| xml_etree_process    | 79.8 ms                                                | 61.1 ms: 1.31x faster                                                   |
| xml_etree_generate   | 100.0 ms                                               | 89.1 ms: 1.12x faster                                                   |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                                    |
| xml_etree_iterparse  | 116 ms                                                 | 110 ms: 1.05x faster                                                    |
| pickle_list          | 5.05 us                                                | 5.18 us: 1.03x slower                                                   |
| unpickle_list        | 5.10 us                                                | 5.25 us: 1.03x slower                                                   |
| unpickle             | 14.9 us                                                | 15.4 us: 1.04x slower                                                   |
| pickle               | 10.7 us                                                | 11.5 us: 1.07x slower                                                   |
| pickle_dict          | 30.0 us                                                | 35.7 us: 1.19x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                   |
| python_startup_no_site | 5.87 ms                                                | 9.07 ms: 1.54x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.3 ms: 1.33x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 119 us: 4.70x faster                                                    |
| generators               | 78.9 ms                                                | 30.1 ms: 2.62x faster                                                   |
| deltablue                | 7.81 ms                                                | 4.08 ms: 1.91x faster                                                   |
| asyncio_tcp              | 918 ms                                                 | 491 ms: 1.87x faster                                                    |
| richards_super           | 95.6 ms                                                | 53.2 ms: 1.80x faster                                                   |
| raytrace                 | 498 ms                                                 | 286 ms: 1.74x faster                                                    |
| logging_silent           | 189 ns                                                 | 110 ns: 1.73x faster                                                    |
| chaos                    | 114 ms                                                 | 67.2 ms: 1.70x faster                                                   |
| richards                 | 79.4 ms                                                | 46.9 ms: 1.69x faster                                                   |
| scimark_sor              | 214 ms                                                 | 127 ms: 1.69x faster                                                    |
| async_tree_none          | 732 ms                                                 | 444 ms: 1.65x faster                                                    |
| sqlglot_parse            | 2.15 ms                                                | 1.32 ms: 1.62x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 78.3 ms: 1.62x faster                                                   |
| go                       | 238 ms                                                 | 151 ms: 1.57x faster                                                    |
| scimark_monte_carlo      | 118 ms                                                 | 75.0 ms: 1.57x faster                                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.65 ms: 1.55x faster                                                   |
| pickle_pure_python       | 482 us                                                 | 312 us: 1.54x faster                                                    |
| async_tree_memoization   | 867 ms                                                 | 568 ms: 1.53x faster                                                    |
| coroutines               | 34.5 ms                                                | 22.7 ms: 1.52x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                                  |
| nbody                    | 148 ms                                                 | 98.9 ms: 1.50x faster                                                   |
| comprehensions           | 28.5 us                                                | 19.4 us: 1.47x faster                                                   |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                                    |
| deepcopy_memo            | 58.8 us                                                | 40.5 us: 1.45x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                                  |
| logging_format           | 9.07 us                                                | 6.38 us: 1.42x faster                                                   |
| logging_simple           | 8.27 us                                                | 5.82 us: 1.42x faster                                                   |
| tomli_loads              | 3.06 sec                                               | 2.16 sec: 1.41x faster                                                  |
| pyflate                  | 708 ms                                                 | 503 ms: 1.41x faster                                                    |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 720 ms: 1.40x faster                                                    |
| unpickle_pure_python     | 327 us                                                 | 234 us: 1.40x faster                                                    |
| chameleon                | 9.84 ms                                                | 7.15 ms: 1.38x faster                                                   |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                   |
| float                    | 116 ms                                                 | 84.9 ms: 1.37x faster                                                   |
| deepcopy                 | 481 us                                                 | 355 us: 1.35x faster                                                    |
| tornado_http             | 131 ms                                                 | 96.5 ms: 1.35x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                                   |
| hexiom                   | 10.3 ms                                                | 7.65 ms: 1.35x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.11 us: 1.34x faster                                                   |
| unpack_sequence          | 65.7 ns                                                | 49.2 ns: 1.34x faster                                                   |
| mako                     | 16.3 ms                                                | 12.3 ms: 1.33x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.60 sec: 1.31x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.31x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 61.1 ms: 1.31x faster                                                   |
| sqlglot_normalize        | 141 ms                                                 | 108 ms: 1.30x faster                                                    |
| pprint_safe_repr         | 1.01 sec                                               | 783 ms: 1.30x faster                                                    |
| regex_compile            | 186 ms                                                 | 144 ms: 1.29x faster                                                    |
| 2to3                     | 346 ms                                                 | 274 ms: 1.26x faster                                                    |
| mypy2                    | 442 ms                                                 | 352 ms: 1.26x faster                                                    |
| sqlglot_optimize         | 68.7 ms                                                | 55.5 ms: 1.24x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.66 sec: 1.23x faster                                                  |
| fannkuch                 | 527 ms                                                 | 431 ms: 1.22x faster                                                    |
| sympy_sum                | 190 ms                                                 | 156 ms: 1.22x faster                                                    |
| sympy_integrate          | 25.4 ms                                                | 20.9 ms: 1.21x faster                                                   |
| spectral_norm            | 163 ms                                                 | 136 ms: 1.20x faster                                                    |
| sympy_str                | 337 ms                                                 | 282 ms: 1.19x faster                                                    |
| sympy_expand             | 558 ms                                                 | 469 ms: 1.19x faster                                                    |
| dask                     | 432 ms                                                 | 365 ms: 1.18x faster                                                    |
| scimark_fft              | 454 ms                                                 | 384 ms: 1.18x faster                                                    |
| nqueens                  | 107 ms                                                 | 92.0 ms: 1.16x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 66.7 ms: 1.15x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.35 ms: 1.14x faster                                                   |
| bench_thread_pool        | 966 us                                                 | 854 us: 1.13x faster                                                    |
| xml_etree_generate       | 100.0 ms                                               | 89.1 ms: 1.12x faster                                                   |
| mdp                      | 2.93 sec                                               | 2.62 sec: 1.12x faster                                                  |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                   |
| json                     | 5.67 ms                                                | 5.15 ms: 1.10x faster                                                   |
| pathlib                  | 20.3 ms                                                | 18.4 ms: 1.10x faster                                                   |
| regex_v8                 | 26.2 ms                                                | 24.0 ms: 1.09x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.82 us: 1.07x faster                                                   |
| meteor_contest           | 119 ms                                                 | 111 ms: 1.07x faster                                                    |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                                    |
| xml_etree_iterparse      | 116 ms                                                 | 110 ms: 1.05x faster                                                    |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                    |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                                    |
| pickle_list              | 5.05 us                                                | 5.18 us: 1.03x slower                                                   |
| unpickle_list            | 5.10 us                                                | 5.25 us: 1.03x slower                                                   |
| regex_dna                | 215 ms                                                 | 221 ms: 1.03x slower                                                    |
| unpickle                 | 14.9 us                                                | 15.4 us: 1.04x slower                                                   |
| regex_effbot             | 3.41 ms                                                | 3.58 ms: 1.05x slower                                                   |
| async_generators         | 442 ms                                                 | 465 ms: 1.05x slower                                                    |
| pickle                   | 10.7 us                                                | 11.5 us: 1.07x slower                                                   |
| coverage                 | 82.0 ms                                                | 96.1 ms: 1.17x slower                                                   |
| pickle_dict              | 30.0 us                                                | 35.7 us: 1.19x slower                                                   |
| telco                    | 7.01 ms                                                | 8.38 ms: 1.19x slower                                                   |
| gc_traversal             | 3.43 ms                                                | 4.29 ms: 1.25x slower                                                   |
| python_startup_no_site   | 5.87 ms                                                | 9.07 ms: 1.54x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-925f140/bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.21x
