
# Results vs. base

- fork: brandtbucher
- ref: justin_stubs
- machine: linux-x86_64
- commit hash: e6cb4a7
- commit date: 2023-09-23
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.59 sec                                                              | 2.69 sec: 1.04x slower                                              |
| tornado_http   | 95.3 ms                                                               | 97.0 ms: 1.02x slower                                               |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pidigits       | 187 ms                                                                | 188 ms: 1.01x slower                                                |
| nbody          | 88.0 ms                                                               | 90.9 ms: 1.03x slower                                               |
| float          | 78.5 ms                                                               | 82.5 ms: 1.05x slower                                               |
| Geometric mean | (ref)                                                                 | 1.03x slower                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 209 ms                                                                | 210 ms: 1.00x slower                                                |
| regex_v8       | 23.1 ms                                                               | 23.3 ms: 1.01x slower                                               |
| regex_effbot   | 3.57 ms                                                               | 3.65 ms: 1.02x slower                                               |
| regex_compile  | 134 ms                                                                | 143 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                                 | 1.02x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_list          | 4.70 us                                                               | 4.58 us: 1.03x faster                                               |
| pickle               | 10.5 us                                                               | 10.3 us: 1.01x faster                                               |
| json_loads           | 25.4 us                                                               | 25.2 us: 1.01x faster                                               |
| pickle_dict          | 31.9 us                                                               | 31.6 us: 1.01x faster                                               |
| xml_etree_parse      | 153 ms                                                                | 152 ms: 1.01x faster                                                |
| unpickle_list        | 4.99 us                                                               | 5.02 us: 1.01x slower                                               |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                                |
| tomli_loads          | 2.04 sec                                                              | 2.07 sec: 1.02x slower                                              |
| unpickle_pure_python | 214 us                                                                | 223 us: 1.04x slower                                                |
| Geometric mean       | (ref)                                                                 | 1.00x slower                                                        |

