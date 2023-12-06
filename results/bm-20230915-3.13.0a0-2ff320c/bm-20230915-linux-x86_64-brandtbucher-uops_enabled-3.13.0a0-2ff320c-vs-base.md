
# Results vs. base

- fork: brandtbucher
- ref: uops_enabled
- machine: linux-x86_64
- commit hash: 2ff320c
- commit date: 2023-09-15
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.71 sec: 1.04x slower                                              |
| tornado_http   | 95.0 ms                                                               | 97.2 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.00x slower                                                |
| float          | 78.7 ms                                                               | 85.1 ms: 1.08x slower                                               |
| nbody          | 87.9 ms                                                               | 108 ms: 1.23x slower                                                |
| Geometric mean | (ref)                                                                 | 1.10x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                                | 208 ms: 1.01x faster                                                |
| regex_effbot   | 3.63 ms                                                               | 3.61 ms: 1.01x faster                                               |
| regex_v8       | 23.0 ms                                                               | 23.6 ms: 1.03x slower                                               |
| regex_compile  | 134 ms                                                                | 152 ms: 1.13x slower                                                |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpickle_list        | 4.90 us                                                               | 4.82 us: 1.02x faster                                               |
| xml_etree_parse      | 154 ms                                                                | 153 ms: 1.01x faster                                                |
| xml_etree_process    | 58.0 ms                                                               | 57.4 ms: 1.01x faster                                               |
| pickle_pure_python   | 297 us                                                                | 299 us: 1.01x slower                                                |
| pickle_list          | 4.67 us                                                               | 4.71 us: 1.01x slower                                               |
| pickle_dict          | 32.4 us                                                               | 32.7 us: 1.01x slower                                               |
| unpickle_pure_python | 211 us                                                                | 237 us: 1.12x slower                                                |
| tomli_loads          | 2.04 sec                                                              | 2.41 sec: 1.18x slower                                              |
| Geometric mean       | (ref)                                                                 | 1.02x slower                                                        |

