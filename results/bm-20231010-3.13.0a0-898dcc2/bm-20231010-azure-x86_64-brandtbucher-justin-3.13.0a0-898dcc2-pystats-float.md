
# Pystats results

- benchmark: float
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 30,068,220 | 16.7% | 16.7% |  |
| STORE_ATTR_SLOT | 18,019,140 | 10.0% | 26.7% |  |
| ENTER_EXECUTOR | 12,009,360 | 6.7% | 33.4% |  |
| BINARY_OP | 12,003,200 | 6.7% | 40.0% |  |
| LOAD_CONST | 12,000,300 | 6.7% | 46.7% |  |
| LOAD_GLOBAL_MODULE | 12,000,280 | 6.7% | 53.3% |  |
| LOAD_FAST_LOAD_FAST | 12,000,180 | 6.7% | 60.0% |  |
| CALL_BUILTIN_O | 12,000,060 | 6.7% | 66.7% |  |
| RETURN_CONST | 12,000,000 | 6.7% | 73.3% |  |
| STORE_FAST | 6,010,140 | 3.3% | 76.6% |  |
| CALL | 6,001,820 | 3.3% | 80.0% |  |
| RESUME_CHECK | 6,000,300 | 3.3% | 83.3% | 0.1% |
| COPY | 6,000,180 | 3.3% | 86.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 6,000,180 | 3.3% | 90.0% |  |
| POP_TOP | 6,000,120 | 3.3% | 93.3% |  |
| INTERPRETER_EXIT | 6,000,060 | 3.3% | 96.6% |  |
| STORE_SUBSCR_LIST_INT | 6,000,000 | 3.3% | 100.0% |  |
| LOAD_ATTR_SLOT | 38,640 | 0.0% | 100.0% |  |
| POP_JUMP_IF_FALSE | 9,720 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 9,660 | 0.0% | 100.0% |  |
| RETURN_VALUE | 9,540 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 4,800 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| SWAP | 180 | 0.0% | 100.0% |  |
| GET_ITER | 180 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 120 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 100 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 60 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| BINARY_SLICE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST STORE_ATTR_SLOT | 18,018,960 | 10.0% | 10.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 12,000,120 | 6.7% | 16.7% |
| LOAD_FAST CALL_BUILTIN_O | 12,000,000 | 6.7% | 23.3% |
| LOAD_CONST BINARY_OP | 12,000,000 | 6.7% | 30.0% |
| BINARY_OP LOAD_FAST | 12,000,000 | 6.7% | 36.6% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 6,000,180 | 3.3% | 40.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 6,000,120 | 3.3% | 43.3% |
| STORE_ATTR_SLOT RETURN_CONST | 6,000,060 | 3.3% | 46.6% |
| CACHE RESUME_CHECK | 6,000,060 | 3.3% | 50.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 6,000,040 | 3.3% | 53.3% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 6,000,000 | 3.3% | 56.6% |
| STORE_ATTR_SLOT STORE_FAST | 6,000,000 | 3.3% | 59.9% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 6,000,000 | 3.3% | 63.3% |
| RETURN_CONST POP_TOP | 6,000,000 | 3.3% | 66.6% |
| RETURN_CONST INTERPRETER_EXIT | 6,000,000 | 3.3% | 69.9% |
| POP_TOP ENTER_EXECUTOR | 6,000,000 | 3.3% | 73.3% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 6,000,000 | 3.3% | 76.6% |
| COPY LOAD_FAST | 6,000,000 | 3.3% | 79.9% |
| CALL_BUILTIN_O LOAD_CONST | 6,000,000 | 3.3% | 83.3% |
| CALL_BUILTIN_O COPY | 6,000,000 | 3.3% | 86.6% |
| CALL LOAD_FAST_LOAD_FAST | 6,000,000 | 3.3% | 89.9% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 6,000,000 | 3.3% | 93.2% |
| ENTER_EXECUTOR RETURN_CONST | 5,999,940 | 3.3% | 96.6% |
| ENTER_EXECUTOR CALL | 5,999,940 | 3.3% | 99.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 38,460 | 0.0% | 99.9% |
| LOAD_ATTR_SLOT LOAD_FAST | 24,000 | 0.0% | 99.9% |
| STORE_ATTR_SLOT LOAD_FAST | 19,080 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 9,720 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT COMPARE_OP_FLOAT | 9,660 | 0.0% | 100.0% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 9,660 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 9,480 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 9,420 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 9,360 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 9,360 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT JUMP_FORWARD | 4,800 | 0.0% | 100.0% |
| JUMP_FORWARD LOAD_FAST | 4,800 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 2,940 | 0.0% | 100.0% |
| CALL CALL | 1,540 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 540 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 260 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| SWAP STORE_ATTR_SLOT | 180 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST | 180 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 180 | 0.0% | 100.0% |
| LOAD_FAST LOAD_CONST | 180 | 0.0% | 100.0% |
| LOAD_FAST COPY | 180 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT STORE_FAST | 180 | 0.0% | 100.0% |
| COPY LOAD_ATTR_SLOT | 180 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 180 | 0.0% | 100.0% |
| BINARY_OP SWAP | 180 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_LIST | 120 | 0.0% | 100.0% |
| FOR_ITER_LIST STORE_FAST | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 120 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 100 | 0.0% | 100.0% |
| LOAD_FAST CALL | 100 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 60 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_DEREF STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 60 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 60 | 0.0% | 100.0% |
| LOAD_CONST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_CONST BINARY_SLICE | 60 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE STORE_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 60 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_O STORE_FAST | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS GET_ITER | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_FAST | 60 | 0.0% | 100.0% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 60 | 0.0% | 100.0% |
| BINARY_SLICE GET_ITER | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 60 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 60 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 60 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT CALL_BUILTIN_O | 60 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |


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
| GET_ITER | 60 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 6,000,060 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 20 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 33.3% |
| CALL_BUILTIN_CLASS | 60 | 33.3% |
| BINARY_SLICE | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 120 | 66.7% |
| FOR_ITER_RANGE | 60 | 33.3% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,000,000 | 100.0% |
| RETURN_VALUE | 60 | 0.0% |

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
| RETURN_CONST | 6,000,000 | 100.0% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,000,000 | 100.0% |
| NOP | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 60.0% |
| LOAD_DEREF | 60 | 20.0% |
| LOAD_ATTR_MODULE | 40 | 13.3% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 80.0% |
| LOAD_FAST | 60 | 20.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,480 | 99.4% |
| RETURN_VALUE | 60 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 9,360 | 98.1% |
| RETURN_VALUE | 60 | 0.6% |
| INTERPRETER_EXIT | 60 | 0.6% |
| LOAD_GLOBAL | 40 | 0.4% |
| LOAD_GLOBAL_MODULE | 20 | 0.2% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 12,000,000 | 100.0% |
| BINARY_OP | 2,940 | 0.0% |
| LOAD_FAST | 260 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000,000 | 100.0% |
| BINARY_OP | 2,940 | 0.0% |
| SWAP | 180 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 5,999,940 | 100.0% |
| CALL | 1,540 | 0.0% |
| PUSH_NULL | 240 | 0.0% |
| LOAD_FAST | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000,000 | 100.0% |
| CALL | 1,540 | 0.0% |
| POP_TOP | 120 | 0.0% |
| STORE_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 6,000,000 | 100.0% |
| LOAD_FAST | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,000,000 | 100.0% |
| LOAD_ATTR_SLOT | 180 | 0.0% |


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
| STORE_SUBSCR_LIST_INT | 6,000,000 | 50.0% |
| POP_TOP | 6,000,000 | 50.0% |
| STORE_FAST | 9,360 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 5,999,940 | 50.0% |
| CALL | 5,999,940 | 50.0% |
| LOAD_FAST | 9,420 | 0.1% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 4,800 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,800 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 40 | 66.7% |
| PUSH_NULL | 20 | 33.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_O | 6,000,000 | 50.0% |
| BINARY_OP_MULTIPLY_FLOAT | 6,000,000 | 50.0% |
| LOAD_FAST | 180 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 12,000,000 | 100.0% |
| LOAD_CONST | 60 | 0.0% |
| BUILD_LIST | 60 | 0.0% |
| BINARY_SLICE | 60 | 0.0% |
| COMPARE_OP_INT | 40 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| NOP | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| PUSH_NULL | 60 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 12,000,120 | 39.9% |
| BINARY_OP | 12,000,000 | 39.9% |
| COPY | 6,000,000 | 20.0% |
| LOAD_ATTR_SLOT | 24,000 | 0.1% |
| STORE_ATTR_SLOT | 19,080 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 18,018,960 | 59.9% |
| CALL_BUILTIN_O | 12,000,000 | 39.9% |
| LOAD_ATTR_SLOT | 38,460 | 0.1% |
| RETURN_VALUE | 9,480 | 0.0% |
| BINARY_OP | 260 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,000,000 | 50.0% |
| CALL | 6,000,000 | 50.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |
| BINARY_OP_MULTIPLY_FLOAT | 60 | 0.0% |
| BINARY_OP_ADD_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 6,000,180 | 50.0% |
| STORE_SUBSCR_LIST_INT | 6,000,000 | 50.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 40.0% |
| STORE_FAST | 20 | 20.0% |
| RESUME_CHECK | 20 | 20.0% |
| ENTER_EXECUTOR | 20 | 20.0% |

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
| COMPARE_OP_FLOAT | 9,660 | 99.4% |
| COMPARE_OP_INT | 60 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 9,720 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,000,060 | 50.0% |
| ENTER_EXECUTOR | 5,999,940 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 6,000,000 | 50.0% |
| INTERPRETER_EXIT | 6,000,000 | 50.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,000,000 | 99.8% |
| RETURN_VALUE | 9,360 | 0.2% |
| LOAD_ATTR_SLOT | 180 | 0.0% |
| FOR_ITER_LIST | 120 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,000,120 | 99.8% |
| ENTER_EXECUTOR | 9,360 | 0.2% |
| LOAD_FAST | 540 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 180 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 50.0% |
| CALL_BUILTIN_O | 60 | 50.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,000 | 100.0% |
| BINARY_OP_ADD_FLOAT | 120 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


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

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 66.7% |
| BINARY_SUBSCR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


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

