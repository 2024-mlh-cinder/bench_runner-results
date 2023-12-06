
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 6c23635
- commit date: 2023-10-21
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.49 sec: 1.19x faster                                 |
| tornado_http   | 91.9 ms                                                | 70.1 ms: 1.31x faster                                  |
| Geometric mean | (ref)                                                  | 1.25x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 94.1 ms                                                | 71.3 ms: 1.32x faster                                  |
| float          | 72.3 ms                                                | 55.0 ms: 1.32x faster                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| Geometric mean | (ref)                                                  | 1.20x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 75.9 ms: 1.27x faster                                  |
| regex_dna      | 160 ms                                                 | 149 ms: 1.07x faster                                   |
| regex_v8       | 17.5 ms                                                | 16.8 ms: 1.04x faster                                  |
| regex_effbot   | 2.45 ms                                                | 2.62 ms: 1.07x slower                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 195 us: 1.45x faster                                   |
| json_dumps           | 8.38 ms                                                | 6.42 ms: 1.30x faster                                  |
| unpickle_pure_python | 203 us                                                 | 156 us: 1.30x faster                                   |
| xml_etree_process    | 45.1 ms                                                | 38.8 ms: 1.16x faster                                  |
| tomli_loads          | 1.76 sec                                               | 1.54 sec: 1.14x faster                                 |
| unpickle             | 9.77 us                                                | 9.12 us: 1.07x faster                                  |
| pickle               | 7.36 us                                                | 7.41 us: 1.01x slower                                  |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.01x slower                                  |
| pickle_list          | 2.83 us                                                | 2.89 us: 1.02x slower                                  |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                   |
| json_loads           | 16.9 us                                                | 17.5 us: 1.04x slower                                  |
| xml_etree_iterparse  | 72.6 ms                                                | 76.4 ms: 1.05x slower                                  |
| xml_etree_generate   | 54.3 ms                                                | 57.1 ms: 1.05x slower                                  |
| unpickle_list        | 2.66 us                                                | 3.14 us: 1.18x slower                                  |
| Geometric mean       | (ref)                                                  | 1.07x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup_no_site | 9.73 ms                                                | 8.50 ms: 1.14x faster                                  |
| python_startup         | 12.6 ms                                                | 11.1 ms: 1.14x faster                                  |
| Geometric mean         | (ref)                                                  | 1.14x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.35 ms: 1.43x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-darwin-arm64-python-main-3.13.0a1+-6c23635 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 92.0 us: 3.74x faster                                  |
| deltablue                | 5.15 ms                                                | 2.34 ms: 2.20x faster                                  |
| raytrace                 | 328 ms                                                 | 173 ms: 1.89x faster                                   |
| logging_silent           | 119 ns                                                 | 67.9 ns: 1.75x faster                                  |
| sqlglot_parse            | 1.33 ms                                                | 794 us: 1.68x faster                                   |
| richards_super           | 60.7 ms                                                | 36.4 ms: 1.67x faster                                  |
| crypto_pyaes             | 78.0 ms                                                | 46.7 ms: 1.67x faster                                  |
| chaos                    | 66.8 ms                                                | 40.1 ms: 1.67x faster                                  |
| scimark_monte_carlo      | 72.2 ms                                                | 44.9 ms: 1.61x faster                                  |
| async_tree_none          | 402 ms                                                 | 251 ms: 1.60x faster                                   |
| go                       | 165 ms                                                 | 103 ms: 1.60x faster                                   |
| sqlglot_transpile        | 1.54 ms                                                | 967 us: 1.59x faster                                   |
| asyncio_tcp              | 673 ms                                                 | 431 ms: 1.56x faster                                   |
| richards                 | 51.4 ms                                                | 33.0 ms: 1.56x faster                                  |
| scimark_lu               | 110 ms                                                 | 70.6 ms: 1.56x faster                                  |
| async_tree_memoization   | 493 ms                                                 | 329 ms: 1.50x faster                                   |
| unpack_sequence          | 38.7 ns                                                | 26.4 ns: 1.47x faster                                  |
| async_tree_io            | 1.02 sec                                               | 698 ms: 1.46x faster                                   |
| pickle_pure_python       | 284 us                                                 | 195 us: 1.45x faster                                   |
| deepcopy_memo            | 34.5 us                                                | 24.0 us: 1.44x faster                                  |
| mako                     | 10.5 ms                                                | 7.35 ms: 1.43x faster                                  |
| hexiom                   | 6.32 ms                                                | 4.59 ms: 1.38x faster                                  |
| generators               | 32.9 ms                                                | 24.0 ms: 1.37x faster                                  |
| spectral_norm            | 96.4 ms                                                | 70.7 ms: 1.36x faster                                  |
| pyflate                  | 453 ms                                                 | 334 ms: 1.36x faster                                   |
| pycparser                | 915 ms                                                 | 691 ms: 1.33x faster                                   |
| nbody                    | 94.1 ms                                                | 71.3 ms: 1.32x faster                                  |
| float                    | 72.3 ms                                                | 55.0 ms: 1.32x faster                                  |
| tornado_http             | 91.9 ms                                                | 70.1 ms: 1.31x faster                                  |
| json_dumps               | 8.38 ms                                                | 6.42 ms: 1.30x faster                                  |
| unpickle_pure_python     | 203 us                                                 | 156 us: 1.30x faster                                   |
| logging_simple           | 4.63 us                                                | 3.57 us: 1.30x faster                                  |
| logging_format           | 5.01 us                                                | 3.87 us: 1.29x faster                                  |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 523 ms: 1.28x faster                                   |
| regex_compile            | 96.6 ms                                                | 75.9 ms: 1.27x faster                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.27x faster                                 |
| deepcopy                 | 278 us                                                 | 220 us: 1.26x faster                                   |
| create_gc_cycles         | 876 us                                                 | 699 us: 1.25x faster                                   |
| scimark_sor              | 127 ms                                                 | 103 ms: 1.22x faster                                   |
| dulwich_log              | 37.1 ms                                                | 30.4 ms: 1.22x faster                                  |
| pprint_pformat           | 1.24 sec                                               | 1.02 sec: 1.22x faster                                 |
| comprehensions           | 17.7 us                                                | 14.6 us: 1.21x faster                                  |
| deepcopy_reduce          | 2.38 us                                                | 1.97 us: 1.21x faster                                  |
| pprint_safe_repr         | 609 ms                                                 | 504 ms: 1.21x faster                                   |
| docutils                 | 1.78 sec                                               | 1.49 sec: 1.19x faster                                 |
| nqueens                  | 68.1 ms                                                | 57.2 ms: 1.19x faster                                  |
| mypy2                    | 308 ms                                                 | 259 ms: 1.19x faster                                   |
| scimark_fft              | 232 ms                                                 | 197 ms: 1.18x faster                                   |
| xml_etree_process        | 45.1 ms                                                | 38.8 ms: 1.16x faster                                  |
| coroutines               | 20.2 ms                                                | 17.5 ms: 1.15x faster                                  |
| bench_thread_pool        | 548 us                                                 | 478 us: 1.15x faster                                   |
| tomli_loads              | 1.76 sec                                               | 1.54 sec: 1.14x faster                                 |
| python_startup_no_site   | 9.73 ms                                                | 8.50 ms: 1.14x faster                                  |
| python_startup           | 12.6 ms                                                | 11.1 ms: 1.14x faster                                  |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.06 ms: 1.13x faster                                  |
| fannkuch                 | 317 ms                                                 | 283 ms: 1.12x faster                                   |
| sqlglot_optimize         | 38.0 ms                                                | 33.8 ms: 1.12x faster                                  |
| sqlglot_normalize        | 197 ms                                                 | 182 ms: 1.08x faster                                   |
| unpickle                 | 9.77 us                                                | 9.12 us: 1.07x faster                                  |
| regex_dna                | 160 ms                                                 | 149 ms: 1.07x faster                                   |
| meteor_contest           | 78.6 ms                                                | 74.0 ms: 1.06x faster                                  |
| regex_v8                 | 17.5 ms                                                | 16.8 ms: 1.04x faster                                  |
| json                     | 3.10 ms                                                | 2.98 ms: 1.04x faster                                  |
| mdp                      | 1.67 sec                                               | 1.61 sec: 1.04x faster                                 |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x slower                                  |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| pickle                   | 7.36 us                                                | 7.41 us: 1.01x slower                                  |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.01x slower                                  |
| pickle_list              | 2.83 us                                                | 2.89 us: 1.02x slower                                  |
| pathlib                  | 28.8 ms                                                | 29.6 ms: 1.03x slower                                  |
| xml_etree_parse          | 107 ms                                                 | 111 ms: 1.03x slower                                   |
| json_loads               | 16.9 us                                                | 17.5 us: 1.04x slower                                  |
| xml_etree_iterparse      | 72.6 ms                                                | 76.4 ms: 1.05x slower                                  |
| xml_etree_generate       | 54.3 ms                                                | 57.1 ms: 1.05x slower                                  |
| regex_effbot             | 2.45 ms                                                | 2.62 ms: 1.07x slower                                  |
| bench_mp_pool            | 41.0 ms                                                | 44.1 ms: 1.08x slower                                  |
| sqlite_synth             | 1.47 us                                                | 1.63 us: 1.11x slower                                  |
| coverage                 | 40.8 ms                                                | 46.8 ms: 1.15x slower                                  |
| unpickle_list            | 2.66 us                                                | 3.14 us: 1.18x slower                                  |
| telco                    | 3.68 ms                                                | 4.65 ms: 1.26x slower                                  |
| async_generators         | 233 ms                                                 | 300 ms: 1.29x slower                                   |
| Geometric mean           | (ref)                                                  | 1.24x faster                                           |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.19x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
