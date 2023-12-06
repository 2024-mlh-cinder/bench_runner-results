
# Results vs. base

- fork: brandtbucher
- ref: justin_operands
- machine: linux-x86_64
- commit hash: fb96638
- commit date: 2023-09-24
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 2.59 sec                                                              | 2.71 sec: 1.04x slower                                                 |
| tornado_http   | 95.3 ms                                                               | 97.1 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 189 ms: 1.01x slower                                                   |
| float          | 78.5 ms                                                               | 83.1 ms: 1.06x slower                                                  |
| nbody          | 88.0 ms                                                               | 97.5 ms: 1.11x slower                                                  |
| Geometric mean | (ref)                                                                 | 1.06x slower                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                                | 206 ms: 1.01x faster                                                   |
| regex_effbot   | 3.57 ms                                                               | 3.54 ms: 1.01x faster                                                  |
| regex_v8       | 23.1 ms                                                               | 23.6 ms: 1.02x slower                                                  |
| regex_compile  | 134 ms                                                                | 145 ms: 1.08x slower                                                   |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------------|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict          | 31.9 us                                                               | 30.7 us: 1.04x faster                                                  |
| pickle               | 10.5 us                                                               | 10.1 us: 1.04x faster                                                  |
| unpickle_list        | 4.99 us                                                               | 4.91 us: 1.01x faster                                                  |
| pickle_list          | 4.70 us                                                               | 4.64 us: 1.01x faster                                                  |
| xml_etree_process    | 58.2 ms                                                               | 57.6 ms: 1.01x faster                                                  |
| xml_etree_parse      | 153 ms                                                                | 152 ms: 1.01x faster                                                   |
| xml_etree_generate   | 84.2 ms                                                               | 83.7 ms: 1.01x faster                                                  |
| json_dumps           | 9.88 ms                                                               | 9.93 ms: 1.01x slower                                                  |
| xml_etree_iterparse  | 102 ms                                                                | 102 ms: 1.01x slower                                                   |
| pickle_pure_python   | 296 us                                                                | 300 us: 1.02x slower                                                   |
| tomli_loads          | 2.04 sec                                                              | 2.12 sec: 1.04x slower                                                 |
| unpickle_pure_python | 214 us                                                                | 230 us: 1.08x slower                                                   |
| Geometric mean       | (ref)                                                                 | 1.00x slower                                                           |

