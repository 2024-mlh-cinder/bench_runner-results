
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: linux-x86_64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.97 sec: 1.15x faster                                              |
| tornado_http   | 152 ms                                                       | 123 ms: 1.24x faster                                                |
| Geometric mean | (ref)                                                        | 1.19x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 96.0 ms: 1.43x faster                                               |
| float          | 110 ms                                                       | 83.2 ms: 1.33x faster                                               |
| pidigits       | 271 ms                                                       | 265 ms: 1.02x faster                                                |
| Geometric mean | (ref)                                                        | 1.25x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 157 ms: 1.23x faster                                                |
| regex_dna      | 259 ms                                                       | 241 ms: 1.08x faster                                                |
| regex_v8       | 26.6 ms                                                      | 25.9 ms: 1.03x faster                                               |
| regex_effbot   | 2.99 ms                                                      | 3.64 ms: 1.22x slower                                               |
| Geometric mean | (ref)                                                        | 1.03x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 319 us: 1.43x faster                                                |
| json_dumps           | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                               |
| unpickle_pure_python | 321 us                                                       | 246 us: 1.30x faster                                                |
| xml_etree_process    | 76.0 ms                                                      | 59.4 ms: 1.28x faster                                               |
| tomli_loads          | 2.97 sec                                                     | 2.42 sec: 1.23x faster                                              |
| json_loads           | 30.0 us                                                      | 25.4 us: 1.18x faster                                               |
| xml_etree_parse      | 162 ms                                                       | 147 ms: 1.10x faster                                                |
| xml_etree_generate   | 94.6 ms                                                      | 87.0 ms: 1.09x faster                                               |
| xml_etree_iterparse  | 110 ms                                                       | 108 ms: 1.02x faster                                                |
| unpickle_list        | 4.49 us                                                      | 4.57 us: 1.02x slower                                               |
| pickle               | 9.94 us                                                      | 10.2 us: 1.03x slower                                               |
| unpickle             | 14.2 us                                                      | 15.0 us: 1.06x slower                                               |
| pickle_list          | 4.11 us                                                      | 4.52 us: 1.10x slower                                               |
| pickle_dict          | 30.0 us                                                      | 33.7 us: 1.12x slower                                               |
| Geometric mean       | (ref)                                                        | 1.11x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 11.9 ms: 1.04x slower                                               |
| python_startup_no_site | 7.32 ms                                                      | 8.86 ms: 1.21x slower                                               |
| Geometric mean         | (ref)                                                        | 1.12x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230905-pythonperf2-x86_64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 160 us: 3.26x faster                                                |
| asyncio_tcp              | 782 ms                                                       | 372 ms: 2.10x faster                                                |
| deltablue                | 7.47 ms                                                      | 3.79 ms: 1.97x faster                                               |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.95x faster                                              |
| raytrace                 | 488 ms                                                       | 279 ms: 1.75x faster                                                |
| logging_silent           | 166 ns                                                       | 99.7 ns: 1.66x faster                                               |
| generators               | 58.0 ms                                                      | 36.6 ms: 1.59x faster                                               |
| chaos                    | 107 ms                                                       | 68.4 ms: 1.57x faster                                               |
| async_tree_none          | 700 ms                                                       | 449 ms: 1.56x faster                                                |
| sqlglot_parse            | 2.26 ms                                                      | 1.45 ms: 1.55x faster                                               |
| crypto_pyaes             | 118 ms                                                       | 76.9 ms: 1.54x faster                                               |
| scimark_lu               | 164 ms                                                       | 107 ms: 1.53x faster                                                |
| scimark_monte_carlo      | 109 ms                                                       | 71.7 ms: 1.53x faster                                               |
| bench_mp_pool            | 7.18 ms                                                      | 4.77 ms: 1.50x faster                                               |
| richards_super           | 90.8 ms                                                      | 61.7 ms: 1.47x faster                                               |
| async_tree_memoization   | 824 ms                                                       | 562 ms: 1.47x faster                                                |
| async_tree_io            | 1.61 sec                                                     | 1.10 sec: 1.46x faster                                              |
| sqlglot_transpile        | 2.71 ms                                                      | 1.87 ms: 1.45x faster                                               |
| pickle_pure_python       | 457 us                                                       | 319 us: 1.43x faster                                                |
| nbody                    | 137 ms                                                       | 96.0 ms: 1.43x faster                                               |
| spectral_norm            | 136 ms                                                       | 95.3 ms: 1.43x faster                                               |
| go                       | 259 ms                                                       | 182 ms: 1.42x faster                                                |
| pyflate                  | 697 ms                                                       | 511 ms: 1.36x faster                                                |
| json_dumps               | 14.2 ms                                                      | 10.4 ms: 1.36x faster                                               |
| mako                     | 14.7 ms                                                      | 10.9 ms: 1.35x faster                                               |
| coroutines               | 30.4 ms                                                      | 22.7 ms: 1.34x faster                                               |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 716 ms: 1.33x faster                                                |
| float                    | 110 ms                                                       | 83.2 ms: 1.33x faster                                               |
| richards                 | 74.1 ms                                                      | 56.0 ms: 1.32x faster                                               |
| unpickle_pure_python     | 321 us                                                       | 246 us: 1.30x faster                                                |
| logging_simple           | 8.90 us                                                      | 6.86 us: 1.30x faster                                               |
| logging_format           | 9.57 us                                                      | 7.43 us: 1.29x faster                                               |
| pprint_pformat           | 2.15 sec                                                     | 1.68 sec: 1.28x faster                                              |
| pycparser                | 1.66 sec                                                     | 1.30 sec: 1.28x faster                                              |
| xml_etree_process        | 76.0 ms                                                      | 59.4 ms: 1.28x faster                                               |
| pprint_safe_repr         | 1.05 sec                                                     | 824 ms: 1.27x faster                                                |
| hexiom                   | 9.52 ms                                                      | 7.51 ms: 1.27x faster                                               |
| tornado_http             | 152 ms                                                       | 123 ms: 1.24x faster                                                |
| regex_compile            | 194 ms                                                       | 157 ms: 1.23x faster                                                |
| tomli_loads              | 2.97 sec                                                     | 2.42 sec: 1.23x faster                                              |
| deepcopy_memo            | 48.9 us                                                      | 40.0 us: 1.22x faster                                               |
| mypy2                    | 466 ms                                                       | 386 ms: 1.21x faster                                                |
| scimark_sor              | 177 ms                                                       | 147 ms: 1.21x faster                                                |
| sqlglot_normalize        | 144 ms                                                       | 121 ms: 1.19x faster                                                |
| json_loads               | 30.0 us                                                      | 25.4 us: 1.18x faster                                               |
| unpack_sequence          | 59.5 ns                                                      | 51.1 ns: 1.17x faster                                               |
| deepcopy_reduce          | 4.03 us                                                      | 3.48 us: 1.16x faster                                               |
| dulwich_log              | 80.1 ms                                                      | 69.5 ms: 1.15x faster                                               |
| json                     | 5.96 ms                                                      | 5.19 ms: 1.15x faster                                               |
| docutils                 | 3.40 sec                                                     | 2.97 sec: 1.15x faster                                              |
| deepcopy                 | 454 us                                                       | 396 us: 1.15x faster                                                |
| sqlglot_optimize         | 70.3 ms                                                      | 61.5 ms: 1.14x faster                                               |
| create_gc_cycles         | 1.82 ms                                                      | 1.60 ms: 1.14x faster                                               |
| mdp                      | 3.03 sec                                                     | 2.67 sec: 1.14x faster                                              |
| fannkuch                 | 496 ms                                                       | 438 ms: 1.13x faster                                                |
| bench_thread_pool        | 1.14 ms                                                      | 1.02 ms: 1.12x faster                                               |
| xml_etree_parse          | 162 ms                                                       | 147 ms: 1.10x faster                                                |
| xml_etree_generate       | 94.6 ms                                                      | 87.0 ms: 1.09x faster                                               |
| pathlib                  | 21.7 ms                                                      | 20.0 ms: 1.09x faster                                               |
| nqueens                  | 112 ms                                                       | 104 ms: 1.08x faster                                                |
| scimark_fft              | 359 ms                                                       | 333 ms: 1.08x faster                                                |
| regex_dna                | 259 ms                                                       | 241 ms: 1.08x faster                                                |
| sqlite_synth             | 2.97 us                                                      | 2.77 us: 1.07x faster                                               |
| regex_v8                 | 26.6 ms                                                      | 25.9 ms: 1.03x faster                                               |
| comprehensions           | 26.9 us                                                      | 26.2 us: 1.03x faster                                               |
| xml_etree_iterparse      | 110 ms                                                       | 108 ms: 1.02x faster                                                |
| pidigits                 | 271 ms                                                       | 265 ms: 1.02x faster                                                |
| async_generators         | 422 ms                                                       | 416 ms: 1.01x faster                                                |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 5.23 ms: 1.01x slower                                               |
| unpickle_list            | 4.49 us                                                      | 4.57 us: 1.02x slower                                               |
| meteor_contest           | 137 ms                                                       | 140 ms: 1.02x slower                                                |
| pickle                   | 9.94 us                                                      | 10.2 us: 1.03x slower                                               |
| python_startup           | 11.5 ms                                                      | 11.9 ms: 1.04x slower                                               |
| unpickle                 | 14.2 us                                                      | 15.0 us: 1.06x slower                                               |
| pickle_list              | 4.11 us                                                      | 4.52 us: 1.10x slower                                               |
| pickle_dict              | 30.0 us                                                      | 33.7 us: 1.12x slower                                               |
| telco                    | 7.14 ms                                                      | 8.29 ms: 1.16x slower                                               |
| gc_traversal             | 3.45 ms                                                      | 4.16 ms: 1.20x slower                                               |
| python_startup_no_site   | 7.32 ms                                                      | 8.86 ms: 1.21x slower                                               |
| regex_effbot             | 2.99 ms                                                      | 3.64 ms: 1.22x slower                                               |
| dask                     | 463 ms                                                       | 596 ms: 1.29x slower                                                |
| coverage                 | 64.0 ms                                                      | 83.0 ms: 1.30x slower                                               |
| Geometric mean           | (ref)                                                        | 1.23x faster                                                        |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.15x
