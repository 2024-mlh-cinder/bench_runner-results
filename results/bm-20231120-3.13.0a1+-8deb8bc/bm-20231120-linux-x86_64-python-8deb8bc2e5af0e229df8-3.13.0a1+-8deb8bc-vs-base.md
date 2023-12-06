
# Results vs. base

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: linux-x86_64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.00x faster
- HPT reliability: 99.64%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| chameleon      | 6.97 ms                                                                | 7.02 ms: 1.01x slower                                                  |
| docutils       | 2.60 sec                                                               | 2.61 sec: 1.00x slower                                                 |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (2): 2to3, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none_tg | 455 ms                                                                 | 457 ms: 1.01x slower                                                   |
| async_tree_io      | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                                 |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (6): async_tree_io_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 81.2 ms                                                                | 82.1 ms: 1.01x slower                                                  |
| pidigits       | 187 ms                                                                 | 195 ms: 1.04x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                           |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_v8       | 25.6 ms                                                                | 25.5 ms: 1.00x faster                                                  |
| regex_dna      | 215 ms                                                                 | 217 ms: 1.01x slower                                                   |
| regex_effbot   | 3.54 ms                                                                | 3.72 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                           |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict        | 35.9 us                                                                | 32.4 us: 1.11x faster                                                  |
| pickle_list        | 5.28 us                                                                | 4.92 us: 1.07x faster                                                  |
| pickle             | 11.6 us                                                                | 11.0 us: 1.06x faster                                                  |
| unpickle           | 14.6 us                                                                | 14.3 us: 1.02x faster                                                  |
| unpickle_list      | 5.14 us                                                                | 5.10 us: 1.01x faster                                                  |
| xml_etree_generate | 86.3 ms                                                                | 86.7 ms: 1.00x slower                                                  |
| pickle_pure_python | 302 us                                                                 | 304 us: 1.01x slower                                                   |
| json_dumps         | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                                  |
| xml_etree_process  | 59.0 ms                                                                | 59.5 ms: 1.01x slower                                                  |
| tomli_loads        | 2.13 sec                                                               | 2.17 sec: 1.02x slower                                                 |
| Geometric mean     | (ref)                                                                  | 1.02x faster                                                           |

