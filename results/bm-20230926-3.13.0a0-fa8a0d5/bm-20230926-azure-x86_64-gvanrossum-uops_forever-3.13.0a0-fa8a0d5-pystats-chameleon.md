
# Pystats results

- benchmark: chameleon
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 125,317,640 | 22.0% | 22.0% |  |
| LOAD_CONST | 60,977,340 | 10.7% | 32.7% |  |
| STORE_FAST | 53,539,220 | 9.4% | 42.1% |  |
| IS_OP | 34,323,360 | 6.0% | 48.1% |  |
| LOAD_GLOBAL_BUILTIN | 32,644,860 | 5.7% | 53.8% |  |
| PUSH_NULL | 30,487,640 | 5.3% | 59.2% |  |
| LOAD_GLOBAL_MODULE | 28,334,020 | 5.0% | 64.1% |  |
| POP_JUMP_IF_FALSE | 27,123,900 | 4.8% | 68.9% |  |
| POP_TOP | 17,284,860 | 3.0% | 71.9% |  |
| CALL_BUILTIN_O | 17,281,440 | 3.0% | 75.0% |  |
| LOAD_FAST_LOAD_FAST | 13,926,240 | 2.4% | 77.4% |  |
| RESUME_CHECK | 13,207,260 | 2.3% | 79.7% |  |
| RETURN_VALUE | 12,965,340 | 2.3% | 82.0% |  |
| POP_JUMP_IF_TRUE | 9,840,480 | 1.7% | 83.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 7,831,580 | 1.4% | 85.1% | 100.0% |
| LOAD_ATTR_CLASS | 7,682,880 | 1.3% | 86.4% |  |
| POP_JUMP_IF_NONE | 7,441,920 | 1.3% | 87.7% |  |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,281,440 | 0.9% | 88.7% |  |
| CALL_PY_EXACT_ARGS | 5,040,960 | 0.9% | 89.6% |  |
| COPY_FREE_VARS | 4,800,540 | 0.8% | 90.4% |  |
| TO_BOOL_BOOL | 4,800,480 | 0.8% | 91.2% |  |
| POP_JUMP_IF_NOT_NONE | 4,800,480 | 0.8% | 92.1% |  |
| CALL_TYPE_1 | 4,800,000 | 0.8% | 92.9% |  |
| CALL_STR_1 | 4,800,000 | 0.8% | 93.8% |  |
| CALL | 3,123,600 | 0.5% | 94.3% |  |
| STORE_SUBSCR | 3,122,280 | 0.5% | 94.9% |  |
| JUMP_FORWARD | 2,880,960 | 0.5% | 95.4% |  |
| NOP | 2,641,500 | 0.5% | 95.8% |  |
| DELETE_SUBSCR | 2,640,480 | 0.5% | 96.3% |  |
| ENTER_EXECUTOR | 2,640,160 | 0.5% | 96.8% |  |
| COMPARE_OP_INT | 2,640,060 | 0.5% | 97.2% |  |
| BINARY_OP_SUBTRACT_INT | 2,640,000 | 0.5% | 97.7% |  |
| BINARY_OP | 2,400,620 | 0.4% | 98.1% |  |
| LOAD_DEREF | 2,400,120 | 0.4% | 98.5% |  |
| BINARY_OP_ADD_UNICODE | 2,400,000 | 0.4% | 98.9% |  |
| BINARY_OP_ADD_INT | 2,400,000 | 0.4% | 99.4% |  |
| CALL_BUILTIN_FAST | 723,840 | 0.1% | 99.5% |  |
| INTERPRETER_EXIT | 482,880 | 0.1% | 99.6% |  |
| STORE_ATTR_SLOT | 481,920 | 0.1% | 99.7% |  |
| RETURN_CONST | 241,920 | 0.0% | 99.7% |  |
| BUILD_TUPLE | 241,440 | 0.0% | 99.7% |  |
| CALL_BUILTIN_CLASS | 241,020 | 0.0% | 99.8% |  |
| FOR_ITER_LIST | 240,640 | 0.0% | 99.8% |  |
| EXTENDED_ARG | 240,640 | 0.0% | 99.9% |  |
| GET_ITER | 240,540 | 0.0% | 99.9% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 240,480 | 0.0% | 100.0% |  |
| CALL_LEN | 240,480 | 0.0% | 100.0% |  |
| LOAD_ATTR | 5,260 | 0.0% | 100.0% |  |
| BUILD_MAP | 1,920 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_GETITEM | 1,920 | 0.0% | 100.0% |  |
| STORE_DEREF | 1,440 | 0.0% | 100.0% |  |
| MAKE_CELL | 1,440 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 1,020 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 960 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 960 | 0.0% | 100.0% |  |
| DICT_MERGE | 960 | 0.0% | 100.0% |  |
| STORE_SUBSCR_DICT | 480 | 0.0% | 100.0% |  |
| LOAD_SUPER_ATTR_ATTR | 480 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 480 | 0.0% | 100.0% |  |
| LOAD_ATTR_INSTANCE_VALUE | 480 | 0.0% | 100.0% |  |
| CONTAINS_OP | 480 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 480 | 0.0% | 100.0% |  |
| CALL_KW | 480 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 480 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 360 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 220 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST LOAD_FAST | 42,491,960 | 7.5% | 7.5% |
| LOAD_FAST PUSH_NULL | 27,606,080 | 4.8% | 12.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 22,323,360 | 3.9% | 16.2% |
| IS_OP POP_JUMP_IF_FALSE | 22,323,360 | 3.9% | 20.1% |
| PUSH_NULL LOAD_CONST | 20,647,200 | 3.6% | 23.7% |
| CALL_BUILTIN_O POP_TOP | 17,280,960 | 3.0% | 26.8% |
| LOAD_FAST LOAD_CONST | 15,603,900 | 2.7% | 29.5% |
| LOAD_GLOBAL_BUILTIN IS_OP | 14,400,000 | 2.5% | 32.0% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 14,400,000 | 2.5% | 34.6% |
| LOAD_FAST RETURN_VALUE | 12,482,940 | 2.2% | 36.8% |
| LOAD_CONST CALL_BUILTIN_O | 12,480,960 | 2.2% | 38.9% |
| LOAD_CONST LOAD_CONST | 12,000,480 | 2.1% | 41.1% |
| LOAD_GLOBAL_MODULE IS_OP | 10,323,360 | 1.8% | 42.9% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 10,323,360 | 1.8% | 44.7% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 10,321,500 | 1.8% | 46.5% |
| POP_TOP LOAD_FAST | 9,842,400 | 1.7% | 48.2% |
| PUSH_NULL LOAD_FAST | 9,600,060 | 1.7% | 49.9% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 7,683,840 | 1.3% | 51.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 7,682,880 | 1.3% | 52.6% |
| LOAD_GLOBAL_MODULE CALL_METHOD_DESCRIPTOR_FAST | 7,682,880 | 1.3% | 53.9% |
| LOAD_GLOBAL_BUILTIN LOAD_ATTR_CLASS | 7,682,880 | 1.3% | 55.3% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_MODULE | 7,682,880 | 1.3% | 56.6% |
| LOAD_ATTR_CLASS LOAD_FAST_LOAD_FAST | 7,682,880 | 1.3% | 58.0% |
| STORE_FAST LOAD_CONST | 7,681,920 | 1.3% | 59.3% |
| LOAD_GLOBAL_MODULE STORE_FAST | 7,442,400 | 1.3% | 60.6% |
| LOAD_FAST POP_JUMP_IF_NONE | 7,441,920 | 1.3% | 61.9% |
| RETURN_VALUE STORE_FAST | 7,200,960 | 1.3% | 63.2% |
| IS_OP POP_JUMP_IF_TRUE | 7,200,000 | 1.3% | 64.5% |
| POP_JUMP_IF_TRUE LOAD_FAST | 7,199,520 | 1.3% | 65.7% |
| LOAD_CONST CALL_BOUND_METHOD_EXACT_ARGS | 5,281,440 | 0.9% | 66.7% |
| CALL_BOUND_METHOD_EXACT_ARGS RESUME_CHECK | 5,281,440 | 0.9% | 67.6% |
| RESUME_CHECK LOAD_FAST | 5,042,880 | 0.9% | 68.5% |
| LOAD_FAST LOAD_FAST | 5,041,920 | 0.9% | 69.3% |
| LOAD_CONST STORE_FAST | 5,041,920 | 0.9% | 70.2% |
| POP_TOP LOAD_GLOBAL_MODULE | 5,041,440 | 0.9% | 71.1% |
| COPY_FREE_VARS RESUME_CHECK | 4,800,540 | 0.8% | 72.0% |
| POP_JUMP_IF_NONE LOAD_FAST | 4,800,480 | 0.8% | 72.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 4,800,480 | 0.8% | 73.6% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 4,800,040 | 0.8% | 74.5% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 4,800,000 | 0.8% | 75.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 4,800,000 | 0.8% | 76.2% |
| LOAD_FAST_LOAD_FAST IS_OP | 4,800,000 | 0.8% | 77.0% |
| LOAD_FAST TO_BOOL_BOOL | 4,800,000 | 0.8% | 77.9% |
| LOAD_FAST STORE_FAST | 4,800,000 | 0.8% | 78.7% |
| LOAD_FAST CALL_TYPE_1 | 4,800,000 | 0.8% | 79.5% |
| IS_OP STORE_FAST | 4,800,000 | 0.8% | 80.4% |
| CALL_TYPE_1 STORE_FAST | 4,800,000 | 0.8% | 81.2% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 4,800,000 | 0.8% | 82.1% |
| LOAD_CONST LOAD_FAST | 2,882,880 | 0.5% | 82.6% |
| STORE_SUBSCR LOAD_FAST | 2,880,960 | 0.5% | 83.1% |
| LOAD_CONST STORE_SUBSCR | 2,880,960 | 0.5% | 83.6% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,642,400 | 0.5% | 84.0% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 2,641,440 | 0.5% | 84.5% |
| LOAD_FAST CALL | 2,640,980 | 0.5% | 85.0% |
| RETURN_VALUE LOAD_CONST | 2,640,480 | 0.5% | 85.4% |
| LOAD_CONST DELETE_SUBSCR | 2,640,480 | 0.5% | 85.9% |
| JUMP_FORWARD LOAD_FAST | 2,640,480 | 0.5% | 86.4% |
| DELETE_SUBSCR JUMP_FORWARD | 2,640,480 | 0.5% | 86.8% |
| LOAD_CONST COMPARE_OP_INT | 2,640,040 | 0.5% | 87.3% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 2,640,000 | 0.5% | 87.7% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 2,640,000 | 0.5% | 88.2% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 2,640,000 | 0.5% | 88.7% |
| BINARY_OP_SUBTRACT_INT STORE_FAST | 2,640,000 | 0.5% | 89.1% |
| LOAD_FAST CALL_BUILTIN_O | 2,400,480 | 0.4% | 89.6% |
| NOP LOAD_DEREF | 2,400,060 | 0.4% | 90.0% |
| LOAD_DEREF PUSH_NULL | 2,400,060 | 0.4% | 90.4% |
| LOAD_FAST BINARY_OP | 2,400,020 | 0.4% | 90.8% |
| RETURN_VALUE CALL_STR_1 | 2,400,000 | 0.4% | 91.2% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_BUILTIN | 2,400,000 | 0.4% | 91.7% |
| POP_JUMP_IF_NONE NOP | 2,400,000 | 0.4% | 92.1% |
| LOAD_GLOBAL_MODULE CALL_PY_EXACT_ARGS | 2,400,000 | 0.4% | 92.5% |
| LOAD_FAST IS_OP | 2,400,000 | 0.4% | 92.9% |
| LOAD_FAST CALL_STR_1 | 2,400,000 | 0.4% | 93.3% |
| LOAD_CONST LOAD_GLOBAL_BUILTIN | 2,400,000 | 0.4% | 93.8% |
| LOAD_CONST IS_OP | 2,400,000 | 0.4% | 94.2% |
| LOAD_CONST BINARY_OP_ADD_INT | 2,400,000 | 0.4% | 94.6% |
| CALL_STR_1 STORE_FAST | 2,400,000 | 0.4% | 95.0% |
| CALL_STR_1 BINARY_OP_ADD_UNICODE | 2,400,000 | 0.4% | 95.5% |
| CALL LOAD_CONST | 2,400,000 | 0.4% | 95.9% |
| BINARY_OP_ADD_UNICODE STORE_FAST | 2,400,000 | 0.4% | 96.3% |
| BINARY_OP_ADD_INT STORE_FAST | 2,400,000 | 0.4% | 96.7% |
| BINARY_OP CALL_BUILTIN_O | 2,400,000 | 0.4% | 97.1% |
| ENTER_EXECUTOR RESUME_CHECK | 2,399,520 | 0.4% | 97.6% |
| POP_TOP ENTER_EXECUTOR | 2,160,300 | 0.4% | 97.9% |
| CACHE RESUME_CHECK | 482,400 | 0.1% | 98.0% |
| CALL_BUILTIN_FAST STORE_FAST | 481,440 | 0.1% | 98.1% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 480,960 | 0.1% | 98.2% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_SLOT | 480,960 | 0.1% | 98.3% |
| RETURN_VALUE PUSH_NULL | 480,480 | 0.1% | 98.4% |
| RETURN_VALUE INTERPRETER_EXIT | 241,920 | 0.0% | 98.4% |
| LOAD_FAST CALL_BUILTIN_FAST | 241,440 | 0.0% | 98.4% |
| STORE_ATTR_SLOT RETURN_CONST | 240,960 | 0.0% | 98.5% |
| RETURN_CONST INTERPRETER_EXIT | 240,960 | 0.0% | 98.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 240,960 | 0.0% | 98.6% |
| LOAD_GLOBAL_MODULE CALL_BUILTIN_FAST | 240,960 | 0.0% | 98.6% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 240,960 | 0.0% | 98.7% |
| LOAD_FAST GET_ITER | 240,540 | 0.0% | 98.7% |
| CALL STORE_FAST | 240,540 | 0.0% | 98.7% |
| LOAD_FAST CALL_BUILTIN_CLASS | 240,520 | 0.0% | 98.8% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST | 240,480 | 0.0% | 98.8% |


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
| RESUME_CHECK | 482,400 | 99.9% |
| COPY_FREE_VARS | 480 | 0.1% |


