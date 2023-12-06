
# Results vs. 3.12.0

- fork: python
- ref: 5a7e1e0a92622c605ab2
- machine: windows-amd64
- commit hash: 5a7e1e0
- commit date: 2022-07-11
- overall geometric mean: 1.06x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 206 ms: 1.03x faster                                                       |
| chameleon      | 4.95 ms                                                     | 5.14 ms: 1.04x slower                                                      |
| docutils       | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                                     |
| tornado_http   | 87.2 ms                                                     | 91.9 ms: 1.05x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x slower                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io           | 712 ms                                                      | 753 ms: 1.06x slower                                                       |
| async_tree_cpu_io_mixed | 477 ms                                                      | 508 ms: 1.06x slower                                                       |
| async_tree_none         | 286 ms                                                      | 317 ms: 1.11x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 375 ms: 1.13x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.09x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 146 ms: 1.03x faster                                                       |
| float          | 54.7 ms                                                     | 53.9 ms: 1.01x faster                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                      | 114 ms: 1.04x faster                                                       |
| regex_v8       | 13.5 ms                                                     | 13.4 ms: 1.01x faster                                                      |
| regex_compile  | 87.2 ms                                                     | 90.8 ms: 1.04x slower                                                      |
| regex_effbot   | 1.58 ms                                                     | 1.70 ms: 1.08x slower                                                      |
| Geometric mean | (ref)                                                       | 1.02x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle               | 7.38 us                                                     | 6.48 us: 1.14x faster                                                      |
| pickle_list          | 2.88 us                                                     | 2.65 us: 1.09x faster                                                      |
| xml_etree_generate   | 55.8 ms                                                     | 53.4 ms: 1.04x faster                                                      |
| pickle_dict          | 18.9 us                                                     | 18.4 us: 1.03x faster                                                      |
| unpickle             | 8.44 us                                                     | 8.32 us: 1.01x faster                                                      |
| xml_etree_process    | 37.6 ms                                                     | 37.8 ms: 1.00x slower                                                      |
| json_loads           | 13.6 us                                                     | 14.1 us: 1.03x slower                                                      |
| unpickle_list        | 2.69 us                                                     | 2.80 us: 1.04x slower                                                      |
| pickle_pure_python   | 195 us                                                      | 204 us: 1.05x slower                                                       |
| xml_etree_parse      | 90.5 ms                                                     | 95.1 ms: 1.05x slower                                                      |
| unpickle_pure_python | 134 us                                                      | 152 us: 1.13x slower                                                       |
| json_dumps           | 5.83 ms                                                     | 7.78 ms: 1.33x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.02x slower                                                               |