Benchmark hidden because not significant (4): unpickle_pure_python, xml_etree_iterparse, json_loads, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 8.93 ms                                                                | 8.97 ms: 1.00x slower                                                  |
| python_startup         | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                                  |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 11.6 ms: 1.02x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231120-linux-x86_64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-linux-x86_64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_dict              | 35.9 us                                                                | 32.4 us: 1.11x faster                                                  |
| unpack_sequence          | 51.2 ns                                                                | 46.3 ns: 1.11x faster                                                  |
| scimark_sparse_mat_mult  | 5.02 ms                                                                | 4.63 ms: 1.08x faster                                                  |
| gc_traversal             | 3.79 ms                                                                | 3.51 ms: 1.08x faster                                                  |
| pickle_list              | 5.28 us                                                                | 4.92 us: 1.07x faster                                                  |
| pickle                   | 11.6 us                                                                | 11.0 us: 1.06x faster                                                  |
| scimark_lu               | 117 ms                                                                 | 114 ms: 1.03x faster                                                   |
| pycparser                | 1.21 sec                                                               | 1.17 sec: 1.03x faster                                                 |
| scimark_fft              | 373 ms                                                                 | 364 ms: 1.03x faster                                                   |
| scimark_monte_carlo      | 69.4 ms                                                                | 67.9 ms: 1.02x faster                                                  |
| unpickle                 | 14.6 us                                                                | 14.3 us: 1.02x faster                                                  |
| coroutines               | 22.4 ms                                                                | 22.0 ms: 1.02x faster                                                  |
| chaos                    | 61.7 ms                                                                | 60.9 ms: 1.01x faster                                                  |
| create_gc_cycles         | 1.48 ms                                                                | 1.46 ms: 1.01x faster                                                  |
| go                       | 144 ms                                                                 | 142 ms: 1.01x faster                                                   |
| deepcopy_memo            | 38.9 us                                                                | 38.5 us: 1.01x faster                                                  |
| coverage                 | 95.7 ms                                                                | 94.8 ms: 1.01x faster                                                  |
| unpickle_list            | 5.14 us                                                                | 5.10 us: 1.01x faster                                                  |
| deltablue                | 3.36 ms                                                                | 3.33 ms: 1.01x faster                                                  |
| hexiom                   | 6.28 ms                                                                | 6.23 ms: 1.01x faster                                                  |
| json                     | 5.16 ms                                                                | 5.12 ms: 1.01x faster                                                  |
| scimark_sor              | 124 ms                                                                 | 123 ms: 1.01x faster                                                   |
| deepcopy_reduce          | 3.07 us                                                                | 3.05 us: 1.00x faster                                                  |
| regex_v8                 | 25.6 ms                                                                | 25.5 ms: 1.00x faster                                                  |
| raytrace                 | 276 ms                                                                 | 275 ms: 1.00x faster                                                   |
| generators               | 29.6 ms                                                                | 29.7 ms: 1.00x slower                                                  |
| docutils                 | 2.60 sec                                                               | 2.61 sec: 1.00x slower                                                 |
| python_startup_no_site   | 8.93 ms                                                                | 8.97 ms: 1.00x slower                                                  |
| python_startup           | 10.3 ms                                                                | 10.3 ms: 1.00x slower                                                  |
| xml_etree_generate       | 86.3 ms                                                                | 86.7 ms: 1.00x slower                                                  |
| pyflate                  | 467 ms                                                                 | 469 ms: 1.00x slower                                                   |
| mypy2                    | 341 ms                                                                 | 343 ms: 1.01x slower                                                   |
| pickle_pure_python       | 302 us                                                                 | 304 us: 1.01x slower                                                   |
| sympy_integrate          | 19.4 ms                                                                | 19.5 ms: 1.01x slower                                                  |
| sympy_sum                | 147 ms                                                                 | 148 ms: 1.01x slower                                                   |
| async_tree_none_tg       | 455 ms                                                                 | 457 ms: 1.01x slower                                                   |
| chameleon                | 6.97 ms                                                                | 7.02 ms: 1.01x slower                                                  |
| pprint_safe_repr         | 735 ms                                                                 | 740 ms: 1.01x slower                                                   |
| async_tree_io            | 1.19 sec                                                               | 1.20 sec: 1.01x slower                                                 |
| json_dumps               | 10.4 ms                                                                | 10.5 ms: 1.01x slower                                                  |
| richards_super           | 54.2 ms                                                                | 54.6 ms: 1.01x slower                                                  |
| xml_etree_process        | 59.0 ms                                                                | 59.5 ms: 1.01x slower                                                  |
| sqlglot_optimize         | 53.2 ms                                                                | 53.7 ms: 1.01x slower                                                  |
| async_generators         | 444 ms                                                                 | 448 ms: 1.01x slower                                                   |
| pathlib                  | 18.1 ms                                                                | 18.3 ms: 1.01x slower                                                  |
| pprint_pformat           | 1.49 sec                                                               | 1.51 sec: 1.01x slower                                                 |
| crypto_pyaes             | 71.7 ms                                                                | 72.3 ms: 1.01x slower                                                  |
| sqlglot_parse            | 1.27 ms                                                                | 1.28 ms: 1.01x slower                                                  |
| sqlglot_transpile        | 1.58 ms                                                                | 1.59 ms: 1.01x slower                                                  |
| sqlite_synth             | 2.81 us                                                                | 2.84 us: 1.01x slower                                                  |
| regex_dna                | 215 ms                                                                 | 217 ms: 1.01x slower                                                   |
| sympy_expand             | 450 ms                                                                 | 455 ms: 1.01x slower                                                   |
| nqueens                  | 81.2 ms                                                                | 82.1 ms: 1.01x slower                                                  |
| float                    | 81.2 ms                                                                | 82.1 ms: 1.01x slower                                                  |
| comprehensions           | 16.4 us                                                                | 16.7 us: 1.01x slower                                                  |
| typing_runtime_protocols | 117 us                                                                 | 119 us: 1.01x slower                                                   |
| tomli_loads              | 2.13 sec                                                               | 2.17 sec: 1.02x slower                                                 |
| logging_format           | 6.20 us                                                                | 6.31 us: 1.02x slower                                                  |
| logging_silent           | 108 ns                                                                 | 110 ns: 1.02x slower                                                   |
| mako                     | 11.4 ms                                                                | 11.6 ms: 1.02x slower                                                  |
| meteor_contest           | 107 ms                                                                 | 109 ms: 1.02x slower                                                   |
| logging_simple           | 5.63 us                                                                | 5.77 us: 1.02x slower                                                  |
| pidigits                 | 187 ms                                                                 | 195 ms: 1.04x slower                                                   |
| regex_effbot             | 3.54 ms                                                                | 3.72 ms: 1.05x slower                                                  |
| mdp                      | 2.57 sec                                                               | 2.74 sec: 1.07x slower                                                 |
| Geometric mean           | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (28): tornado_http, telco, dask, nbody, unpickle_pure_python, xml_etree_iterparse, dulwich_log, bench_thread_pool, 2to3, sqlglot_normalize, asyncio_tcp, asyncio_websockets, bench_mp_pool, asyncio_tcp_ssl, richards, regex_compile, json_loads, deepcopy, async_tree_io_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, fannkuch, async_tree_memoization_tg, xml_etree_parse, async_tree_none, spectral_norm, sympy_str


# HPT report

- Reliability score: 99.64% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
