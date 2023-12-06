
# Results vs. base

- fork: brandtbucher
- ref: justin_no_ghccc
- machine: linux-x86_64
- commit hash: fb676a6
- commit date: 2023-11-08
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| 2to3           | 264 ms                                                                 | 273 ms: 1.04x slower                                                    |
| chameleon      | 6.94 ms                                                                | 7.32 ms: 1.05x slower                                                   |
| docutils       | 2.61 sec                                                               | 2.65 sec: 1.01x slower                                                  |
| tornado_http   | 95.5 ms                                                                | 96.8 ms: 1.01x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                            |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|-------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| async_tree_io_tg        | 1.23 sec                                                               | 1.22 sec: 1.01x faster                                                  |
| async_tree_io           | 1.19 sec                                                               | 1.18 sec: 1.01x faster                                                  |
| async_tree_cpu_io_mixed | 708 ms                                                                 | 724 ms: 1.02x slower                                                    |
| Geometric mean          | (ref)                                                                  | 1.00x slower                                                            |

Benchmark hidden because not significant (5): async_tree_none_tg, async_tree_memoization_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pidigits       | 195 ms                                                                 | 188 ms: 1.04x faster                                                    |
| float          | 81.8 ms                                                                | 86.8 ms: 1.06x slower                                                   |
| nbody          | 89.4 ms                                                                | 103 ms: 1.15x slower                                                    |
| Geometric mean | (ref)                                                                  | 1.05x slower                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_v8       | 25.6 ms                                                                | 25.4 ms: 1.01x faster                                                   |
| regex_dna      | 214 ms                                                                 | 215 ms: 1.00x slower                                                    |
| regex_compile  | 135 ms                                                                 | 142 ms: 1.05x slower                                                    |
| regex_effbot   | 3.57 ms                                                                | 3.77 ms: 1.05x slower                                                   |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|----------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_list          | 5.15 us                                                                | 4.83 us: 1.07x faster                                                   |
| pickle_dict          | 35.3 us                                                                | 33.3 us: 1.06x faster                                                   |
| unpickle_list        | 5.32 us                                                                | 5.07 us: 1.05x faster                                                   |
| json_loads           | 28.0 us                                                                | 27.7 us: 1.01x faster                                                   |
| xml_etree_parse      | 160 ms                                                                 | 159 ms: 1.01x faster                                                    |
| xml_etree_generate   | 86.3 ms                                                                | 87.1 ms: 1.01x slower                                                   |
| xml_etree_process    | 59.3 ms                                                                | 60.0 ms: 1.01x slower                                                   |
| pickle               | 11.4 us                                                                | 11.6 us: 1.01x slower                                                   |
| tomli_loads          | 2.13 sec                                                               | 2.16 sec: 1.01x slower                                                  |
| json_dumps           | 10.4 ms                                                                | 10.6 ms: 1.02x slower                                                   |
| pickle_pure_python   | 298 us                                                                 | 303 us: 1.02x slower                                                    |
| unpickle             | 14.8 us                                                                | 15.1 us: 1.02x slower                                                   |
| xml_etree_iterparse  | 105 ms                                                                 | 109 ms: 1.03x slower                                                    |
| unpickle_pure_python | 219 us                                                                 | 231 us: 1.06x slower                                                    |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                   |
| python_startup_no_site | 8.99 ms                                                                | 9.12 ms: 1.01x slower                                                   |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|-----------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 11.4 ms                                                                | 12.1 ms: 1.06x slower                                                   |

All benchmarks:
===============

