
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: e57ecf6
- commit date: 2023-09-16
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.14x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.48 sec: 1.20x faster                                |
| tornado_http   | 91.9 ms                                                | 71.1 ms: 1.29x faster                                 |
| Geometric mean | (ref)                                                  | 1.25x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 94.1 ms                                                | 70.9 ms: 1.33x faster                                 |
| float          | 72.3 ms                                                | 55.4 ms: 1.31x faster                                 |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.20x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 77.1 ms: 1.25x faster                                 |
| regex_dna      | 160 ms                                                 | 140 ms: 1.14x faster                                  |
| regex_v8       | 17.5 ms                                                | 16.4 ms: 1.07x faster                                 |
| regex_effbot   | 2.45 ms                                                | 2.50 ms: 1.02x slower                                 |
| Geometric mean | (ref)                                                  | 1.11x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 194 us: 1.46x faster                                  |
| json_dumps           | 8.38 ms                                                | 6.48 ms: 1.29x faster                                 |
| unpickle_pure_python | 203 us                                                 | 158 us: 1.29x faster                                  |
| xml_etree_process    | 45.1 ms                                                | 39.1 ms: 1.15x faster                                 |
| tomli_loads          | 1.76 sec                                               | 1.54 sec: 1.15x faster                                |
| unpickle             | 9.77 us                                                | 9.12 us: 1.07x faster                                 |
| pickle_dict          | 17.8 us                                                | 17.8 us: 1.00x slower                                 |
| pickle               | 7.36 us                                                | 7.39 us: 1.00x slower                                 |
| pickle_list          | 2.83 us                                                | 2.88 us: 1.02x slower                                 |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.02x slower                                  |
| json_loads           | 16.9 us                                                | 17.4 us: 1.03x slower                                 |
| xml_etree_iterparse  | 72.6 ms                                                | 75.8 ms: 1.04x slower                                 |
| xml_etree_generate   | 54.3 ms                                                | 57.1 ms: 1.05x slower                                 |
| unpickle_list        | 2.66 us                                                | 3.22 us: 1.21x slower                                 |
| Geometric mean       | (ref)                                                  | 1.06x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.2 ms: 1.03x faster                                 |
| python_startup_no_site | 9.73 ms                                                | 9.56 ms: 1.02x faster                                 |
| Geometric mean         | (ref)                                                  | 1.02x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.28 ms: 1.44x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230916-darwin-arm64-python-main-3.13.0a0-e57ecf6 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 92.4 us: 3.72x faster                                 |
| deltablue                | 5.15 ms                                                | 2.42 ms: 2.13x faster                                 |
| raytrace                 | 328 ms                                                 | 178 ms: 1.85x faster                                  |
| logging_silent           | 119 ns                                                 | 70.6 ns: 1.69x faster                                 |
| crypto_pyaes             | 78.0 ms                                                | 46.8 ms: 1.67x faster                                 |
| asyncio_tcp              | 673 ms                                                 | 404 ms: 1.67x faster                                  |
| sqlglot_parse            | 1.33 ms                                                | 802 us: 1.66x faster                                  |
| chaos                    | 66.8 ms                                                | 40.6 ms: 1.65x faster                                 |
| mypy2                    | 308 ms                                                 | 190 ms: 1.62x faster                                  |
| richards_super           | 60.7 ms                                                | 37.5 ms: 1.62x faster                                 |
| async_tree_none          | 402 ms                                                 | 250 ms: 1.61x faster                                  |
| scimark_monte_carlo      | 72.2 ms                                                | 45.1 ms: 1.60x faster                                 |
| sqlglot_transpile        | 1.54 ms                                                | 977 us: 1.57x faster                                  |
| go                       | 165 ms                                                 | 105 ms: 1.57x faster                                  |
| scimark_lu               | 110 ms                                                 | 71.9 ms: 1.53x faster                                 |
| richards                 | 51.4 ms                                                | 33.9 ms: 1.52x faster                                 |
| async_tree_memoization   | 493 ms                                                 | 326 ms: 1.51x faster                                  |
| unpack_sequence          | 38.7 ns                                                | 26.2 ns: 1.48x faster                                 |
| async_tree_io            | 1.02 sec                                               | 695 ms: 1.47x faster                                  |
| pickle_pure_python       | 284 us                                                 | 194 us: 1.46x faster                                  |
| mako                     | 10.5 ms                                                | 7.28 ms: 1.44x faster                                 |
| deepcopy_memo            | 34.5 us                                                | 24.4 us: 1.41x faster                                 |
| hexiom                   | 6.32 ms                                                | 4.68 ms: 1.35x faster                                 |
| spectral_norm            | 96.4 ms                                                | 71.7 ms: 1.35x faster                                 |
| generators               | 32.9 ms                                                | 24.5 ms: 1.34x faster                                 |
| pycparser                | 915 ms                                                 | 686 ms: 1.33x faster                                  |
| nbody                    | 94.1 ms                                                | 70.9 ms: 1.33x faster                                 |
| pyflate                  | 453 ms                                                 | 345 ms: 1.31x faster                                  |
| float                    | 72.3 ms                                                | 55.4 ms: 1.31x faster                                 |
| json_dumps               | 8.38 ms                                                | 6.48 ms: 1.29x faster                                 |
| tornado_http             | 91.9 ms                                                | 71.1 ms: 1.29x faster                                 |
| logging_format           | 5.01 us                                                | 3.88 us: 1.29x faster                                 |
| unpickle_pure_python     | 203 us                                                 | 158 us: 1.29x faster                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.28 sec: 1.29x faster                                |
| logging_simple           | 4.63 us                                                | 3.59 us: 1.29x faster                                 |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 521 ms: 1.29x faster                                  |
| regex_compile            | 96.6 ms                                                | 77.1 ms: 1.25x faster                                 |
| create_gc_cycles         | 876 us                                                 | 703 us: 1.25x faster                                  |
| deepcopy                 | 278 us                                                 | 225 us: 1.23x faster                                  |
| pprint_pformat           | 1.24 sec                                               | 1.02 sec: 1.21x faster                                |
| dulwich_log              | 37.1 ms                                                | 30.5 ms: 1.21x faster                                 |
| comprehensions           | 17.7 us                                                | 14.6 us: 1.21x faster                                 |
| pprint_safe_repr         | 609 ms                                                 | 504 ms: 1.21x faster                                  |
| docutils                 | 1.78 sec                                               | 1.48 sec: 1.20x faster                                |
| scimark_sor              | 127 ms                                                 | 106 ms: 1.19x faster                                  |
| deepcopy_reduce          | 2.38 us                                                | 2.03 us: 1.17x faster                                 |
| scimark_fft              | 232 ms                                                 | 198 ms: 1.17x faster                                  |
| nqueens                  | 68.1 ms                                                | 58.5 ms: 1.16x faster                                 |
| xml_etree_process        | 45.1 ms                                                | 39.1 ms: 1.15x faster                                 |
| tomli_loads              | 1.76 sec                                               | 1.54 sec: 1.15x faster                                |
| bench_thread_pool        | 548 us                                                 | 481 us: 1.14x faster                                  |
| regex_dna                | 160 ms                                                 | 140 ms: 1.14x faster                                  |
| coroutines               | 20.2 ms                                                | 18.0 ms: 1.12x faster                                 |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.10 ms: 1.12x faster                                 |
| sqlglot_optimize         | 38.0 ms                                                | 34.3 ms: 1.11x faster                                 |
| fannkuch                 | 317 ms                                                 | 289 ms: 1.10x faster                                  |
| regex_v8                 | 17.5 ms                                                | 16.4 ms: 1.07x faster                                 |
| unpickle                 | 9.77 us                                                | 9.12 us: 1.07x faster                                 |
| meteor_contest           | 78.6 ms                                                | 73.8 ms: 1.07x faster                                 |
| sqlglot_normalize        | 197 ms                                                 | 185 ms: 1.06x faster                                  |
| mdp                      | 1.67 sec                                               | 1.61 sec: 1.03x faster                                |
| python_startup           | 12.6 ms                                                | 12.2 ms: 1.03x faster                                 |
| json                     | 3.10 ms                                                | 3.01 ms: 1.03x faster                                 |
| python_startup_no_site   | 9.73 ms                                                | 9.56 ms: 1.02x faster                                 |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                  |
| pickle_dict              | 17.8 us                                                | 17.8 us: 1.00x slower                                 |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                 |
| pickle                   | 7.36 us                                                | 7.39 us: 1.00x slower                                 |
| pickle_list              | 2.83 us                                                | 2.88 us: 1.02x slower                                 |
| xml_etree_parse          | 107 ms                                                 | 110 ms: 1.02x slower                                  |
| regex_effbot             | 2.45 ms                                                | 2.50 ms: 1.02x slower                                 |
| json_loads               | 16.9 us                                                | 17.4 us: 1.03x slower                                 |
| xml_etree_iterparse      | 72.6 ms                                                | 75.8 ms: 1.04x slower                                 |
| xml_etree_generate       | 54.3 ms                                                | 57.1 ms: 1.05x slower                                 |
| sqlite_synth             | 1.47 us                                                | 1.58 us: 1.08x slower                                 |
| pathlib                  | 28.8 ms                                                | 32.8 ms: 1.14x slower                                 |
| bench_mp_pool            | 41.0 ms                                                | 46.7 ms: 1.14x slower                                 |
| coverage                 | 40.8 ms                                                | 46.6 ms: 1.14x slower                                 |
| unpickle_list            | 2.66 us                                                | 3.22 us: 1.21x slower                                 |
| telco                    | 3.68 ms                                                | 4.68 ms: 1.27x slower                                 |
| dask                     | 258 ms                                                 | 332 ms: 1.29x slower                                  |
| async_generators         | 233 ms                                                 | 304 ms: 1.30x slower                                  |
| Geometric mean           | (ref)                                                  | 1.23x faster                                          |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.14x
