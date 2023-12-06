
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.14x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 181 ms: 1.05x faster                                           |
| chameleon      | 5.95 ms                                                | 4.88 ms: 1.22x faster                                          |
| docutils       | 1.73 sec                                               | 1.53 sec: 1.13x faster                                         |
| tornado_http   | 89.9 ms                                                | 74.1 ms: 1.21x faster                                          |
| Geometric mean | (ref)                                                  | 1.15x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 257 ms: 1.50x faster                                           |
| async_tree_memoization  | 473 ms                                                 | 332 ms: 1.42x faster                                           |
| async_tree_io           | 984 ms                                                 | 707 ms: 1.39x faster                                           |
| async_tree_cpu_io_mixed | 646 ms                                                 | 527 ms: 1.22x faster                                           |
| Geometric mean          | (ref)                                                  | 1.38x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 66.8 ms                                                | 58.3 ms: 1.15x faster                                          |
| nbody          | 88.1 ms                                                | 81.7 ms: 1.08x faster                                          |
| Geometric mean | (ref)                                                  | 1.07x faster                                                   |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                           |
| regex_compile  | 92.3 ms                                                | 83.5 ms: 1.11x faster                                          |
| regex_v8       | 17.2 ms                                                | 17.0 ms: 1.01x faster                                          |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 204 us: 1.33x faster                                           |
| json_dumps           | 8.00 ms                                                | 6.55 ms: 1.22x faster                                          |
| unpickle_pure_python | 191 us                                                 | 165 us: 1.16x faster                                           |
| xml_etree_process    | 45.6 ms                                                | 40.9 ms: 1.11x faster                                          |
| tomli_loads          | 1.65 sec                                               | 1.51 sec: 1.09x faster                                         |
| xml_etree_parse      | 111 ms                                                 | 108 ms: 1.02x faster                                           |
| unpickle             | 8.86 us                                                | 9.04 us: 1.02x slower                                          |
| json_loads           | 16.7 us                                                | 17.3 us: 1.03x slower                                          |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                          |
| xml_etree_iterparse  | 72.7 ms                                                | 76.8 ms: 1.06x slower                                          |
| pickle               | 7.04 us                                                | 7.47 us: 1.06x slower                                          |
| pickle_list          | 2.72 us                                                | 2.96 us: 1.09x slower                                          |
| xml_etree_generate   | 53.2 ms                                                | 58.4 ms: 1.10x slower                                          |
| unpickle_list        | 2.79 us                                                | 3.11 us: 1.12x slower                                          |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.3 ms: 1.05x slower                                          |
| python_startup_no_site | 8.64 ms                                                | 10.9 ms: 1.26x slower                                          |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.96 ms: 1.24x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 77.4 us: 4.35x faster                                          |
| deltablue                | 4.94 ms                                                | 2.57 ms: 1.92x faster                                          |
| asyncio_tcp              | 667 ms                                                 | 408 ms: 1.64x faster                                           |
| logging_silent           | 115 ns                                                 | 73.6 ns: 1.56x faster                                          |
| richards_super           | 57.1 ms                                                | 37.1 ms: 1.54x faster                                          |
| raytrace                 | 293 ms                                                 | 194 ms: 1.51x faster                                           |
| async_tree_none          | 384 ms                                                 | 257 ms: 1.50x faster                                           |
| richards                 | 47.6 ms                                                | 33.4 ms: 1.43x faster                                          |
| async_tree_memoization   | 473 ms                                                 | 332 ms: 1.42x faster                                           |
| chaos                    | 64.1 ms                                                | 45.0 ms: 1.42x faster                                          |
| crypto_pyaes             | 70.8 ms                                                | 50.0 ms: 1.42x faster                                          |
| async_tree_io            | 984 ms                                                 | 707 ms: 1.39x faster                                           |
| sqlglot_parse            | 1.20 ms                                                | 867 us: 1.39x faster                                           |
| sqlglot_transpile        | 1.40 ms                                                | 1.05 ms: 1.33x faster                                          |
| asyncio_websockets       | 544 ms                                                 | 408 ms: 1.33x faster                                           |
| pickle_pure_python       | 272 us                                                 | 204 us: 1.33x faster                                           |
| scimark_lu               | 102 ms                                                 | 77.6 ms: 1.31x faster                                          |
| go                       | 148 ms                                                 | 113 ms: 1.31x faster                                           |
| unpack_sequence          | 36.7 ns                                                | 28.4 ns: 1.29x faster                                          |
| generators               | 32.6 ms                                                | 25.6 ms: 1.27x faster                                          |
| deepcopy_memo            | 33.1 us                                                | 26.2 us: 1.26x faster                                          |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.26x faster                                         |
| scimark_monte_carlo      | 62.8 ms                                                | 50.1 ms: 1.25x faster                                          |
| scimark_sor              | 134 ms                                                 | 108 ms: 1.24x faster                                           |
| mako                     | 9.86 ms                                                | 7.96 ms: 1.24x faster                                          |
| create_gc_cycles         | 865 us                                                 | 700 us: 1.24x faster                                           |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 527 ms: 1.22x faster                                           |
| pycparser                | 878 ms                                                 | 717 ms: 1.22x faster                                           |
| json_dumps               | 8.00 ms                                                | 6.55 ms: 1.22x faster                                          |
| chameleon                | 5.95 ms                                                | 4.88 ms: 1.22x faster                                          |
| pathlib                  | 29.4 ms                                                | 24.2 ms: 1.22x faster                                          |
| tornado_http             | 89.9 ms                                                | 74.1 ms: 1.21x faster                                          |
| comprehensions           | 16.8 us                                                | 13.9 us: 1.21x faster                                          |
| pyflate                  | 419 ms                                                 | 350 ms: 1.20x faster                                           |
| logging_format           | 4.62 us                                                | 3.92 us: 1.18x faster                                          |
| logging_simple           | 4.25 us                                                | 3.61 us: 1.18x faster                                          |
| pprint_safe_repr         | 628 ms                                                 | 537 ms: 1.17x faster                                           |
| dulwich_log              | 35.6 ms                                                | 30.4 ms: 1.17x faster                                          |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                           |
| deepcopy                 | 269 us                                                 | 232 us: 1.16x faster                                           |
| unpickle_pure_python     | 191 us                                                 | 165 us: 1.16x faster                                           |
| pprint_pformat           | 1.27 sec                                               | 1.10 sec: 1.15x faster                                         |
| float                    | 66.8 ms                                                | 58.3 ms: 1.15x faster                                          |
| sympy_sum                | 92.4 ms                                                | 80.7 ms: 1.14x faster                                          |
| docutils                 | 1.73 sec                                               | 1.53 sec: 1.13x faster                                         |
| spectral_norm            | 92.1 ms                                                | 81.4 ms: 1.13x faster                                          |
| mypy2                    | 300 ms                                                 | 267 ms: 1.13x faster                                           |
| xml_etree_process        | 45.6 ms                                                | 40.9 ms: 1.11x faster                                          |
| regex_compile            | 92.3 ms                                                | 83.5 ms: 1.11x faster                                          |
| deepcopy_reduce          | 2.28 us                                                | 2.06 us: 1.10x faster                                          |
| dask                     | 254 ms                                                 | 231 ms: 1.10x faster                                           |
| sympy_integrate          | 13.2 ms                                                | 12.0 ms: 1.10x faster                                          |
| mdp                      | 1.87 sec                                               | 1.71 sec: 1.10x faster                                         |
| tomli_loads              | 1.65 sec                                               | 1.51 sec: 1.09x faster                                         |
| nbody                    | 88.1 ms                                                | 81.7 ms: 1.08x faster                                          |
| sympy_str                | 164 ms                                                 | 153 ms: 1.07x faster                                           |
| coroutines               | 19.6 ms                                                | 18.6 ms: 1.05x faster                                          |
| hexiom                   | 6.07 ms                                                | 5.77 ms: 1.05x faster                                          |
| 2to3                     | 189 ms                                                 | 181 ms: 1.05x faster                                           |
| sympy_expand             | 267 ms                                                 | 260 ms: 1.03x faster                                           |
| xml_etree_parse          | 111 ms                                                 | 108 ms: 1.02x faster                                           |
| regex_v8                 | 17.2 ms                                                | 17.0 ms: 1.01x faster                                          |
| json                     | 3.06 ms                                                | 3.02 ms: 1.01x faster                                          |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                          |
| sqlglot_optimize         | 36.3 ms                                                | 36.8 ms: 1.01x slower                                          |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.31 ms: 1.02x slower                                          |
| meteor_contest           | 77.9 ms                                                | 79.1 ms: 1.02x slower                                          |
| fannkuch                 | 294 ms                                                 | 299 ms: 1.02x slower                                           |
| unpickle                 | 8.86 us                                                | 9.04 us: 1.02x slower                                          |
| bench_thread_pool        | 516 us                                                 | 529 us: 1.03x slower                                           |
| scimark_fft              | 216 ms                                                 | 223 ms: 1.03x slower                                           |
| json_loads               | 16.7 us                                                | 17.3 us: 1.03x slower                                          |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                          |
| sqlglot_normalize        | 187 ms                                                 | 196 ms: 1.05x slower                                           |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.05x slower                                          |
| nqueens                  | 62.4 ms                                                | 65.8 ms: 1.05x slower                                          |
| python_startup           | 11.7 ms                                                | 12.3 ms: 1.05x slower                                          |
| xml_etree_iterparse      | 72.7 ms                                                | 76.8 ms: 1.06x slower                                          |
| pickle                   | 7.04 us                                                | 7.47 us: 1.06x slower                                          |
| pickle_list              | 2.72 us                                                | 2.96 us: 1.09x slower                                          |
| xml_etree_generate       | 53.2 ms                                                | 58.4 ms: 1.10x slower                                          |
| unpickle_list            | 2.79 us                                                | 3.11 us: 1.12x slower                                          |
| sqlite_synth             | 1.43 us                                                | 1.65 us: 1.16x slower                                          |
| coverage                 | 41.1 ms                                                | 48.7 ms: 1.19x slower                                          |
| bench_mp_pool            | 39.0 ms                                                | 46.3 ms: 1.19x slower                                          |
| python_startup_no_site   | 8.64 ms                                                | 10.9 ms: 1.26x slower                                          |
| telco                    | 3.42 ms                                                | 4.65 ms: 1.36x slower                                          |
| async_generators         | 233 ms                                                 | 318 ms: 1.37x slower                                           |
| Geometric mean           | (ref)                                                  | 1.14x faster                                                   |

Benchmark hidden because not significant (1): pidigits
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-7bb54b5-PYTHON_UOPS/bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.10x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
