
# Results vs. base

- fork: brandtbucher
- ref: justin_no_stubs
- machine: linux-x86_64
- commit hash: 925f140
- commit date: 2023-11-20
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 264 ms                                                                 | 274 ms: 1.04x slower                                                    |
| chameleon      | 6.90 ms                                                                | 7.15 ms: 1.04x slower                                                   |
| docutils       | 2.60 sec                                                               | 2.66 sec: 1.02x slower                                                  |
| tornado_http   | 95.2 ms                                                                | 96.5 ms: 1.01x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_io_tg   | 1.23 sec                                                               | 1.22 sec: 1.00x faster                                                  |
| async_tree_none_tg | 457 ms                                                                 | 461 ms: 1.01x slower                                                    |
| Geometric mean     | (ref)                                                                  | 1.01x slower                                                            |

Benchmark hidden because not significant (6): async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 195 ms: 1.00x slower                                                    |
| float          | 81.3 ms                                                                | 84.9 ms: 1.04x slower                                                   |
| nbody          | 90.0 ms                                                                | 98.9 ms: 1.10x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.05x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_v8       | 25.5 ms                                                                | 24.0 ms: 1.06x faster                                                   |
| regex_effbot   | 3.66 ms                                                                | 3.58 ms: 1.02x faster                                                   |
| regex_dna      | 212 ms                                                                 | 221 ms: 1.04x slower                                                    |
| regex_compile  | 134 ms                                                                 | 144 ms: 1.07x slower                                                    |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|----------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| json_dumps           | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                                   |
| tomli_loads          | 2.13 sec                                                               | 2.16 sec: 1.01x slower                                                  |
| pickle               | 11.2 us                                                                | 11.5 us: 1.02x slower                                                   |
| xml_etree_process    | 59.6 ms                                                                | 61.1 ms: 1.03x slower                                                   |
| xml_etree_generate   | 86.7 ms                                                                | 89.1 ms: 1.03x slower                                                   |
| pickle_list          | 5.02 us                                                                | 5.18 us: 1.03x slower                                                   |
| pickle_pure_python   | 299 us                                                                 | 312 us: 1.05x slower                                                    |
| xml_etree_iterparse  | 105 ms                                                                 | 110 ms: 1.05x slower                                                    |
| pickle_dict          | 33.7 us                                                                | 35.7 us: 1.06x slower                                                   |
| unpickle             | 14.6 us                                                                | 15.4 us: 1.06x slower                                                   |
| unpickle_pure_python | 219 us                                                                 | 234 us: 1.07x slower                                                    |
| Geometric mean       | (ref)                                                                  | 1.03x slower                                                            |

