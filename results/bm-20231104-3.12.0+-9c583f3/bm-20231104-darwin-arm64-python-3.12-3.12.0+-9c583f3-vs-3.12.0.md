
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.97%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 171 ms                                                 | 170 ms: 1.01x faster                                 |
| chameleon      | 4.51 ms                                                | 4.56 ms: 1.01x slower                                |
| docutils       | 1.54 sec                                               | 1.50 sec: 1.03x faster                               |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|--------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_io_tg   | 673 ms                                                 | 665 ms: 1.01x faster                                 |
| async_tree_io      | 669 ms                                                 | 662 ms: 1.01x faster                                 |
| async_tree_none_tg | 254 ms                                                 | 255 ms: 1.00x slower                                 |
| Geometric mean     | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization_tg, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| float          | 58.1 ms                                                | 56.7 ms: 1.02x faster                                |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| nbody          | 68.5 ms                                                | 68.8 ms: 1.00x slower                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_dna      | 153 ms                                                 | 149 ms: 1.03x faster                                 |
| regex_compile  | 75.6 ms                                                | 74.3 ms: 1.02x faster                                |
| regex_effbot   | 2.59 ms                                                | 2.58 ms: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                         |

Benchmark hidden because not significant (1): regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 6.46 ms                                                | 6.32 ms: 1.02x faster                                |
| pickle               | 7.42 us                                                | 7.33 us: 1.01x faster                                |
| unpickle_pure_python | 145 us                                                 | 143 us: 1.01x faster                                 |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                |
| unpickle_list        | 3.24 us                                                | 3.22 us: 1.01x faster                                |
| xml_etree_process    | 38.7 ms                                                | 38.8 ms: 1.00x slower                                |
| unpickle             | 9.25 us                                                | 9.31 us: 1.01x slower                                |
| xml_etree_iterparse  | 74.6 ms                                                | 75.1 ms: 1.01x slower                                |
| xml_etree_parse      | 109 ms                                                 | 110 ms: 1.01x slower                                 |
| pickle_list          | 2.89 us                                                | 2.93 us: 1.01x slower                                |
| Geometric mean       | (ref)                                                  | 1.00x faster                                         |

