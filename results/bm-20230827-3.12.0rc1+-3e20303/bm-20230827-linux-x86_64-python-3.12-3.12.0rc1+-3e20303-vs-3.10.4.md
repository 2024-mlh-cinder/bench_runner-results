
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 3e20303
- commit date: 2023-08-27
- overall geometric mean: 1.28x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| 2to3           | 336 ms                                                 | 268 ms: 1.25x faster                                    |
| docutils       | 3.17 sec                                               | 2.71 sec: 1.17x faster                                  |
| tornado_http   | 127 ms                                                 | 102 ms: 1.25x faster                                    |
| Geometric mean | (ref)                                                  | 1.23x faster                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.3 ms: 1.57x faster                                   |
| float          | 111 ms                                                 | 81.2 ms: 1.36x faster                                   |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                    |
| Geometric mean | (ref)                                                  | 1.29x faster                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| regex_v8       | 25.0 ms                                                | 22.4 ms: 1.12x faster                                   |
| regex_dna      | 222 ms                                                 | 210 ms: 1.05x faster                                    |
| regex_effbot   | 3.23 ms                                                | 3.56 ms: 1.10x slower                                   |
| Geometric mean | (ref)                                                  | 1.07x faster                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 311 us: 1.46x faster                                    |
| json_dumps           | 13.5 ms                                                | 9.64 ms: 1.40x faster                                   |
| unpickle_pure_python | 300 us                                                 | 218 us: 1.38x faster                                    |
| tomli_loads          | 2.92 sec                                               | 2.25 sec: 1.30x faster                                  |
| xml_etree_process    | 74.9 ms                                                | 58.9 ms: 1.27x faster                                   |
| json_loads           | 28.8 us                                                | 24.9 us: 1.16x faster                                   |
| xml_etree_generate   | 94.2 ms                                                | 85.2 ms: 1.11x faster                                   |
| xml_etree_iterparse  | 111 ms                                                 | 103 ms: 1.08x faster                                    |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| pickle_list          | 4.56 us                                                | 4.66 us: 1.02x slower                                   |
| unpickle_list        | 4.82 us                                                | 5.00 us: 1.04x slower                                   |
| unpickle             | 14.1 us                                                | 14.7 us: 1.04x slower                                   |
| pickle               | 10.3 us                                                | 10.7 us: 1.04x slower                                   |
| pickle_dict          | 27.3 us                                                | 32.8 us: 1.20x slower                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 9.31 ms: 1.52x faster                                   |
| python_startup_no_site | 5.82 ms                                                | 6.77 ms: 1.16x slower                                   |
| Geometric mean         | (ref)                                                  | 1.14x faster                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.8 ms: 1.37x faster                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230827-linux-x86_64-python-3.12-3.12.0rc1+-3e20303 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 144 us: 3.55x faster                                    |
| generators               | 76.8 ms                                                | 30.3 ms: 2.54x faster                                   |
| deltablue                | 7.42 ms                                                | 3.55 ms: 2.09x faster                                   |
| asyncio_tcp              | 925 ms                                                 | 504 ms: 1.84x faster                                    |
| richards_super           | 90.7 ms                                                | 49.7 ms: 1.82x faster                                   |
| richards                 | 74.9 ms                                                | 43.7 ms: 1.71x faster                                   |
| logging_silent           | 175 ns                                                 | 103 ns: 1.69x faster                                    |
| chaos                    | 106 ms                                                 | 63.3 ms: 1.68x faster                                   |
| go                       | 229 ms                                                 | 137 ms: 1.68x faster                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                  |
| scimark_sor              | 197 ms                                                 | 124 ms: 1.58x faster                                    |
| raytrace                 | 464 ms                                                 | 295 ms: 1.57x faster                                    |
| nbody                    | 142 ms                                                 | 90.3 ms: 1.57x faster                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.33 ms: 1.55x faster                                   |
| hexiom                   | 9.53 ms                                                | 6.23 ms: 1.53x faster                                   |
| python_startup           | 14.2 ms                                                | 9.31 ms: 1.52x faster                                   |
| async_tree_io            | 1.77 sec                                               | 1.17 sec: 1.52x faster                                  |
| crypto_pyaes             | 118 ms                                                 | 78.0 ms: 1.52x faster                                   |
| async_tree_none          | 717 ms                                                 | 473 ms: 1.51x faster                                    |
| scimark_monte_carlo      | 108 ms                                                 | 71.5 ms: 1.51x faster                                   |
| pyflate                  | 673 ms                                                 | 450 ms: 1.49x faster                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.65 ms: 1.48x faster                                   |
| async_tree_memoization   | 854 ms                                                 | 577 ms: 1.48x faster                                    |
| pickle_pure_python       | 455 us                                                 | 311 us: 1.46x faster                                    |
| scimark_lu               | 163 ms                                                 | 113 ms: 1.45x faster                                    |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.45x faster                                   |
| spectral_norm            | 150 ms                                                 | 105 ms: 1.43x faster                                    |
| json_dumps               | 13.5 ms                                                | 9.64 ms: 1.40x faster                                   |
| deepcopy_memo            | 52.3 us                                                | 37.9 us: 1.38x faster                                   |
| unpickle_pure_python     | 300 us                                                 | 218 us: 1.38x faster                                    |
| mako                     | 14.8 ms                                                | 10.8 ms: 1.37x faster                                   |
| float                    | 111 ms                                                 | 81.2 ms: 1.36x faster                                   |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 712 ms: 1.34x faster                                    |
| pprint_pformat           | 1.99 sec                                               | 1.49 sec: 1.33x faster                                  |
| pycparser                | 1.50 sec                                               | 1.15 sec: 1.30x faster                                  |
| comprehensions           | 26.8 us                                                | 20.6 us: 1.30x faster                                   |
| tomli_loads              | 2.92 sec                                               | 2.25 sec: 1.30x faster                                  |
| pprint_safe_repr         | 955 ms                                                 | 736 ms: 1.30x faster                                    |
| logging_simple           | 8.07 us                                                | 6.25 us: 1.29x faster                                   |
| logging_format           | 8.91 us                                                | 7.00 us: 1.27x faster                                   |
| xml_etree_process        | 74.9 ms                                                | 58.9 ms: 1.27x faster                                   |
| 2to3                     | 336 ms                                                 | 268 ms: 1.25x faster                                    |
| tornado_http             | 127 ms                                                 | 102 ms: 1.25x faster                                    |
| mypy2                    | 428 ms                                                 | 344 ms: 1.24x faster                                    |
| sqlglot_normalize        | 135 ms                                                 | 109 ms: 1.24x faster                                    |
| deepcopy                 | 442 us                                                 | 357 us: 1.24x faster                                    |
| fannkuch                 | 486 ms                                                 | 394 ms: 1.23x faster                                    |
| regex_compile            | 177 ms                                                 | 144 ms: 1.23x faster                                    |
| nqueens                  | 100 ms                                                 | 81.5 ms: 1.23x faster                                   |
| unpack_sequence          | 64.7 ns                                                | 52.9 ns: 1.22x faster                                   |
| sqlglot_optimize         | 65.3 ms                                                | 53.9 ms: 1.21x faster                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                   |
| scimark_fft              | 424 ms                                                 | 358 ms: 1.18x faster                                    |
| docutils                 | 3.17 sec                                               | 2.71 sec: 1.17x faster                                  |
| json_loads               | 28.8 us                                                | 24.9 us: 1.16x faster                                   |
| sqlalchemy_imperative    | 21.2 ms                                                | 18.4 ms: 1.15x faster                                   |
| sqlalchemy_declarative   | 165 ms                                                 | 144 ms: 1.14x faster                                    |
| json                     | 5.42 ms                                                | 4.74 ms: 1.14x faster                                   |
| bench_thread_pool        | 947 us                                                 | 832 us: 1.14x faster                                    |
| dulwich_log              | 75.9 ms                                                | 67.6 ms: 1.12x faster                                   |
| regex_v8                 | 25.0 ms                                                | 22.4 ms: 1.12x faster                                   |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.93 ms: 1.11x faster                                   |
| xml_etree_generate       | 94.2 ms                                                | 85.2 ms: 1.11x faster                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.10x faster                                   |
| pathlib                  | 20.0 ms                                                | 18.2 ms: 1.10x faster                                   |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.10x faster                                    |
| sqlite_synth             | 2.93 us                                                | 2.71 us: 1.08x faster                                   |
| xml_etree_iterparse      | 111 ms                                                 | 103 ms: 1.08x faster                                    |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                    |
| regex_dna                | 222 ms                                                 | 210 ms: 1.05x faster                                    |
| mdp                      | 2.82 sec                                               | 2.70 sec: 1.05x faster                                  |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                    |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                   |
| gc_traversal             | 3.84 ms                                                | 3.91 ms: 1.02x slower                                   |
| pickle_list              | 4.56 us                                                | 4.66 us: 1.02x slower                                   |
| telco                    | 6.54 ms                                                | 6.79 ms: 1.04x slower                                   |
| unpickle_list            | 4.82 us                                                | 5.00 us: 1.04x slower                                   |
| unpickle                 | 14.1 us                                                | 14.7 us: 1.04x slower                                   |
| pickle                   | 10.3 us                                                | 10.7 us: 1.04x slower                                   |
| async_generators         | 425 ms                                                 | 449 ms: 1.06x slower                                    |
| regex_effbot             | 3.23 ms                                                | 3.56 ms: 1.10x slower                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.77 ms: 1.16x slower                                   |
| pickle_dict              | 27.3 us                                                | 32.8 us: 1.20x slower                                   |
| dask                     | 423 ms                                                 | 537 ms: 1.27x slower                                    |
| coverage                 | 72.8 ms                                                | 94.6 ms: 1.30x slower                                   |
| Geometric mean           | (ref)                                                  | 1.28x faster                                            |
Ignored benchmarks (15) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.24x
- 95% likely to have a speedup of 1.23x
- 99% likely to have a speedup of 1.21x
