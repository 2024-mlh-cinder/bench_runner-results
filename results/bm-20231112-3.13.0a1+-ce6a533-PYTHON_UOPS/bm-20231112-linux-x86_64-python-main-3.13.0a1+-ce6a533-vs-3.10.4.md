
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 295 ms: 1.17x faster                                   |
| chameleon      | 9.84 ms                                                | 7.58 ms: 1.30x faster                                  |
| docutils       | 3.26 sec                                               | 2.73 sec: 1.20x faster                                 |
| tornado_http   | 131 ms                                                 | 102 ms: 1.28x faster                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 467 ms: 1.57x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 598 ms: 1.45x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.23 sec: 1.45x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 746 ms: 1.35x faster                                   |
| Geometric mean          | (ref)                                                  | 1.45x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 148 ms                                                 | 132 ms: 1.12x faster                                   |
| float          | 116 ms                                                 | 112 ms: 1.04x faster                                   |
| pidigits       | 190 ms                                                 | 197 ms: 1.03x slower                                   |
| Geometric mean | (ref)                                                  | 1.04x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 166 ms: 1.11x faster                                   |
| regex_v8       | 26.2 ms                                                | 26.1 ms: 1.01x faster                                  |
| regex_dna      | 215 ms                                                 | 223 ms: 1.04x slower                                   |
| regex_effbot   | 3.41 ms                                                | 3.78 ms: 1.11x slower                                  |
| Geometric mean | (ref)                                                  | 1.01x slower                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 310 us: 1.56x faster                                   |
| json_dumps           | 14.3 ms                                                | 10.7 ms: 1.34x faster                                  |
| xml_etree_process    | 79.8 ms                                                | 59.9 ms: 1.33x faster                                  |
| unpickle_pure_python | 327 us                                                 | 247 us: 1.32x faster                                   |
| xml_etree_generate   | 100.0 ms                                               | 87.8 ms: 1.14x faster                                  |
| json_loads           | 31.4 us                                                | 27.8 us: 1.13x faster                                  |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                   |
| pickle_list          | 5.05 us                                                | 4.84 us: 1.04x faster                                  |
| unpickle_list        | 5.10 us                                                | 4.98 us: 1.02x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 114 ms: 1.02x faster                                   |
| unpickle             | 14.9 us                                                | 14.8 us: 1.01x faster                                  |
| tomli_loads          | 3.06 sec                                               | 3.17 sec: 1.04x slower                                 |
| pickle               | 10.7 us                                                | 11.6 us: 1.09x slower                                  |
| pickle_dict          | 30.0 us                                                | 34.6 us: 1.15x slower                                  |
| Geometric mean       | (ref)                                                  | 1.11x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 10.4 ms: 1.38x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 9.08 ms: 1.55x slower                                  |
| Geometric mean         | (ref)                                                  | 1.06x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 16.3 ms                                                | 15.8 ms: 1.03x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 126 us: 4.43x faster                                   |
| generators               | 78.9 ms                                                | 29.6 ms: 2.66x faster                                  |
| asyncio_tcp              | 918 ms                                                 | 493 ms: 1.86x faster                                   |
| logging_silent           | 189 ns                                                 | 109 ns: 1.73x faster                                   |
| scimark_sor              | 214 ms                                                 | 134 ms: 1.60x faster                                   |
| raytrace                 | 498 ms                                                 | 312 ms: 1.59x faster                                   |
| coroutines               | 34.5 ms                                                | 21.6 ms: 1.59x faster                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.35 ms: 1.58x faster                                  |
| richards_super           | 95.6 ms                                                | 60.5 ms: 1.58x faster                                  |
| async_tree_none          | 732 ms                                                 | 467 ms: 1.57x faster                                   |
| pickle_pure_python       | 482 us                                                 | 310 us: 1.56x faster                                   |
| sqlglot_transpile        | 2.55 ms                                                | 1.68 ms: 1.52x faster                                  |
| richards                 | 79.4 ms                                                | 52.8 ms: 1.50x faster                                  |
| chaos                    | 114 ms                                                 | 76.2 ms: 1.50x faster                                  |
| scimark_lu               | 175 ms                                                 | 120 ms: 1.46x faster                                   |
| async_tree_memoization   | 867 ms                                                 | 598 ms: 1.45x faster                                   |
| async_tree_io            | 1.79 sec                                               | 1.23 sec: 1.45x faster                                 |
| spectral_norm            | 163 ms                                                 | 113 ms: 1.44x faster                                   |
| crypto_pyaes             | 127 ms                                                 | 87.8 ms: 1.44x faster                                  |
| deltablue                | 7.81 ms                                                | 5.43 ms: 1.44x faster                                  |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.81 sec: 1.42x faster                                 |
| scimark_monte_carlo      | 118 ms                                                 | 83.3 ms: 1.42x faster                                  |
| deepcopy_memo            | 58.8 us                                                | 42.6 us: 1.38x faster                                  |
| python_startup           | 14.3 ms                                                | 10.4 ms: 1.38x faster                                  |
| go                       | 238 ms                                                 | 172 ms: 1.38x faster                                   |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 746 ms: 1.35x faster                                   |
| deepcopy                 | 481 us                                                 | 358 us: 1.34x faster                                   |
| json_dumps               | 14.3 ms                                                | 10.7 ms: 1.34x faster                                  |
| xml_etree_process        | 79.8 ms                                                | 59.9 ms: 1.33x faster                                  |
| unpickle_pure_python     | 327 us                                                 | 247 us: 1.32x faster                                   |
| deepcopy_reduce          | 4.17 us                                                | 3.16 us: 1.32x faster                                  |
| logging_simple           | 8.27 us                                                | 6.33 us: 1.31x faster                                  |
| sqlglot_normalize        | 141 ms                                                 | 109 ms: 1.30x faster                                   |
| unpack_sequence          | 65.7 ns                                                | 50.5 ns: 1.30x faster                                  |
| chameleon                | 9.84 ms                                                | 7.58 ms: 1.30x faster                                  |
| tornado_http             | 131 ms                                                 | 102 ms: 1.28x faster                                   |
| logging_format           | 9.07 us                                                | 7.15 us: 1.27x faster                                  |
| sqlglot_optimize         | 68.7 ms                                                | 55.0 ms: 1.25x faster                                  |
| mypy2                    | 442 ms                                                 | 357 ms: 1.24x faster                                   |
| pyflate                  | 708 ms                                                 | 574 ms: 1.23x faster                                   |
| sympy_sum                | 190 ms                                                 | 155 ms: 1.22x faster                                   |
| pprint_pformat           | 2.10 sec                                               | 1.71 sec: 1.22x faster                                 |
| pycparser                | 1.57 sec                                               | 1.28 sec: 1.22x faster                                 |
| pprint_safe_repr         | 1.01 sec                                               | 832 ms: 1.22x faster                                   |
| docutils                 | 3.26 sec                                               | 2.73 sec: 1.20x faster                                 |
| sympy_integrate          | 25.4 ms                                                | 21.7 ms: 1.17x faster                                  |
| 2to3                     | 346 ms                                                 | 295 ms: 1.17x faster                                   |
| sympy_str                | 337 ms                                                 | 292 ms: 1.15x faster                                   |
| sympy_expand             | 558 ms                                                 | 487 ms: 1.15x faster                                   |
| xml_etree_generate       | 100.0 ms                                               | 87.8 ms: 1.14x faster                                  |
| json_loads               | 31.4 us                                                | 27.8 us: 1.13x faster                                  |
| bench_thread_pool        | 966 us                                                 | 859 us: 1.12x faster                                   |
| nbody                    | 148 ms                                                 | 132 ms: 1.12x faster                                   |
| regex_compile            | 186 ms                                                 | 166 ms: 1.11x faster                                   |
| dulwich_log              | 77.0 ms                                                | 69.5 ms: 1.11x faster                                  |
| json                     | 5.67 ms                                                | 5.21 ms: 1.09x faster                                  |
| create_gc_cycles         | 1.61 ms                                                | 1.48 ms: 1.09x faster                                  |
| xml_etree_parse          | 171 ms                                                 | 158 ms: 1.08x faster                                   |
| mdp                      | 2.93 sec                                               | 2.74 sec: 1.07x faster                                 |
| comprehensions           | 28.5 us                                                | 26.7 us: 1.07x faster                                  |
| pickle_list              | 5.05 us                                                | 4.84 us: 1.04x faster                                  |
| sqlite_synth             | 3.02 us                                                | 2.91 us: 1.04x faster                                  |
| float                    | 116 ms                                                 | 112 ms: 1.04x faster                                   |
| mako                     | 16.3 ms                                                | 15.8 ms: 1.03x faster                                  |
| unpickle_list            | 5.10 us                                                | 4.98 us: 1.02x faster                                  |
| xml_etree_iterparse      | 116 ms                                                 | 114 ms: 1.02x faster                                   |
| pathlib                  | 20.3 ms                                                | 20.0 ms: 1.02x faster                                  |
| asyncio_websockets       | 558 ms                                                 | 552 ms: 1.01x faster                                   |
| regex_v8                 | 26.2 ms                                                | 26.1 ms: 1.01x faster                                  |
| unpickle                 | 14.9 us                                                | 14.8 us: 1.01x faster                                  |
| meteor_contest           | 119 ms                                                 | 120 ms: 1.01x slower                                   |
| scimark_fft              | 454 ms                                                 | 460 ms: 1.01x slower                                   |
| pidigits                 | 190 ms                                                 | 197 ms: 1.03x slower                                   |
| async_generators         | 442 ms                                                 | 457 ms: 1.03x slower                                   |
| tomli_loads              | 3.06 sec                                               | 3.17 sec: 1.04x slower                                 |
| regex_dna                | 215 ms                                                 | 223 ms: 1.04x slower                                   |
| fannkuch                 | 527 ms                                                 | 554 ms: 1.05x slower                                   |
| hexiom                   | 10.3 ms                                                | 10.9 ms: 1.06x slower                                  |
| nqueens                  | 107 ms                                                 | 114 ms: 1.07x slower                                   |
| pickle                   | 10.7 us                                                | 11.6 us: 1.09x slower                                  |
| regex_effbot             | 3.41 ms                                                | 3.78 ms: 1.11x slower                                  |
| gc_traversal             | 3.43 ms                                                | 3.80 ms: 1.11x slower                                  |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 6.93 ms: 1.14x slower                                  |
| pickle_dict              | 30.0 us                                                | 34.6 us: 1.15x slower                                  |
| coverage                 | 82.0 ms                                                | 96.6 ms: 1.18x slower                                  |
| telco                    | 7.01 ms                                                | 8.89 ms: 1.27x slower                                  |
| python_startup_no_site   | 5.87 ms                                                | 9.08 ms: 1.55x slower                                  |
| Geometric mean           | (ref)                                                  | 1.21x faster                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231112-3.13.0a1+-ce6a533-PYTHON_UOPS/bm-20231112-linux-x86_64-python-main-3.13.0a1+-ce6a533.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.12x
