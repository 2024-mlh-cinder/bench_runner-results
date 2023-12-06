
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_pic
- machine: linux-x86_64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.18x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.93 sec: 1.16x faster                                                     |
| tornado_http   | 152 ms                                                       | 121 ms: 1.25x faster                                                       |
| Geometric mean | (ref)                                                        | 1.21x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 92.0 ms: 1.49x faster                                                      |
| float          | 110 ms                                                       | 82.0 ms: 1.35x faster                                                      |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                        | 1.27x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 154 ms: 1.26x faster                                                       |
| regex_dna      | 259 ms                                                       | 244 ms: 1.06x faster                                                       |
| regex_v8       | 26.6 ms                                                      | 25.2 ms: 1.06x faster                                                      |
| regex_effbot   | 2.99 ms                                                      | 3.58 ms: 1.19x slower                                                      |
| Geometric mean | (ref)                                                        | 1.04x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 316 us: 1.45x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                                      |
| unpickle_pure_python | 321 us                                                       | 241 us: 1.33x faster                                                       |
| tomli_loads          | 2.97 sec                                                     | 2.29 sec: 1.30x faster                                                     |
| xml_etree_process    | 76.0 ms                                                      | 59.5 ms: 1.28x faster                                                      |
| json_loads           | 30.0 us                                                      | 24.6 us: 1.22x faster                                                      |
| xml_etree_generate   | 94.6 ms                                                      | 86.0 ms: 1.10x faster                                                      |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 106 ms: 1.04x faster                                                       |
| unpickle             | 14.2 us                                                      | 14.4 us: 1.02x slower                                                      |
| pickle               | 9.94 us                                                      | 10.2 us: 1.02x slower                                                      |
| unpickle_list        | 4.49 us                                                      | 4.77 us: 1.06x slower                                                      |
| pickle_dict          | 30.0 us                                                      | 32.7 us: 1.09x slower                                                      |
| pickle_list          | 4.11 us                                                      | 4.49 us: 1.09x slower                                                      |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.9 ms: 1.03x slower                                                      |
| python_startup_no_site | 7.32 ms                                                      | 8.86 ms: 1.21x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.12x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.5 ms: 1.39x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 153 us: 3.41x faster                                                       |
| asyncio_tcp              | 782 ms                                                       | 374 ms: 2.09x faster                                                       |
| deltablue                | 7.47 ms                                                      | 3.75 ms: 1.99x faster                                                      |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                                     |
| raytrace                 | 488 ms                                                       | 276 ms: 1.77x faster                                                       |
| logging_silent           | 166 ns                                                       | 98.1 ns: 1.69x faster                                                      |
| chaos                    | 107 ms                                                       | 65.3 ms: 1.64x faster                                                      |
| scimark_monte_carlo      | 109 ms                                                       | 68.3 ms: 1.60x faster                                                      |
| crypto_pyaes             | 118 ms                                                       | 74.0 ms: 1.60x faster                                                      |
| async_tree_none          | 700 ms                                                       | 438 ms: 1.60x faster                                                       |
| generators               | 58.0 ms                                                      | 36.6 ms: 1.58x faster                                                      |
| scimark_lu               | 164 ms                                                       | 104 ms: 1.57x faster                                                       |
| sqlglot_parse            | 2.26 ms                                                      | 1.46 ms: 1.55x faster                                                      |
| async_tree_memoization   | 824 ms                                                       | 552 ms: 1.49x faster                                                       |
| nbody                    | 137 ms                                                       | 92.0 ms: 1.49x faster                                                      |
| richards_super           | 90.8 ms                                                      | 60.9 ms: 1.49x faster                                                      |
| go                       | 259 ms                                                       | 175 ms: 1.48x faster                                                       |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.48x faster                                                     |
| sqlglot_transpile        | 2.71 ms                                                      | 1.87 ms: 1.45x faster                                                      |
| pickle_pure_python       | 457 us                                                       | 316 us: 1.45x faster                                                       |
| spectral_norm            | 136 ms                                                       | 94.8 ms: 1.44x faster                                                      |
| bench_mp_pool            | 7.18 ms                                                      | 5.02 ms: 1.43x faster                                                      |
| pyflate                  | 697 ms                                                       | 495 ms: 1.41x faster                                                       |
| mako                     | 14.7 ms                                                      | 10.5 ms: 1.39x faster                                                      |
| richards                 | 74.1 ms                                                      | 53.4 ms: 1.39x faster                                                      |
| json_dumps               | 14.2 ms                                                      | 10.3 ms: 1.38x faster                                                      |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 702 ms: 1.36x faster                                                       |
| hexiom                   | 9.52 ms                                                      | 7.03 ms: 1.35x faster                                                      |
| coroutines               | 30.4 ms                                                      | 22.6 ms: 1.35x faster                                                      |
| float                    | 110 ms                                                       | 82.0 ms: 1.35x faster                                                      |
| unpickle_pure_python     | 321 us                                                       | 241 us: 1.33x faster                                                       |
| logging_simple           | 8.90 us                                                      | 6.73 us: 1.32x faster                                                      |
| pprint_pformat           | 2.15 sec                                                     | 1.64 sec: 1.31x faster                                                     |
| pprint_safe_repr         | 1.05 sec                                                     | 804 ms: 1.30x faster                                                       |
| logging_format           | 9.57 us                                                      | 7.34 us: 1.30x faster                                                      |
| tomli_loads              | 2.97 sec                                                     | 2.29 sec: 1.30x faster                                                     |
| xml_etree_process        | 76.0 ms                                                      | 59.5 ms: 1.28x faster                                                      |
| deepcopy_memo            | 48.9 us                                                      | 38.7 us: 1.26x faster                                                      |
| regex_compile            | 194 ms                                                       | 154 ms: 1.26x faster                                                       |
| tornado_http             | 152 ms                                                       | 121 ms: 1.25x faster                                                       |
| pycparser                | 1.66 sec                                                     | 1.34 sec: 1.25x faster                                                     |
| mypy2                    | 466 ms                                                       | 380 ms: 1.23x faster                                                       |
| json_loads               | 30.0 us                                                      | 24.6 us: 1.22x faster                                                      |
| fannkuch                 | 496 ms                                                       | 410 ms: 1.21x faster                                                       |
| sqlglot_normalize        | 144 ms                                                       | 120 ms: 1.20x faster                                                       |
| scimark_sor              | 177 ms                                                       | 148 ms: 1.20x faster                                                       |
| deepcopy_reduce          | 4.03 us                                                      | 3.36 us: 1.20x faster                                                      |
| deepcopy                 | 454 us                                                       | 384 us: 1.18x faster                                                       |
| json                     | 5.96 ms                                                      | 5.07 ms: 1.18x faster                                                      |
| unpack_sequence          | 59.5 ns                                                      | 50.6 ns: 1.18x faster                                                      |
| docutils                 | 3.40 sec                                                     | 2.93 sec: 1.16x faster                                                     |
| create_gc_cycles         | 1.82 ms                                                      | 1.57 ms: 1.16x faster                                                      |
| sqlglot_optimize         | 70.3 ms                                                      | 60.6 ms: 1.16x faster                                                      |
| mdp                      | 3.03 sec                                                     | 2.62 sec: 1.16x faster                                                     |
| dulwich_log              | 80.1 ms                                                      | 69.9 ms: 1.15x faster                                                      |
| nqueens                  | 112 ms                                                       | 98.5 ms: 1.14x faster                                                      |
| bench_thread_pool        | 1.14 ms                                                      | 998 us: 1.14x faster                                                       |
| xml_etree_generate       | 94.6 ms                                                      | 86.0 ms: 1.10x faster                                                      |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                                       |
| comprehensions           | 26.9 us                                                      | 24.7 us: 1.09x faster                                                      |
| scimark_fft              | 359 ms                                                       | 329 ms: 1.09x faster                                                       |
| pathlib                  | 21.7 ms                                                      | 20.0 ms: 1.09x faster                                                      |
| sqlite_synth             | 2.97 us                                                      | 2.74 us: 1.08x faster                                                      |
| regex_dna                | 259 ms                                                       | 244 ms: 1.06x faster                                                       |
| regex_v8                 | 26.6 ms                                                      | 25.2 ms: 1.06x faster                                                      |
| xml_etree_iterparse      | 110 ms                                                       | 106 ms: 1.04x faster                                                       |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                       |
| async_generators         | 422 ms                                                       | 416 ms: 1.01x faster                                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 5.15 ms: 1.01x faster                                                      |
| meteor_contest           | 137 ms                                                       | 137 ms: 1.00x slower                                                       |
| unpickle                 | 14.2 us                                                      | 14.4 us: 1.02x slower                                                      |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.02x slower                                                      |
| python_startup           | 11.5 ms                                                      | 11.9 ms: 1.03x slower                                                      |
| unpickle_list            | 4.49 us                                                      | 4.77 us: 1.06x slower                                                      |
| gc_traversal             | 3.45 ms                                                      | 3.68 ms: 1.07x slower                                                      |
| pickle_dict              | 30.0 us                                                      | 32.7 us: 1.09x slower                                                      |
| pickle_list              | 4.11 us                                                      | 4.49 us: 1.09x slower                                                      |
| telco                    | 7.14 ms                                                      | 8.19 ms: 1.15x slower                                                      |
| regex_effbot             | 2.99 ms                                                      | 3.58 ms: 1.19x slower                                                      |
| python_startup_no_site   | 7.32 ms                                                      | 8.86 ms: 1.21x slower                                                      |
| dask                     | 463 ms                                                       | 593 ms: 1.28x slower                                                       |
| coverage                 | 64.0 ms                                                      | 82.8 ms: 1.29x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.25x faster                                                               |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.20x
- 99% likely to have a speedup of 1.18x
