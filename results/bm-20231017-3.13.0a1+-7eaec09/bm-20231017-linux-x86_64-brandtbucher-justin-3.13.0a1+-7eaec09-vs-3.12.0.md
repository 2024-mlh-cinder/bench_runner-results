
# Results vs. 3.12.0

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tornado_http   | 99.6 ms                                                | 98.0 ms: 1.02x faster                                          |
| Geometric mean | (ref)                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 80.7 ms                                                | 82.4 ms: 1.02x slower                                          |
| nbody          | 88.8 ms                                                | 91.9 ms: 1.03x slower                                          |
| pidigits       | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.51 ms: 1.01x faster                                          |
| regex_dna      | 209 ms                                                 | 215 ms: 1.03x slower                                           |
| regex_v8       | 22.3 ms                                                | 25.2 ms: 1.13x slower                                          |
| Geometric mean | (ref)                                                  | 1.03x slower                                                   |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 2.22 sec                                               | 2.06 sec: 1.07x faster                                         |
| unpickle             | 15.0 us                                                | 15.2 us: 1.02x slower                                          |
| xml_etree_generate   | 84.8 ms                                                | 88.3 ms: 1.04x slower                                          |
| xml_etree_process    | 58.6 ms                                                | 61.0 ms: 1.04x slower                                          |
| unpickle_list        | 4.95 us                                                | 5.17 us: 1.05x slower                                          |
| xml_etree_parse      | 154 ms                                                 | 161 ms: 1.05x slower                                           |
| xml_etree_iterparse  | 104 ms                                                 | 109 ms: 1.05x slower                                           |
| pickle               | 10.6 us                                                | 11.3 us: 1.07x slower                                          |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.07x slower                                          |
| pickle_dict          | 31.6 us                                                | 34.0 us: 1.08x slower                                          |
| unpickle_pure_python | 218 us                                                 | 235 us: 1.08x slower                                           |
| pickle_list          | 4.62 us                                                | 5.00 us: 1.08x slower                                          |
| json_loads           | 25.2 us                                                | 28.0 us: 1.11x slower                                          |
| Geometric mean       | (ref)                                                  | 1.05x slower                                                   |

