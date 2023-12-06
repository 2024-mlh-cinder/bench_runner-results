
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7eaec09
- commit date: 2023-10-17
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.52 sec: 1.18x faster                                         |
| tornado_http   | 91.9 ms                                                | 70.2 ms: 1.31x faster                                          |
| Geometric mean | (ref)                                                  | 1.24x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 72.3 ms                                                | 56.0 ms: 1.29x faster                                          |
| nbody          | 94.1 ms                                                | 75.6 ms: 1.25x faster                                          |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                           |
| Geometric mean | (ref)                                                  | 1.17x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 160 ms                                                 | 149 ms: 1.07x faster                                           |
| regex_v8       | 17.5 ms                                                | 16.9 ms: 1.04x faster                                          |
| regex_effbot   | 2.45 ms                                                | 2.56 ms: 1.05x slower                                          |
| Geometric mean | (ref)                                                  | 1.02x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 193 us: 1.47x faster                                           |
| tomli_loads          | 1.76 sec                                               | 1.34 sec: 1.32x faster                                         |
| json_dumps           | 8.38 ms                                                | 6.45 ms: 1.30x faster                                          |
| unpickle_pure_python | 203 us                                                 | 158 us: 1.29x faster                                           |
| xml_etree_process    | 45.1 ms                                                | 39.5 ms: 1.14x faster                                          |
| unpickle             | 9.77 us                                                | 9.16 us: 1.07x faster                                          |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.01x slower                                          |
| pickle               | 7.36 us                                                | 7.42 us: 1.01x slower                                          |
| pickle_list          | 2.83 us                                                | 2.89 us: 1.02x slower                                          |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                           |
| xml_etree_iterparse  | 72.6 ms                                                | 75.4 ms: 1.04x slower                                          |
| json_loads           | 16.9 us                                                | 17.5 us: 1.04x slower                                          |
| xml_etree_generate   | 54.3 ms                                                | 57.7 ms: 1.06x slower                                          |
| unpickle_list        | 2.66 us                                                | 3.13 us: 1.18x slower                                          |
| Geometric mean       | (ref)                                                  | 1.07x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 11.2 ms: 1.13x faster                                          |
| python_startup_no_site | 9.73 ms                                                | 8.64 ms: 1.13x faster                                          |
| Geometric mean         | (ref)                                                  | 1.13x faster                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.55 ms: 1.39x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231017-darwin-arm64-brandtbucher-justin-3.13.0a1+-7eaec09 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 93.2 us: 3.69x faster                                          |
| deltablue                | 5.15 ms                                                | 2.43 ms: 2.12x faster                                          |
| raytrace                 | 328 ms                                                 | 179 ms: 1.84x faster                                           |
| richards_super           | 60.7 ms                                                | 34.7 ms: 1.75x faster                                          |
| logging_silent           | 119 ns                                                 | 68.2 ns: 1.75x faster                                          |
| sqlglot_parse            | 1.33 ms                                                | 796 us: 1.67x faster                                           |
| richards                 | 51.4 ms                                                | 31.2 ms: 1.65x faster                                          |
| chaos                    | 66.8 ms                                                | 41.7 ms: 1.60x faster                                          |
| crypto_pyaes             | 78.0 ms                                                | 48.7 ms: 1.60x faster                                          |
| async_tree_none          | 402 ms                                                 | 254 ms: 1.59x faster                                           |
| sqlglot_transpile        | 1.54 ms                                                | 975 us: 1.58x faster                                           |
| go                       | 165 ms                                                 | 105 ms: 1.58x faster                                           |
| scimark_monte_carlo      | 72.2 ms                                                | 46.3 ms: 1.56x faster                                          |
| scimark_lu               | 110 ms                                                 | 72.5 ms: 1.52x faster                                          |
| async_tree_memoization   | 493 ms                                                 | 331 ms: 1.49x faster                                           |
| asyncio_tcp              | 673 ms                                                 | 452 ms: 1.49x faster                                           |
| pickle_pure_python       | 284 us                                                 | 193 us: 1.47x faster                                           |
| unpack_sequence          | 38.7 ns                                                | 26.4 ns: 1.46x faster                                          |
| async_tree_io            | 1.02 sec                                               | 701 ms: 1.45x faster                                           |
| mako                     | 10.5 ms                                                | 7.55 ms: 1.39x faster                                          |
| pyflate                  | 453 ms                                                 | 328 ms: 1.38x faster                                           |
| deepcopy_memo            | 34.5 us                                                | 25.1 us: 1.37x faster                                          |
| spectral_norm            | 96.4 ms                                                | 72.0 ms: 1.34x faster                                          |
| generators               | 32.9 ms                                                | 24.7 ms: 1.33x faster                                          |
| logging_simple           | 4.63 us                                                | 3.50 us: 1.32x faster                                          |
| pycparser                | 915 ms                                                 | 693 ms: 1.32x faster                                           |
| logging_format           | 5.01 us                                                | 3.79 us: 1.32x faster                                          |
| tomli_loads              | 1.76 sec                                               | 1.34 sec: 1.32x faster                                         |
| tornado_http             | 91.9 ms                                                | 70.2 ms: 1.31x faster                                          |
| json_dumps               | 8.38 ms                                                | 6.45 ms: 1.30x faster                                          |
| float                    | 72.3 ms                                                | 56.0 ms: 1.29x faster                                          |
| unpickle_pure_python     | 203 us                                                 | 158 us: 1.29x faster                                           |
| hexiom                   | 6.32 ms                                                | 4.94 ms: 1.28x faster                                          |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 525 ms: 1.28x faster                                           |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.31 sec: 1.26x faster                                         |
| create_gc_cycles         | 876 us                                                 | 701 us: 1.25x faster                                           |
| nbody                    | 94.1 ms                                                | 75.6 ms: 1.25x faster                                          |
| deepcopy                 | 278 us                                                 | 224 us: 1.24x faster                                           |
| scimark_sor              | 127 ms                                                 | 104 ms: 1.22x faster                                           |
| dulwich_log              | 37.1 ms                                                | 30.5 ms: 1.21x faster                                          |
| deepcopy_reduce          | 2.38 us                                                | 1.99 us: 1.20x faster                                          |
| mypy2                    | 308 ms                                                 | 262 ms: 1.18x faster                                           |
| docutils                 | 1.78 sec                                               | 1.52 sec: 1.18x faster                                         |
| coroutines               | 20.2 ms                                                | 17.6 ms: 1.15x faster                                          |
| xml_etree_process        | 45.1 ms                                                | 39.5 ms: 1.14x faster                                          |
| fannkuch                 | 317 ms                                                 | 281 ms: 1.13x faster                                           |
| python_startup           | 12.6 ms                                                | 11.2 ms: 1.13x faster                                          |
| python_startup_no_site   | 9.73 ms                                                | 8.64 ms: 1.13x faster                                          |
| bench_thread_pool        | 548 us                                                 | 489 us: 1.12x faster                                           |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.11 ms: 1.12x faster                                          |
| sqlglot_optimize         | 38.0 ms                                                | 34.3 ms: 1.11x faster                                          |
| scimark_fft              | 232 ms                                                 | 210 ms: 1.11x faster                                           |
| comprehensions           | 17.7 us                                                | 16.3 us: 1.09x faster                                          |
| nqueens                  | 68.1 ms                                                | 62.7 ms: 1.09x faster                                          |
| regex_dna                | 160 ms                                                 | 149 ms: 1.07x faster                                           |
| sqlglot_normalize        | 197 ms                                                 | 184 ms: 1.07x faster                                           |
| unpickle                 | 9.77 us                                                | 9.16 us: 1.07x faster                                          |
| json                     | 3.10 ms                                                | 2.97 ms: 1.04x faster                                          |
| regex_v8                 | 17.5 ms                                                | 16.9 ms: 1.04x faster                                          |
| meteor_contest           | 78.6 ms                                                | 76.8 ms: 1.02x faster                                          |
| mdp                      | 1.67 sec                                               | 1.65 sec: 1.01x faster                                         |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                           |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                          |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.01x slower                                          |
| pickle                   | 7.36 us                                                | 7.42 us: 1.01x slower                                          |
| pickle_list              | 2.83 us                                                | 2.89 us: 1.02x slower                                          |
| xml_etree_parse          | 107 ms                                                 | 111 ms: 1.03x slower                                           |
| pathlib                  | 28.8 ms                                                | 29.9 ms: 1.04x slower                                          |
| xml_etree_iterparse      | 72.6 ms                                                | 75.4 ms: 1.04x slower                                          |
| json_loads               | 16.9 us                                                | 17.5 us: 1.04x slower                                          |
| regex_effbot             | 2.45 ms                                                | 2.56 ms: 1.05x slower                                          |
| xml_etree_generate       | 54.3 ms                                                | 57.7 ms: 1.06x slower                                          |
| bench_mp_pool            | 41.0 ms                                                | 45.2 ms: 1.10x slower                                          |
| sqlite_synth             | 1.47 us                                                | 1.63 us: 1.11x slower                                          |
| coverage                 | 40.8 ms                                                | 47.0 ms: 1.15x slower                                          |
| unpickle_list            | 2.66 us                                                | 3.13 us: 1.18x slower                                          |
| telco                    | 3.68 ms                                                | 4.76 ms: 1.29x slower                                          |
| async_generators         | 233 ms                                                 | 309 ms: 1.32x slower                                           |
| Geometric mean           | (ref)                                                  | 1.23x faster                                                   |
Ignored benchmarks (21) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pprint_pformat, pprint_safe_repr, pylint, regex_compile, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.17x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.13x
