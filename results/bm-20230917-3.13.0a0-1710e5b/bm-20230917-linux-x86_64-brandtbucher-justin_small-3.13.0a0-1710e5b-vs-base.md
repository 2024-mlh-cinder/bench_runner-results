
# Results vs. base

- fork: brandtbucher
- ref: justin_small
- machine: linux-x86_64
- commit hash: 1710e5b
- commit date: 2023-09-17
- overall geometric mean: 1.01x slower
- HPT reliability: 99.93%
- HPT 99th percentile: 1.00x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| docutils       | 2.60 sec                                                              | 2.64 sec: 1.01x slower                                              |
| tornado_http   | 95.0 ms                                                               | 96.0 ms: 1.01x slower                                               |
| Geometric mean | (ref)                                                                 | 1.01x slower                                                        |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| nbody          | 87.9 ms                                                               | 83.7 ms: 1.05x faster                                               |
| pidigits       | 187 ms                                                                | 187 ms: 1.00x slower                                                |
| float          | 78.7 ms                                                               | 81.5 ms: 1.04x slower                                               |
| Geometric mean | (ref)                                                                 | 1.00x faster                                                        |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| regex_effbot   | 3.63 ms                                                               | 3.34 ms: 1.09x faster                                               |
| regex_dna      | 209 ms                                                                | 204 ms: 1.03x faster                                                |
| regex_v8       | 23.0 ms                                                               | 23.3 ms: 1.01x slower                                               |
| regex_compile  | 134 ms                                                                | 138 ms: 1.03x slower                                                |
| Geometric mean | (ref)                                                                 | 1.02x faster                                                        |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|----------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| pickle_list          | 4.67 us                                                               | 4.49 us: 1.04x faster                                               |
| pickle_dict          | 32.4 us                                                               | 31.6 us: 1.03x faster                                               |
| tomli_loads          | 2.04 sec                                                              | 1.98 sec: 1.03x faster                                              |
| pickle               | 10.8 us                                                               | 10.6 us: 1.02x faster                                               |
| unpickle             | 14.9 us                                                               | 14.8 us: 1.01x faster                                               |
| json_loads           | 25.4 us                                                               | 25.1 us: 1.01x faster                                               |
| xml_etree_process    | 58.0 ms                                                               | 57.6 ms: 1.01x faster                                               |
| xml_etree_generate   | 83.9 ms                                                               | 83.4 ms: 1.01x faster                                               |
| json_dumps           | 9.81 ms                                                               | 9.91 ms: 1.01x slower                                               |
| xml_etree_iterparse  | 102 ms                                                                | 103 ms: 1.01x slower                                                |
| unpickle_pure_python | 211 us                                                                | 221 us: 1.05x slower                                                |
| Geometric mean       | (ref)                                                                 | 1.01x faster                                                        |

Benchmark hidden because not significant (3): xml_etree_parse, unpickle_list, pickle_pure_python

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| python_startup         | 10.1 ms                                                               | 10.1 ms: 1.00x slower                                               |
| python_startup_no_site | 6.86 ms                                                               | 6.88 ms: 1.00x slower                                               |
| Geometric mean         | (ref)                                                                 | 1.00x slower                                                        |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|-----------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| mako      | 10.5 ms                                                               | 10.8 ms: 1.03x slower                                               |

All benchmarks:
===============

