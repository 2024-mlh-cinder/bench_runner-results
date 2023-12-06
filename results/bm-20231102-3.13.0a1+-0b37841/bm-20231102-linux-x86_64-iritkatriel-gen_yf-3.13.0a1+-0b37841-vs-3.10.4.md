
# Results vs. 3.10.4

- fork: iritkatriel
- ref: gen_yf
- machine: linux-x86_64
- commit hash: 0b37841
- commit date: 2023-11-02
- overall geometric mean: 1.34x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.27x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                          |
| chameleon      | 9.84 ms                                                | 7.06 ms: 1.39x faster                                         |
| docutils       | 3.26 sec                                               | 2.61 sec: 1.25x faster                                        |
| tornado_http   | 131 ms                                                 | 95.1 ms: 1.37x faster                                         |
| Geometric mean | (ref)                                                  | 1.33x faster                                                  |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|-------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 436 ms: 1.68x faster                                          |
| async_tree_memoization  | 867 ms                                                 | 565 ms: 1.54x faster                                          |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                        |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 717 ms: 1.41x faster                                          |
| Geometric mean          | (ref)                                                  | 1.53x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 88.0 ms: 1.68x faster                                         |
| float          | 116 ms                                                 | 82.3 ms: 1.41x faster                                         |
| pidigits       | 190 ms                                                 | 195 ms: 1.03x slower                                          |
| Geometric mean | (ref)                                                  | 1.32x faster                                                  |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 134 ms: 1.38x faster                                          |
| regex_v8       | 26.2 ms                                                | 25.8 ms: 1.02x faster                                         |
| regex_effbot   | 3.41 ms                                                | 3.57 ms: 1.05x slower                                         |
| Geometric mean | (ref)                                                  | 1.08x faster                                                  |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 296 us: 1.63x faster                                          |
| unpickle_pure_python | 327 us                                                 | 217 us: 1.51x faster                                          |
| tomli_loads          | 3.06 sec                                               | 2.15 sec: 1.42x faster                                        |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                         |
| xml_etree_process    | 79.8 ms                                                | 59.4 ms: 1.34x faster                                         |
| xml_etree_generate   | 100.0 ms                                               | 86.5 ms: 1.16x faster                                         |
| json_loads           | 31.4 us                                                | 27.9 us: 1.13x faster                                         |
| xml_etree_iterparse  | 116 ms                                                 | 107 ms: 1.09x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 161 ms: 1.06x faster                                          |
| unpickle_list        | 5.10 us                                                | 5.15 us: 1.01x slower                                         |
| unpickle             | 14.9 us                                                | 15.8 us: 1.06x slower                                         |
| pickle               | 10.7 us                                                | 11.5 us: 1.08x slower                                         |
| pickle_dict          | 30.0 us                                                | 35.2 us: 1.17x slower                                         |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                  |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                         |
| python_startup_no_site | 5.87 ms                                                | 8.99 ms: 1.53x slower                                         |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.4 ms: 1.43x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 115 us: 4.88x faster                                          |
| generators               | 78.9 ms                                                | 30.2 ms: 2.61x faster                                         |
| deltablue                | 7.81 ms                                                | 3.33 ms: 2.35x faster                                         |
| asyncio_tcp              | 918 ms                                                 | 483 ms: 1.90x faster                                          |
| chaos                    | 114 ms                                                 | 61.4 ms: 1.86x faster                                         |
| raytrace                 | 498 ms                                                 | 275 ms: 1.81x faster                                          |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                          |
| richards_super           | 95.6 ms                                                | 54.4 ms: 1.76x faster                                         |
| crypto_pyaes             | 127 ms                                                 | 72.2 ms: 1.76x faster                                         |
| comprehensions           | 28.5 us                                                | 16.4 us: 1.74x faster                                         |
| scimark_monte_carlo      | 118 ms                                                 | 68.1 ms: 1.73x faster                                         |
| scimark_sor              | 214 ms                                                 | 125 ms: 1.72x faster                                          |
| nbody                    | 148 ms                                                 | 88.0 ms: 1.68x faster                                         |
| async_tree_none          | 732 ms                                                 | 436 ms: 1.68x faster                                          |
| hexiom                   | 10.3 ms                                                | 6.14 ms: 1.68x faster                                         |
| sqlglot_parse            | 2.15 ms                                                | 1.29 ms: 1.66x faster                                         |
| go                       | 238 ms                                                 | 143 ms: 1.66x faster                                          |
| richards                 | 79.4 ms                                                | 48.1 ms: 1.65x faster                                         |
| pickle_pure_python       | 482 us                                                 | 296 us: 1.63x faster                                          |
| sqlglot_transpile        | 2.55 ms                                                | 1.61 ms: 1.59x faster                                         |
| async_tree_memoization   | 867 ms                                                 | 565 ms: 1.54x faster                                          |
| deepcopy_memo            | 58.8 us                                                | 38.3 us: 1.53x faster                                         |
| scimark_lu               | 175 ms                                                 | 115 ms: 1.52x faster                                          |
| pyflate                  | 708 ms                                                 | 468 ms: 1.51x faster                                          |
| coroutines               | 34.5 ms                                                | 22.8 ms: 1.51x faster                                         |
| unpickle_pure_python     | 327 us                                                 | 217 us: 1.51x faster                                          |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                        |
| spectral_norm            | 163 ms                                                 | 110 ms: 1.48x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                        |
| mako                     | 16.3 ms                                                | 11.4 ms: 1.43x faster                                         |
| tomli_loads              | 3.06 sec                                               | 2.15 sec: 1.42x faster                                        |
| float                    | 116 ms                                                 | 82.3 ms: 1.41x faster                                         |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 717 ms: 1.41x faster                                          |
| logging_format           | 9.07 us                                                | 6.47 us: 1.40x faster                                         |
| chameleon                | 9.84 ms                                                | 7.06 ms: 1.39x faster                                         |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                         |
| logging_simple           | 8.27 us                                                | 5.97 us: 1.39x faster                                         |
| pprint_pformat           | 2.10 sec                                               | 1.51 sec: 1.39x faster                                        |
| deepcopy                 | 481 us                                                 | 348 us: 1.38x faster                                          |
| regex_compile            | 186 ms                                                 | 134 ms: 1.38x faster                                          |
| tornado_http             | 131 ms                                                 | 95.1 ms: 1.37x faster                                         |
| pprint_safe_repr         | 1.01 sec                                               | 740 ms: 1.37x faster                                          |
| unpack_sequence          | 65.7 ns                                                | 48.2 ns: 1.36x faster                                         |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                         |
| deepcopy_reduce          | 4.17 us                                                | 3.08 us: 1.35x faster                                         |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.52 ms: 1.35x faster                                         |
| nqueens                  | 107 ms                                                 | 79.0 ms: 1.35x faster                                         |
| xml_etree_process        | 79.8 ms                                                | 59.4 ms: 1.34x faster                                         |
| fannkuch                 | 527 ms                                                 | 396 ms: 1.33x faster                                          |
| sqlglot_normalize        | 141 ms                                                 | 107 ms: 1.32x faster                                          |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                          |
| sympy_integrate          | 25.4 ms                                                | 19.5 ms: 1.30x faster                                         |
| mypy2                    | 442 ms                                                 | 340 ms: 1.30x faster                                          |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.29x faster                                        |
| sympy_sum                | 190 ms                                                 | 147 ms: 1.29x faster                                          |
| sqlglot_optimize         | 68.7 ms                                                | 53.9 ms: 1.27x faster                                         |
| docutils                 | 3.26 sec                                               | 2.61 sec: 1.25x faster                                        |
| scimark_fft              | 454 ms                                                 | 362 ms: 1.25x faster                                          |
| sympy_str                | 337 ms                                                 | 273 ms: 1.23x faster                                          |
| sympy_expand             | 558 ms                                                 | 453 ms: 1.23x faster                                          |
| bench_thread_pool        | 966 us                                                 | 815 us: 1.19x faster                                          |
| dulwich_log              | 77.0 ms                                                | 65.9 ms: 1.17x faster                                         |
| xml_etree_generate       | 100.0 ms                                               | 86.5 ms: 1.16x faster                                         |
| mdp                      | 2.93 sec                                               | 2.57 sec: 1.14x faster                                        |
| json_loads               | 31.4 us                                                | 27.9 us: 1.13x faster                                         |
| json                     | 5.67 ms                                                | 5.10 ms: 1.11x faster                                         |
| meteor_contest           | 119 ms                                                 | 109 ms: 1.10x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.47 ms: 1.09x faster                                         |
| xml_etree_iterparse      | 116 ms                                                 | 107 ms: 1.09x faster                                          |
| sqlite_synth             | 3.02 us                                                | 2.79 us: 1.08x faster                                         |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                         |
| xml_etree_parse          | 171 ms                                                 | 161 ms: 1.06x faster                                          |
| regex_v8                 | 26.2 ms                                                | 25.8 ms: 1.02x faster                                         |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                          |
| unpickle_list            | 5.10 us                                                | 5.15 us: 1.01x slower                                         |
| async_generators         | 442 ms                                                 | 449 ms: 1.02x slower                                          |
| pidigits                 | 190 ms                                                 | 195 ms: 1.03x slower                                          |
| regex_effbot             | 3.41 ms                                                | 3.57 ms: 1.05x slower                                         |
| unpickle                 | 14.9 us                                                | 15.8 us: 1.06x slower                                         |
| pickle                   | 10.7 us                                                | 11.5 us: 1.08x slower                                         |
| gc_traversal             | 3.43 ms                                                | 3.81 ms: 1.11x slower                                         |
| coverage                 | 82.0 ms                                                | 95.7 ms: 1.17x slower                                         |
| telco                    | 7.01 ms                                                | 8.19 ms: 1.17x slower                                         |
| pickle_dict              | 30.0 us                                                | 35.2 us: 1.17x slower                                         |
| python_startup_no_site   | 5.87 ms                                                | 8.99 ms: 1.53x slower                                         |
| Geometric mean           | (ref)                                                  | 1.34x faster                                                  |

Benchmark hidden because not significant (3): pickle_list, bench_mp_pool, regex_dna
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231102-3.13.0a1+-0b37841/bm-20231102-linux-x86_64-iritkatriel-gen_yf-3.13.0a1+-0b37841.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.30x
- 95% likely to have a speedup of 1.29x
- 99% likely to have a speedup of 1.27x
