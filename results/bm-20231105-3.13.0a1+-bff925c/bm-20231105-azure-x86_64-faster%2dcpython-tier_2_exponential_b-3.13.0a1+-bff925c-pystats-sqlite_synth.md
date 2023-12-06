
# Pystats results

- benchmark: sqlite_synth
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 18,353,440 | 17.9% | 17.9% |  |
| COPY | 7,864,320 | 7.7% | 25.6% |  |
| SWAP | 7,864,320 | 7.7% | 33.3% |  |
| POP_JUMP_IF_FALSE | 5,243,360 | 5.1% | 38.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 5,242,960 | 5.1% | 43.6% |  |
| STORE_ATTR_INSTANCE_VALUE | 5,242,960 | 5.1% | 48.7% |  |
| BINARY_OP_ADD_INT | 5,242,840 | 5.1% | 53.8% |  |
| COMPARE_OP_FLOAT | 5,242,840 | 5.1% | 59.0% |  |
| STORE_FAST | 2,623,100 | 2.6% | 61.5% |  |
| LOAD_CONST | 2,623,020 | 2.6% | 64.1% |  |
| LOAD_GLOBAL_BUILTIN | 2,622,960 | 2.6% | 66.7% |  |
| FOR_ITER | 2,622,400 | 2.6% | 69.2% |  |
| LOAD_GLOBAL_MODULE | 2,622,380 | 2.6% | 71.8% |  |
| PUSH_NULL | 2,622,300 | 2.6% | 74.3% |  |
| JUMP_BACKWARD | 2,622,040 | 2.6% | 76.9% |  |
| LOAD_ATTR_MODULE | 2,622,020 | 2.6% | 79.5% |  |
| RESUME_CHECK | 2,621,900 | 2.6% | 82.0% |  |
| CALL_BUILTIN_O | 2,621,780 | 2.6% | 84.6% |  |
| INTERPRETER_EXIT | 2,621,760 | 2.6% | 87.2% |  |
| RETURN_CONST | 2,621,520 | 2.6% | 89.7% |  |
| POP_JUMP_IF_NONE | 2,621,440 | 2.6% | 92.3% |  |
| STORE_FAST_STORE_FAST | 2,621,440 | 2.6% | 94.9% |  |
| CALL_LEN | 2,621,420 | 2.6% | 97.4% |  |
| UNPACK_SEQUENCE_TUPLE | 2,621,420 | 2.6% | 100.0% |  |
| POP_TOP | 1,480 | 0.0% | 100.0% |  |
| CALL | 1,260 | 0.0% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 1,120 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 920 | 0.0% | 100.0% |  |
| LOAD_ATTR | 860 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 600 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 580 | 0.0% | 100.0% |  |
| LOAD_DEREF | 560 | 0.0% | 100.0% |  |
| RETURN_VALUE | 480 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 480 | 0.0% | 100.0% |  |
| BUILD_LIST | 460 | 0.0% | 100.0% |  |
| FOR_ITER_TUPLE | 420 | 0.0% | 100.0% |  |
| NOP | 360 | 0.0% | 100.0% |  |
| ENTER_EXECUTOR | 360 | 0.0% | 100.0% |  |
| STORE_ATTR | 360 | 0.0% | 100.0% |  |
| CALL_STR_1 | 360 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 360 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 320 | 0.0% | 100.0% |  |
| GET_ITER | 320 | 0.0% | 100.0% |  |
| POP_EXCEPT | 320 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 320 | 0.0% | 100.0% |  |
| BINARY_OP | 220 | 0.0% | 100.0% |  |
| MAKE_FUNCTION | 160 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 160 | 0.0% | 100.0% |  |
| MAKE_CELL | 160 | 0.0% | 100.0% |  |
| SET_FUNCTION_ATTRIBUTE | 160 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_NOARGS | 120 | 0.0% | 100.0% |  |
| RESUME | 100 | 0.0% | 100.0% |  |
| BUILD_MAP | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COMPARE_OP | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| CALL_ISINSTANCE | 80 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 80 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 80 | 0.0% | 100.0% |  |
| TO_BOOL_BOOL | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_TUPLE_INT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST COPY | 5,242,880 | 5.1% | 5.1% |
| BINARY_OP_ADD_INT SWAP | 5,242,840 | 5.1% | 10.3% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 5,242,840 | 5.1% | 15.4% |
| COPY LOAD_ATTR_INSTANCE_VALUE | 5,242,800 | 5.1% | 20.5% |
| SWAP STORE_ATTR_INSTANCE_VALUE | 5,242,800 | 5.1% | 25.6% |
| PUSH_NULL LOAD_FAST | 2,621,980 | 2.6% | 28.2% |
| LOAD_ATTR_MODULE PUSH_NULL | 2,621,960 | 2.6% | 30.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 2,621,900 | 2.6% | 33.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 2,621,900 | 2.6% | 35.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,621,780 | 2.6% | 38.5% |
| LOAD_FAST CALL_BUILTIN_O | 2,621,740 | 2.6% | 41.0% |
| RESUME_CHECK LOAD_FAST | 2,621,560 | 2.6% | 43.6% |
| CACHE RESUME_CHECK | 2,621,540 | 2.6% | 46.1% |
| POP_JUMP_IF_FALSE LOAD_FAST | 2,621,520 | 2.6% | 48.7% |
| RETURN_CONST INTERPRETER_EXIT | 2,621,520 | 2.6% | 51.3% |
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 2,621,480 | 2.6% | 53.8% |
| JUMP_BACKWARD FOR_ITER | 2,621,460 | 2.6% | 56.4% |
| LOAD_FAST POP_JUMP_IF_NONE | 2,621,440 | 2.6% | 59.0% |
| LOAD_FAST SWAP | 2,621,440 | 2.6% | 61.5% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 2,621,440 | 2.6% | 64.1% |
| POP_JUMP_IF_NONE LOAD_FAST | 2,621,440 | 2.6% | 66.7% |
| STORE_FAST_STORE_FAST STORE_FAST | 2,621,440 | 2.6% | 69.2% |
| SWAP COPY | 2,621,440 | 2.6% | 71.8% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_GLOBAL_BUILTIN | 2,621,440 | 2.6% | 74.3% |
| CALL_BUILTIN_O LOAD_FAST | 2,621,420 | 2.6% | 76.9% |
| LOAD_ATTR_INSTANCE_VALUE LOAD_CONST | 2,621,420 | 2.6% | 79.5% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST | 2,621,420 | 2.6% | 82.0% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 2,621,420 | 2.6% | 84.6% |
| COPY COMPARE_OP_FLOAT | 2,621,400 | 2.6% | 87.2% |
| FOR_ITER UNPACK_SEQUENCE_TUPLE | 2,621,400 | 2.6% | 89.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 2,621,400 | 2.6% | 92.3% |
| LOAD_FAST CALL_LEN | 2,621,400 | 2.6% | 94.8% |
| LOAD_FAST COMPARE_OP_FLOAT | 2,621,400 | 2.6% | 97.4% |
| CALL_LEN BINARY_OP_ADD_INT | 2,621,400 | 2.6% | 100.0% |
| FOR_ITER FOR_ITER | 840 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 720 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 700 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 660 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST_LOAD_FAST | 580 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_FAST POP_TOP | 480 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 440 | 0.0% | 100.0% |
| CALL POP_TOP | 400 | 0.0% | 100.0% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 380 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST CALL_BUILTIN_FAST | 360 | 0.0% | 100.0% |
| CALL_BUILTIN_O STORE_FAST | 360 | 0.0% | 100.0% |
| CALL_STR_1 BUILD_LIST | 360 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 360 | 0.0% | 100.0% |
| FOR_ITER_TUPLE STORE_FAST | 360 | 0.0% | 100.0% |
| BUILD_LIST CALL_METHOD_DESCRIPTOR_FAST | 340 | 0.0% | 100.0% |
| LOAD_FAST CALL_STR_1 | 340 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_GLOBAL_BUILTIN | 340 | 0.0% | 100.0% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 320 | 0.0% | 100.0% |
| POP_TOP POP_EXCEPT | 320 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 320 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 320 | 0.0% | 100.0% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 320 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE POP_TOP | 320 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 320 | 0.0% | 100.0% |
| NOP LOAD_GLOBAL_BUILTIN | 280 | 0.0% | 100.0% |
| POP_EXCEPT JUMP_BACKWARD | 280 | 0.0% | 100.0% |
| POP_TOP ENTER_EXECUTOR | 280 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 280 | 0.0% | 100.0% |
| STORE_FAST NOP | 280 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_TUPLE | 260 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 240 | 0.0% | 100.0% |
| CALL STORE_FAST | 220 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 220 | 0.0% | 100.0% |
| LOAD_CONST CALL | 200 | 0.0% | 100.0% |
| LOAD_FAST CALL | 200 | 0.0% | 100.0% |
| ENTER_EXECUTOR PUSH_EXC_INFO | 180 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 180 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_METHOD_NO_DICT | 180 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 180 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_TUPLE | 160 | 0.0% | 100.0% |
| MAKE_FUNCTION SET_FUNCTION_ATTRIBUTE | 160 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 160 | 0.0% | 100.0% |
| BUILD_TUPLE LOAD_CONST | 160 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_CONST | 160 | 0.0% | 100.0% |
| LOAD_CONST MAKE_FUNCTION | 160 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 160 | 0.0% | 100.0% |
| LOAD_CONST LOAD_FAST | 160 | 0.0% | 100.0% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_FAST | 160 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 160 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 160 | 0.0% | 100.0% |
| LOAD_FAST BUILD_TUPLE | 160 | 0.0% | 100.0% |
| LOAD_FAST LOAD_FAST | 160 | 0.0% | 100.0% |
| LOAD_FAST STORE_ATTR | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 160 | 0.0% | 100.0% |
| CALL CALL | 140 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 140 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_FAST | 140 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 140 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 140 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST POP_TOP | 140 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST PUSH_EXC_INFO | 140 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST STORE_FAST | 140 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL | 140 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,621,540 | 100.0% |
| COPY_FREE_VARS | 80 | 0.0% |
| MAKE_CELL | 80 | 0.0% |
| RESUME | 60 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 20 | 50.0% |
| BINARY_SUBSCR_TUPLE_INT | 20 | 50.0% |


