
# Results vs. 3.12.0

- fork: python
- ref: main
- machine: windows-amd64
- commit hash: 8e56d55
- commit date: 2023-10-07
- overall geometric mean: 1.02x slower
- HPT reliability: 99.95%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| docutils       | 1.63 sec                                                    | 1.61 sec: 1.01x faster                                     |
| tornado_http   | 87.7 ms                                                     | 89.5 ms: 1.02x slower                                      |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| pidigits       | 150 ms                                                      | 151 ms: 1.00x slower                                       |
| Geometric mean | (ref)                                                       | 1.00x slower                                               |

Benchmark hidden because not significant (2): float, nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| regex_effbot   | 1.62 ms                                                     | 1.60 ms: 1.01x faster                                      |
| regex_dna      | 124 ms                                                      | 124 ms: 1.00x slower                                       |
| regex_compile  | 88.3 ms                                                     | 90.7 ms: 1.03x slower                                      |
| regex_v8       | 13.9 ms                                                     | 15.3 ms: 1.10x slower                                      |
| Geometric mean | (ref)                                                       | 1.03x slower                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|----------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| unpickle_list        | 2.78 us                                                     | 2.64 us: 1.05x faster                                      |
| pickle_dict          | 19.3 us                                                     | 18.3 us: 1.05x faster                                      |
| pickle               | 7.13 us                                                     | 6.91 us: 1.03x faster                                      |
| pickle_pure_python   | 196 us                                                      | 193 us: 1.02x faster                                       |
| xml_etree_process    | 38.4 ms                                                     | 38.9 ms: 1.01x slower                                      |
| xml_etree_generate   | 55.6 ms                                                     | 56.4 ms: 1.01x slower                                      |
| json_loads           | 13.4 us                                                     | 13.6 us: 1.02x slower                                      |
| json_dumps           | 5.60 ms                                                     | 5.74 ms: 1.03x slower                                      |
| xml_etree_parse      | 89.2 ms                                                     | 91.8 ms: 1.03x slower                                      |
| xml_etree_iterparse  | 62.5 ms                                                     | 64.6 ms: 1.03x slower                                      |
| unpickle_pure_python | 133 us                                                      | 138 us: 1.04x slower                                       |
| tomli_loads          | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| Geometric mean       | (ref)                                                       | 1.01x slower                                               |

