
# Results vs. 3.10.4

- fork: python
- ref: 8d32a5c8c4e9c90b0a21
- machine: windows-amd64
- commit hash: 8d32a5c
- commit date: 2022-05-06
- overall geometric mean: 1.11x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 203 ms: 1.17x faster                                                       |
| chameleon      | 6.02 ms                                                     | 5.45 ms: 1.10x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.57 sec: 1.19x faster                                                     |
| html5lib       | 47.5 ms                                                     | 38.3 ms: 1.24x faster                                                      |
| tornado_http   | 106 ms                                                      | 89.7 ms: 1.18x faster                                                      |
| Geometric mean | (ref)                                                       | 1.18x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 751 ms: 1.43x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 370 ms: 1.37x faster                                                       |
| async_tree_none         | 424 ms                                                      | 311 ms: 1.36x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 499 ms: 1.24x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.35x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.5 ms: 1.16x faster                                                      |
| nbody          | 71.0 ms                                                     | 67.9 ms: 1.05x faster                                                      |
| pidigits       | 146 ms                                                      | 147 ms: 1.00x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 90.5 ms: 1.13x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                                      |
| regex_dna      | 129 ms                                                      | 121 ms: 1.07x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.47 ms: 1.06x faster                                                      |
| Geometric mean | (ref)                                                       | 1.09x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 204 us: 1.27x faster                                                       |
| unpickle_pure_python | 177 us                                                      | 152 us: 1.16x faster                                                       |
| unpickle             | 9.11 us                                                     | 7.87 us: 1.16x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                                      |
| json_dumps           | 8.77 ms                                                     | 7.72 ms: 1.14x faster                                                      |
| json_loads           | 14.2 us                                                     | 13.4 us: 1.06x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 61.1 ms: 1.06x faster                                                      |
| pickle               | 6.87 us                                                     | 6.59 us: 1.04x faster                                                      |
| unpickle_list        | 2.68 us                                                     | 2.58 us: 1.04x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 93.1 ms: 1.04x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 53.0 ms: 1.03x faster                                                      |
| pickle_list          | 2.69 us                                                     | 2.67 us: 1.01x faster                                                      |
| pickle_dict          | 17.1 us                                                     | 17.1 us: 1.00x faster                                                      |
| Geometric mean       | (ref)                                                       | 1.09x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                      |
| Geometric mean | (ref)                                                       | 1.04x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.13 ms: 1.26x faster                                                      |
| django_template | 28.8 ms                                                     | 24.0 ms: 1.20x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 17.7 ms: 1.07x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.12x faster                                                               |

