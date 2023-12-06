
# Results vs. 3.12.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: darwin-arm64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.07x slower \*
- HPT reliability: 97.67%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 171 ms                                                 | 165 ms: 1.03x faster                                                  |
| chameleon      | 4.51 ms                                                | 4.87 ms: 1.08x slower                                                 |
| docutils       | 1.54 sec                                               | 1.51 sec: 1.02x faster                                                |
| tornado_http   | 70.7 ms                                                | 77.9 ms: 1.10x slower                                                 |
| Geometric mean | (ref)                                                  | 1.03x slower                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 525 ms                                                 | 568 ms: 1.08x slower                                                  |
| async_tree_none         | 262 ms                                                 | 288 ms: 1.10x slower                                                  |
| async_tree_memoization  | 309 ms                                                 | 359 ms: 1.16x slower                                                  |
| async_tree_io           | 669 ms                                                 | 786 ms: 1.17x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.13x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 58.1 ms                                                | 53.4 ms: 1.09x faster                                                 |
| pidigits       | 282 ms                                                 | 280 ms: 1.01x faster                                                  |
| nbody          | 68.5 ms                                                | 73.1 ms: 1.07x slower                                                 |
| Geometric mean | (ref)                                                  | 1.01x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 2.59 ms                                                | 2.46 ms: 1.05x faster                                                 |
| regex_compile  | 75.6 ms                                                | 76.4 ms: 1.01x slower                                                 |
| regex_v8       | 15.7 ms                                                | 16.8 ms: 1.07x slower                                                 |
| regex_dna      | 153 ms                                                 | 174 ms: 1.14x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| unpickle_list        | 3.24 us                                                | 2.75 us: 1.18x faster                                                 |
| xml_etree_generate   | 55.9 ms                                                | 48.3 ms: 1.16x faster                                                 |
| json_loads           | 17.6 us                                                | 15.4 us: 1.15x faster                                                 |
| xml_etree_parse      | 109 ms                                                 | 96.5 ms: 1.13x faster                                                 |
| pickle_list          | 2.89 us                                                | 2.64 us: 1.10x faster                                                 |
| unpickle             | 9.25 us                                                | 8.57 us: 1.08x faster                                                 |
| pickle_dict          | 18.0 us                                                | 16.8 us: 1.07x faster                                                 |
| xml_etree_process    | 38.7 ms                                                | 36.3 ms: 1.07x faster                                                 |
| xml_etree_iterparse  | 74.6 ms                                                | 70.5 ms: 1.06x faster                                                 |
| pickle               | 7.42 us                                                | 7.26 us: 1.02x faster                                                 |
| tomli_loads          | 1.39 sec                                               | 1.52 sec: 1.09x slower                                                |
| unpickle_pure_python | 145 us                                                 | 169 us: 1.17x slower                                                  |
| json_dumps           | 6.46 ms                                                | 7.61 ms: 1.18x slower                                                 |
| pickle_pure_python   | 188 us                                                 | 223 us: 1.18x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 9.71 ms                                                | 8.93 ms: 1.09x faster                                                 |
| python_startup         | 11.9 ms                                                | 15.3 ms: 1.28x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.09x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 22.1 ms                                                | 22.2 ms: 1.00x slower                                                 |
| mako            | 7.53 ms                                                | 8.15 ms: 1.08x slower                                                 |
| Geometric mean  | (ref)                                                  | 1.04x slower                                                          |

All benchmarks:
===============