</details>

### CHECK_EXC_MATCH

<details>
<summary> Successors and predecessors for CHECK_EXC_MATCH </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 320 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 50.0% |
| CALL_BUILTIN_CLASS | 60 | 18.8% |
| CALL_METHOD_DESCRIPTOR_FAST | 60 | 18.8% |
| CALL | 40 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_TUPLE | 160 | 50.0% |
| FOR_ITER | 100 | 31.2% |
| FOR_ITER_RANGE | 60 | 18.8% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,621,520 | 100.0% |
| RETURN_VALUE | 240 | 0.0% |


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 160 | 100.0% |


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 280 | 77.8% |
| POP_TOP | 80 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 280 | 77.8% |
| LOAD_DEREF | 80 | 22.2% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 280 | 87.5% |
| ENTER_EXECUTOR | 40 | 12.5% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 480 | 32.4% |
| CALL | 400 | 27.0% |
| POP_JUMP_IF_FALSE | 320 | 21.6% |
| CALL_BUILTIN_FAST | 140 | 9.5% |
| BINARY_SUBSCR_TUPLE_INT | 60 | 4.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 320 | 21.6% |
| JUMP_BACKWARD | 320 | 21.6% |
| LOAD_FAST | 320 | 21.6% |
| ENTER_EXECUTOR | 280 | 18.9% |
| NOP | 80 | 5.4% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 180 | 56.2% |
| CALL_BUILTIN_FAST | 140 | 43.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 320 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,621,960 | 100.0% |
| LOAD_ATTR | 180 | 0.0% |
| LOAD_DEREF | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,980 | 100.0% |
| CALL | 240 | 0.0% |
| LOAD_CONST | 80 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 160 | 33.3% |
| LOAD_FAST | 160 | 33.3% |
| BINARY_OP | 100 | 20.8% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 240 | 50.0% |
| RETURN_VALUE | 160 | 33.3% |
| LOAD_GLOBAL | 40 | 8.3% |
| LOAD_GLOBAL_MODULE | 40 | 8.3% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 60 | 27.3% |
| CALL | 40 | 18.2% |
| LOAD_CONST | 40 | 18.2% |
| LOAD_FAST | 40 | 18.2% |
| BINARY_OP | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 100 | 45.5% |
| SWAP | 40 | 18.2% |
| BINARY_OP_ADD_INT | 40 | 18.2% |
| BINARY_OP | 20 | 9.1% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 9.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_STR_1 | 360 | 78.3% |
| LOAD_FAST | 80 | 17.4% |
| CALL | 20 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_FAST | 340 | 73.9% |
| LOAD_DEREF | 80 | 17.4% |
| CALL | 40 | 8.7% |


