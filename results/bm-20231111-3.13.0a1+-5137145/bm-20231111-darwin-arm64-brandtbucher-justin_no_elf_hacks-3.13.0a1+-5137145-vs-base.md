
# Results vs. base

- fork: brandtbucher
- ref: justin_no_elf_hacks
- machine: darwin-arm64
- commit hash: 5137145
- commit date: 2023-11-11
- overall geometric mean: 1.03x slower
- HPT reliability: 100.00%
- HPT 99th percentile: 1.01x slower

Benchmarks with tag 'apps':
===========================

| Benchmark      | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| 2to3           | 171 ms                                                                 | 180 ms: 1.05x slower                                                        |
| chameleon      | 4.66 ms                                                                | 4.75 ms: 1.02x slower                                                       |
| docutils       | 1.48 sec                                                               | 1.53 sec: 1.03x slower                                                      |
| tornado_http   | 69.6 ms                                                                | 73.3 ms: 1.05x slower                                                       |
| Geometric mean | (ref)                                                                  | 1.04x slower                                                                |

Benchmarks with tag 'asyncio':
==============================

| Benchmark          | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|--------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| async_tree_io_tg   | 686 ms                                                                 | 692 ms: 1.01x slower                                                        |
| async_tree_io      | 702 ms                                                                 | 710 ms: 1.01x slower                                                        |
| async_tree_none_tg | 267 ms                                                                 | 270 ms: 1.01x slower                                                        |
| Geometric mean     | (ref)                                                                  | 1.01x slower                                                                |

Benchmark hidden because not significant (5): async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, async_tree_memoization_tg, async_tree_memoization, async_tree_none

Benchmarks with tag 'math':
===========================

| Benchmark      | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| pidigits       | 284 ms                                                                 | 283 ms: 1.00x faster                                                        |
| float          | 57.3 ms                                                                | 60.3 ms: 1.05x slower                                                       |
| nbody          | 77.4 ms                                                                | 83.6 ms: 1.08x slower                                                       |
| Geometric mean | (ref)                                                                  | 1.04x slower                                                                |

Benchmarks with tag 'regex':
============================

| Benchmark      | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| regex_dna      | 149 ms                                                                 | 149 ms: 1.00x faster                                                        |
| regex_v8       | 16.9 ms                                                                | 17.0 ms: 1.01x slower                                                       |
| regex_compile  | 76.3 ms                                                                | 82.0 ms: 1.07x slower                                                       |
| Geometric mean | (ref)                                                                  | 1.02x slower                                                                |

Benchmark hidden because not significant (1): regex_effbot

Benchmarks with tag 'serialize':
================================

| Benchmark            | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|----------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads          | 1.55 sec                                                               | 1.49 sec: 1.04x faster                                                      |
| pickle_dict          | 18.4 us                                                                | 17.8 us: 1.04x faster                                                       |
| pickle_list          | 2.94 us                                                                | 2.88 us: 1.02x faster                                                       |
| pickle               | 7.55 us                                                                | 7.46 us: 1.01x faster                                                       |
| pickle_pure_python   | 203 us                                                                 | 200 us: 1.01x faster                                                        |
| json_loads           | 17.6 us                                                                | 17.7 us: 1.01x slower                                                       |
| unpickle             | 9.11 us                                                                | 9.19 us: 1.01x slower                                                       |
| xml_etree_process    | 39.6 ms                                                                | 40.0 ms: 1.01x slower                                                       |
| xml_etree_generate   | 57.7 ms                                                                | 58.6 ms: 1.02x slower                                                       |
| xml_etree_iterparse  | 75.5 ms                                                                | 76.8 ms: 1.02x slower                                                       |
| unpickle_list        | 3.14 us                                                                | 3.20 us: 1.02x slower                                                       |
| json_dumps           | 6.45 ms                                                                | 6.66 ms: 1.03x slower                                                       |
| unpickle_pure_python | 156 us                                                                 | 164 us: 1.05x slower                                                        |
| Geometric mean       | (ref)                                                                  | 1.00x slower                                                                |

Benchmark hidden because not significant (1): xml_etree_parse

Benchmarks with tag 'startup':
==============================

| Benchmark              | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| python_startup         | 12.5 ms                                                                | 12.6 ms: 1.00x slower                                                       |
| python_startup_no_site | 11.1 ms                                                                | 11.2 ms: 1.01x slower                                                       |
| Geometric mean         | (ref)                                                                  | 1.01x slower                                                                |

Benchmarks with tag 'template':
===============================

| Benchmark | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-----------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| mako      | 7.49 ms                                                                | 8.00 ms: 1.07x slower                                                       |

