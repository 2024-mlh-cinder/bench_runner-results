# Results

- fork: python
- version: 3.10.4
- tier 2: False
- commit hash: [9d38120](https://github.com/python/cpython/commit/9d38120)
- commit date: 2022-03-23T20:12:04+00:00
- ref: 9d38120e335357a3b294, v3.10.4

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6627069943)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120.json)

### vs. 3.11.0

- Geometric mean: 1.26x slower (HPT: reliability of 100.00%, 1.20x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.md)
- [plot](bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.29x slower (HPT: reliability of 100.00%, 1.20x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- new benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.md)
- [plot](bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6627069943)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120.json)

### vs. 3.11.0

- Geometric mean: 1.21x slower (HPT: reliability of 100.00%, 1.15x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.md)
- [plot](bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.30x slower (HPT: reliability of 100.00%, 1.21x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.md)
- [plot](bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6627069943)
- cpu model: missing
- platform: Windows-10-10.0.22621-SP0
- [raw results](bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120.json)

### vs. 3.11.0

- Geometric mean: 1.12x slower (HPT: reliability of 100.00%, 1.08x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.md)
- [plot](bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.19x slower (HPT: reliability of 100.00%, 1.13x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.md)
- [plot](bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6961752972)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120.json)

### vs. 3.11.0

- Geometric mean: 1.20x slower (HPT: reliability of 100.00%, 1.16x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120-vs-3.11.0.md)
- [plot](bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.18x slower (HPT: reliability of 100.00%, 1.11x slower at 99th %ile)
- missing benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- new benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120-vs-3.12.0.md)
- [plot](bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120-vs-3.12.0.png)

