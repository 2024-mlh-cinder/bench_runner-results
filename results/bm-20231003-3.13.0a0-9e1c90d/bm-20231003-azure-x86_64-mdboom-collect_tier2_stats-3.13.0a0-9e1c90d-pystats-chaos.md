
# Pystats results

- benchmark: chaos
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 111,094,680 | 20.3% | 20.3% |  |
| LOAD_ATTR_INSTANCE_VALUE | 56,937,300 | 10.4% | 30.7% |  |
| LOAD_FAST_LOAD_FAST | 51,421,920 | 9.4% | 40.1% |  |
| STORE_FAST | 31,322,460 | 5.7% | 45.8% |  |
| LOAD_CONST | 26,111,880 | 4.8% | 50.6% |  |
| BINARY_OP_SUBTRACT_INT | 26,105,760 | 4.8% | 55.4% |  |
| BINARY_OP_MULTIPLY_FLOAT | 23,100,000 | 4.2% | 59.6% |  |
| BINARY_OP | 18,604,560 | 3.4% | 63.0% |  |
| BINARY_SUBSCR_LIST_INT | 18,522,180 | 3.4% | 66.4% |  |
| BINARY_OP_ADD_FLOAT | 15,000,120 | 2.7% | 69.1% |  |
| BINARY_OP_ADD_INT | 14,627,760 | 2.7% | 71.8% |  |
| RESUME_CHECK | 14,400,240 | 2.6% | 74.4% |  |
| RETURN_VALUE | 14,100,120 | 2.6% | 77.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 13,203,960 | 2.4% | 79.4% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,100,000 | 1.5% | 80.9% |  |
| CALL_PY_EXACT_ARGS | 7,800,000 | 1.4% | 82.3% |  |
| LOAD_GLOBAL_MODULE | 7,042,180 | 1.3% | 83.6% |  |
| POP_JUMP_IF_FALSE | 6,794,280 | 1.2% | 84.8% |  |
| ENTER_EXECUTOR | 6,776,400 | 1.2% | 86.1% |  |
| LOAD_GLOBAL_BUILTIN | 6,306,420 | 1.2% | 87.2% |  |
| RETURN_CONST | 4,500,180 | 0.8% | 88.1% |  |
| POP_JUMP_IF_NOT_NONE | 4,500,000 | 0.8% | 88.9% |  |
| COMPARE_OP | 4,200,980 | 0.8% | 89.6% |  |
| EXIT_INIT_CHECK | 4,200,060 | 0.8% | 90.4% |  |
| CALL_ALLOC_AND_ENTER_INIT | 4,200,060 | 0.8% | 91.2% |  |
| STORE_SUBSCR_LIST_INT | 3,900,000 | 0.7% | 91.9% |  |
| BINARY_SUBSCR_TUPLE_INT | 3,900,000 | 0.7% | 92.6% |  |
| PUSH_NULL | 2,894,340 | 0.5% | 93.1% |  |
| GET_ITER | 2,700,120 | 0.5% | 93.6% |  |
| FOR_ITER_RANGE | 2,700,120 | 0.5% | 94.1% |  |
| CALL_BUILTIN_CLASS | 2,700,120 | 0.5% | 94.6% |  |
| COMPARE_OP_INT | 2,594,160 | 0.5% | 95.1% |  |
| CALL_LEN | 2,405,580 | 0.4% | 95.5% |  |
| CALL_BUILTIN_O | 2,293,980 | 0.4% | 95.9% |  |
| CALL | 2,100,920 | 0.4% | 96.3% |  |
| POP_JUMP_IF_TRUE | 2,100,060 | 0.4% | 96.7% |  |
| SWAP | 2,094,540 | 0.4% | 97.1% |  |
| BUILD_TUPLE | 1,800,120 | 0.3% | 97.4% |  |
| BINARY_OP_SUBTRACT_FLOAT | 1,800,060 | 0.3% | 97.8% |  |
| LOAD_ATTR_MODULE | 1,500,160 | 0.3% | 98.0% |  |
| INTERPRETER_EXIT | 1,500,060 | 0.3% | 98.3% |  |
| COMPARE_OP_FLOAT | 1,200,000 | 0.2% | 98.5% |  |
| POP_TOP | 1,194,660 | 0.2% | 98.7% |  |
| LOAD_ATTR | 600,300 | 0.1% | 98.8% |  |
| BUILD_LIST | 600,120 | 0.1% | 99.0% |  |
| LOAD_FAST_AND_CLEAR | 600,060 | 0.1% | 99.1% |  |
| LIST_APPEND | 600,060 | 0.1% | 99.2% |  |
| LOAD_ATTR_METHOD_NO_DICT | 600,000 | 0.1% | 99.3% |  |
| IS_OP | 600,000 | 0.1% | 99.4% |  |
| COPY | 600,000 | 0.1% | 99.5% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 600,000 | 0.1% | 99.6% |  |
| TO_BOOL_BOOL | 300,120 | 0.1% | 99.7% |  |
| CALL_ISINSTANCE | 300,120 | 0.1% | 99.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 300,000 | 0.1% | 99.8% |  |
| UNARY_NEGATIVE | 300,000 | 0.1% | 99.8% |  |
| STORE_FAST_STORE_FAST | 300,000 | 0.1% | 99.9% |  |
| JUMP_FORWARD | 300,000 | 0.1% | 99.9% |  |
| CALL_PY_WITH_DEFAULTS | 300,000 | 0.1% | 100.0% |  |
| BINARY_SUBSCR | 5,620 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 140 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 120 | 0.0% | 100.0% |  |
| TO_BOOL_NONE | 60 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_METHOD | 60 | 0.0% | 100.0% |  |
| CALL_TYPE_1 | 60 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% | 100.0% | 100.0% |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| TO_BOOL | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 52,209,460 | 9.5% | 9.5% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 31,426,020 | 5.7% | 15.3% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 21,600,000 | 3.9% | 19.2% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 16,694,160 | 3.1% | 22.3% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 12,600,180 | 2.3% | 24.6% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 11,700,000 | 2.1% | 26.7% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 11,400,000 | 2.1% | 28.8% |
| STORE_FAST LOAD_FAST | 9,600,240 | 1.8% | 30.6% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 9,600,000 | 1.8% | 32.3% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 9,000,000 | 1.6% | 34.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 8,400,120 | 1.5% | 35.5% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 8,100,000 | 1.5% | 37.0% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 7,805,760 | 1.4% | 38.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 7,800,000 | 1.4% | 39.8% |
| RESUME_CHECK LOAD_FAST | 7,500,060 | 1.4% | 41.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 7,500,000 | 1.4% | 42.6% |
| BINARY_OP STORE_FAST | 7,200,000 | 1.3% | 43.9% |
| RETURN_VALUE STORE_FAST | 6,900,060 | 1.3% | 45.1% |
| BINARY_OP_SUBTRACT_INT BINARY_SUBSCR_LIST_INT | 6,600,000 | 1.2% | 46.3% |
| BINARY_OP_ADD_INT LOAD_FAST | 6,600,000 | 1.2% | 47.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 6,005,580 | 1.1% | 48.6% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 5,700,000 | 1.0% | 49.7% |
| LOAD_FAST RETURN_VALUE | 5,633,580 | 1.0% | 50.7% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 5,400,000 | 1.0% | 51.7% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_ADD_INT | 5,400,000 | 1.0% | 52.7% |
| BINARY_OP_SUBTRACT_INT BINARY_OP | 5,400,000 | 1.0% | 53.7% |
| LOAD_FAST LOAD_CONST | 5,100,360 | 0.9% | 54.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,805,820 | 0.9% | 55.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 4,800,060 | 0.9% | 56.4% |
| BINARY_OP_ADD_INT BINARY_SUBSCR_LIST_INT | 4,800,000 | 0.9% | 57.2% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 4,500,060 | 0.8% | 58.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 4,500,000 | 0.8% | 58.9% |
| BINARY_OP_SUBTRACT_INT LOAD_CONST | 4,500,000 | 0.8% | 59.7% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 4,203,660 | 0.8% | 60.5% |
| RETURN_CONST EXIT_INIT_CHECK | 4,200,060 | 0.8% | 61.2% |
| EXIT_INIT_CHECK RETURN_VALUE | 4,200,060 | 0.8% | 62.0% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 4,200,060 | 0.8% | 62.8% |
| BINARY_OP_SUBTRACT_INT LOAD_FAST | 4,200,000 | 0.8% | 63.6% |
| POP_JUMP_IF_FALSE LOAD_FAST | 4,167,720 | 0.8% | 64.3% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 3,900,180 | 0.7% | 65.0% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 3,900,060 | 0.7% | 65.7% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 3,900,000 | 0.7% | 66.4% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 3,900,000 | 0.7% | 67.2% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 3,900,000 | 0.7% | 67.9% |
| LOAD_CONST BINARY_SUBSCR_TUPLE_INT | 3,900,000 | 0.7% | 68.6% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 3,900,000 | 0.7% | 69.3% |
| BINARY_SUBSCR_LIST_INT LOAD_ATTR_METHOD_WITH_VALUES | 3,900,000 | 0.7% | 70.0% |
| BINARY_OP_ADD_FLOAT CALL_ALLOC_AND_ENTER_INIT | 3,900,000 | 0.7% | 70.7% |
| RETURN_VALUE LOAD_FAST_LOAD_FAST | 3,600,000 | 0.7% | 71.4% |
| POP_JUMP_IF_NOT_NONE LOAD_GLOBAL_MODULE | 3,600,000 | 0.7% | 72.0% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 3,600,000 | 0.7% | 72.7% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 3,600,000 | 0.7% | 73.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 3,600,000 | 0.7% | 74.0% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 3,600,000 | 0.7% | 74.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 3,300,040 | 0.6% | 75.3% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_INT | 3,300,000 | 0.6% | 75.9% |
| LOAD_CONST BINARY_OP | 3,000,120 | 0.5% | 76.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 2,927,760 | 0.5% | 77.0% |
| FOR_ITER_RANGE STORE_FAST | 2,700,120 | 0.5% | 77.5% |
| CALL_BUILTIN_CLASS GET_ITER | 2,700,120 | 0.5% | 77.9% |
| BINARY_OP LOAD_FAST | 2,700,060 | 0.5% | 78.4% |
| LOAD_ATTR_METHOD_WITH_VALUES CALL_PY_EXACT_ARGS | 2,700,000 | 0.5% | 78.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,594,160 | 0.5% | 79.4% |
| PUSH_NULL LOAD_FAST | 2,594,100 | 0.5% | 79.9% |
| LOAD_ATTR_INSTANCE_VALUE CALL_LEN | 2,405,580 | 0.4% | 80.3% |
| COMPARE_OP POP_JUMP_IF_FALSE | 2,400,000 | 0.4% | 80.8% |
| BINARY_SUBSCR_TUPLE_INT COMPARE_OP | 2,400,000 | 0.4% | 81.2% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 2,100,080 | 0.4% | 81.6% |
| GET_ITER FOR_ITER_RANGE | 2,100,060 | 0.4% | 82.0% |
| CALL_LEN LOAD_FAST | 2,100,000 | 0.4% | 82.4% |
| POP_JUMP_IF_FALSE LOAD_FAST_LOAD_FAST | 1,963,440 | 0.4% | 82.7% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 1,841,340 | 0.3% | 83.0% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 1,800,040 | 0.3% | 83.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,800,000 | 0.3% | 83.7% |
| ENTER_EXECUTOR BINARY_OP | 1,800,000 | 0.3% | 84.0% |
| COMPARE_OP POP_JUMP_IF_TRUE | 1,800,000 | 0.3% | 84.4% |
| BINARY_OP_ADD_INT CALL_BUILTIN_CLASS | 1,800,000 | 0.3% | 84.7% |
| LOAD_FAST_LOAD_FAST COMPARE_OP_INT | 1,693,980 | 0.3% | 85.0% |
| BUILD_TUPLE RETURN_VALUE | 1,505,580 | 0.3% | 85.3% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,500,100 | 0.3% | 85.5% |
| LOAD_FAST BINARY_OP | 1,500,080 | 0.3% | 85.8% |
| CACHE RESUME_CHECK | 1,500,060 | 0.3% | 86.1% |
| RETURN_VALUE INTERPRETER_EXIT | 1,500,000 | 0.3% | 86.4% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,500,000 | 0.3% | 86.6% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 1,500,000 | 0.3% | 86.9% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 1,500,000 | 0.3% | 87.2% |
| BINARY_SUBSCR_LIST_INT BUILD_TUPLE | 1,500,000 | 0.3% | 87.5% |
| LOAD_FAST BINARY_SUBSCR_LIST_INT | 1,422,180 | 0.3% | 87.7% |
| LOAD_FAST CALL_BUILTIN_O | 1,393,980 | 0.3% | 88.0% |
| CALL_BUILTIN_O STORE_FAST | 1,393,980 | 0.3% | 88.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,342,060 | 0.2% | 88.5% |
| CALL STORE_FAST | 1,200,060 | 0.2% | 88.7% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP | 1,200,040 | 0.2% | 88.9% |
| POP_JUMP_IF_TRUE LOAD_FAST_LOAD_FAST | 1,200,000 | 0.2% | 89.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,200,000 | 0.2% | 89.4% |
| LOAD_FAST BINARY_OP_ADD_INT | 1,200,000 | 0.2% | 89.6% |
| LOAD_ATTR_INSTANCE_VALUE COMPARE_OP_FLOAT | 1,200,000 | 0.2% | 89.8% |
| LOAD_ATTR_INSTANCE_VALUE BINARY_OP_SUBTRACT_FLOAT | 1,200,000 | 0.2% | 90.0% |
| ENTER_EXECUTOR LOAD_ATTR_INSTANCE_VALUE | 1,200,000 | 0.2% | 90.2% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 1,200,000 | 0.2% | 90.5% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,500,060 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,580 | 99.3% |
| BINARY_SUBSCR | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 5,580 | 99.3% |
| BINARY_SUBSCR | 40 | 0.7% |


