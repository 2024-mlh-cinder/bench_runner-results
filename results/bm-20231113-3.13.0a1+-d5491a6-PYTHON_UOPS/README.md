# Results

- fork: python
- version: 3.13.0a1+
- tier 2: True
- commit hash: [d5491a6](https://github.com/python/cpython/commit/d5491a6)
- commit date: 2023-11-13T17:48:16+00:00
- commit merge base: [cf67ebfb315ce36175f3d425249d7c6560f6d0d5](https://github.com/python/cpython/commit/cf67ebfb315ce36175f3d425249d7c6560f6d0d5)
- ref: d5491a6eff516ad47906

## linux x86_64 (azure)

- [pystats raw](bm-20231113-azure-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-pystats.json)

### vs. base

- [pystats diff](bm-20231113-azure-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-pystats-vs-base.md)

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6854512764)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6.json)

### vs. 3.10.4

- Geometric mean: 1.23x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.md)
- [plot](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower \* (HPT: reliability of 98.62%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, djangocms, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.md)
- [plot](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.md)
- [plot](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- [table](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.md)
- [plot](bm-20231113-linux-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6854512764)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6.json)

### vs. 3.10.4

- Geometric mean: 1.16x faster \* (HPT: reliability of 100.00%, 1.08x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.md)
- [plot](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 96.92%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.md)
- [plot](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.12x slower \* (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.md)
- [plot](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.11x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- [table](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.md)
- [plot](bm-20231113-pythonperf2-x86_64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6866615335)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6.json)

### vs. 3.10.4

- Geometric mean: 1.13x faster \* (HPT: reliability of 100.00%, 1.06x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.md)
- [plot](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 54.73%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.md)
- [plot](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.md)
- [plot](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.07x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- [table](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.md)
- [plot](bm-20231113-pythonperf1-amd64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6854512764)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6.json)

### vs. 3.10.4

- Geometric mean: 1.08x faster (HPT: reliability of 99.86%, 1.01x faster at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.md)
- [plot](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.10x slower (HPT: reliability of 100.00%, 1.04x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, flaskblogging, genshi_text, genshi_xml, gunicorn, html5lib, pylint, sqlalchemy_declarative, sqlalchemy_imperative, thrift
- [table](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.md)
- [plot](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.09x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- missing benchmarks: aiohttp, dask, django_template, gunicorn, sqlalchemy_declarative, sqlalchemy_imperative
- [table](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.md)
- [plot](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-3.12.0.png)

### vs. base

- Geometric mean: 1.09x slower (HPT: reliability of 100.00%, 1.03x slower at 99th %ile)
- [table](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.md)
- [plot](bm-20231113-darwin-arm64-python-d5491a6eff516ad47906-3.13.0a1%2B-d5491a6-vs-base.png)

