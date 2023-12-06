
# Results vs. 3.11.0

- fork: python
- ref: e2b4e4bab90b69fbd361
- machine: linux-x86_64
- commit hash: e2b4e4b
- commit date: 2021-11-05
- overall geometric mean: 1.05x slower \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.02x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| 2to3           | 266 ms                                                 | 274 ms: 1.03x slower                                                  |
| chameleon      | 6.86 ms                                                | 7.46 ms: 1.09x slower                                                 |
| docutils       | 2.69 sec                                               | 2.79 sec: 1.04x slower                                                |
| html5lib       | 65.0 ms                                                | 71.5 ms: 1.10x slower                                                 |
| tornado_http   | 97.7 ms                                                | 111 ms: 1.13x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x slower                                                          |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| async_tree_none         | 532 ms                                                 | 518 ms: 1.03x faster                                                  |
| async_tree_memoization  | 640 ms                                                 | 676 ms: 1.06x slower                                                  |
| async_tree_io           | 1.31 sec                                               | 1.41 sec: 1.08x slower                                                |
| async_tree_cpu_io_mixed | 750 ms                                                 | 818 ms: 1.09x slower                                                  |
| Geometric mean          | (ref)                                                  | 1.05x slower                                                          |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pidigits       | 190 ms                                                 | 188 ms: 1.01x faster                                                  |
| float          | 78.9 ms                                                | 83.3 ms: 1.06x slower                                                 |
| nbody          | 91.6 ms                                                | 112 ms: 1.22x slower                                                  |
| Geometric mean | (ref)                                                  | 1.08x slower                                                          |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| regex_effbot   | 3.45 ms                                                | 3.26 ms: 1.06x faster                                                 |
| regex_compile  | 141 ms                                                 | 145 ms: 1.02x slower                                                  |
| regex_v8       | 22.9 ms                                                | 23.7 ms: 1.04x slower                                                 |
| regex_dna      | 204 ms                                                 | 219 ms: 1.07x slower                                                  |
| Geometric mean | (ref)                                                  | 1.02x slower                                                          |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|----------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| pickle_dict          | 34.8 us                                                | 28.6 us: 1.22x faster                                                 |
| json_loads           | 29.4 us                                                | 25.9 us: 1.14x faster                                                 |
| pickle               | 11.1 us                                                | 10.1 us: 1.10x faster                                                 |
| json_dumps           | 13.5 ms                                                | 12.4 ms: 1.09x faster                                                 |
| xml_etree_parse      | 163 ms                                                 | 158 ms: 1.03x faster                                                  |
| unpickle_list        | 5.22 us                                                | 5.13 us: 1.02x faster                                                 |
| pickle_list          | 4.65 us                                                | 4.68 us: 1.01x slower                                                 |
| xml_etree_generate   | 80.4 ms                                                | 81.6 ms: 1.01x slower                                                 |
| xml_etree_iterparse  | 109 ms                                                 | 110 ms: 1.02x slower                                                  |
| xml_etree_process    | 56.5 ms                                                | 59.6 ms: 1.05x slower                                                 |
| unpickle_pure_python | 241 us                                                 | 271 us: 1.13x slower                                                  |
| pickle_pure_python   | 319 us                                                 | 364 us: 1.14x slower                                                  |
| Geometric mean       | (ref)                                                  | 1.02x faster                                                          |

Benchmark hidden because not significant (1): unpickle

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| python_startup_no_site | 6.09 ms                                                | 5.77 ms: 1.06x faster                                                 |
| python_startup         | 8.69 ms                                                | 14.6 ms: 1.68x slower                                                 |
| Geometric mean         | (ref)                                                  | 1.26x slower                                                          |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-----------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| genshi_xml      | 54.1 ms                                                | 56.1 ms: 1.04x slower                                                 |
| genshi_text     | 22.8 ms                                                | 24.6 ms: 1.08x slower                                                 |
| mako            | 10.8 ms                                                | 12.1 ms: 1.12x slower                                                 |
| django_template | 33.8 ms                                                | 37.9 ms: 1.12x slower                                                 |
| Geometric mean  | (ref)                                                  | 1.09x slower                                                          |

All benchmarks:
===============

