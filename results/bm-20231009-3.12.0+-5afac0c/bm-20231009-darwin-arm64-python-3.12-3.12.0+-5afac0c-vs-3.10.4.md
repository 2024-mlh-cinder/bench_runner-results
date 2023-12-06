
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: 5afac0c
- commit date: 2023-10-09
- overall geometric mean: 1.22x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 202 ms                                                 | 171 ms: 1.19x faster                                 |
| docutils       | 1.78 sec                                               | 1.54 sec: 1.16x faster                               |
| tornado_http   | 91.9 ms                                                | 70.1 ms: 1.31x faster                                |
| Geometric mean | (ref)                                                  | 1.22x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 94.1 ms                                                | 68.7 ms: 1.37x faster                                |
| float          | 72.3 ms                                                | 58.0 ms: 1.25x faster                                |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                 |
| Geometric mean | (ref)                                                  | 1.19x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 75.8 ms: 1.28x faster                                |
| regex_v8       | 17.5 ms                                                | 15.9 ms: 1.10x faster                                |
| regex_dna      | 160 ms                                                 | 149 ms: 1.07x faster                                 |
| regex_effbot   | 2.45 ms                                                | 2.59 ms: 1.06x slower                                |
| Geometric mean | (ref)                                                  | 1.09x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 189 us: 1.50x faster                                 |
| unpickle_pure_python | 203 us                                                 | 144 us: 1.41x faster                                 |
| json_dumps           | 8.38 ms                                                | 6.42 ms: 1.31x faster                                |
| tomli_loads          | 1.76 sec                                               | 1.39 sec: 1.27x faster                               |
| xml_etree_process    | 45.1 ms                                                | 38.6 ms: 1.17x faster                                |
| unpickle             | 9.77 us                                                | 9.28 us: 1.05x faster                                |
| pickle_dict          | 17.8 us                                                | 18.0 us: 1.01x slower                                |
| pickle_list          | 2.83 us                                                | 2.91 us: 1.03x slower                                |
| xml_etree_parse      | 107 ms                                                 | 111 ms: 1.03x slower                                 |
| xml_etree_generate   | 54.3 ms                                                | 55.9 ms: 1.03x slower                                |
| xml_etree_iterparse  | 72.6 ms                                                | 75.5 ms: 1.04x slower                                |
| json_loads           | 16.9 us                                                | 17.6 us: 1.04x slower                                |
| unpickle_list        | 2.66 us                                                | 3.26 us: 1.22x slower                                |
| Geometric mean       | (ref)                                                  | 1.08x faster                                         |

