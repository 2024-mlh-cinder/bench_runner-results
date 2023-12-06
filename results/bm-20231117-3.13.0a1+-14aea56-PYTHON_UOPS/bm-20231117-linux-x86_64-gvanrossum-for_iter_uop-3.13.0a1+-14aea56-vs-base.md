
# Results vs. base

- fork: gvanrossum
- ref: for_iter_uop
- machine: linux-x86_64
- commit hash: 14aea56
- commit date: 2023-11-17
- overall geometric mean: 1.04x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 297 ms                                                                 | 301 ms: 1.01x slower                                               |
| chameleon      | 7.46 ms                                                                | 7.84 ms: 1.05x slower                                              |
| docutils       | 2.72 sec                                                               | 2.79 sec: 1.02x slower                                             |
| tornado_http   | 103 ms                                                                 | 104 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                       |

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|--------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| async_tree_none_tg | 481 ms                                                                 | 485 ms: 1.01x slower                                               |
| Geometric mean     | (ref)                                                                  | 1.00x slower                                                       |

Benchmark hidden because not significant (7): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_io, async_tree_memoization, async_tree_io_tg, async_tree_memoization_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pidigits       | 198 ms                                                                 | 199 ms: 1.00x slower                                               |
| float          | 119 ms                                                                 | 123 ms: 1.04x slower                                               |
| nbody          | 142 ms                                                                 | 159 ms: 1.12x slower                                               |
| Geometric mean | (ref)                                                                  | 1.05x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 3.56 ms                                                                | 3.63 ms: 1.02x slower                                              |
| regex_dna      | 216 ms                                                                 | 220 ms: 1.02x slower                                               |
| regex_compile  | 171 ms                                                                 | 176 ms: 1.03x slower                                               |
| regex_v8       | 24.8 ms                                                                | 26.1 ms: 1.05x slower                                              |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|----------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pickle_dict          | 33.5 us                                                                | 33.2 us: 1.01x faster                                              |
| pickle_list          | 5.05 us                                                                | 5.03 us: 1.00x faster                                              |
| json_loads           | 28.0 us                                                                | 28.2 us: 1.01x slower                                              |
| xml_etree_parse      | 158 ms                                                                 | 159 ms: 1.01x slower                                               |
| unpickle             | 14.9 us                                                                | 15.1 us: 1.01x slower                                              |
| pickle               | 11.1 us                                                                | 11.3 us: 1.02x slower                                              |
| unpickle_list        | 5.29 us                                                                | 5.40 us: 1.02x slower                                              |
| pickle_pure_python   | 308 us                                                                 | 315 us: 1.02x slower                                               |
| unpickle_pure_python | 252 us                                                                 | 262 us: 1.04x slower                                               |
| tomli_loads          | 3.11 sec                                                               | 3.30 sec: 1.06x slower                                             |
| xml_etree_iterparse  | 114 ms                                                                 | 122 ms: 1.07x slower                                               |
| xml_etree_generate   | 87.8 ms                                                                | 98.2 ms: 1.12x slower                                              |
| xml_etree_process    | 59.3 ms                                                                | 67.0 ms: 1.13x slower                                              |
| Geometric mean       | (ref)                                                                  | 1.03x slower                                                       |

Benchmark hidden because not significant (1): json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 9.05 ms                                                                | 9.07 ms: 1.00x slower                                              |
| python_startup         | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                              |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|-----------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 17.7 ms                                                                | 19.1 ms: 1.08x slower                                              |

All benchmarks:
===============

