
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 5afac0c
- commit date: 2023-10-09
- overall geometric mean: 1.01x faster
- HPT reliability: 72.05%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 161 ms                                                 | 171 ms: 1.06x slower                                 |
| docutils       | 1.47 sec                                               | 1.54 sec: 1.05x slower                               |
| Geometric mean | (ref)                                                  | 1.03x slower                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 282 ms: 1.01x slower                                 |
| nbody          | 65.6 ms                                                | 68.7 ms: 1.05x slower                                |
| float          | 53.0 ms                                                | 58.0 ms: 1.09x slower                                |
| Geometric mean | (ref)                                                  | 1.05x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                 |
| regex_effbot   | 2.63 ms                                                | 2.59 ms: 1.02x faster                                |
| regex_v8       | 16.1 ms                                                | 15.9 ms: 1.01x faster                                |
| regex_compile  | 76.7 ms                                                | 75.8 ms: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.42 ms: 1.19x faster                                |
| unpickle_pure_python | 159 us                                                 | 144 us: 1.11x faster                                 |
| pickle_pure_python   | 201 us                                                 | 189 us: 1.06x faster                                 |
| tomli_loads          | 1.47 sec                                               | 1.39 sec: 1.05x faster                               |
| unpickle             | 9.67 us                                                | 9.28 us: 1.04x faster                                |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.02x slower                                 |
| pickle               | 7.15 us                                                | 7.35 us: 1.03x slower                                |
| pickle_list          | 2.81 us                                                | 2.91 us: 1.03x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.5 ms: 1.08x slower                                |
| json_loads           | 16.1 us                                                | 17.6 us: 1.09x slower                                |
| xml_etree_process    | 35.1 ms                                                | 38.6 ms: 1.10x slower                                |
| xml_etree_generate   | 48.3 ms                                                | 55.9 ms: 1.16x slower                                |
| unpickle_list        | 2.65 us                                                | 3.26 us: 1.23x slower                                |
| Geometric mean       | (ref)                                                  | 1.02x slower                                         |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 12.4 ms                                                | 12.1 ms: 1.03x faster                                |
| python_startup_no_site | 10.2 ms                                                | 9.90 ms: 1.03x faster                                |
| Geometric mean         | (ref)                                                  | 1.03x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.55 ms: 1.13x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 91.2 us: 3.68x faster                                |
| asyncio_tcp              | 651 ms                                                 | 462 ms: 1.41x faster                                 |
| json_dumps               | 7.63 ms                                                | 6.42 ms: 1.19x faster                                |
| unpack_sequence          | 34.1 ns                                                | 28.8 ns: 1.18x faster                                |
| coverage                 | 58.4 ms                                                | 50.9 ms: 1.15x faster                                |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.26 sec: 1.15x faster                               |
| mako                     | 8.53 ms                                                | 7.55 ms: 1.13x faster                                |
| richards_super           | 39.2 ms                                                | 35.2 ms: 1.12x faster                                |
| hexiom                   | 4.72 ms                                                | 4.24 ms: 1.11x faster                                |
| unpickle_pure_python     | 159 us                                                 | 144 us: 1.11x faster                                 |
| async_tree_none          | 286 ms                                                 | 262 ms: 1.09x faster                                 |
| chaos                    | 49.4 ms                                                | 45.5 ms: 1.09x faster                                |
| deltablue                | 2.81 ms                                                | 2.59 ms: 1.09x faster                                |
| async_tree_memoization   | 336 ms                                                 | 310 ms: 1.08x faster                                 |
| sqlglot_parse            | 959 us                                                 | 898 us: 1.07x faster                                 |
| deepcopy_memo            | 26.3 us                                                | 24.7 us: 1.07x faster                                |
| pickle_pure_python       | 201 us                                                 | 189 us: 1.06x faster                                 |
| async_tree_io            | 704 ms                                                 | 667 ms: 1.06x faster                                 |
| tomli_loads              | 1.47 sec                                               | 1.39 sec: 1.05x faster                               |
| unpickle                 | 9.67 us                                                | 9.28 us: 1.04x faster                                |
| sqlglot_transpile        | 1.12 ms                                                | 1.08 ms: 1.04x faster                                |
| sqlalchemy_imperative    | 7.20 ms                                                | 6.96 ms: 1.03x faster                                |
| python_startup           | 12.4 ms                                                | 12.1 ms: 1.03x faster                                |
| pycparser                | 698 ms                                                 | 677 ms: 1.03x faster                                 |
| python_startup_no_site   | 10.2 ms                                                | 9.90 ms: 1.03x faster                                |
| create_gc_cycles         | 716 us                                                 | 697 us: 1.03x faster                                 |
| richards                 | 32.2 ms                                                | 31.4 ms: 1.03x faster                                |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                 |
| scimark_lu               | 73.3 ms                                                | 72.1 ms: 1.02x faster                                |
| regex_effbot             | 2.63 ms                                                | 2.59 ms: 1.02x faster                                |
| mypy2                    | 195 ms                                                 | 192 ms: 1.02x faster                                 |
| regex_v8                 | 16.1 ms                                                | 15.9 ms: 1.01x faster                                |
| regex_compile            | 76.7 ms                                                | 75.8 ms: 1.01x faster                                |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 527 ms: 1.01x faster                                 |
| go                       | 109 ms                                                 | 107 ms: 1.01x faster                                 |
| generators               | 28.8 ms                                                | 28.6 ms: 1.01x faster                                |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.18 ms: 1.01x faster                                |
| logging_silent           | 68.1 ns                                                | 67.9 ns: 1.00x faster                                |
| meteor_contest           | 73.5 ms                                                | 73.8 ms: 1.00x slower                                |
| dulwich_log              | 30.3 ms                                                | 30.5 ms: 1.01x slower                                |
| pidigits                 | 281 ms                                                 | 282 ms: 1.01x slower                                 |
| fannkuch                 | 261 ms                                                 | 263 ms: 1.01x slower                                 |
| nqueens                  | 59.8 ms                                                | 60.2 ms: 1.01x slower                                |
| deepcopy                 | 223 us                                                 | 225 us: 1.01x slower                                 |
| coroutines               | 17.8 ms                                                | 18.1 ms: 1.02x slower                                |
| crypto_pyaes             | 51.7 ms                                                | 52.6 ms: 1.02x slower                                |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.02x slower                                 |
| bench_mp_pool            | 43.9 ms                                                | 45.0 ms: 1.03x slower                                |
| pickle                   | 7.15 us                                                | 7.35 us: 1.03x slower                                |
| spectral_norm            | 72.6 ms                                                | 74.7 ms: 1.03x slower                                |
| bench_thread_pool        | 474 us                                                 | 488 us: 1.03x slower                                 |
| pickle_list              | 2.81 us                                                | 2.91 us: 1.03x slower                                |
| docutils                 | 1.47 sec                                               | 1.54 sec: 1.05x slower                               |
| nbody                    | 65.6 ms                                                | 68.7 ms: 1.05x slower                                |
| sqlalchemy_declarative   | 62.6 ms                                                | 65.6 ms: 1.05x slower                                |
| pprint_pformat           | 954 ms                                                 | 1.00 sec: 1.05x slower                               |
| logging_simple           | 3.55 us                                                | 3.73 us: 1.05x slower                                |
| deepcopy_reduce          | 1.91 us                                                | 2.01 us: 1.05x slower                                |
| pprint_safe_repr         | 466 ms                                                 | 492 ms: 1.06x slower                                 |
| 2to3                     | 161 ms                                                 | 171 ms: 1.06x slower                                 |
| logging_format           | 3.78 us                                                | 4.00 us: 1.06x slower                                |
| pyflate                  | 310 ms                                                 | 330 ms: 1.06x slower                                 |
| json                     | 2.78 ms                                                | 2.98 ms: 1.07x slower                                |
| scimark_monte_carlo      | 46.5 ms                                                | 50.0 ms: 1.08x slower                                |
| xml_etree_iterparse      | 70.1 ms                                                | 75.5 ms: 1.08x slower                                |
| mdp                      | 1.55 sec                                               | 1.67 sec: 1.08x slower                               |
| pathlib                  | 27.2 ms                                                | 29.5 ms: 1.08x slower                                |
| sqlglot_normalize        | 171 ms                                                 | 186 ms: 1.09x slower                                 |
| json_loads               | 16.1 us                                                | 17.6 us: 1.09x slower                                |
| float                    | 53.0 ms                                                | 58.0 ms: 1.09x slower                                |
| xml_etree_process        | 35.1 ms                                                | 38.6 ms: 1.10x slower                                |
| sqlglot_optimize         | 31.1 ms                                                | 34.4 ms: 1.11x slower                                |
| telco                    | 3.41 ms                                                | 3.83 ms: 1.12x slower                                |
| scimark_sor              | 82.6 ms                                                | 95.4 ms: 1.16x slower                                |
| xml_etree_generate       | 48.3 ms                                                | 55.9 ms: 1.16x slower                                |
| raytrace                 | 207 ms                                                 | 246 ms: 1.19x slower                                 |
| unpickle_list            | 2.65 us                                                | 3.26 us: 1.23x slower                                |
| sqlite_synth             | 1.27 us                                                | 1.58 us: 1.25x slower                                |
| async_generators         | 196 ms                                                 | 304 ms: 1.55x slower                                 |
| Geometric mean           | (ref)                                                  | 1.01x faster                                         |

Benchmark hidden because not significant (4): tornado_http, comprehensions, scimark_fft, pickle_dict
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20231009-3.12.0+-5afac0c/bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c.json: dask


# HPT report

- Reliability score: 72.05% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
