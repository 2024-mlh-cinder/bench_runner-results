
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: ef4bd1b
- commit date: 2023-10-08
- overall geometric mean: 1.00x faster
- HPT reliability: 93.70%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 288 ms: 1.00x slower                                       |
| Geometric mean | (ref)                                                        | 1.00x faster                                               |

Benchmark hidden because not significant (2): docutils, tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 85.4 ms: 1.10x faster                                      |
| float          | 78.5 ms                                                      | 78.1 ms: 1.01x faster                                      |
| pidigits       | 264 ms                                                       | 265 ms: 1.01x slower                                       |
| Geometric mean | (ref)                                                        | 1.03x faster                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_v8       | 25.0 ms                                                      | 23.2 ms: 1.08x faster                                      |
| regex_compile  | 146 ms                                                       | 144 ms: 1.01x faster                                       |
| regex_effbot   | 3.47 ms                                                      | 3.53 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                        | 1.02x faster                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_list          | 4.39 us                                                      | 4.32 us: 1.02x faster                                      |
| pickle_pure_python   | 323 us                                                       | 319 us: 1.01x faster                                       |
| pickle_dict          | 31.7 us                                                      | 31.5 us: 1.01x faster                                      |
| pickle               | 10.1 us                                                      | 10.0 us: 1.01x faster                                      |
| unpickle_pure_python | 207 us                                                       | 205 us: 1.01x faster                                       |
| xml_etree_generate   | 86.1 ms                                                      | 86.6 ms: 1.01x slower                                      |
| json_loads           | 24.3 us                                                      | 24.4 us: 1.01x slower                                      |
| json_dumps           | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                      |
| xml_etree_iterparse  | 103 ms                                                       | 105 ms: 1.02x slower                                       |
| xml_etree_parse      | 146 ms                                                       | 150 ms: 1.02x slower                                       |
| tomli_loads          | 2.20 sec                                                     | 2.25 sec: 1.02x slower                                     |
| unpickle_list        | 4.77 us                                                      | 5.03 us: 1.05x slower                                      |
| Geometric mean       | (ref)                                                        | 1.01x slower                                               |

