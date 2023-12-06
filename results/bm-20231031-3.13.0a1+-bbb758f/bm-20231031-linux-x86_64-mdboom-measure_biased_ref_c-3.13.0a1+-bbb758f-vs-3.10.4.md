
# Results vs. 3.10.4

- fork: mdboom
- ref: measure_biased_ref_c
- machine: linux-x86_64
- commit hash: bbb758f
- commit date: 2023-10-31
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 285 ms: 1.21x faster                                                   |
| chameleon      | 9.84 ms                                                | 7.47 ms: 1.32x faster                                                  |
| docutils       | 3.26 sec                                               | 2.83 sec: 1.15x faster                                                 |
| tornado_http   | 131 ms                                                 | 106 ms: 1.23x faster                                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 493 ms: 1.49x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 634 ms: 1.37x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.36 sec: 1.32x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 780 ms: 1.29x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.36x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 111 ms: 1.34x faster                                                   |
| float          | 116 ms                                                 | 90.6 ms: 1.29x faster                                                  |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| Geometric mean | (ref)                                                  | 1.20x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 149 ms: 1.25x faster                                                   |
| regex_v8       | 26.2 ms                                                | 25.2 ms: 1.04x faster                                                  |
| regex_dna      | 215 ms                                                 | 209 ms: 1.03x faster                                                   |
| regex_effbot   | 3.41 ms                                                | 3.48 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 333 us: 1.45x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 243 us: 1.35x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.31 sec: 1.32x faster                                                 |
| json_dumps           | 14.3 ms                                                | 11.2 ms: 1.27x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 64.6 ms: 1.23x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 93.6 ms: 1.07x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 112 ms: 1.03x faster                                                   |
| pickle_list          | 5.05 us                                                | 4.94 us: 1.02x faster                                                  |
| json_loads           | 31.4 us                                                | 30.8 us: 1.02x faster                                                  |
| unpickle             | 14.9 us                                                | 15.5 us: 1.04x slower                                                  |
| unpickle_list        | 5.10 us                                                | 5.36 us: 1.05x slower                                                  |
| pickle_dict          | 30.0 us                                                | 31.6 us: 1.05x slower                                                  |
| pickle               | 10.7 us                                                | 11.5 us: 1.08x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.10x faster                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.8 ms: 1.32x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.31 ms: 1.59x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.10x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.7 ms: 1.29x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 157 us: 3.57x faster                                                   |
| generators               | 78.9 ms                                                | 30.2 ms: 2.62x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.65 ms: 2.14x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 484 ms: 1.89x faster                                                   |
| richards_super           | 95.6 ms                                                | 57.0 ms: 1.68x faster                                                  |
| chaos                    | 114 ms                                                 | 68.3 ms: 1.67x faster                                                  |
| logging_silent           | 189 ns                                                 | 113 ns: 1.67x faster                                                   |
| comprehensions           | 28.5 us                                                | 17.6 us: 1.62x faster                                                  |
| raytrace                 | 498 ms                                                 | 309 ms: 1.61x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 79.3 ms: 1.60x faster                                                  |
| scimark_sor              | 214 ms                                                 | 137 ms: 1.56x faster                                                   |
| richards                 | 79.4 ms                                                | 51.0 ms: 1.56x faster                                                  |
| go                       | 238 ms                                                 | 154 ms: 1.54x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.39 ms: 1.54x faster                                                  |
| scimark_monte_carlo      | 118 ms                                                 | 77.5 ms: 1.52x faster                                                  |
| hexiom                   | 10.3 ms                                                | 6.80 ms: 1.51x faster                                                  |
| async_tree_none          | 732 ms                                                 | 493 ms: 1.49x faster                                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.73 ms: 1.47x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 333 us: 1.45x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.44x faster                                                 |
| scimark_lu               | 175 ms                                                 | 123 ms: 1.42x faster                                                   |
| coroutines               | 34.5 ms                                                | 24.4 ms: 1.41x faster                                                  |
| pyflate                  | 708 ms                                                 | 503 ms: 1.41x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 41.9 us: 1.40x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 634 ms: 1.37x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 243 us: 1.35x faster                                                   |
| nbody                    | 148 ms                                                 | 111 ms: 1.34x faster                                                   |
| python_startup           | 14.3 ms                                                | 10.8 ms: 1.32x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.31 sec: 1.32x faster                                                 |
| async_tree_io            | 1.79 sec                                               | 1.36 sec: 1.32x faster                                                 |
| chameleon                | 9.84 ms                                                | 7.47 ms: 1.32x faster                                                  |
| logging_format           | 9.07 us                                                | 6.92 us: 1.31x faster                                                  |
| logging_simple           | 8.27 us                                                | 6.32 us: 1.31x faster                                                  |
| unpack_sequence          | 65.7 ns                                                | 50.7 ns: 1.30x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 780 ms: 1.29x faster                                                   |
| mako                     | 16.3 ms                                                | 12.7 ms: 1.29x faster                                                  |
| float                    | 116 ms                                                 | 90.6 ms: 1.29x faster                                                  |
| spectral_norm            | 163 ms                                                 | 127 ms: 1.28x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.63 sec: 1.28x faster                                                 |
| deepcopy                 | 481 us                                                 | 378 us: 1.27x faster                                                   |
| json_dumps               | 14.3 ms                                                | 11.2 ms: 1.27x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 800 ms: 1.27x faster                                                   |
| pycparser                | 1.57 sec                                               | 1.24 sec: 1.26x faster                                                 |
| regex_compile            | 186 ms                                                 | 149 ms: 1.25x faster                                                   |
| xml_etree_process        | 79.8 ms                                                | 64.6 ms: 1.23x faster                                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.39 us: 1.23x faster                                                  |
| tornado_http             | 131 ms                                                 | 106 ms: 1.23x faster                                                   |
| sqlglot_normalize        | 141 ms                                                 | 115 ms: 1.23x faster                                                   |
| nqueens                  | 107 ms                                                 | 87.0 ms: 1.23x faster                                                  |
| 2to3                     | 346 ms                                                 | 285 ms: 1.21x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 21.3 ms: 1.19x faster                                                  |
| sympy_sum                | 190 ms                                                 | 161 ms: 1.18x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 58.0 ms: 1.18x faster                                                  |
| sympy_str                | 337 ms                                                 | 291 ms: 1.16x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.83 sec: 1.15x faster                                                 |
| fannkuch                 | 527 ms                                                 | 457 ms: 1.15x faster                                                   |
| sympy_expand             | 558 ms                                                 | 484 ms: 1.15x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.35 ms: 1.14x faster                                                  |
| scimark_fft              | 454 ms                                                 | 405 ms: 1.12x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                  |
| dulwich_log              | 77.0 ms                                                | 70.2 ms: 1.10x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.72 sec: 1.08x faster                                                 |
| xml_etree_generate       | 100.0 ms                                               | 93.6 ms: 1.07x faster                                                  |
| meteor_contest           | 119 ms                                                 | 114 ms: 1.04x faster                                                   |
| regex_v8                 | 26.2 ms                                                | 25.2 ms: 1.04x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 112 ms: 1.03x faster                                                   |
| regex_dna                | 215 ms                                                 | 209 ms: 1.03x faster                                                   |
| pickle_list              | 5.05 us                                                | 4.94 us: 1.02x faster                                                  |
| json_loads               | 31.4 us                                                | 30.8 us: 1.02x faster                                                  |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| pathlib                  | 20.3 ms                                                | 20.1 ms: 1.01x faster                                                  |
| json                     | 5.67 ms                                                | 5.64 ms: 1.01x faster                                                  |
| regex_effbot             | 3.41 ms                                                | 3.48 ms: 1.02x slower                                                  |
| sqlite_synth             | 3.02 us                                                | 3.11 us: 1.03x slower                                                  |
| unpickle                 | 14.9 us                                                | 15.5 us: 1.04x slower                                                  |
| unpickle_list            | 5.10 us                                                | 5.36 us: 1.05x slower                                                  |
| pickle_dict              | 30.0 us                                                | 31.6 us: 1.05x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 3.62 ms: 1.05x slower                                                  |
| pickle                   | 10.7 us                                                | 11.5 us: 1.08x slower                                                  |
| bench_thread_pool        | 966 us                                                 | 1.04 ms: 1.08x slower                                                  |
| async_generators         | 442 ms                                                 | 492 ms: 1.11x slower                                                   |
| mypy2                    | 442 ms                                                 | 500 ms: 1.13x slower                                                   |
| telco                    | 7.01 ms                                                | 9.04 ms: 1.29x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.31 ms: 1.59x slower                                                  |
| coverage                 | 82.0 ms                                                | 723 ms: 8.82x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.21x faster                                                           |

Benchmark hidden because not significant (3): xml_etree_parse, bench_mp_pool, asyncio_websockets
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231031-3.13.0a1+-bbb758f/bm-20231031-linux-x86_64-mdboom-measure_biased_ref_c-3.13.0a1+-bbb758f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
