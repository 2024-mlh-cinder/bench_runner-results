
# Results vs. 3.11.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: darwin-arm64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.10x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 155 ms                                                 | 165 ms: 1.06x slower                                                  |
| chameleon      | 4.17 ms                                                | 4.87 ms: 1.17x slower                                                 |
| docutils       | 1.46 sec                                               | 1.51 sec: 1.04x slower                                                |
| html5lib       | 33.6 ms                                                | 36.4 ms: 1.08x slower                                                 |
| tornado_http   | 71.0 ms                                                | 77.9 ms: 1.10x slower                                                 |
| Geometric mean | (ref)                                                  | 1.09x slower                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 282 ms                                                 | 288 ms: 1.02x slower                                                  |
| async_tree_cpu_io_mixed | 522 ms                                                 | 568 ms: 1.09x slower                                                  |
| async_tree_io           | 705 ms                                                 | 786 ms: 1.11x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.05x slower                                                          |

Benchmark hidden because not significant (1): async_tree_memoization

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 55.4 ms                                                | 53.4 ms: 1.04x faster                                                 |
| pidigits       | 281 ms                                                 | 280 ms: 1.00x faster                                                  |
| nbody          | 68.7 ms                                                | 73.1 ms: 1.06x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 73.9 ms                                                | 76.4 ms: 1.03x slower                                                 |
| regex_v8       | 15.3 ms                                                | 16.8 ms: 1.10x slower                                                 |
| regex_dna      | 149 ms                                                 | 174 ms: 1.17x slower                                                  |
| Geometric mean | (ref)                                                  | 1.07x slower                                                          |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_parse      | 107 ms                                                 | 96.5 ms: 1.11x faster                                                 |
| json_loads           | 15.8 us                                                | 15.4 us: 1.03x faster                                                 |
| pickle_dict          | 17.0 us                                                | 16.8 us: 1.02x faster                                                 |
| pickle_list          | 2.67 us                                                | 2.64 us: 1.01x faster                                                 |
| unpickle_list        | 2.77 us                                                | 2.75 us: 1.01x faster                                                 |
| json_dumps           | 7.58 ms                                                | 7.61 ms: 1.00x slower                                                 |
| pickle               | 7.22 us                                                | 7.26 us: 1.01x slower                                                 |
| unpickle             | 8.32 us                                                | 8.57 us: 1.03x slower                                                 |
| xml_etree_generate   | 46.8 ms                                                | 48.3 ms: 1.03x slower                                                 |
| xml_etree_iterparse  | 68.2 ms                                                | 70.5 ms: 1.03x slower                                                 |
| unpickle_pure_python | 163 us                                                 | 169 us: 1.04x slower                                                  |
| pickle_pure_python   | 211 us                                                 | 223 us: 1.06x slower                                                  |
| xml_etree_process    | 34.0 ms                                                | 36.3 ms: 1.07x slower                                                 |
| tomli_loads          | 1.30 sec                                               | 1.52 sec: 1.16x slower                                                |
| Geometric mean       | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.15 ms                                                | 8.93 ms: 1.02x faster                                                 |
| python_startup         | 11.4 ms                                                | 15.3 ms: 1.34x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 8.22 ms                                                | 8.15 ms: 1.01x faster                                                 |
| genshi_text     | 14.5 ms                                                | 15.4 ms: 1.06x slower                                                 |
| genshi_xml      | 28.1 ms                                                | 30.6 ms: 1.09x slower                                                 |
| django_template | 19.8 ms                                                | 22.2 ms: 1.12x slower                                                 |
| Geometric mean  | (ref)                                                  | 1.07x slower                                                          |

All benchmarks:
===============