</details>

### DELETE_SUBSCR

<details>
<summary> Successors and predecessors for DELETE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,640,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 2,640,480 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,540 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 240,000 | 99.8% |
| EXTENDED_ARG | 480 | 0.2% |
| FOR_ITER_RANGE | 60 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 241,920 | 50.1% |
| RETURN_CONST | 240,960 | 49.9% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 960 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NONE | 2,400,000 | 90.9% |
| RESUME_CHECK | 240,480 | 9.1% |
| STORE_FAST | 960 | 0.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 2,400,060 | 90.9% |
| LOAD_GLOBAL_BUILTIN | 240,000 | 9.1% |
| LOAD_FAST | 960 | 0.0% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 17,280,960 | 100.0% |
| CALL_BUILTIN_FAST | 2,400 | 0.0% |
| RETURN_CONST | 960 | 0.0% |
| CALL | 540 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,842,400 | 56.9% |
| LOAD_GLOBAL_MODULE | 5,041,440 | 29.2% |
| ENTER_EXECUTOR | 2,160,300 | 12.5% |
| EXTENDED_ARG | 239,520 | 1.4% |
| RETURN_CONST | 480 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 27,606,080 | 90.5% |
| LOAD_DEREF | 2,400,060 | 7.9% |
| RETURN_VALUE | 480,480 | 1.6% |
| LOAD_ATTR | 500 | 0.0% |
| LOAD_SUPER_ATTR_ATTR | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20,647,200 | 67.7% |
| LOAD_FAST | 9,600,060 | 31.5% |
| CALL | 240,380 | 0.8% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,482,940 | 96.3% |
| BUILD_TUPLE | 240,480 | 1.9% |
| CALL_BUILTIN_FAST | 240,000 | 1.9% |
| CALL_FUNCTION_EX | 960 | 0.0% |
| RETURN_VALUE | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,200,960 | 55.5% |
| LOAD_CONST | 2,640,480 | 20.4% |
| CALL_STR_1 | 2,400,000 | 18.5% |
| PUSH_NULL | 480,480 | 3.7% |
| INTERPRETER_EXIT | 241,920 | 1.9% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,880,960 | 92.3% |
| LOAD_FAST_LOAD_FAST | 240,480 | 7.7% |
| STORE_SUBSCR | 840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,880,960 | 92.3% |
| LOAD_FAST_LOAD_FAST | 240,480 | 7.7% |
| STORE_SUBSCR | 840 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,400,020 | 100.0% |
| BINARY_OP | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 2,400,000 | 100.0% |
| BINARY_OP | 600 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 50.0% |
| STORE_FAST | 480 | 25.0% |
| LOAD_GLOBAL_MODULE | 480 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 50.0% |
| STORE_FAST | 480 | 25.0% |
| CALL | 480 | 25.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 240,480 | 99.6% |
| LOAD_FAST | 960 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 240,480 | 99.6% |
| LOAD_CONST | 960 | 0.4% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,640,980 | 84.5% |
| LOAD_FAST_LOAD_FAST | 240,480 | 7.7% |
| PUSH_NULL | 240,380 | 7.7% |
| CALL | 1,000 | 0.0% |
| BUILD_MAP | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,400,000 | 76.8% |
| STORE_FAST | 240,540 | 7.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 240,480 | 7.7% |
| LOAD_FAST_LOAD_FAST | 240,480 | 7.7% |
| CALL | 1,000 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DICT_MERGE | 960 | 94.1% |
| LOAD_FAST | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 960 | 94.1% |
| COPY_FREE_VARS | 60 | 5.9% |


