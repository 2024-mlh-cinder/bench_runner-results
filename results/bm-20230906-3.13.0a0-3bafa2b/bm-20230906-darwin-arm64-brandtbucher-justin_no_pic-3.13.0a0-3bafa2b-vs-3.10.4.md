
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_pic
- machine: darwin-arm64
- commit hash: 3bafa2b
- commit date: 2023-09-06
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| docutils       | 1.78 sec                                               | 1.53 sec: 1.16x faster                                               |
| tornado_http   | 91.9 ms                                                | 70.3 ms: 1.31x faster                                                |
| Geometric mean | (ref)                                                  | 1.23x faster                                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| float          | 72.3 ms                                                | 57.1 ms: 1.27x faster                                                |
| nbody          | 94.1 ms                                                | 78.8 ms: 1.19x faster                                                |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                                 |
| Geometric mean | (ref)                                                  | 1.15x faster                                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| regex_compile  | 96.6 ms                                                | 81.8 ms: 1.18x faster                                                |
| regex_dna      | 160 ms                                                 | 140 ms: 1.14x faster                                                 |
| regex_v8       | 17.5 ms                                                | 16.5 ms: 1.06x faster                                                |
| regex_effbot   | 2.45 ms                                                | 2.51 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                  | 1.09x faster                                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| pickle_pure_python   | 284 us                                                 | 195 us: 1.46x faster                                                 |
| json_dumps           | 8.38 ms                                                | 6.53 ms: 1.28x faster                                                |
| unpickle_pure_python | 203 us                                                 | 164 us: 1.24x faster                                                 |
| tomli_loads          | 1.76 sec                                               | 1.53 sec: 1.15x faster                                               |
| xml_etree_process    | 45.1 ms                                                | 40.0 ms: 1.13x faster                                                |
| unpickle             | 9.77 us                                                | 9.18 us: 1.06x faster                                                |
| pickle_dict          | 17.8 us                                                | 17.9 us: 1.01x slower                                                |
| pickle               | 7.36 us                                                | 7.40 us: 1.01x slower                                                |
| pickle_list          | 2.83 us                                                | 2.90 us: 1.02x slower                                                |
| xml_etree_parse      | 107 ms                                                 | 110 ms: 1.03x slower                                                 |
| json_loads           | 16.9 us                                                | 17.6 us: 1.04x slower                                                |
| xml_etree_iterparse  | 72.6 ms                                                | 77.2 ms: 1.06x slower                                                |
| xml_etree_generate   | 54.3 ms                                                | 58.2 ms: 1.07x slower                                                |
| unpickle_list        | 2.66 us                                                | 3.18 us: 1.19x slower                                                |
| Geometric mean       | (ref)                                                  | 1.05x faster                                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| python_startup_no_site | 9.73 ms                                                | 10.5 ms: 1.08x slower                                                |
| Geometric mean         | (ref)                                                  | 1.04x slower                                                         |

