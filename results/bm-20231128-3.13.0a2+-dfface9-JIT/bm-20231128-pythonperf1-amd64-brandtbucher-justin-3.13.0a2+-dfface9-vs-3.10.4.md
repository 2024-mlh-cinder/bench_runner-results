
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.13x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 233 ms: 1.02x faster                                                |
| chameleon      | 6.02 ms                                                     | 5.29 ms: 1.14x faster                                               |
| docutils       | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                              |
| tornado_http   | 106 ms                                                      | 93.3 ms: 1.13x faster                                               |
| Geometric mean | (ref)                                                       | 1.11x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 286 ms: 1.49x faster                                                |
| async_tree_memoization  | 505 ms                                                      | 359 ms: 1.41x faster                                                |
| async_tree_io           | 1.07 sec                                                    | 775 ms: 1.38x faster                                                |
| async_tree_cpu_io_mixed | 617 ms                                                      | 482 ms: 1.28x faster                                                |
| Geometric mean          | (ref)                                                       | 1.39x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 50.0 ms: 1.24x faster                                               |
| nbody          | 71.0 ms                                                     | 60.1 ms: 1.18x faster                                               |
| pidigits       | 146 ms                                                      | 150 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                       | 1.12x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 87.7 ms: 1.17x faster                                               |
| regex_dna      | 129 ms                                                      | 124 ms: 1.04x faster                                                |
| regex_effbot   | 1.56 ms                                                     | 1.79 ms: 1.14x slower                                               |
| regex_v8       | 15.0 ms                                                     | 21.3 ms: 1.42x slower                                               |
| Geometric mean | (ref)                                                       | 1.08x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 6.13 ms: 1.43x faster                                               |
| pickle_pure_python   | 259 us                                                      | 193 us: 1.34x faster                                                |
| unpickle_pure_python | 177 us                                                      | 147 us: 1.21x faster                                                |
| tomli_loads          | 1.65 sec                                                    | 1.38 sec: 1.19x faster                                              |
| unpickle             | 9.11 us                                                     | 8.23 us: 1.11x faster                                               |
| xml_etree_process    | 43.1 ms                                                     | 39.7 ms: 1.09x faster                                               |
| xml_etree_parse      | 96.8 ms                                                     | 96.0 ms: 1.01x faster                                               |
| json_loads           | 14.2 us                                                     | 14.5 us: 1.02x slower                                               |
| pickle               | 6.87 us                                                     | 7.11 us: 1.03x slower                                               |
| xml_etree_generate   | 54.5 ms                                                     | 58.0 ms: 1.06x slower                                               |
| pickle_dict          | 17.1 us                                                     | 19.0 us: 1.11x slower                                               |
| pickle_list          | 2.69 us                                                     | 3.26 us: 1.21x slower                                               |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                        |

