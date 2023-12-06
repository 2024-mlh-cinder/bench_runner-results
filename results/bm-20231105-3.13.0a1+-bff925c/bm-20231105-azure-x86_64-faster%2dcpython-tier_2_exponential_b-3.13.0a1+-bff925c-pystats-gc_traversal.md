
# Pystats results

- benchmark: gc_traversal
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| ENTER_EXECUTOR | 161,780 | 41.1% | 41.1% |  |
| LOAD_FAST | 92,060 | 23.4% | 64.4% |  |
| STORE_FAST | 89,560 | 22.7% | 87.2% |  |
| PUSH_NULL | 6,120 | 1.6% | 88.7% |  |
| LOAD_GLOBAL_MODULE | 5,920 | 1.5% | 90.2% |  |
| LOAD_ATTR_MODULE | 5,860 | 1.5% | 91.7% |  |
| CALL | 5,700 | 1.4% | 93.1% |  |
| LOAD_CONST | 3,020 | 0.8% | 93.9% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,900 | 0.7% | 94.6% |  |
| POP_JUMP_IF_FALSE | 2,560 | 0.6% | 95.3% |  |
| POP_JUMP_IF_NOT_NONE | 2,560 | 0.6% | 95.9% |  |
| BINARY_OP_ADD_FLOAT | 2,540 | 0.6% | 96.6% | 2.4% |
| BINARY_OP_SUBTRACT_FLOAT | 2,540 | 0.6% | 97.2% |  |
| COMPARE_OP_INT | 2,540 | 0.6% | 97.9% |  |
| FOR_ITER_RANGE | 1,380 | 0.4% | 98.2% |  |
| JUMP_BACKWARD | 960 | 0.2% | 98.5% |  |
| GET_ITER | 540 | 0.1% | 98.6% |  |
| BUILD_LIST | 540 | 0.1% | 98.7% |  |
| BINARY_OP | 520 | 0.1% | 98.9% |  |
| LOAD_FAST_LOAD_FAST | 500 | 0.1% | 99.0% |  |
| CALL_BUILTIN_CLASS | 480 | 0.1% | 99.1% |  |
| LOAD_GLOBAL_BUILTIN | 480 | 0.1% | 99.2% |  |
| STORE_SUBSCR_LIST_INT | 480 | 0.1% | 99.4% |  |
| POP_TOP | 460 | 0.1% | 99.5% |  |
| LOAD_GLOBAL | 360 | 0.1% | 99.6% |  |
| RETURN_VALUE | 240 | 0.1% | 99.6% |  |
| LOAD_DEREF | 240 | 0.1% | 99.7% |  |
| LOAD_ATTR | 200 | 0.1% | 99.8% |  |
| RESUME_CHECK | 180 | 0.0% | 99.8% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 99.8% |  |
| FOR_ITER | 120 | 0.0% | 99.9% |  |
| NOP | 80 | 0.0% | 99.9% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 99.9% |  |
| COPY_FREE_VARS | 80 | 0.0% | 99.9% |  |
| LIST_EXTEND | 80 | 0.0% | 99.9% |  |
| RESUME | 60 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 40 | 0.0% | 100.0% |  |
| COMPARE_OP | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST STORE_FAST | 80,000 | 20.3% | 20.3% |
| ENTER_EXECUTOR LOAD_FAST | 79,980 | 20.3% | 40.6% |
| STORE_FAST ENTER_EXECUTOR | 79,680 | 20.2% | 60.8% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 79,620 | 20.2% | 81.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 5,860 | 1.5% | 82.5% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 5,760 | 1.5% | 84.0% |
| STORE_FAST LOAD_FAST | 5,120 | 1.3% | 85.3% |
| PUSH_NULL CALL | 3,100 | 0.8% | 86.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,900 | 0.7% | 86.8% |
| PUSH_NULL CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,860 | 0.7% | 87.5% |
| CALL STORE_FAST | 2,580 | 0.7% | 88.2% |
| CALL LOAD_FAST | 2,560 | 0.6% | 88.8% |
| LOAD_FAST LOAD_CONST | 2,560 | 0.6% | 89.5% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,560 | 0.6% | 90.1% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 2,560 | 0.6% | 90.8% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 2,540 | 0.6% | 91.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 2,540 | 0.6% | 92.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,540 | 0.6% | 92.7% |
| LOAD_CONST COMPARE_OP_INT | 2,520 | 0.6% | 93.4% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 2,520 | 0.6% | 94.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,520 | 0.6% | 94.6% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_ADD_FLOAT | 2,520 | 0.6% | 95.3% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 2,240 | 0.6% | 95.8% |
| ENTER_EXECUTOR CALL | 2,180 | 0.6% | 96.4% |
| FOR_ITER_RANGE STORE_FAST | 1,220 | 0.3% | 96.7% |
| JUMP_BACKWARD FOR_ITER_RANGE | 860 | 0.2% | 96.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 500 | 0.1% | 97.1% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 500 | 0.1% | 97.2% |
| CALL_BUILTIN_CLASS GET_ITER | 480 | 0.1% | 97.3% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 480 | 0.1% | 97.4% |
| GET_ITER FOR_ITER_RANGE | 460 | 0.1% | 97.5% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 460 | 0.1% | 97.7% |
| LOAD_FAST BINARY_OP | 420 | 0.1% | 97.8% |
| LOAD_FAST CALL_BUILTIN_CLASS | 420 | 0.1% | 97.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 420 | 0.1% | 98.0% |
| BINARY_OP STORE_FAST | 400 | 0.1% | 98.1% |
| BUILD_LIST LOAD_FAST | 380 | 0.1% | 98.2% |
| LOAD_CONST BUILD_LIST | 380 | 0.1% | 98.3% |
| STORE_FAST LOAD_CONST | 380 | 0.1% | 98.4% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 360 | 0.1% | 98.5% |
| POP_TOP LOAD_GLOBAL_MODULE | 340 | 0.1% | 98.5% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 320 | 0.1% | 98.6% |
| STORE_FAST JUMP_BACKWARD | 320 | 0.1% | 98.7% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 300 | 0.1% | 98.8% |
| CALL CALL | 260 | 0.1% | 98.8% |
| STORE_FAST LOAD_GLOBAL | 240 | 0.1% | 98.9% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 180 | 0.0% | 99.0% |
| PUSH_NULL LOAD_FAST | 160 | 0.0% | 99.0% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 99.0% |
| LOAD_FAST RETURN_VALUE | 160 | 0.0% | 99.1% |
| LOAD_FAST CALL | 160 | 0.0% | 99.1% |
| FOR_ITER_RANGE LOAD_FAST | 160 | 0.0% | 99.2% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 99.2% |
| CALL POP_TOP | 100 | 0.0% | 99.2% |
| LOAD_ATTR PUSH_NULL | 100 | 0.0% | 99.2% |
| LOAD_ATTR LOAD_ATTR_MODULE | 100 | 0.0% | 99.3% |
| LOAD_GLOBAL LOAD_ATTR | 100 | 0.0% | 99.3% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 100 | 0.0% | 99.3% |
| GET_ITER FOR_ITER | 80 | 0.0% | 99.3% |
| NOP LOAD_DEREF | 80 | 0.0% | 99.4% |
| POP_TOP NOP | 80 | 0.0% | 99.4% |
| RETURN_VALUE RETURN_VALUE | 80 | 0.0% | 99.4% |
| RETURN_VALUE STORE_FAST | 80 | 0.0% | 99.4% |
| BINARY_OP BINARY_OP | 80 | 0.0% | 99.4% |
| BUILD_LIST LOAD_DEREF | 80 | 0.0% | 99.5% |
| BUILD_LIST STORE_FAST | 80 | 0.0% | 99.5% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 80 | 0.0% | 99.5% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 80 | 0.0% | 99.5% |
| LIST_EXTEND CALL_INTRINSIC_1 | 80 | 0.0% | 99.5% |
| LOAD_CONST STORE_FAST | 80 | 0.0% | 99.6% |
| LOAD_DEREF LIST_EXTEND | 80 | 0.0% | 99.6% |
| LOAD_FAST BUILD_LIST | 80 | 0.0% | 99.6% |
| LOAD_FAST CALL_FUNCTION_EX | 80 | 0.0% | 99.6% |
| LOAD_GLOBAL LOAD_FAST | 80 | 0.0% | 99.6% |
| CALL GET_ITER | 60 | 0.0% | 99.7% |
| CALL CALL_BUILTIN_CLASS | 60 | 0.0% | 99.7% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 99.7% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 99.7% |
| FOR_ITER FOR_ITER_RANGE | 60 | 0.0% | 99.7% |
| JUMP_BACKWARD ENTER_EXECUTOR | 60 | 0.0% | 99.7% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 99.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 60 | 0.0% | 99.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.0% | 99.8% |
| RESUME_CHECK BUILD_LIST | 60 | 0.0% | 99.8% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 99.8% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 99.8% |
| POP_TOP LOAD_GLOBAL | 40 | 0.0% | 99.8% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 99.8% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 40 | 0.0% | 99.9% |
| CALL CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.0% | 99.9% |
| FOR_ITER STORE_FAST | 40 | 0.0% | 99.9% |
| JUMP_BACKWARD FOR_ITER | 40 | 0.0% | 99.9% |
| LOAD_CONST COMPARE_OP | 40 | 0.0% | 99.9% |
| LOAD_FAST STORE_SUBSCR | 40 | 0.0% | 99.9% |
| LOAD_FAST LOAD_GLOBAL | 40 | 0.0% | 99.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 40 | 0.0% | 99.9% |
| STORE_SUBSCR JUMP_BACKWARD | 20 | 0.0% | 99.9% |
| STORE_SUBSCR STORE_SUBSCR_LIST_INT | 20 | 0.0% | 99.9% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 20 | 0.0% | 99.9% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% | 99.9% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 480 | 88.9% |
| CALL | 60 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 460 | 85.2% |
| FOR_ITER | 80 | 14.8% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 360 | 78.3% |
| CALL | 100 | 21.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 340 | 73.9% |
| NOP | 80 | 17.4% |
| LOAD_GLOBAL | 40 | 8.7% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,860 | 95.8% |
| LOAD_DEREF | 160 | 2.6% |
| LOAD_ATTR | 100 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,100 | 50.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,860 | 46.7% |
| LOAD_FAST | 160 | 2.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 66.7% |
| RETURN_VALUE | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 80 | 33.3% |
| STORE_FAST | 80 | 33.3% |
| LOAD_GLOBAL | 40 | 16.7% |
| LOAD_GLOBAL_MODULE | 40 | 16.7% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 100.0% |

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
| LOAD_FAST | 420 | 80.8% |
| BINARY_OP | 80 | 15.4% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 400 | 76.9% |
| BINARY_OP | 80 | 15.4% |
| BINARY_OP_ADD_FLOAT | 20 | 3.8% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 3.8% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 380 | 70.4% |
| LOAD_FAST | 80 | 14.8% |
| RESUME_CHECK | 60 | 11.1% |
| RESUME | 20 | 3.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 380 | 70.4% |
| LOAD_DEREF | 80 | 14.8% |
| STORE_FAST | 80 | 14.8% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,100 | 54.4% |
| ENTER_EXECUTOR | 2,180 | 38.2% |
| CALL | 260 | 4.6% |
| LOAD_FAST | 160 | 2.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,580 | 45.3% |
| LOAD_FAST | 2,560 | 44.9% |
| CALL | 260 | 4.6% |
| POP_TOP | 100 | 1.8% |
| GET_ITER | 60 | 1.1% |


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
| LOAD_CONST | 40 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 20 | 50.0% |
| COMPARE_OP_INT | 20 | 50.0% |


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
| STORE_FAST | 79,680 | 49.3% |
| ENTER_EXECUTOR | 79,620 | 49.2% |
| POP_JUMP_IF_FALSE | 2,240 | 1.4% |
| STORE_SUBSCR_LIST_INT | 180 | 0.1% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,980 | 49.4% |
| ENTER_EXECUTOR | 79,620 | 49.2% |
| CALL | 2,180 | 1.3% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80 | 66.7% |
| JUMP_BACKWARD | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 60 | 50.0% |
| STORE_FAST | 40 | 33.3% |
| LOAD_FAST | 20 | 16.7% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 320 | 33.3% |
| STORE_FAST | 320 | 33.3% |
| STORE_SUBSCR_LIST_INT | 300 | 31.2% |
| STORE_SUBSCR | 20 | 2.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 860 | 89.6% |
| ENTER_EXECUTOR | 60 | 6.2% |
| FOR_ITER | 40 | 4.2% |


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
| LOAD_GLOBAL | 100 | 50.0% |
| LOAD_GLOBAL_MODULE | 100 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 100 | 50.0% |
| LOAD_ATTR_MODULE | 100 | 50.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,560 | 84.8% |
| STORE_FAST | 380 | 12.6% |
| RESUME_CHECK | 60 | 2.0% |
| RESUME | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,520 | 83.4% |
| BUILD_LIST | 380 | 12.6% |
| STORE_FAST | 80 | 2.6% |
| COMPARE_OP | 40 | 1.3% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 33.3% |
| BUILD_LIST | 80 | 33.3% |
| RESUME_CHECK | 60 | 25.0% |
| RESUME | 20 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 66.7% |
| LIST_EXTEND | 80 | 33.3% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 79,980 | 86.9% |
| STORE_FAST | 5,120 | 5.6% |
| CALL | 2,560 | 2.8% |
| POP_JUMP_IF_NOT_NONE | 2,560 | 2.8% |
| LOAD_FAST_LOAD_FAST | 500 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80,000 | 86.9% |
| LOAD_CONST | 2,560 | 2.8% |
| POP_JUMP_IF_NOT_NONE | 2,560 | 2.8% |
| BINARY_OP_SUBTRACT_FLOAT | 2,520 | 2.7% |
| LOAD_GLOBAL_MODULE | 2,520 | 2.7% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 500 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 500 | 100.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 66.7% |
| POP_TOP | 40 | 11.1% |
| RETURN_VALUE | 40 | 11.1% |
| LOAD_FAST | 40 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 33.3% |
| LOAD_ATTR | 100 | 27.8% |
| LOAD_FAST | 80 | 22.2% |
| LOAD_GLOBAL_BUILTIN | 60 | 16.7% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,540 | 99.2% |
| COMPARE_OP | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,240 | 87.5% |
| JUMP_BACKWARD | 320 | 12.5% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,560 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,560 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,000 | 89.3% |
| CALL | 2,580 | 2.9% |
| BINARY_OP_ADD_FLOAT | 2,540 | 2.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,540 | 2.8% |
| FOR_ITER_RANGE | 1,220 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 79,680 | 89.0% |
| LOAD_FAST | 5,120 | 5.7% |
| LOAD_GLOBAL_MODULE | 2,900 | 3.2% |
| LOAD_FAST_LOAD_FAST | 500 | 0.6% |
| LOAD_GLOBAL_BUILTIN | 420 | 0.5% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 20 | 33.3% |
| CALL_FUNCTION_EX | 20 | 33.3% |
| COPY_FREE_VARS | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 20 | 33.3% |
| LOAD_CONST | 20 | 33.3% |
| LOAD_DEREF | 20 | 33.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 2,520 | 99.2% |
| BINARY_OP | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,540 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,520 | 99.2% |
| BINARY_OP | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 2,520 | 99.2% |
| BINARY_OP | 20 | 0.8% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 420 | 87.5% |
| CALL | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 480 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,860 | 98.6% |
| CALL | 40 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,540 | 87.6% |
| POP_TOP | 360 | 12.4% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 2,520 | 99.2% |
| COMPARE_OP | 20 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,540 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 860 | 62.3% |
| GET_ITER | 460 | 33.3% |
| FOR_ITER | 60 | 4.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,220 | 88.4% |
| LOAD_FAST | 160 | 11.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 5,760 | 98.3% |
| LOAD_ATTR | 100 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 5,860 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 420 | 87.5% |
| LOAD_GLOBAL | 60 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 480 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,900 | 49.0% |
| LOAD_FAST | 2,520 | 42.6% |
| POP_TOP | 340 | 5.7% |
| LOAD_GLOBAL | 120 | 2.0% |
| RETURN_VALUE | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,760 | 97.3% |
| LOAD_ATTR | 100 | 1.7% |
| LOAD_FAST | 60 | 1.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_FUNCTION_EX | 60 | 33.3% |
| COPY_FREE_VARS | 60 | 33.3% |
| CALL_PY_EXACT_ARGS | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 60 | 33.3% |
| LOAD_CONST | 60 | 33.3% |
| LOAD_DEREF | 60 | 33.3% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 460 | 95.8% |
| STORE_SUBSCR | 20 | 4.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 300 | 62.5% |
| ENTER_EXECUTOR | 180 | 37.5% |


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
|     deferred | 420 | 7.5% |
|          hit | 5,020 | 89.6% |
|         miss | 60 | 1.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 40.0% |
| Failure | 60 | 60.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 60 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,320 | 58.2% |
|          hit | 3,440 | 37.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 31.6% |
| Failure | 260 | 68.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 260 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 0.8% |
|          hit | 2,540 | 98.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 4.0% |
|          hit | 1,380 | 92.0% |

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
|     deferred | 100 | 1.7% |
|          hit | 5,860 | 96.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 180 | 2.7% |
|          hit | 6,400 | 94.7% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
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

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 3.8% |
|          hit | 480 | 92.3% |

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
| Basic | 356,560 | 90.5% |
| Not specialized | 12,100 | 3.1% |
| Specialized hits | 25,300 | 6.4% |
| Specialized misses | 60 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 5,320 | 86.9% |
| BINARY_OP | 420 | 6.9% |
| LOAD_GLOBAL | 180 | 2.9% |
| LOAD_ATTR | 100 | 1.6% |
| FOR_ITER | 60 | 1.0% |
| STORE_SUBSCR | 20 | 0.3% |
| COMPARE_OP | 20 | 0.3% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 60 | 100.0% |
| GET_ITER | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| BUILD_LIST | 0 | 0.0% |
| CALL_FUNCTION_EX | 0 | 0.0% |
| CALL_INTRINSIC_1 | 0 | 0.0% |
| COPY_FREE_VARS | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 240 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 66.7% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 60 | 25.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 85,840 | 0.4% |
| Frees to freelist | 92,420 |  |
| Allocations | 22,581,640 | 99.6% |
| Allocations to 512 bytes | 22,506,720 | 99.3% |
| Allocations to 4 kbytes | 35,880 | 0.2% |
| Allocations over 4 kbytes | 39,040 | 0.2% |
| Frees | 22,588,840 |  |
| New values | 0 |  |
| Interpreter increfs | 102,359,760 | 99.9% |
| Interpreter decrefs | 84,837,260 | 67.9% |
| Increfs | 120,120 | 0.1% |
| Decrefs | 40,155,720 | 32.1% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 75 |  |
| Method cache misses | 25 |  |
| Method cache collisions | 25 |  |
| Method cache dunder hits | 0 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 100 | 1,920 | 54,050,480 |
| 1 | 0 | 0 | 0 |
| 2 | 5,120 | 0 | 5,706,473,760 |


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
| Inner loop found | 20 | 33.3% |
| Recursive call | 0 | 0.0% |
| Traces executed | 161,780 |  |
| Uops executed | 521,839,500 | 3,225.61 |

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
| <= 32 | 40 | 66.7% |
| <= 64 | 20 | 33.3% |


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
| <= 32 | 20 | 33.3% |
| <= 64 | 20 | 33.3% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 220 | 0.1% |
| <= 16 | 0 | 0.0% |
| <= 32 | 2,240 | 1.4% |
| <= 64 | 79,800 | 49.3% |
| <= 128 | 400 | 0.2% |
| <= 256 | 800 | 0.5% |
| <= 512 | 1,520 | 0.9% |
| <= 1,024 | 3,200 | 2.0% |
| <= 2,048 | 6,320 | 3.9% |
| <= 4,096 | 12,560 | 7.8% |
| <= 8,192 | 25,200 | 15.6% |
| <= 16,384 | 29,520 | 18.2% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 120,531,440 | 23.1% | 23.1% |  |
| LOAD_FAST | 120,037,740 | 23.0% | 46.1% |  |
| _ITER_CHECK_RANGE | 40,121,280 | 7.7% | 53.8% |  |
| _IS_ITER_EXHAUSTED_RANGE | 40,121,280 | 7.7% | 61.5% |  |
| _POP_JUMP_IF_TRUE | 40,121,280 | 7.7% | 69.2% |  |
| STORE_FAST | 40,120,920 | 7.7% | 76.9% |  |
| _ITER_NEXT_RANGE | 40,041,300 | 7.7% | 84.5% |  |
| STORE_SUBSCR_LIST_INT | 39,959,500 | 7.7% | 92.2% |  |
| _JUMP_TO_TOP | 39,879,880 | 7.6% | 99.8% |  |
| _EXIT_TRACE | 161,780 | 0.0% | 99.9% |  |
| _GUARD_GLOBALS_VERSION | 83,980 | 0.0% | 99.9% |  |
| POP_TOP | 82,160 | 0.0% | 99.9% |  |
| GET_ITER | 79,620 | 0.0% | 99.9% |  |
| BUILD_LIST | 79,620 | 0.0% | 99.9% |  |
| LOAD_CONST | 79,620 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 79,620 | 0.0% | 100.0% |  |
| _GUARD_BUILTINS_VERSION | 79,620 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_BUILTINS | 79,620 | 0.0% | 100.0% |  |
| _BINARY_OP | 79,620 | 0.0% | 100.0% |  |
| PUSH_NULL | 4,360 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_MODULE | 4,360 | 0.0% | 100.0% |  |
| _CHECK_ATTR_MODULE | 4,360 | 0.0% | 100.0% |  |
| _LOAD_ATTR_MODULE | 4,360 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,180 | 0.0% | 100.0% |  |


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
