# Results

- fork: python
- version: 3.12.0
- tier 2: False
- commit hash: [0fb18b0](https://github.com/python/cpython/commit/0fb18b0)
- commit date: 2023-10-02T13:48:14+02:00
- ref: 0fb18b02c8ad56299d6a, v3.12.0

## linux x86_64 (linux)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6627079547)
- cpu model: Intel(R) Xeon(R) W-2255 CPU @ 3.70GHz
- platform: Linux-5.4.0-164-generic-x86_64-with-glibc2.31
- [raw results](bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0.json)

### vs. 3.10.4

- Geometric mean: 1.29x faster (HPT: reliability of 100.00%, 1.20x faster at 99th %ile)
- missing benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.md)
- [plot](bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.03x faster (HPT: reliability of 55.85%, 1.00x faster at 99th %ile)
- missing benchmarks: djangocms, flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.md)
- [plot](bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.png)

## linux x86_64 (pythonperf2)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6627079547)
- cpu model: 12th Gen Intel(R) Core(TM) i9-12900
- platform: Linux-5.15.0-76-generic-x86_64-with-glibc2.35
- [raw results](bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0.json)

### vs. 3.10.4

- Geometric mean: 1.30x faster (HPT: reliability of 100.00%, 1.21x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.md)
- [plot](bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.07x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.md)
- [plot](bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.png)

## windows amd64 (pythonperf1)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6627079547)
- cpu model: missing
- platform: Windows-11-10.0.22621-SP0
- [raw results](bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0.json)

### vs. 3.10.4

- Geometric mean: 1.19x faster (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.md)
- [plot](bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.06x faster (HPT: reliability of 100.00%, 1.02x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.md)
- [plot](bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.png)

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6961755895)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0.json)

### vs. 3.10.4

- Geometric mean: 1.18x faster (HPT: reliability of 100.00%, 1.11x faster at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0-vs-3.10.4.md)
- [plot](bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.02x slower (HPT: reliability of 99.93%, 1.01x slower at 99th %ile)
- missing benchmarks: flaskblogging, genshi_text, genshi_xml, html5lib, pylint, thrift
- [table](bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0-vs-3.11.0.md)
- [plot](bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0-vs-3.11.0.png)

