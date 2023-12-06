
# Results vs. 3.12.0

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: windows-amd64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.02x faster \*
- HPT reliability: 99.44%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 193 ms: 1.10x faster                                                       |
| chameleon      | 4.95 ms                                                     | 4.59 ms: 1.08x faster                                                      |
| docutils       | 1.61 sec                                                    | 1.52 sec: 1.06x faster                                                     |
| tornado_http   | 87.2 ms                                                     | 89.5 ms: 1.03x slower                                                      |
| Geometric mean | (ref)                                                       | 1.05x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 507 ms: 1.06x slower                                                       |
| async_tree_io           | 712 ms                                                      | 783 ms: 1.10x slower                                                       |
| async_tree_none         | 286 ms                                                      | 325 ms: 1.14x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 386 ms: 1.16x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.11x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 54.7 ms                                                     | 48.7 ms: 1.12x faster                                                      |
| nbody          | 68.8 ms                                                     | 62.3 ms: 1.10x faster                                                      |
| pidigits       | 150 ms                                                      | 146 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                       | 1.08x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 82.3 ms: 1.06x faster                                                      |
| regex_dna      | 119 ms                                                      | 120 ms: 1.00x slower                                                       |
| regex_v8       | 13.5 ms                                                     | 13.8 ms: 1.02x slower                                                      |
| regex_effbot   | 1.58 ms                                                     | 1.70 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| xml_etree_generate   | 55.8 ms                                                     | 49.0 ms: 1.14x faster                                                      |
| json_dumps           | 5.83 ms                                                     | 5.12 ms: 1.14x faster                                                      |
| pickle               | 7.38 us                                                     | 6.57 us: 1.12x faster                                                      |
| xml_etree_process    | 37.6 ms                                                     | 33.9 ms: 1.11x faster                                                      |
| pickle_list          | 2.88 us                                                     | 2.62 us: 1.10x faster                                                      |
| pickle_pure_python   | 195 us                                                      | 180 us: 1.08x faster                                                       |
| pickle_dict          | 18.9 us                                                     | 18.3 us: 1.04x faster                                                      |
| xml_etree_parse      | 90.5 ms                                                     | 87.6 ms: 1.03x faster                                                      |
| xml_etree_iterparse  | 63.1 ms                                                     | 61.3 ms: 1.03x faster                                                      |
| unpickle_pure_python | 134 us                                                      | 130 us: 1.03x faster                                                       |
| json_loads           | 13.6 us                                                     | 13.3 us: 1.03x faster                                                      |
| unpickle             | 8.44 us                                                     | 8.25 us: 1.02x faster                                                      |
| unpickle_list        | 2.69 us                                                     | 2.79 us: 1.03x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.4 ms: 1.03x faster                                                      |
| python_startup         | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 6.25 ms: 1.13x faster                                                      |
| django_template | 22.8 ms                                                     | 21.6 ms: 1.05x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.09x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 173 ms: 1.33x faster                                                       |
| unpack_sequence         | 36.9 ns                                                     | 30.8 ns: 1.20x faster                                                      |
| scimark_sor             | 79.8 ms                                                     | 69.2 ms: 1.15x faster                                                      |
| xml_etree_generate      | 55.8 ms                                                     | 49.0 ms: 1.14x faster                                                      |
| json_dumps              | 5.83 ms                                                     | 5.12 ms: 1.14x faster                                                      |
| mako                    | 7.05 ms                                                     | 6.25 ms: 1.13x faster                                                      |
| float                   | 54.7 ms                                                     | 48.7 ms: 1.12x faster                                                      |
| pickle                  | 7.38 us                                                     | 6.57 us: 1.12x faster                                                      |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.25 ms: 1.12x faster                                                      |
| deepcopy_reduce         | 2.08 us                                                     | 1.87 us: 1.11x faster                                                      |
| xml_etree_process       | 37.6 ms                                                     | 33.9 ms: 1.11x faster                                                      |
| pprint_pformat          | 1.04 sec                                                    | 934 ms: 1.11x faster                                                       |
| pprint_safe_repr        | 508 ms                                                      | 458 ms: 1.11x faster                                                       |
| nbody                   | 68.8 ms                                                     | 62.3 ms: 1.10x faster                                                      |
| pickle_list             | 2.88 us                                                     | 2.62 us: 1.10x faster                                                      |
| 2to3                    | 213 ms                                                      | 193 ms: 1.10x faster                                                       |
| bench_mp_pool           | 67.2 ms                                                     | 61.2 ms: 1.10x faster                                                      |
| pathlib                 | 79.6 ms                                                     | 72.6 ms: 1.10x faster                                                      |
| create_gc_cycles        | 726 us                                                      | 665 us: 1.09x faster                                                       |
| pickle_pure_python      | 195 us                                                      | 180 us: 1.08x faster                                                       |
| scimark_monte_carlo     | 43.0 ms                                                     | 39.8 ms: 1.08x faster                                                      |
| pyflate                 | 294 ms                                                      | 272 ms: 1.08x faster                                                       |
| chameleon               | 4.95 ms                                                     | 4.59 ms: 1.08x faster                                                      |
| fannkuch                | 244 ms                                                      | 227 ms: 1.08x faster                                                       |
| nqueens                 | 61.7 ms                                                     | 57.5 ms: 1.07x faster                                                      |
| deepcopy                | 233 us                                                      | 217 us: 1.07x faster                                                       |
| json                    | 2.94 ms                                                     | 2.75 ms: 1.07x faster                                                      |
| scimark_fft             | 181 ms                                                      | 170 ms: 1.07x faster                                                       |
| docutils                | 1.61 sec                                                    | 1.52 sec: 1.06x faster                                                     |
| go                      | 89.0 ms                                                     | 84.0 ms: 1.06x faster                                                      |
| regex_compile           | 87.2 ms                                                     | 82.3 ms: 1.06x faster                                                      |
| sqlglot_optimize        | 34.0 ms                                                     | 32.1 ms: 1.06x faster                                                      |
| django_template         | 22.8 ms                                                     | 21.6 ms: 1.05x faster                                                      |
| deepcopy_memo           | 23.4 us                                                     | 22.2 us: 1.05x faster                                                      |
| sqlglot_normalize       | 183 ms                                                      | 174 ms: 1.05x faster                                                       |
| raytrace                | 192 ms                                                      | 184 ms: 1.04x faster                                                       |
| meteor_contest          | 72.1 ms                                                     | 69.3 ms: 1.04x faster                                                      |
| gc_traversal            | 1.49 ms                                                     | 1.44 ms: 1.04x faster                                                      |
| pickle_dict             | 18.9 us                                                     | 18.3 us: 1.04x faster                                                      |
| pycparser               | 673 ms                                                      | 650 ms: 1.04x faster                                                       |
| python_startup_no_site  | 15.9 ms                                                     | 15.4 ms: 1.03x faster                                                      |
| telco                   | 4.08 ms                                                     | 3.95 ms: 1.03x faster                                                      |
| xml_etree_parse         | 90.5 ms                                                     | 87.6 ms: 1.03x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| richards                | 27.6 ms                                                     | 26.7 ms: 1.03x faster                                                      |
| xml_etree_iterparse     | 63.1 ms                                                     | 61.3 ms: 1.03x faster                                                      |
| unpickle_pure_python    | 134 us                                                      | 130 us: 1.03x faster                                                       |
| json_loads              | 13.6 us                                                     | 13.3 us: 1.03x faster                                                      |
| pidigits                | 150 ms                                                      | 146 ms: 1.03x faster                                                       |
| logging_format          | 6.72 us                                                     | 6.56 us: 1.02x faster                                                      |
| crypto_pyaes            | 46.4 ms                                                     | 45.4 ms: 1.02x faster                                                      |
| unpickle                | 8.44 us                                                     | 8.25 us: 1.02x faster                                                      |
| sqlite_synth            | 1.75 us                                                     | 1.71 us: 1.02x faster                                                      |
| spectral_norm           | 63.9 ms                                                     | 63.1 ms: 1.01x faster                                                      |
| logging_silent          | 60.5 ns                                                     | 59.9 ns: 1.01x faster                                                      |
| scimark_lu              | 57.5 ms                                                     | 56.9 ms: 1.01x faster                                                      |
| sympy_integrate         | 13.0 ms                                                     | 12.9 ms: 1.01x faster                                                      |
| regex_dna               | 119 ms                                                      | 120 ms: 1.00x slower                                                       |
| dulwich_log             | 42.7 ms                                                     | 43.1 ms: 1.01x slower                                                      |
| dask                    | 255 ms                                                      | 258 ms: 1.01x slower                                                       |
| mypy2                   | 209 ms                                                      | 212 ms: 1.01x slower                                                       |
| sympy_expand            | 278 ms                                                      | 282 ms: 1.02x slower                                                       |
| logging_simple          | 6.21 us                                                     | 6.31 us: 1.02x slower                                                      |
| sympy_str               | 171 ms                                                      | 175 ms: 1.02x slower                                                       |
| regex_v8                | 13.5 ms                                                     | 13.8 ms: 1.02x slower                                                      |
| chaos                   | 42.1 ms                                                     | 43.1 ms: 1.02x slower                                                      |
| tornado_http            | 87.2 ms                                                     | 89.5 ms: 1.03x slower                                                      |
| unpickle_list           | 2.69 us                                                     | 2.79 us: 1.03x slower                                                      |
| sqlglot_transpile       | 1.02 ms                                                     | 1.06 ms: 1.05x slower                                                      |
| deltablue               | 2.12 ms                                                     | 2.24 ms: 1.06x slower                                                      |
| coroutines              | 14.1 ms                                                     | 15.0 ms: 1.06x slower                                                      |
| async_tree_cpu_io_mixed | 477 ms                                                      | 507 ms: 1.06x slower                                                       |
| sympy_sum               | 90.1 ms                                                     | 96.1 ms: 1.07x slower                                                      |
| regex_effbot            | 1.58 ms                                                     | 1.70 ms: 1.08x slower                                                      |
| mdp                     | 1.42 sec                                                    | 1.53 sec: 1.08x slower                                                     |
| sqlglot_parse           | 802 us                                                      | 865 us: 1.08x slower                                                       |
| comprehensions          | 14.0 us                                                     | 15.4 us: 1.10x slower                                                      |
| async_tree_io           | 712 ms                                                      | 783 ms: 1.10x slower                                                       |
| async_tree_none         | 286 ms                                                      | 325 ms: 1.14x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 386 ms: 1.16x slower                                                       |
| coverage                | 39.8 ms                                                     | 52.0 ms: 1.31x slower                                                      |
| asyncio_tcp             | 471 ms                                                      | 708 ms: 1.50x slower                                                       |
| generators              | 22.6 ms                                                     | 35.7 ms: 1.58x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.02x faster                                                               |

Benchmark hidden because not significant (2): hexiom, bench_thread_pool
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20221114-3.12.0a2-3b9d793/bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 99.44% likely to be faster
- 90% likely to have a speedup of 1.02x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
