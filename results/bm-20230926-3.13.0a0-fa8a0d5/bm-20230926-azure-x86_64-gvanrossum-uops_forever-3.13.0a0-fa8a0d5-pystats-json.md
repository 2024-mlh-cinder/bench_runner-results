
# Pystats results

- benchmark: json
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 18,581,640 | 22.8% | 22.8% |  |
| POP_JUMP_IF_NOT_NONE | 6,192,000 | 7.6% | 30.4% |  |
| CALL | 5,163,560 | 6.3% | 36.7% |  |
| LOAD_FAST_LOAD_FAST | 4,129,260 | 5.1% | 41.8% |  |
| PUSH_NULL | 3,098,160 | 3.8% | 45.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,097,080 | 3.8% | 49.4% |  |
| RESUME_CHECK | 3,096,360 | 3.8% | 53.2% |  |
| LOAD_CONST | 3,096,360 | 3.8% | 57.0% |  |
| RETURN_VALUE | 3,096,240 | 3.8% | 60.8% |  |
| LOAD_GLOBAL_BUILTIN | 3,096,120 | 3.8% | 64.5% |  |
| POP_JUMP_IF_FALSE | 3,096,000 | 3.8% | 68.3% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,064,120 | 2.5% | 70.9% |  |
| STORE_FAST_STORE_FAST | 2,064,120 | 2.5% | 73.4% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,064,060 | 2.5% | 75.9% |  |
| TO_BOOL_BOOL | 2,064,000 | 2.5% | 78.5% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,064,000 | 2.5% | 81.0% |  |
| STORE_FAST | 1,036,260 | 1.3% | 82.3% |  |
| LOAD_GLOBAL_MODULE | 1,034,260 | 1.3% | 83.5% |  |
| LOAD_ATTR_MODULE | 1,034,020 | 1.3% | 84.8% |  |
| POP_JUMP_IF_TRUE | 1,032,960 | 1.3% | 86.1% |  |
| ENTER_EXECUTOR | 1,032,960 | 1.3% | 87.3% |  |
| TO_BOOL | 1,032,240 | 1.3% | 88.6% |  |
| POP_TOP | 1,032,180 | 1.3% | 89.9% |  |
| LOAD_ATTR_INSTANCE_VALUE | 1,032,120 | 1.3% | 91.1% |  |
| NOP | 1,032,060 | 1.3% | 92.4% |  |
| BUILD_TUPLE | 1,032,060 | 1.3% | 93.7% |  |
| COMPARE_OP_INT | 1,032,000 | 1.3% | 94.9% |  |
| CALL_PY_WITH_DEFAULTS | 1,032,000 | 1.3% | 96.2% |  |
| CALL_LEN | 1,032,000 | 1.3% | 97.5% |  |
| CALL_KW | 1,032,000 | 1.3% | 98.7% |  |
| CALL_ISINSTANCE | 1,032,000 | 1.3% | 100.0% |  |
| GET_ITER | 1,020 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 1,020 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 960 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 960 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 960 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 960 | 0.0% | 100.0% | 6.2% |
| LOAD_ATTR | 320 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 140 | 0.0% | 100.0% |  |
| RETURN_CONST | 120 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 120 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| BUILD_LIST | 120 | 0.0% | 100.0% |  |
| BINARY_OP | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BINARY_SLICE | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 20 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 6,192,000 | 7.6% | 7.6% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 6,192,000 | 7.6% | 15.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 3,096,000 | 3.8% | 19.0% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 2,064,120 | 2.5% | 21.5% |
| PUSH_NULL LOAD_FAST | 2,064,120 | 2.5% | 24.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,064,060 | 2.5% | 26.6% |
| LOAD_CONST CALL | 2,064,060 | 2.5% | 29.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,064,000 | 2.5% | 31.6% |
| LOAD_FAST_LOAD_FAST CALL | 2,064,000 | 2.5% | 34.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 2,064,000 | 2.5% | 36.7% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_FAST | 2,064,000 | 2.5% | 39.2% |
| CALL LOAD_ATTR_METHOD_NO_DICT | 2,064,000 | 2.5% | 41.8% |
| STORE_FAST LOAD_FAST | 1,035,000 | 1.3% | 43.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,034,020 | 1.3% | 44.3% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,033,000 | 1.3% | 45.6% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 1,032,960 | 1.3% | 46.8% |
| LOAD_FAST RETURN_VALUE | 1,032,120 | 1.3% | 48.1% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 1,032,060 | 1.3% | 49.4% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,032,060 | 1.3% | 50.6% |
| RETURN_VALUE RETURN_VALUE | 1,032,060 | 1.3% | 51.9% |
| RESUME_CHECK LOAD_FAST | 1,032,060 | 1.3% | 53.2% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,032,060 | 1.3% | 54.4% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,032,060 | 1.3% | 55.7% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 1,032,060 | 1.3% | 56.9% |
| BUILD_TUPLE RETURN_VALUE | 1,032,060 | 1.3% | 58.2% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 1,032,040 | 1.3% | 59.5% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,032,040 | 1.3% | 60.7% |
| LOAD_FAST CALL | 1,032,040 | 1.3% | 62.0% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,032,000 | 1.3% | 63.3% |
| RETURN_VALUE POP_TOP | 1,032,000 | 1.3% | 64.5% |
| RESUME_CHECK NOP | 1,032,000 | 1.3% | 65.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,032,000 | 1.3% | 67.1% |
| POP_TOP ENTER_EXECUTOR | 1,032,000 | 1.3% | 68.3% |
| NOP LOAD_FAST | 1,032,000 | 1.3% | 69.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 1,032,000 | 1.3% | 70.9% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 1,032,000 | 1.3% | 72.1% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 1,032,000 | 1.3% | 73.4% |
| LOAD_FAST TO_BOOL | 1,032,000 | 1.3% | 74.7% |
| LOAD_FAST PUSH_NULL | 1,032,000 | 1.3% | 75.9% |
| LOAD_FAST LOAD_CONST | 1,032,000 | 1.3% | 77.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,032,000 | 1.3% | 78.5% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 1,032,000 | 1.3% | 79.7% |
| LOAD_FAST CALL_LEN | 1,032,000 | 1.3% | 81.0% |
| LOAD_CONST CALL_KW | 1,032,000 | 1.3% | 82.3% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 1,032,000 | 1.3% | 83.5% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,032,000 | 1.3% | 84.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 1,032,000 | 1.3% | 86.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 1,032,000 | 1.3% | 87.3% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,032,000 | 1.3% | 88.6% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,032,000 | 1.3% | 89.8% |
| CALL_METHOD_DESCRIPTOR_FAST LOAD_CONST | 1,032,000 | 1.3% | 91.1% |
| CALL_LEN COMPARE_OP_INT | 1,032,000 | 1.3% | 92.4% |
| CALL_KW RESUME_CHECK | 1,032,000 | 1.3% | 93.6% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,032,000 | 1.3% | 94.9% |
| CALL UNPACK_SEQUENCE_TWO_TUPLE | 1,032,000 | 1.3% | 96.2% |
| CALL TO_BOOL_BOOL | 1,032,000 | 1.3% | 97.4% |
| CALL RESUME_CHECK | 1,032,000 | 1.3% | 98.7% |
| ENTER_EXECUTOR LOAD_ATTR_MODULE | 1,031,940 | 1.3% | 100.0% |
| PUSH_NULL CALL | 2,040 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,040 | 0.0% | 100.0% |
| CALL STORE_FAST | 1,920 | 0.0% | 100.0% |
| CALL CALL | 1,360 | 0.0% | 100.0% |
| TO_BOOL_STR POP_JUMP_IF_TRUE | 960 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 960 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 960 | 0.0% | 100.0% |
| LOAD_FAST TO_BOOL_STR | 960 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 960 | 0.0% | 100.0% |
| LOAD_FAST CALL_LIST_APPEND | 960 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 960 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 960 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_LIST | 960 | 0.0% | 100.0% |
| FOR_ITER_LIST STORE_FAST | 960 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 960 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_ADD_FLOAT | 960 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 960 | 0.0% | 100.0% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 940 | 0.0% | 100.0% |
| TO_BOOL TO_BOOL | 240 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 140 | 0.0% | 100.0% |
| STORE_FAST LOAD_CONST | 120 | 0.0% | 100.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 120 | 0.0% | 100.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 120 | 0.0% | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| CACHE RESUME_CHECK | 120 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 60 | 0.0% | 100.0% |
| STORE_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 60 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 60 | 0.0% | 100.0% |
| RETURN_CONST POP_TOP | 60 | 0.0% | 100.0% |
| RETURN_CONST INTERPRETER_EXIT | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### BEFORE_WITH

