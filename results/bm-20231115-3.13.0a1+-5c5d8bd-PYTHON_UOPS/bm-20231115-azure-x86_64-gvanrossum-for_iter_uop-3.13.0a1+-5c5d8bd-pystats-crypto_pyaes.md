
# Pystats results

- benchmark: crypto_pyaes
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 75,083,400 | 19.1% | 19.1% |  |
| BINARY_OP | 73,712,760 | 18.8% | 37.9% |  |
| BINARY_SUBSCR_LIST_INT | 54,107,240 | 13.8% | 51.7% |  |
| LOAD_CONST | 43,773,780 | 11.2% | 62.9% |  |
| LOAD_FAST_LOAD_FAST | 20,270,040 | 5.2% | 68.0% |  |
| BINARY_OP_ADD_INT | 13,812,160 | 3.5% | 71.6% |  |
| ENTER_EXECUTOR | 12,437,440 | 3.2% | 74.7% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,978,320 | 3.1% | 77.8% |  |
| LOAD_ATTR_INSTANCE_VALUE | 11,058,080 | 2.8% | 80.6% |  |
| STORE_FAST | 8,991,040 | 2.3% | 82.9% |  |
| STORE_SUBSCR_LIST_INT | 8,527,700 | 2.2% | 85.1% |  |
| LOAD_GLOBAL_MODULE | 5,526,780 | 1.4% | 86.5% |  |
| LOAD_ATTR_METHOD_NO_DICT | 5,061,900 | 1.3% | 87.8% |  |
| PUSH_NULL | 4,142,400 | 1.1% | 88.8% |  |
| FOR_ITER_RANGE | 3,922,040 | 1.0% | 89.8% |  |
| CALL_LIST_APPEND | 3,681,200 | 0.9% | 90.8% |  |
| LOAD_GLOBAL_BUILTIN | 3,222,600 | 0.8% | 91.6% |  |
| RESUME_CHECK | 2,992,340 | 0.8% | 92.4% |  |
| POP_JUMP_IF_FALSE | 2,776,620 | 0.7% | 93.1% |  |
| RETURN_VALUE | 2,762,060 | 0.7% | 93.8% |  |
| CALL_PY_EXACT_ARGS | 2,761,720 | 0.7% | 94.5% |  |
| TO_BOOL | 2,071,460 | 0.5% | 95.0% |  |
| LOAD_ATTR_MODULE | 2,071,380 | 0.5% | 95.5% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,070,700 | 0.5% | 96.1% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 2,070,700 | 0.5% | 96.6% |  |
| CALL_TYPE_1 | 2,070,700 | 0.5% | 97.1% |  |
| SWAP | 1,159,960 | 0.3% | 97.4% |  |
| GET_ITER | 1,153,960 | 0.3% | 97.7% |  |
| CALL_BUILTIN_CLASS | 1,153,520 | 0.3% | 98.0% |  |
| CALL_LEN | 1,151,280 | 0.3% | 98.3% |  |
| LIST_APPEND | 922,580 | 0.2% | 98.5% |  |
| BUILD_LIST | 922,280 | 0.2% | 98.8% |  |
| COMPARE_OP_INT | 703,780 | 0.2% | 98.9% |  |
| COPY | 465,880 | 0.1% | 99.1% |  |
| BINARY_OP_SUBTRACT_INT | 464,660 | 0.1% | 99.2% |  |
| BINARY_OP_MULTIPLY_INT | 460,740 | 0.1% | 99.3% |  |
| LIST_EXTEND | 460,240 | 0.1% | 99.4% |  |
| POP_TOP | 460,000 | 0.1% | 99.5% |  |
| LOAD_FAST_AND_CLEAR | 231,040 | 0.1% | 99.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 231,040 | 0.1% | 99.6% |  |
| BINARY_SLICE | 230,880 | 0.1% | 99.7% |  |
| RETURN_CONST | 230,720 | 0.1% | 99.8% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 230,700 | 0.1% | 99.8% |  |
| STORE_FAST_STORE_FAST | 230,560 | 0.1% | 99.9% |  |
| LOAD_ATTR_PROPERTY | 230,060 | 0.1% | 99.9% |  |
| UNPACK_SEQUENCE_LIST | 230,060 | 0.1% | 100.0% |  |
| JUMP_BACKWARD | 5,860 | 0.0% | 100.0% |  |
| CALL | 2,940 | 0.0% | 100.0% |  |
| LOAD_ATTR | 2,560 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 2,160 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 1,960 | 0.0% | 100.0% |  |
| EXTENDED_ARG | 1,600 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 1,600 | 0.0% | 100.0% |  |
| FOR_ITER | 1,100 | 0.0% | 100.0% |  |
| COMPARE_OP | 540 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 460 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 460 | 0.0% | 100.0% |  |
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
| LOAD_CONST BINARY_OP | 37,540,080 | 9.6% | 9.6% |
| BINARY_OP BINARY_SUBSCR_LIST_INT | 33,376,940 | 8.5% | 18.1% |
| BINARY_SUBSCR_LIST_INT BINARY_OP | 26,241,240 | 6.7% | 24.8% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 18,185,480 | 4.6% | 29.4% |
| BINARY_OP LOAD_FAST | 17,499,640 | 4.5% | 33.9% |
| BINARY_SUBSCR_LIST_INT LOAD_CONST | 14,960,820 | 3.8% | 37.7% |
| BINARY_OP_ADD_INT LOAD_CONST | 13,345,440 | 3.4% | 41.1% |
| LOAD_FAST BINARY_OP_ADD_INT | 13,345,180 | 3.4% | 44.5% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 12,671,940 | 3.2% | 47.7% |
| LOAD_FAST LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,973,880 | 3.1% | 50.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES LOAD_FAST_LOAD_FAST | 11,965,860 | 3.1% | 53.8% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 11,505,480 | 2.9% | 56.7% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 10,367,060 | 2.6% | 59.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 8,983,860 | 2.3% | 61.7% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 8,289,960 | 2.1% | 63.8% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 8,282,880 | 2.1% | 65.9% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 8,282,840 | 2.1% | 68.0% |
| BINARY_OP LOAD_CONST | 7,600,740 | 1.9% | 70.0% |
| ENTER_EXECUTOR BINARY_OP | 6,213,040 | 1.6% | 71.5% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 5,061,900 | 1.3% | 72.8% |
| PUSH_NULL LOAD_FAST | 4,141,600 | 1.1% | 73.9% |
| LOAD_FAST LOAD_CONST | 3,248,820 | 0.8% | 74.7% |
| STORE_FAST LOAD_GLOBAL_MODULE | 3,222,680 | 0.8% | 75.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 3,222,320 | 0.8% | 76.4% |
| STORE_FAST LOAD_FAST | 2,998,820 | 0.8% | 77.1% |
| BINARY_OP CALL_LIST_APPEND | 2,991,120 | 0.8% | 77.9% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 2,991,120 | 0.8% | 78.6% |
| ENTER_EXECUTOR FOR_ITER_RANGE | 2,764,280 | 0.7% | 79.3% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 2,761,720 | 0.7% | 80.0% |
| CALL_LIST_APPEND LOAD_FAST | 2,760,900 | 0.7% | 80.8% |
| BINARY_OP BINARY_OP | 2,566,480 | 0.7% | 81.4% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,301,240 | 0.6% | 82.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,071,380 | 0.5% | 82.5% |
| POP_JUMP_IF_FALSE LOAD_FAST | 2,071,280 | 0.5% | 83.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,071,240 | 0.5% | 83.6% |
| RETURN_VALUE STORE_FAST | 2,071,040 | 0.5% | 84.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,071,000 | 0.5% | 84.6% |
| TO_BOOL POP_JUMP_IF_FALSE | 2,070,740 | 0.5% | 85.2% |
| LOAD_FAST PUSH_NULL | 2,070,720 | 0.5% | 85.7% |
| LOAD_FAST TO_BOOL | 2,070,720 | 0.5% | 86.2% |
| FOR_ITER_RANGE LOAD_GLOBAL_MODULE | 2,070,720 | 0.5% | 86.7% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 2,070,700 | 0.5% | 87.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS RETURN_VALUE | 2,070,700 | 0.5% | 87.8% |
| CALL_TYPE_1 STORE_FAST | 2,070,700 | 0.5% | 88.3% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_FAST | 2,070,680 | 0.5% | 88.9% |
| LOAD_FAST CALL_METHOD_DESCRIPTOR_NOARGS | 2,070,680 | 0.5% | 89.4% |
| LOAD_FAST CALL_TYPE_1 | 2,070,680 | 0.5% | 89.9% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_NO_DICT | 2,070,680 | 0.5% | 90.4% |
| STORE_FAST ENTER_EXECUTOR | 2,070,380 | 0.5% | 91.0% |
| LOAD_CONST BINARY_SUBSCR_LIST_INT | 1,841,400 | 0.5% | 91.4% |
| ENTER_EXECUTOR LOAD_FAST | 1,840,340 | 0.5% | 91.9% |
| FOR_ITER_RANGE STORE_FAST | 1,386,800 | 0.4% | 92.3% |
| CALL_BUILTIN_CLASS GET_ITER | 1,153,460 | 0.3% | 92.6% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 923,120 | 0.2% | 92.8% |
| GET_ITER FOR_ITER_RANGE | 922,880 | 0.2% | 93.0% |
| BINARY_OP LIST_APPEND | 922,180 | 0.2% | 93.3% |
| LOAD_CONST LOAD_CONST | 921,400 | 0.2% | 93.5% |
| LOAD_FAST BINARY_OP | 921,140 | 0.2% | 93.7% |
| LOAD_CONST CALL_BUILTIN_CLASS | 921,120 | 0.2% | 94.0% |
| LIST_APPEND ENTER_EXECUTOR | 920,540 | 0.2% | 94.2% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 920,300 | 0.2% | 94.4% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 919,980 | 0.2% | 94.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 703,640 | 0.2% | 94.8% |
| LOAD_CONST LOAD_FAST | 693,440 | 0.2% | 95.0% |
| CALL_LEN LOAD_CONST | 690,740 | 0.2% | 95.2% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 690,240 | 0.2% | 95.4% |
| ENTER_EXECUTOR CALL_LIST_APPEND | 690,000 | 0.2% | 95.6% |
| ENTER_EXECUTOR LOAD_ATTR_INSTANCE_VALUE | 690,000 | 0.2% | 95.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 466,680 | 0.1% | 95.8% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 465,340 | 0.1% | 96.0% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 462,300 | 0.1% | 96.1% |
| LOAD_CONST COMPARE_OP_INT | 461,960 | 0.1% | 96.2% |
| BUILD_LIST LOAD_CONST | 461,080 | 0.1% | 96.3% |
| LOAD_FAST CALL_LEN | 460,800 | 0.1% | 96.4% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 460,600 | 0.1% | 96.6% |
| LOAD_FAST BINARY_OP_MULTIPLY_INT | 460,560 | 0.1% | 96.7% |
| RESUME_CHECK LOAD_FAST | 460,420 | 0.1% | 96.8% |
| LOAD_CONST LIST_EXTEND | 460,160 | 0.1% | 96.9% |
| STORE_FAST BUILD_LIST | 460,160 | 0.1% | 97.0% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 234,040 | 0.1% | 97.1% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 233,860 | 0.1% | 97.1% |
| SWAP SWAP | 233,820 | 0.1% | 97.2% |
| SWAP STORE_SUBSCR_LIST_INT | 233,700 | 0.1% | 97.3% |
| BINARY_OP SWAP | 233,520 | 0.1% | 97.3% |
| COPY COPY | 232,700 | 0.1% | 97.4% |
| COPY BINARY_SUBSCR_LIST_INT | 232,580 | 0.1% | 97.4% |
| LOAD_FAST CALL_BUILTIN_CLASS | 231,880 | 0.1% | 97.5% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 231,440 | 0.1% | 97.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 231,000 | 0.1% | 97.6% |
| GET_ITER LOAD_FAST_AND_CLEAR | 230,880 | 0.1% | 97.7% |
| BUILD_LIST SWAP | 230,880 | 0.1% | 97.7% |
| LOAD_FAST COPY | 230,880 | 0.1% | 97.8% |
| LOAD_FAST_AND_CLEAR SWAP | 230,880 | 0.1% | 97.9% |
| SWAP BUILD_LIST | 230,880 | 0.1% | 97.9% |
| BINARY_OP_ADD_INT BINARY_SLICE | 230,680 | 0.1% | 98.0% |
| SWAP FOR_ITER_RANGE | 230,620 | 0.1% | 98.0% |
| STORE_FAST STORE_FAST | 230,560 | 0.1% | 98.1% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_ATTR_METHOD_WITH_VALUES | 230,480 | 0.1% | 98.1% |
| RETURN_VALUE LOAD_FAST | 230,460 | 0.1% | 98.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 230,400 | 0.1% | 98.3% |


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
| CALL_BUILTIN_CLASS | 1,153,460 | 100.0% |
| CALL | 420 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 922,880 | 80.0% |
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
| POP_JUMP_IF_FALSE | 229,600 | 49.9% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 230,040 | 50.0% |
| RETURN_CONST | 229,600 | 49.9% |
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
| LOAD_CONST | 37,540,080 | 50.9% |
| BINARY_SUBSCR_LIST_INT | 26,241,240 | 35.6% |
| ENTER_EXECUTOR | 6,213,040 | 8.4% |
| BINARY_OP | 2,566,480 | 3.5% |
| LOAD_FAST | 921,140 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 33,376,940 | 45.3% |
| LOAD_FAST | 17,499,640 | 23.7% |
| LOAD_FAST_LOAD_FAST | 8,282,880 | 11.2% |
| LOAD_CONST | 7,600,740 | 10.3% |
| CALL_LIST_APPEND | 2,991,120 | 4.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 460,160 | 49.9% |
| SWAP | 230,880 | 25.0% |
| FOR_ITER_RANGE | 230,080 | 24.9% |
| LOAD_CONST | 920 | 0.1% |
| STORE_ATTR_INSTANCE_VALUE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 461,080 | 50.0% |
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
| COPY | 232,700 | 49.9% |
| LOAD_FAST | 230,880 | 49.6% |
| LOAD_FAST_LOAD_FAST | 1,820 | 0.4% |
| LOAD_CONST | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 232,700 | 49.9% |
| BINARY_SUBSCR_LIST_INT | 232,580 | 49.9% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 0.1% |
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
| STORE_SUBSCR_LIST_INT | 8,289,960 | 66.7% |
| STORE_FAST | 2,070,380 | 16.6% |
| LIST_APPEND | 920,540 | 7.4% |
| CALL_LIST_APPEND | 919,980 | 7.4% |
| POP_JUMP_IF_FALSE | 234,040 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 6,213,040 | 50.0% |
| FOR_ITER_RANGE | 2,764,280 | 22.2% |
| LOAD_FAST | 1,840,340 | 14.8% |
| CALL_LIST_APPEND | 690,000 | 5.5% |
| LOAD_ATTR_INSTANCE_VALUE | 690,000 | 5.5% |


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
| ENTER_EXECUTOR | 1,100 | 68.8% |
| JUMP_BACKWARD | 340 | 21.2% |
| POP_JUMP_IF_FALSE | 160 | 10.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 580 | 52.7% |
| SWAP | 260 | 23.6% |
| GET_ITER | 200 | 18.2% |
| FOR_ITER | 60 | 5.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 440 | 40.0% |
| FOR_ITER_RANGE | 280 | 25.5% |
| STORE_FAST | 260 | 23.6% |
| FOR_ITER | 60 | 5.5% |
| UNPACK_SEQUENCE | 40 | 3.6% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 2,040 | 34.8% |
| STORE_SUBSCR_LIST_INT | 1,600 | 27.3% |
| POP_JUMP_IF_FALSE | 680 | 11.6% |
| STORE_FAST | 420 | 7.2% |
| EXTENDED_ARG | 340 | 5.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 3,980 | 67.9% |
| LOAD_FAST_LOAD_FAST | 640 | 10.9% |
| FOR_ITER | 580 | 9.9% |
| ENTER_EXECUTOR | 340 | 5.8% |
| LOAD_FAST | 320 | 5.5% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 1,600 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,600 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 922,180 | 100.0% |
| BINARY_SUBSCR_TUPLE_INT | 380 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 920,540 | 99.8% |
| JUMP_BACKWARD | 2,040 | 0.2% |


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
| BINARY_SUBSCR_LIST_INT | 14,960,820 | 34.2% |
| BINARY_OP_ADD_INT | 13,345,440 | 30.5% |
| BINARY_OP | 7,600,740 | 17.4% |
| LOAD_FAST | 3,248,820 | 7.4% |
| LOAD_GLOBAL_MODULE | 923,120 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 37,540,080 | 85.8% |
| BINARY_SUBSCR_LIST_INT | 1,841,400 | 4.2% |
| LOAD_CONST | 921,400 | 2.1% |
| CALL_BUILTIN_CLASS | 921,120 | 2.1% |
| LOAD_FAST | 693,440 | 1.6% |


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
| BINARY_OP | 17,499,640 | 23.3% |
| BINARY_SUBSCR_LIST_INT | 12,671,940 | 16.9% |
| LOAD_FAST_LOAD_FAST | 11,505,480 | 15.3% |
| LOAD_ATTR_INSTANCE_VALUE | 8,983,860 | 12.0% |
| LOAD_ATTR_METHOD_NO_DICT | 5,061,900 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 18,185,480 | 24.2% |
| BINARY_OP_ADD_INT | 13,345,180 | 17.8% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,973,880 | 15.9% |
| LOAD_ATTR_INSTANCE_VALUE | 10,367,060 | 13.8% |
| LOAD_CONST | 3,248,820 | 4.3% |


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
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 11,965,860 | 59.0% |
| BINARY_OP | 8,282,880 | 40.9% |
| POP_JUMP_IF_FALSE | 6,780 | 0.0% |
| STORE_FAST | 6,060 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 2,280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,505,480 | 56.8% |
| STORE_SUBSCR_LIST_INT | 8,282,840 | 40.9% |
| BINARY_SUBSCR_LIST_INT | 465,340 | 2.3% |
| COMPARE_OP_INT | 8,460 | 0.0% |
| LOAD_CONST | 4,620 | 0.0% |


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
| TO_BOOL | 2,070,740 | 74.6% |
| COMPARE_OP_INT | 703,640 | 25.3% |
| ENTER_EXECUTOR | 1,500 | 0.1% |
| COMPARE_OP | 280 | 0.0% |
| CONTAINS_OP | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,071,280 | 74.6% |
| ENTER_EXECUTOR | 234,040 | 8.4% |
| LOAD_GLOBAL_BUILTIN | 230,040 | 8.3% |
| POP_TOP | 229,600 | 8.3% |
| LOAD_FAST_LOAD_FAST | 6,780 | 0.2% |


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
| POP_TOP | 229,600 | 99.5% |
| ENTER_EXECUTOR | 480 | 0.2% |
| STORE_ATTR_INSTANCE_VALUE | 420 | 0.2% |
| FOR_ITER_RANGE | 160 | 0.1% |
| STORE_ATTR | 60 | 0.0% |

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
| FOR_ITER_RANGE | 1,386,800 | 15.4% |
| BINARY_SUBSCR_LIST_INT | 231,440 | 2.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,222,680 | 35.8% |
| LOAD_FAST | 2,998,820 | 33.4% |
| ENTER_EXECUTOR | 2,070,380 | 23.0% |
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
| UNPACK_SEQUENCE_LIST | 230,060 | 99.8% |
| UNPACK_SEQUENCE_TWO_TUPLE | 460 | 0.2% |
| UNPACK_SEQUENCE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 230,080 | 99.8% |
| LOAD_FAST_LOAD_FAST | 480 | 0.2% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 233,820 | 20.2% |
| BINARY_OP | 233,520 | 20.1% |
| BUILD_LIST | 230,880 | 19.9% |
| LOAD_FAST_AND_CLEAR | 230,880 | 19.9% |
| BINARY_OP_ADD_INT | 230,380 | 19.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 233,820 | 20.2% |
| STORE_SUBSCR_LIST_INT | 233,700 | 20.1% |
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
| LOAD_FAST | 13,345,180 | 96.6% |
| LOAD_CONST | 466,680 | 3.4% |
| BINARY_OP | 300 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 13,345,440 | 96.6% |
| BINARY_SLICE | 230,680 | 1.7% |
| SWAP | 230,380 | 1.7% |
| STORE_FAST | 5,380 | 0.0% |
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
| LOAD_CONST | 462,300 | 99.5% |
| BINARY_OP | 2,360 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 230,060 | 49.5% |
| STORE_FAST | 230,060 | 49.5% |
| BINARY_SUBSCR_LIST_INT | 4,460 | 1.0% |
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
| BINARY_OP | 33,376,940 | 61.7% |
| LOAD_FAST | 18,185,480 | 33.6% |
| LOAD_CONST | 1,841,400 | 3.4% |
| LOAD_FAST_LOAD_FAST | 465,340 | 0.9% |
| COPY | 232,580 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 26,241,240 | 48.5% |
| LOAD_CONST | 14,960,820 | 27.7% |
| LOAD_FAST | 12,671,940 | 23.4% |
| STORE_FAST | 231,440 | 0.4% |
| LOAD_FAST_LOAD_FAST | 1,800 | 0.0% |


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
| LOAD_CONST | 921,120 | 79.9% |
| LOAD_FAST | 231,880 | 20.1% |
| CALL | 280 | 0.0% |
| BINARY_OP_ADD_INT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,153,460 | 100.0% |
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
| ENTER_EXECUTOR | 919,980 | 25.0% |
| JUMP_BACKWARD | 320 | 0.0% |


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
| LOAD_CONST | 461,960 | 65.6% |
| CALL_LEN | 230,160 | 32.7% |
| LOAD_FAST_LOAD_FAST | 8,460 | 1.2% |
| ENTER_EXECUTOR | 2,980 | 0.4% |
| COMPARE_OP | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 703,640 | 100.0% |
| EXTENDED_ARG | 140 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,764,280 | 70.5% |
| GET_ITER | 922,880 | 23.5% |
| SWAP | 230,620 | 5.9% |
| JUMP_BACKWARD | 3,980 | 0.1% |
| FOR_ITER | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,070,720 | 52.8% |
| STORE_FAST | 1,386,800 | 35.4% |
| BUILD_LIST | 230,080 | 5.9% |
| LOAD_FAST | 230,080 | 5.9% |
| JUMP_FORWARD | 1,600 | 0.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,367,060 | 93.8% |
| ENTER_EXECUTOR | 690,000 | 6.2% |
| LOAD_ATTR | 460 | 0.0% |
| COPY | 440 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,983,860 | 81.2% |
| LOAD_CONST | 920,300 | 8.3% |
| CALL_LEN | 690,240 | 6.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 230,480 | 2.1% |
| RETURN_VALUE | 230,060 | 2.1% |


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
| LOAD_ATTR_INSTANCE_VALUE | 230,480 | 99.9% |
| LOAD_FAST | 120 | 0.1% |
| LOAD_ATTR | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 230,040 | 99.7% |
| LOAD_FAST | 580 | 0.3% |
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
| LOAD_FAST | 11,973,880 | 100.0% |
| ENTER_EXECUTOR | 4,080 | 0.0% |
| LOAD_ATTR | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 11,965,860 | 99.9% |
| LOAD_FAST | 12,320 | 0.1% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_PROPERTY

