
# Results vs. 3.10.4

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: linux-x86_64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.22x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.17x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 346 ms                                                 | 274 ms: 1.26x faster                                                  |
| chameleon      | 9.84 ms                                                | 7.46 ms: 1.32x faster                                                 |
| docutils       | 3.26 sec                                               | 2.79 sec: 1.17x faster                                                |
| html5lib       | 88.1 ms                                                | 71.5 ms: 1.23x faster                                                 |
| tornado_http   | 131 ms                                                 | 111 ms: 1.18x faster                                                  |
| Geometric mean | (ref)                                                  | 1.23x faster                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 732 ms                                                 | 518 ms: 1.41x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 676 ms: 1.28x faster                                                  |
| async_tree_io           | 1.79 sec                                               | 1.41 sec: 1.27x faster                                                |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 818 ms: 1.23x faster                                                  |
| Geometric mean          | (ref)                                                  | 1.30x faster                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| float          | 116 ms                                                 | 83.3 ms: 1.40x faster                                                 |
| nbody          | 148 ms                                                 | 112 ms: 1.32x faster                                                  |
| pidigits       | 190 ms                                                 | 188 ms: 1.02x faster                                                  |
| Geometric mean | (ref)                                                  | 1.23x faster                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_compile  | 186 ms                                                 | 145 ms: 1.28x faster                                                  |
| regex_v8       | 26.2 ms                                                | 23.7 ms: 1.11x faster                                                 |
| regex_effbot   | 3.41 ms                                                | 3.26 ms: 1.05x faster                                                 |
| regex_dna      | 215 ms                                                 | 219 ms: 1.02x slower                                                  |
| Geometric mean | (ref)                                                  | 1.10x faster                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| xml_etree_process    | 79.8 ms                                                | 59.6 ms: 1.34x faster                                                 |
| pickle_pure_python   | 482 us                                                 | 364 us: 1.32x faster                                                  |
| xml_etree_generate   | 100.0 ms                                               | 81.6 ms: 1.23x faster                                                 |
| json_loads           | 31.4 us                                                | 25.9 us: 1.21x faster                                                 |
| unpickle_pure_python | 327 us                                                 | 271 us: 1.20x faster                                                  |
| json_dumps           | 14.3 ms                                                | 12.4 ms: 1.15x faster                                                 |
| xml_etree_parse      | 171 ms                                                 | 158 ms: 1.08x faster                                                  |
| unpickle             | 14.9 us                                                | 13.7 us: 1.08x faster                                                 |
| pickle_list          | 5.05 us                                                | 4.68 us: 1.08x faster                                                 |
| pickle               | 10.7 us                                                | 10.1 us: 1.06x faster                                                 |
| xml_etree_iterparse  | 116 ms                                                 | 110 ms: 1.05x faster                                                  |
| pickle_dict          | 30.0 us                                                | 28.6 us: 1.05x faster                                                 |
| unpickle_list        | 5.10 us                                                | 5.13 us: 1.01x slower                                                 |
| Geometric mean       | (ref)                                                  | 1.14x faster                                                          |

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 5.87 ms                                                | 5.77 ms: 1.02x faster                                                 |
| python_startup         | 14.3 ms                                                | 14.6 ms: 1.02x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.00x faster                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| mako            | 16.3 ms                                                | 12.1 ms: 1.35x faster                                                 |
| genshi_text     | 31.7 ms                                                | 24.6 ms: 1.29x faster                                                 |
| django_template | 47.6 ms                                                | 37.9 ms: 1.25x faster                                                 |
| genshi_xml      | 66.0 ms                                                | 56.1 ms: 1.18x faster                                                 |
| Geometric mean  | (ref)                                                  | 1.26x faster                                                          |

All benchmarks:
===============

