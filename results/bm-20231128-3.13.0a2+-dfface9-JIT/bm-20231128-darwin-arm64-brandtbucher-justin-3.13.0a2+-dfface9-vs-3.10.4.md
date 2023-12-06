
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: dfface9
- commit date: 2023-11-28
- overall geometric mean: 1.12x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.05x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 181 ms: 1.04x faster                                           |
| chameleon      | 6.00 ms                                                             | 5.15 ms: 1.17x faster                                          |
| docutils       | 1.71 sec                                                            | 1.52 sec: 1.12x faster                                         |
| tornado_http   | 89.1 ms                                                             | 73.7 ms: 1.21x faster                                          |
| Geometric mean | (ref)                                                               | 1.13x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 381 ms                                                              | 257 ms: 1.48x faster                                           |
| async_tree_memoization  | 466 ms                                                              | 332 ms: 1.40x faster                                           |
| async_tree_io           | 972 ms                                                              | 707 ms: 1.38x faster                                           |
| async_tree_cpu_io_mixed | 640 ms                                                              | 528 ms: 1.21x faster                                           |
| Geometric mean          | (ref)                                                               | 1.36x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 66.8 ms                                                             | 58.7 ms: 1.14x faster                                          |
| nbody          | 88.4 ms                                                             | 80.5 ms: 1.10x faster                                          |
| pidigits       | 281 ms                                                              | 283 ms: 1.01x slower                                           |
| Geometric mean | (ref)                                                               | 1.07x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 173 ms                                                              | 149 ms: 1.16x faster                                           |
| regex_compile  | 92.8 ms                                                             | 83.9 ms: 1.11x faster                                          |
| regex_v8       | 17.2 ms                                                             | 17.0 ms: 1.01x faster                                          |
| regex_effbot   | 2.46 ms                                                             | 2.57 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                               | 1.06x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|----------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 209 us: 1.30x faster                                           |
| json_dumps           | 7.95 ms                                                             | 6.57 ms: 1.21x faster                                          |
| unpickle_pure_python | 190 us                                                              | 171 us: 1.11x faster                                           |
| xml_etree_process    | 45.8 ms                                                             | 41.3 ms: 1.11x faster                                          |
| tomli_loads          | 1.66 sec                                                            | 1.53 sec: 1.08x faster                                         |
| unpickle             | 8.88 us                                                             | 9.11 us: 1.03x slower                                          |
| pickle               | 7.01 us                                                             | 7.39 us: 1.06x slower                                          |
| json_loads           | 16.3 us                                                             | 17.3 us: 1.06x slower                                          |
| pickle_dict          | 16.9 us                                                             | 18.0 us: 1.07x slower                                          |
| xml_etree_iterparse  | 71.9 ms                                                             | 76.8 ms: 1.07x slower                                          |
| pickle_list          | 2.70 us                                                             | 2.89 us: 1.07x slower                                          |
| unpickle_list        | 2.86 us                                                             | 3.12 us: 1.09x slower                                          |
| xml_etree_generate   | 52.4 ms                                                             | 59.2 ms: 1.13x slower                                          |
| Geometric mean       | (ref)                                                               | 1.01x faster                                                   |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 12.3 ms: 1.05x slower                                          |
| python_startup_no_site | 8.83 ms                                                             | 10.8 ms: 1.22x slower                                          |
| Geometric mean         | (ref)                                                               | 1.13x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|-----------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 9.78 ms                                                             | 7.96 ms: 1.23x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9 |
|--------------------------|:-------------------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 335 us                                                              | 79.1 us: 4.24x faster                                          |
| deltablue                | 4.93 ms                                                             | 2.57 ms: 1.92x faster                                          |
| asyncio_tcp              | 682 ms                                                              | 427 ms: 1.60x faster                                           |
| logging_silent           | 114 ns                                                              | 71.9 ns: 1.59x faster                                          |
| raytrace                 | 293 ms                                                              | 189 ms: 1.55x faster                                           |
| richards_super           | 57.4 ms                                                             | 37.3 ms: 1.54x faster                                          |
| async_tree_none          | 381 ms                                                              | 257 ms: 1.48x faster                                           |
| richards                 | 47.7 ms                                                             | 33.4 ms: 1.43x faster                                          |
| chaos                    | 64.0 ms                                                             | 44.9 ms: 1.42x faster                                          |
| sqlglot_parse            | 1.20 ms                                                             | 849 us: 1.42x faster                                           |
| crypto_pyaes             | 70.7 ms                                                             | 50.3 ms: 1.41x faster                                          |
| async_tree_memoization   | 466 ms                                                              | 332 ms: 1.40x faster                                           |
| async_tree_io            | 972 ms                                                              | 707 ms: 1.38x faster                                           |
| sqlglot_transpile        | 1.40 ms                                                             | 1.04 ms: 1.35x faster                                          |
| unpack_sequence          | 38.7 ns                                                             | 29.0 ns: 1.34x faster                                          |
| pickle_pure_python       | 272 us                                                              | 209 us: 1.30x faster                                           |
| go                       | 148 ms                                                              | 114 ms: 1.30x faster                                           |
| scimark_lu               | 102 ms                                                              | 78.6 ms: 1.30x faster                                          |
| scimark_monte_carlo      | 63.2 ms                                                             | 50.8 ms: 1.24x faster                                          |
| create_gc_cycles         | 870 us                                                              | 701 us: 1.24x faster                                           |
| scimark_sor              | 134 ms                                                              | 108 ms: 1.24x faster                                           |
| deepcopy_memo            | 33.2 us                                                             | 26.9 us: 1.23x faster                                          |
| spectral_norm            | 101 ms                                                              | 82.1 ms: 1.23x faster                                          |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.31 sec: 1.23x faster                                         |
| generators               | 32.1 ms                                                             | 26.0 ms: 1.23x faster                                          |
| mako                     | 9.78 ms                                                             | 7.96 ms: 1.23x faster                                          |
| comprehensions           | 16.8 us                                                             | 13.8 us: 1.22x faster                                          |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 528 ms: 1.21x faster                                           |
| json_dumps               | 7.95 ms                                                             | 6.57 ms: 1.21x faster                                          |
| tornado_http             | 89.1 ms                                                             | 73.7 ms: 1.21x faster                                          |
| pyflate                  | 420 ms                                                              | 349 ms: 1.20x faster                                           |
| pycparser                | 863 ms                                                              | 719 ms: 1.20x faster                                           |
| logging_format           | 4.59 us                                                             | 3.92 us: 1.17x faster                                          |
| logging_simple           | 4.25 us                                                             | 3.64 us: 1.17x faster                                          |
| chameleon                | 6.00 ms                                                             | 5.15 ms: 1.17x faster                                          |
| regex_dna                | 173 ms                                                              | 149 ms: 1.16x faster                                           |
| pprint_safe_repr         | 625 ms                                                              | 542 ms: 1.15x faster                                           |
| pprint_pformat           | 1.28 sec                                                            | 1.11 sec: 1.15x faster                                         |
| dulwich_log              | 34.9 ms                                                             | 30.5 ms: 1.15x faster                                          |
| float                    | 66.8 ms                                                             | 58.7 ms: 1.14x faster                                          |
| deepcopy                 | 269 us                                                              | 238 us: 1.13x faster                                           |
| sympy_sum                | 91.1 ms                                                             | 81.0 ms: 1.12x faster                                          |
| docutils                 | 1.71 sec                                                            | 1.52 sec: 1.12x faster                                         |
| unpickle_pure_python     | 190 us                                                              | 171 us: 1.11x faster                                           |
| xml_etree_process        | 45.8 ms                                                             | 41.3 ms: 1.11x faster                                          |
| regex_compile            | 92.8 ms                                                             | 83.9 ms: 1.11x faster                                          |
| nbody                    | 88.4 ms                                                             | 80.5 ms: 1.10x faster                                          |
| mdp                      | 1.87 sec                                                            | 1.72 sec: 1.09x faster                                         |
| dask                     | 251 ms                                                              | 231 ms: 1.08x faster                                           |
| tomli_loads              | 1.66 sec                                                            | 1.53 sec: 1.08x faster                                         |
| sympy_integrate          | 12.9 ms                                                             | 12.0 ms: 1.08x faster                                          |
| deepcopy_reduce          | 2.27 us                                                             | 2.12 us: 1.07x faster                                          |
| sympy_str                | 165 ms                                                              | 154 ms: 1.07x faster                                           |
| hexiom                   | 6.05 ms                                                             | 5.82 ms: 1.04x faster                                          |
| 2to3                     | 189 ms                                                              | 181 ms: 1.04x faster                                           |
| sympy_expand             | 268 ms                                                              | 260 ms: 1.03x faster                                           |
| coroutines               | 19.7 ms                                                             | 19.3 ms: 1.02x faster                                          |
| regex_v8                 | 17.2 ms                                                             | 17.0 ms: 1.01x faster                                          |
| bench_thread_pool        | 534 us                                                              | 531 us: 1.01x faster                                           |
| asyncio_websockets       | 408 ms                                                              | 409 ms: 1.00x slower                                           |
| pidigits                 | 281 ms                                                              | 283 ms: 1.01x slower                                           |
| gc_traversal             | 2.38 ms                                                             | 2.40 ms: 1.01x slower                                          |
| meteor_contest           | 77.6 ms                                                             | 78.5 ms: 1.01x slower                                          |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 3.31 ms: 1.02x slower                                          |
| fannkuch                 | 295 ms                                                              | 301 ms: 1.02x slower                                           |
| sqlglot_optimize         | 36.3 ms                                                             | 37.1 ms: 1.02x slower                                          |
| scimark_fft              | 216 ms                                                              | 222 ms: 1.02x slower                                           |
| unpickle                 | 8.88 us                                                             | 9.11 us: 1.03x slower                                          |
| pathlib                  | 24.0 ms                                                             | 24.9 ms: 1.04x slower                                          |
| regex_effbot             | 2.46 ms                                                             | 2.57 ms: 1.05x slower                                          |
| python_startup           | 11.8 ms                                                             | 12.3 ms: 1.05x slower                                          |
| nqueens                  | 62.5 ms                                                             | 65.7 ms: 1.05x slower                                          |
| sqlglot_normalize        | 187 ms                                                              | 197 ms: 1.05x slower                                           |
| pickle                   | 7.01 us                                                             | 7.39 us: 1.06x slower                                          |
| json_loads               | 16.3 us                                                             | 17.3 us: 1.06x slower                                          |
| pickle_dict              | 16.9 us                                                             | 18.0 us: 1.07x slower                                          |
| xml_etree_iterparse      | 71.9 ms                                                             | 76.8 ms: 1.07x slower                                          |
| pickle_list              | 2.70 us                                                             | 2.89 us: 1.07x slower                                          |
| unpickle_list            | 2.86 us                                                             | 3.12 us: 1.09x slower                                          |
| xml_etree_generate       | 52.4 ms                                                             | 59.2 ms: 1.13x slower                                          |
| sqlite_synth             | 1.45 us                                                             | 1.66 us: 1.15x slower                                          |
| bench_mp_pool            | 40.0 ms                                                             | 46.3 ms: 1.16x slower                                          |
| coverage                 | 41.0 ms                                                             | 48.5 ms: 1.18x slower                                          |
| python_startup_no_site   | 8.83 ms                                                             | 10.8 ms: 1.22x slower                                          |
| telco                    | 3.41 ms                                                             | 4.64 ms: 1.36x slower                                          |
| async_generators         | 230 ms                                                              | 321 ms: 1.39x slower                                           |
| mypy2                    | 294 ms                                                              | 541 ms: 1.84x slower                                           |
| Geometric mean           | (ref)                                                               | 1.12x faster                                                   |

Benchmark hidden because not significant (2): xml_etree_parse, json
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231128-3.13.0a2+-dfface9-JIT/bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2+-dfface9.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.08x
- 95% likely to have a speedup of 1.08x
- 99% likely to have a speedup of 1.05x
