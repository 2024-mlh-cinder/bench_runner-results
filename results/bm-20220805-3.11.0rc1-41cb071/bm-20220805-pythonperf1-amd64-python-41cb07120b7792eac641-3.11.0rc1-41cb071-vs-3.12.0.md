
# Results vs. 3.12.0

- fork: python
- ref: 41cb07120b7792eac641
- machine: windows-amd64
- commit hash: 41cb071
- commit date: 2022-08-05
- overall geometric mean: 1.04x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 202 ms: 1.05x faster                                                        |
| chameleon      | 4.95 ms                                                     | 5.05 ms: 1.02x slower                                                       |
| docutils       | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                      |
| tornado_http   | 87.2 ms                                                     | 90.9 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 491 ms: 1.03x slower                                                        |
| async_tree_io           | 712 ms                                                      | 739 ms: 1.04x slower                                                        |
| async_tree_none         | 286 ms                                                      | 310 ms: 1.08x slower                                                        |
| async_tree_memoization  | 333 ms                                                      | 368 ms: 1.11x slower                                                        |
| Geometric mean          | (ref)                                                       | 1.06x slower                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 52.9 ms: 1.03x faster                                                       |
| pidigits       | 150 ms                                                      | 146 ms: 1.03x faster                                                        |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 89.4 ms: 1.02x slower                                                       |
| regex_dna      | 119 ms                                                      | 123 ms: 1.03x slower                                                        |
| regex_v8       | 13.5 ms                                                     | 14.1 ms: 1.04x slower                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.66 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.04x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.44 us: 1.15x faster                                                       |
| pickle_list          | 2.88 us                                                     | 2.57 us: 1.12x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 52.6 ms: 1.06x faster                                                       |
| unpickle             | 8.44 us                                                     | 8.11 us: 1.04x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 36.7 ms: 1.02x faster                                                       |
| unpickle_list        | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| json_loads           | 13.6 us                                                     | 14.0 us: 1.03x slower                                                       |
| pickle_pure_python   | 195 us                                                      | 202 us: 1.04x slower                                                        |
| xml_etree_parse      | 90.5 ms                                                     | 94.8 ms: 1.05x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 150 us: 1.12x slower                                                        |
| json_dumps           | 5.83 ms                                                     | 7.73 ms: 1.33x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.2 ms: 1.05x faster                                                       |
| python_startup         | 18.8 ms                                                     | 18.4 ms: 1.03x faster                                                       |
| Geometric mean         | (ref)                                                       | 1.04x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 7.26 ms: 1.03x slower                                                       |
| django_template | 22.8 ms                                                     | 23.7 ms: 1.04x slower                                                       |
| Geometric mean  | (ref)                                                       | 1.04x slower                                                                |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 176 ms: 1.31x faster                                                        |
| pickle                  | 7.38 us                                                     | 6.44 us: 1.15x faster                                                       |
| pickle_list             | 2.88 us                                                     | 2.57 us: 1.12x faster                                                       |
| pathlib                 | 79.6 ms                                                     | 72.6 ms: 1.10x faster                                                       |
| bench_mp_pool           | 67.2 ms                                                     | 61.4 ms: 1.10x faster                                                       |
| create_gc_cycles        | 726 us                                                      | 665 us: 1.09x faster                                                        |
| gc_traversal            | 1.49 ms                                                     | 1.40 ms: 1.06x faster                                                       |
| xml_etree_generate      | 55.8 ms                                                     | 52.6 ms: 1.06x faster                                                       |
| telco                   | 4.08 ms                                                     | 3.87 ms: 1.06x faster                                                       |
| 2to3                    | 213 ms                                                      | 202 ms: 1.05x faster                                                        |
| python_startup_no_site  | 15.9 ms                                                     | 15.2 ms: 1.05x faster                                                       |
| sqlite_synth            | 1.75 us                                                     | 1.68 us: 1.04x faster                                                       |
| unpickle                | 8.44 us                                                     | 8.11 us: 1.04x faster                                                       |
| float                   | 54.7 ms                                                     | 52.9 ms: 1.03x faster                                                       |
| scimark_sor             | 79.8 ms                                                     | 77.3 ms: 1.03x faster                                                       |
| pickle_dict             | 18.9 us                                                     | 18.4 us: 1.03x faster                                                       |
| pidigits                | 150 ms                                                      | 146 ms: 1.03x faster                                                        |
| python_startup          | 18.8 ms                                                     | 18.4 ms: 1.03x faster                                                       |
| xml_etree_process       | 37.6 ms                                                     | 36.7 ms: 1.02x faster                                                       |
| unpickle_list           | 2.69 us                                                     | 2.64 us: 1.02x faster                                                       |
| deepcopy_reduce         | 2.08 us                                                     | 2.05 us: 1.02x faster                                                       |
| sqlalchemy_declarative  | 84.5 ms                                                     | 83.4 ms: 1.01x faster                                                       |
| docutils                | 1.61 sec                                                    | 1.59 sec: 1.01x faster                                                      |
| scimark_fft             | 181 ms                                                      | 182 ms: 1.01x slower                                                        |
| pprint_pformat          | 1.04 sec                                                    | 1.04 sec: 1.01x slower                                                      |
| pprint_safe_repr        | 508 ms                                                      | 513 ms: 1.01x slower                                                        |
| fannkuch                | 244 ms                                                      | 247 ms: 1.01x slower                                                        |
| dulwich_log             | 42.7 ms                                                     | 43.3 ms: 1.01x slower                                                       |
| aiohttp                 | 848 us                                                      | 861 us: 1.01x slower                                                        |
| sqlglot_optimize        | 34.0 ms                                                     | 34.5 ms: 1.01x slower                                                       |
| meteor_contest          | 72.1 ms                                                     | 73.3 ms: 1.02x slower                                                       |
| chameleon               | 4.95 ms                                                     | 5.05 ms: 1.02x slower                                                       |
| pycparser               | 673 ms                                                      | 689 ms: 1.02x slower                                                        |
| regex_compile           | 87.2 ms                                                     | 89.4 ms: 1.02x slower                                                       |
| deepcopy                | 233 us                                                      | 238 us: 1.02x slower                                                        |
| logging_simple          | 6.21 us                                                     | 6.37 us: 1.03x slower                                                       |
| logging_format          | 6.72 us                                                     | 6.90 us: 1.03x slower                                                       |
| json_loads              | 13.6 us                                                     | 14.0 us: 1.03x slower                                                       |
| mako                    | 7.05 ms                                                     | 7.26 ms: 1.03x slower                                                       |
| async_tree_cpu_io_mixed | 477 ms                                                      | 491 ms: 1.03x slower                                                        |
| regex_dna               | 119 ms                                                      | 123 ms: 1.03x slower                                                        |
| pyflate                 | 294 ms                                                      | 303 ms: 1.03x slower                                                        |
| sqlglot_normalize       | 183 ms                                                      | 189 ms: 1.03x slower                                                        |
| bench_thread_pool       | 830 us                                                      | 856 us: 1.03x slower                                                        |
| scimark_monte_carlo     | 43.0 ms                                                     | 44.4 ms: 1.03x slower                                                       |
| pickle_pure_python      | 195 us                                                      | 202 us: 1.04x slower                                                        |
| async_tree_io           | 712 ms                                                      | 739 ms: 1.04x slower                                                        |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.61 ms: 1.04x slower                                                       |
| nqueens                 | 61.7 ms                                                     | 64.2 ms: 1.04x slower                                                       |
| django_template         | 22.8 ms                                                     | 23.7 ms: 1.04x slower                                                       |
| sympy_integrate         | 13.0 ms                                                     | 13.5 ms: 1.04x slower                                                       |
| tornado_http            | 87.2 ms                                                     | 90.9 ms: 1.04x slower                                                       |
| sympy_expand            | 278 ms                                                      | 290 ms: 1.04x slower                                                        |
| regex_v8                | 13.5 ms                                                     | 14.1 ms: 1.04x slower                                                       |
| coroutines              | 14.1 ms                                                     | 14.8 ms: 1.05x slower                                                       |
| xml_etree_parse         | 90.5 ms                                                     | 94.8 ms: 1.05x slower                                                       |
| dask                    | 255 ms                                                      | 267 ms: 1.05x slower                                                        |
| regex_effbot            | 1.58 ms                                                     | 1.66 ms: 1.05x slower                                                       |
| crypto_pyaes            | 46.4 ms                                                     | 48.7 ms: 1.05x slower                                                       |
| sympy_str               | 171 ms                                                      | 180 ms: 1.05x slower                                                        |
| raytrace                | 192 ms                                                      | 204 ms: 1.06x slower                                                        |
| sympy_sum               | 90.1 ms                                                     | 97.0 ms: 1.08x slower                                                       |
| deepcopy_memo           | 23.4 us                                                     | 25.3 us: 1.08x slower                                                       |
| async_tree_none         | 286 ms                                                      | 310 ms: 1.08x slower                                                        |
| comprehensions          | 14.0 us                                                     | 15.2 us: 1.09x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 368 ms: 1.11x slower                                                        |
| scimark_lu              | 57.5 ms                                                     | 63.7 ms: 1.11x slower                                                       |
| sqlglot_transpile       | 1.02 ms                                                     | 1.13 ms: 1.11x slower                                                       |
| hexiom                  | 4.00 ms                                                     | 4.46 ms: 1.11x slower                                                       |
| unpickle_pure_python    | 134 us                                                      | 150 us: 1.12x slower                                                        |
| spectral_norm           | 63.9 ms                                                     | 71.8 ms: 1.12x slower                                                       |
| mdp                     | 1.42 sec                                                    | 1.60 sec: 1.13x slower                                                      |
| sqlalchemy_imperative   | 9.20 ms                                                     | 10.4 ms: 1.13x slower                                                       |
| go                      | 89.0 ms                                                     | 101 ms: 1.13x slower                                                        |
| richards                | 27.6 ms                                                     | 31.3 ms: 1.13x slower                                                       |
| unpack_sequence         | 36.9 ns                                                     | 41.9 ns: 1.13x slower                                                       |
| sqlglot_parse           | 802 us                                                      | 925 us: 1.15x slower                                                        |
| chaos                   | 42.1 ms                                                     | 49.6 ms: 1.18x slower                                                       |
| logging_silent          | 60.5 ns                                                     | 71.9 ns: 1.19x slower                                                       |
| deltablue               | 2.12 ms                                                     | 2.63 ms: 1.24x slower                                                       |
| mypy2                   | 209 ms                                                      | 275 ms: 1.32x slower                                                        |
| json_dumps              | 5.83 ms                                                     | 7.73 ms: 1.33x slower                                                       |
| coverage                | 39.8 ms                                                     | 53.6 ms: 1.35x slower                                                       |
| asyncio_tcp             | 471 ms                                                      | 659 ms: 1.40x slower                                                        |
| generators              | 22.6 ms                                                     | 33.8 ms: 1.50x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.04x slower                                                                |

Benchmark hidden because not significant (3): nbody, xml_etree_iterparse, json
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220805-3.11.0rc1-41cb071/bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