</details>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 4,200,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 4,200,060 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,700,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 2,100,060 | 77.8% |
| LOAD_FAST_AND_CLEAR | 600,060 | 22.2% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,500,000 | 100.0% |
| RETURN_CONST | 60 | 0.0% |

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
| STORE_FAST | 600,000 | 50.2% |
| RETURN_CONST | 300,060 | 25.1% |
| SWAP | 294,420 | 24.6% |
| CALL | 120 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900,060 | 75.3% |
| RETURN_VALUE | 294,420 | 24.6% |
| NOP | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,500,100 | 51.8% |
| LOAD_FAST | 794,160 | 27.4% |
| BINARY_SUBSCR_LIST_INT | 600,000 | 20.7% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,594,100 | 89.6% |
| LOAD_GLOBAL_BUILTIN | 300,000 | 10.4% |
| CALL | 240 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,633,580 | 40.0% |
| EXIT_INIT_CHECK | 4,200,060 | 29.8% |
| BUILD_TUPLE | 1,505,580 | 10.7% |
| CALL_BUILTIN_O | 900,000 | 6.4% |
| RETURN_VALUE | 600,000 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,900,060 | 48.9% |
| LOAD_FAST_LOAD_FAST | 3,600,000 | 25.5% |
| INTERPRETER_EXIT | 1,500,000 | 10.6% |
| RETURN_VALUE | 600,000 | 4.3% |
| BINARY_OP | 600,000 | 4.3% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_NONE | 20 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 300,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300,000 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 5,400,000 | 29.0% |
| LOAD_FAST_LOAD_FAST | 3,900,000 | 21.0% |
| LOAD_CONST | 3,000,120 | 16.1% |
| ENTER_EXECUTOR | 1,800,000 | 9.7% |
| LOAD_FAST | 1,500,080 | 8.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,200,000 | 38.7% |
| LOAD_FAST_LOAD_FAST | 5,700,000 | 30.6% |
| LOAD_FAST | 2,700,060 | 14.5% |
| BINARY_OP_ADD_FLOAT | 1,800,040 | 9.7% |
| BINARY_OP | 604,320 | 3.2% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 600,060 | 100.0% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 600,060 | 100.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 1,500,000 | 83.3% |
| RETURN_VALUE | 300,000 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,505,580 | 83.6% |
| SWAP | 294,420 | 16.4% |
| CALL_ISINSTANCE | 120 | 0.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900,100 | 42.8% |
| LOAD_ATTR_INSTANCE_VALUE | 300,000 | 14.3% |
| BINARY_OP_ADD_INT | 300,000 | 14.3% |
| BINARY_OP_ADD_FLOAT | 300,000 | 14.3% |
| BINARY_SUBSCR_LIST_INT | 294,420 | 14.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200,060 | 57.1% |
| RESUME_CHECK | 600,000 | 28.6% |
| LOAD_CONST | 300,000 | 14.3% |
| CALL | 560 | 0.0% |
| POP_TOP | 120 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 2,400,000 | 57.1% |
| BINARY_SUBSCR_LIST_INT | 1,200,000 | 28.6% |
| LOAD_CONST | 300,020 | 7.1% |
| LOAD_FAST | 300,000 | 7.1% |
| COMPARE_OP | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,400,000 | 57.1% |
| POP_JUMP_IF_TRUE | 1,800,000 | 42.8% |
| COMPARE_OP | 960 | 0.0% |
| COMPARE_OP_INT | 20 | 0.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 600,000 | 100.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 50.0% |
| CALL | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 3,900,000 | 57.6% |
| ENTER_EXECUTOR | 1,841,340 | 27.2% |
| LIST_APPEND | 600,060 | 8.9% |
| STORE_FAST | 227,760 | 3.4% |
| POP_JUMP_IF_TRUE | 140,760 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,841,340 | 27.2% |
| BINARY_OP | 1,800,000 | 26.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,200,000 | 17.7% |
| LOAD_FAST | 740,820 | 10.9% |
| STORE_FAST | 600,060 | 8.9% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 600,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 600,000 | 100.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 300,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300,000 | 100.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 600,000 | 100.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 600,060 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,080 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600,000 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |
| LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| PUSH_NULL | 20 | 0.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,100,000 | 31.0% |
| LOAD_ATTR_INSTANCE_VALUE | 6,005,580 | 23.0% |
| LOAD_FAST | 5,100,360 | 19.5% |
| BINARY_OP_SUBTRACT_INT | 4,500,000 | 17.2% |
| LOAD_GLOBAL_BUILTIN | 600,060 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 7,805,760 | 29.9% |
| BINARY_OP_ADD_INT | 7,500,000 | 28.7% |
| BINARY_SUBSCR_TUPLE_INT | 3,900,000 | 14.9% |
| BINARY_OP | 3,000,120 | 11.5% |
| COMPARE_OP_INT | 600,160 | 2.3% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| NOP | 60 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| PUSH_NULL | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 31,426,020 | 28.3% |
| BINARY_OP_MULTIPLY_FLOAT | 11,400,000 | 10.3% |
| STORE_FAST | 9,600,240 | 8.6% |
| BINARY_OP_ADD_FLOAT | 9,000,000 | 8.1% |
| RESUME_CHECK | 7,500,060 | 6.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 52,209,460 | 47.0% |
| BINARY_OP_MULTIPLY_FLOAT | 21,600,000 | 19.4% |
| RETURN_VALUE | 5,633,580 | 5.1% |
| BINARY_OP_SUBTRACT_INT | 5,400,000 | 4.9% |
| LOAD_CONST | 5,100,360 | 4.6% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 600,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 600,060 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 16,694,160 | 32.5% |
| STORE_ATTR_INSTANCE_VALUE | 8,400,120 | 16.3% |
| BINARY_OP | 5,700,000 | 11.1% |
| RESUME_CHECK | 4,500,060 | 8.8% |
| BINARY_SUBSCR_LIST_INT | 3,900,000 | 7.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 12,600,180 | 24.5% |
| BINARY_OP_SUBTRACT_INT | 9,600,000 | 18.7% |
| LOAD_CONST | 8,100,000 | 15.8% |
| BINARY_SUBSCR_LIST_INT | 3,900,000 | 7.6% |
| BINARY_OP | 3,900,000 | 7.6% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 28.6% |
| RETURN_VALUE | 40 | 28.6% |
| RESUME_CHECK | 40 | 28.6% |
| POP_TOP | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 57.1% |
| LOAD_GLOBAL_BUILTIN | 40 | 28.6% |
| LOAD_ATTR | 20 | 14.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,594,160 | 38.2% |
| COMPARE_OP | 2,400,000 | 35.3% |
| COMPARE_OP_FLOAT | 1,200,000 | 17.7% |
| IS_OP | 600,000 | 8.8% |
| TO_BOOL_NONE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,167,720 | 61.3% |
| LOAD_FAST_LOAD_FAST | 1,963,440 | 28.9% |
| LOAD_CONST | 300,000 | 4.4% |
| RETURN_CONST | 296,520 | 4.4% |
| ENTER_EXECUTOR | 66,480 | 1.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,500,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,600,000 | 80.0% |
| LOAD_FAST | 900,000 | 20.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 1,800,000 | 85.7% |
| TO_BOOL_BOOL | 300,060 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,200,000 | 57.1% |
| LOAD_FAST | 459,240 | 21.9% |
| LOAD_GLOBAL_MODULE | 300,000 | 14.3% |
| ENTER_EXECUTOR | 140,760 | 6.7% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 4,203,660 | 93.4% |
| POP_JUMP_IF_FALSE | 296,520 | 6.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 4,200,060 | 93.3% |
| POP_TOP | 300,060 | 6.7% |
| INTERPRETER_EXIT | 60 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 7,200,000 | 23.0% |
| RETURN_VALUE | 6,900,060 | 22.0% |
| BINARY_OP_SUBTRACT_INT | 3,900,180 | 12.5% |
| BINARY_SUBSCR_LIST_INT | 3,600,000 | 11.5% |
| FOR_ITER_RANGE | 2,700,120 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 16,694,160 | 53.3% |
| LOAD_FAST | 9,600,240 | 30.6% |
| LOAD_GLOBAL_BUILTIN | 3,300,040 | 10.5% |
| STORE_FAST | 600,060 | 1.9% |
| POP_TOP | 600,000 | 1.9% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 300,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 300,000 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 600,060 | 28.6% |
| BUILD_LIST | 600,060 | 28.6% |
| BINARY_OP_ADD_FLOAT | 600,000 | 28.6% |
| BUILD_TUPLE | 294,420 | 14.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 600,060 | 28.6% |
| BUILD_LIST | 600,060 | 28.6% |
| STORE_ATTR_INSTANCE_VALUE | 600,000 | 28.6% |
| POP_TOP | 294,420 | 14.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 11,700,000 | 78.0% |
| BINARY_OP | 1,800,040 | 12.0% |
| LOAD_ATTR_INSTANCE_VALUE | 900,080 | 6.0% |
| LOAD_CONST | 600,000 | 4.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,000,000 | 60.0% |
| CALL_ALLOC_AND_ENTER_INIT | 3,900,000 | 26.0% |
| CALL_BUILTIN_O | 900,000 | 6.0% |
| SWAP | 600,000 | 4.0% |
| STORE_FAST | 300,000 | 2.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,500,000 | 51.3% |
| LOAD_ATTR_INSTANCE_VALUE | 5,400,000 | 36.9% |
| LOAD_FAST | 1,200,000 | 8.2% |
| BINARY_SUBSCR_LIST_INT | 527,760 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,600,000 | 45.1% |
| BINARY_SUBSCR_LIST_INT | 4,800,000 | 32.8% |
| CALL_BUILTIN_CLASS | 1,800,000 | 12.3% |
| LOAD_CONST | 600,000 | 4.1% |
| COMPARE_OP_INT | 300,000 | 2.1% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 21,600,000 | 93.5% |
| LOAD_ATTR_INSTANCE_VALUE | 600,000 | 2.6% |
| BINARY_OP_SUBTRACT_FLOAT | 600,000 | 2.6% |
| LOAD_FAST_LOAD_FAST | 300,000 | 1.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 11,700,000 | 50.6% |
| LOAD_FAST | 11,400,000 | 49.4% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,200,000 | 66.7% |
| LOAD_CONST | 600,000 | 33.3% |
| LOAD_FAST | 40 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200,000 | 66.7% |
| BINARY_OP_MULTIPLY_FLOAT | 600,000 | 33.3% |
| STORE_FAST | 60 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 9,600,000 | 36.8% |
| LOAD_CONST | 7,805,760 | 29.9% |
| LOAD_FAST | 5,400,000 | 20.7% |
| LOAD_ATTR_INSTANCE_VALUE | 3,300,000 | 12.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 6,600,000 | 25.3% |
| BINARY_OP | 5,400,000 | 20.7% |
| LOAD_CONST | 4,500,000 | 17.2% |
| LOAD_FAST | 4,200,000 | 16.1% |
| STORE_FAST | 3,900,180 | 14.9% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 6,600,000 | 35.6% |
| BINARY_OP_ADD_INT | 4,800,000 | 25.9% |
| LOAD_FAST_LOAD_FAST | 3,900,000 | 21.1% |
| LOAD_FAST | 1,422,180 | 7.7% |
| BINARY_SUBSCR_TUPLE_INT | 1,200,000 | 6.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,900,000 | 21.1% |
| LOAD_ATTR_METHOD_WITH_VALUES | 3,900,000 | 21.1% |
| STORE_FAST | 3,600,000 | 19.4% |
| LOAD_FAST | 1,500,000 | 8.1% |
| BUILD_TUPLE | 1,500,000 | 8.1% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,900,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP | 2,400,000 | 61.5% |
| BINARY_SUBSCR_LIST_INT | 1,200,000 | 30.8% |
| BINARY_OP | 300,000 | 7.7% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 3,900,000 | 92.9% |
| BINARY_OP | 300,000 | 7.1% |
| LOAD_CONST | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,200,060 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,800,000 | 66.7% |
| BINARY_OP_SUBTRACT_INT | 600,000 | 22.2% |
| CALL_LEN | 300,000 | 11.1% |
| LOAD_FAST | 80 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,700,120 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,393,980 | 60.8% |
| BINARY_OP_ADD_FLOAT | 900,000 | 39.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,393,980 | 60.8% |
| RETURN_VALUE | 900,000 | 39.2% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 300,000 | 100.0% |
| BUILD_TUPLE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 300,120 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,405,580 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,100,000 | 87.3% |
| CALL_BUILTIN_CLASS | 300,000 | 12.5% |
| LOAD_CONST | 5,580 | 0.2% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 600,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 600,000 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,600,000 | 46.2% |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,700,000 | 34.6% |
| LOAD_FAST | 1,500,000 | 19.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 7,800,000 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 300,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 300,000 | 100.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,200,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,200,000 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,693,980 | 65.3% |
| LOAD_CONST | 600,160 | 23.1% |
| BINARY_OP_ADD_INT | 300,000 | 11.6% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,594,160 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,100,060 | 77.8% |
| SWAP | 600,060 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,700,120 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 52,209,460 | 91.7% |
| LOAD_FAST_LOAD_FAST | 2,927,760 | 5.1% |
| ENTER_EXECUTOR | 1,200,000 | 2.1% |
| COPY | 600,000 | 1.1% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 31,426,020 | 55.2% |
| LOAD_CONST | 6,005,580 | 10.5% |
| BINARY_OP_ADD_INT | 5,400,000 | 9.5% |
| BINARY_OP_SUBTRACT_INT | 3,300,000 | 5.8% |
| CALL_LEN | 2,405,580 | 4.2% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 600,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_NOARGS | 600,000 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,900,060 | 48.1% |
| BINARY_SUBSCR_LIST_INT | 3,900,000 | 48.1% |
| ENTER_EXECUTOR | 299,940 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,600,000 | 44.4% |
| CALL_PY_EXACT_ARGS | 2,700,000 | 33.3% |
| LOAD_FAST | 1,800,000 | 22.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,342,060 | 89.5% |
| ENTER_EXECUTOR | 158,040 | 10.5% |
| LOAD_ATTR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,500,100 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,300,040 | 52.3% |
| LOAD_ATTR_INSTANCE_VALUE | 1,500,000 | 23.8% |
| BINARY_OP_SUBTRACT_INT | 600,000 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 300,360 | 4.8% |
| RESUME_CHECK | 300,000 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,805,820 | 76.2% |
| LOAD_CONST | 600,060 | 9.5% |
| LOAD_FAST_LOAD_FAST | 600,000 | 9.5% |
| LOAD_GLOBAL_BUILTIN | 300,360 | 4.8% |
| BUILD_TUPLE | 120 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 3,600,000 | 51.1% |
| RESUME_CHECK | 2,100,080 | 29.8% |
| LOAD_FAST | 1,036,380 | 14.7% |
| POP_JUMP_IF_TRUE | 300,000 | 4.3% |
| BINARY_OP_SUBTRACT_INT | 5,580 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800,060 | 68.2% |
| LOAD_ATTR_MODULE | 1,342,060 | 19.1% |
| IS_OP | 600,000 | 8.5% |
| CALL_ISINSTANCE | 300,000 | 4.3% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### LOAD_SUPER_ATTR_METHOD

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_METHOD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 7,800,000 | 54.2% |
| CALL_ALLOC_AND_ENTER_INIT | 4,200,060 | 29.2% |
| CACHE | 1,500,060 | 10.4% |
| CALL | 600,000 | 4.2% |
| CALL_PY_WITH_DEFAULTS | 300,000 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,500,060 | 52.1% |
| LOAD_FAST_LOAD_FAST | 4,500,060 | 31.2% |
| LOAD_GLOBAL_MODULE | 2,100,080 | 14.6% |
| LOAD_GLOBAL_BUILTIN | 300,000 | 2.1% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 12,600,180 | 95.4% |
| SWAP | 600,000 | 4.5% |
| LOAD_FAST | 3,780 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,400,120 | 63.6% |
| RETURN_CONST | 4,203,660 | 31.8% |
| LOAD_FAST | 300,180 | 2.3% |
| JUMP_FORWARD | 300,000 | 2.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,600,000 | 92.3% |
| BINARY_OP_SUBTRACT_INT | 300,000 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,900,000 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 300,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 300,060 | 100.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |


