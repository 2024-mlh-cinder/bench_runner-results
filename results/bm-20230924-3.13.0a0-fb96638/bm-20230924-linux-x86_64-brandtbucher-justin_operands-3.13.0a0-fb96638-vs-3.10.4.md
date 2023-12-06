
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_operands
- machine: linux-x86_64
- commit hash: fb96638
- commit date: 2023-09-24
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.19x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.71 sec: 1.17x faster                                                 |
| tornado_http   | 127 ms                                                 | 97.1 ms: 1.31x faster                                                  |
| Geometric mean | (ref)                                                  | 1.24x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 97.5 ms: 1.45x faster                                                  |
| float          | 111 ms                                                 | 83.1 ms: 1.33x faster                                                  |
| pidigits       | 190 ms                                                 | 189 ms: 1.01x faster                                                   |
| Geometric mean | (ref)                                                  | 1.25x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 145 ms: 1.22x faster                                                   |
| regex_dna      | 222 ms                                                 | 206 ms: 1.08x faster                                                   |
| regex_v8       | 25.0 ms                                                | 23.6 ms: 1.06x faster                                                  |
| regex_effbot   | 3.23 ms                                                | 3.54 ms: 1.10x slower                                                  |
| Geometric mean | (ref)                                                  | 1.06x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 300 us: 1.52x faster                                                   |
| tomli_loads          | 2.92 sec                                               | 2.12 sec: 1.38x faster                                                 |
| json_dumps           | 13.5 ms                                                | 9.93 ms: 1.36x faster                                                  |
| unpickle_pure_python | 300 us                                                 | 230 us: 1.31x faster                                                   |
| xml_etree_process    | 74.9 ms                                                | 57.6 ms: 1.30x faster                                                  |
| json_loads           | 28.8 us                                                | 25.5 us: 1.13x faster                                                  |
| xml_etree_generate   | 94.2 ms                                                | 83.7 ms: 1.13x faster                                                  |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.08x faster                                                   |
| pickle               | 10.3 us                                                | 10.1 us: 1.02x faster                                                  |
| pickle_list          | 4.56 us                                                | 4.64 us: 1.02x slower                                                  |
| unpickle_list        | 4.82 us                                                | 4.91 us: 1.02x slower                                                  |
| unpickle             | 14.1 us                                                | 14.5 us: 1.03x slower                                                  |
| pickle_dict          | 27.3 us                                                | 30.7 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                  |
| python_startup_no_site | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.0 ms: 1.34x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230924-linux-x86_64-brandtbucher-justin_operands-3.13.0a0-fb96638 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 146 us: 3.50x faster                                                   |
| generators               | 76.8 ms                                                | 29.0 ms: 2.65x faster                                                  |
| deltablue                | 7.42 ms                                                | 3.45 ms: 2.15x faster                                                  |
| asyncio_tcp              | 925 ms                                                 | 502 ms: 1.84x faster                                                   |
| raytrace                 | 464 ms                                                 | 276 ms: 1.68x faster                                                   |
| richards_super           | 90.7 ms                                                | 54.4 ms: 1.67x faster                                                  |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.81 sec: 1.66x faster                                                 |
| logging_silent           | 175 ns                                                 | 105 ns: 1.66x faster                                                   |
| crypto_pyaes             | 118 ms                                                 | 71.5 ms: 1.66x faster                                                  |
| async_tree_none          | 717 ms                                                 | 443 ms: 1.62x faster                                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.61x faster                                                  |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.60x faster                                                   |
| chaos                    | 106 ms                                                 | 66.6 ms: 1.60x faster                                                  |
| go                       | 229 ms                                                 | 146 ms: 1.57x faster                                                   |
| richards                 | 74.9 ms                                                | 48.0 ms: 1.56x faster                                                  |
| scimark_monte_carlo      | 108 ms                                                 | 69.8 ms: 1.55x faster                                                  |
| sqlglot_transpile        | 2.45 ms                                                | 1.61 ms: 1.52x faster                                                  |
| pickle_pure_python       | 455 us                                                 | 300 us: 1.52x faster                                                   |
| async_tree_memoization   | 854 ms                                                 | 569 ms: 1.50x faster                                                   |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                                 |
| pyflate                  | 673 ms                                                 | 461 ms: 1.46x faster                                                   |
| nbody                    | 142 ms                                                 | 97.5 ms: 1.45x faster                                                  |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                                   |
| coroutines               | 31.8 ms                                                | 22.7 ms: 1.40x faster                                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                                  |
| spectral_norm            | 150 ms                                                 | 108 ms: 1.39x faster                                                   |
| hexiom                   | 9.53 ms                                                | 6.89 ms: 1.38x faster                                                  |
| tomli_loads              | 2.92 sec                                               | 2.12 sec: 1.38x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.93 ms: 1.36x faster                                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 706 ms: 1.35x faster                                                   |
| mako                     | 14.8 ms                                                | 11.0 ms: 1.34x faster                                                  |
| deepcopy_memo            | 52.3 us                                                | 39.2 us: 1.33x faster                                                  |
| float                    | 111 ms                                                 | 83.1 ms: 1.33x faster                                                  |
| logging_simple           | 8.07 us                                                | 6.09 us: 1.33x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 49.0 ns: 1.32x faster                                                  |
| tornado_http             | 127 ms                                                 | 97.1 ms: 1.31x faster                                                  |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 230 us: 1.31x faster                                                   |
| logging_format           | 8.91 us                                                | 6.85 us: 1.30x faster                                                  |
| xml_etree_process        | 74.9 ms                                                | 57.6 ms: 1.30x faster                                                  |
| pprint_safe_repr         | 955 ms                                                 | 748 ms: 1.28x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.26x faster                                                   |
| pycparser                | 1.50 sec                                               | 1.20 sec: 1.25x faster                                                 |
| deepcopy                 | 442 us                                                 | 357 us: 1.24x faster                                                   |
| mypy2                    | 428 ms                                                 | 351 ms: 1.22x faster                                                   |
| regex_compile            | 177 ms                                                 | 145 ms: 1.22x faster                                                   |
| sqlglot_optimize         | 65.3 ms                                                | 54.3 ms: 1.20x faster                                                  |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                                  |
| fannkuch                 | 486 ms                                                 | 408 ms: 1.19x faster                                                   |
| scimark_fft              | 424 ms                                                 | 358 ms: 1.18x faster                                                   |
| docutils                 | 3.17 sec                                               | 2.71 sec: 1.17x faster                                                 |
| comprehensions           | 26.8 us                                                | 23.1 us: 1.16x faster                                                  |
| bench_thread_pool        | 947 us                                                 | 834 us: 1.14x faster                                                   |
| json_loads               | 28.8 us                                                | 25.5 us: 1.13x faster                                                  |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.84 ms: 1.13x faster                                                  |
| xml_etree_generate       | 94.2 ms                                                | 83.7 ms: 1.13x faster                                                  |
| nqueens                  | 100 ms                                                 | 89.4 ms: 1.12x faster                                                  |
| dulwich_log              | 75.9 ms                                                | 69.0 ms: 1.10x faster                                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                                  |
| json                     | 5.42 ms                                                | 4.97 ms: 1.09x faster                                                  |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                   |
| mdp                      | 2.82 sec                                               | 2.60 sec: 1.09x faster                                                 |
| pathlib                  | 20.0 ms                                                | 18.5 ms: 1.08x faster                                                  |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.08x faster                                                   |
| regex_dna                | 222 ms                                                 | 206 ms: 1.08x faster                                                   |
| regex_v8                 | 25.0 ms                                                | 23.6 ms: 1.06x faster                                                  |
| sqlite_synth             | 2.93 us                                                | 2.78 us: 1.05x faster                                                  |
| meteor_contest           | 115 ms                                                 | 112 ms: 1.02x faster                                                   |
| pickle                   | 10.3 us                                                | 10.1 us: 1.02x faster                                                  |
| pidigits                 | 190 ms                                                 | 189 ms: 1.01x faster                                                   |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.01x slower                                                  |
| pickle_list              | 4.56 us                                                | 4.64 us: 1.02x slower                                                  |
| unpickle_list            | 4.82 us                                                | 4.91 us: 1.02x slower                                                  |
| unpickle                 | 14.1 us                                                | 14.5 us: 1.03x slower                                                  |
| async_generators         | 425 ms                                                 | 457 ms: 1.08x slower                                                   |
| regex_effbot             | 3.23 ms                                                | 3.54 ms: 1.10x slower                                                  |
| pickle_dict              | 27.3 us                                                | 30.7 us: 1.12x slower                                                  |
| coverage                 | 72.8 ms                                                | 84.8 ms: 1.17x slower                                                  |
| python_startup_no_site   | 5.82 ms                                                | 6.87 ms: 1.18x slower                                                  |
| telco                    | 6.54 ms                                                | 8.22 ms: 1.26x slower                                                  |
| dask                     | 423 ms                                                 | 532 ms: 1.26x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.27x faster                                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.23x
- 95% likely to have a speedup of 1.22x
- 99% likely to have a speedup of 1.19x
