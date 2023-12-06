
# Results vs. base

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.02x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 178 ms                                                                 | 183 ms: 1.03x slower                                           |
| chameleon      | 4.85 ms                                                                | 4.92 ms: 1.01x slower                                          |
| docutils       | 1.52 sec                                                               | 1.55 sec: 1.02x slower                                         |
| tornado_http   | 71.0 ms                                                                | 76.3 ms: 1.08x slower                                          |
| Geometric mean | (ref)                                                                  | 1.03x slower                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark        | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_io_tg | 714 ms                                                                 | 700 ms: 1.02x faster                                           |
| Geometric mean   | (ref)                                                                  | 1.00x faster                                                   |

Benchmark hidden because not significant (7): async_tree_none, async_tree_none_tg, async_tree_memoization, async_tree_cpu_io_mixed_tg, async_tree_io, async_tree_memoization_tg, async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| nbody          | 79.6 ms                                                                | 83.5 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (2): pidigits, float

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_v8       | 17.0 ms                                                                | 17.0 ms: 1.00x slower                                          |
| regex_effbot   | 2.56 ms                                                                | 2.58 ms: 1.00x slower                                          |
| regex_dna      | 149 ms                                                                 | 150 ms: 1.01x slower                                           |
| regex_compile  | 78.7 ms                                                                | 83.2 ms: 1.06x slower                                          |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| tomli_loads          | 1.60 sec                                                               | 1.53 sec: 1.04x faster                                         |
| pickle_list          | 2.96 us                                                                | 2.89 us: 1.02x faster                                          |
| pickle_dict          | 18.0 us                                                                | 18.1 us: 1.00x slower                                          |
| pickle               | 7.44 us                                                                | 7.51 us: 1.01x slower                                          |
| json_dumps           | 6.60 ms                                                                | 6.69 ms: 1.01x slower                                          |
| pickle_pure_python   | 202 us                                                                 | 206 us: 1.02x slower                                           |
| unpickle             | 9.09 us                                                                | 9.35 us: 1.03x slower                                          |
| xml_etree_generate   | 59.3 ms                                                                | 62.5 ms: 1.05x slower                                          |
| unpickle_list        | 3.12 us                                                                | 3.37 us: 1.08x slower                                          |
| xml_etree_process    | 41.0 ms                                                                | 44.5 ms: 1.08x slower                                          |
| unpickle_pure_python | 162 us                                                                 | 179 us: 1.10x slower                                           |
| xml_etree_iterparse  | 77.6 ms                                                                | 88.5 ms: 1.14x slower                                          |
| xml_etree_parse      | 108 ms                                                                 | 140 ms: 1.30x slower                                           |
| Geometric mean       | (ref)                                                                  | 1.05x slower                                                   |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup_no_site | 10.6 ms                                                                | 10.4 ms: 1.02x faster                                          |
| python_startup         | 12.0 ms                                                                | 11.9 ms: 1.01x faster                                          |
| Geometric mean         | (ref)                                                                  | 1.01x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 7.81 ms                                                                | 7.96 ms: 1.02x slower                                          |

All benchmarks:
===============

