
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin
- machine: darwin-arm64
- commit hash: 7bb54b5
- commit date: 2023-11-20
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 181 ms: 1.05x faster                                           |
| chameleon      | 5.95 ms                                                | 4.89 ms: 1.22x faster                                          |
| docutils       | 1.73 sec                                               | 1.53 sec: 1.13x faster                                         |
| tornado_http   | 89.9 ms                                                | 73.1 ms: 1.23x faster                                          |
| Geometric mean | (ref)                                                  | 1.15x faster                                                   |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 257 ms: 1.50x faster                                           |
| async_tree_memoization  | 473 ms                                                 | 332 ms: 1.42x faster                                           |
| async_tree_io           | 984 ms                                                 | 706 ms: 1.39x faster                                           |
| async_tree_cpu_io_mixed | 646 ms                                                 | 528 ms: 1.22x faster                                           |
| Geometric mean          | (ref)                                                  | 1.38x faster                                                   |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| float          | 66.8 ms                                                | 58.4 ms: 1.14x faster                                          |
| nbody          | 88.1 ms                                                | 81.4 ms: 1.08x faster                                          |
| pidigits       | 282 ms                                                 | 282 ms: 1.00x faster                                           |
| Geometric mean | (ref)                                                  | 1.07x faster                                                   |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                           |
| regex_compile  | 92.3 ms                                                | 83.7 ms: 1.10x faster                                          |
| regex_v8       | 17.2 ms                                                | 17.0 ms: 1.02x faster                                          |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                          |
| Geometric mean | (ref)                                                  | 1.06x faster                                                   |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|----------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 204 us: 1.33x faster                                           |
| json_dumps           | 8.00 ms                                                | 6.67 ms: 1.20x faster                                          |
| unpickle_pure_python | 191 us                                                 | 166 us: 1.15x faster                                           |
| xml_etree_process    | 45.6 ms                                                | 40.8 ms: 1.12x faster                                          |
| tomli_loads          | 1.65 sec                                               | 1.52 sec: 1.09x faster                                         |
| xml_etree_parse      | 111 ms                                                 | 107 ms: 1.03x faster                                           |
| unpickle             | 8.86 us                                                | 9.04 us: 1.02x slower                                          |
| json_loads           | 16.7 us                                                | 17.2 us: 1.03x slower                                          |
| pickle_dict          | 17.0 us                                                | 17.9 us: 1.05x slower                                          |
| xml_etree_iterparse  | 72.7 ms                                                | 76.6 ms: 1.05x slower                                          |
| pickle               | 7.04 us                                                | 7.43 us: 1.05x slower                                          |
| pickle_list          | 2.72 us                                                | 2.88 us: 1.06x slower                                          |
| xml_etree_generate   | 53.2 ms                                                | 58.9 ms: 1.11x slower                                          |
| unpickle_list        | 2.79 us                                                | 3.13 us: 1.13x slower                                          |
| Geometric mean       | (ref)                                                  | 1.03x faster                                                   |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 11.6 ms: 1.01x faster                                          |
| python_startup_no_site | 8.64 ms                                                | 10.2 ms: 1.18x slower                                          |
| Geometric mean         | (ref)                                                  | 1.08x slower                                                   |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|-----------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 7.92 ms: 1.24x faster                                          |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5 |
|--------------------------|:------------------------------------------------------:|:--------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 77.5 us: 4.34x faster                                          |
| deltablue                | 4.94 ms                                                | 2.57 ms: 1.92x faster                                          |
| asyncio_tcp              | 667 ms                                                 | 398 ms: 1.67x faster                                           |
| logging_silent           | 115 ns                                                 | 73.5 ns: 1.56x faster                                          |
| richards_super           | 57.1 ms                                                | 36.9 ms: 1.55x faster                                          |
| raytrace                 | 293 ms                                                 | 194 ms: 1.51x faster                                           |
| async_tree_none          | 384 ms                                                 | 257 ms: 1.50x faster                                           |
| richards                 | 47.6 ms                                                | 33.2 ms: 1.43x faster                                          |
| chaos                    | 64.1 ms                                                | 45.1 ms: 1.42x faster                                          |
| async_tree_memoization   | 473 ms                                                 | 332 ms: 1.42x faster                                           |
| crypto_pyaes             | 70.8 ms                                                | 50.1 ms: 1.41x faster                                          |
| async_tree_io            | 984 ms                                                 | 706 ms: 1.39x faster                                           |
| sqlglot_parse            | 1.20 ms                                                | 868 us: 1.39x faster                                           |
| sqlglot_transpile        | 1.40 ms                                                | 1.05 ms: 1.33x faster                                          |
| asyncio_websockets       | 544 ms                                                 | 409 ms: 1.33x faster                                           |
| pickle_pure_python       | 272 us                                                 | 204 us: 1.33x faster                                           |
| scimark_lu               | 102 ms                                                 | 77.5 ms: 1.31x faster                                          |
| go                       | 148 ms                                                 | 114 ms: 1.30x faster                                           |
| unpack_sequence          | 36.7 ns                                                | 28.4 ns: 1.29x faster                                          |
| generators               | 32.6 ms                                                | 25.6 ms: 1.27x faster                                          |
| deepcopy_memo            | 33.1 us                                                | 26.1 us: 1.26x faster                                          |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.30 sec: 1.26x faster                                         |
| scimark_monte_carlo      | 62.8 ms                                                | 50.0 ms: 1.26x faster                                          |
| mako                     | 9.86 ms                                                | 7.92 ms: 1.24x faster                                          |
| scimark_sor              | 134 ms                                                 | 108 ms: 1.24x faster                                           |
| pathlib                  | 29.4 ms                                                | 23.8 ms: 1.24x faster                                          |
| create_gc_cycles         | 865 us                                                 | 699 us: 1.24x faster                                           |
| tornado_http             | 89.9 ms                                                | 73.1 ms: 1.23x faster                                          |
| pycparser                | 878 ms                                                 | 715 ms: 1.23x faster                                           |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 528 ms: 1.22x faster                                           |
| chameleon                | 5.95 ms                                                | 4.89 ms: 1.22x faster                                          |
| comprehensions           | 16.8 us                                                | 13.9 us: 1.21x faster                                          |
| json_dumps               | 8.00 ms                                                | 6.67 ms: 1.20x faster                                          |
| pyflate                  | 419 ms                                                 | 350 ms: 1.20x faster                                           |
| logging_format           | 4.62 us                                                | 3.90 us: 1.18x faster                                          |
| logging_simple           | 4.25 us                                                | 3.60 us: 1.18x faster                                          |
| dulwich_log              | 35.6 ms                                                | 30.3 ms: 1.17x faster                                          |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                           |
| pprint_safe_repr         | 628 ms                                                 | 538 ms: 1.17x faster                                           |
| deepcopy                 | 269 us                                                 | 232 us: 1.16x faster                                           |
| sympy_sum                | 92.4 ms                                                | 80.4 ms: 1.15x faster                                          |
| unpickle_pure_python     | 191 us                                                 | 166 us: 1.15x faster                                           |
| pprint_pformat           | 1.27 sec                                               | 1.11 sec: 1.15x faster                                         |
| float                    | 66.8 ms                                                | 58.4 ms: 1.14x faster                                          |
| spectral_norm            | 92.1 ms                                                | 81.4 ms: 1.13x faster                                          |
| docutils                 | 1.73 sec                                               | 1.53 sec: 1.13x faster                                         |
| mypy2                    | 300 ms                                                 | 266 ms: 1.13x faster                                           |
| xml_etree_process        | 45.6 ms                                                | 40.8 ms: 1.12x faster                                          |
| deepcopy_reduce          | 2.28 us                                                | 2.05 us: 1.11x faster                                          |
| sympy_integrate          | 13.2 ms                                                | 11.9 ms: 1.10x faster                                          |
| dask                     | 254 ms                                                 | 230 ms: 1.10x faster                                           |
| mdp                      | 1.87 sec                                               | 1.69 sec: 1.10x faster                                         |
| regex_compile            | 92.3 ms                                                | 83.7 ms: 1.10x faster                                          |
| tomli_loads              | 1.65 sec                                               | 1.52 sec: 1.09x faster                                         |
| nbody                    | 88.1 ms                                                | 81.4 ms: 1.08x faster                                          |
| sympy_str                | 164 ms                                                 | 152 ms: 1.08x faster                                           |
| coroutines               | 19.6 ms                                                | 18.6 ms: 1.05x faster                                          |
| hexiom                   | 6.07 ms                                                | 5.79 ms: 1.05x faster                                          |
| 2to3                     | 189 ms                                                 | 181 ms: 1.05x faster                                           |
| sympy_expand             | 267 ms                                                 | 259 ms: 1.03x faster                                           |
| xml_etree_parse          | 111 ms                                                 | 107 ms: 1.03x faster                                           |
| regex_v8                 | 17.2 ms                                                | 17.0 ms: 1.02x faster                                          |
| json                     | 3.06 ms                                                | 3.01 ms: 1.01x faster                                          |
| python_startup           | 11.7 ms                                                | 11.6 ms: 1.01x faster                                          |
| pidigits                 | 282 ms                                                 | 282 ms: 1.00x faster                                           |
| gc_traversal             | 2.37 ms                                                | 2.39 ms: 1.01x slower                                          |
| meteor_contest           | 77.9 ms                                                | 78.8 ms: 1.01x slower                                          |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.30 ms: 1.01x slower                                          |
| fannkuch                 | 294 ms                                                 | 299 ms: 1.01x slower                                           |
| sqlglot_optimize         | 36.3 ms                                                | 36.8 ms: 1.02x slower                                          |
| unpickle                 | 8.86 us                                                | 9.04 us: 1.02x slower                                          |
| bench_thread_pool        | 516 us                                                 | 530 us: 1.03x slower                                           |
| json_loads               | 16.7 us                                                | 17.2 us: 1.03x slower                                          |
| scimark_fft              | 216 ms                                                 | 224 ms: 1.03x slower                                           |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                          |
| nqueens                  | 62.4 ms                                                | 65.6 ms: 1.05x slower                                          |
| sqlglot_normalize        | 187 ms                                                 | 197 ms: 1.05x slower                                           |
| pickle_dict              | 17.0 us                                                | 17.9 us: 1.05x slower                                          |
| xml_etree_iterparse      | 72.7 ms                                                | 76.6 ms: 1.05x slower                                          |
| pickle                   | 7.04 us                                                | 7.43 us: 1.05x slower                                          |
| pickle_list              | 2.72 us                                                | 2.88 us: 1.06x slower                                          |
| xml_etree_generate       | 53.2 ms                                                | 58.9 ms: 1.11x slower                                          |
| unpickle_list            | 2.79 us                                                | 3.13 us: 1.13x slower                                          |
| bench_mp_pool            | 39.0 ms                                                | 45.4 ms: 1.16x slower                                          |
| sqlite_synth             | 1.43 us                                                | 1.66 us: 1.17x slower                                          |
| coverage                 | 41.1 ms                                                | 48.3 ms: 1.18x slower                                          |
| python_startup_no_site   | 8.64 ms                                                | 10.2 ms: 1.18x slower                                          |
| async_generators         | 233 ms                                                 | 317 ms: 1.36x slower                                           |
| telco                    | 3.42 ms                                                | 4.76 ms: 1.39x slower                                          |
| Geometric mean           | (ref)                                                  | 1.15x faster                                                   |
Ignored benchmarks (11) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231120-3.13.0a1+-7bb54b5/bm-20231120-darwin-arm64-brandtbucher-justin-3.13.0a1+-7bb54b5.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.10x
- 99% likely to have a speedup of 1.09x
