
# Pystats results

- benchmark: spectral_norm
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 3f2d583
- commit date: 2023-10-04T16:12:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| BINARY_OP_ADD_INT | 202,800,000 | 17.2% | 17.2% |  |
| LOAD_CONST | 162,397,380 | 13.8% | 31.0% |  |
| LOAD_FAST | 122,325,900 | 10.4% | 41.3% |  |
| LOAD_FAST_LOAD_FAST | 121,697,580 | 10.3% | 51.6% |  |
| BINARY_OP | 82,380,340 | 7.0% | 58.6% |  |
| FOR_ITER | 40,889,860 | 3.5% | 62.1% |  |
| RETURN_VALUE | 40,875,720 | 3.5% | 65.6% |  |
| STORE_FAST | 40,736,820 | 3.5% | 69.0% |  |
| STORE_FAST_STORE_FAST | 40,725,060 | 3.5% | 72.5% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 40,725,000 | 3.5% | 75.9% |  |
| RESUME_CHECK | 40,720,080 | 3.5% | 79.4% |  |
| CALL_PY_EXACT_ARGS | 40,720,000 | 3.5% | 82.8% | 0.0% |
| BINARY_OP_ADD_FLOAT | 40,575,600 | 3.4% | 86.3% | 0.8% |
| JUMP_BACKWARD | 40,568,000 | 3.4% | 89.7% |  |
| LOAD_GLOBAL_MODULE | 40,564,120 | 3.4% | 93.1% |  |
| BINARY_OP_MULTIPLY_INT | 40,560,000 | 3.4% | 96.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 39,347,880 | 3.3% | 99.9% | 0.0% |
| ENTER_EXECUTOR | 312,480 | 0.0% | 99.9% |  |
| LIST_APPEND | 312,000 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 163,320 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 161,280 | 0.0% | 100.0% |  |
| GET_ITER | 159,360 | 0.0% | 100.0% |  |
| SWAP | 6,360 | 0.0% | 100.0% |  |
| PUSH_NULL | 2,280 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 2,280 | 0.0% | 100.0% |  |
| BUILD_LIST | 2,100 | 0.0% | 100.0% |  |
| STORE_FAST_LOAD_FAST | 1,980 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 1,980 | 0.0% | 100.0% |  |
| CALL_LEN | 1,980 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 1,980 | 0.0% | 100.0% |  |
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
| LOAD_CONST BINARY_OP_ADD_INT | 81,120,000 | 6.9% | 13.8% |
| BINARY_OP_ADD_INT LOAD_CONST | 81,120,000 | 6.9% | 20.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 40,725,000 | 3.5% | 24.1% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 40,719,960 | 3.5% | 27.5% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 40,569,720 | 3.4% | 31.0% |
| STORE_FAST JUMP_BACKWARD | 40,567,940 | 3.4% | 34.4% |
| JUMP_BACKWARD FOR_ITER | 40,567,800 | 3.4% | 37.8% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 40,567,800 | 3.4% | 41.3% |
| STORE_FAST_STORE_FAST LOAD_FAST | 40,560,000 | 3.4% | 44.7% |
| RETURN_VALUE LOAD_FAST | 40,560,000 | 3.4% | 48.2% |
| RESUME_CHECK LOAD_CONST | 40,560,000 | 3.4% | 51.6% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 40,560,000 | 3.4% | 55.0% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 40,560,000 | 3.4% | 58.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 40,560,000 | 3.4% | 61.9% |
| LOAD_FAST BINARY_OP_ADD_INT | 40,560,000 | 3.4% | 65.4% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 40,560,000 | 3.4% | 68.8% |
| LOAD_CONST BINARY_OP | 40,560,000 | 3.4% | 72.2% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 40,560,000 | 3.4% | 75.7% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 40,560,000 | 3.4% | 79.1% |
| BINARY_OP_ADD_INT BINARY_OP_MULTIPLY_INT | 40,560,000 | 3.4% | 82.5% |
| BINARY_OP_ADD_INT BINARY_OP | 40,560,000 | 3.4% | 86.0% |
| BINARY_OP RETURN_VALUE | 40,560,000 | 3.4% | 89.4% |
| BINARY_OP LOAD_FAST | 40,560,000 | 3.4% | 92.9% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 39,347,820 | 3.3% | 96.2% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 39,342,120 | 3.3% | 99.5% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 1,233,480 | 0.1% | 99.6% |
| LOAD_FAST BINARY_OP | 1,227,800 | 0.1% | 99.7% |
| RETURN_VALUE LIST_APPEND | 312,000 | 0.0% | 99.8% |
| LOAD_FAST RETURN_VALUE | 312,000 | 0.0% | 99.8% |
| LIST_APPEND ENTER_EXECUTOR | 312,000 | 0.0% | 99.8% |
| FOR_ITER LOAD_FAST | 312,000 | 0.0% | 99.8% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 159,300 | 0.0% | 99.9% |
| CALL_BUILTIN_CLASS GET_ITER | 159,240 | 0.0% | 99.9% |
| LOAD_FAST CALL_BUILTIN_CLASS | 159,220 | 0.0% | 99.9% |
| GET_ITER FOR_ITER | 157,260 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 157,240 | 0.0% | 99.9% |
| STORE_FAST_STORE_FAST LOAD_CONST | 157,200 | 0.0% | 99.9% |
| RESUME_CHECK LOAD_FAST | 157,200 | 0.0% | 99.9% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 157,200 | 0.0% | 99.9% |
| LOAD_CONST STORE_FAST | 157,200 | 0.0% | 100.0% |
| ENTER_EXECUTOR CALL_PY_EXACT_ARGS | 155,220 | 0.0% | 100.0% |
| ENTER_EXECUTOR FOR_ITER | 154,800 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 20,840 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 15,600 | 0.0% | 100.0% |
| FOR_ITER FOR_ITER | 10,000 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 7,800 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 7,800 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 5,940 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT BINARY_OP | 5,880 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP | 5,760 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 3,960 | 0.0% | 100.0% |
| SWAP STORE_FAST | 2,400 | 0.0% | 100.0% |
| STORE_FAST RETURN_VALUE | 2,400 | 0.0% | 100.0% |
| ENTER_EXECUTOR SWAP | 2,400 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 2,340 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,020 | 0.0% | 100.0% |
| SWAP FOR_ITER_RANGE | 1,980 | 0.0% | 100.0% |
| SWAP BUILD_LIST | 1,980 | 0.0% | 100.0% |
| STORE_FAST_LOAD_FAST PUSH_NULL | 1,980 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 1,980 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 1,980 | 0.0% | 100.0% |
| LOAD_FAST_AND_CLEAR SWAP | 1,980 | 0.0% | 100.0% |
| GET_ITER LOAD_FAST_AND_CLEAR | 1,980 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST_LOAD_FAST | 1,980 | 0.0% | 100.0% |
| CALL_LEN CALL_BUILTIN_CLASS | 1,980 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_LEN | 1,980 | 0.0% | 100.0% |
| BUILD_TUPLE CALL_PY_EXACT_ARGS | 1,980 | 0.0% | 100.0% |
| BUILD_LIST SWAP | 1,980 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 1,560 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 1,560 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 1,260 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 1,200 | 0.0% | 100.0% |
| RETURN_VALUE CALL_PY_EXACT_ARGS | 1,200 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 820 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 780 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 460 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 240 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 180 | 0.0% | 100.0% |
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


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 159,240 | 99.9% |
| LOAD_FAST | 60 | 0.0% |
| CALL | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 157,260 | 98.7% |
| LOAD_FAST_AND_CLEAR | 1,980 | 1.2% |
| FOR_ITER_RANGE | 120 | 0.1% |


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
| STORE_FAST_LOAD_FAST | 1,980 | 86.8% |
| LOAD_ATTR_MODULE | 160 | 7.0% |
| LOAD_DEREF | 120 | 5.3% |
| LOAD_ATTR | 20 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,980 | 86.8% |
| CALL | 180 | 7.9% |
| LOAD_FAST | 120 | 5.3% |


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
| SWAP | 1,980 | 94.3% |
| LOAD_FAST | 60 | 2.9% |
| LOAD_CONST | 60 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,980 | 94.3% |
| LOAD_DEREF | 60 | 2.9% |
| LOAD_GLOBAL_MODULE | 40 | 1.9% |
| LOAD_GLOBAL | 20 | 1.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 1,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 1,980 | 100.0% |


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

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LIST_APPEND | 312,000 | 99.8% |
| STORE_FAST | 460 | 0.1% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 155,220 | 49.7% |
| FOR_ITER | 154,800 | 49.5% |
| SWAP | 2,400 | 0.8% |
| LOAD_CONST | 60 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 40,567,800 | 99.2% |
| GET_ITER | 157,260 | 0.4% |
| ENTER_EXECUTOR | 154,800 | 0.4% |
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
| STORE_FAST | 40,567,940 | 100.0% |
| FOR_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40,567,800 | 100.0% |
| FOR_ITER_RANGE | 180 | 0.0% |
| ENTER_EXECUTOR | 20 | 0.0% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 312,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 312,000 | 100.0% |


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
| BINARY_OP_ADD_INT | 81,120,000 | 50.0% |
| RESUME_CHECK | 40,560,000 | 25.0% |
| BINARY_OP_MULTIPLY_INT | 40,560,000 | 25.0% |
| STORE_FAST_STORE_FAST | 157,200 | 0.1% |
| STORE_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 81,120,000 | 50.0% |
| LOAD_FAST_LOAD_FAST | 40,560,000 | 25.0% |
| BINARY_OP | 40,560,000 | 25.0% |
| STORE_FAST | 157,200 | 0.1% |
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
| STORE_FAST_STORE_FAST | 40,560,000 | 33.2% |
| RETURN_VALUE | 40,560,000 | 33.2% |
| BINARY_OP | 40,560,000 | 33.2% |
| FOR_ITER | 312,000 | 0.3% |
| LOAD_GLOBAL_BUILTIN | 159,300 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40,560,000 | 33.2% |
| BINARY_OP_ADD_INT | 40,560,000 | 33.2% |
| BINARY_OP_MULTIPLY_FLOAT | 39,347,820 | 32.2% |
| BINARY_OP | 1,227,800 | 1.0% |
| RETURN_VALUE | 312,000 | 0.3% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 1,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,980 | 100.0% |


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
| LOAD_GLOBAL_MODULE | 40,560,000 | 33.3% |
| LOAD_CONST | 40,560,000 | 33.3% |
| BINARY_OP_ADD_INT | 40,560,000 | 33.3% |
| STORE_FAST_STORE_FAST | 7,800 | 0.0% |
| STORE_FAST | 7,800 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 81,120,000 | 66.7% |
| CALL_PY_EXACT_ARGS | 40,560,000 | 33.3% |
| LOAD_FAST | 15,600 | 0.0% |
| BUILD_TUPLE | 1,980 | 0.0% |


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
| BINARY_OP_ADD_FLOAT | 40,569,720 | 99.6% |
| LOAD_CONST | 157,200 | 0.4% |
| BINARY_OP | 5,940 | 0.0% |
| SWAP | 2,400 | 0.0% |
| RETURN_VALUE | 1,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 40,567,940 | 99.6% |
| LOAD_GLOBAL_BUILTIN | 157,240 | 0.4% |
| LOAD_FAST_LOAD_FAST | 7,800 | 0.0% |
| RETURN_VALUE | 2,400 | 0.0% |
| LOAD_GLOBAL_MODULE | 820 | 0.0% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 1,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 1,980 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 40,725,000 | 100.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,560,000 | 99.6% |
| LOAD_CONST | 157,200 | 0.4% |
| LOAD_FAST_LOAD_FAST | 7,800 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,400 | 37.7% |
| LOAD_FAST_AND_CLEAR | 1,980 | 31.1% |
| BUILD_LIST | 1,980 | 31.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,400 | 37.7% |
| FOR_ITER_RANGE | 1,980 | 31.1% |
| BUILD_LIST | 1,980 | 31.1% |


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
| LOAD_FAST | 159,220 | 98.7% |
| CALL_LEN | 1,980 | 1.2% |
| LOAD_CONST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 159,240 | 98.7% |
| CALL_LEN | 1,980 | 1.2% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,980 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 1,980 | 100.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40,560,000 | 99.6% |
| ENTER_EXECUTOR | 155,220 | 0.4% |
| BUILD_TUPLE | 1,980 | 0.0% |
| LOAD_FAST | 1,560 | 0.0% |
| RETURN_VALUE | 1,200 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 40,719,960 | 100.0% |
| CALL_PY_EXACT_ARGS | 40 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 1,980 | 86.8% |
| JUMP_BACKWARD | 180 | 7.9% |
| GET_ITER | 120 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 1,980 | 86.8% |
| STORE_FAST | 240 | 10.5% |
| LOAD_GLOBAL_MODULE | 40 | 1.8% |
| LOAD_GLOBAL | 20 | 0.9% |


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
| STORE_FAST | 157,240 | 96.3% |
| LOAD_GLOBAL_BUILTIN | 3,960 | 2.4% |
| RESUME_CHECK | 2,020 | 1.2% |
| LOAD_GLOBAL | 60 | 0.0% |
| STORE_FAST_STORE_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 159,300 | 97.5% |
| LOAD_GLOBAL_BUILTIN | 3,960 | 2.4% |
| LOAD_CONST | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40,560,000 | 100.0% |
| LOAD_GLOBAL_MODULE | 2,340 | 0.0% |
| STORE_FAST | 820 | 0.0% |
| RESUME_CHECK | 780 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40,560,000 | 100.0% |
| LOAD_GLOBAL_MODULE | 2,340 | 0.0% |
| LOAD_FAST | 1,560 | 0.0% |
| LOAD_ATTR_MODULE | 100 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 40,719,960 | 100.0% |
| COPY_FREE_VARS | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 40,560,000 | 99.6% |
| LOAD_FAST | 157,200 | 0.4% |
| LOAD_GLOBAL_BUILTIN | 2,020 | 0.0% |
| LOAD_GLOBAL_MODULE | 780 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 40,567,800 | 99.6% |
| LOAD_FAST | 157,200 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 40,725,000 | 100.0% |


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
| specialization.deopt |           40 | 0.0% |
|          hit |     40881000 | 100.0% |
|         miss |         2260 | 0.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 50.0% |
| Failure | 80 | 50.0% |

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
| specialization.deferred |     40879860 | 100.0% |
|          hit |         2280 | 0.0% |

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
|          hit |     40727440 | 100.0% |

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
|          hit |     40725000 | 100.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 529,559,700 | 44.9% |
| Not specialized | 164,156,360 | 13.9% |
| Specialized | 486,024,200 | 41.2% |

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
| BINARY_OP_ADD_FLOAT | 312,120 | 98.3% |
| BINARY_OP_MULTIPLY_FLOAT | 3,180 | 1.0% |
| CALL_PY_EXACT_ARGS | 2,260 | 0.7% |
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
| Calls to Python functions inlined | 40,720,080 | 100.0% |
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
| Frames pushed | 40,875,720 | 100.4% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 42,552,260 | 20.9% |
| Frees to freelist | 42,552,820 |  |
| Allocations | 160,876,320 | 79.1% |
| Allocations to 512 bytes | 160,873,840 | 79.1% |
| Allocations to 4 kbytes | 2,480 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 160,878,080 |  |
| New values | 0 |  |
| Interpreter increfs | 242,352,760 | 74.6% |
| Interpreter decrefs | 485,873,100 | 92.0% |
| Increfs | 82,304,340 | 25.4% |
| Decrefs | 42,209,860 | 8.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 12 |  |
| Method cache misses | 8 |  |
| Method cache collisions | 8 |  |
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

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 2,386,360 |  |
| Traces created | 20 | 0.0% |
| Traces executed | 312,480 |  |
| Uops executed | 8,566,500 | 27 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 20 |  |
| Inner loop found | 0 |  |
| Recursive call | 0 |  |