Benchmark hidden because not significant (5): json_dumps, xml_etree_process, pickle_pure_python, xml_etree_generate, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                               |
| python_startup_no_site | 6.82 ms                                                               | 6.88 ms: 1.01x slower                                               |
| Geometric mean         | (ref)                                                                 | 1.01x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.6 ms                                                               | 11.0 ms: 1.03x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20230922-linux-x86_64-python-8a82bff12c8e6c6c204c-3.13.0a0-8a82bff | bm-20230923-linux-x86_64-brandtbucher-justin_stubs-3.13.0a0-e6cb4a7 |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| scimark_fft              | 362 ms                                                                | 341 ms: 1.06x faster                                                |
| pickle_list              | 4.70 us                                                               | 4.58 us: 1.03x faster                                               |
| coroutines               | 22.3 ms                                                               | 21.9 ms: 1.02x faster                                               |
| pickle                   | 10.5 us                                                               | 10.3 us: 1.01x faster                                               |
| json_loads               | 25.4 us                                                               | 25.2 us: 1.01x faster                                               |
| pickle_dict              | 31.9 us                                                               | 31.6 us: 1.01x faster                                               |
| xml_etree_parse          | 153 ms                                                                | 152 ms: 1.01x faster                                                |
| scimark_sor              | 120 ms                                                                | 120 ms: 1.00x faster                                                |
| regex_dna                | 209 ms                                                                | 210 ms: 1.00x slower                                                |
| pathlib                  | 18.6 ms                                                               | 18.7 ms: 1.01x slower                                               |
| regex_v8                 | 23.1 ms                                                               | 23.3 ms: 1.01x slower                                               |
| unpickle_list            | 4.99 us                                                               | 5.02 us: 1.01x slower                                               |
| pidigits                 | 187 ms                                                                | 188 ms: 1.01x slower                                                |
| python_startup           | 10.0 ms                                                               | 10.1 ms: 1.01x slower                                               |
| create_gc_cycles         | 1.51 ms                                                               | 1.53 ms: 1.01x slower                                               |
| pycparser                | 1.18 sec                                                              | 1.19 sec: 1.01x slower                                              |
| python_startup_no_site   | 6.82 ms                                                               | 6.88 ms: 1.01x slower                                               |
| sqlglot_parse            | 1.27 ms                                                               | 1.28 ms: 1.01x slower                                               |
| richards                 | 47.7 ms                                                               | 48.2 ms: 1.01x slower                                               |
| scimark_lu               | 110 ms                                                                | 112 ms: 1.01x slower                                                |
| async_tree_memoization   | 564 ms                                                                | 571 ms: 1.01x slower                                                |
| deepcopy_reduce          | 3.13 us                                                               | 3.17 us: 1.01x slower                                               |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                                |
| raytrace                 | 267 ms                                                                | 271 ms: 1.02x slower                                                |
| sqlglot_normalize        | 105 ms                                                                | 106 ms: 1.02x slower                                                |
| coverage                 | 85.2 ms                                                               | 86.7 ms: 1.02x slower                                               |
| tornado_http             | 95.3 ms                                                               | 97.0 ms: 1.02x slower                                               |
| tomli_loads              | 2.04 sec                                                              | 2.07 sec: 1.02x slower                                              |
| spectral_norm            | 107 ms                                                                | 109 ms: 1.02x slower                                                |
| sqlglot_transpile        | 1.58 ms                                                               | 1.61 ms: 1.02x slower                                               |
| pyflate                  | 450 ms                                                                | 459 ms: 1.02x slower                                                |
| deltablue                | 3.31 ms                                                               | 3.38 ms: 1.02x slower                                               |
| scimark_sparse_mat_mult  | 4.64 ms                                                               | 4.74 ms: 1.02x slower                                               |
| regex_effbot             | 3.57 ms                                                               | 3.65 ms: 1.02x slower                                               |
| deepcopy                 | 349 us                                                                | 357 us: 1.02x slower                                                |
| bench_thread_pool        | 813 us                                                                | 832 us: 1.02x slower                                                |
| sqlglot_optimize         | 52.3 ms                                                               | 53.6 ms: 1.02x slower                                               |
| asyncio_tcp              | 489 ms                                                                | 503 ms: 1.03x slower                                                |
| dulwich_log              | 66.2 ms                                                               | 68.3 ms: 1.03x slower                                               |
| mako                     | 10.6 ms                                                               | 11.0 ms: 1.03x slower                                               |
| nbody                    | 88.0 ms                                                               | 90.9 ms: 1.03x slower                                               |
| mdp                      | 2.53 sec                                                              | 2.62 sec: 1.03x slower                                              |
| pprint_safe_repr         | 723 ms                                                                | 748 ms: 1.03x slower                                                |
| pprint_pformat           | 1.47 sec                                                              | 1.52 sec: 1.04x slower                                              |
| meteor_contest           | 106 ms                                                                | 110 ms: 1.04x slower                                                |
| docutils                 | 2.59 sec                                                              | 2.69 sec: 1.04x slower                                              |
| go                       | 139 ms                                                                | 145 ms: 1.04x slower                                                |
| mypy2                    | 337 ms                                                                | 350 ms: 1.04x slower                                                |
| unpickle_pure_python     | 214 us                                                                | 223 us: 1.04x slower                                                |
| logging_silent           | 101 ns                                                                | 105 ns: 1.04x slower                                                |
| async_generators         | 443 ms                                                                | 464 ms: 1.05x slower                                                |
| fannkuch                 | 382 ms                                                                | 401 ms: 1.05x slower                                                |
| float                    | 78.5 ms                                                               | 82.5 ms: 1.05x slower                                               |
| crypto_pyaes             | 67.8 ms                                                               | 71.3 ms: 1.05x slower                                               |
| logging_simple           | 5.92 us                                                               | 6.24 us: 1.06x slower                                               |
| logging_format           | 6.53 us                                                               | 6.92 us: 1.06x slower                                               |
| typing_runtime_protocols | 139 us                                                                | 148 us: 1.07x slower                                                |
| regex_compile            | 134 ms                                                                | 143 ms: 1.07x slower                                                |
| deepcopy_memo            | 36.3 us                                                               | 39.1 us: 1.08x slower                                               |
| chaos                    | 59.8 ms                                                               | 64.8 ms: 1.08x slower                                               |
| nqueens                  | 79.3 ms                                                               | 87.1 ms: 1.10x slower                                               |
| comprehensions           | 20.3 us                                                               | 23.0 us: 1.13x slower                                               |
| gc_traversal             | 3.87 ms                                                               | 4.37 ms: 1.13x slower                                               |
| unpack_sequence          | 43.6 ns                                                               | 49.9 ns: 1.14x slower                                               |
| hexiom                   | 5.99 ms                                                               | 6.86 ms: 1.15x slower                                               |
| Geometric mean           | (ref)                                                                 | 1.02x slower                                                        |

Benchmark hidden because not significant (17): json_dumps, telco, xml_etree_process, asyncio_tcp_ssl, scimark_monte_carlo, bench_mp_pool, dask, async_tree_io, richards_super, pickle_pure_python, generators, json, sqlite_synth, xml_etree_generate, async_tree_cpu_io_mixed, unpickle, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
