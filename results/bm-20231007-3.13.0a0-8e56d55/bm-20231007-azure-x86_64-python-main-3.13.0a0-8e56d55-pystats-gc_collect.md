
# Pystats results

- benchmark: gc_collect
- fork: python
- ref: main
- commit hash: 8e56d55
- commit date: 2023-10-07T17:07:36-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 41,879,280 | 16.8% | 16.8% |  |
| STORE_ATTR_INSTANCE_VALUE | 32,256,000 | 12.9% | 29.7% |  |
| STORE_FAST | 24,215,100 | 9.7% | 39.4% |  |
| LOAD_FAST_LOAD_FAST | 16,519,680 | 6.6% | 46.1% |  |
| RESUME_CHECK | 16,515,960 | 6.6% | 52.7% | 0.0% |
| LOAD_CONST | 16,515,900 | 6.6% | 59.3% |  |
| RETURN_CONST | 16,512,000 | 6.6% | 65.9% |  |
| LOAD_GLOBAL_MODULE | 8,467,240 | 3.4% | 69.3% |  |
| FOR_ITER_RANGE | 8,455,740 | 3.4% | 72.7% |  |
| POP_TOP | 8,451,900 | 3.4% | 76.1% |  |
| CALL_PY_EXACT_ARGS | 8,451,840 | 3.4% | 79.5% |  |
| RETURN_VALUE | 8,067,960 | 3.2% | 82.7% |  |
| JUMP_BACKWARD | 8,067,840 | 3.2% | 86.0% |  |
| LOAD_ATTR_METHOD_WITH_VALUES | 8,064,000 | 3.2% | 89.2% |  |
| LOAD_ATTR_INSTANCE_VALUE | 8,064,000 | 3.2% | 92.4% |  |
| EXIT_INIT_CHECK | 8,064,000 | 3.2% | 95.7% |  |
| CALL_ALLOC_AND_ENTER_INIT | 8,064,000 | 3.2% | 98.9% |  |
| LOAD_GLOBAL_BUILTIN | 387,900 | 0.2% | 99.0% |  |
| GET_ITER | 387,900 | 0.2% | 99.2% |  |
| CALL_BUILTIN_CLASS | 387,900 | 0.2% | 99.4% |  |
| POP_JUMP_IF_FALSE | 387,840 | 0.2% | 99.5% |  |
| COMPARE_OP_INT | 387,840 | 0.2% | 99.7% |  |
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
| STORE_ATTR_INSTANCE_VALUE RETURN_CONST | 16,128,000 | 6.5% | 6.5% |
| LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 16,128,000 | 6.5% | 12.9% |
| LOAD_CONST LOAD_FAST | 16,128,000 | 6.5% | 19.4% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 8,451,840 | 3.4% | 22.8% |
| RETURN_CONST POP_TOP | 8,448,000 | 3.4% | 26.2% |
| STORE_FAST LOAD_GLOBAL_MODULE | 8,071,680 | 3.2% | 29.4% |
| STORE_FAST LOAD_FAST | 8,071,680 | 3.2% | 32.6% |
| RETURN_VALUE STORE_FAST | 8,067,840 | 3.2% | 35.9% |
| JUMP_BACKWARD FOR_ITER_RANGE | 8,067,840 | 3.2% | 39.1% |
| FOR_ITER_RANGE STORE_FAST | 8,067,840 | 3.2% | 42.4% |
| RESUME_CHECK LOAD_CONST | 8,064,060 | 3.2% | 45.6% |
| STORE_ATTR_INSTANCE_VALUE LOAD_FAST_LOAD_FAST | 8,064,000 | 3.2% | 48.8% |
| STORE_ATTR_INSTANCE_VALUE LOAD_CONST | 8,064,000 | 3.2% | 52.1% |
| RETURN_CONST EXIT_INIT_CHECK | 8,064,000 | 3.2% | 55.3% |
| RESUME_CHECK LOAD_FAST_LOAD_FAST | 8,064,000 | 3.2% | 58.5% |
| LOAD_GLOBAL_MODULE CALL_ALLOC_AND_ENTER_INIT | 8,064,000 | 3.2% | 61.8% |
| LOAD_FAST_LOAD_FAST STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 3.2% | 65.0% |
| LOAD_FAST_LOAD_FAST LOAD_ATTR_INSTANCE_VALUE | 8,064,000 | 3.2% | 68.2% |
| LOAD_FAST STORE_FAST | 8,064,000 | 3.2% | 71.5% |
| LOAD_FAST LOAD_ATTR_METHOD_WITH_VALUES | 8,064,000 | 3.2% | 74.7% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 8,064,000 | 3.2% | 77.9% |
| LOAD_ATTR_METHOD_WITH_VALUES LOAD_FAST | 8,064,000 | 3.2% | 81.1% |
| LOAD_ATTR_INSTANCE_VALUE STORE_ATTR_INSTANCE_VALUE | 8,064,000 | 3.2% | 84.4% |
| EXIT_INIT_CHECK RETURN_VALUE | 8,064,000 | 3.2% | 87.6% |
| CALL_ALLOC_AND_ENTER_INIT RESUME_CHECK | 8,064,000 | 3.2% | 90.8% |
| STORE_FAST JUMP_BACKWARD | 7,680,000 | 3.1% | 93.9% |
| POP_TOP LOAD_FAST | 7,680,000 | 3.1% | 97.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 387,900 | 0.2% | 97.2% |
| GET_ITER FOR_ITER_RANGE | 387,900 | 0.2% | 97.3% |
| FOR_ITER_RANGE LOAD_FAST | 387,900 | 0.2% | 97.5% |
| CALL_BUILTIN_CLASS GET_ITER | 387,900 | 0.2% | 97.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 387,880 | 0.2% | 97.8% |
| LOAD_FAST CALL_BUILTIN_CLASS | 387,880 | 0.2% | 97.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 387,840 | 0.2% | 98.1% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 387,840 | 0.2% | 98.3% |
| LOAD_FAST LOAD_CONST | 387,840 | 0.2% | 98.4% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 387,840 | 0.2% | 98.6% |
| RESUME_CHECK LOAD_FAST | 384,000 | 0.2% | 98.7% |
| POP_TOP RETURN_CONST | 384,000 | 0.2% | 98.9% |
| POP_TOP JUMP_BACKWARD | 384,000 | 0.2% | 99.0% |
| POP_JUMP_IF_FALSE LOAD_FAST | 384,000 | 0.2% | 99.2% |
| LOAD_FAST LOAD_ATTR_METHOD_NO_DICT | 384,000 | 0.2% | 99.3% |
| LOAD_FAST CALL_LIST_APPEND | 384,000 | 0.2% | 99.5% |
| LOAD_CONST COMPARE_OP_INT | 384,000 | 0.2% | 99.6% |
| LOAD_ATTR_METHOD_NO_DICT LOAD_FAST | 384,000 | 0.2% | 99.8% |
| CALL_LIST_APPEND LOAD_GLOBAL_MODULE | 384,000 | 0.2% | 99.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 15,400 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 15,380 | 0.0% | 100.0% |
| PUSH_NULL CALL | 7,740 | 0.0% | 100.0% |
| PUSH_NULL CALL_BUILTIN_FAST_WITH_KEYWORDS | 7,680 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 3,900 | 0.0% | 100.0% |
| STORE_FAST DELETE_FAST | 3,840 | 0.0% | 100.0% |
| RESUME_CHECK BUILD_LIST | 3,840 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_MODULE | 3,840 | 0.0% | 100.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST_LOAD_FAST | 3,840 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 3,840 | 0.0% | 100.0% |
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
| CALL CALL_BUILTIN_CLASS | 20 | 0.0% | 100.0% |


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
| JUMP_BACKWARD | 384,000 | 4.5% |
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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 7,680,000 | 95.2% |
| POP_TOP | 384,000 | 4.8% |
| POP_JUMP_IF_FALSE | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 8,067,840 | 100.0% |


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
| JUMP_BACKWARD | 3,840 | 1.0% |


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
| RETURN_VALUE | 8,067,840 | 33.3% |
| FOR_ITER_RANGE | 8,067,840 | 33.3% |
| LOAD_FAST | 8,064,000 | 33.3% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,840 | 0.0% |
| CALL | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 8,071,680 | 33.3% |
| LOAD_FAST | 8,071,680 | 33.3% |
| JUMP_BACKWARD | 7,680,000 | 31.7% |
| LOAD_GLOBAL_BUILTIN | 387,880 | 1.6% |
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
| LOAD_GLOBAL_MODULE | 8,064,000 | 100.0% |

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
| JUMP_BACKWARD | 8,067,840 | 95.4% |
| GET_ITER | 387,900 | 4.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 8,067,840 | 95.4% |
| LOAD_FAST | 387,900 | 4.6% |


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
| LOAD_GLOBAL_MODULE | 15,380 | 99.9% |
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
| STORE_FAST | 8,071,680 | 95.3% |
| CALL_LIST_APPEND | 384,000 | 4.5% |
| POP_TOP | 3,840 | 0.0% |
| LOAD_FAST | 3,840 | 0.0% |
| DELETE_FAST | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_ALLOC_AND_ENTER_INIT | 8,064,000 | 95.2% |
| LOAD_FAST_LOAD_FAST | 387,840 | 4.6% |
| LOAD_ATTR_MODULE | 15,380 | 0.2% |
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
|          hit |      8455740 | 100.0% |


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
|          hit |      8855140 | 100.0% |

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
| Basic | 140,637,540 | 56.4% |
| Not specialized | 8,475,220 | 3.4% |
| Specialized | 100,301,120 | 40.2% |

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
| Interpreter increfs | 131,386,240 | 89.3% |
| Interpreter decrefs | 123,733,380 | 79.3% |
| Increfs | 15,744,100 | 10.7% |
| Decrefs | 32,286,800 | 20.7% |
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
| 0 | 7,680 | 0 | 32,509,440 |
| 1 | 0 | 0 | 0 |
| 2 | 7,680 | 8,064,000 | 970,767,440 |


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
Stats gathered on: 2023-10-08
