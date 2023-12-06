
# Results vs. 3.10.4

- fork: python
- ref: 3d5d3f7af6498effbc60
- machine: linux-x86_64
- commit hash: 3d5d3f7
- commit date: 2023-01-10
- overall geometric mean: 1.37x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.31x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 253 ms: 1.37x faster                                                  |
| chameleon      | 9.84 ms                                                | 6.46 ms: 1.52x faster                                                 |
| docutils       | 3.26 sec                                               | 2.48 sec: 1.32x faster                                                |
| html5lib       | 88.1 ms                                                | 59.8 ms: 1.47x faster                                                 |
| Geometric mean | (ref)                                                  | 1.42x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_memoization  | 867 ms                                                 | 616 ms: 1.41x faster                                                  |
| async_tree_none         | 732 ms                                                 | 521 ms: 1.41x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.30 sec: 1.38x faster                                                |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 747 ms: 1.35x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.39x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 116 ms                                                 | 72.2 ms: 1.61x faster                                                 |
| nbody          | 148 ms                                                 | 93.1 ms: 1.59x faster                                                 |
| pidigits       | 190 ms                                                 | 192 ms: 1.01x slower                                                  |
| Geometric mean | (ref)                                                  | 1.36x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 132 ms: 1.41x faster                                                  |
| regex_v8       | 26.2 ms                                                | 21.1 ms: 1.25x faster                                                 |
| regex_dna      | 215 ms                                                 | 209 ms: 1.03x faster                                                  |
| regex_effbot   | 3.41 ms                                                | 3.49 ms: 1.02x slower                                                 |
| Geometric mean | (ref)                                                  | 1.15x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_pure_python   | 482 us                                                 | 285 us: 1.69x faster                                                  |
| unpickle_pure_python | 327 us                                                 | 200 us: 1.63x faster                                                  |
| json_dumps           | 14.3 ms                                                | 9.54 ms: 1.50x faster                                                 |
| xml_etree_process    | 79.8 ms                                                | 53.9 ms: 1.48x faster                                                 |
| json_loads           | 31.4 us                                                | 24.3 us: 1.29x faster                                                 |
| xml_etree_generate   | 100.0 ms                                               | 77.5 ms: 1.29x faster                                                 |
| pickle_list          | 5.05 us                                                | 4.02 us: 1.26x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 149 ms: 1.15x faster                                                  |
| unpickle             | 14.9 us                                                | 13.0 us: 1.15x faster                                                 |
| xml_etree_iterparse  | 116 ms                                                 | 106 ms: 1.09x faster                                                  |
| pickle               | 10.7 us                                                | 10.0 us: 1.07x faster                                                 |
| unpickle_list        | 5.10 us                                                | 4.96 us: 1.03x faster                                                 |
| Geometric mean       | (ref)                                                  | 1.26x faster                                                          |