| Benchmark                | bm-20230914-linux-x86_64-python-909adb5092c0ae942681-3.13.0a0-909adb5 | bm-20230917-linux-x86_64-brandtbucher-justin_small-3.13.0a0-1710e5b |
|--------------------------|:---------------------------------------------------------------------:|:-------------------------------------------------------------------:|
| unpack_sequence          | 48.2 ns                                                               | 42.4 ns: 1.14x faster                                               |
| regex_effbot             | 3.63 ms                                                               | 3.34 ms: 1.09x faster                                               |
| scimark_sor              | 130 ms                                                                | 120 ms: 1.08x faster                                                |
| scimark_fft              | 352 ms                                                                | 331 ms: 1.06x faster                                                |
| logging_format           | 6.80 us                                                               | 6.45 us: 1.05x faster                                               |
| nbody                    | 87.9 ms                                                               | 83.7 ms: 1.05x faster                                               |
| pickle_list              | 4.67 us                                                               | 4.49 us: 1.04x faster                                               |
| gc_traversal             | 4.11 ms                                                               | 3.98 ms: 1.03x faster                                               |
| pickle_dict              | 32.4 us                                                               | 31.6 us: 1.03x faster                                               |
| tomli_loads              | 2.04 sec                                                              | 1.98 sec: 1.03x faster                                              |
| richards                 | 48.1 ms                                                               | 46.9 ms: 1.03x faster                                               |
| regex_dna                | 209 ms                                                                | 204 ms: 1.03x faster                                                |
| pycparser                | 1.18 sec                                                              | 1.16 sec: 1.02x faster                                              |
| logging_simple           | 6.05 us                                                               | 5.92 us: 1.02x faster                                               |
| mdp                      | 2.63 sec                                                              | 2.58 sec: 1.02x faster                                              |
| scimark_monte_carlo      | 67.9 ms                                                               | 66.6 ms: 1.02x faster                                               |
| pickle                   | 10.8 us                                                               | 10.6 us: 1.02x faster                                               |
| unpickle                 | 14.9 us                                                               | 14.8 us: 1.01x faster                                               |
| json_loads               | 25.4 us                                                               | 25.1 us: 1.01x faster                                               |
| xml_etree_process        | 58.0 ms                                                               | 57.6 ms: 1.01x faster                                               |
| xml_etree_generate       | 83.9 ms                                                               | 83.4 ms: 1.01x faster                                               |
| python_startup           | 10.1 ms                                                               | 10.1 ms: 1.00x slower                                               |
| python_startup_no_site   | 6.86 ms                                                               | 6.88 ms: 1.00x slower                                               |
| pidigits                 | 187 ms                                                                | 187 ms: 1.00x slower                                                |
| create_gc_cycles         | 1.52 ms                                                               | 1.53 ms: 1.00x slower                                               |
| sqlglot_transpile        | 1.58 ms                                                               | 1.59 ms: 1.01x slower                                               |
| dulwich_log              | 66.8 ms                                                               | 67.4 ms: 1.01x slower                                               |
| deepcopy_reduce          | 3.12 us                                                               | 3.15 us: 1.01x slower                                               |
| tornado_http             | 95.0 ms                                                               | 96.0 ms: 1.01x slower                                               |
| asyncio_tcp_ssl          | 1.80 sec                                                              | 1.81 sec: 1.01x slower                                              |
| sqlglot_parse            | 1.27 ms                                                               | 1.28 ms: 1.01x slower                                               |
| pyflate                  | 454 ms                                                                | 459 ms: 1.01x slower                                                |
| scimark_sparse_mat_mult  | 4.56 ms                                                               | 4.61 ms: 1.01x slower                                               |
| json_dumps               | 9.81 ms                                                               | 9.91 ms: 1.01x slower                                               |
| xml_etree_iterparse      | 102 ms                                                                | 103 ms: 1.01x slower                                                |
| sqlglot_optimize         | 52.5 ms                                                               | 53.2 ms: 1.01x slower                                               |
| regex_v8                 | 23.0 ms                                                               | 23.3 ms: 1.01x slower                                               |
| pprint_pformat           | 1.47 sec                                                              | 1.49 sec: 1.01x slower                                              |
| docutils                 | 2.60 sec                                                              | 2.64 sec: 1.01x slower                                              |
| sqlglot_normalize        | 104 ms                                                                | 106 ms: 1.02x slower                                                |
| coverage                 | 84.9 ms                                                               | 86.4 ms: 1.02x slower                                               |
| coroutines               | 21.8 ms                                                               | 22.2 ms: 1.02x slower                                               |
| spectral_norm            | 106 ms                                                                | 108 ms: 1.02x slower                                                |
| scimark_lu               | 110 ms                                                                | 113 ms: 1.02x slower                                                |
| meteor_contest           | 105 ms                                                                | 107 ms: 1.02x slower                                                |
| deltablue                | 3.28 ms                                                               | 3.36 ms: 1.02x slower                                               |
| pathlib                  | 18.3 ms                                                               | 18.8 ms: 1.02x slower                                               |
| deepcopy                 | 344 us                                                                | 352 us: 1.02x slower                                                |
| mypy2                    | 336 ms                                                                | 345 ms: 1.03x slower                                                |
| mako                     | 10.5 ms                                                               | 10.8 ms: 1.03x slower                                               |
| async_generators         | 447 ms                                                                | 459 ms: 1.03x slower                                                |
| regex_compile            | 134 ms                                                                | 138 ms: 1.03x slower                                                |
| logging_silent           | 100 ns                                                                | 103 ns: 1.03x slower                                                |
| typing_runtime_protocols | 142 us                                                                | 146 us: 1.03x slower                                                |
| bench_thread_pool        | 809 us                                                                | 835 us: 1.03x slower                                                |
| float                    | 78.7 ms                                                               | 81.5 ms: 1.04x slower                                               |
| go                       | 140 ms                                                                | 145 ms: 1.04x slower                                                |
| chaos                    | 59.3 ms                                                               | 61.7 ms: 1.04x slower                                               |
| generators               | 28.3 ms                                                               | 29.5 ms: 1.04x slower                                               |
| fannkuch                 | 389 ms                                                                | 406 ms: 1.04x slower                                                |
| asyncio_tcp              | 480 ms                                                                | 501 ms: 1.04x slower                                                |
| deepcopy_memo            | 36.1 us                                                               | 37.8 us: 1.05x slower                                               |
| crypto_pyaes             | 69.2 ms                                                               | 72.4 ms: 1.05x slower                                               |
| unpickle_pure_python     | 211 us                                                                | 221 us: 1.05x slower                                                |
| comprehensions           | 20.4 us                                                               | 22.2 us: 1.09x slower                                               |
| nqueens                  | 78.8 ms                                                               | 85.7 ms: 1.09x slower                                               |
| hexiom                   | 5.86 ms                                                               | 6.53 ms: 1.11x slower                                               |
| Geometric mean           | (ref)                                                                 | 1.01x slower                                                        |

Benchmark hidden because not significant (15): json, telco, pprint_safe_repr, sqlite_synth, xml_etree_parse, bench_mp_pool, raytrace, unpickle_list, async_tree_io, async_tree_memoization, pickle_pure_python, richards_super, dask, async_tree_cpu_io_mixed, async_tree_none


# HPT report

- Reliability score: 99.93% likely to be slow
- 90% likely to have a slowdown of 1.00x
- 95% likely to have a slowdown of 1.00x
- 99% likely to have a slowdown of 1.00x
