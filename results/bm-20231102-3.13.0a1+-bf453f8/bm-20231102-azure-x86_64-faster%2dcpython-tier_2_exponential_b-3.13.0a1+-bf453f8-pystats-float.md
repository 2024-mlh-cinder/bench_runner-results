
# Pystats results

- benchmark: float
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bf453f8
- commit date: 2023-11-02T14:05:18+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 72,096,900 | 19.2% | 19.2% |  |
| STORE_ATTR_SLOT | 48,025,820 | 12.8% | 31.9% |  |
| BINARY_OP | 40,011,080 | 10.6% | 42.6% |  |
| COPY | 24,000,400 | 6.4% | 48.9% |  |
| SWAP | 24,000,000 | 6.4% | 55.3% |  |
| LOAD_ATTR_SLOT | 16,054,720 | 4.3% | 59.6% |  |
| ENTER_EXECUTOR | 16,011,740 | 4.3% | 63.8% |  |
| LOAD_FAST_LOAD_FAST | 16,001,200 | 4.3% | 68.1% |  |
| LOAD_GLOBAL_MODULE | 16,000,900 | 4.3% | 72.3% |  |
| LOAD_CONST | 16,000,400 | 4.3% | 76.6% |  |
| CALL_BUILTIN_O | 16,000,340 | 4.3% | 80.8% |  |
| RETURN_CONST | 16,000,000 | 4.3% | 85.1% |  |
| STORE_FAST | 8,015,980 | 2.1% | 87.2% |  |
| CALL | 8,002,820 | 2.1% | 89.4% |  |
| BINARY_OP_MULTIPLY_FLOAT | 8,001,120 | 2.1% | 91.5% |  |
| RESUME_CHECK | 8,000,920 | 2.1% | 93.6% | 0.1% |
| POP_TOP | 8,000,160 | 2.1% | 95.7% |  |
| INTERPRETER_EXIT | 8,000,080 | 2.1% | 97.9% |  |
| STORE_SUBSCR_LIST_INT | 7,999,980 | 2.1% | 100.0% |  |
| POP_JUMP_IF_FALSE | 13,800 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 13,660 | 0.0% | 100.0% |  |
| RETURN_VALUE | 12,940 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 6,920 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,020 | 0.0% | 100.0% |  |
| LOAD_ATTR | 840 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 820 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 760 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 760 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 760 | 0.0% | 100.0% |  |
| PUSH_NULL | 400 | 0.0% | 100.0% |  |
| STORE_ATTR | 400 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 380 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 320 | 0.0% | 100.0% |  |
| GET_ITER | 240 | 0.0% | 100.0% |  |
| COMPARE_OP | 160 | 0.0% | 100.0% |  |
| LOAD_DEREF | 160 | 0.0% | 100.0% |  |
| RESUME | 120 | 0.0% | 100.0% | 9,483.3% |
| FOR_ITER | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |  |
| BINARY_SLICE | 80 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| BUILD_LIST | 80 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 60 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 40 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST STORE_ATTR_SLOT | 24,025,740 | 6.4% | 6.4% |
| BINARY_OP SWAP | 24,000,000 | 6.4% | 12.8% |
| SWAP STORE_ATTR_SLOT | 23,999,880 | 6.4% | 19.1% |
| LOAD_ATTR_SLOT LOAD_FAST | 16,033,040 | 4.3% | 23.4% |
| STORE_ATTR_SLOT LOAD_FAST | 16,025,900 | 4.3% | 27.7% |
| LOAD_FAST BINARY_OP | 16,000,520 | 4.3% | 31.9% |
| LOAD_FAST COPY | 16,000,400 | 4.3% | 36.2% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 16,000,400 | 4.3% | 40.4% |
| COPY LOAD_ATTR_SLOT | 16,000,280 | 4.3% | 44.7% |
| BINARY_OP LOAD_FAST | 16,000,000 | 4.3% | 48.9% |
| LOAD_CONST BINARY_OP | 16,000,000 | 4.3% | 53.2% |
| STORE_ATTR_SLOT RETURN_CONST | 15,999,960 | 4.3% | 57.4% |
| LOAD_FAST CALL_BUILTIN_O | 15,999,920 | 4.3% | 61.7% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 8,001,040 | 2.1% | 63.8% |
| STORE_FAST LOAD_GLOBAL_MODULE | 8,000,680 | 2.1% | 65.9% |
| CACHE RESUME_CHECK | 8,000,040 | 2.1% | 68.1% |
| CALL LOAD_FAST_LOAD_FAST | 8,000,000 | 2.1% | 70.2% |
| COPY LOAD_FAST | 8,000,000 | 2.1% | 72.3% |
| RETURN_CONST INTERPRETER_EXIT | 8,000,000 | 2.1% | 74.4% |
| RETURN_CONST POP_TOP | 8,000,000 | 2.1% | 76.6% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 8,000,000 | 2.1% | 78.7% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 7,999,980 | 2.1% | 80.8% |
| CALL_BUILTIN_O COPY | 7,999,980 | 2.1% | 82.9% |
| CALL_BUILTIN_O LOAD_CONST | 7,999,980 | 2.1% | 85.1% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 7,999,980 | 2.1% | 87.2% |
| STORE_ATTR_SLOT STORE_FAST | 7,999,980 | 2.1% | 89.3% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 7,999,960 | 2.1% | 91.4% |
| POP_TOP ENTER_EXECUTOR | 7,999,660 | 2.1% | 93.6% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 7,999,660 | 2.1% | 95.7% |
| ENTER_EXECUTOR BINARY_OP | 7,999,600 | 2.1% | 97.8% |
| ENTER_EXECUTOR CALL | 7,999,600 | 2.1% | 99.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 54,100 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 13,800 | 0.0% | 100.0% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 13,660 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT COMPARE_OP_FLOAT | 13,600 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 12,860 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 12,700 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 12,460 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 12,360 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 10,760 | 0.0% | 100.0% |
| JUMP_FORWARD LOAD_FAST | 6,920 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT JUMP_FORWARD | 6,880 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 2,320 | 0.0% | 100.0% |
| CALL CALL | 2,220 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT STORE_FAST | 1,140 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 820 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST | 820 | 0.0% | 100.0% |
| FOR_ITER_LIST STORE_FAST | 760 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 720 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 720 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 640 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 600 | 0.0% | 100.0% |
| LOAD_FAST CALL | 600 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 400 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 380 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 380 | 0.0% | 100.0% |
| CALL_BUILTIN_O STORE_FAST | 380 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 380 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 380 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 380 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT CALL_BUILTIN_O | 360 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 360 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_SLOT | 340 | 0.0% | 100.0% |
| STORE_FAST JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| PUSH_NULL CALL | 320 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 320 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 300 | 0.0% | 100.0% |
| LOAD_FAST STORE_ATTR | 280 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 240 | 0.0% | 100.0% |
| LOAD_FAST LOAD_CONST | 240 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_FAST | 200 | 0.0% | 100.0% |
| STORE_ATTR STORE_ATTR_SLOT | 200 | 0.0% | 100.0% |
| CALL POP_TOP | 160 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 160 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 140 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_LIST | 120 | 0.0% | 100.0% |
| COPY LOAD_ATTR | 120 | 0.0% | 100.0% |
| STORE_ATTR LOAD_FAST | 120 | 0.0% | 100.0% |
| SWAP STORE_ATTR | 120 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 100 | 0.0% | 100.0% |
| CALL STORE_FAST | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_FAST | 100 | 0.0% | 100.0% |
| BINARY_SLICE GET_ITER | 80 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 80 | 0.0% | 100.0% |
| POP_TOP NOP | 80 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 80 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 80 | 0.0% | 100.0% |
| RETURN_VALUE INTERPRETER_EXIT | 80 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 80 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_MULTIPLY_FLOAT | 80 | 0.0% | 100.0% |
| BUILD_LIST LOAD_FAST | 80 | 0.0% | 100.0% |
| CALL LOAD_FAST | 80 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 80 | 0.0% | 100.0% |
| COMPARE_OP POP_JUMP_IF_FALSE | 80 | 0.0% | 100.0% |
| LOAD_ATTR STORE_FAST | 80 | 0.0% | 100.0% |
| LOAD_CONST BINARY_SLICE | 80 | 0.0% | 100.0% |
| LOAD_CONST BUILD_LIST | 80 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 80 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,000,040 | 100.0% |
| RESUME | 40 | 0.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 20 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 20 | 50.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 80 | 33.3% |
| LOAD_FAST | 80 | 33.3% |
| CALL_BUILTIN_CLASS | 60 | 25.0% |
| CALL | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 120 | 50.0% |
| FOR_ITER | 60 | 25.0% |
| FOR_ITER_RANGE | 60 | 25.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,000,000 | 100.0% |
| RETURN_VALUE | 80 | 0.0% |


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
| RETURN_CONST | 8,000,000 | 100.0% |
| CALL | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,999,660 | 100.0% |
| JUMP_BACKWARD | 340 | 0.0% |
| NOP | 80 | 0.0% |
| LOAD_FAST | 80 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 240 | 60.0% |
| LOAD_DEREF | 80 | 20.0% |
| LOAD_ATTR_MODULE | 60 | 15.0% |
| LOAD_ATTR | 20 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 320 | 80.0% |
| LOAD_FAST | 80 | 20.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,860 | 99.4% |
| RETURN_VALUE | 80 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,700 | 98.1% |
| INTERPRETER_EXIT | 80 | 0.6% |
| RETURN_VALUE | 80 | 0.6% |
| LOAD_GLOBAL | 40 | 0.3% |
| LOAD_GLOBAL_MODULE | 40 | 0.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 20 | 50.0% |
| STORE_SUBSCR_LIST_INT | 20 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,000,520 | 40.0% |
| LOAD_CONST | 16,000,000 | 40.0% |
| ENTER_EXECUTOR | 7,999,600 | 20.0% |
| BINARY_OP | 10,760 | 0.0% |
| LOAD_FAST_LOAD_FAST | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 24,000,000 | 60.0% |
| LOAD_FAST | 16,000,000 | 40.0% |
| BINARY_OP | 10,760 | 0.0% |
| STORE_FAST | 100 | 0.0% |
| BINARY_OP_MULTIPLY_FLOAT | 80 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,999,600 | 100.0% |
| CALL | 2,220 | 0.0% |
| LOAD_FAST | 600 | 0.0% |
| PUSH_NULL | 320 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,000,000 | 100.0% |
| CALL | 2,220 | 0.0% |
| POP_TOP | 160 | 0.0% |
| STORE_FAST | 100 | 0.0% |
| LOAD_FAST | 80 | 0.0% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 80 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR | 60 | 37.5% |
| LOAD_ATTR_SLOT | 60 | 37.5% |
| LOAD_CONST | 40 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 80 | 50.0% |
| COMPARE_OP_FLOAT | 60 | 37.5% |
| COMPARE_OP_INT | 20 | 12.5% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,000,400 | 66.7% |
| CALL_BUILTIN_O | 7,999,980 | 33.3% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 16,000,280 | 66.7% |
| LOAD_FAST | 8,000,000 | 33.3% |
| LOAD_ATTR | 120 | 0.0% |


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
| POP_TOP | 7,999,660 | 50.0% |
| STORE_SUBSCR_LIST_INT | 7,999,660 | 50.0% |
| STORE_FAST | 12,360 | 0.1% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 7,999,600 | 50.0% |
| CALL | 7,999,600 | 50.0% |
| LOAD_FAST | 12,460 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 50.0% |
| JUMP_BACKWARD | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 50.0% |
| FOR_ITER_LIST | 40 | 33.3% |
| FOR_ITER_RANGE | 20 | 16.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 340 | 33.3% |
| STORE_FAST | 340 | 33.3% |
| STORE_SUBSCR_LIST_INT | 320 | 31.4% |
| STORE_SUBSCR | 20 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 600 | 58.8% |
| FOR_ITER_RANGE | 300 | 29.4% |
| ENTER_EXECUTOR | 60 | 5.9% |
| FOR_ITER | 60 | 5.9% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,880 | 99.4% |
| LOAD_ATTR | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,920 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 640 | 76.2% |
| COPY | 120 | 14.3% |
| LOAD_GLOBAL | 40 | 4.8% |
| LOAD_GLOBAL_MODULE | 40 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 340 | 40.5% |
| LOAD_FAST | 200 | 23.8% |
| STORE_FAST | 80 | 9.5% |
| COMPARE_OP | 60 | 7.1% |
| JUMP_FORWARD | 40 | 4.8% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 7,999,980 | 50.0% |
| CALL_BUILTIN_O | 7,999,980 | 50.0% |
| LOAD_FAST | 240 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| RESUME_CHECK | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 16,000,000 | 100.0% |
| BINARY_SLICE | 80 | 0.0% |
| BUILD_LIST | 80 | 0.0% |
| LOAD_CONST | 80 | 0.0% |
| BINARY_SUBSCR | 40 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 80 | 50.0% |
| STORE_FAST | 80 | 50.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 16,033,040 | 22.2% |
| STORE_ATTR_SLOT | 16,025,900 | 22.2% |
| LOAD_GLOBAL_MODULE | 16,000,400 | 22.2% |
| BINARY_OP | 16,000,000 | 22.2% |
| COPY | 8,000,000 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 24,025,740 | 33.3% |
| BINARY_OP | 16,000,520 | 22.2% |
| COPY | 16,000,400 | 22.2% |
| CALL_BUILTIN_O | 15,999,920 | 22.2% |
| LOAD_ATTR_SLOT | 54,100 | 0.1% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 8,000,000 | 50.0% |
| STORE_ATTR_SLOT | 7,999,980 | 50.0% |
| BINARY_OP_ADD_FLOAT | 380 | 0.0% |
| BINARY_OP_MULTIPLY_FLOAT | 380 | 0.0% |
| LOAD_GLOBAL_MODULE | 380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 8,001,040 | 50.0% |
| STORE_SUBSCR_LIST_INT | 7,999,960 | 50.0% |
| BINARY_OP | 160 | 0.0% |
| STORE_SUBSCR | 40 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 160 | 50.0% |
| RETURN_VALUE | 40 | 12.5% |
| ENTER_EXECUTOR | 40 | 12.5% |
| RESUME | 40 | 12.5% |
| RESUME_CHECK | 40 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 140 | 43.8% |
| LOAD_FAST | 100 | 31.2% |
| LOAD_ATTR | 40 | 12.5% |
| LOAD_FAST_LOAD_FAST | 20 | 6.2% |
| LOAD_GLOBAL_BUILTIN | 20 | 6.2% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_FLOAT | 13,660 | 99.0% |
| COMPARE_OP | 80 | 0.6% |
| COMPARE_OP_INT | 60 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,800 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 15,999,960 | 100.0% |
| STORE_ATTR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 8,000,000 | 50.0% |
| POP_TOP | 8,000,000 | 50.0% |