| Benchmark               | bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| logging_silent          | 189 ns                                                 | 117 ns: 1.62x faster                                                  |
| deltablue               | 7.81 ms                                                | 4.86 ms: 1.61x faster                                                 |
| spectral_norm           | 163 ms                                                 | 106 ms: 1.54x faster                                                  |
| raytrace                | 498 ms                                                 | 326 ms: 1.53x faster                                                  |
| unpack_sequence         | 65.7 ns                                                | 43.6 ns: 1.51x faster                                                 |
| scimark_monte_carlo     | 118 ms                                                 | 78.4 ms: 1.50x faster                                                 |
| chaos                   | 114 ms                                                 | 77.1 ms: 1.48x faster                                                 |
| deepcopy_memo           | 58.8 us                                                | 40.4 us: 1.45x faster                                                 |
| richards                | 79.4 ms                                                | 55.7 ms: 1.43x faster                                                 |
| go                      | 238 ms                                                 | 167 ms: 1.42x faster                                                  |
| async_tree_none         | 732 ms                                                 | 518 ms: 1.41x faster                                                  |
| crypto_pyaes            | 127 ms                                                 | 90.2 ms: 1.40x faster                                                 |
| float                   | 116 ms                                                 | 83.3 ms: 1.40x faster                                                 |
| hexiom                  | 10.3 ms                                                | 7.42 ms: 1.39x faster                                                 |
| scimark_sor             | 214 ms                                                 | 156 ms: 1.37x faster                                                  |
| generators              | 78.9 ms                                                | 57.4 ms: 1.37x faster                                                 |
| logging_simple          | 8.27 us                                                | 6.07 us: 1.36x faster                                                 |
| logging_format          | 9.07 us                                                | 6.71 us: 1.35x faster                                                 |
| mako                    | 16.3 ms                                                | 12.1 ms: 1.35x faster                                                 |
| xml_etree_process       | 79.8 ms                                                | 59.6 ms: 1.34x faster                                                 |
| pprint_safe_repr        | 1.01 sec                                               | 763 ms: 1.33x faster                                                  |
| pprint_pformat          | 2.10 sec                                               | 1.58 sec: 1.33x faster                                                |
| pickle_pure_python      | 482 us                                                 | 364 us: 1.32x faster                                                  |
| nbody                   | 148 ms                                                 | 112 ms: 1.32x faster                                                  |
| chameleon               | 9.84 ms                                                | 7.46 ms: 1.32x faster                                                 |
| pyflate                 | 708 ms                                                 | 541 ms: 1.31x faster                                                  |
| thrift                  | 1.06 ms                                                | 821 us: 1.30x faster                                                  |
| genshi_text             | 31.7 ms                                                | 24.6 ms: 1.29x faster                                                 |
| scimark_lu              | 175 ms                                                 | 136 ms: 1.29x faster                                                  |
| async_tree_memoization  | 867 ms                                                 | 676 ms: 1.28x faster                                                  |
| regex_compile           | 186 ms                                                 | 145 ms: 1.28x faster                                                  |
| gunicorn                | 1.48 ms                                                | 1.15 ms: 1.28x faster                                                 |
| scimark_fft             | 454 ms                                                 | 355 ms: 1.28x faster                                                  |
| deepcopy_reduce         | 4.17 us                                                | 3.27 us: 1.27x faster                                                 |
| async_tree_io           | 1.79 sec                                               | 1.41 sec: 1.27x faster                                                |
| 2to3                    | 346 ms                                                 | 274 ms: 1.26x faster                                                  |
| deepcopy                | 481 us                                                 | 382 us: 1.26x faster                                                  |
| django_template         | 47.6 ms                                                | 37.9 ms: 1.25x faster                                                 |
| scimark_sparse_mat_mult | 6.10 ms                                                | 4.86 ms: 1.25x faster                                                 |
| pycparser               | 1.57 sec                                               | 1.26 sec: 1.25x faster                                                |
| fannkuch                | 527 ms                                                 | 427 ms: 1.23x faster                                                  |
| async_tree_cpu_io_mixed | 1.01 sec                                               | 818 ms: 1.23x faster                                                  |
| html5lib                | 88.1 ms                                                | 71.5 ms: 1.23x faster                                                 |
| xml_etree_generate      | 100.0 ms                                               | 81.6 ms: 1.23x faster                                                 |
| async_generators        | 442 ms                                                 | 361 ms: 1.22x faster                                                  |
| json_loads              | 31.4 us                                                | 25.9 us: 1.21x faster                                                 |
| unpickle_pure_python    | 327 us                                                 | 271 us: 1.20x faster                                                  |
| coroutines              | 34.5 ms                                                | 28.8 ms: 1.20x faster                                                 |
| sqlglot_normalize       | 141 ms                                                 | 119 ms: 1.18x faster                                                  |
| tornado_http            | 131 ms                                                 | 111 ms: 1.18x faster                                                  |
| genshi_xml              | 66.0 ms                                                | 56.1 ms: 1.18x faster                                                 |
| sqlglot_optimize        | 68.7 ms                                                | 58.4 ms: 1.18x faster                                                 |
| docutils                | 3.26 sec                                               | 2.79 sec: 1.17x faster                                                |
| sqlalchemy_declarative  | 170 ms                                                 | 145 ms: 1.17x faster                                                  |
| nqueens                 | 107 ms                                                 | 91.4 ms: 1.17x faster                                                 |
| sqlalchemy_imperative   | 21.9 ms                                                | 18.8 ms: 1.17x faster                                                 |
| json_dumps              | 14.3 ms                                                | 12.4 ms: 1.15x faster                                                 |
| json                    | 5.67 ms                                                | 4.91 ms: 1.15x faster                                                 |
| sympy_integrate         | 25.4 ms                                                | 22.2 ms: 1.14x faster                                                 |
| pylint                  | 534 ms                                                 | 469 ms: 1.14x faster                                                  |
| flaskblogging           | 8.42 ms                                                | 7.46 ms: 1.13x faster                                                 |
| dulwich_log             | 77.0 ms                                                | 68.3 ms: 1.13x faster                                                 |
| meteor_contest          | 119 ms                                                 | 106 ms: 1.12x faster                                                  |
| sympy_sum               | 190 ms                                                 | 170 ms: 1.12x faster                                                  |
| regex_v8                | 26.2 ms                                                | 23.7 ms: 1.11x faster                                                 |
| sympy_expand            | 558 ms                                                 | 505 ms: 1.11x faster                                                  |
| sympy_str               | 337 ms                                                 | 306 ms: 1.10x faster                                                  |
| sqlite_synth            | 3.02 us                                                | 2.76 us: 1.10x faster                                                 |
| xml_etree_parse         | 171 ms                                                 | 158 ms: 1.08x faster                                                  |
| unpickle                | 14.9 us                                                | 13.7 us: 1.08x faster                                                 |
| bench_thread_pool       | 966 us                                                 | 892 us: 1.08x faster                                                  |
| mdp                     | 2.93 sec                                               | 2.71 sec: 1.08x faster                                                |
| coverage                | 82.0 ms                                                | 75.8 ms: 1.08x faster                                                 |
| telco                   | 7.01 ms                                                | 6.50 ms: 1.08x faster                                                 |
| pickle_list             | 5.05 us                                                | 4.68 us: 1.08x faster                                                 |
| sqlglot_transpile       | 2.55 ms                                                | 2.37 ms: 1.08x faster                                                 |
| pathlib                 | 20.3 ms                                                | 19.1 ms: 1.06x faster                                                 |
| pickle                  | 10.7 us                                                | 10.1 us: 1.06x faster                                                 |
| xml_etree_iterparse     | 116 ms                                                 | 110 ms: 1.05x faster                                                  |
| pickle_dict             | 30.0 us                                                | 28.6 us: 1.05x faster                                                 |
| regex_effbot            | 3.41 ms                                                | 3.26 ms: 1.05x faster                                                 |
| sqlglot_parse           | 2.15 ms                                                | 2.06 ms: 1.04x faster                                                 |
| python_startup_no_site  | 5.87 ms                                                | 5.77 ms: 1.02x faster                                                 |
| pidigits                | 190 ms                                                 | 188 ms: 1.02x faster                                                  |
| unpickle_list           | 5.10 us                                                | 5.13 us: 1.01x slower                                                 |
| python_startup          | 14.3 ms                                                | 14.6 ms: 1.02x slower                                                 |
| regex_dna               | 215 ms                                                 | 219 ms: 1.02x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.22x faster                                                          |

Benchmark hidden because not significant (1): bench_mp_pool
Ignored benchmarks (13) of results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json: aiohttp, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, comprehensions, create_gc_cycles, dask, djangocms, gc_traversal, mypy2, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.20x
- 95% likely to have a speedup of 1.19x
- 99% likely to have a speedup of 1.17x
