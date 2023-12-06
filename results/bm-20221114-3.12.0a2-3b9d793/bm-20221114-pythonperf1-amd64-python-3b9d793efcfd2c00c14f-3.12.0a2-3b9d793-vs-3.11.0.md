
# Results vs. 3.11.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: windows-amd64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.07x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 193 ms: 1.07x faster                                                       |
| chameleon      | 5.35 ms                                                     | 4.59 ms: 1.17x faster                                                      |
| docutils       | 1.59 sec                                                    | 1.52 sec: 1.05x faster                                                     |
| html5lib       | 38.6 ms                                                     | 36.4 ms: 1.06x faster                                                      |
| Geometric mean | (ref)                                                       | 1.07x faster                                                               |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 495 ms                                                      | 507 ms: 1.02x slower                                                       |
| async_tree_none         | 314 ms                                                      | 325 ms: 1.04x slower                                                       |
| async_tree_io           | 753 ms                                                      | 783 ms: 1.04x slower                                                       |
| async_tree_memoization  | 367 ms                                                      | 386 ms: 1.05x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.04x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 48.7 ms: 1.12x faster                                                      |
| nbody          | 69.3 ms                                                     | 62.3 ms: 1.11x faster                                                      |
| pidigits       | 149 ms                                                      | 146 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 82.3 ms: 1.10x faster                                                      |
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                                       |
| regex_v8       | 13.7 ms                                                     | 13.8 ms: 1.01x slower                                                      |
| regex_effbot   | 1.52 ms                                                     | 1.70 ms: 1.12x slower                                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.12 ms: 1.54x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 130 us: 1.17x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 180 us: 1.15x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 33.9 ms: 1.09x faster                                                      |
| xml_etree_parse      | 94.5 ms                                                     | 87.6 ms: 1.08x faster                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 49.0 ms: 1.07x faster                                                      |
| xml_etree_iterparse  | 63.0 ms                                                     | 61.3 ms: 1.03x faster                                                      |
| pickle_list          | 2.68 us                                                     | 2.62 us: 1.02x faster                                                      |
| pickle               | 6.53 us                                                     | 6.57 us: 1.01x slower                                                      |
| json_loads           | 12.9 us                                                     | 13.3 us: 1.03x slower                                                      |
| pickle_dict          | 17.8 us                                                     | 18.3 us: 1.03x slower                                                      |
| unpickle             | 7.82 us                                                     | 8.25 us: 1.05x slower                                                      |
| unpickle_list        | 2.57 us                                                     | 2.79 us: 1.09x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| genshi_xml      | 40.5 ms                                                     | 32.2 ms: 1.26x faster                                                      |
| genshi_text     | 17.7 ms                                                     | 14.4 ms: 1.23x faster                                                      |
| mako            | 7.55 ms                                                     | 6.25 ms: 1.21x faster                                                      |
| django_template | 24.0 ms                                                     | 21.6 ms: 1.11x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.20x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps              | 7.90 ms                                                     | 5.12 ms: 1.54x faster                                                      |
| unpack_sequence         | 47.0 ns                                                     | 30.8 ns: 1.52x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 32.2 ms: 1.26x faster                                                      |
| genshi_text             | 17.7 ms                                                     | 14.4 ms: 1.23x faster                                                      |
| mako                    | 7.55 ms                                                     | 6.25 ms: 1.21x faster                                                      |
| logging_silent          | 70.7 ns                                                     | 59.9 ns: 1.18x faster                                                      |
| go                      | 98.8 ms                                                     | 84.0 ms: 1.18x faster                                                      |
| deltablue               | 2.63 ms                                                     | 2.24 ms: 1.17x faster                                                      |
| unpickle_pure_python    | 152 us                                                      | 130 us: 1.17x faster                                                       |
| chameleon               | 5.35 ms                                                     | 4.59 ms: 1.17x faster                                                      |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.25 ms: 1.15x faster                                                      |
| richards                | 30.8 ms                                                     | 26.7 ms: 1.15x faster                                                      |
| pickle_pure_python      | 207 us                                                      | 180 us: 1.15x faster                                                       |
| nqueens                 | 66.1 ms                                                     | 57.5 ms: 1.15x faster                                                      |
| deepcopy_memo           | 25.5 us                                                     | 22.2 us: 1.15x faster                                                      |
| raytrace                | 211 ms                                                      | 184 ms: 1.14x faster                                                       |
| pprint_pformat          | 1.06 sec                                                    | 934 ms: 1.14x faster                                                       |
| pprint_safe_repr        | 519 ms                                                      | 458 ms: 1.13x faster                                                       |
| mdp                     | 1.73 sec                                                    | 1.53 sec: 1.13x faster                                                     |
| hexiom                  | 4.51 ms                                                     | 4.00 ms: 1.13x faster                                                      |
| scimark_monte_carlo     | 44.6 ms                                                     | 39.8 ms: 1.12x faster                                                      |
| pyflate                 | 305 ms                                                      | 272 ms: 1.12x faster                                                       |
| float                   | 54.4 ms                                                     | 48.7 ms: 1.12x faster                                                      |
| deepcopy                | 242 us                                                      | 217 us: 1.12x faster                                                       |
| nbody                   | 69.3 ms                                                     | 62.3 ms: 1.11x faster                                                      |
| django_template         | 24.0 ms                                                     | 21.6 ms: 1.11x faster                                                      |
| deepcopy_reduce         | 2.07 us                                                     | 1.87 us: 1.11x faster                                                      |
| spectral_norm           | 69.9 ms                                                     | 63.1 ms: 1.11x faster                                                      |
| scimark_sor             | 76.4 ms                                                     | 69.2 ms: 1.10x faster                                                      |
| regex_compile           | 90.8 ms                                                     | 82.3 ms: 1.10x faster                                                      |
| sqlglot_normalize       | 191 ms                                                      | 174 ms: 1.10x faster                                                       |
| scimark_lu              | 62.3 ms                                                     | 56.9 ms: 1.09x faster                                                      |
| xml_etree_process       | 37.0 ms                                                     | 33.9 ms: 1.09x faster                                                      |
| fannkuch                | 248 ms                                                      | 227 ms: 1.09x faster                                                       |
| sqlglot_optimize        | 35.1 ms                                                     | 32.1 ms: 1.09x faster                                                      |
| json                    | 2.99 ms                                                     | 2.75 ms: 1.09x faster                                                      |
| sqlglot_parse           | 939 us                                                      | 865 us: 1.09x faster                                                       |
| pycparser               | 705 ms                                                      | 650 ms: 1.08x faster                                                       |
| chaos                   | 46.8 ms                                                     | 43.1 ms: 1.08x faster                                                      |
| meteor_contest          | 75.0 ms                                                     | 69.3 ms: 1.08x faster                                                      |
| xml_etree_parse         | 94.5 ms                                                     | 87.6 ms: 1.08x faster                                                      |
| sqlglot_transpile       | 1.15 ms                                                     | 1.06 ms: 1.08x faster                                                      |
| logging_format          | 7.06 us                                                     | 6.56 us: 1.08x faster                                                      |
| 2to3                    | 207 ms                                                      | 193 ms: 1.07x faster                                                       |
| mypy2                   | 226 ms                                                      | 212 ms: 1.07x faster                                                       |
| scimark_fft             | 181 ms                                                      | 170 ms: 1.07x faster                                                       |
| xml_etree_generate      | 52.2 ms                                                     | 49.0 ms: 1.07x faster                                                      |
| sympy_integrate         | 13.7 ms                                                     | 12.9 ms: 1.06x faster                                                      |
| create_gc_cycles        | 706 us                                                      | 665 us: 1.06x faster                                                       |
| crypto_pyaes            | 48.2 ms                                                     | 45.4 ms: 1.06x faster                                                      |
| sympy_expand            | 299 ms                                                      | 282 ms: 1.06x faster                                                       |
| html5lib                | 38.6 ms                                                     | 36.4 ms: 1.06x faster                                                      |
| sympy_str               | 184 ms                                                      | 175 ms: 1.05x faster                                                       |
| docutils                | 1.59 sec                                                    | 1.52 sec: 1.05x faster                                                     |
| sqlite_synth            | 1.79 us                                                     | 1.71 us: 1.05x faster                                                      |
| logging_simple          | 6.60 us                                                     | 6.31 us: 1.05x faster                                                      |
| async_generators        | 181 ms                                                      | 173 ms: 1.04x faster                                                       |
| sympy_sum               | 100.0 ms                                                    | 96.1 ms: 1.04x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| xml_etree_iterparse     | 63.0 ms                                                     | 61.3 ms: 1.03x faster                                                      |
| pickle_list             | 2.68 us                                                     | 2.62 us: 1.02x faster                                                      |
| dulwich_log             | 44.1 ms                                                     | 43.1 ms: 1.02x faster                                                      |
| dask                    | 262 ms                                                      | 258 ms: 1.02x faster                                                       |
| pidigits                | 149 ms                                                      | 146 ms: 1.02x faster                                                       |
| bench_thread_pool       | 847 us                                                      | 835 us: 1.02x faster                                                       |
| regex_dna               | 121 ms                                                      | 120 ms: 1.01x faster                                                       |
| comprehensions          | 15.6 us                                                     | 15.4 us: 1.01x faster                                                      |
| gc_traversal            | 1.46 ms                                                     | 1.44 ms: 1.01x faster                                                      |
| telco                   | 3.93 ms                                                     | 3.95 ms: 1.00x slower                                                      |
| regex_v8                | 13.7 ms                                                     | 13.8 ms: 1.01x slower                                                      |
| pickle                  | 6.53 us                                                     | 6.57 us: 1.01x slower                                                      |
| coroutines              | 14.7 ms                                                     | 15.0 ms: 1.02x slower                                                      |
| async_tree_cpu_io_mixed | 495 ms                                                      | 507 ms: 1.02x slower                                                       |
| json_loads              | 12.9 us                                                     | 13.3 us: 1.03x slower                                                      |
| pickle_dict             | 17.8 us                                                     | 18.3 us: 1.03x slower                                                      |
| async_tree_none         | 314 ms                                                      | 325 ms: 1.04x slower                                                       |
| async_tree_io           | 753 ms                                                      | 783 ms: 1.04x slower                                                       |
| pathlib                 | 69.4 ms                                                     | 72.6 ms: 1.05x slower                                                      |
| generators              | 34.0 ms                                                     | 35.7 ms: 1.05x slower                                                      |
| async_tree_memoization  | 367 ms                                                      | 386 ms: 1.05x slower                                                       |
| unpickle                | 7.82 us                                                     | 8.25 us: 1.05x slower                                                      |
| unpickle_list           | 2.57 us                                                     | 2.79 us: 1.09x slower                                                      |
| thrift                  | 501 us                                                      | 558 us: 1.11x slower                                                       |
| regex_effbot            | 1.52 ms                                                     | 1.70 ms: 1.12x slower                                                      |
| asyncio_tcp             | 614 ms                                                      | 708 ms: 1.15x slower                                                       |
| coverage                | 43.0 ms                                                     | 52.0 ms: 1.21x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.07x faster                                                               |

Benchmark hidden because not significant (3): python_startup_no_site, tornado_http, bench_mp_pool
Ignored benchmarks (13) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.05x
- 99% likely to have a speedup of 1.04x
