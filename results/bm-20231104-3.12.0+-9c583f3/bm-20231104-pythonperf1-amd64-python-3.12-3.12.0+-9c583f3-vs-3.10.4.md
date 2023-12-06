
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: windows-amd64
- commit hash: 9c583f3
- commit date: 2023-11-04
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 212 ms: 1.13x faster                                      |
| chameleon      | 6.02 ms                                                     | 5.01 ms: 1.20x faster                                     |
| docutils       | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                    |
| tornado_http   | 106 ms                                                      | 87.4 ms: 1.21x faster                                     |
| Geometric mean | (ref)                                                       | 1.18x faster                                              |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| async_tree_memoization  | 505 ms                                                      | 336 ms: 1.50x faster                                      |
| async_tree_io           | 1.07 sec                                                    | 724 ms: 1.48x faster                                      |
| async_tree_none         | 424 ms                                                      | 288 ms: 1.47x faster                                      |
| async_tree_cpu_io_mixed | 617 ms                                                      | 477 ms: 1.29x faster                                      |
| Geometric mean          | (ref)                                                       | 1.43x faster                                              |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.9 ms: 1.15x faster                                     |
| nbody          | 71.0 ms                                                     | 67.6 ms: 1.05x faster                                     |
| pidigits       | 146 ms                                                      | 152 ms: 1.04x slower                                      |
| Geometric mean | (ref)                                                       | 1.05x faster                                              |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 85.8 ms: 1.19x faster                                     |
| regex_v8       | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                     |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                      |
| regex_effbot   | 1.56 ms                                                     | 1.59 ms: 1.01x slower                                     |
| Geometric mean | (ref)                                                       | 1.09x faster                                              |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.60 ms: 1.56x faster                                     |
| pickle_pure_python   | 259 us                                                      | 192 us: 1.35x faster                                      |
| unpickle_pure_python | 177 us                                                      | 132 us: 1.34x faster                                      |
| tomli_loads          | 1.65 sec                                                    | 1.38 sec: 1.19x faster                                    |
| xml_etree_process    | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                     |
| unpickle             | 9.11 us                                                     | 8.12 us: 1.12x faster                                     |
| xml_etree_parse      | 96.8 ms                                                     | 90.6 ms: 1.07x faster                                     |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                     |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                     |
| xml_etree_generate   | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                     |
| pickle               | 6.87 us                                                     | 7.07 us: 1.03x slower                                     |
| unpickle_list        | 2.68 us                                                     | 2.80 us: 1.05x slower                                     |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                     |
| pickle_list          | 2.69 us                                                     | 2.90 us: 1.08x slower                                     |
| Geometric mean       | (ref)                                                       | 1.10x faster                                              |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 18.9 ms: 1.04x faster                                     |
| python_startup_no_site | 15.3 ms                                                     | 16.0 ms: 1.04x slower                                     |
| Geometric mean         | (ref)                                                       | 1.00x slower                                              |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 6.89 ms: 1.30x faster                                     |
| django_template | 28.8 ms                                                     | 23.3 ms: 1.24x faster                                     |
| Geometric mean  | (ref)                                                       | 1.27x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3 |
|--------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------:|
| typing_runtime_protocols | 337 us                                                      | 77.7 us: 4.33x faster                                     |
| deltablue                | 4.12 ms                                                     | 2.16 ms: 1.91x faster                                     |
| richards_super           | 50.3 ms                                                     | 30.1 ms: 1.67x faster                                     |
| mypy2                    | 347 ms                                                      | 208 ms: 1.66x faster                                      |
| go                       | 135 ms                                                      | 86.3 ms: 1.57x faster                                     |
| json_dumps               | 8.77 ms                                                     | 5.60 ms: 1.56x faster                                     |
| logging_silent           | 93.4 ns                                                     | 60.8 ns: 1.54x faster                                     |
| richards                 | 40.6 ms                                                     | 26.6 ms: 1.52x faster                                     |
| async_tree_memoization   | 505 ms                                                      | 336 ms: 1.50x faster                                      |
| asyncio_tcp              | 717 ms                                                      | 481 ms: 1.49x faster                                      |
| async_tree_io            | 1.07 sec                                                    | 724 ms: 1.48x faster                                      |
| async_tree_none          | 424 ms                                                      | 288 ms: 1.47x faster                                      |
| sqlglot_parse            | 1.20 ms                                                     | 830 us: 1.45x faster                                      |
| scimark_lu               | 84.0 ms                                                     | 58.0 ms: 1.45x faster                                     |
| generators               | 31.8 ms                                                     | 22.1 ms: 1.44x faster                                     |
| chaos                    | 59.5 ms                                                     | 42.4 ms: 1.40x faster                                     |
| sqlglot_transpile        | 1.45 ms                                                     | 1.04 ms: 1.39x faster                                     |
| raytrace                 | 266 ms                                                      | 192 ms: 1.39x faster                                      |
| pyflate                  | 402 ms                                                      | 291 ms: 1.38x faster                                      |
| hexiom                   | 5.59 ms                                                     | 4.06 ms: 1.38x faster                                     |
| crypto_pyaes             | 63.1 ms                                                     | 46.0 ms: 1.37x faster                                     |
| scimark_sor              | 105 ms                                                      | 77.2 ms: 1.36x faster                                     |
| pickle_pure_python       | 259 us                                                      | 192 us: 1.35x faster                                      |
| unpickle_pure_python     | 177 us                                                      | 132 us: 1.34x faster                                      |
| scimark_monte_carlo      | 58.0 ms                                                     | 44.5 ms: 1.30x faster                                     |
| mako                     | 8.98 ms                                                     | 6.89 ms: 1.30x faster                                     |
| async_tree_cpu_io_mixed  | 617 ms                                                      | 477 ms: 1.29x faster                                      |
| pycparser                | 905 ms                                                      | 710 ms: 1.27x faster                                      |
| deepcopy_memo            | 29.0 us                                                     | 23.1 us: 1.25x faster                                     |
| spectral_norm            | 78.9 ms                                                     | 63.1 ms: 1.25x faster                                     |
| django_template          | 28.8 ms                                                     | 23.3 ms: 1.24x faster                                     |
| sqlalchemy_imperative    | 11.2 ms                                                     | 9.13 ms: 1.22x faster                                     |
| tornado_http             | 106 ms                                                      | 87.4 ms: 1.21x faster                                     |
| chameleon                | 6.02 ms                                                     | 5.01 ms: 1.20x faster                                     |
| dask                     | 305 ms                                                      | 254 ms: 1.20x faster                                      |
| sympy_sum                | 105 ms                                                      | 87.7 ms: 1.20x faster                                     |
| regex_compile            | 102 ms                                                      | 85.8 ms: 1.19x faster                                     |
| tomli_loads              | 1.65 sec                                                    | 1.38 sec: 1.19x faster                                    |
| comprehensions           | 16.6 us                                                     | 13.9 us: 1.19x faster                                     |
| pprint_pformat           | 1.22 sec                                                    | 1.03 sec: 1.19x faster                                    |
| docutils                 | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                    |
| sympy_integrate          | 15.0 ms                                                     | 12.7 ms: 1.18x faster                                     |
| pprint_safe_repr         | 594 ms                                                      | 505 ms: 1.18x faster                                      |
| sqlalchemy_declarative   | 98.6 ms                                                     | 84.3 ms: 1.17x faster                                     |
| sympy_expand             | 320 ms                                                      | 277 ms: 1.16x faster                                      |
| sqlglot_optimize         | 39.4 ms                                                     | 34.1 ms: 1.16x faster                                     |
| dulwich_log              | 48.6 ms                                                     | 42.2 ms: 1.15x faster                                     |
| float                    | 61.7 ms                                                     | 53.9 ms: 1.15x faster                                     |
| xml_etree_process        | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                     |
| sympy_str                | 193 ms                                                      | 170 ms: 1.14x faster                                      |
| deepcopy                 | 259 us                                                      | 229 us: 1.13x faster                                      |
| mdp                      | 1.71 sec                                                    | 1.51 sec: 1.13x faster                                    |
| 2to3                     | 239 ms                                                      | 212 ms: 1.13x faster                                      |
| nqueens                  | 68.3 ms                                                     | 60.5 ms: 1.13x faster                                     |
| aiohttp                  | 961 us                                                      | 853 us: 1.13x faster                                      |
| sqlglot_normalize        | 207 ms                                                      | 184 ms: 1.12x faster                                      |
| unpickle                 | 9.11 us                                                     | 8.12 us: 1.12x faster                                     |
| bench_thread_pool        | 913 us                                                      | 823 us: 1.11x faster                                      |
| unpack_sequence          | 40.0 ns                                                     | 36.1 ns: 1.11x faster                                     |
| create_gc_cycles         | 800 us                                                      | 723 us: 1.11x faster                                      |
| coroutines               | 15.5 ms                                                     | 14.1 ms: 1.10x faster                                     |
| sqlite_synth             | 1.90 us                                                     | 1.73 us: 1.10x faster                                     |
| regex_v8                 | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                     |
| asyncio_tcp_ssl          | 2.09 sec                                                    | 1.94 sec: 1.08x faster                                    |
| scimark_sparse_mat_mult  | 2.67 ms                                                     | 2.47 ms: 1.08x faster                                     |
| regex_dna                | 129 ms                                                      | 120 ms: 1.08x faster                                      |
| fannkuch                 | 258 ms                                                      | 239 ms: 1.08x faster                                      |
| deepcopy_reduce          | 2.22 us                                                     | 2.07 us: 1.07x faster                                     |
| json                     | 3.10 ms                                                     | 2.90 ms: 1.07x faster                                     |
| xml_etree_parse          | 96.8 ms                                                     | 90.6 ms: 1.07x faster                                     |
| json_loads               | 14.2 us                                                     | 13.4 us: 1.06x faster                                     |
| nbody                    | 71.0 ms                                                     | 67.6 ms: 1.05x faster                                     |
| python_startup           | 19.7 ms                                                     | 18.9 ms: 1.04x faster                                     |
| scimark_fft              | 187 ms                                                      | 181 ms: 1.04x faster                                      |
| xml_etree_iterparse      | 64.5 ms                                                     | 63.0 ms: 1.02x faster                                     |
| logging_simple           | 6.28 us                                                     | 6.32 us: 1.01x slower                                     |
| regex_effbot             | 1.56 ms                                                     | 1.59 ms: 1.01x slower                                     |
| xml_etree_generate       | 54.5 ms                                                     | 55.4 ms: 1.02x slower                                     |
| coverage                 | 38.4 ms                                                     | 39.4 ms: 1.03x slower                                     |
| pickle                   | 6.87 us                                                     | 7.07 us: 1.03x slower                                     |
| async_generators         | 219 ms                                                      | 227 ms: 1.04x slower                                      |
| pidigits                 | 146 ms                                                      | 152 ms: 1.04x slower                                      |
| python_startup_no_site   | 15.3 ms                                                     | 16.0 ms: 1.04x slower                                     |
| unpickle_list            | 2.68 us                                                     | 2.80 us: 1.05x slower                                     |
| gc_traversal             | 1.40 ms                                                     | 1.46 ms: 1.05x slower                                     |
| bench_mp_pool            | 59.9 ms                                                     | 63.1 ms: 1.05x slower                                     |
| telco                    | 3.82 ms                                                     | 4.03 ms: 1.06x slower                                     |
| pickle_dict              | 17.1 us                                                     | 18.3 us: 1.07x slower                                     |
| pickle_list              | 2.69 us                                                     | 2.90 us: 1.08x slower                                     |
| pathlib                  | 72.8 ms                                                     | 78.8 ms: 1.08x slower                                     |
| Geometric mean           | (ref)                                                       | 1.20x faster                                              |

Benchmark hidden because not significant (2): meteor_contest, logging_format
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231104-3.12.0+-9c583f3/bm-20231104-pythonperf1-amd64-python-3.12-3.12.0+-9c583f3.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.13x
