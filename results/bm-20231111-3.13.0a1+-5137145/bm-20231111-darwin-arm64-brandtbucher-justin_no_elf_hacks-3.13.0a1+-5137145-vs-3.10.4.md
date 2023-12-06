
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: darwin-arm64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.15x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.09x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 189 ms                                                 | 180 ms: 1.05x faster                                                        |
| chameleon      | 5.95 ms                                                | 4.75 ms: 1.25x faster                                                       |
| docutils       | 1.73 sec                                               | 1.53 sec: 1.13x faster                                                      |
| tornado_http   | 89.9 ms                                                | 73.3 ms: 1.23x faster                                                       |
| Geometric mean | (ref)                                                  | 1.16x faster                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_none         | 384 ms                                                 | 256 ms: 1.50x faster                                                        |
| async_tree_memoization  | 473 ms                                                 | 334 ms: 1.42x faster                                                        |
| async_tree_io           | 984 ms                                                 | 710 ms: 1.39x faster                                                        |
| async_tree_cpu_io_mixed | 646 ms                                                 | 529 ms: 1.22x faster                                                        |
| Geometric mean          | (ref)                                                  | 1.38x faster                                                                |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| float          | 66.8 ms                                                | 60.3 ms: 1.11x faster                                                       |
| nbody          | 88.1 ms                                                | 83.6 ms: 1.05x faster                                                       |
| pidigits       | 282 ms                                                 | 283 ms: 1.00x slower                                                        |
| Geometric mean | (ref)                                                  | 1.05x faster                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 174 ms                                                 | 149 ms: 1.17x faster                                                        |
| regex_compile  | 92.3 ms                                                | 82.0 ms: 1.13x faster                                                       |
| regex_v8       | 17.2 ms                                                | 17.0 ms: 1.02x faster                                                       |
| regex_effbot   | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                       |
| Geometric mean | (ref)                                                  | 1.06x faster                                                                |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pickle_pure_python   | 272 us                                                 | 200 us: 1.36x faster                                                        |
| json_dumps           | 8.00 ms                                                | 6.66 ms: 1.20x faster                                                       |
| unpickle_pure_python | 191 us                                                 | 164 us: 1.16x faster                                                        |
| xml_etree_process    | 45.6 ms                                                | 40.0 ms: 1.14x faster                                                       |
| tomli_loads          | 1.65 sec                                               | 1.49 sec: 1.11x faster                                                      |
| xml_etree_parse      | 111 ms                                                 | 110 ms: 1.01x faster                                                        |
| unpickle             | 8.86 us                                                | 9.19 us: 1.04x slower                                                       |
| pickle_dict          | 17.0 us                                                | 17.8 us: 1.05x slower                                                       |
| json_loads           | 16.7 us                                                | 17.7 us: 1.05x slower                                                       |
| xml_etree_iterparse  | 72.7 ms                                                | 76.8 ms: 1.06x slower                                                       |
| pickle_list          | 2.72 us                                                | 2.88 us: 1.06x slower                                                       |
| pickle               | 7.04 us                                                | 7.46 us: 1.06x slower                                                       |
| xml_etree_generate   | 53.2 ms                                                | 58.6 ms: 1.10x slower                                                       |
| unpickle_list        | 2.79 us                                                | 3.20 us: 1.15x slower                                                       |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                                |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 11.7 ms                                                | 12.6 ms: 1.07x slower                                                       |
| python_startup_no_site | 8.64 ms                                                | 11.2 ms: 1.29x slower                                                       |
| Geometric mean         | (ref)                                                  | 1.18x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 9.86 ms                                                | 8.00 ms: 1.23x faster                                                       |

All benchmarks:
===============

