
# Pystats results

- benchmark: pyflate
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 937,003,160 | 25.6% | 25.6% |  |
| POP_JUMP_IF_FALSE | 305,397,740 | 8.3% | 33.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 285,651,020 | 7.8% | 41.7% |  |
| LOAD_CONST | 253,784,820 | 6.9% | 48.6% |  |
| COMPARE_OP_INT | 175,432,580 | 4.8% | 53.4% |  |
| BINARY_OP | 163,149,360 | 4.5% | 57.8% |  |
| TO_BOOL_BOOL | 141,380,480 | 3.9% | 61.7% |  |
| STORE_FAST | 138,186,200 | 3.8% | 65.5% |  |
| ENTER_EXECUTOR | 122,532,080 | 3.3% | 68.8% |  |
| BINARY_OP_SUBTRACT_INT | 112,415,540 | 3.1% | 71.9% |  |
| RETURN_VALUE | 109,528,480 | 3.0% | 74.9% |  |
| RESUME_CHECK | 86,511,160 | 2.4% | 77.2% | 0.0% |
| CALL_PY_EXACT_ARGS | 86,368,920 | 2.4% | 79.6% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 78,936,620 | 2.2% | 81.7% |  |
| POP_JUMP_IF_TRUE | 76,178,260 | 2.1% | 83.8% |  |
| SWAP | 71,812,000 | 2.0% | 85.8% |  |
| BINARY_OP_ADD_INT | 65,848,160 | 1.8% | 87.6% |  |
| CALL_LIST_APPEND | 61,344,700 | 1.7% | 89.2% |  |
| COPY | 59,939,940 | 1.6% | 90.9% |  |
| STORE_ATTR_INSTANCE_VALUE | 47,057,300 | 1.3% | 92.2% |  |
| LOAD_FAST_LOAD_FAST | 46,190,780 | 1.3% | 93.4% |  |
| POP_TOP | 42,611,480 | 1.2% | 94.6% |  |
| LOAD_GLOBAL_BUILTIN | 35,909,200 | 1.0% | 95.6% |  |
| CALL_LEN | 29,801,980 | 0.8% | 96.4% |  |
| BINARY_SLICE | 24,352,660 | 0.7% | 97.0% |  |
| RETURN_CONST | 18,304,080 | 0.5% | 97.5% |  |
| UNARY_INVERT | 12,536,640 | 0.3% | 97.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 11,596,380 | 0.3% | 98.2% |  |
| BINARY_SUBSCR_LIST_INT | 10,673,420 | 0.3% | 98.5% |  |
| LOAD_GLOBAL_MODULE | 7,435,680 | 0.2% | 98.7% |  |
| STORE_SLICE | 7,424,240 | 0.2% | 98.9% |  |
| NOP | 7,188,640 | 0.2% | 99.1% |  |
| JUMP_FORWARD | 6,697,060 | 0.2% | 99.3% |  |
| CALL_BUILTIN_O | 6,088,520 | 0.2% | 99.4% |  |
| LOAD_ATTR | 5,408,820 | 0.1% | 99.6% |  |
| TO_BOOL | 5,404,420 | 0.1% | 99.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 5,402,440 | 0.1% | 99.9% |  |
| BINARY_SUBSCR | 2,140,900 | 0.1% | 99.9% |  |
| TO_BOOL_INT | 629,980 | 0.0% | 100.0% |  |
| GET_ITER | 247,700 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 242,260 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 215,800 | 0.0% | 100.0% |  |
| BUILD_LIST | 82,160 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 73,520 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 71,120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 71,120 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 71,040 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 70,640 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 44,940 | 0.0% | 100.0% |  |
| CALL | 25,660 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 17,800 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 8,320 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 2,400 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 2,120 | 0.0% | 100.0% |  |
| COMPARE_OP | 1,860 | 0.0% | 100.0% |  |
| FOR_ITER | 1,780 | 0.0% | 100.0% |  |
| LIST_APPEND | 1,760 | 0.0% | 100.0% |  |
| STORE_ATTR | 1,000 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 760 | 0.0% | 100.0% |  |
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
| POP_JUMP_IF_FALSE LOAD_FAST | 252,288,360 | 6.9% | 6.9% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 214,787,700 | 5.9% | 12.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 158,689,940 | 4.3% | 17.1% |
| LOAD_FAST TO_BOOL_BOOL | 141,380,280 | 3.9% | 20.9% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 141,379,780 | 3.9% | 24.8% |
| STORE_FAST LOAD_FAST | 110,085,620 | 3.0% | 27.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 104,670,280 | 2.9% | 30.6% |
| LOAD_FAST LOAD_CONST | 92,138,360 | 2.5% | 33.2% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 86,368,920 | 2.4% | 35.5% |
| LOAD_FAST COMPARE_OP_INT | 81,496,700 | 2.2% | 37.7% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 78,900,180 | 2.2% | 39.9% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 73,678,380 | 2.0% | 41.9% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 70,762,300 | 1.9% | 43.8% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 67,920,620 | 1.9% | 45.7% |
| POP_JUMP_IF_TRUE ENTER_EXECUTOR | 58,904,240 | 1.6% | 47.3% |
| ENTER_EXECUTOR POP_JUMP_IF_FALSE | 58,716,480 | 1.6% | 48.9% |
| LOAD_CONST LOAD_FAST | 57,992,620 | 1.6% | 50.5% |
| BINARY_OP_SUBTRACT_INT RETURN_VALUE | 52,186,700 | 1.4% | 51.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 50,365,860 | 1.4% | 53.3% |
| ENTER_EXECUTOR CALL_LIST_APPEND | 49,659,500 | 1.4% | 54.6% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 46,690,320 | 1.3% | 55.9% |
| LOAD_FAST COPY | 46,680,140 | 1.3% | 57.2% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 46,679,940 | 1.3% | 58.4% |
| LOAD_FAST BINARY_OP | 46,349,880 | 1.3% | 59.7% |
| RETURN_VALUE STORE_FAST | 44,595,620 | 1.2% | 60.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 43,959,300 | 1.2% | 62.1% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 41,287,060 | 1.1% | 63.3% |
| RETURN_VALUE BINARY_OP | 39,650,080 | 1.1% | 64.3% |
| RESUME_CHECK LOAD_CONST | 38,803,240 | 1.1% | 65.4% |
| BINARY_OP LOAD_CONST | 38,619,100 | 1.1% | 66.4% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 38,564,040 | 1.1% | 67.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 35,898,320 | 1.0% | 68.5% |
| BINARY_OP LOAD_FAST | 33,587,100 | 0.9% | 69.4% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 31,430,480 | 0.9% | 70.3% |
| POP_TOP LOAD_FAST | 30,094,120 | 0.8% | 71.1% |
| LOAD_FAST CALL_LEN | 29,801,800 | 0.8% | 71.9% |
| BINARY_OP_ADD_INT STORE_FAST | 29,202,420 | 0.8% | 72.7% |
| LOAD_ATTR_INSTANCE_VALUE STORE_FAST | 27,334,200 | 0.7% | 73.4% |
| BINARY_OP RETURN_VALUE | 27,328,180 | 0.7% | 74.2% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 27,221,820 | 0.7% | 74.9% |
| BINARY_OP_SUBTRACT_INT BINARY_OP | 26,033,920 | 0.7% | 75.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 24,407,640 | 0.7% | 76.3% |
| CALL_LEN COMPARE_OP_INT | 24,398,520 | 0.7% | 77.0% |
| LOAD_FAST LOAD_FAST | 24,383,360 | 0.7% | 77.6% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 24,327,060 | 0.7% | 78.3% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 24,180,000 | 0.7% | 78.9% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_INT | 24,176,040 | 0.7% | 79.6% |
| CALL_LIST_APPEND LOAD_FAST | 24,161,240 | 0.7% | 80.3% |
| LOAD_CONST COMPARE_OP_INT | 24,043,680 | 0.7% | 80.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_PY_EXACT_ARGS | 23,723,420 | 0.6% | 81.6% |
| RETURN_CONST POP_TOP | 18,232,880 | 0.5% | 82.1% |
| LOAD_FAST RETURN_VALUE | 18,010,000 | 0.5% | 82.6% |
| BINARY_OP SWAP | 17,941,700 | 0.5% | 83.0% |
| BINARY_OP STORE_FAST | 17,382,720 | 0.5% | 83.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 17,270,340 | 0.5% | 84.0% |
| RESUME_CHECK LOAD_FAST | 16,276,020 | 0.4% | 84.4% |
| BINARY_OP_ADD_INT SWAP | 16,212,640 | 0.4% | 84.9% |
| POP_JUMP_IF_FALSE LOAD_CONST | 14,872,960 | 0.4% | 85.3% |
| BINARY_SLICE BINARY_OP | 14,848,480 | 0.4% | 85.7% |
| ENTER_EXECUTOR LOAD_CONST | 13,439,820 | 0.4% | 86.1% |
| SWAP COPY | 13,258,800 | 0.4% | 86.4% |
| COPY COMPARE_OP_INT | 13,258,560 | 0.4% | 86.8% |
| RETURN_VALUE LOAD_FAST | 12,607,200 | 0.3% | 87.1% |
| UNARY_INVERT BINARY_OP | 12,536,640 | 0.3% | 87.5% |
| BINARY_OP UNARY_INVERT | 12,536,640 | 0.3% | 87.8% |
| BINARY_OP_SUBTRACT_INT SWAP | 12,536,620 | 0.3% | 88.2% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP | 12,536,620 | 0.3% | 88.5% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 12,477,680 | 0.3% | 88.8% |
| STORE_FAST LOAD_CONST | 12,115,400 | 0.3% | 89.2% |
| LOAD_FAST SWAP | 11,862,640 | 0.3% | 89.5% |
| RETURN_VALUE POP_TOP | 11,861,920 | 0.3% | 89.8% |
| POP_TOP RETURN_VALUE | 11,861,680 | 0.3% | 90.1% |
| SWAP POP_TOP | 11,861,680 | 0.3% | 90.5% |
| LOAD_ATTR_INSTANCE_VALUE SWAP | 11,861,660 | 0.3% | 90.8% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 11,595,980 | 0.3% | 91.1% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 11,594,320 | 0.3% | 91.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 10,809,940 | 0.3% | 91.7% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 10,807,280 | 0.3% | 92.0% |
| LOAD_CONST BINARY_OP | 10,232,320 | 0.3% | 92.3% |
| BINARY_OP_ADD_INT BINARY_SLICE | 9,503,620 | 0.3% | 92.5% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 8,820,340 | 0.2% | 92.8% |
| LOAD_CONST LOAD_CONST | 7,431,140 | 0.2% | 93.0% |
| LOAD_CONST BINARY_SLICE | 7,424,720 | 0.2% | 93.2% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 7,424,580 | 0.2% | 93.4% |
| BINARY_SLICE LOAD_FAST | 7,424,240 | 0.2% | 93.6% |
| STORE_SLICE RETURN_CONST | 7,424,240 | 0.2% | 93.8% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 7,424,240 | 0.2% | 94.0% |
| LOAD_CONST STORE_SLICE | 7,424,240 | 0.2% | 94.2% |
| LOAD_FAST BINARY_SLICE | 7,424,240 | 0.2% | 94.4% |
| BINARY_OP_ADD_INT LOAD_CONST | 7,424,220 | 0.2% | 94.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 7,189,700 | 0.2% | 94.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 7,187,800 | 0.2% | 95.0% |
| LOAD_FAST CALL_LIST_APPEND | 7,187,360 | 0.2% | 95.2% |
| BINARY_OP_SUBTRACT_INT COMPARE_OP_INT | 7,187,360 | 0.2% | 95.4% |
| CALL_LIST_APPEND NOP | 7,186,940 | 0.2% | 95.6% |
| BINARY_OP_SUBTRACT_INT BINARY_SUBSCR_LIST_INT | 7,186,920 | 0.2% | 95.8% |
| BINARY_OP_SUBTRACT_INT CALL_PY_EXACT_ARGS | 7,186,920 | 0.2% | 96.0% |
| NOP ENTER_EXECUTOR | 7,186,620 | 0.2% | 96.2% |
| JUMP_FORWARD LOAD_FAST | 6,696,740 | 0.2% | 96.4% |
| LOAD_CONST STORE_FAST | 6,274,200 | 0.2% | 96.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 9,503,620 | 39.0% |
| LOAD_CONST | 7,424,720 | 30.5% |
| LOAD_FAST | 7,424,240 | 30.5% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 14,848,480 | 61.0% |
| LOAD_FAST | 7,424,240 | 30.5% |
| CALL_LIST_APPEND | 712,700 | 2.9% |
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
| BINARY_OP_ADD_INT | 2,138,580 | 99.9% |
| BINARY_SUBSCR | 1,120 | 0.1% |
| LOAD_FAST_LOAD_FAST | 480 | 0.0% |
| LOAD_FAST | 440 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,396,160 | 65.2% |
| COMPARE_OP_INT | 742,440 | 34.7% |
| BINARY_SUBSCR | 1,120 | 0.1% |
| LOAD_FAST | 420 | 0.0% |
| CALL_LIST_APPEND | 360 | 0.0% |


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
| LOAD_ATTR_INSTANCE_VALUE | 238,820 | 96.4% |
| CALL_BUILTIN_CLASS | 8,000 | 3.2% |
| BINARY_SLICE | 480 | 0.2% |
| CALL | 180 | 0.1% |
| LOAD_FAST | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 239,340 | 96.6% |
| FOR_ITER_RANGE | 7,940 | 3.2% |
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
| POP_JUMP_IF_FALSE | 1,120 | 0.0% |
| JUMP_BACKWARD | 320 | 0.0% |
| STORE_FAST | 160 | 0.0% |
| POP_TOP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,186,620 | 100.0% |
| LOAD_FAST | 1,600 | 0.0% |
| JUMP_BACKWARD | 340 | 0.0% |
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
| POP_JUMP_IF_FALSE | 653,620 | 1.5% |
| CALL_KW | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 30,094,120 | 70.6% |
| RETURN_VALUE | 11,861,680 | 27.8% |
| JUMP_FORWARD | 654,260 | 1.5% |
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
| BINARY_OP_SUBTRACT_INT | 52,186,700 | 47.6% |
| BINARY_OP | 27,328,180 | 25.0% |
| LOAD_FAST | 18,010,000 | 16.4% |
| POP_TOP | 11,861,680 | 10.8% |
| EXIT_INIT_CHECK | 71,120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 44,595,620 | 40.7% |
| BINARY_OP | 39,650,080 | 36.2% |
| LOAD_FAST | 12,607,200 | 11.5% |
| POP_TOP | 11,861,920 | 10.8% |
| TO_BOOL_INT | 627,120 | 0.6% |


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
| LOAD_FAST | 5,402,600 | 100.0% |
| TO_BOOL | 1,500 | 0.0% |
| RETURN_VALUE | 160 | 0.0% |
| BINARY_OP | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 5,402,420 | 100.0% |
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
| LOAD_FAST | 46,349,880 | 28.4% |
| RETURN_VALUE | 39,650,080 | 24.3% |
| BINARY_OP_SUBTRACT_INT | 26,033,920 | 16.0% |
| BINARY_SLICE | 14,848,480 | 9.1% |
| UNARY_INVERT | 12,536,640 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,619,100 | 23.7% |
| LOAD_FAST | 33,587,100 | 20.6% |
| RETURN_VALUE | 27,328,180 | 16.8% |
| SWAP | 17,941,700 | 11.0% |
| STORE_FAST | 17,382,720 | 10.7% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 71,040 | 86.5% |
| CALL_BUILTIN_CLASS | 8,700 | 10.6% |
| STORE_FAST | 720 | 0.9% |
| RESUME_CHECK | 580 | 0.7% |
| BUILD_TUPLE | 480 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 80,240 | 97.7% |
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
| ENTER_EXECUTOR | 20,080 | 78.3% |
| LOAD_FAST | 2,160 | 8.4% |
| LOAD_CONST | 1,080 | 4.2% |
| CALL | 520 | 2.0% |
| CALL_BUILTIN_FAST | 380 | 1.5% |

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
| LOAD_FAST | 46,680,140 | 77.9% |
| SWAP | 13,258,800 | 22.1% |
| COPY | 400 | 0.0% |
| LOAD_FAST_LOAD_FAST | 400 | 0.0% |
| RETURN_VALUE | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 46,679,940 | 77.9% |
| COMPARE_OP_INT | 13,258,560 | 22.1% |
| COPY | 400 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 360 | 0.0% |
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
| POP_JUMP_IF_TRUE | 58,904,240 | 48.1% |
| CALL_LIST_APPEND | 27,221,820 | 22.2% |
| POP_JUMP_IF_FALSE | 24,327,060 | 19.9% |
| NOP | 7,186,620 | 5.9% |
| STORE_FAST | 4,815,040 | 3.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 58,716,480 | 47.9% |
| CALL_LIST_APPEND | 49,659,500 | 40.5% |
| LOAD_CONST | 13,439,820 | 11.0% |
| STORE_FAST | 206,860 | 0.2% |
| FOR_ITER_RANGE | 205,540 | 0.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,220 | 68.5% |
| GET_ITER | 340 | 19.1% |
| FOR_ITER | 140 | 7.9% |
| SWAP | 80 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 1,040 | 58.4% |
| STORE_FAST | 240 | 13.5% |
| FOR_ITER_RANGE | 160 | 9.0% |
| FOR_ITER | 140 | 7.9% |
| UNPACK_SEQUENCE | 100 | 5.6% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,040 | 24.5% |
| CALL_LIST_APPEND | 1,600 | 19.2% |
| STORE_FAST | 1,440 | 17.3% |
| POP_JUMP_IF_TRUE | 1,360 | 16.3% |
| STORE_ATTR_INSTANCE_VALUE | 640 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 2,160 | 26.0% |
| FOR_ITER_LIST | 1,820 | 21.9% |
| LOAD_FAST | 1,360 | 16.3% |
| FOR_ITER | 1,220 | 14.7% |
| LOAD_FAST_LOAD_FAST | 960 | 11.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,359,360 | 80.0% |
| STORE_FAST | 683,440 | 10.2% |
| POP_TOP | 654,260 | 9.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,696,740 | 100.0% |
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
| CALL_BUILTIN_FAST | 1,740 | 98.9% |
| CALL | 20 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,420 | 80.7% |
| JUMP_BACKWARD | 340 | 19.3% |


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
| LOAD_ATTR_INSTANCE_VALUE | 5,402,380 | 99.9% |
| LOAD_FAST | 3,080 | 0.1% |
| LOAD_ATTR | 1,680 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,000 | 0.0% |
| COPY | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,403,160 | 99.9% |
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
| LOAD_FAST | 92,138,360 | 36.3% |
| RESUME_CHECK | 38,803,240 | 15.3% |
| BINARY_OP | 38,619,100 | 15.2% |
| POP_JUMP_IF_FALSE | 14,872,960 | 5.9% |
| ENTER_EXECUTOR | 13,439,820 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 73,678,380 | 29.0% |
| LOAD_FAST | 57,992,620 | 22.9% |
| BINARY_OP_ADD_INT | 50,365,860 | 19.8% |
| COMPARE_OP_INT | 24,043,680 | 9.5% |
| BINARY_OP | 10,232,320 | 4.0% |


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
| POP_JUMP_IF_FALSE | 252,288,360 | 26.9% |
| LOAD_ATTR_INSTANCE_VALUE | 158,689,940 | 16.9% |
| STORE_FAST | 110,085,620 | 11.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 67,920,620 | 7.2% |
| LOAD_CONST | 57,992,620 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 214,787,700 | 22.9% |
| TO_BOOL_BOOL | 141,380,280 | 15.1% |
| LOAD_CONST | 92,138,360 | 9.8% |
| COMPARE_OP_INT | 81,496,700 | 8.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 78,900,180 | 8.4% |


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
| RESUME_CHECK | 31,430,480 | 68.0% |
| BINARY_OP | 7,424,240 | 16.1% |
| STORE_FAST | 3,287,840 | 7.1% |
| POP_JUMP_IF_FALSE | 2,252,660 | 4.9% |
| LOAD_FAST | 1,396,100 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 24,180,000 | 52.3% |
| LOAD_FAST | 12,477,680 | 27.0% |
| LOAD_CONST | 8,820,340 | 19.1% |
| CALL_PY_EXACT_ARGS | 244,140 | 0.5% |
| STORE_ATTR_INSTANCE_VALUE | 147,900 | 0.3% |


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
| TO_BOOL_BOOL | 141,379,780 | 46.3% |
| COMPARE_OP_INT | 104,670,280 | 34.3% |
| ENTER_EXECUTOR | 58,716,480 | 19.2% |
| TO_BOOL_INT | 629,980 | 0.2% |
| COMPARE_OP | 920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 252,288,360 | 82.6% |
| ENTER_EXECUTOR | 24,327,060 | 8.0% |
| LOAD_CONST | 14,872,960 | 4.9% |
| RETURN_CONST | 5,402,160 | 1.8% |
| JUMP_FORWARD | 5,359,360 | 1.8% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 70,762,300 | 92.9% |
| TO_BOOL | 5,402,420 | 7.1% |
| ENTER_EXECUTOR | 12,740 | 0.0% |
| TO_BOOL_BOOL | 700 | 0.0% |
| COMPARE_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 58,904,240 | 77.3% |
| LOAD_FAST | 17,270,340 | 22.7% |
| LOAD_GLOBAL_MODULE | 1,760 | 0.0% |
| JUMP_BACKWARD | 1,360 | 0.0% |
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
| FOR_ITER_LIST | 960 | 0.0% |
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
| RETURN_VALUE | 44,595,620 | 32.3% |
| BINARY_OP_ADD_INT | 29,202,420 | 21.1% |
| LOAD_ATTR_INSTANCE_VALUE | 27,334,200 | 19.8% |
| BINARY_OP | 17,382,720 | 12.6% |
| BINARY_SUBSCR_LIST_INT | 7,424,580 | 5.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 110,085,620 | 79.7% |
| LOAD_CONST | 12,115,400 | 8.8% |
| LOAD_GLOBAL_MODULE | 7,187,800 | 5.2% |
| ENTER_EXECUTOR | 4,815,040 | 3.5% |
| LOAD_FAST_LOAD_FAST | 3,287,840 | 2.4% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 70,560 | 96.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,780 | 3.8% |
| UNPACK_SEQUENCE | 100 | 0.1% |
| COPY | 80 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 73,040 | 99.3% |
| LOAD_FAST_LOAD_FAST | 400 | 0.5% |
| BUILD_LIST | 80 | 0.1% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 17,941,700 | 25.0% |
| BINARY_OP_ADD_INT | 16,212,640 | 22.6% |
| BINARY_OP_SUBTRACT_INT | 12,536,620 | 17.5% |
| LOAD_FAST | 11,862,640 | 16.5% |
| LOAD_ATTR_INSTANCE_VALUE | 11,861,660 | 16.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 46,690,320 | 65.0% |
| COPY | 13,258,800 | 18.5% |
| POP_TOP | 11,861,680 | 16.5% |
| SWAP | 400 | 0.0% |
| STORE_SUBSCR_LIST_INT | 360 | 0.0% |


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
| LOAD_CONST | 50,365,860 | 76.5% |
| CALL_BUILTIN_O | 5,404,920 | 8.2% |
| CALL_LEN | 5,402,360 | 8.2% |
| BINARY_OP | 4,675,020 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,202,420 | 44.3% |
| SWAP | 16,212,640 | 24.6% |
| BINARY_SLICE | 9,503,620 | 14.4% |
| LOAD_CONST | 7,424,220 | 11.3% |
| BINARY_SUBSCR | 2,138,580 | 3.2% |


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
| LOAD_CONST | 73,678,380 | 65.5% |
| LOAD_FAST | 38,564,040 | 34.3% |
| ENTER_EXECUTOR | 127,860 | 0.1% |
| BINARY_OP_SUBTRACT_INT | 44,920 | 0.0% |
| BINARY_OP | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 52,186,700 | 46.4% |
| BINARY_OP | 26,033,920 | 23.2% |
| SWAP | 12,536,620 | 11.2% |
| COMPARE_OP_INT | 7,187,360 | 6.4% |
| BINARY_SUBSCR_LIST_INT | 7,186,920 | 6.4% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 7,186,920 | 67.3% |
| LOAD_CONST | 3,010,760 | 28.2% |
| LOAD_FAST | 237,240 | 2.2% |
| BINARY_SUBSCR_LIST_INT | 237,240 | 2.2% |
| LOAD_FAST_LOAD_FAST | 720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,424,580 | 69.6% |
| LOAD_FAST | 2,773,100 | 26.0% |
| BINARY_SUBSCR_LIST_INT | 237,240 | 2.2% |
| CALL_LIST_APPEND | 237,240 | 2.2% |
| UNPACK_SEQUENCE_TWO_TUPLE | 440 | 0.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 69,880 | 98.3% |
| LOAD_FAST_LOAD_FAST | 760 | 1.1% |
| LOAD_FAST | 400 | 0.6% |
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
| BINARY_OP | 8,680 | 48.8% |
| LOAD_CONST | 6,420 | 36.1% |
| LOAD_FAST | 1,120 | 6.3% |
| LOAD_FAST_LOAD_FAST | 760 | 4.3% |
| CALL | 740 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 8,700 | 48.9% |
| GET_ITER | 8,000 | 44.9% |
| LOAD_FAST | 920 | 5.2% |
| STORE_FAST | 120 | 0.7% |
| CALL_BUILTIN_CLASS | 40 | 0.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,080 | 98.1% |
| CALL | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 1,740 | 82.1% |
| CALL | 380 | 17.9% |


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
| LOAD_FAST | 5,404,920 | 88.8% |
| BINARY_SLICE | 683,320 | 11.2% |
| LOAD_CONST | 160 | 0.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 5,404,920 | 88.8% |
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
| LOAD_FAST | 29,801,800 | 100.0% |
| CALL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 24,398,520 | 81.9% |
| BINARY_OP_ADD_INT | 5,402,360 | 18.1% |
| STORE_FAST | 460 | 0.0% |
| LOAD_CONST | 380 | 0.0% |
| BINARY_OP | 80 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 49,659,500 | 81.0% |
| LOAD_FAST | 7,187,360 | 11.7% |
| BINARY_OP | 3,456,400 | 5.6% |
| BINARY_SLICE | 712,700 | 1.2% |
| BINARY_SUBSCR_LIST_INT | 237,240 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 27,221,820 | 44.4% |
| LOAD_FAST | 24,161,240 | 39.4% |
| NOP | 7,186,940 | 11.7% |
| LOAD_CONST | 2,773,100 | 4.5% |
| JUMP_BACKWARD | 1,600 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,402,360 | 100.0% |
| CALL | 40 | 0.0% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,402,380 | 100.0% |
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
| LOAD_FAST | 43,959,300 | 50.9% |
| LOAD_ATTR_INSTANCE_VALUE | 23,723,420 | 27.5% |
| BINARY_OP_SUBTRACT_INT | 7,186,920 | 8.3% |
| LOAD_CONST | 5,850,920 | 6.8% |
| LOAD_ATTR_METHOD_WITH_VALUES | 5,402,500 | 6.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 86,368,920 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 81,496,700 | 46.5% |
| CALL_LEN | 24,398,520 | 13.9% |
| LOAD_ATTR_INSTANCE_VALUE | 24,176,040 | 13.8% |
| LOAD_CONST | 24,043,680 | 13.7% |
| COPY | 13,258,560 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 104,670,280 | 59.7% |
| POP_JUMP_IF_TRUE | 70,762,300 | 40.3% |


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
| GET_ITER | 239,340 | 98.8% |
| JUMP_BACKWARD | 1,820 | 0.8% |
| ENTER_EXECUTOR | 1,000 | 0.4% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,440 | 99.2% |
| RETURN_CONST | 960 | 0.4% |
| UNPACK_SEQUENCE_TWO_TUPLE | 760 | 0.3% |
| LOAD_FAST | 80 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 205,540 | 95.2% |
| GET_ITER | 7,940 | 3.7% |
| JUMP_BACKWARD | 2,160 | 1.0% |
| FOR_ITER | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 73,800 | 34.2% |
| LOAD_FAST_LOAD_FAST | 71,040 | 32.9% |
| LOAD_FAST | 70,640 | 32.7% |
| BUILD_LIST | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 214,787,700 | 75.2% |
| COPY | 46,679,940 | 16.3% |
| LOAD_FAST_LOAD_FAST | 24,180,000 | 8.5% |
| ENTER_EXECUTOR | 2,560 | 0.0% |
| LOAD_ATTR | 820 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 158,689,940 | 55.6% |
| STORE_FAST | 27,334,200 | 9.6% |
| COMPARE_OP_INT | 24,176,040 | 8.5% |
| CALL_PY_EXACT_ARGS | 23,723,420 | 8.3% |
| BINARY_OP | 12,536,620 | 4.4% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,595,980 | 100.0% |
| LOAD_ATTR | 280 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,594,320 | 100.0% |
| LOAD_GLOBAL_MODULE | 1,560 | 0.0% |
| LOAD_FAST_LOAD_FAST | 380 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 78,900,180 | 100.0% |
| LOAD_FAST_LOAD_FAST | 35,800 | 0.0% |
| LOAD_ATTR | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,920,620 | 86.0% |
| LOAD_CONST | 5,613,400 | 7.1% |
| CALL_PY_EXACT_ARGS | 5,402,500 | 6.8% |
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
| LOAD_FAST | 24,407,640 | 68.0% |
| LOAD_ATTR_INSTANCE_VALUE | 10,807,280 | 30.1% |
| BINARY_SLICE | 683,320 | 1.9% |
| STORE_FAST | 7,700 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,898,320 | 100.0% |
| LOAD_FAST_LOAD_FAST | 9,480 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 1,000 | 0.0% |
| LOAD_CONST | 300 | 0.0% |
| LOAD_GLOBAL | 100 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,187,800 | 96.7% |
| POP_JUMP_IF_FALSE | 237,360 | 3.2% |
| STORE_ATTR_INSTANCE_VALUE | 6,380 | 0.1% |
| POP_JUMP_IF_TRUE | 1,760 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 1,560 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,189,700 | 96.7% |
| LOAD_FAST_LOAD_FAST | 244,620 | 3.3% |
| LOAD_ATTR | 1,000 | 0.0% |
| LOAD_ATTR_MODULE | 160 | 0.0% |
| CALL_ISINSTANCE | 120 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 86,368,920 | 99.8% |
| CALL_ALLOC_AND_ENTER_INIT | 71,120 | 0.1% |
| CACHE | 70,560 | 0.1% |
| CALL | 440 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 38,803,240 | 44.9% |
| LOAD_FAST_LOAD_FAST | 31,430,480 | 36.3% |
| LOAD_FAST | 16,276,020 | 18.8% |
| LOAD_GLOBAL_BUILTIN | 640 | 0.0% |
| BUILD_LIST | 580 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 46,690,320 | 99.2% |
| LOAD_FAST | 218,580 | 0.5% |
| LOAD_FAST_LOAD_FAST | 147,900 | 0.3% |
| STORE_ATTR | 500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 41,287,060 | 87.7% |
| RETURN_CONST | 5,476,060 | 11.6% |
| LOAD_CONST | 141,260 | 0.3% |
| ENTER_EXECUTOR | 75,340 | 0.2% |
| LOAD_FAST_LOAD_FAST | 70,540 | 0.1% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 360 | 47.4% |
| BINARY_SUBSCR_LIST_INT | 360 | 47.4% |
| STORE_SUBSCR | 40 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 380 | 50.0% |
| JUMP_BACKWARD | 320 | 42.1% |
| ENTER_EXECUTOR | 60 | 7.9% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 141,380,280 | 100.0% |
| CALL_ISINSTANCE | 120 | 0.0% |
| TO_BOOL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 141,379,780 | 100.0% |
| POP_JUMP_IF_TRUE | 700 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 627,120 | 99.5% |
| BINARY_OP | 1,840 | 0.3% |
| LOAD_FAST | 800 | 0.1% |
| TO_BOOL | 180 | 0.0% |
| CALL_LEN | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 629,980 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,040 | 32.1% |
| LOAD_CONST | 880 | 27.2% |
| FOR_ITER_LIST | 760 | 23.5% |
| BINARY_SUBSCR_LIST_INT | 440 | 13.6% |
| UNPACK_SEQUENCE | 120 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,780 | 85.8% |
| LOAD_FAST | 460 | 14.2% |


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
|     deferred | 163,103,300 | 47.8% |
|          hit | 178,308,700 | 52.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 760 | 1.7% |
| Failure | 45,300 | 98.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| lshift | 17,740 | 39.2% |
| and int | 14,040 | 31.0% |
| rshift | 7,380 | 16.3% |
| add other | 4,480 | 9.9% |
| multiply different types | 1,260 | 2.8% |
| or | 400 | 0.9% |


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
|     deferred | 2,139,620 | 16.7% |
|          hit | 10,673,420 | 83.3% |

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
|          hit | 189,098,220 | 100.0% |

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
|          hit | 175,432,640 | 100.0% |

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
|     deferred | 1,380 | 0.3% |
|          hit | 458,060 | 99.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 65.0% |
| Failure | 140 | 35.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 140 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,405,340 | 1.4% |
|          hit | 376,184,260 | 98.6% |

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
|          hit | 43,344,880 | 100.0% |

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
|          hit | 47,057,300 | 100.0% |

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
|     deferred | 40 | 4.8% |
|          hit | 760 | 90.5% |

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
|     deferred | 5,402,660 | 3.7% |
|          hit | 142,010,460 | 96.3% |

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
|     deferred | 120 | 3.4% |
|          hit | 3,240 | 93.1% |

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
| Basic | 1,826,944,000 | 49.8% |
| Not specialized | 589,489,420 | 16.1% |
| Specialized hits | 1,249,083,000 | 34.1% |
| Specialized misses | 100 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 163,103,300 | 92.6% |
| LOAD_ATTR | 5,405,340 | 3.1% |
| TO_BOOL | 5,402,660 | 3.1% |
| BINARY_SUBSCR | 2,139,620 | 1.2% |
| CALL | 23,340 | 0.0% |
| FOR_ITER | 1,380 | 0.0% |
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
| Calls to Python functions inlined | 86,441,060 | 99.9% |
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
| Frames pushed | 127,978,100 | 147.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 37,375,180 | 10.4% |
| Frees to freelist | 37,380,820 |  |
| Allocations | 322,972,760 | 89.6% |
| Allocations to 512 bytes | 301,306,080 | 83.6% |
| Allocations to 4 kbytes | 21,664,920 | 6.0% |
| Allocations over 4 kbytes | 1,760 | 0.0% |
| Frees | 322,970,828 |  |
| New values | 80 |  |
| Interpreter increfs | 1,993,063,600 | 91.4% |
| Interpreter decrefs | 2,289,965,580 | 89.8% |
| Increfs | 186,652,678 | 8.6% |
| Decrefs | 260,286,828 | 10.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 5,414,765 |  |
| Method cache misses | 655 |  |
| Method cache collisions | 540 |  |
| Method cache dunder hits | 2,837 |  |
| Method cache dunder misses | 163 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 100 | 1,920 | 1,539,480 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 480 |  |
| Traces created | 480 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 220 | 45.8% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 122,532,080 |  |
| Uops executed | 4,987,230,820 | 40.70 |

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
| <= 32 | 60 | 12.5% |
| <= 64 | 120 | 25.0% |
| <= 128 | 300 | 62.5% |


