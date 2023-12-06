
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 0441b8d
- commit date: 2023-09-15
- overall geometric mean: 1.25x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.16x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.70 sec: 1.17x faster                                                  |
| tornado_http   | 127 ms                                                 | 97.9 ms: 1.30x faster                                                   |
| Geometric mean | (ref)                                                  | 1.24x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| float          | 111 ms                                                 | 83.6 ms: 1.32x faster                                                   |
| nbody          | 142 ms                                                 | 122 ms: 1.16x faster                                                    |
| pidigits       | 190 ms                                                 | 189 ms: 1.00x faster                                                    |
| Geometric mean | (ref)                                                  | 1.15x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 148 ms: 1.20x faster                                                    |
| regex_dna      | 222 ms                                                 | 213 ms: 1.04x faster                                                    |
| regex_v8       | 25.0 ms                                                | 24.1 ms: 1.04x faster                                                   |
| regex_effbot   | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                   |
| Geometric mean | (ref)                                                  | 1.04x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 301 us: 1.52x faster                                                    |
| json_dumps           | 13.5 ms                                                | 9.83 ms: 1.38x faster                                                   |
| tomli_loads          | 2.92 sec                                               | 2.16 sec: 1.35x faster                                                  |
| xml_etree_process    | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                   |
| unpickle_pure_python | 300 us                                                 | 236 us: 1.27x faster                                                    |
| json_loads           | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 84.8 ms: 1.11x faster                                                   |
| xml_etree_iterparse  | 111 ms                                                 | 104 ms: 1.08x faster                                                    |
| xml_etree_parse      | 163 ms                                                 | 154 ms: 1.06x faster                                                    |
| pickle_list          | 4.56 us                                                | 4.59 us: 1.01x slower                                                   |
| pickle               | 10.3 us                                                | 10.5 us: 1.02x slower                                                   |
| unpickle             | 14.1 us                                                | 14.7 us: 1.04x slower                                                   |
| unpickle_list        | 4.82 us                                                | 5.01 us: 1.04x slower                                                   |
| pickle_dict          | 27.3 us                                                | 31.9 us: 1.17x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.12x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.1 ms: 1.39x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.92 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.08x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230915-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-0441b8d |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 156 us: 3.28x faster                                                    |
| generators               | 76.8 ms                                                | 28.2 ms: 2.73x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.46 ms: 2.14x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 488 ms: 1.90x faster                                                    |
| logging_silent           | 175 ns                                                 | 102 ns: 1.71x faster                                                    |
| raytrace                 | 464 ms                                                 | 276 ms: 1.68x faster                                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                  |
| richards_super           | 90.7 ms                                                | 54.8 ms: 1.65x faster                                                   |
| scimark_monte_carlo      | 108 ms                                                 | 67.6 ms: 1.60x faster                                                   |
| crypto_pyaes             | 118 ms                                                 | 74.3 ms: 1.59x faster                                                   |
| scimark_sor              | 197 ms                                                 | 123 ms: 1.59x faster                                                    |
| async_tree_none          | 717 ms                                                 | 451 ms: 1.59x faster                                                    |
| sqlglot_parse            | 2.06 ms                                                | 1.30 ms: 1.58x faster                                                   |
| richards                 | 74.9 ms                                                | 48.4 ms: 1.55x faster                                                   |
| go                       | 229 ms                                                 | 149 ms: 1.54x faster                                                    |
| pickle_pure_python       | 455 us                                                 | 301 us: 1.52x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.62 ms: 1.51x faster                                                   |
| async_tree_memoization   | 854 ms                                                 | 578 ms: 1.48x faster                                                    |
| chaos                    | 106 ms                                                 | 72.0 ms: 1.48x faster                                                   |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.46x faster                                                  |
| coroutines               | 31.8 ms                                                | 22.0 ms: 1.45x faster                                                   |
| scimark_lu               | 163 ms                                                 | 114 ms: 1.43x faster                                                    |
| pyflate                  | 673 ms                                                 | 475 ms: 1.42x faster                                                    |
| python_startup           | 14.2 ms                                                | 10.1 ms: 1.39x faster                                                   |
| json_dumps               | 13.5 ms                                                | 9.83 ms: 1.38x faster                                                   |
| spectral_norm            | 150 ms                                                 | 111 ms: 1.35x faster                                                    |
| tomli_loads              | 2.92 sec                                               | 2.16 sec: 1.35x faster                                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 716 ms: 1.33x faster                                                    |
| logging_simple           | 8.07 us                                                | 6.09 us: 1.32x faster                                                   |
| float                    | 111 ms                                                 | 83.6 ms: 1.32x faster                                                   |
| logging_format           | 8.91 us                                                | 6.75 us: 1.32x faster                                                   |
| deepcopy_memo            | 52.3 us                                                | 39.9 us: 1.31x faster                                                   |
| pprint_pformat           | 1.99 sec                                               | 1.51 sec: 1.31x faster                                                  |
| unpack_sequence          | 64.7 ns                                                | 49.6 ns: 1.31x faster                                                   |
| pprint_safe_repr         | 955 ms                                                 | 734 ms: 1.30x faster                                                    |
| tornado_http             | 127 ms                                                 | 97.9 ms: 1.30x faster                                                   |
| hexiom                   | 9.53 ms                                                | 7.34 ms: 1.30x faster                                                   |
| xml_etree_process        | 74.9 ms                                                | 57.9 ms: 1.29x faster                                                   |
| unpickle_pure_python     | 300 us                                                 | 236 us: 1.27x faster                                                    |
| pycparser                | 1.50 sec                                               | 1.18 sec: 1.27x faster                                                  |
| mako                     | 14.8 ms                                                | 11.7 ms: 1.26x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 107 ms: 1.26x faster                                                    |
| deepcopy                 | 442 us                                                 | 355 us: 1.24x faster                                                    |
| sqlglot_optimize         | 65.3 ms                                                | 53.9 ms: 1.21x faster                                                   |
| mypy2                    | 428 ms                                                 | 355 ms: 1.21x faster                                                    |
| deepcopy_reduce          | 3.82 us                                                | 3.18 us: 1.20x faster                                                   |
| regex_compile            | 177 ms                                                 | 148 ms: 1.20x faster                                                    |
| docutils                 | 3.17 sec                                               | 2.70 sec: 1.17x faster                                                  |
| nbody                    | 142 ms                                                 | 122 ms: 1.16x faster                                                    |
| fannkuch                 | 486 ms                                                 | 427 ms: 1.14x faster                                                    |
| bench_thread_pool        | 947 us                                                 | 833 us: 1.14x faster                                                    |
| json_loads               | 28.8 us                                                | 25.4 us: 1.14x faster                                                   |
| scimark_fft              | 424 ms                                                 | 381 ms: 1.11x faster                                                    |
| xml_etree_generate       | 94.2 ms                                                | 84.8 ms: 1.11x faster                                                   |
| json                     | 5.42 ms                                                | 4.92 ms: 1.10x faster                                                   |
| create_gc_cycles         | 1.67 ms                                                | 1.52 ms: 1.10x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 69.5 ms: 1.09x faster                                                   |
| comprehensions           | 26.8 us                                                | 24.9 us: 1.08x faster                                                   |
| xml_etree_iterparse      | 111 ms                                                 | 104 ms: 1.08x faster                                                    |
| pathlib                  | 20.0 ms                                                | 18.7 ms: 1.07x faster                                                   |
| xml_etree_parse          | 163 ms                                                 | 154 ms: 1.06x faster                                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.16 ms: 1.06x faster                                                   |
| sqlite_synth             | 2.93 us                                                | 2.80 us: 1.05x faster                                                   |
| regex_dna                | 222 ms                                                 | 213 ms: 1.04x faster                                                    |
| regex_v8                 | 25.0 ms                                                | 24.1 ms: 1.04x faster                                                   |
| meteor_contest           | 115 ms                                                 | 111 ms: 1.03x faster                                                    |
| nqueens                  | 100 ms                                                 | 98.4 ms: 1.02x faster                                                   |
| mdp                      | 2.82 sec                                               | 2.79 sec: 1.01x faster                                                  |
| pidigits                 | 190 ms                                                 | 189 ms: 1.00x faster                                                    |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                   |
| gc_traversal             | 3.84 ms                                                | 3.86 ms: 1.00x slower                                                   |
| pickle_list              | 4.56 us                                                | 4.59 us: 1.01x slower                                                   |
| pickle                   | 10.3 us                                                | 10.5 us: 1.02x slower                                                   |
| unpickle                 | 14.1 us                                                | 14.7 us: 1.04x slower                                                   |
| unpickle_list            | 4.82 us                                                | 5.01 us: 1.04x slower                                                   |
| async_generators         | 425 ms                                                 | 465 ms: 1.09x slower                                                    |
| regex_effbot             | 3.23 ms                                                | 3.58 ms: 1.11x slower                                                   |
| pickle_dict              | 27.3 us                                                | 31.9 us: 1.17x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.92 ms: 1.19x slower                                                   |
| coverage                 | 72.8 ms                                                | 87.3 ms: 1.20x slower                                                   |
| telco                    | 6.54 ms                                                | 8.15 ms: 1.25x slower                                                   |
| dask                     | 423 ms                                                 | 536 ms: 1.27x slower                                                    |
| Geometric mean           | (ref)                                                  | 1.25x faster                                                            |
Ignored benchmarks (18) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.21x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.16x
