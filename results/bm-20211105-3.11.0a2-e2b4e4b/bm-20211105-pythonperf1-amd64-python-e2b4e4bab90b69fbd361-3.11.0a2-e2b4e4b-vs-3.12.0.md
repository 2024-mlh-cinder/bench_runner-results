
# Results vs. 3.12.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: windows-amd64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.14x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 210 ms: 1.01x faster                                                       |
| chameleon      | 4.95 ms                                                     | 5.53 ms: 1.12x slower                                                      |
| docutils       | 1.61 sec                                                    | 1.67 sec: 1.04x slower                                                     |
| tornado_http   | 87.2 ms                                                     | 98.3 ms: 1.13x slower                                                      |
| Geometric mean | (ref)                                                       | 1.07x slower                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none         | 286 ms                                                      | 307 ms: 1.07x slower                                                       |
| async_tree_cpu_io_mixed | 477 ms                                                      | 530 ms: 1.11x slower                                                       |
| async_tree_io           | 712 ms                                                      | 793 ms: 1.11x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 395 ms: 1.19x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.12x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 148 ms: 1.02x faster                                                       |
| float          | 54.7 ms                                                     | 56.1 ms: 1.03x slower                                                      |
| nbody          | 68.8 ms                                                     | 90.3 ms: 1.31x slower                                                      |
| Geometric mean | (ref)                                                       | 1.10x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 90.4 ms: 1.04x slower                                                      |
| regex_dna      | 119 ms                                                      | 131 ms: 1.10x slower                                                       |
| regex_effbot   | 1.58 ms                                                     | 1.82 ms: 1.15x slower                                                      |
| regex_v8       | 13.5 ms                                                     | 16.6 ms: 1.23x slower                                                      |
| Geometric mean | (ref)                                                       | 1.13x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_dict          | 18.9 us                                                     | 16.2 us: 1.17x faster                                                      |
| pickle_list          | 2.88 us                                                     | 2.49 us: 1.16x faster                                                      |
| pickle               | 7.38 us                                                     | 6.61 us: 1.12x faster                                                      |
| unpickle             | 8.44 us                                                     | 7.81 us: 1.08x faster                                                      |
| unpickle_list        | 2.69 us                                                     | 2.54 us: 1.06x faster                                                      |
| xml_etree_generate   | 55.8 ms                                                     | 54.7 ms: 1.02x faster                                                      |
| xml_etree_iterparse  | 63.1 ms                                                     | 65.2 ms: 1.03x slower                                                      |
| xml_etree_parse      | 90.5 ms                                                     | 93.8 ms: 1.04x slower                                                      |
| xml_etree_process    | 37.6 ms                                                     | 39.7 ms: 1.06x slower                                                      |
| json_loads           | 13.6 us                                                     | 14.9 us: 1.10x slower                                                      |
| pickle_pure_python   | 195 us                                                      | 228 us: 1.17x slower                                                       |
| unpickle_pure_python | 134 us                                                      | 168 us: 1.25x slower                                                       |
| json_dumps           | 5.83 ms                                                     | 7.94 ms: 1.36x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.03x slower                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 15.9 ms                                                     | 15.1 ms: 1.06x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| django_template | 22.8 ms                                                     | 26.0 ms: 1.14x slower                                                      |
| mako            | 7.05 ms                                                     | 8.07 ms: 1.14x slower                                                      |
| Geometric mean  | (ref)                                                       | 1.14x slower                                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_generators        | 230 ms                                                      | 192 ms: 1.20x faster                                                       |
| pickle_dict             | 18.9 us                                                     | 16.2 us: 1.17x faster                                                      |
| pickle_list             | 2.88 us                                                     | 2.49 us: 1.16x faster                                                      |
| logging_simple          | 6.21 us                                                     | 5.45 us: 1.14x faster                                                      |
| logging_format          | 6.72 us                                                     | 5.92 us: 1.13x faster                                                      |
| pickle                  | 7.38 us                                                     | 6.61 us: 1.12x faster                                                      |
| bench_mp_pool           | 67.2 ms                                                     | 61.4 ms: 1.10x faster                                                      |
| pathlib                 | 79.6 ms                                                     | 73.4 ms: 1.08x faster                                                      |
| gc_traversal            | 1.49 ms                                                     | 1.37 ms: 1.08x faster                                                      |
| unpickle                | 8.44 us                                                     | 7.81 us: 1.08x faster                                                      |
| unpickle_list           | 2.69 us                                                     | 2.54 us: 1.06x faster                                                      |
| python_startup_no_site  | 15.9 ms                                                     | 15.1 ms: 1.06x faster                                                      |
| create_gc_cycles        | 726 us                                                      | 686 us: 1.06x faster                                                       |
| telco                   | 4.08 ms                                                     | 3.91 ms: 1.05x faster                                                      |
| xml_etree_generate      | 55.8 ms                                                     | 54.7 ms: 1.02x faster                                                      |
| pidigits                | 150 ms                                                      | 148 ms: 1.02x faster                                                       |
| 2to3                    | 213 ms                                                      | 210 ms: 1.01x faster                                                       |
| float                   | 54.7 ms                                                     | 56.1 ms: 1.03x slower                                                      |
| sqlite_synth            | 1.75 us                                                     | 1.80 us: 1.03x slower                                                      |
| dulwich_log             | 42.7 ms                                                     | 44.1 ms: 1.03x slower                                                      |
| xml_etree_iterparse     | 63.1 ms                                                     | 65.2 ms: 1.03x slower                                                      |
| xml_etree_parse         | 90.5 ms                                                     | 93.8 ms: 1.04x slower                                                      |
| regex_compile           | 87.2 ms                                                     | 90.4 ms: 1.04x slower                                                      |
| docutils                | 1.61 sec                                                    | 1.67 sec: 1.04x slower                                                     |
| json                    | 2.94 ms                                                     | 3.06 ms: 1.04x slower                                                      |
| sqlalchemy_declarative  | 84.5 ms                                                     | 88.5 ms: 1.05x slower                                                      |
| meteor_contest          | 72.1 ms                                                     | 76.2 ms: 1.06x slower                                                      |
| xml_etree_process       | 37.6 ms                                                     | 39.7 ms: 1.06x slower                                                      |
| sqlglot_normalize       | 183 ms                                                      | 196 ms: 1.07x slower                                                       |
| deepcopy_reduce         | 2.08 us                                                     | 2.23 us: 1.07x slower                                                      |
| async_tree_none         | 286 ms                                                      | 307 ms: 1.07x slower                                                       |
| pprint_safe_repr        | 508 ms                                                      | 547 ms: 1.08x slower                                                       |
| pprint_pformat          | 1.04 sec                                                    | 1.13 sec: 1.09x slower                                                     |
| nqueens                 | 61.7 ms                                                     | 67.3 ms: 1.09x slower                                                      |
| bench_thread_pool       | 830 us                                                      | 906 us: 1.09x slower                                                       |
| json_loads              | 13.6 us                                                     | 14.9 us: 1.10x slower                                                      |
| regex_dna               | 119 ms                                                      | 131 ms: 1.10x slower                                                       |
| sqlglot_optimize        | 34.0 ms                                                     | 37.5 ms: 1.10x slower                                                      |
| async_tree_cpu_io_mixed | 477 ms                                                      | 530 ms: 1.11x slower                                                       |
| sympy_integrate         | 13.0 ms                                                     | 14.4 ms: 1.11x slower                                                      |
| raytrace                | 192 ms                                                      | 214 ms: 1.11x slower                                                       |
| async_tree_io           | 712 ms                                                      | 793 ms: 1.11x slower                                                       |
| sympy_str               | 171 ms                                                      | 191 ms: 1.11x slower                                                       |
| chameleon               | 4.95 ms                                                     | 5.53 ms: 1.12x slower                                                      |
| sympy_expand            | 278 ms                                                      | 311 ms: 1.12x slower                                                       |
| fannkuch                | 244 ms                                                      | 275 ms: 1.13x slower                                                       |
| tornado_http            | 87.2 ms                                                     | 98.3 ms: 1.13x slower                                                      |
| sympy_sum               | 90.1 ms                                                     | 102 ms: 1.13x slower                                                       |
| mdp                     | 1.42 sec                                                    | 1.61 sec: 1.14x slower                                                     |
| pycparser               | 673 ms                                                      | 769 ms: 1.14x slower                                                       |
| deepcopy                | 233 us                                                      | 266 us: 1.14x slower                                                       |
| django_template         | 22.8 ms                                                     | 26.0 ms: 1.14x slower                                                      |
| mako                    | 7.05 ms                                                     | 8.07 ms: 1.14x slower                                                      |
| regex_effbot            | 1.58 ms                                                     | 1.82 ms: 1.15x slower                                                      |
| sqlalchemy_imperative   | 9.20 ms                                                     | 10.6 ms: 1.15x slower                                                      |
| dask                    | 255 ms                                                      | 295 ms: 1.16x slower                                                       |
| pickle_pure_python      | 195 us                                                      | 228 us: 1.17x slower                                                       |
| scimark_fft             | 181 ms                                                      | 212 ms: 1.17x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 395 ms: 1.19x slower                                                       |
| logging_silent          | 60.5 ns                                                     | 72.1 ns: 1.19x slower                                                      |
| go                      | 89.0 ms                                                     | 106 ms: 1.19x slower                                                       |
| scimark_monte_carlo     | 43.0 ms                                                     | 51.7 ms: 1.20x slower                                                      |
| deepcopy_memo           | 23.4 us                                                     | 28.1 us: 1.20x slower                                                      |
| pyflate                 | 294 ms                                                      | 358 ms: 1.22x slower                                                       |
| richards                | 27.6 ms                                                     | 34.0 ms: 1.23x slower                                                      |
| regex_v8                | 13.5 ms                                                     | 16.6 ms: 1.23x slower                                                      |
| unpickle_pure_python    | 134 us                                                      | 168 us: 1.25x slower                                                       |
| hexiom                  | 4.00 ms                                                     | 5.06 ms: 1.26x slower                                                      |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 3.18 ms: 1.27x slower                                                      |
| crypto_pyaes            | 46.4 ms                                                     | 58.9 ms: 1.27x slower                                                      |
| scimark_sor             | 79.8 ms                                                     | 101 ms: 1.27x slower                                                       |
| chaos                   | 42.1 ms                                                     | 53.9 ms: 1.28x slower                                                      |
| coroutines              | 14.1 ms                                                     | 18.1 ms: 1.28x slower                                                      |
| spectral_norm           | 63.9 ms                                                     | 82.7 ms: 1.29x slower                                                      |
| nbody                   | 68.8 ms                                                     | 90.3 ms: 1.31x slower                                                      |
| deltablue               | 2.12 ms                                                     | 2.86 ms: 1.35x slower                                                      |
| json_dumps              | 5.83 ms                                                     | 7.94 ms: 1.36x slower                                                      |
| comprehensions          | 14.0 us                                                     | 19.1 us: 1.36x slower                                                      |
| generators              | 22.6 ms                                                     | 31.0 ms: 1.37x slower                                                      |
| unpack_sequence         | 36.9 ns                                                     | 51.9 ns: 1.41x slower                                                      |
| scimark_lu              | 57.5 ms                                                     | 81.5 ms: 1.42x slower                                                      |
| sqlglot_transpile       | 1.02 ms                                                     | 1.50 ms: 1.47x slower                                                      |
| asyncio_tcp             | 471 ms                                                      | 695 ms: 1.48x slower                                                       |
| sqlglot_parse           | 802 us                                                      | 1.29 ms: 1.61x slower                                                      |
| coverage                | 39.8 ms                                                     | 262 ms: 6.58x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.14x slower                                                               |

Benchmark hidden because not significant (1): python_startup
Ignored benchmarks (10) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, mypy2, richards_super, tomli_loads, typing_runtime_protocols
Ignored benchmarks (6) of results/bm-20211105-3.11.0a2-e2b4e4b/bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.09x
- 95% likely to have a slowdown of 1.09x
- 99% likely to have a slowdown of 1.08x