</details>

### TO_BOOL_NONE

<details>
<summary> Successors and predecessors for TO_BOOL_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| TO_BOOL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 300,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 300,000 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         5580 | 0.0% |
|          hit |     22422180 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 40 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 40 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      3900000 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       300180 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     18600180 | 18.7% |
|          hit |     80633700 | 81.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 1.4% |
| Failure | 4,320 | 98.6% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide different types | 1,340 | 31.0% |
| subtract different types | 1,300 | 30.1% |
| power | 660 | 15.3% |
| multiply different types | 420 | 9.7% |
| true divide float | 360 | 8.3% |
| true divide other | 60 | 1.4% |
| subtract other | 60 | 1.4% |
| add other | 60 | 1.4% |
| add different types | 60 | 1.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2100300 | 9.3% |
|          hit |     20599920 | 90.7% |
|         miss |           60 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 9.7% |
| Failure | 560 | 90.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class no vectorcall | 180 | 32.1% |
| bound method | 180 | 32.1% |
| other | 140 | 25.0% |
| cfunc noargs | 60 | 10.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      4200000 | 52.5% |
|          hit |      3794160 | 47.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 2.0% |
| Failure | 960 | 98.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| float long | 960 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2700120 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |       600020 | 0.9% |
|          hit |     67137460 | 99.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 50.0% |
| Failure | 140 | 50.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 140 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     13348600 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |           60 | 100.0% |


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

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     13203960 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       300000 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 265,612,200 | 48.5% |
| Not specialized | 38,906,940 | 7.1% |
| Specialized | 242,740,580 | 44.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 18,600,180 | 72.9% |
| COMPARE_OP | 4,200,000 | 16.5% |
| CALL | 2,100,300 | 8.2% |
| LOAD_ATTR | 600,020 | 2.4% |
| BINARY_SUBSCR | 5,580 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| UNARY_NEGATIVE | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNARY_NEGATIVE | 0 | 0.0% |
| TO_BOOL_NONE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 1,500,060 | 10.4% |
| Calls to Python functions inlined | 12,900,180 | 89.6% |
| Calls via PyEval_EvalFrame (total) | 1,500,060 | 10.4% |
| Calls via PyEval_EvalFrame (vector) | 1,500,060 | 10.4% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,500,060 | 10.4% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 900,000 | 6.2% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 18,600,300 | 129.2% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 51,620,500 | 75.1% |
| Frees to freelist | 51,620,520 |  |
| Allocations | 17,126,600 | 24.9% |
| Allocations to 512 bytes | 17,111,240 | 24.9% |
| Allocations to 4 kbytes | 15,360 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 17,726,580 |  |
| New values | 0 |  |
| Interpreter increfs | 264,398,980 | 89.4% |
| Interpreter decrefs | 303,975,720 | 84.4% |
| Increfs | 31,444,480 | 10.6% |
| Decrefs | 56,383,880 | 15.6% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 600,236 |  |
| Method cache misses | 4 |  |
| Method cache collisions | 4 |  |
| Method cache dunder hits | 1,500,260 |  |
| Method cache dunder misses | 0 |  |


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

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 0 |  |
| Traces created | 0 |  |
| Traces executed | 6,776,400 |  |
| Uops executed | 251,729,760 | 37 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 |  |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,405,640 | 35.5% |
| <= 16 | 407,760 | 6.0% |
| <= 32 | 64,140 | 0.9% |
| <= 64 | 3,158,040 | 46.6% |
| <= 128 | 740,760 | 10.9% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1024 | 0 | 0.0% |
| <= 2048 | 0 | 0.0% |
| <= 4096 | 60 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 61,725,060 | 24.5% | 24.5% |
| LOAD_FAST | 42,037,800 | 16.7% | 41.2% |
| _GUARD_BOTH_INT | 18,044,460 | 7.2% | 48.4% |
| STORE_FAST | 12,467,520 | 5.0% | 53.3% |
| _POP_JUMP_IF_TRUE | 10,495,500 | 4.2% | 57.5% |
| _ITER_CHECK_RANGE | 9,965,400 | 4.0% | 61.5% |
| _IS_ITER_EXHAUSTED_RANGE | 9,965,400 | 4.0% | 65.4% |
| _BINARY_OP_ADD_INT | 9,644,460 | 3.8% | 69.3% |
| _BINARY_OP_SUBTRACT_INT | 8,400,000 | 3.3% | 72.6% |
| _LOAD_ATTR_INSTANCE_VALUE | 7,666,740 | 3.0% | 75.6% |
| _GUARD_TYPE_VERSION | 7,666,740 | 3.0% | 78.7% |
| _CHECK_MANAGED_OBJECT_HAS_VALUES | 7,666,740 | 3.0% | 81.7% |
| _ITER_NEXT_RANGE | 6,959,700 | 2.8% | 84.5% |
| _EXIT_TRACE | 6,776,400 | 2.7% | 87.2% |
| BINARY_SUBSCR_LIST_INT | 6,466,740 | 2.6% | 89.8% |
| LOAD_CONST | 6,437,580 | 2.6% | 92.3% |
| BINARY_OP | 3,615,300 | 1.4% | 93.8% |
| POP_TOP | 3,005,700 | 1.2% | 94.9% |
| _JUMP_TO_TOP | 2,096,820 | 0.8% | 95.8% |
| LIST_APPEND | 1,815,300 | 0.7% | 96.5% |
| _GUARD_GLOBALS_VERSION | 1,358,040 | 0.5% | 97.0% |
| _LOAD_GLOBAL_BUILTINS | 1,200,000 | 0.5% | 97.5% |
| _GUARD_BUILTINS_VERSION | 1,200,000 | 0.5% | 98.0% |
| GET_ITER | 1,200,000 | 0.5% | 98.5% |
| CALL_BUILTIN_CLASS | 1,200,000 | 0.5% | 98.9% |
| _POP_JUMP_IF_FALSE | 866,640 | 0.3% | 99.3% |
| COMPARE_OP | 844,560 | 0.3% | 99.6% |
| COMPARE_OP_INT | 552,180 | 0.2% | 99.8% |
| _LOAD_GLOBAL_MODULE | 158,040 | 0.1% | 99.9% |
| PUSH_NULL | 107,820 | 0.0% | 100.0% |
| CALL_BUILTIN_O | 107,820 | 0.0% | 100.0% |
| BUILD_LIST | 15,300 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|


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
Stats gathered on: 2023-10-03
