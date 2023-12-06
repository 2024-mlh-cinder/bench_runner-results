# Results

- fork: colesbury
- version: 3.13.0a0
- tier 2: False
- commit hash: [2144e0e](https://github.com/colesbury/cpython/commit/2144e0e)
- commit date: 2023-10-12T12:09:07+02:00
- commit merge base: [19b7ead5eb2fd1a0d19403e800a6f3adffbaac69](https://github.com/colesbury/cpython/commit/19b7ead5eb2fd1a0d19403e800a6f3adffbaac69)
- ref: biased_reference_cou

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6497410161)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e.json)

### vs. 3.10.4

- Geometric mean: 1.28x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-3.10.4.md)
- [plot](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster \* (HPT: reliability of 97.22%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-3.11.0.md)
- [plot](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 99.24%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-3.12.0.md)
- [plot](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x faster (HPT: reliability of 58.48%, 1.00x slower at 99th %ile)
- [table](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-base.md)
- [plot](bm-20231012-pythonperf2-x86_64-colesbury-biased_reference_cou-3.13.0a0-2144e0e-vs-base.png)