</details>

### BUILD_MAP

<details>
<summary> Successors and predecessors for BUILD_MAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 80 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 160 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 19.0% |
| LOAD_CONST | 200 | 15.9% |
| LOAD_FAST | 200 | 15.9% |
| CALL | 140 | 11.1% |
| LOAD_GLOBAL_MODULE | 140 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 400 | 31.7% |
| STORE_FAST | 220 | 17.5% |
| CALL | 140 | 11.1% |
| LOAD_FAST | 100 | 7.9% |
| CALL_METHOD_DESCRIPTOR_FAST | 100 | 7.9% |


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
| COPY | 40 | 50.0% |
| LOAD_FAST | 40 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 40 | 50.0% |
| COMPARE_OP_FLOAT | 40 | 50.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 5,242,880 | 66.7% |
| SWAP | 2,621,440 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 5,242,800 | 66.7% |
| COMPARE_OP_FLOAT | 2,621,400 | 33.3% |
| LOAD_ATTR | 80 | 0.0% |
| COMPARE_OP | 40 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 80 | 50.0% |
| CALL_FUNCTION_EX | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 140 | 87.5% |
| RESUME | 20 | 12.5% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 280 | 77.8% |
| POP_EXCEPT | 40 | 11.1% |
| JUMP_BACKWARD | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 180 | 50.0% |
| LOAD_FAST | 100 | 27.8% |
| LOAD_FAST_LOAD_FAST | 80 | 22.2% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,621,460 | 100.0% |
| FOR_ITER | 840 | 0.0% |
| GET_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 2,621,400 | 100.0% |
| FOR_ITER | 840 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| UNPACK_SEQUENCE | 40 | 0.0% |
| STORE_FAST | 20 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,621,440 | 100.0% |
| POP_TOP | 320 | 0.0% |
| POP_EXCEPT | 280 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 2,621,460 | 100.0% |
| FOR_ITER_RANGE | 280 | 0.0% |
| FOR_ITER_TUPLE | 260 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |


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
| LOAD_FAST | 440 | 51.2% |
| LOAD_GLOBAL_MODULE | 180 | 20.9% |
| LOAD_GLOBAL | 140 | 16.3% |
| COPY | 80 | 9.3% |
| LOAD_ATTR | 20 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 20.9% |
| LOAD_ATTR_METHOD_NO_DICT | 180 | 20.9% |
| LOAD_CONST | 160 | 18.6% |
| LOAD_ATTR_MODULE | 120 | 14.0% |
| CALL | 80 | 9.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,621,420 | 99.9% |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 0.0% |
| BUILD_TUPLE | 160 | 0.0% |
| LOAD_ATTR | 160 | 0.0% |
| LOAD_CONST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,621,400 | 99.9% |
| LOAD_FAST_LOAD_FAST | 380 | 0.0% |
| CALL | 200 | 0.0% |
| MAKE_FUNCTION | 160 | 0.0% |
| LOAD_CONST | 160 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 14.3% |
| BUILD_LIST | 80 | 14.3% |
| LOAD_DEREF | 80 | 14.3% |
| LOAD_FAST | 80 | 14.3% |
| POP_JUMP_IF_FALSE | 80 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 28.6% |
| LIST_EXTEND | 80 | 14.3% |
| LOAD_CONST | 80 | 14.3% |
| LOAD_DEREF | 80 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 14.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,621,980 | 14.3% |
| LOAD_GLOBAL_BUILTIN | 2,621,900 | 14.3% |
| RESUME_CHECK | 2,621,560 | 14.3% |
| POP_JUMP_IF_FALSE | 2,621,520 | 14.3% |
| POP_JUMP_IF_NONE | 2,621,440 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 5,242,880 | 28.6% |
| CALL_BUILTIN_O | 2,621,740 | 14.3% |
| POP_JUMP_IF_NONE | 2,621,440 | 14.3% |
| SWAP | 2,621,440 | 14.3% |
| CALL_LEN | 2,621,400 | 14.3% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 580 | 51.8% |
| LOAD_CONST | 380 | 33.9% |
| ENTER_EXECUTOR | 80 | 7.1% |
| LOAD_GLOBAL_MODULE | 80 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_FAST | 360 | 32.1% |
| LOAD_GLOBAL_BUILTIN | 340 | 30.4% |
| LOAD_FAST | 140 | 12.5% |
| BUILD_MAP | 80 | 7.1% |
| STORE_ATTR | 80 | 7.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 25.0% |
| POP_TOP | 80 | 16.7% |
| LOAD_CONST | 80 | 16.7% |
| RETURN_VALUE | 40 | 8.3% |
| LOAD_ATTR | 40 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 33.3% |
| LOAD_ATTR | 140 | 29.2% |
| LOAD_FAST | 80 | 16.7% |
| LOAD_GLOBAL_BUILTIN | 80 | 16.7% |
| CALL | 20 | 4.2% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 80 | 50.0% |
| MAKE_CELL | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 80 | 50.0% |
| RESUME_CHECK | 80 | 50.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 5,242,840 | 100.0% |
| CHECK_EXC_MATCH | 320 | 0.0% |
| COMPARE_OP_INT | 80 | 0.0% |
| TO_BOOL_BOOL | 80 | 0.0% |
| COMPARE_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,520 | 50.0% |
| JUMP_BACKWARD | 2,621,440 | 50.0% |
| POP_TOP | 320 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |


