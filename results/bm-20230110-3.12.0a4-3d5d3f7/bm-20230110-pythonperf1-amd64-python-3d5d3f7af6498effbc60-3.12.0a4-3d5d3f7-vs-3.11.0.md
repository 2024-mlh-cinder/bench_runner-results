
# Results vs. 3.11.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: windows-amd64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.12x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.07x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 193 ms: 1.07x faster                                                       |
| chameleon      | 5.35 ms                                                     | 4.39 ms: 1.22x faster                                                      |
| docutils       | 1.59 sec                                                    | 1.48 sec: 1.07x faster                                                     |
| html5lib       | 38.6 ms                                                     | 33.7 ms: 1.14x faster                                                      |
| Geometric mean | (ref)                                                       | 1.13x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_memoization  | 367 ms                                                      | 342 ms: 1.07x faster                                                       |
| async_tree_cpu_io_mixed | 495 ms                                                      | 465 ms: 1.07x faster                                                       |
| async_tree_none         | 314 ms                                                      | 295 ms: 1.06x faster                                                       |
| async_tree_io           | 753 ms                                                      | 742 ms: 1.02x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.05x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 59.5 ms: 1.16x faster                                                      |
| float          | 54.4 ms                                                     | 47.2 ms: 1.15x faster                                                      |
| pidigits       | 149 ms                                                      | 145 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 78.8 ms: 1.15x faster                                                      |
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                                       |
| regex_v8       | 13.7 ms                                                     | 13.6 ms: 1.00x faster                                                      |
| regex_effbot   | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                      |
| Geometric mean | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.10 ms: 1.55x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 119 us: 1.28x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 169 us: 1.22x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 33.8 ms: 1.09x faster                                                      |
| xml_etree_parse      | 94.5 ms                                                     | 86.5 ms: 1.09x faster                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 48.3 ms: 1.08x faster                                                      |
| xml_etree_iterparse  | 63.0 ms                                                     | 60.1 ms: 1.05x faster                                                      |
| json_loads           | 12.9 us                                                     | 12.4 us: 1.04x faster                                                      |
| pickle               | 6.53 us                                                     | 6.55 us: 1.00x slower                                                      |
| unpickle_list        | 2.57 us                                                     | 2.59 us: 1.01x slower                                                      |
| pickle_dict          | 17.8 us                                                     | 18.2 us: 1.03x slower                                                      |
| pickle_list          | 2.68 us                                                     | 2.81 us: 1.05x slower                                                      |
| unpickle             | 7.82 us                                                     | 8.70 us: 1.11x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.1 ms: 1.04x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 15.2 ms: 1.02x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| genshi_text     | 17.7 ms                                                     | 13.3 ms: 1.33x faster                                                      |
| genshi_xml      | 40.5 ms                                                     | 30.5 ms: 1.33x faster                                                      |
| mako            | 7.55 ms                                                     | 6.05 ms: 1.25x faster                                                      |
| django_template | 24.0 ms                                                     | 20.7 ms: 1.16x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.27x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence         | 47.0 ns                                                     | 26.2 ns: 1.79x faster                                                      |
| json_dumps              | 7.90 ms                                                     | 5.10 ms: 1.55x faster                                                      |
| deltablue               | 2.63 ms                                                     | 1.94 ms: 1.35x faster                                                      |
| genshi_text             | 17.7 ms                                                     | 13.3 ms: 1.33x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 30.5 ms: 1.33x faster                                                      |
| asyncio_tcp             | 614 ms                                                      | 466 ms: 1.32x faster                                                       |
| logging_silent          | 70.7 ns                                                     | 54.2 ns: 1.30x faster                                                      |
| richards                | 30.8 ms                                                     | 24.0 ms: 1.28x faster                                                      |
| unpickle_pure_python    | 152 us                                                      | 119 us: 1.28x faster                                                       |
| deepcopy_memo           | 25.5 us                                                     | 20.4 us: 1.25x faster                                                      |
| mako                    | 7.55 ms                                                     | 6.05 ms: 1.25x faster                                                      |
| raytrace                | 211 ms                                                      | 171 ms: 1.23x faster                                                       |
| go                      | 98.8 ms                                                     | 80.4 ms: 1.23x faster                                                      |
| pickle_pure_python      | 207 us                                                      | 169 us: 1.22x faster                                                       |
| chameleon               | 5.35 ms                                                     | 4.39 ms: 1.22x faster                                                      |
| deepcopy                | 242 us                                                      | 199 us: 1.22x faster                                                       |
| scimark_sor             | 76.4 ms                                                     | 63.7 ms: 1.20x faster                                                      |
| hexiom                  | 4.51 ms                                                     | 3.77 ms: 1.20x faster                                                      |
| scimark_monte_carlo     | 44.6 ms                                                     | 38.0 ms: 1.17x faster                                                      |
| deepcopy_reduce         | 2.07 us                                                     | 1.78 us: 1.16x faster                                                      |
| nbody                   | 69.3 ms                                                     | 59.5 ms: 1.16x faster                                                      |
| django_template         | 24.0 ms                                                     | 20.7 ms: 1.16x faster                                                      |
| pprint_pformat          | 1.06 sec                                                    | 918 ms: 1.16x faster                                                       |
| pprint_safe_repr        | 519 ms                                                      | 448 ms: 1.16x faster                                                       |
| pyflate                 | 305 ms                                                      | 263 ms: 1.16x faster                                                       |
| nqueens                 | 66.1 ms                                                     | 57.3 ms: 1.15x faster                                                      |
| regex_compile           | 90.8 ms                                                     | 78.8 ms: 1.15x faster                                                      |
| float                   | 54.4 ms                                                     | 47.2 ms: 1.15x faster                                                      |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.25 ms: 1.15x faster                                                      |
| json                    | 2.99 ms                                                     | 2.61 ms: 1.15x faster                                                      |
| fannkuch                | 248 ms                                                      | 217 ms: 1.15x faster                                                       |
| sqlglot_optimize        | 35.1 ms                                                     | 30.6 ms: 1.14x faster                                                      |
| html5lib                | 38.6 ms                                                     | 33.7 ms: 1.14x faster                                                      |
| mdp                     | 1.73 sec                                                    | 1.51 sec: 1.14x faster                                                     |
| sqlglot_normalize       | 191 ms                                                      | 168 ms: 1.14x faster                                                       |
| logging_simple          | 6.60 us                                                     | 5.84 us: 1.13x faster                                                      |
| sqlglot_transpile       | 1.15 ms                                                     | 1.02 ms: 1.12x faster                                                      |
| pycparser               | 705 ms                                                      | 628 ms: 1.12x faster                                                       |
| logging_format          | 7.06 us                                                     | 6.29 us: 1.12x faster                                                      |
| spectral_norm           | 69.9 ms                                                     | 62.8 ms: 1.11x faster                                                      |
| scimark_lu              | 62.3 ms                                                     | 56.0 ms: 1.11x faster                                                      |
| chaos                   | 46.8 ms                                                     | 42.1 ms: 1.11x faster                                                      |
| sympy_expand            | 299 ms                                                      | 269 ms: 1.11x faster                                                       |
| sqlglot_parse           | 939 us                                                      | 848 us: 1.11x faster                                                       |
| meteor_contest          | 75.0 ms                                                     | 67.9 ms: 1.10x faster                                                      |
| dulwich_log             | 44.1 ms                                                     | 40.1 ms: 1.10x faster                                                      |
| telco                   | 3.93 ms                                                     | 3.59 ms: 1.09x faster                                                      |
| xml_etree_process       | 37.0 ms                                                     | 33.8 ms: 1.09x faster                                                      |
| sympy_str               | 184 ms                                                      | 168 ms: 1.09x faster                                                       |
| xml_etree_parse         | 94.5 ms                                                     | 86.5 ms: 1.09x faster                                                      |
| sympy_integrate         | 13.7 ms                                                     | 12.6 ms: 1.09x faster                                                      |
| scimark_fft             | 181 ms                                                      | 167 ms: 1.09x faster                                                       |
| sympy_sum               | 100.0 ms                                                    | 92.0 ms: 1.09x faster                                                      |
| mypy2                   | 226 ms                                                      | 209 ms: 1.08x faster                                                       |
| thrift                  | 501 us                                                      | 463 us: 1.08x faster                                                       |
| xml_etree_generate      | 52.2 ms                                                     | 48.3 ms: 1.08x faster                                                      |
| 2to3                    | 207 ms                                                      | 193 ms: 1.07x faster                                                       |
| docutils                | 1.59 sec                                                    | 1.48 sec: 1.07x faster                                                     |
| async_tree_memoization  | 367 ms                                                      | 342 ms: 1.07x faster                                                       |
| async_generators        | 181 ms                                                      | 169 ms: 1.07x faster                                                       |
| dask                    | 262 ms                                                      | 246 ms: 1.07x faster                                                       |
| create_gc_cycles        | 706 us                                                      | 661 us: 1.07x faster                                                       |
| async_tree_cpu_io_mixed | 495 ms                                                      | 465 ms: 1.07x faster                                                       |
| async_tree_none         | 314 ms                                                      | 295 ms: 1.06x faster                                                       |
| bench_thread_pool       | 847 us                                                      | 798 us: 1.06x faster                                                       |
| coroutines              | 14.7 ms                                                     | 13.9 ms: 1.05x faster                                                      |
| crypto_pyaes            | 48.2 ms                                                     | 45.9 ms: 1.05x faster                                                      |
| xml_etree_iterparse     | 63.0 ms                                                     | 60.1 ms: 1.05x faster                                                      |
| sqlite_synth            | 1.79 us                                                     | 1.72 us: 1.05x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.1 ms: 1.04x faster                                                      |
| comprehensions          | 15.6 us                                                     | 15.0 us: 1.04x faster                                                      |
| json_loads              | 12.9 us                                                     | 12.4 us: 1.04x faster                                                      |
| generators              | 34.0 ms                                                     | 33.1 ms: 1.03x faster                                                      |
| pidigits                | 149 ms                                                      | 145 ms: 1.02x faster                                                       |
| python_startup_no_site  | 15.5 ms                                                     | 15.2 ms: 1.02x faster                                                      |
| async_tree_io           | 753 ms                                                      | 742 ms: 1.02x faster                                                       |
| gc_traversal            | 1.46 ms                                                     | 1.43 ms: 1.01x faster                                                      |
| regex_dna               | 121 ms                                                      | 120 ms: 1.01x faster                                                       |
| regex_v8                | 13.7 ms                                                     | 13.6 ms: 1.00x faster                                                      |
| pickle                  | 6.53 us                                                     | 6.55 us: 1.00x slower                                                      |
| unpickle_list           | 2.57 us                                                     | 2.59 us: 1.01x slower                                                      |
| pickle_dict             | 17.8 us                                                     | 18.2 us: 1.03x slower                                                      |
| regex_effbot            | 1.52 ms                                                     | 1.59 ms: 1.05x slower                                                      |
| pickle_list             | 2.68 us                                                     | 2.81 us: 1.05x slower                                                      |
| pathlib                 | 69.4 ms                                                     | 73.2 ms: 1.05x slower                                                      |
| unpickle                | 7.82 us                                                     | 8.70 us: 1.11x slower                                                      |
| coverage                | 43.0 ms                                                     | 52.5 ms: 1.22x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.12x faster                                                               |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.08x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.07x
