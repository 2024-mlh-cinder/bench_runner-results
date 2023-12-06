
# Results vs. 3.11.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: windows-amd64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.01x faster \*
- HPT reliability: 99.14%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 202 ms: 1.03x faster                                                       |
| chameleon      | 5.35 ms                                                     | 4.99 ms: 1.07x faster                                                      |
| html5lib       | 38.6 ms                                                     | 38.1 ms: 1.01x faster                                                      |
| tornado_http   | 89.9 ms                                                     | 91.5 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmark hidden because not significant (1): docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 495 ms                                                      | 506 ms: 1.02x slower                                                       |
| async_tree_io           | 753 ms                                                      | 775 ms: 1.03x slower                                                       |
| async_tree_memoization  | 367 ms                                                      | 381 ms: 1.04x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (1): async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 67.2 ms: 1.03x faster                                                      |
| float          | 54.4 ms                                                     | 53.5 ms: 1.02x faster                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 86.3 ms: 1.05x faster                                                      |
| regex_dna      | 121 ms                                                      | 119 ms: 1.02x faster                                                       |
| regex_v8       | 13.7 ms                                                     | 13.7 ms: 1.00x faster                                                      |
| regex_effbot   | 1.52 ms                                                     | 1.63 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.62 ms: 1.41x faster                                                      |
| xml_etree_parse      | 94.5 ms                                                     | 86.8 ms: 1.09x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 143 us: 1.07x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 196 us: 1.06x faster                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 50.5 ms: 1.03x faster                                                      |
| xml_etree_process    | 37.0 ms                                                     | 36.3 ms: 1.02x faster                                                      |
| pickle_list          | 2.68 us                                                     | 2.64 us: 1.02x faster                                                      |
| unpickle_list        | 2.57 us                                                     | 2.60 us: 1.01x slower                                                      |
| pickle_dict          | 17.8 us                                                     | 18.2 us: 1.02x slower                                                      |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                      |
| unpickle             | 7.82 us                                                     | 8.87 us: 1.13x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                               |

