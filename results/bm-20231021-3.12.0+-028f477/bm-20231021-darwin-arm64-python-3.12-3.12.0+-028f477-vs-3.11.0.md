
# Results vs. 3.11.0

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 028f477
- commit date: 2023-10-21
- overall geometric mean: 1.03x faster
- HPT reliability: 77.18%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 161 ms                                                 | 168 ms: 1.04x slower                                 |
| docutils       | 1.47 sec                                               | 1.50 sec: 1.02x slower                               |
| Geometric mean | (ref)                                                  | 1.02x slower                                         |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pidigits       | 281 ms                                                 | 283 ms: 1.01x slower                                 |
| nbody          | 65.6 ms                                                | 69.3 ms: 1.06x slower                                |
| float          | 53.0 ms                                                | 56.5 ms: 1.07x slower                                |
| Geometric mean | (ref)                                                  | 1.04x slower                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_v8       | 16.1 ms                                                | 15.6 ms: 1.03x faster                                |
| regex_dna      | 152 ms                                                 | 149 ms: 1.02x faster                                 |
| regex_compile  | 76.7 ms                                                | 75.1 ms: 1.02x faster                                |
| regex_effbot   | 2.63 ms                                                | 2.59 ms: 1.01x faster                                |
| Geometric mean | (ref)                                                  | 1.02x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| json_dumps           | 7.63 ms                                                | 6.31 ms: 1.21x faster                                |
| unpickle_pure_python | 159 us                                                 | 144 us: 1.11x faster                                 |
| pickle_pure_python   | 201 us                                                 | 188 us: 1.07x faster                                 |
| tomli_loads          | 1.47 sec                                               | 1.40 sec: 1.05x faster                               |
| unpickle             | 9.67 us                                                | 9.31 us: 1.04x faster                                |
| pickle_dict          | 18.0 us                                                | 17.9 us: 1.00x faster                                |
| xml_etree_parse      | 108 ms                                                 | 111 ms: 1.03x slower                                 |
| pickle_list          | 2.81 us                                                | 2.88 us: 1.03x slower                                |
| pickle               | 7.15 us                                                | 7.34 us: 1.03x slower                                |
| xml_etree_iterparse  | 70.1 ms                                                | 75.0 ms: 1.07x slower                                |
| json_loads           | 16.1 us                                                | 17.7 us: 1.10x slower                                |
| xml_etree_process    | 35.1 ms                                                | 38.7 ms: 1.10x slower                                |
| xml_etree_generate   | 48.3 ms                                                | 55.9 ms: 1.16x slower                                |
| unpickle_list        | 2.65 us                                                | 3.23 us: 1.22x slower                                |
| Geometric mean       | (ref)                                                  | 1.02x slower                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup_no_site | 10.2 ms                                                | 9.01 ms: 1.13x faster                                |
| python_startup         | 12.4 ms                                                | 11.2 ms: 1.11x faster                                |
| Geometric mean         | (ref)                                                  | 1.12x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 8.53 ms                                                | 7.52 ms: 1.14x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 90.3 us: 3.72x faster                                |
| asyncio_tcp              | 651 ms                                                 | 443 ms: 1.47x faster                                 |
| json_dumps               | 7.63 ms                                                | 6.31 ms: 1.21x faster                                |
| unpack_sequence          | 34.1 ns                                                | 28.4 ns: 1.20x faster                                |
| chaos                    | 49.4 ms                                                | 42.1 ms: 1.17x faster                                |
| deltablue                | 2.81 ms                                                | 2.40 ms: 1.17x faster                                |
| richards_super           | 39.2 ms                                                | 33.8 ms: 1.16x faster                                |
| sqlglot_parse            | 959 us                                                 | 830 us: 1.16x faster                                 |
| coverage                 | 58.4 ms                                                | 50.7 ms: 1.15x faster                                |
| asyncio_tcp_ssl          | 1.44 sec                                               | 1.25 sec: 1.15x faster                               |
| go                       | 109 ms                                                 | 94.7 ms: 1.15x faster                                |
| mako                     | 8.53 ms                                                | 7.52 ms: 1.14x faster                                |
| python_startup_no_site   | 10.2 ms                                                | 9.01 ms: 1.13x faster                                |
| python_startup           | 12.4 ms                                                | 11.2 ms: 1.11x faster                                |
| sqlglot_transpile        | 1.12 ms                                                | 1.01 ms: 1.11x faster                                |
| hexiom                   | 4.72 ms                                                | 4.26 ms: 1.11x faster                                |
| unpickle_pure_python     | 159 us                                                 | 144 us: 1.11x faster                                 |
| generators               | 28.8 ms                                                | 26.2 ms: 1.10x faster                                |
| async_tree_none          | 286 ms                                                 | 263 ms: 1.09x faster                                 |
| async_tree_memoization   | 336 ms                                                 | 311 ms: 1.08x faster                                 |
| scimark_monte_carlo      | 46.5 ms                                                | 43.2 ms: 1.08x faster                                |
| pickle_pure_python       | 201 us                                                 | 188 us: 1.07x faster                                 |
| richards                 | 32.2 ms                                                | 30.3 ms: 1.07x faster                                |
| async_tree_io            | 704 ms                                                 | 662 ms: 1.06x faster                                 |
| comprehensions           | 16.1 us                                                | 15.2 us: 1.06x faster                                |
| deepcopy_memo            | 26.3 us                                                | 24.9 us: 1.06x faster                                |
| tomli_loads              | 1.47 sec                                               | 1.40 sec: 1.05x faster                               |
| sqlalchemy_imperative    | 7.20 ms                                                | 6.88 ms: 1.05x faster                                |
| unpickle                 | 9.67 us                                                | 9.31 us: 1.04x faster                                |
| pycparser                | 698 ms                                                 | 673 ms: 1.04x faster                                 |
| regex_v8                 | 16.1 ms                                                | 15.6 ms: 1.03x faster                                |
| create_gc_cycles         | 716 us                                                 | 695 us: 1.03x faster                                 |
| mypy2                    | 195 ms                                                 | 190 ms: 1.03x faster                                 |
| coroutines               | 17.8 ms                                                | 17.3 ms: 1.03x faster                                |
| regex_dna                | 152 ms                                                 | 149 ms: 1.02x faster                                 |
| regex_compile            | 76.7 ms                                                | 75.1 ms: 1.02x faster                                |
| scimark_lu               | 73.3 ms                                                | 71.9 ms: 1.02x faster                                |
| regex_effbot             | 2.63 ms                                                | 2.59 ms: 1.01x faster                                |
| async_tree_cpu_io_mixed  | 533 ms                                                 | 527 ms: 1.01x faster                                 |
| meteor_contest           | 73.5 ms                                                | 72.8 ms: 1.01x faster                                |
| gc_traversal             | 2.42 ms                                                | 2.40 ms: 1.01x faster                                |
| dulwich_log              | 30.3 ms                                                | 30.2 ms: 1.00x faster                                |
| pickle_dict              | 18.0 us                                                | 17.9 us: 1.00x faster                                |
| raytrace                 | 207 ms                                                 | 207 ms: 1.00x faster                                 |
| scimark_fft              | 200 ms                                                 | 200 ms: 1.00x slower                                 |
| logging_silent           | 68.1 ns                                                | 68.3 ns: 1.00x slower                                |
| crypto_pyaes             | 51.7 ms                                                | 52.0 ms: 1.01x slower                                |
| pidigits                 | 281 ms                                                 | 283 ms: 1.01x slower                                 |
| logging_simple           | 3.55 us                                                | 3.60 us: 1.02x slower                                |
| deepcopy                 | 223 us                                                 | 227 us: 1.02x slower                                 |
| pyflate                  | 310 ms                                                 | 316 ms: 1.02x slower                                 |
| fannkuch                 | 261 ms                                                 | 267 ms: 1.02x slower                                 |
| docutils                 | 1.47 sec                                               | 1.50 sec: 1.02x slower                               |
| bench_thread_pool        | 474 us                                                 | 486 us: 1.02x slower                                 |
| xml_etree_parse          | 108 ms                                                 | 111 ms: 1.03x slower                                 |
| pickle_list              | 2.81 us                                                | 2.88 us: 1.03x slower                                |
| logging_format           | 3.78 us                                                | 3.88 us: 1.03x slower                                |
| pickle                   | 7.15 us                                                | 7.34 us: 1.03x slower                                |
| spectral_norm            | 72.6 ms                                                | 74.9 ms: 1.03x slower                                |
| sqlalchemy_declarative   | 62.6 ms                                                | 64.7 ms: 1.03x slower                                |
| scimark_sor              | 82.6 ms                                                | 85.9 ms: 1.04x slower                                |
| 2to3                     | 161 ms                                                 | 168 ms: 1.04x slower                                 |
| pprint_pformat           | 954 ms                                                 | 997 ms: 1.05x slower                                 |
| mdp                      | 1.55 sec                                               | 1.63 sec: 1.05x slower                               |
| nbody                    | 65.6 ms                                                | 69.3 ms: 1.06x slower                                |
| float                    | 53.0 ms                                                | 56.5 ms: 1.07x slower                                |
| xml_etree_iterparse      | 70.1 ms                                                | 75.0 ms: 1.07x slower                                |
| pathlib                  | 27.2 ms                                                | 29.1 ms: 1.07x slower                                |
| pprint_safe_repr         | 466 ms                                                 | 499 ms: 1.07x slower                                 |
| json                     | 2.78 ms                                                | 2.98 ms: 1.07x slower                                |
| deepcopy_reduce          | 1.91 us                                                | 2.05 us: 1.07x slower                                |
| sqlglot_normalize        | 171 ms                                                 | 186 ms: 1.09x slower                                 |
| json_loads               | 16.1 us                                                | 17.7 us: 1.10x slower                                |
| sqlglot_optimize         | 31.1 ms                                                | 34.3 ms: 1.10x slower                                |
| xml_etree_process        | 35.1 ms                                                | 38.7 ms: 1.10x slower                                |
| telco                    | 3.41 ms                                                | 3.84 ms: 1.13x slower                                |
| xml_etree_generate       | 48.3 ms                                                | 55.9 ms: 1.16x slower                                |
| unpickle_list            | 2.65 us                                                | 3.23 us: 1.22x slower                                |
| sqlite_synth             | 1.27 us                                                | 1.59 us: 1.25x slower                                |
| async_generators         | 196 ms                                                 | 306 ms: 1.56x slower                                 |
| Geometric mean           | (ref)                                                  | 1.03x faster                                         |

Benchmark hidden because not significant (4): tornado_http, nqueens, scimark_sparse_mat_mult, bench_mp_pool
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
Ignored benchmarks (1) of results/bm-20231021-3.12.0+-028f477/bm-20231021-darwin-arm64-python-3.12-3.12.0+-028f477.json: dask


# HPT report

- Reliability score: 77.18% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
