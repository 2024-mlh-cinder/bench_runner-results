# Results

- fork: python
- version: 3.11.1
- tier 2: False
- commit hash: [a7a450f](https://github.com/python/cpython/commit/a7a450f)
- commit date: 2022-12-06T19:05:27+00:00
- ref: a7a450f84a0874216031, v3.11.1

## linux x86_64 (linux)

- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f.json)

### vs. 3.10.4

- Geometric mean: 1.31x faster \* (HPT: reliability of 100.00%, 1.25x faster at 99th %ile)
- missing benchmarks: asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f-vs-3.10.4.md)
- [plot](bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f-vs-3.11.0.md)
- [plot](bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 99.99%, 1.01x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, comprehensions, richards_super, tomli_loads, typing_runtime_protocols
- new benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f-vs-3.12.0.md)
- [plot](bm-20221206-linux-x86_64-python-v3.11.1-3.11.1-a7a450f-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/4513537050)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-67-generic-x86_64-with-glibc2.35
- [raw results](bm-20221206-pythonperf2-x86_64-python-a7a450f84a0874216031-3.11.1-a7a450f.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: asyncio_tcp_ssl, asyncio_websockets, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20221206-pythonperf2-x86_64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.10.4.md)
- [plot](bm-20221206-pythonperf2-x86_64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 99.97%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20221206-pythonperf2-x86_64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.11.0.md)
- [plot](bm-20221206-pythonperf2-x86_64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 99.86%, 1.00x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, asyncio_websockets, richards_super, tomli_loads, typing_runtime_protocols
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20221206-pythonperf2-x86_64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.12.0.md)
- [plot](bm-20221206-pythonperf2-x86_64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/4483411626)
- cpu model: missing
- platform: Windows-10-10.0.22000-SP0
- [raw results](bm-20221206-pythonperf1-amd64-python-a7a450f84a0874216031-3.11.1-a7a450f.json)

### vs. 3.10.4

- Geometric mean: 1.12x faster \* (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- missing benchmarks: asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20221206-pythonperf1-amd64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.10.4.md)
- [plot](bm-20221206-pythonperf1-amd64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x slower \* (HPT: reliability of 52.48%, 1.00x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
- [table](bm-20221206-pythonperf1-amd64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.11.0.md)
- [plot](bm-20221206-pythonperf1-amd64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.05x slower \* (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_tcp_ssl, richards_super, tomli_loads, typing_runtime_protocols
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20221206-pythonperf1-amd64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.12.0.md)
- [plot](bm-20221206-pythonperf1-amd64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6961754573)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20221206-darwin-arm64-python-a7a450f84a0874216031-3.11.1-a7a450f.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20221206-darwin-arm64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.10.4.md)
- [plot](bm-20221206-darwin-arm64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster (HPT: reliability of 78.47%, 1.00x slower at 99th %ile)
- [table](bm-20221206-darwin-arm64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.11.0.md)
- [plot](bm-20221206-darwin-arm64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.92%, 1.00x faster at 99th %ile)
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20221206-darwin-arm64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.12.0.md)
- [plot](bm-20221206-darwin-arm64-python-a7a450f84a0874216031-3.11.1-a7a450f-vs-3.12.0.png)