</details>

### POP_JUMP_IF_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,440 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,440 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 2,621,480 | 100.0% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 2,621,520 | 100.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 44.4% |
| LOAD_FAST_LOAD_FAST | 80 | 22.2% |
| SWAP | 80 | 22.2% |
| STORE_ATTR | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100 | 27.8% |
| LOAD_GLOBAL_MODULE | 80 | 22.2% |
| STORE_ATTR_INSTANCE_VALUE | 80 | 22.2% |
| RETURN_CONST | 40 | 11.1% |
| STORE_ATTR | 40 | 11.1% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,621,440 | 99.9% |
| CALL_BUILTIN_O | 360 | 0.0% |
| FOR_ITER_RANGE | 360 | 0.0% |
| FOR_ITER_TUPLE | 360 | 0.0% |
| CALL | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,621,780 | 99.9% |
| LOAD_FAST | 700 | 0.0% |
| NOP | 280 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 220 | 0.0% |
| LOAD_GLOBAL | 120 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 2,621,420 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,621,440 | 100.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 5,242,840 | 66.7% |
| LOAD_FAST | 2,621,440 | 33.3% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 5,242,800 | 66.7% |
| COPY | 2,621,440 | 33.3% |
| STORE_ATTR | 80 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 20 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 20 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 60 | 60.0% |
| CALL_FUNCTION_EX | 20 | 20.0% |
| COPY_FREE_VARS | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 40.0% |
| LOAD_CONST | 20 | 20.0% |
| LOAD_DEREF | 20 | 20.0% |
| LOAD_GLOBAL | 20 | 20.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,621,400 | 50.0% |
| CALL_LEN | 2,621,400 | 50.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 5,242,840 | 100.0% |


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
| LOAD_FAST_LOAD_FAST | 360 | 62.1% |
| LOAD_FAST | 140 | 24.1% |
| BUILD_MAP | 80 | 13.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 140 | 24.1% |
| PUSH_EXC_INFO | 140 | 24.1% |
| STORE_FAST | 140 | 24.1% |
| CALL | 80 | 13.8% |
| LOAD_ATTR_METHOD_NO_DICT | 80 | 13.8% |


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
| LOAD_FAST | 2,621,740 | 100.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,420 | 100.0% |
| STORE_FAST | 360 | 0.0% |