</details>

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 480 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20 | 100.0% |


</details>

### CONTAINS_OP

<details>
<summary> Successors and predecessors for CONTAINS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 480 | 100.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,800,000 | 100.0% |
| CACHE | 480 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 4,800,540 | 100.0% |


</details>

### DICT_MERGE

<details>
<summary> Successors and predecessors for DICT_MERGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 960 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,160,300 | 81.8% |
| POP_JUMP_IF_TRUE | 240,000 | 9.1% |
| EXTENDED_ARG | 239,820 | 9.1% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,399,520 | 90.9% |
| LOAD_FAST | 240,360 | 9.1% |
| CALL | 280 | 0.0% |


</details>

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 239,520 | 99.5% |
| POP_JUMP_IF_TRUE | 480 | 0.2% |
| GET_ITER | 480 | 0.2% |
| JUMP_BACKWARD | 160 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 239,820 | 99.7% |
| FOR_ITER_LIST | 640 | 0.3% |
| JUMP_BACKWARD | 180 | 0.1% |


</details>

### IS_OP

<details>
<summary> Successors and predecessors for IS_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 14,400,000 | 42.0% |
| LOAD_GLOBAL_MODULE | 10,323,360 | 30.1% |
| LOAD_FAST_LOAD_FAST | 4,800,000 | 14.0% |
| LOAD_FAST | 2,400,000 | 7.0% |
| LOAD_CONST | 2,400,000 | 7.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 22,323,360 | 65.0% |
| POP_JUMP_IF_TRUE | 7,200,000 | 21.0% |
| STORE_FAST | 4,800,000 | 14.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 50.0% |
| EXTENDED_ARG | 180 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 160 | 44.4% |
| EXTENDED_ARG | 160 | 44.4% |
| ENTER_EXECUTOR | 40 | 11.1% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| DELETE_SUBSCR | 2,640,480 | 91.7% |
| CALL_BUILTIN_CLASS | 240,480 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,640,480 | 91.7% |
| STORE_FAST | 240,480 | 8.3% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800 | 91.3% |
| LOAD_ATTR | 400 | 7.6% |
| LOAD_GLOBAL_MODULE | 40 | 0.8% |
| LOAD_GLOBAL | 20 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400 | 45.6% |
| LOAD_FAST | 960 | 18.3% |
| PUSH_NULL | 500 | 9.5% |
| TO_BOOL_BOOL | 480 | 9.1% |
| CALL_BUILTIN_CLASS | 480 | 9.1% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 20,647,200 | 33.9% |
| LOAD_FAST | 15,603,900 | 25.6% |
| LOAD_CONST | 12,000,480 | 19.7% |
| STORE_FAST | 7,681,920 | 12.6% |
| RETURN_VALUE | 2,640,480 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 12,480,960 | 20.5% |
| LOAD_CONST | 12,000,480 | 19.7% |
| CALL_BOUND_METHOD_EXACT_ARGS | 5,281,440 | 8.7% |
| STORE_FAST | 5,041,920 | 8.3% |
| LOAD_FAST | 2,882,880 | 4.7% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 2,400,060 | 100.0% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,400,060 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 42,491,960 | 33.9% |
| POP_JUMP_IF_FALSE | 22,323,360 | 17.8% |
| LOAD_GLOBAL_BUILTIN | 10,321,500 | 8.2% |
| POP_TOP | 9,842,400 | 7.9% |
| PUSH_NULL | 9,600,060 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 27,606,080 | 22.0% |
| LOAD_CONST | 15,603,900 | 12.5% |
| LOAD_GLOBAL_BUILTIN | 14,400,000 | 11.5% |
| RETURN_VALUE | 12,482,940 | 10.0% |
| LOAD_GLOBAL_MODULE | 10,323,360 | 8.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_CLASS | 7,682,880 | 55.2% |
| POP_JUMP_IF_NOT_NONE | 4,800,000 | 34.5% |
| LOAD_GLOBAL_MODULE | 240,960 | 1.7% |
| STORE_SUBSCR | 240,480 | 1.7% |
| STORE_ATTR_SLOT | 240,480 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,682,880 | 55.2% |
| IS_OP | 4,800,000 | 34.5% |
| STORE_ATTR_SLOT | 480,960 | 3.5% |
| STORE_SUBSCR | 240,480 | 1.7% |
| CALL | 240,480 | 1.7% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 50.0% |
| RESUME_CHECK | 20 | 25.0% |
| POP_JUMP_IF_FALSE | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 25.0% |
| LOAD_ATTR | 20 | 25.0% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 960 | 66.7% |
| CALL_PY_WITH_DEFAULTS | 480 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 960 | 66.7% |
| RESUME_CHECK | 480 | 33.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 22,323,360 | 82.3% |
| TO_BOOL_BOOL | 4,800,000 | 17.7% |
| CONTAINS_OP | 480 | 0.0% |
| COMPARE_OP_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 22,323,360 | 82.3% |
| LOAD_GLOBAL_BUILTIN | 4,800,040 | 17.7% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,441,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800,480 | 64.5% |
| NOP | 2,400,000 | 32.2% |
| LOAD_GLOBAL_BUILTIN | 240,480 | 3.2% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |
| LOAD_CONST | 480 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,800,000 | 100.0% |
| LOAD_FAST | 480 | 0.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 7,200,000 | 73.2% |
| COMPARE_OP_INT | 2,640,000 | 26.8% |
| TO_BOOL_BOOL | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,199,520 | 73.2% |
| LOAD_GLOBAL_BUILTIN | 2,400,000 | 24.4% |
| ENTER_EXECUTOR | 240,000 | 2.4% |
| RETURN_CONST | 480 | 0.0% |
| EXTENDED_ARG | 480 | 0.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 240,960 | 99.6% |
| POP_TOP | 480 | 0.2% |
| POP_JUMP_IF_TRUE | 480 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 240,960 | 99.6% |
| POP_TOP | 960 | 0.4% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 960 | 66.7% |
| LOAD_GLOBAL_MODULE | 480 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,440 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 7,683,840 | 14.4% |
| LOAD_GLOBAL_MODULE | 7,442,400 | 13.9% |
| RETURN_VALUE | 7,200,960 | 13.4% |
| LOAD_CONST | 5,041,920 | 9.4% |
| LOAD_FAST | 4,800,000 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,491,960 | 79.4% |
| LOAD_CONST | 7,681,920 | 14.3% |
| LOAD_GLOBAL_MODULE | 2,642,400 | 4.9% |
| LOAD_GLOBAL_BUILTIN | 480,960 | 0.9% |
| STORE_FAST | 240,480 | 0.4% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,400,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400,000 | 100.0% |


