
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: linux-x86_64
- commit hash: 84b7e9e
- commit date: 2023-10-14
- overall geometric mean: 1.27x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.64 sec: 1.20x faster                                 |
| tornado_http   | 127 ms                                                 | 96.1 ms: 1.33x faster                                  |
| Geometric mean | (ref)                                                  | 1.26x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| nbody          | 142 ms                                                 | 93.7 ms: 1.51x faster                                  |
| float          | 111 ms                                                 | 82.4 ms: 1.34x faster                                  |
| pidigits       | 190 ms                                                 | 187 ms: 1.01x faster                                   |
| Geometric mean | (ref)                                                  | 1.27x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 137 ms: 1.29x faster                                   |
| regex_dna      | 222 ms                                                 | 220 ms: 1.01x faster                                   |
| regex_v8       | 25.0 ms                                                | 25.7 ms: 1.02x slower                                  |
| regex_effbot   | 3.23 ms                                                | 3.60 ms: 1.11x slower                                  |
| Geometric mean | (ref)                                                  | 1.03x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 304 us: 1.50x faster                                   |
| unpickle_pure_python | 300 us                                                 | 224 us: 1.34x faster                                   |
| tomli_loads          | 2.92 sec                                               | 2.18 sec: 1.34x faster                                 |
| json_dumps           | 13.5 ms                                                | 10.5 ms: 1.29x faster                                  |
| xml_etree_process    | 74.9 ms                                                | 59.2 ms: 1.27x faster                                  |
| xml_etree_generate   | 94.2 ms                                                | 86.4 ms: 1.09x faster                                  |
| xml_etree_iterparse  | 111 ms                                                 | 105 ms: 1.06x faster                                   |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| json_loads           | 28.8 us                                                | 27.9 us: 1.03x faster                                  |
| unpickle_list        | 4.82 us                                                | 5.13 us: 1.06x slower                                  |
| unpickle             | 14.1 us                                                | 15.7 us: 1.11x slower                                  |
| pickle               | 10.3 us                                                | 11.5 us: 1.12x slower                                  |
| pickle_list          | 4.56 us                                                | 5.11 us: 1.12x slower                                  |
| pickle_dict          | 27.3 us                                                | 34.7 us: 1.27x slower                                  |
| Geometric mean       | (ref)                                                  | 1.08x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.41x faster                                  |
| python_startup_no_site | 5.82 ms                                                | 6.85 ms: 1.18x slower                                  |
| Geometric mean         | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 14.8 ms                                                | 12.0 ms: 1.23x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231014-linux-x86_64-python-main-3.13.0a1+-84b7e9e |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 149 us: 3.42x faster                                   |
| generators               | 76.8 ms                                                | 29.4 ms: 2.61x faster                                  |
| deltablue                | 7.42 ms                                                | 3.31 ms: 2.24x faster                                  |
| asyncio_tcp              | 925 ms                                                 | 473 ms: 1.96x faster                                   |
| chaos                    | 106 ms                                                 | 61.8 ms: 1.72x faster                                  |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.77 sec: 1.69x faster                                 |
| richards_super           | 90.7 ms                                                | 53.7 ms: 1.69x faster                                  |
| raytrace                 | 464 ms                                                 | 278 ms: 1.67x faster                                   |
| async_tree_none          | 717 ms                                                 | 436 ms: 1.64x faster                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.28 ms: 1.60x faster                                  |
| go                       | 229 ms                                                 | 143 ms: 1.60x faster                                   |
| logging_silent           | 175 ns                                                 | 110 ns: 1.60x faster                                   |
| crypto_pyaes             | 118 ms                                                 | 75.3 ms: 1.57x faster                                  |
| scimark_monte_carlo      | 108 ms                                                 | 69.8 ms: 1.55x faster                                  |
| richards                 | 74.9 ms                                                | 48.3 ms: 1.55x faster                                  |
| scimark_sor              | 197 ms                                                 | 127 ms: 1.55x faster                                   |
| sqlglot_transpile        | 2.45 ms                                                | 1.60 ms: 1.53x faster                                  |
| async_tree_memoization   | 854 ms                                                 | 561 ms: 1.52x faster                                   |
| hexiom                   | 9.53 ms                                                | 6.26 ms: 1.52x faster                                  |
| nbody                    | 142 ms                                                 | 93.7 ms: 1.51x faster                                  |
| async_tree_io            | 1.77 sec                                               | 1.18 sec: 1.51x faster                                 |
| pickle_pure_python       | 455 us                                                 | 304 us: 1.50x faster                                   |
| unpack_sequence          | 64.7 ns                                                | 45.5 ns: 1.42x faster                                  |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.41x faster                                  |
| pyflate                  | 673 ms                                                 | 481 ms: 1.40x faster                                   |
| scimark_lu               | 163 ms                                                 | 117 ms: 1.40x faster                                   |
| logging_format           | 8.91 us                                                | 6.44 us: 1.38x faster                                  |
| coroutines               | 31.8 ms                                                | 23.2 ms: 1.37x faster                                  |
| logging_simple           | 8.07 us                                                | 5.91 us: 1.37x faster                                  |
| deepcopy_memo            | 52.3 us                                                | 38.9 us: 1.35x faster                                  |
| float                    | 111 ms                                                 | 82.4 ms: 1.34x faster                                  |
| unpickle_pure_python     | 300 us                                                 | 224 us: 1.34x faster                                   |
| tomli_loads              | 2.92 sec                                               | 2.18 sec: 1.34x faster                                 |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 713 ms: 1.33x faster                                   |
| tornado_http             | 127 ms                                                 | 96.1 ms: 1.33x faster                                  |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.31x faster                                 |
| json_dumps               | 13.5 ms                                                | 10.5 ms: 1.29x faster                                  |
| pycparser                | 1.50 sec                                               | 1.16 sec: 1.29x faster                                 |
| regex_compile            | 177 ms                                                 | 137 ms: 1.29x faster                                   |
| pprint_safe_repr         | 955 ms                                                 | 743 ms: 1.28x faster                                   |
| spectral_norm            | 150 ms                                                 | 117 ms: 1.28x faster                                   |
| sqlglot_normalize        | 135 ms                                                 | 106 ms: 1.27x faster                                   |
| xml_etree_process        | 74.9 ms                                                | 59.2 ms: 1.27x faster                                  |
| comprehensions           | 26.8 us                                                | 21.4 us: 1.25x faster                                  |
| nqueens                  | 100 ms                                                 | 79.9 ms: 1.25x faster                                  |
| mypy2                    | 428 ms                                                 | 342 ms: 1.25x faster                                   |
| deepcopy                 | 442 us                                                 | 354 us: 1.25x faster                                   |
| mako                     | 14.8 ms                                                | 12.0 ms: 1.23x faster                                  |
| sqlglot_optimize         | 65.3 ms                                                | 53.8 ms: 1.22x faster                                  |
| deepcopy_reduce          | 3.82 us                                                | 3.15 us: 1.21x faster                                  |
| docutils                 | 3.17 sec                                               | 2.64 sec: 1.20x faster                                 |
| bench_thread_pool        | 947 us                                                 | 808 us: 1.17x faster                                   |
| fannkuch                 | 486 ms                                                 | 417 ms: 1.17x faster                                   |
| dulwich_log              | 75.9 ms                                                | 67.1 ms: 1.13x faster                                  |
| scimark_fft              | 424 ms                                                 | 377 ms: 1.12x faster                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.51 ms: 1.11x faster                                  |
| xml_etree_generate       | 94.2 ms                                                | 86.4 ms: 1.09x faster                                  |
| mdp                      | 2.82 sec                                               | 2.60 sec: 1.09x faster                                 |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.05 ms: 1.08x faster                                  |
| meteor_contest           | 115 ms                                                 | 107 ms: 1.07x faster                                   |
| json                     | 5.42 ms                                                | 5.10 ms: 1.06x faster                                  |
| xml_etree_iterparse      | 111 ms                                                 | 105 ms: 1.06x faster                                   |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.05x faster                                  |
| gc_traversal             | 3.84 ms                                                | 3.69 ms: 1.04x faster                                  |
| sqlite_synth             | 2.93 us                                                | 2.82 us: 1.04x faster                                  |
| xml_etree_parse          | 163 ms                                                 | 158 ms: 1.03x faster                                   |
| json_loads               | 28.8 us                                                | 27.9 us: 1.03x faster                                  |
| pidigits                 | 190 ms                                                 | 187 ms: 1.01x faster                                   |
| regex_dna                | 222 ms                                                 | 220 ms: 1.01x faster                                   |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                  |
| regex_v8                 | 25.0 ms                                                | 25.7 ms: 1.02x slower                                  |
| unpickle_list            | 4.82 us                                                | 5.13 us: 1.06x slower                                  |
| async_generators         | 425 ms                                                 | 462 ms: 1.09x slower                                   |
| unpickle                 | 14.1 us                                                | 15.7 us: 1.11x slower                                  |
| regex_effbot             | 3.23 ms                                                | 3.60 ms: 1.11x slower                                  |
| pickle                   | 10.3 us                                                | 11.5 us: 1.12x slower                                  |
| pickle_list              | 4.56 us                                                | 5.11 us: 1.12x slower                                  |
| python_startup_no_site   | 5.82 ms                                                | 6.85 ms: 1.18x slower                                  |
| coverage                 | 72.8 ms                                                | 90.5 ms: 1.24x slower                                  |
| telco                    | 6.54 ms                                                | 8.22 ms: 1.26x slower                                  |
| pickle_dict              | 27.3 us                                                | 34.7 us: 1.27x slower                                  |
| Geometric mean           | (ref)                                                  | 1.27x faster                                           |
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.26x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