Benchmark hidden because not significant (2): unpickle, pickle_list

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                      |
| python_startup         | 19.5 ms                                                     | 19.9 ms: 1.02x slower                                      |
| Geometric mean         | (ref)                                                       | 1.02x slower                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|-----------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| mako      | 6.93 ms                                                     | 7.43 ms: 1.07x slower                                      |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231007-pythonperf1-amd64-python-main-3.13.0a0-8e56d55 |
|-------------------------|:-----------------------------------------------------------:|:----------------------------------------------------------:|
| coverage                | 51.5 ms                                                     | 46.1 ms: 1.12x faster                                      |
| raytrace                | 191 ms                                                      | 172 ms: 1.11x faster                                       |
| async_tree_none         | 294 ms                                                      | 270 ms: 1.09x faster                                       |
| crypto_pyaes            | 47.4 ms                                                     | 44.9 ms: 1.05x faster                                      |
| unpickle_list           | 2.78 us                                                     | 2.64 us: 1.05x faster                                      |
| pickle_dict             | 19.3 us                                                     | 18.3 us: 1.05x faster                                      |
| bench_mp_pool           | 66.4 ms                                                     | 63.3 ms: 1.05x faster                                      |
| asyncio_tcp_ssl         | 1.96 sec                                                    | 1.87 sec: 1.05x faster                                     |
| deepcopy                | 240 us                                                      | 233 us: 1.03x faster                                       |
| pickle                  | 7.13 us                                                     | 6.91 us: 1.03x faster                                      |
| deepcopy_reduce         | 2.13 us                                                     | 2.07 us: 1.03x faster                                      |
| chaos                   | 42.8 ms                                                     | 41.6 ms: 1.03x faster                                      |
| scimark_monte_carlo     | 43.7 ms                                                     | 42.5 ms: 1.03x faster                                      |
| mdp                     | 1.44 sec                                                    | 1.41 sec: 1.02x faster                                     |
| create_gc_cycles        | 727 us                                                      | 714 us: 1.02x faster                                       |
| pickle_pure_python      | 196 us                                                      | 193 us: 1.02x faster                                       |
| regex_effbot            | 1.62 ms                                                     | 1.60 ms: 1.01x faster                                      |
| async_tree_cpu_io_mixed | 479 ms                                                      | 473 ms: 1.01x faster                                       |
| docutils                | 1.63 sec                                                    | 1.61 sec: 1.01x faster                                     |
| sqlglot_normalize       | 185 ms                                                      | 184 ms: 1.01x faster                                       |
| pidigits                | 150 ms                                                      | 151 ms: 1.00x slower                                       |
| regex_dna               | 124 ms                                                      | 124 ms: 1.00x slower                                       |
| sqlglot_parse           | 820 us                                                      | 825 us: 1.01x slower                                       |
| json                    | 2.86 ms                                                     | 2.89 ms: 1.01x slower                                      |
| pathlib                 | 77.1 ms                                                     | 78.0 ms: 1.01x slower                                      |
| sqlglot_transpile       | 1.04 ms                                                     | 1.05 ms: 1.01x slower                                      |
| scimark_lu              | 58.1 ms                                                     | 58.8 ms: 1.01x slower                                      |
| xml_etree_process       | 38.4 ms                                                     | 38.9 ms: 1.01x slower                                      |
| xml_etree_generate      | 55.6 ms                                                     | 56.4 ms: 1.01x slower                                      |
| deepcopy_memo           | 23.8 us                                                     | 24.2 us: 1.01x slower                                      |
| json_loads              | 13.4 us                                                     | 13.6 us: 1.02x slower                                      |
| python_startup_no_site  | 16.1 ms                                                     | 16.4 ms: 1.02x slower                                      |
| async_tree_io           | 720 ms                                                      | 733 ms: 1.02x slower                                       |
| generators              | 22.7 ms                                                     | 23.2 ms: 1.02x slower                                      |
| meteor_contest          | 73.1 ms                                                     | 74.4 ms: 1.02x slower                                      |
| async_generators        | 235 ms                                                      | 240 ms: 1.02x slower                                       |
| deltablue               | 2.14 ms                                                     | 2.18 ms: 1.02x slower                                      |
| tornado_http            | 87.7 ms                                                     | 89.5 ms: 1.02x slower                                      |
| pyflate                 | 297 ms                                                      | 304 ms: 1.02x slower                                       |
| sqlglot_optimize        | 34.4 ms                                                     | 35.2 ms: 1.02x slower                                      |
| python_startup          | 19.5 ms                                                     | 19.9 ms: 1.02x slower                                      |
| json_dumps              | 5.60 ms                                                     | 5.74 ms: 1.03x slower                                      |
| regex_compile           | 88.3 ms                                                     | 90.7 ms: 1.03x slower                                      |
| go                      | 88.5 ms                                                     | 91.0 ms: 1.03x slower                                      |
| xml_etree_parse         | 89.2 ms                                                     | 91.8 ms: 1.03x slower                                      |
| scimark_fft             | 180 ms                                                      | 185 ms: 1.03x slower                                       |
| async_tree_memoization  | 336 ms                                                      | 346 ms: 1.03x slower                                       |
| xml_etree_iterparse     | 62.5 ms                                                     | 64.6 ms: 1.03x slower                                      |
| hexiom                  | 4.03 ms                                                     | 4.16 ms: 1.03x slower                                      |
| pprint_safe_repr        | 512 ms                                                      | 529 ms: 1.03x slower                                       |
| mypy2                   | 207 ms                                                      | 215 ms: 1.04x slower                                       |
| scimark_sor             | 79.6 ms                                                     | 82.6 ms: 1.04x slower                                      |
| pprint_pformat          | 1.04 sec                                                    | 1.08 sec: 1.04x slower                                     |
| unpickle_pure_python    | 133 us                                                      | 138 us: 1.04x slower                                       |
| logging_simple          | 6.21 us                                                     | 6.48 us: 1.04x slower                                      |
| logging_format          | 6.67 us                                                     | 6.96 us: 1.04x slower                                      |
| logging_silent          | 60.6 ns                                                     | 63.4 ns: 1.05x slower                                      |
| unpack_sequence         | 37.5 ns                                                     | 39.4 ns: 1.05x slower                                      |
| comprehensions          | 14.1 us                                                     | 14.9 us: 1.05x slower                                      |
| richards_super          | 30.5 ms                                                     | 32.1 ms: 1.06x slower                                      |
| dulwich_log             | 42.4 ms                                                     | 45.1 ms: 1.06x slower                                      |
| coroutines              | 14.0 ms                                                     | 14.9 ms: 1.06x slower                                      |
| spectral_norm           | 63.2 ms                                                     | 67.2 ms: 1.06x slower                                      |
| mako                    | 6.93 ms                                                     | 7.43 ms: 1.07x slower                                      |
| richards                | 26.9 ms                                                     | 29.0 ms: 1.08x slower                                      |
| tomli_loads             | 1.37 sec                                                    | 1.48 sec: 1.08x slower                                     |
| fannkuch                | 237 ms                                                      | 257 ms: 1.09x slower                                       |
| regex_v8                | 13.9 ms                                                     | 15.3 ms: 1.10x slower                                      |
| telco                   | 4.09 ms                                                     | 4.73 ms: 1.16x slower                                      |
| pycparser               | 673 ms                                                      | 861 ms: 1.28x slower                                       |
| Geometric mean          | (ref)                                                       | 1.02x slower                                               |

Benchmark hidden because not significant (11): float, unpickle, pickle_list, nqueens, gc_traversal, sqlite_synth, typing_runtime_protocols, scimark_sparse_mat_mult, asyncio_tcp, nbody, bench_thread_pool
Ignored benchmarks (3) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: 2to3, aiohttp, dask


# HPT report

- Reliability score: 99.95% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
