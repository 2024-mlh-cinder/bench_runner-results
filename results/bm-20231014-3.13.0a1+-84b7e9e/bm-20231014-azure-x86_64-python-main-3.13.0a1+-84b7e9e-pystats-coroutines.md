
# Pystats results

- benchmark: coroutines
- fork: python
- ref: main
- commit hash: 84b7e9e
- commit date: 2023-10-14T23:32:57+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_CONST | 174,805,200 | 16.7% | 16.7% |  |
| LOAD_FAST | 145,671,420 | 13.9% | 30.6% |  |
| POP_TOP | 58,268,700 | 5.6% | 36.1% |  |
| POP_JUMP_IF_FALSE | 58,268,640 | 5.6% | 41.7% |  |
| LOAD_GLOBAL_MODULE | 58,268,560 | 5.6% | 47.2% |  |
| RETURN_VALUE | 58,268,520 | 5.6% | 52.8% |  |
| RESUME_CHECK | 58,268,520 | 5.6% | 58.3% |  |
| RETURN_GENERATOR | 58,268,400 | 5.6% | 63.9% |  |
| COMPARE_OP_INT | 58,268,400 | 5.6% | 69.4% |  |
| CALL_PY_EXACT_ARGS | 58,268,400 | 5.6% | 75.0% |  |
| SEND_GEN | 58,268,160 | 5.6% | 80.6% |  |
| GET_AWAITABLE | 58,268,160 | 5.6% | 86.1% |  |
| END_SEND | 58,268,160 | 5.6% | 91.7% |  |
| BINARY_OP_SUBTRACT_INT | 58,268,160 | 5.6% | 97.2% |  |
| BINARY_OP_ADD_INT | 29,134,080 | 2.8% | 100.0% |  |
| STORE_FAST | 600 | 0.0% | 100.0% |  |
| NOP | 540 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 300 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 300 | 0.0% | 100.0% |  |
| CALL | 260 | 0.0% | 100.0% |  |
| PUSH_EXC_INFO | 240 | 0.0% | 100.0% |  |
| POP_EXCEPT | 240 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 240 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 240 | 0.0% | 100.0% |  |
| INTERPRETER_EXIT | 240 | 0.0% | 100.0% |  |
| CHECK_EXC_MATCH | 240 | 0.0% | 100.0% |  |
| CALL_METHOD_DESCRIPTOR_O | 240 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 100 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| GET_ITER | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST LOAD_CONST | 116,536,560 | 11.1% | 11.1% |
| RESUME_CHECK LOAD_FAST | 58,268,400 | 5.6% | 16.7% |
| POP_TOP RESUME_CHECK | 58,268,400 | 5.6% | 22.2% |
| LOAD_CONST COMPARE_OP_INT | 58,268,400 | 5.6% | 27.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 58,268,400 | 5.6% | 33.3% |
| CALL_PY_EXACT_ARGS RETURN_GENERATOR | 58,268,400 | 5.6% | 38.9% |
| SEND_GEN POP_TOP | 58,268,160 | 5.6% | 44.4% |
| RETURN_VALUE END_SEND | 58,268,160 | 5.6% | 50.0% |
| RETURN_GENERATOR GET_AWAITABLE | 58,268,160 | 5.6% | 55.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 58,268,160 | 5.6% | 61.1% |
| LOAD_CONST SEND_GEN | 58,268,160 | 5.6% | 66.7% |
| LOAD_CONST BINARY_OP_SUBTRACT_INT | 58,268,160 | 5.6% | 72.2% |
| GET_AWAITABLE LOAD_CONST | 58,268,160 | 5.6% | 77.8% |
| BINARY_OP_SUBTRACT_INT CALL_PY_EXACT_ARGS | 58,268,160 | 5.6% | 83.3% |
| POP_JUMP_IF_FALSE LOAD_FAST | 29,134,320 | 2.8% | 86.1% |
| LOAD_FAST RETURN_VALUE | 29,134,320 | 2.8% | 88.9% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_MODULE | 29,134,080 | 2.8% | 91.7% |
| END_SEND LOAD_GLOBAL_MODULE | 29,134,080 | 2.8% | 94.4% |
| END_SEND BINARY_OP_ADD_INT | 29,134,080 | 2.8% | 97.2% |
| BINARY_OP_ADD_INT RETURN_VALUE | 29,134,080 | 2.8% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 280 | 0.0% | 100.0% |
| STORE_FAST NOP | 240 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 240 | 0.0% | 100.0% |
| RETURN_GENERATOR STORE_FAST | 240 | 0.0% | 100.0% |
| PUSH_EXC_INFO LOAD_GLOBAL_BUILTIN | 240 | 0.0% | 100.0% |
| POP_TOP POP_EXCEPT | 240 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE POP_TOP | 240 | 0.0% | 100.0% |
| POP_EXCEPT JUMP_BACKWARD | 240 | 0.0% | 100.0% |
| NOP NOP | 240 | 0.0% | 100.0% |
| NOP LOAD_FAST | 240 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 240 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN CHECK_EXC_MATCH | 240 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 240 | 0.0% | 100.0% |
| LOAD_CONST CALL_PY_EXACT_ARGS | 240 | 0.0% | 100.0% |
| LOAD_CONST CALL_METHOD_DESCRIPTOR_O | 240 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_CONST | 240 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 240 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 240 | 0.0% | 100.0% |
| CHECK_EXC_MATCH POP_JUMP_IF_FALSE | 240 | 0.0% | 100.0% |
| CALL_METHOD_DESCRIPTOR_O PUSH_EXC_INFO | 240 | 0.0% | 100.0% |
| CACHE POP_TOP | 240 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 60 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CALL CALL | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 60 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 40 | 0.0% | 100.0% |
| FOR_ITER_RANGE LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_FAST CALL | 20 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 20 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 20 | 0.0% | 100.0% |
| FOR_ITER_RANGE LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 20 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% | 100.0% |


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
| POP_TOP | 240 | 100.0% |


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

