
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 898dcc2
- commit date: 2023-10-10
- overall geometric mean: 1.08x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.04x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.63 sec                                                                   | 1.70 sec: 1.04x slower                                             |
| tornado_http   | 89.2 ms                                                                    | 91.2 ms: 1.02x slower                                              |
| Geometric mean | (ref)                                                                      | 1.03x slower                                                       |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| float          | 55.2 ms                                                                    | 54.6 ms: 1.01x faster                                              |
| pidigits       | 150 ms                                                                     | 151 ms: 1.01x slower                                               |
| nbody          | 75.1 ms                                                                    | 84.9 ms: 1.13x slower                                              |
| Geometric mean | (ref)                                                                      | 1.04x slower                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_dna      | 123 ms                                                                     | 119 ms: 1.04x faster                                               |
| regex_effbot   | 1.61 ms                                                                    | 1.58 ms: 1.02x faster                                              |
| regex_v8       | 15.1 ms                                                                    | 15.2 ms: 1.00x slower                                              |
| regex_compile  | 92.4 ms                                                                    | 98.1 ms: 1.06x slower                                              |
| Geometric mean | (ref)                                                                      | 1.00x slower                                                       |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|----------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| tomli_loads          | 1.50 sec                                                                   | 1.40 sec: 1.07x faster                                             |
| pickle               | 7.26 us                                                                    | 7.11 us: 1.02x faster                                              |
| unpickle_list        | 2.71 us                                                                    | 2.69 us: 1.01x faster                                              |
| pickle_dict          | 18.3 us                                                                    | 18.3 us: 1.00x slower                                              |
| xml_etree_parse      | 91.8 ms                                                                    | 93.2 ms: 1.02x slower                                              |
| pickle_list          | 2.87 us                                                                    | 2.94 us: 1.02x slower                                              |
| json_dumps           | 5.81 ms                                                                    | 6.06 ms: 1.04x slower                                              |
| xml_etree_iterparse  | 64.4 ms                                                                    | 70.2 ms: 1.09x slower                                              |
| xml_etree_generate   | 56.9 ms                                                                    | 64.1 ms: 1.13x slower                                              |
| pickle_pure_python   | 197 us                                                                     | 225 us: 1.14x slower                                               |
| xml_etree_process    | 39.6 ms                                                                    | 45.9 ms: 1.16x slower                                              |
| unpickle_pure_python | 141 us                                                                     | 175 us: 1.24x slower                                               |
| Geometric mean       | (ref)                                                                      | 1.05x slower                                                       |

