
# Results vs. base

- fork: faster-cpython
- ref: deopts_with_ip
- machine: linux-x86_64
- commit hash: 4d1e295
- commit date: 2023-11-12
- overall geometric mean: 1.02x faster
- HPT reliability: 99.92%
- HPT 99th percentile: 1.00x faster

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| 2to3           | 293 ms                                                                 | 286 ms: 1.03x faster                                                       |
| tornado_http   | 103 ms                                                                 | 99.3 ms: 1.04x faster                                                      |
| Geometric mean | (ref)                                                                  | 1.02x faster                                                               |

Benchmark hidden because not significant (2): chameleon, docutils

Benchmarks with tag 'asyncio':
==============================

| Benchmark      | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| async_tree_io  | 1.24 sec                                                               | 1.23 sec: 1.01x faster                                                     |
| Geometric mean | (ref)                                                                  | 1.00x slower                                                               |

Benchmark hidden because not significant (7): async_tree_memoization, async_tree_none, async_tree_io_tg, async_tree_cpu_io_mixed, async_tree_none_tg, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| nbody          | 131 ms                                                                 | 114 ms: 1.15x faster                                                       |
| float          | 112 ms                                                                 | 98.5 ms: 1.13x faster                                                      |
| pidigits       | 196 ms                                                                 | 188 ms: 1.04x faster                                                       |
| Geometric mean | (ref)                                                                  | 1.11x faster                                                               |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| regex_compile  | 169 ms                                                                 | 160 ms: 1.05x faster                                                       |
| regex_dna      | 215 ms                                                                 | 221 ms: 1.03x slower                                                       |
| regex_v8       | 25.1 ms                                                                | 26.1 ms: 1.04x slower                                                      |
| regex_effbot   | 3.50 ms                                                                | 3.73 ms: 1.07x slower                                                      |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                               |

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|----------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| tomli_loads          | 3.21 sec                                                               | 2.76 sec: 1.16x faster                                                     |
| xml_etree_iterparse  | 116 ms                                                                 | 112 ms: 1.04x faster                                                       |
| pickle               | 11.6 us                                                                | 11.5 us: 1.01x faster                                                      |
| unpickle_pure_python | 247 us                                                                 | 246 us: 1.01x faster                                                       |
| pickle_pure_python   | 312 us                                                                 | 314 us: 1.00x slower                                                       |
| json_loads           | 28.3 us                                                                | 28.4 us: 1.01x slower                                                      |
| xml_etree_parse      | 158 ms                                                                 | 159 ms: 1.01x slower                                                       |
| xml_etree_generate   | 87.2 ms                                                                | 88.2 ms: 1.01x slower                                                      |
| unpickle_list        | 5.09 us                                                                | 5.16 us: 1.01x slower                                                      |
| xml_etree_process    | 59.2 ms                                                                | 60.0 ms: 1.01x slower                                                      |
| pickle_dict          | 33.8 us                                                                | 34.3 us: 1.02x slower                                                      |
| pickle_list          | 4.97 us                                                                | 5.22 us: 1.05x slower                                                      |
| Geometric mean       | (ref)                                                                  | 1.01x faster                                                               |

Benchmark hidden because not significant (2): unpickle, json_dumps

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| python_startup_no_site | 9.03 ms                                                                | 9.04 ms: 1.00x slower                                                      |
| python_startup         | 10.3 ms                                                                | 10.4 ms: 1.00x slower                                                      |
| Geometric mean         | (ref)                                                                  | 1.00x slower                                                               |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|-----------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| mako      | 15.6 ms                                                                | 14.8 ms: 1.05x faster                                                      |

All benchmarks:
===============

