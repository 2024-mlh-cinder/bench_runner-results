
# Results vs. 3.11.0

- fork: python
- ref: 982f1b7d6dc2f13b9607
- machine: windows-amd64
- commit hash: 982f1b7
- commit date: 2023-10-10
- overall geometric mean: 1.04x faster
- HPT reliability: 66.33%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.63 sec: 1.02x slower                                                     |
| tornado_http   | 91.8 ms                                                     | 89.2 ms: 1.03x faster                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 150 ms: 1.01x slower                                                       |
| float          | 54.6 ms                                                     | 55.2 ms: 1.01x slower                                                      |
| nbody          | 70.0 ms                                                     | 75.1 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 90.6 ms                                                     | 92.4 ms: 1.02x slower                                                      |
| regex_dna      | 115 ms                                                      | 123 ms: 1.07x slower                                                       |
| regex_effbot   | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                                      |
| regex_v8       | 13.8 ms                                                     | 15.1 ms: 1.09x slower                                                      |
| Geometric mean | (ref)                                                       | 1.06x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.81 ms: 1.30x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 141 us: 1.07x faster                                                       |
| xml_etree_parse      | 95.9 ms                                                     | 91.8 ms: 1.04x faster                                                      |
| pickle_pure_python   | 200 us                                                      | 197 us: 1.02x faster                                                       |
| xml_etree_iterparse  | 62.6 ms                                                     | 64.4 ms: 1.03x slower                                                      |
| json_loads           | 12.9 us                                                     | 13.6 us: 1.06x slower                                                      |
| tomli_loads          | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                                     |
| unpickle_list        | 2.55 us                                                     | 2.71 us: 1.07x slower                                                      |
| xml_etree_process    | 37.1 ms                                                     | 39.6 ms: 1.07x slower                                                      |
| pickle_list          | 2.68 us                                                     | 2.87 us: 1.07x slower                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 56.9 ms: 1.09x slower                                                      |
| pickle               | 6.61 us                                                     | 7.26 us: 1.10x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (2): pickle_dict, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                                      |
| python_startup         | 18.7 ms                                                     | 19.3 ms: 1.03x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.02x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.19 ms: 1.01x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 103 us: 3.13x faster                                                       |
| generators               | 33.8 ms                                                     | 22.4 ms: 1.51x faster                                                      |
| asyncio_tcp              | 699 ms                                                      | 474 ms: 1.47x faster                                                       |
| json_dumps               | 7.56 ms                                                     | 5.81 ms: 1.30x faster                                                      |
| coverage                 | 55.9 ms                                                     | 46.2 ms: 1.21x faster                                                      |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.77 sec: 1.20x faster                                                     |
| raytrace                 | 211 ms                                                      | 178 ms: 1.19x faster                                                       |
| deltablue                | 2.61 ms                                                     | 2.20 ms: 1.19x faster                                                      |
| async_tree_none          | 320 ms                                                      | 271 ms: 1.18x faster                                                       |
| mdp                      | 1.67 sec                                                    | 1.43 sec: 1.16x faster                                                     |
| richards_super           | 37.5 ms                                                     | 32.5 ms: 1.15x faster                                                      |
| sqlglot_parse            | 952 us                                                      | 828 us: 1.15x faster                                                       |
| unpack_sequence          | 46.1 ns                                                     | 41.2 ns: 1.12x faster                                                      |
| json                     | 3.25 ms                                                     | 2.92 ms: 1.12x faster                                                      |
| chaos                    | 47.1 ms                                                     | 42.4 ms: 1.11x faster                                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 455 ms: 1.10x faster                                                       |
| sqlglot_transpile        | 1.16 ms                                                     | 1.06 ms: 1.10x faster                                                      |
| logging_silent           | 69.8 ns                                                     | 63.6 ns: 1.10x faster                                                      |
| comprehensions           | 15.9 us                                                     | 14.5 us: 1.10x faster                                                      |
| hexiom                   | 4.55 ms                                                     | 4.22 ms: 1.08x faster                                                      |
| unpickle_pure_python     | 152 us                                                      | 141 us: 1.07x faster                                                       |
| async_tree_memoization   | 371 ms                                                      | 346 ms: 1.07x faster                                                       |
| async_tree_io            | 779 ms                                                      | 729 ms: 1.07x faster                                                       |
| crypto_pyaes             | 47.6 ms                                                     | 44.7 ms: 1.06x faster                                                      |
| nqueens                  | 64.9 ms                                                     | 61.2 ms: 1.06x faster                                                      |
| go                       | 97.3 ms                                                     | 91.8 ms: 1.06x faster                                                      |
| richards                 | 30.6 ms                                                     | 28.9 ms: 1.06x faster                                                      |
| mypy2                    | 229 ms                                                      | 217 ms: 1.06x faster                                                       |
| scimark_lu               | 63.5 ms                                                     | 60.4 ms: 1.05x faster                                                      |
| xml_etree_parse          | 95.9 ms                                                     | 91.8 ms: 1.04x faster                                                      |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.48 ms: 1.04x faster                                                      |
| spectral_norm            | 67.9 ms                                                     | 65.6 ms: 1.04x faster                                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 43.1 ms: 1.03x faster                                                      |
| tornado_http             | 91.8 ms                                                     | 89.2 ms: 1.03x faster                                                      |
| sqlglot_normalize        | 190 ms                                                      | 186 ms: 1.02x faster                                                       |
| bench_thread_pool        | 852 us                                                      | 835 us: 1.02x faster                                                       |
| pickle_pure_python       | 200 us                                                      | 197 us: 1.02x faster                                                       |
| deepcopy                 | 246 us                                                      | 242 us: 1.01x faster                                                       |
| deepcopy_memo            | 25.2 us                                                     | 24.9 us: 1.01x faster                                                      |
| mako                     | 7.26 ms                                                     | 7.19 ms: 1.01x faster                                                      |
| logging_simple           | 6.61 us                                                     | 6.55 us: 1.01x faster                                                      |
| logging_format           | 7.01 us                                                     | 6.96 us: 1.01x faster                                                      |
| sqlglot_optimize         | 34.9 ms                                                     | 35.2 ms: 1.01x slower                                                      |
| coroutines               | 14.6 ms                                                     | 14.8 ms: 1.01x slower                                                      |
| pidigits                 | 148 ms                                                      | 150 ms: 1.01x slower                                                       |
| float                    | 54.6 ms                                                     | 55.2 ms: 1.01x slower                                                      |
| sqlite_synth             | 1.68 us                                                     | 1.70 us: 1.01x slower                                                      |
| python_startup_no_site   | 15.9 ms                                                     | 16.1 ms: 1.01x slower                                                      |
| meteor_contest           | 74.7 ms                                                     | 75.9 ms: 1.01x slower                                                      |
| docutils                 | 1.60 sec                                                    | 1.63 sec: 1.02x slower                                                     |
| gc_traversal             | 1.46 ms                                                     | 1.48 ms: 1.02x slower                                                      |
| bench_mp_pool            | 62.5 ms                                                     | 63.7 ms: 1.02x slower                                                      |
| regex_compile            | 90.6 ms                                                     | 92.4 ms: 1.02x slower                                                      |
| dulwich_log              | 44.5 ms                                                     | 45.4 ms: 1.02x slower                                                      |
| scimark_fft              | 178 ms                                                      | 183 ms: 1.02x slower                                                       |
| xml_etree_iterparse      | 62.6 ms                                                     | 64.4 ms: 1.03x slower                                                      |
| fannkuch                 | 252 ms                                                      | 260 ms: 1.03x slower                                                       |
| python_startup           | 18.7 ms                                                     | 19.3 ms: 1.03x slower                                                      |
| create_gc_cycles         | 693 us                                                      | 720 us: 1.04x slower                                                       |
| pprint_safe_repr         | 512 ms                                                      | 536 ms: 1.05x slower                                                       |
| json_loads               | 12.9 us                                                     | 13.6 us: 1.06x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.10 sec: 1.06x slower                                                     |
| tomli_loads              | 1.41 sec                                                    | 1.50 sec: 1.06x slower                                                     |
| deepcopy_reduce          | 2.07 us                                                     | 2.20 us: 1.06x slower                                                      |
| unpickle_list            | 2.55 us                                                     | 2.71 us: 1.07x slower                                                      |
| regex_dna                | 115 ms                                                      | 123 ms: 1.07x slower                                                       |
| xml_etree_process        | 37.1 ms                                                     | 39.6 ms: 1.07x slower                                                      |
| pickle_list              | 2.68 us                                                     | 2.87 us: 1.07x slower                                                      |
| nbody                    | 70.0 ms                                                     | 75.1 ms: 1.07x slower                                                      |
| regex_effbot             | 1.50 ms                                                     | 1.61 ms: 1.08x slower                                                      |
| xml_etree_generate       | 52.2 ms                                                     | 56.9 ms: 1.09x slower                                                      |
| pathlib                  | 71.4 ms                                                     | 77.8 ms: 1.09x slower                                                      |
| regex_v8                 | 13.8 ms                                                     | 15.1 ms: 1.09x slower                                                      |
| pickle                   | 6.61 us                                                     | 7.26 us: 1.10x slower                                                      |
| scimark_sor              | 75.6 ms                                                     | 85.0 ms: 1.12x slower                                                      |
| telco                    | 3.90 ms                                                     | 4.72 ms: 1.21x slower                                                      |
| pycparser                | 691 ms                                                      | 901 ms: 1.30x slower                                                       |
| async_generators         | 178 ms                                                      | 245 ms: 1.38x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.04x faster                                                               |

Benchmark hidden because not significant (3): pickle_dict, pyflate, unpickle
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 66.33% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