</details>

### CALL_ISINSTANCE

<details>
<summary> Successors and predecessors for CALL_ISINSTANCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_BOOL | 80 | 100.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,400 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 2,621,400 | 100.0% |
| BINARY_OP | 20 | 0.0% |


</details>

### CALL_METHOD_DESCRIPTOR_FAST

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 340 | 56.7% |
| LOAD_CONST | 160 | 26.7% |
| CALL | 100 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 480 | 80.0% |
| GET_ITER | 60 | 10.0% |
| STORE_FAST | 60 | 10.0% |


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
| LOAD_FAST_LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 80 | 100.0% |


</details>

### CALL_STR_1

<details>
<summary> Successors and predecessors for CALL_STR_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 340 | 94.4% |
| CALL | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 360 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,621,400 | 50.0% |
| LOAD_FAST | 2,621,400 | 50.0% |
| COMPARE_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 5,242,840 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 80 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 280 | 77.8% |
| GET_ITER | 60 | 16.7% |
| FOR_ITER | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360 | 100.0% |


</details>

### FOR_ITER_TUPLE

<details>
<summary> Successors and predecessors for FOR_ITER_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 260 | 61.9% |
| GET_ITER | 160 | 38.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 360 | 85.7% |
| LOAD_FAST | 60 | 14.3% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 5,242,800 | 100.0% |
| LOAD_ATTR | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,621,440 | 50.0% |
| LOAD_CONST | 2,621,420 | 50.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| CALL_BUILTIN_CLASS | 40 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 660 | 71.7% |
| LOAD_ATTR | 180 | 19.6% |
| CALL_BUILTIN_FAST | 80 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 720 | 78.3% |
| CALL_METHOD_DESCRIPTOR_NOARGS | 80 | 8.7% |
| LOAD_GLOBAL_BUILTIN | 80 | 8.7% |
| CALL | 40 | 4.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 2,621,900 | 100.0% |
| LOAD_ATTR | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,621,960 | 100.0% |
| CALL | 60 | 0.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_INSTANCE_VALUE | 2,621,440 | 99.9% |
| LOAD_FAST_LOAD_FAST | 340 | 0.0% |
| PUSH_EXC_INFO | 320 | 0.0% |
| NOP | 280 | 0.0% |
| STORE_FAST | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,900 | 100.0% |
| LOAD_FAST_LOAD_FAST | 580 | 0.0% |
| CHECK_EXC_MATCH | 320 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |
| CALL_ISINSTANCE | 80 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,621,780 | 100.0% |
| LOAD_GLOBAL | 160 | 0.0% |
| RESUME_CHECK | 120 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| LOAD_DEREF | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 2,621,900 | 100.0% |
| LOAD_ATTR | 180 | 0.0% |
| CALL | 140 | 0.0% |
| LOAD_FAST | 80 | 0.0% |
| LOAD_FAST_LOAD_FAST | 80 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 2,621,540 | 100.0% |
| COPY_FREE_VARS | 140 | 0.0% |
| MAKE_CELL | 80 | 0.0% |
| CALL_PY_WITH_DEFAULTS | 80 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,621,560 | 100.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 80 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 5,242,800 | 100.0% |
| LOAD_FAST | 80 | 0.0% |
| STORE_ATTR | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 2,621,480 | 50.0% |
| LOAD_FAST | 2,621,420 | 50.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### TO_BOOL_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_ISINSTANCE | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 80 | 100.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 2,621,400 | 100.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,621,420 | 100.0% |


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
|     deferred | 140 | 0.0% |
|          hit | 5,242,900 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 75.0% |
| Failure | 20 | 25.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide different types | 20 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 20.0% |
|          hit | 60 | 60.0% |

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
|     deferred | 840 | 0.0% |
|          hit | 5,245,200 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 280 | 66.7% |
| Failure | 140 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 42.9% |
| meth descr method fastcall keywords | 40 | 28.6% |
| meth descr varargs keywords | 20 | 14.3% |
| class no vectorcall | 20 | 14.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 40 | 0.0% |
|          hit | 5,242,920 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 2,621,540 | 99.9% |
|          hit | 780 | 0.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 2.3% |
| Failure | 840 | 97.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| other | 840 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 460 | 0.0% |
|          hit | 7,865,900 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 380 | 95.0% |
| Failure | 20 | 5.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| module attr not found | 20 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 240 | 0.0% |
|          hit | 5,245,340 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 100.0% |
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
|     deferred | 240 | 0.0% |
|          hit | 5,242,960 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 66.7% |
| Failure | 40 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| not managed dict | 40 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 80 | 100.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 2,621,420 | 100.0% |

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
| Basic | 52,444,660 | 51.3% |
| Not specialized | 10,490,540 | 10.3% |
| Specialized hits | 39,329,460 | 38.5% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| FOR_ITER | 2,621,540 | 99.9% |
| CALL | 840 | 0.0% |
| LOAD_ATTR | 460 | 0.0% |
| LOAD_GLOBAL | 240 | 0.0% |
| STORE_ATTR | 240 | 0.0% |
| BINARY_OP | 140 | 0.0% |
| COMPARE_OP | 40 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |


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
| Calls to PyEval_EvalDefault | 2,621,760 | 100.0% |
| Calls to Python functions inlined | 240 | 0.0% |
| Calls via PyEval_EvalFrame (total) | 2,621,760 | 100.0% |
| Calls via PyEval_EvalFrame (vector) | 2,621,760 | 100.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 2,621,760 | 100.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 80 | 0.0% |
| Frame objects created | 80 | 0.0% |
| Frames pushed | 80 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 39,337,920 | 51.8% |
| Frees to freelist | 39,337,960 |  |
| Allocations | 36,592,020 | 48.2% |
| Allocations to 512 bytes | 36,591,980 | 48.2% |
| Allocations to 4 kbytes | 40 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 39,226,763 |  |
| New values | 80 |  |
| Interpreter increfs | 81,138,120 | 63.2% |
| Interpreter decrefs | 96,838,880 | 48.0% |
| Increfs | 47,191,236 | 36.8% |
| Decrefs | 104,798,403 | 52.0% |
| Materialize dict (on request) | 0 | 0.0% |
| Materialize dict (new key) | 0 | 0.0% |
| Materialize dict (too big) | 0 | 0.0% |
| Materialize dict (str subclass) | 0 | 0.0% |
| Dematerialize dict | 0 | 0.0% |
| Method cache hits | 2,622,847 |  |
| Method cache misses | 293 |  |
| Method cache collisions | 409 |  |
| Method cache dunder hits | 760 |  |
| Method cache dunder misses | 220 |  |


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
| Optimization attempts | 60 |  |
| Traces created | 40 | 66.7% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 20 | 33.3% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 360 |  |
| Uops executed | 99,604,600 | 276,679.44 |

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
| <= 64 | 40 | 100.0% |


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
| <= 32 | 20 | 50.0% |
| <= 64 | 20 | 50.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 100 | 27.8% |
| <= 16 | 160 | 44.4% |
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 5.6% |
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
| <= 2,097,152 | 80 | 22.2% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 26,211,620 | 26.3% | 26.3% |  |
| LOAD_FAST | 13,105,760 | 13.2% | 39.5% |  |
| STORE_FAST | 5,242,340 | 5.3% | 44.7% |  |
| _GUARD_GLOBALS_VERSION | 5,242,340 | 5.3% | 50.0% |  |
| _POP_JUMP_IF_TRUE | 2,621,440 | 2.6% | 52.6% |  |
| _GUARD_BUILTINS_VERSION | 2,621,280 | 2.6% | 55.3% |  |
| _LOAD_GLOBAL_BUILTINS | 2,621,280 | 2.6% | 57.9% |  |
| POP_TOP | 2,621,260 | 2.6% | 60.5% |  |
| _ITER_CHECK_RANGE | 2,621,140 | 2.6% | 63.2% |  |
| _IS_ITER_EXHAUSTED_RANGE | 2,621,140 | 2.6% | 65.8% |  |
| _JUMP_TO_TOP | 2,621,080 | 2.6% | 68.4% |  |
| PUSH_NULL | 2,621,060 | 2.6% | 71.1% |  |
| BUILD_LIST | 2,621,060 | 2.6% | 73.7% |  |
| LOAD_CONST | 2,621,060 | 2.6% | 76.3% |  |
| CALL_BUILTIN_O | 2,621,060 | 2.6% | 78.9% |  |
| CALL_METHOD_DESCRIPTOR_FAST | 2,621,060 | 2.6% | 81.6% |  |
| CALL_STR_1 | 2,621,060 | 2.6% | 84.2% |  |
| _LOAD_GLOBAL_MODULE | 2,621,060 | 2.6% | 86.8% |  |
| _GUARD_TYPE_VERSION | 2,621,060 | 2.6% | 89.5% |  |
| _CHECK_ATTR_MODULE | 2,621,060 | 2.6% | 92.1% |  |
| _LOAD_ATTR_MODULE | 2,621,060 | 2.6% | 94.7% |  |
| _ITER_NEXT_RANGE | 2,621,060 | 2.6% | 97.4% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 2,621,060 | 2.6% | 100.0% |  |
| _ITER_CHECK_TUPLE | 300 | 0.0% | 100.0% |  |
| _IS_ITER_EXHAUSTED_TUPLE | 300 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST | 220 | 0.0% | 100.0% |  |
| _ITER_NEXT_TUPLE | 200 | 0.0% | 100.0% |  |
| _EXIT_TRACE | 180 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| FOR_ITER | 20 |


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