Benchmark hidden because not significant (2): pickle, xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 15.4 ms: 1.01x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 7.55 ms                                                     | 6.93 ms: 1.09x faster                                                      |
| genshi_xml      | 40.5 ms                                                     | 37.8 ms: 1.07x faster                                                      |
| genshi_text     | 17.7 ms                                                     | 17.1 ms: 1.04x faster                                                      |
| django_template | 24.0 ms                                                     | 23.8 ms: 1.01x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.05x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps              | 7.90 ms                                                     | 5.62 ms: 1.41x faster                                                      |
| unpack_sequence         | 47.0 ns                                                     | 42.3 ns: 1.11x faster                                                      |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.37 ms: 1.09x faster                                                      |
| mako                    | 7.55 ms                                                     | 6.93 ms: 1.09x faster                                                      |
| xml_etree_parse         | 94.5 ms                                                     | 86.8 ms: 1.09x faster                                                      |
| mdp                     | 1.73 sec                                                    | 1.59 sec: 1.09x faster                                                     |
| json                    | 2.99 ms                                                     | 2.77 ms: 1.08x faster                                                      |
| chameleon               | 5.35 ms                                                     | 4.99 ms: 1.07x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 37.8 ms: 1.07x faster                                                      |
| unpickle_pure_python    | 152 us                                                      | 143 us: 1.07x faster                                                       |
| create_gc_cycles        | 706 us                                                      | 663 us: 1.06x faster                                                       |
| pprint_pformat          | 1.06 sec                                                    | 1.00 sec: 1.06x faster                                                     |
| pickle_pure_python      | 207 us                                                      | 196 us: 1.06x faster                                                       |
| go                      | 98.8 ms                                                     | 93.8 ms: 1.05x faster                                                      |
| regex_compile           | 90.8 ms                                                     | 86.3 ms: 1.05x faster                                                      |
| pprint_safe_repr        | 519 ms                                                      | 495 ms: 1.05x faster                                                       |
| deltablue               | 2.63 ms                                                     | 2.51 ms: 1.05x faster                                                      |
| meteor_contest          | 75.0 ms                                                     | 71.8 ms: 1.04x faster                                                      |
| fannkuch                | 248 ms                                                      | 238 ms: 1.04x faster                                                       |
| mypy2                   | 226 ms                                                      | 218 ms: 1.04x faster                                                       |
| genshi_text             | 17.7 ms                                                     | 17.1 ms: 1.04x faster                                                      |
| scimark_sor             | 76.4 ms                                                     | 73.8 ms: 1.04x faster                                                      |
| raytrace                | 211 ms                                                      | 204 ms: 1.04x faster                                                       |
| xml_etree_generate      | 52.2 ms                                                     | 50.5 ms: 1.03x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| deepcopy                | 242 us                                                      | 235 us: 1.03x faster                                                       |
| nbody                   | 69.3 ms                                                     | 67.2 ms: 1.03x faster                                                      |
| thrift                  | 501 us                                                      | 486 us: 1.03x faster                                                       |
| deepcopy_memo           | 25.5 us                                                     | 24.7 us: 1.03x faster                                                      |
| 2to3                    | 207 ms                                                      | 202 ms: 1.03x faster                                                       |
| logging_silent          | 70.7 ns                                                     | 68.8 ns: 1.03x faster                                                      |
| pyflate                 | 305 ms                                                      | 297 ms: 1.03x faster                                                       |
| sympy_integrate         | 13.7 ms                                                     | 13.4 ms: 1.03x faster                                                      |
| gc_traversal            | 1.46 ms                                                     | 1.42 ms: 1.02x faster                                                      |
| telco                   | 3.93 ms                                                     | 3.85 ms: 1.02x faster                                                      |
| crypto_pyaes            | 48.2 ms                                                     | 47.2 ms: 1.02x faster                                                      |
| xml_etree_process       | 37.0 ms                                                     | 36.3 ms: 1.02x faster                                                      |
| sqlglot_optimize        | 35.1 ms                                                     | 34.4 ms: 1.02x faster                                                      |
| scimark_monte_carlo     | 44.6 ms                                                     | 43.8 ms: 1.02x faster                                                      |
| regex_dna               | 121 ms                                                      | 119 ms: 1.02x faster                                                       |
| float                   | 54.4 ms                                                     | 53.5 ms: 1.02x faster                                                      |
| pickle_list             | 2.68 us                                                     | 2.64 us: 1.02x faster                                                      |
| sqlglot_normalize       | 191 ms                                                      | 188 ms: 1.02x faster                                                       |
| dulwich_log             | 44.1 ms                                                     | 43.5 ms: 1.01x faster                                                      |
| html5lib                | 38.6 ms                                                     | 38.1 ms: 1.01x faster                                                      |
| deepcopy_reduce         | 2.07 us                                                     | 2.05 us: 1.01x faster                                                      |
| sympy_sum               | 100.0 ms                                                    | 98.9 ms: 1.01x faster                                                      |
| sympy_expand            | 299 ms                                                      | 296 ms: 1.01x faster                                                       |
| nqueens                 | 66.1 ms                                                     | 65.4 ms: 1.01x faster                                                      |
| python_startup_no_site  | 15.5 ms                                                     | 15.4 ms: 1.01x faster                                                      |
| django_template         | 24.0 ms                                                     | 23.8 ms: 1.01x faster                                                      |
| sqlglot_transpile       | 1.15 ms                                                     | 1.14 ms: 1.01x faster                                                      |
| chaos                   | 46.8 ms                                                     | 46.5 ms: 1.01x faster                                                      |
| sympy_str               | 184 ms                                                      | 183 ms: 1.01x faster                                                       |
| regex_v8                | 13.7 ms                                                     | 13.7 ms: 1.00x faster                                                      |
| richards                | 30.8 ms                                                     | 31.0 ms: 1.01x slower                                                      |
| sqlglot_parse           | 939 us                                                      | 951 us: 1.01x slower                                                       |
| unpickle_list           | 2.57 us                                                     | 2.60 us: 1.01x slower                                                      |
| generators              | 34.0 ms                                                     | 34.5 ms: 1.02x slower                                                      |
| tornado_http            | 89.9 ms                                                     | 91.5 ms: 1.02x slower                                                      |
| async_tree_cpu_io_mixed | 495 ms                                                      | 506 ms: 1.02x slower                                                       |
| coroutines              | 14.7 ms                                                     | 15.0 ms: 1.02x slower                                                      |
| pickle_dict             | 17.8 us                                                     | 18.2 us: 1.02x slower                                                      |
| async_tree_io           | 753 ms                                                      | 775 ms: 1.03x slower                                                       |
| logging_simple          | 6.60 us                                                     | 6.80 us: 1.03x slower                                                      |
| logging_format          | 7.06 us                                                     | 7.28 us: 1.03x slower                                                      |
| scimark_fft             | 181 ms                                                      | 188 ms: 1.03x slower                                                       |
| async_tree_memoization  | 367 ms                                                      | 381 ms: 1.04x slower                                                       |
| json_loads              | 12.9 us                                                     | 13.5 us: 1.05x slower                                                      |
| spectral_norm           | 69.9 ms                                                     | 73.8 ms: 1.06x slower                                                      |
| pathlib                 | 69.4 ms                                                     | 74.0 ms: 1.07x slower                                                      |
| scimark_lu              | 62.3 ms                                                     | 66.6 ms: 1.07x slower                                                      |
| regex_effbot            | 1.52 ms                                                     | 1.63 ms: 1.08x slower                                                      |
| asyncio_tcp             | 614 ms                                                      | 694 ms: 1.13x slower                                                       |
| unpickle                | 7.82 us                                                     | 8.87 us: 1.13x slower                                                      |
| coverage                | 43.0 ms                                                     | 52.1 ms: 1.21x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (14): bench_thread_pool, bench_mp_pool, pidigits, pylint, hexiom, sqlite_synth, docutils, pickle, async_generators, comprehensions, async_tree_none, dask, xml_etree_iterparse, pycparser
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, flaskblogging, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 99.14% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
