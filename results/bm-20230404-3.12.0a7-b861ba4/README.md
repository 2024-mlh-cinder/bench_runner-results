# Results

- fork: python
- version: 3.12.0a7
- tier 2: False
- commit hash: [b861ba4](https://github.com/python/cpython/commit/b861ba4)
- commit date: 2023-04-04T17:52:42+02:00
- commit merge base: [89e6a3446184925ee7f17cd0d948c7784a88b8d7](https://github.com/python/cpython/commit/89e6a3446184925ee7f17cd0d948c7784a88b8d7)
- ref: b861ba4a8247af8159df

## darwin arm64 (darwin)

- [GitHub Action run](https://github.com/faster-cpython/benchmarking/actions/runs/6961755026)
- cpu model: missing
- platform: macOS-14.1.1-arm64-arm-64bit
- [raw results](bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4.json)

### vs. 3.10.4

- Geometric mean: 1.15x faster (HPT: reliability of 100.00%, 1.13x faster at 99th %ile)
- missing benchmarks: aiohttp, coverage, flaskblogging, gunicorn, pylint
- new benchmarks: async_tree_cpu_io_mixed_tg, async_tree_io_tg, async_tree_memoization_tg, async_tree_none_tg
- [table](bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4-vs-3.10.4.md)
- [plot](bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4-vs-3.10.4.png)

### vs. 3.11.0

- Geometric mean: 1.05x slower (HPT: reliability of 100.00%, 1.02x slower at 99th %ile)
- missing benchmarks: aiohttp, coverage, flaskblogging, gunicorn, pylint
- [table](bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4-vs-3.11.0.md)
- [plot](bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4-vs-3.11.0.png)

### vs. 3.12.0

- Geometric mean: 1.03x slower (HPT: reliability of 93.96%, 1.00x slower at 99th %ile)
- missing benchmarks: aiohttp, coverage, gunicorn
- new benchmarks: genshi_text, genshi_xml, html5lib, thrift
- [table](bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4-vs-3.12.0.md)
- [plot](bm-20230404-darwin-arm64-python-b861ba4a8247af8159df-3.12.0a7-b861ba4-vs-3.12.0.png)

