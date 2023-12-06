
# Results vs. 3.10.4

- fork: python
- ref: 5a7e1e0a92622c605ab2
- machine: windows-amd64
- commit hash: 5a7e1e0
- commit date: 2022-07-11
- overall geometric mean: 1.11x faster \*
- HPT reliability: 100.00%
- HPT 99th percentile: 1.08x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 239 ms                                                      | 206 ms: 1.16x faster                                                       |
| chameleon      | 6.02 ms                                                     | 5.14 ms: 1.17x faster                                                      |
| docutils       | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                                     |
| html5lib       | 47.5 ms                                                     | 38.9 ms: 1.22x faster                                                      |
| tornado_http   | 106 ms                                                      | 91.9 ms: 1.15x faster                                                      |
| Geometric mean | (ref)                                                       | 1.18x faster                                                               |

Benchmarks with tag 'asyncio':
==============================

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io           | 1.07 sec                                                    | 753 ms: 1.42x faster                                                       |
| async_tree_memoization  | 505 ms                                                      | 375 ms: 1.35x faster                                                       |
| async_tree_none         | 424 ms                                                      | 317 ms: 1.34x faster                                                       |
| async_tree_cpu_io_mixed | 617 ms                                                      | 508 ms: 1.22x faster                                                       |
| Geometric mean          | (ref)                                                       | 1.33x faster                                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| float          | 61.7 ms                                                     | 53.9 ms: 1.15x faster                                                      |
| nbody          | 71.0 ms                                                     | 68.7 ms: 1.03x faster                                                      |
| Geometric mean | (ref)                                                       | 1.06x faster                                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_dna      | 129 ms                                                      | 114 ms: 1.13x faster                                                       |
| regex_compile  | 102 ms                                                      | 90.8 ms: 1.13x faster                                                      |
| regex_v8       | 15.0 ms                                                     | 13.4 ms: 1.12x faster                                                      |
| regex_effbot   | 1.56 ms                                                     | 1.70 ms: 1.09x slower                                                      |
| Geometric mean | (ref)                                                       | 1.07x faster                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| pickle_pure_python   | 259 us                                                      | 204 us: 1.27x faster                                                       |
| unpickle_pure_python | 177 us                                                      | 152 us: 1.17x faster                                                       |
| xml_etree_process    | 43.1 ms                                                     | 37.8 ms: 1.14x faster                                                      |
| json_dumps           | 8.77 ms                                                     | 7.78 ms: 1.13x faster                                                      |
| unpickle             | 9.11 us                                                     | 8.32 us: 1.09x faster                                                      |
| pickle               | 6.87 us                                                     | 6.48 us: 1.06x faster                                                      |
| xml_etree_iterparse  | 64.5 ms                                                     | 62.7 ms: 1.03x faster                                                      |
| xml_etree_generate   | 54.5 ms                                                     | 53.4 ms: 1.02x faster                                                      |
| xml_etree_parse      | 96.8 ms                                                     | 95.1 ms: 1.02x faster                                                      |
| pickle_list          | 2.69 us                                                     | 2.65 us: 1.01x faster                                                      |
| json_loads           | 14.2 us                                                     | 14.1 us: 1.01x faster                                                      |
| unpickle_list        | 2.68 us                                                     | 2.80 us: 1.04x slower                                                      |
| pickle_dict          | 17.1 us                                                     | 18.4 us: 1.07x slower                                                      |
| Geometric mean       | (ref)                                                       | 1.06x faster                                                               |

Benchmarks with tag 'startup':
==============================

| Benchmark      | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                      |
| Geometric mean | (ref)                                                       | 1.03x faster                                                               |

Benchmark hidden because not significant (1): python_startup_no_site

Benchmarks with tag 'template':
===============================

| Benchmark       | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-----------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako            | 8.98 ms                                                     | 7.23 ms: 1.24x faster                                                      |
| django_template | 28.8 ms                                                     | 25.0 ms: 1.15x faster                                                      |
| genshi_text     | 18.8 ms                                                     | 17.6 ms: 1.07x faster                                                      |
| genshi_xml      | 39.4 ms                                                     | 38.6 ms: 1.02x faster                                                      |
| Geometric mean  | (ref)                                                       | 1.12x faster                                                               |

All benchmarks:
===============

