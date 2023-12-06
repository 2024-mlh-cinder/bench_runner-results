
# Results vs. 3.10.4

- fork: mdboom
- ref: alternative_workarou
- machine: linux-x86_64
- commit hash: f362f9a
- commit date: 2023-11-20
- overall geometric mean: 1.34x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.26x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| chameleon      | 9.84 ms                                                | 6.93 ms: 1.42x faster                                                  |
| docutils       | 3.26 sec                                               | 2.60 sec: 1.25x faster                                                 |
| tornado_http   | 131 ms                                                 | 95.2 ms: 1.37x faster                                                  |
| Geometric mean | (ref)                                                  | 1.34x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 433 ms: 1.69x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 559 ms: 1.55x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.18 sec: 1.52x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 711 ms: 1.42x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.54x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 89.9 ms: 1.65x faster                                                  |
| float          | 116 ms                                                 | 81.6 ms: 1.43x faster                                                  |
| pidigits       | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| Geometric mean | (ref)                                                  | 1.32x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 133 ms: 1.39x faster                                                   |
| regex_v8       | 26.2 ms                                                | 25.6 ms: 1.02x faster                                                  |
| regex_effbot   | 3.41 ms                                                | 3.64 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 304 us: 1.59x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 221 us: 1.48x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.15 sec: 1.42x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 60.1 ms: 1.33x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 86.6 ms: 1.15x faster                                                  |
| json_loads           | 31.4 us                                                | 28.1 us: 1.12x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.09x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 159 ms: 1.08x faster                                                   |
| pickle_list          | 5.05 us                                                | 4.97 us: 1.02x faster                                                  |
| unpickle_list        | 5.10 us                                                | 5.15 us: 1.01x slower                                                  |
| pickle               | 10.7 us                                                | 11.4 us: 1.06x slower                                                  |
| unpickle             | 14.9 us                                                | 15.9 us: 1.07x slower                                                  |
| pickle_dict          | 30.0 us                                                | 33.3 us: 1.11x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.15x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.03 ms: 1.54x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.06x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.4 ms: 1.43x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 116 us: 4.83x faster                                                   |
| generators               | 78.9 ms                                                | 30.0 ms: 2.63x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.33 ms: 2.34x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 486 ms: 1.89x faster                                                   |
| chaos                    | 114 ms                                                 | 61.1 ms: 1.87x faster                                                  |
| raytrace                 | 498 ms                                                 | 275 ms: 1.81x faster                                                   |
| logging_silent           | 189 ns                                                 | 105 ns: 1.80x faster                                                   |
| richards_super           | 95.6 ms                                                | 53.3 ms: 1.79x faster                                                  |
| crypto_pyaes             | 127 ms                                                 | 72.3 ms: 1.75x faster                                                  |
| comprehensions           | 28.5 us                                                | 16.5 us: 1.73x faster                                                  |
| scimark_sor              | 214 ms                                                 | 124 ms: 1.73x faster                                                   |
| scimark_monte_carlo      | 118 ms                                                 | 68.4 ms: 1.72x faster                                                  |
| go                       | 238 ms                                                 | 141 ms: 1.69x faster                                                   |
| async_tree_none          | 732 ms                                                 | 433 ms: 1.69x faster                                                   |
| richards                 | 79.4 ms                                                | 47.1 ms: 1.69x faster                                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.27 ms: 1.68x faster                                                  |
| hexiom                   | 10.3 ms                                                | 6.18 ms: 1.67x faster                                                  |
| nbody                    | 148 ms                                                 | 89.9 ms: 1.65x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.59 ms: 1.61x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 304 us: 1.59x faster                                                   |
| coroutines               | 34.5 ms                                                | 21.8 ms: 1.58x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 559 ms: 1.55x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 38.2 us: 1.54x faster                                                  |
| async_tree_io            | 1.79 sec                                               | 1.18 sec: 1.52x faster                                                 |
| pyflate                  | 708 ms                                                 | 468 ms: 1.51x faster                                                   |
| scimark_lu               | 175 ms                                                 | 116 ms: 1.51x faster                                                   |
| unpickle_pure_python     | 327 us                                                 | 221 us: 1.48x faster                                                   |
| logging_simple           | 8.27 us                                                | 5.68 us: 1.46x faster                                                  |
| logging_format           | 9.07 us                                                | 6.23 us: 1.46x faster                                                  |
| unpack_sequence          | 65.7 ns                                                | 45.3 ns: 1.45x faster                                                  |
| spectral_norm            | 163 ms                                                 | 113 ms: 1.44x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                                                 |
| mako                     | 16.3 ms                                                | 11.4 ms: 1.43x faster                                                  |
| float                    | 116 ms                                                 | 81.6 ms: 1.43x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.15 sec: 1.42x faster                                                 |
| chameleon                | 9.84 ms                                                | 6.93 ms: 1.42x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 711 ms: 1.42x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.49 sec: 1.41x faster                                                 |
| regex_compile            | 186 ms                                                 | 133 ms: 1.39x faster                                                   |
| deepcopy                 | 481 us                                                 | 346 us: 1.39x faster                                                   |
| pprint_safe_repr         | 1.01 sec                                               | 732 ms: 1.39x faster                                                   |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                                  |
| tornado_http             | 131 ms                                                 | 95.2 ms: 1.37x faster                                                  |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                                  |
| deepcopy_reduce          | 4.17 us                                                | 3.08 us: 1.35x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 105 ms: 1.34x faster                                                   |
| xml_etree_process        | 79.8 ms                                                | 60.1 ms: 1.33x faster                                                  |
| fannkuch                 | 527 ms                                                 | 399 ms: 1.32x faster                                                   |
| nqueens                  | 107 ms                                                 | 80.7 ms: 1.32x faster                                                  |
| 2to3                     | 346 ms                                                 | 264 ms: 1.31x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 19.5 ms: 1.31x faster                                                  |
| pycparser                | 1.57 sec                                               | 1.21 sec: 1.30x faster                                                 |
| mypy2                    | 442 ms                                                 | 342 ms: 1.29x faster                                                   |
| sympy_sum                | 190 ms                                                 | 147 ms: 1.29x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.4 ms: 1.29x faster                                                  |
| sympy_str                | 337 ms                                                 | 267 ms: 1.26x faster                                                   |
| docutils                 | 3.26 sec                                               | 2.60 sec: 1.25x faster                                                 |
| sympy_expand             | 558 ms                                                 | 450 ms: 1.24x faster                                                   |
| scimark_fft              | 454 ms                                                 | 368 ms: 1.23x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.97 ms: 1.23x faster                                                  |
| dask                     | 432 ms                                                 | 361 ms: 1.20x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 65.9 ms: 1.17x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 836 us: 1.16x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 86.6 ms: 1.15x faster                                                  |
| json_loads               | 31.4 us                                                | 28.1 us: 1.12x faster                                                  |
| meteor_contest           | 119 ms                                                 | 107 ms: 1.12x faster                                                   |
| pathlib                  | 20.3 ms                                                | 18.2 ms: 1.12x faster                                                  |
| json                     | 5.67 ms                                                | 5.10 ms: 1.11x faster                                                  |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.09x faster                                                   |
| xml_etree_parse          | 171 ms                                                 | 159 ms: 1.08x faster                                                   |
| mdp                      | 2.93 sec                                               | 2.72 sec: 1.08x faster                                                 |
| sqlite_synth             | 3.02 us                                                | 2.85 us: 1.06x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 25.6 ms: 1.02x faster                                                  |
| pickle_list              | 5.05 us                                                | 4.97 us: 1.02x faster                                                  |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                   |
| async_generators         | 442 ms                                                 | 443 ms: 1.00x slower                                                   |
| unpickle_list            | 5.10 us                                                | 5.15 us: 1.01x slower                                                  |
| pidigits                 | 190 ms                                                 | 195 ms: 1.02x slower                                                   |
| gc_traversal             | 3.43 ms                                                | 3.64 ms: 1.06x slower                                                  |
| pickle                   | 10.7 us                                                | 11.4 us: 1.06x slower                                                  |
| regex_effbot             | 3.41 ms                                                | 3.64 ms: 1.07x slower                                                  |
| unpickle                 | 14.9 us                                                | 15.9 us: 1.07x slower                                                  |
| pickle_dict              | 30.0 us                                                | 33.3 us: 1.11x slower                                                  |
| coverage                 | 82.0 ms                                                | 96.3 ms: 1.17x slower                                                  |
| telco                    | 7.01 ms                                                | 8.37 ms: 1.19x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.03 ms: 1.54x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.34x faster                                                           |

Benchmark hidden because not significant (2): bench_mp_pool, regex_dna
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-f362f9a/bm-20231120-linux-x86_64-mdboom-alternative_workarou-3.13.0a1+-f362f9a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.26x