All benchmarks:
===============

| Benchmark               | bm-20231111-darwin-arm64-python-fa84e5fe0a3bd8e77c33-3.13.0a1+-fa84e5f | bm-20231111-darwin-arm64-brandtbucher-justin_no_elf_hacks-3.13.0a1+-5137145 |
|-------------------------|:----------------------------------------------------------------------:|:---------------------------------------------------------------------------:|
| tomli_loads             | 1.55 sec                                                               | 1.49 sec: 1.04x faster                                                      |
| pickle_dict             | 18.4 us                                                                | 17.8 us: 1.04x faster                                                       |
| pickle_list             | 2.94 us                                                                | 2.88 us: 1.02x faster                                                       |
| coroutines              | 18.3 ms                                                                | 17.9 ms: 1.02x faster                                                       |
| unpack_sequence         | 26.8 ns                                                                | 26.3 ns: 1.02x faster                                                       |
| generators              | 24.8 ms                                                                | 24.5 ms: 1.01x faster                                                       |
| pickle                  | 7.55 us                                                                | 7.46 us: 1.01x faster                                                       |
| pickle_pure_python      | 203 us                                                                 | 200 us: 1.01x faster                                                        |
| pidigits                | 284 ms                                                                 | 283 ms: 1.00x faster                                                        |
| regex_dna               | 149 ms                                                                 | 149 ms: 1.00x faster                                                        |
| deepcopy                | 222 us                                                                 | 222 us: 1.00x slower                                                        |
| richards                | 33.5 ms                                                                | 33.6 ms: 1.00x slower                                                       |
| gc_traversal            | 2.40 ms                                                                | 2.40 ms: 1.00x slower                                                       |
| python_startup          | 12.5 ms                                                                | 12.6 ms: 1.00x slower                                                       |
| create_gc_cycles        | 699 us                                                                 | 702 us: 1.00x slower                                                        |
| spectral_norm           | 72.6 ms                                                                | 72.9 ms: 1.00x slower                                                       |
| json                    | 2.98 ms                                                                | 3.00 ms: 1.01x slower                                                       |
| json_loads              | 17.6 us                                                                | 17.7 us: 1.01x slower                                                       |
| richards_super          | 36.8 ms                                                                | 37.0 ms: 1.01x slower                                                       |
| regex_v8                | 16.9 ms                                                                | 17.0 ms: 1.01x slower                                                       |
| telco                   | 4.71 ms                                                                | 4.75 ms: 1.01x slower                                                       |
| python_startup_no_site  | 11.1 ms                                                                | 11.2 ms: 1.01x slower                                                       |
| async_tree_io_tg        | 686 ms                                                                 | 692 ms: 1.01x slower                                                        |
| unpickle                | 9.11 us                                                                | 9.19 us: 1.01x slower                                                       |
| scimark_sor             | 105 ms                                                                 | 107 ms: 1.01x slower                                                        |
| async_tree_io           | 702 ms                                                                 | 710 ms: 1.01x slower                                                        |
| pyflate                 | 341 ms                                                                 | 345 ms: 1.01x slower                                                        |
| sqlite_synth            | 1.62 us                                                                | 1.64 us: 1.01x slower                                                       |
| xml_etree_process       | 39.6 ms                                                                | 40.0 ms: 1.01x slower                                                       |
| pycparser               | 696 ms                                                                 | 705 ms: 1.01x slower                                                        |
| logging_silent          | 70.0 ns                                                                | 70.9 ns: 1.01x slower                                                       |
| async_tree_none_tg      | 267 ms                                                                 | 270 ms: 1.01x slower                                                        |
| sqlglot_transpile       | 1.01 ms                                                                | 1.02 ms: 1.01x slower                                                       |
| sqlglot_normalize       | 186 ms                                                                 | 188 ms: 1.01x slower                                                        |
| xml_etree_generate      | 57.7 ms                                                                | 58.6 ms: 1.02x slower                                                       |
| sqlglot_parse           | 827 us                                                                 | 840 us: 1.02x slower                                                        |
| sympy_expand            | 246 ms                                                                 | 250 ms: 1.02x slower                                                        |
| chameleon               | 4.66 ms                                                                | 4.75 ms: 1.02x slower                                                       |
| coverage                | 47.8 ms                                                                | 48.6 ms: 1.02x slower                                                       |
| xml_etree_iterparse     | 75.5 ms                                                                | 76.8 ms: 1.02x slower                                                       |
| sqlglot_optimize        | 34.4 ms                                                                | 35.1 ms: 1.02x slower                                                       |
| raytrace                | 180 ms                                                                 | 184 ms: 1.02x slower                                                        |
| dulwich_log             | 30.2 ms                                                                | 30.8 ms: 1.02x slower                                                       |
| unpickle_list           | 3.14 us                                                                | 3.20 us: 1.02x slower                                                       |
| bench_mp_pool           | 44.7 ms                                                                | 45.8 ms: 1.02x slower                                                       |
| logging_simple          | 3.50 us                                                                | 3.58 us: 1.02x slower                                                       |
| sympy_str               | 142 ms                                                                 | 146 ms: 1.02x slower                                                        |
| logging_format          | 3.77 us                                                                | 3.87 us: 1.02x slower                                                       |
| sympy_sum               | 74.4 ms                                                                | 76.5 ms: 1.03x slower                                                       |
| docutils                | 1.48 sec                                                               | 1.53 sec: 1.03x slower                                                      |
| json_dumps              | 6.45 ms                                                                | 6.66 ms: 1.03x slower                                                       |
| bench_thread_pool       | 491 us                                                                 | 507 us: 1.03x slower                                                        |
| go                      | 105 ms                                                                 | 109 ms: 1.04x slower                                                        |
| scimark_lu              | 72.9 ms                                                                | 75.8 ms: 1.04x slower                                                       |
| fannkuch                | 287 ms                                                                 | 299 ms: 1.04x slower                                                        |
| mdp                     | 1.63 sec                                                               | 1.70 sec: 1.04x slower                                                      |
| pprint_safe_repr        | 506 ms                                                                 | 528 ms: 1.04x slower                                                        |
| meteor_contest          | 74.4 ms                                                                | 77.7 ms: 1.05x slower                                                       |
| crypto_pyaes            | 47.8 ms                                                                | 50.1 ms: 1.05x slower                                                       |
| pprint_pformat          | 1.03 sec                                                               | 1.08 sec: 1.05x slower                                                      |
| scimark_monte_carlo     | 47.3 ms                                                                | 49.5 ms: 1.05x slower                                                       |
| async_generators        | 300 ms                                                                 | 316 ms: 1.05x slower                                                        |
| 2to3                    | 171 ms                                                                 | 180 ms: 1.05x slower                                                        |
| float                   | 57.3 ms                                                                | 60.3 ms: 1.05x slower                                                       |
| tornado_http            | 69.6 ms                                                                | 73.3 ms: 1.05x slower                                                       |
| unpickle_pure_python    | 156 us                                                                 | 164 us: 1.05x slower                                                        |
| scimark_fft             | 208 ms                                                                 | 220 ms: 1.06x slower                                                        |
| sympy_integrate         | 10.9 ms                                                                | 11.5 ms: 1.06x slower                                                       |
| deepcopy_memo           | 24.3 us                                                                | 25.8 us: 1.06x slower                                                       |
| chaos                   | 41.5 ms                                                                | 44.1 ms: 1.06x slower                                                       |
| mako                    | 7.49 ms                                                                | 8.00 ms: 1.07x slower                                                       |
| regex_compile           | 76.3 ms                                                                | 82.0 ms: 1.07x slower                                                       |
| nbody                   | 77.4 ms                                                                | 83.6 ms: 1.08x slower                                                       |
| pathlib                 | 27.1 ms                                                                | 29.5 ms: 1.09x slower                                                       |
| nqueens                 | 59.8 ms                                                                | 65.2 ms: 1.09x slower                                                       |
| deltablue               | 2.42 ms                                                                | 2.66 ms: 1.10x slower                                                       |
| scimark_sparse_mat_mult | 3.11 ms                                                                | 3.46 ms: 1.11x slower                                                       |
| hexiom                  | 4.71 ms                                                                | 5.55 ms: 1.18x slower                                                       |
| comprehensions          | 11.6 us                                                                | 14.0 us: 1.21x slower                                                       |
| Geometric mean          | (ref)                                                                  | 1.03x slower                                                                |

Benchmark hidden because not significant (13): asyncio_tcp_ssl, regex_effbot, xml_etree_parse, asyncio_websockets, deepcopy_reduce, async_tree_cpu_io_mixed_tg, async_tree_cpu_io_mixed, typing_runtime_protocols, async_tree_memoization_tg, asyncio_tcp, async_tree_memoization, async_tree_none, mypy2


# HPT report

- Reliability score: 100.00% likely to be slow
- 90% likely to have a slowdown of 1.01x
- 95% likely to have a slowdown of 1.01x
- 99% likely to have a slowdown of 1.01x
