
# Results vs. 3.11.0

- fork: python
- ref: 2e91dba437fe5c56c6f8
- machine: darwin-arm64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.05x slower \*
- HPT reliability: 99.74%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| chameleon      | 4.17 ms                                                | 4.65 ms: 1.11x slower                                                 |
| docutils       | 1.46 sec                                               | 1.48 sec: 1.02x slower                                                |
| tornado_http   | 71.0 ms                                                | 76.9 ms: 1.08x slower                                                 |
| Geometric mean | (ref)                                                  | 1.04x slower                                                          |

Benchmark hidden because not significant (2): 2to3, html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 282 ms                                                 | 288 ms: 1.02x slower                                                  |
| async_tree_memoization  | 361 ms                                                 | 374 ms: 1.04x slower                                                  |
| async_tree_cpu_io_mixed | 522 ms                                                 | 558 ms: 1.07x slower                                                  |
| async_tree_io           | 705 ms                                                 | 816 ms: 1.16x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.07x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 55.4 ms                                                | 51.6 ms: 1.07x faster                                                 |
| nbody          | 68.7 ms                                                | 64.4 ms: 1.07x faster                                                 |
| Geometric mean | (ref)                                                  | 1.05x faster                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 73.9 ms                                                | 72.7 ms: 1.02x faster                                                 |
| regex_effbot   | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| regex_v8       | 15.3 ms                                                | 16.6 ms: 1.09x slower                                                 |
| regex_dna      | 149 ms                                                 | 173 ms: 1.16x slower                                                  |
| Geometric mean | (ref)                                                  | 1.05x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_parse      | 107 ms                                                 | 96.7 ms: 1.11x faster                                                 |
| pickle_pure_python   | 211 us                                                 | 203 us: 1.04x faster                                                  |
| unpickle_pure_python | 163 us                                                 | 158 us: 1.03x faster                                                  |
| json_loads           | 15.8 us                                                | 15.3 us: 1.03x faster                                                 |
| json_dumps           | 7.58 ms                                                | 7.46 ms: 1.02x faster                                                 |
| pickle_dict          | 17.0 us                                                | 16.8 us: 1.01x faster                                                 |
| unpickle_list        | 2.77 us                                                | 2.75 us: 1.00x faster                                                 |
| xml_etree_generate   | 46.8 ms                                                | 47.3 ms: 1.01x slower                                                 |
| xml_etree_iterparse  | 68.2 ms                                                | 69.6 ms: 1.02x slower                                                 |
| pickle               | 7.22 us                                                | 7.39 us: 1.02x slower                                                 |
| unpickle             | 8.32 us                                                | 8.57 us: 1.03x slower                                                 |
| xml_etree_process    | 34.0 ms                                                | 35.1 ms: 1.03x slower                                                 |
| tomli_loads          | 1.30 sec                                               | 1.36 sec: 1.04x slower                                                |
| Geometric mean       | (ref)                                                  | 1.01x faster                                                          |