| Benchmark               | bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509 | bm-20211105-linux-x86_64-python-e2b4e4bab90b69fbd361-3.11.0a2-e2b4e4b |
|-------------------------|:------------------------------------------------------:|:---------------------------------------------------------------------:|
| generators              | 76.5 ms                                                | 57.4 ms: 1.33x faster                                                 |
| pickle_dict             | 34.8 us                                                | 28.6 us: 1.22x faster                                                 |
| json_loads              | 29.4 us                                                | 25.9 us: 1.14x faster                                                 |
| pickle                  | 11.1 us                                                | 10.1 us: 1.10x faster                                                 |
| json_dumps              | 13.5 ms                                                | 12.4 ms: 1.09x faster                                                 |
| coverage                | 81.2 ms                                                | 75.8 ms: 1.07x faster                                                 |
| json                    | 5.24 ms                                                | 4.91 ms: 1.07x faster                                                 |
| regex_effbot            | 3.45 ms                                                | 3.26 ms: 1.06x faster                                                 |
| python_startup_no_site  | 6.09 ms                                                | 5.77 ms: 1.06x faster                                                 |
| async_generators        | 375 ms                                                 | 361 ms: 1.04x faster                                                  |
| gunicorn                | 1.20 ms                                                | 1.15 ms: 1.04x faster                                                 |
| telco                   | 6.72 ms                                                | 6.50 ms: 1.03x faster                                                 |
| xml_etree_parse         | 163 ms                                                 | 158 ms: 1.03x faster                                                  |
| mdp                     | 2.79 sec                                               | 2.71 sec: 1.03x faster                                                |
| logging_simple          | 6.24 us                                                | 6.07 us: 1.03x faster                                                 |
| async_tree_none         | 532 ms                                                 | 518 ms: 1.03x faster                                                  |
| meteor_contest          | 109 ms                                                 | 106 ms: 1.02x faster                                                  |
| logging_format          | 6.83 us                                                | 6.71 us: 1.02x faster                                                 |
| unpickle_list           | 5.22 us                                                | 5.13 us: 1.02x faster                                                 |
| pidigits                | 190 ms                                                 | 188 ms: 1.01x faster                                                  |
| pickle_list             | 4.65 us                                                | 4.68 us: 1.01x slower                                                 |
| scimark_sparse_mat_mult | 4.80 ms                                                | 4.86 ms: 1.01x slower                                                 |
| xml_etree_generate      | 80.4 ms                                                | 81.6 ms: 1.01x slower                                                 |
| xml_etree_iterparse     | 109 ms                                                 | 110 ms: 1.02x slower                                                  |
| regex_compile           | 141 ms                                                 | 145 ms: 1.02x slower                                                  |
| sympy_str               | 299 ms                                                 | 306 ms: 1.02x slower                                                  |
| pprint_safe_repr        | 743 ms                                                 | 763 ms: 1.03x slower                                                  |
| 2to3                    | 266 ms                                                 | 274 ms: 1.03x slower                                                  |
| sqlalchemy_imperative   | 18.2 ms                                                | 18.8 ms: 1.03x slower                                                 |
| sympy_expand            | 490 ms                                                 | 505 ms: 1.03x slower                                                  |
| sqlalchemy_declarative  | 141 ms                                                 | 145 ms: 1.03x slower                                                  |
| pathlib                 | 18.5 ms                                                | 19.1 ms: 1.03x slower                                                 |
| pprint_pformat          | 1.53 sec                                               | 1.58 sec: 1.03x slower                                                |
| flaskblogging           | 7.20 ms                                                | 7.46 ms: 1.04x slower                                                 |
| regex_v8                | 22.9 ms                                                | 23.7 ms: 1.04x slower                                                 |
| genshi_xml              | 54.1 ms                                                | 56.1 ms: 1.04x slower                                                 |
| scimark_fft             | 342 ms                                                 | 355 ms: 1.04x slower                                                  |
| docutils                | 2.69 sec                                               | 2.79 sec: 1.04x slower                                                |
| deepcopy_memo           | 38.9 us                                                | 40.4 us: 1.04x slower                                                 |
| sympy_integrate         | 21.4 ms                                                | 22.2 ms: 1.04x slower                                                 |
| fannkuch                | 410 ms                                                 | 427 ms: 1.04x slower                                                  |
| deepcopy_reduce         | 3.14 us                                                | 3.27 us: 1.04x slower                                                 |
| dulwich_log             | 64.9 ms                                                | 68.3 ms: 1.05x slower                                                 |
| pycparser               | 1.20 sec                                               | 1.26 sec: 1.05x slower                                                |
| nqueens                 | 86.8 ms                                                | 91.4 ms: 1.05x slower                                                 |
| xml_etree_process       | 56.5 ms                                                | 59.6 ms: 1.05x slower                                                 |
| float                   | 78.9 ms                                                | 83.3 ms: 1.06x slower                                                 |
| async_tree_memoization  | 640 ms                                                 | 676 ms: 1.06x slower                                                  |
| sqlglot_optimize        | 55.2 ms                                                | 58.4 ms: 1.06x slower                                                 |
| deepcopy                | 360 us                                                 | 382 us: 1.06x slower                                                  |
| thrift                  | 772 us                                                 | 821 us: 1.06x slower                                                  |
| sqlglot_normalize       | 112 ms                                                 | 119 ms: 1.06x slower                                                  |
| raytrace                | 306 ms                                                 | 326 ms: 1.06x slower                                                  |
| sqlite_synth            | 2.58 us                                                | 2.76 us: 1.07x slower                                                 |
| bench_thread_pool       | 833 us                                                 | 892 us: 1.07x slower                                                  |
| regex_dna               | 204 ms                                                 | 219 ms: 1.07x slower                                                  |
| async_tree_io           | 1.31 sec                                               | 1.41 sec: 1.08x slower                                                |
| logging_silent          | 108 ns                                                 | 117 ns: 1.08x slower                                                  |
| chaos                   | 71.4 ms                                                | 77.1 ms: 1.08x slower                                                 |
| genshi_text             | 22.8 ms                                                | 24.6 ms: 1.08x slower                                                 |
| chameleon               | 6.86 ms                                                | 7.46 ms: 1.09x slower                                                 |
| async_tree_cpu_io_mixed | 750 ms                                                 | 818 ms: 1.09x slower                                                  |
| scimark_monte_carlo     | 71.8 ms                                                | 78.4 ms: 1.09x slower                                                 |
| html5lib                | 65.0 ms                                                | 71.5 ms: 1.10x slower                                                 |
| coroutines              | 26.1 ms                                                | 28.8 ms: 1.10x slower                                                 |
| hexiom                  | 6.74 ms                                                | 7.42 ms: 1.10x slower                                                 |
| mako                    | 10.8 ms                                                | 12.1 ms: 1.12x slower                                                 |
| django_template         | 33.8 ms                                                | 37.9 ms: 1.12x slower                                                 |
| unpickle_pure_python    | 241 us                                                 | 271 us: 1.13x slower                                                  |
| tornado_http            | 97.7 ms                                                | 111 ms: 1.13x slower                                                  |
| richards                | 48.9 ms                                                | 55.7 ms: 1.14x slower                                                 |
| pickle_pure_python      | 319 us                                                 | 364 us: 1.14x slower                                                  |
| crypto_pyaes            | 77.5 ms                                                | 90.2 ms: 1.16x slower                                                 |
| go                      | 143 ms                                                 | 167 ms: 1.17x slower                                                  |
| scimark_lu              | 112 ms                                                 | 136 ms: 1.21x slower                                                  |
| nbody                   | 91.6 ms                                                | 112 ms: 1.22x slower                                                  |
| pyflate                 | 426 ms                                                 | 541 ms: 1.27x slower                                                  |
| deltablue               | 3.80 ms                                                | 4.86 ms: 1.28x slower                                                 |
| scimark_sor             | 121 ms                                                 | 156 ms: 1.28x slower                                                  |
| sqlglot_transpile       | 1.75 ms                                                | 2.37 ms: 1.35x slower                                                 |
| sqlglot_parse           | 1.43 ms                                                | 2.06 ms: 1.44x slower                                                 |
| python_startup          | 8.69 ms                                                | 14.6 ms: 1.68x slower                                                 |
| Geometric mean          | (ref)                                                  | 1.05x slower                                                          |

Benchmark hidden because not significant (6): pylint, unpickle, sympy_sum, bench_mp_pool, spectral_norm, unpack_sequence
Ignored benchmarks (17) of results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp, asyncio_tcp_ssl, asyncio_websockets, comprehensions, create_gc_cycles, dask, djangocms, gc_traversal, mypy2, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.03x
- 95% likely to have a slowdown of 1.03x
- 99% likely to have a slowdown of 1.02x