<details>
<summary> Successors and predecessors for BEFORE_WITH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 94.1% |
| CALL_BUILTIN_CLASS | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 960 | 94.1% |
| FOR_ITER_RANGE | 60 | 5.9% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 50.0% |
| RETURN_CONST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,032,000 | 100.0% |
| POP_TOP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,032,000 | 100.0% |
| CALL | 120 | 0.0% |
| RETURN_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,032,000 | 100.0% |
| NOP | 60 | 0.0% |
| LOAD_FAST_CHECK | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,034,020 | 33.4% |
| LOAD_FAST_LOAD_FAST | 1,032,000 | 33.3% |
| LOAD_FAST | 1,032,000 | 33.3% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,064,120 | 66.6% |
| LOAD_FAST_LOAD_FAST | 1,032,000 | 33.3% |
| CALL | 2,040 | 0.1% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,120 | 33.3% |
| RETURN_VALUE | 1,032,060 | 33.3% |
| BUILD_TUPLE | 1,032,060 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,032,060 | 33.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,032,040 | 33.3% |
| POP_TOP | 1,032,000 | 33.3% |
| INTERPRETER_EXIT | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 100.0% |
| TO_BOOL | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,032,000 | 100.0% |
| TO_BOOL | 240 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 75.0% |
| BINARY_OP | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 75.0% |
| BINARY_OP | 20 | 25.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| LOAD_DEREF | 60 | 50.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,032,060 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,032,060 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,064,060 | 40.0% |
| LOAD_FAST_LOAD_FAST | 2,064,000 | 40.0% |
| LOAD_FAST | 1,032,040 | 20.0% |
| PUSH_NULL | 2,040 | 0.0% |
| CALL | 1,360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,064,000 | 40.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,032,000 | 20.0% |
| TO_BOOL_BOOL | 1,032,000 | 20.0% |
| RESUME_CHECK | 1,032,000 | 20.0% |
| STORE_FAST | 1,920 | 0.0% |


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

