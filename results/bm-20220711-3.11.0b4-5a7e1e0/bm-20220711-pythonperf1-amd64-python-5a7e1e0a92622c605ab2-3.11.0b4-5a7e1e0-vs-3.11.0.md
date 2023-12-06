
# Results vs. 3.11.0

- fork: python
- ref: 5a7e1e0a92622c605ab2
- machine: windows-amd64
- commit hash: 5a7e1e0
- commit date: 2022-07-11
- overall geometric mean: 1.01x slower \*
- HPT reliability: 97.24%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 206 ms: 1.01x faster                                                       |
| chameleon      | 5.35 ms                                                     | 5.14 ms: 1.04x faster                                                      |
| docutils       | 1.59 sec                                                    | 1.58 sec: 1.01x faster                                                     |
| tornado_http   | 89.9 ms                                                     | 91.9 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (1): html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none         | 314 ms                                                      | 317 ms: 1.01x slower                                                       |
| async_tree_memoization  | 367 ms                                                      | 375 ms: 1.02x slower                                                       |
| async_tree_cpu_io_mixed | 495 ms                                                      | 508 ms: 1.03x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): async_tree_io

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 146 ms: 1.02x faster                                                       |
| float          | 54.4 ms                                                     | 53.9 ms: 1.01x faster                                                      |
| nbody          | 69.3 ms                                                     | 68.7 ms: 1.01x faster                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 114 ms: 1.06x faster                                                       |
| regex_v8       | 13.7 ms                                                     | 13.4 ms: 1.02x faster                                                      |
| regex_effbot   | 1.52 ms                                                     | 1.70 ms: 1.12x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark          | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|--------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python | 207 us                                                      | 204 us: 1.02x faster                                                       |
| json_dumps         | 7.90 ms                                                     | 7.78 ms: 1.02x faster                                                      |
| pickle_list        | 2.68 us                                                     | 2.65 us: 1.01x faster                                                      |
| pickle             | 6.53 us                                                     | 6.48 us: 1.01x faster                                                      |
| xml_etree_process  | 37.0 ms                                                     | 37.8 ms: 1.02x slower                                                      |
| xml_etree_generate | 52.2 ms                                                     | 53.4 ms: 1.02x slower                                                      |
| pickle_dict        | 17.8 us                                                     | 18.4 us: 1.04x slower                                                      |
| unpickle           | 7.82 us                                                     | 8.32 us: 1.06x slower                                                      |
| unpickle_list      | 2.57 us                                                     | 2.80 us: 1.09x slower                                                      |
| json_loads         | 12.9 us                                                     | 14.1 us: 1.09x slower                                                      |
| Geometric mean     | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (3): xml_etree_iterparse, unpickle_pure_python, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 15.4 ms: 1.01x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| genshi_xml      | 40.5 ms                                                     | 38.6 ms: 1.05x faster                                                      |
| mako            | 7.55 ms                                                     | 7.23 ms: 1.04x faster                                                      |
| django_template | 24.0 ms                                                     | 25.0 ms: 1.04x slower                                                      |
| Geometric mean  | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (1): genshi_text

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| create_gc_cycles        | 706 us                                                      | 664 us: 1.06x faster                                                       |
| regex_dna               | 121 ms                                                      | 114 ms: 1.06x faster                                                       |
| sqlite_synth            | 1.79 us                                                     | 1.70 us: 1.06x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 38.6 ms: 1.05x faster                                                      |
| mako                    | 7.55 ms                                                     | 7.23 ms: 1.04x faster                                                      |
| sympy_sum               | 100.0 ms                                                    | 95.8 ms: 1.04x faster                                                      |
| chameleon               | 5.35 ms                                                     | 5.14 ms: 1.04x faster                                                      |
| unpack_sequence         | 47.0 ns                                                     | 45.4 ns: 1.03x faster                                                      |
| raytrace                | 211 ms                                                      | 204 ms: 1.03x faster                                                       |
| mdp                     | 1.73 sec                                                    | 1.67 sec: 1.03x faster                                                     |
| gc_traversal            | 1.46 ms                                                     | 1.41 ms: 1.03x faster                                                      |
| sympy_expand            | 299 ms                                                      | 291 ms: 1.03x faster                                                       |
| python_startup          | 18.8 ms                                                     | 18.4 ms: 1.02x faster                                                      |
| regex_v8                | 13.7 ms                                                     | 13.4 ms: 1.02x faster                                                      |
| pickle_pure_python      | 207 us                                                      | 204 us: 1.02x faster                                                       |
| json_dumps              | 7.90 ms                                                     | 7.78 ms: 1.02x faster                                                      |
| pidigits                | 149 ms                                                      | 146 ms: 1.02x faster                                                       |
| sqlglot_transpile       | 1.15 ms                                                     | 1.13 ms: 1.01x faster                                                      |
| sympy_str               | 184 ms                                                      | 182 ms: 1.01x faster                                                       |
| python_startup_no_site  | 15.5 ms                                                     | 15.4 ms: 1.01x faster                                                      |
| float                   | 54.4 ms                                                     | 53.9 ms: 1.01x faster                                                      |
| sqlalchemy_imperative   | 10.5 ms                                                     | 10.4 ms: 1.01x faster                                                      |
| pickle_list             | 2.68 us                                                     | 2.65 us: 1.01x faster                                                      |
| nbody                   | 69.3 ms                                                     | 68.7 ms: 1.01x faster                                                      |
| sqlglot_optimize        | 35.1 ms                                                     | 34.8 ms: 1.01x faster                                                      |
| pickle                  | 6.53 us                                                     | 6.48 us: 1.01x faster                                                      |
| 2to3                    | 207 ms                                                      | 206 ms: 1.01x faster                                                       |
| scimark_monte_carlo     | 44.6 ms                                                     | 44.3 ms: 1.01x faster                                                      |
| pprint_safe_repr        | 519 ms                                                      | 515 ms: 1.01x faster                                                       |
| docutils                | 1.59 sec                                                    | 1.58 sec: 1.01x faster                                                     |
| deepcopy_memo           | 25.5 us                                                     | 25.3 us: 1.00x faster                                                      |
| meteor_contest          | 75.0 ms                                                     | 74.8 ms: 1.00x faster                                                      |
| pyflate                 | 305 ms                                                      | 306 ms: 1.00x slower                                                       |
| bench_mp_pool           | 61.1 ms                                                     | 61.4 ms: 1.00x slower                                                      |
| flaskblogging           | 2.03 sec                                                    | 2.05 sec: 1.01x slower                                                     |
| scimark_lu              | 62.3 ms                                                     | 62.7 ms: 1.01x slower                                                      |
| go                      | 98.8 ms                                                     | 99.5 ms: 1.01x slower                                                      |
| coroutines              | 14.7 ms                                                     | 14.8 ms: 1.01x slower                                                      |
| async_tree_none         | 314 ms                                                      | 317 ms: 1.01x slower                                                       |
| sqlalchemy_declarative  | 83.9 ms                                                     | 84.7 ms: 1.01x slower                                                      |
| logging_simple          | 6.60 us                                                     | 6.68 us: 1.01x slower                                                      |
| comprehensions          | 15.6 us                                                     | 15.7 us: 1.01x slower                                                      |
| fannkuch                | 248 ms                                                      | 251 ms: 1.01x slower                                                       |
| deltablue               | 2.63 ms                                                     | 2.66 ms: 1.01x slower                                                      |
| bench_thread_pool       | 847 us                                                      | 858 us: 1.01x slower                                                       |
| deepcopy                | 242 us                                                      | 246 us: 1.01x slower                                                       |
| logging_format          | 7.06 us                                                     | 7.19 us: 1.02x slower                                                      |
| xml_etree_process       | 37.0 ms                                                     | 37.8 ms: 1.02x slower                                                      |
| hexiom                  | 4.51 ms                                                     | 4.61 ms: 1.02x slower                                                      |
| tornado_http            | 89.9 ms                                                     | 91.9 ms: 1.02x slower                                                      |
| async_tree_memoization  | 367 ms                                                      | 375 ms: 1.02x slower                                                       |
| telco                   | 3.93 ms                                                     | 4.02 ms: 1.02x slower                                                      |
| xml_etree_generate      | 52.2 ms                                                     | 53.4 ms: 1.02x slower                                                      |
| nqueens                 | 66.1 ms                                                     | 67.6 ms: 1.02x slower                                                      |
| logging_silent          | 70.7 ns                                                     | 72.4 ns: 1.02x slower                                                      |
| async_tree_cpu_io_mixed | 495 ms                                                      | 508 ms: 1.03x slower                                                       |
| scimark_fft             | 181 ms                                                      | 186 ms: 1.03x slower                                                       |
| scimark_sor             | 76.4 ms                                                     | 78.5 ms: 1.03x slower                                                      |
| dask                    | 262 ms                                                      | 270 ms: 1.03x slower                                                       |
| richards                | 30.8 ms                                                     | 31.7 ms: 1.03x slower                                                      |
| thrift                  | 501 us                                                      | 518 us: 1.03x slower                                                       |
| deepcopy_reduce         | 2.07 us                                                     | 2.14 us: 1.03x slower                                                      |
| pickle_dict             | 17.8 us                                                     | 18.4 us: 1.04x slower                                                      |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.68 ms: 1.04x slower                                                      |
| django_template         | 24.0 ms                                                     | 25.0 ms: 1.04x slower                                                      |
| chaos                   | 46.8 ms                                                     | 48.7 ms: 1.04x slower                                                      |
| pathlib                 | 69.4 ms                                                     | 72.4 ms: 1.04x slower                                                      |
| crypto_pyaes            | 48.2 ms                                                     | 50.6 ms: 1.05x slower                                                      |
| spectral_norm           | 69.9 ms                                                     | 73.7 ms: 1.05x slower                                                      |
| unpickle                | 7.82 us                                                     | 8.32 us: 1.06x slower                                                      |
| unpickle_list           | 2.57 us                                                     | 2.80 us: 1.09x slower                                                      |
| json_loads              | 12.9 us                                                     | 14.1 us: 1.09x slower                                                      |
| asyncio_tcp             | 614 ms                                                      | 675 ms: 1.10x slower                                                       |
| json                    | 2.99 ms                                                     | 3.32 ms: 1.11x slower                                                      |
| regex_effbot            | 1.52 ms                                                     | 1.70 ms: 1.12x slower                                                      |
| mypy2                   | 226 ms                                                      | 278 ms: 1.23x slower                                                       |
| coverage                | 43.0 ms                                                     | 54.1 ms: 1.26x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (17): async_generators, genshi_text, xml_etree_iterparse, sqlglot_parse, unpickle_pure_python, generators, sympy_integrate, async_tree_io, regex_compile, pycparser, pylint, dulwich_log, sqlglot_normalize, pprint_pformat, xml_etree_parse, aiohttp, html5lib
Ignored benchmarks (8) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 97.24% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
