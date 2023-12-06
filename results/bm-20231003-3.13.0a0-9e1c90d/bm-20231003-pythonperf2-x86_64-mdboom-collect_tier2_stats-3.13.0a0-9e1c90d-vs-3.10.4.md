
# Results vs. 3.10.4

- fork: mdboom
- ref: collect_tier2_stats
- machine: linux-x86_64
- commit hash: 9e1c90d
- commit date: 2023-10-03
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.99 sec: 1.14x faster                                                     |
| tornado_http   | 152 ms                                                       | 124 ms: 1.23x faster                                                       |
| Geometric mean | (ref)                                                        | 1.18x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 102 ms: 1.35x faster                                                       |
| float          | 110 ms                                                       | 83.3 ms: 1.32x faster                                                      |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                        | 1.22x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 172 ms: 1.13x faster                                                       |
| regex_dna      | 259 ms                                                       | 242 ms: 1.07x faster                                                       |
| regex_v8       | 26.6 ms                                                      | 25.6 ms: 1.04x faster                                                      |
| regex_effbot   | 2.99 ms                                                      | 3.61 ms: 1.20x slower                                                      |
| Geometric mean | (ref)                                                        | 1.01x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 323 us: 1.41x faster                                                       |
| unpickle_pure_python | 321 us                                                       | 239 us: 1.34x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                      |
| xml_etree_process    | 76.0 ms                                                      | 59.8 ms: 1.27x faster                                                      |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                                      |
| tomli_loads          | 2.97 sec                                                     | 2.71 sec: 1.10x faster                                                     |
| xml_etree_generate   | 94.6 ms                                                      | 87.7 ms: 1.08x faster                                                      |
| xml_etree_parse      | 162 ms                                                       | 153 ms: 1.06x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 109 ms: 1.02x faster                                                       |
| unpickle             | 14.2 us                                                      | 14.5 us: 1.02x slower                                                      |
| pickle               | 9.94 us                                                      | 10.2 us: 1.03x slower                                                      |
| unpickle_list        | 4.49 us                                                      | 4.70 us: 1.05x slower                                                      |
| pickle_list          | 4.11 us                                                      | 4.32 us: 1.05x slower                                                      |
| pickle_dict          | 30.0 us                                                      | 32.2 us: 1.07x slower                                                      |
| Geometric mean       | (ref)                                                        | 1.10x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                      |
| python_startup_no_site | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.14x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 11.5 ms: 1.27x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231003-pythonperf2-x86_64-mdboom-collect_tier2_stats-3.13.0a0-9e1c90d |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 162 us: 3.22x faster                                                       |
| asyncio_tcp              | 782 ms                                                       | 373 ms: 2.10x faster                                                       |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.59 sec: 1.95x faster                                                     |
| deltablue                | 7.47 ms                                                      | 3.91 ms: 1.91x faster                                                      |
| raytrace                 | 488 ms                                                       | 280 ms: 1.75x faster                                                       |
| logging_silent           | 166 ns                                                       | 99.8 ns: 1.66x faster                                                      |
| generators               | 58.0 ms                                                      | 36.0 ms: 1.61x faster                                                      |
| scimark_monte_carlo      | 109 ms                                                       | 68.0 ms: 1.61x faster                                                      |
| async_tree_none          | 700 ms                                                       | 444 ms: 1.58x faster                                                       |
| sqlglot_parse            | 2.26 ms                                                      | 1.43 ms: 1.57x faster                                                      |
| chaos                    | 107 ms                                                       | 68.1 ms: 1.57x faster                                                      |
| crypto_pyaes             | 118 ms                                                       | 75.8 ms: 1.56x faster                                                      |
| bench_mp_pool            | 7.18 ms                                                      | 4.69 ms: 1.53x faster                                                      |
| spectral_norm            | 136 ms                                                       | 91.6 ms: 1.49x faster                                                      |
| async_tree_memoization   | 824 ms                                                       | 557 ms: 1.48x faster                                                       |
| scimark_lu               | 164 ms                                                       | 111 ms: 1.47x faster                                                       |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                                     |
| sqlglot_transpile        | 2.71 ms                                                      | 1.85 ms: 1.46x faster                                                      |
| richards_super           | 90.8 ms                                                      | 63.6 ms: 1.43x faster                                                      |
| go                       | 259 ms                                                       | 182 ms: 1.42x faster                                                       |
| pickle_pure_python       | 457 us                                                       | 323 us: 1.41x faster                                                       |
| nbody                    | 137 ms                                                       | 102 ms: 1.35x faster                                                       |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 708 ms: 1.34x faster                                                       |
| unpickle_pure_python     | 321 us                                                       | 239 us: 1.34x faster                                                       |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                      |
| float                    | 110 ms                                                       | 83.3 ms: 1.32x faster                                                      |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.32x faster                                                      |
| pyflate                  | 697 ms                                                       | 536 ms: 1.30x faster                                                       |
| richards                 | 74.1 ms                                                      | 57.6 ms: 1.29x faster                                                      |
| mako                     | 14.7 ms                                                      | 11.5 ms: 1.27x faster                                                      |
| xml_etree_process        | 76.0 ms                                                      | 59.8 ms: 1.27x faster                                                      |
| logging_simple           | 8.90 us                                                      | 7.05 us: 1.26x faster                                                      |
| pprint_pformat           | 2.15 sec                                                     | 1.72 sec: 1.26x faster                                                     |
| pprint_safe_repr         | 1.05 sec                                                     | 840 ms: 1.25x faster                                                       |
| logging_format           | 9.57 us                                                      | 7.68 us: 1.25x faster                                                      |
| tornado_http             | 152 ms                                                       | 124 ms: 1.23x faster                                                       |
| sqlglot_normalize        | 144 ms                                                       | 118 ms: 1.22x faster                                                       |
| pycparser                | 1.66 sec                                                     | 1.37 sec: 1.22x faster                                                     |
| json_loads               | 30.0 us                                                      | 24.6 us: 1.22x faster                                                      |
| mypy2                    | 466 ms                                                       | 387 ms: 1.21x faster                                                       |
| scimark_sor              | 177 ms                                                       | 149 ms: 1.19x faster                                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 59.9 ms: 1.17x faster                                                      |
| deepcopy_reduce          | 4.03 us                                                      | 3.47 us: 1.16x faster                                                      |
| deepcopy                 | 454 us                                                       | 393 us: 1.16x faster                                                       |
| json                     | 5.96 ms                                                      | 5.17 ms: 1.15x faster                                                      |
| deepcopy_memo            | 48.9 us                                                      | 42.6 us: 1.15x faster                                                      |
| hexiom                   | 9.52 ms                                                      | 8.29 ms: 1.15x faster                                                      |
| bench_thread_pool        | 1.14 ms                                                      | 998 us: 1.14x faster                                                       |
| docutils                 | 3.40 sec                                                     | 2.99 sec: 1.14x faster                                                     |
| unpack_sequence          | 59.5 ns                                                      | 52.5 ns: 1.13x faster                                                      |
| mdp                      | 3.03 sec                                                     | 2.68 sec: 1.13x faster                                                     |
| regex_compile            | 194 ms                                                       | 172 ms: 1.13x faster                                                       |
| dulwich_log              | 80.1 ms                                                      | 71.5 ms: 1.12x faster                                                      |
| sqlite_synth             | 2.97 us                                                      | 2.68 us: 1.10x faster                                                      |
| tomli_loads              | 2.97 sec                                                     | 2.71 sec: 1.10x faster                                                     |
| create_gc_cycles         | 1.82 ms                                                      | 1.68 ms: 1.08x faster                                                      |
| xml_etree_generate       | 94.6 ms                                                      | 87.7 ms: 1.08x faster                                                      |
| pathlib                  | 21.7 ms                                                      | 20.2 ms: 1.07x faster                                                      |
| regex_dna                | 259 ms                                                       | 242 ms: 1.07x faster                                                       |
| fannkuch                 | 496 ms                                                       | 465 ms: 1.07x faster                                                       |
| xml_etree_parse          | 162 ms                                                       | 153 ms: 1.06x faster                                                       |
| async_generators         | 422 ms                                                       | 402 ms: 1.05x faster                                                       |
| nqueens                  | 112 ms                                                       | 108 ms: 1.04x faster                                                       |
| regex_v8                 | 26.6 ms                                                      | 25.6 ms: 1.04x faster                                                      |
| scimark_fft              | 359 ms                                                       | 347 ms: 1.04x faster                                                       |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                       |
| xml_etree_iterparse      | 110 ms                                                       | 109 ms: 1.02x faster                                                       |
| meteor_contest           | 137 ms                                                       | 138 ms: 1.01x slower                                                       |
| comprehensions           | 26.9 us                                                      | 27.3 us: 1.01x slower                                                      |
| unpickle                 | 14.2 us                                                      | 14.5 us: 1.02x slower                                                      |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.03x slower                                                      |
| gc_traversal             | 3.45 ms                                                      | 3.58 ms: 1.04x slower                                                      |
| unpickle_list            | 4.49 us                                                      | 4.70 us: 1.05x slower                                                      |
| pickle_list              | 4.11 us                                                      | 4.32 us: 1.05x slower                                                      |
| pickle_dict              | 30.0 us                                                      | 32.2 us: 1.07x slower                                                      |
| python_startup           | 11.5 ms                                                      | 12.6 ms: 1.10x slower                                                      |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 5.84 ms: 1.13x slower                                                      |
| telco                    | 7.14 ms                                                      | 8.16 ms: 1.14x slower                                                      |
| python_startup_no_site   | 7.32 ms                                                      | 8.65 ms: 1.18x slower                                                      |
| regex_effbot             | 2.99 ms                                                      | 3.61 ms: 1.20x slower                                                      |
| coverage                 | 64.0 ms                                                      | 82.5 ms: 1.29x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.23x faster                                                               |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.13x
