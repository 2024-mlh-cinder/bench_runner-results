
# Pystats results

- benchmark: spectral_norm
- fork: gvanrossum
- ref: split-uops
- commit hash: 8ab398d
- commit date: 2023-10-03T16:05:03-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| BINARY_OP_ADD_INT | 202,800,000 | 17.1% | 17.1% |  |
| LOAD_CONST | 162,552,180 | 13.7% | 30.9% |  |
| LOAD_FAST | 122,636,760 | 10.4% | 41.2% |  |
| LOAD_FAST_LOAD_FAST | 122,007,600 | 10.3% | 51.6% |  |
| BINARY_OP | 82,380,340 | 7.0% | 58.5% |  |
| STORE_FAST | 40,892,040 | 3.5% | 62.0% |  |
| FOR_ITER | 40,889,860 | 3.5% | 65.4% |  |
| JUMP_BACKWARD | 40,880,460 | 3.5% | 68.9% |  |
| STORE_FAST_STORE_FAST | 40,879,860 | 3.5% | 72.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 40,879,800 | 3.5% | 75.8% |  |
| CALL_PY_EXACT_ARGS | 40,878,000 | 3.5% | 79.3% | 0.3% |
| RETURN_VALUE | 40,875,720 | 3.5% | 82.7% |  |
| RESUME_CHECK | 40,875,720 | 3.5% | 86.2% |  |
| BINARY_OP_ADD_FLOAT | 40,575,600 | 3.4% | 89.6% | 0.8% |
| LOAD_GLOBAL_MODULE | 40,566,220 | 3.4% | 93.0% |  |
| BINARY_OP_MULTIPLY_INT | 40,560,000 | 3.4% | 96.5% |  |
| BINARY_OP_MULTIPLY_FLOAT | 39,347,880 | 3.3% | 99.8% | 0.0% |
| LOAD_GLOBAL_BUILTIN | 319,380 | 0.0% | 99.8% |  |
| CALL_BUILTIN_CLASS | 316,920 | 0.0% | 99.8% |  |
| FOR_ITER_RANGE | 315,180 | 0.0% | 99.9% |  |
| GET_ITER | 314,580 | 0.0% | 99.9% |  |
| PUSH_NULL | 312,300 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 312,000 | 0.0% | 99.9% |  |
| LIST_APPEND | 312,000 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 312,000 | 0.0% | 100.0% |  |
| SWAP | 7,200 | 0.0% | 100.0% |  |
| BUILD_LIST | 2,520 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 2,400 | 0.0% | 100.0% |  |
| CALL_LEN | 2,400 | 0.0% | 100.0% |  |
| CALL | 360 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 160 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| POP_TOP | 60 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| COPY | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST_LOAD_FAST BINARY_OP_ADD_INT | 81,120,000 | 6.9% | 6.9% |
| LOAD_CONST BINARY_OP_ADD_INT | 81,120,000 | 6.9% | 13.7% |
| BINARY_OP_ADD_INT LOAD_CONST | 81,120,000 | 6.9% | 20.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 40,879,800 | 3.5% | 24.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 40,875,600 | 3.5% | 27.5% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 40,569,720 | 3.4% | 30.9% |
| STORE_FAST JUMP_BACKWARD | 40,568,400 | 3.4% | 34.3% |
| JUMP_BACKWARD FOR_ITER | 40,567,800 | 3.4% | 37.8% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 40,567,800 | 3.4% | 41.2% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,560,000 | 3.4% | 44.6% |
| RETURN_VALUE LOAD_FAST | 40,560,000 | 3.4% | 48.1% |
| RESUME_CHECK LOAD_CONST | 40,560,000 | 3.4% | 51.5% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 40,560,000 | 3.4% | 54.9% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 40,560,000 | 3.4% | 58.3% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 40,560,000 | 3.4% | 61.8% |
| LOAD_FAST BINARY_OP_ADD_INT | 40,560,000 | 3.4% | 65.2% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 40,560,000 | 3.4% | 68.6% |
| LOAD_CONST BINARY_OP | 40,560,000 | 3.4% | 72.1% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 40,560,000 | 3.4% | 75.5% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 40,560,000 | 3.4% | 78.9% |
| BINARY_OP_ADD_INT BINARY_OP_MULTIPLY_INT | 40,560,000 | 3.4% | 82.3% |
| BINARY_OP_ADD_INT BINARY_OP | 40,560,000 | 3.4% | 85.8% |
| BINARY_OP RETURN_VALUE | 40,560,000 | 3.4% | 89.2% |
| BINARY_OP LOAD_FAST | 40,560,000 | 3.4% | 92.6% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 39,347,820 | 3.3% | 96.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 39,342,120 | 3.3% | 99.3% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 1,233,480 | 0.1% | 99.4% |
| LOAD_FAST BINARY_OP | 1,227,800 | 0.1% | 99.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 314,520 | 0.0% | 99.5% |
| CALL_BUILTIN_CLASS GET_ITER | 314,460 | 0.0% | 99.5% |
| LOAD_FAST CALL_BUILTIN_CLASS | 314,440 | 0.0% | 99.6% |
| JUMP_BACKWARD FOR_ITER_RANGE | 312,660 | 0.0% | 99.6% |
| GET_ITER FOR_ITER | 312,060 | 0.0% | 99.6% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 312,040 | 0.0% | 99.6% |
| STORE_FAST_STORE_FAST LOAD_CONST | 312,000 | 0.0% | 99.7% |
| STORE_FAST_LOAD_FAST PUSH_NULL | 312,000 | 0.0% | 99.7% |
| RETURN_VALUE LIST_APPEND | 312,000 | 0.0% | 99.7% |
| RESUME_CHECK LOAD_FAST | 312,000 | 0.0% | 99.8% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 312,000 | 0.0% | 99.8% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 312,000 | 0.0% | 99.8% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 312,000 | 0.0% | 99.8% |
| LOAD_FAST RETURN_VALUE | 312,000 | 0.0% | 99.9% |
| LOAD_CONST STORE_FAST | 312,000 | 0.0% | 99.9% |
| LIST_APPEND JUMP_BACKWARD | 312,000 | 0.0% | 99.9% |
| FOR_ITER_RANGE STORE_FAST_LOAD_FAST | 312,000 | 0.0% | 99.9% |
| FOR_ITER LOAD_FAST | 312,000 | 0.0% | 100.0% |
| BUILD_TUPLE CALL_PY_EXACT_ARGS | 312,000 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 20,840 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 15,600 | 0.0% | 100.0% |
| FOR_ITER FOR_ITER | 10,000 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 7,800 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 7,800 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 5,940 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT BINARY_OP | 5,880 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP | 5,760 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 4,800 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 3,600 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,440 | 0.0% | 100.0% |
| SWAP STORE_FAST | 2,400 | 0.0% | 100.0% |
| SWAP FOR_ITER_RANGE | 2,400 | 0.0% | 100.0% |
| SWAP BUILD_LIST | 2,400 | 0.0% | 100.0% |
| STORE_FAST RETURN_VALUE | 2,400 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,400 | 0.0% | 100.0% |
| LOAD_FAST_AND_CLEAR SWAP | 2,400 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,400 | 0.0% | 100.0% |
| GET_ITER LOAD_FAST_AND_CLEAR | 2,400 | 0.0% | 100.0% |
| FOR_ITER_RANGE SWAP | 2,400 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS CALL_PY_EXACT_ARGS | 2,400 | 0.0% | 100.0% |
| CALL_LEN CALL_BUILTIN_CLASS | 2,400 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_LEN | 2,400 | 0.0% | 100.0% |
| BUILD_LIST SWAP | 2,400 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 1,260 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,240 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 1,200 | 0.0% | 100.0% |
| RETURN_VALUE CALL_PY_EXACT_ARGS | 1,200 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,200 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 660 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| CALL CALL | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_CONST | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE BINARY_OP | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 60 | 0.0% | 100.0% |
| LOAD_FAST_CHECK CALL | 60 | 0.0% | 100.0% |
| LOAD_FAST LOAD_FAST_CHECK | 60 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 314,460 | 100.0% |
| LOAD_FAST | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 312,060 | 99.2% |
| LOAD_FAST_AND_CLEAR | 2,400 | 0.8% |
| FOR_ITER_RANGE | 120 | 0.0% |


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
| CALL | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 312,000 | 99.9% |
| LOAD_ATTR_MODULE | 160 | 0.1% |
| LOAD_DEREF | 120 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 312,000 | 99.9% |
| CALL | 180 | 0.1% |
| LOAD_FAST | 120 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 40,560,000 | 99.2% |
| LOAD_FAST | 312,000 | 0.8% |
| STORE_FAST | 2,400 | 0.0% |
| RETURN_VALUE | 1,260 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,560,000 | 99.2% |
| LIST_APPEND | 312,000 | 0.8% |
| RETURN_VALUE | 1,260 | 0.0% |
| STORE_FAST | 1,200 | 0.0% |
| CALL_PY_EXACT_ARGS | 1,200 | 0.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,560,000 | 49.2% |
| BINARY_OP_ADD_INT | 40,560,000 | 49.2% |
| LOAD_FAST | 1,227,800 | 1.5% |
| BINARY_OP | 20,840 | 0.0% |
| BINARY_OP_ADD_FLOAT | 5,880 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 40,560,000 | 49.2% |
| LOAD_FAST | 40,560,000 | 49.2% |
| BINARY_OP_ADD_FLOAT | 1,233,480 | 1.5% |
| BINARY_OP | 20,840 | 0.0% |
| STORE_FAST | 5,940 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,400 | 95.2% |
| LOAD_FAST | 60 | 2.4% |
| LOAD_CONST | 60 | 2.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,400 | 95.2% |
| LOAD_DEREF | 60 | 2.4% |
| LOAD_GLOBAL_MODULE | 40 | 1.6% |
| LOAD_GLOBAL | 20 | 0.8% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 312,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 312,000 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 50.0% |
| CALL | 80 | 22.2% |
| LOAD_FAST_CHECK | 60 | 16.7% |
| LOAD_FAST | 20 | 5.6% |
| LOAD_CONST | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 22.2% |
| STORE_FAST | 60 | 16.7% |
| POP_TOP | 60 | 16.7% |
| LOAD_FAST | 60 | 16.7% |
| GET_ITER | 60 | 16.7% |


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

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 60 | 100.0% |


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

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 40,567,800 | 99.2% |
| GET_ITER | 312,060 | 0.8% |
| FOR_ITER | 10,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 40,567,800 | 99.2% |
| LOAD_FAST | 312,000 | 0.8% |
| FOR_ITER | 10,000 | 0.0% |
| JUMP_BACKWARD | 60 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40,568,400 | 99.2% |
| LIST_APPEND | 312,000 | 0.8% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40,567,800 | 99.2% |
| FOR_ITER_RANGE | 312,660 | 0.8% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 312,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 312,000 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 60 | 75.0% |
| LOAD_GLOBAL | 20 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 60 | 75.0% |
| PUSH_NULL | 20 | 25.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 81,120,000 | 49.9% |
| RESUME_CHECK | 40,560,000 | 25.0% |
| BINARY_OP_MULTIPLY_INT | 40,560,000 | 25.0% |
| STORE_FAST_STORE_FAST | 312,000 | 0.2% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 81,120,000 | 49.9% |
| LOAD_FAST_LOAD_FAST | 40,560,000 | 25.0% |
| BINARY_OP | 40,560,000 | 25.0% |
| STORE_FAST | 312,000 | 0.2% |
| COPY | 60 | 0.0% |


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
| STORE_FAST_STORE_FAST | 40,560,000 | 33.1% |
| RETURN_VALUE | 40,560,000 | 33.1% |
| BINARY_OP | 40,560,000 | 33.1% |
| LOAD_GLOBAL_BUILTIN | 314,520 | 0.3% |
| RESUME_CHECK | 312,000 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40,560,000 | 33.1% |
| BINARY_OP_ADD_INT | 40,560,000 | 33.1% |
| BINARY_OP_MULTIPLY_FLOAT | 39,347,820 | 32.1% |
| BINARY_OP | 1,227,800 | 1.0% |
| CALL_BUILTIN_CLASS | 314,440 | 0.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,400 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40,560,000 | 33.2% |
| LOAD_CONST | 40,560,000 | 33.2% |
| BINARY_OP_ADD_INT | 40,560,000 | 33.2% |
| PUSH_NULL | 312,000 | 0.3% |
| STORE_FAST_STORE_FAST | 7,800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 81,120,000 | 66.5% |
| CALL_PY_EXACT_ARGS | 40,560,000 | 33.2% |
| BUILD_TUPLE | 312,000 | 0.3% |
| LOAD_FAST | 15,600 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40 | 25.0% |
| RETURN_VALUE | 40 | 25.0% |
| STORE_FAST_STORE_FAST | 20 | 12.5% |
| RESUME_CHECK | 20 | 12.5% |
| FOR_ITER_RANGE | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 37.5% |
| LOAD_ATTR | 20 | 12.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 40,569,720 | 99.2% |
| LOAD_CONST | 312,000 | 0.8% |
| BINARY_OP | 5,940 | 0.0% |
| SWAP | 2,400 | 0.0% |
| RETURN_VALUE | 1,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 40,568,400 | 99.2% |
| LOAD_GLOBAL_BUILTIN | 312,040 | 0.8% |
| LOAD_FAST_LOAD_FAST | 7,800 | 0.0% |
| RETURN_VALUE | 2,400 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,240 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 312,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 312,000 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 40,879,800 | 100.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,560,000 | 99.2% |
| LOAD_CONST | 312,000 | 0.8% |
| LOAD_FAST_LOAD_FAST | 7,800 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_AND_CLEAR | 2,400 | 33.3% |
| FOR_ITER_RANGE | 2,400 | 33.3% |
| BUILD_LIST | 2,400 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400 | 33.3% |
| FOR_ITER_RANGE | 2,400 | 33.3% |
| BUILD_LIST | 2,400 | 33.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 39,342,120 | 97.0% |
| BINARY_OP | 1,233,480 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 40,569,720 | 100.0% |
| BINARY_OP | 5,880 | 0.0% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 81,120,000 | 40.0% |
| LOAD_CONST | 81,120,000 | 40.0% |
| LOAD_FAST | 40,560,000 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 81,120,000 | 40.0% |
| LOAD_FAST_LOAD_FAST | 40,560,000 | 20.0% |
| BINARY_OP_MULTIPLY_INT | 40,560,000 | 20.0% |
| BINARY_OP | 40,560,000 | 20.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 39,347,820 | 100.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 39,342,120 | 100.0% |
| BINARY_OP | 5,760 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 40,560,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,560,000 | 100.0% |


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
| RETURN_VALUE | 60 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 314,440 | 99.2% |
| CALL_LEN | 2,400 | 0.8% |
| LOAD_CONST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 314,460 | 99.2% |
| CALL_LEN | 2,400 | 0.8% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,400 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,400 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40,560,000 | 99.2% |
| BUILD_TUPLE | 312,000 | 0.8% |
| LOAD_FAST | 2,400 | 0.0% |
| CALL_PY_EXACT_ARGS | 2,400 | 0.0% |
| RETURN_VALUE | 1,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40,875,600 | 100.0% |
| CALL_PY_EXACT_ARGS | 2,400 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 312,660 | 99.2% |
| SWAP | 2,400 | 0.8% |
| GET_ITER | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 312,000 | 99.0% |
| SWAP | 2,400 | 0.8% |
| STORE_FAST | 660 | 0.2% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 62.5% |
| LOAD_ATTR | 60 | 37.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 160 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 312,040 | 97.7% |
| LOAD_GLOBAL_BUILTIN | 4,800 | 1.5% |
| RESUME_CHECK | 2,440 | 0.8% |
| LOAD_GLOBAL | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 314,520 | 98.5% |
| LOAD_GLOBAL_BUILTIN | 4,800 | 1.5% |
| LOAD_CONST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,560,000 | 100.0% |
| LOAD_GLOBAL_MODULE | 3,600 | 0.0% |
| STORE_FAST | 1,240 | 0.0% |
| RESUME_CHECK | 1,200 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40,560,000 | 100.0% |
| LOAD_GLOBAL_MODULE | 3,600 | 0.0% |
| LOAD_FAST | 2,400 | 0.0% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 40,875,600 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,560,000 | 99.2% |
| LOAD_FAST | 312,000 | 0.8% |
| LOAD_GLOBAL_BUILTIN | 2,440 | 0.0% |
| LOAD_GLOBAL_MODULE | 1,200 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40,567,800 | 99.2% |
| LOAD_FAST | 312,000 | 0.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 40,879,800 | 100.0% |


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
| specialization.deferred |     82353720 | 20.3% |
| specialization.deopt |         5940 | 0.0% |
|          hit |    322968240 | 79.6% |
|         miss |       315300 | 0.1% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 5,960 | 18.3% |
| Failure | 26,600 | 81.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide different types | 9,900 | 37.2% |
| floor divide | 9,900 | 37.2% |
| add different types | 5,880 | 22.1% |
| multiply different types | 920 | 3.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          240 | 0.0% |
| specialization.deopt |         2400 | 0.0% |
|          hit |     41070120 | 99.7% |
|         miss |       127200 | 0.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 2,440 | 96.8% |
| Failure | 80 | 3.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 75.0% |
| class no vectorcall | 20 | 25.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     40879860 | 99.2% |
|          hit |       315180 | 0.8% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 10,000 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 9,960 | 99.6% |
| zip | 40 | 0.4% |


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
| specialization.deferred |           20 | 8.3% |
|          hit |          160 | 66.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
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
|          hit |     40885600 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     40879800 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 531,419,880 | 44.9% |
| Not specialized | 164,593,760 | 13.9% |
| Specialized | 486,994,820 | 41.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 82,353,720 | 66.8% |
| FOR_ITER | 40,879,860 | 33.2% |
| CALL | 240 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 312,120 | 70.5% |
| CALL_PY_EXACT_ARGS | 127,200 | 28.7% |
| BINARY_OP_MULTIPLY_FLOAT | 3,180 | 0.7% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| SWAP | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST_LOAD_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RESUME_CHECK | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 40,875,720 | 100.0% |
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
| Frames pushed | 40,875,720 | 100.0% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 42,552,260 | 20.9% |
| Frees to freelist | 42,552,820 |  |
| Allocations | 160,876,300 | 79.1% |
| Allocations to 512 bytes | 160,873,840 | 79.1% |
| Allocations to 4 kbytes | 2,460 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 160,878,080 |  |
| New values | 0 |  |
| Interpreter increfs | 243,284,140 | 75.0% |
| Interpreter decrefs | 486,341,640 | 92.2% |
| Increfs | 81,060,400 | 25.0% |
| Decrefs | 41,428,820 | 7.8% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 15 |  |
| Method cache misses | 5 |  |
| Method cache collisions | 5 |  |
| Method cache dunder hits | 0 |  |
| Method cache dunder misses | 0 |  |


</details>

## GC stats

<details>
<summary> GC collections and effectiveness </summary>

|Generation | Collections | Objects collected | Object visits | 
|---:|---:|---:|---:|
| 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Meta stats

<details>
<summary> Meta statistics </summary>

| | Count | 
|---|---:|
| Number of data files | 20 |


</details>

---
Stats gathered on: 2023-10-04
