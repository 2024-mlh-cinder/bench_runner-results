
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: d65308a
- commit date: 2023-11-08
- overall geometric mean: 1.31x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 270 ms: 1.28x faster                                           |
| chameleon      | 9.84 ms                                                | 7.18 ms: 1.37x faster                                          |
| docutils       | 3.26 sec                                               | 2.66 sec: 1.23x faster                                         |
| tornado_http   | 131 ms                                                 | 96.7 ms: 1.35x faster                                          |
| Geometric mean | (ref)                                                  | 1.31x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 448 ms: 1.63x faster                                           |
| async_tree_memoization  | 867 ms                                                 | 572 ms: 1.52x faster                                           |
| async_tree_io           | 1.79 sec                                               | 1.19 sec: 1.50x faster                                         |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 721 ms: 1.40x faster                                           |
| Geometric mean          | (ref)                                                  | 1.51x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 94.2 ms: 1.57x faster                                          |
| float          | 116 ms                                                 | 82.0 ms: 1.42x faster                                          |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                           |
| Geometric mean | (ref)                                                  | 1.30x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 140 ms: 1.33x faster                                           |
| regex_v8       | 26.2 ms                                                | 25.8 ms: 1.02x faster                                          |
| regex_dna      | 215 ms                                                 | 223 ms: 1.04x slower                                           |
| regex_effbot   | 3.41 ms                                                | 3.59 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.05x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 299 us: 1.61x faster                                           |
| tomli_loads          | 3.06 sec                                               | 2.04 sec: 1.50x faster                                         |
| unpickle_pure_python | 327 us                                                 | 227 us: 1.44x faster                                           |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                          |
| xml_etree_process    | 79.8 ms                                                | 60.4 ms: 1.32x faster                                          |
| xml_etree_generate   | 100.0 ms                                               | 87.1 ms: 1.15x faster                                          |
| json_loads           | 31.4 us                                                | 27.9 us: 1.13x faster                                          |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                           |
| xml_etree_iterparse  | 116 ms                                                 | 107 ms: 1.08x faster                                           |
| pickle_list          | 5.05 us                                                | 4.97 us: 1.01x faster                                          |
| unpickle             | 14.9 us                                                | 15.2 us: 1.02x slower                                          |
| unpickle_list        | 5.10 us                                                | 5.24 us: 1.03x slower                                          |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| pickle_dict          | 30.0 us                                                | 34.3 us: 1.14x slower                                          |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| python_startup_no_site | 5.87 ms                                                | 9.07 ms: 1.54x slower                                          |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.4 ms: 1.43x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 121 us: 4.63x faster                                           |
| generators               | 78.9 ms                                                | 30.9 ms: 2.56x faster                                          |
| deltablue                | 7.81 ms                                                | 3.71 ms: 2.11x faster                                          |
| asyncio_tcp              | 918 ms                                                 | 488 ms: 1.88x faster                                           |
| richards_super           | 95.6 ms                                                | 52.0 ms: 1.84x faster                                          |
| chaos                    | 114 ms                                                 | 63.3 ms: 1.80x faster                                          |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                           |
| raytrace                 | 498 ms                                                 | 283 ms: 1.76x faster                                           |
| crypto_pyaes             | 127 ms                                                 | 73.4 ms: 1.73x faster                                          |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.72x faster                                           |
| richards                 | 79.4 ms                                                | 46.6 ms: 1.70x faster                                          |
| sqlglot_parse            | 2.15 ms                                                | 1.29 ms: 1.66x faster                                          |
| scimark_monte_carlo      | 118 ms                                                 | 71.5 ms: 1.65x faster                                          |
| async_tree_none          | 732 ms                                                 | 448 ms: 1.63x faster                                           |
| go                       | 238 ms                                                 | 147 ms: 1.61x faster                                           |
| pickle_pure_python       | 482 us                                                 | 299 us: 1.61x faster                                           |
| sqlglot_transpile        | 2.55 ms                                                | 1.62 ms: 1.58x faster                                          |
| nbody                    | 148 ms                                                 | 94.2 ms: 1.57x faster                                          |
| comprehensions           | 28.5 us                                                | 18.5 us: 1.54x faster                                          |
| coroutines               | 34.5 ms                                                | 22.4 ms: 1.54x faster                                          |
| async_tree_memoization   | 867 ms                                                 | 572 ms: 1.52x faster                                           |
| spectral_norm            | 163 ms                                                 | 108 ms: 1.51x faster                                           |
| async_tree_io            | 1.79 sec                                               | 1.19 sec: 1.50x faster                                         |
| tomli_loads              | 3.06 sec                                               | 2.04 sec: 1.50x faster                                         |
| deepcopy_memo            | 58.8 us                                                | 39.8 us: 1.48x faster                                          |
| scimark_lu               | 175 ms                                                 | 119 ms: 1.47x faster                                           |
| hexiom                   | 10.3 ms                                                | 7.04 ms: 1.46x faster                                          |
| pyflate                  | 708 ms                                                 | 490 ms: 1.45x faster                                           |
| logging_simple           | 8.27 us                                                | 5.74 us: 1.44x faster                                          |
| unpickle_pure_python     | 327 us                                                 | 227 us: 1.44x faster                                           |
| mako                     | 16.3 ms                                                | 11.4 ms: 1.43x faster                                          |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                                         |
| logging_format           | 9.07 us                                                | 6.35 us: 1.43x faster                                          |
| float                    | 116 ms                                                 | 82.0 ms: 1.42x faster                                          |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 721 ms: 1.40x faster                                           |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                          |
| chameleon                | 9.84 ms                                                | 7.18 ms: 1.37x faster                                          |
| deepcopy                 | 481 us                                                 | 351 us: 1.37x faster                                           |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                          |
| tornado_http             | 131 ms                                                 | 96.7 ms: 1.35x faster                                          |
| deepcopy_reduce          | 4.17 us                                                | 3.10 us: 1.34x faster                                          |
| sqlglot_normalize        | 141 ms                                                 | 106 ms: 1.34x faster                                           |
| pprint_safe_repr         | 1.01 sec                                               | 764 ms: 1.33x faster                                           |
| pprint_pformat           | 2.10 sec                                               | 1.58 sec: 1.33x faster                                         |
| regex_compile            | 186 ms                                                 | 140 ms: 1.33x faster                                           |
| xml_etree_process        | 79.8 ms                                                | 60.4 ms: 1.32x faster                                          |
| pycparser                | 1.57 sec                                               | 1.20 sec: 1.30x faster                                         |
| fannkuch                 | 527 ms                                                 | 410 ms: 1.29x faster                                           |
| 2to3                     | 346 ms                                                 | 270 ms: 1.28x faster                                           |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.77 ms: 1.28x faster                                          |
| sqlglot_optimize         | 68.7 ms                                                | 54.2 ms: 1.27x faster                                          |
| mypy2                    | 442 ms                                                 | 350 ms: 1.26x faster                                           |
| sympy_sum                | 190 ms                                                 | 153 ms: 1.25x faster                                           |
| sympy_integrate          | 25.4 ms                                                | 20.4 ms: 1.24x faster                                          |
| sympy_str                | 337 ms                                                 | 273 ms: 1.24x faster                                           |
| unpack_sequence          | 65.7 ns                                                | 53.2 ns: 1.23x faster                                          |
| scimark_fft              | 454 ms                                                 | 369 ms: 1.23x faster                                           |
| docutils                 | 3.26 sec                                               | 2.66 sec: 1.23x faster                                         |
| sympy_expand             | 558 ms                                                 | 459 ms: 1.22x faster                                           |
| nqueens                  | 107 ms                                                 | 88.5 ms: 1.20x faster                                          |
| dulwich_log              | 77.0 ms                                                | 66.9 ms: 1.15x faster                                          |
| xml_etree_generate       | 100.0 ms                                               | 87.1 ms: 1.15x faster                                          |
| bench_thread_pool        | 966 us                                                 | 853 us: 1.13x faster                                           |
| json_loads               | 31.4 us                                                | 27.9 us: 1.13x faster                                          |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                          |
| json                     | 5.67 ms                                                | 5.17 ms: 1.10x faster                                          |
| sqlite_synth             | 3.02 us                                                | 2.79 us: 1.08x faster                                          |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                           |
| xml_etree_iterparse      | 116 ms                                                 | 107 ms: 1.08x faster                                           |
| pathlib                  | 20.3 ms                                                | 19.2 ms: 1.06x faster                                          |
| meteor_contest           | 119 ms                                                 | 114 ms: 1.05x faster                                           |
| mdp                      | 2.93 sec                                               | 2.82 sec: 1.04x faster                                         |
| regex_v8                 | 26.2 ms                                                | 25.8 ms: 1.02x faster                                          |
| pickle_list              | 5.05 us                                                | 4.97 us: 1.01x faster                                          |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                           |
| unpickle                 | 14.9 us                                                | 15.2 us: 1.02x slower                                          |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                           |
| unpickle_list            | 5.10 us                                                | 5.24 us: 1.03x slower                                          |
| regex_dna                | 215 ms                                                 | 223 ms: 1.04x slower                                           |
| async_generators         | 442 ms                                                 | 459 ms: 1.04x slower                                           |
| regex_effbot             | 3.41 ms                                                | 3.59 ms: 1.05x slower                                          |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                          |
| gc_traversal             | 3.43 ms                                                | 3.82 ms: 1.11x slower                                          |
| pickle_dict              | 30.0 us                                                | 34.3 us: 1.14x slower                                          |
| coverage                 | 82.0 ms                                                | 94.5 ms: 1.15x slower                                          |
| telco                    | 7.01 ms                                                | 8.27 ms: 1.18x slower                                          |
| python_startup_no_site   | 5.87 ms                                                | 9.07 ms: 1.54x slower                                          |
| Geometric mean           | (ref)                                                  | 1.31x faster                                                   |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231108-3.13.0a1+-d65308a/bm-20231108-linux-x86_64-brandtbucher-justin-3.13.0a1+-d65308a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.26x
- 99% likely to have a speedup of 1.24x
