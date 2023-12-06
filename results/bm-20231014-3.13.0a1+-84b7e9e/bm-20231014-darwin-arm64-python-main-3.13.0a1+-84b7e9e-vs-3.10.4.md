
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.48 sec: 1.20x faster                                 |
| tornado_http   | 91.9 ms                                                | 69.3 ms: 1.33x faster                                  |
| Geometric mean | (ref)                                                  | 1.26x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 72.3 ms                                                | 54.7 ms: 1.32x faster                                  |
| nbody          | 94.1 ms                                                | 71.3 ms: 1.32x faster                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| Geometric mean | (ref)                                                  | 1.20x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 75.6 ms: 1.28x faster                                  |
| regex_dna      | 160 ms                                                 | 149 ms: 1.07x faster                                   |
| regex_v8       | 17.5 ms                                                | 16.8 ms: 1.04x faster                                  |
| regex_effbot   | 2.45 ms                                                | 2.57 ms: 1.05x slower                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 193 us: 1.47x faster                                   |
| json_dumps           | 8.38 ms                                                | 6.44 ms: 1.30x faster                                  |
| unpickle_pure_python | 203 us                                                 | 157 us: 1.30x faster                                   |
| xml_etree_process    | 45.1 ms                                                | 39.0 ms: 1.16x faster                                  |
| tomli_loads          | 1.76 sec                                               | 1.54 sec: 1.15x faster                                 |
| unpickle             | 9.77 us                                                | 9.05 us: 1.08x faster                                  |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.00x slower                                  |
| pickle               | 7.36 us                                                | 7.40 us: 1.01x slower                                  |
| pickle_list          | 2.83 us                                                | 2.89 us: 1.02x slower                                  |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                   |
| json_loads           | 16.9 us                                                | 17.4 us: 1.03x slower                                  |
| xml_etree_iterparse  | 72.6 ms                                                | 75.3 ms: 1.04x slower                                  |
| xml_etree_generate   | 54.3 ms                                                | 57.2 ms: 1.05x slower                                  |
| unpickle_list        | 2.66 us                                                | 3.15 us: 1.18x slower                                  |
| Geometric mean       | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.7 ms: 1.01x slower                                  |
| python_startup_no_site | 9.73 ms                                                | 10.3 ms: 1.05x slower                                  |
| Geometric mean         | (ref)                                                  | 1.03x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.34 ms: 1.43x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-darwin-arm64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 94.4 us: 3.65x faster                                  |
| deltablue                | 5.15 ms                                                | 2.34 ms: 2.20x faster                                  |
| raytrace                 | 328 ms                                                 | 173 ms: 1.89x faster                                   |
| logging_silent           | 119 ns                                                 | 67.7 ns: 1.76x faster                                  |
| richards_super           | 60.7 ms                                                | 36.2 ms: 1.68x faster                                  |
| sqlglot_parse            | 1.33 ms                                                | 797 us: 1.67x faster                                   |
| chaos                    | 66.8 ms                                                | 40.1 ms: 1.67x faster                                  |
| crypto_pyaes             | 78.0 ms                                                | 47.1 ms: 1.66x faster                                  |
| scimark_monte_carlo      | 72.2 ms                                                | 44.8 ms: 1.61x faster                                  |
| async_tree_none          | 402 ms                                                 | 250 ms: 1.61x faster                                   |
| asyncio_tcp              | 673 ms                                                 | 420 ms: 1.60x faster                                   |
| go                       | 165 ms                                                 | 104 ms: 1.59x faster                                   |
| sqlglot_transpile        | 1.54 ms                                                | 970 us: 1.58x faster                                   |
| scimark_lu               | 110 ms                                                 | 70.0 ms: 1.57x faster                                  |
| richards                 | 51.4 ms                                                | 32.8 ms: 1.56x faster                                  |
| async_tree_memoization   | 493 ms                                                 | 328 ms: 1.50x faster                                   |
| unpack_sequence          | 38.7 ns                                                | 26.4 ns: 1.47x faster                                  |
| pickle_pure_python       | 284 us                                                 | 193 us: 1.47x faster                                   |
| async_tree_io            | 1.02 sec                                               | 698 ms: 1.46x faster                                   |
| deepcopy_memo            | 34.5 us                                                | 24.0 us: 1.44x faster                                  |
| mako                     | 10.5 ms                                                | 7.34 ms: 1.43x faster                                  |
| hexiom                   | 6.32 ms                                                | 4.58 ms: 1.38x faster                                  |
| spectral_norm            | 96.4 ms                                                | 70.5 ms: 1.37x faster                                  |
| generators               | 32.9 ms                                                | 24.1 ms: 1.37x faster                                  |
| pyflate                  | 453 ms                                                 | 334 ms: 1.36x faster                                   |
| tornado_http             | 91.9 ms                                                | 69.3 ms: 1.33x faster                                  |
| pycparser                | 915 ms                                                 | 690 ms: 1.33x faster                                   |
| float                    | 72.3 ms                                                | 54.7 ms: 1.32x faster                                  |
| nbody                    | 94.1 ms                                                | 71.3 ms: 1.32x faster                                  |
| logging_format           | 5.01 us                                                | 3.84 us: 1.31x faster                                  |
| logging_simple           | 4.63 us                                                | 3.55 us: 1.30x faster                                  |
| json_dumps               | 8.38 ms                                                | 6.44 ms: 1.30x faster                                  |
| unpickle_pure_python     | 203 us                                                 | 157 us: 1.30x faster                                   |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 522 ms: 1.28x faster                                   |
| regex_compile            | 96.6 ms                                                | 75.6 ms: 1.28x faster                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.26x faster                                 |
| deepcopy                 | 278 us                                                 | 221 us: 1.26x faster                                   |
| create_gc_cycles         | 876 us                                                 | 701 us: 1.25x faster                                   |
| scimark_sor              | 127 ms                                                 | 103 ms: 1.23x faster                                   |
| dulwich_log              | 37.1 ms                                                | 30.4 ms: 1.22x faster                                  |
| pprint_pformat           | 1.24 sec                                               | 1.02 sec: 1.21x faster                                 |
| pprint_safe_repr         | 609 ms                                                 | 502 ms: 1.21x faster                                   |
| comprehensions           | 17.7 us                                                | 14.6 us: 1.21x faster                                  |
| deepcopy_reduce          | 2.38 us                                                | 1.97 us: 1.21x faster                                  |
| docutils                 | 1.78 sec                                               | 1.48 sec: 1.20x faster                                 |
| mypy2                    | 308 ms                                                 | 259 ms: 1.19x faster                                   |
| nqueens                  | 68.1 ms                                                | 57.4 ms: 1.19x faster                                  |
| scimark_fft              | 232 ms                                                 | 197 ms: 1.18x faster                                   |
| xml_etree_process        | 45.1 ms                                                | 39.0 ms: 1.16x faster                                  |
| tomli_loads              | 1.76 sec                                               | 1.54 sec: 1.15x faster                                 |
| bench_thread_pool        | 548 us                                                 | 479 us: 1.15x faster                                   |
| coroutines               | 20.2 ms                                                | 17.7 ms: 1.14x faster                                  |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.06 ms: 1.13x faster                                  |
| fannkuch                 | 317 ms                                                 | 282 ms: 1.13x faster                                   |
| sqlglot_optimize         | 38.0 ms                                                | 34.0 ms: 1.12x faster                                  |
| unpickle                 | 9.77 us                                                | 9.05 us: 1.08x faster                                  |
| sqlglot_normalize        | 197 ms                                                 | 182 ms: 1.08x faster                                   |
| regex_dna                | 160 ms                                                 | 149 ms: 1.07x faster                                   |
| meteor_contest           | 78.6 ms                                                | 73.7 ms: 1.07x faster                                  |
| regex_v8                 | 17.5 ms                                                | 16.8 ms: 1.04x faster                                  |
| mdp                      | 1.67 sec                                               | 1.62 sec: 1.03x faster                                 |
| json                     | 3.10 ms                                                | 3.04 ms: 1.02x faster                                  |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                  |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.00x slower                                  |
| pickle                   | 7.36 us                                                | 7.40 us: 1.01x slower                                  |
| python_startup           | 12.6 ms                                                | 12.7 ms: 1.01x slower                                  |
| pickle_list              | 2.83 us                                                | 2.89 us: 1.02x slower                                  |
| pathlib                  | 28.8 ms                                                | 29.6 ms: 1.03x slower                                  |
| xml_etree_parse          | 107 ms                                                 | 111 ms: 1.03x slower                                   |
| json_loads               | 16.9 us                                                | 17.4 us: 1.03x slower                                  |
| xml_etree_iterparse      | 72.6 ms                                                | 75.3 ms: 1.04x slower                                  |
| regex_effbot             | 2.45 ms                                                | 2.57 ms: 1.05x slower                                  |
| xml_etree_generate       | 54.3 ms                                                | 57.2 ms: 1.05x slower                                  |
| python_startup_no_site   | 9.73 ms                                                | 10.3 ms: 1.05x slower                                  |
| sqlite_synth             | 1.47 us                                                | 1.63 us: 1.11x slower                                  |
| bench_mp_pool            | 41.0 ms                                                | 45.9 ms: 1.12x slower                                  |
| coverage                 | 40.8 ms                                                | 47.0 ms: 1.15x slower                                  |
| unpickle_list            | 2.66 us                                                | 3.15 us: 1.18x slower                                  |
| telco                    | 3.68 ms                                                | 4.63 ms: 1.26x slower                                  |
| async_generators         | 233 ms                                                 | 300 ms: 1.29x slower                                   |
| Geometric mean           | (ref)                                                  | 1.24x faster                                           |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.15x
