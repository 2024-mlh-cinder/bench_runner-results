
# Results vs. base

- fork: gvanrossum
- ref: load_attr_uops
- machine: linux-x86_64
- commit hash: b54eee3
- commit date: 2023-09-26
- overall geometric mean: 1.00x faster
- HPT reliability: 88.93%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| tornado_http   | 95.7 ms                                                               | 95.1 ms: 1.01x faster                                               |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                        |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 79.5 ms                                                               | 78.4 ms: 1.01x faster                                               |
| pidigits       | 187 ms                                                                | 188 ms: 1.00x slower                                                |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                        |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_v8       | 24.3 ms                                                               | 24.0 ms: 1.01x faster                                               |
| regex_compile  | 134 ms                                                                | 133 ms: 1.01x faster                                                |
| regex_dna      | 212 ms                                                                | 212 ms: 1.00x slower                                                |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                        |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_dict          | 33.3 us                                                               | 31.9 us: 1.04x faster                                               |
| unpickle             | 14.9 us                                                               | 14.3 us: 1.04x faster                                               |
| xml_etree_generate   | 86.5 ms                                                               | 84.3 ms: 1.03x faster                                               |
| xml_etree_process    | 59.2 ms                                                               | 57.7 ms: 1.03x faster                                               |
| pickle               | 10.8 us                                                               | 10.6 us: 1.02x faster                                               |
| xml_etree_parse      | 155 ms                                                                | 152 ms: 1.02x faster                                                |
| unpickle_pure_python | 214 us                                                                | 211 us: 1.01x faster                                                |
| json_dumps           | 9.88 ms                                                               | 9.76 ms: 1.01x faster                                               |
| json_loads           | 25.2 us                                                               | 25.4 us: 1.01x slower                                               |
| tomli_loads          | 2.06 sec                                                              | 2.09 sec: 1.02x slower                                              |
| unpickle_list        | 4.77 us                                                               | 4.96 us: 1.04x slower                                               |
| pickle_list          | 4.59 us                                                               | 4.78 us: 1.04x slower                                               |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                        |

Benchmark hidden because not significant (2): xml_etree_iterparse, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup_no_site | 6.87 ms                                                               | 6.86 ms: 1.00x faster                                               |
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.00x slower                                               |
| Geometric mean         | (ref)                                                                 | 1.00x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.9 ms                                                               | 10.6 ms: 1.03x faster                                               |

All benchmarks:
===============

