
# Results vs. 3.10.4

- fork: brandtbucher
- ref: justin_registers
- machine: linux-x86_64
- commit hash: 15560d4
- commit date: 2023-10-21
- overall geometric mean: 1.23x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.15x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| docutils       | 3.17 sec                                               | 2.74 sec: 1.16x faster                                                  |
| tornado_http   | 127 ms                                                 | 99.7 ms: 1.28x faster                                                   |
| Geometric mean | (ref)                                                  | 1.22x faster                                                            |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| nbody          | 142 ms                                                 | 100.0 ms: 1.42x faster                                                  |
| float          | 111 ms                                                 | 86.8 ms: 1.27x faster                                                   |
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| Geometric mean | (ref)                                                  | 1.22x faster                                                            |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| regex_compile  | 177 ms                                                 | 151 ms: 1.17x faster                                                    |
| regex_dna      | 222 ms                                                 | 217 ms: 1.02x faster                                                    |
| regex_v8       | 25.0 ms                                                | 25.8 ms: 1.03x slower                                                   |
| regex_effbot   | 3.23 ms                                                | 3.65 ms: 1.13x slower                                                   |
| Geometric mean | (ref)                                                  | 1.01x faster                                                            |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|----------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| pickle_pure_python   | 455 us                                                 | 308 us: 1.48x faster                                                    |
| tomli_loads          | 2.92 sec                                               | 2.14 sec: 1.36x faster                                                  |
| unpickle_pure_python | 300 us                                                 | 234 us: 1.28x faster                                                    |
| json_dumps           | 13.5 ms                                                | 10.6 ms: 1.28x faster                                                   |
| xml_etree_process    | 74.9 ms                                                | 60.2 ms: 1.24x faster                                                   |
| xml_etree_generate   | 94.2 ms                                                | 87.0 ms: 1.08x faster                                                   |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                                    |
| xml_etree_iterparse  | 111 ms                                                 | 109 ms: 1.02x faster                                                    |
| json_loads           | 28.8 us                                                | 28.3 us: 1.02x faster                                                   |
| unpickle_list        | 4.82 us                                                | 5.00 us: 1.04x slower                                                   |
| unpickle             | 14.1 us                                                | 15.4 us: 1.09x slower                                                   |
| pickle_list          | 4.56 us                                                | 5.02 us: 1.10x slower                                                   |
| pickle               | 10.3 us                                                | 11.6 us: 1.12x slower                                                   |
| pickle_dict          | 27.3 us                                                | 34.5 us: 1.26x slower                                                   |
| Geometric mean       | (ref)                                                  | 1.07x faster                                                            |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| python_startup         | 14.2 ms                                                | 10.2 ms: 1.39x faster                                                   |
| python_startup_no_site | 5.82 ms                                                | 6.93 ms: 1.19x slower                                                   |
| Geometric mean         | (ref)                                                  | 1.08x faster                                                            |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|-----------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| mako      | 14.8 ms                                                | 12.1 ms: 1.22x faster                                                   |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231021-linux-x86_64-brandtbucher-justin_registers-3.13.0a0-15560d4 |
|--------------------------|:------------------------------------------------------:|:-----------------------------------------------------------------------:|
| typing_runtime_protocols | 510 us                                                 | 158 us: 3.24x faster                                                    |
| generators               | 76.8 ms                                                | 29.4 ms: 2.62x faster                                                   |
| deltablue                | 7.42 ms                                                | 3.81 ms: 1.95x faster                                                   |
| asyncio_tcp              | 925 ms                                                 | 490 ms: 1.89x faster                                                    |
| asyncio_tcp_ssl          | 3.01 sec                                               | 1.80 sec: 1.67x faster                                                  |
| richards_super           | 90.7 ms                                                | 54.5 ms: 1.66x faster                                                   |
| logging_silent           | 175 ns                                                 | 107 ns: 1.63x faster                                                    |
| async_tree_none          | 717 ms                                                 | 450 ms: 1.59x faster                                                    |
| richards                 | 74.9 ms                                                | 47.9 ms: 1.56x faster                                                   |
| sqlglot_parse            | 2.06 ms                                                | 1.32 ms: 1.56x faster                                                   |
| crypto_pyaes             | 118 ms                                                 | 76.2 ms: 1.55x faster                                                   |
| scimark_sor              | 197 ms                                                 | 127 ms: 1.55x faster                                                    |
| raytrace                 | 464 ms                                                 | 301 ms: 1.54x faster                                                    |
| go                       | 229 ms                                                 | 153 ms: 1.50x faster                                                    |
| sqlglot_transpile        | 2.45 ms                                                | 1.64 ms: 1.49x faster                                                   |
| pickle_pure_python       | 455 us                                                 | 308 us: 1.48x faster                                                    |
| async_tree_memoization   | 854 ms                                                 | 579 ms: 1.48x faster                                                    |
| async_tree_io            | 1.77 sec                                               | 1.21 sec: 1.47x faster                                                  |
| scimark_monte_carlo      | 108 ms                                                 | 74.1 ms: 1.46x faster                                                   |
| chaos                    | 106 ms                                                 | 73.7 ms: 1.44x faster                                                   |
| nbody                    | 142 ms                                                 | 100.0 ms: 1.42x faster                                                  |
| coroutines               | 31.8 ms                                                | 22.5 ms: 1.41x faster                                                   |
| python_startup           | 14.2 ms                                                | 10.2 ms: 1.39x faster                                                   |
| scimark_lu               | 163 ms                                                 | 118 ms: 1.38x faster                                                    |
| tomli_loads              | 2.92 sec                                               | 2.14 sec: 1.36x faster                                                  |
| async_tree_cpu_io_mixed  | 951 ms                                                 | 724 ms: 1.31x faster                                                    |
| logging_simple           | 8.07 us                                                | 6.17 us: 1.31x faster                                                   |
| pyflate                  | 673 ms                                                 | 517 ms: 1.30x faster                                                    |
| logging_format           | 8.91 us                                                | 6.86 us: 1.30x faster                                                   |
| unpickle_pure_python     | 300 us                                                 | 234 us: 1.28x faster                                                    |
| deepcopy_memo            | 52.3 us                                                | 40.8 us: 1.28x faster                                                   |
| tornado_http             | 127 ms                                                 | 99.7 ms: 1.28x faster                                                   |
| json_dumps               | 13.5 ms                                                | 10.6 ms: 1.28x faster                                                   |
| spectral_norm            | 150 ms                                                 | 118 ms: 1.27x faster                                                    |
| float                    | 111 ms                                                 | 86.8 ms: 1.27x faster                                                   |
| sqlglot_normalize        | 135 ms                                                 | 108 ms: 1.25x faster                                                    |
| xml_etree_process        | 74.9 ms                                                | 60.2 ms: 1.24x faster                                                   |
| pycparser                | 1.50 sec                                               | 1.22 sec: 1.23x faster                                                  |
| mako                     | 14.8 ms                                                | 12.1 ms: 1.22x faster                                                   |
| deepcopy                 | 442 us                                                 | 362 us: 1.22x faster                                                    |
| unpack_sequence          | 64.7 ns                                                | 53.6 ns: 1.21x faster                                                   |
| deepcopy_reduce          | 3.82 us                                                | 3.19 us: 1.20x faster                                                   |
| sqlglot_optimize         | 65.3 ms                                                | 54.7 ms: 1.19x faster                                                   |
| mypy2                    | 428 ms                                                 | 361 ms: 1.19x faster                                                    |
| scimark_fft              | 424 ms                                                 | 360 ms: 1.18x faster                                                    |
| regex_compile            | 177 ms                                                 | 151 ms: 1.17x faster                                                    |
| docutils                 | 3.17 sec                                               | 2.74 sec: 1.16x faster                                                  |
| hexiom                   | 9.53 ms                                                | 8.25 ms: 1.15x faster                                                   |
| fannkuch                 | 486 ms                                                 | 423 ms: 1.15x faster                                                    |
| pprint_pformat           | 1.99 sec                                               | 1.73 sec: 1.15x faster                                                  |
| pprint_safe_repr         | 955 ms                                                 | 835 ms: 1.14x faster                                                    |
| create_gc_cycles         | 1.67 ms                                                | 1.46 ms: 1.14x faster                                                   |
| bench_thread_pool        | 947 us                                                 | 843 us: 1.12x faster                                                    |
| scimark_sparse_mat_mult  | 5.45 ms                                                | 5.00 ms: 1.09x faster                                                   |
| dulwich_log              | 75.9 ms                                                | 69.8 ms: 1.09x faster                                                   |
| xml_etree_generate       | 94.2 ms                                                | 87.0 ms: 1.08x faster                                                   |
| nqueens                  | 100 ms                                                 | 92.6 ms: 1.08x faster                                                   |
| pathlib                  | 20.0 ms                                                | 19.0 ms: 1.06x faster                                                   |
| json                     | 5.42 ms                                                | 5.20 ms: 1.04x faster                                                   |
| sqlite_synth             | 2.93 us                                                | 2.83 us: 1.04x faster                                                   |
| comprehensions           | 26.8 us                                                | 25.9 us: 1.04x faster                                                   |
| xml_etree_parse          | 163 ms                                                 | 158 ms: 1.03x faster                                                    |
| meteor_contest           | 115 ms                                                 | 112 ms: 1.03x faster                                                    |
| regex_dna                | 222 ms                                                 | 217 ms: 1.02x faster                                                    |
| xml_etree_iterparse      | 111 ms                                                 | 109 ms: 1.02x faster                                                    |
| json_loads               | 28.8 us                                                | 28.3 us: 1.02x faster                                                   |
| pidigits                 | 190 ms                                                 | 188 ms: 1.01x faster                                                    |
| gc_traversal             | 3.84 ms                                                | 3.82 ms: 1.01x faster                                                   |
| mdp                      | 2.82 sec                                               | 2.81 sec: 1.01x faster                                                  |
| bench_mp_pool            | 24.0 ms                                                | 24.0 ms: 1.00x slower                                                   |
| regex_v8                 | 25.0 ms                                                | 25.8 ms: 1.03x slower                                                   |
| unpickle_list            | 4.82 us                                                | 5.00 us: 1.04x slower                                                   |
| unpickle                 | 14.1 us                                                | 15.4 us: 1.09x slower                                                   |
| pickle_list              | 4.56 us                                                | 5.02 us: 1.10x slower                                                   |
| async_generators         | 425 ms                                                 | 476 ms: 1.12x slower                                                    |
| pickle                   | 10.3 us                                                | 11.6 us: 1.12x slower                                                   |
| regex_effbot             | 3.23 ms                                                | 3.65 ms: 1.13x slower                                                   |
| python_startup_no_site   | 5.82 ms                                                | 6.93 ms: 1.19x slower                                                   |
| coverage                 | 72.8 ms                                                | 91.2 ms: 1.25x slower                                                   |
| pickle_dict              | 27.3 us                                                | 34.5 us: 1.26x slower                                                   |
| telco                    | 6.54 ms                                                | 8.52 ms: 1.30x slower                                                   |
| Geometric mean           | (ref)                                                  | 1.23x faster                                                            |
Ignored benchmarks (19) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: 2to3, aiohttp, chameleon, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.18x
- 95% likely to have a speedup of 1.17x
- 99% likely to have a speedup of 1.15x
