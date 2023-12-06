
# Results vs. 3.10.4

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: windows-amd64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.03x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 210 ms: 1.14x faster                                                       |
| chameleon      | 6.02 ms                                                     | 5.53 ms: 1.09x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.67 sec: 1.12x faster                                                     |
| html5lib       | 47.5 ms                                                     | 41.4 ms: 1.15x faster                                                      |
| tornado_http   | 106 ms                                                      | 98.3 ms: 1.07x faster                                                      |
| Geometric mean | (ref)                                                       | 1.11x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none         | 424 ms                                                      | 307 ms: 1.38x faster                                                       |
| async_tree_io           | 1.07 sec                                                    | 793 ms: 1.35x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 395 ms: 1.28x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 530 ms: 1.17x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.29x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 56.1 ms: 1.10x faster                                                      |
| pidigits       | 146 ms                                                      | 148 ms: 1.01x slower                                                       |
| nbody          | 71.0 ms                                                     | 90.3 ms: 1.27x slower                                                      |
| Geometric mean | (ref)                                                       | 1.05x slower                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 90.4 ms: 1.13x faster                                                      |
| regex_dna      | 129 ms                                                      | 131 ms: 1.01x slower                                                       |
| regex_v8       | 15.0 ms                                                     | 16.6 ms: 1.10x slower                                                      |
| regex_effbot   | 1.56 ms                                                     | 1.82 ms: 1.16x slower                                                      |
| Geometric mean | (ref)                                                       | 1.04x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpickle             | 9.11 us                                                     | 7.81 us: 1.17x faster                                                      |
| pickle_pure_python   | 259 us                                                      | 228 us: 1.14x faster                                                       |
| json_dumps           | 8.77 ms                                                     | 7.94 ms: 1.10x faster                                                      |
| xml_etree_process    | 43.1 ms                                                     | 39.7 ms: 1.09x faster                                                      |
| pickle_list          | 2.69 us                                                     | 2.49 us: 1.08x faster                                                      |
| unpickle_list        | 2.68 us                                                     | 2.54 us: 1.06x faster                                                      |
| unpickle_pure_python | 177 us                                                      | 168 us: 1.06x faster                                                       |
| pickle_dict          | 17.1 us                                                     | 16.2 us: 1.06x faster                                                      |
| pickle               | 6.87 us                                                     | 6.61 us: 1.04x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 93.8 ms: 1.03x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 54.7 ms: 1.00x slower                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 65.2 ms: 1.01x slower                                                      |
| json_loads           | 14.2 us                                                     | 14.9 us: 1.05x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 19.7 ms                                                     | 18.8 ms: 1.04x faster                                                      |
| python_startup_no_site | 15.3 ms                                                     | 15.1 ms: 1.02x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.03x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 8.07 ms: 1.11x faster                                                      |
| django_template | 28.8 ms                                                     | 26.0 ms: 1.11x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 17.5 ms: 1.08x faster                                                      |
| genshi_xml      | 39.4 ms                                                     | 38.5 ms: 1.03x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.08x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-pythonperf1-amd64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.86 ms: 1.44x faster                                                      |
| async_tree_none         | 424 ms                                                      | 307 ms: 1.38x faster                                                       |
| async_tree_io           | 1.07 sec                                                    | 793 ms: 1.35x faster                                                       |
| logging_silent          | 93.4 ns                                                     | 72.1 ns: 1.30x faster                                                      |
| async_tree_memoization  | 505 ms                                                      | 395 ms: 1.28x faster                                                       |
| go                      | 135 ms                                                      | 106 ms: 1.27x faster                                                       |
| raytrace                | 266 ms                                                      | 214 ms: 1.24x faster                                                       |
| richards                | 40.6 ms                                                     | 34.0 ms: 1.20x faster                                                      |
| thrift                  | 623 us                                                      | 528 us: 1.18x faster                                                       |
| pycparser               | 905 ms                                                      | 769 ms: 1.18x faster                                                       |
| unpickle                | 9.11 us                                                     | 7.81 us: 1.17x faster                                                      |
| create_gc_cycles        | 800 us                                                      | 686 us: 1.17x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 530 ms: 1.17x faster                                                       |
| logging_simple          | 6.28 us                                                     | 5.45 us: 1.15x faster                                                      |
| html5lib                | 47.5 ms                                                     | 41.4 ms: 1.15x faster                                                      |
| async_generators        | 219 ms                                                      | 192 ms: 1.14x faster                                                       |
| pickle_pure_python      | 259 us                                                      | 228 us: 1.14x faster                                                       |
| logging_format          | 6.73 us                                                     | 5.92 us: 1.14x faster                                                      |
| 2to3                    | 239 ms                                                      | 210 ms: 1.14x faster                                                       |
| regex_compile           | 102 ms                                                      | 90.4 ms: 1.13x faster                                                      |
| scimark_monte_carlo     | 58.0 ms                                                     | 51.7 ms: 1.12x faster                                                      |
| docutils                | 1.88 sec                                                    | 1.67 sec: 1.12x faster                                                     |
| pyflate                 | 402 ms                                                      | 358 ms: 1.12x faster                                                       |
| sqlalchemy_declarative  | 98.6 ms                                                     | 88.5 ms: 1.11x faster                                                      |
| mako                    | 8.98 ms                                                     | 8.07 ms: 1.11x faster                                                      |
| django_template         | 28.8 ms                                                     | 26.0 ms: 1.11x faster                                                      |
| hexiom                  | 5.59 ms                                                     | 5.06 ms: 1.11x faster                                                      |
| json_dumps              | 8.77 ms                                                     | 7.94 ms: 1.10x faster                                                      |
| chaos                   | 59.5 ms                                                     | 53.9 ms: 1.10x faster                                                      |
| dulwich_log             | 48.6 ms                                                     | 44.1 ms: 1.10x faster                                                      |
| float                   | 61.7 ms                                                     | 56.1 ms: 1.10x faster                                                      |
| chameleon               | 6.02 ms                                                     | 5.53 ms: 1.09x faster                                                      |
| pprint_pformat          | 1.22 sec                                                    | 1.13 sec: 1.09x faster                                                     |
| pprint_safe_repr        | 594 ms                                                      | 547 ms: 1.09x faster                                                       |
| xml_etree_process       | 43.1 ms                                                     | 39.7 ms: 1.09x faster                                                      |
| pickle_list             | 2.69 us                                                     | 2.49 us: 1.08x faster                                                      |
| genshi_text             | 18.8 ms                                                     | 17.5 ms: 1.08x faster                                                      |
| tornado_http            | 106 ms                                                      | 98.3 ms: 1.07x faster                                                      |
| crypto_pyaes            | 63.1 ms                                                     | 58.9 ms: 1.07x faster                                                      |
| mdp                     | 1.71 sec                                                    | 1.61 sec: 1.06x faster                                                     |
| pylint                  | 341 ms                                                      | 321 ms: 1.06x faster                                                       |
| unpickle_list           | 2.68 us                                                     | 2.54 us: 1.06x faster                                                      |
| unpickle_pure_python    | 177 us                                                      | 168 us: 1.06x faster                                                       |
| sqlite_synth            | 1.90 us                                                     | 1.80 us: 1.06x faster                                                      |
| pickle_dict             | 17.1 us                                                     | 16.2 us: 1.06x faster                                                      |
| sqlglot_optimize        | 39.4 ms                                                     | 37.5 ms: 1.05x faster                                                      |
| sqlglot_normalize       | 207 ms                                                      | 196 ms: 1.05x faster                                                       |
| sqlalchemy_imperative   | 11.2 ms                                                     | 10.6 ms: 1.05x faster                                                      |
| python_startup          | 19.7 ms                                                     | 18.8 ms: 1.04x faster                                                      |
| sympy_integrate         | 15.0 ms                                                     | 14.4 ms: 1.04x faster                                                      |
| pickle                  | 6.87 us                                                     | 6.61 us: 1.04x faster                                                      |
| scimark_sor             | 105 ms                                                      | 101 ms: 1.04x faster                                                       |
| sympy_sum               | 105 ms                                                      | 102 ms: 1.03x faster                                                       |
| dask                    | 305 ms                                                      | 295 ms: 1.03x faster                                                       |
| xml_etree_parse         | 96.8 ms                                                     | 93.8 ms: 1.03x faster                                                      |
| scimark_lu              | 84.0 ms                                                     | 81.5 ms: 1.03x faster                                                      |
| sympy_expand            | 320 ms                                                      | 311 ms: 1.03x faster                                                       |
| deepcopy_memo           | 29.0 us                                                     | 28.1 us: 1.03x faster                                                      |
| generators              | 31.8 ms                                                     | 31.0 ms: 1.03x faster                                                      |
| genshi_xml              | 39.4 ms                                                     | 38.5 ms: 1.03x faster                                                      |
| python_startup_no_site  | 15.3 ms                                                     | 15.1 ms: 1.02x faster                                                      |
| gc_traversal            | 1.40 ms                                                     | 1.37 ms: 1.02x faster                                                      |
| nqueens                 | 68.3 ms                                                     | 67.3 ms: 1.02x faster                                                      |
| json                    | 3.10 ms                                                     | 3.06 ms: 1.01x faster                                                      |
| sympy_str               | 193 ms                                                      | 191 ms: 1.01x faster                                                       |
| xml_etree_generate      | 54.5 ms                                                     | 54.7 ms: 1.00x slower                                                      |
| flaskblogging           | 2.04 sec                                                    | 2.05 sec: 1.01x slower                                                     |
| pidigits                | 146 ms                                                      | 148 ms: 1.01x slower                                                       |
| xml_etree_iterparse     | 64.5 ms                                                     | 65.2 ms: 1.01x slower                                                      |
| regex_dna               | 129 ms                                                      | 131 ms: 1.01x slower                                                       |
| telco                   | 3.82 ms                                                     | 3.91 ms: 1.02x slower                                                      |
| bench_mp_pool           | 59.9 ms                                                     | 61.4 ms: 1.02x slower                                                      |
| deepcopy                | 259 us                                                      | 266 us: 1.03x slower                                                       |
| meteor_contest          | 73.8 ms                                                     | 76.2 ms: 1.03x slower                                                      |
| sqlglot_transpile       | 1.45 ms                                                     | 1.50 ms: 1.03x slower                                                      |
| spectral_norm           | 78.9 ms                                                     | 82.7 ms: 1.05x slower                                                      |
| json_loads              | 14.2 us                                                     | 14.9 us: 1.05x slower                                                      |
| fannkuch                | 258 ms                                                      | 275 ms: 1.07x slower                                                       |
| sqlglot_parse           | 1.20 ms                                                     | 1.29 ms: 1.07x slower                                                      |
| regex_v8                | 15.0 ms                                                     | 16.6 ms: 1.10x slower                                                      |
| scimark_fft             | 187 ms                                                      | 212 ms: 1.13x slower                                                       |
| comprehensions          | 16.6 us                                                     | 19.1 us: 1.15x slower                                                      |
| regex_effbot            | 1.56 ms                                                     | 1.82 ms: 1.16x slower                                                      |
| coroutines              | 15.5 ms                                                     | 18.1 ms: 1.17x slower                                                      |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 3.18 ms: 1.19x slower                                                      |
| nbody                   | 71.0 ms                                                     | 90.3 ms: 1.27x slower                                                      |
| unpack_sequence         | 40.0 ns                                                     | 51.9 ns: 1.30x slower                                                      |
| coverage                | 38.4 ms                                                     | 262 ms: 6.83x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.03x faster                                                               |

Benchmark hidden because not significant (4): asyncio_tcp, bench_thread_pool, deepcopy_reduce, pathlib
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, mypy2, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.03x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.03x
