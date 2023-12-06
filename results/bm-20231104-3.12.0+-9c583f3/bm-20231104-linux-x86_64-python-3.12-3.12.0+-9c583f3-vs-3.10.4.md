
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 273 ms: 1.27x faster                                 |
| chameleon      | 9.84 ms                                                | 7.27 ms: 1.35x faster                                |
| docutils       | 3.26 sec                                               | 2.71 sec: 1.21x faster                               |
| tornado_http   | 131 ms                                                 | 99.2 ms: 1.32x faster                                |
| Geometric mean | (ref)                                                  | 1.29x faster                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 477 ms: 1.53x faster                                 |
| async_tree_io           | 1.79 sec                                               | 1.17 sec: 1.52x faster                               |
| async_tree_memoization  | 867 ms                                                 | 581 ms: 1.49x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 727 ms: 1.39x faster                                 |
| Geometric mean          | (ref)                                                  | 1.48x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 148 ms                                                 | 90.3 ms: 1.64x faster                                |
| float          | 116 ms                                                 | 84.1 ms: 1.38x faster                                |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| Geometric mean | (ref)                                                  | 1.32x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 146 ms: 1.27x faster                                 |
| regex_v8       | 26.2 ms                                                | 22.9 ms: 1.14x faster                                |
| regex_dna      | 215 ms                                                 | 213 ms: 1.01x faster                                 |
| regex_effbot   | 3.41 ms                                                | 3.87 ms: 1.14x slower                                |
| Geometric mean | (ref)                                                  | 1.06x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 323 us: 1.49x faster                                 |
| unpickle_pure_python | 327 us                                                 | 226 us: 1.44x faster                                 |
| json_dumps           | 14.3 ms                                                | 10.6 ms: 1.35x faster                                |
| tomli_loads          | 3.06 sec                                               | 2.28 sec: 1.34x faster                               |
| xml_etree_process    | 79.8 ms                                                | 61.9 ms: 1.29x faster                                |
| xml_etree_generate   | 100.0 ms                                               | 89.6 ms: 1.12x faster                                |
| json_loads           | 31.4 us                                                | 28.4 us: 1.11x faster                                |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.10x faster                                 |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                 |
| pickle_list          | 5.05 us                                                | 5.01 us: 1.01x faster                                |
| pickle               | 10.7 us                                                | 11.1 us: 1.04x slower                                |
| unpickle_list        | 5.10 us                                                | 5.36 us: 1.05x slower                                |
| pickle_dict          | 30.0 us                                                | 31.9 us: 1.06x slower                                |
| unpickle             | 14.9 us                                                | 16.1 us: 1.08x slower                                |
| Geometric mean       | (ref)                                                  | 1.13x faster                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 9.49 ms: 1.51x faster                                |
| python_startup_no_site | 5.87 ms                                                | 6.88 ms: 1.17x slower                                |
| Geometric mean         | (ref)                                                  | 1.14x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako            | 16.3 ms                                                | 11.5 ms: 1.41x faster                                |
| django_template | 47.6 ms                                                | 34.5 ms: 1.38x faster                                |
| Geometric mean  | (ref)                                                  | 1.40x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 121 us: 4.64x faster                                 |
| generators               | 78.9 ms                                                | 32.8 ms: 2.40x faster                                |
| deltablue                | 7.81 ms                                                | 3.67 ms: 2.13x faster                                |
| richards_super           | 95.6 ms                                                | 51.1 ms: 1.87x faster                                |
| asyncio_tcp              | 918 ms                                                 | 509 ms: 1.80x faster                                 |
| logging_silent           | 189 ns                                                 | 106 ns: 1.78x faster                                 |
| richards                 | 79.4 ms                                                | 45.3 ms: 1.75x faster                                |
| chaos                    | 114 ms                                                 | 66.2 ms: 1.72x faster                                |
| go                       | 238 ms                                                 | 140 ms: 1.69x faster                                 |
| scimark_sor              | 214 ms                                                 | 129 ms: 1.66x faster                                 |
| nbody                    | 148 ms                                                 | 90.3 ms: 1.64x faster                                |
| raytrace                 | 498 ms                                                 | 306 ms: 1.63x faster                                 |
| hexiom                   | 10.3 ms                                                | 6.38 ms: 1.61x faster                                |
| scimark_monte_carlo      | 118 ms                                                 | 74.0 ms: 1.59x faster                                |
| sqlglot_parse            | 2.15 ms                                                | 1.37 ms: 1.56x faster                                |
| async_tree_none          | 732 ms                                                 | 477 ms: 1.53x faster                                 |
| async_tree_io            | 1.79 sec                                               | 1.17 sec: 1.52x faster                               |
| crypto_pyaes             | 127 ms                                                 | 83.8 ms: 1.51x faster                                |
| python_startup           | 14.3 ms                                                | 9.49 ms: 1.51x faster                                |
| sqlglot_transpile        | 2.55 ms                                                | 1.69 ms: 1.51x faster                                |
| pyflate                  | 708 ms                                                 | 470 ms: 1.51x faster                                 |
| coroutines               | 34.5 ms                                                | 23.1 ms: 1.49x faster                                |
| pickle_pure_python       | 482 us                                                 | 323 us: 1.49x faster                                 |
| async_tree_memoization   | 867 ms                                                 | 581 ms: 1.49x faster                                 |
| scimark_lu               | 175 ms                                                 | 119 ms: 1.48x faster                                 |
| deepcopy_memo            | 58.8 us                                                | 40.2 us: 1.46x faster                                |
| unpickle_pure_python     | 327 us                                                 | 226 us: 1.44x faster                                 |
| spectral_norm            | 163 ms                                                 | 113 ms: 1.44x faster                                 |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.80 sec: 1.43x faster                               |
| mako                     | 16.3 ms                                                | 11.5 ms: 1.41x faster                                |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 727 ms: 1.39x faster                                 |
| comprehensions           | 28.5 us                                                | 20.6 us: 1.39x faster                                |
| float                    | 116 ms                                                 | 84.1 ms: 1.38x faster                                |
| django_template          | 47.6 ms                                                | 34.5 ms: 1.38x faster                                |
| pprint_pformat           | 2.10 sec                                               | 1.54 sec: 1.36x faster                               |
| chameleon                | 9.84 ms                                                | 7.27 ms: 1.35x faster                                |
| json_dumps               | 14.3 ms                                                | 10.6 ms: 1.35x faster                                |
| pprint_safe_repr         | 1.01 sec                                               | 757 ms: 1.34x faster                                 |
| tomli_loads              | 3.06 sec                                               | 2.28 sec: 1.34x faster                               |
| deepcopy                 | 481 us                                                 | 365 us: 1.32x faster                                 |
| tornado_http             | 131 ms                                                 | 99.2 ms: 1.32x faster                                |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.30x faster                               |
| xml_etree_process        | 79.8 ms                                                | 61.9 ms: 1.29x faster                                |
| sqlglot_normalize        | 141 ms                                                 | 110 ms: 1.28x faster                                 |
| nqueens                  | 107 ms                                                 | 83.5 ms: 1.28x faster                                |
| deepcopy_reduce          | 4.17 us                                                | 3.26 us: 1.28x faster                                |
| fannkuch                 | 527 ms                                                 | 416 ms: 1.27x faster                                 |
| regex_compile            | 186 ms                                                 | 146 ms: 1.27x faster                                 |
| 2to3                     | 346 ms                                                 | 273 ms: 1.27x faster                                 |
| logging_simple           | 8.27 us                                                | 6.56 us: 1.26x faster                                |
| sqlglot_optimize         | 68.7 ms                                                | 54.8 ms: 1.25x faster                                |
| logging_format           | 9.07 us                                                | 7.26 us: 1.25x faster                                |
| aiohttp                  | 1.41 ms                                                | 1.14 ms: 1.24x faster                                |
| unpack_sequence          | 65.7 ns                                                | 53.4 ns: 1.23x faster                                |
| sympy_integrate          | 25.4 ms                                                | 20.7 ms: 1.23x faster                                |
| scimark_fft              | 454 ms                                                 | 371 ms: 1.22x faster                                 |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.04 ms: 1.21x faster                                |
| docutils                 | 3.26 sec                                               | 2.71 sec: 1.21x faster                               |
| gunicorn                 | 1.48 ms                                                | 1.24 ms: 1.19x faster                                |
| dask                     | 432 ms                                                 | 369 ms: 1.17x faster                                 |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.7 ms: 1.17x faster                                |
| sympy_expand             | 558 ms                                                 | 478 ms: 1.17x faster                                 |
| sqlalchemy_declarative   | 170 ms                                                 | 146 ms: 1.16x faster                                 |
| sympy_sum                | 190 ms                                                 | 165 ms: 1.16x faster                                 |
| bench_thread_pool        | 966 us                                                 | 841 us: 1.15x faster                                 |
| regex_v8                 | 26.2 ms                                                | 22.9 ms: 1.14x faster                                |
| sympy_str                | 337 ms                                                 | 297 ms: 1.13x faster                                 |
| dulwich_log              | 77.0 ms                                                | 67.9 ms: 1.13x faster                                |
| mdp                      | 2.93 sec                                               | 2.59 sec: 1.13x faster                               |
| xml_etree_generate       | 100.0 ms                                               | 89.6 ms: 1.12x faster                                |
| create_gc_cycles         | 1.61 ms                                                | 1.45 ms: 1.11x faster                                |
| json_loads               | 31.4 us                                                | 28.4 us: 1.11x faster                                |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.10x faster                                 |
| meteor_contest           | 119 ms                                                 | 109 ms: 1.09x faster                                 |
| coverage                 | 82.0 ms                                                | 75.4 ms: 1.09x faster                                |
| json                     | 5.67 ms                                                | 5.26 ms: 1.08x faster                                |
| pathlib                  | 20.3 ms                                                | 18.9 ms: 1.07x faster                                |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                 |
| sqlite_synth             | 3.02 us                                                | 2.87 us: 1.05x faster                                |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                 |
| pickle_list              | 5.05 us                                                | 5.01 us: 1.01x faster                                |
| regex_dna                | 215 ms                                                 | 213 ms: 1.01x faster                                 |
| telco                    | 7.01 ms                                                | 7.17 ms: 1.02x slower                                |
| async_generators         | 442 ms                                                 | 452 ms: 1.02x slower                                 |
| pickle                   | 10.7 us                                                | 11.1 us: 1.04x slower                                |
| unpickle_list            | 5.10 us                                                | 5.36 us: 1.05x slower                                |
| pickle_dict              | 30.0 us                                                | 31.9 us: 1.06x slower                                |
| unpickle                 | 14.9 us                                                | 16.1 us: 1.08x slower                                |
| gc_traversal             | 3.43 ms                                                | 3.78 ms: 1.10x slower                                |
| regex_effbot             | 3.41 ms                                                | 3.87 ms: 1.14x slower                                |
| python_startup_no_site   | 5.87 ms                                                | 6.88 ms: 1.17x slower                                |
| Geometric mean           | (ref)                                                  | 1.30x faster                                         |

Benchmark hidden because not significant (2): bench_mp_pool, mypy2
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231104-3.12.0+-9c583f3/bm-20231104-linux-x86_64-python-3.12-3.12.0+-9c583f3.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
