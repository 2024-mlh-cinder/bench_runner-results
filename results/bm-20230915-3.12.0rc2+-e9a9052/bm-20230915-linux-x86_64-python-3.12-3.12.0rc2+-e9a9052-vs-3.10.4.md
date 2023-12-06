
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: e9a9052
- commit date: 2023-09-15
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.22x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 269 ms: 1.25x faster                                    |
| docutils       | 3.17 sec                                               | 2.71 sec: 1.17x faster                                  |
| tornado_http   | 127 ms                                                 | 99.6 ms: 1.28x faster                                   |
| Geometric mean | (ref)                                                  | 1.23x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 142 ms                                                 | 89.8 ms: 1.58x faster                                   |
| float          | 111 ms                                                 | 80.0 ms: 1.38x faster                                   |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                    |
| Geometric mean | (ref)                                                  | 1.30x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 143 ms: 1.23x faster                                    |
| regex_v8       | 25.0 ms                                                | 22.9 ms: 1.09x faster                                   |
| regex_dna      | 222 ms                                                 | 214 ms: 1.04x faster                                    |
| regex_effbot   | 3.23 ms                                                | 3.72 ms: 1.15x slower                                   |
| Geometric mean | (ref)                                                  | 1.05x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 314 us: 1.45x faster                                    |
| unpickle_pure_python | 300 us                                                 | 218 us: 1.38x faster                                    |
| json_dumps           | 13.5 ms                                                | 9.82 ms: 1.38x faster                                   |
| tomli_loads          | 2.92 sec                                               | 2.19 sec: 1.34x faster                                  |
| xml_etree_process    | 74.9 ms                                                | 58.7 ms: 1.28x faster                                   |
| json_loads           | 28.8 us                                                | 25.0 us: 1.15x faster                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.4 ms: 1.12x faster                                   |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                    |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| pickle_list          | 4.56 us                                                | 4.52 us: 1.01x faster                                   |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                   |
| unpickle             | 14.1 us                                                | 15.3 us: 1.08x slower                                   |
| unpickle_list        | 4.82 us                                                | 5.40 us: 1.12x slower                                   |
| pickle_dict          | 27.3 us                                                | 31.4 us: 1.15x slower                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.46 ms: 1.50x faster                                   |
| python_startup_no_site | 5.82 ms                                                | 6.88 ms: 1.18x slower                                   |
| Geometric mean         | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.9 ms: 1.35x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-python-3.12-3.12.0rc2+-e9a9052 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 148 us: 3.45x faster                                    |
| generators               | 76.8 ms                                                | 32.3 ms: 2.38x faster                                   |
| deltablue                | 7.42 ms                                                | 3.57 ms: 2.08x faster                                   |
| richards_super           | 90.7 ms                                                | 50.3 ms: 1.80x faster                                   |
| asyncio_tcp              | 925 ms                                                 | 524 ms: 1.77x faster                                    |
| logging_silent           | 175 ns                                                 | 103 ns: 1.70x faster                                    |
| richards                 | 74.9 ms                                                | 44.1 ms: 1.70x faster                                   |
| go                       | 229 ms                                                 | 136 ms: 1.69x faster                                    |
| chaos                    | 106 ms                                                 | 63.5 ms: 1.67x faster                                   |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                  |
| scimark_sor              | 197 ms                                                 | 122 ms: 1.61x faster                                    |
| nbody                    | 142 ms                                                 | 89.8 ms: 1.58x faster                                   |
| hexiom                   | 9.53 ms                                                | 6.11 ms: 1.56x faster                                   |
| raytrace                 | 464 ms                                                 | 299 ms: 1.55x faster                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.33 ms: 1.55x faster                                   |
| async_tree_io            | 1.77 sec                                               | 1.15 sec: 1.54x faster                                  |
| crypto_pyaes             | 118 ms                                                 | 77.4 ms: 1.53x faster                                   |
| async_tree_none          | 717 ms                                                 | 469 ms: 1.53x faster                                    |
| scimark_monte_carlo      | 108 ms                                                 | 70.9 ms: 1.53x faster                                   |
| python_startup           | 14.2 ms                                                | 9.46 ms: 1.50x faster                                   |
| async_tree_memoization   | 854 ms                                                 | 572 ms: 1.49x faster                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.64 ms: 1.49x faster                                   |
| scimark_lu               | 163 ms                                                 | 112 ms: 1.45x faster                                    |
| pickle_pure_python       | 455 us                                                 | 314 us: 1.45x faster                                    |
| pyflate                  | 673 ms                                                 | 466 ms: 1.44x faster                                    |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.44x faster                                   |
| spectral_norm            | 150 ms                                                 | 104 ms: 1.44x faster                                    |
| float                    | 111 ms                                                 | 80.0 ms: 1.38x faster                                   |
| deepcopy_memo            | 52.3 us                                                | 37.9 us: 1.38x faster                                   |
| unpickle_pure_python     | 300 us                                                 | 218 us: 1.38x faster                                    |
| json_dumps               | 13.5 ms                                                | 9.82 ms: 1.38x faster                                   |
| mako                     | 14.8 ms                                                | 10.9 ms: 1.35x faster                                   |
| tomli_loads              | 2.92 sec                                               | 2.19 sec: 1.34x faster                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 714 ms: 1.33x faster                                    |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.32x faster                                  |
| pprint_safe_repr         | 955 ms                                                 | 737 ms: 1.30x faster                                    |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.29x faster                                  |
| unpack_sequence          | 64.7 ns                                                | 50.3 ns: 1.29x faster                                   |
| comprehensions           | 26.8 us                                                | 20.9 us: 1.29x faster                                   |
| tornado_http             | 127 ms                                                 | 99.6 ms: 1.28x faster                                   |
| xml_etree_process        | 74.9 ms                                                | 58.7 ms: 1.28x faster                                   |
| logging_simple           | 8.07 us                                                | 6.38 us: 1.27x faster                                   |
| logging_format           | 8.91 us                                                | 7.11 us: 1.25x faster                                   |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                    |
| 2to3                     | 336 ms                                                 | 269 ms: 1.25x faster                                    |
| nqueens                  | 100 ms                                                 | 80.2 ms: 1.25x faster                                   |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                    |
| mypy2                    | 428 ms                                                 | 345 ms: 1.24x faster                                    |
| regex_compile            | 177 ms                                                 | 143 ms: 1.23x faster                                    |
| fannkuch                 | 486 ms                                                 | 395 ms: 1.23x faster                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.2 ms: 1.23x faster                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.21x faster                                   |
| scimark_fft              | 424 ms                                                 | 360 ms: 1.18x faster                                    |
| docutils                 | 3.17 sec                                               | 2.71 sec: 1.17x faster                                  |
| json_loads               | 28.8 us                                                | 25.0 us: 1.15x faster                                   |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.5 ms: 1.14x faster                                   |
| sqlalchemy_declarative   | 165 ms                                                 | 145 ms: 1.14x faster                                    |
| bench_thread_pool        | 947 us                                                 | 833 us: 1.14x faster                                    |
| json                     | 5.42 ms                                                | 4.81 ms: 1.13x faster                                   |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.84 ms: 1.13x faster                                   |
| dulwich_log              | 75.9 ms                                                | 67.8 ms: 1.12x faster                                   |
| xml_etree_generate       | 94.2 ms                                                | 84.4 ms: 1.12x faster                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.10x faster                                   |
| regex_v8                 | 25.0 ms                                                | 22.9 ms: 1.09x faster                                   |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                    |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.07x faster                                    |
| pathlib                  | 20.0 ms                                                | 18.8 ms: 1.07x faster                                   |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| mdp                      | 2.82 sec                                               | 2.68 sec: 1.05x faster                                  |
| sqlite_synth             | 2.93 us                                                | 2.79 us: 1.05x faster                                   |
| regex_dna                | 222 ms                                                 | 214 ms: 1.04x faster                                    |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                    |
| pickle_list              | 4.56 us                                                | 4.52 us: 1.01x faster                                   |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                   |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                   |
| gc_traversal             | 3.84 ms                                                | 3.96 ms: 1.03x slower                                   |
| telco                    | 6.54 ms                                                | 6.82 ms: 1.04x slower                                   |
| async_generators         | 425 ms                                                 | 445 ms: 1.05x slower                                    |
| unpickle                 | 14.1 us                                                | 15.3 us: 1.08x slower                                   |
| unpickle_list            | 4.82 us                                                | 5.40 us: 1.12x slower                                   |
| regex_effbot             | 3.23 ms                                                | 3.72 ms: 1.15x slower                                   |
| pickle_dict              | 27.3 us                                                | 31.4 us: 1.15x slower                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.88 ms: 1.18x slower                                   |
| dask                     | 423 ms                                                 | 535 ms: 1.27x slower                                    |
| coverage                 | 72.8 ms                                                | 94.6 ms: 1.30x slower                                   |
| Geometric mean           | (ref)                                                  | 1.27x faster                                            |
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.22x