Benchmark hidden because not significant (2): unpickle_list, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.8 ms: 1.06x slower                                               |
| python_startup_no_site | 15.3 ms                                                     | 18.9 ms: 1.23x slower                                               |
| Geometric mean         | (ref)                                                       | 1.14x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.37 ms: 1.41x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9 |
|--------------------------|:-----------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 82.7 us: 4.07x faster                                               |
| deltablue                | 4.12 ms                                                     | 2.09 ms: 1.97x faster                                               |
| richards_super           | 50.3 ms                                                     | 32.1 ms: 1.57x faster                                               |
| raytrace                 | 266 ms                                                      | 177 ms: 1.50x faster                                                |
| async_tree_none          | 424 ms                                                      | 286 ms: 1.49x faster                                                |
| logging_silent           | 93.4 ns                                                     | 64.0 ns: 1.46x faster                                               |
| asyncio_tcp              | 717 ms                                                      | 496 ms: 1.44x faster                                                |
| json_dumps               | 8.77 ms                                                     | 6.13 ms: 1.43x faster                                               |
| richards                 | 40.6 ms                                                     | 28.5 ms: 1.43x faster                                               |
| go                       | 135 ms                                                      | 95.8 ms: 1.41x faster                                               |
| mako                     | 8.98 ms                                                     | 6.37 ms: 1.41x faster                                               |
| async_tree_memoization   | 505 ms                                                      | 359 ms: 1.41x faster                                                |
| comprehensions           | 16.6 us                                                     | 11.8 us: 1.40x faster                                               |
| sqlglot_parse            | 1.20 ms                                                     | 862 us: 1.40x faster                                                |
| scimark_lu               | 84.0 ms                                                     | 60.3 ms: 1.39x faster                                               |
| async_tree_io            | 1.07 sec                                                    | 775 ms: 1.38x faster                                                |
| chaos                    | 59.5 ms                                                     | 43.7 ms: 1.36x faster                                               |
| crypto_pyaes             | 63.1 ms                                                     | 46.8 ms: 1.35x faster                                               |
| pickle_pure_python       | 259 us                                                      | 193 us: 1.34x faster                                                |
| pyflate                  | 402 ms                                                      | 305 ms: 1.32x faster                                                |
| sqlglot_transpile        | 1.45 ms                                                     | 1.10 ms: 1.31x faster                                               |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 482 ms: 1.28x faster                                                |
| hexiom                   | 5.59 ms                                                     | 4.38 ms: 1.28x faster                                               |
| scimark_sor              | 105 ms                                                      | 83.9 ms: 1.25x faster                                               |
| generators               | 31.8 ms                                                     | 25.7 ms: 1.24x faster                                               |
| float                    | 61.7 ms                                                     | 50.0 ms: 1.24x faster                                               |
| deepcopy_memo            | 29.0 us                                                     | 23.8 us: 1.22x faster                                               |
| scimark_monte_carlo      | 58.0 ms                                                     | 47.7 ms: 1.22x faster                                               |
| pycparser                | 905 ms                                                      | 747 ms: 1.21x faster                                                |
| mdp                      | 1.71 sec                                                    | 1.41 sec: 1.21x faster                                              |
| unpickle_pure_python     | 177 us                                                      | 147 us: 1.21x faster                                                |
| sympy_sum                | 105 ms                                                      | 87.8 ms: 1.20x faster                                               |
| spectral_norm            | 78.9 ms                                                     | 65.9 ms: 1.20x faster                                               |
| tomli_loads              | 1.65 sec                                                    | 1.38 sec: 1.19x faster                                              |
| sqlite_synth             | 1.90 us                                                     | 1.60 us: 1.19x faster                                               |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.77 sec: 1.18x faster                                              |
| nbody                    | 71.0 ms                                                     | 60.1 ms: 1.18x faster                                               |
| regex_compile            | 102 ms                                                      | 87.7 ms: 1.17x faster                                               |
| chameleon                | 6.02 ms                                                     | 5.29 ms: 1.14x faster                                               |
| tornado_http             | 106 ms                                                      | 93.3 ms: 1.13x faster                                               |
| docutils                 | 1.88 sec                                                    | 1.66 sec: 1.13x faster                                              |
| sympy_str                | 193 ms                                                      | 172 ms: 1.12x faster                                                |
| sympy_expand             | 320 ms                                                      | 289 ms: 1.11x faster                                                |
| unpickle                 | 9.11 us                                                     | 8.23 us: 1.11x faster                                               |
| dask                     | 305 ms                                                      | 276 ms: 1.10x faster                                                |
| pprint_pformat           | 1.22 sec                                                    | 1.11 sec: 1.10x faster                                              |
| sympy_integrate          | 15.0 ms                                                     | 13.7 ms: 1.09x faster                                               |
| xml_etree_process        | 43.1 ms                                                     | 39.7 ms: 1.09x faster                                               |
| pprint_safe_repr         | 594 ms                                                      | 548 ms: 1.08x faster                                                |
| dulwich_log              | 48.6 ms                                                     | 45.1 ms: 1.08x faster                                               |
| sqlglot_optimize         | 39.4 ms                                                     | 36.7 ms: 1.07x faster                                               |
| create_gc_cycles         | 800 us                                                      | 752 us: 1.06x faster                                                |
| deepcopy                 | 259 us                                                      | 247 us: 1.05x faster                                                |
| unpack_sequence          | 40.0 ns                                                     | 38.3 ns: 1.04x faster                                               |
| coroutines               | 15.5 ms                                                     | 14.8 ms: 1.04x faster                                               |
| sqlglot_normalize        | 207 ms                                                      | 198 ms: 1.04x faster                                                |
| regex_dna                | 129 ms                                                      | 124 ms: 1.04x faster                                                |
| bench_thread_pool        | 913 us                                                      | 882 us: 1.03x faster                                                |
| nqueens                  | 68.3 ms                                                     | 66.0 ms: 1.03x faster                                               |
| 2to3                     | 239 ms                                                      | 233 ms: 1.02x faster                                                |
| deepcopy_reduce          | 2.22 us                                                     | 2.19 us: 1.01x faster                                               |
| xml_etree_parse          | 96.8 ms                                                     | 96.0 ms: 1.01x faster                                               |
| fannkuch                 | 258 ms                                                      | 256 ms: 1.01x faster                                                |
| logging_format           | 6.73 us                                                     | 6.82 us: 1.01x slower                                               |
| json_loads               | 14.2 us                                                     | 14.5 us: 1.02x slower                                               |
| scimark_fft              | 187 ms                                                      | 192 ms: 1.02x slower                                                |
| pidigits                 | 146 ms                                                      | 150 ms: 1.03x slower                                                |
| logging_simple           | 6.28 us                                                     | 6.48 us: 1.03x slower                                               |
| pickle                   | 6.87 us                                                     | 7.11 us: 1.03x slower                                               |
| meteor_contest           | 73.8 ms                                                     | 76.9 ms: 1.04x slower                                               |
| python_startup           | 19.7 ms                                                     | 20.8 ms: 1.06x slower                                               |
| xml_etree_generate       | 54.5 ms                                                     | 58.0 ms: 1.06x slower                                               |
| gc_traversal             | 1.40 ms                                                     | 1.53 ms: 1.09x slower                                               |
| pickle_dict              | 17.1 us                                                     | 19.0 us: 1.11x slower                                               |
| bench_mp_pool            | 59.9 ms                                                     | 67.4 ms: 1.12x slower                                               |
| pathlib                  | 72.8 ms                                                     | 82.0 ms: 1.13x slower                                               |
| regex_effbot             | 1.56 ms                                                     | 1.79 ms: 1.14x slower                                               |
| async_generators         | 219 ms                                                      | 255 ms: 1.17x slower                                                |
| pickle_list              | 2.69 us                                                     | 3.26 us: 1.21x slower                                               |
| coverage                 | 38.4 ms                                                     | 47.0 ms: 1.22x slower                                               |
| python_startup_no_site   | 15.3 ms                                                     | 18.9 ms: 1.23x slower                                               |
| telco                    | 3.82 ms                                                     | 4.78 ms: 1.25x slower                                               |
| mypy2                    | 347 ms                                                      | 450 ms: 1.30x slower                                                |
| regex_v8                 | 15.0 ms                                                     | 21.3 ms: 1.42x slower                                               |
| Geometric mean           | (ref)                                                       | 1.13x faster                                                        |

Benchmark hidden because not significant (4): scimark_sparse_mat_mult, unpickle_list, xml_etree_iterparse, json
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231128-3.13.0a2+-dfface9-JIT/bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2+-dfface9.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.07x