Benchmark hidden because not significant (3): json_loads, unpickle_list, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                                   |
| python_startup_no_site | 9.04 ms                                                                | 9.07 ms: 1.00x slower                                                   |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|-----------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 11.1 ms                                                                | 12.3 ms: 1.10x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-brandtbucher-justin_no_stubs-3.13.0a1+-925f140 |
|--------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_v8                 | 25.5 ms                                                                | 24.0 ms: 1.06x faster                                                   |
| richards                 | 48.1 ms                                                                | 46.9 ms: 1.02x faster                                                   |
| regex_effbot             | 3.66 ms                                                                | 3.58 ms: 1.02x faster                                                   |
| richards_super           | 54.1 ms                                                                | 53.2 ms: 1.02x faster                                                   |
| create_gc_cycles         | 1.48 ms                                                                | 1.46 ms: 1.01x faster                                                   |
| async_tree_io_tg         | 1.23 sec                                                               | 1.22 sec: 1.00x faster                                                  |
| pidigits                 | 195 ms                                                                 | 195 ms: 1.00x slower                                                    |
| python_startup           | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                                   |
| python_startup_no_site   | 9.04 ms                                                                | 9.07 ms: 1.00x slower                                                   |
| asyncio_tcp              | 489 ms                                                                 | 491 ms: 1.00x slower                                                    |
| asyncio_tcp_ssl          | 1.79 sec                                                               | 1.81 sec: 1.01x slower                                                  |
| async_tree_none_tg       | 457 ms                                                                 | 461 ms: 1.01x slower                                                    |
| pathlib                  | 18.3 ms                                                                | 18.4 ms: 1.01x slower                                                   |
| deepcopy_reduce          | 3.07 us                                                                | 3.11 us: 1.01x slower                                                   |
| json_dumps               | 10.5 ms                                                                | 10.6 ms: 1.01x slower                                                   |
| coverage                 | 94.9 ms                                                                | 96.1 ms: 1.01x slower                                                   |
| dask                     | 360 ms                                                                 | 365 ms: 1.01x slower                                                    |
| tomli_loads              | 2.13 sec                                                               | 2.16 sec: 1.01x slower                                                  |
| tornado_http             | 95.2 ms                                                                | 96.5 ms: 1.01x slower                                                   |
| mdp                      | 2.58 sec                                                               | 2.62 sec: 1.01x slower                                                  |
| dulwich_log              | 65.7 ms                                                                | 66.7 ms: 1.02x slower                                                   |
| logging_simple           | 5.70 us                                                                | 5.82 us: 1.02x slower                                                   |
| pickle                   | 11.2 us                                                                | 11.5 us: 1.02x slower                                                   |
| logging_format           | 6.23 us                                                                | 6.38 us: 1.02x slower                                                   |
| docutils                 | 2.60 sec                                                               | 2.66 sec: 1.02x slower                                                  |
| pycparser                | 1.17 sec                                                               | 1.20 sec: 1.02x slower                                                  |
| sqlglot_normalize        | 106 ms                                                                 | 108 ms: 1.02x slower                                                    |
| xml_etree_process        | 59.6 ms                                                                | 61.1 ms: 1.03x slower                                                   |
| typing_runtime_protocols | 116 us                                                                 | 119 us: 1.03x slower                                                    |
| bench_thread_pool        | 832 us                                                                 | 854 us: 1.03x slower                                                    |
| logging_silent           | 107 ns                                                                 | 110 ns: 1.03x slower                                                    |
| xml_etree_generate       | 86.7 ms                                                                | 89.1 ms: 1.03x slower                                                   |
| generators               | 29.2 ms                                                                | 30.1 ms: 1.03x slower                                                   |
| pickle_list              | 5.02 us                                                                | 5.18 us: 1.03x slower                                                   |
| mypy2                    | 341 ms                                                                 | 352 ms: 1.03x slower                                                    |
| deepcopy                 | 345 us                                                                 | 355 us: 1.03x slower                                                    |
| scimark_fft              | 372 ms                                                                 | 384 ms: 1.03x slower                                                    |
| meteor_contest           | 108 ms                                                                 | 111 ms: 1.03x slower                                                    |
| 2to3                     | 264 ms                                                                 | 274 ms: 1.04x slower                                                    |
| chameleon                | 6.90 ms                                                                | 7.15 ms: 1.04x slower                                                   |
| sqlglot_parse            | 1.28 ms                                                                | 1.32 ms: 1.04x slower                                                   |
| sqlglot_optimize         | 53.4 ms                                                                | 55.5 ms: 1.04x slower                                                   |
| raytrace                 | 275 ms                                                                 | 286 ms: 1.04x slower                                                    |
| sqlglot_transpile        | 1.59 ms                                                                | 1.65 ms: 1.04x slower                                                   |
| async_generators         | 448 ms                                                                 | 465 ms: 1.04x slower                                                    |
| sympy_expand             | 451 ms                                                                 | 469 ms: 1.04x slower                                                    |
| regex_dna                | 212 ms                                                                 | 221 ms: 1.04x slower                                                    |
| float                    | 81.3 ms                                                                | 84.9 ms: 1.04x slower                                                   |
| pickle_pure_python       | 299 us                                                                 | 312 us: 1.05x slower                                                    |
| xml_etree_iterparse      | 105 ms                                                                 | 110 ms: 1.05x slower                                                    |
| coroutines               | 21.5 ms                                                                | 22.7 ms: 1.06x slower                                                   |
| sympy_sum                | 147 ms                                                                 | 156 ms: 1.06x slower                                                    |
| pickle_dict              | 33.7 us                                                                | 35.7 us: 1.06x slower                                                   |
| unpickle                 | 14.6 us                                                                | 15.4 us: 1.06x slower                                                   |
| scimark_sor              | 120 ms                                                                 | 127 ms: 1.06x slower                                                    |
| scimark_lu               | 113 ms                                                                 | 120 ms: 1.06x slower                                                    |
| sympy_str                | 266 ms                                                                 | 282 ms: 1.06x slower                                                    |
| pprint_safe_repr         | 731 ms                                                                 | 783 ms: 1.07x slower                                                    |
| unpickle_pure_python     | 219 us                                                                 | 234 us: 1.07x slower                                                    |
| regex_compile            | 134 ms                                                                 | 144 ms: 1.07x slower                                                    |
| crypto_pyaes             | 72.7 ms                                                                | 78.3 ms: 1.08x slower                                                   |
| sympy_integrate          | 19.4 ms                                                                | 20.9 ms: 1.08x slower                                                   |
| scimark_sparse_mat_mult  | 4.95 ms                                                                | 5.35 ms: 1.08x slower                                                   |
| pprint_pformat           | 1.48 sec                                                               | 1.60 sec: 1.08x slower                                                  |
| pyflate                  | 466 ms                                                                 | 503 ms: 1.08x slower                                                    |
| deepcopy_memo            | 37.3 us                                                                | 40.5 us: 1.08x slower                                                   |
| go                       | 139 ms                                                                 | 151 ms: 1.09x slower                                                    |
| nbody                    | 90.0 ms                                                                | 98.9 ms: 1.10x slower                                                   |
| fannkuch                 | 392 ms                                                                 | 431 ms: 1.10x slower                                                    |
| mako                     | 11.1 ms                                                                | 12.3 ms: 1.10x slower                                                   |
| scimark_monte_carlo      | 67.9 ms                                                                | 75.0 ms: 1.10x slower                                                   |
| chaos                    | 60.5 ms                                                                | 67.2 ms: 1.11x slower                                                   |
| gc_traversal             | 3.79 ms                                                                | 4.29 ms: 1.13x slower                                                   |
| nqueens                  | 79.2 ms                                                                | 92.0 ms: 1.16x slower                                                   |
| comprehensions           | 16.4 us                                                                | 19.4 us: 1.18x slower                                                   |
| unpack_sequence          | 41.7 ns                                                                | 49.2 ns: 1.18x slower                                                   |
| deltablue                | 3.32 ms                                                                | 4.08 ms: 1.23x slower                                                   |
| spectral_norm            | 110 ms                                                                 | 136 ms: 1.24x slower                                                    |
| hexiom                   | 6.09 ms                                                                | 7.65 ms: 1.26x slower                                                   |
| Geometric mean           | (ref)                                                                  | 1.04x slower                                                            |

Benchmark hidden because not significant (14): sqlite_synth, json_loads, async_tree_io, json, bench_mp_pool, unpickle_list, xml_etree_parse, asyncio_websockets, telco, async_tree_cpu_io_mixed_tg, async_tree_memoization, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization_tg


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
