
# Pystats results

- benchmark: float
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 40,097,980 | 16.7% | 16.7% |  |
| STORE_ATTR_SLOT | 24,026,900 | 10.0% | 26.7% |  |
| ENTER_EXECUTOR | 16,011,780 | 6.7% | 33.4% |  |
| BINARY_OP | 16,005,980 | 6.7% | 40.0% |  |
| LOAD_FAST_LOAD_FAST | 16,001,140 | 6.7% | 46.7% |  |
| LOAD_GLOBAL_MODULE | 16,000,860 | 6.7% | 53.3% |  |
| LOAD_CONST | 16,000,400 | 6.7% | 60.0% |  |
| CALL_BUILTIN_O | 16,000,320 | 6.7% | 66.6% |  |
| RETURN_CONST | 16,000,000 | 6.7% | 73.3% |  |
| STORE_FAST | 8,015,820 | 3.3% | 76.6% |  |
| CALL | 8,002,820 | 3.3% | 80.0% |  |
| COPY | 8,001,140 | 3.3% | 83.3% |  |
| BINARY_OP_MULTIPLY_FLOAT | 8,001,060 | 3.3% | 86.6% |  |
| RESUME_CHECK | 8,000,880 | 3.3% | 90.0% | 0.1% |
| POP_TOP | 8,000,160 | 3.3% | 93.3% |  |
| INTERPRETER_EXIT | 8,000,080 | 3.3% | 96.6% |  |
| STORE_SUBSCR_LIST_INT | 7,999,980 | 3.3% | 100.0% |  |
| LOAD_ATTR_SLOT | 55,220 | 0.0% | 100.0% |  |
| POP_JUMP_IF_FALSE | 13,740 | 0.0% | 100.0% |  |
| COMPARE_OP_FLOAT | 13,600 | 0.0% | 100.0% |  |
| RETURN_VALUE | 12,920 | 0.0% | 100.0% |  |
| JUMP_FORWARD | 6,880 | 0.0% | 100.0% |  |
| SWAP | 1,140 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 960 | 0.0% | 100.0% |  |
| LOAD_ATTR | 840 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 780 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 720 | 0.0% | 100.0% |  |
| FOR_ITER_LIST | 720 | 0.0% | 100.0% |  |
| LOAD_ATTR_METHOD_NO_DICT | 720 | 0.0% | 100.0% |  |
| PUSH_NULL | 400 | 0.0% | 100.0% |  |
| STORE_ATTR | 400 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 360 | 0.0% | 100.0% |  |
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
| LOAD_FAST STORE_ATTR_SLOT | 24,025,680 | 10.0% | 10.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 16,000,380 | 6.7% | 16.7% |
| BINARY_OP LOAD_FAST | 16,000,000 | 6.7% | 23.3% |
| LOAD_CONST BINARY_OP | 16,000,000 | 6.7% | 30.0% |
| LOAD_FAST CALL_BUILTIN_O | 15,999,920 | 6.7% | 36.6% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 8,000,980 | 3.3% | 40.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 8,000,640 | 3.3% | 43.3% |
| STORE_ATTR_SLOT RETURN_CONST | 8,000,340 | 3.3% | 46.6% |
| CACHE RESUME_CHECK | 8,000,040 | 3.3% | 50.0% |
| CALL LOAD_FAST_LOAD_FAST | 8,000,000 | 3.3% | 53.3% |
| COPY LOAD_FAST | 8,000,000 | 3.3% | 56.6% |
| RETURN_CONST INTERPRETER_EXIT | 8,000,000 | 3.3% | 59.9% |
| RETURN_CONST POP_TOP | 8,000,000 | 3.3% | 63.3% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 8,000,000 | 3.3% | 66.6% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 7,999,980 | 3.3% | 69.9% |
| CALL_BUILTIN_O COPY | 7,999,980 | 3.3% | 73.3% |
| CALL_BUILTIN_O LOAD_CONST | 7,999,980 | 3.3% | 76.6% |
| STORE_ATTR_SLOT LOAD_FAST_LOAD_FAST | 7,999,980 | 3.3% | 79.9% |
| STORE_ATTR_SLOT STORE_FAST | 7,999,980 | 3.3% | 83.2% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 7,999,960 | 3.3% | 86.6% |
| POP_TOP ENTER_EXECUTOR | 7,999,680 | 3.3% | 89.9% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 7,999,680 | 3.3% | 93.2% |
| ENTER_EXECUTOR CALL | 7,999,620 | 3.3% | 96.6% |
| ENTER_EXECUTOR RETURN_CONST | 7,999,620 | 3.3% | 99.9% |
| LOAD_FAST LOAD_ATTR_SLOT | 53,860 | 0.0% | 99.9% |
| LOAD_ATTR_SLOT LOAD_FAST | 33,700 | 0.0% | 99.9% |
| STORE_ATTR_SLOT LOAD_FAST | 26,600 | 0.0% | 99.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 13,740 | 0.0% | 99.9% |
| COMPARE_OP_FLOAT POP_JUMP_IF_FALSE | 13,600 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT COMPARE_OP_FLOAT | 13,540 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 12,840 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 12,680 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_FAST | 12,460 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 12,360 | 0.0% | 100.0% |
| JUMP_FORWARD LOAD_FAST | 6,880 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT JUMP_FORWARD | 6,840 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 4,520 | 0.0% | 100.0% |
| CALL CALL | 2,220 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 2,220 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 1,260 | 0.0% | 100.0% |
| BINARY_OP SWAP | 1,140 | 0.0% | 100.0% |
| LOAD_FAST COPY | 1,140 | 0.0% | 100.0% |
| LOAD_ATTR_SLOT STORE_FAST | 1,080 | 0.0% | 100.0% |
| COPY LOAD_ATTR_SLOT | 1,020 | 0.0% | 100.0% |
| SWAP STORE_ATTR_SLOT | 1,020 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 780 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST | 780 | 0.0% | 100.0% |
| FOR_ITER_LIST STORE_FAST | 720 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 680 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 680 | 0.0% | 100.0% |
| LOAD_FAST LOAD_ATTR | 640 | 0.0% | 100.0% |
| LOAD_FAST CALL | 580 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 560 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 380 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 360 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 360 | 0.0% | 100.0% |
| CALL_BUILTIN_O STORE_FAST | 360 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 360 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 360 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 360 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_SLOT | 340 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT CALL_BUILTIN_O | 340 | 0.0% | 100.0% |
| LOAD_ATTR_METHOD_NO_DICT CALL_PY_EXACT_ARGS | 340 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 320 | 0.0% | 100.0% |
| PUSH_NULL CALL | 320 | 0.0% | 100.0% |
| STORE_FAST JUMP_BACKWARD | 320 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 300 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 280 | 0.0% | 100.0% |
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
| ENTER_EXECUTOR | 7,999,680 | 100.0% |
| JUMP_BACKWARD | 320 | 0.0% |
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
| LOAD_FAST | 12,840 | 99.4% |
| RETURN_VALUE | 80 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 12,680 | 98.1% |
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
| LOAD_CONST | 16,000,000 | 100.0% |
| BINARY_OP | 4,520 | 0.0% |
| LOAD_FAST | 1,260 | 0.0% |
| LOAD_FAST_LOAD_FAST | 160 | 0.0% |
| BINARY_OP_MULTIPLY_FLOAT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,000,000 | 100.0% |
| BINARY_OP | 4,520 | 0.0% |
| SWAP | 1,140 | 0.0% |
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
| ENTER_EXECUTOR | 7,999,620 | 100.0% |
| CALL | 2,220 | 0.0% |
| LOAD_FAST | 580 | 0.0% |
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
| CALL_BUILTIN_O | 7,999,980 | 100.0% |
| LOAD_FAST | 1,140 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,000,000 | 100.0% |
| LOAD_ATTR_SLOT | 1,020 | 0.0% |
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
| POP_TOP | 7,999,680 | 50.0% |
| STORE_SUBSCR_LIST_INT | 7,999,680 | 50.0% |
| STORE_FAST | 12,360 | 0.1% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 7,999,620 | 50.0% |
| RETURN_CONST | 7,999,620 | 50.0% |
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
| POP_TOP | 320 | 33.3% |
| STORE_FAST | 320 | 33.3% |
| STORE_SUBSCR_LIST_INT | 300 | 31.2% |
| STORE_SUBSCR | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 560 | 58.3% |
| FOR_ITER_RANGE | 280 | 29.2% |
| ENTER_EXECUTOR | 60 | 6.2% |
| FOR_ITER | 60 | 6.2% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 6,840 | 99.4% |
| LOAD_ATTR | 40 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 6,880 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 16,000,380 | 39.9% |
| BINARY_OP | 16,000,000 | 39.9% |
| COPY | 8,000,000 | 20.0% |
| LOAD_ATTR_SLOT | 33,700 | 0.1% |
| STORE_ATTR_SLOT | 26,600 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 24,025,680 | 59.9% |
| CALL_BUILTIN_O | 15,999,920 | 39.9% |
| LOAD_ATTR_SLOT | 53,860 | 0.1% |
| RETURN_VALUE | 12,840 | 0.0% |
| BINARY_OP | 1,260 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 8,000,000 | 50.0% |
| STORE_ATTR_SLOT | 7,999,980 | 50.0% |
| BINARY_OP_ADD_FLOAT | 360 | 0.0% |
| BINARY_OP_MULTIPLY_FLOAT | 360 | 0.0% |
| LOAD_GLOBAL_MODULE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 8,000,980 | 50.0% |
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
| COMPARE_OP_FLOAT | 13,600 | 99.0% |
| COMPARE_OP | 80 | 0.6% |
| COMPARE_OP_INT | 60 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 13,740 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 8,000,340 | 50.0% |
| ENTER_EXECUTOR | 7,999,620 | 50.0% |
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
| RETURN_VALUE | 12,680 | 0.2% |
| LOAD_ATTR_SLOT | 1,080 | 0.0% |
| FOR_ITER_LIST | 720 | 0.0% |
| CALL_BUILTIN_O | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,000,640 | 99.8% |
| ENTER_EXECUTOR | 12,360 | 0.2% |
| LOAD_FAST | 2,220 | 0.0% |
| JUMP_BACKWARD | 320 | 0.0% |
| LOAD_GLOBAL | 160 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_SLOT | 1,020 | 89.5% |
| STORE_ATTR | 120 | 10.5% |


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
| BINARY_OP_MULTIPLY_FLOAT | 680 | 94.4% |
| BINARY_OP | 40 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 360 | 50.0% |
| CALL_BUILTIN_O | 340 | 47.2% |
| CALL | 20 | 2.8% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,000,980 | 100.0% |
| BINARY_OP | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 7,999,980 | 100.0% |
| BINARY_OP_ADD_FLOAT | 680 | 0.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
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
| BINARY_OP_ADD_FLOAT | 340 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 7,999,980 | 50.0% |
| LOAD_CONST | 7,999,980 | 50.0% |
| STORE_FAST | 360 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 48.7% |
| LOAD_ATTR_METHOD_NO_DICT | 340 | 43.6% |
| CALL | 60 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 780 | 100.0% |


