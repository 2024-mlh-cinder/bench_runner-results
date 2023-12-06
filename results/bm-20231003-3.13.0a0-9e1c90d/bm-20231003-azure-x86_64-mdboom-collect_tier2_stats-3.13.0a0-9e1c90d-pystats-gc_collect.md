
# Pystats results

- benchmark: gc_collect
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 41,879,280 | 18.5% | 18.5% |  |
| STORE_ATTR_INSTANCE_VALUE | 32,256,000 | 14.3% | 32.8% |  |
| STORE_FAST | 16,535,160 | 7.3% | 40.1% |  |
| LOAD_FAST_LOAD_FAST | 16,519,680 | 7.3% | 47.4% |  |
| RESUME_CHECK | 16,515,960 | 7.3% | 54.7% | 0.0% |
| LOAD_CONST | 16,515,900 | 7.3% | 62.0% |  |
| RETURN_CONST | 16,512,000 | 7.3% | 69.4% |  |
| POP_TOP | 8,451,900 | 3.7% | 73.1% |  |
| CALL_PY_EXACT_ARGS | 8,451,840 | 3.7% | 76.8% |  |
| RETURN_VALUE | 8,067,960 | 3.6% | 80.4% |  |
| ENTER_EXECUTOR | 8,067,840 | 3.6% | 84.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,064,000 | 3.6% | 87.5% |  |
| LOAD_ATTR_INSTANCE_VALUE | 8,064,000 | 3.6% | 91.1% |  |
| EXIT_INIT_CHECK | 8,064,000 | 3.6% | 94.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 8,064,000 | 3.6% | 98.2% |  |
| LOAD_GLOBAL_MODULE | 787,300 | 0.3% | 98.6% |  |
| LOAD_GLOBAL_BUILTIN | 387,900 | 0.2% | 98.8% |  |
| GET_ITER | 387,900 | 0.2% | 98.9% |  |
| FOR_ITER_RANGE | 387,900 | 0.2% | 99.1% |  |
| CALL_BUILTIN_CLASS | 387,900 | 0.2% | 99.3% |  |
| POP_JUMP_IF_FALSE | 387,840 | 0.2% | 99.5% |  |
| COMPARE_OP_INT | 387,840 | 0.2% | 99.6% |  |
| LOAD_ATTR_METHOD_NO_DICT | 384,000 | 0.2% | 99.8% |  |
| CALL_LIST_APPEND | 384,000 | 0.2% | 100.0% |  |
| PUSH_NULL | 15,540 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 15,400 | 0.0% | 100.0% |  |
| CALL | 7,860 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,680 | 0.0% | 100.0% |  |
| BUILD_LIST | 3,900 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 3,840 | 0.0% | 100.0% |  |
| DELETE_FAST | 3,840 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 3,840 | 0.0% | 100.0% |  |
| BINARY_OP_MULTIPLY_INT | 3,840 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_INT | 3,840 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 3,840 | 0.0% | 100.0% | 1.6% |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 16,128,000 | 7.1% | 7.1% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 16,128,000 | 7.1% | 14.3% |
| LOAD_CONST LOAD_FAST | 16,128,000 | 7.1% | 21.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,451,840 | 3.7% | 25.2% |
| RETURN_CONST POP_TOP | 8,448,000 | 3.7% | 28.9% |
| STORE_FAST LOAD_FAST | 8,071,680 | 3.6% | 32.5% |
| RETURN_VALUE STORE_FAST | 8,067,840 | 3.6% | 36.0% |
| RESUME_CHECK LOAD_CONST | 8,064,060 | 3.6% | 39.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 8,064,000 | 3.6% | 43.2% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 8,064,000 | 3.6% | 46.7% |
| RETURN_CONST EXIT_INIT_CHECK | 8,064,000 | 3.6% | 50.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 8,064,000 | 3.6% | 53.9% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 3.6% | 57.4% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 8,064,000 | 3.6% | 61.0% |
| LOAD_FAST STORE_FAST | 8,064,000 | 3.6% | 64.6% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 8,064,000 | 3.6% | 68.1% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 8,064,000 | 3.6% | 71.7% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 8,064,000 | 3.6% | 75.3% |
| LOAD_ATTR_INSTANCE_VALUE STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 3.6% | 78.9% |
| EXIT_INIT_CHECK RETURN_VALUE | 8,064,000 | 3.6% | 82.4% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 8,064,000 | 3.6% | 86.0% |
| STORE_FAST ENTER_EXECUTOR | 7,680,000 | 3.4% | 89.4% |
| POP_TOP LOAD_FAST | 7,680,000 | 3.4% | 92.8% |
| ENTER_EXECUTOR CALL_ALLOC_AND_ENTER_INIT | 7,676,160 | 3.4% | 96.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 391,740 | 0.2% | 96.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 387,900 | 0.2% | 96.5% |
| GET_ITER FOR_ITER_RANGE | 387,900 | 0.2% | 96.7% |
| FOR_ITER_RANGE STORE_FAST | 387,900 | 0.2% | 96.9% |
| ENTER_EXECUTOR LOAD_FAST | 387,900 | 0.2% | 97.0% |
| CALL_BUILTIN_CLASS GET_ITER | 387,900 | 0.2% | 97.2% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 387,880 | 0.2% | 97.4% |
| LOAD_FAST CALL_BUILTIN_CLASS | 387,880 | 0.2% | 97.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 387,840 | 0.2% | 97.7% |
| LOAD_GLOBAL_MODULE CALL_ALLOC_AND_ENTER_INIT | 387,840 | 0.2% | 97.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 387,840 | 0.2% | 98.1% |
| LOAD_FAST LOAD_CONST | 387,840 | 0.2% | 98.2% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 387,840 | 0.2% | 98.4% |
| RESUME_CHECK LOAD_FAST | 384,000 | 0.2% | 98.6% |
| POP_TOP RETURN_CONST | 384,000 | 0.2% | 98.8% |
| POP_TOP ENTER_EXECUTOR | 384,000 | 0.2% | 98.9% |
| POP_JUMP_IF_FALSE LOAD_FAST | 384,000 | 0.2% | 99.1% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 384,000 | 0.2% | 99.3% |
| LOAD_FAST CALL_LIST_APPEND | 384,000 | 0.2% | 99.4% |
| LOAD_CONST COMPARE_OP_INT | 384,000 | 0.2% | 99.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 384,000 | 0.2% | 99.8% |
| CALL_LIST_APPEND LOAD_GLOBAL_MODULE | 384,000 | 0.2% | 99.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 15,400 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 11,600 | 0.0% | 100.0% |
| PUSH_NULL CALL | 7,740 | 0.0% | 100.0% |
| PUSH_NULL CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,680 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 3,900 | 0.0% | 100.0% |
| STORE_FAST DELETE_FAST | 3,840 | 0.0% | 100.0% |
| RESUME_CHECK BUILD_LIST | 3,840 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_MODULE | 3,840 | 0.0% | 100.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 3,840 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 3,840 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 3,840 | 0.0% | 100.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 3,840 | 0.0% | 100.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 3,840 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 3,840 | 0.0% | 100.0% |
| LOAD_CONST BINARY_OP_ADD_INT | 3,840 | 0.0% | 100.0% |
| DELETE_FAST LOAD_GLOBAL_MODULE | 3,840 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 3,840 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 3,840 | 0.0% | 100.0% |
| CALL STORE_FAST | 3,840 | 0.0% | 100.0% |
| CALL LOAD_FAST | 3,840 | 0.0% | 100.0% |
| BUILD_LIST STORE_FAST | 3,840 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_ADD_FLOAT | 3,840 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_INT COMPARE_OP_INT | 3,840 | 0.0% | 100.0% |
| BINARY_OP_ADD_INT BINARY_OP_MULTIPLY_INT | 3,840 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 3,840 | 0.0% | 100.0% |
| ENTER_EXECUTOR LOAD_ATTR_MODULE | 3,780 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| CALL CALL | 100 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LOAD_CONST STORE_FAST | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 20 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_FAST CALL | 20 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 20 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 20 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### EXIT_INIT_CHECK

