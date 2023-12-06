
# Results vs. 3.10.4

- fork: python
- ref: fa84e5fe0a3bd8e77c33
- machine: darwin-arm64
- commit hash: fa84e5f
- commit date: 2023-11-11
- overall geometric mean: 1.18x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 171 ms: 1.11x faster                                                   |
| chameleon      | 5.95 ms                                                | 4.66 ms: 1.28x faster                                                  |
| docutils       | 1.73 sec                                               | 1.48 sec: 1.16x faster                                                 |
| tornado_http   | 89.9 ms                                                | 69.6 ms: 1.29x faster                                                  |
| Geometric mean | (ref)                                                  | 1.21x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 253 ms: 1.52x faster                                                   |
| async_tree_memoization  | 473 ms                                                 | 330 ms: 1.43x faster                                                   |
| async_tree_io           | 984 ms                                                 | 702 ms: 1.40x faster                                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 526 ms: 1.23x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.39x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 66.8 ms                                                | 57.0 ms: 1.17x faster                                                  |
| nbody          | 88.1 ms                                                | 77.4 ms: 1.14x faster                                                  |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                  | 1.10x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 76.3 ms: 1.21x faster                                                  |
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| regex_v8       | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                  | 1.09x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 197 us: 1.38x faster                                                   |
| json_dumps           | 8.00 ms                                                | 6.45 ms: 1.24x faster                                                  |
| unpickle_pure_python | 191 us                                                 | 156 us: 1.22x faster                                                   |
| xml_etree_process    | 45.6 ms                                                | 39.7 ms: 1.15x faster                                                  |
| tomli_loads          | 1.65 sec                                               | 1.56 sec: 1.06x faster                                                 |
| xml_etree_parse      | 111 ms                                                 | 110 ms: 1.01x faster                                                   |
| unpickle             | 8.86 us                                                | 9.14 us: 1.03x slower                                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 75.9 ms: 1.04x slower                                                  |
| pickle               | 7.04 us                                                | 7.37 us: 1.05x slower                                                  |
| json_loads           | 16.7 us                                                | 17.6 us: 1.05x slower                                                  |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                                  |
| pickle_list          | 2.72 us                                                | 2.88 us: 1.06x slower                                                  |
| xml_etree_generate   | 53.2 ms                                                | 57.7 ms: 1.09x slower                                                  |
| unpickle_list        | 2.79 us                                                | 3.13 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 11.8 ms: 1.01x slower                                                  |
| python_startup_no_site | 8.64 ms                                                | 10.5 ms: 1.21x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.11x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.49 ms: 1.32x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 75.2 us: 4.48x faster                                                  |
| deltablue                | 4.94 ms                                                | 2.42 ms: 2.04x faster                                                  |
| logging_silent           | 115 ns                                                 | 70.2 ns: 1.64x faster                                                  |
| raytrace                 | 293 ms                                                 | 180 ms: 1.63x faster                                                   |
| richards_super           | 57.1 ms                                                | 36.8 ms: 1.55x faster                                                  |
| chaos                    | 64.1 ms                                                | 41.5 ms: 1.55x faster                                                  |
| async_tree_none          | 384 ms                                                 | 253 ms: 1.52x faster                                                   |
| crypto_pyaes             | 70.8 ms                                                | 47.8 ms: 1.48x faster                                                  |
| asyncio_tcp              | 667 ms                                                 | 451 ms: 1.48x faster                                                   |
| sqlglot_parse            | 1.20 ms                                                | 827 us: 1.45x faster                                                   |
| comprehensions           | 16.8 us                                                | 11.7 us: 1.43x faster                                                  |
| async_tree_memoization   | 473 ms                                                 | 330 ms: 1.43x faster                                                   |
| richards                 | 47.6 ms                                                | 33.6 ms: 1.42x faster                                                  |
| go                       | 148 ms                                                 | 105 ms: 1.41x faster                                                   |
| scimark_lu               | 102 ms                                                 | 72.2 ms: 1.41x faster                                                  |
| async_tree_io            | 984 ms                                                 | 702 ms: 1.40x faster                                                   |
| sqlglot_transpile        | 1.40 ms                                                | 1.01 ms: 1.39x faster                                                  |
| unpack_sequence          | 36.7 ns                                                | 26.5 ns: 1.39x faster                                                  |
| pickle_pure_python       | 272 us                                                 | 197 us: 1.38x faster                                                   |
| deepcopy_memo            | 33.1 us                                                | 24.4 us: 1.36x faster                                                  |
| scimark_monte_carlo      | 62.8 ms                                                | 47.3 ms: 1.33x faster                                                  |
| mako                     | 9.86 ms                                                | 7.49 ms: 1.32x faster                                                  |
| generators               | 32.6 ms                                                | 24.8 ms: 1.31x faster                                                  |
| tornado_http             | 89.9 ms                                                | 69.6 ms: 1.29x faster                                                  |
| hexiom                   | 6.07 ms                                                | 4.71 ms: 1.29x faster                                                  |
| chameleon                | 5.95 ms                                                | 4.66 ms: 1.28x faster                                                  |
| scimark_sor              | 134 ms                                                 | 105 ms: 1.27x faster                                                   |
| spectral_norm            | 92.1 ms                                                | 72.6 ms: 1.27x faster                                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.29 sec: 1.27x faster                                                 |
| pycparser                | 878 ms                                                 | 696 ms: 1.26x faster                                                   |
| sympy_sum                | 92.4 ms                                                | 73.8 ms: 1.25x faster                                                  |
| pprint_safe_repr         | 628 ms                                                 | 505 ms: 1.24x faster                                                   |
| json_dumps               | 8.00 ms                                                | 6.45 ms: 1.24x faster                                                  |
| pprint_pformat           | 1.27 sec                                               | 1.03 sec: 1.24x faster                                                 |
| create_gc_cycles         | 865 us                                                 | 698 us: 1.24x faster                                                   |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 526 ms: 1.23x faster                                                   |
| logging_format           | 4.62 us                                                | 3.77 us: 1.23x faster                                                  |
| pyflate                  | 419 ms                                                 | 341 ms: 1.23x faster                                                   |
| unpickle_pure_python     | 191 us                                                 | 156 us: 1.22x faster                                                   |
| logging_simple           | 4.25 us                                                | 3.49 us: 1.22x faster                                                  |
| regex_compile            | 92.3 ms                                                | 76.3 ms: 1.21x faster                                                  |
| sympy_integrate          | 13.2 ms                                                | 10.9 ms: 1.21x faster                                                  |
| deepcopy                 | 269 us                                                 | 222 us: 1.21x faster                                                   |
| dulwich_log              | 35.6 ms                                                | 30.1 ms: 1.18x faster                                                  |
| float                    | 66.8 ms                                                | 57.0 ms: 1.17x faster                                                  |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| docutils                 | 1.73 sec                                               | 1.48 sec: 1.16x faster                                                 |
| deepcopy_reduce          | 2.28 us                                                | 1.96 us: 1.16x faster                                                  |
| mypy2                    | 300 ms                                                 | 260 ms: 1.15x faster                                                   |
| sympy_str                | 164 ms                                                 | 143 ms: 1.15x faster                                                   |
| mdp                      | 1.87 sec                                               | 1.63 sec: 1.15x faster                                                 |
| xml_etree_process        | 45.6 ms                                                | 39.7 ms: 1.15x faster                                                  |
| nbody                    | 88.1 ms                                                | 77.4 ms: 1.14x faster                                                  |
| 2to3                     | 189 ms                                                 | 171 ms: 1.11x faster                                                   |
| sympy_expand             | 267 ms                                                 | 245 ms: 1.09x faster                                                   |
| coroutines               | 19.6 ms                                                | 18.3 ms: 1.07x faster                                                  |
| nqueens                  | 62.4 ms                                                | 58.3 ms: 1.07x faster                                                  |
| scimark_fft              | 216 ms                                                 | 204 ms: 1.06x faster                                                   |
| tomli_loads              | 1.65 sec                                               | 1.56 sec: 1.06x faster                                                 |
| sqlglot_optimize         | 36.3 ms                                                | 34.3 ms: 1.06x faster                                                  |
| bench_thread_pool        | 516 us                                                 | 490 us: 1.05x faster                                                   |
| meteor_contest           | 77.9 ms                                                | 74.2 ms: 1.05x faster                                                  |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.11 ms: 1.05x faster                                                  |
| json                     | 3.06 ms                                                | 2.98 ms: 1.02x faster                                                  |
| regex_v8                 | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| fannkuch                 | 294 ms                                                 | 289 ms: 1.02x faster                                                   |
| sqlglot_normalize        | 187 ms                                                 | 184 ms: 1.01x faster                                                   |
| xml_etree_parse          | 111 ms                                                 | 110 ms: 1.01x faster                                                   |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x slower                                                   |
| asyncio_websockets       | 544 ms                                                 | 545 ms: 1.00x slower                                                   |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                                  |
| python_startup           | 11.7 ms                                                | 11.8 ms: 1.01x slower                                                  |
| unpickle                 | 8.86 us                                                | 9.14 us: 1.03x slower                                                  |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 75.9 ms: 1.04x slower                                                  |
| pickle                   | 7.04 us                                                | 7.37 us: 1.05x slower                                                  |
| json_loads               | 16.7 us                                                | 17.6 us: 1.05x slower                                                  |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.05x slower                                                  |
| pickle_list              | 2.72 us                                                | 2.88 us: 1.06x slower                                                  |
| xml_etree_generate       | 53.2 ms                                                | 57.7 ms: 1.09x slower                                                  |
| unpickle_list            | 2.79 us                                                | 3.13 us: 1.12x slower                                                  |
| bench_mp_pool            | 39.0 ms                                                | 44.0 ms: 1.13x slower                                                  |
| sqlite_synth             | 1.43 us                                                | 1.62 us: 1.14x slower                                                  |
| coverage                 | 41.1 ms                                                | 48.4 ms: 1.18x slower                                                  |
| python_startup_no_site   | 8.64 ms                                                | 10.5 ms: 1.21x slower                                                  |
| async_generators         | 233 ms                                                 | 300 ms: 1.29x slower                                                   |
| telco                    | 3.42 ms                                                | 4.69 ms: 1.37x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.18x faster                                                           |

Benchmark hidden because not significant (1): pathlib
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-fa84e5f/bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.15x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.11x
