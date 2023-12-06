# Results

- fork: faster-cpython
- version: 3.13.0a0
- tier 2: False
- commit hash: [4da67aa](https://github.com/faster%2dcpython/cpython/commit/4da67aa)
- commit date: 2023-09-25T13:05:55+01:00
- commit merge base: [8b55adfa8ff05477b4be7def36db7b66c73f181d](https://github.com/faster%2dcpython/cpython/commit/8b55adfa8ff05477b4be7def36db7b66c73f181d)
- ref: tidy_up_eval_breaker

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6300186313)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa.json)

### vs. 3.10.4

- Geometric mean: 1.27x faster \* (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-3.10.4.md)
- [plot](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 91.62%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-3.11.0.md)
- [plot](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 98.24%, 1.00x slower at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-3.12.0.md)
- [plot](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.00x slower (HPT: reliability of 98.68%, 1.00x slower at 99th %ile)
- [table](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-base.md)
- [plot](bm-20230925-pythonperf2-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-4da67aa-vs-base.png)

