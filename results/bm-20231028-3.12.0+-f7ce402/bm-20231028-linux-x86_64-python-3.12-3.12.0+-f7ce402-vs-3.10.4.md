
# Results vs. 3.10.4

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: f7ce402
- commit date: 2023-10-28
- overall geometric mean: 1.29x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.21x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| 2to3           | 346 ms                                                 | 275 ms: 1.26x faster                                 |
| chameleon      | 9.84 ms                                                | 7.47 ms: 1.32x faster                                |
| docutils       | 3.26 sec                                               | 2.73 sec: 1.20x faster                               |
| tornado_http   | 131 ms                                                 | 100 ms: 1.31x faster                                 |
| Geometric mean | (ref)                                                  | 1.27x faster                                         |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|-------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 474 ms: 1.54x faster                                 |
| async_tree_io           | 1.79 sec                                               | 1.17 sec: 1.53x faster                               |
| async_tree_memoization  | 867 ms                                                 | 579 ms: 1.50x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 726 ms: 1.39x faster                                 |
| Geometric mean          | (ref)                                                  | 1.49x faster                                         |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| nbody          | 148 ms                                                 | 97.8 ms: 1.51x faster                                |
| float          | 116 ms                                                 | 84.6 ms: 1.38x faster                                |
| pidigits       | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| Geometric mean | (ref)                                                  | 1.28x faster                                         |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 147 ms: 1.26x faster                                 |
| regex_v8       | 26.2 ms                                                | 23.2 ms: 1.13x faster                                |
| regex_dna      | 215 ms                                                 | 209 ms: 1.03x faster                                 |
| regex_effbot   | 3.41 ms                                                | 3.58 ms: 1.05x slower                                |
| Geometric mean | (ref)                                                  | 1.09x faster                                         |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|----------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 323 us: 1.49x faster                                 |
| unpickle_pure_python | 327 us                                                 | 229 us: 1.43x faster                                 |
| json_dumps           | 14.3 ms                                                | 10.5 ms: 1.36x faster                                |
| xml_etree_process    | 79.8 ms                                                | 61.0 ms: 1.31x faster                                |
| tomli_loads          | 3.06 sec                                               | 2.35 sec: 1.30x faster                               |
| xml_etree_generate   | 100.0 ms                                               | 88.5 ms: 1.13x faster                                |
| json_loads           | 31.4 us                                                | 28.2 us: 1.11x faster                                |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.09x faster                                 |
| xml_etree_parse      | 171 ms                                                 | 162 ms: 1.06x faster                                 |
| pickle_list          | 5.05 us                                                | 4.94 us: 1.02x faster                                |
| unpickle_list        | 5.10 us                                                | 5.12 us: 1.00x slower                                |
| pickle               | 10.7 us                                                | 11.4 us: 1.07x slower                                |
| unpickle             | 14.9 us                                                | 16.3 us: 1.10x slower                                |
| pickle_dict          | 30.0 us                                                | 33.5 us: 1.12x slower                                |
| Geometric mean       | (ref)                                                  | 1.13x faster                                         |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 9.62 ms: 1.49x faster                                |
| python_startup_no_site | 5.87 ms                                                | 6.97 ms: 1.19x slower                                |
| Geometric mean         | (ref)                                                  | 1.12x faster                                         |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|-----------------|:------------------------------------------------------:|:----------------------------------------------------:|
| mako            | 16.3 ms                                                | 11.4 ms: 1.43x faster                                |
| django_template | 47.6 ms                                                | 34.7 ms: 1.37x faster                                |
| Geometric mean  | (ref)                                                  | 1.40x faster                                         |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402 |
|--------------------------|:------------------------------------------------------:|:----------------------------------------------------:|
| typing_runtime_protocols | 560 us                                                 | 156 us: 3.59x faster                                 |
| generators               | 78.9 ms                                                | 31.1 ms: 2.54x faster                                |
| deltablue                | 7.81 ms                                                | 3.64 ms: 2.14x faster                                |
| richards_super           | 95.6 ms                                                | 51.3 ms: 1.87x faster                                |
| asyncio_tcp              | 918 ms                                                 | 503 ms: 1.83x faster                                 |
| logging_silent           | 189 ns                                                 | 106 ns: 1.78x faster                                 |
| richards                 | 79.4 ms                                                | 45.4 ms: 1.75x faster                                |
| chaos                    | 114 ms                                                 | 66.8 ms: 1.71x faster                                |
| go                       | 238 ms                                                 | 140 ms: 1.70x faster                                 |
| scimark_sor              | 214 ms                                                 | 131 ms: 1.64x faster                                 |
| raytrace                 | 498 ms                                                 | 307 ms: 1.62x faster                                 |
| hexiom                   | 10.3 ms                                                | 6.46 ms: 1.59x faster                                |
| scimark_monte_carlo      | 118 ms                                                 | 74.1 ms: 1.59x faster                                |
| sqlglot_parse            | 2.15 ms                                                | 1.37 ms: 1.57x faster                                |
| pyflate                  | 708 ms                                                 | 453 ms: 1.56x faster                                 |
| crypto_pyaes             | 127 ms                                                 | 81.7 ms: 1.55x faster                                |
| async_tree_none          | 732 ms                                                 | 474 ms: 1.54x faster                                 |
| async_tree_io            | 1.79 sec                                               | 1.17 sec: 1.53x faster                               |
| nbody                    | 148 ms                                                 | 97.8 ms: 1.51x faster                                |
| sqlglot_transpile        | 2.55 ms                                                | 1.70 ms: 1.50x faster                                |
| async_tree_memoization   | 867 ms                                                 | 579 ms: 1.50x faster                                 |
| pickle_pure_python       | 482 us                                                 | 323 us: 1.49x faster                                 |
| python_startup           | 14.3 ms                                                | 9.62 ms: 1.49x faster                                |
| deepcopy_memo            | 58.8 us                                                | 40.2 us: 1.46x faster                                |
| coroutines               | 34.5 ms                                                | 23.6 ms: 1.46x faster                                |
| asyncio_tcp_ssl          | 2.58 sec                                               | 1.79 sec: 1.44x faster                               |
| scimark_lu               | 175 ms                                                 | 122 ms: 1.43x faster                                 |
| unpickle_pure_python     | 327 us                                                 | 229 us: 1.43x faster                                 |
| mako                     | 16.3 ms                                                | 11.4 ms: 1.43x faster                                |
| spectral_norm            | 163 ms                                                 | 117 ms: 1.39x faster                                 |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 726 ms: 1.39x faster                                 |
| float                    | 116 ms                                                 | 84.6 ms: 1.38x faster                                |
| django_template          | 47.6 ms                                                | 34.7 ms: 1.37x faster                                |
| json_dumps               | 14.3 ms                                                | 10.5 ms: 1.36x faster                                |
| unpack_sequence          | 65.7 ns                                                | 48.5 ns: 1.35x faster                                |
| pprint_pformat           | 2.10 sec                                               | 1.56 sec: 1.35x faster                               |
| pycparser                | 1.57 sec                                               | 1.18 sec: 1.32x faster                               |
| pprint_safe_repr         | 1.01 sec                                               | 769 ms: 1.32x faster                                 |
| comprehensions           | 28.5 us                                                | 21.6 us: 1.32x faster                                |
| chameleon                | 9.84 ms                                                | 7.47 ms: 1.32x faster                                |
| xml_etree_process        | 79.8 ms                                                | 61.0 ms: 1.31x faster                                |
| tornado_http             | 131 ms                                                 | 100 ms: 1.31x faster                                 |
| deepcopy                 | 481 us                                                 | 370 us: 1.30x faster                                 |
| tomli_loads              | 3.06 sec                                               | 2.35 sec: 1.30x faster                               |
| fannkuch                 | 527 ms                                                 | 409 ms: 1.29x faster                                 |
| sqlglot_normalize        | 141 ms                                                 | 110 ms: 1.28x faster                                 |
| deepcopy_reduce          | 4.17 us                                                | 3.26 us: 1.28x faster                                |
| logging_simple           | 8.27 us                                                | 6.49 us: 1.28x faster                                |
| nqueens                  | 107 ms                                                 | 83.8 ms: 1.27x faster                                |
| regex_compile            | 186 ms                                                 | 147 ms: 1.26x faster                                 |
| logging_format           | 9.07 us                                                | 7.21 us: 1.26x faster                                |
| 2to3                     | 346 ms                                                 | 275 ms: 1.26x faster                                 |
| sqlglot_optimize         | 68.7 ms                                                | 54.7 ms: 1.26x faster                                |
| aiohttp                  | 1.41 ms                                                | 1.15 ms: 1.23x faster                                |
| docutils                 | 3.26 sec                                               | 2.73 sec: 1.20x faster                               |
| sympy_integrate          | 25.4 ms                                                | 21.2 ms: 1.20x faster                                |
| gunicorn                 | 1.48 ms                                                | 1.24 ms: 1.19x faster                                |
| scimark_fft              | 454 ms                                                 | 384 ms: 1.18x faster                                 |
| dask                     | 432 ms                                                 | 368 ms: 1.17x faster                                 |
| sqlalchemy_imperative    | 21.9 ms                                                | 18.8 ms: 1.16x faster                                |
| sympy_expand             | 558 ms                                                 | 481 ms: 1.16x faster                                 |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 5.27 ms: 1.16x faster                                |
| sqlalchemy_declarative   | 170 ms                                                 | 147 ms: 1.15x faster                                 |
| bench_thread_pool        | 966 us                                                 | 841 us: 1.15x faster                                 |
| sympy_sum                | 190 ms                                                 | 167 ms: 1.14x faster                                 |
| regex_v8                 | 26.2 ms                                                | 23.2 ms: 1.13x faster                                |
| xml_etree_generate       | 100.0 ms                                               | 88.5 ms: 1.13x faster                                |
| sympy_str                | 337 ms                                                 | 299 ms: 1.13x faster                                 |
| dulwich_log              | 77.0 ms                                                | 68.4 ms: 1.13x faster                                |
| coverage                 | 82.0 ms                                                | 73.3 ms: 1.12x faster                                |
| json_loads               | 31.4 us                                                | 28.2 us: 1.11x faster                                |
| create_gc_cycles         | 1.61 ms                                                | 1.46 ms: 1.10x faster                                |
| meteor_contest           | 119 ms                                                 | 109 ms: 1.09x faster                                 |
| xml_etree_iterparse      | 116 ms                                                 | 106 ms: 1.09x faster                                 |
| json                     | 5.67 ms                                                | 5.25 ms: 1.08x faster                                |
| mdp                      | 2.93 sec                                               | 2.72 sec: 1.08x faster                               |
| pathlib                  | 20.3 ms                                                | 18.8 ms: 1.08x faster                                |
| xml_etree_parse          | 171 ms                                                 | 162 ms: 1.06x faster                                 |
| sqlite_synth             | 3.02 us                                                | 2.86 us: 1.06x faster                                |
| regex_dna                | 215 ms                                                 | 209 ms: 1.03x faster                                 |
| pickle_list              | 5.05 us                                                | 4.94 us: 1.02x faster                                |
| pidigits                 | 190 ms                                                 | 187 ms: 1.02x faster                                 |
| asyncio_websockets       | 558 ms                                                 | 551 ms: 1.01x faster                                 |
| unpickle_list            | 5.10 us                                                | 5.12 us: 1.00x slower                                |
| telco                    | 7.01 ms                                                | 7.19 ms: 1.02x slower                                |
| async_generators         | 442 ms                                                 | 461 ms: 1.04x slower                                 |
| regex_effbot             | 3.41 ms                                                | 3.58 ms: 1.05x slower                                |
| pickle                   | 10.7 us                                                | 11.4 us: 1.07x slower                                |
| unpickle                 | 14.9 us                                                | 16.3 us: 1.10x slower                                |
| pickle_dict              | 30.0 us                                                | 33.5 us: 1.12x slower                                |
| python_startup_no_site   | 5.87 ms                                                | 6.97 ms: 1.19x slower                                |
| gc_traversal             | 3.43 ms                                                | 4.28 ms: 1.25x slower                                |
| Geometric mean           | (ref)                                                  | 1.29x faster                                         |

Benchmark hidden because not significant (2): bench_mp_pool, mypy2
Ignored benchmarks (7) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
Ignored benchmarks (4) of results/bm-20231028-3.12.0+-f7ce402/bm-20231028-linux-x86_64-python-3.12-3.12.0+-f7ce402.json: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.25x
- 95% likely to have a speedup of 1.24x
- 99% likely to have a speedup of 1.21x