</details>

**Trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 20 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 20 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,460 | 0.8% |
| <= 16 | 154,800 | 49.5% |
| <= 32 | 0 | 0.0% |
| <= 64 | 154,800 | 49.5% |
| <= 128 | 420 | 0.1% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 2,026,980 | 23.7% | 23.7% |
| LOAD_FAST | 1,240,920 | 14.5% | 38.1% |
| STORE_FAST | 774,840 | 9.0% | 47.2% |
| _POP_JUMP_IF_TRUE | 312,900 | 3.7% | 50.8% |
| _ITER_CHECK_RANGE | 312,900 | 3.7% | 54.5% |
| _IS_ITER_EXHAUSTED_RANGE | 312,900 | 3.7% | 58.2% |
| _CHECK_PEP_523 | 310,860 | 3.6% | 61.8% |
| _CHECK_FUNCTION_EXACT_ARGS | 310,860 | 3.6% | 65.4% |
| _ITER_NEXT_RANGE | 310,440 | 3.6% | 69.0% |
| PUSH_NULL | 310,020 | 3.6% | 72.7% |
| BUILD_TUPLE | 310,020 | 3.6% | 76.3% |
| _GUARD_GLOBALS_VERSION | 158,160 | 1.8% | 78.1% |
| _EXIT_TRACE | 157,260 | 1.8% | 80.0% |
| _LOAD_GLOBAL_BUILTINS | 156,060 | 1.8% | 81.8% |
| _GUARD_BUILTINS_VERSION | 156,060 | 1.8% | 83.6% |
| _SAVE_CURRENT_IP | 155,640 | 1.8% | 85.4% |
| _PUSH_FRAME | 155,640 | 1.8% | 87.2% |
| _INIT_CALL_PY_EXACT_ARGS | 155,640 | 1.8% | 89.0% |
| _CHECK_STACK_SPACE | 155,640 | 1.8% | 90.9% |
| RESUME_CHECK | 155,640 | 1.8% | 92.7% |
| CALL_BUILTIN_CLASS | 155,640 | 1.8% | 94.5% |
| GET_ITER | 155,220 | 1.8% | 96.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 154,800 | 1.8% | 98.1% |
| LOAD_CONST | 154,800 | 1.8% | 99.9% |
| POP_TOP | 2,460 | 0.0% | 100.0% |
| _LOAD_GLOBAL_MODULE | 2,100 | 0.0% | 100.0% |
| SWAP | 840 | 0.0% | 100.0% |
| LOAD_FAST_AND_CLEAR | 420 | 0.0% | 100.0% |
| CALL_LEN | 420 | 0.0% | 100.0% |
| BUILD_LIST | 420 | 0.0% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER | 2,386,340 |


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
Stats gathered on: 2023-10-04
