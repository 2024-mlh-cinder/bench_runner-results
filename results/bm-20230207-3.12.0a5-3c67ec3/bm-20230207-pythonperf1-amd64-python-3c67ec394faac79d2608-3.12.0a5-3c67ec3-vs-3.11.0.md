
# Results vs. 3.11.0

- fork: python
- ref: 3c67ec394faac79d2608
- machine: windows-amd64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.10x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 192 ms: 1.08x faster                                                       |
| chameleon      | 5.35 ms                                                     | 4.41 ms: 1.21x faster                                                      |
| docutils       | 1.59 sec                                                    | 1.50 sec: 1.06x faster                                                     |
| html5lib       | 38.6 ms                                                     | 34.1 ms: 1.13x faster                                                      |
| Geometric mean | (ref)                                                       | 1.09x faster                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none         | 314 ms                                                      | 302 ms: 1.04x faster                                                       |
| async_tree_cpu_io_mixed | 495 ms                                                      | 480 ms: 1.03x faster                                                       |
| async_tree_memoization  | 367 ms                                                      | 356 ms: 1.03x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.03x faster                                                               |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 59.1 ms: 1.17x faster                                                      |
| float          | 54.4 ms                                                     | 47.3 ms: 1.15x faster                                                      |
| pidigits       | 149 ms                                                      | 146 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 78.8 ms: 1.15x faster                                                      |
| regex_effbot   | 1.52 ms                                                     | 1.68 ms: 1.11x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (2): regex_dna, regex_v8

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.38 ms: 1.47x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 120 us: 1.27x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 166 us: 1.25x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 33.5 ms: 1.10x faster                                                      |
| xml_etree_parse      | 94.5 ms                                                     | 88.5 ms: 1.07x faster                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 49.5 ms: 1.06x faster                                                      |
| xml_etree_iterparse  | 63.0 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| pickle_list          | 2.68 us                                                     | 2.70 us: 1.01x slower                                                      |
| unpickle_list        | 2.57 us                                                     | 2.65 us: 1.03x slower                                                      |
| pickle               | 6.53 us                                                     | 6.77 us: 1.04x slower                                                      |
| pickle_dict          | 17.8 us                                                     | 18.5 us: 1.04x slower                                                      |
| json_loads           | 12.9 us                                                     | 14.2 us: 1.10x slower                                                      |
| unpickle             | 7.82 us                                                     | 9.39 us: 1.20x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.05x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| genshi_text     | 17.7 ms                                                     | 14.2 ms: 1.24x faster                                                      |
| genshi_xml      | 40.5 ms                                                     | 32.6 ms: 1.24x faster                                                      |
| mako            | 7.55 ms                                                     | 6.15 ms: 1.23x faster                                                      |
| django_template | 24.0 ms                                                     | 20.2 ms: 1.19x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.23x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence         | 47.0 ns                                                     | 25.6 ns: 1.83x faster                                                      |
| json_dumps              | 7.90 ms                                                     | 5.38 ms: 1.47x faster                                                      |
| deltablue               | 2.63 ms                                                     | 1.96 ms: 1.34x faster                                                      |
| comprehensions          | 15.6 us                                                     | 11.7 us: 1.33x faster                                                      |
| asyncio_tcp             | 614 ms                                                      | 466 ms: 1.32x faster                                                       |
| richards                | 30.8 ms                                                     | 23.9 ms: 1.29x faster                                                      |
| unpickle_pure_python    | 152 us                                                      | 120 us: 1.27x faster                                                       |
| go                      | 98.8 ms                                                     | 78.8 ms: 1.25x faster                                                      |
| pickle_pure_python      | 207 us                                                      | 166 us: 1.25x faster                                                       |
| genshi_text             | 17.7 ms                                                     | 14.2 ms: 1.24x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 32.6 ms: 1.24x faster                                                      |
| raytrace                | 211 ms                                                      | 170 ms: 1.24x faster                                                       |
| mako                    | 7.55 ms                                                     | 6.15 ms: 1.23x faster                                                      |
| logging_silent          | 70.7 ns                                                     | 58.1 ns: 1.22x faster                                                      |
| chameleon               | 5.35 ms                                                     | 4.41 ms: 1.21x faster                                                      |
| hexiom                  | 4.51 ms                                                     | 3.73 ms: 1.21x faster                                                      |
| nqueens                 | 66.1 ms                                                     | 54.6 ms: 1.21x faster                                                      |
| deepcopy_memo           | 25.5 us                                                     | 21.1 us: 1.21x faster                                                      |
| django_template         | 24.0 ms                                                     | 20.2 ms: 1.19x faster                                                      |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.18 ms: 1.19x faster                                                      |
| chaos                   | 46.8 ms                                                     | 39.6 ms: 1.18x faster                                                      |
| scimark_monte_carlo     | 44.6 ms                                                     | 37.9 ms: 1.18x faster                                                      |
| pprint_pformat          | 1.06 sec                                                    | 907 ms: 1.17x faster                                                       |
| nbody                   | 69.3 ms                                                     | 59.1 ms: 1.17x faster                                                      |
| mdp                     | 1.73 sec                                                    | 1.48 sec: 1.17x faster                                                     |
| fannkuch                | 248 ms                                                      | 213 ms: 1.17x faster                                                       |
| pprint_safe_repr        | 519 ms                                                      | 445 ms: 1.17x faster                                                       |
| regex_compile           | 90.8 ms                                                     | 78.8 ms: 1.15x faster                                                      |
| float                   | 54.4 ms                                                     | 47.3 ms: 1.15x faster                                                      |
| deepcopy                | 242 us                                                      | 211 us: 1.15x faster                                                       |
| scimark_sor             | 76.4 ms                                                     | 67.0 ms: 1.14x faster                                                      |
| pyflate                 | 305 ms                                                      | 267 ms: 1.14x faster                                                       |
| spectral_norm           | 69.9 ms                                                     | 61.5 ms: 1.14x faster                                                      |
| html5lib                | 38.6 ms                                                     | 34.1 ms: 1.13x faster                                                      |
| sympy_str               | 184 ms                                                      | 164 ms: 1.13x faster                                                       |
| logging_format          | 7.06 us                                                     | 6.28 us: 1.12x faster                                                      |
| sqlglot_normalize       | 191 ms                                                      | 171 ms: 1.12x faster                                                       |
| sympy_sum               | 100.0 ms                                                    | 89.5 ms: 1.12x faster                                                      |
| pycparser               | 705 ms                                                      | 633 ms: 1.11x faster                                                       |
| sympy_expand            | 299 ms                                                      | 269 ms: 1.11x faster                                                       |
| sqlglot_optimize        | 35.1 ms                                                     | 31.6 ms: 1.11x faster                                                      |
| thrift                  | 501 us                                                      | 452 us: 1.11x faster                                                       |
| sympy_integrate         | 13.7 ms                                                     | 12.4 ms: 1.11x faster                                                      |
| deepcopy_reduce         | 2.07 us                                                     | 1.88 us: 1.11x faster                                                      |
| xml_etree_process       | 37.0 ms                                                     | 33.5 ms: 1.10x faster                                                      |
| sqlglot_parse           | 939 us                                                      | 851 us: 1.10x faster                                                       |
| logging_simple          | 6.60 us                                                     | 6.01 us: 1.10x faster                                                      |
| crypto_pyaes            | 48.2 ms                                                     | 44.0 ms: 1.09x faster                                                      |
| scimark_fft             | 181 ms                                                      | 166 ms: 1.09x faster                                                       |
| sqlglot_transpile       | 1.15 ms                                                     | 1.05 ms: 1.09x faster                                                      |
| mypy2                   | 226 ms                                                      | 208 ms: 1.09x faster                                                       |
| meteor_contest          | 75.0 ms                                                     | 69.1 ms: 1.08x faster                                                      |
| async_generators        | 181 ms                                                      | 167 ms: 1.08x faster                                                       |
| 2to3                    | 207 ms                                                      | 192 ms: 1.08x faster                                                       |
| xml_etree_parse         | 94.5 ms                                                     | 88.5 ms: 1.07x faster                                                      |
| json                    | 2.99 ms                                                     | 2.81 ms: 1.06x faster                                                      |
| scimark_lu              | 62.3 ms                                                     | 58.7 ms: 1.06x faster                                                      |
| docutils                | 1.59 sec                                                    | 1.50 sec: 1.06x faster                                                     |
| telco                   | 3.93 ms                                                     | 3.72 ms: 1.06x faster                                                      |
| xml_etree_generate      | 52.2 ms                                                     | 49.5 ms: 1.06x faster                                                      |
| dulwich_log             | 44.1 ms                                                     | 41.9 ms: 1.05x faster                                                      |
| create_gc_cycles        | 706 us                                                      | 676 us: 1.04x faster                                                       |
| async_tree_none         | 314 ms                                                      | 302 ms: 1.04x faster                                                       |
| python_startup          | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| async_tree_cpu_io_mixed | 495 ms                                                      | 480 ms: 1.03x faster                                                       |
| async_tree_memoization  | 367 ms                                                      | 356 ms: 1.03x faster                                                       |
| bench_thread_pool       | 847 us                                                      | 823 us: 1.03x faster                                                       |
| generators              | 34.0 ms                                                     | 33.0 ms: 1.03x faster                                                      |
| pidigits                | 149 ms                                                      | 146 ms: 1.02x faster                                                       |
| xml_etree_iterparse     | 63.0 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| pickle_list             | 2.68 us                                                     | 2.70 us: 1.01x slower                                                      |
| coroutines              | 14.7 ms                                                     | 14.8 ms: 1.01x slower                                                      |
| bench_mp_pool           | 61.1 ms                                                     | 61.7 ms: 1.01x slower                                                      |
| sqlite_synth            | 1.79 us                                                     | 1.82 us: 1.02x slower                                                      |
| unpickle_list           | 2.57 us                                                     | 2.65 us: 1.03x slower                                                      |
| pickle                  | 6.53 us                                                     | 6.77 us: 1.04x slower                                                      |
| pickle_dict             | 17.8 us                                                     | 18.5 us: 1.04x slower                                                      |
| pathlib                 | 69.4 ms                                                     | 73.7 ms: 1.06x slower                                                      |
| json_loads              | 12.9 us                                                     | 14.2 us: 1.10x slower                                                      |
| regex_effbot            | 1.52 ms                                                     | 1.68 ms: 1.11x slower                                                      |
| unpickle                | 7.82 us                                                     | 9.39 us: 1.20x slower                                                      |
| coverage                | 43.0 ms                                                     | 51.8 ms: 1.21x slower                                                      |
| dask                    | 262 ms                                                      | 349 ms: 1.33x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.10x faster                                                               |

Benchmark hidden because not significant (6): async_tree_io, gc_traversal, python_startup_no_site, regex_dna, regex_v8, tornado_http
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.08x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.06x
