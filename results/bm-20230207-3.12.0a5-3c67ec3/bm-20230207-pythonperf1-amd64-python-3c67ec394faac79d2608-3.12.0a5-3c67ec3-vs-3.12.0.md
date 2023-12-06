
# Results vs. 3.12.0

- fork: python
- ref: 3c67ec394faac79d2608
- machine: windows-amd64
- commit hash: 3c67ec3
- commit date: 2023-02-07
- overall geometric mean: 1.05x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 192 ms: 1.11x faster                                                       |
| chameleon      | 4.95 ms                                                     | 4.41 ms: 1.12x faster                                                      |
| docutils       | 1.61 sec                                                    | 1.50 sec: 1.07x faster                                                     |
| tornado_http   | 87.2 ms                                                     | 90.5 ms: 1.04x slower                                                      |
| Geometric mean | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io          | 712 ms                                                      | 748 ms: 1.05x slower                                                       |
| async_tree_none        | 286 ms                                                      | 302 ms: 1.06x slower                                                       |
| async_tree_memoization | 333 ms                                                      | 356 ms: 1.07x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.04x slower                                                               |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 59.1 ms: 1.16x faster                                                      |
| float          | 54.7 ms                                                     | 47.3 ms: 1.16x faster                                                      |
| pidigits       | 150 ms                                                      | 146 ms: 1.03x faster                                                       |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 78.8 ms: 1.11x faster                                                      |
| regex_v8       | 13.5 ms                                                     | 13.7 ms: 1.01x slower                                                      |
| regex_dna      | 119 ms                                                      | 121 ms: 1.01x slower                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.68 ms: 1.06x slower                                                      |
| Geometric mean | (ref)                                                       | 1.00x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 195 us                                                      | 166 us: 1.17x faster                                                       |
| xml_etree_generate   | 55.8 ms                                                     | 49.5 ms: 1.13x faster                                                      |
| xml_etree_process    | 37.6 ms                                                     | 33.5 ms: 1.12x faster                                                      |
| unpickle_pure_python | 134 us                                                      | 120 us: 1.12x faster                                                       |
| pickle               | 7.38 us                                                     | 6.77 us: 1.09x faster                                                      |
| json_dumps           | 5.83 ms                                                     | 5.38 ms: 1.08x faster                                                      |
| pickle_list          | 2.88 us                                                     | 2.70 us: 1.07x faster                                                      |
| pickle_dict          | 18.9 us                                                     | 18.5 us: 1.02x faster                                                      |
| xml_etree_parse      | 90.5 ms                                                     | 88.5 ms: 1.02x faster                                                      |
| unpickle_list        | 2.69 us                                                     | 2.65 us: 1.02x faster                                                      |
| xml_etree_iterparse  | 63.1 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| json_loads           | 13.6 us                                                     | 14.2 us: 1.04x slower                                                      |
| unpickle             | 8.44 us                                                     | 9.39 us: 1.11x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.05x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| python_startup_no_site | 15.9 ms                                                     | 15.5 ms: 1.03x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 6.15 ms: 1.15x faster                                                      |
| django_template | 22.8 ms                                                     | 20.2 ms: 1.13x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.14x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence         | 36.9 ns                                                     | 25.6 ns: 1.44x faster                                                      |
| async_generators        | 230 ms                                                      | 167 ms: 1.38x faster                                                       |
| comprehensions          | 14.0 us                                                     | 11.7 us: 1.20x faster                                                      |
| scimark_sor             | 79.8 ms                                                     | 67.0 ms: 1.19x faster                                                      |
| pickle_pure_python      | 195 us                                                      | 166 us: 1.17x faster                                                       |
| nbody                   | 68.8 ms                                                     | 59.1 ms: 1.16x faster                                                      |
| float                   | 54.7 ms                                                     | 47.3 ms: 1.16x faster                                                      |
| richards                | 27.6 ms                                                     | 23.9 ms: 1.15x faster                                                      |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.18 ms: 1.15x faster                                                      |
| fannkuch                | 244 ms                                                      | 213 ms: 1.15x faster                                                       |
| mako                    | 7.05 ms                                                     | 6.15 ms: 1.15x faster                                                      |
| pprint_pformat          | 1.04 sec                                                    | 907 ms: 1.14x faster                                                       |
| pprint_safe_repr        | 508 ms                                                      | 445 ms: 1.14x faster                                                       |
| scimark_monte_carlo     | 43.0 ms                                                     | 37.9 ms: 1.13x faster                                                      |
| raytrace                | 192 ms                                                      | 170 ms: 1.13x faster                                                       |
| django_template         | 22.8 ms                                                     | 20.2 ms: 1.13x faster                                                      |
| go                      | 89.0 ms                                                     | 78.8 ms: 1.13x faster                                                      |
| nqueens                 | 61.7 ms                                                     | 54.6 ms: 1.13x faster                                                      |
| xml_etree_generate      | 55.8 ms                                                     | 49.5 ms: 1.13x faster                                                      |
| xml_etree_process       | 37.6 ms                                                     | 33.5 ms: 1.12x faster                                                      |
| chameleon               | 4.95 ms                                                     | 4.41 ms: 1.12x faster                                                      |
| unpickle_pure_python    | 134 us                                                      | 120 us: 1.12x faster                                                       |
| deepcopy_reduce         | 2.08 us                                                     | 1.88 us: 1.11x faster                                                      |
| deepcopy_memo           | 23.4 us                                                     | 21.1 us: 1.11x faster                                                      |
| 2to3                    | 213 ms                                                      | 192 ms: 1.11x faster                                                       |
| regex_compile           | 87.2 ms                                                     | 78.8 ms: 1.11x faster                                                      |
| deepcopy                | 233 us                                                      | 211 us: 1.10x faster                                                       |
| pyflate                 | 294 ms                                                      | 267 ms: 1.10x faster                                                       |
| telco                   | 4.08 ms                                                     | 3.72 ms: 1.10x faster                                                      |
| scimark_fft             | 181 ms                                                      | 166 ms: 1.09x faster                                                       |
| pickle                  | 7.38 us                                                     | 6.77 us: 1.09x faster                                                      |
| bench_mp_pool           | 67.2 ms                                                     | 61.7 ms: 1.09x faster                                                      |
| deltablue               | 2.12 ms                                                     | 1.96 ms: 1.09x faster                                                      |
| json_dumps              | 5.83 ms                                                     | 5.38 ms: 1.08x faster                                                      |
| pathlib                 | 79.6 ms                                                     | 73.7 ms: 1.08x faster                                                      |
| sqlglot_optimize        | 34.0 ms                                                     | 31.6 ms: 1.08x faster                                                      |
| sqlglot_normalize       | 183 ms                                                      | 171 ms: 1.07x faster                                                       |
| create_gc_cycles        | 726 us                                                      | 676 us: 1.07x faster                                                       |
| docutils                | 1.61 sec                                                    | 1.50 sec: 1.07x faster                                                     |
| hexiom                  | 4.00 ms                                                     | 3.73 ms: 1.07x faster                                                      |
| logging_format          | 6.72 us                                                     | 6.28 us: 1.07x faster                                                      |
| pickle_list             | 2.88 us                                                     | 2.70 us: 1.07x faster                                                      |
| pycparser               | 673 ms                                                      | 633 ms: 1.06x faster                                                       |
| chaos                   | 42.1 ms                                                     | 39.6 ms: 1.06x faster                                                      |
| crypto_pyaes            | 46.4 ms                                                     | 44.0 ms: 1.06x faster                                                      |
| sympy_str               | 171 ms                                                      | 164 ms: 1.05x faster                                                       |
| json                    | 2.94 ms                                                     | 2.81 ms: 1.05x faster                                                      |
| sympy_integrate         | 13.0 ms                                                     | 12.4 ms: 1.05x faster                                                      |
| meteor_contest          | 72.1 ms                                                     | 69.1 ms: 1.04x faster                                                      |
| logging_silent          | 60.5 ns                                                     | 58.1 ns: 1.04x faster                                                      |
| spectral_norm           | 63.9 ms                                                     | 61.5 ms: 1.04x faster                                                      |
| logging_simple          | 6.21 us                                                     | 6.01 us: 1.03x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.2 ms: 1.03x faster                                                      |
| sympy_expand            | 278 ms                                                      | 269 ms: 1.03x faster                                                       |
| python_startup_no_site  | 15.9 ms                                                     | 15.5 ms: 1.03x faster                                                      |
| pidigits                | 150 ms                                                      | 146 ms: 1.03x faster                                                       |
| gc_traversal            | 1.49 ms                                                     | 1.45 ms: 1.03x faster                                                      |
| pickle_dict             | 18.9 us                                                     | 18.5 us: 1.02x faster                                                      |
| xml_etree_parse         | 90.5 ms                                                     | 88.5 ms: 1.02x faster                                                      |
| dulwich_log             | 42.7 ms                                                     | 41.9 ms: 1.02x faster                                                      |
| unpickle_list           | 2.69 us                                                     | 2.65 us: 1.02x faster                                                      |
| xml_etree_iterparse     | 63.1 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| sympy_sum               | 90.1 ms                                                     | 89.5 ms: 1.01x faster                                                      |
| mypy2                   | 209 ms                                                      | 208 ms: 1.00x faster                                                       |
| regex_v8                | 13.5 ms                                                     | 13.7 ms: 1.01x slower                                                      |
| regex_dna               | 119 ms                                                      | 121 ms: 1.01x slower                                                       |
| scimark_lu              | 57.5 ms                                                     | 58.7 ms: 1.02x slower                                                      |
| sqlglot_transpile       | 1.02 ms                                                     | 1.05 ms: 1.03x slower                                                      |
| tornado_http            | 87.2 ms                                                     | 90.5 ms: 1.04x slower                                                      |
| json_loads              | 13.6 us                                                     | 14.2 us: 1.04x slower                                                      |
| mdp                     | 1.42 sec                                                    | 1.48 sec: 1.04x slower                                                     |
| sqlite_synth            | 1.75 us                                                     | 1.82 us: 1.04x slower                                                      |
| coroutines              | 14.1 ms                                                     | 14.8 ms: 1.05x slower                                                      |
| async_tree_io           | 712 ms                                                      | 748 ms: 1.05x slower                                                       |
| async_tree_none         | 286 ms                                                      | 302 ms: 1.06x slower                                                       |
| sqlglot_parse           | 802 us                                                      | 851 us: 1.06x slower                                                       |
| regex_effbot            | 1.58 ms                                                     | 1.68 ms: 1.06x slower                                                      |
| async_tree_memoization  | 333 ms                                                      | 356 ms: 1.07x slower                                                       |
| unpickle                | 8.44 us                                                     | 9.39 us: 1.11x slower                                                      |
| coverage                | 39.8 ms                                                     | 51.8 ms: 1.30x slower                                                      |
| dask                    | 255 ms                                                      | 349 ms: 1.37x slower                                                       |
| generators              | 22.6 ms                                                     | 33.0 ms: 1.46x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.05x faster                                                               |

Benchmark hidden because not significant (3): asyncio_tcp, bench_thread_pool, async_tree_cpu_io_mixed
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20230207-3.12.0a5-3c67ec3/bm-20230207-pythonperf1-amd64-python-3c67ec394faac79d2608-3.12.0a5-3c67ec3.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.03x
