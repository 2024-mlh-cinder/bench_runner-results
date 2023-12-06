
# Results vs. base

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 2b170f6
- commit date: 2023-09-13
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 2.62 sec                                                              | 2.69 sec: 1.03x slower                                                  |
| tornado_http   | 95.5 ms                                                               | 97.4 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 189 ms: 1.01x slower                                                    |
| float          | 79.9 ms                                                               | 84.3 ms: 1.06x slower                                                   |
| nbody          | 89.2 ms                                                               | 127 ms: 1.42x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.15x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_v8       | 23.7 ms                                                               | 24.1 ms: 1.02x slower                                                   |
| regex_dna      | 205 ms                                                                | 209 ms: 1.02x slower                                                    |
| regex_effbot   | 3.39 ms                                                               | 3.57 ms: 1.05x slower                                                   |
| regex_compile  | 133 ms                                                                | 148 ms: 1.11x slower                                                    |
| Geometric mean | (ref)                                                                 | 1.05x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|----------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpickle_list        | 5.05 us                                                               | 4.94 us: 1.02x faster                                                   |
| pickle_dict          | 31.9 us                                                               | 31.7 us: 1.01x faster                                                   |
| xml_etree_parse      | 151 ms                                                                | 152 ms: 1.01x slower                                                    |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                                    |
| pickle_list          | 4.63 us                                                               | 4.67 us: 1.01x slower                                                   |
| xml_etree_process    | 57.1 ms                                                               | 57.8 ms: 1.01x slower                                                   |
| xml_etree_generate   | 82.3 ms                                                               | 83.7 ms: 1.02x slower                                                   |
| pickle               | 10.5 us                                                               | 10.8 us: 1.03x slower                                                   |
| unpickle             | 14.5 us                                                               | 15.5 us: 1.07x slower                                                   |
| tomli_loads          | 2.02 sec                                                              | 2.18 sec: 1.08x slower                                                  |
| unpickle_pure_python | 214 us                                                                | 234 us: 1.10x slower                                                    |
| Geometric mean       | (ref)                                                                 | 1.02x slower                                                            |

