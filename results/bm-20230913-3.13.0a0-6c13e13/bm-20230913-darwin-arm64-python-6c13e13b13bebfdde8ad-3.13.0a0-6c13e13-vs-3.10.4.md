
# Results vs. 3.10.4

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: darwin-arm64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.49 sec: 1.20x faster                                                |
| tornado_http   | 91.9 ms                                                | 70.5 ms: 1.30x faster                                                 |
| Geometric mean | (ref)                                                  | 1.25x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 94.1 ms                                                | 70.8 ms: 1.33x faster                                                 |
| float          | 72.3 ms                                                | 55.5 ms: 1.30x faster                                                 |
| Geometric mean | (ref)                                                  | 1.20x faster                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 77.0 ms: 1.25x faster                                                 |
| regex_dna      | 160 ms                                                 | 140 ms: 1.14x faster                                                  |
| regex_v8       | 17.5 ms                                                | 16.4 ms: 1.07x faster                                                 |
| regex_effbot   | 2.45 ms                                                | 2.50 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.11x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 196 us: 1.44x faster                                                  |
| json_dumps           | 8.38 ms                                                | 6.47 ms: 1.30x faster                                                 |
| unpickle_pure_python | 203 us                                                 | 158 us: 1.29x faster                                                  |
| xml_etree_process    | 45.1 ms                                                | 39.2 ms: 1.15x faster                                                 |
| tomli_loads          | 1.76 sec                                               | 1.54 sec: 1.14x faster                                                |
| unpickle             | 9.77 us                                                | 9.09 us: 1.08x faster                                                 |
| pickle_dict          | 17.8 us                                                | 18.0 us: 1.01x slower                                                 |
| xml_etree_parse      | 107 ms                                                 | 109 ms: 1.01x slower                                                  |
| json_loads           | 16.9 us                                                | 17.5 us: 1.04x slower                                                 |
| xml_etree_iterparse  | 72.6 ms                                                | 75.3 ms: 1.04x slower                                                 |
| xml_etree_generate   | 54.3 ms                                                | 57.3 ms: 1.06x slower                                                 |
| unpickle_list        | 2.66 us                                                | 3.16 us: 1.19x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.07x faster                                                          |