Benchmark hidden because not significant (6): unpickle, json_loads, pickle, xml_etree_generate, json_dumps, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.86 ms                                                               | 6.85 ms: 1.00x faster                                               |
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                               |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 11.6 ms: 1.10x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-uops_enabled-3.13.0a0-2ff320c |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| gc_traversal             | 4.11 ms                                                               | 3.86 ms: 1.07x faster                                               |
| scimark_sor              | 130 ms                                                                | 124 ms: 1.05x faster                                                |
| unpickle_list            | 4.90 us                                                               | 4.82 us: 1.02x faster                                               |
| xml_etree_parse          | 154 ms                                                                | 153 ms: 1.01x faster                                                |
| xml_etree_process        | 58.0 ms                                                               | 57.4 ms: 1.01x faster                                               |
| sqlite_synth             | 2.76 us                                                               | 2.73 us: 1.01x faster                                               |
| regex_dna                | 209 ms                                                                | 208 ms: 1.01x faster                                                |
| regex_effbot             | 3.63 ms                                                               | 3.61 ms: 1.01x faster                                               |
| python_startup_no_site   | 6.86 ms                                                               | 6.85 ms: 1.00x faster                                               |
| python_startup           | 10.1 ms                                                               | 10.1 ms: 1.00x faster                                               |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.80 sec: 1.00x slower                                              |
| pidigits                 | 187 ms                                                                | 188 ms: 1.00x slower                                                |
| pickle_pure_python       | 297 us                                                                | 299 us: 1.01x slower                                                |
| async_generators         | 447 ms                                                                | 451 ms: 1.01x slower                                                |
| generators               | 28.3 ms                                                               | 28.6 ms: 1.01x slower                                               |
| pickle_list              | 4.67 us                                                               | 4.71 us: 1.01x slower                                               |
| mdp                      | 2.63 sec                                                              | 2.65 sec: 1.01x slower                                              |
| pickle_dict              | 32.4 us                                                               | 32.7 us: 1.01x slower                                               |
| create_gc_cycles         | 1.52 ms                                                               | 1.54 ms: 1.01x slower                                               |
| async_tree_io            | 1.19 sec                                                              | 1.20 sec: 1.01x slower                                              |
| coverage                 | 84.9 ms                                                               | 85.9 ms: 1.01x slower                                               |
| sqlglot_transpile        | 1.58 ms                                                               | 1.60 ms: 1.01x slower                                               |
| coroutines               | 21.8 ms                                                               | 22.1 ms: 1.01x slower                                               |
| sqlglot_parse            | 1.27 ms                                                               | 1.28 ms: 1.01x slower                                               |
| deepcopy_reduce          | 3.12 us                                                               | 3.17 us: 1.02x slower                                               |
| spectral_norm            | 106 ms                                                                | 108 ms: 1.02x slower                                                |
| sqlglot_optimize         | 52.5 ms                                                               | 53.5 ms: 1.02x slower                                               |
| pprint_pformat           | 1.47 sec                                                              | 1.50 sec: 1.02x slower                                              |
| sqlglot_normalize        | 104 ms                                                                | 106 ms: 1.02x slower                                                |
| async_tree_memoization   | 563 ms                                                                | 575 ms: 1.02x slower                                                |
| async_tree_none          | 438 ms                                                                | 448 ms: 1.02x slower                                                |
| tornado_http             | 95.0 ms                                                               | 97.2 ms: 1.02x slower                                               |
| dulwich_log              | 66.8 ms                                                               | 68.4 ms: 1.02x slower                                               |
| regex_v8                 | 23.0 ms                                                               | 23.6 ms: 1.03x slower                                               |
| logging_simple           | 6.05 us                                                               | 6.25 us: 1.03x slower                                               |
| pathlib                  | 18.3 ms                                                               | 19.0 ms: 1.03x slower                                               |
| bench_thread_pool        | 809 us                                                                | 837 us: 1.03x slower                                                |
| richards                 | 48.1 ms                                                               | 49.8 ms: 1.03x slower                                               |
| pycparser                | 1.18 sec                                                              | 1.23 sec: 1.04x slower                                              |
| mypy2                    | 336 ms                                                                | 348 ms: 1.04x slower                                                |
| deepcopy                 | 344 us                                                                | 356 us: 1.04x slower                                                |
| logging_format           | 6.80 us                                                               | 7.04 us: 1.04x slower                                               |
| docutils                 | 2.60 sec                                                              | 2.71 sec: 1.04x slower                                              |
| logging_silent           | 100 ns                                                                | 105 ns: 1.04x slower                                                |
| richards_super           | 53.8 ms                                                               | 56.2 ms: 1.05x slower                                               |
| unpack_sequence          | 48.2 ns                                                               | 50.4 ns: 1.05x slower                                               |
| scimark_lu               | 110 ms                                                                | 115 ms: 1.05x slower                                                |
| raytrace                 | 268 ms                                                                | 281 ms: 1.05x slower                                                |
| typing_runtime_protocols | 142 us                                                                | 151 us: 1.06x slower                                                |
| pyflate                  | 454 ms                                                                | 483 ms: 1.06x slower                                                |
| crypto_pyaes             | 69.2 ms                                                               | 73.7 ms: 1.07x slower                                               |
| go                       | 140 ms                                                                | 149 ms: 1.07x slower                                                |
| deltablue                | 3.28 ms                                                               | 3.55 ms: 1.08x slower                                               |
| float                    | 78.7 ms                                                               | 85.1 ms: 1.08x slower                                               |
| meteor_contest           | 105 ms                                                                | 114 ms: 1.08x slower                                                |
| scimark_fft              | 352 ms                                                                | 383 ms: 1.09x slower                                                |
| mako                     | 10.5 ms                                                               | 11.6 ms: 1.10x slower                                               |
| unpickle_pure_python     | 211 us                                                                | 237 us: 1.12x slower                                                |
| regex_compile            | 134 ms                                                                | 152 ms: 1.13x slower                                                |
| fannkuch                 | 389 ms                                                                | 441 ms: 1.13x slower                                                |
| deepcopy_memo            | 36.1 us                                                               | 40.9 us: 1.13x slower                                               |
| tomli_loads              | 2.04 sec                                                              | 2.41 sec: 1.18x slower                                              |
| chaos                    | 59.3 ms                                                               | 70.7 ms: 1.19x slower                                               |
| nbody                    | 87.9 ms                                                               | 108 ms: 1.23x slower                                                |
| nqueens                  | 78.8 ms                                                               | 97.4 ms: 1.24x slower                                               |
| comprehensions           | 20.4 us                                                               | 25.3 us: 1.24x slower                                               |
| scimark_sparse_mat_mult  | 4.56 ms                                                               | 5.79 ms: 1.27x slower                                               |
| hexiom                   | 5.86 ms                                                               | 7.73 ms: 1.32x slower                                               |
| Geometric mean           | (ref)                                                                 | 1.04x slower                                                        |

Benchmark hidden because not significant (14): unpickle, json_loads, scimark_monte_carlo, pickle, bench_mp_pool, json, xml_etree_generate, asyncio_tcp, json_dumps, pprint_safe_repr, xml_etree_iterparse, telco, dask, async_tree_cpu_io_mixed


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
