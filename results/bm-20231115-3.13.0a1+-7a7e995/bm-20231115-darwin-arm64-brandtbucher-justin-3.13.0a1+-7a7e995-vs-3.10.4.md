
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7a7e995
- commit date: 2023-11-15
- overall geometric mean: 1.12x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.06x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 183 ms: 1.03x faster                                           |
| chameleon      | 5.95 ms                                                | 4.92 ms: 1.21x faster                                          |
| docutils       | 1.73 sec                                               | 1.55 sec: 1.11x faster                                         |
| tornado_http   | 89.9 ms                                                | 76.3 ms: 1.18x faster                                          |
| Geometric mean | (ref)                                                  | 1.13x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 261 ms: 1.47x faster                                           |
| async_tree_memoization  | 473 ms                                                 | 338 ms: 1.40x faster                                           |
| async_tree_io           | 984 ms                                                 | 729 ms: 1.35x faster                                           |
| async_tree_cpu_io_mixed | 646 ms                                                 | 539 ms: 1.20x faster                                           |
| Geometric mean          | (ref)                                                  | 1.35x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 66.8 ms                                                | 60.0 ms: 1.11x faster                                          |
| nbody          | 88.1 ms                                                | 83.5 ms: 1.05x faster                                          |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                           |
| Geometric mean | (ref)                                                  | 1.05x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 174 ms                                                 | 150 ms: 1.16x faster                                           |
| regex_compile  | 92.3 ms                                                | 83.2 ms: 1.11x faster                                          |
| regex_v8       | 17.2 ms                                                | 17.0 ms: 1.01x faster                                          |
| regex_effbot   | 2.46 ms                                                | 2.58 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 206 us: 1.32x faster                                           |
| json_dumps           | 8.00 ms                                                | 6.69 ms: 1.20x faster                                          |
| tomli_loads          | 1.65 sec                                               | 1.53 sec: 1.08x faster                                         |
| unpickle_pure_python | 191 us                                                 | 179 us: 1.07x faster                                           |
| xml_etree_process    | 45.6 ms                                                | 44.5 ms: 1.03x faster                                          |
| unpickle             | 8.86 us                                                | 9.35 us: 1.05x slower                                          |
| pickle_list          | 2.72 us                                                | 2.89 us: 1.06x slower                                          |
| pickle_dict          | 17.0 us                                                | 18.1 us: 1.06x slower                                          |
| json_loads           | 16.7 us                                                | 17.9 us: 1.07x slower                                          |
| pickle               | 7.04 us                                                | 7.51 us: 1.07x slower                                          |
| xml_etree_generate   | 53.2 ms                                                | 62.5 ms: 1.17x slower                                          |
| unpickle_list        | 2.79 us                                                | 3.37 us: 1.21x slower                                          |
| xml_etree_iterparse  | 72.7 ms                                                | 88.5 ms: 1.22x slower                                          |
| xml_etree_parse      | 111 ms                                                 | 140 ms: 1.26x slower                                           |
| Geometric mean       | (ref)                                                  | 1.03x slower                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 11.9 ms: 1.01x slower                                          |
| python_startup_no_site | 8.64 ms                                                | 10.4 ms: 1.21x slower                                          |
| Geometric mean         | (ref)                                                  | 1.11x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.96 ms: 1.24x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 78.3 us: 4.30x faster                                          |
| deltablue                | 4.94 ms                                                | 2.62 ms: 1.89x faster                                          |
| richards_super           | 57.1 ms                                                | 37.1 ms: 1.54x faster                                          |
| logging_silent           | 115 ns                                                 | 74.9 ns: 1.53x faster                                          |
| raytrace                 | 293 ms                                                 | 193 ms: 1.52x faster                                           |
| asyncio_tcp              | 667 ms                                                 | 444 ms: 1.50x faster                                           |
| async_tree_none          | 384 ms                                                 | 261 ms: 1.47x faster                                           |
| richards                 | 47.6 ms                                                | 33.6 ms: 1.42x faster                                          |
| chaos                    | 64.1 ms                                                | 45.2 ms: 1.42x faster                                          |
| sqlglot_parse            | 1.20 ms                                                | 858 us: 1.40x faster                                           |
| crypto_pyaes             | 70.8 ms                                                | 50.6 ms: 1.40x faster                                          |
| async_tree_memoization   | 473 ms                                                 | 338 ms: 1.40x faster                                           |
| async_tree_io            | 984 ms                                                 | 729 ms: 1.35x faster                                           |
| sqlglot_transpile        | 1.40 ms                                                | 1.04 ms: 1.35x faster                                          |
| pickle_pure_python       | 272 us                                                 | 206 us: 1.32x faster                                           |
| scimark_lu               | 102 ms                                                 | 77.4 ms: 1.31x faster                                          |
| go                       | 148 ms                                                 | 115 ms: 1.28x faster                                           |
| unpack_sequence          | 36.7 ns                                                | 29.1 ns: 1.26x faster                                          |
| deepcopy_memo            | 33.1 us                                                | 26.3 us: 1.26x faster                                          |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.26x faster                                         |
| scimark_monte_carlo      | 62.8 ms                                                | 50.5 ms: 1.24x faster                                          |
| scimark_sor              | 134 ms                                                 | 108 ms: 1.24x faster                                           |
| generators               | 32.6 ms                                                | 26.3 ms: 1.24x faster                                          |
| mako                     | 9.86 ms                                                | 7.96 ms: 1.24x faster                                          |
| create_gc_cycles         | 865 us                                                 | 708 us: 1.22x faster                                           |
| spectral_norm            | 92.1 ms                                                | 75.5 ms: 1.22x faster                                          |
| pycparser                | 878 ms                                                 | 719 ms: 1.22x faster                                           |
| chameleon                | 5.95 ms                                                | 4.92 ms: 1.21x faster                                          |
| comprehensions           | 16.8 us                                                | 14.0 us: 1.20x faster                                          |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 539 ms: 1.20x faster                                           |
| json_dumps               | 8.00 ms                                                | 6.69 ms: 1.20x faster                                          |
| sympy_sum                | 92.4 ms                                                | 77.5 ms: 1.19x faster                                          |
| pyflate                  | 419 ms                                                 | 352 ms: 1.19x faster                                           |
| logging_format           | 4.62 us                                                | 3.91 us: 1.18x faster                                          |
| tornado_http             | 89.9 ms                                                | 76.3 ms: 1.18x faster                                          |
| logging_simple           | 4.25 us                                                | 3.61 us: 1.18x faster                                          |
| pprint_safe_repr         | 628 ms                                                 | 542 ms: 1.16x faster                                           |
| regex_dna                | 174 ms                                                 | 150 ms: 1.16x faster                                           |
| pprint_pformat           | 1.27 sec                                               | 1.10 sec: 1.15x faster                                         |
| deepcopy                 | 269 us                                                 | 234 us: 1.15x faster                                           |
| dulwich_log              | 35.6 ms                                                | 31.3 ms: 1.14x faster                                          |
| sympy_integrate          | 13.2 ms                                                | 11.8 ms: 1.12x faster                                          |
| deepcopy_reduce          | 2.28 us                                                | 2.04 us: 1.12x faster                                          |
| docutils                 | 1.73 sec                                               | 1.55 sec: 1.11x faster                                         |
| float                    | 66.8 ms                                                | 60.0 ms: 1.11x faster                                          |
| regex_compile            | 92.3 ms                                                | 83.2 ms: 1.11x faster                                          |
| sympy_str                | 164 ms                                                 | 150 ms: 1.10x faster                                           |
| mdp                      | 1.87 sec                                               | 1.72 sec: 1.09x faster                                         |
| dask                     | 254 ms                                                 | 235 ms: 1.08x faster                                           |
| tomli_loads              | 1.65 sec                                               | 1.53 sec: 1.08x faster                                         |
| unpickle_pure_python     | 191 us                                                 | 179 us: 1.07x faster                                           |
| nbody                    | 88.1 ms                                                | 83.5 ms: 1.05x faster                                          |
| sympy_expand             | 267 ms                                                 | 255 ms: 1.05x faster                                           |
| coroutines               | 19.6 ms                                                | 18.8 ms: 1.05x faster                                          |
| 2to3                     | 189 ms                                                 | 183 ms: 1.03x faster                                           |
| hexiom                   | 6.07 ms                                                | 5.89 ms: 1.03x faster                                          |
| xml_etree_process        | 45.6 ms                                                | 44.5 ms: 1.03x faster                                          |
| regex_v8                 | 17.2 ms                                                | 17.0 ms: 1.01x faster                                          |
| sqlglot_optimize         | 36.3 ms                                                | 35.9 ms: 1.01x faster                                          |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                           |
| bench_thread_pool        | 516 us                                                 | 519 us: 1.01x slower                                           |
| json                     | 3.06 ms                                                | 3.09 ms: 1.01x slower                                          |
| asyncio_websockets       | 544 ms                                                 | 550 ms: 1.01x slower                                           |
| python_startup           | 11.7 ms                                                | 11.9 ms: 1.01x slower                                          |
| meteor_contest           | 77.9 ms                                                | 79.0 ms: 1.01x slower                                          |
| scimark_fft              | 216 ms                                                 | 220 ms: 1.02x slower                                           |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.33 ms: 1.02x slower                                          |
| gc_traversal             | 2.37 ms                                                | 2.43 ms: 1.02x slower                                          |
| sqlglot_normalize        | 187 ms                                                 | 193 ms: 1.03x slower                                           |
| regex_effbot             | 2.46 ms                                                | 2.58 ms: 1.05x slower                                          |
| nqueens                  | 62.4 ms                                                | 65.6 ms: 1.05x slower                                          |
| unpickle                 | 8.86 us                                                | 9.35 us: 1.05x slower                                          |
| fannkuch                 | 294 ms                                                 | 311 ms: 1.06x slower                                           |
| pickle_list              | 2.72 us                                                | 2.89 us: 1.06x slower                                          |
| pickle_dict              | 17.0 us                                                | 18.1 us: 1.06x slower                                          |
| json_loads               | 16.7 us                                                | 17.9 us: 1.07x slower                                          |
| pickle                   | 7.04 us                                                | 7.51 us: 1.07x slower                                          |
| sqlite_synth             | 1.43 us                                                | 1.64 us: 1.15x slower                                          |
| bench_mp_pool            | 39.0 ms                                                | 45.3 ms: 1.16x slower                                          |
| xml_etree_generate       | 53.2 ms                                                | 62.5 ms: 1.17x slower                                          |
| coverage                 | 41.1 ms                                                | 48.7 ms: 1.19x slower                                          |
| python_startup_no_site   | 8.64 ms                                                | 10.4 ms: 1.21x slower                                          |
| unpickle_list            | 2.79 us                                                | 3.37 us: 1.21x slower                                          |
| xml_etree_iterparse      | 72.7 ms                                                | 88.5 ms: 1.22x slower                                          |
| xml_etree_parse          | 111 ms                                                 | 140 ms: 1.26x slower                                           |
| async_generators         | 233 ms                                                 | 321 ms: 1.38x slower                                           |
| telco                    | 3.42 ms                                                | 4.79 ms: 1.40x slower                                          |
| Geometric mean           | (ref)                                                  | 1.12x faster                                                   |

Benchmark hidden because not significant (2): mypy2, pathlib
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-7a7e995/bm-20231115-darwin-arm64-brandtbucher-justin-3.13.0a1+-7a7e995.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.06x