</details>

### Optimized trace length histogram

<details>
<summary> optimized trace length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 20 | 4.2% |
| <= 16 | 40 | 8.3% |
| <= 32 | 100 | 20.8% |
| <= 64 | 120 | 25.0% |
| <= 128 | 200 | 41.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 520 | 0.0% |
| <= 4 | 71,800 | 0.1% |
| <= 8 | 6,100 | 0.0% |
| <= 16 | 43,600,200 | 35.6% |
| <= 32 | 26,927,700 | 22.0% |
| <= 64 | 37,941,380 | 31.0% |
| <= 128 | 13,919,560 | 11.4% |
| <= 256 | 50,360 | 0.0% |
| <= 512 | 13,180 | 0.0% |
| <= 1,024 | 720 | 0.0% |
| <= 2,048 | 340 | 0.0% |
| <= 4,096 | 140 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 0 | 0.0% |
| <= 65,536 | 0 | 0.0% |
| <= 131,072 | 0 | 0.0% |
| <= 262,144 | 0 | 0.0% |
| <= 524,288 | 0 | 0.0% |
| <= 1,048,576 | 0 | 0.0% |
| <= 2,097,152 | 0 | 0.0% |
| <= 4,194,304 | 0 | 0.0% |
| <= 8,388,608 | 0 | 0.0% |
| <= 16,777,216 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 883,193,600 | 17.7% | 17.7% |  |
| _SET_IP | 677,636,220 | 13.6% | 31.3% |  |
| _CHECK_VALIDITY | 522,293,160 | 10.5% | 41.8% |  |
| _GUARD_TYPE_VERSION | 232,759,640 | 4.7% | 46.4% |  |
| STORE_FAST | 216,310,120 | 4.3% | 50.8% |  |
| LOAD_CONST | 172,999,980 | 3.5% | 54.2% |  |
| COMPARE_OP_INT | 147,068,740 | 2.9% | 57.2% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 141,519,200 | 2.8% | 60.0% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 141,519,200 | 2.8% | 62.9% |  |
| _GUARD_BOTH_INT | 124,246,780 | 2.5% | 65.4% |  |
| _GUARD_IS_TRUE_POP | 83,248,360 | 1.7% | 67.0% | 52.1% |
| BINARY_SUBSCR_LIST_INT | 80,682,960 | 1.6% | 68.6% |  |
| COPY | 78,032,220 | 1.6% | 70.2% |  |
| SWAP | 78,021,840 | 1.6% | 71.8% |  |
| _BINARY_SUBSCR | 75,216,080 | 1.5% | 73.3% |  |
| _BINARY_OP_ADD_INT | 74,038,700 | 1.5% | 74.8% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 70,661,680 | 1.4% | 76.2% | 0.0% |
| _ITER_CHECK_LIST | 70,661,680 | 1.4% | 77.6% |  |
| _ITER_NEXT_LIST | 70,660,680 | 1.4% | 79.0% |  |
| _GUARD_IS_FALSE_POP | 63,931,020 | 1.3% | 80.3% | 24.0% |
| _EXIT_TRACE | 63,660,300 | 1.3% | 81.6% |  |
| STORE_SUBSCR_LIST_INT | 53,788,640 | 1.1% | 82.7% |  |
| _BINARY_OP_SUBTRACT_INT | 50,208,080 | 1.0% | 83.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 49,769,420 | 1.0% | 84.7% |  |
| RESUME_CHECK | 41,466,940 | 0.8% | 85.5% |  |
| _CHECK_PEP_523 | 41,466,940 | 0.8% | 86.3% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 41,466,940 | 0.8% | 87.2% |  |
| _CHECK_STACK_SPACE | 41,466,940 | 0.8% | 88.0% |  |
| _INIT_CALL_PY_EXACT_ARGS | 41,466,940 | 0.8% | 88.8% |  |
| _PUSH_FRAME | 41,466,940 | 0.8% | 89.6% |  |
| _SAVE_RETURN_OFFSET | 41,466,940 | 0.8% | 90.5% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 41,403,620 | 0.8% | 91.3% |  |
| _GUARD_KEYS_VERSION | 41,403,620 | 0.8% | 92.1% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 41,403,620 | 0.8% | 93.0% |  |
| _BINARY_OP | 30,800,500 | 0.6% | 93.6% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 27,788,080 | 0.6% | 94.1% | 0.5% |
| _ITER_CHECK_RANGE | 27,788,080 | 0.6% | 94.7% |  |
| _ITER_NEXT_RANGE | 27,646,680 | 0.6% | 95.3% |  |
| _JUMP_TO_TOP | 27,336,480 | 0.5% | 95.8% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 26,983,840 | 0.5% | 96.3% |  |
| _FOR_ITER_TIER_TWO | 26,914,240 | 0.5% | 96.9% |  |
| _GUARD_GLOBALS_VERSION | 24,471,760 | 0.5% | 97.4% |  |
| _GUARD_BUILTINS_VERSION | 24,307,820 | 0.5% | 97.9% |  |
| _LOAD_GLOBAL_BUILTINS | 24,307,820 | 0.5% | 98.4% |  |
| CALL_LEN | 24,163,440 | 0.5% | 98.8% |  |
| BINARY_SLICE | 22,765,180 | 0.5% | 99.3% |  |
| POP_TOP | 22,765,180 | 0.5% | 99.7% |  |
| GET_ITER | 11,757,660 | 0.2% | 100.0% |  |
| _POP_FRAME | 217,200 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_MODULE | 163,940 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 144,380 | 0.0% | 100.0% |  |
| TO_BOOL_INT | 88,320 | 0.0% | 100.0% |  |
| _GUARD_DORV_VALUES | 67,400 | 0.0% | 100.0% |  |
| _STORE_ATTR_INSTANCE_VALUE | 67,400 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 29,920 | 0.0% | 100.0% |  |
| TO_BOOL_BOOL | 19,760 | 0.0% | 100.0% |  |
| BUILD_LIST | 10,480 | 0.0% | 100.0% |  |
| LIST_APPEND | 9,840 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,560 | 0.0% | 100.0% |  |
| _TO_BOOL | 2,560 | 0.0% | 100.0% |  |
| _LOAD_ATTR | 2,560 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
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
Stats gathered on: 2023-11-16
