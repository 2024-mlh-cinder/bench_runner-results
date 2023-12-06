
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_opargs
- machine: linux-x86_64
- commit hash: 9d7c25a
- commit date: 2023-09-06
- overall geometric mean: 1.24x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| docutils       | 3.40 sec                                                     | 2.95 sec: 1.15x faster                                                     |
| tornado_http   | 152 ms                                                       | 122 ms: 1.25x faster                                                       |
| Geometric mean | (ref)                                                        | 1.20x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 137 ms                                                       | 93.4 ms: 1.47x faster                                                      |
| float          | 110 ms                                                       | 82.9 ms: 1.33x faster                                                      |
| pidigits       | 271 ms                                                       | 264 ms: 1.02x faster                                                       |
| Geometric mean | (ref)                                                        | 1.26x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 194 ms                                                       | 156 ms: 1.24x faster                                                       |
| regex_dna      | 259 ms                                                       | 248 ms: 1.04x faster                                                       |
| regex_v8       | 26.6 ms                                                      | 25.8 ms: 1.03x faster                                                      |
| regex_effbot   | 2.99 ms                                                      | 3.56 ms: 1.19x slower                                                      |
| Geometric mean | (ref)                                                        | 1.03x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|----------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 457 us                                                       | 317 us: 1.44x faster                                                       |
| json_dumps           | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                      |
| unpickle_pure_python | 321 us                                                       | 242 us: 1.32x faster                                                       |
| xml_etree_process    | 76.0 ms                                                      | 60.2 ms: 1.26x faster                                                      |
| tomli_loads          | 2.97 sec                                                     | 2.38 sec: 1.25x faster                                                     |
| json_loads           | 30.0 us                                                      | 25.1 us: 1.20x faster                                                      |
| xml_etree_generate   | 94.6 ms                                                      | 86.3 ms: 1.10x faster                                                      |
| xml_etree_parse      | 162 ms                                                       | 148 ms: 1.09x faster                                                       |
| xml_etree_iterparse  | 110 ms                                                       | 108 ms: 1.02x faster                                                       |
| pickle               | 9.94 us                                                      | 10.1 us: 1.01x slower                                                      |
| unpickle             | 14.2 us                                                      | 14.4 us: 1.01x slower                                                      |
| unpickle_list        | 4.49 us                                                      | 4.68 us: 1.04x slower                                                      |
| pickle_dict          | 30.0 us                                                      | 31.9 us: 1.06x slower                                                      |
| pickle_list          | 4.11 us                                                      | 4.51 us: 1.10x slower                                                      |
| Geometric mean       | (ref)                                                        | 1.12x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 11.5 ms                                                      | 12.3 ms: 1.07x slower                                                      |
| python_startup_no_site | 7.32 ms                                                      | 9.26 ms: 1.27x slower                                                      |
| Geometric mean         | (ref)                                                        | 1.16x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|-----------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 14.7 ms                                                      | 10.6 ms: 1.39x faster                                                      |

All benchmarks:
===============

