
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 0441b8d
- commit date: 2023-09-15
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.70 sec: 1.04x slower                                                  |
| tornado_http   | 95.0 ms                                                               | 97.9 ms: 1.03x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 189 ms: 1.01x slower                                                    |
| float          | 78.7 ms                                                               | 83.6 ms: 1.06x slower                                                   |
| nbody          | 87.9 ms                                                               | 122 ms: 1.39x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.14x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_effbot   | 3.63 ms                                                               | 3.58 ms: 1.02x faster                                                   |
| regex_dna      | 209 ms                                                                | 213 ms: 1.02x slower                                                    |
| regex_v8       | 23.0 ms                                                               | 24.1 ms: 1.05x slower                                                   |
| regex_compile  | 134 ms                                                                | 148 ms: 1.10x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.04x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle               | 10.8 us                                                               | 10.5 us: 1.03x faster                                                   |
| unpickle             | 14.9 us                                                               | 14.7 us: 1.02x faster                                                   |
| pickle_list          | 4.67 us                                                               | 4.59 us: 1.02x faster                                                   |
| pickle_dict          | 32.4 us                                                               | 31.9 us: 1.02x faster                                                   |
| pickle_pure_python   | 297 us                                                                | 301 us: 1.01x slower                                                    |
| xml_etree_generate   | 83.9 ms                                                               | 84.8 ms: 1.01x slower                                                   |
| xml_etree_iterparse  | 102 ms                                                                | 104 ms: 1.01x slower                                                    |
| unpickle_list        | 4.90 us                                                               | 5.01 us: 1.02x slower                                                   |
| tomli_loads          | 2.04 sec                                                              | 2.16 sec: 1.06x slower                                                  |
| unpickle_pure_python | 211 us                                                                | 236 us: 1.12x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.01x slower                                                            |

