
# Results vs. 3.10.4

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: windows-amd64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.16x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                                     |
| tornado_http   | 109 ms                                                      | 89.3 ms: 1.22x faster                                                      |
| Geometric mean | (ref)                                                       | 1.20x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.8 ms: 1.08x faster                                                      |
| pidigits       | 145 ms                                                      | 151 ms: 1.04x slower                                                       |
| nbody          | 69.3 ms                                                     | 74.6 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 90.2 ms: 1.15x faster                                                      |
| regex_dna      | 132 ms                                                      | 118 ms: 1.12x faster                                                       |
| regex_effbot   | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                                      |
| Geometric mean | (ref)                                                       | 1.08x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.64 ms: 1.51x faster                                                      |
| pickle_pure_python   | 257 us                                                      | 193 us: 1.33x faster                                                       |
| unpickle_pure_python | 171 us                                                      | 137 us: 1.25x faster                                                       |
| xml_etree_process    | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                                      |
| unpickle             | 9.17 us                                                     | 8.21 us: 1.12x faster                                                      |
| xml_etree_parse      | 102 ms                                                      | 92.6 ms: 1.10x faster                                                      |
| tomli_loads          | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                     |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                      |
| unpickle_list        | 2.81 us                                                     | 2.73 us: 1.03x faster                                                      |
| xml_etree_iterparse  | 63.5 ms                                                     | 64.3 ms: 1.01x slower                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                                      |
| pickle               | 6.80 us                                                     | 7.34 us: 1.08x slower                                                      |
| pickle_dict          | 16.9 us                                                     | 18.6 us: 1.10x slower                                                      |
| pickle_list          | 2.59 us                                                     | 3.43 us: 1.33x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.07x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 16.5 ms: 1.06x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.41 ms: 1.19x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 99.4 us: 3.27x faster                                                      |
| deltablue                | 4.17 ms                                                     | 2.20 ms: 1.90x faster                                                      |
| mypy2                    | 352 ms                                                      | 214 ms: 1.64x faster                                                       |
| richards_super           | 51.7 ms                                                     | 32.7 ms: 1.58x faster                                                      |
| raytrace                 | 271 ms                                                      | 171 ms: 1.58x faster                                                       |
| async_tree_none          | 420 ms                                                      | 269 ms: 1.56x faster                                                       |
| logging_silent           | 96.4 ns                                                     | 63.5 ns: 1.52x faster                                                      |
| asyncio_tcp              | 712 ms                                                      | 471 ms: 1.51x faster                                                       |
| json_dumps               | 8.50 ms                                                     | 5.64 ms: 1.51x faster                                                      |
| sqlglot_parse            | 1.22 ms                                                     | 815 us: 1.50x faster                                                       |
| go                       | 136 ms                                                      | 91.3 ms: 1.49x faster                                                      |
| async_tree_io            | 1.07 sec                                                    | 724 ms: 1.47x faster                                                       |
| async_tree_memoization   | 497 ms                                                      | 343 ms: 1.45x faster                                                       |
| richards                 | 41.2 ms                                                     | 28.5 ms: 1.44x faster                                                      |
| chaos                    | 58.9 ms                                                     | 40.9 ms: 1.44x faster                                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.04 ms: 1.41x faster                                                      |
| scimark_lu               | 85.4 ms                                                     | 60.8 ms: 1.40x faster                                                      |
| generators               | 31.6 ms                                                     | 22.7 ms: 1.39x faster                                                      |
| crypto_pyaes             | 62.3 ms                                                     | 45.7 ms: 1.36x faster                                                      |
| pickle_pure_python       | 257 us                                                      | 193 us: 1.33x faster                                                       |
| hexiom                   | 5.52 ms                                                     | 4.18 ms: 1.32x faster                                                      |
| scimark_monte_carlo      | 55.9 ms                                                     | 42.9 ms: 1.30x faster                                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 471 ms: 1.29x faster                                                       |
| pyflate                  | 387 ms                                                      | 304 ms: 1.27x faster                                                       |
| scimark_sor              | 105 ms                                                      | 82.8 ms: 1.27x faster                                                      |
| unpickle_pure_python     | 171 us                                                      | 137 us: 1.25x faster                                                       |
| tornado_http             | 109 ms                                                      | 89.3 ms: 1.22x faster                                                      |
| spectral_norm            | 78.0 ms                                                     | 65.2 ms: 1.20x faster                                                      |
| deepcopy_memo            | 28.5 us                                                     | 24.0 us: 1.19x faster                                                      |
| mako                     | 8.80 ms                                                     | 7.41 ms: 1.19x faster                                                      |
| docutils                 | 1.89 sec                                                    | 1.62 sec: 1.17x faster                                                     |
| mdp                      | 1.71 sec                                                    | 1.47 sec: 1.17x faster                                                     |
| regex_compile            | 103 ms                                                      | 90.2 ms: 1.15x faster                                                      |
| xml_etree_process        | 43.4 ms                                                     | 38.1 ms: 1.14x faster                                                      |
| pprint_safe_repr         | 589 ms                                                      | 517 ms: 1.14x faster                                                       |
| pprint_pformat           | 1.21 sec                                                    | 1.06 sec: 1.14x faster                                                     |
| sqlglot_optimize         | 39.0 ms                                                     | 34.5 ms: 1.13x faster                                                      |
| bench_thread_pool        | 946 us                                                      | 842 us: 1.12x faster                                                       |
| comprehensions           | 16.0 us                                                     | 14.2 us: 1.12x faster                                                      |
| unpickle                 | 9.17 us                                                     | 8.21 us: 1.12x faster                                                      |
| regex_dna                | 132 ms                                                      | 118 ms: 1.12x faster                                                       |
| sqlglot_normalize        | 202 ms                                                      | 183 ms: 1.11x faster                                                       |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.84 sec: 1.11x faster                                                     |
| nqueens                  | 67.0 ms                                                     | 61.0 ms: 1.10x faster                                                      |
| xml_etree_parse          | 102 ms                                                      | 92.6 ms: 1.10x faster                                                      |
| deepcopy                 | 255 us                                                      | 234 us: 1.09x faster                                                       |
| tomli_loads              | 1.62 sec                                                    | 1.49 sec: 1.09x faster                                                     |
| coroutines               | 15.9 ms                                                     | 14.6 ms: 1.09x faster                                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.46 ms: 1.08x faster                                                      |
| float                    | 60.2 ms                                                     | 55.8 ms: 1.08x faster                                                      |
| create_gc_cycles         | 782 us                                                      | 730 us: 1.07x faster                                                       |
| regex_effbot             | 1.66 ms                                                     | 1.57 ms: 1.06x faster                                                      |
| sqlite_synth             | 1.84 us                                                     | 1.74 us: 1.06x faster                                                      |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                      |
| scimark_fft              | 193 ms                                                      | 184 ms: 1.05x faster                                                       |
| dulwich_log              | 47.6 ms                                                     | 45.6 ms: 1.04x faster                                                      |
| json                     | 3.05 ms                                                     | 2.95 ms: 1.03x faster                                                      |
| unpickle_list            | 2.81 us                                                     | 2.73 us: 1.03x faster                                                      |
| deepcopy_reduce          | 2.16 us                                                     | 2.10 us: 1.03x faster                                                      |
| regex_v8                 | 15.0 ms                                                     | 14.9 ms: 1.01x faster                                                      |
| python_startup           | 20.0 ms                                                     | 19.8 ms: 1.01x faster                                                      |
| fannkuch                 | 258 ms                                                      | 261 ms: 1.01x slower                                                       |
| xml_etree_iterparse      | 63.5 ms                                                     | 64.3 ms: 1.01x slower                                                      |
| pathlib                  | 77.4 ms                                                     | 78.3 ms: 1.01x slower                                                      |
| meteor_contest           | 72.5 ms                                                     | 73.6 ms: 1.01x slower                                                      |
| xml_etree_generate       | 54.5 ms                                                     | 55.8 ms: 1.02x slower                                                      |
| logging_format           | 6.66 us                                                     | 6.82 us: 1.02x slower                                                      |
| unpack_sequence          | 37.8 ns                                                     | 38.8 ns: 1.03x slower                                                      |
| logging_simple           | 6.20 us                                                     | 6.36 us: 1.03x slower                                                      |
| pidigits                 | 145 ms                                                      | 151 ms: 1.04x slower                                                       |
| python_startup_no_site   | 15.5 ms                                                     | 16.5 ms: 1.06x slower                                                      |
| nbody                    | 69.3 ms                                                     | 74.6 ms: 1.08x slower                                                      |
| pickle                   | 6.80 us                                                     | 7.34 us: 1.08x slower                                                      |
| pickle_dict              | 16.9 us                                                     | 18.6 us: 1.10x slower                                                      |
| async_generators         | 224 ms                                                      | 246 ms: 1.10x slower                                                       |
| gc_traversal             | 1.34 ms                                                     | 1.49 ms: 1.11x slower                                                      |
| coverage                 | 40.0 ms                                                     | 44.5 ms: 1.11x slower                                                      |
| bench_mp_pool            | 60.7 ms                                                     | 67.7 ms: 1.12x slower                                                      |
| dask                     | 305 ms                                                      | 370 ms: 1.21x slower                                                       |
| telco                    | 3.78 ms                                                     | 4.79 ms: 1.27x slower                                                      |
| pickle_list              | 2.59 us                                                     | 3.43 us: 1.33x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.16x faster                                                               |

Benchmark hidden because not significant (1): pycparser
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
