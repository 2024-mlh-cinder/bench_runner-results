
# Pystats results

- benchmark: gc_traversal
- fork: gvanrossum
- ref: load-attr-uops
- commit hash: b54eee3
- commit date: 2023-09-26T21:26:46-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 30,158,100 | 16.7% | 16.7% |  |
| STORE_FAST | 30,157,860 | 16.7% | 33.4% |  |
| FOR_ITER_RANGE | 30,092,040 | 16.6% | 50.0% |  |
| JUMP_BACKWARD | 30,031,920 | 16.6% | 66.6% |  |
| STORE_SUBSCR_LIST_INT | 29,970,000 | 16.6% | 83.2% |  |
| LOAD_FAST_LOAD_FAST | 29,970,000 | 16.6% | 99.8% |  |
| LOAD_CONST | 61,980 | 0.0% | 99.8% |  |
| LOAD_GLOBAL_BUILTIN | 60,120 | 0.0% | 99.8% |  |
| GET_ITER | 60,120 | 0.0% | 99.9% |  |
| CALL_BUILTIN_CLASS | 60,120 | 0.0% | 99.9% |  |
| BUILD_LIST | 60,120 | 0.0% | 99.9% |  |
| BINARY_OP | 60,040 | 0.0% | 100.0% |  |
| PUSH_NULL | 7,860 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 7,780 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 7,720 | 0.0% | 100.0% |  |
| CALL | 4,060 | 0.0% | 100.0% |  |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,840 | 0.0% | 100.0% |  |
| POP_TOP | 1,980 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 1,920 | 0.0% | 100.0% |  |
| POP_JUMP_IF_FALSE | 1,920 | 0.0% | 100.0% |  |
| COMPARE_OP_INT | 1,920 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 1,920 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 1,920 | 0.0% | 100.0% | 3.1% |
| RETURN_VALUE | 180 | 0.0% | 100.0% |  |
| RESUME_CHECK | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 100 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 40 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| JUMP_BACKWARD FOR_ITER_RANGE | 30,031,920 | 16.6% | 16.6% |
| FOR_ITER_RANGE STORE_FAST | 30,031,920 | 16.6% | 33.2% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 29,970,000 | 16.6% | 49.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 29,970,000 | 16.6% | 66.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 29,970,000 | 16.6% | 83.0% |
| LOAD_FAST STORE_SUBSCR_LIST_INT | 29,970,000 | 16.6% | 99.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 60,120 | 0.0% | 99.6% |
| GET_ITER FOR_ITER_RANGE | 60,120 | 0.0% | 99.6% |
| FOR_ITER_RANGE LOAD_FAST | 60,120 | 0.0% | 99.6% |
| CALL_BUILTIN_CLASS GET_ITER | 60,120 | 0.0% | 99.7% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 60,080 | 0.0% | 99.7% |
| LOAD_FAST CALL_BUILTIN_CLASS | 60,080 | 0.0% | 99.7% |
| STORE_FAST LOAD_CONST | 60,000 | 0.0% | 99.8% |
| STORE_FAST JUMP_BACKWARD | 60,000 | 0.0% | 99.8% |
| LOAD_FAST STORE_FAST | 60,000 | 0.0% | 99.8% |
| LOAD_FAST BINARY_OP | 60,000 | 0.0% | 99.9% |
| LOAD_CONST BUILD_LIST | 60,000 | 0.0% | 99.9% |
| BUILD_LIST LOAD_FAST | 60,000 | 0.0% | 99.9% |
| BINARY_OP STORE_FAST | 60,000 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 7,720 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 7,700 | 0.0% | 100.0% |
| PUSH_NULL CALL | 3,900 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 3,880 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 3,840 | 0.0% | 100.0% |
| PUSH_NULL CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,840 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_MODULE | 1,920 | 0.0% | 100.0% |
| POP_JUMP_IF_NOT_NONE LOAD_FAST | 1,920 | 0.0% | 100.0% |
| POP_JUMP_IF_FALSE JUMP_BACKWARD | 1,920 | 0.0% | 100.0% |
| LOAD_FAST POP_JUMP_IF_NOT_NONE | 1,920 | 0.0% | 100.0% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 1,920 | 0.0% | 100.0% |
| LOAD_FAST LOAD_CONST | 1,920 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 1,920 | 0.0% | 100.0% |
| LOAD_CONST COMPARE_OP_INT | 1,920 | 0.0% | 100.0% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 1,920 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS STORE_FAST | 1,920 | 0.0% | 100.0% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS POP_TOP | 1,920 | 0.0% | 100.0% |
| CALL STORE_FAST | 1,920 | 0.0% | 100.0% |
| CALL LOAD_FAST | 1,920 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT BINARY_OP_ADD_FLOAT | 1,920 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 1,920 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| CALL CALL | 100 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_CONST | 60 | 0.0% | 100.0% |
| RESUME_CHECK BUILD_LIST | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LOAD_CONST STORE_FAST | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| BUILD_LIST STORE_FAST | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 40 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 40 | 0.0% | 100.0% |
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
| CALL_BUILTIN_CLASS | 60,120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 60,120 | 100.0% |


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
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,920 | 97.0% |
| CALL | 60 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 1,920 | 97.0% |
| NOP | 60 | 3.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 7,720 | 98.2% |
| LOAD_DEREF | 120 | 1.5% |
| LOAD_ATTR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 3,900 | 49.6% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 3,840 | 48.9% |
| LOAD_FAST | 120 | 1.5% |


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
| LOAD_FAST | 60,000 | 99.9% |
| BINARY_OP | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60,000 | 99.9% |
| BINARY_OP | 40 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60,000 | 99.8% |
| RESUME_CHECK | 60 | 0.1% |
| LOAD_FAST | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,000 | 99.8% |
| STORE_FAST | 60 | 0.1% |
| LOAD_DEREF | 60 | 0.1% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,900 | 96.1% |
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

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 29,970,000 | 99.8% |
| STORE_FAST | 60,000 | 0.2% |
| POP_JUMP_IF_FALSE | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 30,031,920 | 100.0% |


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
| STORE_FAST | 60,000 | 96.8% |
| LOAD_FAST | 1,920 | 3.1% |
| RESUME_CHECK | 60 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BUILD_LIST | 60,000 | 96.8% |
| COMPARE_OP_INT | 1,920 | 3.1% |
| STORE_FAST | 60 | 0.1% |


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
| LOAD_FAST_LOAD_FAST | 29,970,000 | 99.4% |
| LOAD_GLOBAL_BUILTIN | 60,120 | 0.2% |
| FOR_ITER_RANGE | 60,120 | 0.2% |
| BUILD_LIST | 60,000 | 0.2% |
| STORE_FAST | 3,840 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 29,970,000 | 99.4% |
| CALL_BUILTIN_CLASS | 60,080 | 0.2% |
| STORE_FAST | 60,000 | 0.2% |
| BINARY_OP | 60,000 | 0.2% |
| POP_JUMP_IF_NOT_NONE | 1,920 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 29,970,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,970,000 | 100.0% |


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
| JUMP_BACKWARD | 1,920 | 100.0% |


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
| FOR_ITER_RANGE | 30,031,920 | 99.6% |
| LOAD_FAST | 60,000 | 0.2% |
| BINARY_OP | 60,000 | 0.2% |
| CALL_BUILTIN_FAST_WITH_KEYWORDS | 1,920 | 0.0% |
| CALL | 1,920 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 29,970,000 | 99.4% |
| LOAD_GLOBAL_BUILTIN | 60,080 | 0.2% |
| LOAD_CONST | 60,000 | 0.2% |
| JUMP_BACKWARD | 60,000 | 0.2% |
| LOAD_GLOBAL_MODULE | 3,880 | 0.0% |


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
| LOAD_FAST | 60,080 | 99.9% |
| CALL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60,120 | 100.0% |