Benchmark hidden because not significant (2): unpickle, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|------------------------|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                  |
| python_startup_no_site | 6.82 ms                                                               | 6.87 ms: 1.01x slower                                                  |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|-----------|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 11.0 ms: 1.04x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|--------------------------|:---------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict              | 31.9 us                                                               | 30.7 us: 1.04x faster                                                  |
| pickle                   | 10.5 us                                                               | 10.1 us: 1.04x faster                                                  |
| unpickle_list            | 4.99 us                                                               | 4.91 us: 1.01x faster                                                  |
| pickle_list              | 4.70 us                                                               | 4.64 us: 1.01x faster                                                  |
| regex_dna                | 209 ms                                                                | 206 ms: 1.01x faster                                                   |
| scimark_fft              | 362 ms                                                                | 358 ms: 1.01x faster                                                   |
| xml_etree_process        | 58.2 ms                                                               | 57.6 ms: 1.01x faster                                                  |
| regex_effbot             | 3.57 ms                                                               | 3.54 ms: 1.01x faster                                                  |
| xml_etree_parse          | 153 ms                                                                | 152 ms: 1.01x faster                                                   |
| xml_etree_generate       | 84.2 ms                                                               | 83.7 ms: 1.01x faster                                                  |
| coverage                 | 85.2 ms                                                               | 84.8 ms: 1.01x faster                                                  |
| gc_traversal             | 3.87 ms                                                               | 3.86 ms: 1.00x faster                                                  |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.00x slower                                                 |
| json_dumps               | 9.88 ms                                                               | 9.93 ms: 1.01x slower                                                  |
| spectral_norm            | 107 ms                                                                | 108 ms: 1.01x slower                                                   |
| xml_etree_iterparse      | 102 ms                                                                | 102 ms: 1.01x slower                                                   |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                  |
| create_gc_cycles         | 1.51 ms                                                               | 1.52 ms: 1.01x slower                                                  |
| python_startup_no_site   | 6.82 ms                                                               | 6.87 ms: 1.01x slower                                                  |
| sqlglot_parse            | 1.27 ms                                                               | 1.28 ms: 1.01x slower                                                  |
| pidigits                 | 187 ms                                                                | 189 ms: 1.01x slower                                                   |
| sqlite_synth             | 2.75 us                                                               | 2.78 us: 1.01x slower                                                  |
| pycparser                | 1.18 sec                                                              | 1.20 sec: 1.01x slower                                                 |
| coroutines               | 22.3 ms                                                               | 22.7 ms: 1.02x slower                                                  |
| telco                    | 8.09 ms                                                               | 8.22 ms: 1.02x slower                                                  |
| pickle_pure_python       | 296 us                                                                | 300 us: 1.02x slower                                                   |
| regex_v8                 | 23.1 ms                                                               | 23.6 ms: 1.02x slower                                                  |
| deepcopy_reduce          | 3.13 us                                                               | 3.19 us: 1.02x slower                                                  |
| tornado_http             | 95.3 ms                                                               | 97.1 ms: 1.02x slower                                                  |
| sqlglot_transpile        | 1.58 ms                                                               | 1.61 ms: 1.02x slower                                                  |
| scimark_sor              | 120 ms                                                                | 123 ms: 1.02x slower                                                   |
| generators               | 28.3 ms                                                               | 29.0 ms: 1.02x slower                                                  |
| deepcopy                 | 349 us                                                                | 357 us: 1.02x slower                                                   |
| bench_thread_pool        | 813 us                                                                | 834 us: 1.02x slower                                                   |
| asyncio_tcp              | 489 ms                                                                | 502 ms: 1.03x slower                                                   |
| pyflate                  | 450 ms                                                                | 461 ms: 1.03x slower                                                   |
| json                     | 4.85 ms                                                               | 4.97 ms: 1.03x slower                                                  |
| mdp                      | 2.53 sec                                                              | 2.60 sec: 1.03x slower                                                 |
| sqlglot_normalize        | 105 ms                                                                | 108 ms: 1.03x slower                                                   |
| logging_simple           | 5.92 us                                                               | 6.09 us: 1.03x slower                                                  |
| pprint_pformat           | 1.47 sec                                                              | 1.52 sec: 1.03x slower                                                 |
| async_generators         | 443 ms                                                                | 457 ms: 1.03x slower                                                   |
| raytrace                 | 267 ms                                                                | 276 ms: 1.03x slower                                                   |
| pprint_safe_repr         | 723 ms                                                                | 748 ms: 1.03x slower                                                   |
| mako                     | 10.6 ms                                                               | 11.0 ms: 1.04x slower                                                  |
| scimark_lu               | 110 ms                                                                | 114 ms: 1.04x slower                                                   |
| sqlglot_optimize         | 52.3 ms                                                               | 54.3 ms: 1.04x slower                                                  |
| mypy2                    | 337 ms                                                                | 351 ms: 1.04x slower                                                   |
| tomli_loads              | 2.04 sec                                                              | 2.12 sec: 1.04x slower                                                 |
| deltablue                | 3.31 ms                                                               | 3.45 ms: 1.04x slower                                                  |
| dulwich_log              | 66.2 ms                                                               | 69.0 ms: 1.04x slower                                                  |
| logging_silent           | 101 ns                                                                | 105 ns: 1.04x slower                                                   |
| scimark_sparse_mat_mult  | 4.64 ms                                                               | 4.84 ms: 1.04x slower                                                  |
| docutils                 | 2.59 sec                                                              | 2.71 sec: 1.04x slower                                                 |
| typing_runtime_protocols | 139 us                                                                | 146 us: 1.05x slower                                                   |
| logging_format           | 6.53 us                                                               | 6.85 us: 1.05x slower                                                  |
| go                       | 139 ms                                                                | 146 ms: 1.05x slower                                                   |
| crypto_pyaes             | 67.8 ms                                                               | 71.5 ms: 1.05x slower                                                  |
| scimark_monte_carlo      | 66.2 ms                                                               | 69.8 ms: 1.05x slower                                                  |
| meteor_contest           | 106 ms                                                                | 112 ms: 1.06x slower                                                   |
| float                    | 78.5 ms                                                               | 83.1 ms: 1.06x slower                                                  |
| fannkuch                 | 382 ms                                                                | 408 ms: 1.07x slower                                                   |
| unpickle_pure_python     | 214 us                                                                | 230 us: 1.08x slower                                                   |
| deepcopy_memo            | 36.3 us                                                               | 39.2 us: 1.08x slower                                                  |
| regex_compile            | 134 ms                                                                | 145 ms: 1.08x slower                                                   |
| nbody                    | 88.0 ms                                                               | 97.5 ms: 1.11x slower                                                  |
| chaos                    | 59.8 ms                                                               | 66.6 ms: 1.11x slower                                                  |
| unpack_sequence          | 43.6 ns                                                               | 49.0 ns: 1.12x slower                                                  |
| nqueens                  | 79.3 ms                                                               | 89.4 ms: 1.13x slower                                                  |
| comprehensions           | 20.3 us                                                               | 23.1 us: 1.14x slower                                                  |
| hexiom                   | 5.99 ms                                                               | 6.89 ms: 1.15x slower                                                  |
| Geometric mean           | (ref)                                                                 | 1.03x slower                                                           |

Benchmark hidden because not significant (11): unpickle, pathlib, async_tree_io, bench_mp_pool, json_loads, dask, async_tree_cpu_io_mixed, richards_super, richards, async_tree_memoization, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
