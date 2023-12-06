
# Pystats results

- benchmark: crypto_pyaes
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 58,265,280 | 19.5% | 19.5% |  |
| BINARY_OP | 44,466,320 | 14.9% | 34.4% |  |
| BINARY_SUBSCR_LIST_INT | 30,397,900 | 10.2% | 44.6% |  |
| LOAD_CONST | 25,127,640 | 8.4% | 53.0% |  |
| LOAD_FAST_LOAD_FAST | 17,737,420 | 5.9% | 58.9% |  |
| ENTER_EXECUTOR | 11,740,460 | 3.9% | 62.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 10,363,840 | 3.5% | 66.3% |  |
| STORE_FAST | 8,990,800 | 3.0% | 69.3% |  |
| STORE_SUBSCR_LIST_INT | 8,523,540 | 2.9% | 72.2% |  |
| BINARY_OP_ADD_INT | 5,759,800 | 1.9% | 74.1% |  |
| LOAD_GLOBAL_MODULE | 5,526,740 | 1.8% | 75.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,061,900 | 1.7% | 77.6% |  |
| PUSH_NULL | 4,142,400 | 1.4% | 79.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,918,500 | 1.3% | 80.3% |  |
| LIST_APPEND | 3,912,060 | 1.3% | 81.6% |  |
| STORE_FAST_STORE_FAST | 3,910,080 | 1.3% | 83.0% |  |
| JUMP_BACKWARD | 3,685,200 | 1.2% | 84.2% |  |
| FOR_ITER | 3,681,800 | 1.2% | 85.4% |  |
| CALL_LIST_APPEND | 3,681,200 | 1.2% | 86.6% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,679,980 | 1.2% | 87.9% |  |
| LOAD_GLOBAL_BUILTIN | 3,222,600 | 1.1% | 89.0% |  |
| RESUME_CHECK | 2,992,340 | 1.0% | 90.0% |  |
| POP_JUMP_IF_FALSE | 2,772,080 | 0.9% | 90.9% |  |
| RETURN_VALUE | 2,762,060 | 0.9% | 91.8% |  |
| CALL_PY_EXACT_ARGS | 2,761,720 | 0.9% | 92.7% |  |
| TO_BOOL | 2,071,460 | 0.7% | 93.4% |  |
| LOAD_ATTR_MODULE | 2,071,380 | 0.7% | 94.1% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,070,700 | 0.7% | 94.8% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,070,700 | 0.7% | 95.5% |  |
| CALL_TYPE_1 | 2,070,700 | 0.7% | 96.2% |  |
| SWAP | 1,159,880 | 0.4% | 96.6% |  |
| FOR_ITER_RANGE | 1,157,460 | 0.4% | 97.0% |  |
| GET_ITER | 1,153,920 | 0.4% | 97.4% |  |
| CALL_BUILTIN_CLASS | 1,153,480 | 0.4% | 97.8% |  |
| CALL_LEN | 1,151,280 | 0.4% | 98.1% |  |
| BUILD_LIST | 922,240 | 0.3% | 98.4% |  |
| COMPARE_OP_INT | 700,740 | 0.2% | 98.7% |  |
| COPY | 465,740 | 0.2% | 98.8% |  |
| BINARY_OP_SUBTRACT_INT | 464,600 | 0.2% | 99.0% |  |
| BINARY_OP_MULTIPLY_INT | 460,740 | 0.2% | 99.1% |  |
| LIST_EXTEND | 460,240 | 0.2% | 99.3% |  |
| POP_TOP | 459,980 | 0.2% | 99.5% |  |
| LOAD_FAST_AND_CLEAR | 231,040 | 0.1% | 99.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 231,040 | 0.1% | 99.6% |  |
| BINARY_SLICE | 230,880 | 0.1% | 99.7% |  |
| RETURN_CONST | 230,720 | 0.1% | 99.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 230,680 | 0.1% | 99.8% |  |
| LOAD_ATTR_PROPERTY | 230,060 | 0.1% | 99.9% |  |
| UNPACK_SEQUENCE_LIST | 230,060 | 0.1% | 100.0% |  |
| CALL | 2,940 | 0.0% | 100.0% |  |
| LOAD_ATTR | 2,560 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 2,160 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,960 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 1,600 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 1,600 | 0.0% | 100.0% |  |
| COMPARE_OP | 540 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 460 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 400 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 380 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 380 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 360 | 0.0% | 100.0% |  |
| STORE_ATTR | 320 | 0.0% | 100.0% |  |
| RESUME | 300 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| CONTAINS_OP | 160 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 160 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 140 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 140 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 140 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 140 | 0.0% | 100.0% |  |
| TO_BOOL_BOOL | 140 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 80 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_CONST BINARY_OP | 19,584,200 | 6.6% | 6.6% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 17,490,200 | 5.9% | 12.4% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 11,977,700 | 4.0% | 16.4% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 11,279,760 | 3.8% | 20.2% |
| BINARY_OP BINARY_SUBSCR_LIST_INT | 11,053,060 | 3.7% | 23.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 10,362,840 | 3.5% | 27.4% |
| BINARY_OP LOAD_FAST | 9,438,920 | 3.2% | 30.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 8,979,680 | 3.0% | 33.5% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 8,285,960 | 2.8% | 36.3% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 8,282,880 | 2.8% | 39.1% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 8,282,840 | 2.8% | 41.8% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 6,907,260 | 2.3% | 44.2% |
| ENTER_EXECUTOR BINARY_OP | 6,213,060 | 2.1% | 46.2% |
| BINARY_OP LOAD_CONST | 5,758,120 | 1.9% | 48.2% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 5,293,520 | 1.8% | 49.9% |
| BINARY_OP_ADD_INT LOAD_CONST | 5,293,140 | 1.8% | 51.7% |
| LOAD_FAST BINARY_OP_ADD_INT | 5,292,880 | 1.8% | 53.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 5,061,900 | 1.7% | 55.2% |
| PUSH_NULL LOAD_FAST | 4,141,600 | 1.4% | 56.6% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,918,140 | 1.3% | 57.9% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_FAST_LOAD_FAST | 3,913,520 | 1.3% | 59.2% |
| BINARY_OP LIST_APPEND | 3,911,660 | 1.3% | 60.5% |
| LIST_APPEND JUMP_BACKWARD | 3,681,600 | 1.2% | 61.7% |
| JUMP_BACKWARD FOR_ITER | 3,680,260 | 1.2% | 63.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 3,680,000 | 1.2% | 64.2% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 3,680,000 | 1.2% | 65.4% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 3,679,980 | 1.2% | 66.6% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 3,679,960 | 1.2% | 67.9% |
| LOAD_FAST LOAD_CONST | 3,242,360 | 1.1% | 69.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 3,222,640 | 1.1% | 70.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,222,320 | 1.1% | 71.1% |
| STORE_FAST LOAD_FAST | 2,998,700 | 1.0% | 72.1% |
| BINARY_OP CALL_LIST_APPEND | 2,991,120 | 1.0% | 73.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 2,991,120 | 1.0% | 74.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 2,761,720 | 0.9% | 75.0% |
| CALL_LIST_APPEND LOAD_FAST | 2,760,900 | 0.9% | 76.0% |
| BINARY_OP BINARY_OP | 2,557,860 | 0.9% | 76.8% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,301,240 | 0.8% | 77.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,071,380 | 0.7% | 78.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 2,071,280 | 0.7% | 79.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,071,240 | 0.7% | 79.7% |
| RETURN_VALUE STORE_FAST | 2,071,040 | 0.7% | 80.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,071,000 | 0.7% | 81.1% |
| TO_BOOL POP_JUMP_IF_FALSE | 2,070,740 | 0.7% | 81.8% |
| LOAD_FAST PUSH_NULL | 2,070,720 | 0.7% | 82.5% |
| LOAD_FAST TO_BOOL | 2,070,720 | 0.7% | 83.1% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 2,070,700 | 0.7% | 83.8% |
| CALL_METHOD_DESCRIPTOR_NOARGS RETURN_VALUE | 2,070,700 | 0.7% | 84.5% |
| CALL_TYPE_1 STORE_FAST | 2,070,700 | 0.7% | 85.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 2,070,680 | 0.7% | 85.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_NOARGS | 2,070,680 | 0.7% | 86.6% |
| LOAD_FAST CALL_TYPE_1 | 2,070,680 | 0.7% | 87.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_NO_DICT | 2,070,680 | 0.7% | 88.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 2,070,660 | 0.7% | 88.7% |
| STORE_FAST ENTER_EXECUTOR | 2,070,400 | 0.7% | 89.4% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 1,841,860 | 0.6% | 90.0% |
| FOR_ITER_RANGE STORE_FAST | 1,156,520 | 0.4% | 90.4% |
| CALL_BUILTIN_CLASS GET_ITER | 1,153,420 | 0.4% | 90.8% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 1,151,400 | 0.4% | 91.2% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 923,080 | 0.3% | 91.5% |
| GET_ITER FOR_ITER_RANGE | 922,840 | 0.3% | 91.8% |
| LOAD_CONST LOAD_CONST | 921,360 | 0.3% | 92.1% |
| LOAD_FAST BINARY_OP | 921,140 | 0.3% | 92.4% |
| LOAD_CONST CALL_BUILTIN_CLASS | 921,080 | 0.3% | 92.7% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 920,000 | 0.3% | 93.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 700,600 | 0.2% | 93.2% |
| LOAD_CONST LOAD_FAST | 693,440 | 0.2% | 93.5% |
| CALL_LEN LOAD_CONST | 690,740 | 0.2% | 93.7% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 690,240 | 0.2% | 93.9% |
| ENTER_EXECUTOR CALL_LIST_APPEND | 690,000 | 0.2% | 94.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 466,620 | 0.2% | 94.3% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 465,280 | 0.2% | 94.5% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 462,260 | 0.2% | 94.6% |
| LOAD_CONST COMPARE_OP_INT | 461,940 | 0.2% | 94.8% |
| BUILD_LIST LOAD_CONST | 461,040 | 0.2% | 94.9% |
| LOAD_FAST CALL_LEN | 460,800 | 0.2% | 95.1% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 460,600 | 0.2% | 95.3% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 460,560 | 0.2% | 95.4% |
| RESUME_CHECK LOAD_FAST | 460,420 | 0.2% | 95.6% |
| LOAD_CONST LIST_EXTEND | 460,160 | 0.2% | 95.7% |
| STORE_FAST BUILD_LIST | 460,160 | 0.2% | 95.9% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 233,820 | 0.1% | 95.9% |
| SWAP SWAP | 233,780 | 0.1% | 96.0% |
| SWAP STORE_SUBSCR_LIST_INT | 233,660 | 0.1% | 96.1% |
| BINARY_OP SWAP | 233,500 | 0.1% | 96.2% |
| COPY COPY | 232,640 | 0.1% | 96.3% |
| COPY BINARY_SUBSCR_LIST_INT | 232,520 | 0.1% | 96.3% |
| LOAD_FAST CALL_BUILTIN_CLASS | 231,880 | 0.1% | 96.4% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 231,400 | 0.1% | 96.5% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 231,080 | 0.1% | 96.6% |
| ENTER_EXECUTOR LOAD_FAST | 231,020 | 0.1% | 96.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 231,000 | 0.1% | 96.7% |
| GET_ITER LOAD_FAST_AND_CLEAR | 230,880 | 0.1% | 96.8% |
| BUILD_LIST SWAP | 230,880 | 0.1% | 96.9% |
| LOAD_FAST_AND_CLEAR SWAP | 230,880 | 0.1% | 97.0% |
| SWAP BUILD_LIST | 230,880 | 0.1% | 97.0% |
| LOAD_FAST COPY | 230,840 | 0.1% | 97.1% |
| BINARY_OP_ADD_INT BINARY_SLICE | 230,680 | 0.1% | 97.2% |
| SWAP FOR_ITER_RANGE | 230,620 | 0.1% | 97.3% |
| STORE_FAST STORE_FAST | 230,560 | 0.1% | 97.3% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 230,680 | 99.9% |
| LOAD_CONST | 160 | 0.1% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 230,280 | 99.7% |
| CALL_BUILTIN_FAST | 360 | 0.2% |
| LOAD_FAST | 160 | 0.1% |
| CALL | 80 | 0.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 280 | 77.8% |
| RESUME | 80 | 22.2% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,040 | 48.1% |
| LOAD_FAST | 400 | 18.5% |
| LOAD_CONST | 240 | 11.1% |
| LOAD_FAST_LOAD_FAST | 240 | 11.1% |
| COPY | 120 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 1,040 | 48.1% |
| LOAD_FAST | 400 | 18.5% |
| LOAD_CONST | 340 | 15.7% |
| BINARY_OP | 220 | 10.2% |
| STORE_FAST | 80 | 3.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 140 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,153,420 | 100.0% |
| CALL | 420 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 922,840 | 80.0% |
| LOAD_FAST_AND_CLEAR | 230,880 | 20.0% |
| FOR_ITER | 200 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 340 | 94.4% |
| RETURN_VALUE | 20 | 5.6% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 230,240 | 50.1% |
| POP_JUMP_IF_FALSE | 229,580 | 49.9% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 230,040 | 50.0% |
| RETURN_CONST | 229,580 | 49.9% |
| LOAD_FAST | 220 | 0.0% |
| NOP | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,071,380 | 50.0% |
| LOAD_FAST | 2,070,720 | 50.0% |
| LOAD_DEREF | 160 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,141,600 | 100.0% |
| LOAD_CONST | 400 | 0.0% |
| CALL | 240 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,070,700 | 75.0% |
| BINARY_OP | 230,320 | 8.3% |
| LOAD_FAST | 230,320 | 8.3% |
| LOAD_ATTR_INSTANCE_VALUE | 230,060 | 8.3% |
| RETURN_VALUE | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,071,040 | 75.0% |
| LOAD_FAST | 230,460 | 8.3% |
| BINARY_OP | 230,080 | 8.3% |
| CALL_PY_EXACT_ARGS | 230,040 | 8.3% |
| RETURN_VALUE | 320 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 160 | 40.0% |
| SWAP | 120 | 30.0% |
| LOAD_FAST | 80 | 20.0% |
| LOAD_FAST_LOAD_FAST | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 200 | 50.0% |
| JUMP_BACKWARD | 100 | 25.0% |
| LOAD_FAST | 60 | 15.0% |
| LOAD_FAST_LOAD_FAST | 40 | 10.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,070,720 | 100.0% |
| TO_BOOL | 700 | 0.0% |
| CALL | 20 | 0.0% |
| CALL_ISINSTANCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,070,740 | 100.0% |
| TO_BOOL | 700 | 0.0% |
| TO_BOOL_BOOL | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 19,584,200 | 44.0% |
| BINARY_SUBSCR_LIST_INT | 11,279,760 | 25.4% |
| ENTER_EXECUTOR | 6,213,060 | 14.0% |
| LOAD_FAST_LOAD_FAST | 3,680,000 | 8.3% |
| BINARY_OP | 2,557,860 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 11,053,060 | 24.9% |
| LOAD_FAST | 9,438,920 | 21.2% |
| LOAD_FAST_LOAD_FAST | 8,282,880 | 18.6% |
| LOAD_CONST | 5,758,120 | 12.9% |
| LIST_APPEND | 3,911,660 | 8.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 460,160 | 49.9% |
| SWAP | 230,880 | 25.0% |
| ENTER_EXECUTOR | 230,060 | 24.9% |
| LOAD_CONST | 880 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 461,040 | 50.0% |
| SWAP | 230,880 | 25.0% |
| STORE_FAST | 230,080 | 24.9% |
| LOAD_FAST | 160 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,040 | 35.4% |
| LOAD_CONST | 280 | 9.5% |
| LOAD_GLOBAL_MODULE | 280 | 9.5% |
| PUSH_NULL | 240 | 8.2% |
| CALL | 220 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 460 | 15.6% |
| GET_ITER | 420 | 14.3% |
| CALL_BUILTIN_CLASS | 280 | 9.5% |
| CALL_LEN | 240 | 8.2% |
| CALL | 220 | 7.5% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 50.0% |
| LOAD_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 50.0% |
| RESUME_CHECK | 60 | 37.5% |
| RESUME | 20 | 12.5% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 240 | 44.4% |
| LOAD_CONST | 120 | 22.2% |
| LOAD_GLOBAL_MODULE | 60 | 11.1% |
| CALL | 40 | 7.4% |
| CALL_LEN | 40 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 280 | 51.9% |
| COMPARE_OP_INT | 220 | 40.7% |
| COMPARE_OP | 20 | 3.7% |
| EXTENDED_ARG | 20 | 3.7% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 160 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 232,640 | 50.0% |
| LOAD_FAST | 230,840 | 49.6% |
| LOAD_FAST_LOAD_FAST | 1,800 | 0.4% |
| LOAD_CONST | 460 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 232,640 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 232,520 | 49.9% |
| LOAD_ATTR_INSTANCE_VALUE | 420 | 0.1% |
| BINARY_SUBSCR | 120 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 75.0% |
| RESUME | 20 | 25.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 8,285,960 | 70.6% |
| STORE_FAST | 2,070,400 | 17.6% |
| CALL_LIST_APPEND | 920,000 | 7.8% |
| POP_JUMP_IF_FALSE | 231,080 | 2.0% |
| LIST_APPEND | 230,460 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 6,213,060 | 52.9% |
| LOAD_GLOBAL_MODULE | 2,070,660 | 17.6% |
| LOAD_FAST_LOAD_FAST | 1,841,860 | 15.7% |
| CALL_LIST_APPEND | 690,000 | 5.9% |
| LOAD_FAST | 231,020 | 2.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,440 | 90.0% |
| COMPARE_OP_INT | 140 | 8.8% |
| COMPARE_OP | 20 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,120 | 70.0% |
| JUMP_BACKWARD | 320 | 20.0% |
| POP_JUMP_IF_FALSE | 160 | 10.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,680,260 | 100.0% |
| FOR_ITER | 1,080 | 0.0% |
| SWAP | 260 | 0.0% |
| GET_ITER | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,679,960 | 100.0% |
| FOR_ITER | 1,080 | 0.0% |
| STORE_FAST | 420 | 0.0% |
| FOR_ITER_RANGE | 280 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 3,681,600 | 99.9% |
| STORE_SUBSCR_LIST_INT | 1,500 | 0.0% |
| POP_JUMP_IF_FALSE | 640 | 0.0% |
| STORE_FAST | 400 | 0.0% |
| EXTENDED_ARG | 320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 3,680,260 | 99.9% |
| FOR_ITER_RANGE | 3,720 | 0.1% |
| LOAD_FAST_LOAD_FAST | 600 | 0.0% |
| ENTER_EXECUTOR | 320 | 0.0% |
| LOAD_FAST | 300 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,500 | 93.8% |
| FOR_ITER_RANGE | 100 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,600 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 3,911,660 | 100.0% |
| BINARY_SUBSCR_TUPLE_INT | 380 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 3,681,600 | 94.1% |
| ENTER_EXECUTOR | 230,460 | 5.9% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 460,160 | 100.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 230,080 | 50.0% |
| UNPACK_SEQUENCE_LIST | 230,040 | 50.0% |
| CALL_INTRINSIC_1 | 80 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,840 | 71.9% |
| LOAD_GLOBAL_MODULE | 300 | 11.7% |
| LOAD_GLOBAL | 180 | 7.0% |
| LOAD_ATTR | 100 | 3.9% |
| LOAD_ATTR_INSTANCE_VALUE | 60 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 540 | 21.1% |
| LOAD_ATTR_INSTANCE_VALUE | 460 | 18.0% |
| LOAD_FAST_LOAD_FAST | 360 | 14.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 360 | 14.1% |
| PUSH_NULL | 140 | 5.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 6,907,260 | 27.5% |
| BINARY_OP | 5,758,120 | 22.9% |
| BINARY_OP_ADD_INT | 5,293,140 | 21.1% |
| LOAD_FAST | 3,242,360 | 12.9% |
| LOAD_GLOBAL_MODULE | 923,080 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 19,584,200 | 77.9% |
| BINARY_SUBSCR_LIST_INT | 1,151,400 | 4.6% |
| LOAD_CONST | 921,360 | 3.7% |
| CALL_BUILTIN_CLASS | 921,080 | 3.7% |
| LOAD_FAST | 693,440 | 2.8% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 33.3% |
| BUILD_LIST | 80 | 33.3% |
| RESUME_CHECK | 60 | 25.0% |
| RESUME | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 66.7% |
| LIST_EXTEND | 80 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 11,977,700 | 20.6% |
| BINARY_OP | 9,438,920 | 16.2% |
| LOAD_ATTR_INSTANCE_VALUE | 8,979,680 | 15.4% |
| LOAD_FAST_LOAD_FAST | 5,293,520 | 9.1% |
| LOAD_ATTR_METHOD_NO_DICT | 5,061,900 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 17,490,200 | 30.0% |
| LOAD_ATTR_INSTANCE_VALUE | 10,362,840 | 17.8% |
| BINARY_OP_ADD_INT | 5,292,880 | 9.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,918,140 | 6.7% |
| LOAD_CONST | 3,242,360 | 5.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 230,880 | 99.9% |
| LOAD_FAST_AND_CLEAR | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 230,880 | 99.9% |
| LOAD_FAST_AND_CLEAR | 160 | 0.1% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 50.0% |
| LOAD_GLOBAL_MODULE | 40 | 50.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 8,282,880 | 46.7% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 3,913,520 | 22.1% |
| STORE_FAST_STORE_FAST | 3,680,000 | 20.7% |
| ENTER_EXECUTOR | 1,841,860 | 10.4% |
| STORE_FAST | 6,020 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 8,282,840 | 46.7% |
| LOAD_FAST | 5,293,520 | 29.8% |
| BINARY_OP | 3,680,000 | 20.7% |
| BINARY_SUBSCR_LIST_INT | 465,280 | 2.6% |
| COMPARE_OP_INT | 8,420 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 640 | 32.7% |
| RESUME | 220 | 11.2% |
| RESUME_CHECK | 220 | 11.2% |
| POP_JUMP_IF_FALSE | 160 | 8.2% |
| PUSH_NULL | 80 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 620 | 31.6% |
| LOAD_FAST | 440 | 22.4% |
| LOAD_GLOBAL_BUILTIN | 360 | 18.4% |
| LOAD_CONST | 200 | 10.2% |
| LOAD_ATTR | 180 | 9.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 2,070,740 | 74.7% |
| COMPARE_OP_INT | 700,600 | 25.3% |
| COMPARE_OP | 280 | 0.0% |
| CONTAINS_OP | 160 | 0.0% |
| EXTENDED_ARG | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,071,280 | 74.7% |
| ENTER_EXECUTOR | 231,080 | 8.3% |
| LOAD_GLOBAL_BUILTIN | 230,040 | 8.3% |
| POP_TOP | 229,580 | 8.3% |
| LOAD_FAST_LOAD_FAST | 5,260 | 0.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 75.0% |
| LOAD_GLOBAL | 40 | 25.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 229,580 | 99.5% |
| ENTER_EXECUTOR | 640 | 0.3% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 0.2% |
| STORE_ATTR | 60 | 0.0% |
| FOR_ITER_RANGE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 230,240 | 99.8% |
| INTERPRETER_EXIT | 340 | 0.1% |
| EXIT_INIT_CHECK | 140 | 0.1% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 75.0% |
| LOAD_FAST_LOAD_FAST | 40 | 12.5% |
| SWAP | 40 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 160 | 50.0% |
| RETURN_CONST | 60 | 18.8% |
| LOAD_FAST | 40 | 12.5% |
| LOAD_GLOBAL | 40 | 12.5% |
| BUILD_LIST | 20 | 6.2% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,071,040 | 23.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 2,070,700 | 23.0% |
| CALL_TYPE_1 | 2,070,700 | 23.0% |
| FOR_ITER_RANGE | 1,156,520 | 12.9% |
| BINARY_SUBSCR_LIST_INT | 231,400 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,222,640 | 35.8% |
| LOAD_FAST | 2,998,700 | 33.4% |
| ENTER_EXECUTOR | 2,070,400 | 23.0% |
| BUILD_LIST | 460,160 | 5.1% |
| STORE_FAST | 230,560 | 2.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 440 | 95.7% |
| FOR_ITER | 20 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 3,679,980 | 94.1% |
| UNPACK_SEQUENCE_LIST | 230,060 | 5.9% |
| UNPACK_SEQUENCE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,680,000 | 94.1% |
| STORE_FAST | 230,080 | 5.9% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 233,780 | 20.2% |
| BINARY_OP | 233,500 | 20.1% |
| BUILD_LIST | 230,880 | 19.9% |
| LOAD_FAST_AND_CLEAR | 230,880 | 19.9% |
| BINARY_OP_ADD_INT | 230,360 | 19.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 233,780 | 20.2% |
| STORE_SUBSCR_LIST_INT | 233,660 | 20.1% |
| BUILD_LIST | 230,880 | 19.9% |
| FOR_ITER_RANGE | 230,620 | 19.9% |
| STORE_ATTR_INSTANCE_VALUE | 230,040 | 19.8% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40 | 50.0% |
| LIST_EXTEND | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 40 | 50.0% |
| UNPACK_SEQUENCE_LIST | 20 | 25.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 25.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 180 | 60.0% |
| CACHE | 80 | 26.7% |
| CALL_FUNCTION_EX | 20 | 6.7% |
| COPY_FREE_VARS | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 220 | 73.3% |
| LOAD_FAST | 60 | 20.0% |
| LOAD_DEREF | 20 | 6.7% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,292,880 | 91.9% |
| LOAD_CONST | 466,620 | 8.1% |
| BINARY_OP | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,293,140 | 91.9% |
| BINARY_SLICE | 230,680 | 4.0% |
| SWAP | 230,360 | 4.0% |
| STORE_FAST | 5,340 | 0.1% |
| CALL_BUILTIN_CLASS | 240 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460,560 | 100.0% |
| LOAD_CONST | 120 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 460,600 | 100.0% |
| STORE_FAST | 140 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 462,260 | 99.5% |
| BINARY_OP | 2,340 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 230,060 | 49.5% |
| STORE_FAST | 230,060 | 49.5% |
| BINARY_SUBSCR_LIST_INT | 4,400 | 0.9% |
| BINARY_SUBSCR | 80 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 120 | 85.7% |
| BINARY_SUBSCR | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 140 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,490,200 | 57.5% |
| BINARY_OP | 11,053,060 | 36.4% |
| LOAD_CONST | 1,151,400 | 3.8% |
| LOAD_FAST_LOAD_FAST | 465,280 | 1.5% |
| COPY | 232,520 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,977,700 | 39.4% |
| BINARY_OP | 11,279,760 | 37.1% |
| LOAD_CONST | 6,907,260 | 22.7% |
| STORE_FAST | 231,400 | 0.8% |
| LOAD_FAST_LOAD_FAST | 1,780 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 360 | 94.7% |
| BINARY_SUBSCR | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 380 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 85.7% |
| CALL | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 140 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 921,080 | 79.9% |
| LOAD_FAST | 231,880 | 20.1% |
| CALL | 280 | 0.0% |
| BINARY_OP_ADD_INT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,153,420 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 360 | 94.7% |
| CALL | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 380 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 85.7% |
| CALL | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 120 | 85.7% |
| TO_BOOL | 20 | 14.3% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 690,240 | 60.0% |
| LOAD_FAST | 460,800 | 40.0% |
| CALL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 690,740 | 60.0% |
| COMPARE_OP_INT | 230,160 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 230,160 | 20.0% |
| BINARY_SUBSCR_DICT | 120 | 0.0% |
| COMPARE_OP | 40 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,991,120 | 81.3% |
| ENTER_EXECUTOR | 690,000 | 18.7% |
| CALL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,760,900 | 75.0% |
| ENTER_EXECUTOR | 920,000 | 25.0% |
| JUMP_BACKWARD | 300 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,070,680 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,070,700 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,070,680 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,070,700 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,071,000 | 75.0% |
| BINARY_SLICE | 230,280 | 8.3% |
| RETURN_VALUE | 230,040 | 8.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 230,040 | 8.3% |
| CALL | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,761,720 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,070,680 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,070,700 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 461,940 | 65.9% |
| CALL_LEN | 230,160 | 32.8% |
| LOAD_FAST_LOAD_FAST | 8,420 | 1.2% |
| COMPARE_OP | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 700,600 | 100.0% |
| EXTENDED_ARG | 140 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 922,840 | 79.7% |
| SWAP | 230,620 | 19.9% |
| JUMP_BACKWARD | 3,720 | 0.3% |
| FOR_ITER | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,156,520 | 99.9% |
| STORE_FAST_LOAD_FAST | 440 | 0.0% |
| JUMP_FORWARD | 100 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |
| JUMP_BACKWARD | 60 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,362,840 | 100.0% |
| LOAD_ATTR | 460 | 0.0% |
| COPY | 420 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,979,680 | 86.6% |
| CALL_LEN | 690,240 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 230,460 | 2.2% |
| LOAD_CONST | 230,300 | 2.2% |
| RETURN_VALUE | 230,060 | 2.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,991,120 | 59.1% |
| LOAD_GLOBAL_MODULE | 2,070,680 | 40.9% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,061,900 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 230,460 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 230,040 | 99.7% |
| LOAD_FAST | 560 | 0.2% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| CALL | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,071,240 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,071,380 | 100.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,918,140 | 100.0% |
| LOAD_ATTR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,913,520 | 99.9% |
| LOAD_FAST | 4,840 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 229,620 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 420 | 0.2% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 230,060 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,301,240 | 71.4% |
| CALL_LEN | 230,160 | 7.1% |
| POP_TOP | 230,040 | 7.1% |
| POP_JUMP_IF_FALSE | 230,040 | 7.1% |
| LOAD_GLOBAL_MODULE | 230,040 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,222,320 | 100.0% |
| LOAD_FAST_LOAD_FAST | 140 | 0.0% |
| CALL_ISINSTANCE | 120 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,222,640 | 58.3% |
| ENTER_EXECUTOR | 2,070,660 | 37.5% |
| RESUME_CHECK | 230,400 | 4.2% |
| POP_JUMP_IF_FALSE | 1,800 | 0.0% |
| LOAD_GLOBAL | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,071,240 | 37.5% |
| LOAD_ATTR_METHOD_NO_DICT | 2,070,680 | 37.5% |
| LOAD_CONST | 923,080 | 16.7% |
| LOAD_FAST | 231,000 | 4.2% |
| LOAD_GLOBAL_BUILTIN | 230,040 | 4.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,761,720 | 92.3% |
| LOAD_ATTR_PROPERTY | 230,060 | 7.7% |
| CACHE | 280 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 140 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,301,240 | 76.9% |
| LOAD_FAST | 460,420 | 15.4% |
| LOAD_GLOBAL_MODULE | 230,400 | 7.7% |
| LOAD_GLOBAL | 220 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 230,040 | 99.6% |
| LOAD_FAST | 720 | 0.3% |
| STORE_ATTR | 160 | 0.1% |
| LOAD_FAST_LOAD_FAST | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 230,200 | 99.6% |
| RETURN_CONST | 420 | 0.2% |
| LOAD_GLOBAL_MODULE | 240 | 0.1% |
| BUILD_LIST | 140 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,282,840 | 97.2% |
| SWAP | 233,660 | 2.7% |
| BINARY_OP | 4,440 | 0.1% |
| LOAD_FAST | 2,400 | 0.0% |
| STORE_SUBSCR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 8,285,960 | 97.2% |
| LOAD_FAST | 233,820 | 2.7% |
| LOAD_FAST_LOAD_FAST | 2,260 | 0.0% |
| JUMP_BACKWARD | 1,500 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 120 | 85.7% |
| TO_BOOL | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 140 | 100.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 230,040 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 230,060 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 3,679,960 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 3,679,980 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 44,443,760 | 86.9% |
|          hit | 6,685,200 | 13.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 2.2% |
| Failure | 22,060 | 97.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| xor | 8,460 | 38.3% |
| and int | 4,980 | 22.6% |
| rshift | 3,360 | 15.2% |
| remainder | 2,820 | 12.8% |
| lshift | 1,000 | 4.5% |
| or | 720 | 3.3% |
| floor divide | 360 | 1.6% |
| add other | 240 | 1.1% |
| multiply different types | 120 | 0.5% |


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,080 | 0.0% |
|          hit | 30,398,420 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,080 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,800 | 0.0% |
|          hit | 14,960,440 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 920 | 80.7% |
| Failure | 220 | 19.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| wrong number arguments | 80 | 36.4% |
| class no vectorcall | 80 | 36.4% |
| cfunc noargs | 60 | 27.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 300 | 0.0% |
|          hit | 700,740 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 220 | 91.7% |
| Failure | 20 | 8.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 20 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 3,680,440 | 76.1% |
|          hit | 1,157,460 | 23.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 20.6% |
| Failure | 1,080 | 79.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| zip | 1,080 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,340 | 0.0% |
|          hit | 21,876,360 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,180 | 96.7% |
| Failure | 40 | 3.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 40 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 980 | 0.0% |
|          hit | 8,749,340 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 980 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 160 | 0.1% |
|          hit | 231,040 | 99.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 8,523,540 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,070,740 | 100.0% |
|          hit | 140 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 2.8% |
| Failure | 700 | 97.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 700 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 3,910,040 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 145,362,500 | 48.7% |
| Not specialized | 53,233,660 | 17.8% |
| Specialized hits | 100,185,060 | 33.5% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 44,443,760 | 88.5% |
| FOR_ITER | 3,680,440 | 7.3% |
| TO_BOOL | 2,070,740 | 4.1% |
| CALL | 1,800 | 0.0% |
| LOAD_ATTR | 1,340 | 0.0% |
| BINARY_SUBSCR | 1,080 | 0.0% |
| LOAD_GLOBAL | 980 | 0.0% |
| COMPARE_OP | 300 | 0.0% |
| STORE_SUBSCR | 200 | 0.0% |
| STORE_ATTR | 160 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 360 | 0.0% |
| Calls to Python functions inlined | 2,992,280 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 360 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 360 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 360 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 20 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 3,682,060 | 123.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 3,920,600 | 3.9% |
| Frees to freelist | 3,921,260 |  |
| Allocations | 97,179,040 | 96.1% |
| Allocations to 512 bytes | 97,178,640 | 96.1% |
| Allocations to 4 kbytes | 240 | 0.0% |
| Allocations over 4 kbytes | 160 | 0.0% |
| Frees | 97,638,849 |  |
| New values | 340 |  |
| Interpreter increfs | 287,965,860 | 79.6% |
| Interpreter decrefs | 368,676,300 | 80.1% |
| Increfs | 73,855,072 | 20.4% |
| Decrefs | 91,705,746 | 19.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 2,037 |  |
| Method cache misses | 503 |  |
| Method cache collisions | 374 |  |
| Method cache dunder hits | 858 |  |
| Method cache dunder misses | 102 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 340 |  |
| Traces created | 320 | 94.1% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 20 | 5.9% |
| Trace too long | 80 | 23.5% |
| Trace too short | 20 | 5.9% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 11,740,460 |  |
| Uops executed | 938,378,360 | 79.93 |

