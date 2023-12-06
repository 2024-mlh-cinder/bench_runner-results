# Results

- fork: python
- version: 3.13.0a2+
- tier 2: False
- commit hash: [05a370a](https://github.com/python/cpython/commit/05a370a)
- commit date: 2023-12-01T17:05:56+01:00
- commit merge base: [a9073564ee50bc610e1fd36e45b0a5204618883a](https://github.com/python/cpython/commit/a9073564ee50bc610e1fd36e45b0a5204618883a)
- ref: 05a370abd6cdfe4b54be

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/7072711965)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2%2B-05a370a.json)

### vs. 3.10.4

- Geometric mean: 1.32x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2%2B-05a370a-vs-3.10.4.md)
- [plot](bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2%2B-05a370a-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x faster \* (HPT: reliability of 99.94%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2%2B-05a370a-vs-3.11.0.md)
- [plot](bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2%2B-05a370a-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster \* (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- missing benchmarks: aiohttp, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2%2B-05a370a-vs-3.12.0.md)
- [plot](bm-20231201-linux-x86_64-python-05a370abd6cdfe4b54be-3.13.0a2%2B-05a370a-vs-3.12.0.png)

