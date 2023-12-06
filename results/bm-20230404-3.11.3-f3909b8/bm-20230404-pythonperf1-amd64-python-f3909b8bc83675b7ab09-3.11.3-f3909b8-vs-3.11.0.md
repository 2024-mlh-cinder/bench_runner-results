
# Results vs. 3.11.0

- fork: python
- ref: f3909b8bc83675b7ab09
- machine: windows-amd64
- commit hash: f3909b8
- commit date: 2023-04-04
- overall geometric mean: 1.00x slower \*
- HPT reliability: 68.33%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| chameleon      | 5.35 ms                                                     | 5.27 ms: 1.02x faster                                                    |
| html5lib       | 38.6 ms                                                     | 39.8 ms: 1.03x slower                                                    |
| Geometric mean | (ref)                                                       | 1.00x slower                                                             |

Benchmark hidden because not significant (3): 2to3, docutils, tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| async_tree_io  | 753 ms                                                      | 739 ms: 1.02x faster                                                     |
| Geometric mean | (ref)                                                       | 1.00x faster                                                             |

Benchmark hidden because not significant (3): async_tree_none, async_tree_memoization, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 52.6 ms: 1.03x faster                                                    |
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                     |
| nbody          | 69.3 ms                                                     | 69.8 ms: 1.01x slower                                                    |
| Geometric mean | (ref)                                                       | 1.01x faster                                                             |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 89.7 ms: 1.01x faster                                                    |
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                                     |
| regex_effbot   | 1.52 ms                                                     | 1.57 ms: 1.03x slower                                                    |
| regex_v8       | 13.7 ms                                                     | 14.3 ms: 1.04x slower                                                    |
| Geometric mean | (ref)                                                       | 1.01x slower                                                             |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| pickle_pure_python   | 207 us                                                      | 198 us: 1.05x faster                                                     |
| json_dumps           | 7.90 ms                                                     | 7.60 ms: 1.04x faster                                                    |
| xml_etree_parse      | 94.5 ms                                                     | 91.3 ms: 1.04x faster                                                    |
| xml_etree_iterparse  | 63.0 ms                                                     | 61.4 ms: 1.03x faster                                                    |
| xml_etree_process    | 37.0 ms                                                     | 36.3 ms: 1.02x faster                                                    |
| unpickle_pure_python | 152 us                                                      | 150 us: 1.02x faster                                                     |
| xml_etree_generate   | 52.2 ms                                                     | 51.8 ms: 1.01x faster                                                    |
| json_loads           | 12.9 us                                                     | 13.0 us: 1.01x slower                                                    |
| unpickle             | 7.82 us                                                     | 7.97 us: 1.02x slower                                                    |
| pickle               | 6.53 us                                                     | 6.73 us: 1.03x slower                                                    |
| pickle_list          | 2.68 us                                                     | 2.78 us: 1.04x slower                                                    |
| unpickle_list        | 2.57 us                                                     | 2.68 us: 1.04x slower                                                    |
| pickle_dict          | 17.8 us                                                     | 18.6 us: 1.05x slower                                                    |
| Geometric mean       | (ref)                                                       | 1.00x faster                                                             |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| python_startup | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                    |
| Geometric mean | (ref)                                                       | 1.02x faster                                                             |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|-----------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| genshi_xml      | 40.5 ms                                                     | 37.6 ms: 1.08x faster                                                    |
| mako            | 7.55 ms                                                     | 7.22 ms: 1.05x faster                                                    |
| genshi_text     | 17.7 ms                                                     | 17.3 ms: 1.02x faster                                                    |
| django_template | 24.0 ms                                                     | 23.8 ms: 1.01x faster                                                    |
| Geometric mean  | (ref)                                                       | 1.04x faster                                                             |

