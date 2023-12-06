
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.01x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 1.50 sec                                                               | 1.52 sec: 1.01x slower                                         |
| Geometric mean | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (1): tornado_http

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pidigits       | 283 ms                                                                 | 283 ms: 1.00x faster                                           |
| float          | 54.7 ms                                                                | 56.0 ms: 1.02x slower                                          |
| nbody          | 71.1 ms                                                                | 75.6 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_effbot   | 2.57 ms                                                                | 2.56 ms: 1.00x faster                                          |
| regex_v8       | 16.8 ms                                                                | 16.9 ms: 1.00x slower                                          |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                   |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 1.54 sec                                                               | 1.34 sec: 1.15x faster                                         |
| pickle_pure_python   | 195 us                                                                 | 193 us: 1.01x faster                                           |
| pickle_dict          | 18.1 us                                                                | 17.9 us: 1.01x faster                                          |
| json_dumps           | 6.44 ms                                                                | 6.45 ms: 1.00x slower                                          |
| pickle               | 7.38 us                                                                | 7.42 us: 1.00x slower                                          |
| unpickle             | 9.12 us                                                                | 9.16 us: 1.00x slower                                          |
| xml_etree_generate   | 57.3 ms                                                                | 57.7 ms: 1.01x slower                                          |
| xml_etree_parse      | 110 ms                                                                 | 111 ms: 1.01x slower                                           |
| unpickle_list        | 3.11 us                                                                | 3.13 us: 1.01x slower                                          |
| unpickle_pure_python | 156 us                                                                 | 158 us: 1.01x slower                                           |
| xml_etree_process    | 39.1 ms                                                                | 39.5 ms: 1.01x slower                                          |
| Geometric mean       | (ref)                                                                  | 1.01x faster                                                   |

Benchmark hidden because not significant (3): xml_etree_iterparse, pickle_list, json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 8.84 ms                                                                | 8.64 ms: 1.02x faster                                          |
| python_startup         | 11.4 ms                                                                | 11.2 ms: 1.02x faster                                          |
| Geometric mean         | (ref)                                                                  | 1.02x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.30 ms                                                                | 7.55 ms: 1.03x slower                                          |

All benchmarks:
===============

