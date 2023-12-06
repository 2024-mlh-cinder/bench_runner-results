
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: windows-amd64
- commit hash: 7fb79b8
- commit date: 2023-09-05
- overall geometric mean: 1.01x slower
- HPT reliability: 99.53%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| docutils       | 1.65 sec                                                                   | 1.68 sec: 1.02x slower                                             |
| Geometric mean | (ref)                                                                      | 1.01x slower                                                       |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| nbody          | 78.2 ms                                                                    | 76.8 ms: 1.02x faster                                              |
| float          | 56.7 ms                                                                    | 55.8 ms: 1.02x faster                                              |
| pidigits       | 150 ms                                                                     | 150 ms: 1.00x slower                                               |
| Geometric mean | (ref)                                                                      | 1.01x faster                                                       |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| regex_effbot   | 1.58 ms                                                                    | 1.57 ms: 1.01x faster                                              |
| regex_v8       | 14.8 ms                                                                    | 15.0 ms: 1.01x slower                                              |
| regex_compile  | 94.3 ms                                                                    | 95.9 ms: 1.02x slower                                              |
| Geometric mean | (ref)                                                                      | 1.01x slower                                                       |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|----------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| tomli_loads          | 1.57 sec                                                                   | 1.50 sec: 1.05x faster                                             |
| pickle_dict          | 18.9 us                                                                    | 18.5 us: 1.02x faster                                              |
| unpickle             | 8.39 us                                                                    | 8.31 us: 1.01x faster                                              |
| pickle_pure_python   | 197 us                                                                     | 196 us: 1.01x faster                                               |
| json_loads           | 13.5 us                                                                    | 13.6 us: 1.01x slower                                              |
| json_dumps           | 5.85 ms                                                                    | 5.97 ms: 1.02x slower                                              |
| xml_etree_parse      | 91.2 ms                                                                    | 93.2 ms: 1.02x slower                                              |
| xml_etree_process    | 39.2 ms                                                                    | 40.1 ms: 1.02x slower                                              |
| unpickle_list        | 2.69 us                                                                    | 2.76 us: 1.02x slower                                              |
| xml_etree_generate   | 56.0 ms                                                                    | 57.6 ms: 1.03x slower                                              |
| unpickle_pure_python | 140 us                                                                     | 147 us: 1.05x slower                                               |
| xml_etree_iterparse  | 63.0 ms                                                                    | 66.5 ms: 1.06x slower                                              |
| Geometric mean       | (ref)                                                                      | 1.01x slower                                                       |

Benchmark hidden because not significant (2): pickle_list, pickle

Benchmarks with tag 'startup':
==============================

Benchmark hidden because not significant (2): python_startup, python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|-----------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako      | 7.47 ms                                                                    | 6.79 ms: 1.10x faster                                              |

All benchmarks:
===============