All benchmarks:
===============

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230404-pythonperf1-amd64-python-f3909b8bc83675b7ab09-3.11.3-f3909b8 |
|------------------------|:-----------------------------------------------------------:|:------------------------------------------------------------------------:|
| genshi_xml             | 40.5 ms                                                     | 37.6 ms: 1.08x faster                                                    |
| create_gc_cycles       | 706 us                                                      | 664 us: 1.06x faster                                                     |
| sqlite_synth           | 1.79 us                                                     | 1.69 us: 1.06x faster                                                    |
| sqlalchemy_imperative  | 10.5 ms                                                     | 10.0 ms: 1.05x faster                                                    |
| pickle_pure_python     | 207 us                                                      | 198 us: 1.05x faster                                                     |
| mako                   | 7.55 ms                                                     | 7.22 ms: 1.05x faster                                                    |
| thrift                 | 501 us                                                      | 482 us: 1.04x faster                                                     |
| json_dumps             | 7.90 ms                                                     | 7.60 ms: 1.04x faster                                                    |
| raytrace               | 211 ms                                                      | 203 ms: 1.04x faster                                                     |
| dulwich_log            | 44.1 ms                                                     | 42.5 ms: 1.04x faster                                                    |
| xml_etree_parse        | 94.5 ms                                                     | 91.3 ms: 1.04x faster                                                    |
| float                  | 54.4 ms                                                     | 52.6 ms: 1.03x faster                                                    |
| spectral_norm          | 69.9 ms                                                     | 67.6 ms: 1.03x faster                                                    |
| sqlalchemy_declarative | 83.9 ms                                                     | 81.1 ms: 1.03x faster                                                    |
| sympy_expand           | 299 ms                                                      | 290 ms: 1.03x faster                                                     |
| async_generators       | 181 ms                                                      | 176 ms: 1.03x faster                                                     |
| xml_etree_iterparse    | 63.0 ms                                                     | 61.4 ms: 1.03x faster                                                    |
| deepcopy_memo          | 25.5 us                                                     | 24.8 us: 1.02x faster                                                    |
| python_startup         | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                    |
| unpack_sequence        | 47.0 ns                                                     | 46.0 ns: 1.02x faster                                                    |
| gc_traversal           | 1.46 ms                                                     | 1.43 ms: 1.02x faster                                                    |
| async_tree_io          | 753 ms                                                      | 739 ms: 1.02x faster                                                     |
| xml_etree_process      | 37.0 ms                                                     | 36.3 ms: 1.02x faster                                                    |
| genshi_text            | 17.7 ms                                                     | 17.3 ms: 1.02x faster                                                    |
| deepcopy_reduce        | 2.07 us                                                     | 2.04 us: 1.02x faster                                                    |
| unpickle_pure_python   | 152 us                                                      | 150 us: 1.02x faster                                                     |
| sympy_sum              | 100.0 ms                                                    | 98.4 ms: 1.02x faster                                                    |
| chameleon              | 5.35 ms                                                     | 5.27 ms: 1.02x faster                                                    |
| scimark_sor            | 76.4 ms                                                     | 75.2 ms: 1.02x faster                                                    |
| comprehensions         | 15.6 us                                                     | 15.4 us: 1.01x faster                                                    |
| richards               | 30.8 ms                                                     | 30.4 ms: 1.01x faster                                                    |
| regex_compile          | 90.8 ms                                                     | 89.7 ms: 1.01x faster                                                    |
| sympy_str              | 184 ms                                                      | 182 ms: 1.01x faster                                                     |
| sqlglot_transpile      | 1.15 ms                                                     | 1.13 ms: 1.01x faster                                                    |
| pyflate                | 305 ms                                                      | 301 ms: 1.01x faster                                                     |
| sqlglot_optimize       | 35.1 ms                                                     | 34.7 ms: 1.01x faster                                                    |
| pidigits               | 149 ms                                                      | 147 ms: 1.01x faster                                                     |
| logging_format         | 7.06 us                                                     | 6.99 us: 1.01x faster                                                    |
| sqlglot_parse          | 939 us                                                      | 931 us: 1.01x faster                                                     |
| regex_dna              | 121 ms                                                      | 120 ms: 1.01x faster                                                     |
| xml_etree_generate     | 52.2 ms                                                     | 51.8 ms: 1.01x faster                                                    |
| django_template        | 24.0 ms                                                     | 23.8 ms: 1.01x faster                                                    |
| logging_silent         | 70.7 ns                                                     | 70.1 ns: 1.01x faster                                                    |
| nqueens                | 66.1 ms                                                     | 65.6 ms: 1.01x faster                                                    |
| sympy_integrate        | 13.7 ms                                                     | 13.6 ms: 1.01x faster                                                    |
| meteor_contest         | 75.0 ms                                                     | 74.7 ms: 1.00x faster                                                    |
| json_loads             | 12.9 us                                                     | 13.0 us: 1.01x slower                                                    |
| nbody                  | 69.3 ms                                                     | 69.8 ms: 1.01x slower                                                    |
| flaskblogging          | 2.03 sec                                                    | 2.05 sec: 1.01x slower                                                   |
| mdp                    | 1.73 sec                                                    | 1.74 sec: 1.01x slower                                                   |
| deltablue              | 2.63 ms                                                     | 2.65 ms: 1.01x slower                                                    |
| logging_simple         | 6.60 us                                                     | 6.67 us: 1.01x slower                                                    |
| hexiom                 | 4.51 ms                                                     | 4.56 ms: 1.01x slower                                                    |
| scimark_monte_carlo    | 44.6 ms                                                     | 45.1 ms: 1.01x slower                                                    |
| pprint_safe_repr       | 519 ms                                                      | 526 ms: 1.01x slower                                                     |
| bench_mp_pool          | 61.1 ms                                                     | 62.0 ms: 1.02x slower                                                    |
| scimark_lu             | 62.3 ms                                                     | 63.3 ms: 1.02x slower                                                    |
| scimark_fft            | 181 ms                                                      | 185 ms: 1.02x slower                                                     |
| unpickle               | 7.82 us                                                     | 7.97 us: 1.02x slower                                                    |
| telco                  | 3.93 ms                                                     | 4.02 ms: 1.02x slower                                                    |
| pickle                 | 6.53 us                                                     | 6.73 us: 1.03x slower                                                    |
| fannkuch               | 248 ms                                                      | 256 ms: 1.03x slower                                                     |
| html5lib               | 38.6 ms                                                     | 39.8 ms: 1.03x slower                                                    |
| coroutines             | 14.7 ms                                                     | 15.1 ms: 1.03x slower                                                    |
| regex_effbot           | 1.52 ms                                                     | 1.57 ms: 1.03x slower                                                    |
| pickle_list            | 2.68 us                                                     | 2.78 us: 1.04x slower                                                    |
| regex_v8               | 13.7 ms                                                     | 14.3 ms: 1.04x slower                                                    |
| unpickle_list          | 2.57 us                                                     | 2.68 us: 1.04x slower                                                    |
| chaos                  | 46.8 ms                                                     | 48.9 ms: 1.05x slower                                                    |
| pickle_dict            | 17.8 us                                                     | 18.6 us: 1.05x slower                                                    |
| pathlib                | 69.4 ms                                                     | 73.2 ms: 1.06x slower                                                    |
| json                   | 2.99 ms                                                     | 3.25 ms: 1.09x slower                                                    |
| asyncio_tcp            | 614 ms                                                      | 718 ms: 1.17x slower                                                     |
| mypy2                  | 226 ms                                                      | 280 ms: 1.24x slower                                                     |
| coverage               | 43.0 ms                                                     | 53.2 ms: 1.24x slower                                                    |
| Geometric mean         | (ref)                                                       | 1.00x slower                                                             |

Benchmark hidden because not significant (19): python_startup_no_site, dask, 2to3, docutils, scimark_sparse_mat_mult, pycparser, pprint_pformat, sqlglot_normalize, bench_thread_pool, generators, crypto_pyaes, deepcopy, tornado_http, async_tree_none, async_tree_memoization, go, aiohttp, async_tree_cpu_io_mixed, pylint
Ignored benchmarks (8) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 68.33% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
