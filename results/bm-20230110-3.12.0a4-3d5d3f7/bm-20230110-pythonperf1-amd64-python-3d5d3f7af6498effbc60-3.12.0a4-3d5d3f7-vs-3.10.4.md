
# Results vs. 3.10.4

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: windows-amd64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.26x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 193 ms: 1.24x faster                                                       |
| chameleon      | 6.02 ms                                                     | 4.39 ms: 1.37x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.48 sec: 1.27x faster                                                     |
| html5lib       | 47.5 ms                                                     | 33.7 ms: 1.41x faster                                                      |
| Geometric mean | (ref)                                                       | 1.32x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_memoization  | 505 ms                                                      | 342 ms: 1.48x faster                                                       |
| async_tree_io           | 1.07 sec                                                    | 742 ms: 1.44x faster                                                       |
| async_tree_none         | 424 ms                                                      | 295 ms: 1.44x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 465 ms: 1.33x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.42x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 47.2 ms: 1.31x faster                                                      |
| nbody          | 71.0 ms                                                     | 59.5 ms: 1.19x faster                                                      |
| pidigits       | 146 ms                                                      | 145 ms: 1.01x faster                                                       |
| Geometric mean | (ref)                                                       | 1.16x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 78.8 ms: 1.30x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 13.6 ms: 1.10x faster                                                      |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.10 ms: 1.72x faster                                                      |
| pickle_pure_python   | 259 us                                                      | 169 us: 1.53x faster                                                       |
| unpickle_pure_python | 177 us                                                      | 119 us: 1.49x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 33.8 ms: 1.27x faster                                                      |
| json_loads           | 14.2 us                                                     | 12.4 us: 1.14x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 48.3 ms: 1.13x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 86.5 ms: 1.12x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 60.1 ms: 1.07x faster                                                      |
| pickle               | 6.87 us                                                     | 6.55 us: 1.05x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.70 us: 1.05x faster                                                      |
| unpickle_list        | 2.68 us                                                     | 2.59 us: 1.04x faster                                                      |
| pickle_list          | 2.69 us                                                     | 2.81 us: 1.04x slower                                                      |
| pickle_dict          | 17.1 us                                                     | 18.2 us: 1.06x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.17x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.1 ms: 1.09x faster                                                      |
| Geometric mean | (ref)                                                       | 1.05x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 6.05 ms: 1.48x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 13.3 ms: 1.42x faster                                                      |
| django_template | 28.8 ms                                                     | 20.7 ms: 1.39x faster                                                      |
| genshi_xml      | 39.4 ms                                                     | 30.5 ms: 1.29x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.40x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 1.94 ms: 2.12x faster                                                      |
| logging_silent          | 93.4 ns                                                     | 54.2 ns: 1.72x faster                                                      |
| json_dumps              | 8.77 ms                                                     | 5.10 ms: 1.72x faster                                                      |
| richards                | 40.6 ms                                                     | 24.0 ms: 1.69x faster                                                      |
| go                      | 135 ms                                                      | 80.4 ms: 1.68x faster                                                      |
| mypy2                   | 347 ms                                                      | 209 ms: 1.66x faster                                                       |
| scimark_sor             | 105 ms                                                      | 63.7 ms: 1.65x faster                                                      |
| raytrace                | 266 ms                                                      | 171 ms: 1.56x faster                                                       |
| asyncio_tcp             | 717 ms                                                      | 466 ms: 1.54x faster                                                       |
| pickle_pure_python      | 259 us                                                      | 169 us: 1.53x faster                                                       |
| scimark_monte_carlo     | 58.0 ms                                                     | 38.0 ms: 1.53x faster                                                      |
| unpack_sequence         | 40.0 ns                                                     | 26.2 ns: 1.53x faster                                                      |
| pyflate                 | 402 ms                                                      | 263 ms: 1.53x faster                                                       |
| scimark_lu              | 84.0 ms                                                     | 56.0 ms: 1.50x faster                                                      |
| unpickle_pure_python    | 177 us                                                      | 119 us: 1.49x faster                                                       |
| mako                    | 8.98 ms                                                     | 6.05 ms: 1.48x faster                                                      |
| hexiom                  | 5.59 ms                                                     | 3.77 ms: 1.48x faster                                                      |
| async_tree_memoization  | 505 ms                                                      | 342 ms: 1.48x faster                                                       |
| async_tree_io           | 1.07 sec                                                    | 742 ms: 1.44x faster                                                       |
| pycparser               | 905 ms                                                      | 628 ms: 1.44x faster                                                       |
| async_tree_none         | 424 ms                                                      | 295 ms: 1.44x faster                                                       |
| deepcopy_memo           | 29.0 us                                                     | 20.4 us: 1.42x faster                                                      |
| genshi_text             | 18.8 ms                                                     | 13.3 ms: 1.42x faster                                                      |
| sqlglot_parse           | 1.20 ms                                                     | 848 us: 1.42x faster                                                       |
| sqlglot_transpile       | 1.45 ms                                                     | 1.02 ms: 1.42x faster                                                      |
| chaos                   | 59.5 ms                                                     | 42.1 ms: 1.41x faster                                                      |
| html5lib                | 47.5 ms                                                     | 33.7 ms: 1.41x faster                                                      |
| django_template         | 28.8 ms                                                     | 20.7 ms: 1.39x faster                                                      |
| crypto_pyaes            | 63.1 ms                                                     | 45.9 ms: 1.38x faster                                                      |
| chameleon               | 6.02 ms                                                     | 4.39 ms: 1.37x faster                                                      |
| thrift                  | 623 us                                                      | 463 us: 1.35x faster                                                       |
| pprint_pformat          | 1.22 sec                                                    | 918 ms: 1.33x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 465 ms: 1.33x faster                                                       |
| pprint_safe_repr        | 594 ms                                                      | 448 ms: 1.33x faster                                                       |
| float                   | 61.7 ms                                                     | 47.2 ms: 1.31x faster                                                      |
| deepcopy                | 259 us                                                      | 199 us: 1.30x faster                                                       |
| regex_compile           | 102 ms                                                      | 78.8 ms: 1.30x faster                                                      |
| async_generators        | 219 ms                                                      | 169 ms: 1.30x faster                                                       |
| genshi_xml              | 39.4 ms                                                     | 30.5 ms: 1.29x faster                                                      |
| sqlglot_optimize        | 39.4 ms                                                     | 30.6 ms: 1.29x faster                                                      |
| xml_etree_process       | 43.1 ms                                                     | 33.8 ms: 1.27x faster                                                      |
| docutils                | 1.88 sec                                                    | 1.48 sec: 1.27x faster                                                     |
| spectral_norm           | 78.9 ms                                                     | 62.8 ms: 1.26x faster                                                      |
| deepcopy_reduce         | 2.22 us                                                     | 1.78 us: 1.25x faster                                                      |
| dask                    | 305 ms                                                      | 246 ms: 1.24x faster                                                       |
| 2to3                    | 239 ms                                                      | 193 ms: 1.24x faster                                                       |
| sqlglot_normalize       | 207 ms                                                      | 168 ms: 1.23x faster                                                       |
| dulwich_log             | 48.6 ms                                                     | 40.1 ms: 1.21x faster                                                      |
| create_gc_cycles        | 800 us                                                      | 661 us: 1.21x faster                                                       |
| nbody                   | 71.0 ms                                                     | 59.5 ms: 1.19x faster                                                      |
| nqueens                 | 68.3 ms                                                     | 57.3 ms: 1.19x faster                                                      |
| sympy_integrate         | 15.0 ms                                                     | 12.6 ms: 1.19x faster                                                      |
| json                    | 3.10 ms                                                     | 2.61 ms: 1.19x faster                                                      |
| sympy_expand            | 320 ms                                                      | 269 ms: 1.19x faster                                                       |
| fannkuch                | 258 ms                                                      | 217 ms: 1.19x faster                                                       |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.25 ms: 1.19x faster                                                      |
| sympy_str               | 193 ms                                                      | 168 ms: 1.15x faster                                                       |
| bench_thread_pool       | 913 us                                                      | 798 us: 1.14x faster                                                       |
| sympy_sum               | 105 ms                                                      | 92.0 ms: 1.14x faster                                                      |
| json_loads              | 14.2 us                                                     | 12.4 us: 1.14x faster                                                      |
| mdp                     | 1.71 sec                                                    | 1.51 sec: 1.13x faster                                                     |
| xml_etree_generate      | 54.5 ms                                                     | 48.3 ms: 1.13x faster                                                      |
| scimark_fft             | 187 ms                                                      | 167 ms: 1.13x faster                                                       |
| xml_etree_parse         | 96.8 ms                                                     | 86.5 ms: 1.12x faster                                                      |
| coroutines              | 15.5 ms                                                     | 13.9 ms: 1.11x faster                                                      |
| comprehensions          | 16.6 us                                                     | 15.0 us: 1.11x faster                                                      |
| sqlite_synth            | 1.90 us                                                     | 1.72 us: 1.11x faster                                                      |
| regex_v8                | 15.0 ms                                                     | 13.6 ms: 1.10x faster                                                      |
| meteor_contest          | 73.8 ms                                                     | 67.9 ms: 1.09x faster                                                      |
| python_startup          | 19.7 ms                                                     | 18.1 ms: 1.09x faster                                                      |
| regex_dna               | 129 ms                                                      | 120 ms: 1.08x faster                                                       |
| logging_simple          | 6.28 us                                                     | 5.84 us: 1.08x faster                                                      |
| xml_etree_iterparse     | 64.5 ms                                                     | 60.1 ms: 1.07x faster                                                      |
| logging_format          | 6.73 us                                                     | 6.29 us: 1.07x faster                                                      |
| telco                   | 3.82 ms                                                     | 3.59 ms: 1.06x faster                                                      |
| pickle                  | 6.87 us                                                     | 6.55 us: 1.05x faster                                                      |
| unpickle                | 9.11 us                                                     | 8.70 us: 1.05x faster                                                      |
| unpickle_list           | 2.68 us                                                     | 2.59 us: 1.04x faster                                                      |
| pidigits                | 146 ms                                                      | 145 ms: 1.01x faster                                                       |
| regex_effbot            | 1.56 ms                                                     | 1.59 ms: 1.02x slower                                                      |
| bench_mp_pool           | 59.9 ms                                                     | 61.1 ms: 1.02x slower                                                      |
| gc_traversal            | 1.40 ms                                                     | 1.43 ms: 1.03x slower                                                      |
| generators              | 31.8 ms                                                     | 33.1 ms: 1.04x slower                                                      |
| pickle_list             | 2.69 us                                                     | 2.81 us: 1.04x slower                                                      |
| pickle_dict             | 17.1 us                                                     | 18.2 us: 1.06x slower                                                      |
| coverage                | 38.4 ms                                                     | 52.5 ms: 1.37x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.26x faster                                                               |

Benchmark hidden because not significant (2): python_startup_no_site, pathlib
Ignored benchmarks (10) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.21x
- 99% likely to have a speedup of 1.19x