| Benchmark                | bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pathlib                  | 28.5 ms                                                | 23.8 ms: 1.20x faster                                                 |
| xml_etree_parse          | 107 ms                                                 | 96.5 ms: 1.11x faster                                                 |
| float                    | 55.4 ms                                                | 53.4 ms: 1.04x faster                                                 |
| deepcopy_memo            | 28.9 us                                                | 27.9 us: 1.03x faster                                                 |
| bench_mp_pool            | 41.9 ms                                                | 40.6 ms: 1.03x faster                                                 |
| json_loads               | 15.8 us                                                | 15.4 us: 1.03x faster                                                 |
| python_startup_no_site   | 9.15 ms                                                | 8.93 ms: 1.02x faster                                                 |
| meteor_contest           | 74.9 ms                                                | 73.7 ms: 1.02x faster                                                 |
| pickle_dict              | 17.0 us                                                | 16.8 us: 1.02x faster                                                 |
| pickle_list              | 2.67 us                                                | 2.64 us: 1.01x faster                                                 |
| mako                     | 8.22 ms                                                | 8.15 ms: 1.01x faster                                                 |
| unpickle_list            | 2.77 us                                                | 2.75 us: 1.01x faster                                                 |
| pidigits                 | 281 ms                                                 | 280 ms: 1.00x faster                                                  |
| deepcopy_reduce          | 1.98 us                                                | 1.99 us: 1.00x slower                                                 |
| gc_traversal             | 2.39 ms                                                | 2.40 ms: 1.00x slower                                                 |
| json_dumps               | 7.58 ms                                                | 7.61 ms: 1.00x slower                                                 |
| pickle                   | 7.22 us                                                | 7.26 us: 1.01x slower                                                 |
| pprint_pformat           | 989 ms                                                 | 996 ms: 1.01x slower                                                  |
| logging_simple           | 3.41 us                                                | 3.44 us: 1.01x slower                                                 |
| unpack_sequence          | 32.3 ns                                                | 32.6 ns: 1.01x slower                                                 |
| dulwich_log              | 29.9 ms                                                | 30.2 ms: 1.01x slower                                                 |
| sqlite_synth             | 1.35 us                                                | 1.37 us: 1.01x slower                                                 |
| telco                    | 3.17 ms                                                | 3.21 ms: 1.01x slower                                                 |
| logging_format           | 3.69 us                                                | 3.74 us: 1.01x slower                                                 |
| pprint_safe_repr         | 479 ms                                                 | 487 ms: 1.02x slower                                                  |
| generators               | 29.2 ms                                                | 29.7 ms: 1.02x slower                                                 |
| scimark_monte_carlo      | 47.1 ms                                                | 47.9 ms: 1.02x slower                                                 |
| scimark_fft              | 187 ms                                                 | 190 ms: 1.02x slower                                                  |
| typing_runtime_protocols | 323 us                                                 | 328 us: 1.02x slower                                                  |
| async_tree_none          | 282 ms                                                 | 288 ms: 1.02x slower                                                  |
| scimark_sparse_mat_mult  | 3.01 ms                                                | 3.08 ms: 1.02x slower                                                 |
| create_gc_cycles         | 715 us                                                 | 732 us: 1.02x slower                                                  |
| async_generators         | 192 ms                                                 | 197 ms: 1.02x slower                                                  |
| chaos                    | 48.2 ms                                                | 49.5 ms: 1.03x slower                                                 |
| unpickle                 | 8.32 us                                                | 8.57 us: 1.03x slower                                                 |
| xml_etree_generate       | 46.8 ms                                                | 48.3 ms: 1.03x slower                                                 |
| regex_compile            | 73.9 ms                                                | 76.4 ms: 1.03x slower                                                 |
| xml_etree_iterparse      | 68.2 ms                                                | 70.5 ms: 1.03x slower                                                 |
| sympy_sum                | 81.6 ms                                                | 84.5 ms: 1.04x slower                                                 |
| unpickle_pure_python     | 163 us                                                 | 169 us: 1.04x slower                                                  |
| json                     | 2.77 ms                                                | 2.88 ms: 1.04x slower                                                 |
| docutils                 | 1.46 sec                                               | 1.51 sec: 1.04x slower                                                |
| mdp                      | 1.73 sec                                               | 1.81 sec: 1.04x slower                                                |
| spectral_norm            | 69.7 ms                                                | 72.9 ms: 1.05x slower                                                 |
| sympy_integrate          | 11.3 ms                                                | 11.9 ms: 1.05x slower                                                 |
| pickle_pure_python       | 211 us                                                 | 223 us: 1.06x slower                                                  |
| 2to3                     | 155 ms                                                 | 165 ms: 1.06x slower                                                  |
| nbody                    | 68.7 ms                                                | 73.1 ms: 1.06x slower                                                 |
| genshi_text              | 14.5 ms                                                | 15.4 ms: 1.06x slower                                                 |
| xml_etree_process        | 34.0 ms                                                | 36.3 ms: 1.07x slower                                                 |
| thrift                   | 424 us                                                 | 453 us: 1.07x slower                                                  |
| sqlglot_normalize        | 160 ms                                                 | 171 ms: 1.07x slower                                                  |
| sympy_str                | 144 ms                                                 | 156 ms: 1.08x slower                                                  |
| nqueens                  | 54.6 ms                                                | 59.1 ms: 1.08x slower                                                 |
| html5lib                 | 33.6 ms                                                | 36.4 ms: 1.08x slower                                                 |
| fannkuch                 | 247 ms                                                 | 268 ms: 1.08x slower                                                  |
| hexiom                   | 4.55 ms                                                | 4.95 ms: 1.09x slower                                                 |
| genshi_xml               | 28.1 ms                                                | 30.6 ms: 1.09x slower                                                 |
| async_tree_cpu_io_mixed  | 522 ms                                                 | 568 ms: 1.09x slower                                                  |
| sympy_expand             | 234 ms                                                 | 254 ms: 1.09x slower                                                  |
| regex_v8                 | 15.3 ms                                                | 16.8 ms: 1.10x slower                                                 |
| tornado_http             | 71.0 ms                                                | 77.9 ms: 1.10x slower                                                 |
| pycparser                | 667 ms                                                 | 742 ms: 1.11x slower                                                  |
| raytrace                 | 200 ms                                                 | 223 ms: 1.11x slower                                                  |
| async_tree_io            | 705 ms                                                 | 786 ms: 1.11x slower                                                  |
| sqlglot_optimize         | 29.6 ms                                                | 33.0 ms: 1.12x slower                                                 |
| bench_thread_pool        | 461 us                                                 | 516 us: 1.12x slower                                                  |
| django_template          | 19.8 ms                                                | 22.2 ms: 1.12x slower                                                 |
| gunicorn                 | 1.11 ms                                                | 1.25 ms: 1.12x slower                                                 |
| coroutines               | 16.6 ms                                                | 18.6 ms: 1.12x slower                                                 |
| flaskblogging            | 2.46 ms                                                | 2.84 ms: 1.16x slower                                                 |
| tomli_loads              | 1.30 sec                                               | 1.52 sec: 1.16x slower                                                |
| chameleon                | 4.17 ms                                                | 4.87 ms: 1.17x slower                                                 |
| regex_dna                | 149 ms                                                 | 174 ms: 1.17x slower                                                  |
| crypto_pyaes             | 48.1 ms                                                | 56.9 ms: 1.18x slower                                                 |
| pyflate                  | 297 ms                                                 | 354 ms: 1.19x slower                                                  |
| comprehensions           | 14.7 us                                                | 17.7 us: 1.21x slower                                                 |
| deltablue                | 2.70 ms                                                | 3.26 ms: 1.21x slower                                                 |
| logging_silent           | 64.5 ns                                                | 81.4 ns: 1.26x slower                                                 |
| richards                 | 30.8 ms                                                | 39.0 ms: 1.27x slower                                                 |
| go                       | 102 ms                                                 | 130 ms: 1.27x slower                                                  |
| scimark_lu               | 67.8 ms                                                | 87.1 ms: 1.28x slower                                                 |
| richards_super           | 36.8 ms                                                | 48.0 ms: 1.30x slower                                                 |
| scimark_sor              | 75.2 ms                                                | 98.4 ms: 1.31x slower                                                 |
| dask                     | 224 ms                                                 | 298 ms: 1.33x slower                                                  |
| python_startup           | 11.4 ms                                                | 15.3 ms: 1.34x slower                                                 |
| sqlglot_transpile        | 1.05 ms                                                | 1.44 ms: 1.38x slower                                                 |
| sqlglot_parse            | 886 us                                                 | 1.28 ms: 1.44x slower                                                 |
| coverage                 | 41.4 ms                                                | 330 ms: 7.98x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.10x slower                                                          |

Benchmark hidden because not significant (3): async_tree_memoization, regex_effbot, deepcopy
Ignored benchmarks (12) of results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, pylint, sqlalchemy_declarative, sqlalchemy_imperative


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.04x
- 95% likely to have a slowdown of 1.04x
- 99% likely to have a slowdown of 1.03x
