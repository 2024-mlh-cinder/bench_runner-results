
# Results vs. 3.11.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: windows-amd64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.08x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.03x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 207 ms                                                      | 196 ms: 1.06x faster                                                       |
| chameleon      | 5.35 ms                                                     | 4.53 ms: 1.18x faster                                                      |
| docutils       | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                     |
| html5lib       | 38.6 ms                                                     | 35.0 ms: 1.10x faster                                                      |
| Geometric mean | (ref)                                                       | 1.09x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_none        | 314 ms                                                      | 317 ms: 1.01x slower                                                       |
| async_tree_io          | 753 ms                                                      | 780 ms: 1.04x slower                                                       |
| async_tree_memoization | 367 ms                                                      | 388 ms: 1.06x slower                                                       |
| Geometric mean         | (ref)                                                       | 1.03x slower                                                               |

Benchmark hidden because not significant (1): async_tree_cpu_io_mixed

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 69.3 ms                                                     | 62.3 ms: 1.11x faster                                                      |
| float          | 54.4 ms                                                     | 50.1 ms: 1.08x faster                                                      |
| pidigits       | 149 ms                                                      | 151 ms: 1.01x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 90.8 ms                                                     | 82.5 ms: 1.10x faster                                                      |
| regex_dna      | 121 ms                                                      | 120 ms: 1.01x faster                                                       |
| regex_effbot   | 1.52 ms                                                     | 1.54 ms: 1.02x slower                                                      |
| regex_v8       | 13.7 ms                                                     | 14.0 ms: 1.02x slower                                                      |
| Geometric mean | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 7.90 ms                                                     | 5.17 ms: 1.53x faster                                                      |
| unpickle_pure_python | 152 us                                                      | 121 us: 1.26x faster                                                       |
| pickle_pure_python   | 207 us                                                      | 179 us: 1.16x faster                                                       |
| xml_etree_process    | 37.0 ms                                                     | 35.0 ms: 1.06x faster                                                      |
| xml_etree_generate   | 52.2 ms                                                     | 49.7 ms: 1.05x faster                                                      |
| xml_etree_parse      | 94.5 ms                                                     | 90.5 ms: 1.04x faster                                                      |
| xml_etree_iterparse  | 63.0 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| unpickle_list        | 2.57 us                                                     | 2.61 us: 1.02x slower                                                      |
| unpickle             | 7.82 us                                                     | 7.99 us: 1.02x slower                                                      |
| pickle               | 6.53 us                                                     | 6.90 us: 1.06x slower                                                      |
| pickle_list          | 2.68 us                                                     | 2.85 us: 1.06x slower                                                      |
| pickle_dict          | 17.8 us                                                     | 19.4 us: 1.09x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                               |