</details>

### BINARY_OP_ADD_UNICODE

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_UNICODE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_STR_1 | 2,400,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400,000 | 100.0% |


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
| LOAD_CONST | 2,640,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,640,000 | 100.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 100.0% |


</details>

### BINARY_SUBSCR_GETITEM

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_GETITEM </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,920 | 100.0% |


</details>

### CALL_BOUND_METHOD_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_BOUND_METHOD_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 5,281,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 5,281,440 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,520 | 99.8% |
| LOAD_ATTR | 480 | 0.2% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_FORWARD | 240,480 | 99.8% |
| STORE_FAST | 540 | 0.2% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 241,440 | 33.4% |
| LOAD_GLOBAL_MODULE | 240,960 | 33.3% |
| LOAD_FAST_LOAD_FAST | 240,000 | 33.2% |
| LOAD_CONST | 480 | 0.1% |
| LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES | 480 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 481,440 | 66.5% |
| RETURN_VALUE | 240,000 | 33.2% |
| POP_TOP | 2,400 | 0.3% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,480,960 | 72.2% |
| LOAD_FAST | 2,400,480 | 13.9% |
| BINARY_OP | 2,400,000 | 13.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 17,280,960 | 100.0% |
| RETURN_VALUE | 480 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,480 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,682,880 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 147,740 | 1.9% |
| LOAD_CONST | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,683,840 | 98.1% |
| CALL_METHOD_DESCRIPTOR_FAST | 147,740 | 1.9% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,640,000 | 52.4% |
| LOAD_GLOBAL_MODULE | 2,400,000 | 47.6% |
| LOAD_FAST | 480 | 0.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 4,800,000 | 95.2% |
| RESUME_CHECK | 240,960 | 4.8% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 480 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 2,400,000 | 50.0% |
| LOAD_FAST | 2,400,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400,000 | 50.0% |
| BINARY_OP_ADD_UNICODE | 2,400,000 | 50.0% |


