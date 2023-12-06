
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.18x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 215 ms: 1.11x faster                                      |
| chameleon      | 6.02 ms                                                     | 5.23 ms: 1.15x faster                                     |
| docutils       | 1.88 sec                                                    | 1.62 sec: 1.16x faster                                    |
| tornado_http   | 106 ms                                                      | 87.5 ms: 1.21x faster                                     |
| Geometric mean | (ref)                                                       | 1.16x faster                                              |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 718 ms: 1.49x faster                                      |
| async_tree_memoization  | 505 ms                                                      | 339 ms: 1.49x faster                                      |
| async_tree_none         | 424 ms                                                      | 288 ms: 1.47x faster                                      |
| async_tree_cpu_io_mixed | 617 ms                                                      | 481 ms: 1.28x faster                                      |
| Geometric mean          | (ref)                                                       | 1.43x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 61.7 ms                                                     | 54.5 ms: 1.13x faster                                     |
| nbody          | 71.0 ms                                                     | 70.3 ms: 1.01x faster                                     |
| pidigits       | 146 ms                                                      | 151 ms: 1.03x slower                                      |
| Geometric mean | (ref)                                                       | 1.04x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 89.0 ms: 1.15x faster                                     |
| regex_v8       | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                     |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                      |
| regex_effbot   | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                     |
| Geometric mean | (ref)                                                       | 1.07x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.62 ms: 1.56x faster                                     |
| pickle_pure_python   | 259 us                                                      | 197 us: 1.31x faster                                      |
| unpickle_pure_python | 177 us                                                      | 136 us: 1.30x faster                                      |
| tomli_loads          | 1.65 sec                                                    | 1.41 sec: 1.17x faster                                    |
| unpickle             | 9.11 us                                                     | 8.15 us: 1.12x faster                                     |
| xml_etree_process    | 43.1 ms                                                     | 38.7 ms: 1.11x faster                                     |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                     |
| xml_etree_parse      | 96.8 ms                                                     | 92.3 ms: 1.05x faster                                     |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.7 ms: 1.01x faster                                     |
| unpickle_list        | 2.68 us                                                     | 2.78 us: 1.04x slower                                     |
| xml_etree_generate   | 54.5 ms                                                     | 56.7 ms: 1.04x slower                                     |
| pickle               | 6.87 us                                                     | 7.25 us: 1.05x slower                                     |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                     |
| pickle_list          | 2.69 us                                                     | 2.90 us: 1.08x slower                                     |
| Geometric mean       | (ref)                                                       | 1.09x faster                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 19.9 ms: 1.01x slower                                     |
| python_startup_no_site | 15.3 ms                                                     | 16.5 ms: 1.08x slower                                     |
| Geometric mean         | (ref)                                                       | 1.04x slower                                              |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 6.90 ms: 1.30x faster                                     |
| django_template | 28.8 ms                                                     | 23.3 ms: 1.24x faster                                     |
| Geometric mean  | (ref)                                                       | 1.27x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 95.9 us: 3.51x faster                                     |
| deltablue                | 4.12 ms                                                     | 2.16 ms: 1.91x faster                                     |
| mypy2                    | 347 ms                                                      | 209 ms: 1.66x faster                                      |
| richards_super           | 50.3 ms                                                     | 31.5 ms: 1.60x faster                                     |
| json_dumps               | 8.77 ms                                                     | 5.62 ms: 1.56x faster                                     |
| logging_silent           | 93.4 ns                                                     | 61.1 ns: 1.53x faster                                     |
| asyncio_tcp              | 717 ms                                                      | 474 ms: 1.51x faster                                      |
| go                       | 135 ms                                                      | 89.8 ms: 1.51x faster                                     |
| async_tree_io            | 1.07 sec                                                    | 718 ms: 1.49x faster                                      |
| async_tree_memoization   | 505 ms                                                      | 339 ms: 1.49x faster                                      |
| sqlglot_parse            | 1.20 ms                                                     | 815 us: 1.48x faster                                      |
| async_tree_none          | 424 ms                                                      | 288 ms: 1.47x faster                                      |
| richards                 | 40.6 ms                                                     | 27.8 ms: 1.46x faster                                     |
| generators               | 31.8 ms                                                     | 22.5 ms: 1.42x faster                                     |
| sqlglot_transpile        | 1.45 ms                                                     | 1.03 ms: 1.41x faster                                     |
| scimark_lu               | 84.0 ms                                                     | 61.3 ms: 1.37x faster                                     |
| raytrace                 | 266 ms                                                      | 198 ms: 1.35x faster                                      |
| pyflate                  | 402 ms                                                      | 299 ms: 1.35x faster                                      |
| chaos                    | 59.5 ms                                                     | 44.3 ms: 1.34x faster                                     |
| hexiom                   | 5.59 ms                                                     | 4.18 ms: 1.34x faster                                     |
| pycparser                | 905 ms                                                      | 683 ms: 1.32x faster                                      |
| crypto_pyaes             | 63.1 ms                                                     | 47.7 ms: 1.32x faster                                     |
| pickle_pure_python       | 259 us                                                      | 197 us: 1.31x faster                                      |
| unpickle_pure_python     | 177 us                                                      | 136 us: 1.30x faster                                      |
| mako                     | 8.98 ms                                                     | 6.90 ms: 1.30x faster                                     |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 481 ms: 1.28x faster                                      |
| scimark_monte_carlo      | 58.0 ms                                                     | 45.4 ms: 1.28x faster                                     |
| scimark_sor              | 105 ms                                                      | 84.2 ms: 1.25x faster                                     |
| django_template          | 28.8 ms                                                     | 23.3 ms: 1.24x faster                                     |
| spectral_norm            | 78.9 ms                                                     | 64.5 ms: 1.22x faster                                     |
| tornado_http             | 106 ms                                                      | 87.5 ms: 1.21x faster                                     |
| sqlalchemy_imperative    | 11.2 ms                                                     | 9.25 ms: 1.21x faster                                     |
| sympy_sum                | 105 ms                                                      | 87.9 ms: 1.20x faster                                     |
| deepcopy_memo            | 29.0 us                                                     | 24.4 us: 1.19x faster                                     |
| dask                     | 305 ms                                                      | 257 ms: 1.19x faster                                      |
| mdp                      | 1.71 sec                                                    | 1.46 sec: 1.17x faster                                    |
| tomli_loads              | 1.65 sec                                                    | 1.41 sec: 1.17x faster                                    |
| sympy_integrate          | 15.0 ms                                                     | 12.8 ms: 1.17x faster                                     |
| sqlalchemy_declarative   | 98.6 ms                                                     | 84.7 ms: 1.16x faster                                     |
| docutils                 | 1.88 sec                                                    | 1.62 sec: 1.16x faster                                    |
| pprint_pformat           | 1.22 sec                                                    | 1.06 sec: 1.15x faster                                    |
| chameleon                | 6.02 ms                                                     | 5.23 ms: 1.15x faster                                     |
| regex_compile            | 102 ms                                                      | 89.0 ms: 1.15x faster                                     |
| sqlglot_optimize         | 39.4 ms                                                     | 34.4 ms: 1.15x faster                                     |
| sympy_str                | 193 ms                                                      | 169 ms: 1.14x faster                                      |
| comprehensions           | 16.6 us                                                     | 14.5 us: 1.14x faster                                     |
| dulwich_log              | 48.6 ms                                                     | 42.6 ms: 1.14x faster                                     |
| pprint_safe_repr         | 594 ms                                                      | 522 ms: 1.14x faster                                      |
| sympy_expand             | 320 ms                                                      | 282 ms: 1.14x faster                                      |
| float                    | 61.7 ms                                                     | 54.5 ms: 1.13x faster                                     |
| sqlglot_normalize        | 207 ms                                                      | 184 ms: 1.12x faster                                      |
| unpickle                 | 9.11 us                                                     | 8.15 us: 1.12x faster                                     |
| aiohttp                  | 961 us                                                      | 861 us: 1.12x faster                                      |
| xml_etree_process        | 43.1 ms                                                     | 38.7 ms: 1.11x faster                                     |
| bench_thread_pool        | 913 us                                                      | 820 us: 1.11x faster                                      |
| 2to3                     | 239 ms                                                      | 215 ms: 1.11x faster                                      |
| create_gc_cycles         | 800 us                                                      | 725 us: 1.10x faster                                      |
| coroutines               | 15.5 ms                                                     | 14.1 ms: 1.10x faster                                     |
| nqueens                  | 68.3 ms                                                     | 62.4 ms: 1.10x faster                                     |
| sqlite_synth             | 1.90 us                                                     | 1.74 us: 1.09x faster                                     |
| regex_v8                 | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                     |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.46 ms: 1.08x faster                                     |
| deepcopy                 | 259 us                                                      | 240 us: 1.08x faster                                      |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.96 sec: 1.07x faster                                    |
| regex_dna                | 129 ms                                                      | 121 ms: 1.07x faster                                      |
| json_loads               | 14.2 us                                                     | 13.5 us: 1.05x faster                                     |
| json                     | 3.10 ms                                                     | 2.95 ms: 1.05x faster                                     |
| xml_etree_parse          | 96.8 ms                                                     | 92.3 ms: 1.05x faster                                     |
| deepcopy_reduce          | 2.22 us                                                     | 2.14 us: 1.04x faster                                     |
| fannkuch                 | 258 ms                                                      | 251 ms: 1.03x faster                                      |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.7 ms: 1.01x faster                                     |
| nbody                    | 71.0 ms                                                     | 70.3 ms: 1.01x faster                                     |
| scimark_fft              | 187 ms                                                      | 189 ms: 1.01x slower                                      |
| python_startup           | 19.7 ms                                                     | 19.9 ms: 1.01x slower                                     |
| coverage                 | 38.4 ms                                                     | 38.8 ms: 1.01x slower                                     |
| logging_format           | 6.73 us                                                     | 6.83 us: 1.01x slower                                     |
| meteor_contest           | 73.8 ms                                                     | 75.0 ms: 1.02x slower                                     |
| logging_simple           | 6.28 us                                                     | 6.37 us: 1.02x slower                                     |
| pidigits                 | 146 ms                                                      | 151 ms: 1.03x slower                                      |
| regex_effbot             | 1.56 ms                                                     | 1.62 ms: 1.03x slower                                     |
| unpack_sequence          | 40.0 ns                                                     | 41.4 ns: 1.03x slower                                     |
| unpickle_list            | 2.68 us                                                     | 2.78 us: 1.04x slower                                     |
| xml_etree_generate       | 54.5 ms                                                     | 56.7 ms: 1.04x slower                                     |
| bench_mp_pool            | 59.9 ms                                                     | 63.2 ms: 1.05x slower                                     |
| pickle                   | 6.87 us                                                     | 7.25 us: 1.05x slower                                     |
| telco                    | 3.82 ms                                                     | 4.05 ms: 1.06x slower                                     |
| gc_traversal             | 1.40 ms                                                     | 1.49 ms: 1.06x slower                                     |
| pickle_dict              | 17.1 us                                                     | 18.3 us: 1.07x slower                                     |
| async_generators         | 219 ms                                                      | 234 ms: 1.07x slower                                      |
| pickle_list              | 2.69 us                                                     | 2.90 us: 1.08x slower                                     |
| python_startup_no_site   | 15.3 ms                                                     | 16.5 ms: 1.08x slower                                     |
| pathlib                  | 72.8 ms                                                     | 79.1 ms: 1.09x slower                                     |
| Geometric mean           | (ref)                                                       | 1.18x faster                                              |
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231028-3.12.0+-f7ce402/bm-20231028-pythonperf1-amd64-python-3.12-3.12.0+-f7ce402.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.14x
- 95% likely to have a speedup of 1.13x
- 99% likely to have a speedup of 1.12x