Benchmark hidden because not significant (2): pickle, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.0 ms: 1.05x faster                                                 |
| python_startup_no_site | 9.73 ms                                                | 9.35 ms: 1.04x faster                                                 |
| Geometric mean         | (ref)                                                  | 1.05x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.24 ms: 1.45x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-darwin-arm64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 94.2 us: 3.65x faster                                                 |
| deltablue                | 5.15 ms                                                | 2.42 ms: 2.13x faster                                                 |
| raytrace                 | 328 ms                                                 | 177 ms: 1.85x faster                                                  |
| logging_silent           | 119 ns                                                 | 70.9 ns: 1.68x faster                                                 |
| sqlglot_parse            | 1.33 ms                                                | 802 us: 1.66x faster                                                  |
| crypto_pyaes             | 78.0 ms                                                | 47.1 ms: 1.66x faster                                                 |
| chaos                    | 66.8 ms                                                | 40.3 ms: 1.66x faster                                                 |
| richards_super           | 60.7 ms                                                | 37.1 ms: 1.63x faster                                                 |
| mypy2                    | 308 ms                                                 | 189 ms: 1.63x faster                                                  |
| async_tree_none          | 402 ms                                                 | 250 ms: 1.61x faster                                                  |
| scimark_monte_carlo      | 72.2 ms                                                | 45.1 ms: 1.60x faster                                                 |
| go                       | 165 ms                                                 | 104 ms: 1.58x faster                                                  |
| sqlglot_transpile        | 1.54 ms                                                | 976 us: 1.58x faster                                                  |
| scimark_lu               | 110 ms                                                 | 71.6 ms: 1.53x faster                                                 |
| asyncio_tcp              | 673 ms                                                 | 440 ms: 1.53x faster                                                  |
| async_tree_memoization   | 493 ms                                                 | 326 ms: 1.51x faster                                                  |
| richards                 | 51.4 ms                                                | 34.2 ms: 1.50x faster                                                 |
| async_tree_io            | 1.02 sec                                               | 695 ms: 1.47x faster                                                  |
| mako                     | 10.5 ms                                                | 7.24 ms: 1.45x faster                                                 |
| pickle_pure_python       | 284 us                                                 | 196 us: 1.44x faster                                                  |
| unpack_sequence          | 38.7 ns                                                | 26.8 ns: 1.44x faster                                                 |
| deepcopy_memo            | 34.5 us                                                | 24.6 us: 1.40x faster                                                 |
| hexiom                   | 6.32 ms                                                | 4.68 ms: 1.35x faster                                                 |
| spectral_norm            | 96.4 ms                                                | 71.5 ms: 1.35x faster                                                 |
| generators               | 32.9 ms                                                | 24.5 ms: 1.34x faster                                                 |
| pyflate                  | 453 ms                                                 | 341 ms: 1.33x faster                                                  |
| pycparser                | 915 ms                                                 | 688 ms: 1.33x faster                                                  |
| nbody                    | 94.1 ms                                                | 70.8 ms: 1.33x faster                                                 |
| tornado_http             | 91.9 ms                                                | 70.5 ms: 1.30x faster                                                 |
| float                    | 72.3 ms                                                | 55.5 ms: 1.30x faster                                                 |
| json_dumps               | 8.38 ms                                                | 6.47 ms: 1.30x faster                                                 |
| logging_format           | 5.01 us                                                | 3.87 us: 1.29x faster                                                 |
| unpickle_pure_python     | 203 us                                                 | 158 us: 1.29x faster                                                  |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 521 ms: 1.29x faster                                                  |
| logging_simple           | 4.63 us                                                | 3.60 us: 1.29x faster                                                 |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.28 sec: 1.28x faster                                                |
| regex_compile            | 96.6 ms                                                | 77.0 ms: 1.25x faster                                                 |
| create_gc_cycles         | 876 us                                                 | 708 us: 1.24x faster                                                  |
| deepcopy                 | 278 us                                                 | 227 us: 1.22x faster                                                  |
| dulwich_log              | 37.1 ms                                                | 30.5 ms: 1.22x faster                                                 |
| comprehensions           | 17.7 us                                                | 14.6 us: 1.21x faster                                                 |
| pprint_pformat           | 1.24 sec                                               | 1.03 sec: 1.21x faster                                                |
| pprint_safe_repr         | 609 ms                                                 | 507 ms: 1.20x faster                                                  |
| scimark_sor              | 127 ms                                                 | 105 ms: 1.20x faster                                                  |
| docutils                 | 1.78 sec                                               | 1.49 sec: 1.20x faster                                                |
| nqueens                  | 68.1 ms                                                | 57.7 ms: 1.18x faster                                                 |
| scimark_fft              | 232 ms                                                 | 197 ms: 1.18x faster                                                  |
| deepcopy_reduce          | 2.38 us                                                | 2.04 us: 1.17x faster                                                 |
| xml_etree_process        | 45.1 ms                                                | 39.2 ms: 1.15x faster                                                 |
| bench_thread_pool        | 548 us                                                 | 477 us: 1.15x faster                                                  |
| tomli_loads              | 1.76 sec                                               | 1.54 sec: 1.14x faster                                                |
| regex_dna                | 160 ms                                                 | 140 ms: 1.14x faster                                                  |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.06 ms: 1.14x faster                                                 |
| fannkuch                 | 317 ms                                                 | 280 ms: 1.13x faster                                                  |
| coroutines               | 20.2 ms                                                | 17.9 ms: 1.13x faster                                                 |
| sqlglot_optimize         | 38.0 ms                                                | 34.0 ms: 1.12x faster                                                 |
| unpickle                 | 9.77 us                                                | 9.09 us: 1.08x faster                                                 |
| regex_v8                 | 17.5 ms                                                | 16.4 ms: 1.07x faster                                                 |
| sqlglot_normalize        | 197 ms                                                 | 184 ms: 1.07x faster                                                  |
| meteor_contest           | 78.6 ms                                                | 73.6 ms: 1.07x faster                                                 |
| python_startup           | 12.6 ms                                                | 12.0 ms: 1.05x faster                                                 |
| python_startup_no_site   | 9.73 ms                                                | 9.35 ms: 1.04x faster                                                 |
| json                     | 3.10 ms                                                | 2.99 ms: 1.03x faster                                                 |
| mdp                      | 1.67 sec                                               | 1.63 sec: 1.03x faster                                                |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                                 |
| pickle_dict              | 17.8 us                                                | 18.0 us: 1.01x slower                                                 |
| xml_etree_parse          | 107 ms                                                 | 109 ms: 1.01x slower                                                  |
| regex_effbot             | 2.45 ms                                                | 2.50 ms: 1.02x slower                                                 |
| json_loads               | 16.9 us                                                | 17.5 us: 1.04x slower                                                 |
| xml_etree_iterparse      | 72.6 ms                                                | 75.3 ms: 1.04x slower                                                 |
| xml_etree_generate       | 54.3 ms                                                | 57.3 ms: 1.06x slower                                                 |
| sqlite_synth             | 1.47 us                                                | 1.58 us: 1.07x slower                                                 |
| pathlib                  | 28.8 ms                                                | 32.0 ms: 1.11x slower                                                 |
| bench_mp_pool            | 41.0 ms                                                | 46.5 ms: 1.13x slower                                                 |
| coverage                 | 40.8 ms                                                | 47.0 ms: 1.15x slower                                                 |
| unpickle_list            | 2.66 us                                                | 3.16 us: 1.19x slower                                                 |
| telco                    | 3.68 ms                                                | 4.68 ms: 1.27x slower                                                 |
| dask                     | 258 ms                                                 | 331 ms: 1.28x slower                                                  |
| async_generators         | 233 ms                                                 | 302 ms: 1.29x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.23x faster                                                          |

Benchmark hidden because not significant (3): pickle, pidigits, pickle_list
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.14x