Benchmark hidden because not significant (1): pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.94 ms: 1.01x slower                                          |
| python_startup         | 9.47 ms                                                | 10.2 ms: 1.07x slower                                          |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.5 ms: 1.08x slower                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231017-linux-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads              | 2.22 sec                                               | 2.06 sec: 1.07x faster                                         |
| asyncio_tcp              | 526 ms                                                 | 492 ms: 1.07x faster                                           |
| async_tree_none          | 469 ms                                                 | 444 ms: 1.06x faster                                           |
| coverage                 | 94.2 ms                                                | 89.9 ms: 1.05x faster                                          |
| crypto_pyaes             | 77.2 ms                                                | 74.2 ms: 1.04x faster                                          |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.04x faster                                          |
| tornado_http             | 99.6 ms                                                | 98.0 ms: 1.02x faster                                          |
| logging_simple           | 6.18 us                                                | 6.10 us: 1.01x faster                                          |
| regex_effbot             | 3.55 ms                                                | 3.51 ms: 1.01x faster                                          |
| sqlglot_parse            | 1.32 ms                                                | 1.31 ms: 1.01x faster                                          |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.79 sec: 1.00x faster                                         |
| python_startup_no_site   | 6.90 ms                                                | 6.94 ms: 1.01x slower                                          |
| deepcopy_reduce          | 3.14 us                                                | 3.16 us: 1.01x slower                                          |
| dulwich_log              | 67.9 ms                                                | 68.3 ms: 1.01x slower                                          |
| generators               | 31.1 ms                                                | 31.4 ms: 1.01x slower                                          |
| sqlglot_normalize        | 107 ms                                                 | 109 ms: 1.01x slower                                           |
| unpickle                 | 15.0 us                                                | 15.2 us: 1.02x slower                                          |
| deepcopy                 | 355 us                                                 | 362 us: 1.02x slower                                           |
| mdp                      | 2.57 sec                                               | 2.61 sec: 1.02x slower                                         |
| scimark_fft              | 358 ms                                                 | 365 ms: 1.02x slower                                           |
| float                    | 80.7 ms                                                | 82.4 ms: 1.02x slower                                          |
| bench_thread_pool        | 827 us                                                 | 844 us: 1.02x slower                                           |
| sqlite_synth             | 2.76 us                                                | 2.82 us: 1.02x slower                                          |
| coroutines               | 22.4 ms                                                | 23.0 ms: 1.02x slower                                          |
| chaos                    | 63.5 ms                                                | 65.0 ms: 1.02x slower                                          |
| pycparser                | 1.15 sec                                               | 1.18 sec: 1.02x slower                                         |
| sqlglot_optimize         | 53.3 ms                                                | 54.7 ms: 1.03x slower                                          |
| gc_traversal             | 3.84 ms                                                | 3.95 ms: 1.03x slower                                          |
| async_tree_io            | 1.16 sec                                               | 1.19 sec: 1.03x slower                                         |
| regex_dna                | 209 ms                                                 | 215 ms: 1.03x slower                                           |
| scimark_monte_carlo      | 71.0 ms                                                | 73.4 ms: 1.03x slower                                          |
| nbody                    | 88.8 ms                                                | 91.9 ms: 1.03x slower                                          |
| mypy2                    | 344 ms                                                 | 356 ms: 1.04x slower                                           |
| pathlib                  | 18.5 ms                                                | 19.2 ms: 1.04x slower                                          |
| xml_etree_generate       | 84.8 ms                                                | 88.3 ms: 1.04x slower                                          |
| xml_etree_process        | 58.6 ms                                                | 61.0 ms: 1.04x slower                                          |
| pidigits                 | 187 ms                                                 | 195 ms: 1.04x slower                                           |
| unpickle_list            | 4.95 us                                                | 5.17 us: 1.05x slower                                          |
| xml_etree_parse          | 154 ms                                                 | 161 ms: 1.05x slower                                           |
| xml_etree_iterparse      | 104 ms                                                 | 109 ms: 1.05x slower                                           |
| scimark_sor              | 125 ms                                                 | 131 ms: 1.05x slower                                           |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.00 ms: 1.05x slower                                          |
| meteor_contest           | 105 ms                                                 | 111 ms: 1.06x slower                                           |
| fannkuch                 | 387 ms                                                 | 412 ms: 1.06x slower                                           |
| scimark_lu               | 114 ms                                                 | 122 ms: 1.07x slower                                           |
| pickle                   | 10.6 us                                                | 11.3 us: 1.07x slower                                          |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.07x slower                                          |
| python_startup           | 9.47 ms                                                | 10.2 ms: 1.07x slower                                          |
| pickle_dict              | 31.6 us                                                | 34.0 us: 1.08x slower                                          |
| mako                     | 10.7 ms                                                | 11.5 ms: 1.08x slower                                          |
| unpickle_pure_python     | 218 us                                                 | 235 us: 1.08x slower                                           |
| pprint_pformat           | 1.50 sec                                               | 1.62 sec: 1.08x slower                                         |
| nqueens                  | 81.1 ms                                                | 87.6 ms: 1.08x slower                                          |
| pickle_list              | 4.62 us                                                | 5.00 us: 1.08x slower                                          |
| json                     | 4.77 ms                                                | 5.18 ms: 1.09x slower                                          |
| pprint_safe_repr         | 735 ms                                                 | 801 ms: 1.09x slower                                           |
| async_generators         | 440 ms                                                 | 482 ms: 1.09x slower                                           |
| deltablue                | 3.52 ms                                                | 3.86 ms: 1.10x slower                                          |
| spectral_norm            | 106 ms                                                 | 117 ms: 1.10x slower                                           |
| richards_super           | 49.0 ms                                                | 53.9 ms: 1.10x slower                                          |
| richards                 | 43.2 ms                                                | 47.6 ms: 1.10x slower                                          |
| pyflate                  | 450 ms                                                 | 497 ms: 1.10x slower                                           |
| typing_runtime_protocols | 146 us                                                 | 161 us: 1.11x slower                                           |
| json_loads               | 25.2 us                                                | 28.0 us: 1.11x slower                                          |
| go                       | 136 ms                                                 | 151 ms: 1.11x slower                                           |
| comprehensions           | 20.4 us                                                | 22.9 us: 1.12x slower                                          |
| regex_v8                 | 22.3 ms                                                | 25.2 ms: 1.13x slower                                          |
| logging_silent           | 99.1 ns                                                | 112 ns: 1.13x slower                                           |
| deepcopy_memo            | 37.4 us                                                | 42.5 us: 1.14x slower                                          |
| hexiom                   | 6.12 ms                                                | 7.09 ms: 1.16x slower                                          |
| telco                    | 6.87 ms                                                | 8.56 ms: 1.25x slower                                          |
| unpack_sequence          | 44.8 ns                                                | 58.0 ns: 1.29x slower                                          |
| Geometric mean           | (ref)                                                  | 1.04x slower                                                   |

Benchmark hidden because not significant (9): logging_format, regex_compile, raytrace, async_tree_memoization, sqlglot_transpile, bench_mp_pool, docutils, pickle_pure_python, async_tree_cpu_io_mixed
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, dask, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