</details>

### STORE_ATTR

<details>
<summary> Successors and predecessors for STORE_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 70.0% |
| SWAP | 120 | 30.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 200 | 50.0% |
| LOAD_FAST | 120 | 30.0% |
| RETURN_CONST | 40 | 10.0% |
| LOAD_FAST_LOAD_FAST | 20 | 5.0% |
| STORE_FAST | 20 | 5.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 7,999,980 | 99.8% |
| RETURN_VALUE | 12,700 | 0.2% |
| LOAD_ATTR_SLOT | 1,140 | 0.0% |
| FOR_ITER_LIST | 760 | 0.0% |
| CALL_BUILTIN_O | 380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,000,680 | 99.8% |
| ENTER_EXECUTOR | 12,360 | 0.2% |
| LOAD_FAST | 2,320 | 0.0% |
| JUMP_BACKWARD | 340 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 24,000,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 23,999,880 | 100.0% |
| STORE_ATTR | 120 | 0.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 50.0% |
| CACHE | 40 | 33.3% |
| COPY_FREE_VARS | 20 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 50.0% |
| LOAD_GLOBAL | 40 | 33.3% |
| LOAD_CONST | 20 | 16.7% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 720 | 94.7% |
| BINARY_OP | 40 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 380 | 50.0% |
| CALL_BUILTIN_O | 360 | 47.4% |
| CALL | 20 | 2.6% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,001,040 | 100.0% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,999,980 | 100.0% |
| BINARY_OP_ADD_FLOAT | 720 | 0.0% |
| LOAD_FAST_LOAD_FAST | 380 | 0.0% |
| BINARY_OP | 40 | 0.0% |


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
| LOAD_FAST | 15,999,920 | 100.0% |
| BINARY_OP_ADD_FLOAT | 360 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 7,999,980 | 50.0% |
| LOAD_CONST | 7,999,980 | 50.0% |
| STORE_FAST | 380 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 48.8% |
| LOAD_ATTR_METHOD_NO_DICT | 360 | 43.9% |
| CALL | 60 | 7.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 820 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 13,600 | 99.6% |
| COMPARE_OP | 60 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,660 | 100.0% |


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
| JUMP_BACKWARD | 600 | 78.9% |
| GET_ITER | 120 | 15.8% |
| FOR_ITER | 40 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 760 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 300 | 78.9% |
| GET_ITER | 60 | 15.8% |
| FOR_ITER | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 380 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 720 | 94.7% |
| LOAD_ATTR | 40 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 50.0% |
| CALL_PY_EXACT_ARGS | 360 | 47.4% |
| CALL | 20 | 2.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 66.7% |
| LOAD_ATTR | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### LOAD_ATTR_SLOT

