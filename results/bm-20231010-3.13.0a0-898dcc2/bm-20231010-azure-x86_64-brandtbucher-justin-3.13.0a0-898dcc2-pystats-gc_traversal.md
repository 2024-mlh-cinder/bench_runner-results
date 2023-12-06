
# Pystats results

- benchmark: gc_traversal
- fork: brandtbucher
- ref: justin
- commit hash: 898dcc2
- commit date: 2023-10-10T14:45:03+02:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| ENTER_EXECUTOR | 121,860 | 42.3% | 42.3% |  |
| LOAD_FAST | 68,220 | 23.7% | 65.9% |  |
| STORE_FAST | 66,120 | 22.9% | 88.9% |  |
| PUSH_NULL | 4,140 | 1.4% | 90.3% |  |
| LOAD_GLOBAL_MODULE | 4,060 | 1.4% | 91.7% |  |
| CALL | 4,060 | 1.4% | 93.1% |  |
| LOAD_ATTR_MODULE | 4,000 | 1.4% | 94.5% |  |
| LOAD_CONST | 2,040 | 0.7% | 95.2% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,980 | 0.7% | 95.9% |  |
| POP_JUMP_IF_NOT_NONE | 1,920 | 0.7% | 96.6% |  |
| POP_JUMP_IF_FALSE | 1,920 | 0.7% | 97.2% |  |
| COMPARE_OP_INT | 1,920 | 0.7% | 97.9% |  |
| BINARY_OP_SUBTRACT_FLOAT | 1,920 | 0.7% | 98.6% |  |
| BINARY_OP_ADD_FLOAT | 1,920 | 0.7% | 99.2% | 3.1% |
| RETURN_VALUE | 180 | 0.1% | 99.3% |  |
| RESUME_CHECK | 180 | 0.1% | 99.4% |  |
| LOAD_GLOBAL_BUILTIN | 180 | 0.1% | 99.4% |  |
| LOAD_DEREF | 180 | 0.1% | 99.5% |  |
| GET_ITER | 180 | 0.1% | 99.6% |  |
| FOR_ITER_RANGE | 180 | 0.1% | 99.6% |  |
| CALL_BUILTIN_CLASS | 180 | 0.1% | 99.7% |  |
| BUILD_LIST | 180 | 0.1% | 99.7% |  |
| POP_TOP | 120 | 0.0% | 99.8% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 99.8% |  |
| LOAD_GLOBAL | 100 | 0.0% | 99.9% |  |
| NOP | 60 | 0.0% | 99.9% |  |
| LIST_EXTEND | 60 | 0.0% | 99.9% |  |
| COPY_FREE_VARS | 60 | 0.0% | 99.9% |  |
| CALL_PY_EXACT_ARGS | 60 | 0.0% | 99.9% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_OP | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| ENTER_EXECUTOR LOAD_FAST | 60,060 | 20.8% | 20.8% |
| STORE_FAST ENTER_EXECUTOR | 60,000 | 20.8% | 41.6% |
| LOAD_FAST STORE_FAST | 60,000 | 20.8% | 62.5% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 59,940 | 20.8% | 83.3% |
| LOAD_ATTR_MODULE PUSH_NULL | 4,000 | 1.4% | 84.6% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 3,980 | 1.4% | 86.0% |
| STORE_FAST LOAD_FAST | 3,840 | 1.3% | 87.4% |
| PUSH_NULL CALL | 2,040 | 0.7% | 88.1% |
| STORE_FAST LOAD_GLOBAL_MODULE | 2,020 | 0.7% | 88.8% |
| PUSH_NULL CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,980 | 0.7% | 89.5% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,920 | 0.7% | 90.1% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 1,920 | 0.7% | 90.8% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,920 | 0.7% | 91.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,920 | 0.7% | 92.1% |
| LOAD_FAST LOAD_CONST | 1,920 | 0.7% | 92.8% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 1,920 | 0.7% | 93.5% |
| LOAD_CONST COMPARE_OP_INT | 1,920 | 0.7% | 94.1% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,920 | 0.7% | 94.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 1,920 | 0.7% | 95.4% |
| CALL STORE_FAST | 1,920 | 0.7% | 96.1% |
| CALL LOAD_FAST | 1,920 | 0.7% | 96.8% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_ADD_FLOAT | 1,920 | 0.7% | 97.4% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 1,920 | 0.7% | 98.1% |
| ENTER_EXECUTOR CALL | 1,860 | 0.6% | 98.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 180 | 0.1% | 98.8% |
| GET_ITER FOR_ITER_RANGE | 180 | 0.1% | 98.9% |
| CALL_BUILTIN_CLASS GET_ITER | 180 | 0.1% | 98.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 140 | 0.0% | 99.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 140 | 0.0% | 99.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 99.1% |
| LOAD_FAST RETURN_VALUE | 120 | 0.0% | 99.1% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 99.2% |
| FOR_ITER_RANGE STORE_FAST | 120 | 0.0% | 99.2% |
| CALL CALL | 100 | 0.0% | 99.2% |
| STORE_FAST LOAD_GLOBAL | 60 | 0.0% | 99.3% |
| STORE_FAST LOAD_CONST | 60 | 0.0% | 99.3% |
| RETURN_VALUE STORE_FAST | 60 | 0.0% | 99.3% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 99.3% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 99.3% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 99.4% |
| RESUME_CHECK BUILD_LIST | 60 | 0.0% | 99.4% |
| POP_TOP NOP | 60 | 0.0% | 99.4% |
| POP_TOP LOAD_GLOBAL_MODULE | 60 | 0.0% | 99.4% |
| NOP LOAD_DEREF | 60 | 0.0% | 99.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.0% | 99.5% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 99.5% |
| LOAD_FAST CALL | 60 | 0.0% | 99.5% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 99.5% |
| LOAD_FAST BINARY_OP | 60 | 0.0% | 99.6% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 99.6% |
| LOAD_CONST STORE_FAST | 60 | 0.0% | 99.6% |
| LOAD_CONST BUILD_LIST | 60 | 0.0% | 99.6% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 99.6% |
| FOR_ITER_RANGE LOAD_FAST | 60 | 0.0% | 99.7% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 99.7% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 60 | 0.0% | 99.7% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 99.7% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 99.7% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 99.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 60 | 0.0% | 99.8% |
| CALL POP_TOP | 60 | 0.0% | 99.8% |
| BUILD_LIST STORE_FAST | 60 | 0.0% | 99.8% |
| BUILD_LIST LOAD_FAST | 60 | 0.0% | 99.8% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 99.9% |
| BINARY_OP STORE_FAST | 60 | 0.0% | 99.9% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 40 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 99.9% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 40 | 0.0% | 99.9% |
| CALL CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 20 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 20 | 0.0% | 100.0% |
| CALL CALL_PY_EXACT_ARGS | 20 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 180 | 100.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 60 | 50.0% |
| CALL | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 60 | 50.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 4,000 | 96.6% |
| LOAD_DEREF | 120 | 2.9% |
| LOAD_ATTR | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 2,040 | 49.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,980 | 47.8% |
| LOAD_FAST | 120 | 2.9% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 66.7% |
| RETURN_VALUE | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| RETURN_VALUE | 60 | 33.3% |
| LOAD_GLOBAL | 40 | 22.2% |
| LOAD_GLOBAL_MODULE | 20 | 11.1% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |
| LOAD_CONST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 33.3% |
| LOAD_FAST | 60 | 33.3% |
| LOAD_DEREF | 60 | 33.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 2,040 | 50.2% |
| ENTER_EXECUTOR | 1,860 | 45.8% |
| CALL | 100 | 2.5% |
| LOAD_FAST | 60 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920 | 47.3% |
| LOAD_FAST | 1,920 | 47.3% |
| CALL | 100 | 2.5% |
| POP_TOP | 60 | 1.5% |
| CALL_BUILTIN_CLASS | 40 | 1.0% |


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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60,000 | 49.2% |
| ENTER_EXECUTOR | 59,940 | 49.2% |
| POP_JUMP_IF_FALSE | 1,920 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,060 | 49.3% |
| ENTER_EXECUTOR | 59,940 | 49.2% |
| CALL | 1,860 | 1.5% |


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
| LOAD_GLOBAL_MODULE | 20 | 50.0% |
| LOAD_GLOBAL | 20 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 20 | 50.0% |
| LOAD_ATTR_MODULE | 20 | 50.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 94.1% |
| STORE_FAST | 60 | 2.9% |
| RESUME_CHECK | 60 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 1,920 | 94.1% |
| STORE_FAST | 60 | 2.9% |
| BUILD_LIST | 60 | 2.9% |


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
| ENTER_EXECUTOR | 60,060 | 88.0% |
| STORE_FAST | 3,840 | 5.6% |
| POP_JUMP_IF_NOT_NONE | 1,920 | 2.8% |
| CALL | 1,920 | 2.8% |
| LOAD_GLOBAL_BUILTIN | 180 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60,000 | 88.0% |
| POP_JUMP_IF_NOT_NONE | 1,920 | 2.8% |
| LOAD_GLOBAL_MODULE | 1,920 | 2.8% |
| LOAD_CONST | 1,920 | 2.8% |
| BINARY_OP_SUBTRACT_FLOAT | 1,920 | 2.8% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 60.0% |
| RETURN_VALUE | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 40.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 40.0% |
| LOAD_ATTR | 20 | 20.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 1,920 | 100.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,000 | 90.7% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,920 | 2.9% |
| CALL | 1,920 | 2.9% |
| BINARY_OP_ADD_FLOAT | 1,920 | 2.9% |
| FOR_ITER_RANGE | 120 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 60,000 | 90.7% |
| LOAD_FAST | 3,840 | 5.8% |
| LOAD_GLOBAL_MODULE | 2,020 | 3.1% |
| LOAD_GLOBAL_BUILTIN | 140 | 0.2% |
| LOAD_GLOBAL | 60 | 0.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 1,920 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140 | 77.8% |
| CALL | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 180 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920 | 97.0% |
| POP_TOP | 60 | 3.0% |


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
| LOAD_CONST | 1,920 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 1,920 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 66.7% |
| LOAD_FAST | 60 | 33.3% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,980 | 99.5% |
| LOAD_ATTR | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 4,000 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 140 | 77.8% |
| LOAD_GLOBAL | 40 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,020 | 49.8% |
| LOAD_FAST | 1,920 | 47.3% |
| POP_TOP | 60 | 1.5% |
| LOAD_GLOBAL | 40 | 1.0% |
| RETURN_VALUE | 20 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 3,980 | 98.0% |
| LOAD_FAST | 60 | 1.5% |
| LOAD_ATTR | 20 | 0.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 33.3% |
| CALL_PY_EXACT_ARGS | 60 | 33.3% |
| CALL_FUNCTION_EX | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 33.3% |
| LOAD_CONST | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     29970000 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 1.5% |
|          hit |         3780 | 96.9% |
|         miss |           60 | 1.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         3900 | 5.7% |
|          hit |        64020 | 94.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 37.5% |
| Failure | 100 | 62.5% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 100 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |         1920 | 100.0% |


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
| specialization.deferred |           20 | 0.3% |
|          hit |         7720 | 99.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
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
|          hit |        67900 | 99.9% |

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

