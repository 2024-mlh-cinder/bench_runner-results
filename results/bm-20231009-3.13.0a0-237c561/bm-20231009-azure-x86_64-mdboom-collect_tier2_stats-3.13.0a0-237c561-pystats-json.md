
# Pystats results

- benchmark: json
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 17,550,600 | 22.4% | 22.4% |  |
| POP_JUMP_IF_NOT_NONE | 6,192,000 | 7.9% | 30.3% |  |
| CALL | 5,163,560 | 6.6% | 36.8% |  |
| LOAD_FAST_LOAD_FAST | 4,129,260 | 5.3% | 42.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 3,097,080 | 3.9% | 46.0% |  |
| LOAD_CONST | 3,096,360 | 3.9% | 50.0% |  |
| RESUME_CHECK | 3,096,360 | 3.9% | 53.9% |  |
| RETURN_VALUE | 3,096,240 | 3.9% | 57.9% |  |
| LOAD_GLOBAL_BUILTIN | 3,096,120 | 3.9% | 61.8% |  |
| POP_JUMP_IF_FALSE | 3,096,000 | 3.9% | 65.8% |  |
| PUSH_NULL | 2,066,220 | 2.6% | 68.4% |  |
| STORE_FAST_STORE_FAST | 2,064,120 | 2.6% | 71.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 2,064,120 | 2.6% | 73.7% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,064,060 | 2.6% | 76.3% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 2,064,000 | 2.6% | 78.9% |  |
| TO_BOOL_BOOL | 2,064,000 | 2.6% | 81.6% |  |
| STORE_FAST | 1,036,260 | 1.3% | 82.9% |  |
| LOAD_GLOBAL_MODULE | 1,034,260 | 1.3% | 84.2% |  |
| ENTER_EXECUTOR | 1,032,960 | 1.3% | 85.5% |  |
| POP_JUMP_IF_TRUE | 1,032,960 | 1.3% | 86.8% |  |
| TO_BOOL | 1,032,240 | 1.3% | 88.1% |  |
| POP_TOP | 1,032,180 | 1.3% | 89.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 1,032,120 | 1.3% | 90.8% |  |
| NOP | 1,032,060 | 1.3% | 92.1% |  |
| BUILD_TUPLE | 1,032,060 | 1.3% | 93.4% |  |
| CALL_KW | 1,032,000 | 1.3% | 94.7% |  |
| CALL_ISINSTANCE | 1,032,000 | 1.3% | 96.0% |  |
| CALL_LEN | 1,032,000 | 1.3% | 97.4% |  |
| CALL_PY_WITH_DEFAULTS | 1,032,000 | 1.3% | 98.7% |  |
| COMPARE_OP_INT | 1,032,000 | 1.3% | 100.0% |  |
| LOAD_ATTR_MODULE | 2,080 | 0.0% | 100.0% |  |
| GET_ITER | 1,020 | 0.0% | 100.0% |  |
| CALL_LIST_APPEND | 1,020 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 960 | 0.0% | 100.0% | 6.2% |
| BINARY_OP_SUBTRACT_FLOAT | 960 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 960 | 0.0% | 100.0% |  |
| TO_BOOL_STR | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR | 320 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| STORE_ATTR_INSTANCE_VALUE | 180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 140 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 120 | 0.0% | 100.0% |  |
| BUILD_LIST | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| RETURN_CONST | 120 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 120 | 0.0% | 100.0% |  |
| BINARY_OP | 80 | 0.0% | 100.0% |  |
| BINARY_SLICE | 60 | 0.0% | 100.0% |  |
| BEFORE_WITH | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 20 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 6,192,000 | 7.9% | 7.9% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 6,192,000 | 7.9% | 15.8% |
| POP_JUMP_IF_FALSE LOAD_FAST | 3,096,000 | 3.9% | 19.7% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 2,064,120 | 2.6% | 22.4% |
| LOAD_CONST CALL | 2,064,060 | 2.6% | 25.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,064,060 | 2.6% | 27.6% |
| CALL LOAD_ATTR_METHOD_NO_DICT | 2,064,000 | 2.6% | 30.2% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 2,064,000 | 2.6% | 32.9% |
| LOAD_FAST_LOAD_FAST CALL | 2,064,000 | 2.6% | 35.5% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_FAST | 2,064,000 | 2.6% | 38.1% |
| TO_BOOL_BOOL POP_JUMP_IF_FALSE | 2,064,000 | 2.6% | 40.8% |
| STORE_FAST LOAD_FAST | 1,035,000 | 1.3% | 42.1% |
| PUSH_NULL LOAD_FAST | 1,033,080 | 1.3% | 43.4% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 1,033,000 | 1.3% | 44.7% |
| POP_JUMP_IF_TRUE LOAD_GLOBAL_MODULE | 1,032,960 | 1.3% | 46.0% |
| LOAD_FAST RETURN_VALUE | 1,032,120 | 1.3% | 47.4% |
| RETURN_VALUE RETURN_VALUE | 1,032,060 | 1.3% | 48.7% |
| BUILD_TUPLE RETURN_VALUE | 1,032,060 | 1.3% | 50.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 1,032,060 | 1.3% | 51.3% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,032,060 | 1.3% | 52.6% |
| STORE_FAST_STORE_FAST LOAD_FAST | 1,032,060 | 1.3% | 53.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 1,032,060 | 1.3% | 55.2% |
| CALL_METHOD_DESCRIPTOR_FAST STORE_FAST | 1,032,060 | 1.3% | 56.6% |
| RESUME_CHECK LOAD_FAST | 1,032,060 | 1.3% | 57.9% |
| RETURN_VALUE UNPACK_SEQUENCE_TWO_TUPLE | 1,032,040 | 1.3% | 59.2% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 1,032,040 | 1.3% | 60.5% |
| NOP LOAD_FAST | 1,032,000 | 1.3% | 61.8% |
| POP_TOP ENTER_EXECUTOR | 1,032,000 | 1.3% | 63.1% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,032,000 | 1.3% | 64.5% |
| RETURN_VALUE POP_TOP | 1,032,000 | 1.3% | 65.8% |
| TO_BOOL POP_JUMP_IF_TRUE | 1,032,000 | 1.3% | 67.1% |
| CALL RESUME_CHECK | 1,032,000 | 1.3% | 68.4% |
| CALL TO_BOOL_BOOL | 1,032,000 | 1.3% | 69.7% |
| CALL UNPACK_SEQUENCE_TWO_TUPLE | 1,032,000 | 1.3% | 71.0% |
| CALL_KW RESUME_CHECK | 1,032,000 | 1.3% | 72.3% |
| LOAD_CONST CALL_KW | 1,032,000 | 1.3% | 73.7% |
| LOAD_FAST PUSH_NULL | 1,032,000 | 1.3% | 75.0% |
| LOAD_FAST TO_BOOL | 1,032,000 | 1.3% | 76.3% |
| LOAD_FAST LOAD_CONST | 1,032,000 | 1.3% | 77.6% |
| LOAD_FAST CALL_LEN | 1,032,000 | 1.3% | 78.9% |
| LOAD_FAST CALL_PY_WITH_DEFAULTS | 1,032,000 | 1.3% | 80.2% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 1,032,000 | 1.3% | 81.6% |
| LOAD_FAST_LOAD_FAST PUSH_NULL | 1,032,000 | 1.3% | 82.9% |
| CALL_ISINSTANCE TO_BOOL_BOOL | 1,032,000 | 1.3% | 84.2% |
| CALL_LEN COMPARE_OP_INT | 1,032,000 | 1.3% | 85.5% |
| CALL_METHOD_DESCRIPTOR_FAST LOAD_CONST | 1,032,000 | 1.3% | 86.8% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 1,032,000 | 1.3% | 88.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,032,000 | 1.3% | 89.4% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 1,032,000 | 1.3% | 90.8% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 1,032,000 | 1.3% | 92.1% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 1,032,000 | 1.3% | 93.4% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST_LOAD_FAST | 1,032,000 | 1.3% | 94.7% |
| LOAD_GLOBAL_BUILTIN CALL_ISINSTANCE | 1,032,000 | 1.3% | 96.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_METHOD_WITH_VALUES | 1,032,000 | 1.3% | 97.3% |
| RESUME_CHECK NOP | 1,032,000 | 1.3% | 98.6% |
| ENTER_EXECUTOR CALL | 1,031,940 | 1.3% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,080 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,040 | 0.0% | 100.0% |
| CALL STORE_FAST | 1,920 | 0.0% | 100.0% |
| CALL CALL | 1,360 | 0.0% | 100.0% |
| PUSH_NULL CALL | 1,140 | 0.0% | 100.0% |
| LOAD_FAST CALL | 1,000 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_LIST | 960 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_GLOBAL_MODULE | 960 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 960 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 960 | 0.0% | 100.0% |
| LOAD_FAST CALL_LIST_APPEND | 960 | 0.0% | 100.0% |
| LOAD_FAST TO_BOOL_STR | 960 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 960 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 960 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 960 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_ADD_FLOAT | 960 | 0.0% | 100.0% |
| FOR_ITER_LIST STORE_FAST | 960 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 960 | 0.0% | 100.0% |
| TO_BOOL_STR POP_JUMP_IF_TRUE | 960 | 0.0% | 100.0% |
| CALL_LIST_APPEND ENTER_EXECUTOR | 940 | 0.0% | 100.0% |
| TO_BOOL TO_BOOL | 240 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 140 | 0.0% | 100.0% |
| CACHE RESUME_CHECK | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 120 | 0.0% | 100.0% |
| STORE_FAST LOAD_CONST | 120 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 120 | 0.0% | 100.0% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_FAST | 120 | 0.0% | 100.0% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 100 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| BINARY_SLICE LOAD_FAST | 60 | 0.0% | 100.0% |
| BEFORE_WITH STORE_FAST | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_CONST | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 60 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 60 | 0.0% | 100.0% |


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
| LOAD_CONST | 60 | 0.0% |
| LOAD_FAST_CHECK | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 49.9% |
| LOAD_FAST_LOAD_FAST | 1,032,000 | 49.9% |
| LOAD_ATTR_MODULE | 2,080 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,033,080 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,032,000 | 49.9% |
| CALL | 1,140 | 0.1% |


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
| LOAD_FAST | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


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
| ENTER_EXECUTOR | 1,031,940 | 20.0% |
| CALL | 1,360 | 0.0% |
| PUSH_NULL | 1,140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 2,064,000 | 40.0% |
| RESUME_CHECK | 1,032,000 | 20.0% |
| TO_BOOL_BOOL | 1,032,000 | 20.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,032,000 | 20.0% |
| STORE_FAST | 1,920 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| RESUME_CHECK | 60 | 50.0% |


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
| CALL | 1,031,940 | 99.9% |
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
| LOAD_FAST_CHECK | 20 | 6.2% |
| LOAD_GLOBAL | 20 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 120 | 37.5% |
| LOAD_ATTR | 40 | 12.5% |
| CALL_METHOD_DESCRIPTOR_FAST | 40 | 12.5% |
| LOAD_ATTR_METHOD_NO_DICT | 40 | 12.5% |
| LOAD_ATTR_MODULE | 40 | 12.5% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 33.3% |
| CALL_METHOD_DESCRIPTOR_FAST | 1,032,000 | 33.3% |
| LOAD_ATTR_METHOD_NO_DICT | 1,032,000 | 33.3% |
| LOAD_CONST | 120 | 0.0% |
| STORE_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,064,060 | 66.7% |
| CALL_KW | 1,032,000 | 33.3% |
| LOAD_CONST | 120 | 0.0% |
| BINARY_SLICE | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |
| RESUME_CHECK | 60 | 33.3% |

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
| POP_JUMP_IF_NOT_NONE | 6,192,000 | 35.3% |
| POP_JUMP_IF_FALSE | 3,096,000 | 17.6% |
| LOAD_GLOBAL_BUILTIN | 2,064,060 | 11.8% |
| STORE_FAST | 1,035,000 | 5.9% |
| PUSH_NULL | 1,033,080 | 5.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_NOT_NONE | 6,192,000 | 35.3% |
| LOAD_GLOBAL_BUILTIN | 2,064,000 | 11.8% |
| LOAD_ATTR_METHOD_NO_DICT | 1,033,000 | 5.9% |
| RETURN_VALUE | 1,032,120 | 5.9% |
| LOAD_ATTR_INSTANCE_VALUE | 1,032,060 | 5.9% |


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
| LOAD_ATTR_INSTANCE_VALUE | 1,032,000 | 25.0% |
| LOAD_ATTR_METHOD_WITH_VALUES | 1,032,000 | 25.0% |
| STORE_FAST | 960 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,064,000 | 50.0% |
| BUILD_TUPLE | 1,032,060 | 25.0% |
| PUSH_NULL | 1,032,000 | 25.0% |
| LOAD_FAST | 960 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 28.6% |
| RESUME_CHECK | 40 | 28.6% |
| STORE_FAST | 20 | 14.3% |
| LOAD_ATTR_METHOD_NO_DICT | 20 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 14.3% |

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
| INTERPRETER_EXIT | 60 | 50.0% |
| POP_TOP | 60 | 50.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 1,032,060 | 99.6% |
| CALL | 1,920 | 0.2% |
| BINARY_OP_ADD_FLOAT | 960 | 0.1% |
| FOR_ITER_LIST | 960 | 0.1% |
| BEFORE_WITH | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,035,000 | 99.9% |
| LOAD_FAST_LOAD_FAST | 960 | 0.1% |
| LOAD_CONST | 120 | 0.0% |
| BUILD_LIST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 2,064,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,060 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,032,060 | 50.0% |


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
| LOAD_ATTR | 40 | 0.0% |
| LOAD_FAST_CHECK | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 2,064,000 | 66.6% |
| LOAD_CONST | 1,032,000 | 33.3% |
| LOAD_FAST | 960 | 0.0% |
| CALL_METHOD_DESCRIPTOR_FAST_WITH_KEYWORDS | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 50.0% |
| LOAD_GLOBAL_MODULE | 1,032,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 1,032,000 | 50.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,040 | 98.1% |
| LOAD_ATTR | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,080 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,064,000 | 66.7% |
| RESUME_CHECK | 1,032,040 | 33.3% |
| LOAD_GLOBAL | 40 | 0.0% |
| STORE_FAST | 40 | 0.0% |

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
| CALL | 1,032,000 | 33.3% |
| CALL_KW | 1,032,000 | 33.3% |
| CALL_PY_WITH_DEFAULTS | 1,032,000 | 33.3% |
| CACHE | 120 | 0.0% |
| CALL_PY_EXACT_ARGS | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,032,060 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 1,032,040 | 33.3% |
| NOP | 1,032,000 | 33.3% |
| LOAD_GLOBAL_MODULE | 100 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


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
| CALL | 1,032,000 | 50.0% |
| CALL_ISINSTANCE | 1,032,000 | 50.0% |

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

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 3.0% |
|          hit | 1,860 | 93.0% |
|         miss | 60 | 3.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 20 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 20 | 100.0% |


