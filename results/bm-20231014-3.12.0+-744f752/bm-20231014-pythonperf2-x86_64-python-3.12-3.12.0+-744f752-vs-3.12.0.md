
# Results vs. 3.12.0

- fork: python
- ref: 3.12
- machine: linux-x86_64
- commit hash: 744f752
- commit date: 2023-10-14
- overall geometric mean: 1.00x faster
- HPT reliability: 100.00%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| 2to3           | 287 ms                                                       | 285 ms: 1.01x faster                                       |
| docutils       | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                     |
| tornado_http   | 122 ms                                                       | 120 ms: 1.01x faster                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody          | 94.1 ms                                                      | 84.2 ms: 1.12x faster                                      |
| float          | 78.5 ms                                                      | 77.4 ms: 1.01x faster                                      |
| Geometric mean | (ref)                                                        | 1.04x faster                                               |

Benchmark hidden because not significant (1): pidigits

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| regex_compile  | 146 ms                                                       | 141 ms: 1.03x faster                                       |
| regex_v8       | 25.0 ms                                                      | 24.3 ms: 1.03x faster                                      |
| regex_effbot   | 3.47 ms                                                      | 3.49 ms: 1.01x slower                                      |
| regex_dna      | 241 ms                                                       | 243 ms: 1.01x slower                                       |
| Geometric mean | (ref)                                                        | 1.01x faster                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|----------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| pickle_pure_python   | 323 us                                                       | 316 us: 1.02x faster                                       |
| unpickle_list        | 4.77 us                                                      | 4.70 us: 1.01x faster                                      |
| unpickle             | 14.8 us                                                      | 14.6 us: 1.01x faster                                      |
| json_loads           | 24.3 us                                                      | 24.0 us: 1.01x faster                                      |
| tomli_loads          | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                     |
| json_dumps           | 10.2 ms                                                      | 10.2 ms: 1.00x faster                                      |
| pickle_list          | 4.39 us                                                      | 4.44 us: 1.01x slower                                      |
| unpickle_pure_python | 207 us                                                       | 209 us: 1.01x slower                                       |
| pickle               | 10.1 us                                                      | 10.3 us: 1.02x slower                                      |
| pickle_dict          | 31.7 us                                                      | 32.4 us: 1.02x slower                                      |
| Geometric mean       | (ref)                                                        | 1.00x faster                                               |

Benchmark hidden because not significant (4): xml_etree_iterparse, xml_etree_generate, xml_etree_process, xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| python_startup_no_site | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                      |
| python_startup         | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                      |
| Geometric mean         | (ref)                                                        | 1.00x faster                                               |

Benchmarks with tag 'template':
===============================

Benchmark hidden because not significant (1): mako

All benchmarks:
===============