Benchmark hidden because not significant (2): unpickle, xml_etree_process

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                      |
| Geometric mean         | (ref)                                                        | 1.00x faster                                               |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|-----------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 9.94 ms                                                      | 10.1 ms: 1.01x slower                                      |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231008-pythonperf2-x86_64-python-3.12-3.12.0+-ef4bd1b |
|-------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| unpack_sequence         | 53.3 ns                                                      | 47.4 ns: 1.12x faster                                      |
| nbody                   | 94.1 ms                                                      | 85.4 ms: 1.10x faster                                      |
| regex_v8                | 25.0 ms                                                      | 23.2 ms: 1.08x faster                                      |
| pprint_safe_repr        | 823 ms                                                       | 791 ms: 1.04x faster                                       |
| pprint_pformat          | 1.67 sec                                                     | 1.61 sec: 1.04x faster                                     |
| logging_simple          | 6.73 us                                                      | 6.50 us: 1.04x faster                                      |
| create_gc_cycles        | 1.67 ms                                                      | 1.62 ms: 1.04x faster                                      |
| coverage                | 89.6 ms                                                      | 86.6 ms: 1.03x faster                                      |
| pycparser               | 1.27 sec                                                     | 1.24 sec: 1.03x faster                                     |
| pathlib                 | 19.8 ms                                                      | 19.3 ms: 1.03x faster                                      |
| bench_thread_pool       | 980 us                                                       | 956 us: 1.03x faster                                       |
| deltablue               | 3.29 ms                                                      | 3.23 ms: 1.02x faster                                      |
| logging_silent          | 95.6 ns                                                      | 93.8 ns: 1.02x faster                                      |
| go                      | 150 ms                                                       | 148 ms: 1.02x faster                                       |
| logging_format          | 7.37 us                                                      | 7.25 us: 1.02x faster                                      |
| scimark_fft             | 304 ms                                                       | 299 ms: 1.02x faster                                       |
| sqlglot_parse           | 1.40 ms                                                      | 1.38 ms: 1.02x faster                                      |
| pickle_list             | 4.39 us                                                      | 4.32 us: 1.02x faster                                      |
| sqlglot_transpile       | 1.80 ms                                                      | 1.78 ms: 1.01x faster                                      |
| meteor_contest          | 128 ms                                                       | 126 ms: 1.01x faster                                       |
| deepcopy_memo           | 37.4 us                                                      | 36.9 us: 1.01x faster                                      |
| crypto_pyaes            | 80.9 ms                                                      | 79.9 ms: 1.01x faster                                      |
| regex_compile           | 146 ms                                                       | 144 ms: 1.01x faster                                       |
| gc_traversal            | 3.54 ms                                                      | 3.50 ms: 1.01x faster                                      |
| pickle_pure_python      | 323 us                                                       | 319 us: 1.01x faster                                       |
| scimark_sparse_mat_mult | 4.42 ms                                                      | 4.38 ms: 1.01x faster                                      |
| deepcopy_reduce         | 3.46 us                                                      | 3.43 us: 1.01x faster                                      |
| dulwich_log             | 65.3 ms                                                      | 64.8 ms: 1.01x faster                                      |
| deepcopy                | 376 us                                                       | 373 us: 1.01x faster                                       |
| pickle_dict             | 31.7 us                                                      | 31.5 us: 1.01x faster                                      |
| pickle                  | 10.1 us                                                      | 10.0 us: 1.01x faster                                      |
| unpickle_pure_python    | 207 us                                                       | 205 us: 1.01x faster                                       |
| asyncio_tcp             | 381 ms                                                       | 379 ms: 1.01x faster                                       |
| float                   | 78.5 ms                                                      | 78.1 ms: 1.01x faster                                      |
| python_startup_no_site  | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                      |
| asyncio_tcp_ssl         | 1.58 sec                                                     | 1.57 sec: 1.01x faster                                     |
| spectral_norm           | 91.6 ms                                                      | 91.3 ms: 1.00x faster                                      |
| 2to3                    | 287 ms                                                       | 288 ms: 1.00x slower                                       |
| sqlglot_normalize       | 117 ms                                                       | 118 ms: 1.00x slower                                       |
| mdp                     | 2.53 sec                                                     | 2.54 sec: 1.00x slower                                     |
| raytrace                | 302 ms                                                       | 303 ms: 1.00x slower                                       |
| pidigits                | 264 ms                                                       | 265 ms: 1.01x slower                                       |
| xml_etree_generate      | 86.1 ms                                                      | 86.6 ms: 1.01x slower                                      |
| coroutines              | 23.0 ms                                                      | 23.1 ms: 1.01x slower                                      |
| json_loads              | 24.3 us                                                      | 24.4 us: 1.01x slower                                      |
| sqlite_synth            | 2.70 us                                                      | 2.72 us: 1.01x slower                                      |
| nqueens                 | 90.1 ms                                                      | 91.1 ms: 1.01x slower                                      |
| fannkuch                | 350 ms                                                       | 354 ms: 1.01x slower                                       |
| json_dumps              | 10.2 ms                                                      | 10.4 ms: 1.01x slower                                      |
| mako                    | 9.94 ms                                                      | 10.1 ms: 1.01x slower                                      |
| generators              | 36.7 ms                                                      | 37.2 ms: 1.01x slower                                      |
| chaos                   | 62.9 ms                                                      | 63.9 ms: 1.02x slower                                      |
| regex_effbot            | 3.47 ms                                                      | 3.53 ms: 1.02x slower                                      |
| xml_etree_iterparse     | 103 ms                                                       | 105 ms: 1.02x slower                                       |
| xml_etree_parse         | 146 ms                                                       | 150 ms: 1.02x slower                                       |
| tomli_loads             | 2.20 sec                                                     | 2.25 sec: 1.02x slower                                     |
| telco                   | 6.96 ms                                                      | 7.14 ms: 1.03x slower                                      |
| unpickle_list           | 4.77 us                                                      | 5.03 us: 1.05x slower                                      |
| mypy2                   | 368 ms                                                       | 458 ms: 1.24x slower                                       |
| bench_mp_pool           | 5.34 ms                                                      | 6.96 ms: 1.30x slower                                      |
| Geometric mean          | (ref)                                                        | 1.00x faster                                               |

Benchmark hidden because not significant (23): scimark_lu, tornado_http, dask, async_tree_memoization, richards_super, sqlglot_optimize, regex_dna, hexiom, docutils, python_startup, unpickle, async_tree_none, async_tree_io, richards, pyflate, xml_etree_process, async_generators, async_tree_cpu_io_mixed, comprehensions, typing_runtime_protocols, scimark_monte_carlo, scimark_sor, json


# HPT report

- Reliability score: 93.70% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