</details>

### CALL_TYPE_1

<details>
<summary> Successors and predecessors for CALL_TYPE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,800,000 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,640,040 | 100.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 2,640,000 | 100.0% |
| POP_JUMP_IF_FALSE | 60 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 240,000 | 99.7% |
| EXTENDED_ARG | 640 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,480 | 99.9% |
| LOAD_FAST | 160 | 0.1% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 160 | 72.7% |
| GET_ITER | 60 | 27.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 90.9% |
| LOAD_FAST | 20 | 9.1% |


</details>

### LOAD_ATTR_CLASS

<details>
<summary> Successors and predecessors for LOAD_ATTR_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,682,880 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,682,880 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 960 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 480 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 60.0% |
| PUSH_NULL | 40 | 40.0% |


</details>

### LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_NONDESCRIPTOR_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 480 | 50.0% |
| CALL_BUILTIN_FAST | 480 | 50.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 14,400,000 | 44.1% |
| RESUME_CHECK | 7,682,880 | 23.5% |
| POP_JUMP_IF_FALSE | 4,800,040 | 14.7% |
| POP_JUMP_IF_TRUE | 2,400,000 | 7.4% |
| LOAD_CONST | 2,400,000 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 14,400,000 | 44.1% |
| LOAD_FAST | 10,321,500 | 31.6% |
| LOAD_ATTR_CLASS | 7,682,880 | 23.5% |
| LOAD_FAST_LOAD_FAST | 240,000 | 0.7% |
| LOAD_GLOBAL_MODULE | 480 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 10,323,360 | 36.4% |
| LOAD_FAST_LOAD_FAST | 7,682,880 | 27.1% |
| POP_TOP | 5,041,440 | 17.8% |
| STORE_FAST | 2,642,400 | 9.3% |
| LOAD_CONST | 2,641,440 | 9.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| IS_OP | 10,323,360 | 36.4% |
| CALL_METHOD_DESCRIPTOR_FAST | 7,682,880 | 27.1% |
| STORE_FAST | 7,442,400 | 26.3% |
| CALL_PY_EXACT_ARGS | 2,400,000 | 8.5% |
| LOAD_FAST_LOAD_FAST | 240,960 | 0.9% |


