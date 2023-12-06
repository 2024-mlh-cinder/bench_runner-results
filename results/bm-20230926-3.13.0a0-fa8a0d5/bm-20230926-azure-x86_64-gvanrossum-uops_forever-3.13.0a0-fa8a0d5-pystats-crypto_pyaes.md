
# Pystats results

- benchmark: crypto_pyaes
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| BINARY_OP | 105,703,020 | 21.0% | 21.0% |  |
| LOAD_FAST | 79,107,060 | 15.7% | 36.7% |  |
| LOAD_CONST | 78,577,620 | 15.6% | 52.4% |  |
| BINARY_SUBSCR_LIST_INT | 69,405,600 | 13.8% | 66.2% |  |
| LOAD_FAST_LOAD_FAST | 36,595,560 | 7.3% | 73.5% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 27,633,000 | 5.5% | 78.9% |  |
| BINARY_OP_ADD_INT | 21,056,880 | 4.2% | 83.1% |  |
| ENTER_EXECUTOR | 8,810,560 | 1.8% | 84.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 7,774,080 | 1.5% | 86.4% |  |
| STORE_FAST | 6,739,500 | 1.3% | 87.8% |  |
| STORE_SUBSCR_LIST_INT | 6,395,040 | 1.3% | 89.0% |  |
| LOAD_GLOBAL_MODULE | 4,144,840 | 0.8% | 89.9% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,796,320 | 0.8% | 90.6% |  |
| PUSH_NULL | 3,106,980 | 0.6% | 91.2% |  |
| LIST_APPEND | 2,933,400 | 0.6% | 91.8% |  |
| STORE_FAST_STORE_FAST | 2,932,560 | 0.6% | 92.4% |  |
| CALL_LIST_APPEND | 2,760,960 | 0.5% | 93.0% |  |
| FOR_ITER | 2,760,780 | 0.5% | 93.5% |  |
| JUMP_BACKWARD | 2,760,560 | 0.5% | 94.1% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,760,000 | 0.5% | 94.6% |  |
| LOAD_GLOBAL_BUILTIN | 2,417,220 | 0.5% | 95.1% |  |
| RESUME_CHECK | 2,244,300 | 0.4% | 95.5% |  |
| POP_JUMP_IF_FALSE | 2,078,580 | 0.4% | 95.9% |  |
| RETURN_VALUE | 2,071,380 | 0.4% | 96.4% |  |
| CALL_PY_EXACT_ARGS | 2,071,260 | 0.4% | 96.8% |  |
| LOAD_ATTR_MODULE | 1,553,800 | 0.3% | 97.1% |  |
| TO_BOOL | 1,553,420 | 0.3% | 97.4% |  |
| CALL_TYPE_1 | 1,553,040 | 0.3% | 97.7% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,553,040 | 0.3% | 98.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,553,040 | 0.3% | 98.3% |  |
| SWAP | 869,400 | 0.2% | 98.5% |  |
| FOR_ITER_RANGE | 865,400 | 0.2% | 98.7% |  |
| GET_ITER | 865,020 | 0.2% | 98.8% |  |
| CALL_BUILTIN_CLASS | 864,900 | 0.2% | 99.0% |  |
| CALL_LEN | 863,640 | 0.2% | 99.2% |  |
| BUILD_LIST | 691,260 | 0.1% | 99.3% |  |
| COMPARE_OP_INT | 525,240 | 0.1% | 99.4% |  |
| COPY | 348,120 | 0.1% | 99.5% |  |
| BINARY_OP_SUBTRACT_INT | 347,880 | 0.1% | 99.6% |  |
| BINARY_OP_MULTIPLY_INT | 345,240 | 0.1% | 99.6% |  |
| LIST_EXTEND | 345,180 | 0.1% | 99.7% |  |
| POP_TOP | 344,820 | 0.1% | 99.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 173,400 | 0.0% | 99.8% |  |
| LOAD_FAST_AND_CLEAR | 173,280 | 0.0% | 99.8% |  |
| BINARY_SLICE | 173,160 | 0.0% | 99.9% |  |
| RETURN_CONST | 173,040 | 0.0% | 99.9% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 172,860 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_LIST | 172,560 | 0.0% | 100.0% |  |
| LOAD_ATTR_PROPERTY | 172,560 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 1,200 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 1,200 | 0.0% | 100.0% |  |
| CALL | 900 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 480 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 480 | 0.0% | 100.0% |  |
| LOAD_ATTR | 320 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 220 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| TO_BOOL_BOOL | 120 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 120 | 0.0% | 100.0% |  |
| EXIT_INIT_CHECK | 120 | 0.0% | 100.0% |  |
| CONTAINS_OP | 120 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 120 | 0.0% | 100.0% |  |
| COMPARE_OP | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_CONST BINARY_OP | 74,423,040 | 14.8% | 14.8% |
| BINARY_OP BINARY_SUBSCR_LIST_INT | 48,340,320 | 9.6% | 24.4% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 28,477,440 | 5.7% | 30.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_FAST_LOAD_FAST | 27,609,600 | 5.5% | 35.6% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 25,209,120 | 5.0% | 40.6% |
| BINARY_OP LOAD_CONST | 23,484,840 | 4.7% | 45.2% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,070,440 | 4.2% | 49.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 20,707,680 | 4.1% | 53.6% |
| BINARY_OP_ADD_INT LOAD_CONST | 20,707,320 | 4.1% | 57.7% |
| LOAD_FAST BINARY_OP_ADD_INT | 20,707,200 | 4.1% | 61.8% |
| BINARY_OP LOAD_FAST | 19,171,920 | 3.8% | 65.6% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 15,545,040 | 3.1% | 68.7% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 13,120,440 | 2.6% | 71.3% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 7,773,840 | 1.5% | 72.8% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 6,905,280 | 1.4% | 74.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 6,736,680 | 1.3% | 75.6% |
| ENTER_EXECUTOR LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 6,562,560 | 1.3% | 76.9% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 6,218,200 | 1.2% | 78.1% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 6,212,160 | 1.2% | 79.3% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 6,212,160 | 1.2% | 80.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 3,796,320 | 0.8% | 81.3% |
| PUSH_NULL LOAD_FAST | 3,106,200 | 0.6% | 81.9% |
| LOAD_FAST LOAD_CONST | 2,965,680 | 0.6% | 82.5% |
| BINARY_OP LIST_APPEND | 2,932,920 | 0.6% | 83.1% |
| BINARY_OP CALL_LIST_APPEND | 2,760,960 | 0.5% | 83.7% |
| LIST_APPEND JUMP_BACKWARD | 2,760,180 | 0.5% | 84.2% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 2,760,000 | 0.5% | 84.8% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 2,760,000 | 0.5% | 85.3% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 2,760,000 | 0.5% | 85.9% |
| JUMP_BACKWARD FOR_ITER | 2,760,000 | 0.5% | 86.4% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 2,760,000 | 0.5% | 87.0% |
| BINARY_OP BINARY_OP | 2,447,920 | 0.5% | 87.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,416,980 | 0.5% | 87.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,416,680 | 0.5% | 88.4% |
| STORE_FAST LOAD_FAST | 2,246,940 | 0.4% | 88.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 2,243,280 | 0.4% | 89.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 2,071,260 | 0.4% | 89.7% |
| CALL_LIST_APPEND LOAD_FAST | 2,070,720 | 0.4% | 90.1% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,726,120 | 0.3% | 90.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,553,800 | 0.3% | 90.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 1,553,460 | 0.3% | 91.1% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,553,460 | 0.3% | 91.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,553,360 | 0.3% | 91.7% |
| RETURN_VALUE STORE_FAST | 1,553,280 | 0.3% | 92.0% |
| TO_BOOL POP_JUMP_IF_FALSE | 1,553,040 | 0.3% | 92.3% |
| STORE_FAST ENTER_EXECUTOR | 1,553,040 | 0.3% | 92.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_NO_DICT | 1,553,040 | 0.3% | 92.9% |
| LOAD_FAST TO_BOOL | 1,553,040 | 0.3% | 93.2% |
| LOAD_FAST PUSH_NULL | 1,553,040 | 0.3% | 93.6% |
| LOAD_FAST CALL_TYPE_1 | 1,553,040 | 0.3% | 93.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_NOARGS | 1,553,040 | 0.3% | 94.2% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 1,553,040 | 0.3% | 94.5% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 1,553,040 | 0.3% | 94.8% |
| CALL_TYPE_1 STORE_FAST | 1,553,040 | 0.3% | 95.1% |
| CALL_METHOD_DESCRIPTOR_NOARGS RETURN_VALUE | 1,553,040 | 0.3% | 95.4% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 1,553,040 | 0.3% | 95.7% |
| FOR_ITER_RANGE STORE_FAST | 865,180 | 0.2% | 95.9% |
| CALL_BUILTIN_CLASS GET_ITER | 864,840 | 0.2% | 96.1% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 862,800 | 0.2% | 96.2% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 692,040 | 0.1% | 96.4% |
| GET_ITER FOR_ITER_RANGE | 691,860 | 0.1% | 96.5% |
| LOAD_CONST LOAD_CONST | 690,600 | 0.1% | 96.6% |
| LOAD_CONST CALL_BUILTIN_CLASS | 690,600 | 0.1% | 96.8% |
| LOAD_FAST BINARY_OP | 690,380 | 0.1% | 96.9% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 690,240 | 0.1% | 97.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 525,120 | 0.1% | 97.2% |
| LOAD_CONST LOAD_FAST | 519,720 | 0.1% | 97.3% |
| CALL_LEN LOAD_CONST | 518,160 | 0.1% | 97.4% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 517,800 | 0.1% | 97.5% |
| LOAD_CONST BINARY_OP_ADD_INT | 349,680 | 0.1% | 97.5% |
| LOAD_CONST COMPARE_OP_INT | 346,440 | 0.1% | 97.6% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 346,440 | 0.1% | 97.7% |
| LOAD_FAST CALL_LEN | 345,840 | 0.1% | 97.7% |
| BUILD_LIST LOAD_CONST | 345,360 | 0.1% | 97.8% |
| RESUME_CHECK LOAD_FAST | 345,180 | 0.1% | 97.9% |
| STORE_FAST BUILD_LIST | 345,120 | 0.1% | 98.0% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 345,120 | 0.1% | 98.0% |
| LOAD_CONST LIST_EXTEND | 345,120 | 0.1% | 98.1% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 345,120 | 0.1% | 98.2% |
| SWAP SWAP | 175,080 | 0.0% | 98.2% |
| SWAP STORE_SUBSCR_LIST_INT | 175,080 | 0.0% | 98.2% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 175,080 | 0.0% | 98.3% |
| BINARY_OP SWAP | 174,960 | 0.0% | 98.3% |
| LOAD_FAST CALL_BUILTIN_CLASS | 174,040 | 0.0% | 98.3% |
| COPY COPY | 174,000 | 0.0% | 98.4% |
| COPY BINARY_SUBSCR_LIST_INT | 174,000 | 0.0% | 98.4% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 173,640 | 0.0% | 98.4% |
| LIST_APPEND ENTER_EXECUTOR | 173,220 | 0.0% | 98.5% |
| SWAP BUILD_LIST | 173,160 | 0.0% | 98.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 173,160 | 0.0% | 98.5% |
| LOAD_FAST_AND_CLEAR SWAP | 173,160 | 0.0% | 98.6% |
| GET_ITER LOAD_FAST_AND_CLEAR | 173,160 | 0.0% | 98.6% |
| BUILD_LIST SWAP | 173,160 | 0.0% | 98.6% |
| SWAP FOR_ITER_RANGE | 173,040 | 0.0% | 98.7% |
| BINARY_OP_ADD_INT BINARY_SLICE | 173,040 | 0.0% | 98.7% |
| STORE_FAST STORE_FAST | 172,920 | 0.0% | 98.7% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 172,920 | 0.0% | 98.8% |
| LOAD_FAST COPY | 172,800 | 0.0% | 98.8% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 172,800 | 0.0% | 98.8% |
| LOAD_FAST RETURN_VALUE | 172,740 | 0.0% | 98.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 173,040 | 99.9% |
| LOAD_CONST | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 172,560 | 99.7% |
| CALL_BUILTIN_FAST | 480 | 0.3% |
| LOAD_FAST | 120 | 0.1% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 100.0% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 864,840 | 100.0% |
| CALL | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 691,860 | 80.0% |
| LOAD_FAST_AND_CLEAR | 173,160 | 20.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 172,680 | 50.1% |
| POP_JUMP_IF_FALSE | 172,080 | 49.9% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 172,560 | 50.0% |
| RETURN_CONST | 172,080 | 49.9% |
| LOAD_FAST | 120 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,553,800 | 50.0% |
| LOAD_FAST | 1,553,040 | 50.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,106,200 | 100.0% |
| LOAD_CONST | 480 | 0.0% |
| CALL | 180 | 0.0% |
| LOAD_GLOBAL_MODULE | 80 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 1,553,040 | 75.0% |
| LOAD_FAST | 172,740 | 8.3% |
| LOAD_ATTR_INSTANCE_VALUE | 172,560 | 8.3% |
| BINARY_OP | 172,560 | 8.3% |
| RETURN_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,553,280 | 75.0% |
| LOAD_FAST | 172,680 | 8.3% |
| CALL_PY_EXACT_ARGS | 172,560 | 8.3% |
| BINARY_OP | 172,560 | 8.3% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,553,040 | 100.0% |
| TO_BOOL | 380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,553,040 | 100.0% |
| TO_BOOL | 380 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 74,423,040 | 70.4% |
| BINARY_SUBSCR_LIST_INT | 25,209,120 | 23.8% |
| LOAD_FAST_LOAD_FAST | 2,760,000 | 2.6% |
| BINARY_OP | 2,447,920 | 2.3% |
| LOAD_FAST | 690,380 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 48,340,320 | 45.7% |
| LOAD_CONST | 23,484,840 | 22.2% |
| LOAD_FAST | 19,171,920 | 18.1% |
| LOAD_FAST_LOAD_FAST | 6,212,160 | 5.9% |
| LIST_APPEND | 2,932,920 | 2.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 345,120 | 49.9% |
| SWAP | 173,160 | 25.0% |
| ENTER_EXECUTOR | 172,560 | 25.0% |
| LOAD_CONST | 240 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 345,360 | 50.0% |
| SWAP | 173,160 | 25.0% |
| STORE_FAST | 172,560 | 25.0% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 260 | 28.9% |
| PUSH_NULL | 180 | 20.0% |
| LOAD_FAST | 180 | 20.0% |
| CALL | 160 | 17.8% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 300 | 33.3% |
| CALL | 160 | 17.8% |
| RETURN_VALUE | 120 | 13.3% |
| GET_ITER | 120 | 13.3% |
| POP_TOP | 60 | 6.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| CALL_INTRINSIC_1 | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 50.0% |
| COPY_FREE_VARS | 60 | 50.0% |


