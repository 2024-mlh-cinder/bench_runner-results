
# Results vs. 3.10.4

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: ab9b54e
- commit date: 2023-10-30
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 290 ms: 1.19x faster                                               |
| chameleon      | 9.84 ms                                                | 7.46 ms: 1.32x faster                                              |
| docutils       | 3.26 sec                                               | 2.76 sec: 1.18x faster                                             |
| tornado_http   | 131 ms                                                 | 102 ms: 1.28x faster                                               |
| Geometric mean | (ref)                                                  | 1.24x faster                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 457 ms: 1.60x faster                                               |
| async_tree_io           | 1.79 sec                                               | 1.21 sec: 1.48x faster                                             |
| async_tree_memoization  | 867 ms                                                 | 585 ms: 1.48x faster                                               |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 725 ms: 1.39x faster                                               |
| Geometric mean          | (ref)                                                  | 1.49x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 110 ms: 1.35x faster                                               |
| float          | 116 ms                                                 | 95.9 ms: 1.21x faster                                              |
| pidigits       | 190 ms                                                 | 196 ms: 1.03x slower                                               |
| Geometric mean | (ref)                                                  | 1.17x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 162 ms: 1.15x faster                                               |
| regex_v8       | 26.2 ms                                                | 25.9 ms: 1.01x faster                                              |
| regex_effbot   | 3.41 ms                                                | 3.58 ms: 1.05x slower                                              |
| Geometric mean | (ref)                                                  | 1.03x faster                                                       |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 312 us: 1.55x faster                                               |
| unpickle_pure_python | 327 us                                                 | 240 us: 1.36x faster                                               |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                              |
| xml_etree_process    | 79.8 ms                                                | 60.0 ms: 1.33x faster                                              |
| tomli_loads          | 3.06 sec                                               | 2.46 sec: 1.24x faster                                             |
| xml_etree_generate   | 100.0 ms                                               | 87.7 ms: 1.14x faster                                              |
| json_loads           | 31.4 us                                                | 27.6 us: 1.14x faster                                              |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                               |
| xml_etree_iterparse  | 116 ms                                                 | 111 ms: 1.04x faster                                               |
| pickle_list          | 5.05 us                                                | 5.02 us: 1.01x faster                                              |
| unpickle_list        | 5.10 us                                                | 5.14 us: 1.01x slower                                              |
| pickle               | 10.7 us                                                | 11.2 us: 1.05x slower                                              |
| pickle_dict          | 30.0 us                                                | 35.1 us: 1.17x slower                                              |
| Geometric mean       | (ref)                                                  | 1.13x faster                                                       |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                              |
| python_startup_no_site | 5.87 ms                                                | 9.00 ms: 1.53x slower                                              |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 13.2 ms: 1.23x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 159 us: 3.53x faster                                               |
| generators               | 78.9 ms                                                | 30.4 ms: 2.59x faster                                              |
| asyncio_tcp              | 918 ms                                                 | 477 ms: 1.92x faster                                               |
| logging_silent           | 189 ns                                                 | 106 ns: 1.78x faster                                               |
| deltablue                | 7.81 ms                                                | 4.61 ms: 1.70x faster                                              |
| richards_super           | 95.6 ms                                                | 57.0 ms: 1.68x faster                                              |
| scimark_sor              | 214 ms                                                 | 128 ms: 1.67x faster                                               |
| raytrace                 | 498 ms                                                 | 309 ms: 1.61x faster                                               |
| sqlglot_parse            | 2.15 ms                                                | 1.34 ms: 1.61x faster                                              |
| async_tree_none          | 732 ms                                                 | 457 ms: 1.60x faster                                               |
| richards                 | 79.4 ms                                                | 50.5 ms: 1.57x faster                                              |
| pickle_pure_python       | 482 us                                                 | 312 us: 1.55x faster                                               |
| scimark_monte_carlo      | 118 ms                                                 | 77.1 ms: 1.53x faster                                              |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.53x faster                                              |
| chaos                    | 114 ms                                                 | 75.0 ms: 1.52x faster                                              |
| coroutines               | 34.5 ms                                                | 22.8 ms: 1.51x faster                                              |
| crypto_pyaes             | 127 ms                                                 | 83.9 ms: 1.51x faster                                              |
| async_tree_io            | 1.79 sec                                               | 1.21 sec: 1.48x faster                                             |
| async_tree_memoization   | 867 ms                                                 | 585 ms: 1.48x faster                                               |
| unpack_sequence          | 65.7 ns                                                | 45.0 ns: 1.46x faster                                              |
| scimark_lu               | 175 ms                                                 | 121 ms: 1.45x faster                                               |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                             |
| go                       | 238 ms                                                 | 166 ms: 1.43x faster                                               |
| spectral_norm            | 163 ms                                                 | 116 ms: 1.41x faster                                               |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 725 ms: 1.39x faster                                               |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                              |
| deepcopy_memo            | 58.8 us                                                | 42.8 us: 1.37x faster                                              |
| unpickle_pure_python     | 327 us                                                 | 240 us: 1.36x faster                                               |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                              |
| nbody                    | 148 ms                                                 | 110 ms: 1.35x faster                                               |
| pyflate                  | 708 ms                                                 | 528 ms: 1.34x faster                                               |
| deepcopy                 | 481 us                                                 | 360 us: 1.34x faster                                               |
| xml_etree_process        | 79.8 ms                                                | 60.0 ms: 1.33x faster                                              |
| deepcopy_reduce          | 4.17 us                                                | 3.15 us: 1.32x faster                                              |
| chameleon                | 9.84 ms                                                | 7.46 ms: 1.32x faster                                              |
| sqlglot_normalize        | 141 ms                                                 | 108 ms: 1.32x faster                                               |
| logging_simple           | 8.27 us                                                | 6.35 us: 1.30x faster                                              |
| comprehensions           | 28.5 us                                                | 22.2 us: 1.29x faster                                              |
| tornado_http             | 131 ms                                                 | 102 ms: 1.28x faster                                               |
| pprint_pformat           | 2.10 sec                                               | 1.67 sec: 1.25x faster                                             |
| pprint_safe_repr         | 1.01 sec                                               | 810 ms: 1.25x faster                                               |
| pycparser                | 1.57 sec                                               | 1.26 sec: 1.25x faster                                             |
| logging_format           | 9.07 us                                                | 7.29 us: 1.25x faster                                              |
| sqlglot_optimize         | 68.7 ms                                                | 55.2 ms: 1.24x faster                                              |
| tomli_loads              | 3.06 sec                                               | 2.46 sec: 1.24x faster                                             |
| mypy2                    | 442 ms                                                 | 357 ms: 1.24x faster                                               |
| mako                     | 16.3 ms                                                | 13.2 ms: 1.23x faster                                              |
| float                    | 116 ms                                                 | 95.9 ms: 1.21x faster                                              |
| sympy_sum                | 190 ms                                                 | 157 ms: 1.21x faster                                               |
| 2to3                     | 346 ms                                                 | 290 ms: 1.19x faster                                               |
| docutils                 | 3.26 sec                                               | 2.76 sec: 1.18x faster                                             |
| sympy_integrate          | 25.4 ms                                                | 21.5 ms: 1.18x faster                                              |
| sympy_str                | 337 ms                                                 | 287 ms: 1.17x faster                                               |
| hexiom                   | 10.3 ms                                                | 8.84 ms: 1.16x faster                                              |
| fannkuch                 | 527 ms                                                 | 455 ms: 1.16x faster                                               |
| sympy_expand             | 558 ms                                                 | 484 ms: 1.15x faster                                               |
| regex_compile            | 186 ms                                                 | 162 ms: 1.15x faster                                               |
| xml_etree_generate       | 100.0 ms                                               | 87.7 ms: 1.14x faster                                              |
| json_loads               | 31.4 us                                                | 27.6 us: 1.14x faster                                              |
| bench_thread_pool        | 966 us                                                 | 849 us: 1.14x faster                                               |
| create_gc_cycles         | 1.61 ms                                                | 1.45 ms: 1.11x faster                                              |
| dulwich_log              | 77.0 ms                                                | 69.7 ms: 1.10x faster                                              |
| json                     | 5.67 ms                                                | 5.14 ms: 1.10x faster                                              |
| nqueens                  | 107 ms                                                 | 98.3 ms: 1.08x faster                                              |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                               |
| sqlite_synth             | 3.02 us                                                | 2.86 us: 1.06x faster                                              |
| xml_etree_iterparse      | 116 ms                                                 | 111 ms: 1.04x faster                                               |
| meteor_contest           | 119 ms                                                 | 115 ms: 1.04x faster                                               |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.88 ms: 1.04x faster                                              |
| scimark_fft              | 454 ms                                                 | 439 ms: 1.03x faster                                               |
| pathlib                  | 20.3 ms                                                | 19.8 ms: 1.03x faster                                              |
| mdp                      | 2.93 sec                                               | 2.88 sec: 1.02x faster                                             |
| regex_v8                 | 26.2 ms                                                | 25.9 ms: 1.01x faster                                              |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                               |
| pickle_list              | 5.05 us                                                | 5.02 us: 1.01x faster                                              |
| unpickle_list            | 5.10 us                                                | 5.14 us: 1.01x slower                                              |
| gc_traversal             | 3.43 ms                                                | 3.50 ms: 1.02x slower                                              |
| pidigits                 | 190 ms                                                 | 196 ms: 1.03x slower                                               |
| pickle                   | 10.7 us                                                | 11.2 us: 1.05x slower                                              |
| regex_effbot             | 3.41 ms                                                | 3.58 ms: 1.05x slower                                              |
| async_generators         | 442 ms                                                 | 479 ms: 1.09x slower                                               |
| coverage                 | 82.0 ms                                                | 94.2 ms: 1.15x slower                                              |
| pickle_dict              | 30.0 us                                                | 35.1 us: 1.17x slower                                              |
| telco                    | 7.01 ms                                                | 8.53 ms: 1.22x slower                                              |
| python_startup_no_site   | 5.87 ms                                                | 9.00 ms: 1.53x slower                                              |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                       |

Benchmark hidden because not significant (3): unpickle, bench_mp_pool, regex_dna
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231030-3.13.0a1+-ab9b54e/bm-20231030-linux-x86_64-gvanrossum-uops_forever-3.13.0a1+-ab9b54e.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.18x
