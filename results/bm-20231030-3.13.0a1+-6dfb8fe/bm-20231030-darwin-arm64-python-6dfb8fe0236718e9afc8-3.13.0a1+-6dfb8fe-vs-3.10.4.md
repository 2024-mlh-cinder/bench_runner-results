
# Results vs. 3.10.4

- fork: python
- ref: 6dfb8fe0236718e9afc8
- machine: darwin-arm64
- commit hash: 6dfb8fe
- commit date: 2023-10-30
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 170 ms: 1.11x faster                                                   |
| chameleon      | 5.95 ms                                                | 4.63 ms: 1.28x faster                                                  |
| docutils       | 1.73 sec                                               | 1.49 sec: 1.16x faster                                                 |
| tornado_http   | 89.9 ms                                                | 69.5 ms: 1.29x faster                                                  |
| Geometric mean | (ref)                                                  | 1.21x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 251 ms: 1.53x faster                                                   |
| async_tree_memoization  | 473 ms                                                 | 327 ms: 1.45x faster                                                   |
| async_tree_io           | 984 ms                                                 | 695 ms: 1.42x faster                                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 522 ms: 1.24x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.40x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 88.1 ms                                                | 70.9 ms: 1.24x faster                                                  |
| float          | 66.8 ms                                                | 54.4 ms: 1.23x faster                                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                  | 1.15x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 75.4 ms: 1.22x faster                                                  |
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| regex_v8       | 17.2 ms                                                | 16.8 ms: 1.03x faster                                                  |
| regex_effbot   | 2.46 ms                                                | 2.58 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.09x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 193 us: 1.41x faster                                                   |
| json_dumps           | 8.00 ms                                                | 6.48 ms: 1.24x faster                                                  |
| unpickle_pure_python | 191 us                                                 | 155 us: 1.23x faster                                                   |
| xml_etree_process    | 45.6 ms                                                | 39.0 ms: 1.17x faster                                                  |
| tomli_loads          | 1.65 sec                                               | 1.54 sec: 1.07x faster                                                 |
| unpickle             | 8.86 us                                                | 9.14 us: 1.03x slower                                                  |
| pickle               | 7.04 us                                                | 7.32 us: 1.04x slower                                                  |
| json_loads           | 16.7 us                                                | 17.5 us: 1.04x slower                                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 76.0 ms: 1.05x slower                                                  |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.06x slower                                                  |
| pickle_list          | 2.72 us                                                | 2.91 us: 1.07x slower                                                  |
| xml_etree_generate   | 53.2 ms                                                | 57.3 ms: 1.08x slower                                                  |
| unpickle_list        | 2.79 us                                                | 3.19 us: 1.14x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.04x faster                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.7 ms: 1.08x slower                                                  |
| python_startup_no_site | 8.64 ms                                                | 11.3 ms: 1.31x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.19x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.30 ms: 1.35x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 92.0 us: 3.66x faster                                                  |
| deltablue                | 4.94 ms                                                | 2.33 ms: 2.13x faster                                                  |
| logging_silent           | 115 ns                                                 | 66.8 ns: 1.72x faster                                                  |
| raytrace                 | 293 ms                                                 | 172 ms: 1.70x faster                                                   |
| chaos                    | 64.1 ms                                                | 40.1 ms: 1.60x faster                                                  |
| richards_super           | 57.1 ms                                                | 36.0 ms: 1.59x faster                                                  |
| asyncio_tcp              | 667 ms                                                 | 421 ms: 1.59x faster                                                   |
| async_tree_none          | 384 ms                                                 | 251 ms: 1.53x faster                                                   |
| sqlglot_parse            | 1.20 ms                                                | 789 us: 1.52x faster                                                   |
| crypto_pyaes             | 70.8 ms                                                | 47.0 ms: 1.51x faster                                                  |
| comprehensions           | 16.8 us                                                | 11.5 us: 1.46x faster                                                  |
| richards                 | 47.6 ms                                                | 32.7 ms: 1.46x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                | 963 us: 1.46x faster                                                   |
| scimark_lu               | 102 ms                                                 | 70.0 ms: 1.45x faster                                                  |
| go                       | 148 ms                                                 | 102 ms: 1.45x faster                                                   |
| async_tree_memoization   | 473 ms                                                 | 327 ms: 1.45x faster                                                   |
| async_tree_io            | 984 ms                                                 | 695 ms: 1.42x faster                                                   |
| pickle_pure_python       | 272 us                                                 | 193 us: 1.41x faster                                                   |
| scimark_monte_carlo      | 62.8 ms                                                | 44.9 ms: 1.40x faster                                                  |
| deepcopy_memo            | 33.1 us                                                | 23.9 us: 1.38x faster                                                  |
| unpack_sequence          | 36.7 ns                                                | 26.7 ns: 1.37x faster                                                  |
| mako                     | 9.86 ms                                                | 7.30 ms: 1.35x faster                                                  |
| hexiom                   | 6.07 ms                                                | 4.58 ms: 1.32x faster                                                  |
| generators               | 32.6 ms                                                | 24.7 ms: 1.32x faster                                                  |
| spectral_norm            | 92.1 ms                                                | 70.4 ms: 1.31x faster                                                  |
| scimark_sor              | 134 ms                                                 | 103 ms: 1.30x faster                                                   |
| tornado_http             | 89.9 ms                                                | 69.5 ms: 1.29x faster                                                  |
| chameleon                | 5.95 ms                                                | 4.63 ms: 1.28x faster                                                  |
| pycparser                | 878 ms                                                 | 688 ms: 1.28x faster                                                   |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.29 sec: 1.27x faster                                                 |
| pprint_safe_repr         | 628 ms                                                 | 498 ms: 1.26x faster                                                   |
| sympy_sum                | 92.4 ms                                                | 73.4 ms: 1.26x faster                                                  |
| pyflate                  | 419 ms                                                 | 334 ms: 1.25x faster                                                   |
| pprint_pformat           | 1.27 sec                                               | 1.01 sec: 1.25x faster                                                 |
| nbody                    | 88.1 ms                                                | 70.9 ms: 1.24x faster                                                  |
| create_gc_cycles         | 865 us                                                 | 699 us: 1.24x faster                                                   |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 522 ms: 1.24x faster                                                   |
| json_dumps               | 8.00 ms                                                | 6.48 ms: 1.24x faster                                                  |
| unpickle_pure_python     | 191 us                                                 | 155 us: 1.23x faster                                                   |
| float                    | 66.8 ms                                                | 54.4 ms: 1.23x faster                                                  |
| regex_compile            | 92.3 ms                                                | 75.4 ms: 1.22x faster                                                  |
| sympy_integrate          | 13.2 ms                                                | 10.8 ms: 1.22x faster                                                  |
| deepcopy                 | 269 us                                                 | 221 us: 1.22x faster                                                   |
| logging_format           | 4.62 us                                                | 3.81 us: 1.21x faster                                                  |
| logging_simple           | 4.25 us                                                | 3.54 us: 1.20x faster                                                  |
| dulwich_log              | 35.6 ms                                                | 30.4 ms: 1.17x faster                                                  |
| xml_etree_process        | 45.6 ms                                                | 39.0 ms: 1.17x faster                                                  |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| sympy_str                | 164 ms                                                 | 141 ms: 1.17x faster                                                   |
| mypy2                    | 300 ms                                                 | 258 ms: 1.17x faster                                                   |
| docutils                 | 1.73 sec                                               | 1.49 sec: 1.16x faster                                                 |
| mdp                      | 1.87 sec                                               | 1.62 sec: 1.16x faster                                                 |
| deepcopy_reduce          | 2.28 us                                                | 2.00 us: 1.14x faster                                                  |
| 2to3                     | 189 ms                                                 | 170 ms: 1.11x faster                                                   |
| coroutines               | 19.6 ms                                                | 17.7 ms: 1.11x faster                                                  |
| sympy_expand             | 267 ms                                                 | 242 ms: 1.11x faster                                                   |
| scimark_fft              | 216 ms                                                 | 198 ms: 1.09x faster                                                   |
| nqueens                  | 62.4 ms                                                | 57.7 ms: 1.08x faster                                                  |
| bench_thread_pool        | 516 us                                                 | 477 us: 1.08x faster                                                   |
| tomli_loads              | 1.65 sec                                               | 1.54 sec: 1.07x faster                                                 |
| sqlglot_optimize         | 36.3 ms                                                | 33.9 ms: 1.07x faster                                                  |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.06 ms: 1.06x faster                                                  |
| fannkuch                 | 294 ms                                                 | 279 ms: 1.05x faster                                                   |
| meteor_contest           | 77.9 ms                                                | 74.4 ms: 1.05x faster                                                  |
| regex_v8                 | 17.2 ms                                                | 16.8 ms: 1.03x faster                                                  |
| sqlglot_normalize        | 187 ms                                                 | 182 ms: 1.03x faster                                                   |
| json                     | 3.06 ms                                                | 2.99 ms: 1.02x faster                                                  |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| asyncio_websockets       | 544 ms                                                 | 545 ms: 1.00x slower                                                   |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                                  |
| unpickle                 | 8.86 us                                                | 9.14 us: 1.03x slower                                                  |
| pickle                   | 7.04 us                                                | 7.32 us: 1.04x slower                                                  |
| json_loads               | 16.7 us                                                | 17.5 us: 1.04x slower                                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 76.0 ms: 1.05x slower                                                  |
| regex_effbot             | 2.46 ms                                                | 2.58 ms: 1.05x slower                                                  |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.06x slower                                                  |
| pickle_list              | 2.72 us                                                | 2.91 us: 1.07x slower                                                  |
| xml_etree_generate       | 53.2 ms                                                | 57.3 ms: 1.08x slower                                                  |
| python_startup           | 11.7 ms                                                | 12.7 ms: 1.08x slower                                                  |
| coverage                 | 41.1 ms                                                | 46.5 ms: 1.13x slower                                                  |
| sqlite_synth             | 1.43 us                                                | 1.62 us: 1.14x slower                                                  |
| unpickle_list            | 2.79 us                                                | 3.19 us: 1.14x slower                                                  |
| bench_mp_pool            | 39.0 ms                                                | 45.3 ms: 1.16x slower                                                  |
| async_generators         | 233 ms                                                 | 301 ms: 1.29x slower                                                   |
| python_startup_no_site   | 8.64 ms                                                | 11.3 ms: 1.31x slower                                                  |
| telco                    | 3.42 ms                                                | 4.73 ms: 1.38x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.19x faster                                                           |

Benchmark hidden because not significant (2): xml_etree_parse, pathlib
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231030-3.13.0a1+-6dfb8fe/bm-20231030-darwin-arm64-python-6dfb8fe0236718e9afc8-3.13.0a1+-6dfb8fe.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.15x
- 99% likely to have a speedup of 1.12x
