
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 482fad7
- commit date: 2023-08-26
- overall geometric mean: 1.01x slower
- HPT reliability: 99.60%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.52 sec: 1.03x slower                                |
| Geometric mean | (ref)                                                  | 1.02x slower                                          |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 281 ms: 1.00x slower                                  |
| float          | 53.0 ms                                                | 56.7 ms: 1.07x slower                                 |
| nbody          | 65.6 ms                                                | 72.0 ms: 1.10x slower                                 |
| Geometric mean | (ref)                                                  | 1.06x slower                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_effbot   | 2.63 ms                                                | 2.57 ms: 1.02x faster                                 |
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                  |
| regex_compile  | 76.7 ms                                                | 79.3 ms: 1.03x slower                                 |
| regex_v8       | 16.1 ms                                                | 17.0 ms: 1.05x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.51 ms: 1.17x faster                                 |
| unpickle             | 9.67 us                                                | 9.29 us: 1.04x faster                                 |
| pickle_pure_python   | 201 us                                                 | 200 us: 1.00x faster                                  |
| pickle_dict          | 18.0 us                                                | 18.0 us: 1.00x slower                                 |
| unpickle_pure_python | 159 us                                                 | 162 us: 1.02x slower                                  |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.03x slower                                  |
| pickle_list          | 2.81 us                                                | 2.92 us: 1.04x slower                                 |
| pickle               | 7.15 us                                                | 7.43 us: 1.04x slower                                 |
| tomli_loads          | 1.47 sec                                               | 1.56 sec: 1.07x slower                                |
| json_loads           | 16.1 us                                                | 17.5 us: 1.08x slower                                 |
| xml_etree_iterparse  | 70.1 ms                                                | 76.5 ms: 1.09x slower                                 |
| xml_etree_process    | 35.1 ms                                                | 40.9 ms: 1.17x slower                                 |
| unpickle_list        | 2.65 us                                                | 3.19 us: 1.20x slower                                 |
| xml_etree_generate   | 48.3 ms                                                | 59.0 ms: 1.22x slower                                 |
| Geometric mean       | (ref)                                                  | 1.05x slower                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.27 ms: 1.10x faster                                 |
| python_startup         | 12.4 ms                                                | 11.4 ms: 1.09x faster                                 |
| Geometric mean         | (ref)                                                  | 1.10x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.46 ms: 1.14x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 94.2 us: 3.57x faster                                 |
| asyncio_tcp              | 651 ms                                                 | 428 ms: 1.52x faster                                  |
| unpack_sequence          | 34.1 ns                                                | 27.9 ns: 1.22x faster                                 |
| coverage                 | 58.4 ms                                                | 48.2 ms: 1.21x faster                                 |
| json_dumps               | 7.63 ms                                                | 6.51 ms: 1.17x faster                                 |
| chaos                    | 49.4 ms                                                | 42.2 ms: 1.17x faster                                 |
| sqlglot_parse            | 959 us                                                 | 834 us: 1.15x faster                                  |
| mako                     | 8.53 ms                                                | 7.46 ms: 1.14x faster                                 |
| async_tree_none          | 286 ms                                                 | 255 ms: 1.12x faster                                  |
| sqlglot_transpile        | 1.12 ms                                                | 1.01 ms: 1.11x faster                                 |
| deltablue                | 2.81 ms                                                | 2.56 ms: 1.10x faster                                 |
| python_startup_no_site   | 10.2 ms                                                | 9.27 ms: 1.10x faster                                 |
| python_startup           | 12.4 ms                                                | 11.4 ms: 1.09x faster                                 |
| raytrace                 | 207 ms                                                 | 192 ms: 1.08x faster                                  |
| crypto_pyaes             | 51.7 ms                                                | 48.0 ms: 1.08x faster                                 |
| comprehensions           | 16.1 us                                                | 15.0 us: 1.07x faster                                 |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.36 sec: 1.06x faster                                |
| deepcopy_memo            | 26.3 us                                                | 25.1 us: 1.05x faster                                 |
| unpickle                 | 9.67 us                                                | 9.29 us: 1.04x faster                                 |
| create_gc_cycles         | 716 us                                                 | 696 us: 1.03x faster                                  |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.11 ms: 1.03x faster                                 |
| regex_effbot             | 2.63 ms                                                | 2.57 ms: 1.02x faster                                 |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                  |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 527 ms: 1.01x faster                                  |
| richards_super           | 39.2 ms                                                | 38.8 ms: 1.01x faster                                 |
| generators               | 28.8 ms                                                | 28.5 ms: 1.01x faster                                 |
| gc_traversal             | 2.42 ms                                                | 2.39 ms: 1.01x faster                                 |
| pickle_pure_python       | 201 us                                                 | 200 us: 1.00x faster                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 46.4 ms: 1.00x faster                                 |
| pidigits                 | 281 ms                                                 | 281 ms: 1.00x slower                                  |
| pickle_dict              | 18.0 us                                                | 18.0 us: 1.00x slower                                 |
| nqueens                  | 59.8 ms                                                | 60.0 ms: 1.00x slower                                 |
| go                       | 109 ms                                                 | 109 ms: 1.01x slower                                  |
| meteor_contest           | 73.5 ms                                                | 74.3 ms: 1.01x slower                                 |
| scimark_fft              | 200 ms                                                 | 202 ms: 1.01x slower                                  |
| unpickle_pure_python     | 159 us                                                 | 162 us: 1.02x slower                                  |
| spectral_norm            | 72.6 ms                                                | 73.7 ms: 1.02x slower                                 |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.03x slower                                  |
| dulwich_log              | 30.3 ms                                                | 31.1 ms: 1.03x slower                                 |
| docutils                 | 1.47 sec                                               | 1.52 sec: 1.03x slower                                |
| regex_compile            | 76.7 ms                                                | 79.3 ms: 1.03x slower                                 |
| scimark_lu               | 73.3 ms                                                | 75.8 ms: 1.03x slower                                 |
| hexiom                   | 4.72 ms                                                | 4.88 ms: 1.03x slower                                 |
| bench_mp_pool            | 43.9 ms                                                | 45.5 ms: 1.03x slower                                 |
| bench_thread_pool        | 474 us                                                 | 492 us: 1.04x slower                                  |
| pickle_list              | 2.81 us                                                | 2.92 us: 1.04x slower                                 |
| pickle                   | 7.15 us                                                | 7.43 us: 1.04x slower                                 |
| deepcopy                 | 223 us                                                 | 232 us: 1.04x slower                                  |
| regex_v8                 | 16.1 ms                                                | 17.0 ms: 1.05x slower                                 |
| mdp                      | 1.55 sec                                               | 1.63 sec: 1.05x slower                                |
| logging_simple           | 3.55 us                                                | 3.77 us: 1.06x slower                                 |
| tomli_loads              | 1.47 sec                                               | 1.56 sec: 1.07x slower                                |
| logging_format           | 3.78 us                                                | 4.04 us: 1.07x slower                                 |
| float                    | 53.0 ms                                                | 56.7 ms: 1.07x slower                                 |
| json                     | 2.78 ms                                                | 3.01 ms: 1.08x slower                                 |
| json_loads               | 16.1 us                                                | 17.5 us: 1.08x slower                                 |
| xml_etree_iterparse      | 70.1 ms                                                | 76.5 ms: 1.09x slower                                 |
| deepcopy_reduce          | 1.91 us                                                | 2.09 us: 1.10x slower                                 |
| fannkuch                 | 261 ms                                                 | 287 ms: 1.10x slower                                  |
| nbody                    | 65.6 ms                                                | 72.0 ms: 1.10x slower                                 |
| richards                 | 32.2 ms                                                | 35.4 ms: 1.10x slower                                 |
| pprint_pformat           | 954 ms                                                 | 1.05 sec: 1.10x slower                                |
| coroutines               | 17.8 ms                                                | 19.7 ms: 1.11x slower                                 |
| logging_silent           | 68.1 ns                                                | 75.7 ns: 1.11x slower                                 |
| sqlglot_normalize        | 171 ms                                                 | 192 ms: 1.12x slower                                  |
| pprint_safe_repr         | 466 ms                                                 | 525 ms: 1.13x slower                                  |
| pyflate                  | 310 ms                                                 | 350 ms: 1.13x slower                                  |
| sqlglot_optimize         | 31.1 ms                                                | 35.3 ms: 1.13x slower                                 |
| xml_etree_process        | 35.1 ms                                                | 40.9 ms: 1.17x slower                                 |
| pathlib                  | 27.2 ms                                                | 32.6 ms: 1.20x slower                                 |
| unpickle_list            | 2.65 us                                                | 3.19 us: 1.20x slower                                 |
| xml_etree_generate       | 48.3 ms                                                | 59.0 ms: 1.22x slower                                 |
| sqlite_synth             | 1.27 us                                                | 1.62 us: 1.27x slower                                 |
| scimark_sor              | 82.6 ms                                                | 109 ms: 1.32x slower                                  |
| mypy2                    | 195 ms                                                 | 261 ms: 1.34x slower                                  |
| telco                    | 3.41 ms                                                | 4.57 ms: 1.34x slower                                 |
| async_generators         | 196 ms                                                 | 312 ms: 1.59x slower                                  |
| Geometric mean           | (ref)                                                  | 1.01x slower                                          |

Benchmark hidden because not significant (4): async_tree_memoization, async_tree_io, tornado_http, pycparser
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230826-3.13.0a0-482fad7/bm-20230826-darwin-arm64-python-main-3.13.0a0-482fad7.json: dask


# HPT report

- Reliability score: 99.60% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