</details>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,162,100 | 50.0% |
|          hit | 5,161,440 | 50.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 8.2% |
| Failure | 1,340 | 91.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cmethod | 480 | 35.8% |
| other | 240 | 17.9% |
| code complex parameters | 240 | 17.9% |
| meth descr varargs | 240 | 17.9% |
| cfunc noargs | 120 | 9.0% |
| cfunc varargs | 20 | 1.5% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,032,000 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,020 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 6,195,280 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 66.7% |
| Failure | 40 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 20 | 50.0% |
| class attr simple | 20 | 50.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 4,130,380 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 100.0% |
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

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 180 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,032,000 | 33.3% |
|          hit | 2,064,960 | 66.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 240 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| dict | 240 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 2,064,120 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 38,202,300 | 48.7% |
| Not specialized | 16,517,460 | 21.1% |
| Specialized | 23,747,600 | 30.3% |

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
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| CACHE | 0 | 0.0% |
| BEFORE_WITH | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 60 | 100.0% |
| CACHE | 0 | 0.0% |
| BEFORE_WITH | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| INTERPRETER_EXIT | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| BUILD_LIST | 0 | 0.0% |


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
| Frame objects created | 0 | 0.0% |
| Frames pushed | 3,096,360 | 100.0% |


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
| Frees | 51,686,400 |  |
| New values | 60 |  |
| Interpreter increfs | 39,233,620 | 27.9% |
| Interpreter decrefs | 45,426,300 | 23.9% |
| Increfs | 101,239,860 | 72.1% |
| Decrefs | 144,673,180 | 76.1% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 2,918 |  |
| Method cache misses | 62 |  |
| Method cache collisions | 40 |  |
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

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 20 |  |
| Traces created | 20 | 100.0% |
| Traces executed | 1,032,960 |  |
| Uops executed | 20,641,440 | 19.98 |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |

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
| <= 32 | 20 | 100.0% |


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
| <= 32 | 20 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,020 | 0.1% |
| <= 16 | 900 | 0.1% |
| <= 32 | 1,031,040 | 99.8% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 5,160,840 | 25.0% | 25.0% |  |
| LOAD_FAST | 2,062,080 | 10.0% | 35.0% |  |
| _EXIT_TRACE | 1,032,960 | 5.0% | 40.0% |  |
| _POP_JUMP_IF_TRUE | 1,032,960 | 5.0% | 45.0% |  |
| _ITER_CHECK_LIST | 1,032,000 | 5.0% | 50.0% |  |
| _IS_ITER_EXHAUSTED_LIST | 1,032,000 | 5.0% | 55.0% |  |
| PUSH_NULL | 1,031,940 | 5.0% | 60.0% |  |
| STORE_FAST | 1,031,940 | 5.0% | 65.0% |  |
| _GUARD_GLOBALS_VERSION | 1,031,940 | 5.0% | 70.0% |  |
| _LOAD_GLOBAL_MODULE | 1,031,940 | 5.0% | 75.0% |  |
| _CHECK_ATTR_MODULE | 1,031,940 | 5.0% | 80.0% |  |
| _LOAD_ATTR_MODULE | 1,031,940 | 5.0% | 85.0% |  |
| TO_BOOL_STR | 1,031,040 | 5.0% | 90.0% |  |
| _ITER_NEXT_LIST | 1,031,040 | 5.0% | 95.0% |  |
| _POP_JUMP_IF_FALSE | 1,031,040 | 5.0% | 100.0% |  |
| POP_TOP | 1,020 | 0.0% | 100.0% |  |
| _ITER_CHECK_RANGE | 960 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_RANGE | 960 | 0.0% | 100.0% |  |
| _ITER_NEXT_RANGE | 900 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
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
Stats gathered on: 2023-10-09