| Benchmark                | bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0 | bm-20231014-pythonperf2-x86_64-python-3.12-3.12.0+-744f752 |
|--------------------------|:------------------------------------------------------------:|:----------------------------------------------------------:|
| nbody                    | 94.1 ms                                                      | 84.2 ms: 1.12x faster                                      |
| unpack_sequence          | 53.3 ns                                                      | 50.2 ns: 1.06x faster                                      |
| scimark_monte_carlo      | 72.4 ms                                                      | 69.2 ms: 1.05x faster                                      |
| create_gc_cycles         | 1.67 ms                                                      | 1.60 ms: 1.04x faster                                      |
| pathlib                  | 19.8 ms                                                      | 19.0 ms: 1.04x faster                                      |
| fannkuch                 | 350 ms                                                       | 338 ms: 1.03x faster                                       |
| pprint_safe_repr         | 823 ms                                                       | 797 ms: 1.03x faster                                       |
| scimark_sparse_mat_mult  | 4.42 ms                                                      | 4.29 ms: 1.03x faster                                      |
| scimark_lu               | 101 ms                                                       | 97.6 ms: 1.03x faster                                      |
| pprint_pformat           | 1.67 sec                                                     | 1.62 sec: 1.03x faster                                     |
| deepcopy_memo            | 37.4 us                                                      | 36.3 us: 1.03x faster                                      |
| regex_compile            | 146 ms                                                       | 141 ms: 1.03x faster                                       |
| regex_v8                 | 25.0 ms                                                      | 24.3 ms: 1.03x faster                                      |
| logging_silent           | 95.6 ns                                                      | 93.4 ns: 1.02x faster                                      |
| bench_thread_pool        | 980 us                                                       | 958 us: 1.02x faster                                       |
| meteor_contest           | 128 ms                                                       | 125 ms: 1.02x faster                                       |
| deepcopy                 | 376 us                                                       | 367 us: 1.02x faster                                       |
| pycparser                | 1.27 sec                                                     | 1.25 sec: 1.02x faster                                     |
| comprehensions           | 21.9 us                                                      | 21.5 us: 1.02x faster                                      |
| pickle_pure_python       | 323 us                                                       | 316 us: 1.02x faster                                       |
| richards                 | 45.0 ms                                                      | 44.4 ms: 1.01x faster                                      |
| scimark_fft              | 304 ms                                                       | 300 ms: 1.01x faster                                       |
| float                    | 78.5 ms                                                      | 77.4 ms: 1.01x faster                                      |
| tornado_http             | 122 ms                                                       | 120 ms: 1.01x faster                                       |
| sqlglot_parse            | 1.40 ms                                                      | 1.39 ms: 1.01x faster                                      |
| unpickle_list            | 4.77 us                                                      | 4.70 us: 1.01x faster                                      |
| unpickle                 | 14.8 us                                                      | 14.6 us: 1.01x faster                                      |
| async_generators         | 385 ms                                                       | 381 ms: 1.01x faster                                       |
| hexiom                   | 5.96 ms                                                      | 5.89 ms: 1.01x faster                                      |
| richards_super           | 51.7 ms                                                      | 51.1 ms: 1.01x faster                                      |
| spectral_norm            | 91.6 ms                                                      | 90.7 ms: 1.01x faster                                      |
| deltablue                | 3.29 ms                                                      | 3.25 ms: 1.01x faster                                      |
| json_loads               | 24.3 us                                                      | 24.0 us: 1.01x faster                                      |
| go                       | 150 ms                                                       | 149 ms: 1.01x faster                                       |
| tomli_loads              | 2.20 sec                                                     | 2.18 sec: 1.01x faster                                     |
| deepcopy_reduce          | 3.46 us                                                      | 3.43 us: 1.01x faster                                      |
| raytrace                 | 302 ms                                                       | 299 ms: 1.01x faster                                       |
| json                     | 5.14 ms                                                      | 5.10 ms: 1.01x faster                                      |
| crypto_pyaes             | 80.9 ms                                                      | 80.3 ms: 1.01x faster                                      |
| nqueens                  | 90.1 ms                                                      | 89.4 ms: 1.01x faster                                      |
| 2to3                     | 287 ms                                                       | 285 ms: 1.01x faster                                       |
| asyncio_tcp              | 381 ms                                                       | 379 ms: 1.01x faster                                       |
| docutils                 | 2.89 sec                                                     | 2.87 sec: 1.01x faster                                     |
| python_startup_no_site   | 8.70 ms                                                      | 8.65 ms: 1.01x faster                                      |
| mdp                      | 2.53 sec                                                     | 2.52 sec: 1.01x faster                                     |
| asyncio_tcp_ssl          | 1.58 sec                                                     | 1.57 sec: 1.00x faster                                     |
| json_dumps               | 10.2 ms                                                      | 10.2 ms: 1.00x faster                                      |
| dulwich_log              | 65.3 ms                                                      | 65.1 ms: 1.00x faster                                      |
| python_startup           | 11.7 ms                                                      | 11.7 ms: 1.00x faster                                      |
| sqlglot_optimize         | 57.8 ms                                                      | 58.1 ms: 1.00x slower                                      |
| regex_effbot             | 3.47 ms                                                      | 3.49 ms: 1.01x slower                                      |
| generators               | 36.7 ms                                                      | 37.0 ms: 1.01x slower                                      |
| regex_dna                | 241 ms                                                       | 243 ms: 1.01x slower                                       |
| sqlglot_normalize        | 117 ms                                                       | 118 ms: 1.01x slower                                       |
| typing_runtime_protocols | 151 us                                                       | 153 us: 1.01x slower                                       |
| pickle_list              | 4.39 us                                                      | 4.44 us: 1.01x slower                                      |
| sqlite_synth             | 2.70 us                                                      | 2.73 us: 1.01x slower                                      |
| unpickle_pure_python     | 207 us                                                       | 209 us: 1.01x slower                                       |
| coroutines               | 23.0 ms                                                      | 23.4 ms: 1.02x slower                                      |
| pickle                   | 10.1 us                                                      | 10.3 us: 1.02x slower                                      |
| pickle_dict              | 31.7 us                                                      | 32.4 us: 1.02x slower                                      |
| logging_simple           | 6.73 us                                                      | 6.94 us: 1.03x slower                                      |
| logging_format           | 7.37 us                                                      | 7.59 us: 1.03x slower                                      |
| gc_traversal             | 3.54 ms                                                      | 3.76 ms: 1.06x slower                                      |
| mypy2                    | 368 ms                                                       | 456 ms: 1.24x slower                                       |
| bench_mp_pool            | 5.34 ms                                                      | 7.40 ms: 1.39x slower                                      |
| Geometric mean           | (ref)                                                        | 1.00x faster                                               |

Benchmark hidden because not significant (17): dask, xml_etree_iterparse, sqlglot_transpile, async_tree_cpu_io_mixed, chaos, xml_etree_generate, async_tree_memoization, scimark_sor, pyflate, xml_etree_process, pidigits, telco, async_tree_io, coverage, async_tree_none, mako, xml_etree_parse


# HPT report

- Reliability score: 100.00% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
