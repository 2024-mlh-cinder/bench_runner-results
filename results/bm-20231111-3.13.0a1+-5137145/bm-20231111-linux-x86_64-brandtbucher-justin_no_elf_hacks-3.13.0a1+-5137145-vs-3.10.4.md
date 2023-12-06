
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: linux-x86_64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.29x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 274 ms: 1.26x faster                                                        |
| chameleon      | 9.84 ms                                                | 7.32 ms: 1.34x faster                                                       |
| docutils       | 3.26 sec                                               | 2.65 sec: 1.23x faster                                                      |
| tornado_http   | 131 ms                                                 | 96.4 ms: 1.36x faster                                                       |
| Geometric mean | (ref)                                                  | 1.30x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 446 ms: 1.64x faster                                                        |
| async_tree_memoization  | 867 ms                                                 | 571 ms: 1.52x faster                                                        |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.49x faster                                                      |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 724 ms: 1.39x faster                                                        |
| Geometric mean          | (ref)                                                  | 1.51x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 103 ms: 1.44x faster                                                        |
| float          | 116 ms                                                 | 88.0 ms: 1.32x faster                                                       |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                                        |
| Geometric mean | (ref)                                                  | 1.23x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 142 ms: 1.31x faster                                                        |
| regex_v8       | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                       |
| regex_dna      | 215 ms                                                 | 216 ms: 1.00x slower                                                        |
| regex_effbot   | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                       |
| Geometric mean | (ref)                                                  | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 304 us: 1.59x faster                                                        |
| unpickle_pure_python | 327 us                                                 | 233 us: 1.40x faster                                                        |
| json_dumps           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                       |
| tomli_loads          | 3.06 sec                                               | 2.28 sec: 1.34x faster                                                      |
| xml_etree_process    | 79.8 ms                                                | 60.0 ms: 1.33x faster                                                       |
| xml_etree_generate   | 100.0 ms                                               | 87.7 ms: 1.14x faster                                                       |
| json_loads           | 31.4 us                                                | 27.6 us: 1.14x faster                                                       |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                        |
| xml_etree_iterparse  | 116 ms                                                 | 108 ms: 1.08x faster                                                        |
| pickle_list          | 5.05 us                                                | 5.01 us: 1.01x faster                                                       |
| pickle               | 10.7 us                                                | 11.3 us: 1.06x slower                                                       |
| unpickle_list        | 5.10 us                                                | 5.69 us: 1.12x slower                                                       |
| pickle_dict          | 30.0 us                                                | 34.7 us: 1.16x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                                |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                       |
| python_startup_no_site | 5.87 ms                                                | 9.06 ms: 1.54x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.4 ms: 1.31x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 122 us: 4.60x faster                                                        |
| generators               | 78.9 ms                                                | 29.0 ms: 2.72x faster                                                       |
| deltablue                | 7.81 ms                                                | 4.13 ms: 1.89x faster                                                       |
| asyncio_tcp              | 918 ms                                                 | 495 ms: 1.85x faster                                                        |
| richards_super           | 95.6 ms                                                | 53.5 ms: 1.79x faster                                                       |
| logging_silent           | 189 ns                                                 | 107 ns: 1.77x faster                                                        |
| raytrace                 | 498 ms                                                 | 284 ms: 1.75x faster                                                        |
| chaos                    | 114 ms                                                 | 65.6 ms: 1.74x faster                                                       |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.72x faster                                                        |
| richards                 | 79.4 ms                                                | 47.0 ms: 1.69x faster                                                       |
| sqlglot_parse            | 2.15 ms                                                | 1.29 ms: 1.66x faster                                                       |
| async_tree_none          | 732 ms                                                 | 446 ms: 1.64x faster                                                        |
| unpack_sequence          | 65.7 ns                                                | 40.5 ns: 1.62x faster                                                       |
| crypto_pyaes             | 127 ms                                                 | 78.4 ms: 1.62x faster                                                       |
| scimark_monte_carlo      | 118 ms                                                 | 73.5 ms: 1.60x faster                                                       |
| pickle_pure_python       | 482 us                                                 | 304 us: 1.59x faster                                                        |
| coroutines               | 34.5 ms                                                | 21.8 ms: 1.58x faster                                                       |
| sqlglot_transpile        | 2.55 ms                                                | 1.62 ms: 1.58x faster                                                       |
| go                       | 238 ms                                                 | 151 ms: 1.57x faster                                                        |
| async_tree_memoization   | 867 ms                                                 | 571 ms: 1.52x faster                                                        |
| scimark_lu               | 175 ms                                                 | 117 ms: 1.50x faster                                                        |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.49x faster                                                      |
| deepcopy_memo            | 58.8 us                                                | 40.7 us: 1.44x faster                                                       |
| nbody                    | 148 ms                                                 | 103 ms: 1.44x faster                                                        |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                                      |
| spectral_norm            | 163 ms                                                 | 114 ms: 1.44x faster                                                        |
| unpickle_pure_python     | 327 us                                                 | 233 us: 1.40x faster                                                        |
| logging_simple           | 8.27 us                                                | 5.92 us: 1.40x faster                                                       |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 724 ms: 1.39x faster                                                        |
| logging_format           | 9.07 us                                                | 6.53 us: 1.39x faster                                                       |
| comprehensions           | 28.5 us                                                | 20.6 us: 1.39x faster                                                       |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                       |
| json_dumps               | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                       |
| tornado_http             | 131 ms                                                 | 96.4 ms: 1.36x faster                                                       |
| deepcopy                 | 481 us                                                 | 355 us: 1.35x faster                                                        |
| pyflate                  | 708 ms                                                 | 526 ms: 1.35x faster                                                        |
| chameleon                | 9.84 ms                                                | 7.32 ms: 1.34x faster                                                       |
| tomli_loads              | 3.06 sec                                               | 2.28 sec: 1.34x faster                                                      |
| deepcopy_reduce          | 4.17 us                                                | 3.13 us: 1.33x faster                                                       |
| xml_etree_process        | 79.8 ms                                                | 60.0 ms: 1.33x faster                                                       |
| float                    | 116 ms                                                 | 88.0 ms: 1.32x faster                                                       |
| sqlglot_normalize        | 141 ms                                                 | 107 ms: 1.32x faster                                                        |
| pprint_pformat           | 2.10 sec                                               | 1.59 sec: 1.32x faster                                                      |
| hexiom                   | 10.3 ms                                                | 7.84 ms: 1.31x faster                                                       |
| mako                     | 16.3 ms                                                | 12.4 ms: 1.31x faster                                                       |
| regex_compile            | 186 ms                                                 | 142 ms: 1.31x faster                                                        |
| pprint_safe_repr         | 1.01 sec                                               | 778 ms: 1.30x faster                                                        |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.29x faster                                                      |
| sqlglot_optimize         | 68.7 ms                                                | 53.9 ms: 1.28x faster                                                       |
| mypy2                    | 442 ms                                                 | 348 ms: 1.27x faster                                                        |
| 2to3                     | 346 ms                                                 | 274 ms: 1.26x faster                                                        |
| sympy_sum                | 190 ms                                                 | 152 ms: 1.25x faster                                                        |
| docutils                 | 3.26 sec                                               | 2.65 sec: 1.23x faster                                                      |
| sympy_integrate          | 25.4 ms                                                | 20.6 ms: 1.23x faster                                                       |
| sympy_str                | 337 ms                                                 | 274 ms: 1.23x faster                                                        |
| sympy_expand             | 558 ms                                                 | 460 ms: 1.21x faster                                                        |
| scimark_fft              | 454 ms                                                 | 388 ms: 1.17x faster                                                        |
| fannkuch                 | 527 ms                                                 | 453 ms: 1.16x faster                                                        |
| dulwich_log              | 77.0 ms                                                | 66.7 ms: 1.15x faster                                                       |
| xml_etree_generate       | 100.0 ms                                               | 87.7 ms: 1.14x faster                                                       |
| json_loads               | 31.4 us                                                | 27.6 us: 1.14x faster                                                       |
| bench_thread_pool        | 966 us                                                 | 850 us: 1.14x faster                                                        |
| mdp                      | 2.93 sec                                               | 2.65 sec: 1.11x faster                                                      |
| nqueens                  | 107 ms                                                 | 96.6 ms: 1.10x faster                                                       |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.53 ms: 1.10x faster                                                       |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                                       |
| json                     | 5.67 ms                                                | 5.18 ms: 1.10x faster                                                       |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                        |
| xml_etree_iterparse      | 116 ms                                                 | 108 ms: 1.08x faster                                                        |
| sqlite_synth             | 3.02 us                                                | 2.81 us: 1.08x faster                                                       |
| meteor_contest           | 119 ms                                                 | 114 ms: 1.04x faster                                                        |
| pathlib                  | 20.3 ms                                                | 19.5 ms: 1.04x faster                                                       |
| regex_v8                 | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                       |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                        |
| pickle_list              | 5.05 us                                                | 5.01 us: 1.01x faster                                                       |
| regex_dna                | 215 ms                                                 | 216 ms: 1.00x slower                                                        |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                                        |
| async_generators         | 442 ms                                                 | 465 ms: 1.05x slower                                                        |
| pickle                   | 10.7 us                                                | 11.3 us: 1.06x slower                                                       |
| regex_effbot             | 3.41 ms                                                | 3.62 ms: 1.06x slower                                                       |
| unpickle_list            | 5.10 us                                                | 5.69 us: 1.12x slower                                                       |
| coverage                 | 82.0 ms                                                | 94.6 ms: 1.15x slower                                                       |
| pickle_dict              | 30.0 us                                                | 34.7 us: 1.16x slower                                                       |
| gc_traversal             | 3.43 ms                                                | 4.08 ms: 1.19x slower                                                       |
| telco                    | 7.01 ms                                                | 8.50 ms: 1.21x slower                                                       |
| python_startup_no_site   | 5.87 ms                                                | 9.06 ms: 1.54x slower                                                       |
| Geometric mean           | (ref)                                                  | 1.29x faster                                                                |

Benchmark hidden because not significant (2): bench_mp_pool, unpickle
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-5137145/bm-20231111-linux-x86_64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.23x
