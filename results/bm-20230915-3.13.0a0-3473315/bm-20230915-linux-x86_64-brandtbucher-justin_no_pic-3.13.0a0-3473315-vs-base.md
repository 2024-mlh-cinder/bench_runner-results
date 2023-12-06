
# Results vs. base

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3473315
- commit date: 2023-09-15
- overall geometric mean: 1.01x slower
- HPT reliability: 99.87%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.67 sec: 1.02x slower                                               |
| tornado_http   | 95.0 ms                                                               | 96.8 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                                 |
| float          | 78.7 ms                                                               | 81.5 ms: 1.04x slower                                                |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                         |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_effbot   | 3.63 ms                                                               | 3.40 ms: 1.07x faster                                                |
| regex_dna      | 209 ms                                                                | 204 ms: 1.02x faster                                                 |
| regex_v8       | 23.0 ms                                                               | 23.4 ms: 1.02x slower                                                |
| regex_compile  | 134 ms                                                                | 142 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|----------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| unpickle             | 14.9 us                                                               | 14.1 us: 1.06x faster                                                |
| pickle               | 10.8 us                                                               | 10.3 us: 1.05x faster                                                |
| pickle_dict          | 32.4 us                                                               | 31.2 us: 1.04x faster                                                |
| xml_etree_parse      | 154 ms                                                                | 152 ms: 1.02x faster                                                 |
| xml_etree_process    | 58.0 ms                                                               | 57.4 ms: 1.01x faster                                                |
| pickle_list          | 4.67 us                                                               | 4.64 us: 1.01x faster                                                |
| xml_etree_generate   | 83.9 ms                                                               | 83.4 ms: 1.01x faster                                                |
| unpickle_list        | 4.90 us                                                               | 4.87 us: 1.01x faster                                                |
| json_loads           | 25.4 us                                                               | 25.3 us: 1.00x faster                                                |
| pickle_pure_python   | 297 us                                                                | 300 us: 1.01x slower                                                 |
| tomli_loads          | 2.04 sec                                                              | 2.06 sec: 1.01x slower                                               |
| unpickle_pure_python | 211 us                                                                | 225 us: 1.07x slower                                                 |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                         |

Benchmark hidden because not significant (2): json_dumps, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                               | 10.0 ms: 1.01x faster                                                |
| python_startup_no_site | 6.86 ms                                                               | 6.82 ms: 1.01x faster                                                |
| Geometric mean         | (ref)                                                                 | 1.01x faster                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|-----------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 10.9 ms: 1.04x slower                                                |

All benchmarks:
===============

