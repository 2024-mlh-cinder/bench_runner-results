
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: a52213b
- commit date: 2023-09-02
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.50 sec: 1.18x faster                                |
| tornado_http   | 91.9 ms                                                | 70.5 ms: 1.30x faster                                 |
| Geometric mean | (ref)                                                  | 1.24x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 94.1 ms                                                | 69.5 ms: 1.35x faster                                 |
| float          | 72.3 ms                                                | 54.9 ms: 1.32x faster                                 |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                  |
| Geometric mean | (ref)                                                  | 1.21x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 76.7 ms: 1.26x faster                                 |
| regex_dna      | 160 ms                                                 | 149 ms: 1.07x faster                                  |
| regex_v8       | 17.5 ms                                                | 16.8 ms: 1.04x faster                                 |
| regex_effbot   | 2.45 ms                                                | 2.55 ms: 1.04x slower                                 |
| Geometric mean | (ref)                                                  | 1.08x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 192 us: 1.48x faster                                  |
| unpickle_pure_python | 203 us                                                 | 156 us: 1.31x faster                                  |
| json_dumps           | 8.38 ms                                                | 6.57 ms: 1.28x faster                                 |
| xml_etree_process    | 45.1 ms                                                | 39.2 ms: 1.15x faster                                 |
| tomli_loads          | 1.76 sec                                               | 1.54 sec: 1.14x faster                                |
| unpickle             | 9.77 us                                                | 9.06 us: 1.08x faster                                 |
| pickle               | 7.36 us                                                | 7.44 us: 1.01x slower                                 |
| pickle_dict          | 17.8 us                                                | 18.1 us: 1.02x slower                                 |
| pickle_list          | 2.83 us                                                | 2.89 us: 1.02x slower                                 |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                  |
| xml_etree_iterparse  | 72.6 ms                                                | 75.1 ms: 1.03x slower                                 |
| json_loads           | 16.9 us                                                | 17.5 us: 1.04x slower                                 |
| xml_etree_generate   | 54.3 ms                                                | 57.3 ms: 1.06x slower                                 |
| unpickle_list        | 2.66 us                                                | 3.13 us: 1.18x slower                                 |
| Geometric mean       | (ref)                                                  | 1.07x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 11.6 ms: 1.08x faster                                 |
| python_startup_no_site | 9.73 ms                                                | 9.50 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.05x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.30 ms: 1.44x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230902-darwin-arm64-python-main-3.13.0a0-a52213b |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 92.6 us: 3.71x faster                                 |
| deltablue                | 5.15 ms                                                | 2.38 ms: 2.16x faster                                 |
| raytrace                 | 328 ms                                                 | 176 ms: 1.86x faster                                  |
| logging_silent           | 119 ns                                                 | 68.8 ns: 1.73x faster                                 |
| sqlglot_parse            | 1.33 ms                                                | 798 us: 1.67x faster                                  |
| chaos                    | 66.8 ms                                                | 40.1 ms: 1.67x faster                                 |
| crypto_pyaes             | 78.0 ms                                                | 47.0 ms: 1.66x faster                                 |
| asyncio_tcp              | 673 ms                                                 | 410 ms: 1.64x faster                                  |
| async_tree_none          | 402 ms                                                 | 251 ms: 1.60x faster                                  |
| scimark_monte_carlo      | 72.2 ms                                                | 45.1 ms: 1.60x faster                                 |
| richards_super           | 60.7 ms                                                | 38.2 ms: 1.59x faster                                 |
| go                       | 165 ms                                                 | 104 ms: 1.59x faster                                  |
| sqlglot_transpile        | 1.54 ms                                                | 971 us: 1.58x faster                                  |
| scimark_lu               | 110 ms                                                 | 70.2 ms: 1.57x faster                                 |
| async_tree_memoization   | 493 ms                                                 | 328 ms: 1.51x faster                                  |
| async_tree_io            | 1.02 sec                                               | 686 ms: 1.49x faster                                  |
| richards                 | 51.4 ms                                                | 34.7 ms: 1.48x faster                                 |
| pickle_pure_python       | 284 us                                                 | 192 us: 1.48x faster                                  |
| unpack_sequence          | 38.7 ns                                                | 26.4 ns: 1.46x faster                                 |
| deepcopy_memo            | 34.5 us                                                | 23.9 us: 1.44x faster                                 |
| mako                     | 10.5 ms                                                | 7.30 ms: 1.44x faster                                 |
| spectral_norm            | 96.4 ms                                                | 70.8 ms: 1.36x faster                                 |
| generators               | 32.9 ms                                                | 24.3 ms: 1.36x faster                                 |
| nbody                    | 94.1 ms                                                | 69.5 ms: 1.35x faster                                 |
| hexiom                   | 6.32 ms                                                | 4.70 ms: 1.34x faster                                 |
| pycparser                | 915 ms                                                 | 689 ms: 1.33x faster                                  |
| pyflate                  | 453 ms                                                 | 342 ms: 1.33x faster                                  |
| float                    | 72.3 ms                                                | 54.9 ms: 1.32x faster                                 |
| unpickle_pure_python     | 203 us                                                 | 156 us: 1.31x faster                                  |
| tornado_http             | 91.9 ms                                                | 70.5 ms: 1.30x faster                                 |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 522 ms: 1.28x faster                                  |
| json_dumps               | 8.38 ms                                                | 6.57 ms: 1.28x faster                                 |
| logging_format           | 5.01 us                                                | 3.93 us: 1.28x faster                                 |
| logging_simple           | 4.63 us                                                | 3.64 us: 1.27x faster                                 |
| regex_compile            | 96.6 ms                                                | 76.7 ms: 1.26x faster                                 |
| create_gc_cycles         | 876 us                                                 | 700 us: 1.25x faster                                  |
| deepcopy                 | 278 us                                                 | 225 us: 1.24x faster                                  |
| pprint_pformat           | 1.24 sec                                               | 1.01 sec: 1.23x faster                                |
| scimark_sor              | 127 ms                                                 | 103 ms: 1.23x faster                                  |
| pprint_safe_repr         | 609 ms                                                 | 497 ms: 1.22x faster                                  |
| dulwich_log              | 37.1 ms                                                | 30.5 ms: 1.21x faster                                 |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.36 sec: 1.21x faster                                |
| mypy2                    | 308 ms                                                 | 256 ms: 1.20x faster                                  |
| comprehensions           | 17.7 us                                                | 14.7 us: 1.20x faster                                 |
| deepcopy_reduce          | 2.38 us                                                | 2.00 us: 1.19x faster                                 |
| docutils                 | 1.78 sec                                               | 1.50 sec: 1.18x faster                                |
| scimark_fft              | 232 ms                                                 | 198 ms: 1.17x faster                                  |
| nqueens                  | 68.1 ms                                                | 58.6 ms: 1.16x faster                                 |
| xml_etree_process        | 45.1 ms                                                | 39.2 ms: 1.15x faster                                 |
| bench_thread_pool        | 548 us                                                 | 479 us: 1.14x faster                                  |
| tomli_loads              | 1.76 sec                                               | 1.54 sec: 1.14x faster                                |
| fannkuch                 | 317 ms                                                 | 281 ms: 1.13x faster                                  |
| coroutines               | 20.2 ms                                                | 17.9 ms: 1.13x faster                                 |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.11 ms: 1.12x faster                                 |
| sqlglot_optimize         | 38.0 ms                                                | 34.4 ms: 1.11x faster                                 |
| python_startup           | 12.6 ms                                                | 11.6 ms: 1.08x faster                                 |
| unpickle                 | 9.77 us                                                | 9.06 us: 1.08x faster                                 |
| regex_dna                | 160 ms                                                 | 149 ms: 1.07x faster                                  |
| meteor_contest           | 78.6 ms                                                | 74.7 ms: 1.05x faster                                 |
| sqlglot_normalize        | 197 ms                                                 | 187 ms: 1.05x faster                                  |
| regex_v8                 | 17.5 ms                                                | 16.8 ms: 1.04x faster                                 |
| mdp                      | 1.67 sec                                               | 1.61 sec: 1.04x faster                                |
| json                     | 3.10 ms                                                | 2.99 ms: 1.03x faster                                 |
| python_startup_no_site   | 9.73 ms                                                | 9.50 ms: 1.02x faster                                 |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x slower                                  |
| pickle                   | 7.36 us                                                | 7.44 us: 1.01x slower                                 |
| pickle_dict              | 17.8 us                                                | 18.1 us: 1.02x slower                                 |
| pickle_list              | 2.83 us                                                | 2.89 us: 1.02x slower                                 |
| xml_etree_parse          | 107 ms                                                 | 110 ms: 1.03x slower                                  |
| xml_etree_iterparse      | 72.6 ms                                                | 75.1 ms: 1.03x slower                                 |
| json_loads               | 16.9 us                                                | 17.5 us: 1.04x slower                                 |
| regex_effbot             | 2.45 ms                                                | 2.55 ms: 1.04x slower                                 |
| xml_etree_generate       | 54.3 ms                                                | 57.3 ms: 1.06x slower                                 |
| sqlite_synth             | 1.47 us                                                | 1.59 us: 1.08x slower                                 |
| bench_mp_pool            | 41.0 ms                                                | 45.8 ms: 1.12x slower                                 |
| pathlib                  | 28.8 ms                                                | 32.2 ms: 1.12x slower                                 |
| coverage                 | 40.8 ms                                                | 47.6 ms: 1.17x slower                                 |
| unpickle_list            | 2.66 us                                                | 3.13 us: 1.18x slower                                 |
| telco                    | 3.68 ms                                                | 4.69 ms: 1.28x slower                                 |
| dask                     | 258 ms                                                 | 330 ms: 1.28x slower                                  |
| async_generators         | 233 ms                                                 | 304 ms: 1.30x slower                                  |
| Geometric mean           | (ref)                                                  | 1.23x faster                                          |

Benchmark hidden because not significant (1): gc_traversal
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.14x
