
# Results vs. 3.10.4

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: windows-amd64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.21x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 196 ms: 1.22x faster                                                       |
| chameleon      | 6.02 ms                                                     | 4.53 ms: 1.33x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                                     |
| html5lib       | 47.5 ms                                                     | 35.0 ms: 1.36x faster                                                      |
| Geometric mean | (ref)                                                       | 1.28x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 780 ms: 1.37x faster                                                       |
| async_tree_none         | 424 ms                                                      | 317 ms: 1.34x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 388 ms: 1.30x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 501 ms: 1.23x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.31x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 50.1 ms: 1.23x faster                                                      |
| nbody          | 71.0 ms                                                     | 62.3 ms: 1.14x faster                                                      |
| pidigits       | 146 ms                                                      | 151 ms: 1.03x slower                                                       |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 82.5 ms: 1.24x faster                                                      |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                                       |
| regex_v8       | 15.0 ms                                                     | 14.0 ms: 1.08x faster                                                      |
| regex_effbot   | 1.56 ms                                                     | 1.54 ms: 1.01x faster                                                      |
| Geometric mean | (ref)                                                       | 1.10x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.17 ms: 1.70x faster                                                      |
| unpickle_pure_python | 177 us                                                      | 121 us: 1.47x faster                                                       |
| pickle_pure_python   | 259 us                                                      | 179 us: 1.45x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 35.0 ms: 1.23x faster                                                      |
| unpickle             | 9.11 us                                                     | 7.99 us: 1.14x faster                                                      |
| json_loads           | 14.2 us                                                     | 12.9 us: 1.11x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 49.7 ms: 1.10x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 90.5 ms: 1.07x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.3 ms: 1.04x faster                                                      |
| unpickle_list        | 2.68 us                                                     | 2.61 us: 1.03x faster                                                      |
| pickle               | 6.87 us                                                     | 6.90 us: 1.00x slower                                                      |
| pickle_list          | 2.69 us                                                     | 2.85 us: 1.06x slower                                                      |
| pickle_dict          | 17.1 us                                                     | 19.4 us: 1.13x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.14x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 18.5 ms: 1.06x faster                                                      |
| python_startup_no_site | 15.3 ms                                                     | 15.7 ms: 1.03x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 6.19 ms: 1.45x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 13.8 ms: 1.36x faster                                                      |
| django_template | 28.8 ms                                                     | 21.4 ms: 1.35x faster                                                      |
| genshi_xml      | 39.4 ms                                                     | 32.3 ms: 1.22x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.34x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.07 ms: 1.99x faster                                                      |
| json_dumps              | 8.77 ms                                                     | 5.17 ms: 1.70x faster                                                      |
| richards                | 40.6 ms                                                     | 24.5 ms: 1.65x faster                                                      |
| logging_silent          | 93.4 ns                                                     | 57.2 ns: 1.63x faster                                                      |
| scimark_sor             | 105 ms                                                      | 64.6 ms: 1.63x faster                                                      |
| mypy2                   | 347 ms                                                      | 215 ms: 1.61x faster                                                       |
| go                      | 135 ms                                                      | 84.8 ms: 1.60x faster                                                      |
| scimark_lu              | 84.0 ms                                                     | 54.8 ms: 1.53x faster                                                      |
| pyflate                 | 402 ms                                                      | 264 ms: 1.53x faster                                                       |
| scimark_monte_carlo     | 58.0 ms                                                     | 38.1 ms: 1.52x faster                                                      |
| unpack_sequence         | 40.0 ns                                                     | 26.4 ns: 1.51x faster                                                      |
| raytrace                | 266 ms                                                      | 179 ms: 1.49x faster                                                       |
| unpickle_pure_python    | 177 us                                                      | 121 us: 1.47x faster                                                       |
| mako                    | 8.98 ms                                                     | 6.19 ms: 1.45x faster                                                      |
| pickle_pure_python      | 259 us                                                      | 179 us: 1.45x faster                                                       |
| hexiom                  | 5.59 ms                                                     | 3.89 ms: 1.44x faster                                                      |
| sqlglot_parse           | 1.20 ms                                                     | 860 us: 1.40x faster                                                       |
| crypto_pyaes            | 63.1 ms                                                     | 45.1 ms: 1.40x faster                                                      |
| chaos                   | 59.5 ms                                                     | 43.2 ms: 1.38x faster                                                      |
| async_tree_io           | 1.07 sec                                                    | 780 ms: 1.37x faster                                                       |
| deepcopy_memo           | 29.0 us                                                     | 21.2 us: 1.37x faster                                                      |
| sqlglot_transpile       | 1.45 ms                                                     | 1.06 ms: 1.36x faster                                                      |
| genshi_text             | 18.8 ms                                                     | 13.8 ms: 1.36x faster                                                      |
| html5lib                | 47.5 ms                                                     | 35.0 ms: 1.36x faster                                                      |
| django_template         | 28.8 ms                                                     | 21.4 ms: 1.35x faster                                                      |
| async_tree_none         | 424 ms                                                      | 317 ms: 1.34x faster                                                       |
| chameleon               | 6.02 ms                                                     | 4.53 ms: 1.33x faster                                                      |
| thrift                  | 623 us                                                      | 469 us: 1.33x faster                                                       |
| pycparser               | 905 ms                                                      | 691 ms: 1.31x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 388 ms: 1.30x faster                                                       |
| pprint_safe_repr        | 594 ms                                                      | 458 ms: 1.30x faster                                                       |
| pprint_pformat          | 1.22 sec                                                    | 947 ms: 1.29x faster                                                       |
| spectral_norm           | 78.9 ms                                                     | 61.4 ms: 1.28x faster                                                      |
| regex_compile           | 102 ms                                                      | 82.5 ms: 1.24x faster                                                      |
| xml_etree_process       | 43.1 ms                                                     | 35.0 ms: 1.23x faster                                                      |
| float                   | 61.7 ms                                                     | 50.1 ms: 1.23x faster                                                      |
| async_tree_cpu_io_mixed | 617 ms                                                      | 501 ms: 1.23x faster                                                       |
| sqlglot_optimize        | 39.4 ms                                                     | 32.0 ms: 1.23x faster                                                      |
| genshi_xml              | 39.4 ms                                                     | 32.3 ms: 1.22x faster                                                      |
| async_generators        | 219 ms                                                      | 179 ms: 1.22x faster                                                       |
| 2to3                    | 239 ms                                                      | 196 ms: 1.22x faster                                                       |
| deepcopy                | 259 us                                                      | 214 us: 1.21x faster                                                       |
| sqlglot_normalize       | 207 ms                                                      | 172 ms: 1.20x faster                                                       |
| docutils                | 1.88 sec                                                    | 1.56 sec: 1.20x faster                                                     |
| deepcopy_reduce         | 2.22 us                                                     | 1.88 us: 1.18x faster                                                      |
| dask                    | 305 ms                                                      | 258 ms: 1.18x faster                                                       |
| dulwich_log             | 48.6 ms                                                     | 41.2 ms: 1.18x faster                                                      |
| nqueens                 | 68.3 ms                                                     | 57.9 ms: 1.18x faster                                                      |
| create_gc_cycles        | 800 us                                                      | 682 us: 1.17x faster                                                       |
| fannkuch                | 258 ms                                                      | 222 ms: 1.16x faster                                                       |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.30 ms: 1.16x faster                                                      |
| unpickle                | 9.11 us                                                     | 7.99 us: 1.14x faster                                                      |
| nbody                   | 71.0 ms                                                     | 62.3 ms: 1.14x faster                                                      |
| json                    | 3.10 ms                                                     | 2.74 ms: 1.13x faster                                                      |
| sympy_integrate         | 15.0 ms                                                     | 13.3 ms: 1.13x faster                                                      |
| sympy_expand            | 320 ms                                                      | 286 ms: 1.12x faster                                                       |
| sympy_str               | 193 ms                                                      | 173 ms: 1.12x faster                                                       |
| json_loads              | 14.2 us                                                     | 12.9 us: 1.11x faster                                                      |
| xml_etree_generate      | 54.5 ms                                                     | 49.7 ms: 1.10x faster                                                      |
| sqlite_synth            | 1.90 us                                                     | 1.73 us: 1.10x faster                                                      |
| bench_thread_pool       | 913 us                                                      | 837 us: 1.09x faster                                                       |
| regex_dna               | 129 ms                                                      | 120 ms: 1.08x faster                                                       |
| regex_v8                | 15.0 ms                                                     | 14.0 ms: 1.08x faster                                                      |
| meteor_contest          | 73.8 ms                                                     | 68.8 ms: 1.07x faster                                                      |
| comprehensions          | 16.6 us                                                     | 15.5 us: 1.07x faster                                                      |
| xml_etree_parse         | 96.8 ms                                                     | 90.5 ms: 1.07x faster                                                      |
| mdp                     | 1.71 sec                                                    | 1.61 sec: 1.07x faster                                                     |
| python_startup          | 19.7 ms                                                     | 18.5 ms: 1.06x faster                                                      |
| sympy_sum               | 105 ms                                                      | 99.0 ms: 1.06x faster                                                      |
| scimark_fft             | 187 ms                                                      | 177 ms: 1.06x faster                                                       |
| telco                   | 3.82 ms                                                     | 3.64 ms: 1.05x faster                                                      |
| xml_etree_iterparse     | 64.5 ms                                                     | 62.3 ms: 1.04x faster                                                      |
| coroutines              | 15.5 ms                                                     | 15.1 ms: 1.03x faster                                                      |
| unpickle_list           | 2.68 us                                                     | 2.61 us: 1.03x faster                                                      |
| logging_format          | 6.73 us                                                     | 6.64 us: 1.01x faster                                                      |
| regex_effbot            | 1.56 ms                                                     | 1.54 ms: 1.01x faster                                                      |
| pathlib                 | 72.8 ms                                                     | 72.1 ms: 1.01x faster                                                      |
| logging_simple          | 6.28 us                                                     | 6.22 us: 1.01x faster                                                      |
| pickle                  | 6.87 us                                                     | 6.90 us: 1.00x slower                                                      |
| python_startup_no_site  | 15.3 ms                                                     | 15.7 ms: 1.03x slower                                                      |
| pidigits                | 146 ms                                                      | 151 ms: 1.03x slower                                                       |
| gc_traversal            | 1.40 ms                                                     | 1.44 ms: 1.03x slower                                                      |
| bench_mp_pool           | 59.9 ms                                                     | 62.8 ms: 1.05x slower                                                      |
| pickle_list             | 2.69 us                                                     | 2.85 us: 1.06x slower                                                      |
| generators              | 31.8 ms                                                     | 33.9 ms: 1.07x slower                                                      |
| pickle_dict             | 17.1 us                                                     | 19.4 us: 1.13x slower                                                      |
| coverage                | 38.4 ms                                                     | 51.6 ms: 1.35x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.21x faster                                                               |

Benchmark hidden because not significant (1): asyncio_tcp
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.14x
