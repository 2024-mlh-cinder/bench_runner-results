
# Results vs. 3.11.0

- fork: python
- ref: ed7c3ff15680c1939fad
- machine: windows-amd64
- commit hash: ed7c3ff
- commit date: 2022-09-11
- overall geometric mean: 1.01x faster \*
- HPT reliability: 99.96%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 202 ms: 1.03x faster                                                        |
| chameleon      | 5.35 ms                                                     | 5.09 ms: 1.05x faster                                                       |
| docutils       | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                                      |
| html5lib       | 38.6 ms                                                     | 37.2 ms: 1.04x faster                                                       |
| tornado_http   | 89.9 ms                                                     | 92.1 ms: 1.02x slower                                                       |
| Geometric mean | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io   | 753 ms                                                      | 740 ms: 1.02x faster                                                        |
| async_tree_none | 314 ms                                                      | 310 ms: 1.01x faster                                                        |
| Geometric mean  | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (2): async_tree_cpu_io_mixed, async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| nbody          | 69.3 ms                                                     | 68.6 ms: 1.01x faster                                                       |
| float          | 54.4 ms                                                     | 53.9 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 121 ms                                                      | 115 ms: 1.06x faster                                                        |
| regex_v8       | 13.7 ms                                                     | 13.4 ms: 1.02x faster                                                       |
| regex_compile  | 90.8 ms                                                     | 89.5 ms: 1.02x faster                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|----------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 207 us                                                      | 197 us: 1.05x faster                                                        |
| xml_etree_parse      | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                                       |
| json_dumps           | 7.90 ms                                                     | 7.66 ms: 1.03x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 35.9 ms: 1.03x faster                                                       |
| unpickle_pure_python | 152 us                                                      | 149 us: 1.02x faster                                                        |
| xml_etree_generate   | 52.2 ms                                                     | 51.2 ms: 1.02x faster                                                       |
| xml_etree_iterparse  | 63.0 ms                                                     | 61.9 ms: 1.02x faster                                                       |
| unpickle             | 7.82 us                                                     | 7.70 us: 1.02x faster                                                       |
| pickle_list          | 2.68 us                                                     | 2.65 us: 1.01x faster                                                       |
| unpickle_list        | 2.57 us                                                     | 2.55 us: 1.01x faster                                                       |
| pickle               | 6.53 us                                                     | 6.60 us: 1.01x slower                                                       |
| pickle_dict          | 17.8 us                                                     | 18.2 us: 1.02x slower                                                       |
| json_loads           | 12.9 us                                                     | 13.7 us: 1.06x slower                                                       |
| Geometric mean       | (ref)                                                       | 1.01x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                       |
| python_startup_no_site | 15.5 ms                                                     | 15.3 ms: 1.01x faster                                                       |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-----------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| genshi_text     | 17.7 ms                                                     | 16.7 ms: 1.06x faster                                                       |
| genshi_xml      | 40.5 ms                                                     | 38.3 ms: 1.06x faster                                                       |
| mako            | 7.55 ms                                                     | 7.22 ms: 1.05x faster                                                       |
| django_template | 24.0 ms                                                     | 23.8 ms: 1.01x faster                                                       |
| Geometric mean  | (ref)                                                       | 1.04x faster                                                                |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20220911-pythonperf1-amd64-python-ed7c3ff15680c1939fad-3.11.0rc2-ed7c3ff |
|-------------------------|:-----------------------------------------------------------:|:---------------------------------------------------------------------------:|
| unpack_sequence         | 47.0 ns                                                     | 42.7 ns: 1.10x faster                                                       |
| mdp                     | 1.73 sec                                                    | 1.59 sec: 1.09x faster                                                      |
| sqlite_synth            | 1.79 us                                                     | 1.67 us: 1.07x faster                                                       |
| genshi_text             | 17.7 ms                                                     | 16.7 ms: 1.06x faster                                                       |
| create_gc_cycles        | 706 us                                                      | 667 us: 1.06x faster                                                        |
| regex_dna               | 121 ms                                                      | 115 ms: 1.06x faster                                                        |
| genshi_xml              | 40.5 ms                                                     | 38.3 ms: 1.06x faster                                                       |
| chameleon               | 5.35 ms                                                     | 5.09 ms: 1.05x faster                                                       |
| pickle_pure_python      | 207 us                                                      | 197 us: 1.05x faster                                                        |
| mako                    | 7.55 ms                                                     | 7.22 ms: 1.05x faster                                                       |
| deepcopy_reduce         | 2.07 us                                                     | 2.00 us: 1.04x faster                                                       |
| html5lib                | 38.6 ms                                                     | 37.2 ms: 1.04x faster                                                       |
| gc_traversal            | 1.46 ms                                                     | 1.41 ms: 1.03x faster                                                       |
| xml_etree_parse         | 94.5 ms                                                     | 91.6 ms: 1.03x faster                                                       |
| pycparser               | 705 ms                                                      | 683 ms: 1.03x faster                                                        |
| json_dumps              | 7.90 ms                                                     | 7.66 ms: 1.03x faster                                                       |
| xml_etree_process       | 37.0 ms                                                     | 35.9 ms: 1.03x faster                                                       |
| sqlglot_optimize        | 35.1 ms                                                     | 34.0 ms: 1.03x faster                                                       |
| async_generators        | 181 ms                                                      | 176 ms: 1.03x faster                                                        |
| sqlglot_normalize       | 191 ms                                                      | 186 ms: 1.03x faster                                                        |
| sqlalchemy_declarative  | 83.9 ms                                                     | 81.7 ms: 1.03x faster                                                       |
| comprehensions          | 15.6 us                                                     | 15.2 us: 1.03x faster                                                       |
| 2to3                    | 207 ms                                                      | 202 ms: 1.03x faster                                                        |
| sqlalchemy_imperative   | 10.5 ms                                                     | 10.3 ms: 1.02x faster                                                       |
| regex_v8                | 13.7 ms                                                     | 13.4 ms: 1.02x faster                                                       |
| sqlglot_transpile       | 1.15 ms                                                     | 1.12 ms: 1.02x faster                                                       |
| nqueens                 | 66.1 ms                                                     | 64.6 ms: 1.02x faster                                                       |
| unpickle_pure_python    | 152 us                                                      | 149 us: 1.02x faster                                                        |
| sqlglot_parse           | 939 us                                                      | 920 us: 1.02x faster                                                        |
| xml_etree_generate      | 52.2 ms                                                     | 51.2 ms: 1.02x faster                                                       |
| thrift                  | 501 us                                                      | 491 us: 1.02x faster                                                        |
| sympy_sum               | 100.0 ms                                                    | 98.2 ms: 1.02x faster                                                       |
| python_startup          | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                       |
| xml_etree_iterparse     | 63.0 ms                                                     | 61.9 ms: 1.02x faster                                                       |
| sympy_expand            | 299 ms                                                      | 294 ms: 1.02x faster                                                        |
| async_tree_io           | 753 ms                                                      | 740 ms: 1.02x faster                                                        |
| deepcopy                | 242 us                                                      | 239 us: 1.02x faster                                                        |
| unpickle                | 7.82 us                                                     | 7.70 us: 1.02x faster                                                       |
| regex_compile           | 90.8 ms                                                     | 89.5 ms: 1.02x faster                                                       |
| go                      | 98.8 ms                                                     | 97.5 ms: 1.01x faster                                                       |
| pidigits                | 149 ms                                                      | 147 ms: 1.01x faster                                                        |
| generators              | 34.0 ms                                                     | 33.5 ms: 1.01x faster                                                       |
| python_startup_no_site  | 15.5 ms                                                     | 15.3 ms: 1.01x faster                                                       |
| logging_format          | 7.06 us                                                     | 6.97 us: 1.01x faster                                                       |
| pprint_safe_repr        | 519 ms                                                      | 512 ms: 1.01x faster                                                        |
| sympy_integrate         | 13.7 ms                                                     | 13.5 ms: 1.01x faster                                                       |
| pprint_pformat          | 1.06 sec                                                    | 1.05 sec: 1.01x faster                                                      |
| async_tree_none         | 314 ms                                                      | 310 ms: 1.01x faster                                                        |
| dulwich_log             | 44.1 ms                                                     | 43.6 ms: 1.01x faster                                                       |
| sympy_str               | 184 ms                                                      | 182 ms: 1.01x faster                                                        |
| docutils                | 1.59 sec                                                    | 1.57 sec: 1.01x faster                                                      |
| pickle_list             | 2.68 us                                                     | 2.65 us: 1.01x faster                                                       |
| nbody                   | 69.3 ms                                                     | 68.6 ms: 1.01x faster                                                       |
| float                   | 54.4 ms                                                     | 53.9 ms: 1.01x faster                                                       |
| meteor_contest          | 75.0 ms                                                     | 74.3 ms: 1.01x faster                                                       |
| django_template         | 24.0 ms                                                     | 23.8 ms: 1.01x faster                                                       |
| pyflate                 | 305 ms                                                      | 303 ms: 1.01x faster                                                        |
| richards                | 30.8 ms                                                     | 30.6 ms: 1.01x faster                                                       |
| hexiom                  | 4.51 ms                                                     | 4.48 ms: 1.01x faster                                                       |
| telco                   | 3.93 ms                                                     | 3.91 ms: 1.01x faster                                                       |
| unpickle_list           | 2.57 us                                                     | 2.55 us: 1.01x faster                                                       |
| deltablue               | 2.63 ms                                                     | 2.61 ms: 1.01x faster                                                       |
| logging_simple          | 6.60 us                                                     | 6.57 us: 1.01x faster                                                       |
| flaskblogging           | 2.03 sec                                                    | 2.04 sec: 1.01x slower                                                      |
| crypto_pyaes            | 48.2 ms                                                     | 48.5 ms: 1.01x slower                                                       |
| pickle                  | 6.53 us                                                     | 6.60 us: 1.01x slower                                                       |
| scimark_sor             | 76.4 ms                                                     | 77.3 ms: 1.01x slower                                                       |
| coroutines              | 14.7 ms                                                     | 14.9 ms: 1.01x slower                                                       |
| dask                    | 262 ms                                                      | 267 ms: 1.02x slower                                                        |
| scimark_lu              | 62.3 ms                                                     | 63.4 ms: 1.02x slower                                                       |
| pickle_dict             | 17.8 us                                                     | 18.2 us: 1.02x slower                                                       |
| tornado_http            | 89.9 ms                                                     | 92.1 ms: 1.02x slower                                                       |
| chaos                   | 46.8 ms                                                     | 48.0 ms: 1.03x slower                                                       |
| fannkuch                | 248 ms                                                      | 256 ms: 1.03x slower                                                        |
| pathlib                 | 69.4 ms                                                     | 72.1 ms: 1.04x slower                                                       |
| scimark_fft             | 181 ms                                                      | 189 ms: 1.04x slower                                                        |
| spectral_norm           | 69.9 ms                                                     | 73.2 ms: 1.05x slower                                                       |
| regex_effbot            | 1.52 ms                                                     | 1.60 ms: 1.05x slower                                                       |
| json_loads              | 12.9 us                                                     | 13.7 us: 1.06x slower                                                       |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.81 ms: 1.08x slower                                                       |
| asyncio_tcp             | 614 ms                                                      | 688 ms: 1.12x slower                                                        |
| mypy2                   | 226 ms                                                      | 276 ms: 1.22x slower                                                        |
| coverage                | 43.0 ms                                                     | 53.2 ms: 1.24x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.01x faster                                                                |

Benchmark hidden because not significant (11): async_tree_cpu_io_mixed, pylint, deepcopy_memo, scimark_monte_carlo, raytrace, bench_mp_pool, bench_thread_pool, logging_silent, aiohttp, async_tree_memoization, json
Ignored benchmarks (8) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 99.96% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
