
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: dcaacd9
- commit date: 2023-09-03
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 268 ms: 1.26x faster                                    |
| docutils       | 3.17 sec                                               | 2.72 sec: 1.17x faster                                  |
| tornado_http   | 127 ms                                                 | 99.5 ms: 1.28x faster                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 142 ms                                                 | 89.5 ms: 1.58x faster                                   |
| float          | 111 ms                                                 | 78.6 ms: 1.41x faster                                   |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                    |
| Geometric mean | (ref)                                                  | 1.31x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 142 ms: 1.24x faster                                    |
| regex_v8       | 25.0 ms                                                | 22.7 ms: 1.10x faster                                   |
| regex_dna      | 222 ms                                                 | 210 ms: 1.06x faster                                    |
| regex_effbot   | 3.23 ms                                                | 3.61 ms: 1.12x slower                                   |
| Geometric mean | (ref)                                                  | 1.07x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 307 us: 1.48x faster                                    |
| unpickle_pure_python | 300 us                                                 | 216 us: 1.39x faster                                    |
| json_dumps           | 13.5 ms                                                | 9.85 ms: 1.37x faster                                   |
| tomli_loads          | 2.92 sec                                               | 2.17 sec: 1.34x faster                                  |
| xml_etree_process    | 74.9 ms                                                | 58.6 ms: 1.28x faster                                   |
| json_loads           | 28.8 us                                                | 25.2 us: 1.15x faster                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.4 ms: 1.12x faster                                   |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                    |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| pickle_list          | 4.56 us                                                | 4.74 us: 1.04x slower                                   |
| unpickle             | 14.1 us                                                | 14.8 us: 1.05x slower                                   |
| pickle               | 10.3 us                                                | 11.0 us: 1.06x slower                                   |
| unpickle_list        | 4.82 us                                                | 5.18 us: 1.08x slower                                   |
| pickle_dict          | 27.3 us                                                | 32.7 us: 1.20x slower                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.44 ms: 1.50x faster                                   |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                   |
| Geometric mean         | (ref)                                                  | 1.13x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.7 ms: 1.38x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230903-linux-x86_64-python-3.12-3.12.0rc1+-dcaacd9 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 144 us: 3.55x faster                                    |
| generators               | 76.8 ms                                                | 32.0 ms: 2.40x faster                                   |
| deltablue                | 7.42 ms                                                | 3.49 ms: 2.12x faster                                   |
| richards_super           | 90.7 ms                                                | 50.1 ms: 1.81x faster                                   |
| asyncio_tcp              | 925 ms                                                 | 516 ms: 1.79x faster                                    |
| logging_silent           | 175 ns                                                 | 100 ns: 1.75x faster                                    |
| richards                 | 74.9 ms                                                | 44.0 ms: 1.70x faster                                   |
| go                       | 229 ms                                                 | 136 ms: 1.69x faster                                    |
| chaos                    | 106 ms                                                 | 63.1 ms: 1.68x faster                                   |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                  |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.61x faster                                    |
| raytrace                 | 464 ms                                                 | 291 ms: 1.59x faster                                    |
| nbody                    | 142 ms                                                 | 89.5 ms: 1.58x faster                                   |
| hexiom                   | 9.53 ms                                                | 6.10 ms: 1.56x faster                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.32 ms: 1.55x faster                                   |
| async_tree_none          | 717 ms                                                 | 468 ms: 1.53x faster                                    |
| async_tree_io            | 1.77 sec                                               | 1.16 sec: 1.53x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 70.9 ms: 1.53x faster                                   |
| crypto_pyaes             | 118 ms                                                 | 78.6 ms: 1.51x faster                                   |
| python_startup           | 14.2 ms                                                | 9.44 ms: 1.50x faster                                   |
| sqlglot_transpile        | 2.45 ms                                                | 1.64 ms: 1.50x faster                                   |
| async_tree_memoization   | 854 ms                                                 | 573 ms: 1.49x faster                                    |
| pickle_pure_python       | 455 us                                                 | 307 us: 1.48x faster                                    |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.46x faster                                    |
| pyflate                  | 673 ms                                                 | 464 ms: 1.45x faster                                    |
| coroutines               | 31.8 ms                                                | 22.1 ms: 1.44x faster                                   |
| deepcopy_memo            | 52.3 us                                                | 37.1 us: 1.41x faster                                   |
| float                    | 111 ms                                                 | 78.6 ms: 1.41x faster                                   |
| spectral_norm            | 150 ms                                                 | 107 ms: 1.40x faster                                    |
| unpickle_pure_python     | 300 us                                                 | 216 us: 1.39x faster                                    |
| mako                     | 14.8 ms                                                | 10.7 ms: 1.38x faster                                   |
| json_dumps               | 13.5 ms                                                | 9.85 ms: 1.37x faster                                   |
| tomli_loads              | 2.92 sec                                               | 2.17 sec: 1.34x faster                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 708 ms: 1.34x faster                                    |
| pprint_pformat           | 1.99 sec                                               | 1.49 sec: 1.33x faster                                  |
| logging_simple           | 8.07 us                                                | 6.17 us: 1.31x faster                                   |
| pprint_safe_repr         | 955 ms                                                 | 730 ms: 1.31x faster                                    |
| comprehensions           | 26.8 us                                                | 20.5 us: 1.31x faster                                   |
| unpack_sequence          | 64.7 ns                                                | 49.7 ns: 1.30x faster                                   |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.30x faster                                  |
| logging_format           | 8.91 us                                                | 6.88 us: 1.30x faster                                   |
| tornado_http             | 127 ms                                                 | 99.5 ms: 1.28x faster                                   |
| xml_etree_process        | 74.9 ms                                                | 58.6 ms: 1.28x faster                                   |
| deepcopy                 | 442 us                                                 | 348 us: 1.27x faster                                    |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                    |
| 2to3                     | 336 ms                                                 | 268 ms: 1.26x faster                                    |
| mypy2                    | 428 ms                                                 | 343 ms: 1.25x faster                                    |
| regex_compile            | 177 ms                                                 | 142 ms: 1.24x faster                                    |
| fannkuch                 | 486 ms                                                 | 393 ms: 1.24x faster                                    |
| deepcopy_reduce          | 3.82 us                                                | 3.11 us: 1.23x faster                                   |
| sqlglot_optimize         | 65.3 ms                                                | 53.3 ms: 1.23x faster                                   |
| nqueens                  | 100 ms                                                 | 82.7 ms: 1.21x faster                                   |
| docutils                 | 3.17 sec                                               | 2.72 sec: 1.17x faster                                  |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.3 ms: 1.15x faster                                   |
| sqlalchemy_declarative   | 165 ms                                                 | 144 ms: 1.15x faster                                    |
| json_loads               | 28.8 us                                                | 25.2 us: 1.15x faster                                   |
| bench_thread_pool        | 947 us                                                 | 829 us: 1.14x faster                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.77 ms: 1.14x faster                                   |
| scimark_fft              | 424 ms                                                 | 372 ms: 1.14x faster                                    |
| create_gc_cycles         | 1.67 ms                                                | 1.48 ms: 1.13x faster                                   |
| json                     | 5.42 ms                                                | 4.83 ms: 1.12x faster                                   |
| xml_etree_generate       | 94.2 ms                                                | 84.4 ms: 1.12x faster                                   |
| dulwich_log              | 75.9 ms                                                | 68.1 ms: 1.11x faster                                   |
| pathlib                  | 20.0 ms                                                | 18.1 ms: 1.11x faster                                   |
| regex_v8                 | 25.0 ms                                                | 22.7 ms: 1.10x faster                                   |
| mdp                      | 2.82 sec                                               | 2.56 sec: 1.10x faster                                  |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                    |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.08x faster                                    |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| sqlite_synth             | 2.93 us                                                | 2.77 us: 1.06x faster                                   |
| regex_dna                | 222 ms                                                 | 210 ms: 1.06x faster                                    |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                    |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                   |
| gc_traversal             | 3.84 ms                                                | 3.85 ms: 1.00x slower                                   |
| pickle_list              | 4.56 us                                                | 4.74 us: 1.04x slower                                   |
| unpickle                 | 14.1 us                                                | 14.8 us: 1.05x slower                                   |
| telco                    | 6.54 ms                                                | 6.91 ms: 1.06x slower                                   |
| async_generators         | 425 ms                                                 | 450 ms: 1.06x slower                                    |
| pickle                   | 10.3 us                                                | 11.0 us: 1.06x slower                                   |
| unpickle_list            | 4.82 us                                                | 5.18 us: 1.08x slower                                   |
| regex_effbot             | 3.23 ms                                                | 3.61 ms: 1.12x slower                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                   |
| pickle_dict              | 27.3 us                                                | 32.7 us: 1.20x slower                                   |
| dask                     | 423 ms                                                 | 533 ms: 1.26x slower                                    |
| coverage                 | 72.8 ms                                                | 94.8 ms: 1.30x slower                                   |
| Geometric mean           | (ref)                                                  | 1.28x faster                                            |
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
