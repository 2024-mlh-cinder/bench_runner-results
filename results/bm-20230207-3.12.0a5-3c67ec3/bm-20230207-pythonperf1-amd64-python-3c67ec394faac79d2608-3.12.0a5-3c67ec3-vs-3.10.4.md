
# Results vs. 3.10.4

- fork: python
- ref: 3c67ec394faac79d2608
- machine: windows-amd64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.24x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 192 ms: 1.24x faster                                                       |
| chameleon      | 6.02 ms                                                     | 4.41 ms: 1.37x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.50 sec: 1.25x faster                                                     |
| html5lib       | 47.5 ms                                                     | 34.1 ms: 1.39x faster                                                      |
| tornado_http   | 106 ms                                                      | 90.5 ms: 1.17x faster                                                      |
| Geometric mean | (ref)                                                       | 1.28x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 748 ms: 1.43x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 356 ms: 1.42x faster                                                       |
| async_tree_none         | 424 ms                                                      | 302 ms: 1.41x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 480 ms: 1.29x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.38x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 47.3 ms: 1.31x faster                                                      |
| nbody          | 71.0 ms                                                     | 59.1 ms: 1.20x faster                                                      |
| pidigits       | 146 ms                                                      | 146 ms: 1.00x faster                                                       |
| Geometric mean | (ref)                                                       | 1.16x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 78.8 ms: 1.30x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                                      |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.68 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                       | 1.09x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.38 ms: 1.63x faster                                                      |
| pickle_pure_python   | 259 us                                                      | 166 us: 1.56x faster                                                       |
| unpickle_pure_python | 177 us                                                      | 120 us: 1.48x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 33.5 ms: 1.29x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 49.5 ms: 1.10x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 88.5 ms: 1.09x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.3 ms: 1.04x faster                                                      |
| pickle               | 6.87 us                                                     | 6.77 us: 1.02x faster                                                      |
| unpickle             | 9.11 us                                                     | 9.39 us: 1.03x slower                                                      |
| pickle_dict          | 17.1 us                                                     | 18.5 us: 1.08x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.14x faster                                                               |

