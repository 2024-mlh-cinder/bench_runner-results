
# Results vs. 3.12.0

- fork: python
- ref: f9774e57d84162ff0cba
- machine: windows-amd64
- commit hash: f9774e5
- commit date: 2023-03-07
- overall geometric mean: 1.04x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 214 ms                                                      | 194 ms: 1.10x faster                                                       |
| docutils       | 1.63 sec                                                    | 1.51 sec: 1.08x faster                                                     |
| tornado_http   | 87.7 ms                                                     | 90.6 ms: 1.03x slower                                                      |
| Geometric mean | (ref)                                                       | 1.05x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 55.1 ms                                                     | 47.4 ms: 1.16x faster                                                      |
| nbody          | 72.6 ms                                                     | 63.3 ms: 1.15x faster                                                      |
| pidigits       | 150 ms                                                      | 147 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.50 ms: 1.09x faster                                                      |
| regex_dna      | 124 ms                                                      | 115 ms: 1.08x faster                                                       |
| regex_compile  | 88.3 ms                                                     | 83.5 ms: 1.06x faster                                                      |
| regex_v8       | 13.9 ms                                                     | 13.4 ms: 1.04x faster                                                      |
| Geometric mean | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 196 us                                                      | 175 us: 1.12x faster                                                       |
| xml_etree_process    | 38.4 ms                                                     | 35.6 ms: 1.08x faster                                                      |
| unpickle_pure_python | 133 us                                                      | 124 us: 1.08x faster                                                       |
| xml_etree_generate   | 55.6 ms                                                     | 52.1 ms: 1.07x faster                                                      |
| pickle_dict          | 19.3 us                                                     | 18.7 us: 1.03x faster                                                      |
| pickle               | 7.13 us                                                     | 6.96 us: 1.02x faster                                                      |
| unpickle             | 8.16 us                                                     | 7.98 us: 1.02x faster                                                      |
| pickle_list          | 2.86 us                                                     | 2.80 us: 1.02x faster                                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 61.3 ms: 1.02x faster                                                      |
| json_dumps           | 5.60 ms                                                     | 5.51 ms: 1.02x faster                                                      |
| unpickle_list        | 2.78 us                                                     | 2.74 us: 1.01x faster                                                      |
| xml_etree_parse      | 89.2 ms                                                     | 88.4 ms: 1.01x faster                                                      |
| Geometric mean       | (ref)                                                       | 1.04x faster                                                               |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 19.5 ms                                                     | 18.2 ms: 1.07x faster                                                      |
| python_startup_no_site | 16.1 ms                                                     | 15.5 ms: 1.04x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.05x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 6.20 ms: 1.12x faster                                                      |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence         | 37.5 ns                                                     | 27.9 ns: 1.34x faster                                                      |
| float                   | 55.1 ms                                                     | 47.4 ms: 1.16x faster                                                      |
| nbody                   | 72.6 ms                                                     | 63.3 ms: 1.15x faster                                                      |
| deepcopy_reduce         | 2.13 us                                                     | 1.88 us: 1.13x faster                                                      |
| pickle_pure_python      | 196 us                                                      | 175 us: 1.12x faster                                                       |
| mako                    | 6.93 ms                                                     | 6.20 ms: 1.12x faster                                                      |
| scimark_sor             | 79.6 ms                                                     | 71.6 ms: 1.11x faster                                                      |
| deltablue               | 2.14 ms                                                     | 1.92 ms: 1.11x faster                                                      |
| sqlglot_normalize       | 185 ms                                                      | 168 ms: 1.11x faster                                                       |
| 2to3                    | 214 ms                                                      | 194 ms: 1.10x faster                                                       |
| sqlglot_optimize        | 34.4 ms                                                     | 31.2 ms: 1.10x faster                                                      |
| pyflate                 | 297 ms                                                      | 270 ms: 1.10x faster                                                       |
| richards                | 26.9 ms                                                     | 24.5 ms: 1.10x faster                                                      |
| fannkuch                | 237 ms                                                      | 216 ms: 1.10x faster                                                       |
| deepcopy                | 240 us                                                      | 219 us: 1.10x faster                                                       |
| crypto_pyaes            | 47.4 ms                                                     | 43.3 ms: 1.10x faster                                                      |
| regex_effbot            | 1.62 ms                                                     | 1.50 ms: 1.09x faster                                                      |
| create_gc_cycles        | 727 us                                                      | 671 us: 1.08x faster                                                       |
| scimark_monte_carlo     | 43.7 ms                                                     | 40.4 ms: 1.08x faster                                                      |
| docutils                | 1.63 sec                                                    | 1.51 sec: 1.08x faster                                                     |
| xml_etree_process       | 38.4 ms                                                     | 35.6 ms: 1.08x faster                                                      |
| unpickle_pure_python    | 133 us                                                      | 124 us: 1.08x faster                                                       |
| nqueens                 | 61.2 ms                                                     | 56.9 ms: 1.08x faster                                                      |
| regex_dna               | 124 ms                                                      | 115 ms: 1.08x faster                                                       |
| meteor_contest          | 73.1 ms                                                     | 68.0 ms: 1.08x faster                                                      |
| logging_silent          | 60.6 ns                                                     | 56.5 ns: 1.07x faster                                                      |
| pprint_safe_repr        | 512 ms                                                      | 478 ms: 1.07x faster                                                       |
| go                      | 88.5 ms                                                     | 82.6 ms: 1.07x faster                                                      |
| pprint_pformat          | 1.04 sec                                                    | 977 ms: 1.07x faster                                                       |
| scimark_fft             | 180 ms                                                      | 169 ms: 1.07x faster                                                       |
| python_startup          | 19.5 ms                                                     | 18.2 ms: 1.07x faster                                                      |
| xml_etree_generate      | 55.6 ms                                                     | 52.1 ms: 1.07x faster                                                      |
| telco                   | 4.09 ms                                                     | 3.86 ms: 1.06x faster                                                      |
| raytrace                | 191 ms                                                      | 180 ms: 1.06x faster                                                       |
| regex_compile           | 88.3 ms                                                     | 83.5 ms: 1.06x faster                                                      |
| async_generators        | 235 ms                                                      | 223 ms: 1.06x faster                                                       |
| deepcopy_memo           | 23.8 us                                                     | 22.6 us: 1.06x faster                                                      |
| hexiom                  | 4.03 ms                                                     | 3.83 ms: 1.05x faster                                                      |
| bench_mp_pool           | 66.4 ms                                                     | 63.1 ms: 1.05x faster                                                      |
| json                    | 2.86 ms                                                     | 2.74 ms: 1.05x faster                                                      |
| pathlib                 | 77.1 ms                                                     | 73.9 ms: 1.04x faster                                                      |
| python_startup_no_site  | 16.1 ms                                                     | 15.5 ms: 1.04x faster                                                      |
| regex_v8                | 13.9 ms                                                     | 13.4 ms: 1.04x faster                                                      |
| generators              | 22.7 ms                                                     | 21.9 ms: 1.04x faster                                                      |
| coverage                | 51.5 ms                                                     | 49.9 ms: 1.03x faster                                                      |
| gc_traversal            | 1.48 ms                                                     | 1.44 ms: 1.03x faster                                                      |
| pickle_dict             | 19.3 us                                                     | 18.7 us: 1.03x faster                                                      |
| pickle                  | 7.13 us                                                     | 6.96 us: 1.02x faster                                                      |
| pidigits                | 150 ms                                                      | 147 ms: 1.02x faster                                                       |
| unpickle                | 8.16 us                                                     | 7.98 us: 1.02x faster                                                      |
| pickle_list             | 2.86 us                                                     | 2.80 us: 1.02x faster                                                      |
| bench_thread_pool       | 844 us                                                      | 827 us: 1.02x faster                                                       |
| xml_etree_iterparse     | 62.5 ms                                                     | 61.3 ms: 1.02x faster                                                      |
| logging_format          | 6.67 us                                                     | 6.55 us: 1.02x faster                                                      |
| chaos                   | 42.8 ms                                                     | 42.0 ms: 1.02x faster                                                      |
| logging_simple          | 6.21 us                                                     | 6.10 us: 1.02x faster                                                      |
| json_dumps              | 5.60 ms                                                     | 5.51 ms: 1.02x faster                                                      |
| pycparser               | 673 ms                                                      | 663 ms: 1.02x faster                                                       |
| unpickle_list           | 2.78 us                                                     | 2.74 us: 1.01x faster                                                      |
| xml_etree_parse         | 89.2 ms                                                     | 88.4 ms: 1.01x faster                                                      |
| mdp                     | 1.44 sec                                                    | 1.43 sec: 1.01x faster                                                     |
| dulwich_log             | 42.4 ms                                                     | 42.2 ms: 1.00x faster                                                      |
| scimark_lu              | 58.1 ms                                                     | 58.7 ms: 1.01x slower                                                      |
| mypy2                   | 207 ms                                                      | 211 ms: 1.02x slower                                                       |
| sqlite_synth            | 1.76 us                                                     | 1.79 us: 1.02x slower                                                      |
| sqlglot_transpile       | 1.04 ms                                                     | 1.06 ms: 1.02x slower                                                      |
| scimark_sparse_mat_mult | 2.48 ms                                                     | 2.56 ms: 1.03x slower                                                      |
| async_tree_io           | 720 ms                                                      | 744 ms: 1.03x slower                                                       |
| tornado_http            | 87.7 ms                                                     | 90.6 ms: 1.03x slower                                                      |
| async_tree_none         | 294 ms                                                      | 304 ms: 1.04x slower                                                       |
| async_tree_memoization  | 336 ms                                                      | 356 ms: 1.06x slower                                                       |
| sqlglot_parse           | 820 us                                                      | 871 us: 1.06x slower                                                       |
| spectral_norm           | 63.2 ms                                                     | 67.2 ms: 1.06x slower                                                      |
| comprehensions          | 14.1 us                                                     | 15.9 us: 1.12x slower                                                      |
| dask                    | 259 ms                                                      | 352 ms: 1.36x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.04x faster                                                               |

Benchmark hidden because not significant (4): asyncio_tcp, coroutines, json_loads, async_tree_cpu_io_mixed
Ignored benchmarks (5) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (10) of results/bm-20230307-3.12.0a6-f9774e5/bm-20230307-pythonperf1-amd64-python-f9774e57d84162ff0cba-3.12.0a6-f9774e5.json: chameleon, django_template, genshi_text, genshi_xml, html5lib, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.02x
