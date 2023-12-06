
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.26x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.92 sec: 1.17x faster                                               |
| tornado_http   | 152 ms                                                       | 122 ms: 1.24x faster                                                 |
| Geometric mean | (ref)                                                        | 1.20x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 88.9 ms: 1.54x faster                                                |
| float          | 110 ms                                                       | 78.4 ms: 1.41x faster                                                |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                 |
| Geometric mean | (ref)                                                        | 1.31x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 150 ms: 1.29x faster                                                 |
| regex_dna      | 259 ms                                                       | 247 ms: 1.05x faster                                                 |
| regex_v8       | 26.6 ms                                                      | 25.5 ms: 1.04x faster                                                |
| regex_effbot   | 2.99 ms                                                      | 3.51 ms: 1.17x slower                                                |
| Geometric mean | (ref)                                                        | 1.05x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 315 us: 1.45x faster                                                 |
| unpickle_pure_python | 321 us                                                       | 237 us: 1.35x faster                                                 |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                |
| tomli_loads          | 2.97 sec                                                     | 2.27 sec: 1.31x faster                                               |
| xml_etree_process    | 76.0 ms                                                      | 59.8 ms: 1.27x faster                                                |
| json_loads           | 30.0 us                                                      | 24.4 us: 1.23x faster                                                |
| xml_etree_generate   | 94.6 ms                                                      | 87.1 ms: 1.09x faster                                                |
| xml_etree_parse      | 162 ms                                                       | 150 ms: 1.08x faster                                                 |
| xml_etree_iterparse  | 110 ms                                                       | 105 ms: 1.05x faster                                                 |
| unpickle             | 14.2 us                                                      | 14.7 us: 1.04x slower                                                |
| pickle               | 9.94 us                                                      | 10.3 us: 1.04x slower                                                |
| unpickle_list        | 4.49 us                                                      | 4.75 us: 1.06x slower                                                |
| pickle_dict          | 30.0 us                                                      | 31.8 us: 1.06x slower                                                |
| pickle_list          | 4.11 us                                                      | 4.48 us: 1.09x slower                                                |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                |
| python_startup_no_site | 7.32 ms                                                      | 8.75 ms: 1.20x slower                                                |
| Geometric mean         | (ref)                                                        | 1.15x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.6 ms: 1.39x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-pythonperf2-x86_64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 157 us: 3.32x faster                                                 |
| asyncio_tcp              | 782 ms                                                       | 369 ms: 2.12x faster                                                 |
| deltablue                | 7.47 ms                                                      | 3.72 ms: 2.01x faster                                                |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                               |
| raytrace                 | 488 ms                                                       | 286 ms: 1.70x faster                                                 |
| logging_silent           | 166 ns                                                       | 97.4 ns: 1.70x faster                                                |
| async_tree_none          | 700 ms                                                       | 438 ms: 1.60x faster                                                 |
| generators               | 58.0 ms                                                      | 36.3 ms: 1.60x faster                                                |
| chaos                    | 107 ms                                                       | 67.1 ms: 1.60x faster                                                |
| sqlglot_parse            | 2.26 ms                                                      | 1.43 ms: 1.58x faster                                                |
| richards_super           | 90.8 ms                                                      | 58.1 ms: 1.56x faster                                                |
| scimark_lu               | 164 ms                                                       | 106 ms: 1.55x faster                                                 |
| crypto_pyaes             | 118 ms                                                       | 76.3 ms: 1.55x faster                                                |
| nbody                    | 137 ms                                                       | 88.9 ms: 1.54x faster                                                |
| go                       | 259 ms                                                       | 170 ms: 1.53x faster                                                 |
| scimark_monte_carlo      | 109 ms                                                       | 71.8 ms: 1.53x faster                                                |
| async_tree_memoization   | 824 ms                                                       | 550 ms: 1.50x faster                                                 |
| async_tree_io            | 1.61 sec                                                     | 1.08 sec: 1.49x faster                                               |
| sqlglot_transpile        | 2.71 ms                                                      | 1.84 ms: 1.47x faster                                                |
| spectral_norm            | 136 ms                                                       | 92.8 ms: 1.47x faster                                                |
| pickle_pure_python       | 457 us                                                       | 315 us: 1.45x faster                                                 |
| bench_mp_pool            | 7.18 ms                                                      | 4.97 ms: 1.45x faster                                                |
| richards                 | 74.1 ms                                                      | 51.9 ms: 1.43x faster                                                |
| float                    | 110 ms                                                       | 78.4 ms: 1.41x faster                                                |
| mako                     | 14.7 ms                                                      | 10.6 ms: 1.39x faster                                                |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 700 ms: 1.36x faster                                                 |
| unpickle_pure_python     | 321 us                                                       | 237 us: 1.35x faster                                                 |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                |
| pyflate                  | 697 ms                                                       | 523 ms: 1.33x faster                                                 |
| logging_simple           | 8.90 us                                                      | 6.73 us: 1.32x faster                                                |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.32x faster                                                |
| tomli_loads              | 2.97 sec                                                     | 2.27 sec: 1.31x faster                                               |
| regex_compile            | 194 ms                                                       | 150 ms: 1.29x faster                                                 |
| logging_format           | 9.57 us                                                      | 7.42 us: 1.29x faster                                                |
| hexiom                   | 9.52 ms                                                      | 7.42 ms: 1.28x faster                                                |
| deepcopy_memo            | 48.9 us                                                      | 38.2 us: 1.28x faster                                                |
| pycparser                | 1.66 sec                                                     | 1.31 sec: 1.27x faster                                               |
| xml_etree_process        | 76.0 ms                                                      | 59.8 ms: 1.27x faster                                                |
| pprint_pformat           | 2.15 sec                                                     | 1.71 sec: 1.26x faster                                               |
| pprint_safe_repr         | 1.05 sec                                                     | 836 ms: 1.26x faster                                                 |
| tornado_http             | 152 ms                                                       | 122 ms: 1.24x faster                                                 |
| fannkuch                 | 496 ms                                                       | 400 ms: 1.24x faster                                                 |
| json_loads               | 30.0 us                                                      | 24.4 us: 1.23x faster                                                |
| sqlglot_normalize        | 144 ms                                                       | 118 ms: 1.22x faster                                                 |
| mypy2                    | 466 ms                                                       | 384 ms: 1.21x faster                                                 |
| scimark_sor              | 177 ms                                                       | 146 ms: 1.21x faster                                                 |
| deepcopy_reduce          | 4.03 us                                                      | 3.35 us: 1.20x faster                                                |
| deepcopy                 | 454 us                                                       | 381 us: 1.19x faster                                                 |
| create_gc_cycles         | 1.82 ms                                                      | 1.53 ms: 1.19x faster                                                |
| mdp                      | 3.03 sec                                                     | 2.59 sec: 1.17x faster                                               |
| sqlglot_optimize         | 70.3 ms                                                      | 60.1 ms: 1.17x faster                                                |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.45 ms: 1.17x faster                                                |
| docutils                 | 3.40 sec                                                     | 2.92 sec: 1.17x faster                                               |
| json                     | 5.96 ms                                                      | 5.12 ms: 1.17x faster                                                |
| bench_thread_pool        | 1.14 ms                                                      | 983 us: 1.16x faster                                                 |
| dulwich_log              | 80.1 ms                                                      | 69.7 ms: 1.15x faster                                                |
| nqueens                  | 112 ms                                                       | 98.0 ms: 1.15x faster                                                |
| unpack_sequence          | 59.5 ns                                                      | 52.5 ns: 1.13x faster                                                |
| pathlib                  | 21.7 ms                                                      | 19.6 ms: 1.10x faster                                                |
| sqlite_synth             | 2.97 us                                                      | 2.70 us: 1.10x faster                                                |
| xml_etree_generate       | 94.6 ms                                                      | 87.1 ms: 1.09x faster                                                |
| xml_etree_parse          | 162 ms                                                       | 150 ms: 1.08x faster                                                 |
| comprehensions           | 26.9 us                                                      | 25.2 us: 1.07x faster                                                |
| scimark_fft              | 359 ms                                                       | 341 ms: 1.05x faster                                                 |
| xml_etree_iterparse      | 110 ms                                                       | 105 ms: 1.05x faster                                                 |
| regex_dna                | 259 ms                                                       | 247 ms: 1.05x faster                                                 |
| async_generators         | 422 ms                                                       | 403 ms: 1.05x faster                                                 |
| regex_v8                 | 26.6 ms                                                      | 25.5 ms: 1.04x faster                                                |
| meteor_contest           | 137 ms                                                       | 132 ms: 1.03x faster                                                 |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                 |
| unpickle                 | 14.2 us                                                      | 14.7 us: 1.04x slower                                                |
| pickle                   | 9.94 us                                                      | 10.3 us: 1.04x slower                                                |
| unpickle_list            | 4.49 us                                                      | 4.75 us: 1.06x slower                                                |
| gc_traversal             | 3.45 ms                                                      | 3.66 ms: 1.06x slower                                                |
| pickle_dict              | 30.0 us                                                      | 31.8 us: 1.06x slower                                                |
| pickle_list              | 4.11 us                                                      | 4.48 us: 1.09x slower                                                |
| python_startup           | 11.5 ms                                                      | 12.7 ms: 1.10x slower                                                |
| telco                    | 7.14 ms                                                      | 8.16 ms: 1.14x slower                                                |
| regex_effbot             | 2.99 ms                                                      | 3.51 ms: 1.17x slower                                                |
| python_startup_no_site   | 7.32 ms                                                      | 8.75 ms: 1.20x slower                                                |
| coverage                 | 64.0 ms                                                      | 83.1 ms: 1.30x slower                                                |
| Geometric mean           | (ref)                                                        | 1.26x faster                                                         |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.19x
