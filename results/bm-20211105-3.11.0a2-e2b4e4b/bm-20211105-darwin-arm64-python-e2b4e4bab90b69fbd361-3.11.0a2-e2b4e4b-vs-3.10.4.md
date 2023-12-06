
# Results vs. 3.10.4

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: darwin-arm64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.10x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 165 ms: 1.15x faster                                                  |
| chameleon      | 5.95 ms                                                | 4.87 ms: 1.22x faster                                                 |
| docutils       | 1.73 sec                                               | 1.51 sec: 1.14x faster                                                |
| html5lib       | 41.5 ms                                                | 36.4 ms: 1.14x faster                                                 |
| tornado_http   | 89.9 ms                                                | 77.9 ms: 1.15x faster                                                 |
| Geometric mean | (ref)                                                  | 1.16x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 288 ms: 1.33x faster                                                  |
| async_tree_memoization  | 473 ms                                                 | 359 ms: 1.32x faster                                                  |
| async_tree_io           | 984 ms                                                 | 786 ms: 1.25x faster                                                  |
| async_tree_cpu_io_mixed | 646 ms                                                 | 568 ms: 1.14x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.26x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 66.8 ms                                                | 53.4 ms: 1.25x faster                                                 |
| nbody          | 88.1 ms                                                | 73.1 ms: 1.21x faster                                                 |
| pidigits       | 282 ms                                                 | 280 ms: 1.01x faster                                                  |
| Geometric mean | (ref)                                                  | 1.15x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 76.4 ms: 1.21x faster                                                 |
| regex_v8       | 17.2 ms                                                | 16.8 ms: 1.03x faster                                                 |
| regex_effbot   | 2.46 ms                                                | 2.46 ms: 1.00x faster                                                 |
| Geometric mean | (ref)                                                  | 1.06x faster                                                          |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_process    | 45.6 ms                                                | 36.3 ms: 1.26x faster                                                 |
| pickle_pure_python   | 272 us                                                 | 223 us: 1.22x faster                                                  |
| xml_etree_parse      | 111 ms                                                 | 96.5 ms: 1.15x faster                                                 |
| unpickle_pure_python | 191 us                                                 | 169 us: 1.13x faster                                                  |
| xml_etree_generate   | 53.2 ms                                                | 48.3 ms: 1.10x faster                                                 |
| json_loads           | 16.7 us                                                | 15.4 us: 1.09x faster                                                 |
| tomli_loads          | 1.65 sec                                               | 1.52 sec: 1.09x faster                                                |
| json_dumps           | 8.00 ms                                                | 7.61 ms: 1.05x faster                                                 |
| unpickle             | 8.86 us                                                | 8.57 us: 1.03x faster                                                 |
| xml_etree_iterparse  | 72.7 ms                                                | 70.5 ms: 1.03x faster                                                 |
| pickle_list          | 2.72 us                                                | 2.64 us: 1.03x faster                                                 |
| pickle_dict          | 17.0 us                                                | 16.8 us: 1.01x faster                                                 |
| unpickle_list        | 2.79 us                                                | 2.75 us: 1.01x faster                                                 |
| pickle               | 7.04 us                                                | 7.26 us: 1.03x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.08x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 8.64 ms                                                | 8.93 ms: 1.03x slower                                                 |
| python_startup         | 11.7 ms                                                | 15.3 ms: 1.30x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.16x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.86 ms                                                | 8.15 ms: 1.21x faster                                                 |
| django_template | 25.8 ms                                                | 22.2 ms: 1.16x faster                                                 |
| genshi_text     | 17.1 ms                                                | 15.4 ms: 1.11x faster                                                 |
| genshi_xml      | 33.8 ms                                                | 30.6 ms: 1.10x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.15x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.94 ms                                                | 3.26 ms: 1.52x faster                                                 |
| logging_silent           | 115 ns                                                 | 81.4 ns: 1.41x faster                                                 |
| scimark_sor              | 134 ms                                                 | 98.4 ms: 1.36x faster                                                 |
| async_tree_none          | 384 ms                                                 | 288 ms: 1.33x faster                                                  |
| async_tree_memoization   | 473 ms                                                 | 359 ms: 1.32x faster                                                  |
| scimark_monte_carlo      | 62.8 ms                                                | 47.9 ms: 1.31x faster                                                 |
| raytrace                 | 293 ms                                                 | 223 ms: 1.31x faster                                                  |
| chaos                    | 64.1 ms                                                | 49.5 ms: 1.29x faster                                                 |
| pprint_safe_repr         | 628 ms                                                 | 487 ms: 1.29x faster                                                  |
| pprint_pformat           | 1.27 sec                                               | 996 ms: 1.28x faster                                                  |
| spectral_norm            | 92.1 ms                                                | 72.9 ms: 1.26x faster                                                 |
| xml_etree_process        | 45.6 ms                                                | 36.3 ms: 1.26x faster                                                 |
| async_tree_io            | 984 ms                                                 | 786 ms: 1.25x faster                                                  |
| float                    | 66.8 ms                                                | 53.4 ms: 1.25x faster                                                 |
| crypto_pyaes             | 70.8 ms                                                | 56.9 ms: 1.24x faster                                                 |
| thrift                   | 561 us                                                 | 453 us: 1.24x faster                                                  |
| pathlib                  | 29.4 ms                                                | 23.8 ms: 1.24x faster                                                 |
| logging_format           | 4.62 us                                                | 3.74 us: 1.24x faster                                                 |
| logging_simple           | 4.25 us                                                | 3.44 us: 1.23x faster                                                 |
| hexiom                   | 6.07 ms                                                | 4.95 ms: 1.23x faster                                                 |
| chameleon                | 5.95 ms                                                | 4.87 ms: 1.22x faster                                                 |
| richards                 | 47.6 ms                                                | 39.0 ms: 1.22x faster                                                 |
| pickle_pure_python       | 272 us                                                 | 223 us: 1.22x faster                                                  |
| mako                     | 9.86 ms                                                | 8.15 ms: 1.21x faster                                                 |
| regex_compile            | 92.3 ms                                                | 76.4 ms: 1.21x faster                                                 |
| nbody                    | 88.1 ms                                                | 73.1 ms: 1.21x faster                                                 |
| richards_super           | 57.1 ms                                                | 48.0 ms: 1.19x faster                                                 |
| pycparser                | 878 ms                                                 | 742 ms: 1.18x faster                                                  |
| deepcopy_memo            | 33.1 us                                                | 27.9 us: 1.18x faster                                                 |
| pyflate                  | 419 ms                                                 | 354 ms: 1.18x faster                                                  |
| create_gc_cycles         | 865 us                                                 | 732 us: 1.18x faster                                                  |
| async_generators         | 233 ms                                                 | 197 ms: 1.18x faster                                                  |
| dulwich_log              | 35.6 ms                                                | 30.2 ms: 1.18x faster                                                 |
| scimark_lu               | 102 ms                                                 | 87.1 ms: 1.17x faster                                                 |
| django_template          | 25.8 ms                                                | 22.2 ms: 1.16x faster                                                 |
| tornado_http             | 89.9 ms                                                | 77.9 ms: 1.15x faster                                                 |
| deepcopy                 | 269 us                                                 | 233 us: 1.15x faster                                                  |
| xml_etree_parse          | 111 ms                                                 | 96.5 ms: 1.15x faster                                                 |
| 2to3                     | 189 ms                                                 | 165 ms: 1.15x faster                                                  |
| deepcopy_reduce          | 2.28 us                                                | 1.99 us: 1.15x faster                                                 |
| docutils                 | 1.73 sec                                               | 1.51 sec: 1.14x faster                                                |
| html5lib                 | 41.5 ms                                                | 36.4 ms: 1.14x faster                                                 |
| scimark_fft              | 216 ms                                                 | 190 ms: 1.14x faster                                                  |
| go                       | 148 ms                                                 | 130 ms: 1.14x faster                                                  |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 568 ms: 1.14x faster                                                  |
| unpickle_pure_python     | 191 us                                                 | 169 us: 1.13x faster                                                  |
| unpack_sequence          | 36.7 ns                                                | 32.6 ns: 1.12x faster                                                 |
| genshi_text              | 17.1 ms                                                | 15.4 ms: 1.11x faster                                                 |
| sympy_integrate          | 13.2 ms                                                | 11.9 ms: 1.11x faster                                                 |
| genshi_xml               | 33.8 ms                                                | 30.6 ms: 1.10x faster                                                 |
| xml_etree_generate       | 53.2 ms                                                | 48.3 ms: 1.10x faster                                                 |
| fannkuch                 | 294 ms                                                 | 268 ms: 1.10x faster                                                  |
| sqlglot_optimize         | 36.3 ms                                                | 33.0 ms: 1.10x faster                                                 |
| generators               | 32.6 ms                                                | 29.7 ms: 1.10x faster                                                 |
| sympy_sum                | 92.4 ms                                                | 84.5 ms: 1.09x faster                                                 |
| sqlglot_normalize        | 187 ms                                                 | 171 ms: 1.09x faster                                                  |
| json_loads               | 16.7 us                                                | 15.4 us: 1.09x faster                                                 |
| tomli_loads              | 1.65 sec                                               | 1.52 sec: 1.09x faster                                                |
| gunicorn                 | 1.35 ms                                                | 1.25 ms: 1.08x faster                                                 |
| telco                    | 3.42 ms                                                | 3.21 ms: 1.06x faster                                                 |
| json                     | 3.06 ms                                                | 2.88 ms: 1.06x faster                                                 |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.08 ms: 1.06x faster                                                 |
| meteor_contest           | 77.9 ms                                                | 73.7 ms: 1.06x faster                                                 |
| nqueens                  | 62.4 ms                                                | 59.1 ms: 1.06x faster                                                 |
| coroutines               | 19.6 ms                                                | 18.6 ms: 1.05x faster                                                 |
| sympy_str                | 164 ms                                                 | 156 ms: 1.05x faster                                                  |
| json_dumps               | 8.00 ms                                                | 7.61 ms: 1.05x faster                                                 |
| sympy_expand             | 267 ms                                                 | 254 ms: 1.05x faster                                                  |
| sqlite_synth             | 1.43 us                                                | 1.37 us: 1.04x faster                                                 |
| mdp                      | 1.87 sec                                               | 1.81 sec: 1.03x faster                                                |
| unpickle                 | 8.86 us                                                | 8.57 us: 1.03x faster                                                 |
| xml_etree_iterparse      | 72.7 ms                                                | 70.5 ms: 1.03x faster                                                 |
| pickle_list              | 2.72 us                                                | 2.64 us: 1.03x faster                                                 |
| regex_v8                 | 17.2 ms                                                | 16.8 ms: 1.03x faster                                                 |
| typing_runtime_protocols | 336 us                                                 | 328 us: 1.02x faster                                                  |
| pickle_dict              | 17.0 us                                                | 16.8 us: 1.01x faster                                                 |
| unpickle_list            | 2.79 us                                                | 2.75 us: 1.01x faster                                                 |
| pidigits                 | 282 ms                                                 | 280 ms: 1.01x faster                                                  |
| regex_effbot             | 2.46 ms                                                | 2.46 ms: 1.00x faster                                                 |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                                 |
| flaskblogging            | 2.76 ms                                                | 2.84 ms: 1.03x slower                                                 |
| sqlglot_transpile        | 1.40 ms                                                | 1.44 ms: 1.03x slower                                                 |
| pickle                   | 7.04 us                                                | 7.26 us: 1.03x slower                                                 |
| python_startup_no_site   | 8.64 ms                                                | 8.93 ms: 1.03x slower                                                 |
| bench_mp_pool            | 39.0 ms                                                | 40.6 ms: 1.04x slower                                                 |
| comprehensions           | 16.8 us                                                | 17.7 us: 1.06x slower                                                 |
| sqlglot_parse            | 1.20 ms                                                | 1.28 ms: 1.06x slower                                                 |
| dask                     | 254 ms                                                 | 298 ms: 1.17x slower                                                  |
| python_startup           | 11.7 ms                                                | 15.3 ms: 1.30x slower                                                 |
| coverage                 | 41.1 ms                                                | 330 ms: 8.03x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.10x faster                                                          |

Benchmark hidden because not significant (2): bench_thread_pool, regex_dna
Ignored benchmarks (8) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