Benchmark hidden because not significant (1): json_loads

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                      |
| python_startup_no_site | 15.5 ms                                                     | 15.7 ms: 1.01x slower                                                      |
| Geometric mean         | (ref)                                                       | 1.00x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| genshi_text     | 17.7 ms                                                     | 13.8 ms: 1.28x faster                                                      |
| genshi_xml      | 40.5 ms                                                     | 32.3 ms: 1.25x faster                                                      |
| mako            | 7.55 ms                                                     | 6.19 ms: 1.22x faster                                                      |
| django_template | 24.0 ms                                                     | 21.4 ms: 1.12x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.22x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence         | 47.0 ns                                                     | 26.4 ns: 1.78x faster                                                      |
| json_dumps              | 7.90 ms                                                     | 5.17 ms: 1.53x faster                                                      |
| genshi_text             | 17.7 ms                                                     | 13.8 ms: 1.28x faster                                                      |
| deltablue               | 2.63 ms                                                     | 2.07 ms: 1.27x faster                                                      |
| unpickle_pure_python    | 152 us                                                      | 121 us: 1.26x faster                                                       |
| richards                | 30.8 ms                                                     | 24.5 ms: 1.26x faster                                                      |
| genshi_xml              | 40.5 ms                                                     | 32.3 ms: 1.25x faster                                                      |
| logging_silent          | 70.7 ns                                                     | 57.2 ns: 1.24x faster                                                      |
| mako                    | 7.55 ms                                                     | 6.19 ms: 1.22x faster                                                      |
| deepcopy_memo           | 25.5 us                                                     | 21.2 us: 1.20x faster                                                      |
| chameleon               | 5.35 ms                                                     | 4.53 ms: 1.18x faster                                                      |
| scimark_sor             | 76.4 ms                                                     | 64.6 ms: 1.18x faster                                                      |
| raytrace                | 211 ms                                                      | 179 ms: 1.18x faster                                                       |
| scimark_monte_carlo     | 44.6 ms                                                     | 38.1 ms: 1.17x faster                                                      |
| go                      | 98.8 ms                                                     | 84.8 ms: 1.16x faster                                                      |
| hexiom                  | 4.51 ms                                                     | 3.89 ms: 1.16x faster                                                      |
| pickle_pure_python      | 207 us                                                      | 179 us: 1.16x faster                                                       |
| pyflate                 | 305 ms                                                      | 264 ms: 1.16x faster                                                       |
| nqueens                 | 66.1 ms                                                     | 57.9 ms: 1.14x faster                                                      |
| spectral_norm           | 69.9 ms                                                     | 61.4 ms: 1.14x faster                                                      |
| scimark_lu              | 62.3 ms                                                     | 54.8 ms: 1.14x faster                                                      |
| pprint_safe_repr        | 519 ms                                                      | 458 ms: 1.13x faster                                                       |
| deepcopy                | 242 us                                                      | 214 us: 1.13x faster                                                       |
| scimark_sparse_mat_mult | 2.59 ms                                                     | 2.30 ms: 1.13x faster                                                      |
| django_template         | 24.0 ms                                                     | 21.4 ms: 1.12x faster                                                      |
| pprint_pformat          | 1.06 sec                                                    | 947 ms: 1.12x faster                                                       |
| fannkuch                | 248 ms                                                      | 222 ms: 1.12x faster                                                       |
| sqlglot_normalize       | 191 ms                                                      | 172 ms: 1.11x faster                                                       |
| nbody                   | 69.3 ms                                                     | 62.3 ms: 1.11x faster                                                      |
| deepcopy_reduce         | 2.07 us                                                     | 1.88 us: 1.11x faster                                                      |
| html5lib                | 38.6 ms                                                     | 35.0 ms: 1.10x faster                                                      |
| regex_compile           | 90.8 ms                                                     | 82.5 ms: 1.10x faster                                                      |
| sqlglot_optimize        | 35.1 ms                                                     | 32.0 ms: 1.09x faster                                                      |
| json                    | 2.99 ms                                                     | 2.74 ms: 1.09x faster                                                      |
| sqlglot_parse           | 939 us                                                      | 860 us: 1.09x faster                                                       |
| meteor_contest          | 75.0 ms                                                     | 68.8 ms: 1.09x faster                                                      |
| float                   | 54.4 ms                                                     | 50.1 ms: 1.08x faster                                                      |
| chaos                   | 46.8 ms                                                     | 43.2 ms: 1.08x faster                                                      |
| sqlglot_transpile       | 1.15 ms                                                     | 1.06 ms: 1.08x faster                                                      |
| telco                   | 3.93 ms                                                     | 3.64 ms: 1.08x faster                                                      |
| mdp                     | 1.73 sec                                                    | 1.61 sec: 1.08x faster                                                     |
| dulwich_log             | 44.1 ms                                                     | 41.2 ms: 1.07x faster                                                      |
| thrift                  | 501 us                                                      | 469 us: 1.07x faster                                                       |
| crypto_pyaes            | 48.2 ms                                                     | 45.1 ms: 1.07x faster                                                      |
| logging_format          | 7.06 us                                                     | 6.64 us: 1.06x faster                                                      |
| sympy_str               | 184 ms                                                      | 173 ms: 1.06x faster                                                       |
| logging_simple          | 6.60 us                                                     | 6.22 us: 1.06x faster                                                      |
| 2to3                    | 207 ms                                                      | 196 ms: 1.06x faster                                                       |
| xml_etree_process       | 37.0 ms                                                     | 35.0 ms: 1.06x faster                                                      |
| mypy2                   | 226 ms                                                      | 215 ms: 1.05x faster                                                       |
| xml_etree_generate      | 52.2 ms                                                     | 49.7 ms: 1.05x faster                                                      |
| sympy_expand            | 299 ms                                                      | 286 ms: 1.05x faster                                                       |
| xml_etree_parse         | 94.5 ms                                                     | 90.5 ms: 1.04x faster                                                      |
| sqlite_synth            | 1.79 us                                                     | 1.73 us: 1.04x faster                                                      |
| create_gc_cycles        | 706 us                                                      | 682 us: 1.03x faster                                                       |
| sympy_integrate         | 13.7 ms                                                     | 13.3 ms: 1.03x faster                                                      |
| scimark_fft             | 181 ms                                                      | 177 ms: 1.03x faster                                                       |
| python_startup          | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                      |
| dask                    | 262 ms                                                      | 258 ms: 1.02x faster                                                       |
| docutils                | 1.59 sec                                                    | 1.56 sec: 1.02x faster                                                     |
| regex_dna               | 121 ms                                                      | 120 ms: 1.01x faster                                                       |
| xml_etree_iterparse     | 63.0 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| sympy_sum               | 100.0 ms                                                    | 99.0 ms: 1.01x faster                                                      |
| gc_traversal            | 1.46 ms                                                     | 1.44 ms: 1.01x faster                                                      |
| comprehensions          | 15.6 us                                                     | 15.5 us: 1.01x faster                                                      |
| async_tree_none         | 314 ms                                                      | 317 ms: 1.01x slower                                                       |
| python_startup_no_site  | 15.5 ms                                                     | 15.7 ms: 1.01x slower                                                      |
| pidigits                | 149 ms                                                      | 151 ms: 1.01x slower                                                       |
| regex_effbot            | 1.52 ms                                                     | 1.54 ms: 1.02x slower                                                      |
| unpickle_list           | 2.57 us                                                     | 2.61 us: 1.02x slower                                                      |
| unpickle                | 7.82 us                                                     | 7.99 us: 1.02x slower                                                      |
| regex_v8                | 13.7 ms                                                     | 14.0 ms: 1.02x slower                                                      |
| bench_mp_pool           | 61.1 ms                                                     | 62.8 ms: 1.03x slower                                                      |
| coroutines              | 14.7 ms                                                     | 15.1 ms: 1.03x slower                                                      |
| async_tree_io           | 753 ms                                                      | 780 ms: 1.04x slower                                                       |
| pathlib                 | 69.4 ms                                                     | 72.1 ms: 1.04x slower                                                      |
| pickle                  | 6.53 us                                                     | 6.90 us: 1.06x slower                                                      |
| async_tree_memoization  | 367 ms                                                      | 388 ms: 1.06x slower                                                       |
| pickle_list             | 2.68 us                                                     | 2.85 us: 1.06x slower                                                      |
| pickle_dict             | 17.8 us                                                     | 19.4 us: 1.09x slower                                                      |
| asyncio_tcp             | 614 ms                                                      | 735 ms: 1.20x slower                                                       |
| coverage                | 43.0 ms                                                     | 51.6 ms: 1.20x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.08x faster                                                               |

Benchmark hidden because not significant (6): pycparser, bench_thread_pool, async_generators, json_loads, generators, async_tree_cpu_io_mixed
Ignored benchmarks (14) of results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, flaskblogging, pylint, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.04x
- 95% likely to have a speedup of 1.04x
- 99% likely to have a speedup of 1.03x
