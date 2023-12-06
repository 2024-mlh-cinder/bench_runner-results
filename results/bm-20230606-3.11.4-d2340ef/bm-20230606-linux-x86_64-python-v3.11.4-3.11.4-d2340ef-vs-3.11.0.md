
# Results vs. 3.11.0

- fork: python
- ref: v3.11.4
- machine: linux-x86_64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 258 ms: 1.03x faster                                   |
| chameleon      | 6.86 ms                                                | 6.58 ms: 1.04x faster                                  |
| docutils       | 2.69 sec                                               | 2.57 sec: 1.05x faster                                 |
| tornado_http   | 97.7 ms                                                | 96.6 ms: 1.01x faster                                  |
| Geometric mean | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 532 ms                                                 | 523 ms: 1.02x faster                                   |
| async_tree_cpu_io_mixed | 750 ms                                                 | 738 ms: 1.02x faster                                   |
| async_tree_io           | 1.31 sec                                               | 1.29 sec: 1.01x faster                                 |
| async_tree_memoization  | 640 ms                                                 | 638 ms: 1.00x faster                                   |
| Geometric mean          | (ref)                                                  | 1.01x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 78.9 ms                                                | 77.1 ms: 1.02x faster                                  |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| nbody          | 91.6 ms                                                | 99.4 ms: 1.09x slower                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 141 ms                                                 | 136 ms: 1.04x faster                                   |
| regex_v8       | 22.9 ms                                                | 22.2 ms: 1.03x faster                                  |
| regex_dna      | 204 ms                                                 | 200 ms: 1.02x faster                                   |
| Geometric mean | (ref)                                                  | 1.02x faster                                           |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_list          | 4.65 us                                                | 4.01 us: 1.16x faster                                  |
| pickle               | 11.1 us                                                | 9.76 us: 1.14x faster                                  |
| pickle_dict          | 34.8 us                                                | 30.7 us: 1.13x faster                                  |
| json_loads           | 29.4 us                                                | 26.2 us: 1.12x faster                                  |
| json_dumps           | 13.5 ms                                                | 12.6 ms: 1.07x faster                                  |
| unpickle             | 13.9 us                                                | 13.1 us: 1.06x faster                                  |
| tomli_loads          | 2.31 sec                                               | 2.19 sec: 1.06x faster                                 |
| pickle_pure_python   | 319 us                                                 | 302 us: 1.06x faster                                   |
| unpickle_pure_python | 241 us                                                 | 229 us: 1.05x faster                                   |
| xml_etree_generate   | 80.4 ms                                                | 76.5 ms: 1.05x faster                                  |
| xml_etree_process    | 56.5 ms                                                | 53.9 ms: 1.05x faster                                  |
| xml_etree_iterparse  | 109 ms                                                 | 104 ms: 1.04x faster                                   |
| unpickle_list        | 5.22 us                                                | 5.02 us: 1.04x faster                                  |
| xml_etree_parse      | 163 ms                                                 | 160 ms: 1.02x faster                                   |
| Geometric mean       | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 8.69 ms                                                | 8.53 ms: 1.02x faster                                  |
| python_startup_no_site | 6.09 ms                                                | 6.01 ms: 1.01x faster                                  |
| Geometric mean         | (ref)                                                  | 1.02x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 10.8 ms                                                | 9.80 ms: 1.11x faster                                  |
| genshi_xml      | 54.1 ms                                                | 51.8 ms: 1.04x faster                                  |
| django_template | 33.8 ms                                                | 33.0 ms: 1.02x faster                                  |
| genshi_text     | 22.8 ms                                                | 22.4 ms: 1.02x faster                                  |
| Geometric mean  | (ref)                                                  | 1.05x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_list              | 4.65 us                                                | 4.01 us: 1.16x faster                                  |
| pickle                   | 11.1 us                                                | 9.76 us: 1.14x faster                                  |
| pickle_dict              | 34.8 us                                                | 30.7 us: 1.13x faster                                  |
| json_loads               | 29.4 us                                                | 26.2 us: 1.12x faster                                  |
| mako                     | 10.8 ms                                                | 9.80 ms: 1.11x faster                                  |
| spectral_norm            | 105 ms                                                 | 97.1 ms: 1.08x faster                                  |
| json                     | 5.24 ms                                                | 4.85 ms: 1.08x faster                                  |
| mdp                      | 2.79 sec                                               | 2.60 sec: 1.07x faster                                 |
| deepcopy_memo            | 38.9 us                                                | 36.5 us: 1.07x faster                                  |
| json_dumps               | 13.5 ms                                                | 12.6 ms: 1.07x faster                                  |
| deepcopy_reduce          | 3.14 us                                                | 2.94 us: 1.07x faster                                  |
| unpickle                 | 13.9 us                                                | 13.1 us: 1.06x faster                                  |
| scimark_monte_carlo      | 71.8 ms                                                | 67.7 ms: 1.06x faster                                  |
| tomli_loads              | 2.31 sec                                               | 2.19 sec: 1.06x faster                                 |
| pickle_pure_python       | 319 us                                                 | 302 us: 1.06x faster                                   |
| deepcopy                 | 360 us                                                 | 341 us: 1.06x faster                                   |
| logging_silent           | 108 ns                                                 | 103 ns: 1.06x faster                                   |
| typing_runtime_protocols | 521 us                                                 | 495 us: 1.05x faster                                   |
| unpickle_pure_python     | 241 us                                                 | 229 us: 1.05x faster                                   |
| pprint_pformat           | 1.53 sec                                               | 1.45 sec: 1.05x faster                                 |
| sqlglot_transpile        | 1.75 ms                                                | 1.67 ms: 1.05x faster                                  |
| pprint_safe_repr         | 743 ms                                                 | 707 ms: 1.05x faster                                   |
| xml_etree_generate       | 80.4 ms                                                | 76.5 ms: 1.05x faster                                  |
| scimark_fft              | 342 ms                                                 | 326 ms: 1.05x faster                                   |
| scimark_sparse_mat_mult  | 4.80 ms                                                | 4.58 ms: 1.05x faster                                  |
| docutils                 | 2.69 sec                                               | 2.57 sec: 1.05x faster                                 |
| xml_etree_process        | 56.5 ms                                                | 53.9 ms: 1.05x faster                                  |
| sqlglot_parse            | 1.43 ms                                                | 1.37 ms: 1.05x faster                                  |
| nqueens                  | 86.8 ms                                                | 83.1 ms: 1.04x faster                                  |
| comprehensions           | 23.6 us                                                | 22.6 us: 1.04x faster                                  |
| genshi_xml               | 54.1 ms                                                | 51.8 ms: 1.04x faster                                  |
| chameleon                | 6.86 ms                                                | 6.58 ms: 1.04x faster                                  |
| sympy_expand             | 490 ms                                                 | 470 ms: 1.04x faster                                   |
| xml_etree_iterparse      | 109 ms                                                 | 104 ms: 1.04x faster                                   |
| sqlglot_optimize         | 55.2 ms                                                | 53.0 ms: 1.04x faster                                  |
| raytrace                 | 306 ms                                                 | 294 ms: 1.04x faster                                   |
| fannkuch                 | 410 ms                                                 | 394 ms: 1.04x faster                                   |
| async_generators         | 375 ms                                                 | 361 ms: 1.04x faster                                   |
| regex_compile            | 141 ms                                                 | 136 ms: 1.04x faster                                   |
| unpickle_list            | 5.22 us                                                | 5.02 us: 1.04x faster                                  |
| crypto_pyaes             | 77.5 ms                                                | 74.6 ms: 1.04x faster                                  |
| logging_format           | 6.83 us                                                | 6.58 us: 1.04x faster                                  |
| hexiom                   | 6.74 ms                                                | 6.50 ms: 1.04x faster                                  |
| generators               | 76.5 ms                                                | 73.7 ms: 1.04x faster                                  |
| sqlglot_normalize        | 112 ms                                                 | 108 ms: 1.04x faster                                   |
| pylint                   | 478 ms                                                 | 462 ms: 1.03x faster                                   |
| scimark_sor              | 121 ms                                                 | 118 ms: 1.03x faster                                   |
| sympy_str                | 299 ms                                                 | 290 ms: 1.03x faster                                   |
| 2to3                     | 266 ms                                                 | 258 ms: 1.03x faster                                   |
| regex_v8                 | 22.9 ms                                                | 22.2 ms: 1.03x faster                                  |
| sqlite_synth             | 2.58 us                                                | 2.51 us: 1.03x faster                                  |
| scimark_lu               | 112 ms                                                 | 109 ms: 1.03x faster                                   |
| meteor_contest           | 109 ms                                                 | 106 ms: 1.03x faster                                   |
| pathlib                  | 18.5 ms                                                | 18.0 ms: 1.03x faster                                  |
| sympy_sum                | 170 ms                                                 | 166 ms: 1.03x faster                                   |
| logging_simple           | 6.24 us                                                | 6.09 us: 1.03x faster                                  |
| deltablue                | 3.80 ms                                                | 3.71 ms: 1.03x faster                                  |
| float                    | 78.9 ms                                                | 77.1 ms: 1.02x faster                                  |
| django_template          | 33.8 ms                                                | 33.0 ms: 1.02x faster                                  |
| sympy_integrate          | 21.4 ms                                                | 20.9 ms: 1.02x faster                                  |
| go                       | 143 ms                                                 | 140 ms: 1.02x faster                                   |
| bench_thread_pool        | 833 us                                                 | 816 us: 1.02x faster                                   |
| gunicorn                 | 1.20 ms                                                | 1.17 ms: 1.02x faster                                  |
| regex_dna                | 204 ms                                                 | 200 ms: 1.02x faster                                   |
| richards_super           | 61.2 ms                                                | 60.0 ms: 1.02x faster                                  |
| aiohttp                  | 1.12 ms                                                | 1.09 ms: 1.02x faster                                  |
| sqlalchemy_imperative    | 18.2 ms                                                | 17.9 ms: 1.02x faster                                  |
| python_startup           | 8.69 ms                                                | 8.53 ms: 1.02x faster                                  |
| genshi_text              | 22.8 ms                                                | 22.4 ms: 1.02x faster                                  |
| xml_etree_parse          | 163 ms                                                 | 160 ms: 1.02x faster                                   |
| async_tree_none          | 532 ms                                                 | 523 ms: 1.02x faster                                   |
| chaos                    | 71.4 ms                                                | 70.2 ms: 1.02x faster                                  |
| async_tree_cpu_io_mixed  | 750 ms                                                 | 738 ms: 1.02x faster                                   |
| python_startup_no_site   | 6.09 ms                                                | 6.01 ms: 1.01x faster                                  |
| sqlalchemy_declarative   | 141 ms                                                 | 139 ms: 1.01x faster                                   |
| telco                    | 6.72 ms                                                | 6.62 ms: 1.01x faster                                  |
| dask                     | 365 ms                                                 | 360 ms: 1.01x faster                                   |
| tornado_http             | 97.7 ms                                                | 96.6 ms: 1.01x faster                                  |
| pycparser                | 1.20 sec                                               | 1.18 sec: 1.01x faster                                 |
| pyflate                  | 426 ms                                                 | 421 ms: 1.01x faster                                   |
| async_tree_io            | 1.31 sec                                               | 1.29 sec: 1.01x faster                                 |
| coroutines               | 26.1 ms                                                | 25.9 ms: 1.01x faster                                  |
| richards                 | 48.9 ms                                                | 48.5 ms: 1.01x faster                                  |
| pidigits                 | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| async_tree_memoization   | 640 ms                                                 | 638 ms: 1.00x faster                                   |
| asyncio_tcp_ssl          | 3.13 sec                                               | 3.15 sec: 1.01x slower                                 |
| create_gc_cycles         | 1.48 ms                                                | 1.49 ms: 1.01x slower                                  |
| dulwich_log              | 64.9 ms                                                | 65.5 ms: 1.01x slower                                  |
| gc_traversal             | 3.90 ms                                                | 4.04 ms: 1.04x slower                                  |
| asyncio_tcp              | 887 ms                                                 | 922 ms: 1.04x slower                                   |
| nbody                    | 91.6 ms                                                | 99.4 ms: 1.09x slower                                  |
| mypy2                    | 427 ms                                                 | 534 ms: 1.25x slower                                   |
| Geometric mean           | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (7): html5lib, flaskblogging, djangocms, thrift, regex_effbot, bench_mp_pool, unpack_sequence
Ignored benchmarks (6) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.02x
- 99% likely to have a speedup of 1.02x