| Benchmark               | bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads             | 1.54 sec                                                               | 1.34 sec: 1.15x faster                                         |
| richards                | 33.0 ms                                                                | 31.2 ms: 1.06x faster                                          |
| richards_super          | 36.4 ms                                                                | 34.7 ms: 1.05x faster                                          |
| python_startup_no_site  | 8.84 ms                                                                | 8.64 ms: 1.02x faster                                          |
| pyflate                 | 334 ms                                                                 | 328 ms: 1.02x faster                                           |
| python_startup          | 11.4 ms                                                                | 11.2 ms: 1.02x faster                                          |
| pickle_pure_python      | 195 us                                                                 | 193 us: 1.01x faster                                           |
| pickle_dict             | 18.1 us                                                                | 17.9 us: 1.01x faster                                          |
| logging_simple          | 3.52 us                                                                | 3.50 us: 1.01x faster                                          |
| create_gc_cycles        | 704 us                                                                 | 701 us: 1.00x faster                                           |
| logging_format          | 3.81 us                                                                | 3.79 us: 1.00x faster                                          |
| coroutines              | 17.6 ms                                                                | 17.6 ms: 1.00x faster                                          |
| regex_effbot            | 2.57 ms                                                                | 2.56 ms: 1.00x faster                                          |
| gc_traversal            | 2.41 ms                                                                | 2.40 ms: 1.00x faster                                          |
| pidigits                | 283 ms                                                                 | 283 ms: 1.00x faster                                           |
| json_dumps              | 6.44 ms                                                                | 6.45 ms: 1.00x slower                                          |
| regex_v8                | 16.8 ms                                                                | 16.9 ms: 1.00x slower                                          |
| sqlite_synth            | 1.63 us                                                                | 1.63 us: 1.00x slower                                          |
| async_tree_io           | 699 ms                                                                 | 701 ms: 1.00x slower                                           |
| pickle                  | 7.38 us                                                                | 7.42 us: 1.00x slower                                          |
| unpickle                | 9.12 us                                                                | 9.16 us: 1.00x slower                                          |
| dulwich_log             | 30.4 ms                                                                | 30.5 ms: 1.00x slower                                          |
| sqlglot_parse           | 792 us                                                                 | 796 us: 1.01x slower                                           |
| scimark_sor             | 104 ms                                                                 | 104 ms: 1.01x slower                                           |
| xml_etree_generate      | 57.3 ms                                                                | 57.7 ms: 1.01x slower                                          |
| pycparser               | 688 ms                                                                 | 693 ms: 1.01x slower                                           |
| xml_etree_parse         | 110 ms                                                                 | 111 ms: 1.01x slower                                           |
| unpickle_list           | 3.11 us                                                                | 3.13 us: 1.01x slower                                          |
| sqlglot_transpile       | 967 us                                                                 | 975 us: 1.01x slower                                           |
| unpickle_pure_python    | 156 us                                                                 | 158 us: 1.01x slower                                           |
| xml_etree_process       | 39.1 ms                                                                | 39.5 ms: 1.01x slower                                          |
| deepcopy_reduce         | 1.96 us                                                                | 1.99 us: 1.01x slower                                          |
| logging_silent          | 67.4 ns                                                                | 68.2 ns: 1.01x slower                                          |
| sqlglot_optimize        | 34.0 ms                                                                | 34.3 ms: 1.01x slower                                          |
| unpack_sequence         | 26.2 ns                                                                | 26.4 ns: 1.01x slower                                          |
| sqlglot_normalize       | 182 ms                                                                 | 184 ms: 1.01x slower                                           |
| docutils                | 1.50 sec                                                               | 1.52 sec: 1.01x slower                                         |
| deepcopy                | 221 us                                                                 | 224 us: 1.01x slower                                           |
| go                      | 103 ms                                                                 | 105 ms: 1.01x slower                                           |
| scimark_sparse_mat_mult | 3.05 ms                                                                | 3.11 ms: 1.02x slower                                          |
| spectral_norm           | 70.6 ms                                                                | 72.0 ms: 1.02x slower                                          |
| bench_mp_pool           | 44.3 ms                                                                | 45.2 ms: 1.02x slower                                          |
| bench_thread_pool       | 477 us                                                                 | 489 us: 1.02x slower                                           |
| float                   | 54.7 ms                                                                | 56.0 ms: 1.02x slower                                          |
| telco                   | 4.64 ms                                                                | 4.76 ms: 1.03x slower                                          |
| generators              | 24.1 ms                                                                | 24.7 ms: 1.03x slower                                          |
| mdp                     | 1.60 sec                                                               | 1.65 sec: 1.03x slower                                         |
| async_generators        | 299 ms                                                                 | 309 ms: 1.03x slower                                           |
| scimark_lu              | 70.2 ms                                                                | 72.5 ms: 1.03x slower                                          |
| mako                    | 7.30 ms                                                                | 7.55 ms: 1.03x slower                                          |
| scimark_monte_carlo     | 44.6 ms                                                                | 46.3 ms: 1.04x slower                                          |
| raytrace                | 172 ms                                                                 | 179 ms: 1.04x slower                                           |
| deltablue               | 2.34 ms                                                                | 2.43 ms: 1.04x slower                                          |
| meteor_contest          | 73.9 ms                                                                | 76.8 ms: 1.04x slower                                          |
| crypto_pyaes            | 46.8 ms                                                                | 48.7 ms: 1.04x slower                                          |
| chaos                   | 40.0 ms                                                                | 41.7 ms: 1.04x slower                                          |
| deepcopy_memo           | 23.8 us                                                                | 25.1 us: 1.05x slower                                          |
| nbody                   | 71.1 ms                                                                | 75.6 ms: 1.06x slower                                          |
| scimark_fft             | 196 ms                                                                 | 210 ms: 1.07x slower                                           |
| hexiom                  | 4.59 ms                                                                | 4.94 ms: 1.08x slower                                          |
| nqueens                 | 57.5 ms                                                                | 62.7 ms: 1.09x slower                                          |
| comprehensions          | 14.6 us                                                                | 16.3 us: 1.12x slower                                          |
| Geometric mean          | (ref)                                                                  | 1.01x slower                                                   |

Benchmark hidden because not significant (16): asyncio_tcp, pathlib, json, xml_etree_iterparse, pickle_list, regex_dna, fannkuch, typing_runtime_protocols, coverage, json_loads, async_tree_cpu_io_mixed, async_tree_memoization, async_tree_none, asyncio_tcp_ssl, tornado_http, mypy2
Ignored benchmarks (3) of results/bm-20231016-3.13.0a1+-f07ca27/bm-20231016-darwin-arm64-python-f07ca27709855d4637b4-3.13.0a1+-f07ca27.json: pprint_pformat, pprint_safe_repr, regex_compile


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
