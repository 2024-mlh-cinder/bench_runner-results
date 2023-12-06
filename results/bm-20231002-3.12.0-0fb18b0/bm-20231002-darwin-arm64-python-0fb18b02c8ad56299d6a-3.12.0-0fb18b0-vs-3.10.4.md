
# Results vs. 3.10.4

- fork: python
- ref: 0fb18b02c8ad56299d6a
- machine: darwin-arm64
- commit hash: 0fb18b0
- commit date: 2023-10-02
- overall geometric mean: 1.18x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| 2to3           | 189 ms                                                              | 170 ms: 1.11x faster                                                |
| chameleon      | 6.00 ms                                                             | 4.51 ms: 1.33x faster                                               |
| docutils       | 1.71 sec                                                            | 1.53 sec: 1.11x faster                                              |
| tornado_http   | 89.1 ms                                                             | 70.5 ms: 1.26x faster                                               |
| Geometric mean | (ref)                                                               | 1.20x faster                                                        |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|-------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| async_tree_memoization  | 466 ms                                                              | 306 ms: 1.52x faster                                                |
| async_tree_io           | 972 ms                                                              | 659 ms: 1.48x faster                                                |
| async_tree_none         | 381 ms                                                              | 258 ms: 1.47x faster                                                |
| async_tree_cpu_io_mixed | 640 ms                                                              | 520 ms: 1.23x faster                                                |
| Geometric mean          | (ref)                                                               | 1.42x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 88.4 ms                                                             | 68.8 ms: 1.29x faster                                               |
| float          | 66.8 ms                                                             | 58.0 ms: 1.15x faster                                               |
| pidigits       | 281 ms                                                              | 282 ms: 1.00x slower                                                |
| Geometric mean | (ref)                                                               | 1.14x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 92.8 ms                                                             | 75.8 ms: 1.22x faster                                               |
| regex_dna      | 173 ms                                                              | 152 ms: 1.14x faster                                                |
| regex_v8       | 17.2 ms                                                             | 15.6 ms: 1.10x faster                                               |
| regex_effbot   | 2.46 ms                                                             | 2.58 ms: 1.05x slower                                               |
| Geometric mean | (ref)                                                               | 1.10x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|----------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                              | 189 us: 1.44x faster                                                |
| unpickle_pure_python | 190 us                                                              | 144 us: 1.32x faster                                                |
| json_dumps           | 7.95 ms                                                             | 6.48 ms: 1.23x faster                                               |
| xml_etree_process    | 45.8 ms                                                             | 38.6 ms: 1.19x faster                                               |
| tomli_loads          | 1.66 sec                                                            | 1.40 sec: 1.19x faster                                              |
| xml_etree_parse      | 108 ms                                                              | 106 ms: 1.02x faster                                                |
| xml_etree_iterparse  | 71.9 ms                                                             | 74.2 ms: 1.03x slower                                               |
| unpickle             | 8.88 us                                                             | 9.26 us: 1.04x slower                                               |
| pickle               | 7.01 us                                                             | 7.35 us: 1.05x slower                                               |
| json_loads           | 16.3 us                                                             | 17.3 us: 1.06x slower                                               |
| xml_etree_generate   | 52.4 ms                                                             | 55.8 ms: 1.07x slower                                               |
| pickle_list          | 2.70 us                                                             | 2.89 us: 1.07x slower                                               |
| pickle_dict          | 16.9 us                                                             | 18.1 us: 1.07x slower                                               |
| unpickle_list        | 2.86 us                                                             | 3.20 us: 1.12x slower                                               |
| Geometric mean       | (ref)                                                               | 1.05x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 11.8 ms                                                             | 12.1 ms: 1.03x slower                                               |
| python_startup_no_site | 8.83 ms                                                             | 9.90 ms: 1.12x slower                                               |
| Geometric mean         | (ref)                                                               | 1.07x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|-----------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako            | 9.78 ms                                                             | 7.52 ms: 1.30x faster                                               |
| django_template | 25.5 ms                                                             | 21.8 ms: 1.17x faster                                               |
| Geometric mean  | (ref)                                                               | 1.23x faster                                                        |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120 | bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0 |
|--------------------------|:-------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 335 us                                                              | 90.6 us: 3.70x faster                                               |
| deltablue                | 4.93 ms                                                             | 2.59 ms: 1.90x faster                                               |
| logging_silent           | 114 ns                                                              | 67.8 ns: 1.69x faster                                               |
| richards_super           | 57.4 ms                                                             | 34.9 ms: 1.65x faster                                               |
| asyncio_tcp              | 682 ms                                                              | 419 ms: 1.63x faster                                                |
| richards                 | 47.7 ms                                                             | 31.0 ms: 1.54x faster                                               |
| async_tree_memoization   | 466 ms                                                              | 306 ms: 1.52x faster                                                |
| async_tree_io            | 972 ms                                                              | 659 ms: 1.48x faster                                                |
| async_tree_none          | 381 ms                                                              | 258 ms: 1.47x faster                                                |
| pickle_pure_python       | 272 us                                                              | 189 us: 1.44x faster                                                |
| chaos                    | 64.0 ms                                                             | 44.6 ms: 1.43x faster                                               |
| scimark_sor              | 134 ms                                                              | 93.8 ms: 1.43x faster                                               |
| scimark_lu               | 102 ms                                                              | 71.4 ms: 1.43x faster                                               |
| hexiom                   | 6.05 ms                                                             | 4.24 ms: 1.43x faster                                               |
| go                       | 148 ms                                                              | 106 ms: 1.39x faster                                                |
| crypto_pyaes             | 70.7 ms                                                             | 51.8 ms: 1.37x faster                                               |
| spectral_norm            | 101 ms                                                              | 74.6 ms: 1.36x faster                                               |
| unpack_sequence          | 38.7 ns                                                             | 28.7 ns: 1.35x faster                                               |
| deepcopy_memo            | 33.2 us                                                             | 24.6 us: 1.35x faster                                               |
| sqlglot_parse            | 1.20 ms                                                             | 895 us: 1.35x faster                                                |
| chameleon                | 6.00 ms                                                             | 4.51 ms: 1.33x faster                                               |
| unpickle_pure_python     | 190 us                                                              | 144 us: 1.32x faster                                                |
| sqlglot_transpile        | 1.40 ms                                                             | 1.07 ms: 1.31x faster                                               |
| mako                     | 9.78 ms                                                             | 7.52 ms: 1.30x faster                                               |
| pycparser                | 863 ms                                                              | 667 ms: 1.29x faster                                                |
| nbody                    | 88.4 ms                                                             | 68.8 ms: 1.29x faster                                               |
| pyflate                  | 420 ms                                                              | 328 ms: 1.28x faster                                                |
| asyncio_tcp_ssl          | 1.62 sec                                                            | 1.26 sec: 1.28x faster                                              |
| pprint_pformat           | 1.28 sec                                                            | 1.00 sec: 1.27x faster                                              |
| pprint_safe_repr         | 625 ms                                                              | 492 ms: 1.27x faster                                                |
| sqlalchemy_imperative    | 8.79 ms                                                             | 6.92 ms: 1.27x faster                                               |
| scimark_monte_carlo      | 63.2 ms                                                             | 50.0 ms: 1.26x faster                                               |
| tornado_http             | 89.1 ms                                                             | 70.5 ms: 1.26x faster                                               |
| create_gc_cycles         | 870 us                                                              | 702 us: 1.24x faster                                                |
| async_tree_cpu_io_mixed  | 640 ms                                                              | 520 ms: 1.23x faster                                                |
| json_dumps               | 7.95 ms                                                             | 6.48 ms: 1.23x faster                                               |
| regex_compile            | 92.8 ms                                                             | 75.8 ms: 1.22x faster                                               |
| deepcopy                 | 269 us                                                              | 224 us: 1.20x faster                                                |
| raytrace                 | 293 ms                                                              | 245 ms: 1.20x faster                                                |
| xml_etree_process        | 45.8 ms                                                             | 38.6 ms: 1.19x faster                                               |
| tomli_loads              | 1.66 sec                                                            | 1.40 sec: 1.19x faster                                              |
| dulwich_log              | 34.9 ms                                                             | 29.8 ms: 1.17x faster                                               |
| django_template          | 25.5 ms                                                             | 21.8 ms: 1.17x faster                                               |
| logging_format           | 4.59 us                                                             | 3.98 us: 1.15x faster                                               |
| sympy_sum                | 91.1 ms                                                             | 79.1 ms: 1.15x faster                                               |
| mypy2                    | 294 ms                                                              | 256 ms: 1.15x faster                                                |
| float                    | 66.8 ms                                                             | 58.0 ms: 1.15x faster                                               |
| logging_simple           | 4.25 us                                                             | 3.70 us: 1.15x faster                                               |
| regex_dna                | 173 ms                                                              | 152 ms: 1.14x faster                                                |
| sympy_integrate          | 12.9 ms                                                             | 11.3 ms: 1.14x faster                                               |
| fannkuch                 | 295 ms                                                              | 262 ms: 1.12x faster                                                |
| generators               | 32.1 ms                                                             | 28.6 ms: 1.12x faster                                               |
| mdp                      | 1.87 sec                                                            | 1.67 sec: 1.12x faster                                              |
| dask                     | 251 ms                                                              | 224 ms: 1.12x faster                                                |
| deepcopy_reduce          | 2.27 us                                                             | 2.03 us: 1.12x faster                                               |
| docutils                 | 1.71 sec                                                            | 1.53 sec: 1.11x faster                                              |
| 2to3                     | 189 ms                                                              | 170 ms: 1.11x faster                                                |
| sqlalchemy_declarative   | 72.4 ms                                                             | 65.4 ms: 1.11x faster                                               |
| regex_v8                 | 17.2 ms                                                             | 15.6 ms: 1.10x faster                                               |
| gunicorn                 | 1.34 ms                                                             | 1.22 ms: 1.10x faster                                               |
| scimark_fft              | 216 ms                                                              | 198 ms: 1.09x faster                                                |
| sympy_str                | 165 ms                                                              | 151 ms: 1.09x faster                                                |
| coverage                 | 41.0 ms                                                             | 37.8 ms: 1.08x faster                                               |
| coroutines               | 19.7 ms                                                             | 18.2 ms: 1.08x faster                                               |
| aiohttp                  | 1.27 ms                                                             | 1.18 ms: 1.08x faster                                               |
| sympy_expand             | 268 ms                                                              | 250 ms: 1.07x faster                                                |
| comprehensions           | 16.8 us                                                             | 15.7 us: 1.07x faster                                               |
| meteor_contest           | 77.6 ms                                                             | 72.9 ms: 1.06x faster                                               |
| bench_thread_pool        | 534 us                                                              | 503 us: 1.06x faster                                                |
| sqlglot_optimize         | 36.3 ms                                                             | 34.3 ms: 1.06x faster                                               |
| nqueens                  | 62.5 ms                                                             | 59.6 ms: 1.05x faster                                               |
| scimark_sparse_mat_mult  | 3.24 ms                                                             | 3.14 ms: 1.03x faster                                               |
| xml_etree_parse          | 108 ms                                                              | 106 ms: 1.02x faster                                                |
| sqlglot_normalize        | 187 ms                                                              | 186 ms: 1.00x faster                                                |
| asyncio_websockets       | 408 ms                                                              | 408 ms: 1.00x slower                                                |
| pidigits                 | 281 ms                                                              | 282 ms: 1.00x slower                                                |
| gc_traversal             | 2.38 ms                                                             | 2.40 ms: 1.01x slower                                               |
| pathlib                  | 24.0 ms                                                             | 24.4 ms: 1.01x slower                                               |
| json                     | 3.04 ms                                                             | 3.11 ms: 1.03x slower                                               |
| python_startup           | 11.8 ms                                                             | 12.1 ms: 1.03x slower                                               |
| xml_etree_iterparse      | 71.9 ms                                                             | 74.2 ms: 1.03x slower                                               |
| unpickle                 | 8.88 us                                                             | 9.26 us: 1.04x slower                                               |
| pickle                   | 7.01 us                                                             | 7.35 us: 1.05x slower                                               |
| regex_effbot             | 2.46 ms                                                             | 2.58 ms: 1.05x slower                                               |
| json_loads               | 16.3 us                                                             | 17.3 us: 1.06x slower                                               |
| xml_etree_generate       | 52.4 ms                                                             | 55.8 ms: 1.07x slower                                               |
| pickle_list              | 2.70 us                                                             | 2.89 us: 1.07x slower                                               |
| pickle_dict              | 16.9 us                                                             | 18.1 us: 1.07x slower                                               |
| sqlite_synth             | 1.45 us                                                             | 1.60 us: 1.11x slower                                               |
| telco                    | 3.41 ms                                                             | 3.79 ms: 1.11x slower                                               |
| unpickle_list            | 2.86 us                                                             | 3.20 us: 1.12x slower                                               |
| python_startup_no_site   | 8.83 ms                                                             | 9.90 ms: 1.12x slower                                               |
| bench_mp_pool            | 40.0 ms                                                             | 46.8 ms: 1.17x slower                                               |
| async_generators         | 230 ms                                                              | 306 ms: 1.33x slower                                                |
| Geometric mean           | (ref)                                                               | 1.18x faster                                                        |
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.13x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