Benchmark hidden because not significant (1): xml_etree_iterparse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.4 ms: 1.04x faster                                                      |
| python_startup         | 18.8 ms                                                     | 18.4 ms: 1.03x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 7.23 ms: 1.02x slower                                                      |
| django_template | 22.8 ms                                                     | 25.0 ms: 1.10x slower                                                      |
| Geometric mean  | (ref)                                                       | 1.06x slower                                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 178 ms: 1.30x faster                                                       |
| pickle                  | 7.38 us                                                     | 6.48 us: 1.14x faster                                                      |
| pathlib                 | 79.6 ms                                                     | 72.4 ms: 1.10x faster                                                      |
| bench_mp_pool           | 67.2 ms                                                     | 61.4 ms: 1.10x faster                                                      |
| create_gc_cycles        | 726 us                                                      | 664 us: 1.09x faster                                                       |
| pickle_list             | 2.88 us                                                     | 2.65 us: 1.09x faster                                                      |
| gc_traversal            | 1.49 ms                                                     | 1.41 ms: 1.05x faster                                                      |
| xml_etree_generate      | 55.8 ms                                                     | 53.4 ms: 1.04x faster                                                      |
| regex_dna               | 119 ms                                                      | 114 ms: 1.04x faster                                                       |
| python_startup_no_site  | 15.9 ms                                                     | 15.4 ms: 1.04x faster                                                      |
| 2to3                    | 213 ms                                                      | 206 ms: 1.03x faster                                                       |
| sqlite_synth            | 1.75 us                                                     | 1.70 us: 1.03x faster                                                      |
| pickle_dict             | 18.9 us                                                     | 18.4 us: 1.03x faster                                                      |
| pidigits                | 150 ms                                                      | 146 ms: 1.03x faster                                                       |
| python_startup          | 18.8 ms                                                     | 18.4 ms: 1.03x faster                                                      |
| docutils                | 1.61 sec                                                    | 1.58 sec: 1.02x faster                                                     |
| scimark_sor             | 79.8 ms                                                     | 78.5 ms: 1.02x faster                                                      |
| telco                   | 4.08 ms                                                     | 4.02 ms: 1.02x faster                                                      |
| float                   | 54.7 ms                                                     | 53.9 ms: 1.01x faster                                                      |
| unpickle                | 8.44 us                                                     | 8.32 us: 1.01x faster                                                      |
| regex_v8                | 13.5 ms                                                     | 13.4 ms: 1.01x faster                                                      |
| xml_etree_process       | 37.6 ms                                                     | 37.8 ms: 1.00x slower                                                      |
| pprint_safe_repr        | 508 ms                                                      | 515 ms: 1.01x slower                                                       |
| aiohttp                 | 848 us                                                      | 860 us: 1.01x slower                                                       |
| sqlglot_optimize        | 34.0 ms                                                     | 34.8 ms: 1.02x slower                                                      |
| mako                    | 7.05 ms                                                     | 7.23 ms: 1.02x slower                                                      |
| scimark_fft             | 181 ms                                                      | 186 ms: 1.03x slower                                                       |
| deepcopy_reduce         | 2.08 us                                                     | 2.14 us: 1.03x slower                                                      |
| fannkuch                | 244 ms                                                      | 251 ms: 1.03x slower                                                       |
| pprint_pformat          | 1.04 sec                                                    | 1.07 sec: 1.03x slower                                                     |
| scimark_monte_carlo     | 43.0 ms                                                     | 44.3 ms: 1.03x slower                                                      |
| json_loads              | 13.6 us                                                     | 14.1 us: 1.03x slower                                                      |
| bench_thread_pool       | 830 us                                                      | 858 us: 1.03x slower                                                       |
| dulwich_log             | 42.7 ms                                                     | 44.2 ms: 1.03x slower                                                      |
| meteor_contest          | 72.1 ms                                                     | 74.8 ms: 1.04x slower                                                      |
| unpickle_list           | 2.69 us                                                     | 2.80 us: 1.04x slower                                                      |
| chameleon               | 4.95 ms                                                     | 5.14 ms: 1.04x slower                                                      |
| regex_compile           | 87.2 ms                                                     | 90.8 ms: 1.04x slower                                                      |
| pyflate                 | 294 ms                                                      | 306 ms: 1.04x slower                                                       |
| sqlglot_normalize       | 183 ms                                                      | 192 ms: 1.05x slower                                                       |
| pickle_pure_python      | 195 us                                                      | 204 us: 1.05x slower                                                       |
| coroutines              | 14.1 ms                                                     | 14.8 ms: 1.05x slower                                                      |
| sympy_expand            | 278 ms                                                      | 291 ms: 1.05x slower                                                       |
| pycparser               | 673 ms                                                      | 706 ms: 1.05x slower                                                       |
| xml_etree_parse         | 90.5 ms                                                     | 95.1 ms: 1.05x slower                                                      |
| tornado_http            | 87.2 ms                                                     | 91.9 ms: 1.05x slower                                                      |
| deepcopy                | 233 us                                                      | 246 us: 1.06x slower                                                       |
| sympy_integrate         | 13.0 ms                                                     | 13.7 ms: 1.06x slower                                                      |
| async_tree_io           | 712 ms                                                      | 753 ms: 1.06x slower                                                       |
| dask                    | 255 ms                                                      | 270 ms: 1.06x slower                                                       |
| raytrace                | 192 ms                                                      | 204 ms: 1.06x slower                                                       |
| sympy_str               | 171 ms                                                      | 182 ms: 1.06x slower                                                       |
| sympy_sum               | 90.1 ms                                                     | 95.8 ms: 1.06x slower                                                      |
| async_tree_cpu_io_mixed | 477 ms                                                      | 508 ms: 1.06x slower                                                       |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.68 ms: 1.07x slower                                                      |
| logging_format          | 6.72 us                                                     | 7.19 us: 1.07x slower                                                      |
| regex_effbot            | 1.58 ms                                                     | 1.70 ms: 1.08x slower                                                      |
| logging_simple          | 6.21 us                                                     | 6.68 us: 1.08x slower                                                      |
| deepcopy_memo           | 23.4 us                                                     | 25.3 us: 1.08x slower                                                      |
| crypto_pyaes            | 46.4 ms                                                     | 50.6 ms: 1.09x slower                                                      |
| scimark_lu              | 57.5 ms                                                     | 62.7 ms: 1.09x slower                                                      |
| nqueens                 | 61.7 ms                                                     | 67.6 ms: 1.10x slower                                                      |
| django_template         | 22.8 ms                                                     | 25.0 ms: 1.10x slower                                                      |
| async_tree_none         | 286 ms                                                      | 317 ms: 1.11x slower                                                       |
| sqlglot_transpile       | 1.02 ms                                                     | 1.13 ms: 1.11x slower                                                      |
| go                      | 89.0 ms                                                     | 99.5 ms: 1.12x slower                                                      |
| comprehensions          | 14.0 us                                                     | 15.7 us: 1.13x slower                                                      |
| async_tree_memoization  | 333 ms                                                      | 375 ms: 1.13x slower                                                       |
| json                    | 2.94 ms                                                     | 3.32 ms: 1.13x slower                                                      |
| sqlalchemy_imperative   | 9.20 ms                                                     | 10.4 ms: 1.13x slower                                                      |
| unpickle_pure_python    | 134 us                                                      | 152 us: 1.13x slower                                                       |
| richards                | 27.6 ms                                                     | 31.7 ms: 1.15x slower                                                      |
| hexiom                  | 4.00 ms                                                     | 4.61 ms: 1.15x slower                                                      |
| spectral_norm           | 63.9 ms                                                     | 73.7 ms: 1.15x slower                                                      |
| chaos                   | 42.1 ms                                                     | 48.7 ms: 1.16x slower                                                      |
| sqlglot_parse           | 802 us                                                      | 936 us: 1.17x slower                                                       |
| mdp                     | 1.42 sec                                                    | 1.67 sec: 1.18x slower                                                     |
| logging_silent          | 60.5 ns                                                     | 72.4 ns: 1.20x slower                                                      |
| unpack_sequence         | 36.9 ns                                                     | 45.4 ns: 1.23x slower                                                      |
| deltablue               | 2.12 ms                                                     | 2.66 ms: 1.25x slower                                                      |
| mypy2                   | 209 ms                                                      | 278 ms: 1.33x slower                                                       |
| json_dumps              | 5.83 ms                                                     | 7.78 ms: 1.33x slower                                                      |
| coverage                | 39.8 ms                                                     | 54.1 ms: 1.36x slower                                                      |
| asyncio_tcp             | 471 ms                                                      | 675 ms: 1.43x slower                                                       |
| generators              | 22.6 ms                                                     | 33.9 ms: 1.50x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.06x slower                                                               |

Benchmark hidden because not significant (3): xml_etree_iterparse, nbody, sqlalchemy_declarative
Ignored benchmarks (8) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20220711-3.11.0b4-5a7e1e0/bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