</details>

### CALL_INTRINSIC_1

<details>
<summary> Successors and predecessors for CALL_INTRINSIC_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 75.0% |
| COMPARE_OP | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 75.0% |
| COMPARE_OP | 20 | 25.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 174,000 | 50.0% |
| LOAD_FAST | 172,800 | 49.6% |
| LOAD_FAST_LOAD_FAST | 1,200 | 0.3% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 174,000 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 174,000 | 50.0% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 6,218,200 | 70.6% |
| STORE_FAST | 1,553,040 | 17.6% |
| CALL_LIST_APPEND | 690,240 | 7.8% |
| POP_JUMP_IF_FALSE | 173,640 | 2.0% |
| LIST_APPEND | 173,220 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 6,562,560 | 74.5% |
| LOAD_GLOBAL_MODULE | 1,553,040 | 17.6% |
| STORE_FAST | 172,640 | 2.0% |
| LOAD_FAST | 172,560 | 2.0% |
| BUILD_LIST | 172,560 | 2.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,080 | 90.0% |
| COMPARE_OP_INT | 120 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,080 | 90.0% |
| POP_JUMP_IF_FALSE | 120 | 10.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,760,000 | 100.0% |
| FOR_ITER | 660 | 0.0% |
| SWAP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,760,000 | 100.0% |
| FOR_ITER | 660 | 0.0% |
| STORE_FAST | 120 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 2,760,180 | 100.0% |
| STORE_SUBSCR_LIST_INT | 320 | 0.0% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 2,760,000 | 100.0% |
| FOR_ITER_RANGE | 500 | 0.0% |
| ENTER_EXECUTOR | 60 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,200 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,200 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,932,920 | 100.0% |
| BINARY_SUBSCR_TUPLE_INT | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,760,180 | 94.1% |
| ENTER_EXECUTOR | 173,220 | 5.9% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 345,120 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_LIST | 172,560 | 50.0% |
| STORE_FAST | 172,560 | 50.0% |
| CALL_INTRINSIC_1 | 60 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 220 | 68.8% |
| LOAD_FAST | 60 | 18.8% |
| LOAD_GLOBAL | 20 | 6.2% |
| LOAD_ATTR | 20 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 120 | 37.5% |
| LOAD_ATTR_MODULE | 100 | 31.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 60 | 18.8% |
| PUSH_NULL | 20 | 6.2% |
| LOAD_ATTR | 20 | 6.2% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 28,477,440 | 36.2% |
| BINARY_OP | 23,484,840 | 29.9% |
| BINARY_OP_ADD_INT | 20,707,320 | 26.4% |
| LOAD_FAST | 2,965,680 | 3.8% |
| LOAD_GLOBAL_MODULE | 692,040 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 74,423,040 | 94.7% |
| BINARY_SUBSCR_LIST_INT | 862,800 | 1.1% |
| LOAD_CONST | 690,600 | 0.9% |
| CALL_BUILTIN_CLASS | 690,600 | 0.9% |
| LOAD_FAST | 519,720 | 0.7% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 66.7% |
| LIST_EXTEND | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20,707,680 | 26.2% |
| BINARY_OP | 19,171,920 | 24.2% |
| BINARY_SUBSCR_LIST_INT | 15,545,040 | 19.7% |
| LOAD_ATTR_INSTANCE_VALUE | 6,736,680 | 8.5% |
| LOAD_ATTR_METHOD_NO_DICT | 3,796,320 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 21,070,440 | 26.6% |
| BINARY_OP_ADD_INT | 20,707,200 | 26.2% |
| BINARY_SUBSCR_LIST_INT | 13,120,440 | 16.6% |
| LOAD_ATTR_INSTANCE_VALUE | 7,773,840 | 9.8% |
| LOAD_CONST | 2,965,680 | 3.7% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 173,160 | 99.9% |
| LOAD_FAST_AND_CLEAR | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 173,160 | 99.9% |
| LOAD_FAST_AND_CLEAR | 120 | 0.1% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 27,609,600 | 75.4% |
| BINARY_OP | 6,212,160 | 17.0% |
| STORE_FAST_STORE_FAST | 2,760,000 | 7.5% |
| STORE_FAST | 4,080 | 0.0% |
| POP_JUMP_IF_FALSE | 3,720 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,707,680 | 56.6% |
| BINARY_SUBSCR_LIST_INT | 6,905,280 | 18.9% |
| STORE_SUBSCR_LIST_INT | 6,212,160 | 17.0% |
| BINARY_OP | 2,760,000 | 7.5% |
| COMPARE_OP_INT | 6,120 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 27.3% |
| RETURN_VALUE | 40 | 18.2% |
| PUSH_NULL | 40 | 18.2% |
| RESUME_CHECK | 20 | 9.1% |
| LOAD_FAST_CHECK | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 180 | 81.8% |
| LOAD_GLOBAL_BUILTIN | 20 | 9.1% |
| LOAD_ATTR | 20 | 9.1% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 1,553,040 | 74.7% |
| COMPARE_OP_INT | 525,120 | 25.3% |
| TO_BOOL_BOOL | 120 | 0.0% |
| EXTENDED_ARG | 120 | 0.0% |
| CONTAINS_OP | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,553,460 | 74.7% |
| ENTER_EXECUTOR | 173,640 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 172,560 | 8.3% |
| POP_TOP | 172,080 | 8.3% |
| LOAD_FAST_LOAD_FAST | 3,720 | 0.2% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 172,080 | 99.4% |
| ENTER_EXECUTOR | 600 | 0.3% |
| STORE_ATTR_INSTANCE_VALUE | 360 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 172,680 | 99.8% |
| INTERPRETER_EXIT | 240 | 0.1% |
| EXIT_INIT_CHECK | 120 | 0.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,553,280 | 23.0% |
| CALL_TYPE_1 | 1,553,040 | 23.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,553,040 | 23.0% |
| FOR_ITER_RANGE | 865,180 | 12.8% |
| STORE_FAST | 172,920 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,416,680 | 35.9% |
| LOAD_FAST | 2,246,940 | 33.3% |
| ENTER_EXECUTOR | 1,553,040 | 23.0% |
| BUILD_LIST | 345,120 | 5.1% |
| STORE_FAST | 172,920 | 2.6% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,760,000 | 94.1% |
| UNPACK_SEQUENCE_LIST | 172,560 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,760,000 | 94.1% |
| STORE_FAST | 172,560 | 5.9% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 175,080 | 20.1% |
| BINARY_OP | 174,960 | 20.1% |
| LOAD_FAST_AND_CLEAR | 173,160 | 19.9% |
| BUILD_LIST | 173,160 | 19.9% |
| BINARY_OP_ADD_INT | 172,680 | 19.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 175,080 | 20.1% |
| STORE_SUBSCR_LIST_INT | 175,080 | 20.1% |
| BUILD_LIST | 173,160 | 19.9% |
| FOR_ITER_RANGE | 173,040 | 19.9% |
| STORE_ATTR_INSTANCE_VALUE | 172,560 | 19.8% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20,707,200 | 98.3% |
| LOAD_CONST | 349,680 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,707,320 | 98.3% |
| BINARY_SLICE | 173,040 | 0.8% |
| SWAP | 172,680 | 0.8% |
| STORE_FAST | 3,600 | 0.0% |
| CALL_BUILTIN_CLASS | 240 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 345,120 | 100.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 345,120 | 100.0% |
| STORE_FAST | 120 | 0.0% |


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
| LOAD_CONST | 346,440 | 99.6% |
| BINARY_OP | 1,440 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 172,560 | 49.6% |
| LOAD_CONST | 172,560 | 49.6% |
| BINARY_SUBSCR_LIST_INT | 2,760 | 0.8% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 48,340,320 | 69.6% |
| LOAD_FAST | 13,120,440 | 18.9% |
| LOAD_FAST_LOAD_FAST | 6,905,280 | 9.9% |
| LOAD_CONST | 862,800 | 1.2% |
| COPY | 174,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 28,477,440 | 41.0% |
| BINARY_OP | 25,209,120 | 36.3% |
| LOAD_FAST | 15,545,040 | 22.4% |
| STORE_FAST | 172,800 | 0.2% |
| LOAD_FAST_LOAD_FAST | 1,200 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 480 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 690,600 | 79.8% |
| LOAD_FAST | 174,040 | 20.1% |
| BINARY_OP_ADD_INT | 240 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 864,840 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 120 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 517,800 | 60.0% |
| LOAD_FAST | 345,840 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 518,160 | 60.0% |
| LOAD_GLOBAL_BUILTIN | 172,680 | 20.0% |
| COMPARE_OP_INT | 172,680 | 20.0% |
| BINARY_SUBSCR_DICT | 120 | 0.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 2,760,960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,070,720 | 75.0% |
| ENTER_EXECUTOR | 690,240 | 25.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,553,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,553,040 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,553,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,553,040 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,553,360 | 75.0% |
| RETURN_VALUE | 172,560 | 8.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 172,560 | 8.3% |
| BINARY_SLICE | 172,560 | 8.3% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,071,260 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,553,040 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,553,040 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 346,440 | 66.0% |
| CALL_LEN | 172,680 | 32.9% |
| LOAD_FAST_LOAD_FAST | 6,120 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 525,120 | 100.0% |
| EXTENDED_ARG | 120 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 691,860 | 79.9% |
| SWAP | 173,040 | 20.0% |
| JUMP_BACKWARD | 500 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 865,180 | 100.0% |
| STORE_FAST_LOAD_FAST | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_CONST | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,773,840 | 100.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| COPY | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,736,680 | 86.7% |
| CALL_LEN | 517,800 | 6.7% |
| LOAD_ATTR_METHOD_WITH_VALUES | 172,680 | 2.2% |
| RETURN_VALUE | 172,560 | 2.2% |
| LOAD_CONST | 172,560 | 2.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,243,280 | 59.1% |
| LOAD_GLOBAL_MODULE | 1,553,040 | 40.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,796,320 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 172,680 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 172,560 | 99.8% |
| LOAD_FAST | 240 | 0.1% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,553,460 | 100.0% |
| ENTER_EXECUTOR | 240 | 0.0% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,553,800 | 100.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,070,440 | 76.3% |
| ENTER_EXECUTOR | 6,562,560 | 23.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 27,609,600 | 99.9% |
| LOAD_FAST | 23,280 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 172,440 | 99.9% |
| LOAD_ATTR_INSTANCE_VALUE | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 172,560 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,726,120 | 71.4% |
| CALL_LEN | 172,680 | 7.1% |
| POP_TOP | 172,560 | 7.1% |
| POP_JUMP_IF_FALSE | 172,560 | 7.1% |
| LOAD_GLOBAL_MODULE | 172,560 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,416,980 | 100.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| CALL_ISINSTANCE | 120 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,416,680 | 58.3% |
| ENTER_EXECUTOR | 1,553,040 | 37.5% |
| RESUME_CHECK | 172,920 | 4.2% |
| POP_JUMP_IF_FALSE | 1,440 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,553,460 | 37.5% |
| LOAD_ATTR_METHOD_NO_DICT | 1,553,040 | 37.5% |
| LOAD_CONST | 692,040 | 16.7% |
| LOAD_FAST | 173,160 | 4.2% |
| LOAD_GLOBAL_BUILTIN | 172,560 | 4.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 2,071,260 | 92.3% |
| LOAD_ATTR_PROPERTY | 172,560 | 7.7% |
| CACHE | 240 | 0.0% |
| CALL_ALLOC_AND_ENTER_INIT | 120 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,726,120 | 76.9% |
| LOAD_FAST | 345,180 | 15.4% |
| LOAD_GLOBAL_MODULE | 172,920 | 7.7% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 172,560 | 99.5% |
| LOAD_FAST | 720 | 0.4% |
| LOAD_FAST_LOAD_FAST | 120 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 172,680 | 99.6% |
| RETURN_CONST | 360 | 0.2% |
| LOAD_GLOBAL_MODULE | 240 | 0.1% |
| BUILD_LIST | 120 | 0.1% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,212,160 | 97.1% |
| SWAP | 175,080 | 2.7% |
| LOAD_FAST | 4,920 | 0.1% |
| BINARY_OP | 2,880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,218,200 | 97.2% |
| LOAD_FAST | 175,080 | 2.7% |
| LOAD_FAST_LOAD_FAST | 1,440 | 0.0% |
| JUMP_BACKWARD | 320 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 120 | 100.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_EXTEND | 172,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 172,560 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 2,760,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,760,000 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     73579320 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      6405600 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1553040 | 100.0% |
|          hit |          120 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 380 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 380 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |    105675720 | 81.9% |
|          hit |     23318100 | 18.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.1% |
| Failure | 27,280 | 99.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| xor | 7,840 | 28.7% |
| and int | 7,840 | 28.7% |
| rshift | 5,880 | 21.6% |
| remainder | 5,180 | 19.0% |
| lshift | 280 | 1.0% |
| or | 120 | 0.4% |
| floor divide | 100 | 0.4% |
| add other | 40 | 0.1% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          660 | 0.0% |
|          hit |     13119720 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 33.3% |
| Failure | 160 | 66.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 37.5% |
| wrong number arguments | 60 | 37.5% |
| class no vectorcall | 40 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 0.0% |
|          hit |       531720 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| bytes | 20 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2760120 | 76.1% |
|          hit |       865400 | 23.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 660 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| zip | 660 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          140 | 0.0% |
|          hit |     43358260 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 88.9% |
| Failure | 20 | 11.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| metaclass attribute | 20 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      8461420 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       173400 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2932560 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 224,688,280 | 44.7% |
| Not specialized | 115,031,160 | 22.9% |
| Specialized | 163,177,600 | 32.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 105,675,720 | 96.1% |
| FOR_ITER | 2,760,120 | 2.5% |
| TO_BOOL | 1,553,040 | 1.4% |
| CALL | 660 | 0.0% |
| LOAD_ATTR | 140 | 0.0% |
| COMPARE_OP | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_LIST | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 240 | 0.0% |
| Calls to Python functions inlined | 2,761,740 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 2,762,100 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 2,940,940 | 3.9% |
| Frees to freelist | 2,940,900 |  |
| Allocations | 72,883,460 | 96.1% |
| Allocations to 512 bytes | 72,883,300 | 96.1% |
| Allocations to 4 kbytes | 40 | 0.0% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 73,229,100 |  |
| New values | 240 |  |
| Interpreter increfs | 199,163,120 | 73.4% |
| Interpreter decrefs | 256,046,960 | 74.2% |
| Increfs | 72,206,620 | 26.6% |
| Decrefs | 89,243,560 | 25.8% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 79 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 3 |  |
| Method cache dunder hits | 678 |  |
| Method cache dunder misses | 2 |  |


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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
