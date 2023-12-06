
# Results vs. 3.10.4

- fork: python
- ref: de5f8f7d13c0bbc723ea
- machine: linux-x86_64
- commit hash: de5f8f7
- commit date: 2023-09-11
- overall geometric mean: 1.31x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.25x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                |
| tornado_http   | 127 ms                                                 | 95.5 ms: 1.33x faster                                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 89.2 ms: 1.59x faster                                                 |
| float          | 111 ms                                                 | 79.9 ms: 1.38x faster                                                 |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.31x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 133 ms: 1.33x faster                                                  |
| regex_dna      | 222 ms                                                 | 205 ms: 1.08x faster                                                  |
| regex_v8       | 25.0 ms                                                | 23.7 ms: 1.06x faster                                                 |
| regex_effbot   | 3.23 ms                                                | 3.39 ms: 1.05x slower                                                 |
| Geometric mean | (ref)                                                  | 1.10x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 297 us: 1.53x faster                                                  |
| tomli_loads          | 2.92 sec                                               | 2.02 sec: 1.44x faster                                                |
| unpickle_pure_python | 300 us                                                 | 214 us: 1.41x faster                                                  |
| json_dumps           | 13.5 ms                                                | 9.92 ms: 1.36x faster                                                 |
| xml_etree_process    | 74.9 ms                                                | 57.1 ms: 1.31x faster                                                 |
| xml_etree_generate   | 94.2 ms                                                | 82.3 ms: 1.14x faster                                                 |
| json_loads           | 28.8 us                                                | 25.3 us: 1.14x faster                                                 |
| xml_etree_iterparse  | 111 ms                                                 | 102 ms: 1.09x faster                                                  |
| xml_etree_parse      | 163 ms                                                 | 151 ms: 1.08x faster                                                  |
| pickle_list          | 4.56 us                                                | 4.63 us: 1.02x slower                                                 |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                                 |
| unpickle             | 14.1 us                                                | 14.5 us: 1.02x slower                                                 |
| unpickle_list        | 4.82 us                                                | 5.05 us: 1.05x slower                                                 |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                 |
| python_startup_no_site | 5.82 ms                                                | 6.81 ms: 1.17x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.10x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 10.7 ms: 1.38x faster                                                 |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230911-linux-x86_64-python-de5f8f7d13c0bbc723ea-3.13.0a0-de5f8f7 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 142 us: 3.59x faster                                                  |
| generators               | 76.8 ms                                                | 28.6 ms: 2.68x faster                                                 |
| deltablue                | 7.42 ms                                                | 3.25 ms: 2.29x faster                                                 |
| asyncio_tcp              | 925 ms                                                 | 486 ms: 1.90x faster                                                  |
| chaos                    | 106 ms                                                 | 59.8 ms: 1.78x faster                                                 |
| logging_silent           | 175 ns                                                 | 98.9 ns: 1.77x faster                                                 |
| raytrace                 | 464 ms                                                 | 268 ms: 1.73x faster                                                  |
| crypto_pyaes             | 118 ms                                                 | 68.7 ms: 1.73x faster                                                 |
| richards_super           | 90.7 ms                                                | 53.1 ms: 1.71x faster                                                 |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.79 sec: 1.68x faster                                                |
| scimark_monte_carlo      | 108 ms                                                 | 64.6 ms: 1.68x faster                                                 |
| go                       | 229 ms                                                 | 138 ms: 1.67x faster                                                  |
| scimark_sor              | 197 ms                                                 | 119 ms: 1.66x faster                                                  |
| async_tree_none          | 717 ms                                                 | 437 ms: 1.64x faster                                                  |
| hexiom                   | 9.53 ms                                                | 5.82 ms: 1.64x faster                                                 |
| sqlglot_parse            | 2.06 ms                                                | 1.26 ms: 1.63x faster                                                 |
| richards                 | 74.9 ms                                                | 47.0 ms: 1.59x faster                                                 |
| nbody                    | 142 ms                                                 | 89.2 ms: 1.59x faster                                                 |
| sqlglot_transpile        | 2.45 ms                                                | 1.57 ms: 1.56x faster                                                 |
| pickle_pure_python       | 455 us                                                 | 297 us: 1.53x faster                                                  |
| pyflate                  | 673 ms                                                 | 443 ms: 1.52x faster                                                  |
| async_tree_memoization   | 854 ms                                                 | 564 ms: 1.51x faster                                                  |
| scimark_lu               | 163 ms                                                 | 109 ms: 1.50x faster                                                  |
| async_tree_io            | 1.77 sec                                               | 1.19 sec: 1.50x faster                                                |
| coroutines               | 31.8 ms                                                | 21.5 ms: 1.48x faster                                                 |
| unpack_sequence          | 64.7 ns                                                | 44.4 ns: 1.46x faster                                                 |
| spectral_norm            | 150 ms                                                 | 103 ms: 1.45x faster                                                  |
| tomli_loads              | 2.92 sec                                               | 2.02 sec: 1.44x faster                                                |
| deepcopy_memo            | 52.3 us                                                | 36.4 us: 1.44x faster                                                 |
| python_startup           | 14.2 ms                                                | 10.0 ms: 1.41x faster                                                 |
| unpickle_pure_python     | 300 us                                                 | 214 us: 1.41x faster                                                  |
| logging_simple           | 8.07 us                                                | 5.80 us: 1.39x faster                                                 |
| float                    | 111 ms                                                 | 79.9 ms: 1.38x faster                                                 |
| logging_format           | 8.91 us                                                | 6.45 us: 1.38x faster                                                 |
| mako                     | 14.8 ms                                                | 10.7 ms: 1.38x faster                                                 |
| json_dumps               | 13.5 ms                                                | 9.92 ms: 1.36x faster                                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 705 ms: 1.35x faster                                                  |
| tornado_http             | 127 ms                                                 | 95.5 ms: 1.33x faster                                                 |
| regex_compile            | 177 ms                                                 | 133 ms: 1.33x faster                                                  |
| pycparser                | 1.50 sec                                               | 1.14 sec: 1.31x faster                                                |
| xml_etree_process        | 74.9 ms                                                | 57.1 ms: 1.31x faster                                                 |
| comprehensions           | 26.8 us                                                | 20.5 us: 1.31x faster                                                 |
| pprint_pformat           | 1.99 sec                                               | 1.52 sec: 1.31x faster                                                |
| fannkuch                 | 486 ms                                                 | 373 ms: 1.30x faster                                                  |
| sqlglot_normalize        | 135 ms                                                 | 104 ms: 1.30x faster                                                  |
| pprint_safe_repr         | 955 ms                                                 | 736 ms: 1.30x faster                                                  |
| nqueens                  | 100 ms                                                 | 78.4 ms: 1.28x faster                                                 |
| mypy2                    | 428 ms                                                 | 337 ms: 1.27x faster                                                  |
| deepcopy                 | 442 us                                                 | 349 us: 1.27x faster                                                  |
| sqlglot_optimize         | 65.3 ms                                                | 52.3 ms: 1.25x faster                                                 |
| docutils                 | 3.17 sec                                               | 2.62 sec: 1.21x faster                                                |
| scimark_fft              | 424 ms                                                 | 350 ms: 1.21x faster                                                  |
| deepcopy_reduce          | 3.82 us                                                | 3.18 us: 1.20x faster                                                 |
| bench_thread_pool        | 947 us                                                 | 809 us: 1.17x faster                                                  |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 4.67 ms: 1.17x faster                                                 |
| xml_etree_generate       | 94.2 ms                                                | 82.3 ms: 1.14x faster                                                 |
| dulwich_log              | 75.9 ms                                                | 66.5 ms: 1.14x faster                                                 |
| json                     | 5.42 ms                                                | 4.74 ms: 1.14x faster                                                 |
| json_loads               | 28.8 us                                                | 25.3 us: 1.14x faster                                                 |
| pathlib                  | 20.0 ms                                                | 18.3 ms: 1.10x faster                                                 |
| xml_etree_iterparse      | 111 ms                                                 | 102 ms: 1.09x faster                                                  |
| meteor_contest           | 115 ms                                                 | 105 ms: 1.09x faster                                                  |
| create_gc_cycles         | 1.67 ms                                                | 1.53 ms: 1.09x faster                                                 |
| regex_dna                | 222 ms                                                 | 205 ms: 1.08x faster                                                  |
| xml_etree_parse          | 163 ms                                                 | 151 ms: 1.08x faster                                                  |
| regex_v8                 | 25.0 ms                                                | 23.7 ms: 1.06x faster                                                 |
| sqlite_synth             | 2.93 us                                                | 2.80 us: 1.05x faster                                                 |
| mdp                      | 2.82 sec                                               | 2.69 sec: 1.05x faster                                                |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                                  |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                 |
| pickle_list              | 4.56 us                                                | 4.63 us: 1.02x slower                                                 |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                                 |
| unpickle                 | 14.1 us                                                | 14.5 us: 1.02x slower                                                 |
| gc_traversal             | 3.84 ms                                                | 3.98 ms: 1.04x slower                                                 |
| unpickle_list            | 4.82 us                                                | 5.05 us: 1.05x slower                                                 |
| async_generators         | 425 ms                                                 | 447 ms: 1.05x slower                                                  |
| regex_effbot             | 3.23 ms                                                | 3.39 ms: 1.05x slower                                                 |
| python_startup_no_site   | 5.82 ms                                                | 6.81 ms: 1.17x slower                                                 |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                                 |
| coverage                 | 72.8 ms                                                | 88.4 ms: 1.21x slower                                                 |
| telco                    | 6.54 ms                                                | 8.04 ms: 1.23x slower                                                 |
| dask                     | 423 ms                                                 | 522 ms: 1.23x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.31x faster                                                          |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.29x
- 95% likely to have a speedup of 1.28x
- 99% likely to have a speedup of 1.25x
