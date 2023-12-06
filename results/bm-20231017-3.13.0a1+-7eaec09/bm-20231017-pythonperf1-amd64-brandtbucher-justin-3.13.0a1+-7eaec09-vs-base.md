
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.05x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 1.65 sec                                                                    | 1.70 sec: 1.03x slower                                              |
| Geometric mean | (ref)                                                                       | 1.02x slower                                                        |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| float          | 58.0 ms                                                                     | 52.0 ms: 1.11x faster                                               |
| pidigits       | 147 ms                                                                      | 151 ms: 1.02x slower                                                |
| Geometric mean | (ref)                                                                       | 1.03x faster                                                        |

Benchmark hidden because not significant (1): nbody

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_dna      | 119 ms                                                                      | 119 ms: 1.00x faster                                                |
| regex_effbot   | 1.58 ms                                                                     | 1.61 ms: 1.01x slower                                               |
| regex_compile  | 94.2 ms                                                                     | 95.7 ms: 1.02x slower                                               |
| regex_v8       | 15.1 ms                                                                     | 21.4 ms: 1.42x slower                                               |
| Geometric mean | (ref)                                                                       | 1.10x slower                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| tomli_loads          | 1.59 sec                                                                    | 1.38 sec: 1.15x faster                                              |
| pickle               | 7.11 us                                                                     | 7.04 us: 1.01x faster                                               |
| unpickle             | 8.11 us                                                                     | 8.16 us: 1.01x slower                                               |
| unpickle_list        | 2.69 us                                                                     | 2.71 us: 1.01x slower                                               |
| xml_etree_parse      | 91.5 ms                                                                     | 92.5 ms: 1.01x slower                                               |
| xml_etree_iterparse  | 65.6 ms                                                                     | 68.1 ms: 1.04x slower                                               |
| json_dumps           | 5.76 ms                                                                     | 5.98 ms: 1.04x slower                                               |
| xml_etree_generate   | 57.6 ms                                                                     | 62.2 ms: 1.08x slower                                               |
| xml_etree_process    | 40.1 ms                                                                     | 44.8 ms: 1.12x slower                                               |
| pickle_pure_python   | 200 us                                                                      | 227 us: 1.14x slower                                                |
| unpickle_pure_python | 145 us                                                                      | 170 us: 1.17x slower                                                |
| Geometric mean       | (ref)                                                                       | 1.03x slower                                                        |

