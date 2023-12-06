
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 7389ee1
- commit date: 2023-09-17
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.68 sec: 1.03x slower                                                  |
| tornado_http   | 95.0 ms                                                               | 97.0 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 187 ms: 1.00x slower                                                    |
| float          | 78.7 ms                                                               | 82.8 ms: 1.05x slower                                                   |
| nbody          | 87.9 ms                                                               | 93.3 ms: 1.06x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.63 ms                                                               | 3.46 ms: 1.05x faster                                                   |
| regex_dna      | 209 ms                                                                | 208 ms: 1.00x faster                                                    |
| regex_v8       | 23.0 ms                                                               | 23.7 ms: 1.03x slower                                                   |
| regex_compile  | 134 ms                                                                | 144 ms: 1.07x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle               | 10.8 us                                                               | 10.5 us: 1.03x faster                                                   |
| unpickle_list        | 4.90 us                                                               | 4.81 us: 1.02x faster                                                   |
| pickle_dict          | 32.4 us                                                               | 31.9 us: 1.02x faster                                                   |
| pickle_pure_python   | 297 us                                                                | 299 us: 1.00x slower                                                    |
| tomli_loads          | 2.04 sec                                                              | 2.05 sec: 1.01x slower                                                  |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                                    |
| json_dumps           | 9.81 ms                                                               | 9.94 ms: 1.01x slower                                                   |
| pickle_list          | 4.67 us                                                               | 4.77 us: 1.02x slower                                                   |
| unpickle             | 14.9 us                                                               | 15.3 us: 1.02x slower                                                   |
| unpickle_pure_python | 211 us                                                                | 226 us: 1.07x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                            |

