
# Results vs. 3.12.0

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: windows-amd64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.03x slower \*
- HPT reliability: 98.85%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 202 ms: 1.05x faster                                                       |
| chameleon      | 4.95 ms                                                     | 4.99 ms: 1.01x slower                                                      |
| docutils       | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                     |
| tornado_http   | 87.2 ms                                                     | 91.5 ms: 1.05x slower                                                      |
| Geometric mean | (ref)                                                       | 1.00x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 506 ms: 1.06x slower                                                       |
| async_tree_io           | 712 ms                                                      | 775 ms: 1.09x slower                                                       |
| async_tree_none         | 286 ms                                                      | 316 ms: 1.10x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 381 ms: 1.14x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.10x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 67.2 ms: 1.02x faster                                                      |
| float          | 54.7 ms                                                     | 53.5 ms: 1.02x faster                                                      |
| pidigits       | 150 ms                                                      | 148 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 86.3 ms: 1.01x faster                                                      |
| regex_v8       | 13.5 ms                                                     | 13.7 ms: 1.01x slower                                                      |
| regex_effbot   | 1.58 ms                                                     | 1.63 ms: 1.03x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.55 us: 1.13x faster                                                      |
| xml_etree_generate   | 55.8 ms                                                     | 50.5 ms: 1.10x faster                                                      |
| pickle_list          | 2.88 us                                                     | 2.64 us: 1.09x faster                                                      |
| xml_etree_parse      | 90.5 ms                                                     | 86.8 ms: 1.04x faster                                                      |
| pickle_dict          | 18.9 us                                                     | 18.2 us: 1.04x faster                                                      |
| json_dumps           | 5.83 ms                                                     | 5.62 ms: 1.04x faster                                                      |
| unpickle_list        | 2.69 us                                                     | 2.60 us: 1.04x faster                                                      |
| xml_etree_process    | 37.6 ms                                                     | 36.3 ms: 1.04x faster                                                      |
| json_loads           | 13.6 us                                                     | 13.5 us: 1.01x faster                                                      |
| pickle_pure_python   | 195 us                                                      | 196 us: 1.01x slower                                                       |
| xml_etree_iterparse  | 63.1 ms                                                     | 63.6 ms: 1.01x slower                                                      |
| unpickle             | 8.44 us                                                     | 8.87 us: 1.05x slower                                                      |
| unpickle_pure_python | 134 us                                                      | 143 us: 1.07x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.4 ms: 1.04x faster                                                      |
| python_startup         | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.04x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 6.93 ms: 1.02x faster                                                      |
| django_template | 22.8 ms                                                     | 23.8 ms: 1.05x slower                                                      |
| Geometric mean  | (ref)                                                       | 1.01x slower                                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 181 ms: 1.27x faster                                                       |
| pickle                  | 7.38 us                                                     | 6.55 us: 1.13x faster                                                      |
| bench_mp_pool           | 67.2 ms                                                     | 60.9 ms: 1.10x faster                                                      |
| xml_etree_generate      | 55.8 ms                                                     | 50.5 ms: 1.10x faster                                                      |
| create_gc_cycles        | 726 us                                                      | 663 us: 1.10x faster                                                       |
| pickle_list             | 2.88 us                                                     | 2.64 us: 1.09x faster                                                      |
| scimark_sor             | 79.8 ms                                                     | 73.8 ms: 1.08x faster                                                      |
| pathlib                 | 79.6 ms                                                     | 74.0 ms: 1.08x faster                                                      |
| telco                   | 4.08 ms                                                     | 3.85 ms: 1.06x faster                                                      |
| json                    | 2.94 ms                                                     | 2.77 ms: 1.06x faster                                                      |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.37 ms: 1.06x faster                                                      |
| 2to3                    | 213 ms                                                      | 202 ms: 1.05x faster                                                       |
| gc_traversal            | 1.49 ms                                                     | 1.42 ms: 1.05x faster                                                      |
| xml_etree_parse         | 90.5 ms                                                     | 86.8 ms: 1.04x faster                                                      |
| pickle_dict             | 18.9 us                                                     | 18.2 us: 1.04x faster                                                      |
| json_dumps              | 5.83 ms                                                     | 5.62 ms: 1.04x faster                                                      |
| python_startup_no_site  | 15.9 ms                                                     | 15.4 ms: 1.04x faster                                                      |
| pprint_pformat          | 1.04 sec                                                    | 1.00 sec: 1.04x faster                                                     |
| unpickle_list           | 2.69 us                                                     | 2.60 us: 1.04x faster                                                      |
| xml_etree_process       | 37.6 ms                                                     | 36.3 ms: 1.04x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| pprint_safe_repr        | 508 ms                                                      | 495 ms: 1.03x faster                                                       |
| fannkuch                | 244 ms                                                      | 238 ms: 1.03x faster                                                       |
| nbody                   | 68.8 ms                                                     | 67.2 ms: 1.02x faster                                                      |
| float                   | 54.7 ms                                                     | 53.5 ms: 1.02x faster                                                      |
| mako                    | 7.05 ms                                                     | 6.93 ms: 1.02x faster                                                      |
| deepcopy_reduce         | 2.08 us                                                     | 2.05 us: 1.02x faster                                                      |
| pidigits                | 150 ms                                                      | 148 ms: 1.01x faster                                                       |
| regex_compile           | 87.2 ms                                                     | 86.3 ms: 1.01x faster                                                      |
| docutils                | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                     |
| json_loads              | 13.6 us                                                     | 13.5 us: 1.01x faster                                                      |
| meteor_contest          | 72.1 ms                                                     | 71.8 ms: 1.01x faster                                                      |
| pickle_pure_python      | 195 us                                                      | 196 us: 1.01x slower                                                       |
| chameleon               | 4.95 ms                                                     | 4.99 ms: 1.01x slower                                                      |
| xml_etree_iterparse     | 63.1 ms                                                     | 63.6 ms: 1.01x slower                                                      |
| deepcopy                | 233 us                                                      | 235 us: 1.01x slower                                                       |
| pyflate                 | 294 ms                                                      | 297 ms: 1.01x slower                                                       |
| regex_v8                | 13.5 ms                                                     | 13.7 ms: 1.01x slower                                                      |
| sqlglot_optimize        | 34.0 ms                                                     | 34.4 ms: 1.01x slower                                                      |
| crypto_pyaes            | 46.4 ms                                                     | 47.2 ms: 1.02x slower                                                      |
| bench_thread_pool       | 830 us                                                      | 844 us: 1.02x slower                                                       |
| scimark_monte_carlo     | 43.0 ms                                                     | 43.8 ms: 1.02x slower                                                      |
| dulwich_log             | 42.7 ms                                                     | 43.5 ms: 1.02x slower                                                      |
| sqlglot_normalize       | 183 ms                                                      | 188 ms: 1.03x slower                                                       |
| sqlite_synth            | 1.75 us                                                     | 1.80 us: 1.03x slower                                                      |
| sympy_integrate         | 13.0 ms                                                     | 13.4 ms: 1.03x slower                                                      |
| regex_effbot            | 1.58 ms                                                     | 1.63 ms: 1.03x slower                                                      |
| scimark_fft             | 181 ms                                                      | 188 ms: 1.04x slower                                                       |
| dask                    | 255 ms                                                      | 265 ms: 1.04x slower                                                       |
| mypy2                   | 209 ms                                                      | 218 ms: 1.04x slower                                                       |
| django_template         | 22.8 ms                                                     | 23.8 ms: 1.05x slower                                                      |
| tornado_http            | 87.2 ms                                                     | 91.5 ms: 1.05x slower                                                      |
| unpickle                | 8.44 us                                                     | 8.87 us: 1.05x slower                                                      |
| go                      | 89.0 ms                                                     | 93.8 ms: 1.05x slower                                                      |
| deepcopy_memo           | 23.4 us                                                     | 24.7 us: 1.06x slower                                                      |
| raytrace                | 192 ms                                                      | 204 ms: 1.06x slower                                                       |
| async_tree_cpu_io_mixed | 477 ms                                                      | 506 ms: 1.06x slower                                                       |
| nqueens                 | 61.7 ms                                                     | 65.4 ms: 1.06x slower                                                      |
| coroutines              | 14.1 ms                                                     | 15.0 ms: 1.06x slower                                                      |
| sympy_expand            | 278 ms                                                      | 296 ms: 1.06x slower                                                       |
| unpickle_pure_python    | 134 us                                                      | 143 us: 1.07x slower                                                       |
| sympy_str               | 171 ms                                                      | 183 ms: 1.07x slower                                                       |
| pycparser               | 673 ms                                                      | 721 ms: 1.07x slower                                                       |
| logging_format          | 6.72 us                                                     | 7.28 us: 1.08x slower                                                      |
| async_tree_io           | 712 ms                                                      | 775 ms: 1.09x slower                                                       |
| logging_simple          | 6.21 us                                                     | 6.80 us: 1.10x slower                                                      |
| sympy_sum               | 90.1 ms                                                     | 98.9 ms: 1.10x slower                                                      |
| chaos                   | 42.1 ms                                                     | 46.5 ms: 1.10x slower                                                      |
| async_tree_none         | 286 ms                                                      | 316 ms: 1.10x slower                                                       |
| mdp                     | 1.42 sec                                                    | 1.59 sec: 1.12x slower                                                     |
| comprehensions          | 14.0 us                                                     | 15.6 us: 1.12x slower                                                      |
| sqlglot_transpile       | 1.02 ms                                                     | 1.14 ms: 1.12x slower                                                      |
| richards                | 27.6 ms                                                     | 31.0 ms: 1.12x slower                                                      |
| hexiom                  | 4.00 ms                                                     | 4.51 ms: 1.13x slower                                                      |
| logging_silent          | 60.5 ns                                                     | 68.8 ns: 1.14x slower                                                      |
| async_tree_memoization  | 333 ms                                                      | 381 ms: 1.14x slower                                                       |
| unpack_sequence         | 36.9 ns                                                     | 42.3 ns: 1.15x slower                                                      |
| spectral_norm           | 63.9 ms                                                     | 73.8 ms: 1.16x slower                                                      |
| scimark_lu              | 57.5 ms                                                     | 66.6 ms: 1.16x slower                                                      |
| deltablue               | 2.12 ms                                                     | 2.51 ms: 1.18x slower                                                      |
| sqlglot_parse           | 802 us                                                      | 951 us: 1.19x slower                                                       |
| coverage                | 39.8 ms                                                     | 52.1 ms: 1.31x slower                                                      |
| asyncio_tcp             | 471 ms                                                      | 694 ms: 1.47x slower                                                       |
| generators              | 22.6 ms                                                     | 34.5 ms: 1.53x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.03x slower                                                               |

Benchmark hidden because not significant (1): regex_dna
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20221025-3.12.0a1-4ae1a0e/bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e.json: genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 98.85% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
