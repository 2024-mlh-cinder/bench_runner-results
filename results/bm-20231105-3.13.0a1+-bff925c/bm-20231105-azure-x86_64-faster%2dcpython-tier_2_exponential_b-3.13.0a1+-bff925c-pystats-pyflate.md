
# Pystats results

- benchmark: pyflate
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 868,740,560 | 23.1% | 23.1% |  |
| LOAD_CONST | 267,174,880 | 7.1% | 30.2% |  |
| POP_JUMP_IF_FALSE | 235,057,000 | 6.2% | 36.4% |  |
| LOAD_ATTR_INSTANCE_VALUE | 234,904,820 | 6.2% | 42.7% |  |
| COMPARE_OP_INT | 163,808,320 | 4.4% | 47.0% |  |
| BINARY_OP | 149,260,740 | 4.0% | 51.0% |  |
| TO_BOOL_BOOL | 127,960,420 | 3.4% | 54.4% |  |
| SWAP | 125,252,860 | 3.3% | 57.7% |  |
| ENTER_EXECUTOR | 122,525,140 | 3.3% | 61.0% |  |
| LOAD_FAST_LOAD_FAST | 115,121,200 | 3.1% | 64.0% |  |
| COPY | 112,987,600 | 3.0% | 67.0% |  |
| STORE_FAST | 110,781,080 | 2.9% | 70.0% |  |
| BINARY_OP_SUBTRACT_INT | 98,444,040 | 2.6% | 72.6% |  |
| BINARY_OP_ADD_INT | 92,739,800 | 2.5% | 75.0% |  |
| RETURN_VALUE | 82,459,880 | 2.2% | 77.2% |  |
| POP_JUMP_IF_TRUE | 76,185,200 | 2.0% | 79.3% |  |
| RESUME_CHECK | 74,886,180 | 2.0% | 81.2% | 0.0% |
| CALL_PY_EXACT_ARGS | 74,743,940 | 2.0% | 83.2% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 67,304,660 | 1.8% | 85.0% |  |
| BINARY_SUBSCR_LIST_INT | 64,462,040 | 1.7% | 86.7% |  |
| CALL_LIST_APPEND | 61,344,700 | 1.6% | 88.4% |  |
| STORE_SUBSCR_LIST_INT | 53,789,400 | 1.4% | 89.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 46,712,820 | 1.2% | 91.0% |  |
| POP_TOP | 42,611,460 | 1.1% | 92.2% |  |
| LOAD_GLOBAL_BUILTIN | 35,906,520 | 1.0% | 93.1% |  |
| CALL_LEN | 29,801,940 | 0.8% | 93.9% |  |
| STORE_FAST_STORE_FAST | 26,987,580 | 0.7% | 94.6% |  |
| FOR_ITER | 26,922,820 | 0.7% | 95.3% |  |
| JUMP_BACKWARD | 26,922,080 | 0.7% | 96.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 26,917,300 | 0.7% | 96.8% |  |
| BINARY_SLICE | 24,352,640 | 0.6% | 97.4% |  |
| RETURN_CONST | 18,304,080 | 0.5% | 97.9% |  |
| UNARY_INVERT | 12,536,640 | 0.3% | 98.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 11,596,280 | 0.3% | 98.5% |  |
| LOAD_GLOBAL_MODULE | 7,445,440 | 0.2% | 98.7% |  |
| STORE_SLICE | 7,424,240 | 0.2% | 98.9% |  |
| NOP | 7,188,600 | 0.2% | 99.1% |  |
| JUMP_FORWARD | 6,697,040 | 0.2% | 99.3% |  |
| CALL_BUILTIN_O | 6,085,940 | 0.2% | 99.5% |  |
| LOAD_ATTR | 5,407,960 | 0.1% | 99.6% |  |
| TO_BOOL | 5,403,560 | 0.1% | 99.8% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,401,580 | 0.1% | 99.9% |  |
| BINARY_SUBSCR | 2,140,840 | 0.1% | 100.0% |  |
| TO_BOOL_INT | 629,920 | 0.0% | 100.0% |  |
| GET_ITER | 247,620 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 241,100 | 0.0% | 100.0% |  |
| BUILD_LIST | 82,140 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 71,120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 71,120 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 71,040 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 70,640 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 44,940 | 0.0% | 100.0% |  |
| CALL | 25,660 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 17,740 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 11,940 | 0.0% | 100.0% |  |
| LIST_APPEND | 11,600 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 10,080 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,400 | 0.0% | 100.0% |  |
| COMPARE_OP | 1,860 | 0.0% | 100.0% |  |
| STORE_ATTR | 1,000 | 0.0% | 100.0% |  |
| RESUME | 540 | 0.0% | 100.0% | 18.5% |
| PUSH_NULL | 480 | 0.0% | 100.0% |  |
| CALL_KW | 480 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 240 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 240 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 240 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 160 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 140 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 120 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP_STR | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_FALSE LOAD_FAST | 182,191,100 | 4.8% | 4.8% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 172,916,600 | 4.6% | 9.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 144,637,500 | 3.8% | 13.3% |
| LOAD_FAST TO_BOOL_BOOL | 127,960,220 | 3.4% | 16.7% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 127,939,960 | 3.4% | 20.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 93,046,080 | 2.5% | 22.5% |
| LOAD_FAST LOAD_CONST | 92,138,100 | 2.4% | 25.0% |
| STORE_FAST LOAD_FAST | 82,809,080 | 2.2% | 27.2% |
| LOAD_FAST COMPARE_OP_INT | 81,496,660 | 2.2% | 29.4% |
| LOAD_CONST BINARY_OP_ADD_INT | 77,260,100 | 2.1% | 31.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 74,743,940 | 2.0% | 33.4% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 70,762,240 | 1.9% | 35.3% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 67,268,180 | 1.8% | 37.1% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 60,177,380 | 1.6% | 38.7% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 58,897,800 | 1.6% | 40.2% |
| LOAD_CONST LOAD_FAST | 57,992,500 | 1.5% | 41.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 56,288,860 | 1.5% | 43.3% |
| ENTER_EXECUTOR LOAD_FAST | 55,452,660 | 1.5% | 44.7% |
| ENTER_EXECUTOR CALL_LIST_APPEND | 49,659,540 | 1.3% | 46.1% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 46,342,580 | 1.2% | 47.3% |
| LOAD_FAST BINARY_OP | 46,096,320 | 1.2% | 48.5% |
| LOAD_FAST COPY | 45,939,240 | 1.2% | 49.7% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 45,939,000 | 1.2% | 51.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 43,951,380 | 1.2% | 52.1% |
| BINARY_OP_ADD_INT SWAP | 43,104,360 | 1.1% | 53.3% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 40,941,900 | 1.1% | 54.4% |
| RESUME_CHECK LOAD_CONST | 38,803,100 | 1.0% | 55.4% |
| BINARY_OP LOAD_CONST | 38,558,020 | 1.0% | 56.4% |
| BINARY_OP_SUBTRACT_INT RETURN_VALUE | 38,557,940 | 1.0% | 57.4% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 38,221,400 | 1.0% | 58.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 35,895,680 | 1.0% | 59.4% |
| BINARY_OP LOAD_FAST | 33,522,860 | 0.9% | 60.3% |
| RETURN_VALUE STORE_FAST | 31,155,780 | 0.8% | 61.1% |
| POP_TOP LOAD_FAST | 30,094,120 | 0.8% | 61.9% |
| LOAD_FAST CALL_LEN | 29,801,760 | 0.8% | 62.7% |
| BINARY_OP_ADD_INT STORE_FAST | 29,202,380 | 0.8% | 63.5% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 27,221,920 | 0.7% | 64.2% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 26,916,840 | 0.7% | 64.9% |
| JUMP_BACKWARD FOR_ITER | 26,915,460 | 0.7% | 65.6% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 26,915,120 | 0.7% | 66.4% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 26,895,020 | 0.7% | 67.1% |
| COPY COPY | 26,894,720 | 0.7% | 67.8% |
| LOAD_FAST_LOAD_FAST COPY | 26,894,720 | 0.7% | 68.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST_LOAD_FAST | 26,894,720 | 0.7% | 69.2% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 26,894,720 | 0.7% | 69.9% |
| SWAP SWAP | 26,894,720 | 0.7% | 70.6% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 26,894,700 | 0.7% | 71.4% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 26,894,700 | 0.7% | 72.1% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 26,894,700 | 0.7% | 72.8% |
| COPY BINARY_SUBSCR_LIST_INT | 26,894,680 | 0.7% | 73.5% |
| SWAP STORE_SUBSCR_LIST_INT | 26,894,680 | 0.7% | 74.2% |
| BINARY_SUBSCR_LIST_INT STORE_SUBSCR_LIST_INT | 26,894,680 | 0.7% | 74.9% |
| BINARY_OP_SUBTRACT_INT BINARY_OP | 26,033,820 | 0.7% | 75.6% |
| RETURN_VALUE BINARY_OP | 26,021,320 | 0.7% | 76.3% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 24,407,600 | 0.6% | 77.0% |
| CALL_LEN COMPARE_OP_INT | 24,398,520 | 0.6% | 77.6% |
| LOAD_FAST LOAD_FAST | 24,383,320 | 0.6% | 78.3% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 24,327,160 | 0.6% | 78.9% |
| CALL_LIST_APPEND LOAD_FAST | 24,161,240 | 0.6% | 79.5% |
| LOAD_CONST COMPARE_OP_INT | 24,043,600 | 0.6% | 80.2% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 19,806,560 | 0.5% | 80.7% |
| RETURN_CONST POP_TOP | 18,232,880 | 0.5% | 81.2% |
| LOAD_FAST RETURN_VALUE | 18,009,980 | 0.5% | 81.7% |
| BINARY_OP SWAP | 17,939,120 | 0.5% | 82.1% |
| POP_JUMP_IF_TRUE LOAD_FAST | 17,265,400 | 0.5% | 82.6% |
| BINARY_OP STORE_FAST | 17,129,560 | 0.5% | 83.1% |
| RESUME_CHECK LOAD_FAST | 16,275,100 | 0.4% | 83.5% |
| BINARY_SLICE BINARY_OP | 14,848,480 | 0.4% | 83.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 14,635,740 | 0.4% | 84.3% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 13,894,380 | 0.4% | 84.6% |
| BINARY_OP RETURN_VALUE | 13,888,360 | 0.4% | 85.0% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 13,439,820 | 0.4% | 85.4% |
| SWAP COPY | 13,258,760 | 0.4% | 85.7% |
| COPY COMPARE_OP_INT | 13,258,520 | 0.4% | 86.1% |
| RETURN_VALUE LOAD_FAST | 12,607,200 | 0.3% | 86.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 12,556,020 | 0.3% | 86.7% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 12,551,980 | 0.3% | 87.1% |
| UNARY_INVERT BINARY_OP | 12,536,640 | 0.3% | 87.4% |
| BINARY_OP UNARY_INVERT | 12,536,640 | 0.3% | 87.7% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP | 12,536,620 | 0.3% | 88.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 12,349,360 | 0.3% | 88.4% |
| BINARY_OP_SUBTRACT_INT SWAP | 12,194,060 | 0.3% | 88.7% |
| STORE_FAST LOAD_CONST | 12,115,280 | 0.3% | 89.0% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 12,099,620 | 0.3% | 89.4% |
| LOAD_FAST SWAP | 11,862,620 | 0.3% | 89.7% |
| RETURN_VALUE POP_TOP | 11,861,920 | 0.3% | 90.0% |
| POP_TOP RETURN_VALUE | 11,861,680 | 0.3% | 90.3% |
| SWAP POP_TOP | 11,861,680 | 0.3% | 90.6% |
| LOAD_ATTR_INSTANCE_VALUE SWAP | 11,861,660 | 0.3% | 90.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 11,595,880 | 0.3% | 91.3% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 11,594,280 | 0.3% | 91.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 10,807,360 | 0.3% | 91.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 10,804,680 | 0.3% | 92.1% |
| LOAD_CONST BINARY_OP | 10,229,720 | 0.3% | 92.4% |
| BINARY_OP_ADD_INT BINARY_SLICE | 9,503,600 | 0.3% | 92.7% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 8,820,320 | 0.2% | 92.9% |
| LOAD_CONST LOAD_CONST | 7,431,120 | 0.2% | 93.1% |
| LOAD_CONST BINARY_SLICE | 7,424,720 | 0.2% | 93.3% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 7,424,560 | 0.2% | 93.5% |
| BINARY_SLICE LOAD_FAST | 7,424,240 | 0.2% | 93.7% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 9,503,600 | 39.0% |
| LOAD_CONST | 7,424,720 | 30.5% |
| LOAD_FAST | 7,424,240 | 30.5% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 14,848,480 | 61.0% |
| LOAD_FAST | 7,424,240 | 30.5% |
| CALL_LIST_APPEND | 712,680 | 2.9% |
| CALL_BUILTIN_O | 683,320 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 683,320 | 2.8% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,424,240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 7,424,240 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 70,560 | 99.9% |
| RESUME | 80 | 0.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,138,560 | 99.9% |
| BINARY_SUBSCR | 1,120 | 0.1% |
| LOAD_FAST_LOAD_FAST | 460 | 0.0% |
| LOAD_FAST | 420 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,396,140 | 65.2% |
| COMPARE_OP_INT | 742,440 | 34.7% |
| BINARY_SUBSCR | 1,120 | 0.1% |
| LOAD_FAST | 400 | 0.0% |
| CALL_LIST_APPEND | 340 | 0.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 71,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 71,120 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 238,780 | 96.4% |
| CALL_BUILTIN_CLASS | 7,960 | 3.2% |
| BINARY_SLICE | 480 | 0.2% |
| CALL | 180 | 0.1% |
| LOAD_FAST | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 239,300 | 96.6% |
| FOR_ITER_RANGE | 7,900 | 3.2% |
| FOR_ITER | 340 | 0.1% |
| LOAD_FAST_AND_CLEAR | 80 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 70,560 | 99.9% |
| RETURN_CONST | 80 | 0.1% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 7,186,940 | 100.0% |
| POP_JUMP_IF_FALSE | 1,100 | 0.0% |
| JUMP_BACKWARD | 300 | 0.0% |
| STORE_FAST | 160 | 0.0% |
| POP_TOP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,186,640 | 100.0% |
| LOAD_FAST | 1,560 | 0.0% |
| JUMP_BACKWARD | 320 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 18,232,880 | 42.8% |
| RETURN_VALUE | 11,861,920 | 27.8% |
| SWAP | 11,861,680 | 27.8% |
| POP_JUMP_IF_FALSE | 653,600 | 1.5% |
| CALL_KW | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,094,120 | 70.6% |
| RETURN_VALUE | 11,861,680 | 27.8% |
| JUMP_FORWARD | 654,240 | 1.5% |
| RETURN_CONST | 560 | 0.0% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 240 | 50.0% |
| LOAD_DEREF | 160 | 33.3% |
| LOAD_ATTR | 80 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 50.0% |
| LOAD_FAST | 160 | 33.3% |
| LOAD_FAST_CHECK | 80 | 16.7% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 38,557,940 | 46.8% |
| LOAD_FAST | 18,009,980 | 21.8% |
| BINARY_OP | 13,888,360 | 16.8% |
| POP_TOP | 11,861,680 | 14.4% |
| EXIT_INIT_CHECK | 71,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 31,155,780 | 37.8% |
| BINARY_OP | 26,021,320 | 31.6% |
| LOAD_FAST | 12,607,200 | 15.3% |
| POP_TOP | 11,861,920 | 14.4% |
| TO_BOOL_INT | 627,120 | 0.8% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 40 | 50.0% |
| BINARY_SUBSCR | 20 | 25.0% |
| BINARY_SUBSCR_LIST_INT | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 40 | 50.0% |
| JUMP_BACKWARD | 20 | 25.0% |
| LOAD_FAST_LOAD_FAST | 20 | 25.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,401,740 | 100.0% |
| TO_BOOL | 1,500 | 0.0% |
| RETURN_VALUE | 160 | 0.0% |
| BINARY_OP | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,401,560 | 100.0% |
| TO_BOOL | 1,500 | 0.0% |
| POP_JUMP_IF_FALSE | 240 | 0.0% |
| TO_BOOL_INT | 180 | 0.0% |
| TO_BOOL_BOOL | 80 | 0.0% |