| Benchmark               | bm-20231114-linux-x86_64-python-a519b87958da0b340cae-3.13.0a1+-a519b87 | bm-20231112-linux-x86_64-faster%2dcpython-deopts_with_ip-3.13.0a1+-4d1e295 |
|-------------------------|:----------------------------------------------------------------------:|:--------------------------------------------------------------------------:|
| hexiom                  | 11.4 ms                                                                | 9.40 ms: 1.22x faster                                                      |
| comprehensions          | 27.9 us                                                                | 23.8 us: 1.17x faster                                                      |
| tomli_loads             | 3.21 sec                                                               | 2.76 sec: 1.16x faster                                                     |
| deltablue               | 5.69 ms                                                                | 4.90 ms: 1.16x faster                                                      |
| nbody                   | 131 ms                                                                 | 114 ms: 1.15x faster                                                       |
| float                   | 112 ms                                                                 | 98.5 ms: 1.13x faster                                                      |
| gc_traversal            | 4.28 ms                                                                | 3.83 ms: 1.12x faster                                                      |
| nqueens                 | 112 ms                                                                 | 101 ms: 1.10x faster                                                       |
| fannkuch                | 523 ms                                                                 | 479 ms: 1.09x faster                                                       |
| crypto_pyaes            | 89.3 ms                                                                | 83.0 ms: 1.08x faster                                                      |
| richards                | 53.7 ms                                                                | 50.0 ms: 1.07x faster                                                      |
| richards_super          | 61.0 ms                                                                | 56.9 ms: 1.07x faster                                                      |
| go                      | 174 ms                                                                 | 164 ms: 1.06x faster                                                       |
| scimark_sparse_mat_mult | 6.97 ms                                                                | 6.58 ms: 1.06x faster                                                      |
| chaos                   | 77.7 ms                                                                | 73.5 ms: 1.06x faster                                                      |
| regex_compile           | 169 ms                                                                 | 160 ms: 1.05x faster                                                       |
| mako                    | 15.6 ms                                                                | 14.8 ms: 1.05x faster                                                      |
| mdp                     | 2.88 sec                                                               | 2.74 sec: 1.05x faster                                                     |
| scimark_fft             | 447 ms                                                                 | 427 ms: 1.05x faster                                                       |
| raytrace                | 317 ms                                                                 | 304 ms: 1.04x faster                                                       |
| pidigits                | 196 ms                                                                 | 188 ms: 1.04x faster                                                       |
| logging_format          | 7.20 us                                                                | 6.92 us: 1.04x faster                                                      |
| xml_etree_iterparse     | 116 ms                                                                 | 112 ms: 1.04x faster                                                       |
| pyflate                 | 570 ms                                                                 | 548 ms: 1.04x faster                                                       |
| tornado_http            | 103 ms                                                                 | 99.3 ms: 1.04x faster                                                      |
| unpack_sequence         | 46.9 ns                                                                | 45.3 ns: 1.04x faster                                                      |
| sympy_integrate         | 22.1 ms                                                                | 21.3 ms: 1.04x faster                                                      |
| meteor_contest          | 121 ms                                                                 | 117 ms: 1.04x faster                                                       |
| sympy_expand            | 492 ms                                                                 | 477 ms: 1.03x faster                                                       |
| sympy_str               | 292 ms                                                                 | 284 ms: 1.03x faster                                                       |
| logging_simple          | 6.35 us                                                                | 6.18 us: 1.03x faster                                                      |
| 2to3                    | 293 ms                                                                 | 286 ms: 1.03x faster                                                       |
| scimark_monte_carlo     | 83.5 ms                                                                | 81.5 ms: 1.02x faster                                                      |
| pprint_pformat          | 1.72 sec                                                               | 1.68 sec: 1.02x faster                                                     |
| pprint_safe_repr        | 830 ms                                                                 | 815 ms: 1.02x faster                                                       |
| dulwich_log             | 70.2 ms                                                                | 69.0 ms: 1.02x faster                                                      |
| scimark_lu              | 123 ms                                                                 | 121 ms: 1.01x faster                                                       |
| mypy2                   | 359 ms                                                                 | 354 ms: 1.01x faster                                                       |
| pickle                  | 11.6 us                                                                | 11.5 us: 1.01x faster                                                      |
| async_generators        | 462 ms                                                                 | 459 ms: 1.01x faster                                                       |
| sqlglot_optimize        | 55.0 ms                                                                | 54.6 ms: 1.01x faster                                                      |
| unpickle_pure_python    | 247 us                                                                 | 246 us: 1.01x faster                                                       |
| async_tree_io           | 1.24 sec                                                               | 1.23 sec: 1.01x faster                                                     |
| bench_thread_pool       | 862 us                                                                 | 858 us: 1.01x faster                                                       |
| python_startup_no_site  | 9.03 ms                                                                | 9.04 ms: 1.00x slower                                                      |
| python_startup          | 10.3 ms                                                                | 10.4 ms: 1.00x slower                                                      |
| asyncio_tcp_ssl         | 1.80 sec                                                               | 1.81 sec: 1.00x slower                                                     |
| asyncio_tcp             | 493 ms                                                                 | 495 ms: 1.00x slower                                                       |
| pickle_pure_python      | 312 us                                                                 | 314 us: 1.00x slower                                                       |
| sqlglot_parse           | 1.35 ms                                                                | 1.36 ms: 1.00x slower                                                      |
| json_loads              | 28.3 us                                                                | 28.4 us: 1.01x slower                                                      |
| deepcopy_reduce         | 3.14 us                                                                | 3.16 us: 1.01x slower                                                      |
| xml_etree_parse         | 158 ms                                                                 | 159 ms: 1.01x slower                                                       |
| xml_etree_generate      | 87.2 ms                                                                | 88.2 ms: 1.01x slower                                                      |
| unpickle_list           | 5.09 us                                                                | 5.16 us: 1.01x slower                                                      |
| xml_etree_process       | 59.2 ms                                                                | 60.0 ms: 1.01x slower                                                      |
| pickle_dict             | 33.8 us                                                                | 34.3 us: 1.02x slower                                                      |
| pycparser               | 1.23 sec                                                               | 1.25 sec: 1.02x slower                                                     |
| coroutines              | 21.8 ms                                                                | 22.2 ms: 1.02x slower                                                      |
| scimark_sor             | 127 ms                                                                 | 130 ms: 1.02x slower                                                       |
| generators              | 29.2 ms                                                                | 29.8 ms: 1.02x slower                                                      |
| create_gc_cycles        | 1.46 ms                                                                | 1.49 ms: 1.02x slower                                                      |
| regex_dna               | 215 ms                                                                 | 221 ms: 1.03x slower                                                       |
| logging_silent          | 107 ns                                                                 | 111 ns: 1.03x slower                                                       |
| regex_v8                | 25.1 ms                                                                | 26.1 ms: 1.04x slower                                                      |
| pickle_list             | 4.97 us                                                                | 5.22 us: 1.05x slower                                                      |
| regex_effbot            | 3.50 ms                                                                | 3.73 ms: 1.07x slower                                                      |
| Geometric mean          | (ref)                                                                  | 1.02x faster                                                               |

Benchmark hidden because not significant (25): deepcopy, async_tree_memoization, unpickle, async_tree_none, sympy_sum, telco, deepcopy_memo, sqlglot_normalize, chameleon, asyncio_websockets, async_tree_io_tg, bench_mp_pool, docutils, async_tree_cpu_io_mixed, typing_runtime_protocols, json_dumps, sqlglot_transpile, pathlib, async_tree_none_tg, json, coverage, sqlite_synth, spectral_norm, async_tree_cpu_io_mixed_tg, async_tree_memoization_tg


# HPT report

- Reliability score: 99.92% likely to be faster
- 90% likely to have a speedup of 1.00x
- 95% likely to have a speedup of 1.00x
- 99% likely to have a speedup of 1.00x
