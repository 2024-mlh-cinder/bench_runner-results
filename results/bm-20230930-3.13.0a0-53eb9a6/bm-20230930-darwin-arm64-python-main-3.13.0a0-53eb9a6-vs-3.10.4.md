
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 53eb9a6
- commit date: 2023-09-30
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.49 sec: 1.20x faster                                |
| tornado_http   | 91.9 ms                                                | 70.0 ms: 1.31x faster                                 |
| Geometric mean | (ref)                                                  | 1.25x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 94.1 ms                                                | 66.1 ms: 1.42x faster                                 |
| float          | 72.3 ms                                                | 53.4 ms: 1.36x faster                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.25x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 75.8 ms: 1.27x faster                                 |
| regex_dna      | 160 ms                                                 | 140 ms: 1.14x faster                                  |
| regex_v8       | 17.5 ms                                                | 16.1 ms: 1.09x faster                                 |
| regex_effbot   | 2.45 ms                                                | 2.51 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.11x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 193 us: 1.47x faster                                  |
| unpickle_pure_python | 203 us                                                 | 154 us: 1.32x faster                                  |
| json_dumps           | 8.38 ms                                                | 6.67 ms: 1.26x faster                                 |
| xml_etree_process    | 45.1 ms                                                | 39.0 ms: 1.15x faster                                 |
| tomli_loads          | 1.76 sec                                               | 1.53 sec: 1.15x faster                                |
| unpickle             | 9.77 us                                                | 9.11 us: 1.07x faster                                 |
| pickle               | 7.36 us                                                | 7.33 us: 1.00x faster                                 |
| pickle_dict          | 17.8 us                                                | 18.0 us: 1.01x slower                                 |
| xml_etree_parse      | 107 ms                                                 | 109 ms: 1.02x slower                                  |
| pickle_list          | 2.83 us                                                | 2.90 us: 1.02x slower                                 |
| xml_etree_iterparse  | 72.6 ms                                                | 75.0 ms: 1.03x slower                                 |
| xml_etree_generate   | 54.3 ms                                                | 56.1 ms: 1.03x slower                                 |
| json_loads           | 16.9 us                                                | 17.5 us: 1.04x slower                                 |
| unpickle_list        | 2.66 us                                                | 3.12 us: 1.17x slower                                 |
| Geometric mean       | (ref)                                                  | 1.07x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.0 ms: 1.05x faster                                 |
| python_startup_no_site | 9.73 ms                                                | 9.35 ms: 1.04x faster                                 |
| Geometric mean         | (ref)                                                  | 1.05x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.23 ms: 1.45x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230930-darwin-arm64-python-main-3.13.0a0-53eb9a6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 93.0 us: 3.70x faster                                 |
| deltablue                | 5.15 ms                                                | 2.34 ms: 2.20x faster                                 |
| raytrace                 | 328 ms                                                 | 171 ms: 1.92x faster                                  |
| logging_silent           | 119 ns                                                 | 67.4 ns: 1.77x faster                                 |
| chaos                    | 66.8 ms                                                | 39.7 ms: 1.68x faster                                 |
| sqlglot_parse            | 1.33 ms                                                | 792 us: 1.68x faster                                  |
| crypto_pyaes             | 78.0 ms                                                | 46.4 ms: 1.68x faster                                 |
| scimark_monte_carlo      | 72.2 ms                                                | 44.2 ms: 1.64x faster                                 |
| mypy2                    | 308 ms                                                 | 191 ms: 1.62x faster                                  |
| async_tree_none          | 402 ms                                                 | 250 ms: 1.61x faster                                  |
| richards_super           | 60.7 ms                                                | 37.9 ms: 1.60x faster                                 |
| go                       | 165 ms                                                 | 103 ms: 1.60x faster                                  |
| sqlglot_transpile        | 1.54 ms                                                | 963 us: 1.60x faster                                  |
| scimark_lu               | 110 ms                                                 | 69.5 ms: 1.58x faster                                 |
| asyncio_tcp              | 673 ms                                                 | 433 ms: 1.55x faster                                  |
| async_tree_memoization   | 493 ms                                                 | 326 ms: 1.51x faster                                  |
| richards                 | 51.4 ms                                                | 34.4 ms: 1.49x faster                                 |
| unpack_sequence          | 38.7 ns                                                | 26.2 ns: 1.47x faster                                 |
| pickle_pure_python       | 284 us                                                 | 193 us: 1.47x faster                                  |
| async_tree_io            | 1.02 sec                                               | 696 ms: 1.47x faster                                  |
| mako                     | 10.5 ms                                                | 7.23 ms: 1.45x faster                                 |
| deepcopy_memo            | 34.5 us                                                | 23.9 us: 1.44x faster                                 |
| nbody                    | 94.1 ms                                                | 66.1 ms: 1.42x faster                                 |
| spectral_norm            | 96.4 ms                                                | 69.1 ms: 1.39x faster                                 |
| hexiom                   | 6.32 ms                                                | 4.61 ms: 1.37x faster                                 |
| float                    | 72.3 ms                                                | 53.4 ms: 1.36x faster                                 |
| pyflate                  | 453 ms                                                 | 335 ms: 1.35x faster                                  |
| pycparser                | 915 ms                                                 | 683 ms: 1.34x faster                                  |
| generators               | 32.9 ms                                                | 24.7 ms: 1.33x faster                                 |
| unpickle_pure_python     | 203 us                                                 | 154 us: 1.32x faster                                  |
| tornado_http             | 91.9 ms                                                | 70.0 ms: 1.31x faster                                 |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.27 sec: 1.29x faster                                |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 521 ms: 1.29x faster                                  |
| logging_format           | 5.01 us                                                | 3.92 us: 1.28x faster                                 |
| regex_compile            | 96.6 ms                                                | 75.8 ms: 1.27x faster                                 |
| logging_simple           | 4.63 us                                                | 3.64 us: 1.27x faster                                 |
| json_dumps               | 8.38 ms                                                | 6.67 ms: 1.26x faster                                 |
| deepcopy                 | 278 us                                                 | 222 us: 1.25x faster                                  |
| create_gc_cycles         | 876 us                                                 | 703 us: 1.25x faster                                  |
| scimark_sor              | 127 ms                                                 | 103 ms: 1.23x faster                                  |
| dulwich_log              | 37.1 ms                                                | 30.2 ms: 1.23x faster                                 |
| pprint_pformat           | 1.24 sec                                               | 1.01 sec: 1.22x faster                                |
| pprint_safe_repr         | 609 ms                                                 | 500 ms: 1.22x faster                                  |
| deepcopy_reduce          | 2.38 us                                                | 1.98 us: 1.20x faster                                 |
| docutils                 | 1.78 sec                                               | 1.49 sec: 1.20x faster                                |
| comprehensions           | 17.7 us                                                | 14.8 us: 1.20x faster                                 |
| scimark_fft              | 232 ms                                                 | 194 ms: 1.20x faster                                  |
| nqueens                  | 68.1 ms                                                | 57.2 ms: 1.19x faster                                 |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.00 ms: 1.16x faster                                 |
| xml_etree_process        | 45.1 ms                                                | 39.0 ms: 1.15x faster                                 |
| tomli_loads              | 1.76 sec                                               | 1.53 sec: 1.15x faster                                |
| regex_dna                | 160 ms                                                 | 140 ms: 1.14x faster                                  |
| coroutines               | 20.2 ms                                                | 17.7 ms: 1.14x faster                                 |
| bench_thread_pool        | 548 us                                                 | 483 us: 1.14x faster                                  |
| fannkuch                 | 317 ms                                                 | 285 ms: 1.12x faster                                  |
| sqlglot_optimize         | 38.0 ms                                                | 34.2 ms: 1.11x faster                                 |
| regex_v8                 | 17.5 ms                                                | 16.1 ms: 1.09x faster                                 |
| sqlglot_normalize        | 197 ms                                                 | 183 ms: 1.07x faster                                  |
| unpickle                 | 9.77 us                                                | 9.11 us: 1.07x faster                                 |
| meteor_contest           | 78.6 ms                                                | 73.5 ms: 1.07x faster                                 |
| python_startup           | 12.6 ms                                                | 12.0 ms: 1.05x faster                                 |
| mdp                      | 1.67 sec                                               | 1.60 sec: 1.04x faster                                |
| python_startup_no_site   | 9.73 ms                                                | 9.35 ms: 1.04x faster                                 |
| json                     | 3.10 ms                                                | 3.01 ms: 1.03x faster                                 |
| pickle                   | 7.36 us                                                | 7.33 us: 1.00x faster                                 |
| pidigits                 | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                 |
| pickle_dict              | 17.8 us                                                | 18.0 us: 1.01x slower                                 |
| xml_etree_parse          | 107 ms                                                 | 109 ms: 1.02x slower                                  |
| pickle_list              | 2.83 us                                                | 2.90 us: 1.02x slower                                 |
| regex_effbot             | 2.45 ms                                                | 2.51 ms: 1.03x slower                                 |
| xml_etree_iterparse      | 72.6 ms                                                | 75.0 ms: 1.03x slower                                 |
| xml_etree_generate       | 54.3 ms                                                | 56.1 ms: 1.03x slower                                 |
| json_loads               | 16.9 us                                                | 17.5 us: 1.04x slower                                 |
| sqlite_synth             | 1.47 us                                                | 1.59 us: 1.08x slower                                 |
| coverage                 | 40.8 ms                                                | 46.2 ms: 1.13x slower                                 |
| bench_mp_pool            | 41.0 ms                                                | 46.9 ms: 1.14x slower                                 |
| pathlib                  | 28.8 ms                                                | 33.6 ms: 1.17x slower                                 |
| unpickle_list            | 2.66 us                                                | 3.12 us: 1.17x slower                                 |
| telco                    | 3.68 ms                                                | 4.62 ms: 1.26x slower                                 |
| async_generators         | 233 ms                                                 | 295 ms: 1.27x slower                                  |
| Geometric mean           | (ref)                                                  | 1.25x faster                                          |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.16x
