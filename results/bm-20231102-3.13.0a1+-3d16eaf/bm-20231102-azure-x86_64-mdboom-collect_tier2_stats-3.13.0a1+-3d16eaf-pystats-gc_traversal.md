
# Pystats results

- benchmark: gc_traversal
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3d16eaf
- commit date: 2023-11-02T14:21:11-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 251,340 | 19.8% | 19.8% |  |
| STORE_FAST | 248,860 | 19.6% | 39.4% |  |
| ENTER_EXECUTOR | 161,740 | 12.7% | 52.1% |  |
| FOR_ITER_RANGE | 81,060 | 6.4% | 58.5% |  |
| BINARY_OP | 80,280 | 6.3% | 64.8% |  |
| GET_ITER | 80,160 | 6.3% | 71.1% |  |
| LOAD_FAST_LOAD_FAST | 80,140 | 6.3% | 77.4% |  |
| STORE_SUBSCR_LIST_INT | 80,120 | 6.3% | 83.7% |  |
| CALL_BUILTIN_CLASS | 80,100 | 6.3% | 90.0% |  |
| LOAD_GLOBAL_BUILTIN | 80,100 | 6.3% | 96.3% |  |
| PUSH_NULL | 6,160 | 0.5% | 96.8% |  |
| LOAD_GLOBAL_MODULE | 5,960 | 0.5% | 97.3% |  |
| LOAD_ATTR_MODULE | 5,900 | 0.5% | 97.8% |  |
| CALL | 5,700 | 0.4% | 98.2% |  |
| LOAD_CONST | 3,040 | 0.2% | 98.4% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,920 | 0.2% | 98.7% |  |
| POP_JUMP_IF_FALSE | 2,560 | 0.2% | 98.9% |  |
| POP_JUMP_IF_NOT_NONE | 2,560 | 0.2% | 99.1% |  |
| BINARY_OP_ADD_FLOAT | 2,540 | 0.2% | 99.3% | 2.4% |
| BINARY_OP_SUBTRACT_FLOAT | 2,540 | 0.2% | 99.5% |  |
| COMPARE_OP_INT | 2,540 | 0.2% | 99.7% |  |
| JUMP_BACKWARD | 1,020 | 0.1% | 99.8% |  |
| BUILD_LIST | 560 | 0.0% | 99.8% |  |
| POP_TOP | 480 | 0.0% | 99.8% |  |
| LOAD_GLOBAL | 360 | 0.0% | 99.9% |  |
| RETURN_VALUE | 240 | 0.0% | 99.9% |  |
| LOAD_DEREF | 240 | 0.0% | 99.9% |  |
| LOAD_ATTR | 200 | 0.0% | 99.9% |  |
| RESUME_CHECK | 180 | 0.0% | 99.9% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 99.9% |  |
| FOR_ITER | 120 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
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
| FOR_ITER_RANGE STORE_FAST | 80,900 | 6.4% | 6.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 80,140 | 6.3% | 12.7% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 80,140 | 6.3% | 19.0% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 80,100 | 6.3% | 25.3% |
| CALL_BUILTIN_CLASS GET_ITER | 80,100 | 6.3% | 31.6% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 80,100 | 6.3% | 37.9% |
| GET_ITER FOR_ITER_RANGE | 80,080 | 6.3% | 44.2% |
| LOAD_FAST CALL_BUILTIN_CLASS | 80,040 | 6.3% | 50.5% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 80,040 | 6.3% | 56.8% |
| BINARY_OP STORE_FAST | 80,020 | 6.3% | 63.1% |
| LOAD_FAST STORE_FAST | 80,000 | 6.3% | 69.4% |
| ENTER_EXECUTOR LOAD_FAST | 79,980 | 6.3% | 75.7% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 79,800 | 6.3% | 82.0% |
| STORE_FAST ENTER_EXECUTOR | 79,660 | 6.3% | 88.2% |
| ENTER_EXECUTOR BINARY_OP | 79,600 | 6.3% | 94.5% |
| LOAD_ATTR_MODULE PUSH_NULL | 5,900 | 0.5% | 95.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 5,800 | 0.5% | 95.4% |
| STORE_FAST LOAD_FAST | 5,120 | 0.4% | 95.8% |
| PUSH_NULL CALL | 3,120 | 0.2% | 96.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,920 | 0.2% | 96.3% |
| PUSH_NULL CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,880 | 0.2% | 96.5% |
| CALL STORE_FAST | 2,580 | 0.2% | 96.7% |
| CALL LOAD_FAST | 2,560 | 0.2% | 96.9% |
| LOAD_FAST LOAD_CONST | 2,560 | 0.2% | 97.1% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 2,560 | 0.2% | 97.3% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 2,560 | 0.2% | 97.5% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 2,540 | 0.2% | 97.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 2,540 | 0.2% | 97.9% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,540 | 0.2% | 98.1% |
| LOAD_CONST COMPARE_OP_INT | 2,520 | 0.2% | 98.3% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 2,520 | 0.2% | 98.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 2,520 | 0.2% | 98.7% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_ADD_FLOAT | 2,520 | 0.2% | 98.9% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 2,220 | 0.2% | 99.1% |
| ENTER_EXECUTOR CALL | 2,160 | 0.2% | 99.3% |
| JUMP_BACKWARD FOR_ITER_RANGE | 920 | 0.1% | 99.4% |
| LOAD_FAST BINARY_OP | 440 | 0.0% | 99.4% |
| BUILD_LIST LOAD_FAST | 400 | 0.0% | 99.4% |
| LOAD_CONST BUILD_LIST | 400 | 0.0% | 99.5% |
| STORE_FAST LOAD_CONST | 400 | 0.0% | 99.5% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 380 | 0.0% | 99.5% |
| POP_TOP LOAD_GLOBAL_MODULE | 360 | 0.0% | 99.5% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 340 | 0.0% | 99.6% |
| STORE_FAST JUMP_BACKWARD | 340 | 0.0% | 99.6% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 320 | 0.0% | 99.6% |
| CALL CALL | 260 | 0.0% | 99.6% |
| STORE_FAST LOAD_GLOBAL | 240 | 0.0% | 99.7% |
| BINARY_OP BINARY_OP | 220 | 0.0% | 99.7% |
| PUSH_NULL LOAD_FAST | 160 | 0.0% | 99.7% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 99.7% |
| LOAD_FAST RETURN_VALUE | 160 | 0.0% | 99.7% |
| LOAD_FAST CALL | 160 | 0.0% | 99.7% |
| FOR_ITER_RANGE LOAD_FAST | 160 | 0.0% | 99.7% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 120 | 0.0% | 99.8% |
| CALL POP_TOP | 100 | 0.0% | 99.8% |
| LOAD_ATTR PUSH_NULL | 100 | 0.0% | 99.8% |
| LOAD_ATTR LOAD_ATTR_MODULE | 100 | 0.0% | 99.8% |
| LOAD_GLOBAL LOAD_ATTR | 100 | 0.0% | 99.8% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 100 | 0.0% | 99.8% |
| GET_ITER FOR_ITER | 80 | 0.0% | 99.8% |
| NOP LOAD_DEREF | 80 | 0.0% | 99.8% |
| POP_TOP NOP | 80 | 0.0% | 99.8% |
| RETURN_VALUE RETURN_VALUE | 80 | 0.0% | 99.8% |
| RETURN_VALUE STORE_FAST | 80 | 0.0% | 99.8% |
| BUILD_LIST LOAD_DEREF | 80 | 0.0% | 99.8% |
| BUILD_LIST STORE_FAST | 80 | 0.0% | 99.8% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 80 | 0.0% | 99.8% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 80 | 0.0% | 99.9% |
| LIST_EXTEND CALL_INTRINSIC_1 | 80 | 0.0% | 99.9% |
| LOAD_CONST STORE_FAST | 80 | 0.0% | 99.9% |
| LOAD_DEREF LIST_EXTEND | 80 | 0.0% | 99.9% |
| LOAD_FAST BUILD_LIST | 80 | 0.0% | 99.9% |
| LOAD_FAST CALL_FUNCTION_EX | 80 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_FAST | 80 | 0.0% | 99.9% |
| CALL GET_ITER | 60 | 0.0% | 99.9% |
| CALL CALL_BUILTIN_CLASS | 60 | 0.0% | 99.9% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 99.9% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 99.9% |
| FOR_ITER FOR_ITER_RANGE | 60 | 0.0% | 99.9% |
| JUMP_BACKWARD ENTER_EXECUTOR | 60 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 99.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 60 | 0.0% | 99.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.0% | 99.9% |
| RESUME_CHECK BUILD_LIST | 60 | 0.0% | 99.9% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 99.9% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 99.9% |
| POP_TOP LOAD_GLOBAL | 40 | 0.0% | 99.9% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_FAST_WITH_KEYWORDS | 40 | 0.0% | 100.0% |
| FOR_ITER STORE_FAST | 40 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER | 40 | 0.0% | 100.0% |
| LOAD_CONST COMPARE_OP | 40 | 0.0% | 100.0% |
| LOAD_FAST STORE_SUBSCR | 40 | 0.0% | 100.0% |
| LOAD_FAST LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 40 | 0.0% | 100.0% |
| STORE_SUBSCR JUMP_BACKWARD | 20 | 0.0% | 100.0% |
| STORE_SUBSCR STORE_SUBSCR_LIST_INT | 20 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 20 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 80,100 | 99.9% |
| CALL | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 80,080 | 99.9% |
| FOR_ITER | 80 | 0.1% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 380 | 79.2% |
| CALL | 100 | 20.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 360 | 75.0% |
| NOP | 80 | 16.7% |
| LOAD_GLOBAL | 40 | 8.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,900 | 95.8% |
| LOAD_DEREF | 160 | 2.6% |
| LOAD_ATTR | 100 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,120 | 50.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 2,880 | 46.8% |
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
| ENTER_EXECUTOR | 79,600 | 99.2% |
| LOAD_FAST | 440 | 0.5% |
| BINARY_OP | 220 | 0.3% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80,020 | 99.7% |
| BINARY_OP | 220 | 0.3% |
| BINARY_OP_ADD_FLOAT | 20 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 400 | 71.4% |
| LOAD_FAST | 80 | 14.3% |
| RESUME_CHECK | 60 | 10.7% |
| RESUME | 20 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 400 | 71.4% |
| LOAD_DEREF | 80 | 14.3% |
| STORE_FAST | 80 | 14.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,120 | 54.7% |
| ENTER_EXECUTOR | 2,160 | 37.9% |
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
| STORE_SUBSCR_LIST_INT | 79,800 | 49.3% |
| STORE_FAST | 79,660 | 49.3% |
| POP_JUMP_IF_FALSE | 2,220 | 1.4% |
| JUMP_BACKWARD | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 79,980 | 49.4% |
| BINARY_OP | 79,600 | 49.2% |
| CALL | 2,160 | 1.3% |


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
| POP_JUMP_IF_FALSE | 340 | 33.3% |
| STORE_FAST | 340 | 33.3% |
| STORE_SUBSCR_LIST_INT | 320 | 31.4% |
| STORE_SUBSCR | 20 | 2.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 920 | 90.2% |
| ENTER_EXECUTOR | 60 | 5.9% |
| FOR_ITER | 40 | 3.9% |


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
| LOAD_FAST | 2,560 | 84.2% |
| STORE_FAST | 400 | 13.2% |
| RESUME_CHECK | 60 | 2.0% |
| RESUME | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,520 | 82.9% |
| BUILD_LIST | 400 | 13.2% |
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
| LOAD_FAST_LOAD_FAST | 80,140 | 31.9% |
| LOAD_GLOBAL_BUILTIN | 80,100 | 31.9% |
| ENTER_EXECUTOR | 79,980 | 31.8% |
| STORE_FAST | 5,120 | 2.0% |
| CALL | 2,560 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 80,100 | 31.9% |
| CALL_BUILTIN_CLASS | 80,040 | 31.8% |
| STORE_FAST | 80,000 | 31.8% |
| LOAD_CONST | 2,560 | 1.0% |
| POP_JUMP_IF_NOT_NONE | 2,560 | 1.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80,140 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,140 | 100.0% |


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
| ENTER_EXECUTOR | 2,220 | 86.7% |
| JUMP_BACKWARD | 340 | 13.3% |


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
| FOR_ITER_RANGE | 80,900 | 32.5% |
| BINARY_OP | 80,020 | 32.2% |
| LOAD_FAST | 80,000 | 32.1% |
| CALL | 2,580 | 1.0% |
| BINARY_OP_ADD_FLOAT | 2,540 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80,140 | 32.2% |
| LOAD_GLOBAL_BUILTIN | 80,040 | 32.2% |
| ENTER_EXECUTOR | 79,660 | 32.0% |
| LOAD_FAST | 5,120 | 2.1% |
| LOAD_GLOBAL_MODULE | 2,920 | 1.2% |


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
| LOAD_FAST | 80,040 | 99.9% |
| CALL | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 80,100 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,880 | 98.6% |
| CALL | 40 | 1.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,540 | 87.0% |
| POP_TOP | 380 | 13.0% |


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
| GET_ITER | 80,080 | 98.8% |
| JUMP_BACKWARD | 920 | 1.1% |
| FOR_ITER | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80,900 | 99.8% |
| LOAD_FAST | 160 | 0.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 5,800 | 98.3% |
| LOAD_ATTR | 100 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 5,900 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80,040 | 99.9% |
| LOAD_GLOBAL | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,100 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,920 | 49.0% |
| LOAD_FAST | 2,520 | 42.3% |
| POP_TOP | 360 | 6.0% |
| LOAD_GLOBAL | 120 | 2.0% |
| RETURN_VALUE | 40 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 5,800 | 97.3% |
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
| LOAD_FAST | 80,100 | 100.0% |
| STORE_SUBSCR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 79,800 | 99.6% |
| JUMP_BACKWARD | 320 | 0.4% |


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
|     deferred | 80,040 | 93.8% |
|          hit | 5,020 | 5.9% |
|         miss | 60 | 0.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 16.7% |
| Failure | 200 | 83.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 200 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 5,320 | 6.0% |
|          hit | 83,080 | 93.6% |

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
|     deferred | 60 | 0.1% |
|          hit | 81,060 | 99.9% |

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
|     deferred | 100 | 1.6% |
|          hit | 5,900 | 96.7% |

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
|     deferred | 180 | 0.2% |
|          hit | 86,060 | 99.6% |

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
|     deferred | 20 | 0.0% |
|          hit | 80,120 | 100.0% |

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
| Basic | 834,520 | 65.7% |
| Not specialized | 91,860 | 7.2% |
| Specialized hits | 343,960 | 27.1% |
| Specialized misses | 60 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 80,040 | 93.4% |
| CALL | 5,320 | 6.2% |
| LOAD_GLOBAL | 180 | 0.2% |
| LOAD_ATTR | 100 | 0.1% |
| FOR_ITER | 60 | 0.1% |
| STORE_SUBSCR | 20 | 0.0% |
| COMPARE_OP | 20 | 0.0% |
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
| Allocations to 512 bytes | 22,506,740 | 99.3% |
| Allocations to 4 kbytes | 35,860 | 0.2% |
| Allocations over 4 kbytes | 39,040 | 0.2% |
| Frees | 22,588,840 |  |
| New values | 0 |  |
| Interpreter increfs | 102,359,720 | 99.9% |
| Interpreter decrefs | 84,837,220 | 67.9% |
| Increfs | 120,120 | 0.1% |
| Decrefs | 40,155,720 | 32.1% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 77 |  |
| Method cache misses | 23 |  |
| Method cache collisions | 23 |  |
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
| 2 | 5,120 | 0 | 5,706,074,400 |


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
| Traces executed | 161,740 |  |
| Uops executed | 520,007,240 | 3,215.08 |

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
| <= 32 | 60 | 100.0% |


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
| <= 32 | 40 | 66.7% |


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
| <= 16 | 79,600 | 49.2% |
| <= 32 | 2,220 | 1.4% |
| <= 64 | 200 | 0.1% |
| <= 128 | 380 | 0.2% |
| <= 256 | 800 | 0.5% |
| <= 512 | 1,520 | 0.9% |
| <= 1,024 | 3,200 | 2.0% |
| <= 2,048 | 6,320 | 3.9% |
| <= 4,096 | 12,560 | 7.8% |
| <= 8,192 | 25,200 | 15.6% |
| <= 16,384 | 29,520 | 18.3% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>


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
Stats gathered on: 2023-11-02