Benchmark hidden because not significant (1): python_startup

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| mako      | 10.5 ms                                                | 7.66 ms: 1.37x faster                                                |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-darwin-arm64-brandtbucher-justin_no_pic-3.13.0a0-3bafa2b |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------------:|
| typing_runtime_protocols | 344 us                                                 | 95.1 us: 3.62x faster                                                |
| deltablue                | 5.15 ms                                                | 2.50 ms: 2.06x faster                                                |
| raytrace                 | 328 ms                                                 | 180 ms: 1.82x faster                                                 |
| logging_silent           | 119 ns                                                 | 72.3 ns: 1.65x faster                                                |
| asyncio_tcp              | 673 ms                                                 | 413 ms: 1.63x faster                                                 |
| sqlglot_parse            | 1.33 ms                                                | 818 us: 1.63x faster                                                 |
| crypto_pyaes             | 78.0 ms                                                | 48.6 ms: 1.60x faster                                                |
| richards_super           | 60.7 ms                                                | 38.0 ms: 1.60x faster                                                |
| async_tree_none          | 402 ms                                                 | 254 ms: 1.58x faster                                                 |
| chaos                    | 66.8 ms                                                | 42.3 ms: 1.58x faster                                                |
| scimark_monte_carlo      | 72.2 ms                                                | 46.3 ms: 1.56x faster                                                |
| sqlglot_transpile        | 1.54 ms                                                | 999 us: 1.54x faster                                                 |
| go                       | 165 ms                                                 | 108 ms: 1.53x faster                                                 |
| scimark_lu               | 110 ms                                                 | 73.1 ms: 1.50x faster                                                |
| async_tree_memoization   | 493 ms                                                 | 331 ms: 1.49x faster                                                 |
| richards                 | 51.4 ms                                                | 34.7 ms: 1.48x faster                                                |
| async_tree_io            | 1.02 sec                                               | 691 ms: 1.48x faster                                                 |
| pickle_pure_python       | 284 us                                                 | 195 us: 1.46x faster                                                 |
| unpack_sequence          | 38.7 ns                                                | 26.9 ns: 1.44x faster                                                |
| mako                     | 10.5 ms                                                | 7.66 ms: 1.37x faster                                                |
| deepcopy_memo            | 34.5 us                                                | 25.5 us: 1.35x faster                                                |
| pyflate                  | 453 ms                                                 | 341 ms: 1.33x faster                                                 |
| generators               | 32.9 ms                                                | 25.0 ms: 1.32x faster                                                |
| pycparser                | 915 ms                                                 | 696 ms: 1.31x faster                                                 |
| tornado_http             | 91.9 ms                                                | 70.3 ms: 1.31x faster                                                |
| spectral_norm            | 96.4 ms                                                | 74.4 ms: 1.30x faster                                                |
| logging_format           | 5.01 us                                                | 3.88 us: 1.29x faster                                                |
| json_dumps               | 8.38 ms                                                | 6.53 ms: 1.28x faster                                                |
| logging_simple           | 4.63 us                                                | 3.63 us: 1.28x faster                                                |
| async_tree_cpu_io_mixed  | 670 ms                                                 | 526 ms: 1.27x faster                                                 |
| float                    | 72.3 ms                                                | 57.1 ms: 1.27x faster                                                |
| create_gc_cycles         | 876 us                                                 | 699 us: 1.25x faster                                                 |
| unpickle_pure_python     | 203 us                                                 | 164 us: 1.24x faster                                                 |
| hexiom                   | 6.32 ms                                                | 5.19 ms: 1.22x faster                                                |
| deepcopy                 | 278 us                                                 | 229 us: 1.21x faster                                                 |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.36 sec: 1.21x faster                                               |
| pprint_safe_repr         | 609 ms                                                 | 507 ms: 1.20x faster                                                 |
| pprint_pformat           | 1.24 sec                                               | 1.03 sec: 1.20x faster                                               |
| dulwich_log              | 37.1 ms                                                | 31.0 ms: 1.19x faster                                                |
| nbody                    | 94.1 ms                                                | 78.8 ms: 1.19x faster                                                |
| scimark_sor              | 127 ms                                                 | 106 ms: 1.19x faster                                                 |
| regex_compile            | 96.6 ms                                                | 81.8 ms: 1.18x faster                                                |
| mypy2                    | 308 ms                                                 | 264 ms: 1.17x faster                                                 |
| deepcopy_reduce          | 2.38 us                                                | 2.04 us: 1.17x faster                                                |
| docutils                 | 1.78 sec                                               | 1.53 sec: 1.16x faster                                               |
| tomli_loads              | 1.76 sec                                               | 1.53 sec: 1.15x faster                                               |
| regex_dna                | 160 ms                                                 | 140 ms: 1.14x faster                                                 |
| xml_etree_process        | 45.1 ms                                                | 40.0 ms: 1.13x faster                                                |
| coroutines               | 20.2 ms                                                | 18.0 ms: 1.12x faster                                                |
| scimark_fft              | 232 ms                                                 | 210 ms: 1.11x faster                                                 |
| fannkuch                 | 317 ms                                                 | 289 ms: 1.10x faster                                                 |
| bench_thread_pool        | 548 us                                                 | 503 us: 1.09x faster                                                 |
| sqlglot_optimize         | 38.0 ms                                                | 35.4 ms: 1.07x faster                                                |
| regex_v8                 | 17.5 ms                                                | 16.5 ms: 1.06x faster                                                |
| unpickle                 | 9.77 us                                                | 9.18 us: 1.06x faster                                                |
| comprehensions           | 17.7 us                                                | 16.7 us: 1.06x faster                                                |
| nqueens                  | 68.1 ms                                                | 64.5 ms: 1.06x faster                                                |
| scimark_sparse_mat_mult  | 3.47 ms                                                | 3.35 ms: 1.04x faster                                                |
| json                     | 3.10 ms                                                | 3.01 ms: 1.03x faster                                                |
| sqlglot_normalize        | 197 ms                                                 | 193 ms: 1.02x faster                                                 |
| mdp                      | 1.67 sec                                               | 1.66 sec: 1.01x faster                                               |
| meteor_contest           | 78.6 ms                                                | 78.3 ms: 1.00x faster                                                |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x slower                                                 |
| pickle_dict              | 17.8 us                                                | 17.9 us: 1.01x slower                                                |
| pickle                   | 7.36 us                                                | 7.40 us: 1.01x slower                                                |
| pickle_list              | 2.83 us                                                | 2.90 us: 1.02x slower                                                |
| xml_etree_parse          | 107 ms                                                 | 110 ms: 1.03x slower                                                 |
| regex_effbot             | 2.45 ms                                                | 2.51 ms: 1.03x slower                                                |
| json_loads               | 16.9 us                                                | 17.6 us: 1.04x slower                                                |
| xml_etree_iterparse      | 72.6 ms                                                | 77.2 ms: 1.06x slower                                                |
| xml_etree_generate       | 54.3 ms                                                | 58.2 ms: 1.07x slower                                                |
| python_startup_no_site   | 9.73 ms                                                | 10.5 ms: 1.08x slower                                                |
| sqlite_synth             | 1.47 us                                                | 1.61 us: 1.09x slower                                                |
| pathlib                  | 28.8 ms                                                | 32.1 ms: 1.12x slower                                                |
| coverage                 | 40.8 ms                                                | 47.9 ms: 1.17x slower                                                |
| bench_mp_pool            | 41.0 ms                                                | 48.1 ms: 1.17x slower                                                |
| unpickle_list            | 2.66 us                                                | 3.18 us: 1.19x slower                                                |
| telco                    | 3.68 ms                                                | 4.62 ms: 1.25x slower                                                |
| dask                     | 258 ms                                                 | 334 ms: 1.30x slower                                                 |
| async_generators         | 233 ms                                                 | 312 ms: 1.34x slower                                                 |
| Geometric mean           | (ref)                                                  | 1.20x faster                                                         |

Benchmark hidden because not significant (2): gc_traversal, python_startup
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.12x
