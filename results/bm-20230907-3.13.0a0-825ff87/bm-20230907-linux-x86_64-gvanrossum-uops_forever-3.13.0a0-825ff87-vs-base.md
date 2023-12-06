
# Results vs. base

- fork: gvanrossum
- ref: uops_forever
- machine: linux-x86_64
- commit hash: 825ff87
- commit date: 2023-09-07
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.72 sec: 1.04x slower                                            |
| tornado_http   | 95.3 ms                                                               | 97.8 ms: 1.03x slower                                             |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                      |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits       | 212 ms                                                                | 187 ms: 1.13x faster                                              |
| float          | 78.4 ms                                                               | 84.9 ms: 1.08x slower                                             |
| nbody          | 91.7 ms                                                               | 106 ms: 1.15x slower                                              |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                      |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| regex_dna      | 212 ms                                                                | 220 ms: 1.04x slower                                              |
| regex_effbot   | 3.61 ms                                                               | 3.82 ms: 1.06x slower                                             |
| regex_compile  | 135 ms                                                                | 152 ms: 1.13x slower                                              |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                      |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pickle_dict          | 32.8 us                                                               | 31.3 us: 1.05x faster                                             |
| unpickle             | 14.3 us                                                               | 13.8 us: 1.04x faster                                             |
| pickle_list          | 4.69 us                                                               | 4.59 us: 1.02x faster                                             |
| xml_etree_process    | 56.6 ms                                                               | 56.9 ms: 1.01x slower                                             |
| pickle               | 10.6 us                                                               | 10.8 us: 1.01x slower                                             |
| json_dumps           | 9.75 ms                                                               | 9.90 ms: 1.02x slower                                             |
| xml_etree_parse      | 151 ms                                                                | 153 ms: 1.02x slower                                              |
| xml_etree_iterparse  | 102 ms                                                                | 104 ms: 1.02x slower                                              |
| xml_etree_generate   | 81.5 ms                                                               | 83.3 ms: 1.02x slower                                             |
| pickle_pure_python   | 296 us                                                                | 303 us: 1.03x slower                                              |
| unpickle_pure_python | 212 us                                                                | 238 us: 1.12x slower                                              |
| tomli_loads          | 2.06 sec                                                              | 2.39 sec: 1.16x slower                                            |
| Geometric mean       | (ref)                                                                 | 1.02x slower                                                      |

Benchmark hidden because not significant (2): json_loads, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| python_startup         | 9.50 ms                                                               | 9.54 ms: 1.00x slower                                             |
| python_startup_no_site | 6.97 ms                                                               | 7.01 ms: 1.01x slower                                             |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                      |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| mako      | 10.8 ms                                                               | 11.9 ms: 1.10x slower                                             |

All benchmarks:
===============

