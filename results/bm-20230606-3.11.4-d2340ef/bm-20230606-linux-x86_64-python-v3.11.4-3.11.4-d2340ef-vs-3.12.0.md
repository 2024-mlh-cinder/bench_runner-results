
# Results vs. 3.12.0

- fork: python
- ref: v3.11.4
- machine: linux-x86_64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.00x faster \*
- HPT reliability: 99.98%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 274 ms                                                 | 258 ms: 1.06x faster                                   |
| chameleon      | 7.41 ms                                                | 6.58 ms: 1.13x faster                                  |
| docutils       | 2.75 sec                                               | 2.57 sec: 1.07x faster                                 |
| tornado_http   | 101 ms                                                 | 96.6 ms: 1.04x faster                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_cpu_io_mixed | 724 ms                                                 | 738 ms: 1.02x slower                                   |
| async_tree_memoization  | 580 ms                                                 | 638 ms: 1.10x slower                                   |
| async_tree_none         | 475 ms                                                 | 523 ms: 1.10x slower                                   |
| async_tree_io           | 1.16 sec                                               | 1.29 sec: 1.11x slower                                 |
| Geometric mean          | (ref)                                                  | 1.08x slower                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 83.3 ms                                                | 77.1 ms: 1.08x faster                                  |
| pidigits       | 187 ms                                                 | 190 ms: 1.01x slower                                   |
| nbody          | 92.2 ms                                                | 99.4 ms: 1.08x slower                                  |
| Geometric mean | (ref)                                                  | 1.00x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 148 ms                                                 | 136 ms: 1.09x faster                                   |
| regex_dna      | 209 ms                                                 | 200 ms: 1.04x faster                                   |
| regex_effbot   | 3.57 ms                                                | 3.45 ms: 1.04x faster                                  |
| regex_v8       | 22.7 ms                                                | 22.2 ms: 1.02x faster                                  |
| Geometric mean | (ref)                                                  | 1.05x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| unpickle             | 15.8 us                                                | 13.1 us: 1.21x faster                                  |
| pickle_list          | 4.67 us                                                | 4.01 us: 1.17x faster                                  |
| xml_etree_generate   | 88.7 ms                                                | 76.5 ms: 1.16x faster                                  |
| pickle               | 11.2 us                                                | 9.76 us: 1.15x faster                                  |
| xml_etree_process    | 61.2 ms                                                | 53.9 ms: 1.14x faster                                  |
| pickle_dict          | 33.5 us                                                | 30.7 us: 1.09x faster                                  |
| json_loads           | 28.4 us                                                | 26.2 us: 1.08x faster                                  |
| pickle_pure_python   | 326 us                                                 | 302 us: 1.08x faster                                   |
| tomli_loads          | 2.30 sec                                               | 2.19 sec: 1.05x faster                                 |
| xml_etree_iterparse  | 106 ms                                                 | 104 ms: 1.01x faster                                   |
| unpickle_list        | 5.04 us                                                | 5.02 us: 1.00x faster                                  |
| unpickle_pure_python | 230 us                                                 | 229 us: 1.00x faster                                   |
| json_dumps           | 10.6 ms                                                | 12.6 ms: 1.19x slower                                  |
| Geometric mean       | (ref)                                                  | 1.07x faster                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 6.92 ms                                                | 6.01 ms: 1.15x faster                                  |
| python_startup         | 9.53 ms                                                | 8.53 ms: 1.12x faster                                  |
| Geometric mean         | (ref)                                                  | 1.13x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 11.5 ms                                                | 9.80 ms: 1.17x faster                                  |
| django_template | 35.0 ms                                                | 33.0 ms: 1.06x faster                                  |
| Geometric mean  | (ref)                                                  | 1.12x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_generators         | 459 ms                                                 | 361 ms: 1.27x faster                                   |
| unpack_sequence          | 54.2 ns                                                | 43.6 ns: 1.24x faster                                  |
| unpickle                 | 15.8 us                                                | 13.1 us: 1.21x faster                                  |
| spectral_norm            | 115 ms                                                 | 97.1 ms: 1.18x faster                                  |
| mako                     | 11.5 ms                                                | 9.80 ms: 1.17x faster                                  |
| scimark_fft              | 381 ms                                                 | 326 ms: 1.17x faster                                   |
| scimark_sparse_mat_mult  | 5.33 ms                                                | 4.58 ms: 1.17x faster                                  |
| pickle_list              | 4.67 us                                                | 4.01 us: 1.17x faster                                  |
| xml_etree_generate       | 88.7 ms                                                | 76.5 ms: 1.16x faster                                  |
| python_startup_no_site   | 6.92 ms                                                | 6.01 ms: 1.15x faster                                  |
| pickle                   | 11.2 us                                                | 9.76 us: 1.15x faster                                  |
| xml_etree_process        | 61.2 ms                                                | 53.9 ms: 1.14x faster                                  |
| sqlite_synth             | 2.83 us                                                | 2.51 us: 1.13x faster                                  |
| chameleon                | 7.41 ms                                                | 6.58 ms: 1.13x faster                                  |
| crypto_pyaes             | 83.6 ms                                                | 74.6 ms: 1.12x faster                                  |
| python_startup           | 9.53 ms                                                | 8.53 ms: 1.12x faster                                  |
| pyflate                  | 471 ms                                                 | 421 ms: 1.12x faster                                   |
| scimark_monte_carlo      | 74.6 ms                                                | 67.7 ms: 1.10x faster                                  |
| scimark_lu               | 120 ms                                                 | 109 ms: 1.10x faster                                   |
| scimark_sor              | 129 ms                                                 | 118 ms: 1.10x faster                                   |
| deepcopy_reduce          | 3.23 us                                                | 2.94 us: 1.10x faster                                  |
| pickle_dict              | 33.5 us                                                | 30.7 us: 1.09x faster                                  |
| deepcopy_memo            | 39.7 us                                                | 36.5 us: 1.09x faster                                  |
| regex_compile            | 148 ms                                                 | 136 ms: 1.09x faster                                   |
| telco                    | 7.18 ms                                                | 6.62 ms: 1.08x faster                                  |
| json_loads               | 28.4 us                                                | 26.2 us: 1.08x faster                                  |
| pprint_safe_repr         | 765 ms                                                 | 707 ms: 1.08x faster                                   |
| float                    | 83.3 ms                                                | 77.1 ms: 1.08x faster                                  |
| pickle_pure_python       | 326 us                                                 | 302 us: 1.08x faster                                   |
| logging_format           | 7.10 us                                                | 6.58 us: 1.08x faster                                  |
| json                     | 5.22 ms                                                | 4.85 ms: 1.08x faster                                  |
| docutils                 | 2.75 sec                                               | 2.57 sec: 1.07x faster                                 |
| pprint_pformat           | 1.55 sec                                               | 1.45 sec: 1.07x faster                                 |
| 2to3                     | 274 ms                                                 | 258 ms: 1.06x faster                                   |
| deepcopy                 | 363 us                                                 | 341 us: 1.06x faster                                   |
| gunicorn                 | 1.24 ms                                                | 1.17 ms: 1.06x faster                                  |
| django_template          | 35.0 ms                                                | 33.0 ms: 1.06x faster                                  |
| gc_traversal             | 4.28 ms                                                | 4.04 ms: 1.06x faster                                  |
| sqlalchemy_declarative   | 147 ms                                                 | 139 ms: 1.06x faster                                   |
| aiohttp                  | 1.15 ms                                                | 1.09 ms: 1.05x faster                                  |
| pathlib                  | 18.9 ms                                                | 18.0 ms: 1.05x faster                                  |
| dulwich_log              | 68.7 ms                                                | 65.5 ms: 1.05x faster                                  |
| tomli_loads              | 2.30 sec                                               | 2.19 sec: 1.05x faster                                 |
| logging_simple           | 6.38 us                                                | 6.09 us: 1.05x faster                                  |
| logging_silent           | 108 ns                                                 | 103 ns: 1.05x faster                                   |
| raytrace                 | 308 ms                                                 | 294 ms: 1.05x faster                                   |
| regex_dna                | 209 ms                                                 | 200 ms: 1.04x faster                                   |
| tornado_http             | 101 ms                                                 | 96.6 ms: 1.04x faster                                  |
| fannkuch                 | 410 ms                                                 | 394 ms: 1.04x faster                                   |
| sqlalchemy_imperative    | 18.5 ms                                                | 17.9 ms: 1.04x faster                                  |
| nqueens                  | 86.2 ms                                                | 83.1 ms: 1.04x faster                                  |
| meteor_contest           | 110 ms                                                 | 106 ms: 1.04x faster                                   |
| bench_thread_pool        | 845 us                                                 | 816 us: 1.04x faster                                   |
| regex_effbot             | 3.57 ms                                                | 3.45 ms: 1.04x faster                                  |
| sqlglot_optimize         | 54.8 ms                                                | 53.0 ms: 1.03x faster                                  |
| sqlglot_normalize        | 112 ms                                                 | 108 ms: 1.03x faster                                   |
| dask                     | 369 ms                                                 | 360 ms: 1.02x faster                                   |
| sympy_str                | 296 ms                                                 | 290 ms: 1.02x faster                                   |
| regex_v8                 | 22.7 ms                                                | 22.2 ms: 1.02x faster                                  |
| sympy_integrate          | 21.2 ms                                                | 20.9 ms: 1.01x faster                                  |
| xml_etree_iterparse      | 106 ms                                                 | 104 ms: 1.01x faster                                   |
| sympy_expand             | 476 ms                                                 | 470 ms: 1.01x faster                                   |
| sympy_sum                | 167 ms                                                 | 166 ms: 1.01x faster                                   |
| hexiom                   | 6.54 ms                                                | 6.50 ms: 1.01x faster                                  |
| unpickle_list            | 5.04 us                                                | 5.02 us: 1.00x faster                                  |
| unpickle_pure_python     | 230 us                                                 | 229 us: 1.00x faster                                   |
| pycparser                | 1.17 sec                                               | 1.18 sec: 1.01x slower                                 |
| pidigits                 | 187 ms                                                 | 190 ms: 1.01x slower                                   |
| mdp                      | 2.57 sec                                               | 2.60 sec: 1.01x slower                                 |
| sqlglot_parse            | 1.35 ms                                                | 1.37 ms: 1.02x slower                                  |
| async_tree_cpu_io_mixed  | 724 ms                                                 | 738 ms: 1.02x slower                                   |
| create_gc_cycles         | 1.45 ms                                                | 1.49 ms: 1.02x slower                                  |
| chaos                    | 67.5 ms                                                | 70.2 ms: 1.04x slower                                  |
| richards                 | 46.0 ms                                                | 48.5 ms: 1.05x slower                                  |
| comprehensions           | 20.9 us                                                | 22.6 us: 1.08x slower                                  |
| nbody                    | 92.2 ms                                                | 99.4 ms: 1.08x slower                                  |
| async_tree_memoization   | 580 ms                                                 | 638 ms: 1.10x slower                                   |
| async_tree_none          | 475 ms                                                 | 523 ms: 1.10x slower                                   |
| coroutines               | 23.5 ms                                                | 25.9 ms: 1.10x slower                                  |
| async_tree_io            | 1.16 sec                                               | 1.29 sec: 1.11x slower                                 |
| richards_super           | 51.9 ms                                                | 60.0 ms: 1.16x slower                                  |
| json_dumps               | 10.6 ms                                                | 12.6 ms: 1.19x slower                                  |
| mypy2                    | 351 ms                                                 | 534 ms: 1.52x slower                                   |
| asyncio_tcp_ssl          | 1.78 sec                                               | 3.15 sec: 1.77x slower                                 |
| asyncio_tcp              | 506 ms                                                 | 922 ms: 1.82x slower                                   |
| generators               | 32.5 ms                                                | 73.7 ms: 2.27x slower                                  |
| typing_runtime_protocols | 153 us                                                 | 495 us: 3.23x slower                                   |
| Geometric mean           | (ref)                                                  | 1.00x faster                                           |

Benchmark hidden because not significant (5): sqlglot_transpile, go, bench_mp_pool, deltablue, xml_etree_parse
Ignored benchmarks (6) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
Ignored benchmarks (7) of results/bm-20230606-3.11.4-d2340ef/bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 99.98% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
