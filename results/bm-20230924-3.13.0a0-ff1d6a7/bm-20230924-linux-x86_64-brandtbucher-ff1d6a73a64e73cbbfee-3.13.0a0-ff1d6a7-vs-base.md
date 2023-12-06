
# Results vs. base

- fork: brandtbucher
- ref: ff1d6a73a64e73cbbfee
- machine: linux-x86_64
- commit hash: ff1d6a7
- commit date: 2023-09-24
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 2.59 sec                                                              | 2.69 sec: 1.04x slower                                                      |
| tornado_http   | 95.3 ms                                                               | 96.5 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                                        |
| nbody          | 88.0 ms                                                               | 90.3 ms: 1.03x slower                                                       |
| float          | 78.5 ms                                                               | 82.5 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_effbot   | 3.57 ms                                                               | 3.49 ms: 1.02x faster                                                       |
| regex_dna      | 209 ms                                                                | 206 ms: 1.02x faster                                                        |
| regex_v8       | 23.1 ms                                                               | 23.8 ms: 1.03x slower                                                       |
| regex_compile  | 134 ms                                                                | 140 ms: 1.05x slower                                                        |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|----------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpickle             | 14.7 us                                                               | 14.2 us: 1.03x faster                                                       |
| pickle_dict          | 31.9 us                                                               | 31.1 us: 1.03x faster                                                       |
| unpickle_list        | 4.99 us                                                               | 4.89 us: 1.02x faster                                                       |
| tomli_loads          | 2.04 sec                                                              | 2.00 sec: 1.02x faster                                                      |
| pickle               | 10.5 us                                                               | 10.5 us: 1.00x slower                                                       |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                                        |
| pickle_pure_python   | 296 us                                                                | 300 us: 1.02x slower                                                        |
| unpickle_pure_python | 214 us                                                                | 224 us: 1.05x slower                                                        |
| Geometric mean       | (ref)                                                                 | 1.00x faster                                                                |

Benchmark hidden because not significant (6): xml_etree_parse, json_dumps, pickle_list, json_loads, xml_etree_generate, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 6.82 ms                                                               | 6.86 ms: 1.01x slower                                                       |
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|-----------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 10.9 ms: 1.03x slower                                                       |

All benchmarks:
===============