### Trace length histogram

<details>
<summary> trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 80 | 25.0% |
| <= 64 | 60 | 18.8% |
| <= 128 | 180 | 56.2% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 100 | 31.2% |
| <= 64 | 80 | 25.0% |
| <= 128 | 140 | 43.8% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,530,980 | 21.6% |
| <= 16 | 0 | 0.0% |
| <= 32 | 229,620 | 2.0% |
| <= 64 | 692,000 | 5.9% |
| <= 128 | 8,054,540 | 68.6% |
| <= 256 | 1,820 | 0.0% |
| <= 512 | 231,500 | 2.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 264,871,020 | 28.2% | 28.2% |  |
| LOAD_FAST | 127,859,980 | 13.6% | 41.9% |  |
| _BINARY_OP | 101,321,060 | 10.8% | 52.6% |  |
| LOAD_CONST | 90,965,240 | 9.7% | 62.3% |  |
| BINARY_SUBSCR_LIST_INT | 67,706,020 | 7.2% | 69.6% |  |
| _GUARD_TYPE_VERSION | 35,933,260 | 3.8% | 73.4% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 33,154,760 | 3.5% | 76.9% |  |
| _GUARD_KEYS_VERSION | 33,154,760 | 3.5% | 80.5% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 32,925,140 | 3.5% | 84.0% |  |
| _GUARD_BOTH_INT | 24,405,100 | 2.6% | 86.6% |  |
| _BINARY_OP_ADD_INT | 23,016,220 | 2.5% | 89.0% |  |
| _ITER_CHECK_RANGE | 14,051,860 | 1.5% | 90.5% |  |
| _IS_ITER_EXHAUSTED_RANGE | 14,051,860 | 1.5% | 92.0% |  |
| _POP_JUMP_IF_TRUE | 14,051,860 | 1.5% | 93.5% |  |
| STORE_FAST | 11,992,660 | 1.3% | 94.8% |  |
| _EXIT_TRACE | 11,740,460 | 1.3% | 96.0% |  |
| _ITER_NEXT_RANGE | 11,287,440 | 1.2% | 97.2% |  |
| POP_TOP | 2,764,920 | 0.3% | 97.5% |  |
| _GUARD_GLOBALS_VERSION | 2,531,600 | 0.3% | 97.8% |  |
| _LOAD_GLOBAL_MODULE | 2,531,600 | 0.3% | 98.1% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 2,088,500 | 0.2% | 98.3% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 2,088,500 | 0.2% | 98.5% |  |
| GET_ITER | 1,841,360 | 0.2% | 98.7% |  |
| CALL_BUILTIN_CLASS | 1,841,360 | 0.2% | 98.9% |  |
| _BINARY_OP_MULTIPLY_INT | 1,380,000 | 0.1% | 99.1% |  |
| _JUMP_TO_TOP | 705,300 | 0.1% | 99.1% |  |
| LIST_APPEND | 694,980 | 0.1% | 99.2% |  |
| BINARY_SLICE | 690,240 | 0.1% | 99.3% |  |
| RESUME_CHECK | 690,000 | 0.1% | 99.4% |  |
| _POP_FRAME | 690,000 | 0.1% | 99.4% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 690,000 | 0.1% | 99.5% |  |
| _CHECK_PEP_523 | 690,000 | 0.1% | 99.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 690,000 | 0.1% | 99.7% |  |
| _CHECK_STACK_SPACE | 690,000 | 0.1% | 99.7% |  |
| _INIT_CALL_PY_EXACT_ARGS | 690,000 | 0.1% | 99.8% |  |
| _PUSH_FRAME | 690,000 | 0.1% | 99.9% |  |
| _SAVE_RETURN_OFFSET | 690,000 | 0.1% | 99.9% |  |
| COPY | 238,900 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 229,620 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 17,060 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 8,880 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 8,000 | 0.0% | 100.0% |  |
| _POP_JUMP_IF_FALSE | 8,000 | 0.0% | 100.0% |  |
| SWAP | 7,000 | 0.0% | 100.0% |  |
| BUILD_LIST | 2,640 | 0.0% | 100.0% |  |
| PUSH_NULL | 240 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 240 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 240 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 20 |
| CALL_LIST_APPEND | 20 |
| LOAD_ATTR_PROPERTY | 20 |


</details>


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-11-08