### END_SEND

<details>
<summary> Successors and predecessors for END_SEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 58,268,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 29,134,080 | 50.0% |
| BINARY_OP_ADD_INT | 29,134,080 | 50.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 60 | 100.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### NOP

<details>
<summary> Successors and predecessors for NOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 44.4% |
| NOP | 240 | 44.4% |
| POP_TOP | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 240 | 44.4% |
| LOAD_FAST | 240 | 44.4% |
| LOAD_DEREF | 60 | 11.1% |


</details>

### POP_EXCEPT

<details>
<summary> Successors and predecessors for POP_EXCEPT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 100.0% |


</details>

### POP_TOP

<details>
<summary> Successors and predecessors for POP_TOP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SEND_GEN | 58,268,160 | 100.0% |
| POP_JUMP_IF_FALSE | 240 | 0.0% |
| CACHE | 240 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 58,268,400 | 100.0% |
| POP_EXCEPT | 240 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_EXC_INFO

<details>
<summary> Successors and predecessors for PUSH_EXC_INFO </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_METHOD_DESCRIPTOR_O | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 240 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 160 | 53.3% |
| LOAD_DEREF | 120 | 40.0% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 180 | 60.0% |
| LOAD_FAST | 120 | 40.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 58,268,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_AWAITABLE | 58,268,160 | 100.0% |
| STORE_FAST | 240 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,134,320 | 50.0% |
| BINARY_OP_ADD_INT | 29,134,080 | 50.0% |
| RETURN_VALUE | 60 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 58,268,160 | 100.0% |
| INTERPRETER_EXIT | 240 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 20 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 69.2% |
| CALL | 60 | 23.1% |
| LOAD_FAST | 20 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 23.1% |
| POP_TOP | 60 | 23.1% |
| LOAD_FAST | 60 | 23.1% |
| CALL | 60 | 23.1% |
| CALL_BUILTIN_CLASS | 20 | 7.7% |


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

### GET_AWAITABLE

