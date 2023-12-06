
# Results vs. base

- fork: python
- ref: 8deb8bc2e5af0e229df8
- machine: darwin-arm64
- commit hash: 8deb8bc
- commit date: 2023-11-20
- overall geometric mean: 1.00x faster
- HPT reliability: 74.44%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 174 ms                                                                 | 174 ms: 1.00x faster                                                   |
| chameleon      | 4.86 ms                                                                | 4.83 ms: 1.01x faster                                                  |
| docutils       | 1.50 sec                                                               | 1.49 sec: 1.00x faster                                                 |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none_tg | 269 ms                                                                 | 268 ms: 1.00x faster                                                   |
| async_tree_io_tg   | 688 ms                                                                 | 686 ms: 1.00x faster                                                   |
| Geometric mean     | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (6): async_tree_memoization, async_tree_none, async_tree_io, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| pidigits       | 281 ms                                                                 | 282 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (2): nbody, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|----------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_effbot   | 2.56 ms                                                                | 2.57 ms: 1.00x slower                                                  |
| regex_compile  | 78.4 ms                                                                | 78.7 ms: 1.00x slower                                                  |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (2): regex_v8, regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark           | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|---------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| xml_etree_parse     | 108 ms                                                                 | 107 ms: 1.01x faster                                                   |
| xml_etree_process   | 40.5 ms                                                                | 40.2 ms: 1.01x faster                                                  |
| xml_etree_iterparse | 76.6 ms                                                                | 76.2 ms: 1.01x faster                                                  |
| pickle_list         | 2.91 us                                                                | 2.90 us: 1.00x faster                                                  |
| pickle_pure_python  | 204 us                                                                 | 203 us: 1.00x faster                                                   |
| json_dumps          | 6.55 ms                                                                | 6.56 ms: 1.00x slower                                                  |
| json_loads          | 17.3 us                                                                | 17.4 us: 1.01x slower                                                  |
| xml_etree_generate  | 57.9 ms                                                                | 58.4 ms: 1.01x slower                                                  |
| unpickle            | 9.04 us                                                                | 9.19 us: 1.02x slower                                                  |
| Geometric mean      | (ref)                                                                  | 1.00x slower                                                           |

Benchmark hidden because not significant (5): tomli_loads, unpickle_pure_python, pickle, pickle_dict, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site | 10.7 ms                                                                | 10.3 ms: 1.04x faster                                                  |
| python_startup         | 12.0 ms                                                                | 11.6 ms: 1.03x faster                                                  |
| Geometric mean         | (ref)                                                                  | 1.04x faster                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|-----------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 7.76 ms                                                                | 7.78 ms: 1.00x slower                                                  |

All benchmarks:
===============