Benchmark hidden because not significant (4): json_loads, xml_etree_process, xml_etree_parse, xml_etree_generate

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                               | 10.2 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.86 ms                                                               | 6.94 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 11.4 ms: 1.08x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-7389ee1 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| scimark_sor              | 130 ms                                                                | 121 ms: 1.07x faster                                                    |
| gc_traversal             | 4.11 ms                                                               | 3.86 ms: 1.07x faster                                                   |
| scimark_fft              | 352 ms                                                                | 333 ms: 1.06x faster                                                    |
| regex_effbot             | 3.63 ms                                                               | 3.46 ms: 1.05x faster                                                   |
| pickle                   | 10.8 us                                                               | 10.5 us: 1.03x faster                                                   |
| unpickle_list            | 4.90 us                                                               | 4.81 us: 1.02x faster                                                   |
| pickle_dict              | 32.4 us                                                               | 31.9 us: 1.02x faster                                                   |
| logging_format           | 6.80 us                                                               | 6.68 us: 1.02x faster                                                   |
| regex_dna                | 209 ms                                                                | 208 ms: 1.00x faster                                                    |
| pidigits                 | 187 ms                                                                | 187 ms: 1.00x slower                                                    |
| pickle_pure_python       | 297 us                                                                | 299 us: 1.00x slower                                                    |
| create_gc_cycles         | 1.52 ms                                                               | 1.53 ms: 1.01x slower                                                   |
| tomli_loads              | 2.04 sec                                                              | 2.05 sec: 1.01x slower                                                  |
| pyflate                  | 454 ms                                                                | 457 ms: 1.01x slower                                                    |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.01x slower                                                  |
| python_startup           | 10.1 ms                                                               | 10.2 ms: 1.01x slower                                                   |
| raytrace                 | 268 ms                                                                | 271 ms: 1.01x slower                                                    |
| python_startup_no_site   | 6.86 ms                                                               | 6.94 ms: 1.01x slower                                                   |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                                    |
| deepcopy_reduce          | 3.12 us                                                               | 3.16 us: 1.01x slower                                                   |
| dask                     | 529 ms                                                                | 536 ms: 1.01x slower                                                    |
| json_dumps               | 9.81 ms                                                               | 9.94 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed  | 708 ms                                                                | 717 ms: 1.01x slower                                                    |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.01x slower                                                  |
| pycparser                | 1.18 sec                                                              | 1.20 sec: 1.01x slower                                                  |
| sqlglot_parse            | 1.27 ms                                                               | 1.29 ms: 1.01x slower                                                   |
| scimark_sparse_mat_mult  | 4.56 ms                                                               | 4.63 ms: 1.01x slower                                                   |
| sqlglot_transpile        | 1.58 ms                                                               | 1.61 ms: 1.02x slower                                                   |
| sqlglot_normalize        | 104 ms                                                                | 106 ms: 1.02x slower                                                    |
| tornado_http             | 95.0 ms                                                               | 97.0 ms: 1.02x slower                                                   |
| sqlglot_optimize         | 52.5 ms                                                               | 53.6 ms: 1.02x slower                                                   |
| telco                    | 8.07 ms                                                               | 8.25 ms: 1.02x slower                                                   |
| pickle_list              | 4.67 us                                                               | 4.77 us: 1.02x slower                                                   |
| unpickle                 | 14.9 us                                                               | 15.3 us: 1.02x slower                                                   |
| async_tree_memoization   | 563 ms                                                                | 576 ms: 1.02x slower                                                    |
| deepcopy                 | 344 us                                                                | 353 us: 1.03x slower                                                    |
| coverage                 | 84.9 ms                                                               | 87.1 ms: 1.03x slower                                                   |
| meteor_contest           | 105 ms                                                                | 108 ms: 1.03x slower                                                    |
| async_tree_none          | 438 ms                                                                | 450 ms: 1.03x slower                                                    |
| fannkuch                 | 389 ms                                                                | 400 ms: 1.03x slower                                                    |
| coroutines               | 21.8 ms                                                               | 22.4 ms: 1.03x slower                                                   |
| dulwich_log              | 66.8 ms                                                               | 68.7 ms: 1.03x slower                                                   |
| docutils                 | 2.60 sec                                                              | 2.68 sec: 1.03x slower                                                  |
| richards_super           | 53.8 ms                                                               | 55.4 ms: 1.03x slower                                                   |
| bench_thread_pool        | 809 us                                                                | 833 us: 1.03x slower                                                    |
| pathlib                  | 18.3 ms                                                               | 18.9 ms: 1.03x slower                                                   |
| scimark_lu               | 110 ms                                                                | 114 ms: 1.03x slower                                                    |
| regex_v8                 | 23.0 ms                                                               | 23.7 ms: 1.03x slower                                                   |
| async_generators         | 447 ms                                                                | 462 ms: 1.03x slower                                                    |
| spectral_norm            | 106 ms                                                                | 110 ms: 1.03x slower                                                    |
| deltablue                | 3.28 ms                                                               | 3.40 ms: 1.04x slower                                                   |
| pprint_safe_repr         | 727 ms                                                                | 755 ms: 1.04x slower                                                    |
| crypto_pyaes             | 69.2 ms                                                               | 72.1 ms: 1.04x slower                                                   |
| mypy2                    | 336 ms                                                                | 351 ms: 1.04x slower                                                    |
| pprint_pformat           | 1.47 sec                                                              | 1.54 sec: 1.05x slower                                                  |
| go                       | 140 ms                                                                | 147 ms: 1.05x slower                                                    |
| asyncio_tcp              | 480 ms                                                                | 505 ms: 1.05x slower                                                    |
| float                    | 78.7 ms                                                               | 82.8 ms: 1.05x slower                                                   |
| mdp                      | 2.63 sec                                                              | 2.77 sec: 1.05x slower                                                  |
| logging_silent           | 100 ns                                                                | 106 ns: 1.06x slower                                                    |
| nbody                    | 87.9 ms                                                               | 93.3 ms: 1.06x slower                                                   |
| unpack_sequence          | 48.2 ns                                                               | 51.5 ns: 1.07x slower                                                   |
| regex_compile            | 134 ms                                                                | 144 ms: 1.07x slower                                                    |
| unpickle_pure_python     | 211 us                                                                | 226 us: 1.07x slower                                                    |
| typing_runtime_protocols | 142 us                                                                | 152 us: 1.08x slower                                                    |
| chaos                    | 59.3 ms                                                               | 64.2 ms: 1.08x slower                                                   |
| mako                     | 10.5 ms                                                               | 11.4 ms: 1.08x slower                                                   |
| deepcopy_memo            | 36.1 us                                                               | 39.4 us: 1.09x slower                                                   |
| nqueens                  | 78.8 ms                                                               | 88.8 ms: 1.13x slower                                                   |
| comprehensions           | 20.4 us                                                               | 23.8 us: 1.16x slower                                                   |
| hexiom                   | 5.86 ms                                                               | 6.96 ms: 1.19x slower                                                   |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                            |

Benchmark hidden because not significant (11): scimark_monte_carlo, sqlite_synth, generators, json_loads, xml_etree_process, bench_mp_pool, richards, xml_etree_parse, logging_simple, xml_etree_generate, json


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
