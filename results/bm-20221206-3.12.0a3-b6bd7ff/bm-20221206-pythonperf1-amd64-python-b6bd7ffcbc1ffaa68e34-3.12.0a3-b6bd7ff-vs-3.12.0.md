
# Results vs. 3.12.0

- fork: python
- ref: b6bd7ffcbc1ffaa68e34
- machine: windows-amd64
- commit hash: b6bd7ff
- commit date: 2022-12-06
- overall geometric mean: 1.03x faster \*
- HPT reliability: 99.56%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 213 ms                                                      | 196 ms: 1.09x faster                                                       |
| chameleon      | 4.95 ms                                                     | 4.53 ms: 1.09x faster                                                      |
| docutils       | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                     |
| Geometric mean | (ref)                                                       | 1.07x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_cpu_io_mixed | 477 ms                                                      | 501 ms: 1.05x slower                                                       |
| async_tree_io           | 712 ms                                                      | 780 ms: 1.10x slower                                                       |
| async_tree_none         | 286 ms                                                      | 317 ms: 1.11x slower                                                       |
| async_tree_memoization  | 333 ms                                                      | 388 ms: 1.17x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.10x slower                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 68.8 ms                                                     | 62.3 ms: 1.10x faster                                                      |
| float          | 54.7 ms                                                     | 50.1 ms: 1.09x faster                                                      |
| pidigits       | 150 ms                                                      | 151 ms: 1.00x slower                                                       |
| Geometric mean | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 87.2 ms                                                     | 82.5 ms: 1.06x faster                                                      |
| regex_effbot   | 1.58 ms                                                     | 1.54 ms: 1.02x faster                                                      |
| regex_v8       | 13.5 ms                                                     | 14.0 ms: 1.04x slower                                                      |
| Geometric mean | (ref)                                                       | 1.01x faster                                                               |