</details>

### UNARY_INVERT

<details>
<summary> Successors and predecessors for UNARY_INVERT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 12,536,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 12,536,640 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 46,096,320 | 30.9% |
| BINARY_OP_SUBTRACT_INT | 26,033,820 | 17.4% |
| RETURN_VALUE | 26,021,320 | 17.4% |
| BINARY_SLICE | 14,848,480 | 9.9% |
| UNARY_INVERT | 12,536,640 | 8.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,558,020 | 25.8% |
| LOAD_FAST | 33,522,860 | 22.5% |
| SWAP | 17,939,120 | 12.0% |
| STORE_FAST | 17,129,560 | 11.5% |
| RETURN_VALUE | 13,888,360 | 9.3% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,040 | 86.5% |
| CALL_BUILTIN_CLASS | 8,680 | 10.6% |
| STORE_FAST | 720 | 0.9% |
| RESUME_CHECK | 580 | 0.7% |
| BUILD_TUPLE | 480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 80,220 | 97.7% |
| STORE_FAST | 1,600 | 1.9% |
| LOAD_CONST | 80 | 0.1% |
| LOAD_DEREF | 80 | 0.1% |
| SWAP | 80 | 0.1% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 70,540 | 99.3% |
| LOAD_CONST | 480 | 0.7% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 70,560 | 99.3% |
| BUILD_LIST | 480 | 0.7% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 20,100 | 78.3% |
| LOAD_FAST | 2,160 | 8.4% |
| LOAD_CONST | 1,080 | 4.2% |
| CALL | 520 | 2.0% |
| CALL_BUILTIN_FAST | 360 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 20,620 | 80.4% |
| CALL_PY_EXACT_ARGS | 860 | 3.4% |
| CALL_BUILTIN_CLASS | 740 | 2.9% |
| CALL | 520 | 2.0% |
| RESUME_CHECK | 440 | 1.7% |


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

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 840 | 45.2% |
| COPY | 240 | 12.9% |
| LOAD_FAST | 160 | 8.6% |
| CALL | 100 | 5.4% |
| LOAD_ATTR | 100 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 920 | 49.5% |
| COMPARE_OP_INT | 760 | 40.9% |
| POP_JUMP_IF_TRUE | 100 | 5.4% |
| COMPARE_OP | 60 | 3.2% |
| COMPARE_OP_STR | 20 | 1.1% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 45,939,240 | 40.7% |
| COPY | 26,894,720 | 23.8% |
| LOAD_FAST_LOAD_FAST | 26,894,720 | 23.8% |
| SWAP | 13,258,760 | 11.7% |
| RETURN_VALUE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 45,939,000 | 40.7% |
| COPY | 26,894,720 | 23.8% |
| BINARY_SUBSCR_LIST_INT | 26,894,680 | 23.8% |
| COMPARE_OP_INT | 13,258,520 | 11.7% |
| COMPARE_OP | 240 | 0.0% |


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
| POP_JUMP_IF_TRUE | 58,897,800 | 48.1% |
| CALL_LIST_APPEND | 27,221,920 | 22.2% |
| POP_JUMP_IF_FALSE | 24,327,160 | 19.9% |
| NOP | 7,186,640 | 5.9% |
| STORE_FAST | 4,815,120 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 55,452,660 | 45.3% |
| CALL_LIST_APPEND | 49,659,540 | 40.5% |
| POP_JUMP_IF_FALSE | 13,439,820 | 11.0% |
| LOAD_ATTR_INSTANCE_VALUE | 3,492,380 | 2.9% |
| LOAD_CONST | 237,280 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 26,915,460 | 100.0% |
| FOR_ITER | 6,940 | 0.0% |
| GET_ITER | 340 | 0.0% |
| SWAP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 26,915,120 | 100.0% |
| FOR_ITER | 6,940 | 0.0% |
| STORE_FAST | 320 | 0.0% |
| FOR_ITER_RANGE | 160 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 26,894,700 | 99.9% |
| LIST_APPEND | 11,600 | 0.0% |
| POP_JUMP_IF_TRUE | 9,840 | 0.0% |
| POP_JUMP_IF_FALSE | 1,920 | 0.0% |
| CALL_LIST_APPEND | 1,500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 26,915,460 | 100.0% |
| FOR_ITER_RANGE | 2,020 | 0.0% |
| FOR_ITER_LIST | 1,700 | 0.0% |
| LOAD_FAST | 1,280 | 0.0% |
| LOAD_FAST_LOAD_FAST | 900 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,358,820 | 80.0% |
| STORE_FAST | 683,440 | 10.2% |
| POP_TOP | 654,240 | 9.8% |
| ENTER_EXECUTOR | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,696,720 | 100.0% |
| BUILD_LIST | 80 | 0.0% |
| JUMP_BACKWARD | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 11,580 | 99.8% |
| CALL | 20 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 11,600 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 80 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,401,520 | 99.9% |
| LOAD_FAST | 3,080 | 0.1% |
| LOAD_ATTR | 1,680 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,000 | 0.0% |
| COPY | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,402,300 | 99.9% |
| LOAD_ATTR | 1,680 | 0.0% |
| LOAD_CONST | 980 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 820 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 640 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 92,138,100 | 34.5% |
| RESUME_CHECK | 38,803,100 | 14.5% |
| BINARY_OP | 38,558,020 | 14.4% |
| BINARY_SUBSCR_LIST_INT | 26,894,700 | 10.1% |
| POP_JUMP_IF_FALSE | 14,635,740 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 77,260,100 | 28.9% |
| BINARY_OP_SUBTRACT_INT | 60,177,380 | 22.5% |
| LOAD_FAST | 57,992,500 | 21.7% |
| COMPARE_OP_INT | 24,043,600 | 9.0% |
| BINARY_OP | 10,229,720 | 3.8% |


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
| POP_JUMP_IF_FALSE | 182,191,100 | 21.0% |
| LOAD_ATTR_INSTANCE_VALUE | 144,637,500 | 16.6% |
| STORE_FAST | 82,809,080 | 9.5% |
| LOAD_CONST | 57,992,500 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 56,288,860 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 172,916,600 | 19.9% |
| TO_BOOL_BOOL | 127,960,220 | 14.7% |
| LOAD_CONST | 92,138,100 | 10.6% |
| COMPARE_OP_INT | 81,496,660 | 9.4% |
| LOAD_ATTR_METHOD_WITH_VALUES | 67,268,180 | 7.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 50.0% |
| LOAD_FAST_AND_CLEAR | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 80 | 50.0% |
| SWAP | 80 | 50.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 40 | 50.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 50.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,894,720 | 23.4% |
| STORE_FAST_STORE_FAST | 26,894,720 | 23.4% |
| STORE_SUBSCR_LIST_INT | 26,894,700 | 23.4% |
| RESUME_CHECK | 19,806,560 | 17.2% |
| BINARY_OP | 7,424,240 | 6.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 26,895,020 | 23.4% |
| COPY | 26,894,720 | 23.4% |
| LOAD_FAST_LOAD_FAST | 26,894,720 | 23.4% |
| LOAD_ATTR_INSTANCE_VALUE | 12,556,020 | 10.9% |
| LOAD_FAST | 12,349,360 | 10.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 800 | 33.3% |
| LOAD_FAST | 320 | 13.3% |
| POP_JUMP_IF_FALSE | 240 | 10.0% |
| LOAD_ATTR | 100 | 4.2% |
| LOAD_GLOBAL | 100 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 740 | 30.8% |
| LOAD_FAST | 680 | 28.3% |
| LOAD_GLOBAL_MODULE | 460 | 19.2% |
| LOAD_FAST_LOAD_FAST | 160 | 6.7% |
| LOAD_ATTR | 120 | 5.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 127,939,960 | 54.4% |
| COMPARE_OP_INT | 93,046,080 | 39.6% |
| ENTER_EXECUTOR | 13,439,820 | 5.7% |
| TO_BOOL_INT | 629,920 | 0.3% |
| COMPARE_OP | 920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 182,191,100 | 77.5% |
| ENTER_EXECUTOR | 24,327,160 | 10.3% |
| LOAD_CONST | 14,635,740 | 6.2% |
| RETURN_CONST | 5,402,160 | 2.3% |
| JUMP_FORWARD | 5,358,820 | 2.3% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 70,762,240 | 92.9% |
| TO_BOOL | 5,401,560 | 7.1% |
| TO_BOOL_BOOL | 20,460 | 0.0% |
| ENTER_EXECUTOR | 840 | 0.0% |
| COMPARE_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 58,897,800 | 77.3% |
| LOAD_FAST | 17,265,400 | 22.7% |
| LOAD_GLOBAL_MODULE | 11,600 | 0.0% |
| JUMP_BACKWARD | 9,840 | 0.0% |
| POP_TOP | 480 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SLICE | 7,424,240 | 40.6% |
| STORE_ATTR_INSTANCE_VALUE | 5,476,060 | 29.9% |
| POP_JUMP_IF_FALSE | 5,402,160 | 29.5% |
| ENTER_EXECUTOR | 960 | 0.0% |
| POP_TOP | 560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 18,232,880 | 99.6% |
| EXIT_INIT_CHECK | 71,120 | 0.4% |
| INTERPRETER_EXIT | 80 | 0.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 560 | 56.0% |
| SWAP | 240 | 24.0% |
| LOAD_FAST_LOAD_FAST | 200 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 500 | 50.0% |
| LOAD_FAST | 220 | 22.0% |
| LOAD_CONST | 100 | 10.0% |
| RETURN_CONST | 100 | 10.0% |
| JUMP_BACKWARD | 40 | 4.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 31,155,780 | 28.1% |
| BINARY_OP_ADD_INT | 29,202,380 | 26.4% |
| BINARY_OP | 17,129,560 | 15.5% |
| LOAD_ATTR_INSTANCE_VALUE | 13,894,380 | 12.5% |
| BINARY_SUBSCR_LIST_INT | 7,424,560 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 82,809,080 | 74.8% |
| LOAD_CONST | 12,115,280 | 10.9% |
| LOAD_GLOBAL_MODULE | 7,187,780 | 6.5% |
| ENTER_EXECUTOR | 4,815,120 | 4.3% |
| LOAD_FAST_LOAD_FAST | 3,159,420 | 2.9% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 26,916,840 | 99.7% |
| LOAD_FAST_LOAD_FAST | 70,560 | 0.3% |
| UNPACK_SEQUENCE | 100 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,894,720 | 99.7% |
| LOAD_FAST | 92,780 | 0.3% |
| BUILD_LIST | 80 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 43,104,360 | 34.4% |
| SWAP | 26,894,720 | 21.5% |
| BINARY_OP | 17,939,120 | 14.3% |
| BINARY_OP_SUBTRACT_INT | 12,194,060 | 9.7% |
| LOAD_FAST | 11,862,620 | 9.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 46,342,580 | 37.0% |
| SWAP | 26,894,720 | 21.5% |
| STORE_SUBSCR_LIST_INT | 26,894,680 | 21.5% |
| COPY | 13,258,760 | 10.6% |
| POP_TOP | 11,861,680 | 9.5% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 100 | 41.7% |
| LOAD_CONST | 80 | 33.3% |
| BINARY_SUBSCR | 20 | 8.3% |
| BINARY_SUBSCR_LIST_INT | 20 | 8.3% |
| FOR_ITER_LIST | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 120 | 50.0% |
| STORE_FAST_STORE_FAST | 100 | 41.7% |
| LOAD_FAST | 20 | 8.3% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 420 | 77.8% |
| CACHE | 80 | 14.8% |
| CALL_FUNCTION_EX | 20 | 3.7% |
| COPY_FREE_VARS | 20 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 33.3% |
| LOAD_CONST | 100 | 18.5% |
| LOAD_GLOBAL | 100 | 18.5% |
| LOAD_FAST_LOAD_FAST | 80 | 14.8% |
| BUILD_LIST | 60 | 11.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 77,260,100 | 83.3% |
| CALL_BUILTIN_O | 5,402,340 | 5.8% |
| CALL_LEN | 5,402,340 | 5.8% |
| BINARY_OP | 4,675,020 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 43,104,360 | 46.5% |
| STORE_FAST | 29,202,380 | 31.5% |
| BINARY_SLICE | 9,503,600 | 10.2% |
| LOAD_CONST | 7,424,220 | 8.0% |
| BINARY_SUBSCR | 2,138,560 | 2.3% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 44,920 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 44,940 | 100.0% |


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
| LOAD_CONST | 60,177,380 | 61.1% |
| LOAD_FAST | 38,221,400 | 38.8% |
| BINARY_OP_SUBTRACT_INT | 44,920 | 0.0% |
| BINARY_OP | 300 | 0.0% |
| CALL_BUILTIN_O | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 38,557,940 | 39.2% |
| BINARY_OP | 26,033,820 | 26.4% |
| SWAP | 12,194,060 | 12.4% |
| COMPARE_OP_INT | 7,187,340 | 7.3% |
| BINARY_SUBSCR_LIST_INT | 7,186,920 | 7.3% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 26,895,020 | 41.7% |
| COPY | 26,894,680 | 41.7% |
| BINARY_OP_SUBTRACT_INT | 7,186,920 | 11.1% |
| LOAD_CONST | 3,010,760 | 4.7% |
| LOAD_FAST | 237,240 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 26,894,700 | 41.7% |
| STORE_SUBSCR_LIST_INT | 26,894,680 | 41.7% |
| STORE_FAST | 7,424,560 | 11.5% |
| LOAD_FAST | 2,773,100 | 4.3% |
| BINARY_SUBSCR_LIST_INT | 237,240 | 0.4% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 69,920 | 98.3% |
| LOAD_FAST_LOAD_FAST | 740 | 1.0% |
| LOAD_FAST | 380 | 0.5% |
| CALL | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 71,120 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 8,660 | 48.8% |
| LOAD_CONST | 6,400 | 36.1% |
| LOAD_FAST | 1,120 | 6.3% |
| CALL | 740 | 4.2% |
| LOAD_FAST_LOAD_FAST | 740 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 8,680 | 48.9% |
| GET_ITER | 7,960 | 44.9% |
| LOAD_FAST | 920 | 5.2% |
| STORE_FAST | 120 | 0.7% |
| CALL_BUILTIN_CLASS | 40 | 0.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,900 | 99.7% |
| CALL | 40 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 11,580 | 97.0% |
| CALL | 360 | 3.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 33.3% |
| LOAD_FAST | 80 | 33.3% |
| LOAD_CONST | 40 | 16.7% |
| LOAD_FAST_CHECK | 40 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 25.0% |
| LOAD_CONST | 60 | 25.0% |
| STORE_FAST | 60 | 25.0% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 16.7% |
| LOAD_ATTR | 20 | 8.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,402,340 | 88.8% |
| BINARY_SLICE | 683,320 | 11.2% |
| LOAD_CONST | 160 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 5,402,340 | 88.8% |
| LOAD_CONST | 683,340 | 11.2% |
| COMPARE_OP_INT | 80 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| BINARY_OP | 40 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 85.7% |
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
| LOAD_FAST | 29,801,760 | 100.0% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 24,398,520 | 81.9% |
| BINARY_OP_ADD_INT | 5,402,340 | 18.1% |
| STORE_FAST | 460 | 0.0% |
| LOAD_CONST | 360 | 0.0% |
| BINARY_OP | 80 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 49,659,540 | 81.0% |
| LOAD_FAST | 7,187,360 | 11.7% |
| BINARY_OP | 3,456,400 | 5.6% |
| BINARY_SLICE | 712,680 | 1.2% |
| BINARY_SUBSCR_LIST_INT | 237,240 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 27,221,920 | 44.4% |
| LOAD_FAST | 24,161,240 | 39.4% |
| NOP | 7,186,940 | 11.7% |
| LOAD_CONST | 2,773,100 | 4.5% |
| JUMP_BACKWARD | 1,500 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,401,500 | 100.0% |
| CALL | 40 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,401,520 | 100.0% |
| POP_TOP | 60 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 40 | 33.3% |
| LOAD_ATTR | 40 | 33.3% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 50.0% |
| LOAD_CONST | 60 | 50.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 43,951,380 | 58.8% |
| LOAD_ATTR_INSTANCE_VALUE | 12,099,620 | 16.2% |
| BINARY_OP_SUBTRACT_INT | 7,186,920 | 9.6% |
| LOAD_CONST | 5,850,720 | 7.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,402,460 | 7.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 74,743,940 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,496,660 | 49.8% |
| CALL_LEN | 24,398,520 | 14.9% |
| LOAD_CONST | 24,043,600 | 14.7% |
| COPY | 13,258,520 | 8.1% |
| LOAD_ATTR_INSTANCE_VALUE | 12,551,980 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 93,046,080 | 56.8% |
| POP_JUMP_IF_TRUE | 70,762,240 | 43.2% |


