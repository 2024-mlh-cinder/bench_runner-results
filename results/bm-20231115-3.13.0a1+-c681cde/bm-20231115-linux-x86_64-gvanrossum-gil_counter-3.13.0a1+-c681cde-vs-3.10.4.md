
# Results vs. 3.10.4

- fork: gvanrossum
- ref: gil_counter
- machine: linux-x86_64
- commit hash: c681cde
- commit date: 2023-11-15
- overall geometric mean: 1.27x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.20x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 285 ms: 1.21x faster                                              |
| chameleon      | 9.84 ms                                                | 7.77 ms: 1.27x faster                                             |
| docutils       | 3.26 sec                                               | 2.70 sec: 1.21x faster                                            |
| tornado_http   | 131 ms                                                 | 98.0 ms: 1.33x faster                                             |
| Geometric mean | (ref)                                                  | 1.25x faster                                                      |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|-------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 444 ms: 1.65x faster                                              |
| async_tree_memoization  | 867 ms                                                 | 570 ms: 1.52x faster                                              |
| async_tree_io           | 1.79 sec                                               | 1.20 sec: 1.50x faster                                            |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 719 ms: 1.40x faster                                              |
| Geometric mean          | (ref)                                                  | 1.51x faster                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 102 ms: 1.45x faster                                              |
| float          | 116 ms                                                 | 83.4 ms: 1.40x faster                                             |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                              |
| Geometric mean | (ref)                                                  | 1.27x faster                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 151 ms: 1.23x faster                                              |
| regex_v8       | 26.2 ms                                                | 26.3 ms: 1.00x slower                                             |
| regex_dna      | 215 ms                                                 | 216 ms: 1.01x slower                                              |
| regex_effbot   | 3.41 ms                                                | 3.61 ms: 1.06x slower                                             |
| Geometric mean | (ref)                                                  | 1.04x faster                                                      |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 344 us: 1.40x faster                                              |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                             |
| unpickle_pure_python | 327 us                                                 | 246 us: 1.33x faster                                              |
| xml_etree_process    | 79.8 ms                                                | 61.7 ms: 1.29x faster                                             |
| tomli_loads          | 3.06 sec                                               | 2.46 sec: 1.25x faster                                            |
| xml_etree_generate   | 100.0 ms                                               | 89.1 ms: 1.12x faster                                             |
| json_loads           | 31.4 us                                                | 28.3 us: 1.11x faster                                             |
| xml_etree_iterparse  | 116 ms                                                 | 107 ms: 1.09x faster                                              |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                              |
| unpickle_list        | 5.10 us                                                | 4.93 us: 1.03x faster                                             |
| unpickle             | 14.9 us                                                | 14.9 us: 1.01x slower                                             |
| pickle_list          | 5.05 us                                                | 5.17 us: 1.03x slower                                             |
| pickle               | 10.7 us                                                | 11.6 us: 1.08x slower                                             |
| pickle_dict          | 30.0 us                                                | 34.3 us: 1.14x slower                                             |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                      |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                             |
| python_startup_no_site | 5.87 ms                                                | 9.04 ms: 1.54x slower                                             |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 12.0 ms: 1.36x faster                                             |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 117 us: 4.78x faster                                              |
| generators               | 78.9 ms                                                | 32.1 ms: 2.46x faster                                             |
| deltablue                | 7.81 ms                                                | 3.78 ms: 2.07x faster                                             |
| asyncio_tcp              | 918 ms                                                 | 494 ms: 1.86x faster                                              |
| chaos                    | 114 ms                                                 | 66.6 ms: 1.72x faster                                             |
| async_tree_none          | 732 ms                                                 | 444 ms: 1.65x faster                                              |
| logging_silent           | 189 ns                                                 | 115 ns: 1.64x faster                                              |
| raytrace                 | 498 ms                                                 | 306 ms: 1.62x faster                                              |
| scimark_monte_carlo      | 118 ms                                                 | 73.4 ms: 1.61x faster                                             |
| scimark_sor              | 214 ms                                                 | 135 ms: 1.59x faster                                              |
| crypto_pyaes             | 127 ms                                                 | 80.3 ms: 1.58x faster                                             |
| comprehensions           | 28.5 us                                                | 18.2 us: 1.57x faster                                             |
| async_tree_memoization   | 867 ms                                                 | 570 ms: 1.52x faster                                              |
| async_tree_io            | 1.79 sec                                               | 1.20 sec: 1.50x faster                                            |
| sqlglot_parse            | 2.15 ms                                                | 1.46 ms: 1.47x faster                                             |
| richards_super           | 95.6 ms                                                | 65.2 ms: 1.47x faster                                             |
| coroutines               | 34.5 ms                                                | 23.6 ms: 1.46x faster                                             |
| go                       | 238 ms                                                 | 163 ms: 1.46x faster                                              |
| nbody                    | 148 ms                                                 | 102 ms: 1.45x faster                                              |
| logging_simple           | 8.27 us                                                | 5.74 us: 1.44x faster                                             |
| scimark_lu               | 175 ms                                                 | 122 ms: 1.44x faster                                              |
| logging_format           | 9.07 us                                                | 6.34 us: 1.43x faster                                             |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                            |
| sqlglot_transpile        | 2.55 ms                                                | 1.79 ms: 1.43x faster                                             |
| hexiom                   | 10.3 ms                                                | 7.27 ms: 1.42x faster                                             |
| pyflate                  | 708 ms                                                 | 502 ms: 1.41x faster                                              |
| pickle_pure_python       | 482 us                                                 | 344 us: 1.40x faster                                              |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 719 ms: 1.40x faster                                              |
| float                    | 116 ms                                                 | 83.4 ms: 1.40x faster                                             |
| deepcopy_memo            | 58.8 us                                                | 42.3 us: 1.39x faster                                             |
| richards                 | 79.4 ms                                                | 57.3 ms: 1.39x faster                                             |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                             |
| unpack_sequence          | 65.7 ns                                                | 48.3 ns: 1.36x faster                                             |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                             |
| mako                     | 16.3 ms                                                | 12.0 ms: 1.36x faster                                             |
| tornado_http             | 131 ms                                                 | 98.0 ms: 1.33x faster                                             |
| spectral_norm            | 163 ms                                                 | 123 ms: 1.33x faster                                              |
| unpickle_pure_python     | 327 us                                                 | 246 us: 1.33x faster                                              |
| xml_etree_process        | 79.8 ms                                                | 61.7 ms: 1.29x faster                                             |
| sqlglot_normalize        | 141 ms                                                 | 111 ms: 1.27x faster                                              |
| deepcopy_reduce          | 4.17 us                                                | 3.28 us: 1.27x faster                                             |
| pprint_pformat           | 2.10 sec                                               | 1.65 sec: 1.27x faster                                            |
| chameleon                | 9.84 ms                                                | 7.77 ms: 1.27x faster                                             |
| nqueens                  | 107 ms                                                 | 84.6 ms: 1.26x faster                                             |
| pprint_safe_repr         | 1.01 sec                                               | 810 ms: 1.25x faster                                              |
| deepcopy                 | 481 us                                                 | 385 us: 1.25x faster                                              |
| sympy_sum                | 190 ms                                                 | 153 ms: 1.25x faster                                              |
| tomli_loads              | 3.06 sec                                               | 2.46 sec: 1.25x faster                                            |
| mypy2                    | 442 ms                                                 | 357 ms: 1.24x faster                                              |
| sympy_integrate          | 25.4 ms                                                | 20.6 ms: 1.23x faster                                             |
| regex_compile            | 186 ms                                                 | 151 ms: 1.23x faster                                              |
| 2to3                     | 346 ms                                                 | 285 ms: 1.21x faster                                              |
| fannkuch                 | 527 ms                                                 | 435 ms: 1.21x faster                                              |
| docutils                 | 3.26 sec                                               | 2.70 sec: 1.21x faster                                            |
| sqlglot_optimize         | 68.7 ms                                                | 56.9 ms: 1.21x faster                                             |
| pycparser                | 1.57 sec                                               | 1.31 sec: 1.20x faster                                            |
| sympy_str                | 337 ms                                                 | 281 ms: 1.20x faster                                              |
| sympy_expand             | 558 ms                                                 | 467 ms: 1.19x faster                                              |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.17 ms: 1.18x faster                                             |
| scimark_fft              | 454 ms                                                 | 387 ms: 1.17x faster                                              |
| mdp                      | 2.93 sec                                               | 2.58 sec: 1.14x faster                                            |
| dulwich_log              | 77.0 ms                                                | 68.3 ms: 1.13x faster                                             |
| xml_etree_generate       | 100.0 ms                                               | 89.1 ms: 1.12x faster                                             |
| bench_thread_pool        | 966 us                                                 | 862 us: 1.12x faster                                              |
| json_loads               | 31.4 us                                                | 28.3 us: 1.11x faster                                             |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                             |
| json                     | 5.67 ms                                                | 5.17 ms: 1.10x faster                                             |
| xml_etree_iterparse      | 116 ms                                                 | 107 ms: 1.09x faster                                              |
| pathlib                  | 20.3 ms                                                | 18.7 ms: 1.09x faster                                             |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                              |
| sqlite_synth             | 3.02 us                                                | 2.82 us: 1.07x faster                                             |
| meteor_contest           | 119 ms                                                 | 112 ms: 1.06x faster                                              |
| unpickle_list            | 5.10 us                                                | 4.93 us: 1.03x faster                                             |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                              |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                              |
| regex_v8                 | 26.2 ms                                                | 26.3 ms: 1.00x slower                                             |
| unpickle                 | 14.9 us                                                | 14.9 us: 1.01x slower                                             |
| regex_dna                | 215 ms                                                 | 216 ms: 1.01x slower                                              |
| async_generators         | 442 ms                                                 | 452 ms: 1.02x slower                                              |
| pickle_list              | 5.05 us                                                | 5.17 us: 1.03x slower                                             |
| regex_effbot             | 3.41 ms                                                | 3.61 ms: 1.06x slower                                             |
| gc_traversal             | 3.43 ms                                                | 3.64 ms: 1.06x slower                                             |
| pickle                   | 10.7 us                                                | 11.6 us: 1.08x slower                                             |
| pickle_dict              | 30.0 us                                                | 34.3 us: 1.14x slower                                             |
| coverage                 | 82.0 ms                                                | 95.8 ms: 1.17x slower                                             |
| telco                    | 7.01 ms                                                | 8.44 ms: 1.20x slower                                             |
| python_startup_no_site   | 5.87 ms                                                | 9.04 ms: 1.54x slower                                             |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                      |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-c681cde/bm-20231115-linux-x86_64-gvanrossum-gil_counter-3.13.0a1+-c681cde.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.20x
