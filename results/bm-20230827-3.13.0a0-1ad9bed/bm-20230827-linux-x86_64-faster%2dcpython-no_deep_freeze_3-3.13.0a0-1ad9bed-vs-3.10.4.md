
# Results vs. 3.10.4

- fork: faster-cpython
- ref: no_deep_freeze_3
- machine: linux-x86_64
- commit hash: 1ad9bed
- commit date: 2023-08-27
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.61 sec: 1.22x faster                                                      |
| tornado_http   | 127 ms                                                 | 95.3 ms: 1.34x faster                                                       |
| Geometric mean | (ref)                                                  | 1.27x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 91.3 ms: 1.55x faster                                                       |
| float          | 111 ms                                                 | 80.4 ms: 1.38x faster                                                       |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                                        |
| Geometric mean | (ref)                                                  | 1.29x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 135 ms: 1.31x faster                                                        |
| regex_dna      | 222 ms                                                 | 204 ms: 1.09x faster                                                        |
| regex_v8       | 25.0 ms                                                | 23.1 ms: 1.08x faster                                                       |
| regex_effbot   | 3.23 ms                                                | 3.45 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                  | 1.10x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 301 us: 1.51x faster                                                        |
| unpickle_pure_python | 300 us                                                 | 212 us: 1.41x faster                                                        |
| json_dumps           | 13.5 ms                                                | 9.75 ms: 1.39x faster                                                       |
| tomli_loads          | 2.92 sec                                               | 2.11 sec: 1.38x faster                                                      |
| xml_etree_process    | 74.9 ms                                                | 57.5 ms: 1.30x faster                                                       |
| json_loads           | 28.8 us                                                | 25.2 us: 1.15x faster                                                       |
| xml_etree_generate   | 94.2 ms                                                | 83.4 ms: 1.13x faster                                                       |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                        |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                                        |
| pickle               | 10.3 us                                                | 10.1 us: 1.01x faster                                                       |
| pickle_list          | 4.56 us                                                | 4.63 us: 1.02x slower                                                       |
| unpickle             | 14.1 us                                                | 14.4 us: 1.02x slower                                                       |
| unpickle_list        | 4.82 us                                                | 5.04 us: 1.05x slower                                                       |
| pickle_dict          | 27.3 us                                                | 30.4 us: 1.12x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                       |
| python_startup_no_site | 5.82 ms                                                | 6.84 ms: 1.17x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.36x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-faster%2dcpython-no_deep_freeze_3-3.13.0a0-1ad9bed |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 144 us: 3.54x faster                                                        |
| generators               | 76.8 ms                                                | 28.5 ms: 2.70x faster                                                       |
| deltablue                | 7.42 ms                                                | 3.33 ms: 2.23x faster                                                       |
| asyncio_tcp              | 925 ms                                                 | 486 ms: 1.90x faster                                                        |
| chaos                    | 106 ms                                                 | 60.3 ms: 1.76x faster                                                       |
| logging_silent           | 175 ns                                                 | 102 ns: 1.71x faster                                                        |
| crypto_pyaes             | 118 ms                                                 | 69.8 ms: 1.70x faster                                                       |
| richards_super           | 90.7 ms                                                | 53.7 ms: 1.69x faster                                                       |
| raytrace                 | 464 ms                                                 | 275 ms: 1.68x faster                                                        |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                      |
| async_tree_none          | 717 ms                                                 | 437 ms: 1.64x faster                                                        |
| scimark_monte_carlo      | 108 ms                                                 | 66.7 ms: 1.62x faster                                                       |
| go                       | 229 ms                                                 | 141 ms: 1.62x faster                                                        |
| sqlglot_parse            | 2.06 ms                                                | 1.27 ms: 1.62x faster                                                       |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                                        |
| unpack_sequence          | 64.7 ns                                                | 40.5 ns: 1.60x faster                                                       |
| richards                 | 74.9 ms                                                | 47.8 ms: 1.57x faster                                                       |
| hexiom                   | 9.53 ms                                                | 6.10 ms: 1.56x faster                                                       |
| nbody                    | 142 ms                                                 | 91.3 ms: 1.55x faster                                                       |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.55x faster                                                       |
| async_tree_memoization   | 854 ms                                                 | 562 ms: 1.52x faster                                                        |
| pickle_pure_python       | 455 us                                                 | 301 us: 1.51x faster                                                        |
| pyflate                  | 673 ms                                                 | 449 ms: 1.50x faster                                                        |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.49x faster                                                        |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                      |
| spectral_norm            | 150 ms                                                 | 106 ms: 1.42x faster                                                        |
| unpickle_pure_python     | 300 us                                                 | 212 us: 1.41x faster                                                        |
| deepcopy_memo            | 52.3 us                                                | 37.1 us: 1.41x faster                                                       |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                       |
| json_dumps               | 13.5 ms                                                | 9.75 ms: 1.39x faster                                                       |
| logging_format           | 8.91 us                                                | 6.43 us: 1.39x faster                                                       |
| tomli_loads              | 2.92 sec                                               | 2.11 sec: 1.38x faster                                                      |
| logging_simple           | 8.07 us                                                | 5.86 us: 1.38x faster                                                       |
| float                    | 111 ms                                                 | 80.4 ms: 1.38x faster                                                       |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 698 ms: 1.36x faster                                                        |
| pprint_pformat           | 1.99 sec                                               | 1.46 sec: 1.36x faster                                                      |
| tornado_http             | 127 ms                                                 | 95.3 ms: 1.34x faster                                                       |
| pprint_safe_repr         | 955 ms                                                 | 716 ms: 1.33x faster                                                        |
| coroutines               | 31.8 ms                                                | 24.0 ms: 1.33x faster                                                       |
| regex_compile            | 177 ms                                                 | 135 ms: 1.31x faster                                                        |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.31x faster                                                        |
| xml_etree_process        | 74.9 ms                                                | 57.5 ms: 1.30x faster                                                       |
| comprehensions           | 26.8 us                                                | 20.6 us: 1.30x faster                                                       |
| deepcopy                 | 442 us                                                 | 343 us: 1.29x faster                                                        |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.27x faster                                                      |
| mypy2                    | 428 ms                                                 | 338 ms: 1.27x faster                                                        |
| deepcopy_reduce          | 3.82 us                                                | 3.05 us: 1.25x faster                                                       |
| sqlglot_optimize         | 65.3 ms                                                | 52.3 ms: 1.25x faster                                                       |
| nqueens                  | 100 ms                                                 | 80.2 ms: 1.25x faster                                                       |
| fannkuch                 | 486 ms                                                 | 391 ms: 1.24x faster                                                        |
| docutils                 | 3.17 sec                                               | 2.61 sec: 1.22x faster                                                      |
| scimark_fft              | 424 ms                                                 | 354 ms: 1.20x faster                                                        |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.67 ms: 1.17x faster                                                       |
| bench_thread_pool        | 947 us                                                 | 816 us: 1.16x faster                                                        |
| dulwich_log              | 75.9 ms                                                | 66.0 ms: 1.15x faster                                                       |
| json_loads               | 28.8 us                                                | 25.2 us: 1.15x faster                                                       |
| xml_etree_generate       | 94.2 ms                                                | 83.4 ms: 1.13x faster                                                       |
| json                     | 5.42 ms                                                | 4.85 ms: 1.12x faster                                                       |
| mdp                      | 2.82 sec                                               | 2.55 sec: 1.11x faster                                                      |
| meteor_contest           | 115 ms                                                 | 104 ms: 1.10x faster                                                        |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                        |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                                       |
| regex_dna                | 222 ms                                                 | 204 ms: 1.09x faster                                                        |
| regex_v8                 | 25.0 ms                                                | 23.1 ms: 1.08x faster                                                       |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                                        |
| pathlib                  | 20.0 ms                                                | 18.6 ms: 1.08x faster                                                       |
| sqlite_synth             | 2.93 us                                                | 2.74 us: 1.07x faster                                                       |
| pickle                   | 10.3 us                                                | 10.1 us: 1.01x faster                                                       |
| pidigits                 | 190 ms                                                 | 189 ms: 1.00x faster                                                        |
| pickle_list              | 4.56 us                                                | 4.63 us: 1.02x slower                                                       |
| unpickle                 | 14.1 us                                                | 14.4 us: 1.02x slower                                                       |
| gc_traversal             | 3.84 ms                                                | 4.01 ms: 1.04x slower                                                       |
| unpickle_list            | 4.82 us                                                | 5.04 us: 1.05x slower                                                       |
| async_generators         | 425 ms                                                 | 446 ms: 1.05x slower                                                        |
| regex_effbot             | 3.23 ms                                                | 3.45 ms: 1.07x slower                                                       |
| pickle_dict              | 27.3 us                                                | 30.4 us: 1.12x slower                                                       |
| python_startup_no_site   | 5.82 ms                                                | 6.84 ms: 1.17x slower                                                       |
| coverage                 | 72.8 ms                                                | 85.6 ms: 1.18x slower                                                       |
| dask                     | 423 ms                                                 | 522 ms: 1.23x slower                                                        |
| telco                    | 6.54 ms                                                | 8.16 ms: 1.25x slower                                                       |
| Geometric mean           | (ref)                                                  | 1.31x faster                                                                |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.24x
