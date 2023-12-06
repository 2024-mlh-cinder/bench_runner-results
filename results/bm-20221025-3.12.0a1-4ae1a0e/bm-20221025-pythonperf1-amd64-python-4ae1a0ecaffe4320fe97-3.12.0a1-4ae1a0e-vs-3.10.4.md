
# Results vs. 3.10.4

- fork: python
- ref: 4ae1a0ecaffe4320fe97
- machine: windows-amd64
- commit hash: 4ae1a0e
- commit date: 2022-10-25
- overall geometric mean: 1.14x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 202 ms: 1.18x faster                                                       |
| chameleon      | 6.02 ms                                                     | 4.99 ms: 1.21x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                     |
| html5lib       | 47.5 ms                                                     | 38.1 ms: 1.25x faster                                                      |
| tornado_http   | 106 ms                                                      | 91.5 ms: 1.15x faster                                                      |
| Geometric mean | (ref)                                                       | 1.19x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 775 ms: 1.38x faster                                                       |
| async_tree_none         | 424 ms                                                      | 316 ms: 1.34x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 381 ms: 1.33x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 506 ms: 1.22x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.32x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.5 ms: 1.15x faster                                                      |
| nbody          | 71.0 ms                                                     | 67.2 ms: 1.06x faster                                                      |
| pidigits       | 146 ms                                                      | 148 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 86.3 ms: 1.18x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                                      |
| regex_dna      | 129 ms                                                      | 119 ms: 1.08x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.63 ms: 1.04x slower                                                      |
| Geometric mean | (ref)                                                       | 1.08x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.62 ms: 1.56x faster                                                      |
| pickle_pure_python   | 259 us                                                      | 196 us: 1.32x faster                                                       |
| unpickle_pure_python | 177 us                                                      | 143 us: 1.24x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 36.3 ms: 1.19x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 86.8 ms: 1.11x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 50.5 ms: 1.08x faster                                                      |
| json_loads           | 14.2 us                                                     | 13.5 us: 1.05x faster                                                      |
| pickle               | 6.87 us                                                     | 6.55 us: 1.05x faster                                                      |
| unpickle_list        | 2.68 us                                                     | 2.60 us: 1.03x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.87 us: 1.03x faster                                                      |
| pickle_list          | 2.69 us                                                     | 2.64 us: 1.02x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 63.6 ms: 1.01x faster                                                      |
| pickle_dict          | 17.1 us                                                     | 18.2 us: 1.06x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.12x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.2 ms: 1.08x faster                                                      |
| Geometric mean | (ref)                                                       | 1.04x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 6.93 ms: 1.30x faster                                                      |
| django_template | 28.8 ms                                                     | 23.8 ms: 1.21x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 17.1 ms: 1.10x faster                                                      |
| genshi_xml      | 39.4 ms                                                     | 37.8 ms: 1.04x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.16x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221025-pythonperf1-amd64-python-4ae1a0ecaffe4320fe97-3.12.0a1-4ae1a0e |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.51 ms: 1.64x faster                                                      |
| mypy2                   | 347 ms                                                      | 218 ms: 1.59x faster                                                       |
| json_dumps              | 8.77 ms                                                     | 5.62 ms: 1.56x faster                                                      |
| go                      | 135 ms                                                      | 93.8 ms: 1.44x faster                                                      |
| scimark_sor             | 105 ms                                                      | 73.8 ms: 1.43x faster                                                      |
| async_tree_io           | 1.07 sec                                                    | 775 ms: 1.38x faster                                                       |
| logging_silent          | 93.4 ns                                                     | 68.8 ns: 1.36x faster                                                      |
| pyflate                 | 402 ms                                                      | 297 ms: 1.35x faster                                                       |
| async_tree_none         | 424 ms                                                      | 316 ms: 1.34x faster                                                       |
| crypto_pyaes            | 63.1 ms                                                     | 47.2 ms: 1.34x faster                                                      |
| async_tree_memoization  | 505 ms                                                      | 381 ms: 1.33x faster                                                       |
| scimark_monte_carlo     | 58.0 ms                                                     | 43.8 ms: 1.33x faster                                                      |
| pickle_pure_python      | 259 us                                                      | 196 us: 1.32x faster                                                       |
| richards                | 40.6 ms                                                     | 31.0 ms: 1.31x faster                                                      |
| raytrace                | 266 ms                                                      | 204 ms: 1.31x faster                                                       |
| mako                    | 8.98 ms                                                     | 6.93 ms: 1.30x faster                                                      |
| chaos                   | 59.5 ms                                                     | 46.5 ms: 1.28x faster                                                      |
| thrift                  | 623 us                                                      | 486 us: 1.28x faster                                                       |
| sqlglot_transpile       | 1.45 ms                                                     | 1.14 ms: 1.27x faster                                                      |
| sqlglot_parse           | 1.20 ms                                                     | 951 us: 1.27x faster                                                       |
| scimark_lu              | 84.0 ms                                                     | 66.6 ms: 1.26x faster                                                      |
| pycparser               | 905 ms                                                      | 721 ms: 1.26x faster                                                       |
| html5lib                | 47.5 ms                                                     | 38.1 ms: 1.25x faster                                                      |
| unpickle_pure_python    | 177 us                                                      | 143 us: 1.24x faster                                                       |
| hexiom                  | 5.59 ms                                                     | 4.51 ms: 1.24x faster                                                      |
| pprint_pformat          | 1.22 sec                                                    | 1.00 sec: 1.22x faster                                                     |
| async_tree_cpu_io_mixed | 617 ms                                                      | 506 ms: 1.22x faster                                                       |
| django_template         | 28.8 ms                                                     | 23.8 ms: 1.21x faster                                                      |
| chameleon               | 6.02 ms                                                     | 4.99 ms: 1.21x faster                                                      |
| async_generators        | 219 ms                                                      | 181 ms: 1.21x faster                                                       |
| create_gc_cycles        | 800 us                                                      | 663 us: 1.21x faster                                                       |
| pprint_safe_repr        | 594 ms                                                      | 495 ms: 1.20x faster                                                       |
| xml_etree_process       | 43.1 ms                                                     | 36.3 ms: 1.19x faster                                                      |
| regex_compile           | 102 ms                                                      | 86.3 ms: 1.18x faster                                                      |
| 2to3                    | 239 ms                                                      | 202 ms: 1.18x faster                                                       |
| docutils                | 1.88 sec                                                    | 1.59 sec: 1.18x faster                                                     |
| deepcopy_memo           | 29.0 us                                                     | 24.7 us: 1.17x faster                                                      |
| tornado_http            | 106 ms                                                      | 91.5 ms: 1.15x faster                                                      |
| float                   | 61.7 ms                                                     | 53.5 ms: 1.15x faster                                                      |
| dask                    | 305 ms                                                      | 265 ms: 1.15x faster                                                       |
| sqlglot_optimize        | 39.4 ms                                                     | 34.4 ms: 1.15x faster                                                      |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.37 ms: 1.13x faster                                                      |
| sympy_integrate         | 15.0 ms                                                     | 13.4 ms: 1.12x faster                                                      |
| json                    | 3.10 ms                                                     | 2.77 ms: 1.12x faster                                                      |
| dulwich_log             | 48.6 ms                                                     | 43.5 ms: 1.12x faster                                                      |
| xml_etree_parse         | 96.8 ms                                                     | 86.8 ms: 1.11x faster                                                      |
| deepcopy                | 259 us                                                      | 235 us: 1.10x faster                                                       |
| genshi_text             | 18.8 ms                                                     | 17.1 ms: 1.10x faster                                                      |
| regex_v8                | 15.0 ms                                                     | 13.7 ms: 1.10x faster                                                      |
| sqlglot_normalize       | 207 ms                                                      | 188 ms: 1.10x faster                                                       |
| regex_dna               | 129 ms                                                      | 119 ms: 1.08x faster                                                       |
| fannkuch                | 258 ms                                                      | 238 ms: 1.08x faster                                                       |
| sympy_expand            | 320 ms                                                      | 296 ms: 1.08x faster                                                       |
| deepcopy_reduce         | 2.22 us                                                     | 2.05 us: 1.08x faster                                                      |
| bench_thread_pool       | 913 us                                                      | 844 us: 1.08x faster                                                       |
| mdp                     | 1.71 sec                                                    | 1.59 sec: 1.08x faster                                                     |
| python_startup          | 19.7 ms                                                     | 18.2 ms: 1.08x faster                                                      |
| xml_etree_generate      | 54.5 ms                                                     | 50.5 ms: 1.08x faster                                                      |
| pylint                  | 341 ms                                                      | 317 ms: 1.07x faster                                                       |
| spectral_norm           | 78.9 ms                                                     | 73.8 ms: 1.07x faster                                                      |
| sympy_sum               | 105 ms                                                      | 98.9 ms: 1.06x faster                                                      |
| comprehensions          | 16.6 us                                                     | 15.6 us: 1.06x faster                                                      |
| nbody                   | 71.0 ms                                                     | 67.2 ms: 1.06x faster                                                      |
| sqlite_synth            | 1.90 us                                                     | 1.80 us: 1.06x faster                                                      |
| sympy_str               | 193 ms                                                      | 183 ms: 1.06x faster                                                       |
| json_loads              | 14.2 us                                                     | 13.5 us: 1.05x faster                                                      |
| pickle                  | 6.87 us                                                     | 6.55 us: 1.05x faster                                                      |
| nqueens                 | 68.3 ms                                                     | 65.4 ms: 1.04x faster                                                      |
| genshi_xml              | 39.4 ms                                                     | 37.8 ms: 1.04x faster                                                      |
| coroutines              | 15.5 ms                                                     | 15.0 ms: 1.03x faster                                                      |
| unpickle_list           | 2.68 us                                                     | 2.60 us: 1.03x faster                                                      |
| meteor_contest          | 73.8 ms                                                     | 71.8 ms: 1.03x faster                                                      |
| unpickle                | 9.11 us                                                     | 8.87 us: 1.03x faster                                                      |
| pickle_list             | 2.69 us                                                     | 2.64 us: 1.02x faster                                                      |
| xml_etree_iterparse     | 64.5 ms                                                     | 63.6 ms: 1.01x faster                                                      |
| telco                   | 3.82 ms                                                     | 3.85 ms: 1.01x slower                                                      |
| pidigits                | 146 ms                                                      | 148 ms: 1.01x slower                                                       |
| pathlib                 | 72.8 ms                                                     | 74.0 ms: 1.02x slower                                                      |
| bench_mp_pool           | 59.9 ms                                                     | 60.9 ms: 1.02x slower                                                      |
| gc_traversal            | 1.40 ms                                                     | 1.42 ms: 1.02x slower                                                      |
| regex_effbot            | 1.56 ms                                                     | 1.63 ms: 1.04x slower                                                      |
| unpack_sequence         | 40.0 ns                                                     | 42.3 ns: 1.06x slower                                                      |
| pickle_dict             | 17.1 us                                                     | 18.2 us: 1.06x slower                                                      |
| logging_format          | 6.73 us                                                     | 7.28 us: 1.08x slower                                                      |
| logging_simple          | 6.28 us                                                     | 6.80 us: 1.08x slower                                                      |
| generators              | 31.8 ms                                                     | 34.5 ms: 1.09x slower                                                      |
| coverage                | 38.4 ms                                                     | 52.1 ms: 1.36x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.14x faster                                                               |

Benchmark hidden because not significant (3): asyncio_tcp, scimark_fft, python_startup_no_site
Ignored benchmarks (8) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, flaskblogging, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