<details>
<summary> Successors and predecessors for GET_AWAITABLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 58,268,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,268,160 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_EXCEPT | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 240 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 60 | 75.0% |
| LOAD_GLOBAL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 60 | 75.0% |
| PUSH_NULL | 20 | 25.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 116,536,560 | 66.7% |
| GET_AWAITABLE | 58,268,160 | 33.3% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |
| LOAD_ATTR_METHOD_NO_DICT | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 58,268,400 | 33.3% |
| SEND_GEN | 58,268,160 | 33.3% |
| BINARY_OP_SUBTRACT_INT | 58,268,160 | 33.3% |
| CALL_PY_EXACT_ARGS | 240 | 0.0% |
| CALL_METHOD_DESCRIPTOR_O | 240 | 0.0% |


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
| RESUME_CHECK | 58,268,400 | 40.0% |
| LOAD_GLOBAL_MODULE | 58,268,160 | 40.0% |
| POP_JUMP_IF_FALSE | 29,134,320 | 20.0% |
| NOP | 240 | 0.0% |
| PUSH_NULL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 116,536,560 | 80.0% |
| RETURN_VALUE | 29,134,320 | 20.0% |
| LOAD_ATTR_METHOD_NO_DICT | 240 | 0.0% |
| GET_ITER | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 40.0% |
| STORE_FAST | 20 | 20.0% |
| RESUME_CHECK | 20 | 20.0% |
| FOR_ITER_RANGE | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_GLOBAL_BUILTIN | 20 | 20.0% |
| LOAD_ATTR | 20 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 58,268,400 | 100.0% |
| CHECK_EXC_MATCH | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,134,320 | 50.0% |
| LOAD_GLOBAL_MODULE | 29,134,080 | 50.0% |
| POP_TOP | 240 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 240 | 40.0% |
| FOR_ITER_RANGE | 240 | 40.0% |
| CALL_BUILTIN_CLASS | 60 | 10.0% |
| CALL | 60 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 280 | 46.7% |
| NOP | 240 | 40.0% |
| LOAD_FAST | 60 | 10.0% |
| LOAD_GLOBAL | 20 | 3.3% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| END_SEND | 29,134,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 29,134,080 | 100.0% |


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

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,268,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 58,268,160 | 100.0% |


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
| STORE_FAST | 60 | 100.0% |


</details>

### CALL_METHOD_DESCRIPTOR_O

<details>
<summary> Successors and predecessors for CALL_METHOD_DESCRIPTOR_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 240 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_INT | 58,268,160 | 100.0% |
| LOAD_CONST | 240 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 58,268,400 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,268,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 58,268,400 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 240 | 80.0% |
| GET_ITER | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 80.0% |
| LOAD_GLOBAL_MODULE | 40 | 13.3% |
| LOAD_GLOBAL | 20 | 6.7% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 240 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 62.5% |
| LOAD_ATTR | 60 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_EXC_INFO | 240 | 80.0% |
| RESUME_CHECK | 40 | 13.3% |
| LOAD_GLOBAL | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CHECK_EXC_MATCH | 240 | 80.0% |
| LOAD_FAST | 60 | 20.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 29,134,080 | 50.0% |
| END_SEND | 29,134,080 | 50.0% |
| STORE_FAST | 280 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| FOR_ITER_RANGE | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,268,160 | 100.0% |
| LOAD_CONST | 240 | 0.0% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 58,268,400 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 58,268,400 | 100.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### SEND_GEN

<details>
<summary> Successors and predecessors for SEND_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 58,268,160 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 58,268,160 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     87402300 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          180 | 0.0% |
|          hit |     58268700 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 25.0% |
| Failure | 60 | 75.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     58268400 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |          300 | 100.0% |


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
| specialization.deferred |           20 | 4.2% |
|          hit |          400 | 83.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     58268860 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
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

### SEND

<details>
<summary> specialization stats for SEND family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     58268160 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 611,821,560 | 58.3% |
| Not specialized | 58,269,340 | 5.6% |
| Specialized | 378,745,640 | 36.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 180 | 81.8% |
| LOAD_GLOBAL | 20 | 9.1% |
| LOAD_ATTR | 20 | 9.1% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR | 0 | 0.0% |
| SEND_GEN | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 240 | 0.0% |
| Calls to Python functions inlined | 116,536,680 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 240 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 58,268,520 | 50.0% |
| Frame objects created | 60 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 460 | 0.0% |
| Frees to freelist | 420 |  |
| Allocations | 58,359,380 | 100.0% |
| Allocations to 512 bytes | 58,359,380 | 100.0% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 58,359,360 |  |
| New values | 0 |  |
| Interpreter increfs | 174,806,620 | 100.0% |
| Interpreter decrefs | 233,165,880 | 100.0% |
| Increfs | 1,720 | 0.0% |
| Decrefs | 2,180 | 0.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 20 |  |
| Method cache misses | 0 |  |
| Method cache collisions | 0 |  |
| Method cache dunder hits | 0 |  |
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
| Traces executed | 0 |  |
| Uops executed | 0 | 0 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
| Trace too short | 0 |  |
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
| <= 1 | 0 |  |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|


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
Stats gathered on: 2023-10-15
