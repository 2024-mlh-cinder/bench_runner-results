
# Results vs. 3.11.0

- fork: brandtbucher
- ref: justin_no_pic
- machine: darwin-arm64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.01x slower
- HPT reliability: 99.42%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.53 sec: 1.04x slower                                               |
| Geometric mean | (ref)                                                  | 1.01x slower                                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.01x slower                                                 |
| float          | 53.0 ms                                                | 57.1 ms: 1.08x slower                                                |
| nbody          | 65.6 ms                                                | 78.8 ms: 1.20x slower                                                |
| Geometric mean | (ref)                                                  | 1.09x slower                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 140 ms: 1.09x faster                                                 |
| regex_effbot   | 2.63 ms                                                | 2.51 ms: 1.05x faster                                                |
| regex_v8       | 16.1 ms                                                | 16.5 ms: 1.02x slower                                                |
| regex_compile  | 76.7 ms                                                | 81.8 ms: 1.07x slower                                                |
| Geometric mean | (ref)                                                  | 1.01x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.53 ms: 1.17x faster                                                |
| unpickle             | 9.67 us                                                | 9.18 us: 1.05x faster                                                |
| pickle_pure_python   | 201 us                                                 | 195 us: 1.03x faster                                                 |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                                |
| xml_etree_parse      | 108 ms                                                 | 110 ms: 1.02x slower                                                 |
| pickle_list          | 2.81 us                                                | 2.90 us: 1.03x slower                                                |
| unpickle_pure_python | 159 us                                                 | 164 us: 1.03x slower                                                 |
| pickle               | 7.15 us                                                | 7.40 us: 1.03x slower                                                |
| tomli_loads          | 1.47 sec                                               | 1.53 sec: 1.05x slower                                               |
| json_loads           | 16.1 us                                                | 17.6 us: 1.10x slower                                                |
| xml_etree_iterparse  | 70.1 ms                                                | 77.2 ms: 1.10x slower                                                |
| xml_etree_process    | 35.1 ms                                                | 40.0 ms: 1.14x slower                                                |
| unpickle_list        | 2.65 us                                                | 3.18 us: 1.20x slower                                                |
| xml_etree_generate   | 48.3 ms                                                | 58.2 ms: 1.21x slower                                                |
| Geometric mean       | (ref)                                                  | 1.04x slower                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 12.4 ms                                                | 12.6 ms: 1.01x slower                                                |
| python_startup_no_site | 10.2 ms                                                | 10.5 ms: 1.03x slower                                                |
| Geometric mean         | (ref)                                                  | 1.02x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.66 ms: 1.11x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 95.1 us: 3.53x faster                                                |
| asyncio_tcp              | 651 ms                                                 | 413 ms: 1.58x faster                                                 |
| unpack_sequence          | 34.1 ns                                                | 26.9 ns: 1.27x faster                                                |
| coverage                 | 58.4 ms                                                | 47.9 ms: 1.22x faster                                                |
| sqlglot_parse            | 959 us                                                 | 818 us: 1.17x faster                                                 |
| json_dumps               | 7.63 ms                                                | 6.53 ms: 1.17x faster                                                |
| chaos                    | 49.4 ms                                                | 42.3 ms: 1.17x faster                                                |
| generators               | 28.8 ms                                                | 25.0 ms: 1.15x faster                                                |
| raytrace                 | 207 ms                                                 | 180 ms: 1.15x faster                                                 |
| deltablue                | 2.81 ms                                                | 2.50 ms: 1.13x faster                                                |
| sqlglot_transpile        | 1.12 ms                                                | 999 us: 1.12x faster                                                 |
| async_tree_none          | 286 ms                                                 | 254 ms: 1.12x faster                                                 |
| mako                     | 8.53 ms                                                | 7.66 ms: 1.11x faster                                                |
| regex_dna                | 152 ms                                                 | 140 ms: 1.09x faster                                                 |
| crypto_pyaes             | 51.7 ms                                                | 48.6 ms: 1.06x faster                                                |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.36 sec: 1.06x faster                                               |
| unpickle                 | 9.67 us                                                | 9.18 us: 1.05x faster                                                |
| regex_effbot             | 2.63 ms                                                | 2.51 ms: 1.05x faster                                                |
| deepcopy_memo            | 26.3 us                                                | 25.5 us: 1.03x faster                                                |
| richards_super           | 39.2 ms                                                | 38.0 ms: 1.03x faster                                                |
| pickle_pure_python       | 201 us                                                 | 195 us: 1.03x faster                                                 |
| create_gc_cycles         | 716 us                                                 | 699 us: 1.02x faster                                                 |
| async_tree_io            | 704 ms                                                 | 691 ms: 1.02x faster                                                 |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 526 ms: 1.01x faster                                                 |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                                |
| go                       | 109 ms                                                 | 108 ms: 1.01x faster                                                 |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                                |
| scimark_monte_carlo      | 46.5 ms                                                | 46.3 ms: 1.00x faster                                                |
| scimark_lu               | 73.3 ms                                                | 73.1 ms: 1.00x faster                                                |
| pidigits                 | 281 ms                                                 | 282 ms: 1.01x slower                                                 |
| coroutines               | 17.8 ms                                                | 18.0 ms: 1.01x slower                                                |
| python_startup           | 12.4 ms                                                | 12.6 ms: 1.01x slower                                                |
| xml_etree_parse          | 108 ms                                                 | 110 ms: 1.02x slower                                                 |
| logging_simple           | 3.55 us                                                | 3.63 us: 1.02x slower                                                |
| regex_v8                 | 16.1 ms                                                | 16.5 ms: 1.02x slower                                                |
| dulwich_log              | 30.3 ms                                                | 31.0 ms: 1.02x slower                                                |
| spectral_norm            | 72.6 ms                                                | 74.4 ms: 1.02x slower                                                |
| logging_format           | 3.78 us                                                | 3.88 us: 1.03x slower                                                |
| deepcopy                 | 223 us                                                 | 229 us: 1.03x slower                                                 |
| pickle_list              | 2.81 us                                                | 2.90 us: 1.03x slower                                                |
| python_startup_no_site   | 10.2 ms                                                | 10.5 ms: 1.03x slower                                                |
| unpickle_pure_python     | 159 us                                                 | 164 us: 1.03x slower                                                 |
| pickle                   | 7.15 us                                                | 7.40 us: 1.03x slower                                                |
| comprehensions           | 16.1 us                                                | 16.7 us: 1.04x slower                                                |
| docutils                 | 1.47 sec                                               | 1.53 sec: 1.04x slower                                               |
| tomli_loads              | 1.47 sec                                               | 1.53 sec: 1.05x slower                                               |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.35 ms: 1.05x slower                                                |
| scimark_fft              | 200 ms                                                 | 210 ms: 1.05x slower                                                 |
| bench_thread_pool        | 474 us                                                 | 503 us: 1.06x slower                                                 |
| logging_silent           | 68.1 ns                                                | 72.3 ns: 1.06x slower                                                |
| meteor_contest           | 73.5 ms                                                | 78.3 ms: 1.07x slower                                                |
| regex_compile            | 76.7 ms                                                | 81.8 ms: 1.07x slower                                                |
| deepcopy_reduce          | 1.91 us                                                | 2.04 us: 1.07x slower                                                |
| mdp                      | 1.55 sec                                               | 1.66 sec: 1.07x slower                                               |
| richards                 | 32.2 ms                                                | 34.7 ms: 1.08x slower                                                |
| float                    | 53.0 ms                                                | 57.1 ms: 1.08x slower                                                |
| nqueens                  | 59.8 ms                                                | 64.5 ms: 1.08x slower                                                |
| json                     | 2.78 ms                                                | 3.01 ms: 1.09x slower                                                |
| pprint_pformat           | 954 ms                                                 | 1.03 sec: 1.09x slower                                               |
| pprint_safe_repr         | 466 ms                                                 | 507 ms: 1.09x slower                                                 |
| bench_mp_pool            | 43.9 ms                                                | 48.1 ms: 1.09x slower                                                |
| json_loads               | 16.1 us                                                | 17.6 us: 1.10x slower                                                |
| pyflate                  | 310 ms                                                 | 341 ms: 1.10x slower                                                 |
| hexiom                   | 4.72 ms                                                | 5.19 ms: 1.10x slower                                                |
| xml_etree_iterparse      | 70.1 ms                                                | 77.2 ms: 1.10x slower                                                |
| fannkuch                 | 261 ms                                                 | 289 ms: 1.10x slower                                                 |
| sqlglot_normalize        | 171 ms                                                 | 193 ms: 1.13x slower                                                 |
| sqlglot_optimize         | 31.1 ms                                                | 35.4 ms: 1.14x slower                                                |
| xml_etree_process        | 35.1 ms                                                | 40.0 ms: 1.14x slower                                                |
| pathlib                  | 27.2 ms                                                | 32.1 ms: 1.18x slower                                                |
| unpickle_list            | 2.65 us                                                | 3.18 us: 1.20x slower                                                |
| nbody                    | 65.6 ms                                                | 78.8 ms: 1.20x slower                                                |
| xml_etree_generate       | 48.3 ms                                                | 58.2 ms: 1.21x slower                                                |
| sqlite_synth             | 1.27 us                                                | 1.61 us: 1.26x slower                                                |
| scimark_sor              | 82.6 ms                                                | 106 ms: 1.29x slower                                                 |
| mypy2                    | 195 ms                                                 | 264 ms: 1.35x slower                                                 |
| telco                    | 3.41 ms                                                | 4.62 ms: 1.36x slower                                                |
| async_generators         | 196 ms                                                 | 312 ms: 1.59x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.01x slower                                                         |

Benchmark hidden because not significant (3): tornado_http, async_tree_memoization, pycparser
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230906-3.13.0a0-3bafa2b/bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b.json: dask


# HPT report

- Reliability score: 99.42% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.00x