<details>
<summary> Successors and predecessors for EXIT_INIT_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 8,064,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,064,000 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 387,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 387,900 | 100.0% |


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
| RETURN_CONST | 8,448,000 | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,840 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 7,680,000 | 90.9% |
| RETURN_CONST | 384,000 | 4.5% |
| ENTER_EXECUTOR | 384,000 | 4.5% |
| LOAD_GLOBAL_MODULE | 3,840 | 0.0% |
| NOP | 60 | 0.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 15,400 | 99.1% |
| LOAD_DEREF | 120 | 0.8% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 7,740 | 49.8% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,680 | 49.4% |
| LOAD_FAST | 120 | 0.8% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXIT_INIT_CHECK | 8,064,000 | 100.0% |
| LOAD_FAST | 3,900 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,067,840 | 100.0% |
| RETURN_VALUE | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_MODULE | 20 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 3,840 | 98.5% |
| LOAD_FAST | 60 | 1.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,840 | 98.5% |
| LOAD_DEREF | 60 | 1.5% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,740 | 98.5% |
| CALL | 100 | 1.3% |
| LOAD_FAST | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,840 | 48.9% |
| LOAD_FAST | 3,840 | 48.9% |
| CALL | 100 | 1.3% |
| POP_TOP | 60 | 0.8% |
| CALL_BUILTIN_CLASS | 20 | 0.3% |


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

