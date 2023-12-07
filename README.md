# Faster CPython Benchmark Infrastructure

🔒 [▶️ START A BENCHMARK RUN](../../actions/workflows/benchmark.yml)

## Results

Here are some recent and important revisions. 👉 [Complete list of results](RESULTS.md).

<!-- START table -->
[Most recent pystats on main (3faf8e5)](results/bm-20231125-3.13.0a2%2B-3faf8e5-PYTHON_UOPS/bm-20231125-azure-x86_64-python-3faf8e586d36e73faba1-3.13.0a2%2B-3faf8e5-pystats.md)

## linux x86_64 (linux)
| date | fork | ref | version | hash | vs. 3.10.4: | vs. 3.11.0: | vs. 3.12.0: | vs. base: |
| --- | --- | --- | --- | --- | ---: | ---: | ---: | ---: |
| [2023-12-04](results/bm-20231204-3.13.0a2%2B-e25f138) | mdboom | compact_in | 3.13.0a2+ | e25f138 | [1.33x faster \* (100% rel.)](results/bm-20231204-3.13.0a2%2B-e25f138/bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.10.4.md) | [1.05x faster \* (99% rel.)](results/bm-20231204-3.13.0a2%2B-e25f138/bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.11.0.md) | [1.02x faster \* (99% rel.)](results/bm-20231204-3.13.0a2%2B-e25f138/bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-3.12.0.md) | [1.00x faster (86% rel.)](results/bm-20231204-3.13.0a2%2B-e25f138/bm-20231204-linux-x86_64-mdboom-compact_ints2-3.13.0a2%2B-e25f138-vs-base.md) |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 | [1.33x faster \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.06x faster \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.02x faster \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.07x faster (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 2️⃣ | [1.24x faster \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.01x slower \* (98% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.04x slower \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.07x slower (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-linux-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-10-02](results/bm-20231002-3.12.0-0fb18b0) | python | v3.12.0 | 3.12.0 | 0fb18b0 | [1.29x faster (100% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.md) | [1.03x faster (55% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-linux-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.md) |  |  |
| [2022-10-24](results/bm-20221024-3.11.0-deaf509) | python | v3.11.0 | 3.11.0 | deaf509 | [1.26x faster (100% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509-vs-3.10.4.md) |  | [1.03x slower (55% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-linux-x86_64-python-v3.11.0-3.11.0-deaf509-vs-3.12.0.md) |  |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python | v3.10.4 | 3.10.4 | 9d38120 |  | [1.26x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.md) | [1.29x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-linux-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.md) |  |

## linux x86_64 (pythonperf2)
| date | fork | ref | version | hash | vs. 3.10.4: | vs. 3.11.0: | vs. 3.12.0: | vs. base: |
| --- | --- | --- | --- | --- | ---: | ---: | ---: | ---: |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 | [1.28x faster \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.06x faster \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.01x slower \* (63% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.10x faster (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 2️⃣ | [1.16x faster \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.04x slower \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.12x slower \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.10x slower (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf2-x86_64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-11-28](results/bm-20231128-3.13.0a2%2B-dfface9-JIT) | brandtbucher | justin | 3.13.0a2+ | dfface9 *️⃣ | [1.24x faster \* (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.10.4.md) | [1.02x faster \* (79% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.11.0.md) | [1.05x slower \* (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.12.0.md) | [1.04x slower (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-pythonperf2-x86_64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-base.md) |
| [2023-10-02](results/bm-20231002-3.12.0-0fb18b0) | python | v3.12.0 | 3.12.0 | 0fb18b0 | [1.30x faster (100% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.md) | [1.07x faster (100% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf2-x86_64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.md) |  |  |
| [2022-10-24](results/bm-20221024-3.11.0-deaf509) | python | v3.11.0 | 3.11.0 | deaf509 | [1.21x faster (100% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509-vs-3.10.4.md) |  | [1.07x slower (100% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf2-x86_64-python-v3.11.0-3.11.0-deaf509-vs-3.12.0.md) |  |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python | v3.10.4 | 3.10.4 | 9d38120 |  | [1.21x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.md) | [1.30x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf2-x86_64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.md) |  |

## windows amd64 (pythonperf1)
| date | fork | ref | version | hash | vs. 3.10.4: | vs. 3.11.0: | vs. 3.12.0: | vs. base: |
| --- | --- | --- | --- | --- | ---: | ---: | ---: | ---: |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 | [1.16x faster \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.03x faster \* (97% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.03x slower \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.03x faster (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 2️⃣ | [1.12x faster \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.00x faster \* (86% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.06x slower \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.03x slower (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-pythonperf1-amd64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-11-28](results/bm-20231128-3.13.0a2%2B-dfface9-JIT) | brandtbucher | justin | 3.13.0a2+ | dfface9 *️⃣ | [1.13x faster \* (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.10.4.md) | [1.01x faster \* (92% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.11.0.md) | [1.05x slower \* (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-pythonperf1-amd64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.12.0.md) |  |
| [2023-10-02](results/bm-20231002-3.12.0-0fb18b0) | python | v3.12.0 | 3.12.0 | 0fb18b0 | [1.19x faster (100% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0-vs-3.10.4.md) | [1.06x faster (100% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-pythonperf1-amd64-python-v3.12.0-3.12.0-0fb18b0-vs-3.11.0.md) |  |  |
| [2022-10-24](results/bm-20221024-3.11.0-deaf509) | python | v3.11.0 | 3.11.0 | deaf509 | [1.12x faster (100% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509-vs-3.10.4.md) |  | [1.06x slower (100% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-pythonperf1-amd64-python-v3.11.0-3.11.0-deaf509-vs-3.12.0.md) |  |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python | v3.10.4 | 3.10.4 | 9d38120 |  | [1.12x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120-vs-3.11.0.md) | [1.19x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-pythonperf1-amd64-python-v3.10.4-3.10.4-9d38120-vs-3.12.0.md) |  |

## darwin arm64 (darwin)
| date | fork | ref | version | hash | vs. 3.10.4: | vs. 3.11.0: | vs. 3.12.0: | vs. base: |
| --- | --- | --- | --- | --- | ---: | ---: | ---: | ---: |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 | [1.14x faster \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.05x slower \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.03x slower \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.06x faster (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-12-02](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS) | python | a9574c68f0 | 3.13.0a2+ | a9574c6 2️⃣ | [1.08x faster \* (99% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.10.4.md) | [1.11x slower \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.11.0.md) | [1.10x slower \* (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-3.12.0.md) | [1.06x slower (100% rel.)](results/bm-20231202-3.13.0a2%2B-a9574c6-PYTHON_UOPS/bm-20231202-darwin-arm64-python-a9574c68f04695eecd19-3.13.0a2%2B-a9574c6-vs-base.md) |
| [2023-11-28](results/bm-20231128-3.13.0a2%2B-dfface9-JIT) | brandtbucher | justin | 3.13.0a2+ | dfface9 *️⃣ | [1.12x faster \* (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.10.4.md) | [1.07x slower \* (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.11.0.md) | [1.05x slower \* (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-3.12.0.md) | [1.01x slower (100% rel.)](results/bm-20231128-3.13.0a2%2B-dfface9-JIT/bm-20231128-darwin-arm64-brandtbucher-justin-3.13.0a2%2B-dfface9-vs-base.md) |
| [2023-10-02](results/bm-20231002-3.12.0-0fb18b0) | python | 0fb18b02c8 | 3.12.0 | 0fb18b0 | [1.18x faster (100% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0-vs-3.10.4.md) | [1.02x slower (99% rel.)](results/bm-20231002-3.12.0-0fb18b0/bm-20231002-darwin-arm64-python-0fb18b02c8ad56299d6a-3.12.0-0fb18b0-vs-3.11.0.md) |  |  |
| [2022-10-24](results/bm-20221024-3.11.0-deaf509) | python | deaf509e8f | 3.11.0 | deaf509 | [1.20x faster (100% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509-vs-3.10.4.md) |  | [1.02x faster (99% rel.)](results/bm-20221024-3.11.0-deaf509/bm-20221024-darwin-arm64-python-deaf509e8fc6e0363bd6-3.11.0-deaf509-vs-3.12.0.md) |  |
| [2022-03-23](results/bm-20220323-3.10.4-9d38120) | python | 9d38120e33 | 3.10.4 | 9d38120 |  | [1.20x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120-vs-3.11.0.md) | [1.18x slower (100% rel.)](results/bm-20220323-3.10.4-9d38120/bm-20220323-darwin-arm64-python-9d38120e335357a3b294-3.10.4-9d38120-vs-3.12.0.md) |  |


<!-- END table -->

`*` indicates that the exact same versions of pyperformance was not used.

For the results above, the "faster/slower" result is a geometric mean of each of the benchmarks. The "reliability (rel)" number is the likelihood that the change is faster or slower based on the [Heirarchical Performance Testing (HPT)](#hpt) method.  For more details, visit each individual result's README.md.

![Longitudinal speed improvement](/longitudinal.png)

Improvement of the HPT score of key merged benchmarks, computed with `pyperf compare`.
The results have a resolution of 0.01 (1%).

- linux: Intel® Xeon® W-2255 CPU @ 3.70GHz, running Ubuntu 20.04 LTS, gcc 9.4.0
- linux2: 12th Gen Intel® Core™ i9-12900 @ 2.40 GHz, running Ubuntu 22.04 LTS, gcc 11.3.0
- macos: M1 arm64 Mac® Mini, running macOS 13.2.1, clang 1400.0.29.202
- windows: 12th Gen Intel® Core™ i9-12900 @ 2.40 GHz, running Windows 11 Pro (21H2, 22000.1696), MSVC v143

## Documentation

### Running benchmarks from the GitHub web UI

Visit the 🔒 [benchmark action](../../actions/workflows/benchmark.yml) and click the "Run Workflow" button.

The available parameters are:

- `fork`: The fork of CPython to benchmark.
  If benchmarking a pull request, this would normally be your GitHub username.
- `ref`: The branch, tag or commit SHA to benchmark.
  If a SHA, it must be the full SHA, since finding it by a prefix is not supported.
- `machine`: The machine to run on.
  One of `linux-amd64` (default), `windows-amd64`, `darwin-arm64` or `all`.
- `benchmark_base`: If checked, the base of the selected branch will also be benchmarked.
  The base is determined by running `git merge-base upstream/main $ref`.
- `pystats`: If checked, collect the pystats from running the benchmarks.

To watch the progress of the benchmark, select it from the 🔒 [benchmark action page](../../actions/workflows/benchmark.yml).
It may be canceled from there as well.
To show only your benchmark workflows, select your GitHub ID from the "Actor" dropdown.

When the benchmarking is complete, the results are published to this repository and will appear in the [master table](RESULTS.md).
Each set of benchmarks will have:

- The raw `.json` results from pyperformance.
- Comparisons against important reference releases, as well as the merge base of the branch if `benchmark_base` was selected.  These include
  - A markdown table produced by `pyperf compare_to`.
  - A set of "violin" plots showing the distribution of results for each benchmark.

The most convenient way to get results locally is to clone this repo and `git pull` from it.

### Running benchmarks from the GitHub CLI

To automate benchmarking runs, it may be more convenient to use the [GitHub CLI](https://cli.github.com/).
Once you have `gh` installed and configured, you can run benchmarks by cloning this repository and then from inside it:

```bash
$ gh workflow run benchmark.yml -f fork=me -f ref=my_branch
```

Any of the parameters described above are available at the commandline using the `-f key=value` syntax.

### Collecting Linux perf profiling data

To collect Linux perf sampling profile data for a benchmarking run, run the `_benchmark` action and check the `perf` checkbox.
Follow this by a run of the `_generate` action to regenerate the plots.

### Costs

We are limited to 2,000 compute minutes per month.


| Action | Minutes |
| -- | -- |
| Benchmarks | 7 minutes (most of the time is on self-hosted runners) |
| CI | 10 minutes |

To reduce CI usage, PRs that are only documentation changes should add the `[skip ci]` token to their commit message.

### Analysis changes

This is a changelog of changes that affect the derived data and results:

- 2023-02-09: The plots exclude benchmarks that aren't significant using the same algorithm used by the table results.
  These benchmarks do not contribute to the overall distribution at the top of the plot.

### Developer docs

For documentation about how this works, see the [bench_runner project](https://github.com/faster-cpython/bench_runner).

### HPT

Heirarchical performance testing (HPT) is a method introduced in this paper:

> T. Chen, Y. Chen, Q. Guo, O. Temam, Y. Wu and W. Hu,
"Statistical performance comparisons of computers,"
IEEE International Symposium on High-Performance Comp Architecture,
New Orleans, LA, USA, 2012, pp. 1-12,
doi: 10.1109/HPCA.2012.6169043.

From the abstract:

> In traditional performance comparisons, the impact of performance variability
is usually ignored (i.e., the means of performance measurements are compared
regardless of the variability), or in the few cases where it is factored in
using parametric confidence techniques, the confidence is either erroneously
computed based on the distribution of performance measurements (with the
implicit assumption that it obeys the normal law), instead of the distribution
of sample mean of performance measurements, or too few measurements are
considered for the distribution of sample mean to be normal. …  We propose a
non-parametric Hierarchical Performance Testing (HPT) framework for
performance comparison, which is significantly more practical than standard
parametric techniques because it does not require to collect a large number of
measurements in order to achieve a normal distribution of the sample mean.

For each result, we compute a reliability score, as well as the estimated
speedup at the 90th, 95th and 99th percentile.

**The inclusion of HPT scores is considered experimental as we learn about their
usefulness for decision-making.**
