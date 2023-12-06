
# Results vs. 3.10.4

- fork: python
- ref: 3b9d793efcfd2c00c14f
- machine: windows-amd64
- commit hash: 3b9d793
- commit date: 2022-11-14
- overall geometric mean: 1.20x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 193 ms: 1.24x faster                                                       |
| chameleon      | 6.02 ms                                                     | 4.59 ms: 1.31x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.52 sec: 1.24x faster                                                     |
| html5lib       | 47.5 ms                                                     | 36.4 ms: 1.30x faster                                                      |
| tornado_http   | 106 ms                                                      | 89.5 ms: 1.18x faster                                                      |
| Geometric mean | (ref)                                                       | 1.25x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 783 ms: 1.37x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 386 ms: 1.31x faster                                                       |
| async_tree_none         | 424 ms                                                      | 325 ms: 1.30x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 507 ms: 1.22x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.30x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 48.7 ms: 1.27x faster                                                      |
| nbody          | 71.0 ms                                                     | 62.3 ms: 1.14x faster                                                      |
| Geometric mean | (ref)                                                       | 1.13x faster                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 102 ms                                                      | 82.3 ms: 1.24x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                                      |
| regex_dna      | 129 ms                                                      | 120 ms: 1.08x faster                                                       |
| regex_effbot   | 1.56 ms                                                     | 1.70 ms: 1.09x slower                                                      |
| Geometric mean | (ref)                                                       | 1.08x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 8.77 ms                                                     | 5.12 ms: 1.71x faster                                                      |
| pickle_pure_python   | 259 us                                                      | 180 us: 1.44x faster                                                       |
| unpickle_pure_python | 177 us                                                      | 130 us: 1.36x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 33.9 ms: 1.27x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 49.0 ms: 1.11x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 87.6 ms: 1.10x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.25 us: 1.10x faster                                                      |
| json_loads           | 14.2 us                                                     | 13.3 us: 1.07x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 61.3 ms: 1.05x faster                                                      |
| pickle               | 6.87 us                                                     | 6.57 us: 1.05x faster                                                      |
| pickle_list          | 2.69 us                                                     | 2.62 us: 1.03x faster                                                      |
| unpickle_list        | 2.68 us                                                     | 2.79 us: 1.04x slower                                                      |
| pickle_dict          | 17.1 us                                                     | 18.3 us: 1.07x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.15x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.2 ms: 1.08x faster                                                      |
| Geometric mean | (ref)                                                       | 1.04x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 6.25 ms: 1.44x faster                                                      |
| django_template | 28.8 ms                                                     | 21.6 ms: 1.33x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 14.4 ms: 1.31x faster                                                      |
| genshi_xml      | 39.4 ms                                                     | 32.2 ms: 1.22x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.32x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20221114-pythonperf1-amd64-python-3b9d793efcfd2c00c14f-3.12.0a2-3b9d793 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.24 ms: 1.84x faster                                                      |
| json_dumps              | 8.77 ms                                                     | 5.12 ms: 1.71x faster                                                      |
| mypy2                   | 347 ms                                                      | 212 ms: 1.64x faster                                                       |
| go                      | 135 ms                                                      | 84.0 ms: 1.61x faster                                                      |
| logging_silent          | 93.4 ns                                                     | 59.9 ns: 1.56x faster                                                      |
| scimark_sor             | 105 ms                                                      | 69.2 ms: 1.52x faster                                                      |
| richards                | 40.6 ms                                                     | 26.7 ms: 1.52x faster                                                      |
| pyflate                 | 402 ms                                                      | 272 ms: 1.48x faster                                                       |
| scimark_lu              | 84.0 ms                                                     | 56.9 ms: 1.48x faster                                                      |
| scimark_monte_carlo     | 58.0 ms                                                     | 39.8 ms: 1.46x faster                                                      |
| raytrace                | 266 ms                                                      | 184 ms: 1.44x faster                                                       |
| pickle_pure_python      | 259 us                                                      | 180 us: 1.44x faster                                                       |
| mako                    | 8.98 ms                                                     | 6.25 ms: 1.44x faster                                                      |
| hexiom                  | 5.59 ms                                                     | 4.00 ms: 1.40x faster                                                      |
| sqlglot_parse           | 1.20 ms                                                     | 865 us: 1.39x faster                                                       |
| pycparser               | 905 ms                                                      | 650 ms: 1.39x faster                                                       |
| crypto_pyaes            | 63.1 ms                                                     | 45.4 ms: 1.39x faster                                                      |
| chaos                   | 59.5 ms                                                     | 43.1 ms: 1.38x faster                                                      |
| async_tree_io           | 1.07 sec                                                    | 783 ms: 1.37x faster                                                       |
| unpickle_pure_python    | 177 us                                                      | 130 us: 1.36x faster                                                       |
| sqlglot_transpile       | 1.45 ms                                                     | 1.06 ms: 1.36x faster                                                      |
| django_template         | 28.8 ms                                                     | 21.6 ms: 1.33x faster                                                      |
| chameleon               | 6.02 ms                                                     | 4.59 ms: 1.31x faster                                                      |
| async_tree_memoization  | 505 ms                                                      | 386 ms: 1.31x faster                                                       |
| pprint_pformat          | 1.22 sec                                                    | 934 ms: 1.31x faster                                                       |
| genshi_text             | 18.8 ms                                                     | 14.4 ms: 1.31x faster                                                      |
| async_tree_none         | 424 ms                                                      | 325 ms: 1.30x faster                                                       |
| html5lib                | 47.5 ms                                                     | 36.4 ms: 1.30x faster                                                      |
| deepcopy_memo           | 29.0 us                                                     | 22.2 us: 1.30x faster                                                      |
| pprint_safe_repr        | 594 ms                                                      | 458 ms: 1.30x faster                                                       |
| unpack_sequence         | 40.0 ns                                                     | 30.8 ns: 1.30x faster                                                      |
| xml_etree_process       | 43.1 ms                                                     | 33.9 ms: 1.27x faster                                                      |
| float                   | 61.7 ms                                                     | 48.7 ms: 1.27x faster                                                      |
| async_generators        | 219 ms                                                      | 173 ms: 1.26x faster                                                       |
| spectral_norm           | 78.9 ms                                                     | 63.1 ms: 1.25x faster                                                      |
| regex_compile           | 102 ms                                                      | 82.3 ms: 1.24x faster                                                      |
| docutils                | 1.88 sec                                                    | 1.52 sec: 1.24x faster                                                     |
| 2to3                    | 239 ms                                                      | 193 ms: 1.24x faster                                                       |
| sqlglot_optimize        | 39.4 ms                                                     | 32.1 ms: 1.23x faster                                                      |
| genshi_xml              | 39.4 ms                                                     | 32.2 ms: 1.22x faster                                                      |
| async_tree_cpu_io_mixed | 617 ms                                                      | 507 ms: 1.22x faster                                                       |
| create_gc_cycles        | 800 us                                                      | 665 us: 1.20x faster                                                       |
| deepcopy                | 259 us                                                      | 217 us: 1.20x faster                                                       |
| nqueens                 | 68.3 ms                                                     | 57.5 ms: 1.19x faster                                                      |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.25 ms: 1.19x faster                                                      |
| deepcopy_reduce         | 2.22 us                                                     | 1.87 us: 1.19x faster                                                      |
| sqlglot_normalize       | 207 ms                                                      | 174 ms: 1.18x faster                                                       |
| dask                    | 305 ms                                                      | 258 ms: 1.18x faster                                                       |
| tornado_http            | 106 ms                                                      | 89.5 ms: 1.18x faster                                                      |
| sympy_integrate         | 15.0 ms                                                     | 12.9 ms: 1.16x faster                                                      |
| nbody                   | 71.0 ms                                                     | 62.3 ms: 1.14x faster                                                      |
| fannkuch                | 258 ms                                                      | 227 ms: 1.14x faster                                                       |
| sympy_expand            | 320 ms                                                      | 282 ms: 1.13x faster                                                       |
| json                    | 3.10 ms                                                     | 2.75 ms: 1.13x faster                                                      |
| dulwich_log             | 48.6 ms                                                     | 43.1 ms: 1.13x faster                                                      |
| mdp                     | 1.71 sec                                                    | 1.53 sec: 1.12x faster                                                     |
| thrift                  | 623 us                                                      | 558 us: 1.12x faster                                                       |
| xml_etree_generate      | 54.5 ms                                                     | 49.0 ms: 1.11x faster                                                      |
| sqlite_synth            | 1.90 us                                                     | 1.71 us: 1.11x faster                                                      |
| xml_etree_parse         | 96.8 ms                                                     | 87.6 ms: 1.10x faster                                                      |
| scimark_fft             | 187 ms                                                      | 170 ms: 1.10x faster                                                       |
| sympy_str               | 193 ms                                                      | 175 ms: 1.10x faster                                                       |
| unpickle                | 9.11 us                                                     | 8.25 us: 1.10x faster                                                      |
| sympy_sum               | 105 ms                                                      | 96.1 ms: 1.10x faster                                                      |
| bench_thread_pool       | 913 us                                                      | 835 us: 1.09x faster                                                       |
| regex_v8                | 15.0 ms                                                     | 13.8 ms: 1.09x faster                                                      |
| regex_dna               | 129 ms                                                      | 120 ms: 1.08x faster                                                       |
| comprehensions          | 16.6 us                                                     | 15.4 us: 1.08x faster                                                      |
| python_startup          | 19.7 ms                                                     | 18.2 ms: 1.08x faster                                                      |
| json_loads              | 14.2 us                                                     | 13.3 us: 1.07x faster                                                      |
| meteor_contest          | 73.8 ms                                                     | 69.3 ms: 1.07x faster                                                      |
| xml_etree_iterparse     | 64.5 ms                                                     | 61.3 ms: 1.05x faster                                                      |
| pickle                  | 6.87 us                                                     | 6.57 us: 1.05x faster                                                      |
| coroutines              | 15.5 ms                                                     | 15.0 ms: 1.03x faster                                                      |
| pickle_list             | 2.69 us                                                     | 2.62 us: 1.03x faster                                                      |
| logging_format          | 6.73 us                                                     | 6.56 us: 1.03x faster                                                      |
| logging_simple          | 6.28 us                                                     | 6.31 us: 1.01x slower                                                      |
| bench_mp_pool           | 59.9 ms                                                     | 61.2 ms: 1.02x slower                                                      |
| gc_traversal            | 1.40 ms                                                     | 1.44 ms: 1.03x slower                                                      |
| telco                   | 3.82 ms                                                     | 3.95 ms: 1.03x slower                                                      |
| unpickle_list           | 2.68 us                                                     | 2.79 us: 1.04x slower                                                      |
| pickle_dict             | 17.1 us                                                     | 18.3 us: 1.07x slower                                                      |
| regex_effbot            | 1.56 ms                                                     | 1.70 ms: 1.09x slower                                                      |
| generators              | 31.8 ms                                                     | 35.7 ms: 1.12x slower                                                      |
| coverage                | 38.4 ms                                                     | 52.0 ms: 1.36x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.20x faster                                                               |

Benchmark hidden because not significant (4): asyncio_tcp, pathlib, pidigits, python_startup_no_site
Ignored benchmarks (9) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.14x