Benchmark hidden because not significant (3): json_loads, pickle_dict, pickle_list

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 7.59 ms                                                                     | 6.39 ms: 1.19x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20231016-pythonperf1-amd64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-pythonperf1-amd64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:---------------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako                     | 7.59 ms                                                                     | 6.39 ms: 1.19x faster                                               |
| tomli_loads              | 1.59 sec                                                                    | 1.38 sec: 1.15x faster                                              |
| float                    | 58.0 ms                                                                     | 52.0 ms: 1.11x faster                                               |
| scimark_sparse_mat_mult  | 2.57 ms                                                                     | 2.34 ms: 1.10x faster                                               |
| mdp                      | 1.54 sec                                                                    | 1.44 sec: 1.07x faster                                              |
| fannkuch                 | 265 ms                                                                      | 249 ms: 1.06x faster                                                |
| deltablue                | 2.38 ms                                                                     | 2.34 ms: 1.02x faster                                               |
| pickle                   | 7.11 us                                                                     | 7.04 us: 1.01x faster                                               |
| sqlite_synth             | 1.67 us                                                                     | 1.66 us: 1.01x faster                                               |
| regex_dna                | 119 ms                                                                      | 119 ms: 1.00x faster                                                |
| telco                    | 4.70 ms                                                                     | 4.69 ms: 1.00x faster                                               |
| unpickle                 | 8.11 us                                                                     | 8.16 us: 1.01x slower                                               |
| unpickle_list            | 2.69 us                                                                     | 2.71 us: 1.01x slower                                               |
| xml_etree_parse          | 91.5 ms                                                                     | 92.5 ms: 1.01x slower                                               |
| gc_traversal             | 1.49 ms                                                                     | 1.51 ms: 1.01x slower                                               |
| regex_effbot             | 1.58 ms                                                                     | 1.61 ms: 1.01x slower                                               |
| hexiom                   | 4.51 ms                                                                     | 4.58 ms: 1.01x slower                                               |
| async_tree_io            | 755 ms                                                                      | 767 ms: 1.02x slower                                                |
| coverage                 | 45.0 ms                                                                     | 45.8 ms: 1.02x slower                                               |
| regex_compile            | 94.2 ms                                                                     | 95.7 ms: 1.02x slower                                               |
| logging_simple           | 6.84 us                                                                     | 6.95 us: 1.02x slower                                               |
| async_tree_cpu_io_mixed  | 466 ms                                                                      | 476 ms: 1.02x slower                                                |
| pidigits                 | 147 ms                                                                      | 151 ms: 1.02x slower                                                |
| nqueens                  | 63.7 ms                                                                     | 65.4 ms: 1.03x slower                                               |
| async_tree_memoization   | 357 ms                                                                      | 368 ms: 1.03x slower                                                |
| bench_thread_pool        | 850 us                                                                      | 877 us: 1.03x slower                                                |
| docutils                 | 1.65 sec                                                                    | 1.70 sec: 1.03x slower                                              |
| crypto_pyaes             | 45.1 ms                                                                     | 46.6 ms: 1.03x slower                                               |
| scimark_fft              | 186 ms                                                                      | 192 ms: 1.03x slower                                                |
| async_tree_none          | 281 ms                                                                      | 290 ms: 1.04x slower                                                |
| xml_etree_iterparse      | 65.6 ms                                                                     | 68.1 ms: 1.04x slower                                               |
| json_dumps               | 5.76 ms                                                                     | 5.98 ms: 1.04x slower                                               |
| bench_mp_pool            | 63.8 ms                                                                     | 66.3 ms: 1.04x slower                                               |
| mypy2                    | 221 ms                                                                      | 230 ms: 1.04x slower                                                |
| sqlglot_normalize        | 198 ms                                                                      | 207 ms: 1.05x slower                                                |
| meteor_contest           | 74.2 ms                                                                     | 77.6 ms: 1.05x slower                                               |
| pyflate                  | 315 ms                                                                      | 331 ms: 1.05x slower                                                |
| sqlglot_optimize         | 36.9 ms                                                                     | 38.9 ms: 1.05x slower                                               |
| pprint_pformat           | 1.09 sec                                                                    | 1.17 sec: 1.07x slower                                              |
| deepcopy_reduce          | 2.24 us                                                                     | 2.41 us: 1.07x slower                                               |
| xml_etree_generate       | 57.6 ms                                                                     | 62.2 ms: 1.08x slower                                               |
| pprint_safe_repr         | 534 ms                                                                      | 577 ms: 1.08x slower                                                |
| typing_runtime_protocols | 98.8 us                                                                     | 107 us: 1.09x slower                                                |
| async_generators         | 251 ms                                                                      | 274 ms: 1.09x slower                                                |
| richards_super           | 35.1 ms                                                                     | 38.4 ms: 1.09x slower                                               |
| chaos                    | 44.2 ms                                                                     | 48.6 ms: 1.10x slower                                               |
| go                       | 99.1 ms                                                                     | 109 ms: 1.10x slower                                                |
| sqlglot_transpile        | 1.11 ms                                                                     | 1.22 ms: 1.10x slower                                               |
| richards                 | 31.2 ms                                                                     | 34.5 ms: 1.10x slower                                               |
| raytrace                 | 189 ms                                                                      | 209 ms: 1.11x slower                                                |
| sqlglot_parse            | 882 us                                                                      | 979 us: 1.11x slower                                                |
| deepcopy                 | 249 us                                                                      | 277 us: 1.11x slower                                                |
| xml_etree_process        | 40.1 ms                                                                     | 44.8 ms: 1.12x slower                                               |
| scimark_monte_carlo      | 44.1 ms                                                                     | 50.1 ms: 1.14x slower                                               |
| pickle_pure_python       | 200 us                                                                      | 227 us: 1.14x slower                                                |
| deepcopy_memo            | 26.4 us                                                                     | 30.2 us: 1.14x slower                                               |
| unpickle_pure_python     | 145 us                                                                      | 170 us: 1.17x slower                                                |
| unpack_sequence          | 40.0 ns                                                                     | 48.4 ns: 1.21x slower                                               |
| scimark_sor              | 85.9 ms                                                                     | 105 ms: 1.22x slower                                                |
| spectral_norm            | 65.6 ms                                                                     | 80.1 ms: 1.22x slower                                               |
| scimark_lu               | 60.7 ms                                                                     | 75.3 ms: 1.24x slower                                               |
| coroutines               | 15.3 ms                                                                     | 19.4 ms: 1.27x slower                                               |
| generators               | 25.4 ms                                                                     | 33.5 ms: 1.32x slower                                               |
| logging_silent           | 68.9 ns                                                                     | 92.1 ns: 1.34x slower                                               |
| regex_v8                 | 15.1 ms                                                                     | 21.4 ms: 1.42x slower                                               |
| Geometric mean           | (ref)                                                                       | 1.05x slower                                                        |

Benchmark hidden because not significant (16): pycparser, python_startup, python_startup_no_site, asyncio_tcp, comprehensions, create_gc_cycles, dulwich_log, json_loads, logging_format, nbody, pathlib, pickle_dict, tornado_http, json, pickle_list, asyncio_tcp_ssl


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.02x
- 95% likely to have a slowdown of 1.02x
- 99% likely to have a slowdown of 1.01x