Benchmark hidden because not significant (3): json_loads, pickle_pure_python, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| python_startup_no_site | 6.81 ms                                                               | 6.89 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|-----------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 10.7 ms                                                               | 11.7 ms: 1.10x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 | bm-20230913-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-2b170f6 |
|--------------------------|:---------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| gc_traversal             | 3.98 ms                                                               | 3.69 ms: 1.08x faster                                                   |
| generators               | 28.6 ms                                                               | 27.8 ms: 1.03x faster                                                   |
| mdp                      | 2.69 sec                                                              | 2.63 sec: 1.02x faster                                                  |
| unpickle_list            | 5.05 us                                                               | 4.94 us: 1.02x faster                                                   |
| create_gc_cycles         | 1.53 ms                                                               | 1.50 ms: 1.02x faster                                                   |
| pickle_dict              | 31.9 us                                                               | 31.7 us: 1.01x faster                                                   |
| asyncio_tcp_ssl          | 1.79 sec                                                              | 1.79 sec: 1.00x slower                                                  |
| xml_etree_parse          | 151 ms                                                                | 152 ms: 1.01x slower                                                    |
| pprint_safe_repr         | 736 ms                                                                | 741 ms: 1.01x slower                                                    |
| asyncio_tcp              | 486 ms                                                                | 490 ms: 1.01x slower                                                    |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                                    |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                   |
| pickle_list              | 4.63 us                                                               | 4.67 us: 1.01x slower                                                   |
| deepcopy_reduce          | 3.18 us                                                               | 3.22 us: 1.01x slower                                                   |
| telco                    | 8.04 ms                                                               | 8.13 ms: 1.01x slower                                                   |
| python_startup_no_site   | 6.81 ms                                                               | 6.89 ms: 1.01x slower                                                   |
| pidigits                 | 187 ms                                                                | 189 ms: 1.01x slower                                                    |
| async_tree_cpu_io_mixed  | 705 ms                                                                | 713 ms: 1.01x slower                                                    |
| xml_etree_process        | 57.1 ms                                                               | 57.8 ms: 1.01x slower                                                   |
| async_tree_memoization   | 564 ms                                                                | 572 ms: 1.01x slower                                                    |
| json                     | 4.74 ms                                                               | 4.82 ms: 1.02x slower                                                   |
| regex_v8                 | 23.7 ms                                                               | 24.1 ms: 1.02x slower                                                   |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.02x slower                                                  |
| xml_etree_generate       | 82.3 ms                                                               | 83.7 ms: 1.02x slower                                                   |
| tornado_http             | 95.5 ms                                                               | 97.4 ms: 1.02x slower                                                   |
| regex_dna                | 205 ms                                                                | 209 ms: 1.02x slower                                                    |
| dask                     | 522 ms                                                                | 535 ms: 1.03x slower                                                    |
| docutils                 | 2.62 sec                                                              | 2.69 sec: 1.03x slower                                                  |
| sqlglot_optimize         | 52.3 ms                                                               | 53.8 ms: 1.03x slower                                                   |
| coroutines               | 21.5 ms                                                               | 22.1 ms: 1.03x slower                                                   |
| pickle                   | 10.5 us                                                               | 10.8 us: 1.03x slower                                                   |
| async_tree_none          | 437 ms                                                                | 450 ms: 1.03x slower                                                    |
| raytrace                 | 268 ms                                                                | 277 ms: 1.03x slower                                                    |
| richards                 | 47.0 ms                                                               | 48.4 ms: 1.03x slower                                                   |
| sqlglot_normalize        | 104 ms                                                                | 107 ms: 1.03x slower                                                    |
| bench_thread_pool        | 809 us                                                                | 838 us: 1.04x slower                                                    |
| sqlglot_parse            | 1.26 ms                                                               | 1.31 ms: 1.04x slower                                                   |
| deepcopy                 | 349 us                                                                | 362 us: 1.04x slower                                                    |
| sqlglot_transpile        | 1.57 ms                                                               | 1.63 ms: 1.04x slower                                                   |
| dulwich_log              | 66.5 ms                                                               | 69.0 ms: 1.04x slower                                                   |
| logging_simple           | 5.80 us                                                               | 6.03 us: 1.04x slower                                                   |
| pathlib                  | 18.3 ms                                                               | 19.0 ms: 1.04x slower                                                   |
| logging_format           | 6.45 us                                                               | 6.71 us: 1.04x slower                                                   |
| scimark_lu               | 109 ms                                                                | 113 ms: 1.04x slower                                                    |
| richards_super           | 53.1 ms                                                               | 55.4 ms: 1.04x slower                                                   |
| scimark_monte_carlo      | 64.6 ms                                                               | 67.5 ms: 1.05x slower                                                   |
| scimark_sor              | 119 ms                                                                | 124 ms: 1.05x slower                                                    |
| meteor_contest           | 105 ms                                                                | 111 ms: 1.05x slower                                                    |
| async_generators         | 447 ms                                                                | 470 ms: 1.05x slower                                                    |
| regex_effbot             | 3.39 ms                                                               | 3.57 ms: 1.05x slower                                                   |
| float                    | 79.9 ms                                                               | 84.3 ms: 1.06x slower                                                   |
| logging_silent           | 98.9 ns                                                               | 105 ns: 1.06x slower                                                    |
| pycparser                | 1.14 sec                                                              | 1.21 sec: 1.06x slower                                                  |
| mypy2                    | 337 ms                                                                | 358 ms: 1.06x slower                                                    |
| unpickle                 | 14.5 us                                                               | 15.5 us: 1.07x slower                                                   |
| deltablue                | 3.25 ms                                                               | 3.48 ms: 1.07x slower                                                   |
| tomli_loads              | 2.02 sec                                                              | 2.18 sec: 1.08x slower                                                  |
| pyflate                  | 443 ms                                                                | 477 ms: 1.08x slower                                                    |
| spectral_norm            | 103 ms                                                                | 112 ms: 1.08x slower                                                    |
| crypto_pyaes             | 68.7 ms                                                               | 74.7 ms: 1.09x slower                                                   |
| typing_runtime_protocols | 142 us                                                                | 155 us: 1.09x slower                                                    |
| unpickle_pure_python     | 214 us                                                                | 234 us: 1.10x slower                                                    |
| go                       | 138 ms                                                                | 151 ms: 1.10x slower                                                    |
| mako                     | 10.7 ms                                                               | 11.7 ms: 1.10x slower                                                   |
| deepcopy_memo            | 36.4 us                                                               | 40.1 us: 1.10x slower                                                   |
| scimark_fft              | 350 ms                                                                | 386 ms: 1.10x slower                                                    |
| regex_compile            | 133 ms                                                                | 148 ms: 1.11x slower                                                    |
| scimark_sparse_mat_mult  | 4.67 ms                                                               | 5.38 ms: 1.15x slower                                                   |
| fannkuch                 | 373 ms                                                                | 435 ms: 1.17x slower                                                    |
| chaos                    | 59.8 ms                                                               | 72.7 ms: 1.22x slower                                                   |
| nqueens                  | 78.4 ms                                                               | 95.7 ms: 1.22x slower                                                   |
| comprehensions           | 20.5 us                                                               | 25.4 us: 1.24x slower                                                   |
| unpack_sequence          | 44.4 ns                                                               | 55.2 ns: 1.24x slower                                                   |
| hexiom                   | 5.82 ms                                                               | 7.28 ms: 1.25x slower                                                   |
| nbody                    | 89.2 ms                                                               | 127 ms: 1.42x slower                                                    |
| Geometric mean           | (ref)                                                                 | 1.05x slower                                                            |

Benchmark hidden because not significant (7): coverage, pprint_pformat, bench_mp_pool, json_loads, sqlite_synth, pickle_pure_python, json_dumps


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
