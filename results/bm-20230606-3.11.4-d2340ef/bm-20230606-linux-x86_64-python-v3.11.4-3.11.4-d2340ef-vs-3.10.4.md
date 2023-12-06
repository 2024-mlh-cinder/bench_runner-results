
# Results vs. 3.10.4

- fork: python
- ref: v3.11.4
- machine: linux-x86_64
- commit hash: d2340ef
- commit date: 2023-06-06
- overall geometric mean: 1.30x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.23x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 258 ms: 1.34x faster                                   |
| chameleon      | 9.84 ms                                                | 6.58 ms: 1.50x faster                                  |
| docutils       | 3.26 sec                                               | 2.57 sec: 1.27x faster                                 |
| html5lib       | 88.1 ms                                                | 64.2 ms: 1.37x faster                                  |
| tornado_http   | 131 ms                                                 | 96.6 ms: 1.35x faster                                  |
| Geometric mean | (ref)                                                  | 1.36x faster                                           |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 523 ms: 1.40x faster                                   |
| async_tree_io           | 1.79 sec                                               | 1.29 sec: 1.38x faster                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 738 ms: 1.37x faster                                   |
| async_tree_memoization  | 867 ms                                                 | 638 ms: 1.36x faster                                   |
| Geometric mean          | (ref)                                                  | 1.38x faster                                           |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| float          | 116 ms                                                 | 77.1 ms: 1.51x faster                                  |
| nbody          | 148 ms                                                 | 99.4 ms: 1.49x faster                                  |
| pidigits       | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| Geometric mean | (ref)                                                  | 1.31x faster                                           |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 136 ms: 1.36x faster                                   |
| regex_v8       | 26.2 ms                                                | 22.2 ms: 1.18x faster                                  |
| regex_dna      | 215 ms                                                 | 200 ms: 1.07x faster                                   |
| regex_effbot   | 3.41 ms                                                | 3.45 ms: 1.01x slower                                  |
| Geometric mean | (ref)                                                  | 1.14x faster                                           |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|----------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 302 us: 1.60x faster                                   |
| xml_etree_process    | 79.8 ms                                                | 53.9 ms: 1.48x faster                                  |
| unpickle_pure_python | 327 us                                                 | 229 us: 1.43x faster                                   |
| tomli_loads          | 3.06 sec                                               | 2.19 sec: 1.40x faster                                 |
| xml_etree_generate   | 100.0 ms                                               | 76.5 ms: 1.31x faster                                  |
| pickle_list          | 5.05 us                                                | 4.01 us: 1.26x faster                                  |
| json_loads           | 31.4 us                                                | 26.2 us: 1.20x faster                                  |
| unpickle             | 14.9 us                                                | 13.1 us: 1.14x faster                                  |
| json_dumps           | 14.3 ms                                                | 12.6 ms: 1.13x faster                                  |
| xml_etree_iterparse  | 116 ms                                                 | 104 ms: 1.11x faster                                   |
| pickle               | 10.7 us                                                | 9.76 us: 1.09x faster                                  |
| xml_etree_parse      | 171 ms                                                 | 160 ms: 1.07x faster                                   |
| unpickle_list        | 5.10 us                                                | 5.02 us: 1.01x faster                                  |
| pickle_dict          | 30.0 us                                                | 30.7 us: 1.03x slower                                  |
| Geometric mean       | (ref)                                                  | 1.22x faster                                           |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.53 ms: 1.68x faster                                  |
| python_startup_no_site | 5.87 ms                                                | 6.01 ms: 1.02x slower                                  |
| Geometric mean         | (ref)                                                  | 1.28x faster                                           |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|-----------------|:------------------------------------------------------:|:------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.80 ms: 1.66x faster                                  |
| django_template | 47.6 ms                                                | 33.0 ms: 1.44x faster                                  |
| genshi_text     | 31.7 ms                                                | 22.4 ms: 1.42x faster                                  |
| genshi_xml      | 66.0 ms                                                | 51.8 ms: 1.27x faster                                  |
| Geometric mean  | (ref)                                                  | 1.44x faster                                           |

All benchmarks:
===============