### POP_JUMP_IF_NOT_NONE

<details>
<summary> specialization stats for POP_JUMP_IF_NOT_NONE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 263,580 | 91.4% |
| Not specialized | 8,160 | 2.8% |
| Specialized | 16,520 | 5.7% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 3,900 | 97.5% |
| BINARY_OP | 60 | 1.5% |
| LOAD_GLOBAL | 20 | 0.5% |
| LOAD_ATTR | 20 | 0.5% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 60 | 100.0% |
| STORE_FAST | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RESUME_CHECK | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| NOP | 0 | 0.0% |
| LOAD_GLOBAL_MODULE | 0 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 0 | 0.0% |
| LOAD_FAST | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 180 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 66.7% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 180 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 64,860 | 0.4% |
| Frees to freelist | 68,820 |  |
| Allocations | 16,935,660 | 99.6% |
| Allocations to 512 bytes | 16,879,500 | 99.3% |
| Allocations to 4 kbytes | 26,880 | 0.2% |
| Allocations over 4 kbytes | 29,280 | 0.2% |
| Frees | 16,935,580 |  |
| New values | 0 |  |
| Interpreter increfs | 194,620 | 0.3% |
| Interpreter decrefs | 79,140 | 0.1% |
| Increfs | 76,665,220 | 99.7% |
| Decrefs | 93,661,160 | 99.9% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 16 |  |
| Method cache misses | 4 |  |
| Method cache collisions | 4 |  |
| Method cache dunder hits | 0 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 60 | 0 | 36,240,200 |
| 1 | 0 | 0 | 0 |
| 2 | 3,840 | 0 | 4,294,694,400 |


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