| Benchmark                | bm-20231107-linux-x86_64-python-0e83d941bea921380ce4-3.13.0a1+-0e83d94 | bm-20231108-linux-x86_64-brandtbucher-justin_no_ghccc-3.13.0a1+-fb676a6 |
|--------------------------|:----------------------------------------------------------------------:|:-----------------------------------------------------------------------:|
| unpack_sequence          | 47.2 ns                                                                | 41.4 ns: 1.14x faster                                                   |
| pickle_list              | 5.15 us                                                                | 4.83 us: 1.07x faster                                                   |
| pickle_dict              | 35.3 us                                                                | 33.3 us: 1.06x faster                                                   |
| unpickle_list            | 5.32 us                                                                | 5.07 us: 1.05x faster                                                   |
| pidigits                 | 195 ms                                                                 | 188 ms: 1.04x faster                                                    |
| richards_super           | 55.7 ms                                                                | 53.7 ms: 1.04x faster                                                   |
| pycparser                | 1.21 sec                                                               | 1.17 sec: 1.04x faster                                                  |
| richards                 | 48.7 ms                                                                | 47.3 ms: 1.03x faster                                                   |
| mdp                      | 2.71 sec                                                               | 2.64 sec: 1.03x faster                                                  |
| logging_silent           | 109 ns                                                                 | 106 ns: 1.03x faster                                                    |
| logging_simple           | 5.84 us                                                                | 5.75 us: 1.02x faster                                                   |
| async_tree_io_tg         | 1.23 sec                                                               | 1.22 sec: 1.01x faster                                                  |
| regex_v8                 | 25.6 ms                                                                | 25.4 ms: 1.01x faster                                                   |
| async_tree_io            | 1.19 sec                                                               | 1.18 sec: 1.01x faster                                                  |
| json_loads               | 28.0 us                                                                | 27.7 us: 1.01x faster                                                   |
| xml_etree_parse          | 160 ms                                                                 | 159 ms: 1.01x faster                                                    |
| regex_dna                | 214 ms                                                                 | 215 ms: 1.00x slower                                                    |
| sqlite_synth             | 2.77 us                                                                | 2.79 us: 1.01x slower                                                   |
| sqlglot_normalize        | 105 ms                                                                 | 106 ms: 1.01x slower                                                    |
| asyncio_tcp_ssl          | 1.79 sec                                                               | 1.80 sec: 1.01x slower                                                  |
| generators               | 29.6 ms                                                                | 29.8 ms: 1.01x slower                                                   |
| xml_etree_generate       | 86.3 ms                                                                | 87.1 ms: 1.01x slower                                                   |
| python_startup           | 10.3 ms                                                                | 10.4 ms: 1.01x slower                                                   |
| sympy_expand             | 455 ms                                                                 | 460 ms: 1.01x slower                                                    |
| spectral_norm            | 111 ms                                                                 | 112 ms: 1.01x slower                                                    |
| asyncio_tcp              | 482 ms                                                                 | 487 ms: 1.01x slower                                                    |
| sqlglot_transpile        | 1.61 ms                                                                | 1.63 ms: 1.01x slower                                                   |
| pathlib                  | 19.1 ms                                                                | 19.3 ms: 1.01x slower                                                   |
| xml_etree_process        | 59.3 ms                                                                | 60.0 ms: 1.01x slower                                                   |
| docutils                 | 2.61 sec                                                               | 2.65 sec: 1.01x slower                                                  |
| tornado_http             | 95.5 ms                                                                | 96.8 ms: 1.01x slower                                                   |
| pickle                   | 11.4 us                                                                | 11.6 us: 1.01x slower                                                   |
| sqlglot_optimize         | 53.5 ms                                                                | 54.3 ms: 1.01x slower                                                   |
| coroutines               | 22.2 ms                                                                | 22.5 ms: 1.01x slower                                                   |
| tomli_loads              | 2.13 sec                                                               | 2.16 sec: 1.01x slower                                                  |
| python_startup_no_site   | 8.99 ms                                                                | 9.12 ms: 1.01x slower                                                   |
| dulwich_log              | 65.6 ms                                                                | 66.6 ms: 1.02x slower                                                   |
| json_dumps               | 10.4 ms                                                                | 10.6 ms: 1.02x slower                                                   |
| pickle_pure_python       | 298 us                                                                 | 303 us: 1.02x slower                                                    |
| typing_runtime_protocols | 117 us                                                                 | 119 us: 1.02x slower                                                    |
| async_tree_cpu_io_mixed  | 708 ms                                                                 | 724 ms: 1.02x slower                                                    |
| meteor_contest           | 111 ms                                                                 | 113 ms: 1.02x slower                                                    |
| unpickle                 | 14.8 us                                                                | 15.1 us: 1.02x slower                                                   |
| deepcopy_reduce          | 3.09 us                                                                | 3.16 us: 1.02x slower                                                   |
| mypy2                    | 342 ms                                                                 | 350 ms: 1.02x slower                                                    |
| raytrace                 | 277 ms                                                                 | 284 ms: 1.03x slower                                                    |
| gc_traversal             | 3.58 ms                                                                | 3.67 ms: 1.03x slower                                                   |
| sympy_sum                | 148 ms                                                                 | 153 ms: 1.03x slower                                                    |
| bench_thread_pool        | 826 us                                                                 | 850 us: 1.03x slower                                                    |
| xml_etree_iterparse      | 105 ms                                                                 | 109 ms: 1.03x slower                                                    |
| deepcopy                 | 344 us                                                                 | 355 us: 1.03x slower                                                    |
| 2to3                     | 264 ms                                                                 | 273 ms: 1.04x slower                                                    |
| pyflate                  | 479 ms                                                                 | 497 ms: 1.04x slower                                                    |
| go                       | 142 ms                                                                 | 148 ms: 1.04x slower                                                    |
| scimark_lu               | 115 ms                                                                 | 120 ms: 1.05x slower                                                    |
| regex_compile            | 135 ms                                                                 | 142 ms: 1.05x slower                                                    |
| sympy_integrate          | 19.5 ms                                                                | 20.6 ms: 1.05x slower                                                   |
| regex_effbot             | 3.57 ms                                                                | 3.77 ms: 1.05x slower                                                   |
| chameleon                | 6.94 ms                                                                | 7.32 ms: 1.05x slower                                                   |
| pprint_safe_repr         | 737 ms                                                                 | 778 ms: 1.06x slower                                                    |
| unpickle_pure_python     | 219 us                                                                 | 231 us: 1.06x slower                                                    |
| async_generators         | 440 ms                                                                 | 465 ms: 1.06x slower                                                    |
| fannkuch                 | 402 ms                                                                 | 424 ms: 1.06x slower                                                    |
| deepcopy_memo            | 38.5 us                                                                | 40.8 us: 1.06x slower                                                   |
| pprint_pformat           | 1.51 sec                                                               | 1.60 sec: 1.06x slower                                                  |
| float                    | 81.8 ms                                                                | 86.8 ms: 1.06x slower                                                   |
| mako                     | 11.4 ms                                                                | 12.1 ms: 1.06x slower                                                   |
| scimark_fft              | 362 ms                                                                 | 385 ms: 1.06x slower                                                    |
| telco                    | 8.35 ms                                                                | 9.01 ms: 1.08x slower                                                   |
| chaos                    | 60.6 ms                                                                | 65.5 ms: 1.08x slower                                                   |
| scimark_monte_carlo      | 68.0 ms                                                                | 73.5 ms: 1.08x slower                                                   |
| crypto_pyaes             | 70.3 ms                                                                | 78.2 ms: 1.11x slower                                                   |
| scimark_sparse_mat_mult  | 4.87 ms                                                                | 5.50 ms: 1.13x slower                                                   |
| nbody                    | 89.4 ms                                                                | 103 ms: 1.15x slower                                                    |
| deltablue                | 3.43 ms                                                                | 3.94 ms: 1.15x slower                                                   |
| nqueens                  | 78.7 ms                                                                | 91.4 ms: 1.16x slower                                                   |
| hexiom                   | 6.23 ms                                                                | 7.51 ms: 1.21x slower                                                   |
| comprehensions           | 16.2 us                                                                | 19.7 us: 1.21x slower                                                   |
| Geometric mean           | (ref)                                                                  | 1.02x slower                                                            |

Benchmark hidden because not significant (14): logging_format, json, asyncio_websockets, async_tree_none_tg, bench_mp_pool, create_gc_cycles, coverage, async_tree_memoization_tg, sqlglot_parse, async_tree_memoization, scimark_sor, sympy_str, async_tree_cpu_io_mixed_tg, async_tree_none


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
