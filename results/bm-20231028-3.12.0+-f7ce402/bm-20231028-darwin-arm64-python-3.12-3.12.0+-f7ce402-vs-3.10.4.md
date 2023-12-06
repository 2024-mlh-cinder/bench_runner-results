
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: darwin-arm64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.20x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.13x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 189 ms                                                 | 168 ms: 1.12x faster                                 |
| chameleon      | 5.95 ms                                                | 4.53 ms: 1.31x faster                                |
| docutils       | 1.73 sec                                               | 1.51 sec: 1.15x faster                               |
| tornado_http   | 89.9 ms                                                | 72.0 ms: 1.25x faster                                |
| Geometric mean | (ref)                                                  | 1.21x faster                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_memoization  | 473 ms                                                 | 311 ms: 1.52x faster                                 |
| async_tree_io           | 984 ms                                                 | 662 ms: 1.49x faster                                 |
| async_tree_none         | 384 ms                                                 | 263 ms: 1.46x faster                                 |
| async_tree_cpu_io_mixed | 646 ms                                                 | 526 ms: 1.23x faster                                 |
| Geometric mean          | (ref)                                                  | 1.42x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 88.1 ms                                                | 69.1 ms: 1.28x faster                                |
| float          | 66.8 ms                                                | 56.6 ms: 1.18x faster                                |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| Geometric mean | (ref)                                                  | 1.14x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 75.2 ms: 1.23x faster                                |
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                 |
| regex_v8       | 17.2 ms                                                | 15.6 ms: 1.10x faster                                |
| regex_effbot   | 2.46 ms                                                | 2.59 ms: 1.05x slower                                |
| Geometric mean | (ref)                                                  | 1.11x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 189 us: 1.44x faster                                 |
| unpickle_pure_python | 191 us                                                 | 144 us: 1.33x faster                                 |
| json_dumps           | 8.00 ms                                                | 6.31 ms: 1.27x faster                                |
| tomli_loads          | 1.65 sec                                               | 1.39 sec: 1.19x faster                               |
| xml_etree_process    | 45.6 ms                                                | 38.8 ms: 1.18x faster                                |
| xml_etree_parse      | 111 ms                                                 | 108 ms: 1.02x faster                                 |
| xml_etree_iterparse  | 72.7 ms                                                | 74.6 ms: 1.03x slower                                |
| pickle               | 7.04 us                                                | 7.33 us: 1.04x slower                                |
| xml_etree_generate   | 53.2 ms                                                | 55.9 ms: 1.05x slower                                |
| unpickle             | 8.86 us                                                | 9.33 us: 1.05x slower                                |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                |
| json_loads           | 16.7 us                                                | 17.7 us: 1.06x slower                                |
| pickle_list          | 2.72 us                                                | 2.91 us: 1.07x slower                                |
| unpickle_list        | 2.79 us                                                | 3.24 us: 1.16x slower                                |
| Geometric mean       | (ref)                                                  | 1.06x faster                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.1 ms: 1.04x slower                                |
| python_startup_no_site | 8.64 ms                                                | 9.88 ms: 1.14x slower                                |
| Geometric mean         | (ref)                                                  | 1.09x slower                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako            | 9.86 ms                                                | 7.53 ms: 1.31x faster                                |
| django_template | 25.8 ms                                                | 21.3 ms: 1.21x faster                                |
| Geometric mean  | (ref)                                                  | 1.26x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 91.2 us: 3.69x faster                                |
| deltablue                | 4.94 ms                                                | 2.41 ms: 2.05x faster                                |
| logging_silent           | 115 ns                                                 | 68.1 ns: 1.69x faster                                |
| richards_super           | 57.1 ms                                                | 34.0 ms: 1.68x faster                                |
| mypy2                    | 300 ms                                                 | 190 ms: 1.58x faster                                 |
| go                       | 148 ms                                                 | 94.3 ms: 1.57x faster                                |
| richards                 | 47.6 ms                                                | 30.5 ms: 1.56x faster                                |
| scimark_sor              | 134 ms                                                 | 86.7 ms: 1.54x faster                                |
| chaos                    | 64.1 ms                                                | 42.1 ms: 1.52x faster                                |
| async_tree_memoization   | 473 ms                                                 | 311 ms: 1.52x faster                                 |
| async_tree_io            | 984 ms                                                 | 662 ms: 1.49x faster                                 |
| async_tree_none          | 384 ms                                                 | 263 ms: 1.46x faster                                 |
| sqlglot_parse            | 1.20 ms                                                | 827 us: 1.45x faster                                 |
| asyncio_tcp              | 667 ms                                                 | 459 ms: 1.45x faster                                 |
| scimark_monte_carlo      | 62.8 ms                                                | 43.2 ms: 1.45x faster                                |
| pickle_pure_python       | 272 us                                                 | 189 us: 1.44x faster                                 |
| hexiom                   | 6.07 ms                                                | 4.28 ms: 1.42x faster                                |
| raytrace                 | 293 ms                                                 | 207 ms: 1.41x faster                                 |
| scimark_lu               | 102 ms                                                 | 72.2 ms: 1.41x faster                                |
| sqlglot_transpile        | 1.40 ms                                                | 1.00 ms: 1.40x faster                                |
| crypto_pyaes             | 70.8 ms                                                | 52.0 ms: 1.36x faster                                |
| unpickle_pure_python     | 191 us                                                 | 144 us: 1.33x faster                                 |
| deepcopy_memo            | 33.1 us                                                | 24.9 us: 1.33x faster                                |
| pyflate                  | 419 ms                                                 | 317 ms: 1.32x faster                                 |
| chameleon                | 5.95 ms                                                | 4.53 ms: 1.31x faster                                |
| mako                     | 9.86 ms                                                | 7.53 ms: 1.31x faster                                |
| pycparser                | 878 ms                                                 | 673 ms: 1.30x faster                                 |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.26 sec: 1.30x faster                               |
| unpack_sequence          | 36.7 ns                                                | 28.3 ns: 1.30x faster                                |
| pprint_safe_repr         | 628 ms                                                 | 490 ms: 1.28x faster                                 |
| pprint_pformat           | 1.27 sec                                               | 994 ms: 1.28x faster                                 |
| nbody                    | 88.1 ms                                                | 69.1 ms: 1.28x faster                                |
| json_dumps               | 8.00 ms                                                | 6.31 ms: 1.27x faster                                |
| sqlalchemy_imperative    | 8.65 ms                                                | 6.91 ms: 1.25x faster                                |
| generators               | 32.6 ms                                                | 26.1 ms: 1.25x faster                                |
| tornado_http             | 89.9 ms                                                | 72.0 ms: 1.25x faster                                |
| create_gc_cycles         | 865 us                                                 | 696 us: 1.24x faster                                 |
| regex_compile            | 92.3 ms                                                | 75.2 ms: 1.23x faster                                |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 526 ms: 1.23x faster                                 |
| spectral_norm            | 92.1 ms                                                | 75.1 ms: 1.23x faster                                |
| django_template          | 25.8 ms                                                | 21.3 ms: 1.21x faster                                |
| logging_format           | 4.62 us                                                | 3.87 us: 1.19x faster                                |
| tomli_loads              | 1.65 sec                                               | 1.39 sec: 1.19x faster                               |
| deepcopy                 | 269 us                                                 | 227 us: 1.18x faster                                 |
| logging_simple           | 4.25 us                                                | 3.60 us: 1.18x faster                                |
| float                    | 66.8 ms                                                | 56.6 ms: 1.18x faster                                |
| dulwich_log              | 35.6 ms                                                | 30.2 ms: 1.18x faster                                |
| xml_etree_process        | 45.6 ms                                                | 38.8 ms: 1.18x faster                                |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                 |
| sympy_sum                | 92.4 ms                                                | 79.4 ms: 1.16x faster                                |
| sympy_integrate          | 13.2 ms                                                | 11.4 ms: 1.16x faster                                |
| docutils                 | 1.73 sec                                               | 1.51 sec: 1.15x faster                               |
| mdp                      | 1.87 sec                                               | 1.64 sec: 1.14x faster                               |
| aiohttp                  | 1.29 ms                                                | 1.13 ms: 1.14x faster                                |
| sqlalchemy_declarative   | 73.7 ms                                                | 65.1 ms: 1.13x faster                                |
| coroutines               | 19.6 ms                                                | 17.4 ms: 1.13x faster                                |
| 2to3                     | 189 ms                                                 | 168 ms: 1.12x faster                                 |
| dask                     | 254 ms                                                 | 227 ms: 1.12x faster                                 |
| fannkuch                 | 294 ms                                                 | 265 ms: 1.11x faster                                 |
| deepcopy_reduce          | 2.28 us                                                | 2.05 us: 1.11x faster                                |
| comprehensions           | 16.8 us                                                | 15.2 us: 1.10x faster                                |
| regex_v8                 | 17.2 ms                                                | 15.6 ms: 1.10x faster                                |
| gunicorn                 | 1.35 ms                                                | 1.23 ms: 1.10x faster                                |
| coverage                 | 41.1 ms                                                | 37.6 ms: 1.09x faster                                |
| sympy_str                | 164 ms                                                 | 151 ms: 1.09x faster                                 |
| scimark_fft              | 216 ms                                                 | 201 ms: 1.08x faster                                 |
| sympy_expand             | 267 ms                                                 | 248 ms: 1.08x faster                                 |
| meteor_contest           | 77.9 ms                                                | 73.3 ms: 1.06x faster                                |
| sqlglot_optimize         | 36.3 ms                                                | 34.2 ms: 1.06x faster                                |
| bench_thread_pool        | 516 us                                                 | 486 us: 1.06x faster                                 |
| nqueens                  | 62.4 ms                                                | 59.3 ms: 1.05x faster                                |
| xml_etree_parse          | 111 ms                                                 | 108 ms: 1.02x faster                                 |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.19 ms: 1.02x faster                                |
| json                     | 3.06 ms                                                | 3.00 ms: 1.02x faster                                |
| sqlglot_normalize        | 187 ms                                                 | 185 ms: 1.01x faster                                 |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                 |
| asyncio_websockets       | 544 ms                                                 | 545 ms: 1.00x slower                                 |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                |
| xml_etree_iterparse      | 72.7 ms                                                | 74.6 ms: 1.03x slower                                |
| python_startup           | 11.7 ms                                                | 12.1 ms: 1.04x slower                                |
| pickle                   | 7.04 us                                                | 7.33 us: 1.04x slower                                |
| regex_effbot             | 2.46 ms                                                | 2.59 ms: 1.05x slower                                |
| xml_etree_generate       | 53.2 ms                                                | 55.9 ms: 1.05x slower                                |
| unpickle                 | 8.86 us                                                | 9.33 us: 1.05x slower                                |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.05x slower                                |
| json_loads               | 16.7 us                                                | 17.7 us: 1.06x slower                                |
| pickle_list              | 2.72 us                                                | 2.91 us: 1.07x slower                                |
| sqlite_synth             | 1.43 us                                                | 1.59 us: 1.11x slower                                |
| telco                    | 3.42 ms                                                | 3.82 ms: 1.12x slower                                |
| python_startup_no_site   | 8.64 ms                                                | 9.88 ms: 1.14x slower                                |
| unpickle_list            | 2.79 us                                                | 3.24 us: 1.16x slower                                |
| bench_mp_pool            | 39.0 ms                                                | 45.4 ms: 1.16x slower                                |
| async_generators         | 233 ms                                                 | 307 ms: 1.32x slower                                 |
| Geometric mean           | (ref)                                                  | 1.20x faster                                         |

Benchmark hidden because not significant (1): pathlib
Ignored benchmarks (6) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231028-3.12.0+-f7ce402/bm-20231028-darwin-arm64-python-3.12-3.12.0+-f7ce402.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.14x
- 99% likely to have a speedup of 1.13x