Benchmark hidden because not significant (3): unpickle_list, json_loads, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.2 ms: 1.08x faster                                                      |
| Geometric mean | (ref)                                                       | 1.03x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 6.15 ms: 1.46x faster                                                      |
| django_template | 28.8 ms                                                     | 20.2 ms: 1.43x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 14.2 ms: 1.32x faster                                                      |
| genshi_xml      | 39.4 ms                                                     | 32.6 ms: 1.21x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.35x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 1.96 ms: 2.11x faster                                                      |
| go                      | 135 ms                                                      | 78.8 ms: 1.72x faster                                                      |
| richards                | 40.6 ms                                                     | 23.9 ms: 1.70x faster                                                      |
| mypy2                   | 347 ms                                                      | 208 ms: 1.67x faster                                                       |
| json_dumps              | 8.77 ms                                                     | 5.38 ms: 1.63x faster                                                      |
| logging_silent          | 93.4 ns                                                     | 58.1 ns: 1.61x faster                                                      |
| scimark_sor             | 105 ms                                                      | 67.0 ms: 1.57x faster                                                      |
| unpack_sequence         | 40.0 ns                                                     | 25.6 ns: 1.56x faster                                                      |
| raytrace                | 266 ms                                                      | 170 ms: 1.56x faster                                                       |
| pickle_pure_python      | 259 us                                                      | 166 us: 1.56x faster                                                       |
| asyncio_tcp             | 717 ms                                                      | 466 ms: 1.54x faster                                                       |
| scimark_monte_carlo     | 58.0 ms                                                     | 37.9 ms: 1.53x faster                                                      |
| pyflate                 | 402 ms                                                      | 267 ms: 1.50x faster                                                       |
| chaos                   | 59.5 ms                                                     | 39.6 ms: 1.50x faster                                                      |
| hexiom                  | 5.59 ms                                                     | 3.73 ms: 1.50x faster                                                      |
| unpickle_pure_python    | 177 us                                                      | 120 us: 1.48x faster                                                       |
| mako                    | 8.98 ms                                                     | 6.15 ms: 1.46x faster                                                      |
| crypto_pyaes            | 63.1 ms                                                     | 44.0 ms: 1.43x faster                                                      |
| scimark_lu              | 84.0 ms                                                     | 58.7 ms: 1.43x faster                                                      |
| async_tree_io           | 1.07 sec                                                    | 748 ms: 1.43x faster                                                       |
| pycparser               | 905 ms                                                      | 633 ms: 1.43x faster                                                       |
| django_template         | 28.8 ms                                                     | 20.2 ms: 1.43x faster                                                      |
| async_tree_memoization  | 505 ms                                                      | 356 ms: 1.42x faster                                                       |
| comprehensions          | 16.6 us                                                     | 11.7 us: 1.42x faster                                                      |
| sqlglot_parse           | 1.20 ms                                                     | 851 us: 1.41x faster                                                       |
| async_tree_none         | 424 ms                                                      | 302 ms: 1.41x faster                                                       |
| html5lib                | 47.5 ms                                                     | 34.1 ms: 1.39x faster                                                      |
| thrift                  | 623 us                                                      | 452 us: 1.38x faster                                                       |
| sqlglot_transpile       | 1.45 ms                                                     | 1.05 ms: 1.38x faster                                                      |
| deepcopy_memo           | 29.0 us                                                     | 21.1 us: 1.37x faster                                                      |
| chameleon               | 6.02 ms                                                     | 4.41 ms: 1.37x faster                                                      |
| pprint_pformat          | 1.22 sec                                                    | 907 ms: 1.35x faster                                                       |
| pprint_safe_repr        | 594 ms                                                      | 445 ms: 1.33x faster                                                       |
| genshi_text             | 18.8 ms                                                     | 14.2 ms: 1.32x faster                                                      |
| async_generators        | 219 ms                                                      | 167 ms: 1.31x faster                                                       |
| float                   | 61.7 ms                                                     | 47.3 ms: 1.31x faster                                                      |
| regex_compile           | 102 ms                                                      | 78.8 ms: 1.30x faster                                                      |
| xml_etree_process       | 43.1 ms                                                     | 33.5 ms: 1.29x faster                                                      |
| async_tree_cpu_io_mixed | 617 ms                                                      | 480 ms: 1.29x faster                                                       |
| spectral_norm           | 78.9 ms                                                     | 61.5 ms: 1.28x faster                                                      |
| docutils                | 1.88 sec                                                    | 1.50 sec: 1.25x faster                                                     |
| nqueens                 | 68.3 ms                                                     | 54.6 ms: 1.25x faster                                                      |
| sqlglot_optimize        | 39.4 ms                                                     | 31.6 ms: 1.25x faster                                                      |
| 2to3                    | 239 ms                                                      | 192 ms: 1.24x faster                                                       |
| deepcopy                | 259 us                                                      | 211 us: 1.23x faster                                                       |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.18 ms: 1.22x faster                                                      |
| fannkuch                | 258 ms                                                      | 213 ms: 1.21x faster                                                       |
| genshi_xml              | 39.4 ms                                                     | 32.6 ms: 1.21x faster                                                      |
| sqlglot_normalize       | 207 ms                                                      | 171 ms: 1.21x faster                                                       |
| sympy_integrate         | 15.0 ms                                                     | 12.4 ms: 1.21x faster                                                      |
| nbody                   | 71.0 ms                                                     | 59.1 ms: 1.20x faster                                                      |
| sympy_expand            | 320 ms                                                      | 269 ms: 1.19x faster                                                       |
| create_gc_cycles        | 800 us                                                      | 676 us: 1.18x faster                                                       |
| deepcopy_reduce         | 2.22 us                                                     | 1.88 us: 1.18x faster                                                      |
| sympy_str               | 193 ms                                                      | 164 ms: 1.18x faster                                                       |
| sympy_sum               | 105 ms                                                      | 89.5 ms: 1.18x faster                                                      |
| tornado_http            | 106 ms                                                      | 90.5 ms: 1.17x faster                                                      |
| dulwich_log             | 48.6 ms                                                     | 41.9 ms: 1.16x faster                                                      |
| mdp                     | 1.71 sec                                                    | 1.48 sec: 1.16x faster                                                     |
| scimark_fft             | 187 ms                                                      | 166 ms: 1.13x faster                                                       |
| bench_thread_pool       | 913 us                                                      | 823 us: 1.11x faster                                                       |
| json                    | 3.10 ms                                                     | 2.81 ms: 1.10x faster                                                      |
| xml_etree_generate      | 54.5 ms                                                     | 49.5 ms: 1.10x faster                                                      |
| regex_v8                | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                                      |
| xml_etree_parse         | 96.8 ms                                                     | 88.5 ms: 1.09x faster                                                      |
| python_startup          | 19.7 ms                                                     | 18.2 ms: 1.08x faster                                                      |
| logging_format          | 6.73 us                                                     | 6.28 us: 1.07x faster                                                      |
| meteor_contest          | 73.8 ms                                                     | 69.1 ms: 1.07x faster                                                      |
| regex_dna               | 129 ms                                                      | 121 ms: 1.07x faster                                                       |
| coroutines              | 15.5 ms                                                     | 14.8 ms: 1.05x faster                                                      |
| logging_simple          | 6.28 us                                                     | 6.01 us: 1.04x faster                                                      |
| sqlite_synth            | 1.90 us                                                     | 1.82 us: 1.04x faster                                                      |
| xml_etree_iterparse     | 64.5 ms                                                     | 62.3 ms: 1.04x faster                                                      |
| telco                   | 3.82 ms                                                     | 3.72 ms: 1.03x faster                                                      |
| pickle                  | 6.87 us                                                     | 6.77 us: 1.02x faster                                                      |
| pidigits                | 146 ms                                                      | 146 ms: 1.00x faster                                                       |
| pathlib                 | 72.8 ms                                                     | 73.7 ms: 1.01x slower                                                      |
| bench_mp_pool           | 59.9 ms                                                     | 61.7 ms: 1.03x slower                                                      |
| unpickle                | 9.11 us                                                     | 9.39 us: 1.03x slower                                                      |
| gc_traversal            | 1.40 ms                                                     | 1.45 ms: 1.04x slower                                                      |
| generators              | 31.8 ms                                                     | 33.0 ms: 1.04x slower                                                      |
| regex_effbot            | 1.56 ms                                                     | 1.68 ms: 1.08x slower                                                      |
| pickle_dict             | 17.1 us                                                     | 18.5 us: 1.08x slower                                                      |
| dask                    | 305 ms                                                      | 349 ms: 1.15x slower                                                       |
| coverage                | 38.4 ms                                                     | 51.8 ms: 1.35x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.24x faster                                                               |

Benchmark hidden because not significant (4): unpickle_list, json_loads, pickle_list, python_startup_no_site
Ignored benchmarks (9) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.22x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.19x
