
# Results vs. 3.11.0

- fork: python
- ref: 6c13e13b13bebfdde8ad
- machine: windows-amd64
- commit hash: 6c13e13
- commit date: 2023-09-13
- overall geometric mean: 1.04x faster
- HPT reliability: 75.09%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                                     |
| tornado_http   | 91.8 ms                                                     | 89.3 ms: 1.03x faster                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 148 ms                                                      | 151 ms: 1.02x slower                                                       |
| float          | 54.6 ms                                                     | 55.8 ms: 1.02x slower                                                      |
| nbody          | 70.0 ms                                                     | 74.6 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 115 ms                                                      | 118 ms: 1.02x slower                                                       |
| regex_effbot   | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                                      |
| regex_v8       | 13.8 ms                                                     | 14.9 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                       | 1.04x slower                                                               |

Benchmark hidden because not significant (1): regex_compile

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.56 ms                                                     | 5.64 ms: 1.34x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 137 us: 1.11x faster                                                       |
| xml_etree_parse      | 95.9 ms                                                     | 92.6 ms: 1.04x faster                                                      |
| pickle_pure_python   | 200 us                                                      | 193 us: 1.03x faster                                                       |
| unpickle             | 8.09 us                                                     | 8.21 us: 1.02x slower                                                      |
| xml_etree_iterparse  | 62.6 ms                                                     | 64.3 ms: 1.03x slower                                                      |
| xml_etree_process    | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                                      |
| json_loads           | 12.9 us                                                     | 13.5 us: 1.05x slower                                                      |
| tomli_loads          | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                     |
| xml_etree_generate   | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                                      |
| unpickle_list        | 2.55 us                                                     | 2.73 us: 1.07x slower                                                      |
| pickle               | 6.61 us                                                     | 7.34 us: 1.11x slower                                                      |
| pickle_list          | 2.68 us                                                     | 3.43 us: 1.28x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.01x slower                                                               |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                                      |
| python_startup         | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.05x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|-----------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 7.26 ms                                                     | 7.41 ms: 1.02x slower                                                      |

All benchmarks:
===============