| Benchmark               | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------:|
| richards                | 35.1 ms                                                                | 33.6 ms: 1.05x faster                                          |
| tomli_loads             | 1.60 sec                                                               | 1.53 sec: 1.04x faster                                         |
| richards_super          | 38.5 ms                                                                | 37.1 ms: 1.04x faster                                          |
| create_gc_cycles        | 729 us                                                                 | 708 us: 1.03x faster                                           |
| pickle_list             | 2.96 us                                                                | 2.89 us: 1.02x faster                                          |
| async_tree_io_tg        | 714 ms                                                                 | 700 ms: 1.02x faster                                           |
| logging_simple          | 3.68 us                                                                | 3.61 us: 1.02x faster                                          |
| coroutines              | 19.1 ms                                                                | 18.8 ms: 1.02x faster                                          |
| python_startup_no_site  | 10.6 ms                                                                | 10.4 ms: 1.02x faster                                          |
| logging_format          | 3.95 us                                                                | 3.91 us: 1.01x faster                                          |
| python_startup          | 12.0 ms                                                                | 11.9 ms: 1.01x faster                                          |
| sympy_expand            | 257 ms                                                                 | 255 ms: 1.01x faster                                           |
| regex_v8                | 17.0 ms                                                                | 17.0 ms: 1.00x slower                                          |
| raytrace                | 192 ms                                                                 | 193 ms: 1.00x slower                                           |
| asyncio_websockets      | 547 ms                                                                 | 550 ms: 1.00x slower                                           |
| regex_effbot            | 2.56 ms                                                                | 2.58 ms: 1.00x slower                                          |
| pickle_dict             | 18.0 us                                                                | 18.1 us: 1.00x slower                                          |
| pyflate                 | 350 ms                                                                 | 352 ms: 1.00x slower                                           |
| spectral_norm           | 75.1 ms                                                                | 75.5 ms: 1.00x slower                                          |
| sqlglot_optimize        | 35.7 ms                                                                | 35.9 ms: 1.01x slower                                          |
| sqlglot_parse           | 853 us                                                                 | 858 us: 1.01x slower                                           |
| sqlite_synth            | 1.63 us                                                                | 1.64 us: 1.01x slower                                          |
| pickle                  | 7.44 us                                                                | 7.51 us: 1.01x slower                                          |
| regex_dna               | 149 ms                                                                 | 150 ms: 1.01x slower                                           |
| json                    | 3.05 ms                                                                | 3.09 ms: 1.01x slower                                          |
| dulwich_log             | 30.9 ms                                                                | 31.3 ms: 1.01x slower                                          |
| chameleon               | 4.85 ms                                                                | 4.92 ms: 1.01x slower                                          |
| coverage                | 48.1 ms                                                                | 48.7 ms: 1.01x slower                                          |
| bench_mp_pool           | 44.7 ms                                                                | 45.3 ms: 1.01x slower                                          |
| json_dumps              | 6.60 ms                                                                | 6.69 ms: 1.01x slower                                          |
| pickle_pure_python      | 202 us                                                                 | 206 us: 1.02x slower                                           |
| pathlib                 | 28.7 ms                                                                | 29.3 ms: 1.02x slower                                          |
| mako                    | 7.81 ms                                                                | 7.96 ms: 1.02x slower                                          |
| sympy_sum               | 76.0 ms                                                                | 77.5 ms: 1.02x slower                                          |
| sympy_str               | 147 ms                                                                 | 150 ms: 1.02x slower                                           |
| docutils                | 1.52 sec                                                               | 1.55 sec: 1.02x slower                                         |
| chaos                   | 44.3 ms                                                                | 45.2 ms: 1.02x slower                                          |
| deepcopy                | 229 us                                                                 | 234 us: 1.02x slower                                           |
| generators              | 25.7 ms                                                                | 26.3 ms: 1.02x slower                                          |
| mdp                     | 1.68 sec                                                               | 1.72 sec: 1.02x slower                                         |
| unpack_sequence         | 28.3 ns                                                                | 29.1 ns: 1.03x slower                                          |
| crypto_pyaes            | 49.3 ms                                                                | 50.6 ms: 1.03x slower                                          |
| unpickle                | 9.09 us                                                                | 9.35 us: 1.03x slower                                          |
| 2to3                    | 178 ms                                                                 | 183 ms: 1.03x slower                                           |
| scimark_lu              | 75.3 ms                                                                | 77.4 ms: 1.03x slower                                          |
| pprint_safe_repr        | 527 ms                                                                 | 542 ms: 1.03x slower                                           |
| telco                   | 4.63 ms                                                                | 4.79 ms: 1.03x slower                                          |
| scimark_monte_carlo     | 48.8 ms                                                                | 50.5 ms: 1.04x slower                                          |
| pprint_pformat          | 1.06 sec                                                               | 1.10 sec: 1.04x slower                                         |
| sympy_integrate         | 11.4 ms                                                                | 11.8 ms: 1.04x slower                                          |
| async_generators        | 308 ms                                                                 | 321 ms: 1.04x slower                                           |
| deepcopy_memo           | 25.2 us                                                                | 26.3 us: 1.04x slower                                          |
| scimark_sparse_mat_mult | 3.18 ms                                                                | 3.33 ms: 1.05x slower                                          |
| scimark_fft             | 210 ms                                                                 | 220 ms: 1.05x slower                                           |
| nbody                   | 79.6 ms                                                                | 83.5 ms: 1.05x slower                                          |
| deltablue               | 2.49 ms                                                                | 2.62 ms: 1.05x slower                                          |
| meteor_contest          | 75.1 ms                                                                | 79.0 ms: 1.05x slower                                          |
| xml_etree_generate      | 59.3 ms                                                                | 62.5 ms: 1.05x slower                                          |
| regex_compile           | 78.7 ms                                                                | 83.2 ms: 1.06x slower                                          |
| fannkuch                | 294 ms                                                                 | 311 ms: 1.06x slower                                           |
| tornado_http            | 71.0 ms                                                                | 76.3 ms: 1.08x slower                                          |
| go                      | 107 ms                                                                 | 115 ms: 1.08x slower                                           |
| unpickle_list           | 3.12 us                                                                | 3.37 us: 1.08x slower                                          |
| xml_etree_process       | 41.0 ms                                                                | 44.5 ms: 1.08x slower                                          |
| nqueens                 | 60.1 ms                                                                | 65.6 ms: 1.09x slower                                          |
| unpickle_pure_python    | 162 us                                                                 | 179 us: 1.10x slower                                           |
| comprehensions          | 12.6 us                                                                | 14.0 us: 1.11x slower                                          |
| xml_etree_iterparse     | 77.6 ms                                                                | 88.5 ms: 1.14x slower                                          |
| hexiom                  | 4.99 ms                                                                | 5.89 ms: 1.18x slower                                          |
| xml_etree_parse         | 108 ms                                                                 | 140 ms: 1.30x slower                                           |
| Geometric mean          | (ref)                                                                  | 1.02x slower                                                   |

Benchmark hidden because not significant (23): asyncio_tcp_ssl, gc_traversal, deepcopy_reduce, bench_thread_pool, async_tree_none, sqlglot_normalize, logging_silent, async_tree_none_tg, sqlglot_transpile, pidigits, float, async_tree_memoization, async_tree_cpu_io_mixed_tg, scimark_sor, pycparser, async_tree_io, async_tree_memoization_tg, json_loads, typing_runtime_protocols, async_tree_cpu_io_mixed, dask, mypy2, asyncio_tcp


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
