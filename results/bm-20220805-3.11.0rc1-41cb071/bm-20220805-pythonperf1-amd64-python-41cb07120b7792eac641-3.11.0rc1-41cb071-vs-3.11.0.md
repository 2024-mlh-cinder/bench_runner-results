
# Results vs. 3.11.0

- fork: python
- ref: 41cb07120b7792eac641
- machine: windows-amd64
- commit hash: 41cb071
- commit date: 2022-08-05
- overall geometric mean: 1.00x faster \*
- HPT reliability: 98.07%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 202 ms: 1.02x faster                                                        |
| chameleon      | 5.35 ms                                                     | 5.05 ms: 1.06x faster                                                       |
| tornado_http   | 89.9 ms                                                     | 90.9 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (2): docutils, html5lib

Benchmarks with tag 'asyncio':
==============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io   | 753 ms                                                      | 739 ms: 1.02x faster                                                        |
| async_tree_none | 314 ms                                                      | 310 ms: 1.01x faster                                                        |
| Geometric mean  | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 54.4 ms                                                     | 52.9 ms: 1.03x faster                                                       |
| pidigits       | 149 ms                                                      | 146 ms: 1.02x faster                                                        |
| nbody          | 69.3 ms                                                     | 68.3 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 89.4 ms: 1.02x faster                                                       |
| regex_dna      | 121 ms                                                      | 123 ms: 1.01x slower                                                        |
| regex_v8       | 13.7 ms                                                     | 14.1 ms: 1.03x slower                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.66 ms: 1.09x slower                                                       |
| Geometric mean | (ref)                                                       | 1.03x slower                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_list          | 2.68 us                                                     | 2.57 us: 1.04x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 202 us: 1.03x faster                                                        |
| json_dumps           | 7.90 ms                                                     | 7.73 ms: 1.02x faster                                                       |
| pickle               | 6.53 us                                                     | 6.44 us: 1.01x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 150 us: 1.01x faster                                                        |
| xml_etree_process    | 37.0 ms                                                     | 36.7 ms: 1.01x faster                                                       |
| xml_etree_generate   | 52.2 ms                                                     | 52.6 ms: 1.01x slower                                                       |
| unpickle_list        | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| unpickle             | 7.82 us                                                     | 8.11 us: 1.04x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.4 us: 1.04x slower                                                       |
| json_loads           | 12.9 us                                                     | 14.0 us: 1.09x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                                |

