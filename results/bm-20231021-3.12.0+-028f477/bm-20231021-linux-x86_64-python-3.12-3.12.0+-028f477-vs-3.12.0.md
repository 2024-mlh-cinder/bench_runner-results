
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 268 ms                                                 | 275 ms: 1.03x slower                                 |
| docutils       | 2.70 sec                                               | 2.73 sec: 1.01x slower                               |
| Geometric mean | (ref)                                                  | 1.01x slower                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 187 ms                                                 | 187 ms: 1.00x slower                                 |
| float          | 80.7 ms                                                | 83.7 ms: 1.04x slower                                |
| nbody          | 88.8 ms                                                | 95.1 ms: 1.07x slower                                |
| Geometric mean | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_effbot   | 3.55 ms                                                | 3.63 ms: 1.02x slower                                |
| regex_compile  | 144 ms                                                 | 147 ms: 1.02x slower                                 |
| regex_v8       | 22.3 ms                                                | 23.0 ms: 1.03x slower                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                         |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| xml_etree_iterparse  | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| xml_etree_parse      | 154 ms                                                 | 159 ms: 1.04x slower                                 |
| tomli_loads          | 2.22 sec                                               | 2.30 sec: 1.04x slower                               |
| unpickle_pure_python | 218 us                                                 | 228 us: 1.05x slower                                 |
| xml_etree_generate   | 84.8 ms                                                | 88.7 ms: 1.05x slower                                |
| pickle_pure_python   | 309 us                                                 | 324 us: 1.05x slower                                 |
| unpickle_list        | 4.95 us                                                | 5.20 us: 1.05x slower                                |
| xml_etree_process    | 58.6 ms                                                | 62.2 ms: 1.06x slower                                |
| json_dumps           | 9.85 ms                                                | 10.5 ms: 1.06x slower                                |
| unpickle             | 15.0 us                                                | 16.0 us: 1.07x slower                                |
| pickle               | 10.6 us                                                | 11.6 us: 1.10x slower                                |
| pickle_list          | 4.62 us                                                | 5.16 us: 1.12x slower                                |
| pickle_dict          | 31.6 us                                                | 35.4 us: 1.12x slower                                |
| json_loads           | 25.2 us                                                | 28.7 us: 1.14x slower                                |
| Geometric mean       | (ref)                                                  | 1.07x slower                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 6.90 ms                                                | 6.93 ms: 1.01x slower                                |
| python_startup         | 9.47 ms                                                | 9.57 ms: 1.01x slower                                |
| Geometric mean         | (ref)                                                  | 1.01x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.7 ms                                                | 11.3 ms: 1.05x slower                                |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231021-linux-x86_64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| gc_traversal             | 3.84 ms                                                | 3.55 ms: 1.08x faster                                |
| create_gc_cycles         | 1.52 ms                                                | 1.46 ms: 1.05x faster                                |
| asyncio_tcp              | 526 ms                                                 | 512 ms: 1.03x faster                                 |
| asyncio_tcp_ssl          | 1.79 sec                                               | 1.78 sec: 1.01x faster                               |
| generators               | 31.1 ms                                                | 30.9 ms: 1.00x faster                                |
| pidigits                 | 187 ms                                                 | 187 ms: 1.00x slower                                 |
| pathlib                  | 18.5 ms                                                | 18.6 ms: 1.01x slower                                |
| python_startup_no_site   | 6.90 ms                                                | 6.93 ms: 1.01x slower                                |
| async_tree_io            | 1.16 sec                                               | 1.16 sec: 1.01x slower                               |
| dulwich_log              | 67.9 ms                                                | 68.5 ms: 1.01x slower                                |
| docutils                 | 2.70 sec                                               | 2.73 sec: 1.01x slower                               |
| python_startup           | 9.47 ms                                                | 9.57 ms: 1.01x slower                                |
| sqlalchemy_imperative    | 18.4 ms                                                | 18.6 ms: 1.01x slower                                |
| bench_thread_pool        | 827 us                                                 | 837 us: 1.01x slower                                 |
| pyflate                  | 450 ms                                                 | 456 ms: 1.01x slower                                 |
| sqlalchemy_declarative   | 144 ms                                                 | 146 ms: 1.01x slower                                 |
| async_tree_cpu_io_mixed  | 714 ms                                                 | 725 ms: 1.02x slower                                 |
| regex_effbot             | 3.55 ms                                                | 3.63 ms: 1.02x slower                                |
| richards_super           | 49.0 ms                                                | 50.1 ms: 1.02x slower                                |
| richards                 | 43.2 ms                                                | 44.2 ms: 1.02x slower                                |
| unpack_sequence          | 44.8 ns                                                | 46.0 ns: 1.02x slower                                |
| regex_compile            | 144 ms                                                 | 147 ms: 1.02x slower                                 |
| 2to3                     | 268 ms                                                 | 275 ms: 1.03x slower                                 |
| regex_v8                 | 22.3 ms                                                | 23.0 ms: 1.03x slower                                |
| xml_etree_iterparse      | 104 ms                                                 | 107 ms: 1.03x slower                                 |
| go                       | 136 ms                                                 | 140 ms: 1.03x slower                                 |
| logging_format           | 6.90 us                                                | 7.11 us: 1.03x slower                                |
| sqlglot_transpile        | 1.64 ms                                                | 1.69 ms: 1.03x slower                                |
| sqlglot_parse            | 1.32 ms                                                | 1.36 ms: 1.03x slower                                |
| scimark_lu               | 114 ms                                                 | 118 ms: 1.03x slower                                 |
| deepcopy_reduce          | 3.14 us                                                | 3.24 us: 1.03x slower                                |
| sqlglot_normalize        | 107 ms                                                 | 111 ms: 1.03x slower                                 |
| sqlite_synth             | 2.76 us                                                | 2.85 us: 1.03x slower                                |
| sqlglot_optimize         | 53.3 ms                                                | 55.1 ms: 1.03x slower                                |
| deepcopy                 | 355 us                                                 | 368 us: 1.03x slower                                 |
| scimark_sor              | 125 ms                                                 | 129 ms: 1.04x slower                                 |
| deltablue                | 3.52 ms                                                | 3.64 ms: 1.04x slower                                |
| float                    | 80.7 ms                                                | 83.7 ms: 1.04x slower                                |
| pprint_pformat           | 1.50 sec                                               | 1.56 sec: 1.04x slower                               |
| chaos                    | 63.5 ms                                                | 65.9 ms: 1.04x slower                                |
| crypto_pyaes             | 77.2 ms                                                | 80.1 ms: 1.04x slower                                |
| xml_etree_parse          | 154 ms                                                 | 159 ms: 1.04x slower                                 |
| nqueens                  | 81.1 ms                                                | 84.2 ms: 1.04x slower                                |
| coverage                 | 94.2 ms                                                | 97.8 ms: 1.04x slower                                |
| pprint_safe_repr         | 735 ms                                                 | 763 ms: 1.04x slower                                 |
| tomli_loads              | 2.22 sec                                               | 2.30 sec: 1.04x slower                               |
| raytrace                 | 294 ms                                                 | 306 ms: 1.04x slower                                 |
| coroutines               | 22.4 ms                                                | 23.4 ms: 1.04x slower                                |
| unpickle_pure_python     | 218 us                                                 | 228 us: 1.05x slower                                 |
| logging_simple           | 6.18 us                                                | 6.46 us: 1.05x slower                                |
| scimark_monte_carlo      | 71.0 ms                                                | 74.3 ms: 1.05x slower                                |
| xml_etree_generate       | 84.8 ms                                                | 88.7 ms: 1.05x slower                                |
| pickle_pure_python       | 309 us                                                 | 324 us: 1.05x slower                                 |
| unpickle_list            | 4.95 us                                                | 5.20 us: 1.05x slower                                |
| pycparser                | 1.15 sec                                               | 1.21 sec: 1.05x slower                               |
| telco                    | 6.87 ms                                                | 7.23 ms: 1.05x slower                                |
| mako                     | 10.7 ms                                                | 11.3 ms: 1.05x slower                                |
| meteor_contest           | 105 ms                                                 | 110 ms: 1.05x slower                                 |
| async_generators         | 440 ms                                                 | 465 ms: 1.06x slower                                 |
| fannkuch                 | 387 ms                                                 | 409 ms: 1.06x slower                                 |
| comprehensions           | 20.4 us                                                | 21.6 us: 1.06x slower                                |
| hexiom                   | 6.12 ms                                                | 6.48 ms: 1.06x slower                                |
| logging_silent           | 99.1 ns                                                | 105 ns: 1.06x slower                                 |
| xml_etree_process        | 58.6 ms                                                | 62.2 ms: 1.06x slower                                |
| json_dumps               | 9.85 ms                                                | 10.5 ms: 1.06x slower                                |
| deepcopy_memo            | 37.4 us                                                | 39.9 us: 1.07x slower                                |
| typing_runtime_protocols | 146 us                                                 | 156 us: 1.07x slower                                 |
| unpickle                 | 15.0 us                                                | 16.0 us: 1.07x slower                                |
| spectral_norm            | 106 ms                                                 | 114 ms: 1.07x slower                                 |
| nbody                    | 88.8 ms                                                | 95.1 ms: 1.07x slower                                |
| scimark_fft              | 358 ms                                                 | 384 ms: 1.07x slower                                 |
| mdp                      | 2.57 sec                                               | 2.75 sec: 1.07x slower                               |
| json                     | 4.77 ms                                                | 5.23 ms: 1.10x slower                                |
| pickle                   | 10.6 us                                                | 11.6 us: 1.10x slower                                |
| pickle_list              | 4.62 us                                                | 5.16 us: 1.12x slower                                |
| pickle_dict              | 31.6 us                                                | 35.4 us: 1.12x slower                                |
| scimark_sparse_mat_mult  | 4.74 ms                                                | 5.40 ms: 1.14x slower                                |
| json_loads               | 25.2 us                                                | 28.7 us: 1.14x slower                                |
| mypy2                    | 344 ms                                                 | 466 ms: 1.35x slower                                 |
| Geometric mean           | (ref)                                                  | 1.04x slower                                         |

Benchmark hidden because not significant (6): bench_mp_pool, regex_dna, tornado_http, async_tree_memoization, async_tree_none, dask


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.02x
