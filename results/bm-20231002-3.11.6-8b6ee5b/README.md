# Results

- fork: python
- version: 3.11.6
- tier 2: False
- commit hash: [8b6ee5b](https://github.com/python/cpython/commit/8b6ee5b)
- commit date: 2023-10-02T14:29:10+01:00
- ref: v3.11.6

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6411052916)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-122-generic-x86_64-with-glibc2.31
- [raw results](bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b.json)

### vs. 3.10.4

- Geometric mean: 1.25x faster \* (HPT: reliability of 100.00%, 1.19x faster at 99th %ile)
- missing benchmarks: asyncio_websockets, coverage
- [table](bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.10.4.md)
- [plot](bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 75.63%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- [table](bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.11.0.md)
- [plot](bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.04x slower \* (HPT: reliability of 78.64%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- new benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.12.0.md)
- [plot](bm-20231002-linux-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6411052916)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b.json)

### vs. 3.10.4

- Geometric mean: 1.22x faster \* (HPT: reliability of 100.00%, 1.16x faster at 99th %ile)
- missing benchmarks: asyncio_websockets, coverage
- [table](bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.10.4.md)
- [plot](bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 97.75%, 1.00x faster at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- [table](bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.11.0.md)
- [plot](bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 99.68%, 1.00x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg, asyncio_websockets, coverage
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.12.0.md)
- [plot](bm-20231002-pythonperf2-x86_64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6411052916)
- cpu model: missing
- platform: Windows-10-10.0.22621-SP0
- [raw results](bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b.json)

### vs. 3.10.4

- Geometric mean: 1.11x faster \* (HPT: reliability of 100.00%, 1.07x faster at 99th %ile)
- [table](bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.10.4.md)
- [plot](bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.01x slower \* (HPT: reliability of 95.23%, 1.00x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.11.0.md)
- [plot](bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.06x slower \* (HPT: reliability of 100.00%, 1.01x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.12.0.md)
- [plot](bm-20231002-pythonperf1-amd64-python-v3.11.6-3.11.6-8b6ee5b-vs-3.12.0.png)

