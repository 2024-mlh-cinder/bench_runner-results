
# Results vs. 3.10.4

- fork: python
- ref: main
- machine: darwin-arm64
- commit hash: 853b4b5
- commit date: 2023-11-04
- overall geometric mean: 1.17x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.10x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 174 ms: 1.09x faster                                   |
| chameleon      | 5.95 ms                                                | 4.68 ms: 1.27x faster                                  |
| docutils       | 1.73 sec                                               | 1.50 sec: 1.15x faster                                 |
| tornado_http   | 89.9 ms                                                | 69.7 ms: 1.29x faster                                  |
| Geometric mean | (ref)                                                  | 1.20x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 257 ms: 1.50x faster                                   |
| async_tree_memoization  | 473 ms                                                 | 334 ms: 1.42x faster                                   |
| async_tree_io           | 984 ms                                                 | 710 ms: 1.39x faster                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 530 ms: 1.22x faster                                   |
| Geometric mean          | (ref)                                                  | 1.38x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 66.8 ms                                                | 57.7 ms: 1.16x faster                                  |
| nbody          | 88.1 ms                                                | 78.5 ms: 1.12x faster                                  |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                   |
| Geometric mean | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 76.2 ms: 1.21x faster                                  |
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                   |
| regex_v8       | 17.2 ms                                                | 16.8 ms: 1.02x faster                                  |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| Geometric mean | (ref)                                                  | 1.09x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 199 us: 1.37x faster                                   |
| unpickle_pure_python | 191 us                                                 | 156 us: 1.22x faster                                   |
| json_dumps           | 8.00 ms                                                | 6.60 ms: 1.21x faster                                  |
| xml_etree_process    | 45.6 ms                                                | 39.8 ms: 1.15x faster                                  |
| tomli_loads          | 1.65 sec                                               | 1.56 sec: 1.06x faster                                 |
| unpickle             | 8.86 us                                                | 9.15 us: 1.03x slower                                  |
| json_loads           | 16.7 us                                                | 17.5 us: 1.04x slower                                  |
| pickle               | 7.04 us                                                | 7.38 us: 1.05x slower                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 76.3 ms: 1.05x slower                                  |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                  |
| pickle_list          | 2.72 us                                                | 2.92 us: 1.07x slower                                  |
| xml_etree_generate   | 53.2 ms                                                | 57.8 ms: 1.09x slower                                  |
| unpickle_list        | 2.79 us                                                | 3.11 us: 1.12x slower                                  |
| Geometric mean       | (ref)                                                  | 1.03x faster                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 13.0 ms: 1.11x slower                                  |
| python_startup_no_site | 8.64 ms                                                | 11.7 ms: 1.35x slower                                  |
| Geometric mean         | (ref)                                                  | 1.23x slower                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|-----------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.50 ms: 1.31x faster                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5 |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 74.2 us: 4.53x faster                                  |
| deltablue                | 4.94 ms                                                | 2.43 ms: 2.03x faster                                  |
| logging_silent           | 115 ns                                                 | 69.6 ns: 1.65x faster                                  |
| raytrace                 | 293 ms                                                 | 180 ms: 1.63x faster                                   |
| asyncio_tcp              | 667 ms                                                 | 429 ms: 1.56x faster                                   |
| chaos                    | 64.1 ms                                                | 41.5 ms: 1.55x faster                                  |
| async_tree_none          | 384 ms                                                 | 257 ms: 1.50x faster                                   |
| richards_super           | 57.1 ms                                                | 38.3 ms: 1.49x faster                                  |
| crypto_pyaes             | 70.8 ms                                                | 48.0 ms: 1.48x faster                                  |
| sqlglot_parse            | 1.20 ms                                                | 828 us: 1.45x faster                                   |
| comprehensions           | 16.8 us                                                | 11.8 us: 1.42x faster                                  |
| async_tree_memoization   | 473 ms                                                 | 334 ms: 1.42x faster                                   |
| go                       | 148 ms                                                 | 105 ms: 1.41x faster                                   |
| sqlglot_transpile        | 1.40 ms                                                | 1.01 ms: 1.39x faster                                  |
| unpack_sequence          | 36.7 ns                                                | 26.5 ns: 1.39x faster                                  |
| async_tree_io            | 984 ms                                                 | 710 ms: 1.39x faster                                   |
| scimark_lu               | 102 ms                                                 | 73.3 ms: 1.39x faster                                  |
| pickle_pure_python       | 272 us                                                 | 199 us: 1.37x faster                                   |
| richards                 | 47.6 ms                                                | 34.9 ms: 1.37x faster                                  |
| deepcopy_memo            | 33.1 us                                                | 24.6 us: 1.35x faster                                  |
| generators               | 32.6 ms                                                | 24.4 ms: 1.34x faster                                  |
| scimark_monte_carlo      | 62.8 ms                                                | 47.4 ms: 1.33x faster                                  |
| mako                     | 9.86 ms                                                | 7.50 ms: 1.31x faster                                  |
| tornado_http             | 89.9 ms                                                | 69.7 ms: 1.29x faster                                  |
| hexiom                   | 6.07 ms                                                | 4.74 ms: 1.28x faster                                  |
| scimark_sor              | 134 ms                                                 | 105 ms: 1.27x faster                                   |
| chameleon                | 5.95 ms                                                | 4.68 ms: 1.27x faster                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.29 sec: 1.27x faster                                 |
| spectral_norm            | 92.1 ms                                                | 73.1 ms: 1.26x faster                                  |
| pycparser                | 878 ms                                                 | 698 ms: 1.26x faster                                   |
| sympy_sum                | 92.4 ms                                                | 74.4 ms: 1.24x faster                                  |
| pprint_pformat           | 1.27 sec                                               | 1.03 sec: 1.23x faster                                 |
| create_gc_cycles         | 865 us                                                 | 701 us: 1.23x faster                                   |
| pprint_safe_repr         | 628 ms                                                 | 510 ms: 1.23x faster                                   |
| pyflate                  | 419 ms                                                 | 341 ms: 1.23x faster                                   |
| unpickle_pure_python     | 191 us                                                 | 156 us: 1.22x faster                                   |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 530 ms: 1.22x faster                                   |
| deepcopy                 | 269 us                                                 | 221 us: 1.22x faster                                   |
| json_dumps               | 8.00 ms                                                | 6.60 ms: 1.21x faster                                  |
| regex_compile            | 92.3 ms                                                | 76.2 ms: 1.21x faster                                  |
| sympy_integrate          | 13.2 ms                                                | 10.9 ms: 1.21x faster                                  |
| dulwich_log              | 35.6 ms                                                | 30.2 ms: 1.18x faster                                  |
| logging_format           | 4.62 us                                                | 3.93 us: 1.18x faster                                  |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                   |
| logging_simple           | 4.25 us                                                | 3.64 us: 1.17x faster                                  |
| float                    | 66.8 ms                                                | 57.7 ms: 1.16x faster                                  |
| deepcopy_reduce          | 2.28 us                                                | 1.97 us: 1.16x faster                                  |
| docutils                 | 1.73 sec                                               | 1.50 sec: 1.15x faster                                 |
| mdp                      | 1.87 sec                                               | 1.62 sec: 1.15x faster                                 |
| mypy2                    | 300 ms                                                 | 261 ms: 1.15x faster                                   |
| xml_etree_process        | 45.6 ms                                                | 39.8 ms: 1.15x faster                                  |
| sympy_str                | 164 ms                                                 | 144 ms: 1.14x faster                                   |
| nbody                    | 88.1 ms                                                | 78.5 ms: 1.12x faster                                  |
| coroutines               | 19.6 ms                                                | 18.0 ms: 1.09x faster                                  |
| 2to3                     | 189 ms                                                 | 174 ms: 1.09x faster                                   |
| sympy_expand             | 267 ms                                                 | 247 ms: 1.08x faster                                   |
| nqueens                  | 62.4 ms                                                | 58.6 ms: 1.06x faster                                  |
| scimark_fft              | 216 ms                                                 | 204 ms: 1.06x faster                                   |
| tomli_loads              | 1.65 sec                                               | 1.56 sec: 1.06x faster                                 |
| fannkuch                 | 294 ms                                                 | 279 ms: 1.05x faster                                   |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.10 ms: 1.05x faster                                  |
| sqlglot_optimize         | 36.3 ms                                                | 34.6 ms: 1.05x faster                                  |
| bench_thread_pool        | 516 us                                                 | 492 us: 1.05x faster                                   |
| meteor_contest           | 77.9 ms                                                | 74.7 ms: 1.04x faster                                  |
| regex_v8                 | 17.2 ms                                                | 16.8 ms: 1.02x faster                                  |
| json                     | 3.06 ms                                                | 3.00 ms: 1.02x faster                                  |
| sqlglot_normalize        | 187 ms                                                 | 186 ms: 1.01x faster                                   |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x slower                                   |
| asyncio_websockets       | 544 ms                                                 | 545 ms: 1.00x slower                                   |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                  |
| unpickle                 | 8.86 us                                                | 9.15 us: 1.03x slower                                  |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                  |
| json_loads               | 16.7 us                                                | 17.5 us: 1.04x slower                                  |
| pickle                   | 7.04 us                                                | 7.38 us: 1.05x slower                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 76.3 ms: 1.05x slower                                  |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.05x slower                                  |
| pickle_list              | 2.72 us                                                | 2.92 us: 1.07x slower                                  |
| xml_etree_generate       | 53.2 ms                                                | 57.8 ms: 1.09x slower                                  |
| python_startup           | 11.7 ms                                                | 13.0 ms: 1.11x slower                                  |
| unpickle_list            | 2.79 us                                                | 3.11 us: 1.12x slower                                  |
| sqlite_synth             | 1.43 us                                                | 1.62 us: 1.13x slower                                  |
| coverage                 | 41.1 ms                                                | 47.8 ms: 1.16x slower                                  |
| bench_mp_pool            | 39.0 ms                                                | 45.6 ms: 1.17x slower                                  |
| async_generators         | 233 ms                                                 | 298 ms: 1.28x slower                                   |
| python_startup_no_site   | 8.64 ms                                                | 11.7 ms: 1.35x slower                                  |
| telco                    | 3.42 ms                                                | 4.69 ms: 1.37x slower                                  |
| Geometric mean           | (ref)                                                  | 1.17x faster                                           |

Benchmark hidden because not significant (2): xml_etree_parse, pathlib
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231104-3.13.0a1+-853b4b5/bm-20231104-darwin-arm64-python-main-3.13.0a1+-853b4b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.10x