| Benchmark                | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230924-linux-x86_64-brandtbucher-ff1d6a73a64e73cbbfee-3.13.0a0-ff1d6a7 |
|--------------------------|:---------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| scimark_fft              | 362 ms                                                                | 334 ms: 1.08x faster                                                        |
| unpickle                 | 14.7 us                                                               | 14.2 us: 1.03x faster                                                       |
| scimark_sparse_mat_mult  | 4.64 ms                                                               | 4.51 ms: 1.03x faster                                                       |
| pickle_dict              | 31.9 us                                                               | 31.1 us: 1.03x faster                                                       |
| regex_effbot             | 3.57 ms                                                               | 3.49 ms: 1.02x faster                                                       |
| pycparser                | 1.18 sec                                                              | 1.16 sec: 1.02x faster                                                      |
| unpickle_list            | 4.99 us                                                               | 4.89 us: 1.02x faster                                                       |
| tomli_loads              | 2.04 sec                                                              | 2.00 sec: 1.02x faster                                                      |
| regex_dna                | 209 ms                                                                | 206 ms: 1.02x faster                                                        |
| create_gc_cycles         | 1.51 ms                                                               | 1.50 ms: 1.01x faster                                                       |
| asyncio_tcp              | 489 ms                                                                | 485 ms: 1.01x faster                                                        |
| logging_format           | 6.53 us                                                               | 6.48 us: 1.01x faster                                                       |
| telco                    | 8.09 ms                                                               | 8.03 ms: 1.01x faster                                                       |
| coroutines               | 22.3 ms                                                               | 22.2 ms: 1.01x faster                                                       |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.79 sec: 1.00x faster                                                      |
| pickle                   | 10.5 us                                                               | 10.5 us: 1.00x slower                                                       |
| pathlib                  | 18.6 ms                                                               | 18.7 ms: 1.01x slower                                                       |
| python_startup_no_site   | 6.82 ms                                                               | 6.86 ms: 1.01x slower                                                       |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                                       |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                                        |
| richards_super           | 54.1 ms                                                               | 54.6 ms: 1.01x slower                                                       |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                                        |
| json                     | 4.85 ms                                                               | 4.89 ms: 1.01x slower                                                       |
| generators               | 28.3 ms                                                               | 28.6 ms: 1.01x slower                                                       |
| sqlglot_parse            | 1.27 ms                                                               | 1.29 ms: 1.01x slower                                                       |
| tornado_http             | 95.3 ms                                                               | 96.5 ms: 1.01x slower                                                       |
| async_tree_io            | 1.19 sec                                                              | 1.21 sec: 1.01x slower                                                      |
| sqlglot_transpile        | 1.58 ms                                                               | 1.60 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed  | 702 ms                                                                | 713 ms: 1.02x slower                                                        |
| pickle_pure_python       | 296 us                                                                | 300 us: 1.02x slower                                                        |
| richards                 | 47.7 ms                                                               | 48.5 ms: 1.02x slower                                                       |
| dulwich_log              | 66.2 ms                                                               | 67.3 ms: 1.02x slower                                                       |
| pyflate                  | 450 ms                                                                | 457 ms: 1.02x slower                                                        |
| spectral_norm            | 107 ms                                                                | 109 ms: 1.02x slower                                                        |
| scimark_monte_carlo      | 66.2 ms                                                               | 67.5 ms: 1.02x slower                                                       |
| scimark_sor              | 120 ms                                                                | 123 ms: 1.02x slower                                                        |
| bench_thread_pool        | 813 us                                                                | 832 us: 1.02x slower                                                        |
| deltablue                | 3.31 ms                                                               | 3.39 ms: 1.02x slower                                                       |
| deepcopy                 | 349 us                                                                | 358 us: 1.03x slower                                                        |
| nbody                    | 88.0 ms                                                               | 90.3 ms: 1.03x slower                                                       |
| sqlglot_normalize        | 105 ms                                                                | 107 ms: 1.03x slower                                                        |
| regex_v8                 | 23.1 ms                                                               | 23.8 ms: 1.03x slower                                                       |
| mako                     | 10.6 ms                                                               | 10.9 ms: 1.03x slower                                                       |
| mypy2                    | 337 ms                                                                | 347 ms: 1.03x slower                                                        |
| meteor_contest           | 106 ms                                                                | 109 ms: 1.03x slower                                                        |
| sqlglot_optimize         | 52.3 ms                                                               | 53.9 ms: 1.03x slower                                                       |
| raytrace                 | 267 ms                                                                | 275 ms: 1.03x slower                                                        |
| crypto_pyaes             | 67.8 ms                                                               | 70.0 ms: 1.03x slower                                                       |
| go                       | 139 ms                                                                | 144 ms: 1.03x slower                                                        |
| pprint_safe_repr         | 723 ms                                                                | 749 ms: 1.04x slower                                                        |
| docutils                 | 2.59 sec                                                              | 2.69 sec: 1.04x slower                                                      |
| fannkuch                 | 382 ms                                                                | 397 ms: 1.04x slower                                                        |
| deepcopy_reduce          | 3.13 us                                                               | 3.25 us: 1.04x slower                                                       |
| pprint_pformat           | 1.47 sec                                                              | 1.53 sec: 1.04x slower                                                      |
| async_generators         | 443 ms                                                                | 463 ms: 1.05x slower                                                        |
| regex_compile            | 134 ms                                                                | 140 ms: 1.05x slower                                                        |
| scimark_lu               | 110 ms                                                                | 116 ms: 1.05x slower                                                        |
| unpickle_pure_python     | 214 us                                                                | 224 us: 1.05x slower                                                        |
| float                    | 78.5 ms                                                               | 82.5 ms: 1.05x slower                                                       |
| chaos                    | 59.8 ms                                                               | 63.1 ms: 1.06x slower                                                       |
| deepcopy_memo            | 36.3 us                                                               | 38.7 us: 1.07x slower                                                       |
| logging_silent           | 101 ns                                                                | 108 ns: 1.07x slower                                                        |
| mdp                      | 2.53 sec                                                              | 2.71 sec: 1.07x slower                                                      |
| typing_runtime_protocols | 139 us                                                                | 150 us: 1.07x slower                                                        |
| unpack_sequence          | 43.6 ns                                                               | 46.9 ns: 1.07x slower                                                       |
| gc_traversal             | 3.87 ms                                                               | 4.20 ms: 1.09x slower                                                       |
| hexiom                   | 5.99 ms                                                               | 6.57 ms: 1.10x slower                                                       |
| nqueens                  | 79.3 ms                                                               | 87.7 ms: 1.11x slower                                                       |
| comprehensions           | 20.3 us                                                               | 22.9 us: 1.13x slower                                                       |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                                |

Benchmark hidden because not significant (13): xml_etree_parse, logging_simple, sqlite_synth, bench_mp_pool, coverage, json_dumps, dask, pickle_list, json_loads, xml_etree_generate, xml_etree_process, async_tree_memoization, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