</details>

### COMPARE_OP_FLOAT

<details>
<summary> Successors and predecessors for COMPARE_OP_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_SLOT | 13,540 | 99.6% |
| COMPARE_OP | 60 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 13,600 | 100.0% |


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
| JUMP_BACKWARD | 560 | 77.8% |
| GET_ITER | 120 | 16.7% |
| FOR_ITER | 40 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 720 | 100.0% |


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

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 680 | 94.4% |
| LOAD_ATTR | 40 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 360 | 50.0% |
| CALL_PY_EXACT_ARGS | 340 | 47.2% |
| CALL | 20 | 2.8% |


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
| LOAD_FAST | 53,860 | 97.5% |
| COPY | 1,020 | 1.8% |
| LOAD_ATTR | 340 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 33,700 | 61.0% |
| COMPARE_OP_FLOAT | 13,540 | 24.5% |
| JUMP_FORWARD | 6,840 | 12.4% |
| STORE_FAST | 1,080 | 2.0% |
| COMPARE_OP | 60 | 0.1% |


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
| STORE_FAST | 8,000,640 | 50.0% |
| RESUME_CHECK | 8,000,000 | 50.0% |
| LOAD_GLOBAL | 140 | 0.0% |
| RETURN_VALUE | 40 | 0.0% |
| ENTER_EXECUTOR | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,000,380 | 100.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| LOAD_ATTR_MODULE | 80 | 0.0% |
| LOAD_ATTR | 40 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 8,000,040 | 100.0% |
| CALL_PY_EXACT_ARGS | 780 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,000,000 | 100.0% |
| LOAD_FAST | 780 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### STORE_ATTR_SLOT