Benchmark hidden because not significant (1): pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.15 ms                                                | 9.02 ms: 1.01x faster                                                 |
| python_startup         | 11.4 ms                                                | 14.9 ms: 1.31x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.14x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.22 ms                                                | 8.07 ms: 1.02x faster                                                 |
| genshi_text     | 14.5 ms                                                | 14.8 ms: 1.02x slower                                                 |
| genshi_xml      | 28.1 ms                                                | 29.4 ms: 1.05x slower                                                 |
| django_template | 19.8 ms                                                | 20.8 ms: 1.05x slower                                                 |
| Geometric mean  | (ref)                                                  | 1.02x slower                                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pathlib                  | 28.5 ms                                                | 23.3 ms: 1.22x faster                                                 |
| deepcopy_memo            | 28.9 us                                                | 26.0 us: 1.11x faster                                                 |
| xml_etree_parse          | 107 ms                                                 | 96.7 ms: 1.11x faster                                                 |
| generators               | 29.2 ms                                                | 26.6 ms: 1.10x faster                                                 |
| scimark_monte_carlo      | 47.1 ms                                                | 43.2 ms: 1.09x faster                                                 |
| float                    | 55.4 ms                                                | 51.6 ms: 1.07x faster                                                 |
| logging_simple           | 3.41 us                                                | 3.19 us: 1.07x faster                                                 |
| nbody                    | 68.7 ms                                                | 64.4 ms: 1.07x faster                                                 |
| pylint                   | 256 ms                                                 | 241 ms: 1.06x faster                                                  |
| logging_format           | 3.69 us                                                | 3.49 us: 1.06x faster                                                 |
| deepcopy_reduce          | 1.98 us                                                | 1.89 us: 1.05x faster                                                 |
| meteor_contest           | 74.9 ms                                                | 71.7 ms: 1.05x faster                                                 |
| unpack_sequence          | 32.3 ns                                                | 31.0 ns: 1.04x faster                                                 |
| chaos                    | 48.2 ms                                                | 46.4 ms: 1.04x faster                                                 |
| pprint_pformat           | 989 ms                                                 | 952 ms: 1.04x faster                                                  |
| deepcopy                 | 233 us                                                 | 224 us: 1.04x faster                                                  |
| pickle_pure_python       | 211 us                                                 | 203 us: 1.04x faster                                                  |
| hexiom                   | 4.55 ms                                                | 4.41 ms: 1.03x faster                                                 |
| unpickle_pure_python     | 163 us                                                 | 158 us: 1.03x faster                                                  |
| json_loads               | 15.8 us                                                | 15.3 us: 1.03x faster                                                 |
| pprint_safe_repr         | 479 ms                                                 | 465 ms: 1.03x faster                                                  |
| sqlite_synth             | 1.35 us                                                | 1.32 us: 1.02x faster                                                 |
| mako                     | 8.22 ms                                                | 8.07 ms: 1.02x faster                                                 |
| regex_compile            | 73.9 ms                                                | 72.7 ms: 1.02x faster                                                 |
| json_dumps               | 7.58 ms                                                | 7.46 ms: 1.02x faster                                                 |
| python_startup_no_site   | 9.15 ms                                                | 9.02 ms: 1.01x faster                                                 |
| scimark_fft              | 187 ms                                                 | 184 ms: 1.01x faster                                                  |
| pickle_dict              | 17.0 us                                                | 16.8 us: 1.01x faster                                                 |
| flaskblogging            | 2.46 ms                                                | 2.43 ms: 1.01x faster                                                 |
| dulwich_log              | 29.9 ms                                                | 29.6 ms: 1.01x faster                                                 |
| async_generators         | 192 ms                                                 | 191 ms: 1.01x faster                                                  |
| unpickle_list            | 2.77 us                                                | 2.75 us: 1.00x faster                                                 |
| regex_effbot             | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| fannkuch                 | 247 ms                                                 | 247 ms: 1.00x slower                                                  |
| gc_traversal             | 2.39 ms                                                | 2.40 ms: 1.00x slower                                                 |
| typing_runtime_protocols | 323 us                                                 | 325 us: 1.01x slower                                                  |
| sympy_sum                | 81.6 ms                                                | 82.2 ms: 1.01x slower                                                 |
| xml_etree_generate       | 46.8 ms                                                | 47.3 ms: 1.01x slower                                                 |
| mdp                      | 1.73 sec                                               | 1.76 sec: 1.01x slower                                                |
| docutils                 | 1.46 sec                                               | 1.48 sec: 1.02x slower                                                |
| nqueens                  | 54.6 ms                                                | 55.5 ms: 1.02x slower                                                 |
| create_gc_cycles         | 715 us                                                 | 729 us: 1.02x slower                                                  |
| genshi_text              | 14.5 ms                                                | 14.8 ms: 1.02x slower                                                 |
| xml_etree_iterparse      | 68.2 ms                                                | 69.6 ms: 1.02x slower                                                 |
| async_tree_none          | 282 ms                                                 | 288 ms: 1.02x slower                                                  |
| coroutines               | 16.6 ms                                                | 16.9 ms: 1.02x slower                                                 |
| pickle                   | 7.22 us                                                | 7.39 us: 1.02x slower                                                 |
| spectral_norm            | 69.7 ms                                                | 71.6 ms: 1.03x slower                                                 |
| sqlglot_normalize        | 160 ms                                                 | 164 ms: 1.03x slower                                                  |
| unpickle                 | 8.32 us                                                | 8.57 us: 1.03x slower                                                 |
| xml_etree_process        | 34.0 ms                                                | 35.1 ms: 1.03x slower                                                 |
| json                     | 2.77 ms                                                | 2.86 ms: 1.03x slower                                                 |
| sqlalchemy_declarative   | 60.6 ms                                                | 62.6 ms: 1.03x slower                                                 |
| async_tree_memoization   | 361 ms                                                 | 374 ms: 1.04x slower                                                  |
| sqlalchemy_imperative    | 7.17 ms                                                | 7.43 ms: 1.04x slower                                                 |
| thrift                   | 424 us                                                 | 440 us: 1.04x slower                                                  |
| tomli_loads              | 1.30 sec                                               | 1.36 sec: 1.04x slower                                                |
| sympy_str                | 144 ms                                                 | 151 ms: 1.04x slower                                                  |
| sympy_expand             | 234 ms                                                 | 244 ms: 1.05x slower                                                  |
| genshi_xml               | 28.1 ms                                                | 29.4 ms: 1.05x slower                                                 |
| telco                    | 3.17 ms                                                | 3.31 ms: 1.05x slower                                                 |
| django_template          | 19.8 ms                                                | 20.8 ms: 1.05x slower                                                 |
| pycparser                | 667 ms                                                 | 702 ms: 1.05x slower                                                  |
| scimark_lu               | 67.8 ms                                                | 71.4 ms: 1.05x slower                                                 |
| sqlglot_optimize         | 29.6 ms                                                | 31.6 ms: 1.07x slower                                                 |
| async_tree_cpu_io_mixed  | 522 ms                                                 | 558 ms: 1.07x slower                                                  |
| bench_thread_pool        | 461 us                                                 | 498 us: 1.08x slower                                                  |
| richards                 | 30.8 ms                                                | 33.2 ms: 1.08x slower                                                 |
| tornado_http             | 71.0 ms                                                | 76.9 ms: 1.08x slower                                                 |
| pyflate                  | 297 ms                                                 | 322 ms: 1.09x slower                                                  |
| regex_v8                 | 15.3 ms                                                | 16.6 ms: 1.09x slower                                                 |
| raytrace                 | 200 ms                                                 | 218 ms: 1.09x slower                                                  |
| deltablue                | 2.70 ms                                                | 2.96 ms: 1.10x slower                                                 |
| gunicorn                 | 1.11 ms                                                | 1.23 ms: 1.11x slower                                                 |
| go                       | 102 ms                                                 | 113 ms: 1.11x slower                                                  |
| chameleon                | 4.17 ms                                                | 4.65 ms: 1.11x slower                                                 |
| comprehensions           | 14.7 us                                                | 16.5 us: 1.13x slower                                                 |
| scimark_sor              | 75.2 ms                                                | 85.3 ms: 1.13x slower                                                 |
| logging_silent           | 64.5 ns                                                | 74.3 ns: 1.15x slower                                                 |
| async_tree_io            | 705 ms                                                 | 816 ms: 1.16x slower                                                  |
| richards_super           | 36.8 ms                                                | 42.7 ms: 1.16x slower                                                 |
| regex_dna                | 149 ms                                                 | 173 ms: 1.16x slower                                                  |
| crypto_pyaes             | 48.1 ms                                                | 56.0 ms: 1.16x slower                                                 |
| sqlglot_transpile        | 1.05 ms                                                | 1.35 ms: 1.29x slower                                                 |
| python_startup           | 11.4 ms                                                | 14.9 ms: 1.31x slower                                                 |
| sqlglot_parse            | 886 us                                                 | 1.19 ms: 1.34x slower                                                 |
| dask                     | 224 ms                                                 | 302 ms: 1.35x slower                                                  |
| coverage                 | 41.4 ms                                                | 303 ms: 7.32x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.05x slower                                                          |

Benchmark hidden because not significant (7): bench_mp_pool, sympy_integrate, scimark_sparse_mat_mult, pickle_list, html5lib, 2to3, pidigits
Ignored benchmarks (9) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2


# HPT report

- Reliability score: 99.74% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