Benchmark hidden because not significant (2): json_loads, unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|------------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| python_startup_no_site | 16.1 ms                                                                    | 16.6 ms: 1.03x slower                                              |
| python_startup         | 19.3 ms                                                                    | 20.0 ms: 1.03x slower                                              |
| Geometric mean         | (ref)                                                                      | 1.03x slower                                                       |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|-----------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.19 ms                                                                    | 6.72 ms: 1.07x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20231010-pythonperf1-amd64-python-982f1b7d6dc2f13b9607-3.13.0a0-982f1b7 | bm-20231010-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-898dcc2 |
|--------------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| pycparser                | 901 ms                                                                     | 776 ms: 1.16x faster                                               |
| mako                     | 7.19 ms                                                                    | 6.72 ms: 1.07x faster                                              |
| tomli_loads              | 1.50 sec                                                                   | 1.40 sec: 1.07x faster                                             |
| regex_dna                | 123 ms                                                                     | 119 ms: 1.04x faster                                               |
| scimark_sparse_mat_mult  | 2.48 ms                                                                    | 2.42 ms: 1.02x faster                                              |
| pickle                   | 7.26 us                                                                    | 7.11 us: 1.02x faster                                              |
| regex_effbot             | 1.61 ms                                                                    | 1.58 ms: 1.02x faster                                              |
| typing_runtime_protocols | 103 us                                                                     | 101 us: 1.01x faster                                               |
| float                    | 55.2 ms                                                                    | 54.6 ms: 1.01x faster                                              |
| unpickle_list            | 2.71 us                                                                    | 2.69 us: 1.01x faster                                              |
| pickle_dict              | 18.3 us                                                                    | 18.3 us: 1.00x slower                                              |
| fannkuch                 | 260 ms                                                                     | 261 ms: 1.00x slower                                               |
| regex_v8                 | 15.1 ms                                                                    | 15.2 ms: 1.00x slower                                              |
| pidigits                 | 150 ms                                                                     | 151 ms: 1.01x slower                                               |
| dulwich_log              | 45.4 ms                                                                    | 45.7 ms: 1.01x slower                                              |
| pathlib                  | 77.8 ms                                                                    | 78.4 ms: 1.01x slower                                              |
| mdp                      | 1.43 sec                                                                   | 1.44 sec: 1.01x slower                                             |
| telco                    | 4.72 ms                                                                    | 4.77 ms: 1.01x slower                                              |
| create_gc_cycles         | 720 us                                                                     | 729 us: 1.01x slower                                               |
| xml_etree_parse          | 91.8 ms                                                                    | 93.2 ms: 1.02x slower                                              |
| tornado_http             | 89.2 ms                                                                    | 91.2 ms: 1.02x slower                                              |
| pickle_list              | 2.87 us                                                                    | 2.94 us: 1.02x slower                                              |
| python_startup_no_site   | 16.1 ms                                                                    | 16.6 ms: 1.03x slower                                              |
| python_startup           | 19.3 ms                                                                    | 20.0 ms: 1.03x slower                                              |
| json                     | 2.92 ms                                                                    | 3.03 ms: 1.04x slower                                              |
| json_dumps               | 5.81 ms                                                                    | 6.06 ms: 1.04x slower                                              |
| docutils                 | 1.63 sec                                                                   | 1.70 sec: 1.04x slower                                             |
| meteor_contest           | 75.9 ms                                                                    | 79.3 ms: 1.05x slower                                              |
| async_tree_cpu_io_mixed  | 455 ms                                                                     | 477 ms: 1.05x slower                                               |
| bench_thread_pool        | 835 us                                                                     | 880 us: 1.05x slower                                               |
| mypy2                    | 217 ms                                                                     | 229 ms: 1.06x slower                                               |
| async_tree_io            | 729 ms                                                                     | 771 ms: 1.06x slower                                               |
| regex_compile            | 92.4 ms                                                                    | 98.1 ms: 1.06x slower                                              |
| async_tree_memoization   | 346 ms                                                                     | 368 ms: 1.06x slower                                               |
| asyncio_tcp_ssl          | 1.77 sec                                                                   | 1.88 sec: 1.06x slower                                             |
| async_tree_none          | 271 ms                                                                     | 288 ms: 1.06x slower                                               |
| logging_simple           | 6.55 us                                                                    | 6.98 us: 1.07x slower                                              |
| logging_format           | 6.96 us                                                                    | 7.42 us: 1.07x slower                                              |
| crypto_pyaes             | 44.7 ms                                                                    | 48.3 ms: 1.08x slower                                              |
| nqueens                  | 61.2 ms                                                                    | 66.4 ms: 1.09x slower                                              |
| comprehensions           | 14.5 us                                                                    | 15.8 us: 1.09x slower                                              |
| pprint_safe_repr         | 536 ms                                                                     | 582 ms: 1.09x slower                                               |
| bench_mp_pool            | 63.7 ms                                                                    | 69.3 ms: 1.09x slower                                              |
| pprint_pformat           | 1.10 sec                                                                   | 1.20 sec: 1.09x slower                                             |
| deepcopy_reduce          | 2.20 us                                                                    | 2.39 us: 1.09x slower                                              |
| xml_etree_iterparse      | 64.4 ms                                                                    | 70.2 ms: 1.09x slower                                              |
| scimark_fft              | 183 ms                                                                     | 200 ms: 1.10x slower                                               |
| async_generators         | 245 ms                                                                     | 269 ms: 1.10x slower                                               |
| sqlglot_optimize         | 35.2 ms                                                                    | 38.7 ms: 1.10x slower                                              |
| sqlglot_normalize        | 186 ms                                                                     | 208 ms: 1.12x slower                                               |
| pyflate                  | 304 ms                                                                     | 342 ms: 1.12x slower                                               |
| deltablue                | 2.20 ms                                                                    | 2.47 ms: 1.12x slower                                              |
| xml_etree_generate       | 56.9 ms                                                                    | 64.1 ms: 1.13x slower                                              |
| nbody                    | 75.1 ms                                                                    | 84.9 ms: 1.13x slower                                              |
| pickle_pure_python       | 197 us                                                                     | 225 us: 1.14x slower                                               |
| hexiom                   | 4.22 ms                                                                    | 4.83 ms: 1.15x slower                                              |
| sqlglot_transpile        | 1.06 ms                                                                    | 1.22 ms: 1.15x slower                                              |
| deepcopy                 | 242 us                                                                     | 279 us: 1.15x slower                                               |
| chaos                    | 42.4 ms                                                                    | 48.9 ms: 1.15x slower                                              |
| xml_etree_process        | 39.6 ms                                                                    | 45.9 ms: 1.16x slower                                              |
| scimark_monte_carlo      | 43.1 ms                                                                    | 50.4 ms: 1.17x slower                                              |
| unpack_sequence          | 41.2 ns                                                                    | 48.4 ns: 1.17x slower                                              |
| sqlglot_parse            | 828 us                                                                     | 976 us: 1.18x slower                                               |
| richards_super           | 32.5 ms                                                                    | 38.6 ms: 1.19x slower                                              |
| raytrace                 | 178 ms                                                                     | 211 ms: 1.19x slower                                               |
| go                       | 91.8 ms                                                                    | 110 ms: 1.20x slower                                               |
| richards                 | 28.9 ms                                                                    | 34.8 ms: 1.21x slower                                              |
| scimark_sor              | 85.0 ms                                                                    | 103 ms: 1.21x slower                                               |
| spectral_norm            | 65.6 ms                                                                    | 80.9 ms: 1.23x slower                                              |
| unpickle_pure_python     | 141 us                                                                     | 175 us: 1.24x slower                                               |
| scimark_lu               | 60.4 ms                                                                    | 75.0 ms: 1.24x slower                                              |
| deepcopy_memo            | 24.9 us                                                                    | 31.8 us: 1.28x slower                                              |
| coroutines               | 14.8 ms                                                                    | 18.9 ms: 1.28x slower                                              |
| logging_silent           | 63.6 ns                                                                    | 90.9 ns: 1.43x slower                                              |
| generators               | 22.4 ms                                                                    | 34.0 ms: 1.52x slower                                              |
| Geometric mean           | (ref)                                                                      | 1.08x slower                                                       |

Benchmark hidden because not significant (6): asyncio_tcp, json_loads, sqlite_synth, coverage, gc_traversal, unpickle


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.05x
- 95% likely to have a slowdown of 1.05x
- 99% likely to have a slowdown of 1.04x