Benchmark hidden because not significant (1): genshi_xml

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220506-pythonperf1-amd64-python-8d32a5c8c4e9c90b0a21-3.11.0b1-8d32a5c |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.66 ms: 1.55x faster                                                      |
| async_tree_io           | 1.07 sec                                                    | 751 ms: 1.43x faster                                                       |
| go                      | 135 ms                                                      | 97.9 ms: 1.38x faster                                                      |
| async_tree_memoization  | 505 ms                                                      | 370 ms: 1.37x faster                                                       |
| scimark_sor             | 105 ms                                                      | 77.1 ms: 1.36x faster                                                      |
| async_tree_none         | 424 ms                                                      | 311 ms: 1.36x faster                                                       |
| richards                | 40.6 ms                                                     | 30.1 ms: 1.35x faster                                                      |
| scimark_lu              | 84.0 ms                                                     | 62.7 ms: 1.34x faster                                                      |
| logging_silent          | 93.4 ns                                                     | 70.2 ns: 1.33x faster                                                      |
| pyflate                 | 402 ms                                                      | 303 ms: 1.33x faster                                                       |
| raytrace                | 266 ms                                                      | 203 ms: 1.31x faster                                                       |
| scimark_monte_carlo     | 58.0 ms                                                     | 45.0 ms: 1.29x faster                                                      |
| crypto_pyaes            | 63.1 ms                                                     | 49.1 ms: 1.29x faster                                                      |
| pickle_pure_python      | 259 us                                                      | 204 us: 1.27x faster                                                       |
| mako                    | 8.98 ms                                                     | 7.13 ms: 1.26x faster                                                      |
| mypy2                   | 347 ms                                                      | 277 ms: 1.25x faster                                                       |
| html5lib                | 47.5 ms                                                     | 38.3 ms: 1.24x faster                                                      |
| async_tree_cpu_io_mixed | 617 ms                                                      | 499 ms: 1.24x faster                                                       |
| thrift                  | 623 us                                                      | 504 us: 1.23x faster                                                       |
| hexiom                  | 5.59 ms                                                     | 4.59 ms: 1.22x faster                                                      |
| chaos                   | 59.5 ms                                                     | 48.9 ms: 1.22x faster                                                      |
| pycparser               | 905 ms                                                      | 748 ms: 1.21x faster                                                       |
| create_gc_cycles        | 800 us                                                      | 663 us: 1.21x faster                                                       |
| django_template         | 28.8 ms                                                     | 24.0 ms: 1.20x faster                                                      |
| async_generators        | 219 ms                                                      | 182 ms: 1.20x faster                                                       |
| docutils                | 1.88 sec                                                    | 1.57 sec: 1.19x faster                                                     |
| tornado_http            | 106 ms                                                      | 89.7 ms: 1.18x faster                                                      |
| 2to3                    | 239 ms                                                      | 203 ms: 1.17x faster                                                       |
| unpickle_pure_python    | 177 us                                                      | 152 us: 1.16x faster                                                       |
| unpickle                | 9.11 us                                                     | 7.87 us: 1.16x faster                                                      |
| float                   | 61.7 ms                                                     | 53.5 ms: 1.16x faster                                                      |
| deepcopy_memo           | 29.0 us                                                     | 25.1 us: 1.15x faster                                                      |
| xml_etree_process       | 43.1 ms                                                     | 37.6 ms: 1.15x faster                                                      |
| dulwich_log             | 48.6 ms                                                     | 42.5 ms: 1.14x faster                                                      |
| dask                    | 305 ms                                                      | 268 ms: 1.14x faster                                                       |
| json_dumps              | 8.77 ms                                                     | 7.72 ms: 1.14x faster                                                      |
| spectral_norm           | 78.9 ms                                                     | 69.6 ms: 1.13x faster                                                      |
| pprint_pformat          | 1.22 sec                                                    | 1.08 sec: 1.13x faster                                                     |
| pprint_safe_repr        | 594 ms                                                      | 525 ms: 1.13x faster                                                       |
| regex_compile           | 102 ms                                                      | 90.5 ms: 1.13x faster                                                      |
| aiohttp                 | 961 us                                                      | 854 us: 1.13x faster                                                       |
| sqlite_synth            | 1.90 us                                                     | 1.69 us: 1.12x faster                                                      |
| sqlglot_optimize        | 39.4 ms                                                     | 35.6 ms: 1.11x faster                                                      |
| chameleon               | 6.02 ms                                                     | 5.45 ms: 1.10x faster                                                      |
| sympy_integrate         | 15.0 ms                                                     | 13.6 ms: 1.10x faster                                                      |
| sympy_expand            | 320 ms                                                      | 293 ms: 1.09x faster                                                       |
| sympy_sum               | 105 ms                                                      | 96.9 ms: 1.09x faster                                                      |
| pylint                  | 341 ms                                                      | 314 ms: 1.09x faster                                                       |
| logging_simple          | 6.28 us                                                     | 5.80 us: 1.08x faster                                                      |
| regex_v8                | 15.0 ms                                                     | 13.9 ms: 1.08x faster                                                      |
| logging_format          | 6.73 us                                                     | 6.25 us: 1.08x faster                                                      |
| python_startup          | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                      |
| regex_dna               | 129 ms                                                      | 121 ms: 1.07x faster                                                       |
| genshi_text             | 18.8 ms                                                     | 17.7 ms: 1.07x faster                                                      |
| asyncio_tcp             | 717 ms                                                      | 673 ms: 1.07x faster                                                       |
| regex_effbot            | 1.56 ms                                                     | 1.47 ms: 1.06x faster                                                      |
| json_loads              | 14.2 us                                                     | 13.4 us: 1.06x faster                                                      |
| sqlglot_transpile       | 1.45 ms                                                     | 1.37 ms: 1.06x faster                                                      |
| sympy_str               | 193 ms                                                      | 183 ms: 1.06x faster                                                       |
| sqlglot_normalize       | 207 ms                                                      | 196 ms: 1.06x faster                                                       |
| xml_etree_iterparse     | 64.5 ms                                                     | 61.1 ms: 1.06x faster                                                      |
| deepcopy_reduce         | 2.22 us                                                     | 2.12 us: 1.05x faster                                                      |
| mdp                     | 1.71 sec                                                    | 1.63 sec: 1.05x faster                                                     |
| nbody                   | 71.0 ms                                                     | 67.9 ms: 1.05x faster                                                      |
| pickle                  | 6.87 us                                                     | 6.59 us: 1.04x faster                                                      |
| sqlglot_parse           | 1.20 ms                                                     | 1.15 ms: 1.04x faster                                                      |
| scimark_fft             | 187 ms                                                      | 180 ms: 1.04x faster                                                       |
| unpickle_list           | 2.68 us                                                     | 2.58 us: 1.04x faster                                                      |
| xml_etree_parse         | 96.8 ms                                                     | 93.1 ms: 1.04x faster                                                      |
| xml_etree_generate      | 54.5 ms                                                     | 53.0 ms: 1.03x faster                                                      |
| bench_thread_pool       | 913 us                                                      | 888 us: 1.03x faster                                                       |
| deepcopy                | 259 us                                                      | 252 us: 1.03x faster                                                       |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.60 ms: 1.03x faster                                                      |
| fannkuch                | 258 ms                                                      | 252 ms: 1.02x faster                                                       |
| pathlib                 | 72.8 ms                                                     | 71.4 ms: 1.02x faster                                                      |
| coroutines              | 15.5 ms                                                     | 15.2 ms: 1.02x faster                                                      |
| nqueens                 | 68.3 ms                                                     | 67.6 ms: 1.01x faster                                                      |
| pickle_list             | 2.69 us                                                     | 2.67 us: 1.01x faster                                                      |
| pickle_dict             | 17.1 us                                                     | 17.1 us: 1.00x faster                                                      |
| pidigits                | 146 ms                                                      | 147 ms: 1.00x slower                                                       |
| flaskblogging           | 2.04 sec                                                    | 2.05 sec: 1.01x slower                                                     |
| bench_mp_pool           | 59.9 ms                                                     | 60.6 ms: 1.01x slower                                                      |
| gc_traversal            | 1.40 ms                                                     | 1.42 ms: 1.01x slower                                                      |
| meteor_contest          | 73.8 ms                                                     | 75.5 ms: 1.02x slower                                                      |
| telco                   | 3.82 ms                                                     | 3.94 ms: 1.03x slower                                                      |
| unpack_sequence         | 40.0 ns                                                     | 42.2 ns: 1.05x slower                                                      |
| generators              | 31.8 ms                                                     | 33.9 ms: 1.07x slower                                                      |
| comprehensions          | 16.6 us                                                     | 17.8 us: 1.07x slower                                                      |
| coverage                | 38.4 ms                                                     | 103 ms: 2.67x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.11x faster                                                               |

Benchmark hidden because not significant (3): python_startup_no_site, genshi_xml, json
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.07x