| Benchmark                | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef |
|--------------------------|:------------------------------------------------------:|:------------------------------------------------------:|
| deltablue                | 7.81 ms                                                | 3.71 ms: 2.11x faster                                  |
| logging_silent           | 189 ns                                                 | 103 ns: 1.84x faster                                   |
| scimark_sor              | 214 ms                                                 | 118 ms: 1.82x faster                                   |
| scimark_monte_carlo      | 118 ms                                                 | 67.7 ms: 1.74x faster                                  |
| crypto_pyaes             | 127 ms                                                 | 74.6 ms: 1.70x faster                                  |
| go                       | 238 ms                                                 | 140 ms: 1.70x faster                                   |
| raytrace                 | 498 ms                                                 | 294 ms: 1.69x faster                                   |
| pyflate                  | 708 ms                                                 | 421 ms: 1.68x faster                                   |
| spectral_norm            | 163 ms                                                 | 97.1 ms: 1.68x faster                                  |
| python_startup           | 14.3 ms                                                | 8.53 ms: 1.68x faster                                  |
| mako                     | 16.3 ms                                                | 9.80 ms: 1.66x faster                                  |
| richards                 | 79.4 ms                                                | 48.5 ms: 1.64x faster                                  |
| chaos                    | 114 ms                                                 | 70.2 ms: 1.63x faster                                  |
| deepcopy_memo            | 58.8 us                                                | 36.5 us: 1.61x faster                                  |
| scimark_lu               | 175 ms                                                 | 109 ms: 1.61x faster                                   |
| pickle_pure_python       | 482 us                                                 | 302 us: 1.60x faster                                   |
| richards_super           | 95.6 ms                                                | 60.0 ms: 1.59x faster                                  |
| hexiom                   | 10.3 ms                                                | 6.50 ms: 1.59x faster                                  |
| sqlglot_parse            | 2.15 ms                                                | 1.37 ms: 1.57x faster                                  |
| sqlglot_transpile        | 2.55 ms                                                | 1.67 ms: 1.53x faster                                  |
| float                    | 116 ms                                                 | 77.1 ms: 1.51x faster                                  |
| unpack_sequence          | 65.7 ns                                                | 43.6 ns: 1.51x faster                                  |
| chameleon                | 9.84 ms                                                | 6.58 ms: 1.50x faster                                  |
| nbody                    | 148 ms                                                 | 99.4 ms: 1.49x faster                                  |
| xml_etree_process        | 79.8 ms                                                | 53.9 ms: 1.48x faster                                  |
| pprint_pformat           | 2.10 sec                                               | 1.45 sec: 1.45x faster                                 |
| django_template          | 47.6 ms                                                | 33.0 ms: 1.44x faster                                  |
| pprint_safe_repr         | 1.01 sec                                               | 707 ms: 1.44x faster                                   |
| unpickle_pure_python     | 327 us                                                 | 229 us: 1.43x faster                                   |
| deepcopy_reduce          | 4.17 us                                                | 2.94 us: 1.42x faster                                  |
| genshi_text              | 31.7 ms                                                | 22.4 ms: 1.42x faster                                  |
| deepcopy                 | 481 us                                                 | 341 us: 1.41x faster                                   |
| async_tree_none          | 732 ms                                                 | 523 ms: 1.40x faster                                   |
| tomli_loads              | 3.06 sec                                               | 2.19 sec: 1.40x faster                                 |
| scimark_fft              | 454 ms                                                 | 326 ms: 1.39x faster                                   |
| async_tree_io            | 1.79 sec                                               | 1.29 sec: 1.38x faster                                 |
| thrift                   | 1.06 ms                                                | 771 us: 1.38x faster                                   |
| logging_format           | 9.07 us                                                | 6.58 us: 1.38x faster                                  |
| html5lib                 | 88.1 ms                                                | 64.2 ms: 1.37x faster                                  |
| async_tree_cpu_io_mixed  | 1.01 sec                                               | 738 ms: 1.37x faster                                   |
| regex_compile            | 186 ms                                                 | 136 ms: 1.36x faster                                   |
| async_tree_memoization   | 867 ms                                                 | 638 ms: 1.36x faster                                   |
| logging_simple           | 8.27 us                                                | 6.09 us: 1.36x faster                                  |
| tornado_http             | 131 ms                                                 | 96.6 ms: 1.35x faster                                  |
| 2to3                     | 346 ms                                                 | 258 ms: 1.34x faster                                   |
| fannkuch                 | 527 ms                                                 | 394 ms: 1.34x faster                                   |
| scimark_sparse_mat_mult  | 6.10 ms                                                | 4.58 ms: 1.33x faster                                  |
| coroutines               | 34.5 ms                                                | 25.9 ms: 1.33x faster                                  |
| pycparser                | 1.57 sec                                               | 1.18 sec: 1.33x faster                                 |
| xml_etree_generate       | 100.0 ms                                               | 76.5 ms: 1.31x faster                                  |
| sqlglot_normalize        | 141 ms                                                 | 108 ms: 1.31x faster                                   |
| sqlglot_optimize         | 68.7 ms                                                | 53.0 ms: 1.30x faster                                  |
| aiohttp                  | 1.41 ms                                                | 1.09 ms: 1.29x faster                                  |
| nqueens                  | 107 ms                                                 | 83.1 ms: 1.28x faster                                  |
| genshi_xml               | 66.0 ms                                                | 51.8 ms: 1.27x faster                                  |
| docutils                 | 3.26 sec                                               | 2.57 sec: 1.27x faster                                 |
| comprehensions           | 28.5 us                                                | 22.6 us: 1.26x faster                                  |
| gunicorn                 | 1.48 ms                                                | 1.17 ms: 1.26x faster                                  |
| pickle_list              | 5.05 us                                                | 4.01 us: 1.26x faster                                  |
| sqlalchemy_imperative    | 21.9 ms                                                | 17.9 ms: 1.22x faster                                  |
| sqlalchemy_declarative   | 170 ms                                                 | 139 ms: 1.22x faster                                   |
| async_generators         | 442 ms                                                 | 361 ms: 1.22x faster                                   |
| sympy_integrate          | 25.4 ms                                                | 20.9 ms: 1.22x faster                                  |
| sqlite_synth             | 3.02 us                                                | 2.51 us: 1.21x faster                                  |
| dask                     | 432 ms                                                 | 360 ms: 1.20x faster                                   |
| json_loads               | 31.4 us                                                | 26.2 us: 1.20x faster                                  |
| sympy_expand             | 558 ms                                                 | 470 ms: 1.19x faster                                   |
| bench_thread_pool        | 966 us                                                 | 816 us: 1.18x faster                                   |
| regex_v8                 | 26.2 ms                                                | 22.2 ms: 1.18x faster                                  |
| dulwich_log              | 77.0 ms                                                | 65.5 ms: 1.18x faster                                  |
| flaskblogging            | 8.42 ms                                                | 7.17 ms: 1.17x faster                                  |
| json                     | 5.67 ms                                                | 4.85 ms: 1.17x faster                                  |
| sympy_str                | 337 ms                                                 | 290 ms: 1.16x faster                                   |
| pylint                   | 534 ms                                                 | 462 ms: 1.16x faster                                   |
| sympy_sum                | 190 ms                                                 | 166 ms: 1.15x faster                                   |
| unpickle                 | 14.9 us                                                | 13.1 us: 1.14x faster                                  |
| json_dumps               | 14.3 ms                                                | 12.6 ms: 1.13x faster                                  |
| typing_runtime_protocols | 560 us                                                 | 495 us: 1.13x faster                                   |
| pathlib                  | 20.3 ms                                                | 18.0 ms: 1.13x faster                                  |
| djangocms                | 37.2 us                                                | 33.0 us: 1.13x faster                                  |
| mdp                      | 2.93 sec                                               | 2.60 sec: 1.13x faster                                 |
| meteor_contest           | 119 ms                                                 | 106 ms: 1.13x faster                                   |
| xml_etree_iterparse      | 116 ms                                                 | 104 ms: 1.11x faster                                   |
| pickle                   | 10.7 us                                                | 9.76 us: 1.09x faster                                  |
| create_gc_cycles         | 1.61 ms                                                | 1.49 ms: 1.08x faster                                  |
| regex_dna                | 215 ms                                                 | 200 ms: 1.07x faster                                   |
| generators               | 78.9 ms                                                | 73.7 ms: 1.07x faster                                  |
| xml_etree_parse          | 171 ms                                                 | 160 ms: 1.07x faster                                   |
| telco                    | 7.01 ms                                                | 6.62 ms: 1.06x faster                                  |
| unpickle_list            | 5.10 us                                                | 5.02 us: 1.01x faster                                  |
| pidigits                 | 190 ms                                                 | 190 ms: 1.00x faster                                   |
| asyncio_tcp              | 918 ms                                                 | 922 ms: 1.00x slower                                   |
| regex_effbot             | 3.41 ms                                                | 3.45 ms: 1.01x slower                                  |
| python_startup_no_site   | 5.87 ms                                                | 6.01 ms: 1.02x slower                                  |
| pickle_dict              | 30.0 us                                                | 30.7 us: 1.03x slower                                  |
| gc_traversal             | 3.43 ms                                                | 4.04 ms: 1.18x slower                                  |
| mypy2                    | 442 ms                                                 | 534 ms: 1.21x slower                                   |
| asyncio_tcp_ssl          | 2.58 sec                                               | 3.15 sec: 1.22x slower                                 |
| Geometric mean           | (ref)                                                  | 1.30x faster                                           |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (2) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: asyncio_websockets, coverage


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.28x
- 95% likely to have a speedup of 1.27x
- 99% likely to have a speedup of 1.23x
