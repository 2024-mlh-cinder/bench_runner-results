
# Results vs. 3.11.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: windows-amd64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.08x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 210 ms: 1.01x slower                                                       |
| chameleon      | 5.35 ms                                                     | 5.53 ms: 1.03x slower                                                      |
| docutils       | 1.59 sec                                                    | 1.67 sec: 1.05x slower                                                     |
| html5lib       | 38.6 ms                                                     | 41.4 ms: 1.07x slower                                                      |
| tornado_http   | 89.9 ms                                                     | 98.3 ms: 1.09x slower                                                      |
| Geometric mean | (ref)                                                       | 1.05x slower                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none         | 314 ms                                                      | 307 ms: 1.02x faster                                                       |
| async_tree_io           | 753 ms                                                      | 793 ms: 1.05x slower                                                       |
| async_tree_cpu_io_mixed | 495 ms                                                      | 530 ms: 1.07x slower                                                       |
| async_tree_memoization  | 367 ms                                                      | 395 ms: 1.08x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.04x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 148 ms: 1.01x faster                                                       |
| float          | 54.4 ms                                                     | 56.1 ms: 1.03x slower                                                      |
| nbody          | 69.3 ms                                                     | 90.3 ms: 1.30x slower                                                      |
| Geometric mean | (ref)                                                       | 1.10x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 90.4 ms: 1.00x faster                                                      |
| regex_dna      | 121 ms                                                      | 131 ms: 1.08x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.82 ms: 1.20x slower                                                      |
| regex_v8       | 13.7 ms                                                     | 16.6 ms: 1.21x slower                                                      |
| Geometric mean | (ref)                                                       | 1.12x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict          | 17.8 us                                                     | 16.2 us: 1.09x faster                                                      |
| pickle_list          | 2.68 us                                                     | 2.49 us: 1.08x faster                                                      |
| unpickle_list        | 2.57 us                                                     | 2.54 us: 1.01x faster                                                      |
| pickle               | 6.53 us                                                     | 6.61 us: 1.01x slower                                                      |
| xml_etree_iterparse  | 63.0 ms                                                     | 65.2 ms: 1.03x slower                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 54.7 ms: 1.05x slower                                                      |
| xml_etree_process    | 37.0 ms                                                     | 39.7 ms: 1.07x slower                                                      |
| pickle_pure_python   | 207 us                                                      | 228 us: 1.10x slower                                                       |
| unpickle_pure_python | 152 us                                                      | 168 us: 1.10x slower                                                       |
| json_loads           | 12.9 us                                                     | 14.9 us: 1.16x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (3): xml_etree_parse, unpickle, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.5 ms                                                     | 15.1 ms: 1.03x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| genshi_xml      | 40.5 ms                                                     | 38.5 ms: 1.05x faster                                                      |
| genshi_text     | 17.7 ms                                                     | 17.5 ms: 1.01x faster                                                      |
| mako            | 7.55 ms                                                     | 8.07 ms: 1.07x slower                                                      |
| django_template | 24.0 ms                                                     | 26.0 ms: 1.08x slower                                                      |
| Geometric mean  | (ref)                                                       | 1.02x slower                                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| logging_simple          | 6.60 us                                                     | 5.45 us: 1.21x faster                                                      |
| logging_format          | 7.06 us                                                     | 5.92 us: 1.19x faster                                                      |
| generators              | 34.0 ms                                                     | 31.0 ms: 1.10x faster                                                      |
| pickle_dict             | 17.8 us                                                     | 16.2 us: 1.09x faster                                                      |
| pickle_list             | 2.68 us                                                     | 2.49 us: 1.08x faster                                                      |
| mdp                     | 1.73 sec                                                    | 1.61 sec: 1.07x faster                                                     |
| gc_traversal            | 1.46 ms                                                     | 1.37 ms: 1.06x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 38.5 ms: 1.05x faster                                                      |
| python_startup_no_site  | 15.5 ms                                                     | 15.1 ms: 1.03x faster                                                      |
| create_gc_cycles        | 706 us                                                      | 686 us: 1.03x faster                                                       |
| async_tree_none         | 314 ms                                                      | 307 ms: 1.02x faster                                                       |
| unpickle_list           | 2.57 us                                                     | 2.54 us: 1.01x faster                                                      |
| genshi_text             | 17.7 ms                                                     | 17.5 ms: 1.01x faster                                                      |
| telco                   | 3.93 ms                                                     | 3.91 ms: 1.01x faster                                                      |
| pidigits                | 149 ms                                                      | 148 ms: 1.01x faster                                                       |
| regex_compile           | 90.8 ms                                                     | 90.4 ms: 1.00x faster                                                      |
| flaskblogging           | 2.03 sec                                                    | 2.05 sec: 1.01x slower                                                     |
| sqlalchemy_imperative   | 10.5 ms                                                     | 10.6 ms: 1.01x slower                                                      |
| pickle                  | 6.53 us                                                     | 6.61 us: 1.01x slower                                                      |
| 2to3                    | 207 ms                                                      | 210 ms: 1.01x slower                                                       |
| raytrace                | 211 ms                                                      | 214 ms: 1.01x slower                                                       |
| meteor_contest          | 75.0 ms                                                     | 76.2 ms: 1.02x slower                                                      |
| sympy_sum               | 100.0 ms                                                    | 102 ms: 1.02x slower                                                       |
| nqueens                 | 66.1 ms                                                     | 67.3 ms: 1.02x slower                                                      |
| logging_silent          | 70.7 ns                                                     | 72.1 ns: 1.02x slower                                                      |
| sqlglot_normalize       | 191 ms                                                      | 196 ms: 1.03x slower                                                       |
| float                   | 54.4 ms                                                     | 56.1 ms: 1.03x slower                                                      |
| chameleon               | 5.35 ms                                                     | 5.53 ms: 1.03x slower                                                      |
| xml_etree_iterparse     | 63.0 ms                                                     | 65.2 ms: 1.03x slower                                                      |
| sympy_str               | 184 ms                                                      | 191 ms: 1.04x slower                                                       |
| sympy_expand            | 299 ms                                                      | 311 ms: 1.04x slower                                                       |
| xml_etree_generate      | 52.2 ms                                                     | 54.7 ms: 1.05x slower                                                      |
| sympy_integrate         | 13.7 ms                                                     | 14.4 ms: 1.05x slower                                                      |
| docutils                | 1.59 sec                                                    | 1.67 sec: 1.05x slower                                                     |
| async_tree_io           | 753 ms                                                      | 793 ms: 1.05x slower                                                       |
| thrift                  | 501 us                                                      | 528 us: 1.05x slower                                                       |
| pprint_safe_repr        | 519 ms                                                      | 547 ms: 1.05x slower                                                       |
| sqlalchemy_declarative  | 83.9 ms                                                     | 88.5 ms: 1.06x slower                                                      |
| pathlib                 | 69.4 ms                                                     | 73.4 ms: 1.06x slower                                                      |
| pprint_pformat          | 1.06 sec                                                    | 1.13 sec: 1.06x slower                                                     |
| async_generators        | 181 ms                                                      | 192 ms: 1.06x slower                                                       |
| mako                    | 7.55 ms                                                     | 8.07 ms: 1.07x slower                                                      |
| sqlglot_optimize        | 35.1 ms                                                     | 37.5 ms: 1.07x slower                                                      |
| bench_thread_pool       | 847 us                                                      | 906 us: 1.07x slower                                                       |
| async_tree_cpu_io_mixed | 495 ms                                                      | 530 ms: 1.07x slower                                                       |
| xml_etree_process       | 37.0 ms                                                     | 39.7 ms: 1.07x slower                                                      |
| html5lib                | 38.6 ms                                                     | 41.4 ms: 1.07x slower                                                      |
| go                      | 98.8 ms                                                     | 106 ms: 1.08x slower                                                       |
| deepcopy_reduce         | 2.07 us                                                     | 2.23 us: 1.08x slower                                                      |
| async_tree_memoization  | 367 ms                                                      | 395 ms: 1.08x slower                                                       |
| regex_dna               | 121 ms                                                      | 131 ms: 1.08x slower                                                       |
| django_template         | 24.0 ms                                                     | 26.0 ms: 1.08x slower                                                      |
| deltablue               | 2.63 ms                                                     | 2.86 ms: 1.09x slower                                                      |
| pycparser               | 705 ms                                                      | 769 ms: 1.09x slower                                                       |
| tornado_http            | 89.9 ms                                                     | 98.3 ms: 1.09x slower                                                      |
| deepcopy                | 242 us                                                      | 266 us: 1.10x slower                                                       |
| pickle_pure_python      | 207 us                                                      | 228 us: 1.10x slower                                                       |
| unpickle_pure_python    | 152 us                                                      | 168 us: 1.10x slower                                                       |
| richards                | 30.8 ms                                                     | 34.0 ms: 1.10x slower                                                      |
| deepcopy_memo           | 25.5 us                                                     | 28.1 us: 1.10x slower                                                      |
| unpack_sequence         | 47.0 ns                                                     | 51.9 ns: 1.11x slower                                                      |
| fannkuch                | 248 ms                                                      | 275 ms: 1.11x slower                                                       |
| hexiom                  | 4.51 ms                                                     | 5.06 ms: 1.12x slower                                                      |
| dask                    | 262 ms                                                      | 295 ms: 1.12x slower                                                       |
| asyncio_tcp             | 614 ms                                                      | 695 ms: 1.13x slower                                                       |
| chaos                   | 46.8 ms                                                     | 53.9 ms: 1.15x slower                                                      |
| json_loads              | 12.9 us                                                     | 14.9 us: 1.16x slower                                                      |
| scimark_monte_carlo     | 44.6 ms                                                     | 51.7 ms: 1.16x slower                                                      |
| scimark_fft             | 181 ms                                                      | 212 ms: 1.17x slower                                                       |
| pyflate                 | 305 ms                                                      | 358 ms: 1.17x slower                                                       |
| spectral_norm           | 69.9 ms                                                     | 82.7 ms: 1.18x slower                                                      |
| regex_effbot            | 1.52 ms                                                     | 1.82 ms: 1.20x slower                                                      |
| regex_v8                | 13.7 ms                                                     | 16.6 ms: 1.21x slower                                                      |
| crypto_pyaes            | 48.2 ms                                                     | 58.9 ms: 1.22x slower                                                      |
| comprehensions          | 15.6 us                                                     | 19.1 us: 1.23x slower                                                      |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 3.18 ms: 1.23x slower                                                      |
| coroutines              | 14.7 ms                                                     | 18.1 ms: 1.23x slower                                                      |
| nbody                   | 69.3 ms                                                     | 90.3 ms: 1.30x slower                                                      |
| sqlglot_transpile       | 1.15 ms                                                     | 1.50 ms: 1.30x slower                                                      |
| scimark_lu              | 62.3 ms                                                     | 81.5 ms: 1.31x slower                                                      |
| scimark_sor             | 76.4 ms                                                     | 101 ms: 1.33x slower                                                       |
| sqlglot_parse           | 939 us                                                      | 1.29 ms: 1.38x slower                                                      |
| coverage                | 43.0 ms                                                     | 262 ms: 6.09x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.08x slower                                                               |

Benchmark hidden because not significant (9): xml_etree_parse, unpickle, dulwich_log, python_startup, sqlite_synth, json_dumps, bench_mp_pool, pylint, json
Ignored benchmarks (10) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, mypy2, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