Benchmark hidden because not significant (1): pickle_dict

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup         | 14.3 ms                                                | 8.54 ms: 1.68x faster                                                 |
| python_startup_no_site | 5.87 ms                                                | 6.09 ms: 1.04x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.27x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 16.3 ms                                                | 9.74 ms: 1.67x faster                                                 |
| genshi_text     | 31.7 ms                                                | 20.8 ms: 1.52x faster                                                 |
| django_template | 47.6 ms                                                | 32.6 ms: 1.46x faster                                                 |
| genshi_xml      | 66.0 ms                                                | 46.5 ms: 1.42x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.52x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20230110-linux-x86_64-python-3d5d3f7af6498effbc60-3.12.0a4-3d5d3f7 |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| deltablue               | 7.81 ms                                                | 3.25 ms: 2.40x faster                                                 |
| logging_silent          | 189 ns                                                 | 93.5 ns: 2.02x faster                                                 |
| scimark_sor             | 214 ms                                                 | 108 ms: 1.98x faster                                                  |
| richards                | 79.4 ms                                                | 42.3 ms: 1.88x faster                                                 |
| asyncio_tcp             | 918 ms                                                 | 504 ms: 1.82x faster                                                  |
| scimark_monte_carlo     | 118 ms                                                 | 65.7 ms: 1.80x faster                                                 |
| pyflate                 | 708 ms                                                 | 397 ms: 1.79x faster                                                  |
| go                      | 238 ms                                                 | 135 ms: 1.76x faster                                                  |
| raytrace                | 498 ms                                                 | 284 ms: 1.75x faster                                                  |
| hexiom                  | 10.3 ms                                                | 5.98 ms: 1.72x faster                                                 |
| spectral_norm           | 163 ms                                                 | 95.0 ms: 1.72x faster                                                 |
| deepcopy_memo           | 58.8 us                                                | 34.7 us: 1.70x faster                                                 |
| pickle_pure_python      | 482 us                                                 | 285 us: 1.69x faster                                                  |
| chaos                   | 114 ms                                                 | 67.7 ms: 1.69x faster                                                 |
| python_startup          | 14.3 ms                                                | 8.54 ms: 1.68x faster                                                 |
| crypto_pyaes            | 127 ms                                                 | 75.7 ms: 1.67x faster                                                 |
| mako                    | 16.3 ms                                                | 9.74 ms: 1.67x faster                                                 |
| unpickle_pure_python    | 327 us                                                 | 200 us: 1.63x faster                                                  |
| scimark_lu              | 175 ms                                                 | 107 ms: 1.63x faster                                                  |
| float                   | 116 ms                                                 | 72.2 ms: 1.61x faster                                                 |
| nbody                   | 148 ms                                                 | 93.1 ms: 1.59x faster                                                 |
| unpack_sequence         | 65.7 ns                                                | 41.4 ns: 1.59x faster                                                 |
| sqlglot_parse           | 2.15 ms                                                | 1.41 ms: 1.53x faster                                                 |
| genshi_text             | 31.7 ms                                                | 20.8 ms: 1.52x faster                                                 |
| chameleon               | 9.84 ms                                                | 6.46 ms: 1.52x faster                                                 |
| pprint_pformat          | 2.10 sec                                               | 1.38 sec: 1.52x faster                                                |
| sqlglot_transpile       | 2.55 ms                                                | 1.69 ms: 1.51x faster                                                 |
| json_dumps              | 14.3 ms                                                | 9.54 ms: 1.50x faster                                                 |
| pprint_safe_repr        | 1.01 sec                                               | 680 ms: 1.49x faster                                                  |
| xml_etree_process       | 79.8 ms                                                | 53.9 ms: 1.48x faster                                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.13 ms: 1.48x faster                                                 |
| html5lib                | 88.1 ms                                                | 59.8 ms: 1.47x faster                                                 |
| django_template         | 47.6 ms                                                | 32.6 ms: 1.46x faster                                                 |
| fannkuch                | 527 ms                                                 | 362 ms: 1.46x faster                                                  |
| pycparser               | 1.57 sec                                               | 1.08 sec: 1.45x faster                                                |
| scimark_fft             | 454 ms                                                 | 314 ms: 1.45x faster                                                  |
| logging_simple          | 8.27 us                                                | 5.77 us: 1.44x faster                                                 |
| logging_format          | 9.07 us                                                | 6.35 us: 1.43x faster                                                 |
| deepcopy                | 481 us                                                 | 339 us: 1.42x faster                                                  |
| genshi_xml              | 66.0 ms                                                | 46.5 ms: 1.42x faster                                                 |
| thrift                  | 1.06 ms                                                | 752 us: 1.41x faster                                                  |
| regex_compile           | 186 ms                                                 | 132 ms: 1.41x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 616 ms: 1.41x faster                                                  |
| async_tree_none         | 732 ms                                                 | 521 ms: 1.41x faster                                                  |
| deepcopy_reduce         | 4.17 us                                                | 2.99 us: 1.39x faster                                                 |
| async_tree_io           | 1.79 sec                                               | 1.30 sec: 1.38x faster                                                |
| 2to3                    | 346 ms                                                 | 253 ms: 1.37x faster                                                  |
| nqueens                 | 107 ms                                                 | 78.0 ms: 1.37x faster                                                 |
| sqlglot_normalize       | 141 ms                                                 | 104 ms: 1.36x faster                                                  |
| coroutines              | 34.5 ms                                                | 25.4 ms: 1.35x faster                                                 |
| sqlglot_optimize        | 68.7 ms                                                | 50.7 ms: 1.35x faster                                                 |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 747 ms: 1.35x faster                                                  |
| mypy2                   | 442 ms                                                 | 332 ms: 1.33x faster                                                  |
| docutils                | 3.26 sec                                               | 2.48 sec: 1.32x faster                                                |
| json_loads              | 31.4 us                                                | 24.3 us: 1.29x faster                                                 |
| xml_etree_generate      | 100.0 ms                                               | 77.5 ms: 1.29x faster                                                 |
| pickle_list             | 5.05 us                                                | 4.02 us: 1.26x faster                                                 |
| sympy_integrate         | 25.4 ms                                                | 20.3 ms: 1.25x faster                                                 |
| async_generators        | 442 ms                                                 | 354 ms: 1.25x faster                                                  |
| regex_v8                | 26.2 ms                                                | 21.1 ms: 1.25x faster                                                 |
| dulwich_log             | 77.0 ms                                                | 62.1 ms: 1.24x faster                                                 |
| bench_thread_pool       | 966 us                                                 | 782 us: 1.24x faster                                                  |
| sympy_expand            | 558 ms                                                 | 455 ms: 1.23x faster                                                  |
| dask                    | 432 ms                                                 | 355 ms: 1.22x faster                                                  |
| djangocms               | 37.2 us                                                | 30.9 us: 1.20x faster                                                 |
| comprehensions          | 28.5 us                                                | 23.7 us: 1.20x faster                                                 |
| json                    | 5.67 ms                                                | 4.74 ms: 1.20x faster                                                 |
| sympy_str               | 337 ms                                                 | 282 ms: 1.19x faster                                                  |
| sqlite_synth            | 3.02 us                                                | 2.57 us: 1.18x faster                                                 |
| sympy_sum               | 190 ms                                                 | 163 ms: 1.17x faster                                                  |
| xml_etree_parse         | 171 ms                                                 | 149 ms: 1.15x faster                                                  |
| unpickle                | 14.9 us                                                | 13.0 us: 1.15x faster                                                 |
| meteor_contest          | 119 ms                                                 | 104 ms: 1.14x faster                                                  |
| pathlib                 | 20.3 ms                                                | 18.0 ms: 1.13x faster                                                 |
| telco                   | 7.01 ms                                                | 6.26 ms: 1.12x faster                                                 |
| create_gc_cycles        | 1.61 ms                                                | 1.45 ms: 1.11x faster                                                 |
| mdp                     | 2.93 sec                                               | 2.66 sec: 1.10x faster                                                |
| xml_etree_iterparse     | 116 ms                                                 | 106 ms: 1.09x faster                                                  |
| pickle                  | 10.7 us                                                | 10.0 us: 1.07x faster                                                 |
| regex_dna               | 215 ms                                                 | 209 ms: 1.03x faster                                                  |
| unpickle_list           | 5.10 us                                                | 4.96 us: 1.03x faster                                                 |
| generators              | 78.9 ms                                                | 79.1 ms: 1.00x slower                                                 |
| pidigits                | 190 ms                                                 | 192 ms: 1.01x slower                                                  |
| regex_effbot            | 3.41 ms                                                | 3.49 ms: 1.02x slower                                                 |
| python_startup_no_site  | 5.87 ms                                                | 6.09 ms: 1.04x slower                                                 |
| gc_traversal            | 3.43 ms                                                | 3.57 ms: 1.04x slower                                                 |
| coverage                | 82.0 ms                                                | 99.0 ms: 1.21x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.37x faster                                                          |

Benchmark hidden because not significant (2): bench_mp_pool, pickle_dict
Ignored benchmarks (12) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp_ssl, asyncio_websockets, flaskblogging, gunicorn, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.35x
- 95% likely to have a speedup of 1.34x
- 99% likely to have a speedup of 1.31x
