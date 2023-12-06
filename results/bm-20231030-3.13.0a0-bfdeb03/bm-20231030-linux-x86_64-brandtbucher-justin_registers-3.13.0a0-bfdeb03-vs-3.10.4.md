
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: bfdeb03
- commit date: 2023-10-30
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 293 ms: 1.18x faster                                                    |
| chameleon      | 9.84 ms                                                | 7.47 ms: 1.32x faster                                                   |
| docutils       | 3.26 sec                                               | 2.76 sec: 1.18x faster                                                  |
| tornado_http   | 131 ms                                                 | 99.7 ms: 1.31x faster                                                   |
| Geometric mean | (ref)                                                  | 1.25x faster                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 457 ms: 1.60x faster                                                    |
| async_tree_memoization  | 867 ms                                                 | 583 ms: 1.49x faster                                                    |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.47x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 725 ms: 1.39x faster                                                    |
| Geometric mean          | (ref)                                                  | 1.49x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 112 ms: 1.32x faster                                                    |
| float          | 116 ms                                                 | 97.8 ms: 1.19x faster                                                   |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                  | 1.17x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 156 ms: 1.19x faster                                                    |
| regex_v8       | 26.2 ms                                                | 25.0 ms: 1.05x faster                                                   |
| regex_dna      | 215 ms                                                 | 208 ms: 1.03x faster                                                    |
| regex_effbot   | 3.41 ms                                                | 3.58 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                  | 1.05x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 307 us: 1.57x faster                                                    |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.36x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 244 us: 1.34x faster                                                    |
| xml_etree_process    | 79.8 ms                                                | 60.6 ms: 1.32x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.35 sec: 1.30x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 88.7 ms: 1.13x faster                                                   |
| json_loads           | 31.4 us                                                | 28.2 us: 1.12x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                                    |
| unpickle_list        | 5.10 us                                                | 4.95 us: 1.03x faster                                                   |
| xml_etree_iterparse  | 116 ms                                                 | 114 ms: 1.02x faster                                                    |
| pickle_list          | 5.05 us                                                | 5.22 us: 1.03x slower                                                   |
| unpickle             | 14.9 us                                                | 15.5 us: 1.04x slower                                                   |
| pickle               | 10.7 us                                                | 11.6 us: 1.08x slower                                                   |
| pickle_dict          | 30.0 us                                                | 35.4 us: 1.18x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                   |
| python_startup_no_site | 5.87 ms                                                | 7.10 ms: 1.21x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.07x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.4 ms: 1.31x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 159 us: 3.51x faster                                                    |
| generators               | 78.9 ms                                                | 29.4 ms: 2.68x faster                                                   |
| asyncio_tcp              | 918 ms                                                 | 485 ms: 1.89x faster                                                    |
| deltablue                | 7.81 ms                                                | 4.14 ms: 1.89x faster                                                   |
| richards_super           | 95.6 ms                                                | 55.5 ms: 1.72x faster                                                   |
| logging_silent           | 189 ns                                                 | 113 ns: 1.67x faster                                                    |
| crypto_pyaes             | 127 ms                                                 | 76.8 ms: 1.65x faster                                                   |
| scimark_sor              | 214 ms                                                 | 130 ms: 1.65x faster                                                    |
| raytrace                 | 498 ms                                                 | 306 ms: 1.63x faster                                                    |
| async_tree_none          | 732 ms                                                 | 457 ms: 1.60x faster                                                    |
| sqlglot_parse            | 2.15 ms                                                | 1.34 ms: 1.60x faster                                                   |
| richards                 | 79.4 ms                                                | 49.8 ms: 1.60x faster                                                   |
| pickle_pure_python       | 482 us                                                 | 307 us: 1.57x faster                                                    |
| go                       | 238 ms                                                 | 155 ms: 1.53x faster                                                    |
| scimark_monte_carlo      | 118 ms                                                 | 77.0 ms: 1.53x faster                                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.68 ms: 1.52x faster                                                   |
| chaos                    | 114 ms                                                 | 75.3 ms: 1.52x faster                                                   |
| coroutines               | 34.5 ms                                                | 23.0 ms: 1.50x faster                                                   |
| async_tree_memoization   | 867 ms                                                 | 583 ms: 1.49x faster                                                    |
| scimark_lu               | 175 ms                                                 | 119 ms: 1.48x faster                                                    |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.47x faster                                                  |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 725 ms: 1.39x faster                                                    |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                   |
| spectral_norm            | 163 ms                                                 | 119 ms: 1.37x faster                                                    |
| deepcopy_memo            | 58.8 us                                                | 43.2 us: 1.36x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.36x faster                                                   |
| unpack_sequence          | 65.7 ns                                                | 49.0 ns: 1.34x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 244 us: 1.34x faster                                                    |
| logging_simple           | 8.27 us                                                | 6.21 us: 1.33x faster                                                   |
| logging_format           | 9.07 us                                                | 6.82 us: 1.33x faster                                                   |
| pyflate                  | 708 ms                                                 | 537 ms: 1.32x faster                                                    |
| chameleon                | 9.84 ms                                                | 7.47 ms: 1.32x faster                                                   |
| nbody                    | 148 ms                                                 | 112 ms: 1.32x faster                                                    |
| deepcopy                 | 481 us                                                 | 365 us: 1.32x faster                                                    |
| xml_etree_process        | 79.8 ms                                                | 60.6 ms: 1.32x faster                                                   |
| mako                     | 16.3 ms                                                | 12.4 ms: 1.31x faster                                                   |
| tornado_http             | 131 ms                                                 | 99.7 ms: 1.31x faster                                                   |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.31x faster                                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.20 us: 1.30x faster                                                   |
| tomli_loads              | 3.06 sec                                               | 2.35 sec: 1.30x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 110 ms: 1.29x faster                                                    |
| sqlglot_optimize         | 68.7 ms                                                | 55.4 ms: 1.24x faster                                                   |
| mypy2                    | 442 ms                                                 | 364 ms: 1.21x faster                                                    |
| float                    | 116 ms                                                 | 97.8 ms: 1.19x faster                                                   |
| regex_compile            | 186 ms                                                 | 156 ms: 1.19x faster                                                    |
| docutils                 | 3.26 sec                                               | 2.76 sec: 1.18x faster                                                  |
| scimark_fft              | 454 ms                                                 | 384 ms: 1.18x faster                                                    |
| pprint_safe_repr         | 1.01 sec                                               | 860 ms: 1.18x faster                                                    |
| 2to3                     | 346 ms                                                 | 293 ms: 1.18x faster                                                    |
| sympy_expand             | 558 ms                                                 | 482 ms: 1.16x faster                                                    |
| pprint_pformat           | 2.10 sec                                               | 1.82 sec: 1.15x faster                                                  |
| sympy_sum                | 190 ms                                                 | 166 ms: 1.15x faster                                                    |
| fannkuch                 | 527 ms                                                 | 463 ms: 1.14x faster                                                    |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.36 ms: 1.14x faster                                                   |
| bench_thread_pool        | 966 us                                                 | 850 us: 1.14x faster                                                    |
| sympy_str                | 337 ms                                                 | 298 ms: 1.13x faster                                                    |
| sympy_integrate          | 25.4 ms                                                | 22.5 ms: 1.13x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 88.7 ms: 1.13x faster                                                   |
| json_loads               | 31.4 us                                                | 28.2 us: 1.12x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 69.4 ms: 1.11x faster                                                   |
| nqueens                  | 107 ms                                                 | 97.2 ms: 1.10x faster                                                   |
| json                     | 5.67 ms                                                | 5.18 ms: 1.09x faster                                                   |
| hexiom                   | 10.3 ms                                                | 9.49 ms: 1.09x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.81 us: 1.07x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.50 ms: 1.07x faster                                                   |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                                    |
| pathlib                  | 20.3 ms                                                | 19.1 ms: 1.06x faster                                                   |
| comprehensions           | 28.5 us                                                | 26.9 us: 1.06x faster                                                   |
| regex_v8                 | 26.2 ms                                                | 25.0 ms: 1.05x faster                                                   |
| meteor_contest           | 119 ms                                                 | 114 ms: 1.05x faster                                                    |
| regex_dna                | 215 ms                                                 | 208 ms: 1.03x faster                                                    |
| unpickle_list            | 5.10 us                                                | 4.95 us: 1.03x faster                                                   |
| mdp                      | 2.93 sec                                               | 2.85 sec: 1.03x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 114 ms: 1.02x faster                                                    |
| asyncio_websockets       | 558 ms                                                 | 553 ms: 1.01x faster                                                    |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                                    |
| pickle_list              | 5.05 us                                                | 5.22 us: 1.03x slower                                                   |
| unpickle                 | 14.9 us                                                | 15.5 us: 1.04x slower                                                   |
| regex_effbot             | 3.41 ms                                                | 3.58 ms: 1.05x slower                                                   |
| async_generators         | 442 ms                                                 | 478 ms: 1.08x slower                                                    |
| pickle                   | 10.7 us                                                | 11.6 us: 1.08x slower                                                   |
| gc_traversal             | 3.43 ms                                                | 3.96 ms: 1.15x slower                                                   |
| coverage                 | 82.0 ms                                                | 95.9 ms: 1.17x slower                                                   |
| pickle_dict              | 30.0 us                                                | 35.4 us: 1.18x slower                                                   |
| python_startup_no_site   | 5.87 ms                                                | 7.10 ms: 1.21x slower                                                   |
| telco                    | 7.01 ms                                                | 8.50 ms: 1.21x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                            |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231030-3.13.0a0-bfdeb03/bm-20231030-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-bfdeb03.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