</details>

### CALL_BUILTIN_FAST_WITH_KEYWORDS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_FAST_WITH_KEYWORDS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,840 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,920 | 50.0% |
| POP_TOP | 1,920 | 50.0% |


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
| JUMP_BACKWARD | 30,031,920 | 99.8% |
| GET_ITER | 60,120 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 30,031,920 | 99.8% |
| LOAD_FAST | 60,120 | 0.2% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 7,700 | 99.7% |
| LOAD_ATTR | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 7,720 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60,080 | 99.9% |
| LOAD_GLOBAL | 40 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60,120 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,880 | 49.9% |
| POP_TOP | 1,920 | 24.7% |
| LOAD_FAST | 1,920 | 24.7% |
| LOAD_GLOBAL | 40 | 0.5% |
| RETURN_VALUE | 20 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 7,700 | 99.0% |
| LOAD_FAST | 60 | 0.8% |
| LOAD_ATTR | 20 | 0.3% |


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

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 29,970,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 29,970,000 | 100.0% |


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
| specialization.deferred |        60000 | 93.9% |
|          hit |         3780 | 5.9% |
|         miss |           60 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 40 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| multiply different types | 40 | 100.0% |


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
|          hit |     30092040 | 100.0% |


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
| Basic | 90,478,740 | 50.0% |
| Not specialized | 30,100,060 | 16.6% |
| Specialized | 60,207,560 | 33.3% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 60,000 | 93.8% |
| CALL | 3,900 | 6.1% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 60 | 100.0% |
| STORE_SUBSCR_LIST_INT | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RESUME_CHECK | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| NOP | 0 | 0.0% |
| LOAD_GLOBAL_MODULE | 0 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 0 | 0.0% |


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
| Interpreter increfs | 76,648,540 | 99.9% |
| Interpreter decrefs | 63,506,580 | 67.8% |
| Increfs | 89,440 | 0.1% |
| Decrefs | 30,111,860 | 32.2% |
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
| 0 | 60 | 0 | 36,240,200 |
| 1 | 0 | 0 | 0 |
| 2 | 3,840 | 0 | 4,296,737,280 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-09-27
