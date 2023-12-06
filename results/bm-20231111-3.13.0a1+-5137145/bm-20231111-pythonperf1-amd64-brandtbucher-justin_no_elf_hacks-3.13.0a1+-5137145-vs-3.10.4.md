
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: windows-amd64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 216 ms: 1.11x faster                                                             |
| chameleon      | 6.02 ms                                                     | 4.98 ms: 1.21x faster                                                            |
| docutils       | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                                           |
| tornado_http   | 106 ms                                                      | 89.0 ms: 1.19x faster                                                            |
| Geometric mean | (ref)                                                       | 1.18x faster                                                                     |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 271 ms: 1.56x faster                                                             |
| async_tree_io           | 1.07 sec                                                    | 725 ms: 1.48x faster                                                             |
| async_tree_memoization  | 505 ms                                                      | 346 ms: 1.46x faster                                                             |
| async_tree_cpu_io_mixed | 617 ms                                                      | 456 ms: 1.36x faster                                                             |
| Geometric mean          | (ref)                                                       | 1.46x faster                                                                     |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 51.5 ms: 1.20x faster                                                            |
| nbody          | 71.0 ms                                                     | 71.9 ms: 1.01x slower                                                            |
| pidigits       | 146 ms                                                      | 150 ms: 1.03x slower                                                             |
| Geometric mean | (ref)                                                       | 1.05x faster                                                                     |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 81.7 ms: 1.25x faster                                                            |
| regex_dna      | 129 ms                                                      | 119 ms: 1.08x faster                                                             |
| regex_v8       | 15.0 ms                                                     | 14.7 ms: 1.02x faster                                                            |
| regex_effbot   | 1.56 ms                                                     | 1.57 ms: 1.00x slower                                                            |
| Geometric mean | (ref)                                                       | 1.08x faster                                                                     |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.79 ms: 1.51x faster                                                            |
| pickle_pure_python   | 259 us                                                      | 182 us: 1.42x faster                                                             |
| unpickle_pure_python | 177 us                                                      | 136 us: 1.31x faster                                                             |
| tomli_loads          | 1.65 sec                                                    | 1.32 sec: 1.25x faster                                                           |
| xml_etree_process    | 43.1 ms                                                     | 37.0 ms: 1.16x faster                                                            |
| unpickle             | 9.11 us                                                     | 8.22 us: 1.11x faster                                                            |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                            |
| xml_etree_parse      | 96.8 ms                                                     | 92.1 ms: 1.05x faster                                                            |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.3 ms: 1.02x faster                                                            |
| pickle               | 6.87 us                                                     | 7.07 us: 1.03x slower                                                            |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.07x slower                                                            |
| pickle_list          | 2.69 us                                                     | 2.91 us: 1.08x slower                                                            |
| Geometric mean       | (ref)                                                       | 1.11x faster                                                                     |