<details>
<summary> Successors and predecessors for LOAD_ATTR_PROPERTY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 229,600 | 99.8% |
| LOAD_ATTR_INSTANCE_VALUE | 440 | 0.2% |
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
| STORE_FAST | 3,222,680 | 58.3% |
| FOR_ITER_RANGE | 2,070,720 | 37.5% |
| RESUME_CHECK | 230,400 | 4.2% |
| POP_JUMP_IF_FALSE | 1,800 | 0.0% |
| LOAD_GLOBAL | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,071,240 | 37.5% |
| LOAD_ATTR_METHOD_NO_DICT | 2,070,680 | 37.5% |
| LOAD_CONST | 923,120 | 16.7% |
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
| LOAD_FAST_LOAD_FAST | 8,282,840 | 97.1% |
| SWAP | 233,700 | 2.7% |
| LOAD_FAST | 6,480 | 0.1% |
| BINARY_OP | 4,480 | 0.1% |
| STORE_SUBSCR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 8,289,960 | 97.2% |
| LOAD_FAST | 233,860 | 2.7% |
| LOAD_FAST_LOAD_FAST | 2,280 | 0.0% |
| JUMP_BACKWARD | 1,600 | 0.0% |


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
| FOR_ITER | 440 | 95.7% |
| UNPACK_SEQUENCE | 20 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 460 | 100.0% |


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
|     deferred | 73,682,740 | 83.3% |
|          hit | 14,737,620 | 16.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 500 | 1.7% |
| Failure | 29,520 | 98.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| xor | 9,760 | 33.1% |
| and int | 8,600 | 29.1% |
| remainder | 4,800 | 16.3% |
| rshift | 3,880 | 13.1% |
| lshift | 1,040 | 3.5% |
| or | 720 | 2.4% |
| floor divide | 360 | 1.2% |
| add other | 240 | 0.8% |
| multiply different types | 120 | 0.4% |


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
|          hit | 54,107,760 | 100.0% |

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
|          hit | 14,960,480 | 100.0% |

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
|          hit | 703,780 | 99.9% |

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
|     deferred | 760 | 0.0% |
|          hit | 3,922,040 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 82.4% |
| Failure | 60 | 17.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| zip | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,340 | 0.0% |
|          hit | 30,630,440 | 100.0% |

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
|          hit | 8,749,380 | 100.0% |

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
|          hit | 8,527,700 | 100.0% |

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
|          hit | 230,520 | 100.0% |

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
| Basic | 173,708,580 | 44.3% |
| Not specialized | 78,803,940 | 20.1% |
| Specialized hits | 139,793,240 | 35.6% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 73,682,740 | 97.3% |
| TO_BOOL | 2,070,740 | 2.7% |
| CALL | 1,800 | 0.0% |
| LOAD_ATTR | 1,340 | 0.0% |
| BINARY_SUBSCR | 1,080 | 0.0% |
| LOAD_GLOBAL | 980 | 0.0% |
| FOR_ITER | 760 | 0.0% |
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
| Allocations from freelist | 3,920,580 | 3.9% |
| Frees to freelist | 3,921,260 |  |
| Allocations | 97,179,060 | 96.1% |
| Allocations to 512 bytes | 97,178,680 | 96.1% |
| Allocations to 4 kbytes | 220 | 0.0% |
| Allocations over 4 kbytes | 160 | 0.0% |
| Frees | 97,638,860 |  |
| New values | 340 |  |
| Interpreter increfs | 288,662,840 | 79.6% |
| Interpreter decrefs | 369,373,280 | 80.1% |
| Increfs | 73,855,083 | 20.4% |
| Decrefs | 91,705,773 | 19.9% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 2,052 |  |
| Method cache misses | 488 |  |
| Method cache collisions | 385 |  |
| Method cache dunder hits | 857 |  |
| Method cache dunder misses | 103 |  |


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
| Traces created | 340 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 20 | 5.9% |
| Trace too long | 140 | 41.2% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 12,437,440 |  |
| Uops executed | 667,758,080 | 53.69 |

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
| <= 32 | 80 | 23.5% |
| <= 64 | 60 | 17.6% |
| <= 128 | 200 | 58.8% |


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
| <= 16 | 80 | 23.5% |
| <= 32 | 60 | 17.6% |
| <= 64 | 120 | 35.3% |
| <= 128 | 80 | 23.5% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 2,762,200 | 22.2% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 229,620 | 1.8% |
| <= 64 | 701,640 | 5.6% |
| <= 128 | 8,743,360 | 70.3% |
| <= 256 | 460 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 0 | 0.0% |
| <= 65,536 | 0 | 0.0% |
| <= 131,072 | 0 | 0.0% |
| <= 262,144 | 0 | 0.0% |
| <= 524,288 | 160 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 116,543,640 | 17.5% | 17.5% |  |
| LOAD_FAST | 105,976,620 | 15.9% | 33.3% |  |
| LOAD_CONST | 72,319,100 | 10.8% | 44.2% |  |
| _BINARY_OP | 72,082,080 | 10.8% | 54.9% |  |
| BINARY_SUBSCR_LIST_INT | 43,996,680 | 6.6% | 61.5% |  |
| _GUARD_TYPE_VERSION | 27,179,180 | 4.1% | 65.6% |  |
| _GUARD_DORV_VALUES_INST_ATTR_FROM_DICT | 25,094,920 | 3.8% | 69.4% |  |
| _GUARD_KEYS_VERSION | 25,094,920 | 3.8% | 73.1% |  |
| _LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 24,865,320 | 3.7% | 76.8% |  |
| _CHECK_VALIDITY | 19,818,660 | 3.0% | 79.8% |  |
| STORE_FAST | 19,351,460 | 2.9% | 82.7% |  |
| _GUARD_BOTH_INT | 16,352,680 | 2.4% | 85.2% |  |
| _BINARY_OP_ADD_INT | 14,963,860 | 2.2% | 87.4% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 14,051,560 | 2.1% | 89.5% | 19.7% |
| _ITER_CHECK_RANGE | 14,051,560 | 2.1% | 91.6% |  |
| _ITER_NEXT_RANGE | 11,287,280 | 1.7% | 93.3% |  |
| _EXIT_TRACE | 9,671,500 | 1.4% | 94.8% |  |
| _JUMP_TO_TOP | 3,687,680 | 0.6% | 95.3% |  |
| LIST_APPEND | 3,684,460 | 0.6% | 95.9% |  |
| _FOR_ITER_TIER_TWO | 3,679,680 | 0.6% | 96.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 3,679,520 | 0.6% | 97.0% |  |
| _GUARD_GLOBALS_VERSION | 2,531,560 | 0.4% | 97.3% |  |
| _LOAD_GLOBAL_MODULE | 2,531,560 | 0.4% | 97.7% |  |
| GET_ITER | 1,841,320 | 0.3% | 98.0% |  |
| CALL_BUILTIN_CLASS | 1,841,320 | 0.3% | 98.3% |  |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 1,394,260 | 0.2% | 98.5% |  |
| _LOAD_ATTR_INSTANCE_VALUE | 1,394,260 | 0.2% | 98.7% |  |
| _BINARY_OP_MULTIPLY_INT | 1,380,000 | 0.2% | 98.9% |  |
| BINARY_SLICE | 690,240 | 0.1% | 99.0% |  |
| RESUME_CHECK | 690,000 | 0.1% | 99.1% |  |
| _POP_FRAME | 690,000 | 0.1% | 99.2% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 690,000 | 0.1% | 99.3% |  |
| _CHECK_PEP_523 | 690,000 | 0.1% | 99.4% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 690,000 | 0.1% | 99.5% |  |
| _CHECK_STACK_SPACE | 690,000 | 0.1% | 99.6% |  |
| _INIT_CALL_PY_EXACT_ARGS | 690,000 | 0.1% | 99.7% |  |
| _PUSH_FRAME | 690,000 | 0.1% | 99.8% |  |
| _SAVE_RETURN_OFFSET | 690,000 | 0.1% | 99.9% |  |
| COPY | 238,760 | 0.0% | 100.0% |  |
| _LOAD_ATTR_METHOD_WITH_VALUES | 229,600 | 0.0% | 100.0% |  |
| STORE_SUBSCR_LIST_INT | 12,900 | 0.0% | 100.0% |  |
| _BINARY_OP_SUBTRACT_INT | 8,820 | 0.0% | 100.0% |  |
| SWAP | 6,920 | 0.0% | 100.0% |  |
| _GUARD_IS_TRUE_POP | 4,960 | 0.0% | 100.0% | 30.2% |
| COMPARE_OP_INT | 4,960 | 0.0% | 100.0% |  |
| BUILD_LIST | 2,600 | 0.0% | 100.0% |  |
| POP_TOP | 480 | 0.0% | 100.0% |  |
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
Stats gathered on: 2023-11-16
