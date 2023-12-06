
# Results vs. base

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 2.91 sec                                                                    | 2.95 sec: 1.01x slower                                                     |
| Geometric mean | (ref)                                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 264 ms                                                                      | 264 ms: 1.00x slower                                                       |
| float          | 80.4 ms                                                                     | 82.9 ms: 1.03x slower                                                      |
| nbody          | 87.6 ms                                                                     | 93.4 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                                       | 1.03x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 3.63 ms                                                                     | 3.56 ms: 1.02x faster                                                      |
| regex_v8       | 25.6 ms                                                                     | 25.8 ms: 1.01x slower                                                      |
| regex_dna      | 245 ms                                                                      | 248 ms: 1.01x slower                                                       |
| regex_compile  | 147 ms                                                                      | 156 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict          | 32.2 us                                                                     | 31.9 us: 1.01x faster                                                      |
| pickle               | 10.1 us                                                                     | 10.1 us: 1.01x faster                                                      |
| unpickle             | 14.3 us                                                                     | 14.4 us: 1.01x slower                                                      |
| json_dumps           | 10.4 ms                                                                     | 10.6 ms: 1.02x slower                                                      |
| pickle_pure_python   | 310 us                                                                      | 317 us: 1.02x slower                                                       |
| pickle_list          | 4.41 us                                                                     | 4.51 us: 1.02x slower                                                      |
| xml_etree_iterparse  | 105 ms                                                                      | 108 ms: 1.02x slower                                                       |
| xml_etree_parse      | 144 ms                                                                      | 148 ms: 1.03x slower                                                       |
| xml_etree_generate   | 83.9 ms                                                                     | 86.3 ms: 1.03x slower                                                      |
| xml_etree_process    | 58.0 ms                                                                     | 60.2 ms: 1.04x slower                                                      |
| unpickle_pure_python | 227 us                                                                      | 242 us: 1.07x slower                                                       |
| tomli_loads          | 2.20 sec                                                                    | 2.38 sec: 1.09x slower                                                     |
| Geometric mean       | (ref)                                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (2): unpickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 11.9 ms                                                                     | 12.3 ms: 1.03x slower                                                      |
| python_startup_no_site | 8.83 ms                                                                     | 9.26 ms: 1.05x slower                                                      |
| Geometric mean         | (ref)                                                                       | 1.04x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 10.3 ms                                                                     | 10.6 ms: 1.03x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20230905-pythonperf2-x86_64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:---------------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| bench_mp_pool            | 5.73 ms                                                                     | 4.90 ms: 1.17x faster                                                      |
| create_gc_cycles         | 1.64 ms                                                                     | 1.56 ms: 1.05x faster                                                      |
| richards                 | 55.3 ms                                                                     | 53.8 ms: 1.03x faster                                                      |
| regex_effbot             | 3.63 ms                                                                     | 3.56 ms: 1.02x faster                                                      |
| telco                    | 8.20 ms                                                                     | 8.07 ms: 1.02x faster                                                      |
| gc_traversal             | 3.53 ms                                                                     | 3.48 ms: 1.01x faster                                                      |
| pyflate                  | 510 ms                                                                      | 503 ms: 1.01x faster                                                       |
| json                     | 5.18 ms                                                                     | 5.13 ms: 1.01x faster                                                      |
| coverage                 | 83.3 ms                                                                     | 82.5 ms: 1.01x faster                                                      |
| pickle_dict              | 32.2 us                                                                     | 31.9 us: 1.01x faster                                                      |
| pickle                   | 10.1 us                                                                     | 10.1 us: 1.01x faster                                                      |
| pathlib                  | 19.7 ms                                                                     | 19.7 ms: 1.00x faster                                                      |
| pidigits                 | 264 ms                                                                      | 264 ms: 1.00x slower                                                       |
| regex_v8                 | 25.6 ms                                                                     | 25.8 ms: 1.01x slower                                                      |
| dulwich_log              | 69.1 ms                                                                     | 69.5 ms: 1.01x slower                                                      |
| unpickle                 | 14.3 us                                                                     | 14.4 us: 1.01x slower                                                      |
| logging_simple           | 6.83 us                                                                     | 6.88 us: 1.01x slower                                                      |
| dask                     | 591 ms                                                                      | 596 ms: 1.01x slower                                                       |
| async_tree_io            | 1.08 sec                                                                    | 1.09 sec: 1.01x slower                                                     |
| sqlite_synth             | 2.70 us                                                                     | 2.73 us: 1.01x slower                                                      |
| pprint_pformat           | 1.64 sec                                                                    | 1.66 sec: 1.01x slower                                                     |
| docutils                 | 2.91 sec                                                                    | 2.95 sec: 1.01x slower                                                     |
| regex_dna                | 245 ms                                                                      | 248 ms: 1.01x slower                                                       |
| pprint_safe_repr         | 802 ms                                                                      | 815 ms: 1.02x slower                                                       |
| scimark_sor              | 147 ms                                                                      | 150 ms: 1.02x slower                                                       |
| json_dumps               | 10.4 ms                                                                     | 10.6 ms: 1.02x slower                                                      |
| logging_silent           | 98.0 ns                                                                     | 100.0 ns: 1.02x slower                                                     |
| pickle_pure_python       | 310 us                                                                      | 317 us: 1.02x slower                                                       |
| coroutines               | 22.6 ms                                                                     | 23.1 ms: 1.02x slower                                                      |
| pickle_list              | 4.41 us                                                                     | 4.51 us: 1.02x slower                                                      |
| xml_etree_iterparse      | 105 ms                                                                      | 108 ms: 1.02x slower                                                       |
| deepcopy_reduce          | 3.38 us                                                                     | 3.46 us: 1.02x slower                                                      |
| deltablue                | 3.69 ms                                                                     | 3.78 ms: 1.02x slower                                                      |
| xml_etree_parse          | 144 ms                                                                      | 148 ms: 1.03x slower                                                       |
| crypto_pyaes             | 72.3 ms                                                                     | 74.2 ms: 1.03x slower                                                      |
| go                       | 175 ms                                                                      | 179 ms: 1.03x slower                                                       |
| xml_etree_generate       | 83.9 ms                                                                     | 86.3 ms: 1.03x slower                                                      |
| mako                     | 10.3 ms                                                                     | 10.6 ms: 1.03x slower                                                      |
| async_generators         | 397 ms                                                                      | 409 ms: 1.03x slower                                                       |
| float                    | 80.4 ms                                                                     | 82.9 ms: 1.03x slower                                                      |
| python_startup           | 11.9 ms                                                                     | 12.3 ms: 1.03x slower                                                      |
| scimark_monte_carlo      | 68.8 ms                                                                     | 71.1 ms: 1.03x slower                                                      |
| sqlglot_normalize        | 118 ms                                                                      | 122 ms: 1.03x slower                                                       |
| sqlglot_parse            | 1.41 ms                                                                     | 1.46 ms: 1.03x slower                                                      |
| logging_format           | 7.37 us                                                                     | 7.61 us: 1.03x slower                                                      |
| xml_etree_process        | 58.0 ms                                                                     | 60.2 ms: 1.04x slower                                                      |
| bench_thread_pool        | 973 us                                                                      | 1.01 ms: 1.04x slower                                                      |
| sqlglot_optimize         | 59.1 ms                                                                     | 61.4 ms: 1.04x slower                                                      |
| mypy2                    | 372 ms                                                                      | 386 ms: 1.04x slower                                                       |
| sqlglot_transpile        | 1.81 ms                                                                     | 1.88 ms: 1.04x slower                                                      |
| python_startup_no_site   | 8.83 ms                                                                     | 9.26 ms: 1.05x slower                                                      |
| generators               | 35.1 ms                                                                     | 36.9 ms: 1.05x slower                                                      |
| scimark_lu               | 101 ms                                                                      | 106 ms: 1.05x slower                                                       |
| deepcopy_memo            | 37.4 us                                                                     | 39.4 us: 1.05x slower                                                      |
| mdp                      | 2.50 sec                                                                    | 2.64 sec: 1.06x slower                                                     |
| deepcopy                 | 375 us                                                                      | 396 us: 1.06x slower                                                       |
| spectral_norm            | 89.7 ms                                                                     | 95.2 ms: 1.06x slower                                                      |
| typing_runtime_protocols | 147 us                                                                      | 156 us: 1.06x slower                                                       |
| nbody                    | 87.6 ms                                                                     | 93.4 ms: 1.07x slower                                                      |
| regex_compile            | 147 ms                                                                      | 156 ms: 1.07x slower                                                       |
| unpickle_pure_python     | 227 us                                                                      | 242 us: 1.07x slower                                                       |
| meteor_contest           | 130 ms                                                                      | 139 ms: 1.07x slower                                                       |
| fannkuch                 | 391 ms                                                                      | 421 ms: 1.08x slower                                                       |
| chaos                    | 61.6 ms                                                                     | 66.9 ms: 1.08x slower                                                      |
| tomli_loads              | 2.20 sec                                                                    | 2.38 sec: 1.09x slower                                                     |
| scimark_fft              | 297 ms                                                                      | 334 ms: 1.13x slower                                                       |
| comprehensions           | 22.2 us                                                                     | 25.2 us: 1.14x slower                                                      |
| hexiom                   | 6.43 ms                                                                     | 7.40 ms: 1.15x slower                                                      |
| unpack_sequence          | 48.4 ns                                                                     | 56.2 ns: 1.16x slower                                                      |
| nqueens                  | 88.2 ms                                                                     | 104 ms: 1.17x slower                                                       |
| scimark_sparse_mat_mult  | 4.14 ms                                                                     | 5.12 ms: 1.24x slower                                                      |
| Geometric mean           | (ref)                                                                       | 1.03x slower                                                               |

Benchmark hidden because not significant (11): unpickle_list, richards_super, asyncio_tcp_ssl, pycparser, asyncio_tcp, raytrace, json_loads, async_tree_none, async_tree_memoization, async_tree_cpu_io_mixed, tornado_http


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
