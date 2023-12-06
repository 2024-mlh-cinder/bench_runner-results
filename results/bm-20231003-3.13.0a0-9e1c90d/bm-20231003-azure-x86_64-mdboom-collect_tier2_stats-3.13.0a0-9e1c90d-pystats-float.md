
# Pystats results

- benchmark: float
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 168,000,180 | 24.6% | 24.6% |  |
| LOAD_ATTR_SLOT | 89,999,460 | 13.2% | 37.7% |  |
| STORE_ATTR_SLOT | 53,999,820 | 7.9% | 45.6% |  |
| STORE_FAST | 36,000,480 | 5.3% | 50.9% |  |
| BINARY_OP | 30,007,400 | 4.4% | 55.3% |  |
| LOAD_FAST_LOAD_FAST | 30,000,000 | 4.4% | 59.6% |  |
| COPY | 24,000,000 | 3.5% | 63.2% |  |
| BINARY_OP_MULTIPLY_FLOAT | 24,000,000 | 3.5% | 66.7% |  |
| LOAD_GLOBAL_MODULE | 18,000,220 | 2.6% | 69.3% |  |
| RESUME_CHECK | 18,000,120 | 2.6% | 71.9% | 0.0% |
| SWAP | 18,000,000 | 2.6% | 74.6% |  |
| CALL_BUILTIN_O | 18,000,000 | 2.6% | 77.2% |  |
| ENTER_EXECUTOR | 17,999,940 | 2.6% | 79.8% |  |
| POP_JUMP_IF_FALSE | 17,999,880 | 2.6% | 82.5% |  |
| COMPARE_OP_FLOAT | 17,999,820 | 2.6% | 85.1% |  |
| LOAD_CONST | 12,000,300 | 1.8% | 86.8% |  |
| RETURN_CONST | 12,000,000 | 1.8% | 88.6% |  |
| CALL_PY_EXACT_ARGS | 12,000,000 | 1.8% | 90.4% |  |
| BINARY_OP_ADD_FLOAT | 12,000,000 | 1.8% | 92.1% |  |
| LOAD_ATTR_METHOD_NO_DICT | 11,999,940 | 1.8% | 93.9% |  |
| JUMP_FORWARD | 11,995,080 | 1.8% | 95.6% |  |
| CALL | 6,001,820 | 0.9% | 96.5% |  |
| RETURN_VALUE | 6,000,120 | 0.9% | 97.4% |  |
| POP_TOP | 6,000,120 | 0.9% | 98.2% |  |
| INTERPRETER_EXIT | 6,000,060 | 0.9% | 99.1% |  |
| STORE_SUBSCR_LIST_INT | 6,000,000 | 0.9% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| GET_ITER | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 120 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 120 | 0.0% | 100.0% |  |
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
| LOAD_FAST LOAD_ATTR_SLOT | 71,999,460 | 10.5% | 10.5% |
| LOAD_ATTR_SLOT LOAD_FAST | 42,004,560 | 6.1% | 16.7% |
| LOAD_FAST STORE_ATTR_SLOT | 35,999,820 | 5.3% | 21.9% |
| STORE_ATTR_SLOT LOAD_FAST | 29,999,820 | 4.4% | 26.3% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 24,000,000 | 3.5% | 29.8% |
| STORE_FAST LOAD_FAST | 18,000,360 | 2.6% | 32.5% |
| LOAD_FAST BINARY_OP | 18,000,080 | 2.6% | 35.1% |
| SWAP STORE_ATTR_SLOT | 18,000,000 | 2.6% | 37.7% |
| LOAD_FAST COPY | 18,000,000 | 2.6% | 40.4% |
| LOAD_ATTR_SLOT STORE_FAST | 18,000,000 | 2.6% | 43.0% |
| COPY LOAD_ATTR_SLOT | 18,000,000 | 2.6% | 45.6% |
| BINARY_OP SWAP | 18,000,000 | 2.6% | 48.2% |
| POP_JUMP_IF_FALSE LOAD_FAST | 17,999,880 | 2.6% | 50.9% |
| LOAD_ATTR_SLOT COMPARE_OP_FLOAT | 17,999,820 | 2.6% | 53.5% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 17,999,820 | 2.6% | 56.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 12,000,120 | 1.8% | 57.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 12,000,060 | 1.8% | 59.6% |
| STORE_ATTR_SLOT RETURN_CONST | 12,000,000 | 1.8% | 61.4% |
| RESUME_CHECK LOAD_FAST | 12,000,000 | 1.8% | 63.2% |
| LOAD_FAST CALL_BUILTIN_O | 12,000,000 | 1.8% | 64.9% |
| LOAD_CONST BINARY_OP | 12,000,000 | 1.8% | 66.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 12,000,000 | 1.8% | 68.4% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 12,000,000 | 1.8% | 70.2% |
| BINARY_OP LOAD_FAST | 12,000,000 | 1.8% | 71.9% |
| ENTER_EXECUTOR LOAD_ATTR_METHOD_NO_DICT | 11,999,820 | 1.8% | 73.7% |
| LOAD_ATTR_SLOT JUMP_FORWARD | 11,995,080 | 1.8% | 75.4% |
| JUMP_FORWARD LOAD_FAST | 11,995,080 | 1.8% | 77.2% |
| LOAD_FAST RETURN_VALUE | 6,000,060 | 0.9% | 78.1% |
| CACHE RESUME_CHECK | 6,000,060 | 0.9% | 78.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 6,000,040 | 0.9% | 79.8% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 6,000,000 | 0.9% | 80.7% |
| STORE_ATTR_SLOT STORE_FAST | 6,000,000 | 0.9% | 81.6% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 6,000,000 | 0.9% | 82.5% |
| RETURN_CONST POP_TOP | 6,000,000 | 0.9% | 83.3% |
| RETURN_CONST INTERPRETER_EXIT | 6,000,000 | 0.9% | 84.2% |
| POP_TOP ENTER_EXECUTOR | 6,000,000 | 0.9% | 85.1% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 6,000,000 | 0.9% | 86.0% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 6,000,000 | 0.9% | 86.8% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 6,000,000 | 0.9% | 87.7% |
| COPY LOAD_FAST | 6,000,000 | 0.9% | 88.6% |
| CALL_BUILTIN_O STORE_FAST | 6,000,000 | 0.9% | 89.5% |
| CALL_BUILTIN_O LOAD_CONST | 6,000,000 | 0.9% | 90.3% |
| CALL_BUILTIN_O COPY | 6,000,000 | 0.9% | 91.2% |
| CALL LOAD_FAST_LOAD_FAST | 6,000,000 | 0.9% | 92.1% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 6,000,000 | 0.9% | 93.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 6,000,000 | 0.9% | 93.9% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 6,000,000 | 0.9% | 94.7% |
| BINARY_OP_ADD_FLOAT CALL_BUILTIN_O | 6,000,000 | 0.9% | 95.6% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 5,999,980 | 0.9% | 96.5% |
| STORE_FAST ENTER_EXECUTOR | 5,999,940 | 0.9% | 97.4% |
| RETURN_VALUE STORE_FAST | 5,999,940 | 0.9% | 98.2% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 5,999,940 | 0.9% | 99.1% |
| ENTER_EXECUTOR CALL | 5,999,940 | 0.9% | 100.0% |
| BINARY_OP BINARY_OP | 7,320 | 0.0% | 100.0% |
| CALL CALL | 1,540 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 180 | 0.0% | 100.0% |
| LOAD_FAST LOAD_CONST | 180 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 120 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_LIST | 120 | 0.0% | 100.0% |
| FOR_ITER_LIST STORE_FAST | 120 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| LOAD_FAST CALL | 100 | 0.0% | 100.0% |
| STORE_FAST LOAD_DEREF | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
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
| GET_ITER FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS GET_ITER | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_FAST | 60 | 0.0% | 100.0% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 60 | 0.0% | 100.0% |
| BINARY_SLICE GET_ITER | 60 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 60 | 0.0% | 100.0% |
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
| LOAD_FAST | 6,000,060 | 100.0% |
| RETURN_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,999,940 | 100.0% |
| RETURN_VALUE | 60 | 0.0% |
| INTERPRETER_EXIT | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,000,080 | 60.0% |
| LOAD_CONST | 12,000,000 | 40.0% |
| BINARY_OP | 7,320 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 18,000,000 | 60.0% |
| LOAD_FAST | 12,000,000 | 40.0% |
| BINARY_OP | 7,320 | 0.0% |
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
| LOAD_FAST | 18,000,000 | 75.0% |
| CALL_BUILTIN_O | 6,000,000 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 18,000,000 | 75.0% |
| LOAD_FAST | 6,000,000 | 25.0% |


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
| STORE_SUBSCR_LIST_INT | 6,000,000 | 33.3% |
| POP_TOP | 6,000,000 | 33.3% |
| STORE_FAST | 5,999,940 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 11,999,820 | 66.7% |
| CALL | 5,999,940 | 33.3% |
| LOAD_FAST | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 11,995,080 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 11,995,080 | 100.0% |


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
| LOAD_ATTR_SLOT | 42,004,560 | 25.0% |
| STORE_ATTR_SLOT | 29,999,820 | 17.9% |
| STORE_FAST | 18,000,360 | 10.7% |
| POP_JUMP_IF_FALSE | 17,999,880 | 10.7% |
| LOAD_GLOBAL_MODULE | 12,000,120 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 71,999,460 | 42.9% |
| STORE_ATTR_SLOT | 35,999,820 | 21.4% |
| BINARY_OP | 18,000,080 | 10.7% |
| COPY | 18,000,000 | 10.7% |
| CALL_BUILTIN_O | 12,000,000 | 7.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 6,000,000 | 20.0% |
| LOAD_GLOBAL_MODULE | 6,000,000 | 20.0% |
| CALL | 6,000,000 | 20.0% |
| BINARY_OP_MULTIPLY_FLOAT | 6,000,000 | 20.0% |
| BINARY_OP_ADD_FLOAT | 6,000,000 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 24,000,000 | 80.0% |
| STORE_SUBSCR_LIST_INT | 6,000,000 | 20.0% |


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
| COMPARE_OP_FLOAT | 17,999,820 | 100.0% |
| COMPARE_OP_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 17,999,880 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 12,000,000 | 100.0% |

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
| LOAD_ATTR_SLOT | 18,000,000 | 50.0% |
| STORE_ATTR_SLOT | 6,000,000 | 16.7% |
| CALL_BUILTIN_O | 6,000,000 | 16.7% |
| RETURN_VALUE | 5,999,940 | 16.7% |
| FOR_ITER_LIST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 18,000,360 | 50.0% |
| LOAD_GLOBAL_MODULE | 12,000,060 | 33.3% |
| ENTER_EXECUTOR | 5,999,940 | 16.7% |
| LOAD_DEREF | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 18,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 18,000,000 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 12,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 6,000,000 | 50.0% |
| CALL_BUILTIN_O | 6,000,000 | 50.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 24,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 12,000,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 6,000,000 | 25.0% |
| LOAD_CONST | 6,000,000 | 25.0% |


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
| LOAD_FAST | 12,000,000 | 66.7% |
| BINARY_OP_ADD_FLOAT | 6,000,000 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 6,000,000 | 33.3% |
| LOAD_CONST | 6,000,000 | 33.3% |
| COPY | 6,000,000 | 33.3% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_METHOD_NO_DICT | 6,000,000 | 50.0% |
| LOAD_FAST | 5,999,980 | 50.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 12,000,000 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 17,999,820 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 17,999,820 | 100.0% |


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
| ENTER_EXECUTOR | 11,999,820 | 100.0% |
| LOAD_FAST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 6,000,000 | 50.0% |
| LOAD_FAST | 5,999,940 | 50.0% |


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
| LOAD_FAST | 71,999,460 | 80.0% |
| COPY | 18,000,000 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 42,004,560 | 46.7% |
| STORE_FAST | 18,000,000 | 20.0% |
| COMPARE_OP_FLOAT | 17,999,820 | 20.0% |
| JUMP_FORWARD | 11,995,080 | 13.3% |


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
| STORE_FAST | 12,000,060 | 66.7% |
| RESUME_CHECK | 6,000,040 | 33.3% |
| LOAD_GLOBAL | 60 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |
| RETURN_VALUE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000,120 | 66.7% |
| LOAD_FAST_LOAD_FAST | 6,000,000 | 33.3% |
| LOAD_ATTR_MODULE | 60 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 12,000,000 | 66.7% |
| CACHE | 6,000,060 | 33.3% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000,000 | 66.7% |
| LOAD_GLOBAL_MODULE | 6,000,040 | 33.3% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 35,999,820 | 66.7% |
| SWAP | 18,000,000 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,999,820 | 55.6% |
| RETURN_CONST | 12,000,000 | 22.2% |
| STORE_FAST | 6,000,000 | 11.1% |
| LOAD_FAST_LOAD_FAST | 6,000,000 | 11.1% |


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
| specialization.deferred |     30000060 | 45.4% |
|          hit |     36000060 | 54.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.3% |
| Failure | 7,320 | 99.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide float | 4,380 | 59.8% |
| multiply different types | 1,480 | 20.2% |
| true divide different types | 1,460 | 19.9% |


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
|          hit |     18000280 | 100.0% |

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
| Basic | 347,997,120 | 50.9% |
| Not specialized | 54,017,880 | 7.9% |
| Specialized | 281,991,440 | 41.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,023,800 | 100.0% |
| BINARY_OP | 30,000,060 | 0.0% |
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
| Interpreter increfs | 425,938,720 | 87.7% |
| Interpreter decrefs | 485,923,560 | 82.7% |
| Increfs | 59,968,960 | 12.3% |
| Decrefs | 101,986,340 | 17.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 18 |  |
| Method cache misses | 2 |  |
| Method cache collisions | 2 |  |
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
| 2 | 60 | 0 | 48,854,720 |


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
| Traces executed | 17,999,940 |  |
| Uops executed | 179,998,920 | 9 |
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
| <= 8 | 180 | 0.0% |
| <= 16 | 17,999,760 | 100.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 41,999,820 | 23.3% | 23.3% |
| _POP_JUMP_IF_TRUE | 17,999,940 | 10.0% | 33.3% |
| _EXIT_TRACE | 17,999,940 | 10.0% | 43.3% |
| STORE_FAST | 17,999,760 | 10.0% | 53.3% |
| LOAD_FAST | 17,999,760 | 10.0% | 63.3% |
| _ITER_CHECK_LIST | 11,999,940 | 6.7% | 70.0% |
| _IS_ITER_EXHAUSTED_LIST | 11,999,940 | 6.7% | 76.7% |
| _ITER_NEXT_LIST | 11,999,820 | 6.7% | 83.3% |
| _ITER_CHECK_RANGE | 6,000,000 | 3.3% | 86.7% |
| _IS_ITER_EXHAUSTED_RANGE | 6,000,000 | 3.3% | 90.0% |
| _LOAD_GLOBAL_MODULE | 5,999,940 | 3.3% | 93.3% |
| _ITER_NEXT_RANGE | 5,999,940 | 3.3% | 96.7% |
| _GUARD_GLOBALS_VERSION | 5,999,940 | 3.3% | 100.0% |
| POP_TOP | 180 | 0.0% | 100.0% |


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
