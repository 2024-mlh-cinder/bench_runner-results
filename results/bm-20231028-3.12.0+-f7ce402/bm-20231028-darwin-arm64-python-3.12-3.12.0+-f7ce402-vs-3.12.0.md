
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.02x faster
- HPT reliability: 99.53%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 171 ms                                                 | 168 ms: 1.01x faster                                 |
| chameleon      | 4.51 ms                                                | 4.53 ms: 1.00x slower                                |
| docutils       | 1.54 sec                                               | 1.51 sec: 1.02x faster                               |
| Geometric mean | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|--------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_io_tg   | 673 ms                                                 | 665 ms: 1.01x faster                                 |
| async_tree_io      | 669 ms                                                 | 662 ms: 1.01x faster                                 |
| async_tree_none_tg | 254 ms                                                 | 255 ms: 1.00x slower                                 |
| async_tree_none    | 262 ms                                                 | 263 ms: 1.01x slower                                 |
| Geometric mean     | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (4): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization_tg, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| float          | 58.1 ms                                                | 56.6 ms: 1.03x faster                                |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| nbody          | 68.5 ms                                                | 69.1 ms: 1.01x slower                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                 |
| regex_compile  | 75.6 ms                                                | 75.2 ms: 1.00x faster                                |
| regex_effbot   | 2.59 ms                                                | 2.59 ms: 1.00x faster                                |
| regex_v8       | 15.7 ms                                                | 15.6 ms: 1.00x faster                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 6.46 ms                                                | 6.31 ms: 1.02x faster                                |
| pickle               | 7.42 us                                                | 7.33 us: 1.01x faster                                |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                |
| unpickle_pure_python | 145 us                                                 | 144 us: 1.00x faster                                 |
| pickle_pure_python   | 188 us                                                 | 189 us: 1.00x slower                                 |
| xml_etree_process    | 38.7 ms                                                | 38.8 ms: 1.00x slower                                |
| unpickle             | 9.25 us                                                | 9.33 us: 1.01x slower                                |
| Geometric mean       | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (7): xml_etree_parse, xml_etree_generate, unpickle_list, xml_etree_iterparse, json_loads, tomli_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 9.71 ms                                                | 9.88 ms: 1.02x slower                                |
| python_startup         | 11.9 ms                                                | 12.1 ms: 1.02x slower                                |
| Geometric mean         | (ref)                                                  | 1.02x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| django_template | 22.1 ms                                                | 21.3 ms: 1.04x faster                                |
| Geometric mean  | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mypy2                    | 260 ms                                                 | 190 ms: 1.36x faster                                 |
| raytrace                 | 246 ms                                                 | 207 ms: 1.18x faster                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 43.2 ms: 1.16x faster                                |
| go                       | 107 ms                                                 | 94.3 ms: 1.14x faster                                |
| scimark_sor              | 94.3 ms                                                | 86.7 ms: 1.09x faster                                |
| generators               | 28.3 ms                                                | 26.1 ms: 1.09x faster                                |
| sqlglot_parse            | 897 us                                                 | 827 us: 1.08x faster                                 |
| sqlglot_transpile        | 1.08 ms                                                | 1.00 ms: 1.08x faster                                |
| deltablue                | 2.58 ms                                                | 2.41 ms: 1.07x faster                                |
| chaos                    | 44.8 ms                                                | 42.1 ms: 1.06x faster                                |
| coroutines               | 18.1 ms                                                | 17.4 ms: 1.04x faster                                |
| django_template          | 22.1 ms                                                | 21.3 ms: 1.04x faster                                |
| comprehensions           | 15.8 us                                                | 15.2 us: 1.04x faster                                |
| pyflate                  | 329 ms                                                 | 317 ms: 1.04x faster                                 |
| logging_format           | 3.99 us                                                | 3.87 us: 1.03x faster                                |
| richards_super           | 34.9 ms                                                | 34.0 ms: 1.03x faster                                |
| regex_dna                | 153 ms                                                 | 149 ms: 1.03x faster                                 |
| logging_simple           | 3.69 us                                                | 3.60 us: 1.03x faster                                |
| float                    | 58.1 ms                                                | 56.6 ms: 1.03x faster                                |
| json_dumps               | 6.46 ms                                                | 6.31 ms: 1.02x faster                                |
| docutils                 | 1.54 sec                                               | 1.51 sec: 1.02x faster                               |
| richards                 | 31.1 ms                                                | 30.5 ms: 1.02x faster                                |
| bench_mp_pool            | 46.3 ms                                                | 45.4 ms: 1.02x faster                                |
| sqlglot_normalize        | 188 ms                                                 | 185 ms: 1.02x faster                                 |
| sqlglot_optimize         | 34.7 ms                                                | 34.2 ms: 1.02x faster                                |
| mdp                      | 1.66 sec                                               | 1.64 sec: 1.02x faster                               |
| nqueens                  | 60.2 ms                                                | 59.3 ms: 1.01x faster                                |
| 2to3                     | 171 ms                                                 | 168 ms: 1.01x faster                                 |
| async_tree_io_tg         | 673 ms                                                 | 665 ms: 1.01x faster                                 |
| bench_thread_pool        | 492 us                                                 | 486 us: 1.01x faster                                 |
| create_gc_cycles         | 704 us                                                 | 696 us: 1.01x faster                                 |
| pickle                   | 7.42 us                                                | 7.33 us: 1.01x faster                                |
| async_tree_io            | 669 ms                                                 | 662 ms: 1.01x faster                                 |
| coverage                 | 37.9 ms                                                | 37.6 ms: 1.01x faster                                |
| json                     | 3.02 ms                                                | 3.00 ms: 1.01x faster                                |
| pprint_pformat           | 1.00 sec                                               | 994 ms: 1.01x faster                                 |
| dulwich_log              | 30.4 ms                                                | 30.2 ms: 1.01x faster                                |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                |
| regex_compile            | 75.6 ms                                                | 75.2 ms: 1.00x faster                                |
| unpickle_pure_python     | 145 us                                                 | 144 us: 1.00x faster                                 |
| logging_silent           | 68.3 ns                                                | 68.1 ns: 1.00x faster                                |
| sqlalchemy_declarative   | 65.4 ms                                                | 65.1 ms: 1.00x faster                                |
| sympy_expand             | 249 ms                                                 | 248 ms: 1.00x faster                                 |
| pprint_safe_repr         | 491 ms                                                 | 490 ms: 1.00x faster                                 |
| regex_effbot             | 2.59 ms                                                | 2.59 ms: 1.00x faster                                |
| regex_v8                 | 15.7 ms                                                | 15.6 ms: 1.00x faster                                |
| fannkuch                 | 265 ms                                                 | 265 ms: 1.00x faster                                 |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| pickle_pure_python       | 188 us                                                 | 189 us: 1.00x slower                                 |
| sympy_integrate          | 11.3 ms                                                | 11.4 ms: 1.00x slower                                |
| xml_etree_process        | 38.7 ms                                                | 38.8 ms: 1.00x slower                                |
| async_generators         | 306 ms                                                 | 307 ms: 1.00x slower                                 |
| async_tree_none_tg       | 254 ms                                                 | 255 ms: 1.00x slower                                 |
| chameleon                | 4.51 ms                                                | 4.53 ms: 1.00x slower                                |
| typing_runtime_protocols | 90.8 us                                                | 91.2 us: 1.00x slower                                |
| async_tree_none          | 262 ms                                                 | 263 ms: 1.01x slower                                 |
| hexiom                   | 4.25 ms                                                | 4.28 ms: 1.01x slower                                |
| spectral_norm            | 74.6 ms                                                | 75.1 ms: 1.01x slower                                |
| nbody                    | 68.5 ms                                                | 69.1 ms: 1.01x slower                                |
| unpickle                 | 9.25 us                                                | 9.33 us: 1.01x slower                                |
| deepcopy                 | 225 us                                                 | 227 us: 1.01x slower                                 |
| telco                    | 3.79 ms                                                | 3.82 ms: 1.01x slower                                |
| scimark_lu               | 71.5 ms                                                | 72.2 ms: 1.01x slower                                |
| scimark_fft              | 198 ms                                                 | 201 ms: 1.01x slower                                 |
| deepcopy_memo            | 24.6 us                                                | 24.9 us: 1.01x slower                                |
| scimark_sparse_mat_mult  | 3.14 ms                                                | 3.19 ms: 1.01x slower                                |
| python_startup_no_site   | 9.71 ms                                                | 9.88 ms: 1.02x slower                                |
| python_startup           | 11.9 ms                                                | 12.1 ms: 1.02x slower                                |
| Geometric mean           | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (30): pathlib, xml_etree_parse, dask, unpack_sequence, sympy_sum, sympy_str, sqlalchemy_imperative, gc_traversal, sqlite_synth, aiohttp, meteor_contest, asyncio_websockets, async_tree_cpu_io_mixed_tg, xml_etree_generate, unpickle_list, xml_etree_iterparse, crypto_pyaes, mako, deepcopy_reduce, json_loads, asyncio_tcp_ssl, async_tree_cpu_io_mixed, tomli_loads, pycparser, pickle_list, async_tree_memoization_tg, async_tree_memoization, tornado_http, asyncio_tcp, gunicorn


# HPT report

- Reliability score: 99.53% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
