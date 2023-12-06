
# Results vs. 3.10.4

- fork: python
- ref: deea7c82682848b2a0db
- machine: windows-amd64
- commit hash: deea7c8
- commit date: 2023-09-05
- overall geometric mean: 1.14x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.65 sec: 1.15x faster                                                     |
| tornado_http   | 109 ms                                                      | 91.1 ms: 1.20x faster                                                      |
| Geometric mean | (ref)                                                       | 1.17x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 56.7 ms: 1.06x faster                                                      |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                                       |
| nbody          | 69.3 ms                                                     | 78.2 ms: 1.13x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 119 ms: 1.11x faster                                                       |
| regex_compile  | 103 ms                                                      | 94.3 ms: 1.10x faster                                                      |
| regex_effbot   | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 14.8 ms: 1.01x faster                                                      |
| Geometric mean | (ref)                                                       | 1.07x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.85 ms: 1.45x faster                                                      |
| pickle_pure_python   | 257 us                                                      | 197 us: 1.30x faster                                                       |
| unpickle_pure_python | 171 us                                                      | 140 us: 1.22x faster                                                       |
| xml_etree_parse      | 102 ms                                                      | 91.2 ms: 1.12x faster                                                      |
| xml_etree_process    | 43.4 ms                                                     | 39.2 ms: 1.11x faster                                                      |
| unpickle             | 9.17 us                                                     | 8.39 us: 1.09x faster                                                      |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                      |
| unpickle_list        | 2.81 us                                                     | 2.69 us: 1.04x faster                                                      |
| tomli_loads          | 1.62 sec                                                    | 1.57 sec: 1.03x faster                                                     |
| xml_etree_generate   | 54.5 ms                                                     | 56.0 ms: 1.03x slower                                                      |
| pickle               | 6.80 us                                                     | 7.09 us: 1.04x slower                                                      |
| pickle_list          | 2.59 us                                                     | 2.85 us: 1.10x slower                                                      |
| pickle_dict          | 16.9 us                                                     | 18.9 us: 1.12x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.07x faster                                                               |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.7 ms: 1.01x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 16.5 ms: 1.07x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.47 ms: 1.18x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 98.3 us: 3.30x faster                                                      |
| deltablue                | 4.17 ms                                                     | 2.30 ms: 1.81x faster                                                      |
| mypy2                    | 352 ms                                                      | 222 ms: 1.58x faster                                                       |
| richards_super           | 51.7 ms                                                     | 33.1 ms: 1.56x faster                                                      |
| logging_silent           | 96.4 ns                                                     | 64.2 ns: 1.50x faster                                                      |
| raytrace                 | 271 ms                                                      | 181 ms: 1.49x faster                                                       |
| async_tree_none          | 420 ms                                                      | 282 ms: 1.49x faster                                                       |
| asyncio_tcp              | 712 ms                                                      | 486 ms: 1.47x faster                                                       |
| json_dumps               | 8.50 ms                                                     | 5.85 ms: 1.45x faster                                                      |
| scimark_lu               | 85.4 ms                                                     | 59.4 ms: 1.44x faster                                                      |
| async_tree_io            | 1.07 sec                                                    | 752 ms: 1.42x faster                                                       |
| sqlglot_parse            | 1.22 ms                                                     | 870 us: 1.40x faster                                                       |
| richards                 | 41.2 ms                                                     | 29.4 ms: 1.40x faster                                                      |
| go                       | 136 ms                                                      | 97.9 ms: 1.39x faster                                                      |
| async_tree_memoization   | 497 ms                                                      | 361 ms: 1.38x faster                                                       |
| crypto_pyaes             | 62.3 ms                                                     | 45.5 ms: 1.37x faster                                                      |
| chaos                    | 58.9 ms                                                     | 43.7 ms: 1.35x faster                                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.10 ms: 1.33x faster                                                      |
| generators               | 31.6 ms                                                     | 24.2 ms: 1.31x faster                                                      |
| pickle_pure_python       | 257 us                                                      | 197 us: 1.30x faster                                                       |
| scimark_monte_carlo      | 55.9 ms                                                     | 43.3 ms: 1.29x faster                                                      |
| hexiom                   | 5.52 ms                                                     | 4.34 ms: 1.27x faster                                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 487 ms: 1.25x faster                                                       |
| pyflate                  | 387 ms                                                      | 312 ms: 1.24x faster                                                       |
| unpickle_pure_python     | 171 us                                                      | 140 us: 1.22x faster                                                       |
| tornado_http             | 109 ms                                                      | 91.1 ms: 1.20x faster                                                      |
| mako                     | 8.80 ms                                                     | 7.47 ms: 1.18x faster                                                      |
| scimark_sor              | 105 ms                                                      | 89.4 ms: 1.17x faster                                                      |
| pycparser                | 868 ms                                                      | 748 ms: 1.16x faster                                                       |
| docutils                 | 1.89 sec                                                    | 1.65 sec: 1.15x faster                                                     |
| deepcopy_memo            | 28.5 us                                                     | 24.9 us: 1.14x faster                                                      |
| xml_etree_parse          | 102 ms                                                      | 91.2 ms: 1.12x faster                                                      |
| mdp                      | 1.71 sec                                                    | 1.54 sec: 1.11x faster                                                     |
| regex_dna                | 132 ms                                                      | 119 ms: 1.11x faster                                                       |
| xml_etree_process        | 43.4 ms                                                     | 39.2 ms: 1.11x faster                                                      |
| bench_thread_pool        | 946 us                                                      | 855 us: 1.11x faster                                                       |
| regex_compile            | 103 ms                                                      | 94.3 ms: 1.10x faster                                                      |
| pprint_pformat           | 1.21 sec                                                    | 1.10 sec: 1.10x faster                                                     |
| spectral_norm            | 78.0 ms                                                     | 71.2 ms: 1.10x faster                                                      |
| pprint_safe_repr         | 589 ms                                                      | 538 ms: 1.10x faster                                                       |
| unpickle                 | 9.17 us                                                     | 8.39 us: 1.09x faster                                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.44 ms: 1.09x faster                                                      |
| comprehensions           | 16.0 us                                                     | 14.8 us: 1.08x faster                                                      |
| create_gc_cycles         | 782 us                                                      | 723 us: 1.08x faster                                                       |
| coroutines               | 15.9 ms                                                     | 14.7 ms: 1.08x faster                                                      |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.88 sec: 1.08x faster                                                     |
| nqueens                  | 67.0 ms                                                     | 62.2 ms: 1.08x faster                                                      |
| sqlglot_optimize         | 39.0 ms                                                     | 36.2 ms: 1.08x faster                                                      |
| float                    | 60.2 ms                                                     | 56.7 ms: 1.06x faster                                                      |
| regex_effbot             | 1.66 ms                                                     | 1.58 ms: 1.05x faster                                                      |
| sqlite_synth             | 1.84 us                                                     | 1.76 us: 1.05x faster                                                      |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                      |
| unpickle_list            | 2.81 us                                                     | 2.69 us: 1.04x faster                                                      |
| sqlglot_normalize        | 202 ms                                                      | 194 ms: 1.04x faster                                                       |
| scimark_fft              | 193 ms                                                      | 187 ms: 1.03x faster                                                       |
| tomli_loads              | 1.62 sec                                                    | 1.57 sec: 1.03x faster                                                     |
| deepcopy                 | 255 us                                                      | 248 us: 1.03x faster                                                       |
| dulwich_log              | 47.6 ms                                                     | 46.5 ms: 1.02x faster                                                      |
| json                     | 3.05 ms                                                     | 3.00 ms: 1.02x faster                                                      |
| python_startup           | 20.0 ms                                                     | 19.7 ms: 1.01x faster                                                      |
| regex_v8                 | 15.0 ms                                                     | 14.8 ms: 1.01x faster                                                      |
| fannkuch                 | 258 ms                                                      | 255 ms: 1.01x faster                                                       |
| pathlib                  | 77.4 ms                                                     | 79.5 ms: 1.03x slower                                                      |
| xml_etree_generate       | 54.5 ms                                                     | 56.0 ms: 1.03x slower                                                      |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                                       |
| meteor_contest           | 72.5 ms                                                     | 75.1 ms: 1.04x slower                                                      |
| pickle                   | 6.80 us                                                     | 7.09 us: 1.04x slower                                                      |
| deepcopy_reduce          | 2.16 us                                                     | 2.26 us: 1.05x slower                                                      |
| python_startup_no_site   | 15.5 ms                                                     | 16.5 ms: 1.07x slower                                                      |
| logging_format           | 6.66 us                                                     | 7.19 us: 1.08x slower                                                      |
| logging_simple           | 6.20 us                                                     | 6.70 us: 1.08x slower                                                      |
| async_generators         | 224 ms                                                      | 243 ms: 1.09x slower                                                       |
| pickle_list              | 2.59 us                                                     | 2.85 us: 1.10x slower                                                      |
| gc_traversal             | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                                      |
| bench_mp_pool            | 60.7 ms                                                     | 67.3 ms: 1.11x slower                                                      |
| pickle_dict              | 16.9 us                                                     | 18.9 us: 1.12x slower                                                      |
| nbody                    | 69.3 ms                                                     | 78.2 ms: 1.13x slower                                                      |
| coverage                 | 40.0 ms                                                     | 47.1 ms: 1.18x slower                                                      |
| telco                    | 3.78 ms                                                     | 4.60 ms: 1.22x slower                                                      |
| dask                     | 305 ms                                                      | 394 ms: 1.29x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.14x faster                                                               |

Benchmark hidden because not significant (2): xml_etree_iterparse, unpack_sequence
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.08x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.07x
