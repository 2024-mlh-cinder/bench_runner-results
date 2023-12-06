
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_ghccc
- machine: linux-x86_64
- commit hash: fb676a6
- commit date: 2023-11-08
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 273 ms: 1.26x faster                                                    |
| chameleon      | 9.84 ms                                                | 7.32 ms: 1.35x faster                                                   |
| docutils       | 3.26 sec                                               | 2.65 sec: 1.23x faster                                                  |
| tornado_http   | 131 ms                                                 | 96.8 ms: 1.35x faster                                                   |
| Geometric mean | (ref)                                                  | 1.30x faster                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 447 ms: 1.64x faster                                                    |
| async_tree_memoization  | 867 ms                                                 | 567 ms: 1.53x faster                                                    |
| async_tree_io           | 1.79 sec                                               | 1.18 sec: 1.51x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 724 ms: 1.39x faster                                                    |
| Geometric mean          | (ref)                                                  | 1.52x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 103 ms: 1.44x faster                                                    |
| float          | 116 ms                                                 | 86.8 ms: 1.34x faster                                                   |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                  | 1.25x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 142 ms: 1.31x faster                                                    |
| regex_v8       | 26.2 ms                                                | 25.4 ms: 1.03x faster                                                   |
| regex_effbot   | 3.41 ms                                                | 3.77 ms: 1.10x slower                                                   |
| Geometric mean | (ref)                                                  | 1.05x faster                                                            |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 303 us: 1.59x faster                                                    |
| tomli_loads          | 3.06 sec                                               | 2.16 sec: 1.42x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 231 us: 1.41x faster                                                    |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                                   |
| xml_etree_process    | 79.8 ms                                                | 60.0 ms: 1.33x faster                                                   |
| xml_etree_generate   | 100.0 ms                                               | 87.1 ms: 1.15x faster                                                   |
| json_loads           | 31.4 us                                                | 27.7 us: 1.13x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                    |
| xml_etree_iterparse  | 116 ms                                                 | 109 ms: 1.07x faster                                                    |
| pickle_list          | 5.05 us                                                | 4.83 us: 1.05x faster                                                   |
| unpickle_list        | 5.10 us                                                | 5.07 us: 1.00x faster                                                   |
| unpickle             | 14.9 us                                                | 15.1 us: 1.02x slower                                                   |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                                   |
| pickle_dict          | 30.0 us                                                | 33.3 us: 1.11x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                   |
| python_startup_no_site | 5.87 ms                                                | 9.12 ms: 1.55x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.1 ms: 1.34x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 119 us: 4.70x faster                                                    |
| generators               | 78.9 ms                                                | 29.8 ms: 2.65x faster                                                   |
| deltablue                | 7.81 ms                                                | 3.94 ms: 1.98x faster                                                   |
| asyncio_tcp              | 918 ms                                                 | 487 ms: 1.88x faster                                                    |
| richards_super           | 95.6 ms                                                | 53.7 ms: 1.78x faster                                                   |
| logging_silent           | 189 ns                                                 | 106 ns: 1.78x faster                                                    |
| raytrace                 | 498 ms                                                 | 284 ms: 1.75x faster                                                    |
| chaos                    | 114 ms                                                 | 65.5 ms: 1.75x faster                                                   |
| scimark_sor              | 214 ms                                                 | 126 ms: 1.70x faster                                                    |
| richards                 | 79.4 ms                                                | 47.3 ms: 1.68x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.30 ms: 1.65x faster                                                   |
| async_tree_none          | 732 ms                                                 | 447 ms: 1.64x faster                                                    |
| crypto_pyaes             | 127 ms                                                 | 78.2 ms: 1.62x faster                                                   |
| go                       | 238 ms                                                 | 148 ms: 1.60x faster                                                    |
| scimark_monte_carlo      | 118 ms                                                 | 73.5 ms: 1.60x faster                                                   |
| pickle_pure_python       | 482 us                                                 | 303 us: 1.59x faster                                                    |
| unpack_sequence          | 65.7 ns                                                | 41.4 ns: 1.59x faster                                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.63 ms: 1.57x faster                                                   |
| coroutines               | 34.5 ms                                                | 22.5 ms: 1.53x faster                                                   |
| async_tree_memoization   | 867 ms                                                 | 567 ms: 1.53x faster                                                    |
| async_tree_io            | 1.79 sec                                               | 1.18 sec: 1.51x faster                                                  |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                                    |
| spectral_norm            | 163 ms                                                 | 112 ms: 1.45x faster                                                    |
| comprehensions           | 28.5 us                                                | 19.7 us: 1.45x faster                                                   |
| nbody                    | 148 ms                                                 | 103 ms: 1.44x faster                                                    |
| deepcopy_memo            | 58.8 us                                                | 40.8 us: 1.44x faster                                                   |
| logging_simple           | 8.27 us                                                | 5.75 us: 1.44x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                                  |
| logging_format           | 9.07 us                                                | 6.35 us: 1.43x faster                                                   |
| pyflate                  | 708 ms                                                 | 497 ms: 1.43x faster                                                    |
| tomli_loads              | 3.06 sec                                               | 2.16 sec: 1.42x faster                                                  |
| unpickle_pure_python     | 327 us                                                 | 231 us: 1.41x faster                                                    |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 724 ms: 1.39x faster                                                    |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.37x faster                                                   |
| hexiom                   | 10.3 ms                                                | 7.51 ms: 1.37x faster                                                   |
| deepcopy                 | 481 us                                                 | 355 us: 1.35x faster                                                    |
| tornado_http             | 131 ms                                                 | 96.8 ms: 1.35x faster                                                   |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                                   |
| chameleon                | 9.84 ms                                                | 7.32 ms: 1.35x faster                                                   |
| mako                     | 16.3 ms                                                | 12.1 ms: 1.34x faster                                                   |
| float                    | 116 ms                                                 | 86.8 ms: 1.34x faster                                                   |
| pycparser                | 1.57 sec                                               | 1.17 sec: 1.34x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.34x faster                                                    |
| xml_etree_process        | 79.8 ms                                                | 60.0 ms: 1.33x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.16 us: 1.32x faster                                                   |
| regex_compile            | 186 ms                                                 | 142 ms: 1.31x faster                                                    |
| pprint_pformat           | 2.10 sec                                               | 1.60 sec: 1.31x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 778 ms: 1.30x faster                                                    |
| sqlglot_optimize         | 68.7 ms                                                | 54.3 ms: 1.27x faster                                                   |
| 2to3                     | 346 ms                                                 | 273 ms: 1.26x faster                                                    |
| mypy2                    | 442 ms                                                 | 350 ms: 1.26x faster                                                    |
| sympy_sum                | 190 ms                                                 | 153 ms: 1.25x faster                                                    |
| fannkuch                 | 527 ms                                                 | 424 ms: 1.24x faster                                                    |
| sympy_integrate          | 25.4 ms                                                | 20.6 ms: 1.23x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.65 sec: 1.23x faster                                                  |
| sympy_str                | 337 ms                                                 | 274 ms: 1.23x faster                                                    |
| sympy_expand             | 558 ms                                                 | 460 ms: 1.21x faster                                                    |
| scimark_fft              | 454 ms                                                 | 385 ms: 1.18x faster                                                    |
| nqueens                  | 107 ms                                                 | 91.4 ms: 1.17x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 66.6 ms: 1.16x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 87.1 ms: 1.15x faster                                                   |
| bench_thread_pool        | 966 us                                                 | 850 us: 1.14x faster                                                    |
| json_loads               | 31.4 us                                                | 27.7 us: 1.13x faster                                                   |
| mdp                      | 2.93 sec                                               | 2.64 sec: 1.11x faster                                                  |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.50 ms: 1.11x faster                                                   |
| json                     | 5.67 ms                                                | 5.16 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.10x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.79 us: 1.08x faster                                                   |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                    |
| xml_etree_iterparse      | 116 ms                                                 | 109 ms: 1.07x faster                                                    |
| meteor_contest           | 119 ms                                                 | 113 ms: 1.05x faster                                                    |
| pathlib                  | 20.3 ms                                                | 19.3 ms: 1.05x faster                                                   |
| pickle_list              | 5.05 us                                                | 4.83 us: 1.05x faster                                                   |
| regex_v8                 | 26.2 ms                                                | 25.4 ms: 1.03x faster                                                   |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                    |
| unpickle_list            | 5.10 us                                                | 5.07 us: 1.00x faster                                                   |
| unpickle                 | 14.9 us                                                | 15.1 us: 1.02x slower                                                   |
| async_generators         | 442 ms                                                 | 465 ms: 1.05x slower                                                    |
| gc_traversal             | 3.43 ms                                                | 3.67 ms: 1.07x slower                                                   |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                                   |
| regex_effbot             | 3.41 ms                                                | 3.77 ms: 1.10x slower                                                   |
| pickle_dict              | 30.0 us                                                | 33.3 us: 1.11x slower                                                   |
| coverage                 | 82.0 ms                                                | 96.0 ms: 1.17x slower                                                   |
| telco                    | 7.01 ms                                                | 9.01 ms: 1.28x slower                                                   |
| python_startup_no_site   | 5.87 ms                                                | 9.12 ms: 1.55x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                            |

Benchmark hidden because not significant (2): bench_mp_pool, regex_dna
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231108-3.13.0a1+-fb676a6/bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.23x