</details>

### LOAD_SUPER_ATTR_ATTR

<details>
<summary> Successors and predecessors for LOAD_SUPER_ATTR_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 480 | 100.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BOUND_METHOD_EXACT_ARGS | 5,281,440 | 40.0% |
| COPY_FREE_VARS | 4,800,540 | 36.3% |
| ENTER_EXECUTOR | 2,399,520 | 18.2% |
| CACHE | 482,400 | 3.7% |
| CALL_PY_EXACT_ARGS | 240,960 | 1.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 7,682,880 | 58.2% |
| LOAD_FAST | 5,042,880 | 38.2% |
| NOP | 240,480 | 1.8% |
| LOAD_FAST_LOAD_FAST | 240,480 | 1.8% |
| LOAD_GLOBAL_MODULE | 520 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 480,960 | 99.8% |
| LOAD_FAST | 960 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 240,960 | 50.0% |
| LOAD_FAST_LOAD_FAST | 240,480 | 49.9% |
| LOAD_FAST | 480 | 0.1% |


</details>

### STORE_SUBSCR_DICT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 480 | 100.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800,000 | 100.0% |
| LOAD_ATTR | 480 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 4,800,000 | 100.0% |
| POP_JUMP_IF_TRUE | 480 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 240,480 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240,480 | 100.0% |


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
|          hit |         2400 | 100.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3121440 | 100.0% |
|          hit |          480 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 840 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict subclass no override | 780 | 92.9% |
| other | 60 | 7.1% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      4800480 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2400000 | 24.4% |
|          hit |      7440060 | 75.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 3.2% |
| Failure | 600 | 96.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| remainder | 600 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      3122580 | 4.9% |
| specialization.deopt |       147740 | 0.2% |
|          hit |     53290140 | 82.9% |
|         miss |      7830620 | 12.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 147,760 | 99.3% |
| Failure | 1,000 | 0.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cmethod | 600 | 60.0% |
| other | 140 | 14.0% |
| cfunc noargs | 120 | 12.0% |
| no dict | 100 | 10.0% |
| class mutable | 40 | 4.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2640060 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       240860 | 100.0% |


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
| specialization.deferred |         4820 | 0.1% |
|          hit |      7685860 | 99.9% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 9.1% |
| Failure | 400 | 90.9% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| method | 280 | 70.0% |
| class attr descriptor | 40 | 10.0% |
| class attr simple | 40 | 10.0% |
| shadowed | 40 | 10.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     66017440 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_SUPER_ATTR

