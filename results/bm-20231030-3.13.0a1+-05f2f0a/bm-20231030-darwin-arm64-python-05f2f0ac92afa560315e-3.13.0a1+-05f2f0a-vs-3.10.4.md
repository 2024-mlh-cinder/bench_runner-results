
# Results vs. 3.10.4

- fork: python
- ref: 05f2f0ac92afa560315e
- machine: darwin-arm64
- commit hash: 05f2f0a
- commit date: 2023-10-30
- overall geometric mean: 1.19x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.12x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 170 ms: 1.12x faster                                                   |
| chameleon      | 5.95 ms                                                | 4.63 ms: 1.29x faster                                                  |
| docutils       | 1.73 sec                                               | 1.49 sec: 1.16x faster                                                 |
| tornado_http   | 89.9 ms                                                | 70.0 ms: 1.29x faster                                                  |
| Geometric mean | (ref)                                                  | 1.21x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 251 ms: 1.53x faster                                                   |
| async_tree_memoization  | 473 ms                                                 | 327 ms: 1.45x faster                                                   |
| async_tree_io           | 984 ms                                                 | 696 ms: 1.41x faster                                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 522 ms: 1.24x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.40x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| nbody          | 88.1 ms                                                | 70.4 ms: 1.25x faster                                                  |
| float          | 66.8 ms                                                | 54.4 ms: 1.23x faster                                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                  | 1.15x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 75.3 ms: 1.23x faster                                                  |
| regex_dna      | 174 ms                                                 | 151 ms: 1.15x faster                                                   |
| regex_v8       | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| regex_effbot   | 2.46 ms                                                | 2.60 ms: 1.05x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 193 us: 1.41x faster                                                   |
| json_dumps           | 8.00 ms                                                | 6.44 ms: 1.24x faster                                                  |
| unpickle_pure_python | 191 us                                                 | 155 us: 1.23x faster                                                   |
| xml_etree_process    | 45.6 ms                                                | 38.9 ms: 1.17x faster                                                  |
| tomli_loads          | 1.65 sec                                               | 1.54 sec: 1.07x faster                                                 |
| unpickle             | 8.86 us                                                | 9.12 us: 1.03x slower                                                  |
| pickle               | 7.04 us                                                | 7.31 us: 1.04x slower                                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 75.9 ms: 1.04x slower                                                  |
| json_loads           | 16.7 us                                                | 17.5 us: 1.04x slower                                                  |
| pickle_dict          | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| pickle_list          | 2.72 us                                                | 2.90 us: 1.07x slower                                                  |
| xml_etree_generate   | 53.2 ms                                                | 57.1 ms: 1.07x slower                                                  |
| unpickle_list        | 2.79 us                                                | 3.13 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.04x faster                                                           |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.8 ms: 1.10x slower                                                  |
| python_startup_no_site | 8.64 ms                                                | 11.5 ms: 1.33x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.21x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.34 ms: 1.34x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 92.7 us: 3.63x faster                                                  |
| deltablue                | 4.94 ms                                                | 2.32 ms: 2.13x faster                                                  |
| logging_silent           | 115 ns                                                 | 66.6 ns: 1.73x faster                                                  |
| raytrace                 | 293 ms                                                 | 172 ms: 1.70x faster                                                   |
| chaos                    | 64.1 ms                                                | 40.0 ms: 1.61x faster                                                  |
| richards_super           | 57.1 ms                                                | 35.9 ms: 1.59x faster                                                  |
| async_tree_none          | 384 ms                                                 | 251 ms: 1.53x faster                                                   |
| sqlglot_parse            | 1.20 ms                                                | 790 us: 1.52x faster                                                   |
| crypto_pyaes             | 70.8 ms                                                | 46.7 ms: 1.51x faster                                                  |
| asyncio_tcp              | 667 ms                                                 | 447 ms: 1.49x faster                                                   |
| richards                 | 47.6 ms                                                | 32.4 ms: 1.47x faster                                                  |
| comprehensions           | 16.8 us                                                | 11.5 us: 1.46x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                | 962 us: 1.46x faster                                                   |
| scimark_lu               | 102 ms                                                 | 69.9 ms: 1.45x faster                                                  |
| async_tree_memoization   | 473 ms                                                 | 327 ms: 1.45x faster                                                   |
| go                       | 148 ms                                                 | 102 ms: 1.45x faster                                                   |
| async_tree_io            | 984 ms                                                 | 696 ms: 1.41x faster                                                   |
| pickle_pure_python       | 272 us                                                 | 193 us: 1.41x faster                                                   |
| unpack_sequence          | 36.7 ns                                                | 26.1 ns: 1.41x faster                                                  |
| scimark_monte_carlo      | 62.8 ms                                                | 44.9 ms: 1.40x faster                                                  |
| deepcopy_memo            | 33.1 us                                                | 23.8 us: 1.39x faster                                                  |
| mako                     | 9.86 ms                                                | 7.34 ms: 1.34x faster                                                  |
| hexiom                   | 6.07 ms                                                | 4.58 ms: 1.33x faster                                                  |
| generators               | 32.6 ms                                                | 24.6 ms: 1.32x faster                                                  |
| spectral_norm            | 92.1 ms                                                | 70.3 ms: 1.31x faster                                                  |
| scimark_sor              | 134 ms                                                 | 103 ms: 1.30x faster                                                   |
| chameleon                | 5.95 ms                                                | 4.63 ms: 1.29x faster                                                  |
| tornado_http             | 89.9 ms                                                | 70.0 ms: 1.29x faster                                                  |
| pycparser                | 878 ms                                                 | 686 ms: 1.28x faster                                                   |
| pprint_safe_repr         | 628 ms                                                 | 493 ms: 1.27x faster                                                   |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.29 sec: 1.27x faster                                                 |
| pprint_pformat           | 1.27 sec                                               | 1.00 sec: 1.27x faster                                                 |
| sympy_sum                | 92.4 ms                                                | 73.4 ms: 1.26x faster                                                  |
| pyflate                  | 419 ms                                                 | 333 ms: 1.26x faster                                                   |
| nbody                    | 88.1 ms                                                | 70.4 ms: 1.25x faster                                                  |
| json_dumps               | 8.00 ms                                                | 6.44 ms: 1.24x faster                                                  |
| create_gc_cycles         | 865 us                                                 | 698 us: 1.24x faster                                                   |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 522 ms: 1.24x faster                                                   |
| unpickle_pure_python     | 191 us                                                 | 155 us: 1.23x faster                                                   |
| float                    | 66.8 ms                                                | 54.4 ms: 1.23x faster                                                  |
| regex_compile            | 92.3 ms                                                | 75.3 ms: 1.23x faster                                                  |
| sympy_integrate          | 13.2 ms                                                | 10.8 ms: 1.22x faster                                                  |
| deepcopy                 | 269 us                                                 | 221 us: 1.22x faster                                                   |
| logging_format           | 4.62 us                                                | 3.80 us: 1.21x faster                                                  |
| logging_simple           | 4.25 us                                                | 3.54 us: 1.20x faster                                                  |
| xml_etree_process        | 45.6 ms                                                | 38.9 ms: 1.17x faster                                                  |
| sympy_str                | 164 ms                                                 | 141 ms: 1.17x faster                                                   |
| dulwich_log              | 35.6 ms                                                | 30.5 ms: 1.17x faster                                                  |
| mypy2                    | 300 ms                                                 | 257 ms: 1.17x faster                                                   |
| docutils                 | 1.73 sec                                               | 1.49 sec: 1.16x faster                                                 |
| mdp                      | 1.87 sec                                               | 1.61 sec: 1.16x faster                                                 |
| deepcopy_reduce          | 2.28 us                                                | 1.98 us: 1.15x faster                                                  |
| regex_dna                | 174 ms                                                 | 151 ms: 1.15x faster                                                   |
| 2to3                     | 189 ms                                                 | 170 ms: 1.12x faster                                                   |
| coroutines               | 19.6 ms                                                | 17.7 ms: 1.11x faster                                                  |
| sympy_expand             | 267 ms                                                 | 241 ms: 1.11x faster                                                   |
| scimark_fft              | 216 ms                                                 | 197 ms: 1.10x faster                                                   |
| nqueens                  | 62.4 ms                                                | 57.7 ms: 1.08x faster                                                  |
| bench_thread_pool        | 516 us                                                 | 478 us: 1.08x faster                                                   |
| sqlglot_optimize         | 36.3 ms                                                | 33.8 ms: 1.07x faster                                                  |
| tomli_loads              | 1.65 sec                                               | 1.54 sec: 1.07x faster                                                 |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.06 ms: 1.07x faster                                                  |
| meteor_contest           | 77.9 ms                                                | 73.8 ms: 1.06x faster                                                  |
| fannkuch                 | 294 ms                                                 | 279 ms: 1.05x faster                                                   |
| sqlglot_normalize        | 187 ms                                                 | 182 ms: 1.03x faster                                                   |
| regex_v8                 | 17.2 ms                                                | 16.9 ms: 1.02x faster                                                  |
| json                     | 3.06 ms                                                | 3.00 ms: 1.02x faster                                                  |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| asyncio_websockets       | 544 ms                                                 | 545 ms: 1.00x slower                                                   |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                                  |
| unpickle                 | 8.86 us                                                | 9.12 us: 1.03x slower                                                  |
| pickle                   | 7.04 us                                                | 7.31 us: 1.04x slower                                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 75.9 ms: 1.04x slower                                                  |
| json_loads               | 16.7 us                                                | 17.5 us: 1.04x slower                                                  |
| regex_effbot             | 2.46 ms                                                | 2.60 ms: 1.05x slower                                                  |
| pickle_dict              | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| pickle_list              | 2.72 us                                                | 2.90 us: 1.07x slower                                                  |
| xml_etree_generate       | 53.2 ms                                                | 57.1 ms: 1.07x slower                                                  |
| python_startup           | 11.7 ms                                                | 12.8 ms: 1.10x slower                                                  |
| coverage                 | 41.1 ms                                                | 46.1 ms: 1.12x slower                                                  |
| unpickle_list            | 2.79 us                                                | 3.13 us: 1.12x slower                                                  |
| sqlite_synth             | 1.43 us                                                | 1.61 us: 1.13x slower                                                  |
| bench_mp_pool            | 39.0 ms                                                | 45.2 ms: 1.16x slower                                                  |
| async_generators         | 233 ms                                                 | 301 ms: 1.29x slower                                                   |
| python_startup_no_site   | 8.64 ms                                                | 11.5 ms: 1.33x slower                                                  |
| telco                    | 3.42 ms                                                | 4.74 ms: 1.39x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.19x faster                                                           |

Benchmark hidden because not significant (2): xml_etree_parse, pathlib
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231030-3.13.0a1+-05f2f0a/bm-20231030-darwin-arm64-python-05f2f0ac92afa560315e-3.13.0a1+-05f2f0a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.12x
