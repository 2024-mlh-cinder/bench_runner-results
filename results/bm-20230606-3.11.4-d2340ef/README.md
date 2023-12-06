# Results

- fork: python
- version: 3.11.4
- tier 2: False
- commit hash: [d2340ef](https://github.com/python/cpython/commit/d2340ef)
- commit date: 2023-06-06T23:00:27+01:00
- ref: d2340ef25721b6a72d45, v3.11.4

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5204077606)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.23x faster at 99th %ile)
- missing benchmarks: asyncio_websockets, coverage
- [table](bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.10.4.md)
- [plot](bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- [table](bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.11.0.md)
- [plot](bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 99.98%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- new benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.12.0.md)
- [plot](bm-20230606-linux-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5204077606)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-67-generic-x86_64-with-glibc2.35
- [raw results](bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: asyncio_websockets, coverage
- [table](bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.10.4.md)
- [plot](bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 99.69%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- [table](bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.11.0.md)
- [plot](bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.07x slower \* (HPT: reliability of 99.99%, 1.01x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.12.0.md)
- [plot](bm-20230606-pythonperf2-x86_64-python-v3.11.4-3.11.4-d2340ef-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/5204077606)
- cpu model: missing
- platform: Windows-10-10.0.22621-SP0
- [raw results](bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef.json)

### vs. 3.10.4

- Geometric mean: 1.08x faster \* (HPT: reliability of 100.00%, 1.05x faster at 99th %ile)
- [table](bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef-vs-3.10.4.md)
- [plot](bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef-vs-3.11.0.md)
- [plot](bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.10x slower \* (HPT: reliability of 100.00%, 1.05x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef-vs-3.12.0.md)
- [plot](bm-20230606-pythonperf1-amd64-python-v3.11.4-3.11.4-d2340ef-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6961755333)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20230606-darwin-arm64-python-d2340ef25721b6a72d45-3.11.4-d2340ef.json)

### vs. 3.10.4

- Geometric mean: 1.19x faster (HPT: reliability of 100.00%, 1.15x faster at 99th %ile)
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20230606-darwin-arm64-python-d2340ef25721b6a72d45-3.11.4-d2340ef-vs-3.10.4.md)
- [plot](bm-20230606-darwin-arm64-python-d2340ef25721b6a72d45-3.11.4-d2340ef-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower (HPT: reliability of 99.97%, 1.00x slower at 99th %ile)
- [table](bm-20230606-darwin-arm64-python-d2340ef25721b6a72d45-3.11.4-d2340ef-vs-3.11.0.md)
- [plot](bm-20230606-darwin-arm64-python-d2340ef25721b6a72d45-3.11.4-d2340ef-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster (HPT: reliability of 99.89%, 1.00x faster at 99th %ile)
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20230606-darwin-arm64-python-d2340ef25721b6a72d45-3.11.4-d2340ef-vs-3.12.0.md)
- [plot](bm-20230606-darwin-arm64-python-d2340ef25721b6a72d45-3.11.4-d2340ef-vs-3.12.0.png)