| Benchmark                | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230913-pythonperf1-amd64-python-6c13e13b13bebfdde8ad-3.13.0a0-6c13e13 |
|--------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 322 us                                                      | 99.4 us: 3.24x faster                                                      |
| generators               | 33.8 ms                                                     | 22.7 ms: 1.49x faster                                                      |
| asyncio_tcp              | 699 ms                                                      | 471 ms: 1.48x faster                                                       |
| json_dumps               | 7.56 ms                                                     | 5.64 ms: 1.34x faster                                                      |
| coverage                 | 55.9 ms                                                     | 44.5 ms: 1.25x faster                                                      |
| raytrace                 | 211 ms                                                      | 171 ms: 1.23x faster                                                       |
| async_tree_none          | 320 ms                                                      | 269 ms: 1.19x faster                                                       |
| unpack_sequence          | 46.1 ns                                                     | 38.8 ns: 1.19x faster                                                      |
| deltablue                | 2.61 ms                                                     | 2.20 ms: 1.19x faster                                                      |
| sqlglot_parse            | 952 us                                                      | 815 us: 1.17x faster                                                       |
| chaos                    | 47.1 ms                                                     | 40.9 ms: 1.15x faster                                                      |
| asyncio_tcp_ssl          | 2.11 sec                                                    | 1.84 sec: 1.15x faster                                                     |
| richards_super           | 37.5 ms                                                     | 32.7 ms: 1.15x faster                                                      |
| mdp                      | 1.67 sec                                                    | 1.47 sec: 1.14x faster                                                     |
| sqlglot_transpile        | 1.16 ms                                                     | 1.04 ms: 1.12x faster                                                      |
| comprehensions           | 15.9 us                                                     | 14.2 us: 1.12x faster                                                      |
| unpickle_pure_python     | 152 us                                                      | 137 us: 1.11x faster                                                       |
| json                     | 3.25 ms                                                     | 2.95 ms: 1.10x faster                                                      |
| logging_silent           | 69.8 ns                                                     | 63.5 ns: 1.10x faster                                                      |
| hexiom                   | 4.55 ms                                                     | 4.18 ms: 1.09x faster                                                      |
| async_tree_memoization   | 371 ms                                                      | 343 ms: 1.08x faster                                                       |
| async_tree_io            | 779 ms                                                      | 724 ms: 1.08x faster                                                       |
| richards                 | 30.6 ms                                                     | 28.5 ms: 1.07x faster                                                      |
| mypy2                    | 229 ms                                                      | 214 ms: 1.07x faster                                                       |
| go                       | 97.3 ms                                                     | 91.3 ms: 1.07x faster                                                      |
| async_tree_cpu_io_mixed  | 501 ms                                                      | 471 ms: 1.06x faster                                                       |
| nqueens                  | 64.9 ms                                                     | 61.0 ms: 1.06x faster                                                      |
| deepcopy                 | 246 us                                                      | 234 us: 1.05x faster                                                       |
| deepcopy_memo            | 25.2 us                                                     | 24.0 us: 1.05x faster                                                      |
| scimark_sparse_mat_mult  | 2.57 ms                                                     | 2.46 ms: 1.05x faster                                                      |
| scimark_lu               | 63.5 ms                                                     | 60.8 ms: 1.04x faster                                                      |
| sqlglot_normalize        | 190 ms                                                      | 183 ms: 1.04x faster                                                       |
| spectral_norm            | 67.9 ms                                                     | 65.2 ms: 1.04x faster                                                      |
| crypto_pyaes             | 47.6 ms                                                     | 45.7 ms: 1.04x faster                                                      |
| scimark_monte_carlo      | 44.6 ms                                                     | 42.9 ms: 1.04x faster                                                      |
| logging_simple           | 6.61 us                                                     | 6.36 us: 1.04x faster                                                      |
| xml_etree_parse          | 95.9 ms                                                     | 92.6 ms: 1.04x faster                                                      |
| pickle_pure_python       | 200 us                                                      | 193 us: 1.03x faster                                                       |
| logging_format           | 7.01 us                                                     | 6.82 us: 1.03x faster                                                      |
| tornado_http             | 91.8 ms                                                     | 89.3 ms: 1.03x faster                                                      |
| meteor_contest           | 74.7 ms                                                     | 73.6 ms: 1.02x faster                                                      |
| bench_thread_pool        | 852 us                                                      | 842 us: 1.01x faster                                                       |
| sqlglot_optimize         | 34.9 ms                                                     | 34.5 ms: 1.01x faster                                                      |
| docutils                 | 1.60 sec                                                    | 1.62 sec: 1.01x slower                                                     |
| pprint_safe_repr         | 512 ms                                                      | 517 ms: 1.01x slower                                                       |
| deepcopy_reduce          | 2.07 us                                                     | 2.10 us: 1.01x slower                                                      |
| unpickle                 | 8.09 us                                                     | 8.21 us: 1.02x slower                                                      |
| pidigits                 | 148 ms                                                      | 151 ms: 1.02x slower                                                       |
| mako                     | 7.26 ms                                                     | 7.41 ms: 1.02x slower                                                      |
| pprint_pformat           | 1.04 sec                                                    | 1.06 sec: 1.02x slower                                                     |
| float                    | 54.6 ms                                                     | 55.8 ms: 1.02x slower                                                      |
| gc_traversal             | 1.46 ms                                                     | 1.49 ms: 1.02x slower                                                      |
| regex_dna                | 115 ms                                                      | 118 ms: 1.02x slower                                                       |
| dulwich_log              | 44.5 ms                                                     | 45.6 ms: 1.02x slower                                                      |
| xml_etree_iterparse      | 62.6 ms                                                     | 64.3 ms: 1.03x slower                                                      |
| xml_etree_process        | 37.1 ms                                                     | 38.1 ms: 1.03x slower                                                      |
| scimark_fft              | 178 ms                                                      | 184 ms: 1.03x slower                                                       |
| fannkuch                 | 252 ms                                                      | 261 ms: 1.03x slower                                                       |
| sqlite_synth             | 1.68 us                                                     | 1.74 us: 1.04x slower                                                      |
| python_startup_no_site   | 15.9 ms                                                     | 16.5 ms: 1.04x slower                                                      |
| json_loads               | 12.9 us                                                     | 13.5 us: 1.05x slower                                                      |
| regex_effbot             | 1.50 ms                                                     | 1.57 ms: 1.05x slower                                                      |
| tomli_loads              | 1.41 sec                                                    | 1.49 sec: 1.05x slower                                                     |
| create_gc_cycles         | 693 us                                                      | 730 us: 1.05x slower                                                       |
| python_startup           | 18.7 ms                                                     | 19.8 ms: 1.06x slower                                                      |
| nbody                    | 70.0 ms                                                     | 74.6 ms: 1.07x slower                                                      |
| xml_etree_generate       | 52.2 ms                                                     | 55.8 ms: 1.07x slower                                                      |
| unpickle_list            | 2.55 us                                                     | 2.73 us: 1.07x slower                                                      |
| regex_v8                 | 13.8 ms                                                     | 14.9 ms: 1.07x slower                                                      |
| bench_mp_pool            | 62.5 ms                                                     | 67.7 ms: 1.08x slower                                                      |
| scimark_sor              | 75.6 ms                                                     | 82.8 ms: 1.10x slower                                                      |
| pathlib                  | 71.4 ms                                                     | 78.3 ms: 1.10x slower                                                      |
| pickle                   | 6.61 us                                                     | 7.34 us: 1.11x slower                                                      |
| telco                    | 3.90 ms                                                     | 4.79 ms: 1.23x slower                                                      |
| pickle_list              | 2.68 us                                                     | 3.43 us: 1.28x slower                                                      |
| pycparser                | 691 ms                                                      | 894 ms: 1.29x slower                                                       |
| async_generators         | 178 ms                                                      | 246 ms: 1.38x slower                                                       |
| dask                     | 264 ms                                                      | 370 ms: 1.40x slower                                                       |
| Geometric mean           | (ref)                                                       | 1.04x faster                                                               |

Benchmark hidden because not significant (4): regex_compile, coroutines, pyflate, pickle_dict
Ignored benchmarks (16) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 75.09% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
