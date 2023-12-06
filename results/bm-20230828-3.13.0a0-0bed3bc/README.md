# Results

- fork: faster-cpython
- version: 3.13.0a0
- tier 2: False
- commit hash: [0bed3bc](https://github.com/faster%2dcpython/cpython/commit/0bed3bc)
- commit date: 2023-08-28T05:47:50+01:00
- commit merge base: [2928e5dc6512e4206c616cd33e0bcc3288abf6ed](https://github.com/faster%2dcpython/cpython/commit/2928e5dc6512e4206c616cd33e0bcc3288abf6ed)
- ref: no_deep_freeze_3

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6047222418)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.10.4.md)
- [plot](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 72.22%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.11.0.md)
- [plot](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, chameleon, django_template, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.12.0.md)
- [plot](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 98.20%, 1.00x slower at 99th %ile)
- [table](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-base.md)
- [plot](bm-20230828-pythonperf1-amd64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6047226291)
- cpu model: missing
- platform: macOS-13.4.1-arm64-arm-64bit
- [raw results](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc.json)

### vs. 3.10.4

- Geometric mean: 1.21x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.10.4.md)
- [plot](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 99.02%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.11.0.md)
- [plot](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 98.83%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.12.0.md)
- [plot](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 100.00%, 1.00x faster at 99th %ile)
- [table](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-base.md)
- [plot](bm-20230828-darwin-arm64-faster%252dcpython-no_deep_freeze_3-3.13.0a0-0bed3bc-vs-base.png)

