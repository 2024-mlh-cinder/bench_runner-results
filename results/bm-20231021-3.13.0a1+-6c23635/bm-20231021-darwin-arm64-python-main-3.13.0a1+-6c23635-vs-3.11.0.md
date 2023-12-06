
# Results vs. 3.11.0

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.02x faster
- HPT reliability: 52.35%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 1.47 sec                                               | 1.49 sec: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.00x faster                                           |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| float          | 53.0 ms                                                | 55.0 ms: 1.04x slower                                  |
| nbody          | 65.6 ms                                                | 71.3 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                   |
| regex_compile  | 76.7 ms                                                | 75.9 ms: 1.01x faster                                  |
| regex_v8       | 16.1 ms                                                | 16.8 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.42 ms: 1.19x faster                                  |
| unpickle             | 9.67 us                                                | 9.12 us: 1.06x faster                                  |
| pickle_pure_python   | 201 us                                                 | 195 us: 1.03x faster                                   |
| unpickle_pure_python | 159 us                                                 | 156 us: 1.02x faster                                   |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.03x slower                                   |
| pickle_list          | 2.81 us                                                | 2.89 us: 1.03x slower                                  |
| pickle               | 7.15 us                                                | 7.41 us: 1.04x slower                                  |
| tomli_loads          | 1.47 sec                                               | 1.54 sec: 1.05x slower                                 |
| json_loads           | 16.1 us                                                | 17.5 us: 1.09x slower                                  |
| xml_etree_iterparse  | 70.1 ms                                                | 76.4 ms: 1.09x slower                                  |
| xml_etree_process    | 35.1 ms                                                | 38.8 ms: 1.11x slower                                  |
| unpickle_list        | 2.65 us                                                | 3.14 us: 1.18x slower                                  |
| xml_etree_generate   | 48.3 ms                                                | 57.1 ms: 1.18x slower                                  |
| Geometric mean       | (ref)                                                  | 1.03x slower                                           |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 8.50 ms: 1.20x faster                                  |
| python_startup         | 12.4 ms                                                | 11.1 ms: 1.12x faster                                  |
| Geometric mean         | (ref)                                                  | 1.16x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.35 ms: 1.16x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 92.0 us: 3.65x faster                                  |
| asyncio_tcp              | 651 ms                                                 | 431 ms: 1.51x faster                                   |
| unpack_sequence          | 34.1 ns                                                | 26.4 ns: 1.29x faster                                  |
| coverage                 | 58.4 ms                                                | 46.8 ms: 1.25x faster                                  |
| chaos                    | 49.4 ms                                                | 40.1 ms: 1.23x faster                                  |
| sqlglot_parse            | 959 us                                                 | 794 us: 1.21x faster                                   |
| deltablue                | 2.81 ms                                                | 2.34 ms: 1.20x faster                                  |
| generators               | 28.8 ms                                                | 24.0 ms: 1.20x faster                                  |
| python_startup_no_site   | 10.2 ms                                                | 8.50 ms: 1.20x faster                                  |
| raytrace                 | 207 ms                                                 | 173 ms: 1.19x faster                                   |
| json_dumps               | 7.63 ms                                                | 6.42 ms: 1.19x faster                                  |
| sqlglot_transpile        | 1.12 ms                                                | 967 us: 1.16x faster                                   |
| mako                     | 8.53 ms                                                | 7.35 ms: 1.16x faster                                  |
| async_tree_none          | 286 ms                                                 | 251 ms: 1.14x faster                                   |
| python_startup           | 12.4 ms                                                | 11.1 ms: 1.12x faster                                  |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.30 sec: 1.11x faster                                 |
| crypto_pyaes             | 51.7 ms                                                | 46.7 ms: 1.11x faster                                  |
| comprehensions           | 16.1 us                                                | 14.6 us: 1.11x faster                                  |
| deepcopy_memo            | 26.3 us                                                | 24.0 us: 1.10x faster                                  |
| richards_super           | 39.2 ms                                                | 36.4 ms: 1.08x faster                                  |
| unpickle                 | 9.67 us                                                | 9.12 us: 1.06x faster                                  |
| go                       | 109 ms                                                 | 103 ms: 1.05x faster                                   |
| nqueens                  | 59.8 ms                                                | 57.2 ms: 1.04x faster                                  |
| scimark_sparse_mat_mult  | 3.19 ms                                                | 3.06 ms: 1.04x faster                                  |
| scimark_lu               | 73.3 ms                                                | 70.6 ms: 1.04x faster                                  |
| scimark_monte_carlo      | 46.5 ms                                                | 44.9 ms: 1.04x faster                                  |
| pickle_pure_python       | 201 us                                                 | 195 us: 1.03x faster                                   |
| hexiom                   | 4.72 ms                                                | 4.59 ms: 1.03x faster                                  |
| spectral_norm            | 72.6 ms                                                | 70.7 ms: 1.03x faster                                  |
| create_gc_cycles         | 716 us                                                 | 699 us: 1.02x faster                                   |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 523 ms: 1.02x faster                                   |
| unpickle_pure_python     | 159 us                                                 | 156 us: 1.02x faster                                   |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                   |
| scimark_fft              | 200 ms                                                 | 197 ms: 1.01x faster                                   |
| deepcopy                 | 223 us                                                 | 220 us: 1.01x faster                                   |
| coroutines               | 17.8 ms                                                | 17.5 ms: 1.01x faster                                  |
| regex_compile            | 76.7 ms                                                | 75.9 ms: 1.01x faster                                  |
| async_tree_io            | 704 ms                                                 | 698 ms: 1.01x faster                                   |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                  |
| logging_silent           | 68.1 ns                                                | 67.9 ns: 1.00x faster                                  |
| logging_simple           | 3.55 us                                                | 3.57 us: 1.01x slower                                  |
| meteor_contest           | 73.5 ms                                                | 74.0 ms: 1.01x slower                                  |
| pidigits                 | 281 ms                                                 | 283 ms: 1.01x slower                                   |
| bench_thread_pool        | 474 us                                                 | 478 us: 1.01x slower                                   |
| docutils                 | 1.47 sec                                               | 1.49 sec: 1.02x slower                                 |
| richards                 | 32.2 ms                                                | 33.0 ms: 1.02x slower                                  |
| logging_format           | 3.78 us                                                | 3.87 us: 1.02x slower                                  |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.03x slower                                   |
| pickle_list              | 2.81 us                                                | 2.89 us: 1.03x slower                                  |
| deepcopy_reduce          | 1.91 us                                                | 1.97 us: 1.03x slower                                  |
| pickle                   | 7.15 us                                                | 7.41 us: 1.04x slower                                  |
| float                    | 53.0 ms                                                | 55.0 ms: 1.04x slower                                  |
| mdp                      | 1.55 sec                                               | 1.61 sec: 1.04x slower                                 |
| regex_v8                 | 16.1 ms                                                | 16.8 ms: 1.05x slower                                  |
| tomli_loads              | 1.47 sec                                               | 1.54 sec: 1.05x slower                                 |
| sqlglot_normalize        | 171 ms                                                 | 182 ms: 1.07x slower                                   |
| pprint_pformat           | 954 ms                                                 | 1.02 sec: 1.07x slower                                 |
| json                     | 2.78 ms                                                | 2.98 ms: 1.07x slower                                  |
| pyflate                  | 310 ms                                                 | 334 ms: 1.08x slower                                   |
| pprint_safe_repr         | 466 ms                                                 | 504 ms: 1.08x slower                                   |
| fannkuch                 | 261 ms                                                 | 283 ms: 1.08x slower                                   |
| json_loads               | 16.1 us                                                | 17.5 us: 1.09x slower                                  |
| nbody                    | 65.6 ms                                                | 71.3 ms: 1.09x slower                                  |
| sqlglot_optimize         | 31.1 ms                                                | 33.8 ms: 1.09x slower                                  |
| pathlib                  | 27.2 ms                                                | 29.6 ms: 1.09x slower                                  |
| xml_etree_iterparse      | 70.1 ms                                                | 76.4 ms: 1.09x slower                                  |
| xml_etree_process        | 35.1 ms                                                | 38.8 ms: 1.11x slower                                  |
| unpickle_list            | 2.65 us                                                | 3.14 us: 1.18x slower                                  |
| xml_etree_generate       | 48.3 ms                                                | 57.1 ms: 1.18x slower                                  |
| scimark_sor              | 82.6 ms                                                | 103 ms: 1.25x slower                                   |
| sqlite_synth             | 1.27 us                                                | 1.63 us: 1.28x slower                                  |
| mypy2                    | 195 ms                                                 | 259 ms: 1.33x slower                                   |
| telco                    | 3.41 ms                                                | 4.65 ms: 1.37x slower                                  |
| async_generators         | 196 ms                                                 | 300 ms: 1.53x slower                                   |
| Geometric mean           | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (7): async_tree_memoization, tornado_http, pycparser, regex_effbot, pickle_dict, dulwich_log, bench_mp_pool
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 52.35% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
