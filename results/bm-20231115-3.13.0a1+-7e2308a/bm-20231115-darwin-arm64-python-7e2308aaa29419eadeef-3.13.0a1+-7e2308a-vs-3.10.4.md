
# Results vs. 3.10.4

- fork: python
- ref: 7e2308aaa29419eadeef
- machine: darwin-arm64
- commit hash: 7e2308a
- commit date: 2023-11-15
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 178 ms: 1.06x faster                                                   |
| chameleon      | 5.95 ms                                                | 4.85 ms: 1.23x faster                                                  |
| docutils       | 1.73 sec                                               | 1.52 sec: 1.14x faster                                                 |
| tornado_http   | 89.9 ms                                                | 71.0 ms: 1.27x faster                                                  |
| Geometric mean | (ref)                                                  | 1.17x faster                                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 261 ms: 1.47x faster                                                   |
| async_tree_memoization  | 473 ms                                                 | 338 ms: 1.40x faster                                                   |
| async_tree_io           | 984 ms                                                 | 727 ms: 1.35x faster                                                   |
| async_tree_cpu_io_mixed | 646 ms                                                 | 534 ms: 1.21x faster                                                   |
| Geometric mean          | (ref)                                                  | 1.36x faster                                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| float          | 66.8 ms                                                | 59.9 ms: 1.12x faster                                                  |
| nbody          | 88.1 ms                                                | 79.6 ms: 1.11x faster                                                  |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| Geometric mean | (ref)                                                  | 1.07x faster                                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 78.7 ms: 1.17x faster                                                  |
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| regex_v8       | 17.2 ms                                                | 17.0 ms: 1.02x faster                                                  |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 202 us: 1.34x faster                                                   |
| json_dumps           | 8.00 ms                                                | 6.60 ms: 1.21x faster                                                  |
| unpickle_pure_python | 191 us                                                 | 162 us: 1.18x faster                                                   |
| xml_etree_process    | 45.6 ms                                                | 41.0 ms: 1.11x faster                                                  |
| tomli_loads          | 1.65 sec                                               | 1.60 sec: 1.04x faster                                                 |
| xml_etree_parse      | 111 ms                                                 | 108 ms: 1.03x faster                                                   |
| unpickle             | 8.86 us                                                | 9.09 us: 1.03x slower                                                  |
| pickle               | 7.04 us                                                | 7.44 us: 1.06x slower                                                  |
| pickle_dict          | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| json_loads           | 16.7 us                                                | 17.8 us: 1.06x slower                                                  |
| xml_etree_iterparse  | 72.7 ms                                                | 77.6 ms: 1.07x slower                                                  |
| pickle_list          | 2.72 us                                                | 2.96 us: 1.09x slower                                                  |
| xml_etree_generate   | 53.2 ms                                                | 59.3 ms: 1.11x slower                                                  |
| unpickle_list        | 2.79 us                                                | 3.12 us: 1.12x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.0 ms: 1.02x slower                                                  |
| python_startup_no_site | 8.64 ms                                                | 10.6 ms: 1.23x slower                                                  |
| Geometric mean         | (ref)                                                  | 1.12x slower                                                           |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|-----------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.81 ms: 1.26x faster                                                  |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 77.9 us: 4.32x faster                                                  |
| deltablue                | 4.94 ms                                                | 2.49 ms: 1.98x faster                                                  |
| asyncio_tcp              | 667 ms                                                 | 422 ms: 1.58x faster                                                   |
| logging_silent           | 115 ns                                                 | 75.0 ns: 1.53x faster                                                  |
| raytrace                 | 293 ms                                                 | 192 ms: 1.53x faster                                                   |
| richards_super           | 57.1 ms                                                | 38.5 ms: 1.49x faster                                                  |
| async_tree_none          | 384 ms                                                 | 261 ms: 1.47x faster                                                   |
| chaos                    | 64.1 ms                                                | 44.3 ms: 1.45x faster                                                  |
| crypto_pyaes             | 70.8 ms                                                | 49.3 ms: 1.44x faster                                                  |
| sqlglot_parse            | 1.20 ms                                                | 853 us: 1.41x faster                                                   |
| async_tree_memoization   | 473 ms                                                 | 338 ms: 1.40x faster                                                   |
| go                       | 148 ms                                                 | 107 ms: 1.38x faster                                                   |
| richards                 | 47.6 ms                                                | 35.1 ms: 1.36x faster                                                  |
| async_tree_io            | 984 ms                                                 | 727 ms: 1.35x faster                                                   |
| scimark_lu               | 102 ms                                                 | 75.3 ms: 1.35x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                | 1.04 ms: 1.35x faster                                                  |
| pickle_pure_python       | 272 us                                                 | 202 us: 1.34x faster                                                   |
| comprehensions           | 16.8 us                                                | 12.6 us: 1.33x faster                                                  |
| deepcopy_memo            | 33.1 us                                                | 25.2 us: 1.31x faster                                                  |
| unpack_sequence          | 36.7 ns                                                | 28.3 ns: 1.30x faster                                                  |
| scimark_monte_carlo      | 62.8 ms                                                | 48.8 ms: 1.29x faster                                                  |
| generators               | 32.6 ms                                                | 25.7 ms: 1.27x faster                                                  |
| tornado_http             | 89.9 ms                                                | 71.0 ms: 1.27x faster                                                  |
| mako                     | 9.86 ms                                                | 7.81 ms: 1.26x faster                                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.31 sec: 1.25x faster                                                 |
| scimark_sor              | 134 ms                                                 | 108 ms: 1.24x faster                                                   |
| chameleon                | 5.95 ms                                                | 4.85 ms: 1.23x faster                                                  |
| spectral_norm            | 92.1 ms                                                | 75.1 ms: 1.23x faster                                                  |
| pycparser                | 878 ms                                                 | 717 ms: 1.22x faster                                                   |
| hexiom                   | 6.07 ms                                                | 4.99 ms: 1.22x faster                                                  |
| sympy_sum                | 92.4 ms                                                | 76.0 ms: 1.21x faster                                                  |
| json_dumps               | 8.00 ms                                                | 6.60 ms: 1.21x faster                                                  |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 534 ms: 1.21x faster                                                   |
| pyflate                  | 419 ms                                                 | 350 ms: 1.20x faster                                                   |
| pprint_pformat           | 1.27 sec                                               | 1.06 sec: 1.19x faster                                                 |
| pprint_safe_repr         | 628 ms                                                 | 527 ms: 1.19x faster                                                   |
| create_gc_cycles         | 865 us                                                 | 729 us: 1.19x faster                                                   |
| unpickle_pure_python     | 191 us                                                 | 162 us: 1.18x faster                                                   |
| regex_compile            | 92.3 ms                                                | 78.7 ms: 1.17x faster                                                  |
| deepcopy                 | 269 us                                                 | 229 us: 1.17x faster                                                   |
| logging_format           | 4.62 us                                                | 3.95 us: 1.17x faster                                                  |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                                   |
| sympy_integrate          | 13.2 ms                                                | 11.4 ms: 1.16x faster                                                  |
| logging_simple           | 4.25 us                                                | 3.68 us: 1.16x faster                                                  |
| dulwich_log              | 35.6 ms                                                | 30.9 ms: 1.15x faster                                                  |
| docutils                 | 1.73 sec                                               | 1.52 sec: 1.14x faster                                                 |
| mypy2                    | 300 ms                                                 | 265 ms: 1.13x faster                                                   |
| sympy_str                | 164 ms                                                 | 147 ms: 1.12x faster                                                   |
| mdp                      | 1.87 sec                                               | 1.68 sec: 1.12x faster                                                 |
| float                    | 66.8 ms                                                | 59.9 ms: 1.12x faster                                                  |
| deepcopy_reduce          | 2.28 us                                                | 2.05 us: 1.11x faster                                                  |
| xml_etree_process        | 45.6 ms                                                | 41.0 ms: 1.11x faster                                                  |
| nbody                    | 88.1 ms                                                | 79.6 ms: 1.11x faster                                                  |
| dask                     | 254 ms                                                 | 233 ms: 1.09x faster                                                   |
| 2to3                     | 189 ms                                                 | 178 ms: 1.06x faster                                                   |
| sympy_expand             | 267 ms                                                 | 257 ms: 1.04x faster                                                   |
| nqueens                  | 62.4 ms                                                | 60.1 ms: 1.04x faster                                                  |
| meteor_contest           | 77.9 ms                                                | 75.1 ms: 1.04x faster                                                  |
| tomli_loads              | 1.65 sec                                               | 1.60 sec: 1.04x faster                                                 |
| scimark_fft              | 216 ms                                                 | 210 ms: 1.03x faster                                                   |
| coroutines               | 19.6 ms                                                | 19.1 ms: 1.03x faster                                                  |
| xml_etree_parse          | 111 ms                                                 | 108 ms: 1.03x faster                                                   |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.18 ms: 1.02x faster                                                  |
| pathlib                  | 29.4 ms                                                | 28.7 ms: 1.02x faster                                                  |
| regex_v8                 | 17.2 ms                                                | 17.0 ms: 1.02x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                | 35.7 ms: 1.02x faster                                                  |
| fannkuch                 | 294 ms                                                 | 294 ms: 1.00x faster                                                   |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                                   |
| asyncio_websockets       | 544 ms                                                 | 547 ms: 1.01x slower                                                   |
| python_startup           | 11.7 ms                                                | 12.0 ms: 1.02x slower                                                  |
| unpickle                 | 8.86 us                                                | 9.09 us: 1.03x slower                                                  |
| gc_traversal             | 2.37 ms                                                | 2.44 ms: 1.03x slower                                                  |
| sqlglot_normalize        | 187 ms                                                 | 193 ms: 1.03x slower                                                   |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                  |
| pickle                   | 7.04 us                                                | 7.44 us: 1.06x slower                                                  |
| pickle_dict              | 17.0 us                                                | 18.0 us: 1.06x slower                                                  |
| json_loads               | 16.7 us                                                | 17.8 us: 1.06x slower                                                  |
| xml_etree_iterparse      | 72.7 ms                                                | 77.6 ms: 1.07x slower                                                  |
| pickle_list              | 2.72 us                                                | 2.96 us: 1.09x slower                                                  |
| xml_etree_generate       | 53.2 ms                                                | 59.3 ms: 1.11x slower                                                  |
| unpickle_list            | 2.79 us                                                | 3.12 us: 1.12x slower                                                  |
| sqlite_synth             | 1.43 us                                                | 1.63 us: 1.14x slower                                                  |
| bench_mp_pool            | 39.0 ms                                                | 44.7 ms: 1.15x slower                                                  |
| coverage                 | 41.1 ms                                                | 48.1 ms: 1.17x slower                                                  |
| python_startup_no_site   | 8.64 ms                                                | 10.6 ms: 1.23x slower                                                  |
| async_generators         | 233 ms                                                 | 308 ms: 1.33x slower                                                   |
| telco                    | 3.42 ms                                                | 4.63 ms: 1.35x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.15x faster                                                           |

Benchmark hidden because not significant (2): json, bench_thread_pool
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231115-3.13.0a1+-7e2308a/bm-20231115-darwin-arm64-python-7e2308aaa29419eadeef-3.13.0a1+-7e2308a.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.12x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.08x
