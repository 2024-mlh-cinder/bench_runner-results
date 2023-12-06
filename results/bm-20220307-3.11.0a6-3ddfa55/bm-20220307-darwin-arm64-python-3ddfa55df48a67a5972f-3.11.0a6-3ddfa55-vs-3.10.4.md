
# Results vs. 3.10.4

- fork: python
- ref: 3ddfa55df48a67a5972f
- machine: darwin-arm64
- commit hash: 3ddfa55
- commit date: 2022-03-07
- overall geometric mean: 1.11x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.11x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 164 ms: 1.15x faster                                                  |
| chameleon      | 5.95 ms                                                | 4.55 ms: 1.31x faster                                                 |
| docutils       | 1.73 sec                                               | 1.47 sec: 1.18x faster                                                |
| html5lib       | 41.5 ms                                                | 33.5 ms: 1.24x faster                                                 |
| tornado_http   | 89.9 ms                                                | 73.8 ms: 1.22x faster                                                 |
| Geometric mean | (ref)                                                  | 1.22x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_io           | 984 ms                                                 | 704 ms: 1.40x faster                                                  |
| async_tree_memoization  | 473 ms                                                 | 347 ms: 1.36x faster                                                  |
| async_tree_none         | 384 ms                                                 | 287 ms: 1.34x faster                                                  |
| async_tree_cpu_io_mixed | 646 ms                                                 | 533 ms: 1.21x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.33x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 66.8 ms                                                | 54.8 ms: 1.22x faster                                                 |
| nbody          | 88.1 ms                                                | 74.1 ms: 1.19x faster                                                 |
| pidigits       | 282 ms                                                 | 281 ms: 1.00x faster                                                  |
| Geometric mean | (ref)                                                  | 1.13x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 92.3 ms                                                | 76.7 ms: 1.20x faster                                                 |
| regex_effbot   | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| regex_v8       | 17.2 ms                                                | 17.5 ms: 1.02x slower                                                 |
| regex_dna      | 174 ms                                                 | 177 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.04x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 214 us: 1.27x faster                                                  |
| xml_etree_process    | 45.6 ms                                                | 36.5 ms: 1.25x faster                                                 |
| tomli_loads          | 1.65 sec                                               | 1.44 sec: 1.15x faster                                                |
| unpickle_pure_python | 191 us                                                 | 167 us: 1.14x faster                                                  |
| xml_etree_parse      | 111 ms                                                 | 97.5 ms: 1.14x faster                                                 |
| json_loads           | 16.7 us                                                | 14.9 us: 1.13x faster                                                 |
| xml_etree_generate   | 53.2 ms                                                | 48.7 ms: 1.09x faster                                                 |
| unpickle             | 8.86 us                                                | 8.29 us: 1.07x faster                                                 |
| xml_etree_iterparse  | 72.7 ms                                                | 69.4 ms: 1.05x faster                                                 |
| json_dumps           | 8.00 ms                                                | 7.66 ms: 1.04x faster                                                 |
| pickle_list          | 2.72 us                                                | 2.61 us: 1.04x faster                                                 |
| unpickle_list        | 2.79 us                                                | 2.74 us: 1.02x faster                                                 |
| pickle_dict          | 17.0 us                                                | 17.3 us: 1.02x slower                                                 |
| pickle               | 7.04 us                                                | 7.21 us: 1.02x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.09x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 8.64 ms                                                | 9.28 ms: 1.07x slower                                                 |
| python_startup         | 11.7 ms                                                | 14.8 ms: 1.27x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.17x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 9.86 ms                                                | 7.33 ms: 1.34x faster                                                 |
| django_template | 25.8 ms                                                | 21.6 ms: 1.20x faster                                                 |
| genshi_text     | 17.1 ms                                                | 15.2 ms: 1.12x faster                                                 |
| genshi_xml      | 33.8 ms                                                | 31.4 ms: 1.08x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.18x faster                                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue                | 4.94 ms                                                | 3.03 ms: 1.63x faster                                                 |
| scimark_sor              | 134 ms                                                 | 88.7 ms: 1.51x faster                                                 |
| logging_silent           | 115 ns                                                 | 80.3 ns: 1.43x faster                                                 |
| scimark_monte_carlo      | 62.8 ms                                                | 44.6 ms: 1.41x faster                                                 |
| async_tree_io            | 984 ms                                                 | 704 ms: 1.40x faster                                                  |
| raytrace                 | 293 ms                                                 | 214 ms: 1.37x faster                                                  |
| richards                 | 47.6 ms                                                | 34.9 ms: 1.36x faster                                                 |
| richards_super           | 57.1 ms                                                | 41.9 ms: 1.36x faster                                                 |
| async_tree_memoization   | 473 ms                                                 | 347 ms: 1.36x faster                                                  |
| chaos                    | 64.1 ms                                                | 47.2 ms: 1.36x faster                                                 |
| scimark_lu               | 102 ms                                                 | 75.5 ms: 1.35x faster                                                 |
| logging_format           | 4.62 us                                                | 3.43 us: 1.35x faster                                                 |
| mako                     | 9.86 ms                                                | 7.33 ms: 1.34x faster                                                 |
| async_tree_none          | 384 ms                                                 | 287 ms: 1.34x faster                                                  |
| logging_simple           | 4.25 us                                                | 3.21 us: 1.32x faster                                                 |
| pyflate                  | 419 ms                                                 | 316 ms: 1.32x faster                                                  |
| go                       | 148 ms                                                 | 112 ms: 1.32x faster                                                  |
| chameleon                | 5.95 ms                                                | 4.55 ms: 1.31x faster                                                 |
| thrift                   | 561 us                                                 | 433 us: 1.30x faster                                                  |
| crypto_pyaes             | 70.8 ms                                                | 55.4 ms: 1.28x faster                                                 |
| pathlib                  | 29.4 ms                                                | 23.1 ms: 1.27x faster                                                 |
| hexiom                   | 6.07 ms                                                | 4.78 ms: 1.27x faster                                                 |
| pickle_pure_python       | 272 us                                                 | 214 us: 1.27x faster                                                  |
| xml_etree_process        | 45.6 ms                                                | 36.5 ms: 1.25x faster                                                 |
| html5lib                 | 41.5 ms                                                | 33.5 ms: 1.24x faster                                                 |
| pycparser                | 878 ms                                                 | 711 ms: 1.23x faster                                                  |
| spectral_norm            | 92.1 ms                                                | 75.5 ms: 1.22x faster                                                 |
| float                    | 66.8 ms                                                | 54.8 ms: 1.22x faster                                                 |
| tornado_http             | 89.9 ms                                                | 73.8 ms: 1.22x faster                                                 |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 533 ms: 1.21x faster                                                  |
| regex_compile            | 92.3 ms                                                | 76.7 ms: 1.20x faster                                                 |
| deepcopy_memo            | 33.1 us                                                | 27.5 us: 1.20x faster                                                 |
| create_gc_cycles         | 865 us                                                 | 720 us: 1.20x faster                                                  |
| async_generators         | 233 ms                                                 | 194 ms: 1.20x faster                                                  |
| django_template          | 25.8 ms                                                | 21.6 ms: 1.20x faster                                                 |
| nbody                    | 88.1 ms                                                | 74.1 ms: 1.19x faster                                                 |
| dulwich_log              | 35.6 ms                                                | 30.0 ms: 1.19x faster                                                 |
| docutils                 | 1.73 sec                                               | 1.47 sec: 1.18x faster                                                |
| deepcopy                 | 269 us                                                 | 229 us: 1.17x faster                                                  |
| pprint_safe_repr         | 628 ms                                                 | 538 ms: 1.17x faster                                                  |
| deepcopy_reduce          | 2.28 us                                                | 1.95 us: 1.17x faster                                                 |
| sqlalchemy_declarative   | 73.7 ms                                                | 63.8 ms: 1.15x faster                                                 |
| 2to3                     | 189 ms                                                 | 164 ms: 1.15x faster                                                  |
| pprint_pformat           | 1.27 sec                                               | 1.10 sec: 1.15x faster                                                |
| tomli_loads              | 1.65 sec                                               | 1.44 sec: 1.15x faster                                                |
| aiohttp                  | 1.29 ms                                                | 1.12 ms: 1.15x faster                                                 |
| sqlite_synth             | 1.43 us                                                | 1.25 us: 1.14x faster                                                 |
| unpickle_pure_python     | 191 us                                                 | 167 us: 1.14x faster                                                  |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.44 sec: 1.14x faster                                                |
| pylint                   | 282 ms                                                 | 247 ms: 1.14x faster                                                  |
| xml_etree_parse          | 111 ms                                                 | 97.5 ms: 1.14x faster                                                 |
| flaskblogging            | 2.76 ms                                                | 2.43 ms: 1.14x faster                                                 |
| sqlglot_optimize         | 36.3 ms                                                | 32.2 ms: 1.13x faster                                                 |
| sympy_sum                | 92.4 ms                                                | 82.0 ms: 1.13x faster                                                 |
| json                     | 3.06 ms                                                | 2.71 ms: 1.13x faster                                                 |
| json_loads               | 16.7 us                                                | 14.9 us: 1.13x faster                                                 |
| genshi_text              | 17.1 ms                                                | 15.2 ms: 1.12x faster                                                 |
| sympy_integrate          | 13.2 ms                                                | 11.7 ms: 1.12x faster                                                 |
| sqlalchemy_imperative    | 8.65 ms                                                | 7.72 ms: 1.12x faster                                                 |
| fannkuch                 | 294 ms                                                 | 264 ms: 1.12x faster                                                  |
| gunicorn                 | 1.35 ms                                                | 1.21 ms: 1.12x faster                                                 |
| scimark_fft              | 216 ms                                                 | 194 ms: 1.12x faster                                                  |
| sqlglot_normalize        | 187 ms                                                 | 170 ms: 1.10x faster                                                  |
| sympy_str                | 164 ms                                                 | 150 ms: 1.10x faster                                                  |
| xml_etree_generate       | 53.2 ms                                                | 48.7 ms: 1.09x faster                                                 |
| coroutines               | 19.6 ms                                                | 18.1 ms: 1.09x faster                                                 |
| sympy_expand             | 267 ms                                                 | 247 ms: 1.08x faster                                                  |
| genshi_xml               | 33.8 ms                                                | 31.4 ms: 1.08x faster                                                 |
| unpickle                 | 8.86 us                                                | 8.29 us: 1.07x faster                                                 |
| nqueens                  | 62.4 ms                                                | 58.5 ms: 1.07x faster                                                 |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.07 ms: 1.06x faster                                                 |
| generators               | 32.6 ms                                                | 30.8 ms: 1.06x faster                                                 |
| meteor_contest           | 77.9 ms                                                | 74.1 ms: 1.05x faster                                                 |
| xml_etree_iterparse      | 72.7 ms                                                | 69.4 ms: 1.05x faster                                                 |
| json_dumps               | 8.00 ms                                                | 7.66 ms: 1.04x faster                                                 |
| pickle_list              | 2.72 us                                                | 2.61 us: 1.04x faster                                                 |
| mdp                      | 1.87 sec                                               | 1.80 sec: 1.04x faster                                                |
| telco                    | 3.42 ms                                                | 3.34 ms: 1.02x faster                                                 |
| typing_runtime_protocols | 336 us                                                 | 330 us: 1.02x faster                                                  |
| unpickle_list            | 2.79 us                                                | 2.74 us: 1.02x faster                                                 |
| bench_thread_pool        | 516 us                                                 | 510 us: 1.01x faster                                                  |
| asyncio_tcp              | 667 ms                                                 | 663 ms: 1.01x faster                                                  |
| pidigits                 | 282 ms                                                 | 281 ms: 1.00x faster                                                  |
| regex_effbot             | 2.46 ms                                                | 2.45 ms: 1.00x faster                                                 |
| sqlglot_transpile        | 1.40 ms                                                | 1.40 ms: 1.00x faster                                                 |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                                 |
| regex_v8                 | 17.2 ms                                                | 17.5 ms: 1.02x slower                                                 |
| pickle_dict              | 17.0 us                                                | 17.3 us: 1.02x slower                                                 |
| comprehensions           | 16.8 us                                                | 17.1 us: 1.02x slower                                                 |
| regex_dna                | 174 ms                                                 | 177 ms: 1.02x slower                                                  |
| sqlglot_parse            | 1.20 ms                                                | 1.23 ms: 1.02x slower                                                 |
| pickle                   | 7.04 us                                                | 7.21 us: 1.02x slower                                                 |
| python_startup_no_site   | 8.64 ms                                                | 9.28 ms: 1.07x slower                                                 |
| bench_mp_pool            | 39.0 ms                                                | 42.8 ms: 1.10x slower                                                 |
| dask                     | 254 ms                                                 | 308 ms: 1.21x slower                                                  |
| python_startup           | 11.7 ms                                                | 14.8 ms: 1.27x slower                                                 |
| unpack_sequence          | 36.7 ns                                                | 93.6 ns: 2.55x slower                                                 |
| coverage                 | 41.1 ms                                                | 328 ms: 7.97x slower                                                  |
| Geometric mean           | (ref)                                                  | 1.11x faster                                                          |
Ignored benchmarks (2) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: asyncio_websockets, mypy2
Ignored benchmarks (4) of results/bm-20220307-3.11.0a6-3ddfa55/bm-20220307-darwin-arm64-python-3ddfa55df48a67a5972f-3.11.0a6-3ddfa55.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.13x
- 95% likely to have a speedup of 1.12x
- 99% likely to have a speedup of 1.11x
