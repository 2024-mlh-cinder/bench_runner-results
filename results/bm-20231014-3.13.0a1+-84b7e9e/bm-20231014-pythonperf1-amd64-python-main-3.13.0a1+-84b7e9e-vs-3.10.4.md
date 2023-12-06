
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.13x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| docutils       | 1.89 sec                                                    | 1.65 sec: 1.14x faster                                      |
| tornado_http   | 109 ms                                                      | 90.8 ms: 1.20x faster                                       |
| Geometric mean | (ref)                                                       | 1.17x faster                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| float          | 60.2 ms                                                     | 58.9 ms: 1.02x faster                                       |
| pidigits       | 145 ms                                                      | 147 ms: 1.01x slower                                        |
| nbody          | 69.3 ms                                                     | 83.4 ms: 1.20x slower                                       |
| Geometric mean | (ref)                                                       | 1.06x slower                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| regex_dna      | 132 ms                                                      | 119 ms: 1.11x faster                                        |
| regex_compile  | 103 ms                                                      | 93.4 ms: 1.11x faster                                       |
| regex_effbot   | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                       |
| regex_v8       | 15.0 ms                                                     | 15.0 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                       | 1.07x faster                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| json_dumps           | 8.50 ms                                                     | 5.69 ms: 1.49x faster                                       |
| pickle_pure_python   | 257 us                                                      | 199 us: 1.29x faster                                        |
| unpickle_pure_python | 171 us                                                      | 144 us: 1.19x faster                                        |
| unpickle             | 9.17 us                                                     | 8.13 us: 1.13x faster                                       |
| xml_etree_parse      | 102 ms                                                      | 92.3 ms: 1.10x faster                                       |
| xml_etree_process    | 43.4 ms                                                     | 40.1 ms: 1.08x faster                                       |
| json_loads           | 14.2 us                                                     | 13.6 us: 1.04x faster                                       |
| tomli_loads          | 1.62 sec                                                    | 1.57 sec: 1.04x faster                                      |
| unpickle_list        | 2.81 us                                                     | 2.73 us: 1.03x faster                                       |
| xml_etree_iterparse  | 63.5 ms                                                     | 65.2 ms: 1.03x slower                                       |
| pickle               | 6.80 us                                                     | 7.00 us: 1.03x slower                                       |
| xml_etree_generate   | 54.5 ms                                                     | 57.2 ms: 1.05x slower                                       |
| pickle_dict          | 16.9 us                                                     | 18.1 us: 1.07x slower                                       |
| pickle_list          | 2.59 us                                                     | 2.81 us: 1.09x slower                                       |
| Geometric mean       | (ref)                                                       | 1.07x faster                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| python_startup         | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                       |
| python_startup_no_site | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                       |
| Geometric mean         | (ref)                                                       | 1.01x slower                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|-----------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| mako      | 8.80 ms                                                     | 7.70 ms: 1.14x faster                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-pythonperf1-amd64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:-----------------------------------------------------------:|:-----------------------------------------------------------:|
| typing_runtime_protocols | 325 us                                                      | 96.2 us: 3.37x faster                                       |
| deltablue                | 4.17 ms                                                     | 2.40 ms: 1.74x faster                                       |
| mypy2                    | 352 ms                                                      | 220 ms: 1.60x faster                                        |
| richards_super           | 51.7 ms                                                     | 34.1 ms: 1.52x faster                                       |
| json_dumps               | 8.50 ms                                                     | 5.69 ms: 1.49x faster                                       |
| async_tree_none          | 420 ms                                                      | 282 ms: 1.49x faster                                        |
| asyncio_tcp              | 712 ms                                                      | 481 ms: 1.48x faster                                        |
| raytrace                 | 271 ms                                                      | 192 ms: 1.41x faster                                        |
| scimark_lu               | 85.4 ms                                                     | 60.6 ms: 1.41x faster                                       |
| async_tree_io            | 1.07 sec                                                    | 756 ms: 1.41x faster                                        |
| go                       | 136 ms                                                      | 98.4 ms: 1.38x faster                                       |
| async_tree_memoization   | 497 ms                                                      | 360 ms: 1.38x faster                                        |
| logging_silent           | 96.4 ns                                                     | 70.1 ns: 1.38x faster                                       |
| sqlglot_parse            | 1.22 ms                                                     | 888 us: 1.37x faster                                        |
| crypto_pyaes             | 62.3 ms                                                     | 45.7 ms: 1.36x faster                                       |
| richards                 | 41.2 ms                                                     | 30.4 ms: 1.36x faster                                       |
| sqlglot_transpile        | 1.46 ms                                                     | 1.12 ms: 1.31x faster                                       |
| chaos                    | 58.9 ms                                                     | 45.1 ms: 1.31x faster                                       |
| async_tree_cpu_io_mixed  | 609 ms                                                      | 472 ms: 1.29x faster                                        |
| pickle_pure_python       | 257 us                                                      | 199 us: 1.29x faster                                        |
| scimark_monte_carlo      | 55.9 ms                                                     | 43.5 ms: 1.28x faster                                       |
| scimark_sor              | 105 ms                                                      | 82.9 ms: 1.27x faster                                       |
| pyflate                  | 387 ms                                                      | 316 ms: 1.23x faster                                        |
| hexiom                   | 5.52 ms                                                     | 4.53 ms: 1.22x faster                                       |
| generators               | 31.6 ms                                                     | 26.1 ms: 1.21x faster                                       |
| tornado_http             | 109 ms                                                      | 90.8 ms: 1.20x faster                                       |
| spectral_norm            | 78.0 ms                                                     | 65.4 ms: 1.19x faster                                       |
| unpickle_pure_python     | 171 us                                                      | 144 us: 1.19x faster                                        |
| asyncio_tcp_ssl          | 2.03 sec                                                    | 1.75 sec: 1.16x faster                                      |
| docutils                 | 1.89 sec                                                    | 1.65 sec: 1.14x faster                                      |
| mako                     | 8.80 ms                                                     | 7.70 ms: 1.14x faster                                       |
| unpickle                 | 9.17 us                                                     | 8.13 us: 1.13x faster                                       |
| mdp                      | 1.71 sec                                                    | 1.53 sec: 1.12x faster                                      |
| regex_dna                | 132 ms                                                      | 119 ms: 1.11x faster                                        |
| regex_compile            | 103 ms                                                      | 93.4 ms: 1.11x faster                                       |
| xml_etree_parse          | 102 ms                                                      | 92.3 ms: 1.10x faster                                       |
| bench_thread_pool        | 946 us                                                      | 861 us: 1.10x faster                                        |
| sqlite_synth             | 1.84 us                                                     | 1.67 us: 1.10x faster                                       |
| pprint_safe_repr         | 589 ms                                                      | 536 ms: 1.10x faster                                        |
| pprint_pformat           | 1.21 sec                                                    | 1.10 sec: 1.10x faster                                      |
| deepcopy_memo            | 28.5 us                                                     | 26.3 us: 1.09x faster                                       |
| xml_etree_process        | 43.4 ms                                                     | 40.1 ms: 1.08x faster                                       |
| pycparser                | 868 ms                                                      | 805 ms: 1.08x faster                                        |
| create_gc_cycles         | 782 us                                                      | 726 us: 1.08x faster                                        |
| json                     | 3.05 ms                                                     | 2.86 ms: 1.07x faster                                       |
| sqlglot_optimize         | 39.0 ms                                                     | 36.8 ms: 1.06x faster                                       |
| regex_effbot             | 1.66 ms                                                     | 1.59 ms: 1.05x faster                                       |
| json_loads               | 14.2 us                                                     | 13.6 us: 1.04x faster                                       |
| sqlglot_normalize        | 202 ms                                                      | 195 ms: 1.04x faster                                        |
| tomli_loads              | 1.62 sec                                                    | 1.57 sec: 1.04x faster                                      |
| coroutines               | 15.9 ms                                                     | 15.4 ms: 1.03x faster                                       |
| comprehensions           | 16.0 us                                                     | 15.4 us: 1.03x faster                                       |
| dulwich_log              | 47.6 ms                                                     | 46.0 ms: 1.03x faster                                       |
| nqueens                  | 67.0 ms                                                     | 64.9 ms: 1.03x faster                                       |
| python_startup           | 20.0 ms                                                     | 19.4 ms: 1.03x faster                                       |
| unpickle_list            | 2.81 us                                                     | 2.73 us: 1.03x faster                                       |
| deepcopy                 | 255 us                                                      | 249 us: 1.03x faster                                        |
| float                    | 60.2 ms                                                     | 58.9 ms: 1.02x faster                                       |
| scimark_sparse_mat_mult  | 2.66 ms                                                     | 2.62 ms: 1.01x faster                                       |
| scimark_fft              | 193 ms                                                      | 191 ms: 1.01x faster                                        |
| regex_v8                 | 15.0 ms                                                     | 15.0 ms: 1.01x faster                                       |
| pidigits                 | 145 ms                                                      | 147 ms: 1.01x slower                                        |
| deepcopy_reduce          | 2.16 us                                                     | 2.20 us: 1.02x slower                                       |
| pathlib                  | 77.4 ms                                                     | 79.1 ms: 1.02x slower                                       |
| xml_etree_iterparse      | 63.5 ms                                                     | 65.2 ms: 1.03x slower                                       |
| pickle                   | 6.80 us                                                     | 7.00 us: 1.03x slower                                       |
| meteor_contest           | 72.5 ms                                                     | 75.4 ms: 1.04x slower                                       |
| fannkuch                 | 258 ms                                                      | 269 ms: 1.04x slower                                        |
| python_startup_no_site   | 15.5 ms                                                     | 16.3 ms: 1.05x slower                                       |
| xml_etree_generate       | 54.5 ms                                                     | 57.2 ms: 1.05x slower                                       |
| bench_mp_pool            | 60.7 ms                                                     | 63.8 ms: 1.05x slower                                       |
| unpack_sequence          | 37.8 ns                                                     | 39.8 ns: 1.05x slower                                       |
| pickle_dict              | 16.9 us                                                     | 18.1 us: 1.07x slower                                       |
| pickle_list              | 2.59 us                                                     | 2.81 us: 1.09x slower                                       |
| async_generators         | 224 ms                                                      | 245 ms: 1.09x slower                                        |
| gc_traversal             | 1.34 ms                                                     | 1.48 ms: 1.10x slower                                       |
| logging_simple           | 6.20 us                                                     | 6.91 us: 1.11x slower                                       |
| logging_format           | 6.66 us                                                     | 7.45 us: 1.12x slower                                       |
| coverage                 | 40.0 ms                                                     | 45.7 ms: 1.14x slower                                       |
| nbody                    | 69.3 ms                                                     | 83.4 ms: 1.20x slower                                       |
| telco                    | 3.78 ms                                                     | 4.77 ms: 1.26x slower                                       |
| Geometric mean           | (ref)                                                       | 1.13x faster                                                |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.06x