### CALL_BUILTIN_O

<details>
<summary> Successors and predecessors for CALL_BUILTIN_O </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000,000 | 100.0% |
| BINARY_OP_ADD_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 6,000,000 | 50.0% |
| COPY | 6,000,000 | 50.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100 | 55.6% |
| LOAD_ATTR_METHOD_NO_DICT | 60 | 33.3% |
| CALL | 20 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 180 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 9,660 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 9,660 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

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
| GET_ITER | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 100.0% |


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

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| CALL_PY_EXACT_ARGS | 60 | 50.0% |


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

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 38,460 | 99.5% |
| COPY | 180 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,000 | 62.1% |
| COMPARE_OP_FLOAT | 9,660 | 25.0% |
| JUMP_FORWARD | 4,800 | 12.4% |
| STORE_FAST | 180 | 0.5% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,120 | 50.0% |
| RESUME_CHECK | 6,000,040 | 50.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000,120 | 100.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 6,000,060 | 100.0% |
| CALL_PY_EXACT_ARGS | 180 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 6,000,040 | 100.0% |
| LOAD_FAST | 180 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,018,960 | 100.0% |
| SWAP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 6,000,060 | 33.3% |
| STORE_FAST | 6,000,000 | 33.3% |
| LOAD_FAST_LOAD_FAST | 6,000,000 | 33.3% |
| LOAD_FAST | 19,080 | 0.1% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 6,000,000 | 100.0% |


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
|          hit |           60 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      6000000 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     12000240 | 25.0% |
|          hit |     36000060 | 75.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.7% |
| Failure | 2,940 | 99.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 1,480 | 50.3% |
| true divide different types | 1,460 | 49.7% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      6000240 | 16.7% |
|          hit |     30000060 | 83.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 2.5% |
| Failure | 1,540 | 97.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 1,460 | 94.8% |
| cfunc noargs | 60 | 3.9% |
| other | 20 | 1.3% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     17999880 | 100.0% |

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
|          hit |          180 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |    101999500 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
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
|          hit |     24000220 | 100.0% |

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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     53999820 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 102,103,920 | 56.7% |
| Not specialized | 18,023,520 | 10.0% |
| Specialized | 60,060,740 | 33.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,023,800 | 100.0% |
| BINARY_OP | 12,000,240 | 0.0% |
| CALL | 6,000,240 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME_CHECK | 8,520 | 50.0% |
| RESUME | 8,520 | 50.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_SLOT | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RETURN_CONST | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 6,000,060 | 33.3% |
| Calls to Python functions inlined | 12,000,060 | 66.7% |
| Calls via PyEval_EvalFrame (total) | 6,000,060 | 33.3% |
| Calls via PyEval_EvalFrame (vector) | 6,000,060 | 33.3% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 6,000,060 | 33.3% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 18,000,120 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 72,005,820 | 70.6% |
| Frees to freelist | 72,006,000 |  |
| Allocations | 29,996,580 | 29.4% |
| Allocations to 512 bytes | 29,996,460 | 29.4% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 120 | 0.0% |
| Frees | 29,996,460 |  |
| New values | 0 |  |
| Interpreter increfs | 108,056,320 | 22.5% |
| Interpreter decrefs | 186,031,440 | 32.0% |
| Increfs | 371,860,780 | 77.5% |
| Decrefs | 395,887,880 | 68.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 16 |  |
| Method cache misses | 4 |  |
| Method cache collisions | 4 |  |
| Method cache dunder hits | 6,000,000 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 7,760 | 0 | 55,487,120 |
| 1 | 700 | 0 | 57,422,000 |
| 2 | 60 | 0 | 48,826,400 |


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
Stats gathered on: 2023-10-11
