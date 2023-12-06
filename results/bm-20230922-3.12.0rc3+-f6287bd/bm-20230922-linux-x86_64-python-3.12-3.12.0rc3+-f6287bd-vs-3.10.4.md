
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f6287bd
- commit date: 2023-09-22
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 268 ms: 1.25x faster                                    |
| docutils       | 3.17 sec                                               | 2.72 sec: 1.16x faster                                  |
| tornado_http   | 127 ms                                                 | 99.9 ms: 1.28x faster                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 142 ms                                                 | 88.7 ms: 1.60x faster                                   |
| float          | 111 ms                                                 | 80.5 ms: 1.37x faster                                   |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                    |
| Geometric mean | (ref)                                                  | 1.31x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| regex_v8       | 25.0 ms                                                | 22.5 ms: 1.11x faster                                   |
| regex_dna      | 222 ms                                                 | 214 ms: 1.04x faster                                    |
| regex_effbot   | 3.23 ms                                                | 3.66 ms: 1.13x slower                                   |
| Geometric mean | (ref)                                                  | 1.06x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 315 us: 1.45x faster                                    |
| json_dumps           | 13.5 ms                                                | 9.79 ms: 1.38x faster                                   |
| unpickle_pure_python | 300 us                                                 | 219 us: 1.37x faster                                    |
| tomli_loads          | 2.92 sec                                               | 2.19 sec: 1.33x faster                                  |
| xml_etree_process    | 74.9 ms                                                | 59.0 ms: 1.27x faster                                   |
| json_loads           | 28.8 us                                                | 25.0 us: 1.15x faster                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.8 ms: 1.11x faster                                   |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                    |
| xml_etree_parse      | 163 ms                                                 | 153 ms: 1.06x faster                                    |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                   |
| pickle_list          | 4.56 us                                                | 4.65 us: 1.02x slower                                   |
| unpickle             | 14.1 us                                                | 14.9 us: 1.05x slower                                   |
| unpickle_list        | 4.82 us                                                | 5.07 us: 1.05x slower                                   |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.47 ms: 1.49x faster                                   |
| python_startup_no_site | 5.82 ms                                                | 6.90 ms: 1.19x slower                                   |
| Geometric mean         | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.37x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230922-linux-x86_64-python-3.12-3.12.0rc3+-f6287bd |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 148 us: 3.44x faster                                    |
| generators               | 76.8 ms                                                | 30.1 ms: 2.55x faster                                   |
| deltablue                | 7.42 ms                                                | 3.55 ms: 2.09x faster                                   |
| richards_super           | 90.7 ms                                                | 50.0 ms: 1.81x faster                                   |
| asyncio_tcp              | 925 ms                                                 | 533 ms: 1.73x faster                                    |
| richards                 | 74.9 ms                                                | 44.0 ms: 1.70x faster                                   |
| logging_silent           | 175 ns                                                 | 103 ns: 1.70x faster                                    |
| go                       | 229 ms                                                 | 136 ms: 1.68x faster                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                  |
| chaos                    | 106 ms                                                 | 63.8 ms: 1.67x faster                                   |
| nbody                    | 142 ms                                                 | 88.7 ms: 1.60x faster                                   |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.59x faster                                    |
| async_tree_io            | 1.77 sec                                               | 1.14 sec: 1.56x faster                                  |
| raytrace                 | 464 ms                                                 | 298 ms: 1.56x faster                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.33 ms: 1.55x faster                                   |
| async_tree_none          | 717 ms                                                 | 464 ms: 1.55x faster                                    |
| hexiom                   | 9.53 ms                                                | 6.17 ms: 1.54x faster                                   |
| scimark_monte_carlo      | 108 ms                                                 | 70.4 ms: 1.54x faster                                   |
| async_tree_memoization   | 854 ms                                                 | 566 ms: 1.51x faster                                    |
| pyflate                  | 673 ms                                                 | 449 ms: 1.50x faster                                    |
| python_startup           | 14.2 ms                                                | 9.47 ms: 1.49x faster                                   |
| sqlglot_transpile        | 2.45 ms                                                | 1.64 ms: 1.49x faster                                   |
| crypto_pyaes             | 118 ms                                                 | 80.4 ms: 1.47x faster                                   |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.45x faster                                    |
| pickle_pure_python       | 455 us                                                 | 315 us: 1.45x faster                                    |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                   |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                    |
| deepcopy_memo            | 52.3 us                                                | 37.8 us: 1.38x faster                                   |
| json_dumps               | 13.5 ms                                                | 9.79 ms: 1.38x faster                                   |
| unpickle_pure_python     | 300 us                                                 | 219 us: 1.37x faster                                    |
| float                    | 111 ms                                                 | 80.5 ms: 1.37x faster                                   |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.37x faster                                   |
| unpack_sequence          | 64.7 ns                                                | 47.9 ns: 1.35x faster                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 709 ms: 1.34x faster                                    |
| tomli_loads              | 2.92 sec                                               | 2.19 sec: 1.33x faster                                  |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.32x faster                                  |
| comprehensions           | 26.8 us                                                | 20.4 us: 1.31x faster                                   |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                  |
| pprint_safe_repr         | 955 ms                                                 | 741 ms: 1.29x faster                                    |
| logging_simple           | 8.07 us                                                | 6.29 us: 1.28x faster                                   |
| fannkuch                 | 486 ms                                                 | 379 ms: 1.28x faster                                    |
| tornado_http             | 127 ms                                                 | 99.9 ms: 1.28x faster                                   |
| logging_format           | 8.91 us                                                | 7.01 us: 1.27x faster                                   |
| xml_etree_process        | 74.9 ms                                                | 59.0 ms: 1.27x faster                                   |
| 2to3                     | 336 ms                                                 | 268 ms: 1.25x faster                                    |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                    |
| mypy2                    | 428 ms                                                 | 344 ms: 1.24x faster                                    |
| deepcopy                 | 442 us                                                 | 356 us: 1.24x faster                                    |
| nqueens                  | 100 ms                                                 | 80.9 ms: 1.24x faster                                   |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.5 ms: 1.22x faster                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.21x faster                                   |
| docutils                 | 3.17 sec                                               | 2.72 sec: 1.16x faster                                  |
| dask                     | 423 ms                                                 | 365 ms: 1.16x faster                                    |
| scimark_fft              | 424 ms                                                 | 366 ms: 1.16x faster                                    |
| json_loads               | 28.8 us                                                | 25.0 us: 1.15x faster                                   |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.4 ms: 1.15x faster                                   |
| sqlalchemy_declarative   | 165 ms                                                 | 145 ms: 1.14x faster                                    |
| bench_thread_pool        | 947 us                                                 | 831 us: 1.14x faster                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.82 ms: 1.13x faster                                   |
| json                     | 5.42 ms                                                | 4.80 ms: 1.13x faster                                   |
| dulwich_log              | 75.9 ms                                                | 68.1 ms: 1.11x faster                                   |
| regex_v8                 | 25.0 ms                                                | 22.5 ms: 1.11x faster                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.50 ms: 1.11x faster                                   |
| xml_etree_generate       | 94.2 ms                                                | 84.8 ms: 1.11x faster                                   |
| mdp                      | 2.82 sec                                               | 2.56 sec: 1.10x faster                                  |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                    |
| pathlib                  | 20.0 ms                                                | 18.5 ms: 1.08x faster                                   |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.08x faster                                    |
| xml_etree_parse          | 163 ms                                                 | 153 ms: 1.06x faster                                    |
| sqlite_synth             | 2.93 us                                                | 2.76 us: 1.06x faster                                   |
| regex_dna                | 222 ms                                                 | 214 ms: 1.04x faster                                    |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                    |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                   |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                   |
| pickle_list              | 4.56 us                                                | 4.65 us: 1.02x slower                                   |
| async_generators         | 425 ms                                                 | 441 ms: 1.04x slower                                    |
| telco                    | 6.54 ms                                                | 6.88 ms: 1.05x slower                                   |
| unpickle                 | 14.1 us                                                | 14.9 us: 1.05x slower                                   |
| unpickle_list            | 4.82 us                                                | 5.07 us: 1.05x slower                                   |
| gc_traversal             | 3.84 ms                                                | 4.09 ms: 1.06x slower                                   |
| regex_effbot             | 3.23 ms                                                | 3.66 ms: 1.13x slower                                   |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.90 ms: 1.19x slower                                   |
| coverage                 | 72.8 ms                                                | 95.8 ms: 1.32x slower                                   |
| Geometric mean           | (ref)                                                  | 1.28x faster                                            |
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.22x
