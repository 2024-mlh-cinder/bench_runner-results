
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 51863b7
- commit date: 2023-09-23
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.48 sec: 1.20x faster                                |
| tornado_http   | 91.9 ms                                                | 69.7 ms: 1.32x faster                                 |
| Geometric mean | (ref)                                                  | 1.26x faster                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| nbody          | 94.1 ms                                                | 65.9 ms: 1.43x faster                                 |
| float          | 72.3 ms                                                | 53.3 ms: 1.36x faster                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| Geometric mean | (ref)                                                  | 1.25x faster                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 75.8 ms: 1.27x faster                                 |
| regex_dna      | 160 ms                                                 | 141 ms: 1.13x faster                                  |
| regex_v8       | 17.5 ms                                                | 16.1 ms: 1.09x faster                                 |
| regex_effbot   | 2.45 ms                                                | 2.52 ms: 1.03x slower                                 |
| Geometric mean | (ref)                                                  | 1.11x faster                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 192 us: 1.48x faster                                  |
| unpickle_pure_python | 203 us                                                 | 153 us: 1.33x faster                                  |
| json_dumps           | 8.38 ms                                                | 6.66 ms: 1.26x faster                                 |
| tomli_loads          | 1.76 sec                                               | 1.53 sec: 1.15x faster                                |
| xml_etree_process    | 45.1 ms                                                | 39.2 ms: 1.15x faster                                 |
| unpickle             | 9.77 us                                                | 9.14 us: 1.07x faster                                 |
| pickle               | 7.36 us                                                | 7.32 us: 1.00x faster                                 |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.01x slower                                 |
| pickle_list          | 2.83 us                                                | 2.86 us: 1.01x slower                                 |
| xml_etree_parse      | 107 ms                                                 | 109 ms: 1.02x slower                                  |
| xml_etree_generate   | 54.3 ms                                                | 55.6 ms: 1.02x slower                                 |
| xml_etree_iterparse  | 72.6 ms                                                | 75.3 ms: 1.04x slower                                 |
| json_loads           | 16.9 us                                                | 17.6 us: 1.04x slower                                 |
| unpickle_list        | 2.66 us                                                | 3.11 us: 1.17x slower                                 |
| Geometric mean       | (ref)                                                  | 1.07x faster                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.0 ms: 1.05x faster                                 |
| python_startup_no_site | 9.73 ms                                                | 9.38 ms: 1.04x faster                                 |
| Geometric mean         | (ref)                                                  | 1.04x faster                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.25 ms: 1.45x faster                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230923-darwin-arm64-python-main-3.13.0a0-51863b7 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 91.2 us: 3.77x faster                                 |
| deltablue                | 5.15 ms                                                | 2.35 ms: 2.19x faster                                 |
| raytrace                 | 328 ms                                                 | 170 ms: 1.92x faster                                  |
| logging_silent           | 119 ns                                                 | 66.8 ns: 1.78x faster                                 |
| crypto_pyaes             | 78.0 ms                                                | 46.3 ms: 1.68x faster                                 |
| chaos                    | 66.8 ms                                                | 39.7 ms: 1.68x faster                                 |
| sqlglot_parse            | 1.33 ms                                                | 795 us: 1.67x faster                                  |
| scimark_monte_carlo      | 72.2 ms                                                | 44.3 ms: 1.63x faster                                 |
| mypy2                    | 308 ms                                                 | 189 ms: 1.63x faster                                  |
| async_tree_none          | 402 ms                                                 | 250 ms: 1.61x faster                                  |
| richards_super           | 60.7 ms                                                | 38.0 ms: 1.60x faster                                 |
| sqlglot_transpile        | 1.54 ms                                                | 966 us: 1.59x faster                                  |
| scimark_lu               | 110 ms                                                 | 69.5 ms: 1.58x faster                                 |
| go                       | 165 ms                                                 | 104 ms: 1.58x faster                                  |
| async_tree_memoization   | 493 ms                                                 | 325 ms: 1.52x faster                                  |
| richards                 | 51.4 ms                                                | 34.4 ms: 1.49x faster                                 |
| pickle_pure_python       | 284 us                                                 | 192 us: 1.48x faster                                  |
| unpack_sequence          | 38.7 ns                                                | 26.2 ns: 1.47x faster                                 |
| asyncio_tcp              | 673 ms                                                 | 458 ms: 1.47x faster                                  |
| async_tree_io            | 1.02 sec                                               | 696 ms: 1.47x faster                                  |
| deepcopy_memo            | 34.5 us                                                | 23.6 us: 1.46x faster                                 |
| mako                     | 10.5 ms                                                | 7.25 ms: 1.45x faster                                 |
| nbody                    | 94.1 ms                                                | 65.9 ms: 1.43x faster                                 |
| spectral_norm            | 96.4 ms                                                | 69.1 ms: 1.39x faster                                 |
| hexiom                   | 6.32 ms                                                | 4.62 ms: 1.37x faster                                 |
| float                    | 72.3 ms                                                | 53.3 ms: 1.36x faster                                 |
| pycparser                | 915 ms                                                 | 681 ms: 1.34x faster                                  |
| pyflate                  | 453 ms                                                 | 338 ms: 1.34x faster                                  |
| unpickle_pure_python     | 203 us                                                 | 153 us: 1.33x faster                                  |
| tornado_http             | 91.9 ms                                                | 69.7 ms: 1.32x faster                                 |
| generators               | 32.9 ms                                                | 25.1 ms: 1.31x faster                                 |
| logging_format           | 5.01 us                                                | 3.88 us: 1.29x faster                                 |
| logging_simple           | 4.63 us                                                | 3.59 us: 1.29x faster                                 |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 520 ms: 1.29x faster                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.28 sec: 1.29x faster                                |
| regex_compile            | 96.6 ms                                                | 75.8 ms: 1.27x faster                                 |
| deepcopy                 | 278 us                                                 | 219 us: 1.27x faster                                  |
| json_dumps               | 8.38 ms                                                | 6.66 ms: 1.26x faster                                 |
| pprint_safe_repr         | 609 ms                                                 | 489 ms: 1.24x faster                                  |
| create_gc_cycles         | 876 us                                                 | 705 us: 1.24x faster                                  |
| pprint_pformat           | 1.24 sec                                               | 999 ms: 1.24x faster                                  |
| scimark_sor              | 127 ms                                                 | 103 ms: 1.23x faster                                  |
| dulwich_log              | 37.1 ms                                                | 30.1 ms: 1.23x faster                                 |
| scimark_fft              | 232 ms                                                 | 192 ms: 1.21x faster                                  |
| deepcopy_reduce          | 2.38 us                                                | 1.97 us: 1.21x faster                                 |
| comprehensions           | 17.7 us                                                | 14.7 us: 1.20x faster                                 |
| docutils                 | 1.78 sec                                               | 1.48 sec: 1.20x faster                                |
| nqueens                  | 68.1 ms                                                | 57.2 ms: 1.19x faster                                 |
| bench_thread_pool        | 548 us                                                 | 474 us: 1.16x faster                                  |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.01 ms: 1.15x faster                                 |
| coroutines               | 20.2 ms                                                | 17.5 ms: 1.15x faster                                 |
| tomli_loads              | 1.76 sec                                               | 1.53 sec: 1.15x faster                                |
| xml_etree_process        | 45.1 ms                                                | 39.2 ms: 1.15x faster                                 |
| regex_dna                | 160 ms                                                 | 141 ms: 1.13x faster                                  |
| fannkuch                 | 317 ms                                                 | 281 ms: 1.13x faster                                  |
| sqlglot_optimize         | 38.0 ms                                                | 34.0 ms: 1.12x faster                                 |
| regex_v8                 | 17.5 ms                                                | 16.1 ms: 1.09x faster                                 |
| meteor_contest           | 78.6 ms                                                | 72.9 ms: 1.08x faster                                 |
| sqlglot_normalize        | 197 ms                                                 | 183 ms: 1.08x faster                                  |
| unpickle                 | 9.77 us                                                | 9.14 us: 1.07x faster                                 |
| mdp                      | 1.67 sec                                               | 1.59 sec: 1.05x faster                                |
| python_startup           | 12.6 ms                                                | 12.0 ms: 1.05x faster                                 |
| python_startup_no_site   | 9.73 ms                                                | 9.38 ms: 1.04x faster                                 |
| json                     | 3.10 ms                                                | 3.00 ms: 1.03x faster                                 |
| pickle                   | 7.36 us                                                | 7.32 us: 1.00x faster                                 |
| pidigits                 | 282 ms                                                 | 281 ms: 1.00x faster                                  |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                 |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.01x slower                                 |
| pickle_list              | 2.83 us                                                | 2.86 us: 1.01x slower                                 |
| xml_etree_parse          | 107 ms                                                 | 109 ms: 1.02x slower                                  |
| xml_etree_generate       | 54.3 ms                                                | 55.6 ms: 1.02x slower                                 |
| regex_effbot             | 2.45 ms                                                | 2.52 ms: 1.03x slower                                 |
| xml_etree_iterparse      | 72.6 ms                                                | 75.3 ms: 1.04x slower                                 |
| json_loads               | 16.9 us                                                | 17.6 us: 1.04x slower                                 |
| sqlite_synth             | 1.47 us                                                | 1.58 us: 1.08x slower                                 |
| coverage                 | 40.8 ms                                                | 46.2 ms: 1.13x slower                                 |
| bench_mp_pool            | 41.0 ms                                                | 46.6 ms: 1.14x slower                                 |
| pathlib                  | 28.8 ms                                                | 33.0 ms: 1.14x slower                                 |
| unpickle_list            | 2.66 us                                                | 3.11 us: 1.17x slower                                 |
| async_generators         | 233 ms                                                 | 296 ms: 1.27x slower                                  |
| telco                    | 3.68 ms                                                | 4.68 ms: 1.27x slower                                 |
| dask                     | 258 ms                                                 | 328 ms: 1.27x slower                                  |
| Geometric mean           | (ref)                                                  | 1.24x faster                                          |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.15x