Benchmark hidden because not significant (4): pickle_pure_python, tomli_loads, xml_etree_generate, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 11.9 ms                                                | 12.5 ms: 1.05x slower                                |
| python_startup_no_site | 9.71 ms                                                | 10.3 ms: 1.07x slower                                |
| Geometric mean         | (ref)                                                  | 1.06x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| django_template | 22.1 ms                                                | 21.2 ms: 1.04x faster                                |
| mako            | 7.53 ms                                                | 7.24 ms: 1.04x faster                                |
| Geometric mean  | (ref)                                                  | 1.04x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231104-darwin-arm64-python-3.12-3.12.0+-9c583f3 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mypy2                    | 260 ms                                                 | 189 ms: 1.37x faster                                 |
| typing_runtime_protocols | 90.8 us                                                | 72.1 us: 1.26x faster                                |
| raytrace                 | 246 ms                                                 | 207 ms: 1.18x faster                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 43.2 ms: 1.16x faster                                |
| go                       | 107 ms                                                 | 94.7 ms: 1.13x faster                                |
| scimark_sor              | 94.3 ms                                                | 86.6 ms: 1.09x faster                                |
| sqlglot_parse            | 897 us                                                 | 824 us: 1.09x faster                                 |
| generators               | 28.3 ms                                                | 26.1 ms: 1.09x faster                                |
| sqlglot_transpile        | 1.08 ms                                                | 999 us: 1.08x faster                                 |
| deltablue                | 2.58 ms                                                | 2.40 ms: 1.07x faster                                |
| comprehensions           | 15.8 us                                                | 14.7 us: 1.07x faster                                |
| chaos                    | 44.8 ms                                                | 42.1 ms: 1.06x faster                                |
| pyflate                  | 329 ms                                                 | 316 ms: 1.04x faster                                 |
| django_template          | 22.1 ms                                                | 21.2 ms: 1.04x faster                                |
| mako                     | 7.53 ms                                                | 7.24 ms: 1.04x faster                                |
| richards_super           | 34.9 ms                                                | 33.7 ms: 1.04x faster                                |
| logging_format           | 3.99 us                                                | 3.85 us: 1.04x faster                                |
| logging_simple           | 3.69 us                                                | 3.57 us: 1.03x faster                                |
| richards                 | 31.1 ms                                                | 30.1 ms: 1.03x faster                                |
| docutils                 | 1.54 sec                                               | 1.50 sec: 1.03x faster                               |
| regex_dna                | 153 ms                                                 | 149 ms: 1.03x faster                                 |
| float                    | 58.1 ms                                                | 56.7 ms: 1.02x faster                                |
| json_dumps               | 6.46 ms                                                | 6.32 ms: 1.02x faster                                |
| dulwich_log              | 30.4 ms                                                | 29.9 ms: 1.02x faster                                |
| regex_compile            | 75.6 ms                                                | 74.3 ms: 1.02x faster                                |
| fannkuch                 | 265 ms                                                 | 261 ms: 1.02x faster                                 |
| sqlglot_normalize        | 188 ms                                                 | 185 ms: 1.02x faster                                 |
| sympy_str                | 151 ms                                                 | 149 ms: 1.01x faster                                 |
| bench_thread_pool        | 492 us                                                 | 486 us: 1.01x faster                                 |
| coverage                 | 37.9 ms                                                | 37.5 ms: 1.01x faster                                |
| sympy_integrate          | 11.3 ms                                                | 11.2 ms: 1.01x faster                                |
| mdp                      | 1.66 sec                                               | 1.64 sec: 1.01x faster                               |
| sqlglot_optimize         | 34.7 ms                                                | 34.3 ms: 1.01x faster                                |
| pickle                   | 7.42 us                                                | 7.33 us: 1.01x faster                                |
| async_tree_io_tg         | 673 ms                                                 | 665 ms: 1.01x faster                                 |
| create_gc_cycles         | 704 us                                                 | 696 us: 1.01x faster                                 |
| async_tree_io            | 669 ms                                                 | 662 ms: 1.01x faster                                 |
| sympy_sum                | 79.5 ms                                                | 78.7 ms: 1.01x faster                                |
| deepcopy_reduce          | 2.05 us                                                | 2.03 us: 1.01x faster                                |
| telco                    | 3.79 ms                                                | 3.75 ms: 1.01x faster                                |
| async_generators         | 306 ms                                                 | 303 ms: 1.01x faster                                 |
| json                     | 3.02 ms                                                | 2.99 ms: 1.01x faster                                |
| unpickle_pure_python     | 145 us                                                 | 143 us: 1.01x faster                                 |
| deepcopy                 | 225 us                                                 | 223 us: 1.01x faster                                 |
| sqlalchemy_declarative   | 65.4 ms                                                | 64.9 ms: 1.01x faster                                |
| sympy_expand             | 249 ms                                                 | 247 ms: 1.01x faster                                 |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                |
| unpickle_list            | 3.24 us                                                | 3.22 us: 1.01x faster                                |
| 2to3                     | 171 ms                                                 | 170 ms: 1.01x faster                                 |
| regex_effbot             | 2.59 ms                                                | 2.58 ms: 1.01x faster                                |
| sqlalchemy_imperative    | 6.92 ms                                                | 6.88 ms: 1.00x faster                                |
| pprint_pformat           | 1.00 sec                                               | 996 ms: 1.00x faster                                 |
| meteor_contest           | 73.3 ms                                                | 73.0 ms: 1.00x faster                                |
| crypto_pyaes             | 52.0 ms                                                | 51.9 ms: 1.00x faster                                |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| async_tree_none_tg       | 254 ms                                                 | 255 ms: 1.00x slower                                 |
| xml_etree_process        | 38.7 ms                                                | 38.8 ms: 1.00x slower                                |
| nbody                    | 68.5 ms                                                | 68.8 ms: 1.00x slower                                |
| scimark_lu               | 71.5 ms                                                | 71.8 ms: 1.00x slower                                |
| nqueens                  | 60.2 ms                                                | 60.5 ms: 1.00x slower                                |
| unpickle                 | 9.25 us                                                | 9.31 us: 1.01x slower                                |
| xml_etree_iterparse      | 74.6 ms                                                | 75.1 ms: 1.01x slower                                |
| xml_etree_parse          | 109 ms                                                 | 110 ms: 1.01x slower                                 |
| deepcopy_memo            | 24.6 us                                                | 24.8 us: 1.01x slower                                |
| scimark_fft              | 198 ms                                                 | 200 ms: 1.01x slower                                 |
| chameleon                | 4.51 ms                                                | 4.56 ms: 1.01x slower                                |
| spectral_norm            | 74.6 ms                                                | 75.5 ms: 1.01x slower                                |
| pickle_list              | 2.89 us                                                | 2.93 us: 1.01x slower                                |
| scimark_sparse_mat_mult  | 3.14 ms                                                | 3.19 ms: 1.01x slower                                |
| unpack_sequence          | 28.4 ns                                                | 28.8 ns: 1.01x slower                                |
| python_startup           | 11.9 ms                                                | 12.5 ms: 1.05x slower                                |
| coroutines               | 18.1 ms                                                | 19.1 ms: 1.05x slower                                |
| python_startup_no_site   | 9.71 ms                                                | 10.3 ms: 1.07x slower                                |
| Geometric mean           | (ref)                                                  | 1.02x faster                                         |

Benchmark hidden because not significant (24): gunicorn, aiohttp, bench_mp_pool, tornado_http, pathlib, dask, logging_silent, async_tree_cpu_io_mixed_tg, pickle_pure_python, sqlite_synth, hexiom, regex_v8, tomli_loads, xml_etree_generate, asyncio_websockets, json_loads, pprint_safe_repr, asyncio_tcp_ssl, async_tree_cpu_io_mixed, async_tree_none, async_tree_memoization_tg, async_tree_memoization, pycparser, asyncio_tcp


# HPT report

- Reliability score: 99.97% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