<details>
<summary> specialization stats for LOAD_SUPER_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          480 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>

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
|          hit |       481920 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       240480 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 368,282,480 | 64.6% |
| Not specialized | 65,689,620 | 11.5% |
| Specialized | 136,129,840 | 23.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 3,122,580 | 36.1% |
| STORE_SUBSCR | 3,121,440 | 36.1% |
| BINARY_OP | 2,400,000 | 27.7% |
| LOAD_ATTR | 4,820 | 0.1% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR_DICT | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 7,830,620 | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| STORE_SUBSCR_DICT | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_DEREF | 0 | 0.0% |
| STORE_ATTR_SLOT | 0 | 0.0% |
| SET_FUNCTION_ATTRIBUTE | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RETURN_CONST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 482,880 | 3.7% |
| Calls to Python functions inlined | 12,724,380 | 96.3% |
| Calls via PyEval_EvalFrame (total) | 482,880 | 3.7% |
| Calls via PyEval_EvalFrame (vector) | 482,880 | 3.7% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 482,880 | 3.7% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 13,207,260 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 972,600 | 4.9% |
| Frees to freelist | 972,540 |  |
| Allocations | 18,830,560 | 95.1% |
| Allocations to 512 bytes | 18,829,580 | 95.1% |
| Allocations to 4 kbytes | 500 | 0.0% |
| Allocations over 4 kbytes | 480 | 0.0% |
| Frees | 18,831,001 |  |
| New values | 0 |  |
| Interpreter increfs | 177,926,680 | 77.6% |
| Interpreter decrefs | 191,974,480 | 78.0% |
| Increfs | 51,400,200 | 22.4% |
| Decrefs | 54,289,861 | 22.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 243,650 |  |
| Method cache misses | 10 |  |
| Method cache collisions | 10 |  |
| Method cache dunder hits | 724,020 |  |
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

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
