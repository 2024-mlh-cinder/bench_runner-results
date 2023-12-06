
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.02x faster
- HPT reliability: 57.75%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.48 sec: 1.01x slower                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| float          | 53.0 ms                                                | 54.7 ms: 1.03x slower                                  |
| nbody          | 65.6 ms                                                | 71.3 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                   |
| regex_effbot   | 2.63 ms                                                | 2.57 ms: 1.02x faster                                  |
| regex_compile  | 76.7 ms                                                | 75.6 ms: 1.02x faster                                  |
| regex_v8       | 16.1 ms                                                | 16.8 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.44 ms: 1.18x faster                                  |
| unpickle             | 9.67 us                                                | 9.05 us: 1.07x faster                                  |
| pickle_pure_python   | 201 us                                                 | 193 us: 1.04x faster                                   |
| unpickle_pure_python | 159 us                                                 | 157 us: 1.02x faster                                   |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.01x faster                                  |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.02x slower                                   |
| pickle_list          | 2.81 us                                                | 2.89 us: 1.03x slower                                  |
| pickle               | 7.15 us                                                | 7.40 us: 1.03x slower                                  |
| tomli_loads          | 1.47 sec                                               | 1.54 sec: 1.05x slower                                 |
| xml_etree_iterparse  | 70.1 ms                                                | 75.3 ms: 1.07x slower                                  |
| json_loads           | 16.1 us                                                | 17.4 us: 1.08x slower                                  |
| xml_etree_process    | 35.1 ms                                                | 39.0 ms: 1.11x slower                                  |
| xml_etree_generate   | 48.3 ms                                                | 57.2 ms: 1.19x slower                                  |
| unpickle_list        | 2.65 us                                                | 3.15 us: 1.19x slower                                  |
| Geometric mean       | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 10.3 ms: 1.01x slower                                  |
| python_startup         | 12.4 ms                                                | 12.7 ms: 1.02x slower                                  |
| Geometric mean         | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.34 ms: 1.16x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 94.4 us: 3.56x faster                                  |
| asyncio_tcp              | 651 ms                                                 | 420 ms: 1.55x faster                                   |
| unpack_sequence          | 34.1 ns                                                | 26.4 ns: 1.29x faster                                  |
| coverage                 | 58.4 ms                                                | 47.0 ms: 1.24x faster                                  |
| chaos                    | 49.4 ms                                                | 40.1 ms: 1.23x faster                                  |
| sqlglot_parse            | 959 us                                                 | 797 us: 1.20x faster                                   |
| deltablue                | 2.81 ms                                                | 2.34 ms: 1.20x faster                                  |
| raytrace                 | 207 ms                                                 | 173 ms: 1.19x faster                                   |
| generators               | 28.8 ms                                                | 24.1 ms: 1.19x faster                                  |
| json_dumps               | 7.63 ms                                                | 6.44 ms: 1.18x faster                                  |
| mako                     | 8.53 ms                                                | 7.34 ms: 1.16x faster                                  |
| sqlglot_transpile        | 1.12 ms                                                | 970 us: 1.16x faster                                   |
| async_tree_none          | 286 ms                                                 | 250 ms: 1.14x faster                                   |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.30 sec: 1.11x faster                                 |
| comprehensions           | 16.1 us                                                | 14.6 us: 1.10x faster                                  |
| crypto_pyaes             | 51.7 ms                                                | 47.1 ms: 1.10x faster                                  |
| deepcopy_memo            | 26.3 us                                                | 24.0 us: 1.10x faster                                  |
| richards_super           | 39.2 ms                                                | 36.2 ms: 1.08x faster                                  |
| unpickle                 | 9.67 us                                                | 9.05 us: 1.07x faster                                  |
| go                       | 109 ms                                                 | 104 ms: 1.05x faster                                   |
| scimark_lu               | 73.3 ms                                                | 70.0 ms: 1.05x faster                                  |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.06 ms: 1.04x faster                                  |
| nqueens                  | 59.8 ms                                                | 57.4 ms: 1.04x faster                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 44.8 ms: 1.04x faster                                  |
| pickle_pure_python       | 201 us                                                 | 193 us: 1.04x faster                                   |
| hexiom                   | 4.72 ms                                                | 4.58 ms: 1.03x faster                                  |
| spectral_norm            | 72.6 ms                                                | 70.5 ms: 1.03x faster                                  |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 522 ms: 1.02x faster                                   |
| regex_effbot             | 2.63 ms                                                | 2.57 ms: 1.02x faster                                  |
| create_gc_cycles         | 716 us                                                 | 701 us: 1.02x faster                                   |
| unpickle_pure_python     | 159 us                                                 | 157 us: 1.02x faster                                   |
| regex_compile            | 76.7 ms                                                | 75.6 ms: 1.02x faster                                  |
| scimark_fft              | 200 ms                                                 | 197 ms: 1.01x faster                                   |
| async_tree_io            | 704 ms                                                 | 698 ms: 1.01x faster                                   |
| deepcopy                 | 223 us                                                 | 221 us: 1.01x faster                                   |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.01x faster                                  |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                  |
| logging_silent           | 68.1 ns                                                | 67.7 ns: 1.01x faster                                  |
| meteor_contest           | 73.5 ms                                                | 73.7 ms: 1.00x slower                                  |
| pidigits                 | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| docutils                 | 1.47 sec                                               | 1.48 sec: 1.01x slower                                 |
| bench_thread_pool        | 474 us                                                 | 479 us: 1.01x slower                                   |
| python_startup_no_site   | 10.2 ms                                                | 10.3 ms: 1.01x slower                                  |
| logging_format           | 3.78 us                                                | 3.84 us: 1.01x slower                                  |
| richards                 | 32.2 ms                                                | 32.8 ms: 1.02x slower                                  |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.02x slower                                   |
| python_startup           | 12.4 ms                                                | 12.7 ms: 1.02x slower                                  |
| pickle_list              | 2.81 us                                                | 2.89 us: 1.03x slower                                  |
| deepcopy_reduce          | 1.91 us                                                | 1.97 us: 1.03x slower                                  |
| float                    | 53.0 ms                                                | 54.7 ms: 1.03x slower                                  |
| pickle                   | 7.15 us                                                | 7.40 us: 1.03x slower                                  |
| regex_v8                 | 16.1 ms                                                | 16.8 ms: 1.04x slower                                  |
| bench_mp_pool            | 43.9 ms                                                | 45.9 ms: 1.04x slower                                  |
| mdp                      | 1.55 sec                                               | 1.62 sec: 1.05x slower                                 |
| tomli_loads              | 1.47 sec                                               | 1.54 sec: 1.05x slower                                 |
| sqlglot_normalize        | 171 ms                                                 | 182 ms: 1.07x slower                                   |
| pprint_pformat           | 954 ms                                                 | 1.02 sec: 1.07x slower                                 |
| xml_etree_iterparse      | 70.1 ms                                                | 75.3 ms: 1.07x slower                                  |
| pprint_safe_repr         | 466 ms                                                 | 502 ms: 1.08x slower                                   |
| fannkuch                 | 261 ms                                                 | 282 ms: 1.08x slower                                   |
| pyflate                  | 310 ms                                                 | 334 ms: 1.08x slower                                   |
| json_loads               | 16.1 us                                                | 17.4 us: 1.08x slower                                  |
| pathlib                  | 27.2 ms                                                | 29.6 ms: 1.09x slower                                  |
| nbody                    | 65.6 ms                                                | 71.3 ms: 1.09x slower                                  |
| sqlglot_optimize         | 31.1 ms                                                | 34.0 ms: 1.09x slower                                  |
| json                     | 2.78 ms                                                | 3.04 ms: 1.10x slower                                  |
| xml_etree_process        | 35.1 ms                                                | 39.0 ms: 1.11x slower                                  |
| xml_etree_generate       | 48.3 ms                                                | 57.2 ms: 1.19x slower                                  |
| unpickle_list            | 2.65 us                                                | 3.15 us: 1.19x slower                                  |
| scimark_sor              | 82.6 ms                                                | 103 ms: 1.25x slower                                   |
| sqlite_synth             | 1.27 us                                                | 1.63 us: 1.28x slower                                  |
| mypy2                    | 195 ms                                                 | 259 ms: 1.33x slower                                   |
| telco                    | 3.41 ms                                                | 4.63 ms: 1.36x slower                                  |
| async_generators         | 196 ms                                                 | 300 ms: 1.53x slower                                   |
| Geometric mean           | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (6): tornado_http, async_tree_memoization, pycparser, coroutines, logging_simple, dulwich_log
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 57.75% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
