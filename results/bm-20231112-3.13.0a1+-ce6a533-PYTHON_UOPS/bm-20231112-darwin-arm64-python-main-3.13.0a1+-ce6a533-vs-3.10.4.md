
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: ce6a533
- commit date: 2023-11-12
- overall geometric mean: 1.08x faster \*
- HPT reliability: 99.82%
- HPT 99th percentile: 1.01x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 186 ms: 1.02x faster                                   |
| chameleon      | 5.95 ms                                                | 5.01 ms: 1.19x faster                                  |
| docutils       | 1.73 sec                                               | 1.55 sec: 1.12x faster                                 |
| tornado_http   | 89.9 ms                                                | 72.3 ms: 1.24x faster                                  |
| Geometric mean | (ref)                                                  | 1.14x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 270 ms: 1.42x faster                                   |
| async_tree_memoization  | 473 ms                                                 | 346 ms: 1.37x faster                                   |
| async_tree_io           | 984 ms                                                 | 729 ms: 1.35x faster                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 542 ms: 1.19x faster                                   |
| Geometric mean          | (ref)                                                  | 1.33x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| nbody          | 88.1 ms                                                | 98.8 ms: 1.12x slower                                  |
| float          | 66.8 ms                                                | 75.9 ms: 1.14x slower                                  |
| Geometric mean | (ref)                                                  | 1.09x slower                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                   |
| regex_v8       | 17.2 ms                                                | 17.0 ms: 1.01x faster                                  |
| regex_compile  | 92.3 ms                                                | 93.2 ms: 1.01x slower                                  |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.03x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 201 us: 1.36x faster                                   |
| json_dumps           | 8.00 ms                                                | 6.56 ms: 1.22x faster                                  |
| xml_etree_process    | 45.6 ms                                                | 40.0 ms: 1.14x faster                                  |
| unpickle_pure_python | 191 us                                                 | 177 us: 1.08x faster                                   |
| unpickle             | 8.86 us                                                | 9.17 us: 1.03x slower                                  |
| json_loads           | 16.7 us                                                | 17.6 us: 1.05x slower                                  |
| pickle               | 7.04 us                                                | 7.44 us: 1.06x slower                                  |
| pickle_list          | 2.72 us                                                | 2.88 us: 1.06x slower                                  |
| pickle_dict          | 17.0 us                                                | 18.1 us: 1.06x slower                                  |
| xml_etree_generate   | 53.2 ms                                                | 59.2 ms: 1.11x slower                                  |
| unpickle_list        | 2.79 us                                                | 3.13 us: 1.12x slower                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 82.1 ms: 1.13x slower                                  |
| tomli_loads          | 1.65 sec                                               | 2.05 sec: 1.24x slower                                 |
| Geometric mean       | (ref)                                                  | 1.01x slower                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.2 ms: 1.05x slower                                  |
| python_startup_no_site | 8.64 ms                                                | 10.9 ms: 1.26x slower                                  |
| Geometric mean         | (ref)                                                  | 1.15x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 9.86 ms                                                | 10.5 ms: 1.07x slower                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 81.3 us: 4.14x faster                                  |
| logging_silent           | 115 ns                                                 | 72.3 ns: 1.59x faster                                  |
| asyncio_tcp              | 667 ms                                                 | 438 ms: 1.52x faster                                   |
| richards_super           | 57.1 ms                                                | 38.5 ms: 1.48x faster                                  |
| raytrace                 | 293 ms                                                 | 198 ms: 1.48x faster                                   |
| async_tree_none          | 384 ms                                                 | 270 ms: 1.42x faster                                   |
| sqlglot_parse            | 1.20 ms                                                | 862 us: 1.39x faster                                   |
| unpack_sequence          | 36.7 ns                                                | 26.7 ns: 1.37x faster                                  |
| async_tree_memoization   | 473 ms                                                 | 346 ms: 1.37x faster                                   |
| richards                 | 47.6 ms                                                | 35.0 ms: 1.36x faster                                  |
| pickle_pure_python       | 272 us                                                 | 201 us: 1.36x faster                                   |
| async_tree_io            | 984 ms                                                 | 729 ms: 1.35x faster                                   |
| sqlglot_transpile        | 1.40 ms                                                | 1.05 ms: 1.34x faster                                  |
| generators               | 32.6 ms                                                | 24.7 ms: 1.32x faster                                  |
| chaos                    | 64.1 ms                                                | 49.1 ms: 1.31x faster                                  |
| scimark_lu               | 102 ms                                                 | 78.4 ms: 1.30x faster                                  |
| deltablue                | 4.94 ms                                                | 3.90 ms: 1.27x faster                                  |
| spectral_norm            | 92.1 ms                                                | 72.9 ms: 1.26x faster                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.26x faster                                 |
| tornado_http             | 89.9 ms                                                | 72.3 ms: 1.24x faster                                  |
| go                       | 148 ms                                                 | 119 ms: 1.24x faster                                   |
| create_gc_cycles         | 865 us                                                 | 700 us: 1.24x faster                                   |
| scimark_sor              | 134 ms                                                 | 109 ms: 1.23x faster                                   |
| crypto_pyaes             | 70.8 ms                                                | 57.9 ms: 1.22x faster                                  |
| json_dumps               | 8.00 ms                                                | 6.56 ms: 1.22x faster                                  |
| pycparser                | 878 ms                                                 | 721 ms: 1.22x faster                                   |
| deepcopy_memo            | 33.1 us                                                | 27.4 us: 1.20x faster                                  |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 542 ms: 1.19x faster                                   |
| deepcopy                 | 269 us                                                 | 226 us: 1.19x faster                                   |
| chameleon                | 5.95 ms                                                | 5.01 ms: 1.19x faster                                  |
| sympy_sum                | 92.4 ms                                                | 78.0 ms: 1.18x faster                                  |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                   |
| logging_format           | 4.62 us                                                | 4.00 us: 1.16x faster                                  |
| dulwich_log              | 35.6 ms                                                | 30.9 ms: 1.15x faster                                  |
| logging_simple           | 4.25 us                                                | 3.72 us: 1.14x faster                                  |
| deepcopy_reduce          | 2.28 us                                                | 1.99 us: 1.14x faster                                  |
| xml_etree_process        | 45.6 ms                                                | 40.0 ms: 1.14x faster                                  |
| docutils                 | 1.73 sec                                               | 1.55 sec: 1.12x faster                                 |
| scimark_monte_carlo      | 62.8 ms                                                | 57.3 ms: 1.10x faster                                  |
| pprint_safe_repr         | 628 ms                                                 | 579 ms: 1.09x faster                                   |
| sympy_integrate          | 13.2 ms                                                | 12.2 ms: 1.08x faster                                  |
| sympy_str                | 164 ms                                                 | 152 ms: 1.08x faster                                   |
| coroutines               | 19.6 ms                                                | 18.2 ms: 1.08x faster                                  |
| unpickle_pure_python     | 191 us                                                 | 177 us: 1.08x faster                                   |
| pprint_pformat           | 1.27 sec                                               | 1.18 sec: 1.08x faster                                 |
| mdp                      | 1.87 sec                                               | 1.78 sec: 1.05x faster                                 |
| sympy_expand             | 267 ms                                                 | 256 ms: 1.04x faster                                   |
| pyflate                  | 419 ms                                                 | 403 ms: 1.04x faster                                   |
| sqlglot_optimize         | 36.3 ms                                                | 35.3 ms: 1.03x faster                                  |
| 2to3                     | 189 ms                                                 | 186 ms: 1.02x faster                                   |
| json                     | 3.06 ms                                                | 3.01 ms: 1.02x faster                                  |
| regex_v8                 | 17.2 ms                                                | 17.0 ms: 1.01x faster                                  |
| bench_thread_pool        | 516 us                                                 | 514 us: 1.00x faster                                   |
| asyncio_websockets       | 544 ms                                                 | 545 ms: 1.00x slower                                   |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                   |
| regex_compile            | 92.3 ms                                                | 93.2 ms: 1.01x slower                                  |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                  |
| sqlglot_normalize        | 187 ms                                                 | 190 ms: 1.02x slower                                   |
| pathlib                  | 29.4 ms                                                | 30.0 ms: 1.02x slower                                  |
| unpickle                 | 8.86 us                                                | 9.17 us: 1.03x slower                                  |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| python_startup           | 11.7 ms                                                | 12.2 ms: 1.05x slower                                  |
| json_loads               | 16.7 us                                                | 17.6 us: 1.05x slower                                  |
| pickle                   | 7.04 us                                                | 7.44 us: 1.06x slower                                  |
| pickle_list              | 2.72 us                                                | 2.88 us: 1.06x slower                                  |
| pickle_dict              | 17.0 us                                                | 18.1 us: 1.06x slower                                  |
| mako                     | 9.86 ms                                                | 10.5 ms: 1.07x slower                                  |
| meteor_contest           | 77.9 ms                                                | 83.8 ms: 1.08x slower                                  |
| xml_etree_generate       | 53.2 ms                                                | 59.2 ms: 1.11x slower                                  |
| nbody                    | 88.1 ms                                                | 98.8 ms: 1.12x slower                                  |
| unpickle_list            | 2.79 us                                                | 3.13 us: 1.12x slower                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 82.1 ms: 1.13x slower                                  |
| float                    | 66.8 ms                                                | 75.9 ms: 1.14x slower                                  |
| bench_mp_pool            | 39.0 ms                                                | 44.9 ms: 1.15x slower                                  |
| coverage                 | 41.1 ms                                                | 47.5 ms: 1.16x slower                                  |
| sqlite_synth             | 1.43 us                                                | 1.69 us: 1.19x slower                                  |
| comprehensions           | 16.8 us                                                | 19.9 us: 1.19x slower                                  |
| scimark_fft              | 216 ms                                                 | 258 ms: 1.19x slower                                   |
| tomli_loads              | 1.65 sec                                               | 2.05 sec: 1.24x slower                                 |
| hexiom                   | 6.07 ms                                                | 7.57 ms: 1.25x slower                                  |
| python_startup_no_site   | 8.64 ms                                                | 10.9 ms: 1.26x slower                                  |
| nqueens                  | 62.4 ms                                                | 80.1 ms: 1.28x slower                                  |
| async_generators         | 233 ms                                                 | 312 ms: 1.34x slower                                   |
| fannkuch                 | 294 ms                                                 | 396 ms: 1.35x slower                                   |
| telco                    | 3.42 ms                                                | 5.07 ms: 1.48x slower                                  |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 4.98 ms: 1.53x slower                                  |
| Geometric mean           | (ref)                                                  | 1.08x faster                                           |

Benchmark hidden because not significant (2): mypy2, xml_etree_parse
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231112-3.13.0a1+-ce6a533-PYTHON_UOPS/bm-20231112-darwin-arm64-python-main-3.13.0a1+-ce6a533.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 99.82% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.03x
- 99% likely to have a speedup of 1.01x