<details>
<summary> Successors and predecessors for LOAD_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 16,000,280 | 99.7% |
| LOAD_FAST | 54,100 | 0.3% |
| LOAD_ATTR | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,033,040 | 99.9% |
| COMPARE_OP_FLOAT | 13,600 | 0.1% |
| JUMP_FORWARD | 6,880 | 0.0% |
| STORE_FAST | 1,140 | 0.0% |
| COMPARE_OP | 60 | 0.0% |


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
| STORE_FAST | 8,000,680 | 50.0% |
| RESUME_CHECK | 8,000,000 | 50.0% |
| LOAD_GLOBAL | 140 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,000,400 | 100.0% |
| LOAD_FAST_LOAD_FAST | 380 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 8,000,040 | 100.0% |
| CALL_PY_EXACT_ARGS | 820 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,000,000 | 100.0% |
| LOAD_FAST | 820 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,025,740 | 50.0% |
| SWAP | 23,999,880 | 50.0% |
| STORE_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,025,900 | 33.4% |
| RETURN_CONST | 15,999,960 | 33.3% |
| LOAD_FAST_LOAD_FAST | 7,999,980 | 16.7% |
| STORE_FAST | 7,999,980 | 16.7% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 7,999,960 | 100.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,999,660 | 100.0% |
| JUMP_BACKWARD | 320 | 0.0% |


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
|     deferred | 40,000,220 | 83.3% |
|          hit | 8,001,940 | 16.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 1.3% |
| Failure | 10,720 | 98.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide float | 6,420 | 59.9% |
| multiply different types | 2,160 | 20.1% |
| true divide different types | 2,140 | 20.0% |


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
|     deferred | 8,000,460 | 33.3% |
|          hit | 16,001,220 | 66.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 5.9% |
| Failure | 2,220 | 94.1% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| no dict | 2,140 | 96.4% |
| cfunc noargs | 60 | 2.7% |
| other | 20 | 0.9% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 80 | 0.6% |
|          hit | 13,720 | 98.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 4.8% |
|          hit | 1,140 | 90.5% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 420 | 0.0% |
|          hit | 16,055,600 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 420 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 160 | 0.0% |
|          hit | 16,000,960 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> specialization stats for POP_JUMP_IF_FALSE family </summary>