| Benchmark                | bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120 | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|--------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------------:|
| typing_runtime_protocols | 336 us                                                 | 76.5 us: 4.40x faster                                                       |
| deltablue                | 4.94 ms                                                | 2.66 ms: 1.86x faster                                                       |
| logging_silent           | 115 ns                                                 | 70.9 ns: 1.62x faster                                                       |
| raytrace                 | 293 ms                                                 | 184 ms: 1.59x faster                                                        |
| richards_super           | 57.1 ms                                                | 37.0 ms: 1.54x faster                                                       |
| asyncio_tcp              | 667 ms                                                 | 443 ms: 1.51x faster                                                        |
| async_tree_none          | 384 ms                                                 | 256 ms: 1.50x faster                                                        |
| chaos                    | 64.1 ms                                                | 44.1 ms: 1.45x faster                                                       |
| sqlglot_parse            | 1.20 ms                                                | 840 us: 1.43x faster                                                        |
| richards                 | 47.6 ms                                                | 33.6 ms: 1.42x faster                                                       |
| async_tree_memoization   | 473 ms                                                 | 334 ms: 1.42x faster                                                        |
| crypto_pyaes             | 70.8 ms                                                | 50.1 ms: 1.41x faster                                                       |
| unpack_sequence          | 36.7 ns                                                | 26.3 ns: 1.40x faster                                                       |
| async_tree_io            | 984 ms                                                 | 710 ms: 1.39x faster                                                        |
| sqlglot_transpile        | 1.40 ms                                                | 1.02 ms: 1.37x faster                                                       |
| go                       | 148 ms                                                 | 109 ms: 1.36x faster                                                        |
| pickle_pure_python       | 272 us                                                 | 200 us: 1.36x faster                                                        |
| scimark_lu               | 102 ms                                                 | 75.8 ms: 1.34x faster                                                       |
| generators               | 32.6 ms                                                | 24.5 ms: 1.33x faster                                                       |
| deepcopy_memo            | 33.1 us                                                | 25.8 us: 1.28x faster                                                       |
| scimark_monte_carlo      | 62.8 ms                                                | 49.5 ms: 1.27x faster                                                       |
| asyncio_tcp_ssl          | 1.64 sec                                               | 1.29 sec: 1.27x faster                                                      |
| spectral_norm            | 92.1 ms                                                | 72.9 ms: 1.26x faster                                                       |
| scimark_sor              | 134 ms                                                 | 107 ms: 1.26x faster                                                        |
| chameleon                | 5.95 ms                                                | 4.75 ms: 1.25x faster                                                       |
| pycparser                | 878 ms                                                 | 705 ms: 1.25x faster                                                        |
| create_gc_cycles         | 865 us                                                 | 702 us: 1.23x faster                                                        |
| mako                     | 9.86 ms                                                | 8.00 ms: 1.23x faster                                                       |
| tornado_http             | 89.9 ms                                                | 73.3 ms: 1.23x faster                                                       |
| async_tree_cpu_io_mixed  | 646 ms                                                 | 529 ms: 1.22x faster                                                        |
| pyflate                  | 419 ms                                                 | 345 ms: 1.21x faster                                                        |
| deepcopy                 | 269 us                                                 | 222 us: 1.21x faster                                                        |
| sympy_sum                | 92.4 ms                                                | 76.5 ms: 1.21x faster                                                       |
| json_dumps               | 8.00 ms                                                | 6.66 ms: 1.20x faster                                                       |
| logging_format           | 4.62 us                                                | 3.87 us: 1.19x faster                                                       |
| comprehensions           | 16.8 us                                                | 14.0 us: 1.19x faster                                                       |
| pprint_safe_repr         | 628 ms                                                 | 528 ms: 1.19x faster                                                        |
| logging_simple           | 4.25 us                                                | 3.58 us: 1.19x faster                                                       |
| pprint_pformat           | 1.27 sec                                               | 1.08 sec: 1.18x faster                                                      |
| regex_dna                | 174 ms                                                 | 149 ms: 1.17x faster                                                        |
| unpickle_pure_python     | 191 us                                                 | 164 us: 1.16x faster                                                        |
| deepcopy_reduce          | 2.28 us                                                | 1.97 us: 1.16x faster                                                       |
| dulwich_log              | 35.6 ms                                                | 30.8 ms: 1.16x faster                                                       |
| sympy_integrate          | 13.2 ms                                                | 11.5 ms: 1.14x faster                                                       |
| xml_etree_process        | 45.6 ms                                                | 40.0 ms: 1.14x faster                                                       |
| docutils                 | 1.73 sec                                               | 1.53 sec: 1.13x faster                                                      |
| sympy_str                | 164 ms                                                 | 146 ms: 1.13x faster                                                        |
| regex_compile            | 92.3 ms                                                | 82.0 ms: 1.13x faster                                                       |
| tomli_loads              | 1.65 sec                                               | 1.49 sec: 1.11x faster                                                      |
| float                    | 66.8 ms                                                | 60.3 ms: 1.11x faster                                                       |
| mdp                      | 1.87 sec                                               | 1.70 sec: 1.10x faster                                                      |
| coroutines               | 19.6 ms                                                | 17.9 ms: 1.09x faster                                                       |
| hexiom                   | 6.07 ms                                                | 5.55 ms: 1.09x faster                                                       |
| sympy_expand             | 267 ms                                                 | 250 ms: 1.07x faster                                                        |
| nbody                    | 88.1 ms                                                | 83.6 ms: 1.05x faster                                                       |
| 2to3                     | 189 ms                                                 | 180 ms: 1.05x faster                                                        |
| sqlglot_optimize         | 36.3 ms                                                | 35.1 ms: 1.03x faster                                                       |
| json                     | 3.06 ms                                                | 3.00 ms: 1.02x faster                                                       |
| bench_thread_pool        | 516 us                                                 | 507 us: 1.02x faster                                                        |
| regex_v8                 | 17.2 ms                                                | 17.0 ms: 1.02x faster                                                       |
| xml_etree_parse          | 111 ms                                                 | 110 ms: 1.01x faster                                                        |
| pidigits                 | 282 ms                                                 | 283 ms: 1.00x slower                                                        |
| asyncio_websockets       | 544 ms                                                 | 545 ms: 1.00x slower                                                        |
| sqlglot_normalize        | 187 ms                                                 | 188 ms: 1.01x slower                                                        |
| gc_traversal             | 2.37 ms                                                | 2.40 ms: 1.01x slower                                                       |
| scimark_fft              | 216 ms                                                 | 220 ms: 1.02x slower                                                        |
| fannkuch                 | 294 ms                                                 | 299 ms: 1.02x slower                                                        |
| unpickle                 | 8.86 us                                                | 9.19 us: 1.04x slower                                                       |
| regex_effbot             | 2.46 ms                                                | 2.56 ms: 1.04x slower                                                       |
| nqueens                  | 62.4 ms                                                | 65.2 ms: 1.05x slower                                                       |
| pickle_dict              | 17.0 us                                                | 17.8 us: 1.05x slower                                                       |
| json_loads               | 16.7 us                                                | 17.7 us: 1.05x slower                                                       |
| xml_etree_iterparse      | 72.7 ms                                                | 76.8 ms: 1.06x slower                                                       |
| pickle_list              | 2.72 us                                                | 2.88 us: 1.06x slower                                                       |
| pickle                   | 7.04 us                                                | 7.46 us: 1.06x slower                                                       |
| scimark_sparse_mat_mult  | 3.26 ms                                                | 3.46 ms: 1.06x slower                                                       |
| python_startup           | 11.7 ms                                                | 12.6 ms: 1.07x slower                                                       |
| xml_etree_generate       | 53.2 ms                                                | 58.6 ms: 1.10x slower                                                       |
| unpickle_list            | 2.79 us                                                | 3.20 us: 1.15x slower                                                       |
| sqlite_synth             | 1.43 us                                                | 1.64 us: 1.15x slower                                                       |
| bench_mp_pool            | 39.0 ms                                                | 45.8 ms: 1.17x slower                                                       |
| coverage                 | 41.1 ms                                                | 48.6 ms: 1.18x slower                                                       |
| python_startup_no_site   | 8.64 ms                                                | 11.2 ms: 1.29x slower                                                       |
| async_generators         | 233 ms                                                 | 316 ms: 1.36x slower                                                        |
| telco                    | 3.42 ms                                                | 4.75 ms: 1.39x slower                                                       |
| Geometric mean           | (ref)                                                  | 1.15x faster                                                                |

Benchmark hidden because not significant (3): mypy2, meteor_contest, pathlib
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
Ignored benchmarks (4) of results/bm-20231111-3.13.0a1+-5137145/bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.11x
- 95% likely to have a speedup of 1.11x
- 99% likely to have a speedup of 1.09x
