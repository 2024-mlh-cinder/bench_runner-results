
# Results vs. 3.10.4

- fork: iritkatriel
- ref: gen_yf
- machine: linux-x86_64
- commit hash: 309abda
- commit date: 2023-11-02
- overall geometric mean: 1.34x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.27x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                          |
| chameleon      | 9.84 ms                                                | 6.96 ms: 1.41x faster                                         |
| docutils       | 3.26 sec                                               | 2.60 sec: 1.25x faster                                        |
| tornado_http   | 131 ms                                                 | 95.1 ms: 1.37x faster                                         |
| Geometric mean | (ref)                                                  | 1.34x faster                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 437 ms: 1.68x faster                                          |
| async_tree_memoization  | 867 ms                                                 | 563 ms: 1.54x faster                                          |
| async_tree_io           | 1.79 sec                                               | 1.18 sec: 1.51x faster                                        |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 713 ms: 1.41x faster                                          |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 91.3 ms: 1.62x faster                                         |
| float          | 116 ms                                                 | 81.7 ms: 1.42x faster                                         |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                  | 1.33x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 134 ms: 1.38x faster                                          |
| regex_v8       | 26.2 ms                                                | 25.5 ms: 1.03x faster                                         |
| regex_dna      | 215 ms                                                 | 217 ms: 1.01x slower                                          |
| regex_effbot   | 3.41 ms                                                | 3.68 ms: 1.08x slower                                         |
| Geometric mean | (ref)                                                  | 1.07x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 293 us: 1.64x faster                                          |
| unpickle_pure_python | 327 us                                                 | 215 us: 1.52x faster                                          |
| tomli_loads          | 3.06 sec                                               | 2.17 sec: 1.41x faster                                        |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                         |
| xml_etree_process    | 79.8 ms                                                | 59.3 ms: 1.34x faster                                         |
| xml_etree_generate   | 100.0 ms                                               | 86.2 ms: 1.16x faster                                         |
| json_loads           | 31.4 us                                                | 27.8 us: 1.13x faster                                         |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.10x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.07x faster                                          |
| pickle_list          | 5.05 us                                                | 5.11 us: 1.01x slower                                         |
| unpickle_list        | 5.10 us                                                | 5.19 us: 1.02x slower                                         |
| unpickle             | 14.9 us                                                | 15.8 us: 1.06x slower                                         |
| pickle               | 10.7 us                                                | 11.5 us: 1.08x slower                                         |
| pickle_dict          | 30.0 us                                                | 36.0 us: 1.20x slower                                         |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                         |
| python_startup_no_site | 5.87 ms                                                | 8.98 ms: 1.53x slower                                         |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.4 ms: 1.43x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 115 us: 4.86x faster                                          |
| generators               | 78.9 ms                                                | 29.5 ms: 2.68x faster                                         |
| deltablue                | 7.81 ms                                                | 3.37 ms: 2.32x faster                                         |
| asyncio_tcp              | 918 ms                                                 | 482 ms: 1.90x faster                                          |
| chaos                    | 114 ms                                                 | 61.2 ms: 1.87x faster                                         |
| raytrace                 | 498 ms                                                 | 277 ms: 1.80x faster                                          |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                          |
| crypto_pyaes             | 127 ms                                                 | 71.2 ms: 1.78x faster                                         |
| richards_super           | 95.6 ms                                                | 53.8 ms: 1.78x faster                                         |
| scimark_sor              | 214 ms                                                 | 122 ms: 1.75x faster                                          |
| comprehensions           | 28.5 us                                                | 16.3 us: 1.75x faster                                         |
| scimark_monte_carlo      | 118 ms                                                 | 67.5 ms: 1.75x faster                                         |
| hexiom                   | 10.3 ms                                                | 6.05 ms: 1.70x faster                                         |
| sqlglot_parse            | 2.15 ms                                                | 1.28 ms: 1.68x faster                                         |
| async_tree_none          | 732 ms                                                 | 437 ms: 1.68x faster                                          |
| go                       | 238 ms                                                 | 142 ms: 1.67x faster                                          |
| richards                 | 79.4 ms                                                | 47.8 ms: 1.66x faster                                         |
| pickle_pure_python       | 482 us                                                 | 293 us: 1.64x faster                                          |
| nbody                    | 148 ms                                                 | 91.3 ms: 1.62x faster                                         |
| sqlglot_transpile        | 2.55 ms                                                | 1.59 ms: 1.61x faster                                         |
| pyflate                  | 708 ms                                                 | 452 ms: 1.57x faster                                          |
| scimark_lu               | 175 ms                                                 | 114 ms: 1.54x faster                                          |
| async_tree_memoization   | 867 ms                                                 | 563 ms: 1.54x faster                                          |
| deepcopy_memo            | 58.8 us                                                | 38.4 us: 1.53x faster                                         |
| unpickle_pure_python     | 327 us                                                 | 215 us: 1.52x faster                                          |
| async_tree_io            | 1.79 sec                                               | 1.18 sec: 1.51x faster                                        |
| coroutines               | 34.5 ms                                                | 22.8 ms: 1.51x faster                                         |
| spectral_norm            | 163 ms                                                 | 110 ms: 1.48x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                        |
| mako                     | 16.3 ms                                                | 11.4 ms: 1.43x faster                                         |
| float                    | 116 ms                                                 | 81.7 ms: 1.42x faster                                         |
| logging_simple           | 8.27 us                                                | 5.82 us: 1.42x faster                                         |
| chameleon                | 9.84 ms                                                | 6.96 ms: 1.41x faster                                         |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 713 ms: 1.41x faster                                          |
| tomli_loads              | 3.06 sec                                               | 2.17 sec: 1.41x faster                                        |
| logging_format           | 9.07 us                                                | 6.44 us: 1.41x faster                                         |
| pprint_pformat           | 2.10 sec                                               | 1.49 sec: 1.41x faster                                        |
| pprint_safe_repr         | 1.01 sec                                               | 728 ms: 1.39x faster                                          |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                         |
| deepcopy                 | 481 us                                                 | 347 us: 1.39x faster                                          |
| regex_compile            | 186 ms                                                 | 134 ms: 1.38x faster                                          |
| tornado_http             | 131 ms                                                 | 95.1 ms: 1.37x faster                                         |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                         |
| nqueens                  | 107 ms                                                 | 78.3 ms: 1.36x faster                                         |
| deepcopy_reduce          | 4.17 us                                                | 3.06 us: 1.36x faster                                         |
| sqlglot_normalize        | 141 ms                                                 | 105 ms: 1.35x faster                                          |
| xml_etree_process        | 79.8 ms                                                | 59.3 ms: 1.34x faster                                         |
| fannkuch                 | 527 ms                                                 | 392 ms: 1.34x faster                                          |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.34x faster                                        |
| sympy_integrate          | 25.4 ms                                                | 19.3 ms: 1.31x faster                                         |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                          |
| mypy2                    | 442 ms                                                 | 340 ms: 1.30x faster                                          |
| sympy_sum                | 190 ms                                                 | 147 ms: 1.30x faster                                          |
| sqlglot_optimize         | 68.7 ms                                                | 53.1 ms: 1.29x faster                                         |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.79 ms: 1.27x faster                                         |
| sympy_str                | 337 ms                                                 | 267 ms: 1.26x faster                                          |
| docutils                 | 3.26 sec                                               | 2.60 sec: 1.25x faster                                        |
| sympy_expand             | 558 ms                                                 | 447 ms: 1.25x faster                                          |
| unpack_sequence          | 65.7 ns                                                | 53.9 ns: 1.22x faster                                         |
| scimark_fft              | 454 ms                                                 | 376 ms: 1.21x faster                                          |
| bench_thread_pool        | 966 us                                                 | 811 us: 1.19x faster                                          |
| dulwich_log              | 77.0 ms                                                | 65.7 ms: 1.17x faster                                         |
| xml_etree_generate       | 100.0 ms                                               | 86.2 ms: 1.16x faster                                         |
| mdp                      | 2.93 sec                                               | 2.54 sec: 1.16x faster                                        |
| json_loads               | 31.4 us                                                | 27.8 us: 1.13x faster                                         |
| meteor_contest           | 119 ms                                                 | 106 ms: 1.12x faster                                          |
| json                     | 5.67 ms                                                | 5.10 ms: 1.11x faster                                         |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.10x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.49 ms: 1.08x faster                                         |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.07x faster                                          |
| sqlite_synth             | 3.02 us                                                | 2.83 us: 1.07x faster                                         |
| pathlib                  | 20.3 ms                                                | 19.1 ms: 1.06x faster                                         |
| regex_v8                 | 26.2 ms                                                | 25.5 ms: 1.03x faster                                         |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                          |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                          |
| regex_dna                | 215 ms                                                 | 217 ms: 1.01x slower                                          |
| pickle_list              | 5.05 us                                                | 5.11 us: 1.01x slower                                         |
| async_generators         | 442 ms                                                 | 448 ms: 1.01x slower                                          |
| unpickle_list            | 5.10 us                                                | 5.19 us: 1.02x slower                                         |
| unpickle                 | 14.9 us                                                | 15.8 us: 1.06x slower                                         |
| regex_effbot             | 3.41 ms                                                | 3.68 ms: 1.08x slower                                         |
| pickle                   | 10.7 us                                                | 11.5 us: 1.08x slower                                         |
| gc_traversal             | 3.43 ms                                                | 3.82 ms: 1.11x slower                                         |
| coverage                 | 82.0 ms                                                | 94.3 ms: 1.15x slower                                         |
| telco                    | 7.01 ms                                                | 8.31 ms: 1.18x slower                                         |
| pickle_dict              | 30.0 us                                                | 36.0 us: 1.20x slower                                         |
| python_startup_no_site   | 5.87 ms                                                | 8.98 ms: 1.53x slower                                         |
| Geometric mean           | (ref)                                                  | 1.34x faster                                                  |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-309abda/bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-309abda.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.31x
- 95% likely to have a speedup of 1.30x
- 99% likely to have a speedup of 1.27x
