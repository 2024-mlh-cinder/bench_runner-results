# Results

- fork: faster-cpython
- version: 3.13.0a0
- tier 2: False
- commit hash: [2b8766e](https://github.com/faster%2dcpython/cpython/commit/2b8766e)
- commit date: 2023-09-13T14:08:11+01:00
- commit merge base: [8b55adfa8ff05477b4be7def36db7b66c73f181d](https://github.com/faster%2dcpython/cpython/commit/8b55adfa8ff05477b4be7def36db7b66c73f181d)
- ref: tidy_up_eval_breaker

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6173499880)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.24x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-3.10.4.md)
- [plot](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 88.49%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum, thrift
- [table](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-3.11.0.md)
- [plot](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 99.53%, 1.00x faster at 99th %ile)
- missing benchmarks: 2to3, aiohttp, async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, chameleon, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative, sympy_expand, sympy_integrate, sympy_str, sympy_sum
- [table](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-3.12.0.md)
- [plot](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.01x faster (HPT: reliability of 99.47%, 1.00x faster at 99th %ile)
- [table](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-base.md)
- [plot](bm-20230913-linux-x86_64-faster%252dcpython-tidy_up_eval_breaker-3.13.0a0-2b8766e-vs-base.png)

