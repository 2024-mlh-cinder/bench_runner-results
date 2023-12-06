# Results

- fork: python
- version: 3.12.0+
- tier 2: False
- commit hash: [9c583f3](https://github.com/python/cpython/commit/9c583f3)
- commit date: 2023-11-04T15:55:55-04:00
- ref: 3.12

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6758056367)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231104-linux-x86_64-python-3.12-3.12.0%2B-9c583f3.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-linux-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.md)
- [plot](bm-20231104-linux-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster \* (HPT: reliability of 64.97%, 1.00x faster at 99th %ile)
- missing benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231104-linux-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.md)
- [plot](bm-20231104-linux-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 84.07%, 1.00x faster at 99th %ile)
- [table](bm-20231104-linux-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.md)
- [plot](bm-20231104-linux-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6758056367)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0%2B-9c583f3.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster \* (HPT: reliability of 100.00%, 1.22x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.md)
- [plot](bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.md)
- [plot](bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.00x faster \* (HPT: reliability of 99.58%, 1.00x faster at 99th %ile)
- [table](bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.md)
- [plot](bm-20231104-pythonperf2-x86_64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6758056367)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231104-pythonperf1-amd64-python-3.12-3.12.0%2B-9c583f3.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster \* (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-pythonperf1-amd64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.md)
- [plot](bm-20231104-pythonperf1-amd64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster \* (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231104-pythonperf1-amd64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.md)
- [plot](bm-20231104-pythonperf1-amd64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.01x faster \* (HPT: reliability of 92.96%, 1.00x faster at 99th %ile)
- [table](bm-20231104-pythonperf1-amd64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.md)
- [plot](bm-20231104-pythonperf1-amd64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6758056367)
- cpu model: missing
- platform: macOS-13.6-arm64-arm-64bit
- [raw results](bm-20231104-darwin-arm64-python-3.12-3.12.0%2B-9c583f3.json)

### vs. 3.10.4

- Geometric mean: 1.20x faster (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231104-darwin-arm64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.md)
- [plot](bm-20231104-darwin-arm64-python-3.12-3.12.0%2B-9c583f3-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.00x faster (HPT: reliability of 95.95%, 1.00x slower at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231104-darwin-arm64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.md)
- [plot](bm-20231104-darwin-arm64-python-3.12-3.12.0%2B-9c583f3-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.02x faster (HPT: reliability of 99.97%, 1.00x faster at 99th %ile)
- [table](bm-20231104-darwin-arm64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.md)
- [plot](bm-20231104-darwin-arm64-python-3.12-3.12.0%2B-9c583f3-vs-3.12.0.png)