### CALL_KW

<details>
<summary> Successors and predecessors for CALL_KW </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,032,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,032,000 | 100.0% |


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
| POP_TOP | 1,032,000 | 99.9% |
| CALL_LIST_APPEND | 940 | 0.1% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,031,940 | 99.9% |
| LOAD_GLOBAL_MODULE | 960 | 0.1% |
| LOAD_FAST | 60 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LIST_APPEND | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 20 | 100.0% |


</details>

### LIST_EXTEND

<details>
<summary> Successors and predecessors for LIST_EXTEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 43.8% |
| LOAD_GLOBAL_MODULE | 100 | 31.2% |
| LOAD_ATTR | 40 | 12.5% |
| LOAD_GLOBAL | 20 | 6.2% |
| LOAD_FAST_CHECK | 20 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 120 | 37.5% |
| LOAD_ATTR_MODULE | 40 | 12.5% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 12.5% |
| LOAD_ATTR | 40 | 12.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 12.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 33.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,032,000 | 33.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,032,000 | 33.3% |
| STORE_FAST | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,064,060 | 66.7% |
| CALL_KW | 1,032,000 | 33.3% |
| LOAD_CONST | 120 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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
| POP_JUMP_IF_NOT_NONE | 6,192,000 | 33.3% |
| POP_JUMP_IF_FALSE | 3,096,000 | 16.7% |
| PUSH_NULL | 2,064,120 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 2,064,060 | 11.1% |
| STORE_FAST | 1,035,000 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 6,192,000 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 2,064,000 | 11.1% |
| LOAD_ATTR_METHOD_NO_DICT | 1,033,000 | 5.6% |
| RETURN_VALUE | 1,032,120 | 5.6% |
| LOAD_ATTR_INSTANCE_VALUE | 1,032,060 | 5.6% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 40 | 66.7% |
| LOAD_ATTR | 20 | 33.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,032,060 | 25.0% |
| PUSH_NULL | 1,032,000 | 25.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,032,000 | 25.0% |
| LOAD_ATTR_INSTANCE_VALUE | 1,032,000 | 25.0% |
| STORE_FAST | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,064,000 | 50.0% |
| BUILD_TUPLE | 1,032,060 | 25.0% |
| PUSH_NULL | 1,032,000 | 25.0% |
| LOAD_FAST | 960 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 28.6% |
| RESUME_CHECK | 40 | 28.6% |
| STORE_FAST | 20 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 14.3% |

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
| TO_BOOL_BOOL | 2,064,000 | 66.7% |
| COMPARE_OP_INT | 1,032,000 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,096,000 | 100.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,192,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,192,000 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL | 1,032,000 | 99.9% |
| TO_BOOL_STR | 960 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,032,960 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 50.0% |
| INTERPRETER_EXIT | 60 | 50.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 1,032,060 | 99.6% |
| CALL | 1,920 | 0.2% |
| FOR_ITER_LIST | 960 | 0.1% |
| BINARY_OP_ADD_FLOAT | 960 | 0.1% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,000 | 99.9% |
| LOAD_FAST_LOAD_FAST | 960 | 0.1% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,064,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,032,060 | 50.0% |
| LOAD_FAST | 1,032,060 | 50.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 20 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 960 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 60 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BEFORE_WITH | 60 | 100.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,032,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 1,032,000 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 1,032,000 | 100.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 94.1% |
| CALL | 60 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 940 | 92.2% |
| LOAD_FAST_LOAD_FAST | 60 | 5.9% |
| JUMP_BACKWARD | 20 | 2.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,064,000 | 100.0% |
| LOAD_ATTR | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,032,060 | 50.0% |
| LOAD_CONST | 1,032,000 | 50.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 50.0% |
| LOAD_FAST | 40 | 33.3% |
| CALL | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,032,000 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 1,032,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,032,000 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 960 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,060 | 100.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,032,000 | 100.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,064,000 | 66.6% |
| LOAD_FAST | 1,033,000 | 33.4% |
| LOAD_FAST_CHECK | 40 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 2,064,000 | 66.6% |
| LOAD_CONST | 1,032,000 | 33.3% |
| LOAD_FAST | 960 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,032,000 | 50.0% |
| LOAD_FAST | 1,032,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,032,000 | 50.0% |
| LOAD_FAST | 1,032,000 | 50.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,031,940 | 99.8% |
| LOAD_GLOBAL_MODULE | 2,040 | 0.2% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,034,020 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,064,000 | 66.7% |
| RESUME_CHECK | 1,032,040 | 33.3% |
| STORE_FAST | 40 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,064,060 | 66.7% |
| CALL_ISINSTANCE | 1,032,000 | 33.3% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 1,032,960 | 99.9% |
| ENTER_EXECUTOR | 960 | 0.1% |
| RESUME_CHECK | 100 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_WITH_VALUES | 1,032,000 | 99.8% |
| LOAD_ATTR_MODULE | 2,040 | 0.2% |
| LOAD_ATTR | 100 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 1,032,000 | 33.3% |
| CALL_KW | 1,032,000 | 33.3% |
| CALL | 1,032,000 | 33.3% |
| CALL_PY_EXACT_ARGS | 120 | 0.0% |
| CACHE | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,060 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 1,032,040 | 33.3% |
| NOP | 1,032,000 | 33.3% |
| LOAD_GLOBAL_MODULE | 100 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 66.7% |
| LOAD_FAST_LOAD_FAST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 120 | 66.7% |
| LOAD_FAST | 60 | 33.3% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 1,032,000 | 50.0% |
| CALL | 1,032,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,064,000 | 100.0% |


