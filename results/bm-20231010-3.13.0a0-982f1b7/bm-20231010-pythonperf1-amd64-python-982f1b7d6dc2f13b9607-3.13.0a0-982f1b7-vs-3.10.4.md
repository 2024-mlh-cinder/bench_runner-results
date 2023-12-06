
# Results vs. 3.10.4

- fork: python
- ref: 982f1b7d6dc2f13b9607
- machine: windows-amd64
- commit hash: 982f1b7
- commit date: 2023-10-10
- overall geometric mean: 1.16x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                                     |
| tornado_http   | 109 ms                                                      | 89.2 ms: 1.22x faster                                                      |
| Geometric mean | (ref)                                                       | 1.19x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 60.2 ms                                                     | 55.2 ms: 1.09x faster                                                      |
| pidigits       | 145 ms                                                      | 150 ms: 1.03x slower                                                       |
| nbody          | 69.3 ms                                                     | 75.1 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 103 ms                                                      | 92.4 ms: 1.12x faster                                                      |
| regex_dna      | 132 ms                                                      | 123 ms: 1.07x faster                                                       |
| regex_effbot   | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 15.1 ms: 1.00x slower                                                      |
| Geometric mean | (ref)                                                       | 1.05x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.81 ms: 1.46x faster                                                      |
| pickle_pure_python   | 257 us                                                      | 197 us: 1.30x faster                                                       |
| unpickle_pure_python | 171 us                                                      | 141 us: 1.21x faster                                                       |
| unpickle             | 9.17 us                                                     | 8.13 us: 1.13x faster                                                      |
| xml_etree_parse      | 102 ms                                                      | 91.8 ms: 1.11x faster                                                      |
| xml_etree_process    | 43.4 ms                                                     | 39.6 ms: 1.10x faster                                                      |
| tomli_loads          | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                                     |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                                      |
| unpickle_list        | 2.81 us                                                     | 2.71 us: 1.04x faster                                                      |
| xml_etree_iterparse  | 63.5 ms                                                     | 64.4 ms: 1.01x slower                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 56.9 ms: 1.04x slower                                                      |
| pickle               | 6.80 us                                                     | 7.26 us: 1.07x slower                                                      |
| pickle_dict          | 16.9 us                                                     | 18.3 us: 1.08x slower                                                      |
| pickle_list          | 2.59 us                                                     | 2.87 us: 1.11x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.07x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.3 ms: 1.03x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.00x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.19 ms: 1.22x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 103 us: 3.16x faster                                                       |
| deltablue                | 4.17 ms                                                     | 2.20 ms: 1.89x faster                                                      |
| mypy2                    | 352 ms                                                      | 217 ms: 1.62x faster                                                       |
| richards_super           | 51.7 ms                                                     | 32.5 ms: 1.59x faster                                                      |
| async_tree_none          | 420 ms                                                      | 271 ms: 1.55x faster                                                       |
| raytrace                 | 271 ms                                                      | 178 ms: 1.53x faster                                                       |
| logging_silent           | 96.4 ns                                                     | 63.6 ns: 1.52x faster                                                      |
| asyncio_tcp              | 712 ms                                                      | 474 ms: 1.50x faster                                                       |
| go                       | 136 ms                                                      | 91.8 ms: 1.48x faster                                                      |
| sqlglot_parse            | 1.22 ms                                                     | 828 us: 1.47x faster                                                       |
| json_dumps               | 8.50 ms                                                     | 5.81 ms: 1.46x faster                                                      |
| async_tree_io            | 1.07 sec                                                    | 729 ms: 1.46x faster                                                       |
| async_tree_memoization   | 497 ms                                                      | 346 ms: 1.44x faster                                                       |
| richards                 | 41.2 ms                                                     | 28.9 ms: 1.42x faster                                                      |
| scimark_lu               | 85.4 ms                                                     | 60.4 ms: 1.42x faster                                                      |
| generators               | 31.6 ms                                                     | 22.4 ms: 1.41x faster                                                      |
| crypto_pyaes             | 62.3 ms                                                     | 44.7 ms: 1.39x faster                                                      |
| chaos                    | 58.9 ms                                                     | 42.4 ms: 1.39x faster                                                      |
| sqlglot_transpile        | 1.46 ms                                                     | 1.06 ms: 1.39x faster                                                      |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 455 ms: 1.34x faster                                                       |
| hexiom                   | 5.52 ms                                                     | 4.22 ms: 1.31x faster                                                      |
| pickle_pure_python       | 257 us                                                      | 197 us: 1.30x faster                                                       |
| scimark_monte_carlo      | 55.9 ms                                                     | 43.1 ms: 1.29x faster                                                      |
| pyflate                  | 387 ms                                                      | 304 ms: 1.27x faster                                                       |
| scimark_sor              | 105 ms                                                      | 85.0 ms: 1.23x faster                                                      |
| tornado_http             | 109 ms                                                      | 89.2 ms: 1.22x faster                                                      |
| mako                     | 8.80 ms                                                     | 7.19 ms: 1.22x faster                                                      |
| unpickle_pure_python     | 171 us                                                      | 141 us: 1.21x faster                                                       |
| mdp                      | 1.71 sec                                                    | 1.43 sec: 1.19x faster                                                     |
| spectral_norm            | 78.0 ms                                                     | 65.6 ms: 1.19x faster                                                      |
| docutils                 | 1.89 sec                                                    | 1.63 sec: 1.16x faster                                                     |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.77 sec: 1.15x faster                                                     |
| deepcopy_memo            | 28.5 us                                                     | 24.9 us: 1.15x faster                                                      |
| bench_thread_pool        | 946 us                                                      | 835 us: 1.13x faster                                                       |
| unpickle                 | 9.17 us                                                     | 8.13 us: 1.13x faster                                                      |
| regex_compile            | 103 ms                                                      | 92.4 ms: 1.12x faster                                                      |
| xml_etree_parse          | 102 ms                                                      | 91.8 ms: 1.11x faster                                                      |
| sqlglot_optimize         | 39.0 ms                                                     | 35.2 ms: 1.11x faster                                                      |
| comprehensions           | 16.0 us                                                     | 14.5 us: 1.10x faster                                                      |
| pprint_pformat           | 1.21 sec                                                    | 1.10 sec: 1.10x faster                                                     |
| pprint_safe_repr         | 589 ms                                                      | 536 ms: 1.10x faster                                                       |
| xml_etree_process        | 43.4 ms                                                     | 39.6 ms: 1.10x faster                                                      |
| nqueens                  | 67.0 ms                                                     | 61.2 ms: 1.10x faster                                                      |
| float                    | 60.2 ms                                                     | 55.2 ms: 1.09x faster                                                      |
| sqlglot_normalize        | 202 ms                                                      | 186 ms: 1.09x faster                                                       |
| create_gc_cycles         | 782 us                                                      | 720 us: 1.09x faster                                                       |
| tomli_loads              | 1.62 sec                                                    | 1.50 sec: 1.08x faster                                                     |
| sqlite_synth             | 1.84 us                                                     | 1.70 us: 1.08x faster                                                      |
| coroutines               | 15.9 ms                                                     | 14.8 ms: 1.08x faster                                                      |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.48 ms: 1.07x faster                                                      |
| regex_dna                | 132 ms                                                      | 123 ms: 1.07x faster                                                       |
| scimark_fft              | 193 ms                                                      | 183 ms: 1.06x faster                                                       |
| deepcopy                 | 255 us                                                      | 242 us: 1.05x faster                                                       |
| dulwich_log              | 47.6 ms                                                     | 45.4 ms: 1.05x faster                                                      |
| json                     | 3.05 ms                                                     | 2.92 ms: 1.05x faster                                                      |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                                      |
| unpickle_list            | 2.81 us                                                     | 2.71 us: 1.04x faster                                                      |
| python_startup           | 20.0 ms                                                     | 19.3 ms: 1.03x faster                                                      |
| regex_effbot             | 1.66 ms                                                     | 1.61 ms: 1.03x faster                                                      |
| regex_v8                 | 15.0 ms                                                     | 15.1 ms: 1.00x slower                                                      |
| fannkuch                 | 258 ms                                                      | 260 ms: 1.01x slower                                                       |
| xml_etree_iterparse      | 63.5 ms                                                     | 64.4 ms: 1.01x slower                                                      |
| deepcopy_reduce          | 2.16 us                                                     | 2.20 us: 1.02x slower                                                      |
| pidigits                 | 145 ms                                                      | 150 ms: 1.03x slower                                                       |
| python_startup_no_site   | 15.5 ms                                                     | 16.1 ms: 1.04x slower                                                      |
| xml_etree_generate       | 54.5 ms                                                     | 56.9 ms: 1.04x slower                                                      |
| logging_format           | 6.66 us                                                     | 6.96 us: 1.04x slower                                                      |
| meteor_contest           | 72.5 ms                                                     | 75.9 ms: 1.05x slower                                                      |
| bench_mp_pool            | 60.7 ms                                                     | 63.7 ms: 1.05x slower                                                      |
| logging_simple           | 6.20 us                                                     | 6.55 us: 1.06x slower                                                      |
| pickle                   | 6.80 us                                                     | 7.26 us: 1.07x slower                                                      |
| pickle_dict              | 16.9 us                                                     | 18.3 us: 1.08x slower                                                      |
| nbody                    | 69.3 ms                                                     | 75.1 ms: 1.08x slower                                                      |
| unpack_sequence          | 37.8 ns                                                     | 41.2 ns: 1.09x slower                                                      |
| async_generators         | 224 ms                                                      | 245 ms: 1.09x slower                                                       |
| gc_traversal             | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                                      |
| pickle_list              | 2.59 us                                                     | 2.87 us: 1.11x slower                                                      |
| coverage                 | 40.0 ms                                                     | 46.2 ms: 1.15x slower                                                      |
| telco                    | 3.78 ms                                                     | 4.72 ms: 1.25x slower                                                      |
| Geometric mean           | (ref)                                                       | 1.16x faster                                                               |

Benchmark hidden because not significant (2): pathlib, pycparser
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
