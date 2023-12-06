
# Results vs. 3.10.4

- fork: gvanrossum
- ref: load_attr_uops
- machine: linux-x86_64
- commit hash: b54eee3
- commit date: 2023-09-26
- overall geometric mean: 1.30x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.24x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.62 sec: 1.21x faster                                              |
| tornado_http   | 127 ms                                                 | 95.1 ms: 1.34x faster                                               |
| Geometric mean | (ref)                                                  | 1.27x faster                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 90.9 ms: 1.56x faster                                               |
| float          | 111 ms                                                 | 78.4 ms: 1.41x faster                                               |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| Geometric mean | (ref)                                                  | 1.31x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 133 ms: 1.33x faster                                                |
| regex_dna      | 222 ms                                                 | 212 ms: 1.05x faster                                                |
| regex_v8       | 25.0 ms                                                | 24.0 ms: 1.04x faster                                               |
| regex_effbot   | 3.23 ms                                                | 3.52 ms: 1.09x slower                                               |
| Geometric mean | (ref)                                                  | 1.07x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|----------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 296 us: 1.54x faster                                                |
| unpickle_pure_python | 300 us                                                 | 211 us: 1.42x faster                                                |
| tomli_loads          | 2.92 sec                                               | 2.09 sec: 1.39x faster                                              |
| json_dumps           | 13.5 ms                                                | 9.76 ms: 1.39x faster                                               |
| xml_etree_process    | 74.9 ms                                                | 57.7 ms: 1.30x faster                                               |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                               |
| xml_etree_generate   | 94.2 ms                                                | 84.3 ms: 1.12x faster                                               |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                |
| xml_etree_parse      | 163 ms                                                 | 152 ms: 1.07x faster                                                |
| unpickle             | 14.1 us                                                | 14.3 us: 1.01x slower                                               |
| pickle               | 10.3 us                                                | 10.6 us: 1.03x slower                                               |
| unpickle_list        | 4.82 us                                                | 4.96 us: 1.03x slower                                               |
| pickle_list          | 4.56 us                                                | 4.78 us: 1.05x slower                                               |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                               |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                        |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.40x faster                                               |
| python_startup_no_site | 5.82 ms                                                | 6.86 ms: 1.18x slower                                               |
| Geometric mean         | (ref)                                                  | 1.09x faster                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|-----------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.6 ms: 1.39x faster                                               |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230926-linux-x86_64-gvanrossum-load_attr_uops-3.13.0a0-b54eee3 |
|--------------------------|:------------------------------------------------------:|:-------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.60x faster                                                |
| generators               | 76.8 ms                                                | 28.8 ms: 2.67x faster                                               |
| deltablue                | 7.42 ms                                                | 3.29 ms: 2.25x faster                                               |
| asyncio_tcp              | 925 ms                                                 | 505 ms: 1.83x faster                                                |
| chaos                    | 106 ms                                                 | 60.6 ms: 1.75x faster                                               |
| logging_silent           | 175 ns                                                 | 101 ns: 1.74x faster                                                |
| raytrace                 | 464 ms                                                 | 268 ms: 1.73x faster                                                |
| crypto_pyaes             | 118 ms                                                 | 68.6 ms: 1.73x faster                                               |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                              |
| scimark_monte_carlo      | 108 ms                                                 | 66.2 ms: 1.64x faster                                               |
| richards_super           | 90.7 ms                                                | 55.4 ms: 1.64x faster                                               |
| sqlglot_parse            | 2.06 ms                                                | 1.26 ms: 1.63x faster                                               |
| async_tree_none          | 717 ms                                                 | 440 ms: 1.63x faster                                                |
| go                       | 229 ms                                                 | 141 ms: 1.62x faster                                                |
| hexiom                   | 9.53 ms                                                | 6.02 ms: 1.58x faster                                               |
| nbody                    | 142 ms                                                 | 90.9 ms: 1.56x faster                                               |
| sqlglot_transpile        | 2.45 ms                                                | 1.58 ms: 1.55x faster                                               |
| richards                 | 74.9 ms                                                | 48.6 ms: 1.54x faster                                               |
| pickle_pure_python       | 455 us                                                 | 296 us: 1.54x faster                                                |
| scimark_sor              | 197 ms                                                 | 129 ms: 1.52x faster                                                |
| async_tree_memoization   | 854 ms                                                 | 565 ms: 1.51x faster                                                |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.50x faster                                                |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.49x faster                                              |
| pyflate                  | 673 ms                                                 | 457 ms: 1.47x faster                                                |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.44x faster                                               |
| deepcopy_memo            | 52.3 us                                                | 36.4 us: 1.44x faster                                               |
| spectral_norm            | 150 ms                                                 | 105 ms: 1.43x faster                                                |
| unpickle_pure_python     | 300 us                                                 | 211 us: 1.42x faster                                                |
| float                    | 111 ms                                                 | 78.4 ms: 1.41x faster                                               |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.40x faster                                               |
| tomli_loads              | 2.92 sec                                               | 2.09 sec: 1.39x faster                                              |
| mako                     | 14.8 ms                                                | 10.6 ms: 1.39x faster                                               |
| json_dumps               | 13.5 ms                                                | 9.76 ms: 1.39x faster                                               |
| logging_format           | 8.91 us                                                | 6.52 us: 1.37x faster                                               |
| logging_simple           | 8.07 us                                                | 5.96 us: 1.35x faster                                               |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 703 ms: 1.35x faster                                                |
| unpack_sequence          | 64.7 ns                                                | 48.2 ns: 1.34x faster                                               |
| tornado_http             | 127 ms                                                 | 95.1 ms: 1.34x faster                                               |
| pprint_pformat           | 1.99 sec                                               | 1.48 sec: 1.34x faster                                              |
| regex_compile            | 177 ms                                                 | 133 ms: 1.33x faster                                                |
| pprint_safe_repr         | 955 ms                                                 | 727 ms: 1.31x faster                                                |
| pycparser                | 1.50 sec                                               | 1.15 sec: 1.31x faster                                              |
| xml_etree_process        | 74.9 ms                                                | 57.7 ms: 1.30x faster                                               |
| comprehensions           | 26.8 us                                                | 20.7 us: 1.30x faster                                               |
| sqlglot_normalize        | 135 ms                                                 | 105 ms: 1.29x faster                                                |
| mypy2                    | 428 ms                                                 | 336 ms: 1.27x faster                                                |
| nqueens                  | 100 ms                                                 | 78.9 ms: 1.27x faster                                               |
| deepcopy                 | 442 us                                                 | 351 us: 1.26x faster                                                |
| fannkuch                 | 486 ms                                                 | 387 ms: 1.26x faster                                                |
| sqlglot_optimize         | 65.3 ms                                                | 52.6 ms: 1.24x faster                                               |
| docutils                 | 3.17 sec                                               | 2.62 sec: 1.21x faster                                              |
| deepcopy_reduce          | 3.82 us                                                | 3.17 us: 1.21x faster                                               |
| scimark_fft              | 424 ms                                                 | 359 ms: 1.18x faster                                                |
| bench_thread_pool        | 947 us                                                 | 810 us: 1.17x faster                                                |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.67 ms: 1.17x faster                                               |
| dulwich_log              | 75.9 ms                                                | 66.2 ms: 1.15x faster                                               |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                               |
| xml_etree_generate       | 94.2 ms                                                | 84.3 ms: 1.12x faster                                               |
| json                     | 5.42 ms                                                | 4.85 ms: 1.12x faster                                               |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                               |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                |
| meteor_contest           | 115 ms                                                 | 106 ms: 1.09x faster                                                |
| gc_traversal             | 3.84 ms                                                | 3.56 ms: 1.08x faster                                               |
| pathlib                  | 20.0 ms                                                | 18.6 ms: 1.07x faster                                               |
| xml_etree_parse          | 163 ms                                                 | 152 ms: 1.07x faster                                                |
| sqlite_synth             | 2.93 us                                                | 2.75 us: 1.07x faster                                               |
| mdp                      | 2.82 sec                                               | 2.67 sec: 1.06x faster                                              |
| regex_dna                | 222 ms                                                 | 212 ms: 1.05x faster                                                |
| regex_v8                 | 25.0 ms                                                | 24.0 ms: 1.04x faster                                               |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                               |
| unpickle                 | 14.1 us                                                | 14.3 us: 1.01x slower                                               |
| pickle                   | 10.3 us                                                | 10.6 us: 1.03x slower                                               |
| unpickle_list            | 4.82 us                                                | 4.96 us: 1.03x slower                                               |
| async_generators         | 425 ms                                                 | 444 ms: 1.04x slower                                                |
| pickle_list              | 4.56 us                                                | 4.78 us: 1.05x slower                                               |
| regex_effbot             | 3.23 ms                                                | 3.52 ms: 1.09x slower                                               |
| coverage                 | 72.8 ms                                                | 84.8 ms: 1.17x slower                                               |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                               |
| python_startup_no_site   | 5.82 ms                                                | 6.86 ms: 1.18x slower                                               |
| telco                    | 6.54 ms                                                | 8.06 ms: 1.23x slower                                               |
| dask                     | 423 ms                                                 | 524 ms: 1.24x slower                                                |
| Geometric mean           | (ref)                                                  | 1.30x faster                                                        |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.24x
