
# Results vs. 3.10.4

- fork: python
- ref: 2e91dba437fe5c56c6f8
- machine: darwin-arm64
- commit hash: 2e91dba
- commit date: 2021-12-08
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 155 ms: 1.22x faster                                                  |
| chameleon      | 5.95 ms                                                | 4.65 ms: 1.28x faster                                                 |
| docutils       | 1.73 sec                                               | 1.48 sec: 1.17x faster                                                |
| html5lib       | 41.5 ms                                                | 33.6 ms: 1.23x faster                                                 |
| tornado_http   | 89.9 ms                                                | 76.9 ms: 1.17x faster                                                 |
| Geometric mean | (ref)                                                  | 1.21x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 288 ms: 1.33x faster                                                  |
| async_tree_memoization  | 473 ms                                                 | 374 ms: 1.26x faster                                                  |
| async_tree_io           | 984 ms                                                 | 816 ms: 1.21x faster                                                  |
| async_tree_cpu_io_mixed | 646 ms                                                 | 558 ms: 1.16x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.24x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| nbody          | 88.1 ms                                                | 64.4 ms: 1.37x faster                                                 |
| float          | 66.8 ms                                                | 51.6 ms: 1.29x faster                                                 |
| Geometric mean | (ref)                                                  | 1.21x faster                                                          |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 72.7 ms: 1.27x faster                                                 |
| regex_v8       | 17.2 ms                                                | 16.6 ms: 1.04x faster                                                 |
| regex_effbot   | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| regex_dna      | 174 ms                                                 | 173 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                  | 1.07x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 203 us: 1.34x faster                                                  |
| xml_etree_process    | 45.6 ms                                                | 35.1 ms: 1.30x faster                                                 |
| tomli_loads          | 1.65 sec                                               | 1.36 sec: 1.22x faster                                                |
| unpickle_pure_python | 191 us                                                 | 158 us: 1.21x faster                                                  |
| xml_etree_parse      | 111 ms                                                 | 96.7 ms: 1.15x faster                                                 |
| xml_etree_generate   | 53.2 ms                                                | 47.3 ms: 1.12x faster                                                 |
| json_loads           | 16.7 us                                                | 15.3 us: 1.10x faster                                                 |
| json_dumps           | 8.00 ms                                                | 7.46 ms: 1.07x faster                                                 |
| xml_etree_iterparse  | 72.7 ms                                                | 69.6 ms: 1.04x faster                                                 |
| unpickle             | 8.86 us                                                | 8.57 us: 1.03x faster                                                 |
| pickle_list          | 2.72 us                                                | 2.67 us: 1.02x faster                                                 |
| unpickle_list        | 2.79 us                                                | 2.75 us: 1.01x faster                                                 |
| pickle_dict          | 17.0 us                                                | 16.8 us: 1.01x faster                                                 |
| pickle               | 7.04 us                                                | 7.39 us: 1.05x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.11x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 8.64 ms                                                | 9.02 ms: 1.04x slower                                                 |
| python_startup         | 11.7 ms                                                | 14.9 ms: 1.27x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.15x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| django_template | 25.8 ms                                                | 20.8 ms: 1.24x faster                                                 |
| mako            | 9.86 ms                                                | 8.07 ms: 1.22x faster                                                 |
| genshi_text     | 17.1 ms                                                | 14.8 ms: 1.16x faster                                                 |
| genshi_xml      | 33.8 ms                                                | 29.4 ms: 1.15x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.19x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20211208-darwin-arm64-python-2e91dba437fe5c56c6f8-3.11.0a3-2e91dba |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.94 ms                                                | 2.96 ms: 1.67x faster                                                 |
| scimark_sor              | 134 ms                                                 | 85.3 ms: 1.57x faster                                                 |
| logging_silent           | 115 ns                                                 | 74.3 ns: 1.55x faster                                                 |
| scimark_monte_carlo      | 62.8 ms                                                | 43.2 ms: 1.45x faster                                                 |
| richards                 | 47.6 ms                                                | 33.2 ms: 1.43x faster                                                 |
| scimark_lu               | 102 ms                                                 | 71.4 ms: 1.42x faster                                                 |
| chaos                    | 64.1 ms                                                | 46.4 ms: 1.38x faster                                                 |
| hexiom                   | 6.07 ms                                                | 4.41 ms: 1.38x faster                                                 |
| nbody                    | 88.1 ms                                                | 64.4 ms: 1.37x faster                                                 |
| pprint_safe_repr         | 628 ms                                                 | 465 ms: 1.35x faster                                                  |
| raytrace                 | 293 ms                                                 | 218 ms: 1.34x faster                                                  |
| pickle_pure_python       | 272 us                                                 | 203 us: 1.34x faster                                                  |
| richards_super           | 57.1 ms                                                | 42.7 ms: 1.34x faster                                                 |
| logging_simple           | 4.25 us                                                | 3.19 us: 1.34x faster                                                 |
| pprint_pformat           | 1.27 sec                                               | 952 ms: 1.34x faster                                                  |
| async_tree_none          | 384 ms                                                 | 288 ms: 1.33x faster                                                  |
| logging_format           | 4.62 us                                                | 3.49 us: 1.32x faster                                                 |
| go                       | 148 ms                                                 | 113 ms: 1.31x faster                                                  |
| xml_etree_process        | 45.6 ms                                                | 35.1 ms: 1.30x faster                                                 |
| pyflate                  | 419 ms                                                 | 322 ms: 1.30x faster                                                  |
| float                    | 66.8 ms                                                | 51.6 ms: 1.29x faster                                                 |
| spectral_norm            | 92.1 ms                                                | 71.6 ms: 1.29x faster                                                 |
| chameleon                | 5.95 ms                                                | 4.65 ms: 1.28x faster                                                 |
| thrift                   | 561 us                                                 | 440 us: 1.27x faster                                                  |
| deepcopy_memo            | 33.1 us                                                | 26.0 us: 1.27x faster                                                 |
| regex_compile            | 92.3 ms                                                | 72.7 ms: 1.27x faster                                                 |
| crypto_pyaes             | 70.8 ms                                                | 56.0 ms: 1.26x faster                                                 |
| async_tree_memoization   | 473 ms                                                 | 374 ms: 1.26x faster                                                  |
| pathlib                  | 29.4 ms                                                | 23.3 ms: 1.26x faster                                                 |
| pycparser                | 878 ms                                                 | 702 ms: 1.25x faster                                                  |
| django_template          | 25.8 ms                                                | 20.8 ms: 1.24x faster                                                 |
| html5lib                 | 41.5 ms                                                | 33.6 ms: 1.23x faster                                                 |
| generators               | 32.6 ms                                                | 26.6 ms: 1.23x faster                                                 |
| mako                     | 9.86 ms                                                | 8.07 ms: 1.22x faster                                                 |
| 2to3                     | 189 ms                                                 | 155 ms: 1.22x faster                                                  |
| async_generators         | 233 ms                                                 | 191 ms: 1.22x faster                                                  |
| tomli_loads              | 1.65 sec                                               | 1.36 sec: 1.22x faster                                                |
| unpickle_pure_python     | 191 us                                                 | 158 us: 1.21x faster                                                  |
| async_tree_io            | 984 ms                                                 | 816 ms: 1.21x faster                                                  |
| deepcopy_reduce          | 2.28 us                                                | 1.89 us: 1.20x faster                                                 |
| dulwich_log              | 35.6 ms                                                | 29.6 ms: 1.20x faster                                                 |
| deepcopy                 | 269 us                                                 | 224 us: 1.20x faster                                                  |
| fannkuch                 | 294 ms                                                 | 247 ms: 1.19x faster                                                  |
| create_gc_cycles         | 865 us                                                 | 729 us: 1.19x faster                                                  |
| unpack_sequence          | 36.7 ns                                                | 31.0 ns: 1.18x faster                                                 |
| sqlalchemy_declarative   | 73.7 ms                                                | 62.6 ms: 1.18x faster                                                 |
| scimark_fft              | 216 ms                                                 | 184 ms: 1.17x faster                                                  |
| pylint                   | 282 ms                                                 | 241 ms: 1.17x faster                                                  |
| tornado_http             | 89.9 ms                                                | 76.9 ms: 1.17x faster                                                 |
| docutils                 | 1.73 sec                                               | 1.48 sec: 1.17x faster                                                |
| sqlalchemy_imperative    | 8.65 ms                                                | 7.43 ms: 1.16x faster                                                 |
| sympy_integrate          | 13.2 ms                                                | 11.3 ms: 1.16x faster                                                 |
| coroutines               | 19.6 ms                                                | 16.9 ms: 1.16x faster                                                 |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 558 ms: 1.16x faster                                                  |
| genshi_text              | 17.1 ms                                                | 14.8 ms: 1.16x faster                                                 |
| sqlglot_optimize         | 36.3 ms                                                | 31.6 ms: 1.15x faster                                                 |
| genshi_xml               | 33.8 ms                                                | 29.4 ms: 1.15x faster                                                 |
| xml_etree_parse          | 111 ms                                                 | 96.7 ms: 1.15x faster                                                 |
| sqlglot_normalize        | 187 ms                                                 | 164 ms: 1.14x faster                                                  |
| flaskblogging            | 2.76 ms                                                | 2.43 ms: 1.14x faster                                                 |
| xml_etree_generate       | 53.2 ms                                                | 47.3 ms: 1.12x faster                                                 |
| nqueens                  | 62.4 ms                                                | 55.5 ms: 1.12x faster                                                 |
| sympy_sum                | 92.4 ms                                                | 82.2 ms: 1.12x faster                                                 |
| gunicorn                 | 1.35 ms                                                | 1.23 ms: 1.10x faster                                                 |
| json_loads               | 16.7 us                                                | 15.3 us: 1.10x faster                                                 |
| sympy_expand             | 267 ms                                                 | 244 ms: 1.09x faster                                                  |
| sympy_str                | 164 ms                                                 | 151 ms: 1.09x faster                                                  |
| meteor_contest           | 77.9 ms                                                | 71.7 ms: 1.09x faster                                                 |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.01 ms: 1.08x faster                                                 |
| sqlite_synth             | 1.43 us                                                | 1.32 us: 1.08x faster                                                 |
| json_dumps               | 8.00 ms                                                | 7.46 ms: 1.07x faster                                                 |
| json                     | 3.06 ms                                                | 2.86 ms: 1.07x faster                                                 |
| mdp                      | 1.87 sec                                               | 1.76 sec: 1.07x faster                                                |
| xml_etree_iterparse      | 72.7 ms                                                | 69.6 ms: 1.04x faster                                                 |
| typing_runtime_protocols | 336 us                                                 | 325 us: 1.04x faster                                                  |
| regex_v8                 | 17.2 ms                                                | 16.6 ms: 1.04x faster                                                 |
| bench_thread_pool        | 516 us                                                 | 498 us: 1.04x faster                                                  |
| sqlglot_transpile        | 1.40 ms                                                | 1.35 ms: 1.04x faster                                                 |
| unpickle                 | 8.86 us                                                | 8.57 us: 1.03x faster                                                 |
| telco                    | 3.42 ms                                                | 3.31 ms: 1.03x faster                                                 |
| pickle_list              | 2.72 us                                                | 2.67 us: 1.02x faster                                                 |
| comprehensions           | 16.8 us                                                | 16.5 us: 1.02x faster                                                 |
| sqlglot_parse            | 1.20 ms                                                | 1.19 ms: 1.01x faster                                                 |
| unpickle_list            | 2.79 us                                                | 2.75 us: 1.01x faster                                                 |
| pickle_dict              | 17.0 us                                                | 16.8 us: 1.01x faster                                                 |
| regex_effbot             | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| regex_dna                | 174 ms                                                 | 173 ms: 1.00x faster                                                  |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                                 |
| python_startup_no_site   | 8.64 ms                                                | 9.02 ms: 1.04x slower                                                 |
| pickle                   | 7.04 us                                                | 7.39 us: 1.05x slower                                                 |
| bench_mp_pool            | 39.0 ms                                                | 41.4 ms: 1.06x slower                                                 |
| dask                     | 254 ms                                                 | 302 ms: 1.19x slower                                                  |
| python_startup           | 11.7 ms                                                | 14.9 ms: 1.27x slower                                                 |
| coverage                 | 41.1 ms                                                | 303 ms: 7.37x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.15x faster                                                          |

Benchmark hidden because not significant (1): pidigits
Ignored benchmarks (5) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, mypy2


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.16x
- 95% likely to have a speedup of 1.16x
- 99% likely to have a speedup of 1.15x