| Benchmark               | bm-20230926-linux-x86_64-python-fbfec5642edd9d7690bb-3.13.0a0-fbfec56 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|-------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| gc_traversal            | 3.98 ms                                                               | 3.56 ms: 1.12x faster                                               |
| pickle_dict             | 33.3 us                                                               | 31.9 us: 1.04x faster                                               |
| pycparser               | 1.19 sec                                                              | 1.15 sec: 1.04x faster                                              |
| logging_format          | 6.77 us                                                               | 6.52 us: 1.04x faster                                               |
| generators              | 29.9 ms                                                               | 28.8 ms: 1.04x faster                                               |
| unpickle                | 14.9 us                                                               | 14.3 us: 1.04x faster                                               |
| json                    | 4.98 ms                                                               | 4.85 ms: 1.03x faster                                               |
| xml_etree_generate      | 86.5 ms                                                               | 84.3 ms: 1.03x faster                                               |
| mako                    | 10.9 ms                                                               | 10.6 ms: 1.03x faster                                               |
| logging_simple          | 6.12 us                                                               | 5.96 us: 1.03x faster                                               |
| xml_etree_process       | 59.2 ms                                                               | 57.7 ms: 1.03x faster                                               |
| create_gc_cycles        | 1.54 ms                                                               | 1.51 ms: 1.02x faster                                               |
| deepcopy_memo           | 37.3 us                                                               | 36.4 us: 1.02x faster                                               |
| pickle                  | 10.8 us                                                               | 10.6 us: 1.02x faster                                               |
| crypto_pyaes            | 70.1 ms                                                               | 68.6 ms: 1.02x faster                                               |
| coroutines              | 22.4 ms                                                               | 22.0 ms: 1.02x faster                                               |
| scimark_lu              | 111 ms                                                                | 109 ms: 1.02x faster                                                |
| xml_etree_parse         | 155 ms                                                                | 152 ms: 1.02x faster                                                |
| async_generators        | 451 ms                                                                | 444 ms: 1.02x faster                                                |
| unpickle_pure_python    | 214 us                                                                | 211 us: 1.01x faster                                                |
| float                   | 79.5 ms                                                               | 78.4 ms: 1.01x faster                                               |
| sqlglot_normalize       | 106 ms                                                                | 105 ms: 1.01x faster                                                |
| json_dumps              | 9.88 ms                                                               | 9.76 ms: 1.01x faster                                               |
| regex_v8                | 24.3 ms                                                               | 24.0 ms: 1.01x faster                                               |
| logging_silent          | 102 ns                                                                | 101 ns: 1.01x faster                                                |
| sqlglot_optimize        | 53.2 ms                                                               | 52.6 ms: 1.01x faster                                               |
| spectral_norm           | 106 ms                                                                | 105 ms: 1.01x faster                                                |
| coverage                | 85.7 ms                                                               | 84.8 ms: 1.01x faster                                               |
| meteor_contest          | 107 ms                                                                | 106 ms: 1.01x faster                                                |
| sqlglot_parse           | 1.27 ms                                                               | 1.26 ms: 1.01x faster                                               |
| regex_compile           | 134 ms                                                                | 133 ms: 1.01x faster                                                |
| tornado_http            | 95.7 ms                                                               | 95.1 ms: 1.01x faster                                               |
| mypy2                   | 338 ms                                                                | 336 ms: 1.01x faster                                                |
| sqlglot_transpile       | 1.59 ms                                                               | 1.58 ms: 1.01x faster                                               |
| fannkuch                | 388 ms                                                                | 387 ms: 1.00x faster                                                |
| asyncio_tcp             | 507 ms                                                                | 505 ms: 1.00x faster                                                |
| deepcopy                | 352 us                                                                | 351 us: 1.00x faster                                                |
| python_startup_no_site  | 6.87 ms                                                               | 6.86 ms: 1.00x faster                                               |
| python_startup          | 10.1 ms                                                               | 10.1 ms: 1.00x slower                                               |
| regex_dna               | 212 ms                                                                | 212 ms: 1.00x slower                                                |
| asyncio_tcp_ssl         | 1.80 sec                                                              | 1.80 sec: 1.00x slower                                              |
| bench_thread_pool       | 808 us                                                                | 810 us: 1.00x slower                                                |
| hexiom                  | 6.00 ms                                                               | 6.02 ms: 1.00x slower                                               |
| pyflate                 | 456 ms                                                                | 457 ms: 1.00x slower                                                |
| pprint_pformat          | 1.48 sec                                                              | 1.48 sec: 1.00x slower                                              |
| pidigits                | 187 ms                                                                | 188 ms: 1.00x slower                                                |
| pprint_safe_repr        | 724 ms                                                                | 727 ms: 1.00x slower                                                |
| raytrace                | 266 ms                                                                | 268 ms: 1.01x slower                                                |
| nqueens                 | 78.4 ms                                                               | 78.9 ms: 1.01x slower                                               |
| json_loads              | 25.2 us                                                               | 25.4 us: 1.01x slower                                               |
| scimark_monte_carlo     | 65.6 ms                                                               | 66.2 ms: 1.01x slower                                               |
| telco                   | 7.99 ms                                                               | 8.06 ms: 1.01x slower                                               |
| mdp                     | 2.64 sec                                                              | 2.67 sec: 1.01x slower                                              |
| tomli_loads             | 2.06 sec                                                              | 2.09 sec: 1.02x slower                                              |
| go                      | 139 ms                                                                | 141 ms: 1.02x slower                                                |
| comprehensions          | 20.3 us                                                               | 20.7 us: 1.02x slower                                               |
| scimark_sparse_mat_mult | 4.51 ms                                                               | 4.67 ms: 1.03x slower                                               |
| unpickle_list           | 4.77 us                                                               | 4.96 us: 1.04x slower                                               |
| pickle_list             | 4.59 us                                                               | 4.78 us: 1.04x slower                                               |
| unpack_sequence         | 45.5 ns                                                               | 48.2 ns: 1.06x slower                                               |
| scimark_sor             | 118 ms                                                                | 129 ms: 1.10x slower                                                |
| Geometric mean          | (ref)                                                                 | 1.00x faster                                                        |

Benchmark hidden because not significant (21): async_tree_cpu_io_mixed, richards, pathlib, dulwich_log, dask, xml_etree_iterparse, async_tree_io, bench_mp_pool, docutils, regex_effbot, deltablue, nbody, sqlite_synth, scimark_fft, chaos, typing_runtime_protocols, pickle_pure_python, richards_super, async_tree_memoization, deepcopy_reduce, async_tree_none


# HPT report

- Reliability score: 88.93% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
