
# Results vs. 3.10.4

- fork: mdboom
- ref: pogo2
- machine: linux-x86_64
- commit hash: 69004d6
- commit date: 2023-11-20
- overall geometric mean: 1.16x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 300 ms: 1.15x faster                                    |
| chameleon      | 9.84 ms                                                | 7.79 ms: 1.26x faster                                   |
| docutils       | 3.26 sec                                               | 2.77 sec: 1.18x faster                                  |
| tornado_http   | 131 ms                                                 | 103 ms: 1.27x faster                                    |
| Geometric mean | (ref)                                                  | 1.21x faster                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 467 ms: 1.57x faster                                    |
| async_tree_memoization  | 867 ms                                                 | 594 ms: 1.46x faster                                    |
| async_tree_io           | 1.79 sec                                               | 1.24 sec: 1.45x faster                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 737 ms: 1.37x faster                                    |
| Geometric mean          | (ref)                                                  | 1.46x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 191 ms: 1.00x slower                                    |
| float          | 116 ms                                                 | 120 ms: 1.03x slower                                    |
| nbody          | 148 ms                                                 | 170 ms: 1.15x slower                                    |
| Geometric mean | (ref)                                                  | 1.06x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 174 ms: 1.07x faster                                    |
| regex_v8       | 26.2 ms                                                | 24.7 ms: 1.06x faster                                   |
| regex_dna      | 215 ms                                                 | 224 ms: 1.04x slower                                    |
| regex_effbot   | 3.41 ms                                                | 3.61 ms: 1.06x slower                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 310 us: 1.55x faster                                    |
| json_dumps           | 14.3 ms                                                | 10.7 ms: 1.34x faster                                   |
| unpickle_pure_python | 327 us                                                 | 258 us: 1.27x faster                                    |
| xml_etree_process    | 79.8 ms                                                | 65.8 ms: 1.21x faster                                   |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                   |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                    |
| xml_etree_generate   | 100.0 ms                                               | 96.7 ms: 1.03x faster                                   |
| pickle_list          | 5.05 us                                                | 4.93 us: 1.02x faster                                   |
| unpickle_list        | 5.10 us                                                | 5.18 us: 1.02x slower                                   |
| tomli_loads          | 3.06 sec                                               | 3.17 sec: 1.04x slower                                  |
| pickle               | 10.7 us                                                | 11.3 us: 1.06x slower                                   |
| xml_etree_iterparse  | 116 ms                                                 | 124 ms: 1.06x slower                                    |
| unpickle             | 14.9 us                                                | 16.3 us: 1.10x slower                                   |
| pickle_dict          | 30.0 us                                                | 33.4 us: 1.11x slower                                   |
| Geometric mean       | (ref)                                                  | 1.08x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                   |
| python_startup_no_site | 5.87 ms                                                | 9.08 ms: 1.55x slower                                   |
| Geometric mean         | (ref)                                                  | 1.06x slower                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 16.3 ms                                                | 18.4 ms: 1.13x slower                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 129 us: 4.36x faster                                    |
| generators               | 78.9 ms                                                | 29.6 ms: 2.67x faster                                   |
| asyncio_tcp              | 918 ms                                                 | 491 ms: 1.87x faster                                    |
| logging_silent           | 189 ns                                                 | 114 ns: 1.66x faster                                    |
| richards_super           | 95.6 ms                                                | 60.2 ms: 1.59x faster                                   |
| async_tree_none          | 732 ms                                                 | 467 ms: 1.57x faster                                    |
| scimark_sor              | 214 ms                                                 | 137 ms: 1.56x faster                                    |
| pickle_pure_python       | 482 us                                                 | 310 us: 1.55x faster                                    |
| coroutines               | 34.5 ms                                                | 22.4 ms: 1.54x faster                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.44 ms: 1.49x faster                                   |
| richards                 | 79.4 ms                                                | 53.4 ms: 1.49x faster                                   |
| raytrace                 | 498 ms                                                 | 336 ms: 1.48x faster                                    |
| async_tree_memoization   | 867 ms                                                 | 594 ms: 1.46x faster                                    |
| async_tree_io            | 1.79 sec                                               | 1.24 sec: 1.45x faster                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.77 ms: 1.44x faster                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                  |
| scimark_lu               | 175 ms                                                 | 124 ms: 1.41x faster                                    |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                   |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 737 ms: 1.37x faster                                    |
| go                       | 238 ms                                                 | 177 ms: 1.34x faster                                    |
| json_dumps               | 14.3 ms                                                | 10.7 ms: 1.34x faster                                   |
| unpack_sequence          | 65.7 ns                                                | 49.3 ns: 1.33x faster                                   |
| logging_simple           | 8.27 us                                                | 6.31 us: 1.31x faster                                   |
| deepcopy                 | 481 us                                                 | 368 us: 1.31x faster                                    |
| deepcopy_reduce          | 4.17 us                                                | 3.20 us: 1.30x faster                                   |
| deepcopy_memo            | 58.8 us                                                | 45.4 us: 1.30x faster                                   |
| chaos                    | 114 ms                                                 | 89.4 ms: 1.28x faster                                   |
| logging_format           | 9.07 us                                                | 7.11 us: 1.28x faster                                   |
| unpickle_pure_python     | 327 us                                                 | 258 us: 1.27x faster                                    |
| tornado_http             | 131 ms                                                 | 103 ms: 1.27x faster                                    |
| chameleon                | 9.84 ms                                                | 7.79 ms: 1.26x faster                                   |
| deltablue                | 7.81 ms                                                | 6.30 ms: 1.24x faster                                   |
| pycparser                | 1.57 sec                                               | 1.26 sec: 1.24x faster                                  |
| crypto_pyaes             | 127 ms                                                 | 103 ms: 1.23x faster                                    |
| mypy2                    | 442 ms                                                 | 361 ms: 1.22x faster                                    |
| xml_etree_process        | 79.8 ms                                                | 65.8 ms: 1.21x faster                                   |
| docutils                 | 3.26 sec                                               | 2.77 sec: 1.18x faster                                  |
| sqlglot_normalize        | 141 ms                                                 | 121 ms: 1.17x faster                                    |
| dask                     | 432 ms                                                 | 371 ms: 1.16x faster                                    |
| 2to3                     | 346 ms                                                 | 300 ms: 1.15x faster                                    |
| scimark_monte_carlo      | 118 ms                                                 | 103 ms: 1.15x faster                                    |
| sympy_sum                | 190 ms                                                 | 169 ms: 1.13x faster                                    |
| pyflate                  | 708 ms                                                 | 632 ms: 1.12x faster                                    |
| sympy_integrate          | 25.4 ms                                                | 22.7 ms: 1.12x faster                                   |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                   |
| sqlglot_optimize         | 68.7 ms                                                | 62.0 ms: 1.11x faster                                   |
| sympy_expand             | 558 ms                                                 | 504 ms: 1.11x faster                                    |
| bench_thread_pool        | 966 us                                                 | 875 us: 1.10x faster                                    |
| dulwich_log              | 77.0 ms                                                | 69.7 ms: 1.10x faster                                   |
| json                     | 5.67 ms                                                | 5.14 ms: 1.10x faster                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                   |
| pprint_safe_repr         | 1.01 sec                                               | 928 ms: 1.09x faster                                    |
| pprint_pformat           | 2.10 sec                                               | 1.93 sec: 1.09x faster                                  |
| sympy_str                | 337 ms                                                 | 313 ms: 1.08x faster                                    |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                   |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                    |
| regex_compile            | 186 ms                                                 | 174 ms: 1.07x faster                                    |
| regex_v8                 | 26.2 ms                                                | 24.7 ms: 1.06x faster                                   |
| mdp                      | 2.93 sec                                               | 2.80 sec: 1.05x faster                                  |
| xml_etree_generate       | 100.0 ms                                               | 96.7 ms: 1.03x faster                                   |
| pickle_list              | 5.05 us                                                | 4.93 us: 1.02x faster                                   |
| sqlite_synth             | 3.02 us                                                | 2.96 us: 1.02x faster                                   |
| asyncio_websockets       | 558 ms                                                 | 553 ms: 1.01x faster                                    |
| pidigits                 | 190 ms                                                 | 191 ms: 1.00x slower                                    |
| unpickle_list            | 5.10 us                                                | 5.18 us: 1.02x slower                                   |
| gc_traversal             | 3.43 ms                                                | 3.51 ms: 1.02x slower                                   |
| float                    | 116 ms                                                 | 120 ms: 1.03x slower                                    |
| tomli_loads              | 3.06 sec                                               | 3.17 sec: 1.04x slower                                  |
| regex_dna                | 215 ms                                                 | 224 ms: 1.04x slower                                    |
| fannkuch                 | 527 ms                                                 | 551 ms: 1.04x slower                                    |
| pickle                   | 10.7 us                                                | 11.3 us: 1.06x slower                                   |
| async_generators         | 442 ms                                                 | 467 ms: 1.06x slower                                    |
| regex_effbot             | 3.41 ms                                                | 3.61 ms: 1.06x slower                                   |
| xml_etree_iterparse      | 116 ms                                                 | 124 ms: 1.06x slower                                    |
| meteor_contest           | 119 ms                                                 | 127 ms: 1.06x slower                                    |
| unpickle                 | 14.9 us                                                | 16.3 us: 1.10x slower                                   |
| pickle_dict              | 30.0 us                                                | 33.4 us: 1.11x slower                                   |
| hexiom                   | 10.3 ms                                                | 11.5 ms: 1.12x slower                                   |
| nqueens                  | 107 ms                                                 | 120 ms: 1.12x slower                                    |
| mako                     | 16.3 ms                                                | 18.4 ms: 1.13x slower                                   |
| nbody                    | 148 ms                                                 | 170 ms: 1.15x slower                                    |
| coverage                 | 82.0 ms                                                | 95.2 ms: 1.16x slower                                   |
| scimark_fft              | 454 ms                                                 | 567 ms: 1.25x slower                                    |
| spectral_norm            | 163 ms                                                 | 205 ms: 1.25x slower                                    |
| telco                    | 7.01 ms                                                | 9.06 ms: 1.29x slower                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 7.94 ms: 1.30x slower                                   |
| python_startup_no_site   | 5.87 ms                                                | 9.08 ms: 1.55x slower                                   |
| Geometric mean           | (ref)                                                  | 1.16x faster                                            |

Benchmark hidden because not significant (2): bench_mp_pool, comprehensions
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-69004d6-PYTHON_UOPS/bm-20231120-linux-x86_64-mdboom-pogo2-3.13.0a1+-69004d6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.07x