Benchmark hidden because not significant (1): regex_dna

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| json_dumps           | 5.83 ms                                                     | 5.17 ms: 1.13x faster                                                      |
| xml_etree_generate   | 55.8 ms                                                     | 49.7 ms: 1.12x faster                                                      |
| unpickle_pure_python | 134 us                                                      | 121 us: 1.11x faster                                                       |
| pickle_pure_python   | 195 us                                                      | 179 us: 1.09x faster                                                       |
| xml_etree_process    | 37.6 ms                                                     | 35.0 ms: 1.07x faster                                                      |
| pickle               | 7.38 us                                                     | 6.90 us: 1.07x faster                                                      |
| json_loads           | 13.6 us                                                     | 12.9 us: 1.06x faster                                                      |
| unpickle             | 8.44 us                                                     | 7.99 us: 1.06x faster                                                      |
| unpickle_list        | 2.69 us                                                     | 2.61 us: 1.03x faster                                                      |
| xml_etree_iterparse  | 63.1 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| pickle_list          | 2.88 us                                                     | 2.85 us: 1.01x faster                                                      |
| pickle_dict          | 18.9 us                                                     | 19.4 us: 1.02x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                               |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup         | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                      |
| python_startup_no_site | 15.9 ms                                                     | 15.7 ms: 1.01x faster                                                      |
| Geometric mean         | (ref)                                                       | 1.02x faster                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 7.05 ms                                                     | 6.19 ms: 1.14x faster                                                      |
| django_template | 22.8 ms                                                     | 21.4 ms: 1.06x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.10x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0 | bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| unpack_sequence         | 36.9 ns                                                     | 26.4 ns: 1.40x faster                                                      |
| async_generators        | 230 ms                                                      | 179 ms: 1.28x faster                                                       |
| scimark_sor             | 79.8 ms                                                     | 64.6 ms: 1.23x faster                                                      |
| mako                    | 7.05 ms                                                     | 6.19 ms: 1.14x faster                                                      |
| scimark_monte_carlo     | 43.0 ms                                                     | 38.1 ms: 1.13x faster                                                      |
| json_dumps              | 5.83 ms                                                     | 5.17 ms: 1.13x faster                                                      |
| richards                | 27.6 ms                                                     | 24.5 ms: 1.12x faster                                                      |
| xml_etree_generate      | 55.8 ms                                                     | 49.7 ms: 1.12x faster                                                      |
| telco                   | 4.08 ms                                                     | 3.64 ms: 1.12x faster                                                      |
| pyflate                 | 294 ms                                                      | 264 ms: 1.11x faster                                                       |
| deepcopy_reduce         | 2.08 us                                                     | 1.88 us: 1.11x faster                                                      |
| pprint_safe_repr        | 508 ms                                                      | 458 ms: 1.11x faster                                                       |
| unpickle_pure_python    | 134 us                                                      | 121 us: 1.11x faster                                                       |
| deepcopy_memo           | 23.4 us                                                     | 21.2 us: 1.11x faster                                                      |
| pathlib                 | 79.6 ms                                                     | 72.1 ms: 1.10x faster                                                      |
| nbody                   | 68.8 ms                                                     | 62.3 ms: 1.10x faster                                                      |
| fannkuch                | 244 ms                                                      | 222 ms: 1.10x faster                                                       |
| pprint_pformat          | 1.04 sec                                                    | 947 ms: 1.09x faster                                                       |
| chameleon               | 4.95 ms                                                     | 4.53 ms: 1.09x faster                                                      |
| scimark_sparse_mat_mult | 2.51 ms                                                     | 2.30 ms: 1.09x faster                                                      |
| float                   | 54.7 ms                                                     | 50.1 ms: 1.09x faster                                                      |
| pickle_pure_python      | 195 us                                                      | 179 us: 1.09x faster                                                       |
| deepcopy                | 233 us                                                      | 214 us: 1.09x faster                                                       |
| 2to3                    | 213 ms                                                      | 196 ms: 1.09x faster                                                       |
| json                    | 2.94 ms                                                     | 2.74 ms: 1.08x faster                                                      |
| raytrace                | 192 ms                                                      | 179 ms: 1.08x faster                                                       |
| xml_etree_process       | 37.6 ms                                                     | 35.0 ms: 1.07x faster                                                      |
| bench_mp_pool           | 67.2 ms                                                     | 62.8 ms: 1.07x faster                                                      |
| pickle                  | 7.38 us                                                     | 6.90 us: 1.07x faster                                                      |
| sqlglot_normalize       | 183 ms                                                      | 172 ms: 1.07x faster                                                       |
| nqueens                 | 61.7 ms                                                     | 57.9 ms: 1.07x faster                                                      |
| create_gc_cycles        | 726 us                                                      | 682 us: 1.06x faster                                                       |
| django_template         | 22.8 ms                                                     | 21.4 ms: 1.06x faster                                                      |
| sqlglot_optimize        | 34.0 ms                                                     | 32.0 ms: 1.06x faster                                                      |
| json_loads              | 13.6 us                                                     | 12.9 us: 1.06x faster                                                      |
| logging_silent          | 60.5 ns                                                     | 57.2 ns: 1.06x faster                                                      |
| regex_compile           | 87.2 ms                                                     | 82.5 ms: 1.06x faster                                                      |
| unpickle                | 8.44 us                                                     | 7.99 us: 1.06x faster                                                      |
| go                      | 89.0 ms                                                     | 84.8 ms: 1.05x faster                                                      |
| scimark_lu              | 57.5 ms                                                     | 54.8 ms: 1.05x faster                                                      |
| meteor_contest          | 72.1 ms                                                     | 68.8 ms: 1.05x faster                                                      |
| spectral_norm           | 63.9 ms                                                     | 61.4 ms: 1.04x faster                                                      |
| dulwich_log             | 42.7 ms                                                     | 41.2 ms: 1.04x faster                                                      |
| gc_traversal            | 1.49 ms                                                     | 1.44 ms: 1.03x faster                                                      |
| unpickle_list           | 2.69 us                                                     | 2.61 us: 1.03x faster                                                      |
| crypto_pyaes            | 46.4 ms                                                     | 45.1 ms: 1.03x faster                                                      |
| hexiom                  | 4.00 ms                                                     | 3.89 ms: 1.03x faster                                                      |
| docutils                | 1.61 sec                                                    | 1.56 sec: 1.03x faster                                                     |
| scimark_fft             | 181 ms                                                      | 177 ms: 1.03x faster                                                       |
| deltablue               | 2.12 ms                                                     | 2.07 ms: 1.02x faster                                                      |
| regex_effbot            | 1.58 ms                                                     | 1.54 ms: 1.02x faster                                                      |
| python_startup          | 18.8 ms                                                     | 18.5 ms: 1.02x faster                                                      |
| xml_etree_iterparse     | 63.1 ms                                                     | 62.3 ms: 1.01x faster                                                      |
| python_startup_no_site  | 15.9 ms                                                     | 15.7 ms: 1.01x faster                                                      |
| pickle_list             | 2.88 us                                                     | 2.85 us: 1.01x faster                                                      |
| logging_format          | 6.72 us                                                     | 6.64 us: 1.01x faster                                                      |
| sqlite_synth            | 1.75 us                                                     | 1.73 us: 1.01x faster                                                      |
| pidigits                | 150 ms                                                      | 151 ms: 1.00x slower                                                       |
| sympy_str               | 171 ms                                                      | 173 ms: 1.01x slower                                                       |
| dask                    | 255 ms                                                      | 258 ms: 1.01x slower                                                       |
| pickle_dict             | 18.9 us                                                     | 19.4 us: 1.02x slower                                                      |
| chaos                   | 42.1 ms                                                     | 43.2 ms: 1.03x slower                                                      |
| sympy_integrate         | 13.0 ms                                                     | 13.3 ms: 1.03x slower                                                      |
| sympy_expand            | 278 ms                                                      | 286 ms: 1.03x slower                                                       |
| mypy2                   | 209 ms                                                      | 215 ms: 1.03x slower                                                       |
| regex_v8                | 13.5 ms                                                     | 14.0 ms: 1.04x slower                                                      |
| sqlglot_transpile       | 1.02 ms                                                     | 1.06 ms: 1.04x slower                                                      |
| async_tree_cpu_io_mixed | 477 ms                                                      | 501 ms: 1.05x slower                                                       |
| coroutines              | 14.1 ms                                                     | 15.1 ms: 1.07x slower                                                      |
| sqlglot_parse           | 802 us                                                      | 860 us: 1.07x slower                                                       |
| async_tree_io           | 712 ms                                                      | 780 ms: 1.10x slower                                                       |
| sympy_sum               | 90.1 ms                                                     | 99.0 ms: 1.10x slower                                                      |
| comprehensions          | 14.0 us                                                     | 15.5 us: 1.11x slower                                                      |
| async_tree_none         | 286 ms                                                      | 317 ms: 1.11x slower                                                       |
| mdp                     | 1.42 sec                                                    | 1.61 sec: 1.13x slower                                                     |
| async_tree_memoization  | 333 ms                                                      | 388 ms: 1.17x slower                                                       |
| coverage                | 39.8 ms                                                     | 51.6 ms: 1.30x slower                                                      |
| generators              | 22.6 ms                                                     | 33.9 ms: 1.50x slower                                                      |
| asyncio_tcp             | 471 ms                                                      | 735 ms: 1.56x slower                                                       |
| Geometric mean          | (ref)                                                       | 1.03x faster                                                               |

Benchmark hidden because not significant (5): xml_etree_parse, logging_simple, regex_dna, bench_thread_pool, pycparser
Ignored benchmarks (12) of results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json: aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, sqlalchemy_declarative, sqlalchemy_imperative, tomli_loads, tornado_http, typing_runtime_protocols
Ignored benchmarks (4) of results/bm-20221206-3.12.0a3-b6bd7ff/bm-20221206-pythonperf1-amd64-python-b6bd7ffcbc1ffaa68e34-3.12.0a3-b6bd7ff.json: genshi_text, genshi_xml, html5lib, thrift


# HPT report

- Reliability score: 99.56% likely to be faster
- 90% likely to have a speedup of 1.01x
- 95% likely to have a speedup of 1.01x
- 99% likely to have a speedup of 1.00x