</details>

### COMPARE_OP_STR

<details>
<summary> Successors and predecessors for COMPARE_OP_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| COMPARE_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 239,300 | 99.3% |
| JUMP_BACKWARD | 1,700 | 0.7% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,300 | 99.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 740 | 0.3% |
| LOAD_FAST | 40 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 7,900 | 78.4% |
| JUMP_BACKWARD | 2,020 | 20.0% |
| FOR_ITER | 160 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,520 | 94.4% |
| LOAD_FAST_LOAD_FAST | 300 | 3.0% |
| LOAD_FAST | 140 | 1.4% |
| BUILD_LIST | 40 | 0.4% |
| LOAD_GLOBAL | 40 | 0.4% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 172,916,600 | 73.6% |
| COPY | 45,939,000 | 19.6% |
| LOAD_FAST_LOAD_FAST | 12,556,020 | 5.3% |
| ENTER_EXECUTOR | 3,492,380 | 1.5% |
| LOAD_ATTR | 820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 144,637,500 | 61.6% |
| STORE_FAST | 13,894,380 | 5.9% |
| COMPARE_OP_INT | 12,551,980 | 5.3% |
| BINARY_OP | 12,536,620 | 5.3% |
| CALL_PY_EXACT_ARGS | 12,099,620 | 5.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,595,880 | 100.0% |
| LOAD_ATTR | 280 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,594,280 | 100.0% |
| LOAD_GLOBAL_MODULE | 1,520 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,268,180 | 99.9% |
| LOAD_FAST_LOAD_FAST | 35,780 | 0.1% |
| LOAD_ATTR | 640 | 0.0% |
| ENTER_EXECUTOR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 56,288,860 | 83.6% |
| LOAD_CONST | 5,613,240 | 8.3% |
| CALL_PY_EXACT_ARGS | 5,402,460 | 8.0% |
| CALL | 100 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 66.7% |
| LOAD_ATTR | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,407,600 | 68.0% |
| LOAD_ATTR_INSTANCE_VALUE | 10,804,680 | 30.1% |
| BINARY_SLICE | 683,320 | 1.9% |
| STORE_FAST | 7,680 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,895,680 | 100.0% |
| LOAD_FAST_LOAD_FAST | 9,440 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,000 | 0.0% |
| LOAD_CONST | 300 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,187,780 | 96.5% |
| POP_JUMP_IF_FALSE | 237,360 | 3.2% |
| POP_JUMP_IF_TRUE | 11,600 | 0.2% |
| STORE_ATTR_INSTANCE_VALUE | 6,360 | 0.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,520 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,199,500 | 96.7% |
| LOAD_FAST_LOAD_FAST | 244,580 | 3.3% |
| LOAD_ATTR | 1,000 | 0.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| CALL_ISINSTANCE | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 74,743,940 | 99.8% |
| CALL_ALLOC_AND_ENTER_INIT | 71,120 | 0.1% |
| CACHE | 70,560 | 0.1% |
| CALL | 440 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,803,100 | 51.8% |
| LOAD_FAST_LOAD_FAST | 19,806,560 | 26.4% |
| LOAD_FAST | 16,275,100 | 21.7% |
| LOAD_GLOBAL_BUILTIN | 640 | 0.0% |
| BUILD_LIST | 580 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 46,342,580 | 99.2% |
| LOAD_FAST | 219,280 | 0.5% |
| LOAD_FAST_LOAD_FAST | 147,880 | 0.3% |
| ENTER_EXECUTOR | 2,580 | 0.0% |
| STORE_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,941,900 | 87.6% |
| RETURN_CONST | 5,476,060 | 11.7% |
| LOAD_CONST | 141,260 | 0.3% |
| ENTER_EXECUTOR | 76,080 | 0.2% |
| LOAD_FAST_LOAD_FAST | 70,540 | 0.2% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 26,894,680 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 26,894,680 | 50.0% |
| STORE_SUBSCR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 26,894,700 | 50.0% |
| LOAD_FAST_LOAD_FAST | 26,894,700 | 50.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 127,960,220 | 100.0% |
| CALL_ISINSTANCE | 120 | 0.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 127,939,960 | 100.0% |
| POP_JUMP_IF_TRUE | 20,460 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 627,120 | 99.6% |
| BINARY_OP | 1,800 | 0.3% |
| LOAD_FAST | 780 | 0.1% |
| TO_BOOL | 180 | 0.0% |
| CALL_LEN | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 629,920 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 26,915,120 | 100.0% |
| LOAD_CONST | 880 | 0.0% |
| FOR_ITER_LIST | 740 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 440 | 0.0% |
| UNPACK_SEQUENCE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 26,916,840 | 100.0% |
| LOAD_FAST | 460 | 0.0% |


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
|     deferred | 149,218,200 | 43.8% |
|          hit | 191,228,840 | 56.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 760 | 1.8% |
| Failure | 41,780 | 98.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| lshift | 17,720 | 42.4% |
| and int | 10,660 | 25.5% |
| rshift | 7,320 | 17.5% |
| add other | 4,480 | 10.7% |
| multiply different types | 1,260 | 3.0% |
| or | 340 | 0.8% |


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
|     deferred | 2,139,560 | 3.2% |
|          hit | 64,462,040 | 96.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 14.1% |
| Failure | 1,100 | 85.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| buffer int | 1,100 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 23,340 | 0.0% |
|          hit | 177,479,520 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,980 | 85.3% |
| Failure | 340 | 14.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| meth descr varargs | 180 | 52.9% |
| class no vectorcall | 100 | 29.4% |
| cfunc noargs | 60 | 17.6% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,020 | 0.0% |
|          hit | 163,808,380 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 780 | 92.9% |
| Failure | 60 | 7.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| big int | 60 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 26,915,620 | 99.0% |
|          hit | 251,180 | 0.9% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 3.6% |
| Failure | 6,940 | 96.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 6,940 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,404,480 | 1.7% |
|          hit | 313,806,000 | 98.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,820 | 52.3% |
| Failure | 1,660 | 47.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 1,540 | 92.8% |
| non overriding descriptor | 60 | 3.6% |
| metaclass attribute | 60 | 3.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,200 | 0.0% |
|          hit | 43,351,960 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 500 | 0.0% |
|          hit | 46,712,820 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 53,789,400 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,401,800 | 4.0% |
|          hit | 128,590,340 | 96.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 14.8% |
| Failure | 1,500 | 85.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 1,500 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 0.0% |
|          hit | 26,917,300 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 1,946,847,220 | 51.7% |
| Not specialized | 532,186,240 | 14.1% |
| Specialized hits | 1,285,283,860 | 34.1% |
| Specialized misses | 100 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 149,218,200 | 78.9% |
| FOR_ITER | 26,915,620 | 14.2% |
| LOAD_ATTR | 5,404,480 | 2.9% |
| TO_BOOL | 5,401,800 | 2.9% |
| BINARY_SUBSCR | 2,139,560 | 1.1% |
| CALL | 23,340 | 0.0% |
| LOAD_GLOBAL | 1,200 | 0.0% |
| COMPARE_OP | 1,020 | 0.0% |
| STORE_ATTR | 500 | 0.0% |
| UNPACK_SEQUENCE | 120 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 100 | 50.0% |
| RESUME_CHECK | 100 | 50.0% |
| CACHE | 0 | 0.0% |
| EXIT_INIT_CHECK | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 70,640 | 0.1% |
| Calls to Python functions inlined | 74,816,080 | 99.9% |
| Calls via PyEval_EvalFrame (total) | 70,640 | 0.1% |
| Calls via PyEval_EvalFrame (vector) | 70,640 | 0.1% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 70,640 | 0.1% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 70,560 | 0.1% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 127,978,100 | 170.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 37,375,180 | 10.4% |
| Frees to freelist | 37,380,820 |  |
| Allocations | 322,972,700 | 89.6% |
| Allocations to 512 bytes | 301,306,040 | 83.6% |
| Allocations to 4 kbytes | 21,664,900 | 6.0% |
| Allocations over 4 kbytes | 1,760 | 0.0% |
| Frees | 322,970,840 |  |
| New values | 80 |  |
| Interpreter increfs | 1,993,056,660 | 91.4% |
| Interpreter decrefs | 2,289,958,640 | 89.8% |
| Increfs | 186,652,624 | 8.6% |
| Decrefs | 260,286,793 | 10.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 5,414,765 |  |
| Method cache misses | 655 |  |
| Method cache collisions | 565 |  |
| Method cache dunder hits | 2,839 |  |
| Method cache dunder misses | 161 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 100 | 1,920 | 1,542,600 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 480 |  |
| Traces created | 420 | 87.5% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 220 | 45.8% |
| Trace too short | 60 | 12.5% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 122,525,140 |  |
| Uops executed | 5,010,603,620 | 40.89 |

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
| <= 32 | 80 | 19.0% |
| <= 64 | 100 | 23.8% |
| <= 128 | 240 | 57.1% |


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
| <= 16 | 20 | 4.8% |
| <= 32 | 60 | 14.3% |
| <= 64 | 120 | 28.6% |
| <= 128 | 220 | 52.4% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 72,360 | 0.1% |
| <= 16 | 243,320 | 0.2% |
| <= 32 | 70,282,980 | 57.4% |
| <= 64 | 26,317,800 | 21.5% |
| <= 128 | 25,543,720 | 20.8% |
| <= 256 | 49,900 | 0.0% |
| <= 512 | 13,240 | 0.0% |
| <= 1,024 | 1,180 | 0.0% |
| <= 2,048 | 560 | 0.0% |
| <= 4,096 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 1,136,887,880 | 22.7% | 22.7% |  |
| LOAD_FAST | 813,595,360 | 16.2% | 38.9% |  |
| _GUARD_TYPE_VERSION | 295,482,380 | 5.9% | 44.8% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 192,265,400 | 3.8% | 48.7% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 192,265,400 | 3.8% | 52.5% |  |
| STORE_FAST | 189,887,120 | 3.8% | 56.3% |  |
| _POP_JUMP_IF_TRUE | 162,442,940 | 3.2% | 59.5% |  |
| LOAD_CONST | 159,609,920 | 3.2% | 62.7% |  |
| COMPARE_OP_INT | 158,693,000 | 3.2% | 65.9% |  |
| _EXIT_TRACE | 122,525,140 | 2.4% | 68.3% |  |
| _GUARD_BOTH_INT | 111,326,640 | 2.2% | 70.6% |  |
| _POP_JUMP_IF_FALSE | 94,855,260 | 1.9% | 72.4% |  |
| _BINARY_SUBSCR | 75,216,140 | 1.5% | 73.9% |  |
| _ITER_CHECK_LIST | 70,661,840 | 1.4% | 75.4% |  |
| _IS_ITER_EXHAUSTED_LIST | 70,661,840 | 1.4% | 76.8% |  |
| _ITER_NEXT_LIST | 70,660,840 | 1.4% | 78.2% |  |
| _BINARY_OP_SUBTRACT_INT | 64,179,580 | 1.3% | 79.5% |  |
| RESUME_CHECK | 53,091,920 | 1.1% | 80.5% |  |
| _CHECK_PEP_523 | 53,091,920 | 1.1% | 81.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 53,091,920 | 1.1% | 82.6% |  |
| _CHECK_STACK_SPACE | 53,091,920 | 1.1% | 83.7% |  |
| _INIT_CALL_PY_EXACT_ARGS | 53,091,920 | 1.1% | 84.8% |  |
| _PUSH_FRAME | 53,091,920 | 1.1% | 85.8% |  |
| _SAVE_RETURN_OFFSET | 53,091,920 | 1.1% | 86.9% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 53,035,580 | 1.1% | 87.9% |  |
| _GUARD_KEYS_VERSION | 53,035,580 | 1.1% | 89.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 53,035,580 | 1.1% | 90.0% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 49,769,520 | 1.0% | 91.0% |  |
| _BINARY_OP_ADD_INT | 47,147,060 | 0.9% | 92.0% |  |
| _BINARY_OP | 44,685,600 | 0.9% | 92.9% |  |
| _ITER_CHECK_RANGE | 27,852,400 | 0.6% | 93.4% |  |
| _IS_ITER_EXHAUSTED_RANGE | 27,852,400 | 0.6% | 94.0% |  |
| _ITER_NEXT_RANGE | 27,710,960 | 0.6% | 94.5% |  |
| _POP_FRAME | 27,285,800 | 0.5% | 95.1% |  |
| BINARY_SUBSCR_LIST_INT | 26,894,340 | 0.5% | 95.6% |  |
| COPY | 24,984,560 | 0.5% | 96.1% |  |
| SWAP | 24,580,980 | 0.5% | 96.6% |  |
| _GUARD_GLOBALS_VERSION | 24,464,680 | 0.5% | 97.1% |  |
| _GUARD_BUILTINS_VERSION | 24,310,500 | 0.5% | 97.6% |  |
| _LOAD_GLOBAL_BUILTINS | 24,310,500 | 0.5% | 98.1% |  |
| CALL_LEN | 24,163,480 | 0.5% | 98.6% |  |
| POP_TOP | 22,907,640 | 0.5% | 99.0% |  |
| BINARY_SLICE | 22,765,200 | 0.5% | 99.5% |  |
| TO_BOOL_BOOL | 13,439,820 | 0.3% | 99.7% |  |
| GET_ITER | 11,757,740 | 0.2% | 100.0% |  |
| _JUMP_TO_TOP | 429,600 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 411,880 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 411,880 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_MODULE | 154,180 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 144,440 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 88,380 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 69,780 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 20,100 | 0.0% | 100.0% |  |
| BUILD_LIST | 10,500 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 3,420 | 0.0% | 100.0% |  |
| _TO_BOOL | 3,420 | 0.0% | 100.0% |  |
| _LOAD_ATTR | 3,420 | 0.0% | 100.0% |  |
| CALL_BUILTIN_O | 2,580 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 60 |
| CALL_ALLOC_AND_ENTER_INIT | 60 |
| CALL_LIST_APPEND | 40 |
| CALL | 20 |


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
