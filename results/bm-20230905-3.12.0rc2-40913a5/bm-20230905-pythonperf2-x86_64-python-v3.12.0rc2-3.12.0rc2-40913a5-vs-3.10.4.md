
# Results vs. 3.10.4

- fork: python
- ref: v3.12.0rc2
- machine: linux-x86_64
- commit hash: 40913a5
- commit date: 2023-09-05
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| 2to3           | 350 ms                                                       | 287 ms: 1.22x faster                                               |
| docutils       | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                             |
| tornado_http   | 152 ms                                                       | 120 ms: 1.27x faster                                               |
| Geometric mean | (ref)                                                        | 1.22x faster                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 87.5 ms: 1.57x faster                                              |
| float          | 110 ms                                                       | 79.6 ms: 1.39x faster                                              |
| pidigits       | 271 ms                                                       | 264 ms: 1.03x faster                                               |
| Geometric mean | (ref)                                                        | 1.31x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 146 ms: 1.33x faster                                               |
| regex_v8       | 26.6 ms                                                      | 23.8 ms: 1.12x faster                                              |
| regex_dna      | 259 ms                                                       | 238 ms: 1.09x faster                                               |
| regex_effbot   | 2.99 ms                                                      | 3.52 ms: 1.18x slower                                              |
| Geometric mean | (ref)                                                        | 1.08x faster                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|----------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| unpickle_pure_python | 321 us                                                       | 212 us: 1.52x faster                                               |
| pickle_pure_python   | 457 us                                                       | 326 us: 1.40x faster                                               |
| json_dumps           | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                              |
| tomli_loads          | 2.97 sec                                                     | 2.17 sec: 1.37x faster                                             |
| xml_etree_process    | 76.0 ms                                                      | 58.9 ms: 1.29x faster                                              |
| json_loads           | 30.0 us                                                      | 24.4 us: 1.23x faster                                              |
| xml_etree_parse      | 162 ms                                                       | 146 ms: 1.11x faster                                               |
| xml_etree_generate   | 94.6 ms                                                      | 85.8 ms: 1.10x faster                                              |
| xml_etree_iterparse  | 110 ms                                                       | 103 ms: 1.07x faster                                               |
| unpickle             | 14.2 us                                                      | 14.7 us: 1.04x slower                                              |
| pickle               | 9.94 us                                                      | 10.4 us: 1.05x slower                                              |
| unpickle_list        | 4.49 us                                                      | 4.75 us: 1.06x slower                                              |
| pickle_dict          | 30.0 us                                                      | 32.4 us: 1.08x slower                                              |
| pickle_list          | 4.11 us                                                      | 4.46 us: 1.09x slower                                              |
| Geometric mean       | (ref)                                                        | 1.14x faster                                                       |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                              |
| python_startup_no_site | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                              |
| Geometric mean         | (ref)                                                        | 1.10x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|-----------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 9.92 ms: 1.48x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-python-v3.12.0rc2-3.12.0rc2-40913a5 |
|--------------------------|:------------------------------------------------------------:|:------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 149 us: 3.50x faster                                               |
| deltablue                | 7.47 ms                                                      | 3.29 ms: 2.27x faster                                              |
| asyncio_tcp              | 782 ms                                                       | 386 ms: 2.03x faster                                               |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.57 sec: 1.96x faster                                             |
| richards_super           | 90.8 ms                                                      | 50.5 ms: 1.80x faster                                              |
| go                       | 259 ms                                                       | 148 ms: 1.75x faster                                               |
| logging_silent           | 166 ns                                                       | 95.9 ns: 1.73x faster                                              |
| chaos                    | 107 ms                                                       | 62.3 ms: 1.72x faster                                              |
| scimark_lu               | 164 ms                                                       | 97.6 ms: 1.68x faster                                              |
| richards                 | 74.1 ms                                                      | 44.6 ms: 1.66x faster                                              |
| scimark_sor              | 177 ms                                                       | 111 ms: 1.60x faster                                               |
| sqlglot_parse            | 2.26 ms                                                      | 1.41 ms: 1.60x faster                                              |
| hexiom                   | 9.52 ms                                                      | 5.97 ms: 1.59x faster                                              |
| raytrace                 | 488 ms                                                       | 308 ms: 1.58x faster                                               |
| generators               | 58.0 ms                                                      | 36.7 ms: 1.58x faster                                              |
| scimark_monte_carlo      | 109 ms                                                       | 69.4 ms: 1.58x faster                                              |
| pyflate                  | 697 ms                                                       | 443 ms: 1.57x faster                                               |
| nbody                    | 137 ms                                                       | 87.5 ms: 1.57x faster                                              |
| async_tree_none          | 700 ms                                                       | 458 ms: 1.53x faster                                               |
| async_tree_io            | 1.61 sec                                                     | 1.06 sec: 1.52x faster                                             |
| unpickle_pure_python     | 321 us                                                       | 212 us: 1.52x faster                                               |
| bench_mp_pool            | 7.18 ms                                                      | 4.79 ms: 1.50x faster                                              |
| sqlglot_transpile        | 2.71 ms                                                      | 1.81 ms: 1.50x faster                                              |
| spectral_norm            | 136 ms                                                       | 91.3 ms: 1.49x faster                                              |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                               |
| fannkuch                 | 496 ms                                                       | 335 ms: 1.48x faster                                               |
| mako                     | 14.7 ms                                                      | 9.92 ms: 1.48x faster                                              |
| crypto_pyaes             | 118 ms                                                       | 81.5 ms: 1.45x faster                                              |
| pickle_pure_python       | 457 us                                                       | 326 us: 1.40x faster                                               |
| json_dumps               | 14.2 ms                                                      | 10.2 ms: 1.39x faster                                              |
| float                    | 110 ms                                                       | 79.6 ms: 1.39x faster                                              |
| tomli_loads              | 2.97 sec                                                     | 2.17 sec: 1.37x faster                                             |
| pycparser                | 1.66 sec                                                     | 1.23 sec: 1.36x faster                                             |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 702 ms: 1.36x faster                                               |
| regex_compile            | 194 ms                                                       | 146 ms: 1.33x faster                                               |
| coroutines               | 30.4 ms                                                      | 23.3 ms: 1.30x faster                                              |
| logging_simple           | 8.90 us                                                      | 6.84 us: 1.30x faster                                              |
| deepcopy_memo            | 48.9 us                                                      | 37.7 us: 1.30x faster                                              |
| pprint_pformat           | 2.15 sec                                                     | 1.67 sec: 1.29x faster                                             |
| logging_format           | 9.57 us                                                      | 7.40 us: 1.29x faster                                              |
| xml_etree_process        | 76.0 ms                                                      | 58.9 ms: 1.29x faster                                              |
| pprint_safe_repr         | 1.05 sec                                                     | 820 ms: 1.28x faster                                               |
| tornado_http             | 152 ms                                                       | 120 ms: 1.27x faster                                               |
| mypy2                    | 466 ms                                                       | 368 ms: 1.27x faster                                               |
| scimark_fft              | 359 ms                                                       | 288 ms: 1.25x faster                                               |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 4.21 ms: 1.23x faster                                              |
| comprehensions           | 26.9 us                                                      | 21.8 us: 1.23x faster                                              |
| dulwich_log              | 80.1 ms                                                      | 64.9 ms: 1.23x faster                                              |
| nqueens                  | 112 ms                                                       | 91.3 ms: 1.23x faster                                              |
| json_loads               | 30.0 us                                                      | 24.4 us: 1.23x faster                                              |
| 2to3                     | 350 ms                                                       | 287 ms: 1.22x faster                                               |
| mdp                      | 3.03 sec                                                     | 2.52 sec: 1.20x faster                                             |
| sqlglot_normalize        | 144 ms                                                       | 120 ms: 1.20x faster                                               |
| sqlglot_optimize         | 70.3 ms                                                      | 58.6 ms: 1.20x faster                                              |
| deepcopy                 | 454 us                                                       | 382 us: 1.19x faster                                               |
| docutils                 | 3.40 sec                                                     | 2.90 sec: 1.17x faster                                             |
| deepcopy_reduce          | 4.03 us                                                      | 3.45 us: 1.17x faster                                              |
| bench_thread_pool        | 1.14 ms                                                      | 975 us: 1.17x faster                                               |
| json                     | 5.96 ms                                                      | 5.12 ms: 1.16x faster                                              |
| pathlib                  | 21.7 ms                                                      | 19.1 ms: 1.13x faster                                              |
| regex_v8                 | 26.6 ms                                                      | 23.8 ms: 1.12x faster                                              |
| unpack_sequence          | 59.5 ns                                                      | 53.7 ns: 1.11x faster                                              |
| xml_etree_parse          | 162 ms                                                       | 146 ms: 1.11x faster                                               |
| async_generators         | 422 ms                                                       | 381 ms: 1.11x faster                                               |
| xml_etree_generate       | 94.6 ms                                                      | 85.8 ms: 1.10x faster                                              |
| create_gc_cycles         | 1.82 ms                                                      | 1.66 ms: 1.09x faster                                              |
| sqlite_synth             | 2.97 us                                                      | 2.72 us: 1.09x faster                                              |
| regex_dna                | 259 ms                                                       | 238 ms: 1.09x faster                                               |
| meteor_contest           | 137 ms                                                       | 126 ms: 1.09x faster                                               |
| xml_etree_iterparse      | 110 ms                                                       | 103 ms: 1.07x faster                                               |
| pidigits                 | 271 ms                                                       | 264 ms: 1.03x faster                                               |
| telco                    | 7.14 ms                                                      | 6.99 ms: 1.02x faster                                              |
| python_startup           | 11.5 ms                                                      | 11.7 ms: 1.02x slower                                              |
| gc_traversal             | 3.45 ms                                                      | 3.54 ms: 1.03x slower                                              |
| unpickle                 | 14.2 us                                                      | 14.7 us: 1.04x slower                                              |
| pickle                   | 9.94 us                                                      | 10.4 us: 1.05x slower                                              |
| unpickle_list            | 4.49 us                                                      | 4.75 us: 1.06x slower                                              |
| pickle_dict              | 30.0 us                                                      | 32.4 us: 1.08x slower                                              |
| pickle_list              | 4.11 us                                                      | 4.46 us: 1.09x slower                                              |
| regex_effbot             | 2.99 ms                                                      | 3.52 ms: 1.18x slower                                              |
| python_startup_no_site   | 7.32 ms                                                      | 8.67 ms: 1.18x slower                                              |
| dask                     | 463 ms                                                       | 566 ms: 1.22x slower                                               |
| coverage                 | 64.0 ms                                                      | 88.0 ms: 1.38x slower                                              |
| Geometric mean           | (ref)                                                        | 1.30x faster                                                       |
Ignored benchmarks (16) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.27x
- 95% likely to have a speedup of 1.25x
- 99% likely to have a speedup of 1.23x
