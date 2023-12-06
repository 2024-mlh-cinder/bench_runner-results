
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.03x faster
- HPT reliability: 82.38%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.48 sec: 1.01x slower                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 281 ms: 1.00x slower                                  |
| nbody          | 65.6 ms                                                | 65.9 ms: 1.01x slower                                 |
| float          | 53.0 ms                                                | 53.3 ms: 1.01x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 141 ms: 1.08x faster                                  |
| regex_effbot   | 2.63 ms                                                | 2.52 ms: 1.04x faster                                 |
| regex_compile  | 76.7 ms                                                | 75.8 ms: 1.01x faster                                 |
| regex_v8       | 16.1 ms                                                | 16.1 ms: 1.00x slower                                 |
| Geometric mean | (ref)                                                  | 1.03x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.66 ms: 1.14x faster                                 |
| unpickle             | 9.67 us                                                | 9.14 us: 1.06x faster                                 |
| pickle_pure_python   | 201 us                                                 | 192 us: 1.05x faster                                  |
| unpickle_pure_python | 159 us                                                 | 153 us: 1.04x faster                                  |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                 |
| xml_etree_parse      | 108 ms                                                 | 109 ms: 1.01x slower                                  |
| pickle_list          | 2.81 us                                                | 2.86 us: 1.02x slower                                 |
| pickle               | 7.15 us                                                | 7.32 us: 1.02x slower                                 |
| tomli_loads          | 1.47 sec                                               | 1.53 sec: 1.05x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.3 ms: 1.07x slower                                 |
| json_loads           | 16.1 us                                                | 17.6 us: 1.10x slower                                 |
| xml_etree_process    | 35.1 ms                                                | 39.2 ms: 1.12x slower                                 |
| xml_etree_generate   | 48.3 ms                                                | 55.6 ms: 1.15x slower                                 |
| unpickle_list        | 2.65 us                                                | 3.11 us: 1.17x slower                                 |
| Geometric mean       | (ref)                                                  | 1.03x slower                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.38 ms: 1.08x faster                                 |
| python_startup         | 12.4 ms                                                | 12.0 ms: 1.03x faster                                 |
| Geometric mean         | (ref)                                                  | 1.06x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.25 ms: 1.18x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 91.2 us: 3.68x faster                                 |
| asyncio_tcp              | 651 ms                                                 | 458 ms: 1.42x faster                                  |
| unpack_sequence          | 34.1 ns                                                | 26.2 ns: 1.30x faster                                 |
| coverage                 | 58.4 ms                                                | 46.2 ms: 1.26x faster                                 |
| chaos                    | 49.4 ms                                                | 39.7 ms: 1.24x faster                                 |
| raytrace                 | 207 ms                                                 | 170 ms: 1.22x faster                                  |
| sqlglot_parse            | 959 us                                                 | 795 us: 1.21x faster                                  |
| deltablue                | 2.81 ms                                                | 2.35 ms: 1.20x faster                                 |
| mako                     | 8.53 ms                                                | 7.25 ms: 1.18x faster                                 |
| sqlglot_transpile        | 1.12 ms                                                | 966 us: 1.16x faster                                  |
| generators               | 28.8 ms                                                | 25.1 ms: 1.15x faster                                 |
| json_dumps               | 7.63 ms                                                | 6.66 ms: 1.14x faster                                 |
| async_tree_none          | 286 ms                                                 | 250 ms: 1.14x faster                                  |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.28 sec: 1.13x faster                                |
| crypto_pyaes             | 51.7 ms                                                | 46.3 ms: 1.12x faster                                 |
| deepcopy_memo            | 26.3 us                                                | 23.6 us: 1.11x faster                                 |
| comprehensions           | 16.1 us                                                | 14.7 us: 1.10x faster                                 |
| python_startup_no_site   | 10.2 ms                                                | 9.38 ms: 1.08x faster                                 |
| regex_dna                | 152 ms                                                 | 141 ms: 1.08x faster                                  |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.01 ms: 1.06x faster                                 |
| unpickle                 | 9.67 us                                                | 9.14 us: 1.06x faster                                 |
| scimark_lu               | 73.3 ms                                                | 69.5 ms: 1.05x faster                                 |
| scimark_monte_carlo      | 46.5 ms                                                | 44.3 ms: 1.05x faster                                 |
| spectral_norm            | 72.6 ms                                                | 69.1 ms: 1.05x faster                                 |
| pickle_pure_python       | 201 us                                                 | 192 us: 1.05x faster                                  |
| nqueens                  | 59.8 ms                                                | 57.2 ms: 1.05x faster                                 |
| regex_effbot             | 2.63 ms                                                | 2.52 ms: 1.04x faster                                 |
| unpickle_pure_python     | 159 us                                                 | 153 us: 1.04x faster                                  |
| scimark_fft              | 200 ms                                                 | 192 ms: 1.04x faster                                  |
| go                       | 109 ms                                                 | 104 ms: 1.04x faster                                  |
| async_tree_memoization   | 336 ms                                                 | 325 ms: 1.03x faster                                  |
| richards_super           | 39.2 ms                                                | 38.0 ms: 1.03x faster                                 |
| python_startup           | 12.4 ms                                                | 12.0 ms: 1.03x faster                                 |
| mypy2                    | 195 ms                                                 | 189 ms: 1.03x faster                                  |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 520 ms: 1.03x faster                                  |
| pycparser                | 698 ms                                                 | 681 ms: 1.02x faster                                  |
| hexiom                   | 4.72 ms                                                | 4.62 ms: 1.02x faster                                 |
| logging_silent           | 68.1 ns                                                | 66.8 ns: 1.02x faster                                 |
| deepcopy                 | 223 us                                                 | 219 us: 1.02x faster                                  |
| create_gc_cycles         | 716 us                                                 | 705 us: 1.02x faster                                  |
| coroutines               | 17.8 ms                                                | 17.5 ms: 1.01x faster                                 |
| async_tree_io            | 704 ms                                                 | 696 ms: 1.01x faster                                  |
| regex_compile            | 76.7 ms                                                | 75.8 ms: 1.01x faster                                 |
| meteor_contest           | 73.5 ms                                                | 72.9 ms: 1.01x faster                                 |
| dulwich_log              | 30.3 ms                                                | 30.1 ms: 1.01x faster                                 |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                 |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                 |
| regex_v8                 | 16.1 ms                                                | 16.1 ms: 1.00x slower                                 |
| pidigits                 | 281 ms                                                 | 281 ms: 1.00x slower                                  |
| nbody                    | 65.6 ms                                                | 65.9 ms: 1.01x slower                                 |
| float                    | 53.0 ms                                                | 53.3 ms: 1.01x slower                                 |
| docutils                 | 1.47 sec                                               | 1.48 sec: 1.01x slower                                |
| logging_simple           | 3.55 us                                                | 3.59 us: 1.01x slower                                 |
| xml_etree_parse          | 108 ms                                                 | 109 ms: 1.01x slower                                  |
| pickle_list              | 2.81 us                                                | 2.86 us: 1.02x slower                                 |
| pickle                   | 7.15 us                                                | 7.32 us: 1.02x slower                                 |
| logging_format           | 3.78 us                                                | 3.88 us: 1.03x slower                                 |
| mdp                      | 1.55 sec                                               | 1.59 sec: 1.03x slower                                |
| deepcopy_reduce          | 1.91 us                                                | 1.97 us: 1.03x slower                                 |
| tomli_loads              | 1.47 sec                                               | 1.53 sec: 1.05x slower                                |
| pprint_pformat           | 954 ms                                                 | 999 ms: 1.05x slower                                  |
| pprint_safe_repr         | 466 ms                                                 | 489 ms: 1.05x slower                                  |
| bench_mp_pool            | 43.9 ms                                                | 46.6 ms: 1.06x slower                                 |
| richards                 | 32.2 ms                                                | 34.4 ms: 1.07x slower                                 |
| sqlglot_normalize        | 171 ms                                                 | 183 ms: 1.07x slower                                  |
| xml_etree_iterparse      | 70.1 ms                                                | 75.3 ms: 1.07x slower                                 |
| fannkuch                 | 261 ms                                                 | 281 ms: 1.08x slower                                  |
| json                     | 2.78 ms                                                | 3.00 ms: 1.08x slower                                 |
| pyflate                  | 310 ms                                                 | 338 ms: 1.09x slower                                  |
| sqlglot_optimize         | 31.1 ms                                                | 34.0 ms: 1.09x slower                                 |
| json_loads               | 16.1 us                                                | 17.6 us: 1.10x slower                                 |
| xml_etree_process        | 35.1 ms                                                | 39.2 ms: 1.12x slower                                 |
| xml_etree_generate       | 48.3 ms                                                | 55.6 ms: 1.15x slower                                 |
| unpickle_list            | 2.65 us                                                | 3.11 us: 1.17x slower                                 |
| pathlib                  | 27.2 ms                                                | 33.0 ms: 1.21x slower                                 |
| scimark_sor              | 82.6 ms                                                | 103 ms: 1.24x slower                                  |
| sqlite_synth             | 1.27 us                                                | 1.58 us: 1.25x slower                                 |
| telco                    | 3.41 ms                                                | 4.68 ms: 1.37x slower                                 |
| async_generators         | 196 ms                                                 | 296 ms: 1.51x slower                                  |
| Geometric mean           | (ref)                                                  | 1.03x faster                                          |

Benchmark hidden because not significant (2): tornado_http, bench_thread_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230923-3.13.0a0-51863b7/bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7.json: dask


# HPT report

- Reliability score: 82.38% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
