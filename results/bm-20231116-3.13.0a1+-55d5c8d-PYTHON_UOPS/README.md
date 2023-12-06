# Results

- fork: faster-cpython
- version: 3.13.0a1+
- tier 2: True
- commit hash: [55d5c8d](https://github.com/faster%2dcpython/cpython/commit/55d5c8d)
- commit date: 2023-11-16T23:56:06+00:00
- commit merge base: [2dbb2e035b968811ddc00317ccf0cadafacffe1c](https://github.com/faster%2dcpython/cpython/commit/2dbb2e035b968811ddc00317ccf0cadafacffe1c)
- ref: likelihood_on_trace

## linux x86_64 (azure)

- [pystats raw](bm-20231116-azure-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-pystats.json)
- [pystats table](bm-20231116-azure-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-pystats.md)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6906526519)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231116-pythonperf2-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d.json)

### vs. 3.10.4

- Geometric mean: 1.19x faster \* (HPT: reliability of 100.00%, 1.12x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231116-pythonperf2-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-vs-3.10.4.md)
- [plot](bm-20231116-pythonperf2-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 80.94%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231116-pythonperf2-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-vs-3.11.0.md)
- [plot](bm-20231116-pythonperf2-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.09x slower \* (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231116-pythonperf2-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-vs-3.12.0.md)
- [plot](bm-20231116-pythonperf2-x86_64-faster%252dcpython-likelihood_on_trace-3.13.0a1%2B-55d5c8d-vs-3.12.0.png)

