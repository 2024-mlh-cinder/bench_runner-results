
# Pystats results

- benchmark: sqlite_synth
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 13,764,420 | 17.9% | 17.9% |  |
| COPY | 5,898,240 | 7.7% | 25.6% |  |
| SWAP | 5,898,240 | 7.7% | 33.3% |  |
| POP_JUMP_IF_FALSE | 3,932,520 | 5.1% | 38.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 3,932,280 | 5.1% | 43.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 3,932,280 | 5.1% | 48.7% |  |
| BINARY_OP_ADD_INT | 3,932,160 | 5.1% | 53.8% |  |
| COMPARE_OP_FLOAT | 3,932,160 | 5.1% | 59.0% |  |
| LOAD_GLOBAL_BUILTIN | 1,967,080 | 2.6% | 61.5% |  |
| LOAD_CONST | 1,967,040 | 2.6% | 64.1% |  |
| STORE_FAST | 1,966,900 | 2.6% | 66.7% |  |
| LOAD_GLOBAL_MODULE | 1,966,660 | 2.6% | 69.2% |  |
| FOR_ITER | 1,966,620 | 2.6% | 71.8% |  |
| PUSH_NULL | 1,966,500 | 2.6% | 74.4% |  |
| RESUME_CHECK | 1,966,500 | 2.6% | 76.9% |  |
| LOAD_ATTR_MODULE | 1,966,360 | 2.6% | 79.5% |  |
| INTERPRETER_EXIT | 1,966,320 | 2.6% | 82.0% |  |
| JUMP_BACKWARD | 1,966,300 | 2.6% | 84.6% |  |
| RETURN_CONST | 1,966,140 | 2.6% | 87.2% |  |
| CALL_BUILTIN_O | 1,966,140 | 2.6% | 89.7% |  |
| POP_JUMP_IF_NONE | 1,966,080 | 2.6% | 92.3% |  |
| STORE_FAST_STORE_FAST | 1,966,080 | 2.6% | 94.9% |  |
| CALL_LEN | 1,966,080 | 2.6% | 97.4% |  |
| UNPACK_SEQUENCE_TUPLE | 1,966,080 | 2.6% | 100.0% |  |
| POP_TOP | 900 | 0.0% | 100.0% |  |
| CALL | 720 | 0.0% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 640 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 600 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 460 | 0.0% | 100.0% |  |
| LOAD_DEREF | 420 | 0.0% | 100.0% |  |
| LOAD_ATTR | 380 | 0.0% | 100.0% |  |
| RETURN_VALUE | 360 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 320 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 300 | 0.0% | 100.0% |  |
| NOP | 280 | 0.0% | 100.0% |  |
| ENTER_EXECUTOR | 280 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 240 | 0.0% | 100.0% |  |
| GET_ITER | 240 | 0.0% | 100.0% |  |
| POP_EXCEPT | 240 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 180 | 0.0% | 100.0% |  |
| STORE_ATTR | 180 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 120 | 0.0% | 100.0% |  |
| BUILD_LIST | 120 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 120 | 0.0% | 100.0% |  |
| MAKE_CELL | 120 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% | 100.0% |  |
| BINARY_OP | 100 | 0.0% | 100.0% |  |
| BUILD_MAP | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 60 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 60 | 0.0% | 100.0% |  |
| CALL_STR_1 | 60 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| TO_BOOL_BOOL | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| COPY LOAD_ATTR_INSTANCE_VALUE | 3,932,160 | 5.1% | 5.1% |
| LOAD_FAST COPY | 3,932,160 | 5.1% | 10.3% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 3,932,160 | 5.1% | 15.4% |
| BINARY_OP_ADD_INT SWAP | 3,932,160 | 5.1% | 20.5% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 3,932,160 | 5.1% | 25.6% |
| LOAD_ATTR_MODULE PUSH_NULL | 1,966,300 | 2.6% | 28.2% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 1,966,280 | 2.6% | 30.8% |
| PUSH_NULL LOAD_FAST | 1,966,260 | 2.6% | 33.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 1,966,260 | 2.6% | 35.9% |
| CACHE RESUME_CHECK | 1,966,200 | 2.6% | 38.5% |
| RESUME_CHECK LOAD_FAST | 1,966,200 | 2.6% | 41.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,966,180 | 2.6% | 43.6% |
| LOAD_FAST CALL_BUILTIN_O | 1,966,140 | 2.6% | 46.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 1,966,140 | 2.6% | 48.7% |
| RETURN_CONST INTERPRETER_EXIT | 1,966,140 | 2.6% | 51.3% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 1,966,140 | 2.6% | 53.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 1,966,120 | 2.6% | 56.4% |
| COPY COMPARE_OP_FLOAT | 1,966,080 | 2.6% | 59.0% |
| FOR_ITER UNPACK_SEQUENCE_TUPLE | 1,966,080 | 2.6% | 61.5% |
| JUMP_BACKWARD FOR_ITER | 1,966,080 | 2.6% | 64.1% |
| LOAD_CONST BINARY_OP_ADD_INT | 1,966,080 | 2.6% | 66.7% |
| LOAD_FAST POP_JUMP_IF_NONE | 1,966,080 | 2.6% | 69.2% |
| LOAD_FAST SWAP | 1,966,080 | 2.6% | 71.8% |
| LOAD_FAST CALL_LEN | 1,966,080 | 2.6% | 74.3% |
| LOAD_FAST COMPARE_OP_FLOAT | 1,966,080 | 2.6% | 76.9% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 1,966,080 | 2.6% | 79.5% |
| POP_JUMP_IF_NONE LOAD_FAST | 1,966,080 | 2.6% | 82.0% |
| STORE_FAST_STORE_FAST STORE_FAST | 1,966,080 | 2.6% | 84.6% |
| SWAP COPY | 1,966,080 | 2.6% | 87.2% |
| CALL_BUILTIN_O LOAD_FAST | 1,966,080 | 2.6% | 89.7% |
| CALL_LEN BINARY_OP_ADD_INT | 1,966,080 | 2.6% | 92.3% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 1,966,080 | 2.6% | 94.9% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 1,966,080 | 2.6% | 97.4% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 1,966,080 | 2.6% | 100.0% |
| FOR_ITER FOR_ITER | 480 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 460 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 420 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 380 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 300 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 280 | 0.0% | 100.0% |
| FOR_ITER_TUPLE STORE_FAST | 280 | 0.0% | 100.0% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 240 | 0.0% | 100.0% |
| POP_TOP POP_EXCEPT | 240 | 0.0% | 100.0% |
| POP_TOP ENTER_EXECUTOR | 240 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 240 | 0.0% | 100.0% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 240 | 0.0% | 100.0% |
| CALL POP_TOP | 240 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE POP_TOP | 240 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 240 | 0.0% | 100.0% |
| NOP LOAD_GLOBAL_BUILTIN | 220 | 0.0% | 100.0% |
| POP_EXCEPT JUMP_BACKWARD | 220 | 0.0% | 100.0% |
| STORE_FAST NOP | 220 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 200 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 200 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 180 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 180 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST POP_TOP | 180 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_METHOD_NO_DICT | 160 | 0.0% | 100.0% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 160 | 0.0% | 100.0% |
| ENTER_EXECUTOR PUSH_EXC_INFO | 140 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 140 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_TUPLE | 120 | 0.0% | 100.0% |
| MAKE_FUNCTION SET_FUNCTION_ATTRIBUTE | 120 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 120 | 0.0% | 100.0% |
| BUILD_TUPLE LOAD_CONST | 120 | 0.0% | 100.0% |
| CALL CALL | 120 | 0.0% | 100.0% |
| CALL STORE_FAST | 120 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 120 | 0.0% | 100.0% |
| LOAD_CONST MAKE_FUNCTION | 120 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 120 | 0.0% | 100.0% |
| LOAD_CONST LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 120 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 120 | 0.0% | 100.0% |
| LOAD_FAST BUILD_TUPLE | 120 | 0.0% | 100.0% |
| LOAD_FAST LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 120 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST POP_TOP | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST STORE_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL | 120 | 0.0% | 100.0% |
| LOAD_CONST CALL | 100 | 0.0% | 100.0% |
| LOAD_FAST STORE_ATTR | 100 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST PUSH_EXC_INFO | 100 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |
| CALL CALL_METHOD_DESCRIPTOR_FAST | 80 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 80 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 80 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 80 | 0.0% | 100.0% |
| LOAD_CONST LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 80 | 0.0% | 100.0% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 80 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_METHOD_DESCRIPTOR_NOARGS | 80 | 0.0% | 100.0% |
| CACHE COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CACHE MAKE_CELL | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 1,966,200 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 20 | 100.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 240 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 50.0% |
| CALL_BUILTIN_CLASS | 60 | 25.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 120 | 50.0% |
| FOR_ITER | 60 | 25.0% |
| FOR_ITER_RANGE | 60 | 25.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,966,140 | 100.0% |
| RETURN_VALUE | 180 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 120 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 220 | 78.6% |
| POP_TOP | 60 | 21.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 220 | 78.6% |
| LOAD_DEREF | 60 | 21.4% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 220 | 91.7% |
| ENTER_EXECUTOR | 20 | 8.3% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 26.7% |
| POP_JUMP_IF_FALSE | 240 | 26.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 180 | 20.0% |
| CALL_BUILTIN_FAST | 120 | 13.3% |
| BINARY_SUBSCR_TUPLE_INT | 60 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 240 | 26.7% |
| ENTER_EXECUTOR | 240 | 26.7% |
| LOAD_FAST | 240 | 26.7% |
| NOP | 60 | 6.7% |
| LOAD_GLOBAL | 40 | 4.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 140 | 58.3% |
| CALL_BUILTIN_FAST | 100 | 41.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 240 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,966,300 | 100.0% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,260 | 100.0% |
| CALL | 180 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 33.3% |
| LOAD_FAST | 120 | 33.3% |
| BINARY_OP | 60 | 16.7% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 180 | 50.0% |
| RETURN_VALUE | 120 | 33.3% |
| LOAD_GLOBAL | 40 | 11.1% |
| LOAD_GLOBAL_MODULE | 20 | 5.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 60 | 60.0% |
| BINARY_OP | 20 | 20.0% |
| LOAD_FAST | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 60.0% |
| BINARY_OP | 20 | 20.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 20.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| CALL_STR_1 | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 50.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 50.0% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 60 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 120 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 25.0% |
| CALL | 120 | 16.7% |
| LOAD_GLOBAL_MODULE | 120 | 16.7% |
| LOAD_CONST | 100 | 13.9% |
| CALL_BUILTIN_FAST | 60 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 240 | 33.3% |
| CALL | 120 | 16.7% |
| STORE_FAST | 120 | 16.7% |
| CALL_METHOD_DESCRIPTOR_FAST | 80 | 11.1% |
| LOAD_FAST | 60 | 8.3% |


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

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,932,160 | 66.7% |
| SWAP | 1,966,080 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 3,932,160 | 66.7% |
| COMPARE_OP_FLOAT | 1,966,080 | 33.3% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 60 | 50.0% |
| CALL_FUNCTION_EX | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 120 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 240 | 85.7% |
| POP_EXCEPT | 20 | 7.1% |
| JUMP_BACKWARD | 20 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 140 | 50.0% |
| LOAD_FAST | 80 | 28.6% |
| LOAD_FAST_LOAD_FAST | 60 | 21.4% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 1,966,080 | 100.0% |
| FOR_ITER | 480 | 0.0% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,966,080 | 100.0% |
| FOR_ITER | 480 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,966,080 | 100.0% |
| POP_EXCEPT | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,966,080 | 100.0% |
| FOR_ITER_TUPLE | 200 | 0.0% |
| ENTER_EXECUTOR | 20 | 0.0% |


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
| LOAD_FAST | 200 | 52.6% |
| LOAD_GLOBAL_MODULE | 140 | 36.8% |
| LOAD_ATTR | 20 | 5.3% |
| LOAD_GLOBAL | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 160 | 42.1% |
| PUSH_NULL | 80 | 21.1% |
| LOAD_ATTR_MODULE | 80 | 21.1% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 10.5% |
| LOAD_ATTR | 20 | 5.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,966,080 | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT | 420 | 0.0% |
| BUILD_TUPLE | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| PUSH_NULL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,966,080 | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST | 160 | 0.0% |
| MAKE_FUNCTION | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| LOAD_FAST | 120 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 14.3% |
| BUILD_LIST | 60 | 14.3% |
| LOAD_DEREF | 60 | 14.3% |
| LOAD_FAST | 60 | 14.3% |
| POP_JUMP_IF_FALSE | 60 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 120 | 28.6% |
| LIST_EXTEND | 60 | 14.3% |
| LOAD_CONST | 60 | 14.3% |
| LOAD_DEREF | 60 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 60 | 14.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,966,260 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 1,966,260 | 14.3% |
| RESUME_CHECK | 1,966,200 | 14.3% |
| POP_JUMP_IF_FALSE | 1,966,140 | 14.3% |
| POP_JUMP_IF_NONE | 1,966,080 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,932,160 | 28.6% |
| CALL_BUILTIN_O | 1,966,140 | 14.3% |
| POP_JUMP_IF_NONE | 1,966,080 | 14.3% |
| SWAP | 1,966,080 | 14.3% |
| CALL_LEN | 1,966,080 | 14.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 460 | 71.9% |
| ENTER_EXECUTOR | 60 | 9.4% |
| LOAD_CONST | 60 | 9.4% |
| LOAD_GLOBAL_MODULE | 60 | 9.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 280 | 43.8% |
| LOAD_FAST | 120 | 18.8% |
| BUILD_MAP | 60 | 9.4% |
| STORE_ATTR | 60 | 9.4% |
| CALL_PY_WITH_DEFAULTS | 60 | 9.4% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 40 | 22.2% |
| RETURN_VALUE | 40 | 22.2% |
| LOAD_CONST | 40 | 22.2% |
| STORE_FAST | 20 | 11.1% |
| LOAD_ATTR_INSTANCE_VALUE | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 66.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 22.2% |
| LOAD_ATTR | 20 | 11.1% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 60 | 50.0% |
| MAKE_CELL | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 60 | 50.0% |
| RESUME_CHECK | 60 | 50.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 3,932,160 | 100.0% |
| CHECK_EXC_MATCH | 240 | 0.0% |
| COMPARE_OP_INT | 60 | 0.0% |
| TO_BOOL_BOOL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,140 | 50.0% |
| JUMP_BACKWARD | 1,966,080 | 50.0% |
| POP_TOP | 240 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,080 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 1,966,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 1,966,140 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100 | 55.6% |
| LOAD_FAST_LOAD_FAST | 60 | 33.3% |
| STORE_ATTR | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 33.3% |
| LOAD_GLOBAL_MODULE | 60 | 33.3% |
| STORE_ATTR_INSTANCE_VALUE | 40 | 22.2% |
| STORE_ATTR | 20 | 11.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,966,080 | 100.0% |
| FOR_ITER_TUPLE | 280 | 0.0% |
| CALL | 120 | 0.0% |
| CALL_BUILTIN_FAST | 120 | 0.0% |
| SET_FUNCTION_ATTRIBUTE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,966,180 | 100.0% |
| LOAD_FAST | 300 | 0.0% |
| NOP | 220 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,966,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,966,080 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 3,932,160 | 66.7% |
| LOAD_FAST | 1,966,080 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 3,932,160 | 66.7% |
| COPY | 1,966,080 | 33.3% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,966,080 | 50.0% |
| CALL_LEN | 1,966,080 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,932,160 | 100.0% |


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
| RETURN_VALUE | 60 | 100.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_SUBSCR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 40 | 33.3% |
| LOAD_FAST | 40 | 33.3% |
| LOAD_ATTR_INSTANCE_VALUE | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 50.0% |
| BINARY_OP | 60 | 50.0% |