| Benchmark                | bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0 | bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_generators         | 306 ms                                                 | 197 ms: 1.55x faster                                                  |
| pathlib                  | 29.3 ms                                                | 23.8 ms: 1.23x faster                                                 |
| unpickle_list            | 3.24 us                                                | 2.75 us: 1.18x faster                                                 |
| telco                    | 3.79 ms                                                | 3.21 ms: 1.18x faster                                                 |
| sqlite_synth             | 1.59 us                                                | 1.37 us: 1.16x faster                                                 |
| xml_etree_generate       | 55.9 ms                                                | 48.3 ms: 1.16x faster                                                 |
| json_loads               | 17.6 us                                                | 15.4 us: 1.15x faster                                                 |
| bench_mp_pool            | 46.3 ms                                                | 40.6 ms: 1.14x faster                                                 |
| xml_etree_parse          | 109 ms                                                 | 96.5 ms: 1.13x faster                                                 |
| raytrace                 | 246 ms                                                 | 223 ms: 1.10x faster                                                  |
| sqlglot_normalize        | 188 ms                                                 | 171 ms: 1.10x faster                                                  |
| pickle_list              | 2.89 us                                                | 2.64 us: 1.10x faster                                                 |
| float                    | 58.1 ms                                                | 53.4 ms: 1.09x faster                                                 |
| python_startup_no_site   | 9.71 ms                                                | 8.93 ms: 1.09x faster                                                 |
| unpickle                 | 9.25 us                                                | 8.57 us: 1.08x faster                                                 |
| pickle_dict              | 18.0 us                                                | 16.8 us: 1.07x faster                                                 |
| logging_simple           | 3.69 us                                                | 3.44 us: 1.07x faster                                                 |
| xml_etree_process        | 38.7 ms                                                | 36.3 ms: 1.07x faster                                                 |
| logging_format           | 3.99 us                                                | 3.74 us: 1.07x faster                                                 |
| xml_etree_iterparse      | 74.6 ms                                                | 70.5 ms: 1.06x faster                                                 |
| regex_effbot             | 2.59 ms                                                | 2.46 ms: 1.05x faster                                                 |
| sqlglot_optimize         | 34.7 ms                                                | 33.0 ms: 1.05x faster                                                 |
| json                     | 3.02 ms                                                | 2.88 ms: 1.05x faster                                                 |
| scimark_monte_carlo      | 50.1 ms                                                | 47.9 ms: 1.05x faster                                                 |
| scimark_fft              | 198 ms                                                 | 190 ms: 1.04x faster                                                  |
| 2to3                     | 171 ms                                                 | 165 ms: 1.03x faster                                                  |
| deepcopy_reduce          | 2.05 us                                                | 1.99 us: 1.03x faster                                                 |
| spectral_norm            | 74.6 ms                                                | 72.9 ms: 1.02x faster                                                 |
| scimark_sparse_mat_mult  | 3.14 ms                                                | 3.08 ms: 1.02x faster                                                 |
| pickle                   | 7.42 us                                                | 7.26 us: 1.02x faster                                                 |
| nqueens                  | 60.2 ms                                                | 59.1 ms: 1.02x faster                                                 |
| docutils                 | 1.54 sec                                               | 1.51 sec: 1.02x faster                                                |
| pprint_safe_repr         | 491 ms                                                 | 487 ms: 1.01x faster                                                  |
| pidigits                 | 282 ms                                                 | 280 ms: 1.01x faster                                                  |
| dulwich_log              | 30.4 ms                                                | 30.2 ms: 1.01x faster                                                 |
| pprint_pformat           | 1.00 sec                                               | 996 ms: 1.00x faster                                                  |
| gc_traversal             | 2.40 ms                                                | 2.40 ms: 1.00x faster                                                 |
| django_template          | 22.1 ms                                                | 22.2 ms: 1.00x slower                                                 |
| meteor_contest           | 73.3 ms                                                | 73.7 ms: 1.00x slower                                                 |
| regex_compile            | 75.6 ms                                                | 76.4 ms: 1.01x slower                                                 |
| fannkuch                 | 265 ms                                                 | 268 ms: 1.01x slower                                                  |
| sympy_expand             | 249 ms                                                 | 254 ms: 1.02x slower                                                  |
| coroutines               | 18.1 ms                                                | 18.6 ms: 1.03x slower                                                 |
| sympy_str                | 151 ms                                                 | 156 ms: 1.03x slower                                                  |
| gunicorn                 | 1.21 ms                                                | 1.25 ms: 1.04x slower                                                 |
| deepcopy                 | 225 us                                                 | 233 us: 1.04x slower                                                  |
| create_gc_cycles         | 704 us                                                 | 732 us: 1.04x slower                                                  |
| scimark_sor              | 94.3 ms                                                | 98.4 ms: 1.04x slower                                                 |
| generators               | 28.3 ms                                                | 29.7 ms: 1.05x slower                                                 |
| bench_thread_pool        | 492 us                                                 | 516 us: 1.05x slower                                                  |
| sympy_integrate          | 11.3 ms                                                | 11.9 ms: 1.05x slower                                                 |
| sympy_sum                | 79.5 ms                                                | 84.5 ms: 1.06x slower                                                 |
| nbody                    | 68.5 ms                                                | 73.1 ms: 1.07x slower                                                 |
| regex_v8                 | 15.7 ms                                                | 16.8 ms: 1.07x slower                                                 |
| pyflate                  | 329 ms                                                 | 354 ms: 1.08x slower                                                  |
| chameleon                | 4.51 ms                                                | 4.87 ms: 1.08x slower                                                 |
| async_tree_cpu_io_mixed  | 525 ms                                                 | 568 ms: 1.08x slower                                                  |
| mako                     | 7.53 ms                                                | 8.15 ms: 1.08x slower                                                 |
| mdp                      | 1.66 sec                                               | 1.81 sec: 1.09x slower                                                |
| tomli_loads              | 1.39 sec                                               | 1.52 sec: 1.09x slower                                                |
| crypto_pyaes             | 52.0 ms                                                | 56.9 ms: 1.09x slower                                                 |
| async_tree_none          | 262 ms                                                 | 288 ms: 1.10x slower                                                  |
| tornado_http             | 70.7 ms                                                | 77.9 ms: 1.10x slower                                                 |
| pycparser                | 670 ms                                                 | 742 ms: 1.11x slower                                                  |
| chaos                    | 44.8 ms                                                | 49.5 ms: 1.11x slower                                                 |
| comprehensions           | 15.8 us                                                | 17.7 us: 1.12x slower                                                 |
| deepcopy_memo            | 24.6 us                                                | 27.9 us: 1.14x slower                                                 |
| regex_dna                | 153 ms                                                 | 174 ms: 1.14x slower                                                  |
| unpack_sequence          | 28.4 ns                                                | 32.6 ns: 1.15x slower                                                 |
| async_tree_memoization   | 309 ms                                                 | 359 ms: 1.16x slower                                                  |
| hexiom                   | 4.25 ms                                                | 4.95 ms: 1.16x slower                                                 |
| unpickle_pure_python     | 145 us                                                 | 169 us: 1.17x slower                                                  |
| async_tree_io            | 669 ms                                                 | 786 ms: 1.17x slower                                                  |
| json_dumps               | 6.46 ms                                                | 7.61 ms: 1.18x slower                                                 |
| pickle_pure_python       | 188 us                                                 | 223 us: 1.18x slower                                                  |
| logging_silent           | 68.3 ns                                                | 81.4 ns: 1.19x slower                                                 |
| go                       | 107 ms                                                 | 130 ms: 1.21x slower                                                  |
| scimark_lu               | 71.5 ms                                                | 87.1 ms: 1.22x slower                                                 |
| richards                 | 31.1 ms                                                | 39.0 ms: 1.25x slower                                                 |
| deltablue                | 2.58 ms                                                | 3.26 ms: 1.26x slower                                                 |
| python_startup           | 11.9 ms                                                | 15.3 ms: 1.28x slower                                                 |
| dask                     | 228 ms                                                 | 298 ms: 1.31x slower                                                  |
| sqlglot_transpile        | 1.08 ms                                                | 1.44 ms: 1.34x slower                                                 |
| richards_super           | 34.9 ms                                                | 48.0 ms: 1.37x slower                                                 |
| sqlglot_parse            | 897 us                                                 | 1.28 ms: 1.42x slower                                                 |
| typing_runtime_protocols | 90.8 us                                                | 328 us: 3.62x slower                                                  |
| coverage                 | 37.9 ms                                                | 330 ms: 8.70x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.07x slower                                                          |
Ignored benchmarks (11) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2, sqlalchemy_declarative, sqlalchemy_imperative
Ignored benchmarks (5) of results/bm-20211105-3.11.0a2-e2b4e4b/bm-20211105-darwin-arm64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b.json: flaskblogging, genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 97.67% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
