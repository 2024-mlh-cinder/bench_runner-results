
# Results vs. 3.12.0

- fork: python
- ref: 2e91dba437fe5c56c6f8
- machine: darwin-arm64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.03x slower \*
- HPT reliability: 94.22%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 155 ms: 1.10x faster                                                  |
| chameleon      | 4.51 ms                                                | 4.65 ms: 1.03x slower                                                 |
| docutils       | 1.54 sec                                               | 1.48 sec: 1.04x faster                                                |
| tornado_http   | 70.7 ms                                                | 76.9 ms: 1.09x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 525 ms                                                 | 558 ms: 1.06x slower                                                  |
| async_tree_none         | 262 ms                                                 | 288 ms: 1.10x slower                                                  |
| async_tree_memoization  | 309 ms                                                 | 374 ms: 1.21x slower                                                  |
| async_tree_io           | 669 ms                                                 | 816 ms: 1.22x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.15x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.1 ms                                                | 51.6 ms: 1.12x faster                                                 |
| nbody          | 68.5 ms                                                | 64.4 ms: 1.07x faster                                                 |
| Geometric mean | (ref)                                                  | 1.06x faster                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.59 ms                                                | 2.45 ms: 1.06x faster                                                 |
| regex_compile  | 75.6 ms                                                | 72.7 ms: 1.04x faster                                                 |
| regex_v8       | 15.7 ms                                                | 16.6 ms: 1.06x slower                                                 |
| regex_dna      | 153 ms                                                 | 173 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_generate   | 55.9 ms                                                | 47.3 ms: 1.18x faster                                                 |
| unpickle_list        | 3.24 us                                                | 2.75 us: 1.18x faster                                                 |
| json_loads           | 17.6 us                                                | 15.3 us: 1.15x faster                                                 |
| xml_etree_parse      | 109 ms                                                 | 96.7 ms: 1.13x faster                                                 |
| xml_etree_process    | 38.7 ms                                                | 35.1 ms: 1.10x faster                                                 |
| pickle_list          | 2.89 us                                                | 2.67 us: 1.08x faster                                                 |
| unpickle             | 9.25 us                                                | 8.57 us: 1.08x faster                                                 |
| xml_etree_iterparse  | 74.6 ms                                                | 69.6 ms: 1.07x faster                                                 |
| pickle_dict          | 18.0 us                                                | 16.8 us: 1.07x faster                                                 |
| tomli_loads          | 1.39 sec                                               | 1.36 sec: 1.03x faster                                                |
| pickle               | 7.42 us                                                | 7.39 us: 1.00x faster                                                 |
| pickle_pure_python   | 188 us                                                 | 203 us: 1.08x slower                                                  |
| unpickle_pure_python | 145 us                                                 | 158 us: 1.09x slower                                                  |
| json_dumps           | 6.46 ms                                                | 7.46 ms: 1.15x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.05x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.71 ms                                                | 9.02 ms: 1.08x faster                                                 |
| python_startup         | 11.9 ms                                                | 14.9 ms: 1.25x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.08x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 22.1 ms                                                | 20.8 ms: 1.07x faster                                                 |
| mako            | 7.53 ms                                                | 8.07 ms: 1.07x slower                                                 |
| Geometric mean  | (ref)                                                  | 1.00x slower                                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators         | 306 ms                                                 | 191 ms: 1.60x faster                                                  |
| pathlib                  | 29.3 ms                                                | 23.3 ms: 1.26x faster                                                 |
| sqlite_synth             | 1.59 us                                                | 1.32 us: 1.20x faster                                                 |
| xml_etree_generate       | 55.9 ms                                                | 47.3 ms: 1.18x faster                                                 |
| unpickle_list            | 3.24 us                                                | 2.75 us: 1.18x faster                                                 |
| logging_simple           | 3.69 us                                                | 3.19 us: 1.16x faster                                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 43.2 ms: 1.16x faster                                                 |
| json_loads               | 17.6 us                                                | 15.3 us: 1.15x faster                                                 |
| sqlglot_normalize        | 188 ms                                                 | 164 ms: 1.14x faster                                                  |
| telco                    | 3.79 ms                                                | 3.31 ms: 1.14x faster                                                 |
| logging_format           | 3.99 us                                                | 3.49 us: 1.14x faster                                                 |
| xml_etree_parse          | 109 ms                                                 | 96.7 ms: 1.13x faster                                                 |
| raytrace                 | 246 ms                                                 | 218 ms: 1.13x faster                                                  |
| float                    | 58.1 ms                                                | 51.6 ms: 1.12x faster                                                 |
| bench_mp_pool            | 46.3 ms                                                | 41.4 ms: 1.12x faster                                                 |
| scimark_sor              | 94.3 ms                                                | 85.3 ms: 1.11x faster                                                 |
| xml_etree_process        | 38.7 ms                                                | 35.1 ms: 1.10x faster                                                 |
| 2to3                     | 171 ms                                                 | 155 ms: 1.10x faster                                                  |
| sqlglot_optimize         | 34.7 ms                                                | 31.6 ms: 1.10x faster                                                 |
| nqueens                  | 60.2 ms                                                | 55.5 ms: 1.08x faster                                                 |
| pickle_list              | 2.89 us                                                | 2.67 us: 1.08x faster                                                 |
| deepcopy_reduce          | 2.05 us                                                | 1.89 us: 1.08x faster                                                 |
| unpickle                 | 9.25 us                                                | 8.57 us: 1.08x faster                                                 |
| python_startup_no_site   | 9.71 ms                                                | 9.02 ms: 1.08x faster                                                 |
| scimark_fft              | 198 ms                                                 | 184 ms: 1.07x faster                                                  |
| xml_etree_iterparse      | 74.6 ms                                                | 69.6 ms: 1.07x faster                                                 |
| coroutines               | 18.1 ms                                                | 16.9 ms: 1.07x faster                                                 |
| fannkuch                 | 265 ms                                                 | 247 ms: 1.07x faster                                                  |
| pickle_dict              | 18.0 us                                                | 16.8 us: 1.07x faster                                                 |
| generators               | 28.3 ms                                                | 26.6 ms: 1.07x faster                                                 |
| django_template          | 22.1 ms                                                | 20.8 ms: 1.07x faster                                                 |
| nbody                    | 68.5 ms                                                | 64.4 ms: 1.07x faster                                                 |
| pprint_safe_repr         | 491 ms                                                 | 465 ms: 1.06x faster                                                  |
| regex_effbot             | 2.59 ms                                                | 2.45 ms: 1.06x faster                                                 |
| json                     | 3.02 ms                                                | 2.86 ms: 1.05x faster                                                 |
| pprint_pformat           | 1.00 sec                                               | 952 ms: 1.05x faster                                                  |
| scimark_sparse_mat_mult  | 3.14 ms                                                | 3.01 ms: 1.05x faster                                                 |
| sqlalchemy_declarative   | 65.4 ms                                                | 62.6 ms: 1.04x faster                                                 |
| docutils                 | 1.54 sec                                               | 1.48 sec: 1.04x faster                                                |
| spectral_norm            | 74.6 ms                                                | 71.6 ms: 1.04x faster                                                 |
| regex_compile            | 75.6 ms                                                | 72.7 ms: 1.04x faster                                                 |
| dulwich_log              | 30.4 ms                                                | 29.6 ms: 1.03x faster                                                 |
| tomli_loads              | 1.39 sec                                               | 1.36 sec: 1.03x faster                                                |
| meteor_contest           | 73.3 ms                                                | 71.7 ms: 1.02x faster                                                 |
| pyflate                  | 329 ms                                                 | 322 ms: 1.02x faster                                                  |
| sympy_expand             | 249 ms                                                 | 244 ms: 1.02x faster                                                  |
| sympy_str                | 151 ms                                                 | 151 ms: 1.01x faster                                                  |
| pickle                   | 7.42 us                                                | 7.39 us: 1.00x faster                                                 |
| deepcopy                 | 225 us                                                 | 224 us: 1.00x faster                                                  |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                                 |
| bench_thread_pool        | 492 us                                                 | 498 us: 1.01x slower                                                  |
| chameleon                | 4.51 ms                                                | 4.65 ms: 1.03x slower                                                 |
| sympy_sum                | 79.5 ms                                                | 82.2 ms: 1.03x slower                                                 |
| create_gc_cycles         | 704 us                                                 | 729 us: 1.04x slower                                                  |
| chaos                    | 44.8 ms                                                | 46.4 ms: 1.04x slower                                                 |
| hexiom                   | 4.25 ms                                                | 4.41 ms: 1.04x slower                                                 |
| pycparser                | 670 ms                                                 | 702 ms: 1.05x slower                                                  |
| comprehensions           | 15.8 us                                                | 16.5 us: 1.05x slower                                                 |
| mdp                      | 1.66 sec                                               | 1.76 sec: 1.06x slower                                                |
| go                       | 107 ms                                                 | 113 ms: 1.06x slower                                                  |
| deepcopy_memo            | 24.6 us                                                | 26.0 us: 1.06x slower                                                 |
| async_tree_cpu_io_mixed  | 525 ms                                                 | 558 ms: 1.06x slower                                                  |
| regex_v8                 | 15.7 ms                                                | 16.6 ms: 1.06x slower                                                 |
| richards                 | 31.1 ms                                                | 33.2 ms: 1.07x slower                                                 |
| mako                     | 7.53 ms                                                | 8.07 ms: 1.07x slower                                                 |
| sqlalchemy_imperative    | 6.92 ms                                                | 7.43 ms: 1.07x slower                                                 |
| crypto_pyaes             | 52.0 ms                                                | 56.0 ms: 1.08x slower                                                 |
| pickle_pure_python       | 188 us                                                 | 203 us: 1.08x slower                                                  |
| logging_silent           | 68.3 ns                                                | 74.3 ns: 1.09x slower                                                 |
| tornado_http             | 70.7 ms                                                | 76.9 ms: 1.09x slower                                                 |
| unpickle_pure_python     | 145 us                                                 | 158 us: 1.09x slower                                                  |
| unpack_sequence          | 28.4 ns                                                | 31.0 ns: 1.09x slower                                                 |
| async_tree_none          | 262 ms                                                 | 288 ms: 1.10x slower                                                  |
| regex_dna                | 153 ms                                                 | 173 ms: 1.13x slower                                                  |
| deltablue                | 2.58 ms                                                | 2.96 ms: 1.15x slower                                                 |
| json_dumps               | 6.46 ms                                                | 7.46 ms: 1.15x slower                                                 |
| async_tree_memoization   | 309 ms                                                 | 374 ms: 1.21x slower                                                  |
| async_tree_io            | 669 ms                                                 | 816 ms: 1.22x slower                                                  |
| richards_super           | 34.9 ms                                                | 42.7 ms: 1.22x slower                                                 |
| python_startup           | 11.9 ms                                                | 14.9 ms: 1.25x slower                                                 |
| sqlglot_transpile        | 1.08 ms                                                | 1.35 ms: 1.26x slower                                                 |
| sqlglot_parse            | 897 us                                                 | 1.19 ms: 1.32x slower                                                 |
| dask                     | 228 ms                                                 | 302 ms: 1.33x slower                                                  |
| typing_runtime_protocols | 90.8 us                                                | 325 us: 3.58x slower                                                  |
| coverage                 | 37.9 ms                                                | 303 ms: 7.98x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.03x slower                                                          |

Benchmark hidden because not significant (4): pidigits, sympy_integrate, scimark_lu, gunicorn
Ignored benchmarks (9) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2
Ignored benchmarks (6) of results/bm-20211208-3.11.0a3-2e91dba/bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 94.22% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