| Benchmark                | bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230906-pythonperf2-x86_64-brandtbucher-justin_opargs-3.13.0a0-9d7c25a |
|--------------------------|:------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| typing_runtime_protocols | 523 us                                                       | 156 us: 3.35x faster                                                       |
| asyncio_tcp              | 782 ms                                                       | 372 ms: 2.10x faster                                                       |
| deltablue                | 7.47 ms                                                      | 3.78 ms: 1.97x faster                                                      |
| asyncio_tcp_ssl          | 3.09 sec                                                     | 1.58 sec: 1.96x faster                                                     |
| raytrace                 | 488 ms                                                       | 279 ms: 1.75x faster                                                       |
| logging_silent           | 166 ns                                                       | 100.0 ns: 1.66x faster                                                     |
| chaos                    | 107 ms                                                       | 66.9 ms: 1.60x faster                                                      |
| crypto_pyaes             | 118 ms                                                       | 74.2 ms: 1.59x faster                                                      |
| async_tree_none          | 700 ms                                                       | 441 ms: 1.59x faster                                                       |
| generators               | 58.0 ms                                                      | 36.9 ms: 1.57x faster                                                      |
| sqlglot_parse            | 2.26 ms                                                      | 1.46 ms: 1.55x faster                                                      |
| scimark_lu               | 164 ms                                                       | 106 ms: 1.54x faster                                                       |
| scimark_monte_carlo      | 109 ms                                                       | 71.1 ms: 1.54x faster                                                      |
| richards_super           | 90.8 ms                                                      | 60.6 ms: 1.50x faster                                                      |
| async_tree_memoization   | 824 ms                                                       | 555 ms: 1.48x faster                                                       |
| async_tree_io            | 1.61 sec                                                     | 1.09 sec: 1.47x faster                                                     |
| nbody                    | 137 ms                                                       | 93.4 ms: 1.47x faster                                                      |
| bench_mp_pool            | 7.18 ms                                                      | 4.90 ms: 1.47x faster                                                      |
| go                       | 259 ms                                                       | 179 ms: 1.44x faster                                                       |
| sqlglot_transpile        | 2.71 ms                                                      | 1.88 ms: 1.44x faster                                                      |
| pickle_pure_python       | 457 us                                                       | 317 us: 1.44x faster                                                       |
| spectral_norm            | 136 ms                                                       | 95.2 ms: 1.43x faster                                                      |
| mako                     | 14.7 ms                                                      | 10.6 ms: 1.39x faster                                                      |
| pyflate                  | 697 ms                                                       | 503 ms: 1.39x faster                                                       |
| richards                 | 74.1 ms                                                      | 53.8 ms: 1.38x faster                                                      |
| async_tree_cpu_io_mixed  | 952 ms                                                       | 707 ms: 1.35x faster                                                       |
| json_dumps               | 14.2 ms                                                      | 10.6 ms: 1.34x faster                                                      |
| float                    | 110 ms                                                       | 82.9 ms: 1.33x faster                                                      |
| unpickle_pure_python     | 321 us                                                       | 242 us: 1.32x faster                                                       |
| coroutines               | 30.4 ms                                                      | 23.1 ms: 1.32x faster                                                      |
| pprint_pformat           | 2.15 sec                                                     | 1.66 sec: 1.30x faster                                                     |
| logging_simple           | 8.90 us                                                      | 6.88 us: 1.29x faster                                                      |
| pprint_safe_repr         | 1.05 sec                                                     | 815 ms: 1.29x faster                                                       |
| hexiom                   | 9.52 ms                                                      | 7.40 ms: 1.29x faster                                                      |
| xml_etree_process        | 76.0 ms                                                      | 60.2 ms: 1.26x faster                                                      |
| logging_format           | 9.57 us                                                      | 7.61 us: 1.26x faster                                                      |
| tornado_http             | 152 ms                                                       | 122 ms: 1.25x faster                                                       |
| pycparser                | 1.66 sec                                                     | 1.33 sec: 1.25x faster                                                     |
| tomli_loads              | 2.97 sec                                                     | 2.38 sec: 1.25x faster                                                     |
| deepcopy_memo            | 48.9 us                                                      | 39.4 us: 1.24x faster                                                      |
| regex_compile            | 194 ms                                                       | 156 ms: 1.24x faster                                                       |
| mypy2                    | 466 ms                                                       | 386 ms: 1.21x faster                                                       |
| json_loads               | 30.0 us                                                      | 25.1 us: 1.20x faster                                                      |
| sqlglot_normalize        | 144 ms                                                       | 122 ms: 1.19x faster                                                       |
| scimark_sor              | 177 ms                                                       | 150 ms: 1.18x faster                                                       |
| fannkuch                 | 496 ms                                                       | 421 ms: 1.18x faster                                                       |
| create_gc_cycles         | 1.82 ms                                                      | 1.56 ms: 1.17x faster                                                      |
| deepcopy_reduce          | 4.03 us                                                      | 3.46 us: 1.17x faster                                                      |
| json                     | 5.96 ms                                                      | 5.13 ms: 1.16x faster                                                      |
| docutils                 | 3.40 sec                                                     | 2.95 sec: 1.15x faster                                                     |
| dulwich_log              | 80.1 ms                                                      | 69.5 ms: 1.15x faster                                                      |
| mdp                      | 3.03 sec                                                     | 2.64 sec: 1.15x faster                                                     |
| deepcopy                 | 454 us                                                       | 396 us: 1.15x faster                                                       |
| sqlglot_optimize         | 70.3 ms                                                      | 61.4 ms: 1.15x faster                                                      |
| bench_thread_pool        | 1.14 ms                                                      | 1.01 ms: 1.13x faster                                                      |
| pathlib                  | 21.7 ms                                                      | 19.7 ms: 1.10x faster                                                      |
| xml_etree_generate       | 94.6 ms                                                      | 86.3 ms: 1.10x faster                                                      |
| xml_etree_parse          | 162 ms                                                       | 148 ms: 1.09x faster                                                       |
| sqlite_synth             | 2.97 us                                                      | 2.73 us: 1.09x faster                                                      |
| nqueens                  | 112 ms                                                       | 104 ms: 1.09x faster                                                       |
| scimark_fft              | 359 ms                                                       | 334 ms: 1.08x faster                                                       |
| comprehensions           | 26.9 us                                                      | 25.2 us: 1.07x faster                                                      |
| unpack_sequence          | 59.5 ns                                                      | 56.2 ns: 1.06x faster                                                      |
| regex_dna                | 259 ms                                                       | 248 ms: 1.04x faster                                                       |
| regex_v8                 | 26.6 ms                                                      | 25.8 ms: 1.03x faster                                                      |
| async_generators         | 422 ms                                                       | 409 ms: 1.03x faster                                                       |
| xml_etree_iterparse      | 110 ms                                                       | 108 ms: 1.02x faster                                                       |
| pidigits                 | 271 ms                                                       | 264 ms: 1.02x faster                                                       |
| scimark_sparse_mat_mult  | 5.19 ms                                                      | 5.12 ms: 1.01x faster                                                      |
| gc_traversal             | 3.45 ms                                                      | 3.48 ms: 1.01x slower                                                      |
| pickle                   | 9.94 us                                                      | 10.1 us: 1.01x slower                                                      |
| unpickle                 | 14.2 us                                                      | 14.4 us: 1.01x slower                                                      |
| meteor_contest           | 137 ms                                                       | 139 ms: 1.02x slower                                                       |
| unpickle_list            | 4.49 us                                                      | 4.68 us: 1.04x slower                                                      |
| pickle_dict              | 30.0 us                                                      | 31.9 us: 1.06x slower                                                      |
| python_startup           | 11.5 ms                                                      | 12.3 ms: 1.07x slower                                                      |
| pickle_list              | 4.11 us                                                      | 4.51 us: 1.10x slower                                                      |
| telco                    | 7.14 ms                                                      | 8.07 ms: 1.13x slower                                                      |
| regex_effbot             | 2.99 ms                                                      | 3.56 ms: 1.19x slower                                                      |
| python_startup_no_site   | 7.32 ms                                                      | 9.26 ms: 1.27x slower                                                      |
| dask                     | 463 ms                                                       | 596 ms: 1.29x slower                                                       |
| coverage                 | 64.0 ms                                                      | 82.5 ms: 1.29x slower                                                      |
| Geometric mean           | (ref)                                                        | 1.24x faster                                                               |
Ignored benchmarks (17) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.18x
- 99% likely to have a speedup of 1.16x
