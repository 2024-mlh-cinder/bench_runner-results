
# Results vs. 3.10.4

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: linux-x86_64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.35x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.27x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 261 ms: 1.32x faster                                                   |
| chameleon      | 9.84 ms                                                | 6.96 ms: 1.41x faster                                                  |
| docutils       | 3.26 sec                                               | 2.59 sec: 1.26x faster                                                 |
| tornado_http   | 131 ms                                                 | 94.4 ms: 1.38x faster                                                  |
| Geometric mean | (ref)                                                  | 1.34x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 435 ms: 1.68x faster                                                   |
| async_tree_memoization  | 867 ms                                                 | 559 ms: 1.55x faster                                                   |
| async_tree_io           | 1.79 sec                                               | 1.18 sec: 1.51x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 709 ms: 1.42x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.54x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 148 ms                                                 | 88.2 ms: 1.68x faster                                                  |
| float          | 116 ms                                                 | 81.1 ms: 1.44x faster                                                  |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| Geometric mean | (ref)                                                  | 1.35x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 134 ms: 1.38x faster                                                   |
| regex_v8       | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                  |
| regex_dna      | 215 ms                                                 | 212 ms: 1.01x faster                                                   |
| regex_effbot   | 3.41 ms                                                | 3.61 ms: 1.06x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 303 us: 1.59x faster                                                   |
| unpickle_pure_python | 327 us                                                 | 219 us: 1.49x faster                                                   |
| tomli_loads          | 3.06 sec                                               | 2.14 sec: 1.43x faster                                                 |
| json_dumps           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| xml_etree_process    | 79.8 ms                                                | 59.0 ms: 1.35x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 85.8 ms: 1.17x faster                                                  |
| json_loads           | 31.4 us                                                | 27.9 us: 1.13x faster                                                  |
| xml_etree_iterparse  | 116 ms                                                 | 105 ms: 1.11x faster                                                   |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                                   |
| unpickle             | 14.9 us                                                | 14.6 us: 1.02x faster                                                  |
| pickle_list          | 5.05 us                                                | 5.03 us: 1.00x faster                                                  |
| unpickle_list        | 5.10 us                                                | 5.30 us: 1.04x slower                                                  |
| pickle               | 10.7 us                                                | 11.3 us: 1.06x slower                                                  |
| pickle_dict          | 30.0 us                                                | 33.9 us: 1.13x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.16x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| python_startup_no_site | 5.87 ms                                                | 9.02 ms: 1.54x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.05x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 16.3 ms                                                | 11.4 ms: 1.43x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 116 us: 4.84x faster                                                   |
| generators               | 78.9 ms                                                | 28.8 ms: 2.74x faster                                                  |
| deltablue                | 7.81 ms                                                | 3.29 ms: 2.38x faster                                                  |
| asyncio_tcp              | 918 ms                                                 | 482 ms: 1.90x faster                                                   |
| chaos                    | 114 ms                                                 | 60.2 ms: 1.90x faster                                                  |
| logging_silent           | 189 ns                                                 | 104 ns: 1.81x faster                                                   |
| raytrace                 | 498 ms                                                 | 275 ms: 1.81x faster                                                   |
| scimark_sor              | 214 ms                                                 | 121 ms: 1.78x faster                                                   |
| crypto_pyaes             | 127 ms                                                 | 71.3 ms: 1.78x faster                                                  |
| richards_super           | 95.6 ms                                                | 54.3 ms: 1.76x faster                                                  |
| comprehensions           | 28.5 us                                                | 16.4 us: 1.74x faster                                                  |
| scimark_monte_carlo      | 118 ms                                                 | 68.5 ms: 1.72x faster                                                  |
| go                       | 238 ms                                                 | 140 ms: 1.70x faster                                                   |
| sqlglot_parse            | 2.15 ms                                                | 1.27 ms: 1.69x faster                                                  |
| async_tree_none          | 732 ms                                                 | 435 ms: 1.68x faster                                                   |
| nbody                    | 148 ms                                                 | 88.2 ms: 1.68x faster                                                  |
| hexiom                   | 10.3 ms                                                | 6.17 ms: 1.67x faster                                                  |
| richards                 | 79.4 ms                                                | 47.7 ms: 1.67x faster                                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.58 ms: 1.61x faster                                                  |
| pickle_pure_python       | 482 us                                                 | 303 us: 1.59x faster                                                   |
| coroutines               | 34.5 ms                                                | 22.0 ms: 1.56x faster                                                  |
| async_tree_memoization   | 867 ms                                                 | 559 ms: 1.55x faster                                                   |
| scimark_lu               | 175 ms                                                 | 114 ms: 1.54x faster                                                   |
| deepcopy_memo            | 58.8 us                                                | 38.4 us: 1.53x faster                                                  |
| pyflate                  | 708 ms                                                 | 468 ms: 1.51x faster                                                   |
| async_tree_io            | 1.79 sec                                               | 1.18 sec: 1.51x faster                                                 |
| unpickle_pure_python     | 327 us                                                 | 219 us: 1.49x faster                                                   |
| logging_format           | 9.07 us                                                | 6.21 us: 1.46x faster                                                  |
| logging_simple           | 8.27 us                                                | 5.69 us: 1.45x faster                                                  |
| spectral_norm            | 163 ms                                                 | 112 ms: 1.45x faster                                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.78 sec: 1.44x faster                                                 |
| float                    | 116 ms                                                 | 81.1 ms: 1.44x faster                                                  |
| tomli_loads              | 3.06 sec                                               | 2.14 sec: 1.43x faster                                                 |
| mako                     | 16.3 ms                                                | 11.4 ms: 1.43x faster                                                  |
| unpack_sequence          | 65.7 ns                                                | 46.1 ns: 1.42x faster                                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 709 ms: 1.42x faster                                                   |
| chameleon                | 9.84 ms                                                | 6.96 ms: 1.41x faster                                                  |
| deepcopy                 | 481 us                                                 | 343 us: 1.40x faster                                                   |
| pprint_pformat           | 2.10 sec                                               | 1.49 sec: 1.40x faster                                                 |
| json_dumps               | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| python_startup           | 14.3 ms                                                | 10.3 ms: 1.39x faster                                                  |
| regex_compile            | 186 ms                                                 | 134 ms: 1.38x faster                                                   |
| tornado_http             | 131 ms                                                 | 94.4 ms: 1.38x faster                                                  |
| pprint_safe_repr         | 1.01 sec                                               | 733 ms: 1.38x faster                                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.04 us: 1.37x faster                                                  |
| xml_etree_process        | 79.8 ms                                                | 59.0 ms: 1.35x faster                                                  |
| sqlglot_normalize        | 141 ms                                                 | 105 ms: 1.35x faster                                                   |
| pycparser                | 1.57 sec                                               | 1.16 sec: 1.35x faster                                                 |
| fannkuch                 | 527 ms                                                 | 394 ms: 1.34x faster                                                   |
| 2to3                     | 346 ms                                                 | 261 ms: 1.32x faster                                                   |
| sympy_integrate          | 25.4 ms                                                | 19.3 ms: 1.31x faster                                                  |
| nqueens                  | 107 ms                                                 | 81.7 ms: 1.31x faster                                                  |
| mypy2                    | 442 ms                                                 | 339 ms: 1.30x faster                                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.68 ms: 1.30x faster                                                  |
| sympy_sum                | 190 ms                                                 | 147 ms: 1.30x faster                                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.3 ms: 1.29x faster                                                  |
| docutils                 | 3.26 sec                                               | 2.59 sec: 1.26x faster                                                 |
| sympy_str                | 337 ms                                                 | 268 ms: 1.26x faster                                                   |
| scimark_fft              | 454 ms                                                 | 364 ms: 1.25x faster                                                   |
| sympy_expand             | 558 ms                                                 | 450 ms: 1.24x faster                                                   |
| dulwich_log              | 77.0 ms                                                | 65.5 ms: 1.18x faster                                                  |
| bench_thread_pool        | 966 us                                                 | 828 us: 1.17x faster                                                   |
| xml_etree_generate       | 100.0 ms                                               | 85.8 ms: 1.17x faster                                                  |
| mdp                      | 2.93 sec                                               | 2.55 sec: 1.15x faster                                                 |
| json_loads               | 31.4 us                                                | 27.9 us: 1.13x faster                                                  |
| xml_etree_iterparse      | 116 ms                                                 | 105 ms: 1.11x faster                                                   |
| json                     | 5.67 ms                                                | 5.13 ms: 1.10x faster                                                  |
| meteor_contest           | 119 ms                                                 | 109 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                                  |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                                   |
| sqlite_synth             | 3.02 us                                                | 2.82 us: 1.07x faster                                                  |
| pathlib                  | 20.3 ms                                                | 19.0 ms: 1.07x faster                                                  |
| regex_v8                 | 26.2 ms                                                | 25.7 ms: 1.02x faster                                                  |
| unpickle                 | 14.9 us                                                | 14.6 us: 1.02x faster                                                  |
| regex_dna                | 215 ms                                                 | 212 ms: 1.01x faster                                                   |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                   |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                                   |
| pickle_list              | 5.05 us                                                | 5.03 us: 1.00x faster                                                  |
| async_generators         | 442 ms                                                 | 445 ms: 1.01x slower                                                   |
| unpickle_list            | 5.10 us                                                | 5.30 us: 1.04x slower                                                  |
| regex_effbot             | 3.41 ms                                                | 3.61 ms: 1.06x slower                                                  |
| pickle                   | 10.7 us                                                | 11.3 us: 1.06x slower                                                  |
| pickle_dict              | 30.0 us                                                | 33.9 us: 1.13x slower                                                  |
| coverage                 | 82.0 ms                                                | 96.1 ms: 1.17x slower                                                  |
| gc_traversal             | 3.43 ms                                                | 4.04 ms: 1.18x slower                                                  |
| telco                    | 7.01 ms                                                | 8.29 ms: 1.18x slower                                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.02 ms: 1.54x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.35x faster                                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-fa84e5f/bm-20231111-linux-x86_64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.31x
- 95% likely to have a speedup of 1.30x
- 99% likely to have a speedup of 1.27x