Benchmark hidden because not significant (2): xml_etree_generate, unpickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 20.0 ms: 1.02x slower                                                            |
| python_startup_no_site | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                            |
| Geometric mean         | (ref)                                                       | 1.10x slower                                                                     |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| mako      | 8.98 ms                                                     | 6.48 ms: 1.39x faster                                                            |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 76.5 us: 4.40x faster                                                            |
| deltablue                | 4.12 ms                                                     | 2.13 ms: 1.94x faster                                                            |
| richards_super           | 50.3 ms                                                     | 29.0 ms: 1.74x faster                                                            |
| logging_silent           | 93.4 ns                                                     | 56.9 ns: 1.64x faster                                                            |
| raytrace                 | 266 ms                                                      | 169 ms: 1.57x faster                                                             |
| richards                 | 40.6 ms                                                     | 25.9 ms: 1.57x faster                                                            |
| async_tree_none          | 424 ms                                                      | 271 ms: 1.56x faster                                                             |
| sqlglot_parse            | 1.20 ms                                                     | 779 us: 1.55x faster                                                             |
| generators               | 31.8 ms                                                     | 20.9 ms: 1.52x faster                                                            |
| asyncio_tcp              | 717 ms                                                      | 471 ms: 1.52x faster                                                             |
| json_dumps               | 8.77 ms                                                     | 5.79 ms: 1.51x faster                                                            |
| go                       | 135 ms                                                      | 90.8 ms: 1.49x faster                                                            |
| async_tree_io            | 1.07 sec                                                    | 725 ms: 1.48x faster                                                             |
| async_tree_memoization   | 505 ms                                                      | 346 ms: 1.46x faster                                                             |
| comprehensions           | 16.6 us                                                     | 11.5 us: 1.44x faster                                                            |
| chaos                    | 59.5 ms                                                     | 41.4 ms: 1.44x faster                                                            |
| sqlglot_transpile        | 1.45 ms                                                     | 1.01 ms: 1.44x faster                                                            |
| scimark_lu               | 84.0 ms                                                     | 58.8 ms: 1.43x faster                                                            |
| pickle_pure_python       | 259 us                                                      | 182 us: 1.42x faster                                                             |
| crypto_pyaes             | 63.1 ms                                                     | 45.3 ms: 1.39x faster                                                            |
| mako                     | 8.98 ms                                                     | 6.48 ms: 1.39x faster                                                            |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 456 ms: 1.36x faster                                                             |
| spectral_norm            | 78.9 ms                                                     | 58.3 ms: 1.35x faster                                                            |
| pyflate                  | 402 ms                                                      | 300 ms: 1.34x faster                                                             |
| scimark_monte_carlo      | 58.0 ms                                                     | 44.3 ms: 1.31x faster                                                            |
| unpickle_pure_python     | 177 us                                                      | 136 us: 1.31x faster                                                             |
| hexiom                   | 5.59 ms                                                     | 4.37 ms: 1.28x faster                                                            |
| scimark_sor              | 105 ms                                                      | 84.0 ms: 1.25x faster                                                            |
| regex_compile            | 102 ms                                                      | 81.7 ms: 1.25x faster                                                            |
| tomli_loads              | 1.65 sec                                                    | 1.32 sec: 1.25x faster                                                           |
| deepcopy_memo            | 29.0 us                                                     | 23.3 us: 1.24x faster                                                            |
| sympy_sum                | 105 ms                                                      | 85.4 ms: 1.23x faster                                                            |
| sqlite_synth             | 1.90 us                                                     | 1.55 us: 1.23x faster                                                            |
| chameleon                | 6.02 ms                                                     | 4.98 ms: 1.21x faster                                                            |
| pycparser                | 905 ms                                                      | 748 ms: 1.21x faster                                                             |
| sympy_str                | 193 ms                                                      | 160 ms: 1.20x faster                                                             |
| docutils                 | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                                           |
| float                    | 61.7 ms                                                     | 51.5 ms: 1.20x faster                                                            |
| deepcopy                 | 259 us                                                      | 218 us: 1.19x faster                                                             |
| tornado_http             | 106 ms                                                      | 89.0 ms: 1.19x faster                                                            |
| mypy2                    | 347 ms                                                      | 293 ms: 1.18x faster                                                             |
| dulwich_log              | 48.6 ms                                                     | 41.3 ms: 1.18x faster                                                            |
| sympy_expand             | 320 ms                                                      | 274 ms: 1.17x faster                                                             |
| sympy_integrate          | 15.0 ms                                                     | 12.8 ms: 1.17x faster                                                            |
| xml_etree_process        | 43.1 ms                                                     | 37.0 ms: 1.16x faster                                                            |
| pprint_pformat           | 1.22 sec                                                    | 1.05 sec: 1.16x faster                                                           |
| coroutines               | 15.5 ms                                                     | 13.4 ms: 1.16x faster                                                            |
| sqlglot_optimize         | 39.4 ms                                                     | 34.2 ms: 1.15x faster                                                            |
| pprint_safe_repr         | 594 ms                                                      | 516 ms: 1.15x faster                                                             |
| mdp                      | 1.71 sec                                                    | 1.49 sec: 1.15x faster                                                           |
| sqlglot_normalize        | 207 ms                                                      | 181 ms: 1.14x faster                                                             |
| deepcopy_reduce          | 2.22 us                                                     | 1.96 us: 1.13x faster                                                            |
| create_gc_cycles         | 800 us                                                      | 721 us: 1.11x faster                                                             |
| unpickle                 | 9.11 us                                                     | 8.22 us: 1.11x faster                                                            |
| 2to3                     | 239 ms                                                      | 216 ms: 1.11x faster                                                             |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.90 sec: 1.10x faster                                                           |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.43 ms: 1.10x faster                                                            |
| bench_thread_pool        | 913 us                                                      | 834 us: 1.09x faster                                                             |
| nqueens                  | 68.3 ms                                                     | 62.8 ms: 1.09x faster                                                            |
| regex_dna                | 129 ms                                                      | 119 ms: 1.08x faster                                                             |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                                            |
| xml_etree_parse          | 96.8 ms                                                     | 92.1 ms: 1.05x faster                                                            |
| fannkuch                 | 258 ms                                                      | 250 ms: 1.03x faster                                                             |
| logging_format           | 6.73 us                                                     | 6.54 us: 1.03x faster                                                            |
| logging_simple           | 6.28 us                                                     | 6.11 us: 1.03x faster                                                            |
| regex_v8                 | 15.0 ms                                                     | 14.7 ms: 1.02x faster                                                            |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.3 ms: 1.02x faster                                                            |
| regex_effbot             | 1.56 ms                                                     | 1.57 ms: 1.00x slower                                                            |
| nbody                    | 71.0 ms                                                     | 71.9 ms: 1.01x slower                                                            |
| meteor_contest           | 73.8 ms                                                     | 74.9 ms: 1.01x slower                                                            |
| python_startup           | 19.7 ms                                                     | 20.0 ms: 1.02x slower                                                            |
| scimark_fft              | 187 ms                                                      | 191 ms: 1.02x slower                                                             |
| pidigits                 | 146 ms                                                      | 150 ms: 1.03x slower                                                             |
| pickle                   | 6.87 us                                                     | 7.07 us: 1.03x slower                                                            |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.07x slower                                                            |
| pickle_dict              | 17.1 us                                                     | 18.4 us: 1.07x slower                                                            |
| bench_mp_pool            | 59.9 ms                                                     | 64.8 ms: 1.08x slower                                                            |
| pickle_list              | 2.69 us                                                     | 2.91 us: 1.08x slower                                                            |
| pathlib                  | 72.8 ms                                                     | 79.1 ms: 1.09x slower                                                            |
| async_generators         | 219 ms                                                      | 238 ms: 1.09x slower                                                             |
| coverage                 | 38.4 ms                                                     | 44.5 ms: 1.16x slower                                                            |
| python_startup_no_site   | 15.3 ms                                                     | 18.1 ms: 1.18x slower                                                            |
| telco                    | 3.82 ms                                                     | 4.66 ms: 1.22x slower                                                            |
| Geometric mean           | (ref)                                                       | 1.20x faster                                                                     |

Benchmark hidden because not significant (4): xml_etree_generate, json, unpack_sequence, unpickle_list
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-5137145/bm-20231111-pythonperf1-amd64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.14x