Benchmark hidden because not significant (2): xml_etree_iterparse, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.4 ms: 1.03x faster                                                       |
| python_startup_no_site | 15.5 ms                                                     | 15.2 ms: 1.02x faster                                                       |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_xml      | 40.5 ms                                                     | 37.7 ms: 1.07x faster                                                       |
| genshi_text     | 17.7 ms                                                     | 16.7 ms: 1.06x faster                                                       |
| mako            | 7.55 ms                                                     | 7.26 ms: 1.04x faster                                                       |
| django_template | 24.0 ms                                                     | 23.7 ms: 1.01x faster                                                       |
| Geometric mean  | (ref)                                                       | 1.05x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220805-pythonperf1-amd64-python-41cb07120b7792eac641-3.11.0rc1-41cb071 |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence         | 47.0 ns                                                     | 41.9 ns: 1.12x faster                                                       |
| mdp                     | 1.73 sec                                                    | 1.60 sec: 1.08x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 37.7 ms: 1.07x faster                                                       |
| sqlite_synth            | 1.79 us                                                     | 1.68 us: 1.07x faster                                                       |
| create_gc_cycles        | 706 us                                                      | 665 us: 1.06x faster                                                        |
| chameleon               | 5.35 ms                                                     | 5.05 ms: 1.06x faster                                                       |
| genshi_text             | 17.7 ms                                                     | 16.7 ms: 1.06x faster                                                       |
| pickle_list             | 2.68 us                                                     | 2.57 us: 1.04x faster                                                       |
| mako                    | 7.55 ms                                                     | 7.26 ms: 1.04x faster                                                       |
| thrift                  | 501 us                                                      | 482 us: 1.04x faster                                                        |
| gc_traversal            | 1.46 ms                                                     | 1.40 ms: 1.04x faster                                                       |
| logging_simple          | 6.60 us                                                     | 6.37 us: 1.04x faster                                                       |
| raytrace                | 211 ms                                                      | 204 ms: 1.04x faster                                                        |
| sympy_sum               | 100.0 ms                                                    | 97.0 ms: 1.03x faster                                                       |
| sympy_expand            | 299 ms                                                      | 290 ms: 1.03x faster                                                        |
| nqueens                 | 66.1 ms                                                     | 64.2 ms: 1.03x faster                                                       |
| float                   | 54.4 ms                                                     | 52.9 ms: 1.03x faster                                                       |
| async_generators        | 181 ms                                                      | 176 ms: 1.03x faster                                                        |
| python_startup          | 18.8 ms                                                     | 18.4 ms: 1.03x faster                                                       |
| pickle_pure_python      | 207 us                                                      | 202 us: 1.03x faster                                                        |
| comprehensions          | 15.6 us                                                     | 15.2 us: 1.03x faster                                                       |
| 2to3                    | 207 ms                                                      | 202 ms: 1.02x faster                                                        |
| pycparser               | 705 ms                                                      | 689 ms: 1.02x faster                                                        |
| logging_format          | 7.06 us                                                     | 6.90 us: 1.02x faster                                                       |
| meteor_contest          | 75.0 ms                                                     | 73.3 ms: 1.02x faster                                                       |
| sympy_str               | 184 ms                                                      | 180 ms: 1.02x faster                                                        |
| json_dumps              | 7.90 ms                                                     | 7.73 ms: 1.02x faster                                                       |
| async_tree_io           | 753 ms                                                      | 739 ms: 1.02x faster                                                        |
| dulwich_log             | 44.1 ms                                                     | 43.3 ms: 1.02x faster                                                       |
| pidigits                | 149 ms                                                      | 146 ms: 1.02x faster                                                        |
| pprint_pformat          | 1.06 sec                                                    | 1.04 sec: 1.02x faster                                                      |
| python_startup_no_site  | 15.5 ms                                                     | 15.2 ms: 1.02x faster                                                       |
| deepcopy                | 242 us                                                      | 238 us: 1.02x faster                                                        |
| regex_compile           | 90.8 ms                                                     | 89.4 ms: 1.02x faster                                                       |
| telco                   | 3.93 ms                                                     | 3.87 ms: 1.02x faster                                                       |
| sympy_integrate         | 13.7 ms                                                     | 13.5 ms: 1.02x faster                                                       |
| sqlglot_optimize        | 35.1 ms                                                     | 34.5 ms: 1.02x faster                                                       |
| sqlglot_parse           | 939 us                                                      | 925 us: 1.01x faster                                                        |
| pickle                  | 6.53 us                                                     | 6.44 us: 1.01x faster                                                       |
| unpickle_pure_python    | 152 us                                                      | 150 us: 1.01x faster                                                        |
| sqlglot_transpile       | 1.15 ms                                                     | 1.13 ms: 1.01x faster                                                       |
| deepcopy_reduce         | 2.07 us                                                     | 2.05 us: 1.01x faster                                                       |
| nbody                   | 69.3 ms                                                     | 68.3 ms: 1.01x faster                                                       |
| hexiom                  | 4.51 ms                                                     | 4.46 ms: 1.01x faster                                                       |
| django_template         | 24.0 ms                                                     | 23.7 ms: 1.01x faster                                                       |
| async_tree_none         | 314 ms                                                      | 310 ms: 1.01x faster                                                        |
| sqlalchemy_imperative   | 10.5 ms                                                     | 10.4 ms: 1.01x faster                                                       |
| sqlglot_normalize       | 191 ms                                                      | 189 ms: 1.01x faster                                                        |
| pprint_safe_repr        | 519 ms                                                      | 513 ms: 1.01x faster                                                        |
| xml_etree_process       | 37.0 ms                                                     | 36.7 ms: 1.01x faster                                                       |
| pyflate                 | 305 ms                                                      | 303 ms: 1.01x faster                                                        |
| sqlalchemy_declarative  | 83.9 ms                                                     | 83.4 ms: 1.01x faster                                                       |
| deepcopy_memo           | 25.5 us                                                     | 25.3 us: 1.01x faster                                                       |
| scimark_monte_carlo     | 44.6 ms                                                     | 44.4 ms: 1.00x faster                                                       |
| scimark_fft             | 181 ms                                                      | 182 ms: 1.01x slower                                                        |
| flaskblogging           | 2.03 sec                                                    | 2.05 sec: 1.01x slower                                                      |
| coroutines              | 14.7 ms                                                     | 14.8 ms: 1.01x slower                                                       |
| xml_etree_generate      | 52.2 ms                                                     | 52.6 ms: 1.01x slower                                                       |
| aiohttp                 | 854 us                                                      | 861 us: 1.01x slower                                                        |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.61 ms: 1.01x slower                                                       |
| tornado_http            | 89.9 ms                                                     | 90.9 ms: 1.01x slower                                                       |
| scimark_sor             | 76.4 ms                                                     | 77.3 ms: 1.01x slower                                                       |
| crypto_pyaes            | 48.2 ms                                                     | 48.7 ms: 1.01x slower                                                       |
| regex_dna               | 121 ms                                                      | 123 ms: 1.01x slower                                                        |
| richards                | 30.8 ms                                                     | 31.3 ms: 1.02x slower                                                       |
| logging_silent          | 70.7 ns                                                     | 71.9 ns: 1.02x slower                                                       |
| go                      | 98.8 ms                                                     | 101 ms: 1.02x slower                                                        |
| dask                    | 262 ms                                                      | 267 ms: 1.02x slower                                                        |
| scimark_lu              | 62.3 ms                                                     | 63.7 ms: 1.02x slower                                                       |
| spectral_norm           | 69.9 ms                                                     | 71.8 ms: 1.03x slower                                                       |
| unpickle_list           | 2.57 us                                                     | 2.64 us: 1.03x slower                                                       |
| regex_v8                | 13.7 ms                                                     | 14.1 ms: 1.03x slower                                                       |
| unpickle                | 7.82 us                                                     | 8.11 us: 1.04x slower                                                       |
| pickle_dict             | 17.8 us                                                     | 18.4 us: 1.04x slower                                                       |
| pathlib                 | 69.4 ms                                                     | 72.6 ms: 1.05x slower                                                       |
| chaos                   | 46.8 ms                                                     | 49.6 ms: 1.06x slower                                                       |
| asyncio_tcp             | 614 ms                                                      | 659 ms: 1.07x slower                                                        |
| json_loads              | 12.9 us                                                     | 14.0 us: 1.09x slower                                                       |
| regex_effbot            | 1.52 ms                                                     | 1.66 ms: 1.09x slower                                                       |
| mypy2                   | 226 ms                                                      | 275 ms: 1.22x slower                                                        |
| coverage                | 43.0 ms                                                     | 53.6 ms: 1.25x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.00x faster                                                                |

Benchmark hidden because not significant (13): json, async_tree_cpu_io_mixed, generators, html5lib, fannkuch, xml_etree_iterparse, deltablue, pylint, docutils, xml_etree_parse, async_tree_memoization, bench_mp_pool, bench_thread_pool
Ignored benchmarks (8) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 98.07% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