### DELETE_FAST

<details>
<summary> Successors and predecessors for DELETE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 3,840 | 100.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,680,000 | 95.2% |
| POP_TOP | 384,000 | 4.8% |
| POP_JUMP_IF_FALSE | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ALLOC_AND_ENTER_INIT | 7,676,160 | 95.1% |
| LOAD_FAST | 387,900 | 4.8% |
| LOAD_ATTR_MODULE | 3,780 | 0.0% |


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
| RESUME_CHECK | 8,064,060 | 48.8% |
| STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 48.8% |
| LOAD_FAST | 387,840 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,128,000 | 97.7% |
| COMPARE_OP_INT | 384,000 | 2.3% |
| BINARY_OP_ADD_INT | 3,840 | 0.0% |
| STORE_FAST | 60 | 0.0% |


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
| LOAD_CONST | 16,128,000 | 38.5% |
| STORE_FAST | 8,071,680 | 19.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,064,000 | 19.3% |
| POP_TOP | 7,680,000 | 18.3% |
| LOAD_GLOBAL_BUILTIN | 387,900 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 16,128,000 | 38.5% |
| STORE_FAST | 8,064,000 | 19.3% |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,064,000 | 19.3% |
| CALL_PY_EXACT_ARGS | 8,064,000 | 19.3% |
| CALL_BUILTIN_CLASS | 387,880 | 0.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 48.8% |
| RESUME_CHECK | 8,064,000 | 48.8% |
| LOAD_GLOBAL_MODULE | 387,840 | 2.3% |
| POP_JUMP_IF_NOT_NONE | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 48.8% |
| LOAD_ATTR_INSTANCE_VALUE | 8,064,000 | 48.8% |
| CALL_PY_EXACT_ARGS | 387,840 | 2.3% |
| LOAD_FAST | 3,840 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40 | 66.7% |
| STORE_FAST | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 20 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 20 | 33.3% |
| LOAD_ATTR | 20 | 33.3% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 387,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 384,000 | 99.0% |
| ENTER_EXECUTOR | 3,840 | 1.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,840 | 100.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 16,128,000 | 97.7% |
| POP_TOP | 384,000 | 2.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 8,448,000 | 51.2% |
| EXIT_INIT_CHECK | 8,064,000 | 48.8% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 8,067,840 | 48.8% |
| LOAD_FAST | 8,064,000 | 48.8% |
| FOR_ITER_RANGE | 387,900 | 2.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,840 | 0.0% |
| CALL | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,071,680 | 48.8% |
| ENTER_EXECUTOR | 7,680,000 | 46.4% |
| LOAD_GLOBAL_MODULE | 391,740 | 2.4% |
| LOAD_GLOBAL_BUILTIN | 387,880 | 2.3% |
| DELETE_FAST | 3,840 | 0.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,840 | 100.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_INT | 3,840 | 100.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 3,840 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 3,840 | 100.0% |


</details>

### CALL_ALLOC_AND_ENTER_INIT

<details>
<summary> Successors and predecessors for CALL_ALLOC_AND_ENTER_INIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 7,676,160 | 95.2% |
| LOAD_GLOBAL_MODULE | 387,840 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,064,000 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 387,880 | 100.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 387,900 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,680 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,840 | 50.0% |
| POP_TOP | 3,840 | 50.0% |


</details>

### CALL_LIST_APPEND

<details>
<summary> Successors and predecessors for CALL_LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 384,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 384,000 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,064,000 | 95.4% |
| LOAD_FAST_LOAD_FAST | 387,840 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 8,451,840 | 100.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 384,000 | 99.0% |
| BINARY_OP_MULTIPLY_INT | 3,840 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 387,840 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 387,900 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 387,900 | 100.0% |


</details>

### LOAD_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for LOAD_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 8,064,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 100.0% |


</details>

### LOAD_ATTR_METHOD_NO_DICT

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_NO_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 384,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 384,000 | 100.0% |


</details>

### LOAD_ATTR_METHOD_WITH_VALUES

