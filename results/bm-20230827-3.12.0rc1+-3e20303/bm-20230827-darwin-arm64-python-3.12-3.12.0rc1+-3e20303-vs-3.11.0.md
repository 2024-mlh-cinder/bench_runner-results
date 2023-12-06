
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.02x faster
- HPT reliability: 76.09%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 161 ms                                                 | 168 ms: 1.04x slower                                    |
| docutils       | 1.47 sec                                               | 1.50 sec: 1.02x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                            |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.00x slower                                    |
| nbody          | 65.6 ms                                                | 69.2 ms: 1.06x slower                                   |
| float          | 53.0 ms                                                | 56.6 ms: 1.07x slower                                   |
| Geometric mean | (ref)                                                  | 1.04x slower                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_effbot   | 2.63 ms                                                | 2.55 ms: 1.03x faster                                   |
| regex_compile  | 76.7 ms                                                | 75.6 ms: 1.02x faster                                   |
| regex_v8       | 16.1 ms                                                | 15.9 ms: 1.01x faster                                   |
| regex_dna      | 152 ms                                                 | 150 ms: 1.01x faster                                    |
| Geometric mean | (ref)                                                  | 1.02x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.37 ms: 1.20x faster                                   |
| unpickle_pure_python | 159 us                                                 | 146 us: 1.09x faster                                    |
| pickle_pure_python   | 201 us                                                 | 190 us: 1.05x faster                                    |
| unpickle             | 9.67 us                                                | 9.20 us: 1.05x faster                                   |
| tomli_loads          | 1.47 sec                                               | 1.40 sec: 1.05x faster                                  |
| xml_etree_parse      | 108 ms                                                 | 110 ms: 1.01x slower                                    |
| pickle_list          | 2.81 us                                                | 2.90 us: 1.03x slower                                   |
| pickle               | 7.15 us                                                | 7.38 us: 1.03x slower                                   |
| xml_etree_iterparse  | 70.1 ms                                                | 74.4 ms: 1.06x slower                                   |
| json_loads           | 16.1 us                                                | 17.6 us: 1.09x slower                                   |
| xml_etree_process    | 35.1 ms                                                | 38.9 ms: 1.11x slower                                   |
| xml_etree_generate   | 48.3 ms                                                | 56.1 ms: 1.16x slower                                   |
| unpickle_list        | 2.65 us                                                | 3.18 us: 1.20x slower                                   |
| Geometric mean       | (ref)                                                  | 1.02x slower                                            |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.22 ms: 1.10x faster                                   |
| python_startup         | 12.4 ms                                                | 11.3 ms: 1.10x faster                                   |
| Geometric mean         | (ref)                                                  | 1.10x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.61 ms: 1.12x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 90.8 us: 3.70x faster                                   |
| asyncio_tcp              | 651 ms                                                 | 463 ms: 1.41x faster                                    |
| unpack_sequence          | 34.1 ns                                                | 28.3 ns: 1.20x faster                                   |
| json_dumps               | 7.63 ms                                                | 6.37 ms: 1.20x faster                                   |
| chaos                    | 49.4 ms                                                | 42.0 ms: 1.18x faster                                   |
| deltablue                | 2.81 ms                                                | 2.41 ms: 1.17x faster                                   |
| sqlglot_parse            | 959 us                                                 | 826 us: 1.16x faster                                    |
| coverage                 | 58.4 ms                                                | 50.4 ms: 1.16x faster                                   |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.24 sec: 1.16x faster                                  |
| richards_super           | 39.2 ms                                                | 33.9 ms: 1.16x faster                                   |
| go                       | 109 ms                                                 | 94.0 ms: 1.15x faster                                   |
| hexiom                   | 4.72 ms                                                | 4.19 ms: 1.13x faster                                   |
| mako                     | 8.53 ms                                                | 7.61 ms: 1.12x faster                                   |
| sqlglot_transpile        | 1.12 ms                                                | 1.00 ms: 1.12x faster                                   |
| generators               | 28.8 ms                                                | 26.0 ms: 1.11x faster                                   |
| python_startup_no_site   | 10.2 ms                                                | 9.22 ms: 1.10x faster                                   |
| python_startup           | 12.4 ms                                                | 11.3 ms: 1.10x faster                                   |
| unpickle_pure_python     | 159 us                                                 | 146 us: 1.09x faster                                    |
| async_tree_none          | 286 ms                                                 | 262 ms: 1.09x faster                                    |
| async_tree_memoization   | 336 ms                                                 | 311 ms: 1.08x faster                                    |
| async_tree_io            | 704 ms                                                 | 656 ms: 1.07x faster                                    |
| richards                 | 32.2 ms                                                | 30.1 ms: 1.07x faster                                   |
| comprehensions           | 16.1 us                                                | 15.1 us: 1.07x faster                                   |
| scimark_monte_carlo      | 46.5 ms                                                | 43.7 ms: 1.06x faster                                   |
| deepcopy_memo            | 26.3 us                                                | 24.9 us: 1.06x faster                                   |
| pickle_pure_python       | 201 us                                                 | 190 us: 1.05x faster                                    |
| unpickle                 | 9.67 us                                                | 9.20 us: 1.05x faster                                   |
| tomli_loads              | 1.47 sec                                               | 1.40 sec: 1.05x faster                                  |
| pycparser                | 698 ms                                                 | 667 ms: 1.05x faster                                    |
| regex_effbot             | 2.63 ms                                                | 2.55 ms: 1.03x faster                                   |
| sqlalchemy_imperative    | 7.20 ms                                                | 7.00 ms: 1.03x faster                                   |
| coroutines               | 17.8 ms                                                | 17.3 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 523 ms: 1.02x faster                                    |
| regex_compile            | 76.7 ms                                                | 75.6 ms: 1.02x faster                                   |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.15 ms: 1.01x faster                                   |
| regex_v8                 | 16.1 ms                                                | 15.9 ms: 1.01x faster                                   |
| regex_dna                | 152 ms                                                 | 150 ms: 1.01x faster                                    |
| create_gc_cycles         | 716 us                                                 | 709 us: 1.01x faster                                    |
| scimark_lu               | 73.3 ms                                                | 72.7 ms: 1.01x faster                                   |
| pyflate                  | 310 ms                                                 | 308 ms: 1.01x faster                                    |
| logging_silent           | 68.1 ns                                                | 67.6 ns: 1.01x faster                                   |
| dulwich_log              | 30.3 ms                                                | 30.1 ms: 1.01x faster                                   |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                   |
| crypto_pyaes             | 51.7 ms                                                | 51.5 ms: 1.00x faster                                   |
| scimark_fft              | 200 ms                                                 | 199 ms: 1.00x faster                                    |
| pidigits                 | 281 ms                                                 | 282 ms: 1.00x slower                                    |
| raytrace                 | 207 ms                                                 | 208 ms: 1.00x slower                                    |
| deepcopy                 | 223 us                                                 | 225 us: 1.01x slower                                    |
| fannkuch                 | 261 ms                                                 | 264 ms: 1.01x slower                                    |
| meteor_contest           | 73.5 ms                                                | 74.5 ms: 1.01x slower                                   |
| xml_etree_parse          | 108 ms                                                 | 110 ms: 1.01x slower                                    |
| logging_simple           | 3.55 us                                                | 3.60 us: 1.01x slower                                   |
| docutils                 | 1.47 sec                                               | 1.50 sec: 1.02x slower                                  |
| logging_format           | 3.78 us                                                | 3.87 us: 1.02x slower                                   |
| spectral_norm            | 72.6 ms                                                | 74.6 ms: 1.03x slower                                   |
| bench_thread_pool        | 474 us                                                 | 488 us: 1.03x slower                                    |
| pickle_list              | 2.81 us                                                | 2.90 us: 1.03x slower                                   |
| pickle                   | 7.15 us                                                | 7.38 us: 1.03x slower                                   |
| scimark_sor              | 82.6 ms                                                | 85.4 ms: 1.03x slower                                   |
| sqlalchemy_declarative   | 62.6 ms                                                | 64.9 ms: 1.04x slower                                   |
| bench_mp_pool            | 43.9 ms                                                | 45.6 ms: 1.04x slower                                   |
| 2to3                     | 161 ms                                                 | 168 ms: 1.04x slower                                    |
| nbody                    | 65.6 ms                                                | 69.2 ms: 1.06x slower                                   |
| mdp                      | 1.55 sec                                               | 1.63 sec: 1.06x slower                                  |
| pprint_pformat           | 954 ms                                                 | 1.01 sec: 1.06x slower                                  |
| pprint_safe_repr         | 466 ms                                                 | 494 ms: 1.06x slower                                    |
| xml_etree_iterparse      | 70.1 ms                                                | 74.4 ms: 1.06x slower                                   |
| json                     | 2.78 ms                                                | 2.97 ms: 1.07x slower                                   |
| float                    | 53.0 ms                                                | 56.6 ms: 1.07x slower                                   |
| sqlglot_normalize        | 171 ms                                                 | 184 ms: 1.07x slower                                    |
| deepcopy_reduce          | 1.91 us                                                | 2.06 us: 1.08x slower                                   |
| json_loads               | 16.1 us                                                | 17.6 us: 1.09x slower                                   |
| sqlglot_optimize         | 31.1 ms                                                | 34.1 ms: 1.10x slower                                   |
| telco                    | 3.41 ms                                                | 3.74 ms: 1.10x slower                                   |
| xml_etree_process        | 35.1 ms                                                | 38.9 ms: 1.11x slower                                   |
| xml_etree_generate       | 48.3 ms                                                | 56.1 ms: 1.16x slower                                   |
| pathlib                  | 27.2 ms                                                | 32.2 ms: 1.18x slower                                   |
| unpickle_list            | 2.65 us                                                | 3.18 us: 1.20x slower                                   |
| sqlite_synth             | 1.27 us                                                | 1.61 us: 1.26x slower                                   |
| mypy2                    | 195 ms                                                 | 256 ms: 1.31x slower                                    |
| async_generators         | 196 ms                                                 | 307 ms: 1.56x slower                                    |
| Geometric mean           | (ref)                                                  | 1.02x faster                                            |

Benchmark hidden because not significant (3): tornado_http, pickle_dict, nqueens
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20230827-3.12.0rc1+-3e20303/bm-20230827-darwin-arm64-python-3.12-3.12.0rc1+-3e20303.json: dask


# HPT report

- Reliability score: 76.09% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
