
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_opargs
- machine: darwin-arm64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.53 sec: 1.17x faster                                               |
| tornado_http   | 91.9 ms                                                | 72.0 ms: 1.28x faster                                                |
| Geometric mean | (ref)                                                  | 1.22x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 72.3 ms                                                | 57.0 ms: 1.27x faster                                                |
| nbody          | 94.1 ms                                                | 76.1 ms: 1.24x faster                                                |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                  | 1.16x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 80.4 ms: 1.20x faster                                                |
| regex_dna      | 160 ms                                                 | 142 ms: 1.12x faster                                                 |
| regex_v8       | 17.5 ms                                                | 16.4 ms: 1.07x faster                                                |
| regex_effbot   | 2.45 ms                                                | 2.52 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                  | 1.09x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 194 us: 1.46x faster                                                 |
| json_dumps           | 8.38 ms                                                | 6.49 ms: 1.29x faster                                                |
| unpickle_pure_python | 203 us                                                 | 161 us: 1.26x faster                                                 |
| tomli_loads          | 1.76 sec                                               | 1.47 sec: 1.20x faster                                               |
| xml_etree_process    | 45.1 ms                                                | 40.1 ms: 1.12x faster                                                |
| unpickle             | 9.77 us                                                | 9.23 us: 1.06x faster                                                |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.00x slower                                                |
| pickle               | 7.36 us                                                | 7.39 us: 1.00x slower                                                |
| pickle_list          | 2.83 us                                                | 2.90 us: 1.02x slower                                                |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                                 |
| json_loads           | 16.9 us                                                | 17.7 us: 1.05x slower                                                |
| xml_etree_iterparse  | 72.6 ms                                                | 77.2 ms: 1.06x slower                                                |
| xml_etree_generate   | 54.3 ms                                                | 58.0 ms: 1.07x slower                                                |
| unpickle_list        | 2.66 us                                                | 3.16 us: 1.19x slower                                                |
| Geometric mean       | (ref)                                                  | 1.06x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup         | 12.6 ms                                                | 12.4 ms: 1.01x faster                                                |
| python_startup_no_site | 9.73 ms                                                | 10.5 ms: 1.08x slower                                                |
| Geometric mean         | (ref)                                                  | 1.03x slower                                                         |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.47 ms: 1.40x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 94.4 us: 3.65x faster                                                |
| deltablue                | 5.15 ms                                                | 2.50 ms: 2.06x faster                                                |
| raytrace                 | 328 ms                                                 | 180 ms: 1.82x faster                                                 |
| logging_silent           | 119 ns                                                 | 72.4 ns: 1.64x faster                                                |
| sqlglot_parse            | 1.33 ms                                                | 817 us: 1.63x faster                                                 |
| richards_super           | 60.7 ms                                                | 37.7 ms: 1.61x faster                                                |
| crypto_pyaes             | 78.0 ms                                                | 48.5 ms: 1.61x faster                                                |
| chaos                    | 66.8 ms                                                | 41.8 ms: 1.60x faster                                                |
| async_tree_none          | 402 ms                                                 | 254 ms: 1.59x faster                                                 |
| scimark_monte_carlo      | 72.2 ms                                                | 46.2 ms: 1.56x faster                                                |
| asyncio_tcp              | 673 ms                                                 | 430 ms: 1.56x faster                                                 |
| sqlglot_transpile        | 1.54 ms                                                | 998 us: 1.54x faster                                                 |
| go                       | 165 ms                                                 | 108 ms: 1.53x faster                                                 |
| scimark_lu               | 110 ms                                                 | 72.9 ms: 1.51x faster                                                |
| async_tree_memoization   | 493 ms                                                 | 329 ms: 1.50x faster                                                 |
| richards                 | 51.4 ms                                                | 34.4 ms: 1.49x faster                                                |
| async_tree_io            | 1.02 sec                                               | 691 ms: 1.47x faster                                                 |
| unpack_sequence          | 38.7 ns                                                | 26.4 ns: 1.47x faster                                                |
| pickle_pure_python       | 284 us                                                 | 194 us: 1.46x faster                                                 |
| mako                     | 10.5 ms                                                | 7.47 ms: 1.40x faster                                                |
| deepcopy_memo            | 34.5 us                                                | 25.3 us: 1.36x faster                                                |
| pyflate                  | 453 ms                                                 | 336 ms: 1.35x faster                                                 |
| pycparser                | 915 ms                                                 | 694 ms: 1.32x faster                                                 |
| generators               | 32.9 ms                                                | 25.0 ms: 1.32x faster                                                |
| logging_format           | 5.01 us                                                | 3.86 us: 1.30x faster                                                |
| json_dumps               | 8.38 ms                                                | 6.49 ms: 1.29x faster                                                |
| spectral_norm            | 96.4 ms                                                | 74.7 ms: 1.29x faster                                                |
| logging_simple           | 4.63 us                                                | 3.60 us: 1.28x faster                                                |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 524 ms: 1.28x faster                                                 |
| tornado_http             | 91.9 ms                                                | 72.0 ms: 1.28x faster                                                |
| float                    | 72.3 ms                                                | 57.0 ms: 1.27x faster                                                |
| unpickle_pure_python     | 203 us                                                 | 161 us: 1.26x faster                                                 |
| create_gc_cycles         | 876 us                                                 | 697 us: 1.26x faster                                                 |
| hexiom                   | 6.32 ms                                                | 5.10 ms: 1.24x faster                                                |
| nbody                    | 94.1 ms                                                | 76.1 ms: 1.24x faster                                                |
| deepcopy                 | 278 us                                                 | 228 us: 1.22x faster                                                 |
| pprint_pformat           | 1.24 sec                                               | 1.03 sec: 1.21x faster                                               |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.36 sec: 1.21x faster                                               |
| pprint_safe_repr         | 609 ms                                                 | 505 ms: 1.20x faster                                                 |
| regex_compile            | 96.6 ms                                                | 80.4 ms: 1.20x faster                                                |
| dulwich_log              | 37.1 ms                                                | 30.9 ms: 1.20x faster                                                |
| tomli_loads              | 1.76 sec                                               | 1.47 sec: 1.20x faster                                               |
| scimark_sor              | 127 ms                                                 | 106 ms: 1.19x faster                                                 |
| deepcopy_reduce          | 2.38 us                                                | 2.04 us: 1.17x faster                                                |
| mypy2                    | 308 ms                                                 | 264 ms: 1.17x faster                                                 |
| docutils                 | 1.78 sec                                               | 1.53 sec: 1.17x faster                                               |
| scimark_fft              | 232 ms                                                 | 205 ms: 1.13x faster                                                 |
| xml_etree_process        | 45.1 ms                                                | 40.1 ms: 1.12x faster                                                |
| regex_dna                | 160 ms                                                 | 142 ms: 1.12x faster                                                 |
| fannkuch                 | 317 ms                                                 | 283 ms: 1.12x faster                                                 |
| coroutines               | 20.2 ms                                                | 18.0 ms: 1.12x faster                                                |
| bench_thread_pool        | 548 us                                                 | 500 us: 1.10x faster                                                 |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.17 ms: 1.10x faster                                                |
| sqlglot_optimize         | 38.0 ms                                                | 35.3 ms: 1.08x faster                                                |
| regex_v8                 | 17.5 ms                                                | 16.4 ms: 1.07x faster                                                |
| comprehensions           | 17.7 us                                                | 16.6 us: 1.07x faster                                                |
| unpickle                 | 9.77 us                                                | 9.23 us: 1.06x faster                                                |
| nqueens                  | 68.1 ms                                                | 64.4 ms: 1.06x faster                                                |
| json                     | 3.10 ms                                                | 3.03 ms: 1.02x faster                                                |
| sqlglot_normalize        | 197 ms                                                 | 193 ms: 1.02x faster                                                 |
| python_startup           | 12.6 ms                                                | 12.4 ms: 1.01x faster                                                |
| meteor_contest           | 78.6 ms                                                | 78.1 ms: 1.01x faster                                                |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                                 |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.00x slower                                                |
| pickle                   | 7.36 us                                                | 7.39 us: 1.00x slower                                                |
| pickle_list              | 2.83 us                                                | 2.90 us: 1.02x slower                                                |
| xml_etree_parse          | 107 ms                                                 | 110 ms: 1.03x slower                                                 |
| regex_effbot             | 2.45 ms                                                | 2.52 ms: 1.03x slower                                                |
| json_loads               | 16.9 us                                                | 17.7 us: 1.05x slower                                                |
| xml_etree_iterparse      | 72.6 ms                                                | 77.2 ms: 1.06x slower                                                |
| xml_etree_generate       | 54.3 ms                                                | 58.0 ms: 1.07x slower                                                |
| python_startup_no_site   | 9.73 ms                                                | 10.5 ms: 1.08x slower                                                |
| sqlite_synth             | 1.47 us                                                | 1.60 us: 1.09x slower                                                |
| pathlib                  | 28.8 ms                                                | 32.8 ms: 1.14x slower                                                |
| coverage                 | 40.8 ms                                                | 47.1 ms: 1.15x slower                                                |
| bench_mp_pool            | 41.0 ms                                                | 48.4 ms: 1.18x slower                                                |
| unpickle_list            | 2.66 us                                                | 3.16 us: 1.19x slower                                                |
| telco                    | 3.68 ms                                                | 4.57 ms: 1.24x slower                                                |
| dask                     | 258 ms                                                 | 335 ms: 1.30x slower                                                 |
| async_generators         | 233 ms                                                 | 310 ms: 1.33x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.20x faster                                                         |

Benchmark hidden because not significant (2): mdp, gc_traversal
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.12x
