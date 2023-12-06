
# Results vs. 3.12.0

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: windows-amd64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.06x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 193 ms: 1.10x faster                                                       |
| chameleon      | 4.95 ms                                                     | 4.39 ms: 1.13x faster                                                      |
| docutils       | 1.61 sec                                                    | 1.48 sec: 1.09x faster                                                     |
| Geometric mean | (ref)                                                       | 1.10x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 465 ms: 1.03x faster                                                       |
| async_tree_memoization  | 333 ms                                                      | 342 ms: 1.03x slower                                                       |
| async_tree_none         | 286 ms                                                      | 295 ms: 1.03x slower                                                       |
| async_tree_io           | 712 ms                                                      | 742 ms: 1.04x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.02x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 47.2 ms: 1.16x faster                                                      |
| nbody          | 68.8 ms                                                     | 59.5 ms: 1.16x faster                                                      |
| pidigits       | 150 ms                                                      | 145 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 78.8 ms: 1.11x faster                                                      |
| regex_effbot   | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                      |
| regex_dna      | 119 ms                                                      | 120 ms: 1.01x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 13.6 ms: 1.01x slower                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                     | 48.3 ms: 1.15x faster                                                      |
| pickle_pure_python   | 195 us                                                      | 169 us: 1.15x faster                                                       |
| json_dumps           | 5.83 ms                                                     | 5.10 ms: 1.14x faster                                                      |
| unpickle_pure_python | 134 us                                                      | 119 us: 1.13x faster                                                       |
| pickle               | 7.38 us                                                     | 6.55 us: 1.13x faster                                                      |
| xml_etree_process    | 37.6 ms                                                     | 33.8 ms: 1.11x faster                                                      |
| json_loads           | 13.6 us                                                     | 12.4 us: 1.10x faster                                                      |
| xml_etree_iterparse  | 63.1 ms                                                     | 60.1 ms: 1.05x faster                                                      |
| xml_etree_parse      | 90.5 ms                                                     | 86.5 ms: 1.05x faster                                                      |
| unpickle_list        | 2.69 us                                                     | 2.59 us: 1.04x faster                                                      |
| pickle_dict          | 18.9 us                                                     | 18.2 us: 1.04x faster                                                      |
| pickle_list          | 2.88 us                                                     | 2.81 us: 1.03x faster                                                      |
| unpickle             | 8.44 us                                                     | 8.70 us: 1.03x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.08x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.2 ms: 1.05x faster                                                      |
| python_startup         | 18.8 ms                                                     | 18.1 ms: 1.04x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.04x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 6.05 ms: 1.17x faster                                                      |
| django_template | 22.8 ms                                                     | 20.7 ms: 1.10x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.13x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence         | 36.9 ns                                                     | 26.2 ns: 1.41x faster                                                      |
| async_generators        | 230 ms                                                      | 169 ms: 1.36x faster                                                       |
| scimark_sor             | 79.8 ms                                                     | 63.7 ms: 1.25x faster                                                      |
| deepcopy_reduce         | 2.08 us                                                     | 1.78 us: 1.17x faster                                                      |
| mako                    | 7.05 ms                                                     | 6.05 ms: 1.17x faster                                                      |
| deepcopy                | 233 us                                                      | 199 us: 1.17x faster                                                       |
| float                   | 54.7 ms                                                     | 47.2 ms: 1.16x faster                                                      |
| nbody                   | 68.8 ms                                                     | 59.5 ms: 1.16x faster                                                      |
| xml_etree_generate      | 55.8 ms                                                     | 48.3 ms: 1.15x faster                                                      |
| richards                | 27.6 ms                                                     | 24.0 ms: 1.15x faster                                                      |
| pickle_pure_python      | 195 us                                                      | 169 us: 1.15x faster                                                       |
| deepcopy_memo           | 23.4 us                                                     | 20.4 us: 1.15x faster                                                      |
| json_dumps              | 5.83 ms                                                     | 5.10 ms: 1.14x faster                                                      |
| telco                   | 4.08 ms                                                     | 3.59 ms: 1.14x faster                                                      |
| pprint_safe_repr        | 508 ms                                                      | 448 ms: 1.13x faster                                                       |
| scimark_monte_carlo     | 43.0 ms                                                     | 38.0 ms: 1.13x faster                                                      |
| pprint_pformat          | 1.04 sec                                                    | 918 ms: 1.13x faster                                                       |
| json                    | 2.94 ms                                                     | 2.61 ms: 1.13x faster                                                      |
| chameleon               | 4.95 ms                                                     | 4.39 ms: 1.13x faster                                                      |
| fannkuch                | 244 ms                                                      | 217 ms: 1.13x faster                                                       |
| unpickle_pure_python    | 134 us                                                      | 119 us: 1.13x faster                                                       |
| pickle                  | 7.38 us                                                     | 6.55 us: 1.13x faster                                                      |
| raytrace                | 192 ms                                                      | 171 ms: 1.13x faster                                                       |
| logging_silent          | 60.5 ns                                                     | 54.2 ns: 1.12x faster                                                      |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.25 ms: 1.12x faster                                                      |
| pyflate                 | 294 ms                                                      | 263 ms: 1.11x faster                                                       |
| xml_etree_process       | 37.6 ms                                                     | 33.8 ms: 1.11x faster                                                      |
| sqlglot_optimize        | 34.0 ms                                                     | 30.6 ms: 1.11x faster                                                      |
| go                      | 89.0 ms                                                     | 80.4 ms: 1.11x faster                                                      |
| regex_compile           | 87.2 ms                                                     | 78.8 ms: 1.11x faster                                                      |
| django_template         | 22.8 ms                                                     | 20.7 ms: 1.10x faster                                                      |
| 2to3                    | 213 ms                                                      | 193 ms: 1.10x faster                                                       |
| bench_mp_pool           | 67.2 ms                                                     | 61.1 ms: 1.10x faster                                                      |
| create_gc_cycles        | 726 us                                                      | 661 us: 1.10x faster                                                       |
| json_loads              | 13.6 us                                                     | 12.4 us: 1.10x faster                                                      |
| deltablue               | 2.12 ms                                                     | 1.94 ms: 1.09x faster                                                      |
| sqlglot_normalize       | 183 ms                                                      | 168 ms: 1.09x faster                                                       |
| pathlib                 | 79.6 ms                                                     | 73.2 ms: 1.09x faster                                                      |
| scimark_fft             | 181 ms                                                      | 167 ms: 1.09x faster                                                       |
| docutils                | 1.61 sec                                                    | 1.48 sec: 1.09x faster                                                     |
| nqueens                 | 61.7 ms                                                     | 57.3 ms: 1.08x faster                                                      |
| pycparser               | 673 ms                                                      | 628 ms: 1.07x faster                                                       |
| logging_format          | 6.72 us                                                     | 6.29 us: 1.07x faster                                                      |
| dulwich_log             | 42.7 ms                                                     | 40.1 ms: 1.06x faster                                                      |
| logging_simple          | 6.21 us                                                     | 5.84 us: 1.06x faster                                                      |
| hexiom                  | 4.00 ms                                                     | 3.77 ms: 1.06x faster                                                      |
| meteor_contest          | 72.1 ms                                                     | 67.9 ms: 1.06x faster                                                      |
| xml_etree_iterparse     | 63.1 ms                                                     | 60.1 ms: 1.05x faster                                                      |
| python_startup_no_site  | 15.9 ms                                                     | 15.2 ms: 1.05x faster                                                      |
| xml_etree_parse         | 90.5 ms                                                     | 86.5 ms: 1.05x faster                                                      |
| unpickle_list           | 2.69 us                                                     | 2.59 us: 1.04x faster                                                      |
| bench_thread_pool       | 830 us                                                      | 798 us: 1.04x faster                                                       |
| python_startup          | 18.8 ms                                                     | 18.1 ms: 1.04x faster                                                      |
| pickle_dict             | 18.9 us                                                     | 18.2 us: 1.04x faster                                                      |
| gc_traversal            | 1.49 ms                                                     | 1.43 ms: 1.04x faster                                                      |
| dask                    | 255 ms                                                      | 246 ms: 1.04x faster                                                       |
| sympy_expand            | 278 ms                                                      | 269 ms: 1.03x faster                                                       |
| pidigits                | 150 ms                                                      | 145 ms: 1.03x faster                                                       |
| sympy_integrate         | 13.0 ms                                                     | 12.6 ms: 1.03x faster                                                      |
| async_tree_cpu_io_mixed | 477 ms                                                      | 465 ms: 1.03x faster                                                       |
| scimark_lu              | 57.5 ms                                                     | 56.0 ms: 1.03x faster                                                      |
| pickle_list             | 2.88 us                                                     | 2.81 us: 1.03x faster                                                      |
| sympy_str               | 171 ms                                                      | 168 ms: 1.02x faster                                                       |
| spectral_norm           | 63.9 ms                                                     | 62.8 ms: 1.02x faster                                                      |
| sqlite_synth            | 1.75 us                                                     | 1.72 us: 1.02x faster                                                      |
| coroutines              | 14.1 ms                                                     | 13.9 ms: 1.02x faster                                                      |
| crypto_pyaes            | 46.4 ms                                                     | 45.9 ms: 1.01x faster                                                      |
| sqlglot_transpile       | 1.02 ms                                                     | 1.02 ms: 1.00x slower                                                      |
| regex_effbot            | 1.58 ms                                                     | 1.59 ms: 1.01x slower                                                      |
| regex_dna               | 119 ms                                                      | 120 ms: 1.01x slower                                                       |
| regex_v8                | 13.5 ms                                                     | 13.6 ms: 1.01x slower                                                      |
| sympy_sum               | 90.1 ms                                                     | 92.0 ms: 1.02x slower                                                      |
| async_tree_memoization  | 333 ms                                                      | 342 ms: 1.03x slower                                                       |
| unpickle                | 8.44 us                                                     | 8.70 us: 1.03x slower                                                      |
| async_tree_none         | 286 ms                                                      | 295 ms: 1.03x slower                                                       |
| async_tree_io           | 712 ms                                                      | 742 ms: 1.04x slower                                                       |
| sqlglot_parse           | 802 us                                                      | 848 us: 1.06x slower                                                       |
| mdp                     | 1.42 sec                                                    | 1.51 sec: 1.07x slower                                                     |
| comprehensions          | 14.0 us                                                     | 15.0 us: 1.07x slower                                                      |
| coverage                | 39.8 ms                                                     | 52.5 ms: 1.32x slower                                                      |
| generators              | 22.6 ms                                                     | 33.1 ms: 1.47x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.06x faster                                                               |

Benchmark hidden because not significant (3): asyncio_tcp, chaos, mypy2
Ignored benchmarks (12) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20230110-3.12.0a4-3d5d3f7/bm-20230110-pythonperf1-amd64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.05x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