| Benchmark                | bm-20230907-linux-x86_64-python-74fc96bc60f5c02bde50-3.13.0a0-74fc96b | bm-20230907-linux-x86_64-gvanrossum-uops_forever-3.13.0a0-825ff87 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------:|
| pidigits                 | 212 ms                                                                | 187 ms: 1.13x faster                                              |
| unpack_sequence          | 58.5 ns                                                               | 55.0 ns: 1.06x faster                                             |
| pickle_dict              | 32.8 us                                                               | 31.3 us: 1.05x faster                                             |
| unpickle                 | 14.3 us                                                               | 13.8 us: 1.04x faster                                             |
| pickle_list              | 4.69 us                                                               | 4.59 us: 1.02x faster                                             |
| generators               | 30.1 ms                                                               | 29.8 ms: 1.01x faster                                             |
| logging_silent           | 103 ns                                                                | 102 ns: 1.01x faster                                              |
| python_startup           | 9.50 ms                                                               | 9.54 ms: 1.00x slower                                             |
| python_startup_no_site   | 6.97 ms                                                               | 7.01 ms: 1.01x slower                                             |
| xml_etree_process        | 56.6 ms                                                               | 56.9 ms: 1.01x slower                                             |
| sqlglot_normalize        | 105 ms                                                                | 105 ms: 1.01x slower                                              |
| pathlib                  | 18.7 ms                                                               | 18.9 ms: 1.01x slower                                             |
| async_tree_cpu_io_mixed  | 700 ms                                                                | 708 ms: 1.01x slower                                              |
| sqlglot_optimize         | 52.9 ms                                                               | 53.6 ms: 1.01x slower                                             |
| create_gc_cycles         | 1.49 ms                                                               | 1.51 ms: 1.01x slower                                             |
| asyncio_tcp              | 485 ms                                                                | 492 ms: 1.01x slower                                              |
| pickle                   | 10.6 us                                                               | 10.8 us: 1.01x slower                                             |
| spectral_norm            | 107 ms                                                                | 109 ms: 1.01x slower                                              |
| json_dumps               | 9.75 ms                                                               | 9.90 ms: 1.02x slower                                             |
| sqlglot_parse            | 1.26 ms                                                               | 1.29 ms: 1.02x slower                                             |
| sqlite_synth             | 2.72 us                                                               | 2.77 us: 1.02x slower                                             |
| dask                     | 524 ms                                                                | 534 ms: 1.02x slower                                              |
| xml_etree_parse          | 151 ms                                                                | 153 ms: 1.02x slower                                              |
| xml_etree_iterparse      | 102 ms                                                                | 104 ms: 1.02x slower                                              |
| sqlglot_transpile        | 1.57 ms                                                               | 1.60 ms: 1.02x slower                                             |
| pprint_safe_repr         | 734 ms                                                                | 749 ms: 1.02x slower                                              |
| crypto_pyaes             | 70.9 ms                                                               | 72.4 ms: 1.02x slower                                             |
| pprint_pformat           | 1.50 sec                                                              | 1.53 sec: 1.02x slower                                            |
| logging_simple           | 5.97 us                                                               | 6.10 us: 1.02x slower                                             |
| scimark_sor              | 121 ms                                                                | 123 ms: 1.02x slower                                              |
| xml_etree_generate       | 81.5 ms                                                               | 83.3 ms: 1.02x slower                                             |
| pickle_pure_python       | 296 us                                                                | 303 us: 1.03x slower                                              |
| tornado_http             | 95.3 ms                                                               | 97.8 ms: 1.03x slower                                             |
| coroutines               | 22.1 ms                                                               | 22.7 ms: 1.03x slower                                             |
| async_tree_io            | 1.18 sec                                                              | 1.21 sec: 1.03x slower                                            |
| deepcopy                 | 350 us                                                                | 360 us: 1.03x slower                                              |
| raytrace                 | 273 ms                                                                | 281 ms: 1.03x slower                                              |
| dulwich_log              | 66.3 ms                                                               | 68.4 ms: 1.03x slower                                             |
| async_tree_none          | 433 ms                                                                | 447 ms: 1.03x slower                                              |
| async_tree_memoization   | 561 ms                                                                | 580 ms: 1.03x slower                                              |
| docutils                 | 2.62 sec                                                              | 2.72 sec: 1.04x slower                                            |
| mypy2                    | 338 ms                                                                | 350 ms: 1.04x slower                                              |
| regex_dna                | 212 ms                                                                | 220 ms: 1.04x slower                                              |
| bench_thread_pool        | 814 us                                                                | 847 us: 1.04x slower                                              |
| gc_traversal             | 3.68 ms                                                               | 3.83 ms: 1.04x slower                                             |
| deepcopy_reduce          | 3.12 us                                                               | 3.25 us: 1.04x slower                                             |
| richards_super           | 53.1 ms                                                               | 55.4 ms: 1.04x slower                                             |
| scimark_monte_carlo      | 65.7 ms                                                               | 68.7 ms: 1.05x slower                                             |
| async_generators         | 440 ms                                                                | 461 ms: 1.05x slower                                              |
| logging_format           | 6.50 us                                                               | 6.82 us: 1.05x slower                                             |
| telco                    | 7.86 ms                                                               | 8.25 ms: 1.05x slower                                             |
| coverage                 | 85.0 ms                                                               | 89.2 ms: 1.05x slower                                             |
| json                     | 4.89 ms                                                               | 5.15 ms: 1.05x slower                                             |
| regex_effbot             | 3.61 ms                                                               | 3.82 ms: 1.06x slower                                             |
| pycparser                | 1.17 sec                                                              | 1.24 sec: 1.06x slower                                            |
| deltablue                | 3.25 ms                                                               | 3.49 ms: 1.07x slower                                             |
| go                       | 138 ms                                                                | 149 ms: 1.08x slower                                              |
| scimark_lu               | 109 ms                                                                | 118 ms: 1.08x slower                                              |
| float                    | 78.4 ms                                                               | 84.9 ms: 1.08x slower                                             |
| richards                 | 46.2 ms                                                               | 50.0 ms: 1.08x slower                                             |
| meteor_contest           | 107 ms                                                                | 115 ms: 1.08x slower                                              |
| pyflate                  | 452 ms                                                                | 491 ms: 1.09x slower                                              |
| scimark_fft              | 357 ms                                                                | 388 ms: 1.09x slower                                              |
| typing_runtime_protocols | 139 us                                                                | 153 us: 1.10x slower                                              |
| mako                     | 10.8 ms                                                               | 11.9 ms: 1.10x slower                                             |
| mdp                      | 2.57 sec                                                              | 2.84 sec: 1.10x slower                                            |
| deepcopy_memo            | 37.2 us                                                               | 41.4 us: 1.11x slower                                             |
| unpickle_pure_python     | 212 us                                                                | 238 us: 1.12x slower                                              |
| regex_compile            | 135 ms                                                                | 152 ms: 1.13x slower                                              |
| chaos                    | 60.2 ms                                                               | 68.4 ms: 1.13x slower                                             |
| fannkuch                 | 390 ms                                                                | 444 ms: 1.14x slower                                              |
| nbody                    | 91.7 ms                                                               | 106 ms: 1.15x slower                                              |
| tomli_loads              | 2.06 sec                                                              | 2.39 sec: 1.16x slower                                            |
| nqueens                  | 79.4 ms                                                               | 96.7 ms: 1.22x slower                                             |
| comprehensions           | 20.6 us                                                               | 25.2 us: 1.22x slower                                             |
| scimark_sparse_mat_mult  | 4.62 ms                                                               | 5.89 ms: 1.27x slower                                             |
| hexiom                   | 6.03 ms                                                               | 7.68 ms: 1.27x slower                                             |
| Geometric mean           | (ref)                                                                 | 1.05x slower                                                      |

Benchmark hidden because not significant (5): regex_v8, bench_mp_pool, asyncio_tcp_ssl, json_loads, unpickle_list


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