<details>
<summary> Successors and predecessors for STORE_ATTR_SLOT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 24,025,680 | 100.0% |
| SWAP | 1,020 | 0.0% |
| STORE_ATTR | 200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,000,340 | 33.3% |
| LOAD_FAST_LOAD_FAST | 7,999,980 | 33.3% |
| STORE_FAST | 7,999,980 | 33.3% |
| LOAD_FAST | 26,600 | 0.1% |


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
| ENTER_EXECUTOR | 7,999,680 | 100.0% |
| JUMP_BACKWARD | 300 | 0.0% |


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
|     deferred | 16,001,360 | 66.7% |
|          hit | 8,001,840 | 33.3% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 3.0% |
| Failure | 4,480 | 97.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 2,160 | 48.2% |
| true divide different types | 2,140 | 47.8% |
| true divide float | 180 | 4.0% |


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
|          hit | 16,001,160 | 66.7% |

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
|          hit | 13,660 | 98.8% |

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
|     deferred | 60 | 5.0% |
|          hit | 1,080 | 90.0% |

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
|     deferred | 420 | 0.7% |
|          hit | 56,060 | 98.5% |

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
|          hit | 16,000,920 | 100.0% |

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
|          hit | 24,026,900 | 100.0% |

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
| Basic | 136,151,640 | 56.7% |
| Not specialized | 24,024,540 | 10.0% |
| Specialized hits | 80,091,160 | 33.3% |
| Specialized misses | 11,380 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 16,001,360 | 66.7% |
| CALL | 8,000,460 | 33.3% |
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
| Calls to Python functions inlined | 920 | 0.0% |
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
| Frees | 40,004,106 |  |
| New values | 0 |  |
| Interpreter increfs | 607,908,580 | 95.0% |
| Interpreter decrefs | 687,889,520 | 88.7% |
| Increfs | 31,981,980 | 5.0% |
| Decrefs | 88,009,866 | 11.3% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 1,083 |  |
| Method cache misses | 117 |  |
| Method cache collisions | 102 |  |
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
| 2 | 80 | 0 | 67,312,360 |


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
| Trace too long | 20 | 33.3% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 16,011,780 |  |
| Uops executed | 1,543,548,600 | 96.40 |

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
| <= 16 | 7,999,620 | 50.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 60 | 0.0% |
| <= 128 | 7,999,620 | 50.0% |
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
| _SET_IP | 375,893,820 | 24.4% | 24.4% |  |
| LOAD_FAST | 255,899,660 | 16.6% | 40.9% |  |
| _GUARD_TYPE_VERSION | 183,915,540 | 11.9% | 52.8% |  |
| _LOAD_ATTR_SLOT | 119,943,720 | 7.8% | 60.6% |  |
| STORE_FAST | 63,984,500 | 4.1% | 64.8% |  |
| _STORE_ATTR_SLOT | 47,972,660 | 3.1% | 67.9% |  |
| _GUARD_BOTH_FLOAT | 39,998,100 | 2.6% | 70.5% |  |
| _POP_JUMP_IF_TRUE | 23,999,020 | 1.6% | 72.0% |  |
| COPY | 23,998,860 | 1.6% | 73.6% |  |
| SWAP | 23,998,860 | 1.6% | 75.1% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 23,998,860 | 1.6% | 76.7% |  |
| _BINARY_OP | 23,998,860 | 1.6% | 78.2% |  |
| COMPARE_OP_FLOAT | 23,986,100 | 1.6% | 79.8% |  |
| _POP_JUMP_IF_FALSE | 23,986,100 | 1.6% | 81.3% |  |
| _EXIT_TRACE | 16,011,780 | 1.0% | 82.4% |  |
| _ITER_CHECK_LIST | 15,999,320 | 1.0% | 83.4% |  |
| _IS_ITER_EXHAUSTED_LIST | 15,999,320 | 1.0% | 84.5% |  |
| _BINARY_OP_ADD_FLOAT | 15,999,240 | 1.0% | 85.5% |  |
| _GUARD_GLOBALS_VERSION | 15,999,240 | 1.0% | 86.5% |  |
| _LOAD_GLOBAL_MODULE | 15,999,240 | 1.0% | 87.6% |  |
| RESUME_CHECK | 15,999,160 | 1.0% | 88.6% |  |
| _ITER_NEXT_LIST | 15,999,160 | 1.0% | 89.6% |  |
| _LOAD_ATTR_METHOD_NO_DICT | 15,999,160 | 1.0% | 90.7% |  |
| _CHECK_PEP_523 | 15,999,160 | 1.0% | 91.7% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 15,999,160 | 1.0% | 92.7% |  |
| _CHECK_STACK_SPACE | 15,999,160 | 1.0% | 93.8% |  |
| _INIT_CALL_PY_EXACT_ARGS | 15,999,160 | 1.0% | 94.8% |  |
| _PUSH_FRAME | 15,999,160 | 1.0% | 95.9% |  |
| _SAVE_RETURN_OFFSET | 15,999,160 | 1.0% | 96.9% |  |
| _ITER_CHECK_RANGE | 7,999,700 | 0.5% | 97.4% |  |
| _IS_ITER_EXHAUSTED_RANGE | 7,999,700 | 0.5% | 97.9% |  |
| CALL_BUILTIN_O | 7,999,620 | 0.5% | 98.4% |  |
| _ITER_NEXT_RANGE | 7,999,620 | 0.5% | 99.0% |  |
| _POP_FRAME | 7,987,240 | 0.5% | 99.5% |  |
| _JUMP_TO_TOP | 7,987,240 | 0.5% | 100.0% |  |
| POP_TOP | 240 | 0.0% | 100.0% |  |


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
Stats gathered on: 2023-11-08