| Benchmark                | bm-20231120-darwin-arm64-python-c4c63211e83aa50927f3-3.13.0a1+-c4c6321 | bm-20231120-darwin-arm64-python-8deb8bc2e5af0e229df8-3.13.0a1+-8deb8bc |
|--------------------------|:----------------------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup_no_site   | 10.7 ms                                                                | 10.3 ms: 1.04x faster                                                  |
| python_startup           | 12.0 ms                                                                | 11.6 ms: 1.03x faster                                                  |
| pathlib                  | 24.0 ms                                                                | 23.6 ms: 1.02x faster                                                  |
| create_gc_cycles         | 711 us                                                                 | 701 us: 1.01x faster                                                   |
| xml_etree_parse          | 108 ms                                                                 | 107 ms: 1.01x faster                                                   |
| bench_mp_pool            | 44.0 ms                                                                | 43.6 ms: 1.01x faster                                                  |
| xml_etree_process        | 40.5 ms                                                                | 40.2 ms: 1.01x faster                                                  |
| fannkuch                 | 289 ms                                                                 | 287 ms: 1.01x faster                                                   |
| richards                 | 34.7 ms                                                                | 34.5 ms: 1.01x faster                                                  |
| xml_etree_iterparse      | 76.6 ms                                                                | 76.2 ms: 1.01x faster                                                  |
| spectral_norm            | 75.4 ms                                                                | 75.0 ms: 1.01x faster                                                  |
| chameleon                | 4.86 ms                                                                | 4.83 ms: 1.01x faster                                                  |
| async_generators         | 306 ms                                                                 | 304 ms: 1.01x faster                                                   |
| richards_super           | 38.6 ms                                                                | 38.4 ms: 1.01x faster                                                  |
| gc_traversal             | 2.40 ms                                                                | 2.39 ms: 1.01x faster                                                  |
| telco                    | 4.66 ms                                                                | 4.64 ms: 1.00x faster                                                  |
| async_tree_none_tg       | 269 ms                                                                 | 268 ms: 1.00x faster                                                   |
| pickle_list              | 2.91 us                                                                | 2.90 us: 1.00x faster                                                  |
| docutils                 | 1.50 sec                                                               | 1.49 sec: 1.00x faster                                                 |
| deepcopy                 | 231 us                                                                 | 230 us: 1.00x faster                                                   |
| async_tree_io_tg         | 688 ms                                                                 | 686 ms: 1.00x faster                                                   |
| pickle_pure_python       | 204 us                                                                 | 203 us: 1.00x faster                                                   |
| deepcopy_memo            | 25.3 us                                                                | 25.2 us: 1.00x faster                                                  |
| raytrace                 | 189 ms                                                                 | 189 ms: 1.00x faster                                                   |
| scimark_fft              | 208 ms                                                                 | 208 ms: 1.00x faster                                                   |
| 2to3                     | 174 ms                                                                 | 174 ms: 1.00x faster                                                   |
| pidigits                 | 281 ms                                                                 | 282 ms: 1.00x slower                                                   |
| go                       | 107 ms                                                                 | 107 ms: 1.00x slower                                                   |
| hexiom                   | 4.95 ms                                                                | 4.96 ms: 1.00x slower                                                  |
| dulwich_log              | 30.0 ms                                                                | 30.0 ms: 1.00x slower                                                  |
| mako                     | 7.76 ms                                                                | 7.78 ms: 1.00x slower                                                  |
| json_dumps               | 6.55 ms                                                                | 6.56 ms: 1.00x slower                                                  |
| regex_effbot             | 2.56 ms                                                                | 2.57 ms: 1.00x slower                                                  |
| logging_format           | 3.93 us                                                                | 3.94 us: 1.00x slower                                                  |
| regex_compile            | 78.4 ms                                                                | 78.7 ms: 1.00x slower                                                  |
| sympy_integrate          | 11.1 ms                                                                | 11.1 ms: 1.00x slower                                                  |
| sqlglot_optimize         | 35.3 ms                                                                | 35.4 ms: 1.00x slower                                                  |
| pprint_safe_repr         | 522 ms                                                                 | 524 ms: 1.00x slower                                                   |
| deepcopy_reduce          | 2.04 us                                                                | 2.05 us: 1.00x slower                                                  |
| sqlglot_normalize        | 190 ms                                                                 | 191 ms: 1.00x slower                                                   |
| chaos                    | 43.5 ms                                                                | 43.7 ms: 1.00x slower                                                  |
| comprehensions           | 12.5 us                                                                | 12.6 us: 1.00x slower                                                  |
| crypto_pyaes             | 49.4 ms                                                                | 49.7 ms: 1.00x slower                                                  |
| logging_simple           | 3.61 us                                                                | 3.63 us: 1.01x slower                                                  |
| json_loads               | 17.3 us                                                                | 17.4 us: 1.01x slower                                                  |
| nqueens                  | 60.2 ms                                                                | 60.6 ms: 1.01x slower                                                  |
| sympy_expand             | 254 ms                                                                 | 255 ms: 1.01x slower                                                   |
| typing_runtime_protocols | 75.9 us                                                                | 76.4 us: 1.01x slower                                                  |
| sympy_str                | 146 ms                                                                 | 147 ms: 1.01x slower                                                   |
| sqlite_synth             | 1.64 us                                                                | 1.65 us: 1.01x slower                                                  |
| json                     | 3.00 ms                                                                | 3.03 ms: 1.01x slower                                                  |
| xml_etree_generate       | 57.9 ms                                                                | 58.4 ms: 1.01x slower                                                  |
| scimark_lu               | 74.8 ms                                                                | 75.9 ms: 1.02x slower                                                  |
| unpickle                 | 9.04 us                                                                | 9.19 us: 1.02x slower                                                  |
| coverage                 | 47.4 ms                                                                | 48.4 ms: 1.02x slower                                                  |
| Geometric mean           | (ref)                                                                  | 1.00x faster                                                           |

Benchmark hidden because not significant (38): asyncio_tcp, tornado_http, mdp, async_tree_memoization, dask, async_tree_none, async_tree_io, logging_silent, sympy_sum, generators, bench_thread_pool, tomli_loads, nbody, mypy2, float, deltablue, unpickle_pure_python, regex_v8, meteor_contest, scimark_monte_carlo, async_tree_cpu_io_mixed_tg, pyflate, pycparser, async_tree_memoization_tg, scimark_sparse_mat_mult, scimark_sor, pickle, sqlglot_parse, async_tree_cpu_io_mixed, regex_dna, asyncio_websockets, pprint_pformat, pickle_dict, unpickle_list, sqlglot_transpile, asyncio_tcp_ssl, unpack_sequence, coroutines


# HPT report

- Reliability score: 74.44% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
