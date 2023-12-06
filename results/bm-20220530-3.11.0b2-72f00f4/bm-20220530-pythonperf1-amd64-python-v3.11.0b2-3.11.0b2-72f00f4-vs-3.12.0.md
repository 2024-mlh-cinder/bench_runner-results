
# Results vs. 3.12.0

- fork: python
- ref: v3.11.0b2
- machine: windows-amd64
- commit hash: 72f00f4
- commit date: 2022-05-30
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 211 ms: 1.01x faster                                            |
| chameleon      | 4.95 ms                                                     | 5.59 ms: 1.13x slower                                           |
| docutils       | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                          |
| tornado_http   | 87.2 ms                                                     | 95.3 ms: 1.09x slower                                           |
| Geometric mean | (ref)                                                       | 1.06x slower                                                    |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 520 ms: 1.09x slower                                            |
| async_tree_io           | 712 ms                                                      | 794 ms: 1.12x slower                                            |
| async_tree_none         | 286 ms                                                      | 336 ms: 1.18x slower                                            |
| async_tree_memoization  | 333 ms                                                      | 400 ms: 1.20x slower                                            |
| Geometric mean          | (ref)                                                       | 1.14x slower                                                    |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 70.1 ms: 1.02x slower                                           |
| pidigits       | 150 ms                                                      | 153 ms: 1.02x slower                                            |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (1): float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                     | 1.39 ms: 1.14x faster                                           |
| regex_v8       | 13.5 ms                                                     | 14.4 ms: 1.07x slower                                           |
| regex_compile  | 87.2 ms                                                     | 97.0 ms: 1.11x slower                                           |
| Geometric mean | (ref)                                                       | 1.01x slower                                                    |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.74 us: 1.10x faster                                           |
| pickle_list          | 2.88 us                                                     | 2.64 us: 1.09x faster                                           |
| pickle_dict          | 18.9 us                                                     | 17.4 us: 1.09x faster                                           |
| unpickle             | 8.44 us                                                     | 8.07 us: 1.05x faster                                           |
| xml_etree_generate   | 55.8 ms                                                     | 54.1 ms: 1.03x faster                                           |
| xml_etree_iterparse  | 63.1 ms                                                     | 62.0 ms: 1.02x faster                                           |
| unpickle_list        | 2.69 us                                                     | 2.76 us: 1.02x slower                                           |
| json_loads           | 13.6 us                                                     | 14.1 us: 1.03x slower                                           |
| xml_etree_process    | 37.6 ms                                                     | 39.1 ms: 1.04x slower                                           |
| xml_etree_parse      | 90.5 ms                                                     | 96.7 ms: 1.07x slower                                           |
| pickle_pure_python   | 195 us                                                      | 216 us: 1.11x slower                                            |
| unpickle_pure_python | 134 us                                                      | 164 us: 1.22x slower                                            |
| json_dumps           | 5.83 ms                                                     | 8.21 ms: 1.41x slower                                           |
| Geometric mean       | (ref)                                                       | 1.04x slower                                                    |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| python_startup | 18.8 ms                                                     | 19.0 ms: 1.01x slower                                           |
| Geometric mean | (ref)                                                       | 1.00x slower                                                    |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 7.62 ms: 1.08x slower                                           |
| django_template | 22.8 ms                                                     | 25.1 ms: 1.10x slower                                           |
| Geometric mean  | (ref)                                                       | 1.09x slower                                                    |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 187 ms: 1.23x faster                                            |
| regex_effbot            | 1.58 ms                                                     | 1.39 ms: 1.14x faster                                           |
| pickle                  | 7.38 us                                                     | 6.74 us: 1.10x faster                                           |
| pickle_list             | 2.88 us                                                     | 2.64 us: 1.09x faster                                           |
| pickle_dict             | 18.9 us                                                     | 17.4 us: 1.09x faster                                           |
| create_gc_cycles        | 726 us                                                      | 675 us: 1.08x faster                                            |
| pathlib                 | 79.6 ms                                                     | 74.8 ms: 1.06x faster                                           |
| bench_mp_pool           | 67.2 ms                                                     | 63.3 ms: 1.06x faster                                           |
| logging_format          | 6.72 us                                                     | 6.39 us: 1.05x faster                                           |
| unpickle                | 8.44 us                                                     | 8.07 us: 1.05x faster                                           |
| logging_simple          | 6.21 us                                                     | 5.94 us: 1.04x faster                                           |
| xml_etree_generate      | 55.8 ms                                                     | 54.1 ms: 1.03x faster                                           |
| gc_traversal            | 1.49 ms                                                     | 1.46 ms: 1.02x faster                                           |
| sqlite_synth            | 1.75 us                                                     | 1.71 us: 1.02x faster                                           |
| xml_etree_iterparse     | 63.1 ms                                                     | 62.0 ms: 1.02x faster                                           |
| sqlalchemy_declarative  | 84.5 ms                                                     | 83.2 ms: 1.01x faster                                           |
| telco                   | 4.08 ms                                                     | 4.05 ms: 1.01x faster                                           |
| 2to3                    | 213 ms                                                      | 211 ms: 1.01x faster                                            |
| python_startup          | 18.8 ms                                                     | 19.0 ms: 1.01x slower                                           |
| nbody                   | 68.8 ms                                                     | 70.1 ms: 1.02x slower                                           |
| pidigits                | 150 ms                                                      | 153 ms: 1.02x slower                                            |
| unpickle_list           | 2.69 us                                                     | 2.76 us: 1.02x slower                                           |
| docutils                | 1.61 sec                                                    | 1.66 sec: 1.03x slower                                          |
| json_loads              | 13.6 us                                                     | 14.1 us: 1.03x slower                                           |
| xml_etree_process       | 37.6 ms                                                     | 39.1 ms: 1.04x slower                                           |
| deepcopy_reduce         | 2.08 us                                                     | 2.19 us: 1.05x slower                                           |
| scimark_fft             | 181 ms                                                      | 191 ms: 1.05x slower                                            |
| xml_etree_parse         | 90.5 ms                                                     | 96.7 ms: 1.07x slower                                           |
| pyflate                 | 294 ms                                                      | 314 ms: 1.07x slower                                            |
| regex_v8                | 13.5 ms                                                     | 14.4 ms: 1.07x slower                                           |
| scimark_monte_carlo     | 43.0 ms                                                     | 46.0 ms: 1.07x slower                                           |
| bench_thread_pool       | 830 us                                                      | 889 us: 1.07x slower                                            |
| pprint_pformat          | 1.04 sec                                                    | 1.11 sec: 1.07x slower                                          |
| pprint_safe_repr        | 508 ms                                                      | 548 ms: 1.08x slower                                            |
| dulwich_log             | 42.7 ms                                                     | 46.1 ms: 1.08x slower                                           |
| mako                    | 7.05 ms                                                     | 7.62 ms: 1.08x slower                                           |
| aiohttp                 | 848 us                                                      | 921 us: 1.09x slower                                            |
| fannkuch                | 244 ms                                                      | 266 ms: 1.09x slower                                            |
| async_tree_cpu_io_mixed | 477 ms                                                      | 520 ms: 1.09x slower                                            |
| meteor_contest          | 72.1 ms                                                     | 78.7 ms: 1.09x slower                                           |
| tornado_http            | 87.2 ms                                                     | 95.3 ms: 1.09x slower                                           |
| json                    | 2.94 ms                                                     | 3.23 ms: 1.10x slower                                           |
| sympy_integrate         | 13.0 ms                                                     | 14.2 ms: 1.10x slower                                           |
| django_template         | 22.8 ms                                                     | 25.1 ms: 1.10x slower                                           |
| dask                    | 255 ms                                                      | 280 ms: 1.10x slower                                            |
| sqlglot_optimize        | 34.0 ms                                                     | 37.5 ms: 1.10x slower                                           |
| sqlglot_normalize       | 183 ms                                                      | 203 ms: 1.10x slower                                            |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.77 ms: 1.10x slower                                           |
| coroutines              | 14.1 ms                                                     | 15.6 ms: 1.10x slower                                           |
| spectral_norm           | 63.9 ms                                                     | 70.6 ms: 1.11x slower                                           |
| sympy_str               | 171 ms                                                      | 190 ms: 1.11x slower                                            |
| raytrace                | 192 ms                                                      | 213 ms: 1.11x slower                                            |
| pickle_pure_python      | 195 us                                                      | 216 us: 1.11x slower                                            |
| regex_compile           | 87.2 ms                                                     | 97.0 ms: 1.11x slower                                           |
| pycparser               | 673 ms                                                      | 750 ms: 1.11x slower                                            |
| deepcopy_memo           | 23.4 us                                                     | 26.1 us: 1.12x slower                                           |
| async_tree_io           | 712 ms                                                      | 794 ms: 1.12x slower                                            |
| nqueens                 | 61.7 ms                                                     | 68.9 ms: 1.12x slower                                           |
| crypto_pyaes            | 46.4 ms                                                     | 51.8 ms: 1.12x slower                                           |
| deepcopy                | 233 us                                                      | 261 us: 1.12x slower                                            |
| sympy_expand            | 278 ms                                                      | 312 ms: 1.12x slower                                            |
| scimark_lu              | 57.5 ms                                                     | 64.6 ms: 1.12x slower                                           |
| go                      | 89.0 ms                                                     | 100 ms: 1.13x slower                                            |
| chameleon               | 4.95 ms                                                     | 5.59 ms: 1.13x slower                                           |
| sqlalchemy_imperative   | 9.20 ms                                                     | 10.5 ms: 1.14x slower                                           |
| sympy_sum               | 90.1 ms                                                     | 103 ms: 1.14x slower                                            |
| richards                | 27.6 ms                                                     | 31.6 ms: 1.15x slower                                           |
| async_tree_none         | 286 ms                                                      | 336 ms: 1.18x slower                                            |
| logging_silent          | 60.5 ns                                                     | 72.2 ns: 1.19x slower                                           |
| async_tree_memoization  | 333 ms                                                      | 400 ms: 1.20x slower                                            |
| unpack_sequence         | 36.9 ns                                                     | 44.3 ns: 1.20x slower                                           |
| hexiom                  | 4.00 ms                                                     | 4.84 ms: 1.21x slower                                           |
| unpickle_pure_python    | 134 us                                                      | 164 us: 1.22x slower                                            |
| chaos                   | 42.1 ms                                                     | 51.8 ms: 1.23x slower                                           |
| mdp                     | 1.42 sec                                                    | 1.75 sec: 1.23x slower                                          |
| deltablue               | 2.12 ms                                                     | 2.72 ms: 1.28x slower                                           |
| comprehensions          | 14.0 us                                                     | 18.2 us: 1.30x slower                                           |
| sqlglot_transpile       | 1.02 ms                                                     | 1.42 ms: 1.40x slower                                           |
| json_dumps              | 5.83 ms                                                     | 8.21 ms: 1.41x slower                                           |
| mypy2                   | 209 ms                                                      | 295 ms: 1.41x slower                                            |
| sqlglot_parse           | 802 us                                                      | 1.21 ms: 1.50x slower                                           |
| asyncio_tcp             | 471 ms                                                      | 742 ms: 1.57x slower                                            |
| generators              | 22.6 ms                                                     | 35.7 ms: 1.58x slower                                           |
| coverage                | 39.8 ms                                                     | 106 ms: 2.66x slower                                            |
| Geometric mean          | (ref)                                                       | 1.10x slower                                                    |

Benchmark hidden because not significant (4): python_startup_no_site, float, regex_dna, scimark_sor
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (5) of results/bm-20220530-3.11.0b2-72f00f4/bm-20220530-pythonperf1-amd64-python-v3.11.0b2-3.11.0b2-72f00f4.json: genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.08x
- 95% likely to have a slowdown of 1.07x
- 99% likely to have a slowdown of 1.07x