</details>

### CALL_BUILTIN_FAST

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 280 | 60.9% |
| LOAD_FAST | 120 | 26.1% |
| BUILD_MAP | 60 | 13.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 26.1% |
| STORE_FAST | 120 | 26.1% |
| PUSH_EXC_INFO | 100 | 21.7% |
| CALL | 60 | 13.0% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 13.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,080 | 100.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 60 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 1,966,080 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 53.3% |
| CALL | 80 | 26.7% |
| BUILD_LIST | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 180 | 60.0% |
| GET_ITER | 60 | 20.0% |
| STORE_FAST | 60 | 20.0% |


</details>

### CALL_METHOD_DESCRIPTOR_NOARGS

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_NOARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 80 | 66.7% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 50.0% |
| LOAD_CONST | 60 | 50.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 60 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 1,966,080 | 50.0% |
| LOAD_FAST | 1,966,080 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 3,932,160 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


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

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 200 | 62.5% |
| GET_ITER | 120 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 87.5% |
| LOAD_FAST | 40 | 12.5% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 3,932,160 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 1,966,120 | 50.0% |
| LOAD_CONST | 1,966,080 | 50.0% |
| CALL_BUILTIN_CLASS | 40 | 0.0% |
| CALL | 20 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 63.3% |
| LOAD_ATTR | 160 | 26.7% |
| CALL_BUILTIN_FAST | 60 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 420 | 70.0% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 80 | 13.3% |
| LOAD_GLOBAL_BUILTIN | 60 | 10.0% |
| CALL | 40 | 6.7% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,966,280 | 100.0% |
| LOAD_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,966,300 | 100.0% |
| CALL | 60 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 1,966,120 | 100.0% |
| PUSH_EXC_INFO | 240 | 0.0% |
| NOP | 220 | 0.0% |
| STORE_FAST | 180 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,260 | 100.0% |
| LOAD_FAST_LOAD_FAST | 460 | 0.0% |
| CHECK_EXC_MATCH | 240 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| CALL_ISINSTANCE | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,966,180 | 100.0% |
| LOAD_GLOBAL | 120 | 0.0% |
| RESUME_CHECK | 100 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 1,966,280 | 100.0% |
| LOAD_ATTR | 140 | 0.0% |
| CALL | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 1,966,200 | 100.0% |
| COPY_FREE_VARS | 120 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| MAKE_CELL | 60 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,966,200 | 100.0% |
| LOAD_GLOBAL_MODULE | 100 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,932,160 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 1,966,140 | 50.0% |
| LOAD_FAST | 1,966,080 | 50.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,966,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 1,966,080 | 100.0% |


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
|     deferred | 60 | 0.0% |
|          hit | 3,932,220 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 50.0% |
| Failure | 20 | 50.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide different types | 20 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 60 | 75.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 420 | 0.0% |
|          hit | 3,933,460 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 60.0% |
| Failure | 120 | 40.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 50.0% |
| meth descr method fastcall keywords | 40 | 33.3% |
| class no vectorcall | 20 | 16.7% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 3,932,220 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 1,966,140 | 100.0% |
|          hit | 380 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 480 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 480 | 100.0% |


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
|     deferred | 80 | 0.0% |
|          hit | 5,899,240 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 93.3% |
| Failure | 20 | 6.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| module attr not found | 20 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 3,933,740 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### POP_JUMP_IF_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NONE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 120 | 0.0% |
|          hit | 3,932,280 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 66.7% |
| Failure | 20 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 20 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 60 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 1,966,080 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 37,364,740 | 48.7% |
| Not specialized | 9,833,100 | 12.8% |
| Specialized | 29,496,240 | 38.5% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 1,966,140 | 100.0% |
| CALL | 420 | 0.0% |
| STORE_ATTR | 120 | 0.0% |
| LOAD_ATTR | 80 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| CACHE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |


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
| Calls to PyEval_EvalDefault | 1,966,320 | 100.0% |
| Calls to Python functions inlined | 180 | 0.0% |
| Calls via PyEval_EvalFrame (total) | 1,966,320 | 100.0% |
| Calls via PyEval_EvalFrame (vector) | 1,966,320 | 100.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 1,966,320 | 100.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 60 | 0.0% |
| Frame objects created | 60 | 0.0% |
| Frames pushed | 1,966,500 | 100.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 29,503,420 | 51.8% |
| Frees to freelist | 29,503,440 |  |
| Allocations | 27,443,980 | 48.2% |
| Allocations to 512 bytes | 27,443,960 | 48.2% |
| Allocations to 4 kbytes | 20 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 29,420,040 |  |
| New values | 60 |  |
| Interpreter increfs | 43,205,500 | 44.9% |
| Interpreter decrefs | 51,048,280 | 33.8% |
| Increfs | 53,041,085 | 55.1% |
| Decrefs | 100,179,185 | 66.2% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 1,967,015 |  |
| Method cache misses | 5 |  |
| Method cache collisions | 25 |  |
| Method cache dunder hits | 700 |  |
| Method cache dunder misses | 20 |  |


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
| Optimization attempts | 115,680 |  |
| Traces created | 20 | 0.0% |
| Traces executed | 280 |  |
| Uops executed | 74,711,700 | 266,827.50 |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 115,660 | 578,300.0% |
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
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 100.0% |


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
| <= 8 | 80 | 28.6% |
| <= 16 | 140 | 50.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 0 | 0.0% |
| <= 256 | 0 | 0.0% |
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
| <= 524,288 | 0 | 0.0% |
| <= 1,048,576 | 0 | 0.0% |
| <= 2,097,152 | 60 | 21.4% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 19,660,900 | 26.3% | 26.3% |  |
| LOAD_FAST | 9,830,380 | 13.2% | 39.5% |  |
| STORE_FAST | 3,932,180 | 5.3% | 44.7% |  |
| _GUARD_GLOBALS_VERSION | 3,932,180 | 5.3% | 50.0% |  |
| _POP_JUMP_IF_TRUE | 1,966,300 | 2.6% | 52.6% |  |
| POP_TOP | 1,966,160 | 2.6% | 55.3% |  |
| _GUARD_BUILTINS_VERSION | 1,966,160 | 2.6% | 57.9% |  |
| _LOAD_GLOBAL_BUILTINS | 1,966,160 | 2.6% | 60.5% |  |
| _ITER_CHECK_RANGE | 1,966,080 | 2.6% | 63.2% |  |
| _IS_ITER_EXHAUSTED_RANGE | 1,966,080 | 2.6% | 65.8% |  |
| PUSH_NULL | 1,966,020 | 2.6% | 68.4% |  |
| BUILD_LIST | 1,966,020 | 2.6% | 71.1% |  |
| LOAD_CONST | 1,966,020 | 2.6% | 73.7% |  |
| CALL_BUILTIN_O | 1,966,020 | 2.6% | 76.3% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 1,966,020 | 2.6% | 78.9% |  |
| CALL_STR_1 | 1,966,020 | 2.6% | 81.6% |  |
| _LOAD_GLOBAL_MODULE | 1,966,020 | 2.6% | 84.2% |  |
| _GUARD_TYPE_VERSION | 1,966,020 | 2.6% | 86.8% |  |
| _CHECK_ATTR_MODULE | 1,966,020 | 2.6% | 89.5% |  |
| _LOAD_ATTR_MODULE | 1,966,020 | 2.6% | 92.1% |  |
| _ITER_NEXT_RANGE | 1,966,020 | 2.6% | 94.7% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 1,966,020 | 2.6% | 97.4% |  |
| _JUMP_TO_TOP | 1,966,020 | 2.6% | 100.0% |  |
| _ITER_CHECK_TUPLE | 220 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 220 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 140 | 0.0% | 100.0% |  |
| _EXIT_TRACE | 140 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 140 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 115,660 |


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