<details>
<summary> Successors and predecessors for LOAD_ATTR_METHOD_WITH_VALUES </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,064,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 8,064,000 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 11,600 | 75.3% |
| ENTER_EXECUTOR | 3,780 | 24.5% |
| LOAD_ATTR | 20 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 15,400 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 387,880 | 100.0% |
| LOAD_GLOBAL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 387,900 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 391,740 | 49.8% |
| CALL_LIST_APPEND | 384,000 | 48.8% |
| POP_TOP | 3,840 | 0.5% |
| LOAD_FAST | 3,840 | 0.5% |
| DELETE_FAST | 3,840 | 0.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 387,840 | 49.3% |
| CALL_ALLOC_AND_ENTER_INIT | 387,840 | 49.3% |
| LOAD_ATTR_MODULE | 11,600 | 1.5% |
| LOAD_ATTR | 20 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 8,451,840 | 51.2% |
| CALL_ALLOC_AND_ENTER_INIT | 8,064,000 | 48.8% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 8,064,060 | 48.8% |
| LOAD_FAST_LOAD_FAST | 8,064,000 | 48.8% |
| LOAD_FAST | 384,000 | 2.3% |
| BUILD_LIST | 3,840 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### STORE_ATTR_INSTANCE_VALUE

<details>
<summary> Successors and predecessors for STORE_ATTR_INSTANCE_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 16,128,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 8,064,000 | 25.0% |
| LOAD_ATTR_INSTANCE_VALUE | 8,064,000 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 16,128,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 8,064,000 | 25.0% |
| LOAD_CONST | 8,064,000 | 25.0% |


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
|          hit |        15300 | 99.6% |
|         miss |           60 | 0.4% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |         7740 | 0.0% |
|          hit |     17295420 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 16.7% |
| Failure | 100 | 83.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 100 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       387840 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       387900 | 100.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           20 | 0.0% |
|          hit |     16527400 | 100.0% |

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
|          hit |      1175200 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
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

### STORE_ATTR

<details>
<summary> specialization stats for STORE_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     32256000 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 141,025,440 | 62.4% |
| Not specialized | 407,380 | 0.2% |
| Specialized | 84,553,340 | 37.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME | 368,934,881,474,191,024,640 | 100.0% |
| CALL | 7,740 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| RESUME_CHECK | 7,680 | 49.8% |
| RESUME | 7,680 | 49.8% |
| BINARY_OP_ADD_FLOAT | 60 | 0.4% |
| STORE_FAST | 0 | 0.0% |
| STORE_ATTR_INSTANCE_VALUE | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RETURN_CONST | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| NOP | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 16,515,960 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 24,579,960 | 148.8% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 0 | 0.0% |
| Frees to freelist | 11,640 |  |
| Allocations | 16,953,960 | 100.0% |
| Allocations to 512 bytes | 16,953,960 | 100.0% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 16,957,720 |  |
| New values | 0 |  |
| Interpreter increfs | 131,774,140 | 84.9% |
| Interpreter decrefs | 123,345,480 | 75.2% |
| Increfs | 23,424,040 | 15.1% |
| Decrefs | 40,742,540 | 24.8% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 18 |  |
| Method cache misses | 2 |  |
| Method cache collisions | 2 |  |
| Method cache dunder hits | 0 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 7,680 | 0 | 32,509,440 |
| 1 | 0 | 0 | 0 |
| 2 | 7,680 | 8,064,000 | 974,407,760 |


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
| Traces executed | 8,067,840 |  |
| Uops executed | 87,194,640 | 10 |
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
| <= 8 | 387,900 | 4.8% |
| <= 16 | 7,679,940 | 95.2% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 23,815,620 | 27.3% | 27.3% |
| _POP_JUMP_IF_TRUE | 8,067,840 | 9.3% | 36.6% |
| _ITER_CHECK_RANGE | 8,067,840 | 9.3% | 45.8% |
| _IS_ITER_EXHAUSTED_RANGE | 8,067,840 | 9.3% | 55.1% |
| _EXIT_TRACE | 8,067,840 | 9.3% | 64.3% |
| _LOAD_GLOBAL_MODULE | 7,679,940 | 8.8% | 73.1% |
| _ITER_NEXT_RANGE | 7,679,940 | 8.8% | 81.9% |
| _GUARD_GLOBALS_VERSION | 7,679,940 | 8.8% | 90.7% |
| STORE_FAST | 7,679,940 | 8.8% | 99.6% |
| POP_TOP | 387,900 | 0.4% | 100.0% |


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