</details>

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 48,025,820 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.0% |
|          hit | 7,999,980 | 100.0% |

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
| Basic | 208,148,980 | 55.3% |
| Not specialized | 48,029,700 | 12.8% |
| Specialized hits | 120,089,980 | 31.9% |
| Specialized misses | 11,380 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 40,000,220 | 83.3% |
| CALL | 8,000,460 | 16.7% |
| LOAD_ATTR | 420 | 0.0% |
| STORE_ATTR | 200 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |
| COMPARE_OP | 80 | 0.0% |
| FOR_ITER | 60 | 0.0% |
| BINARY_SUBSCR | 20 | 0.0% |
| STORE_SUBSCR | 20 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 11,380 | 50.0% |
| RESUME_CHECK | 11,380 | 50.0% |
| CACHE | 0 | 0.0% |
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
| Calls to PyEval_EvalDefault | 8,000,080 | 100.0% |
| Calls to Python functions inlined | 960 | 0.0% |
| Calls via PyEval_EvalFrame (total) | 8,000,080 | 100.0% |
| Calls via PyEval_EvalFrame (vector) | 8,000,080 | 100.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 8,000,080 | 100.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 80 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 15,999,940 | 200.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 96,005,960 | 70.6% |
| Frees to freelist | 96,008,700 |  |
| Allocations | 39,997,400 | 29.4% |
| Allocations to 512 bytes | 39,997,200 | 29.4% |
| Allocations to 4 kbytes | 40 | 0.0% |
| Allocations over 4 kbytes | 160 | 0.0% |
| Frees | 40,004,110 |  |
| New values | 0 |  |
| Interpreter increfs | 607,908,540 | 95.0% |
| Interpreter decrefs | 687,889,480 | 88.7% |
| Increfs | 31,981,980 | 5.0% |
| Decrefs | 88,009,870 | 11.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 1,080 |  |
| Method cache misses | 120 |  |
| Method cache collisions | 119 |  |
| Method cache dunder hits | 7,999,980 |  |
| Method cache dunder misses | 20 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 10,360 | 1,920 | 70,094,920 |
| 1 | 940 | 0 | 76,522,000 |
| 2 | 80 | 0 | 67,306,120 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 60 |  |
| Traces created | 60 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 16,011,740 |  |
| Uops executed | 1,303,556,740 | 81.41 |

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
| <= 32 | 20 | 33.3% |
| <= 64 | 0 | 0.0% |
| <= 128 | 40 | 66.7% |


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
| <= 16 | 20 | 33.3% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 40 | 66.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 160 | 0.0% |
| <= 16 | 7,999,600 | 50.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 60 | 0.0% |
| <= 128 | 7,999,600 | 50.0% |
| <= 256 | 240 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 240 | 0.0% |
| <= 4,096 | 0 | 0.0% |
| <= 8,192 | 0 | 0.0% |
| <= 16,384 | 0 | 0.0% |
| <= 32,768 | 11,760 | 0.1% |
| <= 65,536 | 0 | 0.0% |
| <= 131,072 | 0 | 0.0% |
| <= 262,144 | 0 | 0.0% |
| <= 524,288 | 0 | 0.0% |
| <= 1,048,576 | 0 | 0.0% |
| <= 2,097,152 | 0 | 0.0% |
| <= 4,194,304 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 311,896,080 | 23.9% | 23.9% |  |
| LOAD_FAST | 223,900,620 | 17.2% | 41.1% |  |
| _GUARD_TYPE_VERSION | 143,917,080 | 11.0% | 52.1% |  |
| _LOAD_ATTR_SLOT | 103,944,220 | 8.0% | 60.1% |  |
| STORE_FAST | 63,984,340 | 4.9% | 65.0% |  |
| _GUARD_BOTH_FLOAT | 39,998,000 | 3.1% | 68.1% |  |
| _POP_JUMP_IF_TRUE | 23,998,960 | 1.8% | 69.9% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 23,998,800 | 1.8% | 71.8% |  |
| COMPARE_OP_FLOAT | 23,986,040 | 1.8% | 73.6% |  |
| _POP_JUMP_IF_FALSE | 23,986,040 | 1.8% | 75.5% |  |
| _STORE_ATTR_SLOT | 23,973,740 | 1.8% | 77.3% |  |
| _EXIT_TRACE | 16,011,740 | 1.2% | 78.5% |  |
| _ITER_CHECK_LIST | 15,999,280 | 1.2% | 79.8% |  |
| _IS_ITER_EXHAUSTED_LIST | 15,999,280 | 1.2% | 81.0% |  |
| _BINARY_OP_ADD_FLOAT | 15,999,200 | 1.2% | 82.2% |  |
| _GUARD_GLOBALS_VERSION | 15,999,200 | 1.2% | 83.4% |  |
| _LOAD_GLOBAL_MODULE | 15,999,200 | 1.2% | 84.7% |  |
| RESUME_CHECK | 15,999,120 | 1.2% | 85.9% |  |
| _ITER_NEXT_LIST | 15,999,120 | 1.2% | 87.1% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 15,999,120 | 1.2% | 88.3% |  |
| _CHECK_PEP_523 | 15,999,120 | 1.2% | 89.6% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 15,999,120 | 1.2% | 90.8% |  |
| _CHECK_STACK_SPACE | 15,999,120 | 1.2% | 92.0% |  |
| _INIT_CALL_PY_EXACT_ARGS | 15,999,120 | 1.2% | 93.3% |  |
| _PUSH_FRAME | 15,999,120 | 1.2% | 94.5% |  |
| _SAVE_RETURN_OFFSET | 15,999,120 | 1.2% | 95.7% |  |
| _ITER_CHECK_RANGE | 7,999,680 | 0.6% | 96.3% |  |
| _IS_ITER_EXHAUSTED_RANGE | 7,999,680 | 0.6% | 96.9% |  |
| COPY | 7,999,600 | 0.6% | 97.5% |  |
| CALL_BUILTIN_O | 7,999,600 | 0.6% | 98.2% |  |
| _ITER_NEXT_RANGE | 7,999,600 | 0.6% | 98.8% |  |
| _POP_FRAME | 7,987,220 | 0.6% | 99.4% |  |
| _JUMP_TO_TOP | 7,987,220 | 0.6% | 100.0% |  |
| POP_TOP | 240 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---:|
| BINARY_OP | 20 |
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
Stats gathered on: 2023-11-03