| Benchmark                | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230915-linux-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3473315 |
|--------------------------|:---------------------------------------------------------------------:|:--------------------------------------------------------------------:|
| scimark_sor              | 130 ms                                                                | 119 ms: 1.09x faster                                                 |
| gc_traversal             | 4.11 ms                                                               | 3.84 ms: 1.07x faster                                                |
| regex_effbot             | 3.63 ms                                                               | 3.40 ms: 1.07x faster                                                |
| unpickle                 | 14.9 us                                                               | 14.1 us: 1.06x faster                                                |
| pickle                   | 10.8 us                                                               | 10.3 us: 1.05x faster                                                |
| pickle_dict              | 32.4 us                                                               | 31.2 us: 1.04x faster                                                |
| scimark_fft              | 352 ms                                                                | 340 ms: 1.03x faster                                                 |
| pycparser                | 1.18 sec                                                              | 1.15 sec: 1.03x faster                                               |
| unpack_sequence          | 48.2 ns                                                               | 46.9 ns: 1.03x faster                                                |
| regex_dna                | 209 ms                                                                | 204 ms: 1.02x faster                                                 |
| logging_format           | 6.80 us                                                               | 6.66 us: 1.02x faster                                                |
| scimark_monte_carlo      | 67.9 ms                                                               | 66.5 ms: 1.02x faster                                                |
| telco                    | 8.07 ms                                                               | 7.92 ms: 1.02x faster                                                |
| logging_simple           | 6.05 us                                                               | 5.94 us: 1.02x faster                                                |
| xml_etree_parse          | 154 ms                                                                | 152 ms: 1.02x faster                                                 |
| pprint_safe_repr         | 727 ms                                                                | 717 ms: 1.01x faster                                                 |
| create_gc_cycles         | 1.52 ms                                                               | 1.50 ms: 1.01x faster                                                |
| richards                 | 48.1 ms                                                               | 47.6 ms: 1.01x faster                                                |
| xml_etree_process        | 58.0 ms                                                               | 57.4 ms: 1.01x faster                                                |
| deepcopy_reduce          | 3.12 us                                                               | 3.10 us: 1.01x faster                                                |
| python_startup           | 10.1 ms                                                               | 10.0 ms: 1.01x faster                                                |
| python_startup_no_site   | 6.86 ms                                                               | 6.82 ms: 1.01x faster                                                |
| pickle_list              | 4.67 us                                                               | 4.64 us: 1.01x faster                                                |
| xml_etree_generate       | 83.9 ms                                                               | 83.4 ms: 1.01x faster                                                |
| unpickle_list            | 4.90 us                                                               | 4.87 us: 1.01x faster                                                |
| json_loads               | 25.4 us                                                               | 25.3 us: 1.00x faster                                                |
| pyflate                  | 454 ms                                                                | 456 ms: 1.00x slower                                                 |
| generators               | 28.3 ms                                                               | 28.5 ms: 1.00x slower                                                |
| sqlglot_transpile        | 1.58 ms                                                               | 1.59 ms: 1.01x slower                                                |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.01x slower                                               |
| raytrace                 | 268 ms                                                                | 270 ms: 1.01x slower                                                 |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                                 |
| sqlglot_parse            | 1.27 ms                                                               | 1.28 ms: 1.01x slower                                                |
| pickle_pure_python       | 297 us                                                                | 300 us: 1.01x slower                                                 |
| tomli_loads              | 2.04 sec                                                              | 2.06 sec: 1.01x slower                                               |
| asyncio_tcp              | 480 ms                                                                | 487 ms: 1.02x slower                                                 |
| sqlglot_optimize         | 52.5 ms                                                               | 53.4 ms: 1.02x slower                                                |
| spectral_norm            | 106 ms                                                                | 108 ms: 1.02x slower                                                 |
| tornado_http             | 95.0 ms                                                               | 96.8 ms: 1.02x slower                                                |
| regex_v8                 | 23.0 ms                                                               | 23.4 ms: 1.02x slower                                                |
| scimark_lu               | 110 ms                                                                | 112 ms: 1.02x slower                                                 |
| deepcopy                 | 344 us                                                                | 351 us: 1.02x slower                                                 |
| sqlglot_normalize        | 104 ms                                                                | 106 ms: 1.02x slower                                                 |
| pathlib                  | 18.3 ms                                                               | 18.7 ms: 1.02x slower                                                |
| deepcopy_memo            | 36.1 us                                                               | 37.0 us: 1.02x slower                                                |
| docutils                 | 2.60 sec                                                              | 2.67 sec: 1.02x slower                                               |
| async_generators         | 447 ms                                                                | 458 ms: 1.03x slower                                                 |
| dulwich_log              | 66.8 ms                                                               | 68.7 ms: 1.03x slower                                                |
| logging_silent           | 100 ns                                                                | 103 ns: 1.03x slower                                                 |
| scimark_sparse_mat_mult  | 4.56 ms                                                               | 4.69 ms: 1.03x slower                                                |
| deltablue                | 3.28 ms                                                               | 3.38 ms: 1.03x slower                                                |
| bench_thread_pool        | 809 us                                                                | 834 us: 1.03x slower                                                 |
| go                       | 140 ms                                                                | 144 ms: 1.03x slower                                                 |
| crypto_pyaes             | 69.2 ms                                                               | 71.6 ms: 1.04x slower                                                |
| float                    | 78.7 ms                                                               | 81.5 ms: 1.04x slower                                                |
| mdp                      | 2.63 sec                                                              | 2.73 sec: 1.04x slower                                               |
| meteor_contest           | 105 ms                                                                | 109 ms: 1.04x slower                                                 |
| mako                     | 10.5 ms                                                               | 10.9 ms: 1.04x slower                                                |
| mypy2                    | 336 ms                                                                | 350 ms: 1.04x slower                                                 |
| typing_runtime_protocols | 142 us                                                                | 147 us: 1.04x slower                                                 |
| json                     | 4.81 ms                                                               | 5.02 ms: 1.04x slower                                                |
| fannkuch                 | 389 ms                                                                | 409 ms: 1.05x slower                                                 |
| regex_compile            | 134 ms                                                                | 142 ms: 1.06x slower                                                 |
| unpickle_pure_python     | 211 us                                                                | 225 us: 1.07x slower                                                 |
| chaos                    | 59.3 ms                                                               | 64.3 ms: 1.08x slower                                                |
| comprehensions           | 20.4 us                                                               | 22.5 us: 1.10x slower                                                |
| nqueens                  | 78.8 ms                                                               | 87.8 ms: 1.11x slower                                                |
| hexiom                   | 5.86 ms                                                               | 6.80 ms: 1.16x slower                                                |
| Geometric mean           | (ref)                                                                 | 1.01x slower                                                         |

Benchmark hidden because not significant (14): async_tree_cpu_io_mixed, coverage, sqlite_synth, json_dumps, richards_super, async_tree_none, dask, nbody, bench_mp_pool, async_tree_io, coroutines, xml_etree_iterparse, pprint_pformat, async_tree_memoization


# HPT report

- Reliability score: 99.87% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