| Benchmark               | bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120 | bm-20220711-pythonperf1-amd64-python-5a7e1e0a92622c605ab2-3.11.0b4-5a7e1e0 |
|-------------------------|:-----------------------------------------------------------:|:--------------------------------------------------------------------------:|
| deltablue               | 4.12 ms                                                     | 2.66 ms: 1.55x faster                                                      |
| async_tree_io           | 1.07 sec                                                    | 753 ms: 1.42x faster                                                       |
| go                      | 135 ms                                                      | 99.5 ms: 1.36x faster                                                      |
| async_tree_memoization  | 505 ms                                                      | 375 ms: 1.35x faster                                                       |
| scimark_sor             | 105 ms                                                      | 78.5 ms: 1.34x faster                                                      |
| async_tree_none         | 424 ms                                                      | 317 ms: 1.34x faster                                                       |
| scimark_lu              | 84.0 ms                                                     | 62.7 ms: 1.34x faster                                                      |
| pyflate                 | 402 ms                                                      | 306 ms: 1.31x faster                                                       |
| scimark_monte_carlo     | 58.0 ms                                                     | 44.3 ms: 1.31x faster                                                      |
| raytrace                | 266 ms                                                      | 204 ms: 1.31x faster                                                       |
| logging_silent          | 93.4 ns                                                     | 72.4 ns: 1.29x faster                                                      |
| sqlglot_parse           | 1.20 ms                                                     | 936 us: 1.29x faster                                                       |
| pycparser               | 905 ms                                                      | 706 ms: 1.28x faster                                                       |
| richards                | 40.6 ms                                                     | 31.7 ms: 1.28x faster                                                      |
| sqlglot_transpile       | 1.45 ms                                                     | 1.13 ms: 1.28x faster                                                      |
| pickle_pure_python      | 259 us                                                      | 204 us: 1.27x faster                                                       |
| mypy2                   | 347 ms                                                      | 278 ms: 1.25x faster                                                       |
| crypto_pyaes            | 63.1 ms                                                     | 50.6 ms: 1.25x faster                                                      |
| mako                    | 8.98 ms                                                     | 7.23 ms: 1.24x faster                                                      |
| async_generators        | 219 ms                                                      | 178 ms: 1.23x faster                                                       |
| html5lib                | 47.5 ms                                                     | 38.9 ms: 1.22x faster                                                      |
| chaos                   | 59.5 ms                                                     | 48.7 ms: 1.22x faster                                                      |
| async_tree_cpu_io_mixed | 617 ms                                                      | 508 ms: 1.22x faster                                                       |
| hexiom                  | 5.59 ms                                                     | 4.61 ms: 1.21x faster                                                      |
| create_gc_cycles        | 800 us                                                      | 664 us: 1.20x faster                                                       |
| thrift                  | 623 us                                                      | 518 us: 1.20x faster                                                       |
| docutils                | 1.88 sec                                                    | 1.58 sec: 1.19x faster                                                     |
| chameleon               | 6.02 ms                                                     | 5.14 ms: 1.17x faster                                                      |
| unpickle_pure_python    | 177 us                                                      | 152 us: 1.17x faster                                                       |
| sqlalchemy_declarative  | 98.6 ms                                                     | 84.7 ms: 1.16x faster                                                      |
| 2to3                    | 239 ms                                                      | 206 ms: 1.16x faster                                                       |
| pprint_safe_repr        | 594 ms                                                      | 515 ms: 1.15x faster                                                       |
| django_template         | 28.8 ms                                                     | 25.0 ms: 1.15x faster                                                      |
| tornado_http            | 106 ms                                                      | 91.9 ms: 1.15x faster                                                      |
| float                   | 61.7 ms                                                     | 53.9 ms: 1.15x faster                                                      |
| pprint_pformat          | 1.22 sec                                                    | 1.07 sec: 1.15x faster                                                     |
| deepcopy_memo           | 29.0 us                                                     | 25.3 us: 1.14x faster                                                      |
| xml_etree_process       | 43.1 ms                                                     | 37.8 ms: 1.14x faster                                                      |
| sqlglot_optimize        | 39.4 ms                                                     | 34.8 ms: 1.13x faster                                                      |
| regex_dna               | 129 ms                                                      | 114 ms: 1.13x faster                                                       |
| dask                    | 305 ms                                                      | 270 ms: 1.13x faster                                                       |
| json_dumps              | 8.77 ms                                                     | 7.78 ms: 1.13x faster                                                      |
| regex_compile           | 102 ms                                                      | 90.8 ms: 1.13x faster                                                      |
| regex_v8                | 15.0 ms                                                     | 13.4 ms: 1.12x faster                                                      |
| sqlite_synth            | 1.90 us                                                     | 1.70 us: 1.12x faster                                                      |
| aiohttp                 | 961 us                                                      | 860 us: 1.12x faster                                                       |
| dulwich_log             | 48.6 ms                                                     | 44.2 ms: 1.10x faster                                                      |
| sympy_expand            | 320 ms                                                      | 291 ms: 1.10x faster                                                       |
| sympy_sum               | 105 ms                                                      | 95.8 ms: 1.10x faster                                                      |
| unpickle                | 9.11 us                                                     | 8.32 us: 1.09x faster                                                      |
| sympy_integrate         | 15.0 ms                                                     | 13.7 ms: 1.09x faster                                                      |
| sqlglot_normalize       | 207 ms                                                      | 192 ms: 1.08x faster                                                       |
| sqlalchemy_imperative   | 11.2 ms                                                     | 10.4 ms: 1.07x faster                                                      |
| genshi_text             | 18.8 ms                                                     | 17.6 ms: 1.07x faster                                                      |
| pylint                  | 341 ms                                                      | 318 ms: 1.07x faster                                                       |
| python_startup          | 19.7 ms                                                     | 18.4 ms: 1.07x faster                                                      |
| spectral_norm           | 78.9 ms                                                     | 73.7 ms: 1.07x faster                                                      |
| bench_thread_pool       | 913 us                                                      | 858 us: 1.06x faster                                                       |
| asyncio_tcp             | 717 ms                                                      | 675 ms: 1.06x faster                                                       |
| pickle                  | 6.87 us                                                     | 6.48 us: 1.06x faster                                                      |
| sympy_str               | 193 ms                                                      | 182 ms: 1.06x faster                                                       |
| deepcopy                | 259 us                                                      | 246 us: 1.06x faster                                                       |
| comprehensions          | 16.6 us                                                     | 15.7 us: 1.05x faster                                                      |
| coroutines              | 15.5 ms                                                     | 14.8 ms: 1.05x faster                                                      |
| deepcopy_reduce         | 2.22 us                                                     | 2.14 us: 1.04x faster                                                      |
| nbody                   | 71.0 ms                                                     | 68.7 ms: 1.03x faster                                                      |
| xml_etree_iterparse     | 64.5 ms                                                     | 62.7 ms: 1.03x faster                                                      |
| fannkuch                | 258 ms                                                      | 251 ms: 1.03x faster                                                       |
| mdp                     | 1.71 sec                                                    | 1.67 sec: 1.03x faster                                                     |
| genshi_xml              | 39.4 ms                                                     | 38.6 ms: 1.02x faster                                                      |
| xml_etree_generate      | 54.5 ms                                                     | 53.4 ms: 1.02x faster                                                      |
| xml_etree_parse         | 96.8 ms                                                     | 95.1 ms: 1.02x faster                                                      |
| pickle_list             | 2.69 us                                                     | 2.65 us: 1.01x faster                                                      |
| json_loads              | 14.2 us                                                     | 14.1 us: 1.01x faster                                                      |
| nqueens                 | 68.3 ms                                                     | 67.6 ms: 1.01x faster                                                      |
| scimark_fft             | 187 ms                                                      | 186 ms: 1.01x faster                                                       |
| flaskblogging           | 2.04 sec                                                    | 2.05 sec: 1.01x slower                                                     |
| scimark_sparse_mat_mult | 2.67 ms                                                     | 2.68 ms: 1.01x slower                                                      |
| gc_traversal            | 1.40 ms                                                     | 1.41 ms: 1.01x slower                                                      |
| meteor_contest          | 73.8 ms                                                     | 74.8 ms: 1.01x slower                                                      |
| bench_mp_pool           | 59.9 ms                                                     | 61.4 ms: 1.02x slower                                                      |
| unpickle_list           | 2.68 us                                                     | 2.80 us: 1.04x slower                                                      |
| telco                   | 3.82 ms                                                     | 4.02 ms: 1.05x slower                                                      |
| logging_simple          | 6.28 us                                                     | 6.68 us: 1.06x slower                                                      |
| generators              | 31.8 ms                                                     | 33.9 ms: 1.07x slower                                                      |
| logging_format          | 6.73 us                                                     | 7.19 us: 1.07x slower                                                      |
| json                    | 3.10 ms                                                     | 3.32 ms: 1.07x slower                                                      |
| pickle_dict             | 17.1 us                                                     | 18.4 us: 1.07x slower                                                      |
| regex_effbot            | 1.56 ms                                                     | 1.70 ms: 1.09x slower                                                      |
| unpack_sequence         | 40.0 ns                                                     | 45.4 ns: 1.13x slower                                                      |
| coverage                | 38.4 ms                                                     | 54.1 ms: 1.41x slower                                                      |
| Geometric mean          | (ref)                                                       | 1.11x faster                                                               |

Benchmark hidden because not significant (3): pathlib, pidigits, python_startup_no_site
Ignored benchmarks (4) of results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.09x
- 95% likely to have a speedup of 1.09x
- 99% likely to have a speedup of 1.08x
