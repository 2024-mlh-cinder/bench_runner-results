
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.52 sec: 1.17x faster                                        |
| tornado_http   | 91.9 ms                                                | 70.8 ms: 1.30x faster                                         |
| Geometric mean | (ref)                                                  | 1.23x faster                                                  |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| float          | 72.3 ms                                                | 57.1 ms: 1.27x faster                                         |
| nbody          | 94.1 ms                                                | 78.8 ms: 1.20x faster                                         |
| Geometric mean | (ref)                                                  | 1.15x faster                                                  |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 81.5 ms: 1.19x faster                                         |
| regex_dna      | 160 ms                                                 | 140 ms: 1.14x faster                                          |
| regex_v8       | 17.5 ms                                                | 16.3 ms: 1.07x faster                                         |
| regex_effbot   | 2.45 ms                                                | 2.51 ms: 1.03x slower                                         |
| Geometric mean | (ref)                                                  | 1.09x faster                                                  |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 195 us: 1.45x faster                                          |
| json_dumps           | 8.38 ms                                                | 6.48 ms: 1.29x faster                                         |
| unpickle_pure_python | 203 us                                                 | 164 us: 1.24x faster                                          |
| tomli_loads          | 1.76 sec                                               | 1.52 sec: 1.16x faster                                        |
| xml_etree_process    | 45.1 ms                                                | 39.9 ms: 1.13x faster                                         |
| unpickle             | 9.77 us                                                | 9.10 us: 1.07x faster                                         |
| pickle_dict          | 17.8 us                                                | 17.8 us: 1.00x slower                                         |
| pickle               | 7.36 us                                                | 7.45 us: 1.01x slower                                         |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                          |
| pickle_list          | 2.83 us                                                | 2.93 us: 1.04x slower                                         |
| json_loads           | 16.9 us                                                | 17.6 us: 1.04x slower                                         |
| xml_etree_iterparse  | 72.6 ms                                                | 77.3 ms: 1.06x slower                                         |
| xml_etree_generate   | 54.3 ms                                                | 58.0 ms: 1.07x slower                                         |
| unpickle_list        | 2.66 us                                                | 3.18 us: 1.19x slower                                         |
| Geometric mean       | (ref)                                                  | 1.06x faster                                                  |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 11.7 ms: 1.08x faster                                         |
| python_startup_no_site | 9.73 ms                                                | 9.58 ms: 1.02x faster                                         |
| Geometric mean         | (ref)                                                  | 1.05x faster                                                  |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.66 ms: 1.37x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-darwin-arm64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 95.7 us: 3.60x faster                                         |
| deltablue                | 5.15 ms                                                | 2.50 ms: 2.06x faster                                         |
| raytrace                 | 328 ms                                                 | 180 ms: 1.82x faster                                          |
| logging_silent           | 119 ns                                                 | 72.4 ns: 1.64x faster                                         |
| sqlglot_parse            | 1.33 ms                                                | 819 us: 1.62x faster                                          |
| richards_super           | 60.7 ms                                                | 37.7 ms: 1.61x faster                                         |
| asyncio_tcp              | 673 ms                                                 | 418 ms: 1.61x faster                                          |
| crypto_pyaes             | 78.0 ms                                                | 48.6 ms: 1.61x faster                                         |
| async_tree_none          | 402 ms                                                 | 254 ms: 1.58x faster                                          |
| chaos                    | 66.8 ms                                                | 42.3 ms: 1.58x faster                                         |
| scimark_monte_carlo      | 72.2 ms                                                | 46.5 ms: 1.55x faster                                         |
| sqlglot_transpile        | 1.54 ms                                                | 997 us: 1.54x faster                                          |
| go                       | 165 ms                                                 | 108 ms: 1.53x faster                                          |
| scimark_lu               | 110 ms                                                 | 73.2 ms: 1.50x faster                                         |
| richards                 | 51.4 ms                                                | 34.2 ms: 1.50x faster                                         |
| async_tree_memoization   | 493 ms                                                 | 330 ms: 1.49x faster                                          |
| async_tree_io            | 1.02 sec                                               | 690 ms: 1.48x faster                                          |
| unpack_sequence          | 38.7 ns                                                | 26.4 ns: 1.46x faster                                         |
| pickle_pure_python       | 284 us                                                 | 195 us: 1.45x faster                                          |
| mako                     | 10.5 ms                                                | 7.66 ms: 1.37x faster                                         |
| deepcopy_memo            | 34.5 us                                                | 25.5 us: 1.35x faster                                         |
| pyflate                  | 453 ms                                                 | 340 ms: 1.33x faster                                          |
| pycparser                | 915 ms                                                 | 692 ms: 1.32x faster                                          |
| generators               | 32.9 ms                                                | 25.1 ms: 1.31x faster                                         |
| tornado_http             | 91.9 ms                                                | 70.8 ms: 1.30x faster                                         |
| spectral_norm            | 96.4 ms                                                | 74.3 ms: 1.30x faster                                         |
| json_dumps               | 8.38 ms                                                | 6.48 ms: 1.29x faster                                         |
| logging_format           | 5.01 us                                                | 3.89 us: 1.29x faster                                         |
| logging_simple           | 4.63 us                                                | 3.62 us: 1.28x faster                                         |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 525 ms: 1.28x faster                                          |
| float                    | 72.3 ms                                                | 57.1 ms: 1.27x faster                                         |
| create_gc_cycles         | 876 us                                                 | 698 us: 1.25x faster                                          |
| unpickle_pure_python     | 203 us                                                 | 164 us: 1.24x faster                                          |
| hexiom                   | 6.32 ms                                                | 5.20 ms: 1.22x faster                                         |
| deepcopy                 | 278 us                                                 | 229 us: 1.21x faster                                          |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.37 sec: 1.20x faster                                        |
| pprint_safe_repr         | 609 ms                                                 | 508 ms: 1.20x faster                                          |
| pprint_pformat           | 1.24 sec                                               | 1.04 sec: 1.20x faster                                        |
| dulwich_log              | 37.1 ms                                                | 31.0 ms: 1.20x faster                                         |
| nbody                    | 94.1 ms                                                | 78.8 ms: 1.20x faster                                         |
| regex_compile            | 96.6 ms                                                | 81.5 ms: 1.19x faster                                         |
| scimark_sor              | 127 ms                                                 | 107 ms: 1.18x faster                                          |
| deepcopy_reduce          | 2.38 us                                                | 2.03 us: 1.17x faster                                         |
| docutils                 | 1.78 sec                                               | 1.52 sec: 1.17x faster                                        |
| mypy2                    | 308 ms                                                 | 264 ms: 1.17x faster                                          |
| tomli_loads              | 1.76 sec                                               | 1.52 sec: 1.16x faster                                        |
| regex_dna                | 160 ms                                                 | 140 ms: 1.14x faster                                          |
| xml_etree_process        | 45.1 ms                                                | 39.9 ms: 1.13x faster                                         |
| coroutines               | 20.2 ms                                                | 18.0 ms: 1.12x faster                                         |
| scimark_fft              | 232 ms                                                 | 209 ms: 1.11x faster                                          |
| fannkuch                 | 317 ms                                                 | 289 ms: 1.10x faster                                          |
| python_startup           | 12.6 ms                                                | 11.7 ms: 1.08x faster                                         |
| sqlglot_optimize         | 38.0 ms                                                | 35.4 ms: 1.08x faster                                         |
| regex_v8                 | 17.5 ms                                                | 16.3 ms: 1.07x faster                                         |
| unpickle                 | 9.77 us                                                | 9.10 us: 1.07x faster                                         |
| bench_thread_pool        | 548 us                                                 | 512 us: 1.07x faster                                          |
| comprehensions           | 17.7 us                                                | 16.8 us: 1.05x faster                                         |
| nqueens                  | 68.1 ms                                                | 64.7 ms: 1.05x faster                                         |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.35 ms: 1.04x faster                                         |
| json                     | 3.10 ms                                                | 3.03 ms: 1.02x faster                                         |
| sqlglot_normalize        | 197 ms                                                 | 193 ms: 1.02x faster                                          |
| python_startup_no_site   | 9.73 ms                                                | 9.58 ms: 1.02x faster                                         |
| mdp                      | 1.67 sec                                               | 1.66 sec: 1.01x faster                                        |
| pickle_dict              | 17.8 us                                                | 17.8 us: 1.00x slower                                         |
| pickle                   | 7.36 us                                                | 7.45 us: 1.01x slower                                         |
| regex_effbot             | 2.45 ms                                                | 2.51 ms: 1.03x slower                                         |
| xml_etree_parse          | 107 ms                                                 | 111 ms: 1.03x slower                                          |
| pickle_list              | 2.83 us                                                | 2.93 us: 1.04x slower                                         |
| json_loads               | 16.9 us                                                | 17.6 us: 1.04x slower                                         |
| xml_etree_iterparse      | 72.6 ms                                                | 77.3 ms: 1.06x slower                                         |
| xml_etree_generate       | 54.3 ms                                                | 58.0 ms: 1.07x slower                                         |
| sqlite_synth             | 1.47 us                                                | 1.61 us: 1.09x slower                                         |
| pathlib                  | 28.8 ms                                                | 32.7 ms: 1.14x slower                                         |
| bench_mp_pool            | 41.0 ms                                                | 47.6 ms: 1.16x slower                                         |
| coverage                 | 40.8 ms                                                | 47.5 ms: 1.16x slower                                         |
| unpickle_list            | 2.66 us                                                | 3.18 us: 1.19x slower                                         |
| telco                    | 3.68 ms                                                | 4.59 ms: 1.25x slower                                         |
| dask                     | 258 ms                                                 | 333 ms: 1.29x slower                                          |
| async_generators         | 233 ms                                                 | 312 ms: 1.34x slower                                          |
| Geometric mean           | (ref)                                                  | 1.20x faster                                                  |

Benchmark hidden because not significant (3): meteor_contest, gc_traversal, pidigits
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.11x