| Benchmark                | bm-20231117-linux-x86_64-python-dabc0d77b21d8cc619a2-3.13.0a1+-dabc0d7 | bm-20231117-linux-x86_64-gvanrossum-for_iter_uop-3.13.0a1+-14aea56 |
|--------------------------|:----------------------------------------------------------------------:|:------------------------------------------------------------------:|
| create_gc_cycles         | 1.49 ms                                                                | 1.47 ms: 1.01x faster                                              |
| pickle_dict              | 33.5 us                                                                | 33.2 us: 1.01x faster                                              |
| pickle_list              | 5.05 us                                                                | 5.03 us: 1.00x faster                                              |
| pidigits                 | 198 ms                                                                 | 199 ms: 1.00x slower                                               |
| asyncio_tcp_ssl          | 1.81 sec                                                               | 1.81 sec: 1.00x slower                                             |
| python_startup_no_site   | 9.05 ms                                                                | 9.07 ms: 1.00x slower                                              |
| python_startup           | 10.4 ms                                                                | 10.4 ms: 1.00x slower                                              |
| json_loads               | 28.0 us                                                                | 28.2 us: 1.01x slower                                              |
| async_tree_none_tg       | 481 ms                                                                 | 485 ms: 1.01x slower                                               |
| xml_etree_parse          | 158 ms                                                                 | 159 ms: 1.01x slower                                               |
| generators               | 29.5 ms                                                                | 29.7 ms: 1.01x slower                                              |
| scimark_sor              | 137 ms                                                                 | 138 ms: 1.01x slower                                               |
| pathlib                  | 18.9 ms                                                                | 19.1 ms: 1.01x slower                                              |
| scimark_lu               | 122 ms                                                                 | 124 ms: 1.01x slower                                               |
| tornado_http             | 103 ms                                                                 | 104 ms: 1.01x slower                                               |
| unpickle                 | 14.9 us                                                                | 15.1 us: 1.01x slower                                              |
| mypy2                    | 355 ms                                                                 | 360 ms: 1.01x slower                                               |
| scimark_sparse_mat_mult  | 7.82 ms                                                                | 7.92 ms: 1.01x slower                                              |
| 2to3                     | 297 ms                                                                 | 301 ms: 1.01x slower                                               |
| logging_simple           | 6.23 us                                                                | 6.31 us: 1.01x slower                                              |
| mdp                      | 2.75 sec                                                               | 2.80 sec: 1.02x slower                                             |
| deepcopy_reduce          | 3.13 us                                                                | 3.18 us: 1.02x slower                                              |
| pickle                   | 11.1 us                                                                | 11.3 us: 1.02x slower                                              |
| richards                 | 52.2 ms                                                                | 53.2 ms: 1.02x slower                                              |
| logging_format           | 6.98 us                                                                | 7.11 us: 1.02x slower                                              |
| typing_runtime_protocols | 127 us                                                                 | 130 us: 1.02x slower                                               |
| bench_thread_pool        | 860 us                                                                 | 877 us: 1.02x slower                                               |
| regex_effbot             | 3.56 ms                                                                | 3.63 ms: 1.02x slower                                              |
| regex_dna                | 216 ms                                                                 | 220 ms: 1.02x slower                                               |
| asyncio_tcp              | 483 ms                                                                 | 493 ms: 1.02x slower                                               |
| unpickle_list            | 5.29 us                                                                | 5.40 us: 1.02x slower                                              |
| pickle_pure_python       | 308 us                                                                 | 315 us: 1.02x slower                                               |
| docutils                 | 2.72 sec                                                               | 2.79 sec: 1.02x slower                                             |
| richards_super           | 59.1 ms                                                                | 60.6 ms: 1.03x slower                                              |
| deepcopy_memo            | 43.6 us                                                                | 44.7 us: 1.03x slower                                              |
| dulwich_log              | 68.7 ms                                                                | 70.6 ms: 1.03x slower                                              |
| regex_compile            | 171 ms                                                                 | 176 ms: 1.03x slower                                               |
| sqlite_synth             | 2.91 us                                                                | 3.00 us: 1.03x slower                                              |
| pprint_safe_repr         | 879 ms                                                                 | 905 ms: 1.03x slower                                               |
| pprint_pformat           | 1.84 sec                                                               | 1.90 sec: 1.03x slower                                             |
| raytrace                 | 328 ms                                                                 | 339 ms: 1.03x slower                                               |
| async_generators         | 457 ms                                                                 | 472 ms: 1.03x slower                                               |
| float                    | 119 ms                                                                 | 123 ms: 1.04x slower                                               |
| unpickle_pure_python     | 252 us                                                                 | 262 us: 1.04x slower                                               |
| telco                    | 8.96 ms                                                                | 9.30 ms: 1.04x slower                                              |
| scimark_monte_carlo      | 93.5 ms                                                                | 97.1 ms: 1.04x slower                                              |
| go                       | 174 ms                                                                 | 181 ms: 1.04x slower                                               |
| deepcopy                 | 358 us                                                                 | 372 us: 1.04x slower                                               |
| sqlglot_transpile        | 1.70 ms                                                                | 1.77 ms: 1.04x slower                                              |
| chaos                    | 85.9 ms                                                                | 89.5 ms: 1.04x slower                                              |
| gc_traversal             | 3.92 ms                                                                | 4.09 ms: 1.04x slower                                              |
| nqueens                  | 115 ms                                                                 | 120 ms: 1.05x slower                                               |
| sqlglot_parse            | 1.38 ms                                                                | 1.44 ms: 1.05x slower                                              |
| sympy_integrate          | 21.9 ms                                                                | 22.9 ms: 1.05x slower                                              |
| pycparser                | 1.22 sec                                                               | 1.27 sec: 1.05x slower                                             |
| chameleon                | 7.46 ms                                                                | 7.84 ms: 1.05x slower                                              |
| comprehensions           | 27.2 us                                                                | 28.6 us: 1.05x slower                                              |
| regex_v8                 | 24.8 ms                                                                | 26.1 ms: 1.05x slower                                              |
| tomli_loads              | 3.11 sec                                                               | 3.30 sec: 1.06x slower                                             |
| fannkuch                 | 532 ms                                                                 | 566 ms: 1.06x slower                                               |
| hexiom                   | 10.9 ms                                                                | 11.6 ms: 1.07x slower                                              |
| xml_etree_iterparse      | 114 ms                                                                 | 122 ms: 1.07x slower                                               |
| meteor_contest           | 121 ms                                                                 | 129 ms: 1.07x slower                                               |
| deltablue                | 5.97 ms                                                                | 6.38 ms: 1.07x slower                                              |
| crypto_pyaes             | 98.1 ms                                                                | 105 ms: 1.07x slower                                               |
| scimark_fft              | 540 ms                                                                 | 581 ms: 1.08x slower                                               |
| mako                     | 17.7 ms                                                                | 19.1 ms: 1.08x slower                                              |
| sympy_expand             | 488 ms                                                                 | 528 ms: 1.08x slower                                               |
| pyflate                  | 593 ms                                                                 | 645 ms: 1.09x slower                                               |
| unpack_sequence          | 46.7 ns                                                                | 50.9 ns: 1.09x slower                                              |
| sympy_sum                | 155 ms                                                                 | 171 ms: 1.10x slower                                               |
| sympy_str                | 290 ms                                                                 | 319 ms: 1.10x slower                                               |
| sqlglot_normalize        | 109 ms                                                                 | 121 ms: 1.11x slower                                               |
| xml_etree_generate       | 87.8 ms                                                                | 98.2 ms: 1.12x slower                                              |
| sqlglot_optimize         | 55.3 ms                                                                | 62.1 ms: 1.12x slower                                              |
| nbody                    | 142 ms                                                                 | 159 ms: 1.12x slower                                               |
| xml_etree_process        | 59.3 ms                                                                | 67.0 ms: 1.13x slower                                              |
| spectral_norm            | 114 ms                                                                 | 209 ms: 1.82x slower                                               |
| Geometric mean           | (ref)                                                                  | 1.04x slower                                                       |

Benchmark hidden because not significant (15): async_tree_cpu_io_mixed_tg, json, async_tree_cpu_io_mixed, async_tree_io, asyncio_websockets, bench_mp_pool, json_dumps, coroutines, coverage, async_tree_memoization, async_tree_io_tg, logging_silent, async_tree_memoization_tg, dask, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