| Benchmark                | bm-20230905-pythonperf1-amd64-python-deea7c82682848b2a0db-3.13.0a0-deea7c8 | bm-20230905-pythonperf1-amd64-brandtbucher-justin-3.13.0a0-7fb79b8 |
|--------------------------|:--------------------------------------------------------------------------:|:------------------------------------------------------------------:|
| mako                     | 7.47 ms                                                                    | 6.79 ms: 1.10x faster                                              |
| scimark_sor              | 89.4 ms                                                                    | 83.6 ms: 1.07x faster                                              |
| mdp                      | 1.54 sec                                                                   | 1.45 sec: 1.06x faster                                             |
| tomli_loads              | 1.57 sec                                                                   | 1.50 sec: 1.05x faster                                             |
| spectral_norm            | 71.2 ms                                                                    | 68.1 ms: 1.05x faster                                              |
| fannkuch                 | 255 ms                                                                     | 247 ms: 1.03x faster                                               |
| async_tree_io            | 752 ms                                                                     | 732 ms: 1.03x faster                                               |
| deepcopy_reduce          | 2.26 us                                                                    | 2.21 us: 1.03x faster                                              |
| pickle_dict              | 18.9 us                                                                    | 18.5 us: 1.02x faster                                              |
| nbody                    | 78.2 ms                                                                    | 76.8 ms: 1.02x faster                                              |
| json                     | 3.00 ms                                                                    | 2.94 ms: 1.02x faster                                              |
| float                    | 56.7 ms                                                                    | 55.8 ms: 1.02x faster                                              |
| unpack_sequence          | 37.6 ns                                                                    | 37.1 ns: 1.01x faster                                              |
| logging_format           | 7.19 us                                                                    | 7.11 us: 1.01x faster                                              |
| unpickle                 | 8.39 us                                                                    | 8.31 us: 1.01x faster                                              |
| regex_effbot             | 1.58 ms                                                                    | 1.57 ms: 1.01x faster                                              |
| deepcopy_memo            | 24.9 us                                                                    | 24.8 us: 1.01x faster                                              |
| coverage                 | 47.1 ms                                                                    | 46.7 ms: 1.01x faster                                              |
| pickle_pure_python       | 197 us                                                                     | 196 us: 1.01x faster                                               |
| logging_simple           | 6.70 us                                                                    | 6.66 us: 1.01x faster                                              |
| pidigits                 | 150 ms                                                                     | 150 ms: 1.00x slower                                               |
| pyflate                  | 312 ms                                                                     | 313 ms: 1.00x slower                                               |
| dulwich_log              | 46.5 ms                                                                    | 46.7 ms: 1.00x slower                                              |
| json_loads               | 13.5 us                                                                    | 13.6 us: 1.01x slower                                              |
| pprint_safe_repr         | 538 ms                                                                     | 541 ms: 1.01x slower                                               |
| deepcopy                 | 248 us                                                                     | 250 us: 1.01x slower                                               |
| richards_super           | 33.1 ms                                                                    | 33.5 ms: 1.01x slower                                              |
| scimark_lu               | 59.4 ms                                                                    | 60.1 ms: 1.01x slower                                              |
| scimark_fft              | 187 ms                                                                     | 189 ms: 1.01x slower                                               |
| logging_silent           | 64.2 ns                                                                    | 65.0 ns: 1.01x slower                                              |
| pprint_pformat           | 1.10 sec                                                                   | 1.11 sec: 1.01x slower                                             |
| regex_v8                 | 14.8 ms                                                                    | 15.0 ms: 1.01x slower                                              |
| gc_traversal             | 1.48 ms                                                                    | 1.50 ms: 1.01x slower                                              |
| richards                 | 29.4 ms                                                                    | 29.9 ms: 1.02x slower                                              |
| deltablue                | 2.30 ms                                                                    | 2.34 ms: 1.02x slower                                              |
| bench_thread_pool        | 855 us                                                                     | 869 us: 1.02x slower                                               |
| regex_compile            | 94.3 ms                                                                    | 95.9 ms: 1.02x slower                                              |
| docutils                 | 1.65 sec                                                                   | 1.68 sec: 1.02x slower                                             |
| mypy2                    | 222 ms                                                                     | 227 ms: 1.02x slower                                               |
| sqlite_synth             | 1.76 us                                                                    | 1.79 us: 1.02x slower                                              |
| json_dumps               | 5.85 ms                                                                    | 5.97 ms: 1.02x slower                                              |
| pycparser                | 748 ms                                                                     | 765 ms: 1.02x slower                                               |
| xml_etree_parse          | 91.2 ms                                                                    | 93.2 ms: 1.02x slower                                              |
| crypto_pyaes             | 45.5 ms                                                                    | 46.5 ms: 1.02x slower                                              |
| sqlglot_optimize         | 36.2 ms                                                                    | 37.0 ms: 1.02x slower                                              |
| sqlglot_transpile        | 1.10 ms                                                                    | 1.12 ms: 1.02x slower                                              |
| xml_etree_process        | 39.2 ms                                                                    | 40.1 ms: 1.02x slower                                              |
| typing_runtime_protocols | 98.3 us                                                                    | 101 us: 1.02x slower                                               |
| scimark_monte_carlo      | 43.3 ms                                                                    | 44.3 ms: 1.02x slower                                              |
| unpickle_list            | 2.69 us                                                                    | 2.76 us: 1.02x slower                                              |
| sqlglot_normalize        | 194 ms                                                                     | 199 ms: 1.03x slower                                               |
| xml_etree_generate       | 56.0 ms                                                                    | 57.6 ms: 1.03x slower                                              |
| generators               | 24.2 ms                                                                    | 24.9 ms: 1.03x slower                                              |
| raytrace                 | 181 ms                                                                     | 187 ms: 1.03x slower                                               |
| chaos                    | 43.7 ms                                                                    | 45.5 ms: 1.04x slower                                              |
| bench_mp_pool            | 67.3 ms                                                                    | 70.2 ms: 1.04x slower                                              |
| sqlglot_parse            | 870 us                                                                     | 912 us: 1.05x slower                                               |
| nqueens                  | 62.2 ms                                                                    | 65.2 ms: 1.05x slower                                              |
| unpickle_pure_python     | 140 us                                                                     | 147 us: 1.05x slower                                               |
| xml_etree_iterparse      | 63.0 ms                                                                    | 66.5 ms: 1.06x slower                                              |
| meteor_contest           | 75.1 ms                                                                    | 79.3 ms: 1.06x slower                                              |
| async_generators         | 243 ms                                                                     | 257 ms: 1.06x slower                                               |
| go                       | 97.9 ms                                                                    | 103 ms: 1.06x slower                                               |
| telco                    | 4.60 ms                                                                    | 4.87 ms: 1.06x slower                                              |
| comprehensions           | 14.8 us                                                                    | 15.9 us: 1.08x slower                                              |
| scimark_sparse_mat_mult  | 2.44 ms                                                                    | 2.66 ms: 1.09x slower                                              |
| hexiom                   | 4.34 ms                                                                    | 4.77 ms: 1.10x slower                                              |
| Geometric mean           | (ref)                                                                      | 1.01x slower                                                       |

Benchmark hidden because not significant (15): asyncio_tcp, async_tree_none, dask, async_tree_memoization, pickle_list, async_tree_cpu_io_mixed, python_startup, tornado_http, pathlib, regex_dna, coroutines, pickle, create_gc_cycles, python_startup_no_site, asyncio_tcp_ssl


# HPT report

- Reliability score: 99.53% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