Benchmark hidden because not significant (1): pickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.1 ms: 1.05x faster                                |
| python_startup_no_site | 9.73 ms                                                | 9.90 ms: 1.02x slower                                |
| Geometric mean         | (ref)                                                  | 1.01x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|-----------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.55 ms: 1.39x faster                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231009-darwin-arm64-python-3.12-3.12.0+-5afac0c |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 91.2 us: 3.77x faster                                |
| deltablue                | 5.15 ms                                                | 2.59 ms: 1.99x faster                                |
| logging_silent           | 119 ns                                                 | 67.9 ns: 1.76x faster                                |
| richards_super           | 60.7 ms                                                | 35.2 ms: 1.73x faster                                |
| richards                 | 51.4 ms                                                | 31.4 ms: 1.63x faster                                |
| mypy2                    | 308 ms                                                 | 192 ms: 1.61x faster                                 |
| async_tree_memoization   | 493 ms                                                 | 310 ms: 1.59x faster                                 |
| go                       | 165 ms                                                 | 107 ms: 1.53x faster                                 |
| async_tree_none          | 402 ms                                                 | 262 ms: 1.53x faster                                 |
| async_tree_io            | 1.02 sec                                               | 667 ms: 1.53x faster                                 |
| scimark_lu               | 110 ms                                                 | 72.1 ms: 1.52x faster                                |
| pickle_pure_python       | 284 us                                                 | 189 us: 1.50x faster                                 |
| hexiom                   | 6.32 ms                                                | 4.24 ms: 1.49x faster                                |
| sqlglot_parse            | 1.33 ms                                                | 898 us: 1.48x faster                                 |
| crypto_pyaes             | 78.0 ms                                                | 52.6 ms: 1.48x faster                                |
| chaos                    | 66.8 ms                                                | 45.5 ms: 1.47x faster                                |
| asyncio_tcp              | 673 ms                                                 | 462 ms: 1.46x faster                                 |
| scimark_monte_carlo      | 72.2 ms                                                | 50.0 ms: 1.45x faster                                |
| sqlglot_transpile        | 1.54 ms                                                | 1.08 ms: 1.43x faster                                |
| unpickle_pure_python     | 203 us                                                 | 144 us: 1.41x faster                                 |
| deepcopy_memo            | 34.5 us                                                | 24.7 us: 1.40x faster                                |
| mako                     | 10.5 ms                                                | 7.55 ms: 1.39x faster                                |
| pyflate                  | 453 ms                                                 | 330 ms: 1.38x faster                                 |
| nbody                    | 94.1 ms                                                | 68.7 ms: 1.37x faster                                |
| pycparser                | 915 ms                                                 | 677 ms: 1.35x faster                                 |
| unpack_sequence          | 38.7 ns                                                | 28.8 ns: 1.34x faster                                |
| raytrace                 | 328 ms                                                 | 246 ms: 1.33x faster                                 |
| scimark_sor              | 127 ms                                                 | 95.4 ms: 1.33x faster                                |
| tornado_http             | 91.9 ms                                                | 70.1 ms: 1.31x faster                                |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.26 sec: 1.31x faster                               |
| json_dumps               | 8.38 ms                                                | 6.42 ms: 1.31x faster                                |
| sqlalchemy_imperative    | 9.03 ms                                                | 6.96 ms: 1.30x faster                                |
| spectral_norm            | 96.4 ms                                                | 74.7 ms: 1.29x faster                                |
| regex_compile            | 96.6 ms                                                | 75.8 ms: 1.28x faster                                |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 527 ms: 1.27x faster                                 |
| tomli_loads              | 1.76 sec                                               | 1.39 sec: 1.27x faster                               |
| create_gc_cycles         | 876 us                                                 | 697 us: 1.26x faster                                 |
| logging_format           | 5.01 us                                                | 4.00 us: 1.25x faster                                |
| float                    | 72.3 ms                                                | 58.0 ms: 1.25x faster                                |
| logging_simple           | 4.63 us                                                | 3.73 us: 1.24x faster                                |
| pprint_pformat           | 1.24 sec                                               | 1.00 sec: 1.24x faster                               |
| deepcopy                 | 278 us                                                 | 225 us: 1.24x faster                                 |
| pprint_safe_repr         | 609 ms                                                 | 492 ms: 1.24x faster                                 |
| dulwich_log              | 37.1 ms                                                | 30.5 ms: 1.22x faster                                |
| fannkuch                 | 317 ms                                                 | 263 ms: 1.21x faster                                 |
| 2to3                     | 202 ms                                                 | 171 ms: 1.19x faster                                 |
| deepcopy_reduce          | 2.38 us                                                | 2.01 us: 1.18x faster                                |
| xml_etree_process        | 45.1 ms                                                | 38.6 ms: 1.17x faster                                |
| scimark_fft              | 232 ms                                                 | 200 ms: 1.16x faster                                 |
| docutils                 | 1.78 sec                                               | 1.54 sec: 1.16x faster                               |
| generators               | 32.9 ms                                                | 28.6 ms: 1.15x faster                                |
| sqlalchemy_declarative   | 74.8 ms                                                | 65.6 ms: 1.14x faster                                |
| dask                     | 258 ms                                                 | 228 ms: 1.13x faster                                 |
| nqueens                  | 68.1 ms                                                | 60.2 ms: 1.13x faster                                |
| bench_thread_pool        | 548 us                                                 | 488 us: 1.12x faster                                 |
| coroutines               | 20.2 ms                                                | 18.1 ms: 1.12x faster                                |
| sqlglot_optimize         | 38.0 ms                                                | 34.4 ms: 1.10x faster                                |
| regex_v8                 | 17.5 ms                                                | 15.9 ms: 1.10x faster                                |
| comprehensions           | 17.7 us                                                | 16.1 us: 1.10x faster                                |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.18 ms: 1.09x faster                                |
| regex_dna                | 160 ms                                                 | 149 ms: 1.07x faster                                 |
| meteor_contest           | 78.6 ms                                                | 73.8 ms: 1.07x faster                                |
| sqlglot_normalize        | 197 ms                                                 | 186 ms: 1.06x faster                                 |
| unpickle                 | 9.77 us                                                | 9.28 us: 1.05x faster                                |
| python_startup           | 12.6 ms                                                | 12.1 ms: 1.05x faster                                |
| json                     | 3.10 ms                                                | 2.98 ms: 1.04x faster                                |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x slower                                 |
| pickle_dict              | 17.8 us                                                | 18.0 us: 1.01x slower                                |
| python_startup_no_site   | 9.73 ms                                                | 9.90 ms: 1.02x slower                                |
| pathlib                  | 28.8 ms                                                | 29.5 ms: 1.02x slower                                |
| pickle_list              | 2.83 us                                                | 2.91 us: 1.03x slower                                |
| xml_etree_parse          | 107 ms                                                 | 111 ms: 1.03x slower                                 |
| xml_etree_generate       | 54.3 ms                                                | 55.9 ms: 1.03x slower                                |
| xml_etree_iterparse      | 72.6 ms                                                | 75.5 ms: 1.04x slower                                |
| telco                    | 3.68 ms                                                | 3.83 ms: 1.04x slower                                |
| json_loads               | 16.9 us                                                | 17.6 us: 1.04x slower                                |
| regex_effbot             | 2.45 ms                                                | 2.59 ms: 1.06x slower                                |
| sqlite_synth             | 1.47 us                                                | 1.58 us: 1.08x slower                                |
| bench_mp_pool            | 41.0 ms                                                | 45.0 ms: 1.10x slower                                |
| unpickle_list            | 2.66 us                                                | 3.26 us: 1.22x slower                                |
| coverage                 | 40.8 ms                                                | 50.9 ms: 1.25x slower                                |
| async_generators         | 233 ms                                                 | 304 ms: 1.31x slower                                 |
| Geometric mean           | (ref)                                                  | 1.22x faster                                         |

Benchmark hidden because not significant (3): pickle, gc_traversal, mdp
Ignored benchmarks (14) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