Benchmark hidden because not significant (4): json_loads, xml_etree_process, xml_etree_parse, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.86 ms                                                               | 6.92 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 11.7 ms: 1.11x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| gc_traversal             | 4.11 ms                                                               | 3.86 ms: 1.07x faster                                                   |
| scimark_sor              | 130 ms                                                                | 123 ms: 1.05x faster                                                    |
| pickle                   | 10.8 us                                                               | 10.5 us: 1.03x faster                                                   |
| unpickle                 | 14.9 us                                                               | 14.7 us: 1.02x faster                                                   |
| pickle_list              | 4.67 us                                                               | 4.59 us: 1.02x faster                                                   |
| pickle_dict              | 32.4 us                                                               | 31.9 us: 1.02x faster                                                   |
| regex_effbot             | 3.63 ms                                                               | 3.58 ms: 1.02x faster                                                   |
| logging_format           | 6.80 us                                                               | 6.75 us: 1.01x faster                                                   |
| generators               | 28.3 ms                                                               | 28.2 ms: 1.01x faster                                                   |
| create_gc_cycles         | 1.52 ms                                                               | 1.52 ms: 1.00x slower                                                   |
| python_startup           | 10.1 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.80 sec: 1.01x slower                                                  |
| coroutines               | 21.8 ms                                                               | 22.0 ms: 1.01x slower                                                   |
| logging_simple           | 6.05 us                                                               | 6.09 us: 1.01x slower                                                   |
| python_startup_no_site   | 6.86 ms                                                               | 6.92 ms: 1.01x slower                                                   |
| telco                    | 8.07 ms                                                               | 8.15 ms: 1.01x slower                                                   |
| pprint_safe_repr         | 727 ms                                                                | 734 ms: 1.01x slower                                                    |
| pickle_pure_python       | 297 us                                                                | 301 us: 1.01x slower                                                    |
| xml_etree_generate       | 83.9 ms                                                               | 84.8 ms: 1.01x slower                                                   |
| async_tree_cpu_io_mixed  | 708 ms                                                                | 716 ms: 1.01x slower                                                    |
| dask                     | 529 ms                                                                | 536 ms: 1.01x slower                                                    |
| pidigits                 | 187 ms                                                                | 189 ms: 1.01x slower                                                    |
| xml_etree_iterparse      | 102 ms                                                                | 104 ms: 1.01x slower                                                    |
| sqlite_synth             | 2.76 us                                                               | 2.80 us: 1.02x slower                                                   |
| asyncio_tcp              | 480 ms                                                                | 488 ms: 1.02x slower                                                    |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.02x slower                                                  |
| regex_dna                | 209 ms                                                                | 213 ms: 1.02x slower                                                    |
| pathlib                  | 18.3 ms                                                               | 18.7 ms: 1.02x slower                                                   |
| richards_super           | 53.8 ms                                                               | 54.8 ms: 1.02x slower                                                   |
| deepcopy_reduce          | 3.12 us                                                               | 3.18 us: 1.02x slower                                                   |
| logging_silent           | 100 ns                                                                | 102 ns: 1.02x slower                                                    |
| json                     | 4.81 ms                                                               | 4.92 ms: 1.02x slower                                                   |
| unpickle_list            | 4.90 us                                                               | 5.01 us: 1.02x slower                                                   |
| sqlglot_transpile        | 1.58 ms                                                               | 1.62 ms: 1.02x slower                                                   |
| sqlglot_parse            | 1.27 ms                                                               | 1.30 ms: 1.03x slower                                                   |
| sqlglot_optimize         | 52.5 ms                                                               | 53.9 ms: 1.03x slower                                                   |
| async_tree_memoization   | 563 ms                                                                | 578 ms: 1.03x slower                                                    |
| raytrace                 | 268 ms                                                                | 276 ms: 1.03x slower                                                    |
| unpack_sequence          | 48.2 ns                                                               | 49.6 ns: 1.03x slower                                                   |
| pprint_pformat           | 1.47 sec                                                              | 1.51 sec: 1.03x slower                                                  |
| coverage                 | 84.9 ms                                                               | 87.3 ms: 1.03x slower                                                   |
| async_tree_none          | 438 ms                                                                | 451 ms: 1.03x slower                                                    |
| bench_thread_pool        | 809 us                                                                | 833 us: 1.03x slower                                                    |
| tornado_http             | 95.0 ms                                                               | 97.9 ms: 1.03x slower                                                   |
| sqlglot_normalize        | 104 ms                                                                | 107 ms: 1.03x slower                                                    |
| deepcopy                 | 344 us                                                                | 355 us: 1.03x slower                                                    |
| scimark_lu               | 110 ms                                                                | 114 ms: 1.03x slower                                                    |
| docutils                 | 2.60 sec                                                              | 2.70 sec: 1.04x slower                                                  |
| dulwich_log              | 66.8 ms                                                               | 69.5 ms: 1.04x slower                                                   |
| async_generators         | 447 ms                                                                | 465 ms: 1.04x slower                                                    |
| spectral_norm            | 106 ms                                                                | 111 ms: 1.04x slower                                                    |
| pyflate                  | 454 ms                                                                | 475 ms: 1.05x slower                                                    |
| regex_v8                 | 23.0 ms                                                               | 24.1 ms: 1.05x slower                                                   |
| deltablue                | 3.28 ms                                                               | 3.46 ms: 1.05x slower                                                   |
| mypy2                    | 336 ms                                                                | 355 ms: 1.06x slower                                                    |
| meteor_contest           | 105 ms                                                                | 111 ms: 1.06x slower                                                    |
| mdp                      | 2.63 sec                                                              | 2.79 sec: 1.06x slower                                                  |
| tomli_loads              | 2.04 sec                                                              | 2.16 sec: 1.06x slower                                                  |
| float                    | 78.7 ms                                                               | 83.6 ms: 1.06x slower                                                   |
| go                       | 140 ms                                                                | 149 ms: 1.07x slower                                                    |
| crypto_pyaes             | 69.2 ms                                                               | 74.3 ms: 1.07x slower                                                   |
| scimark_fft              | 352 ms                                                                | 381 ms: 1.08x slower                                                    |
| fannkuch                 | 389 ms                                                                | 427 ms: 1.10x slower                                                    |
| typing_runtime_protocols | 142 us                                                                | 156 us: 1.10x slower                                                    |
| regex_compile            | 134 ms                                                                | 148 ms: 1.10x slower                                                    |
| deepcopy_memo            | 36.1 us                                                               | 39.9 us: 1.10x slower                                                   |
| mako                     | 10.5 ms                                                               | 11.7 ms: 1.11x slower                                                   |
| unpickle_pure_python     | 211 us                                                                | 236 us: 1.12x slower                                                    |
| scimark_sparse_mat_mult  | 4.56 ms                                                               | 5.16 ms: 1.13x slower                                                   |
| chaos                    | 59.3 ms                                                               | 72.0 ms: 1.21x slower                                                   |
| comprehensions           | 20.4 us                                                               | 24.9 us: 1.22x slower                                                   |
| nqueens                  | 78.8 ms                                                               | 98.4 ms: 1.25x slower                                                   |
| hexiom                   | 5.86 ms                                                               | 7.34 ms: 1.25x slower                                                   |
| nbody                    | 87.9 ms                                                               | 122 ms: 1.39x slower                                                    |
| Geometric mean           | (ref)                                                                 | 1.04x slower                                                            |

Benchmark hidden because not significant (8): scimark_monte_carlo, json_loads, pycparser, xml_etree_process, bench_mp_pool, xml_etree_parse, json_dumps, richards


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