</details>

### TO_BOOL_STR

<details>
<summary> Successors and predecessors for TO_BOOL_STR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 960 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_TRUE | 960 | 100.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 1,032,040 | 50.0% |
| CALL | 1,032,000 | 50.0% |
| CALL_BUILTIN_FAST | 60 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,064,120 | 100.0% |


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

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      1032000 | 25.0% |
|          hit |      3096000 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 240 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 240 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 3.0% |
|          hit |         1860 | 93.0% |
|         miss |           60 | 3.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 20 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      5162100 | 50.0% |
|          hit |      5161440 | 50.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 8.2% |
| Failure | 1,340 | 91.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cmethod | 480 | 35.8% |
| meth descr varargs | 240 | 17.9% |
| code complex parameters | 240 | 17.9% |
| other | 240 | 17.9% |
| cfunc noargs | 120 | 9.0% |
| cfunc varargs | 20 | 1.5% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      1032000 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1020 | 100.0% |


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
| specialization.deferred |          200 | 0.0% |
|          hit |      7227220 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 66.7% |
| Failure | 40 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| class attr simple | 20 | 50.0% |
| not managed dict | 20 | 50.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |      5162320 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 100.0% |
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
|          hit |          180 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2064120 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 40,265,280 | 49.4% |
| Not specialized | 16,517,460 | 20.3% |
| Specialized | 24,779,540 | 30.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 5,162,100 | 83.3% |
| TO_BOOL | 1,032,000 | 16.7% |
| LOAD_ATTR | 200 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL_STR | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 60 | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| TO_BOOL_STR | 0 | 0.0% |
| TO_BOOL_BOOL | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RETURN_CONST | 0 | 0.0% |
| RESUME_CHECK | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 120 | 0.0% |
| Calls to Python functions inlined | 3,096,240 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 3,096,360 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 8,260,000 | 14.3% |
| Frees to freelist | 8,260,020 |  |
| Allocations | 49,622,440 | 85.7% |
| Allocations to 512 bytes | 49,554,160 | 85.6% |
| Allocations to 4 kbytes | 67,980 | 0.1% |
| Allocations over 4 kbytes | 300 | 0.0% |
| Frees | 51,686,403 |  |
| New values | 60 |  |
| Interpreter increfs | 41,296,600 | 29.4% |
| Interpreter decrefs | 46,458,240 | 24.4% |
| Increfs | 99,176,883 | 70.6% |
| Decrefs | 143,641,246 | 75.6% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 2,915 |  |
| Method cache misses | 65 |  |
| Method cache collisions | 41 |  |
| Method cache dunder hits | 300 |  |
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
