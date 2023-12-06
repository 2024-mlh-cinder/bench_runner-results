
# Pystats results

- benchmark: spectral_norm
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 1,886,100 | 14.9% | 14.9% |  |
| BINARY_OP_ADD_INT | 1,464,860 | 11.6% | 26.5% |  |
| BINARY_OP | 1,261,540 | 10.0% | 36.5% |  |
| LOAD_CONST | 1,258,480 | 9.9% | 46.4% |  |
| RETURN_VALUE | 837,600 | 6.6% | 53.0% |  |
| ENTER_EXECUTOR | 832,240 | 6.6% | 59.6% |  |
| LOAD_FAST_LOAD_FAST | 635,580 | 5.0% | 64.6% |  |
| STORE_FAST | 632,860 | 5.0% | 69.6% |  |
| RESUME_CHECK | 424,460 | 3.4% | 73.0% |  |
| CALL_PY_EXACT_ARGS | 424,360 | 3.4% | 76.4% | 0.9% |
| STORE_FAST_STORE_FAST | 420,960 | 3.3% | 79.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 420,780 | 3.3% | 83.0% |  |
| LIST_APPEND | 416,000 | 3.3% | 86.3% |  |
| BINARY_OP_MULTIPLY_FLOAT | 405,300 | 3.2% | 89.5% | 0.8% |
| LOAD_GLOBAL_BUILTIN | 218,340 | 1.7% | 91.2% |  |
| LOAD_GLOBAL_MODULE | 216,540 | 1.7% | 92.9% |  |
| CALL_BUILTIN_CLASS | 215,520 | 1.7% | 94.6% |  |
| GET_ITER | 212,940 | 1.7% | 96.3% |  |
| FOR_ITER | 211,480 | 1.7% | 98.0% |  |
| BINARY_OP_MULTIPLY_INT | 210,540 | 1.7% | 99.7% |  |
| SWAP | 8,760 | 0.1% | 99.7% |  |
| FOR_ITER_RANGE | 6,860 | 0.1% | 99.8% |  |
| BINARY_OP_ADD_FLOAT | 3,520 | 0.0% | 99.8% | 63.6% |
| PUSH_NULL | 3,500 | 0.0% | 99.8% |  |
| BUILD_TUPLE | 3,100 | 0.0% | 99.9% |  |
| STORE_FAST_LOAD_FAST | 3,100 | 0.0% | 99.9% |  |
| BUILD_LIST | 2,940 | 0.0% | 99.9% |  |
| LOAD_FAST_AND_CLEAR | 2,780 | 0.0% | 99.9% |  |
| CALL_LEN | 2,760 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 1,780 | 0.0% | 100.0% |  |
| CALL | 960 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 800 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 200 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| RESUME | 140 | 0.0% | 100.0% |  |
| LOAD_ATTR | 120 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| POP_TOP | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| LOAD_FAST_CHECK | 80 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| BINARY_OP_ADD_INT LOAD_CONST | 627,160 | 5.0% | 5.0% |
| LOAD_CONST BINARY_OP_ADD_INT | 627,120 | 5.0% | 9.9% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 424,280 | 3.4% | 13.3% |
| LOAD_FAST_LOAD_FAST BINARY_OP_ADD_INT | 421,040 | 3.3% | 16.6% |
| UNPACK_SEQUENCE_TWO_TUPLE STORE_FAST_STORE_FAST | 420,780 | 3.3% | 19.9% |
| BINARY_OP RETURN_VALUE | 416,660 | 3.3% | 23.2% |
| RETURN_VALUE LOAD_FAST | 416,640 | 3.3% | 26.5% |
| BINARY_OP LOAD_FAST | 416,640 | 3.3% | 29.8% |
| BINARY_OP_ADD_INT BINARY_OP | 416,640 | 3.3% | 33.1% |
| LOAD_FAST BINARY_OP_ADD_INT | 416,600 | 3.3% | 36.4% |
| STORE_FAST ENTER_EXECUTOR | 416,480 | 3.3% | 39.7% |
| RETURN_VALUE LIST_APPEND | 416,000 | 3.3% | 43.0% |
| ENTER_EXECUTOR LOAD_FAST | 416,000 | 3.3% | 46.3% |
| LOAD_FAST RETURN_VALUE | 416,000 | 3.3% | 49.6% |
| LIST_APPEND ENTER_EXECUTOR | 415,660 | 3.3% | 52.8% |
| BINARY_OP STORE_FAST | 414,040 | 3.3% | 56.1% |
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 405,160 | 3.2% | 59.3% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP | 403,220 | 3.2% | 62.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 212,760 | 1.7% | 64.2% |
| CALL_BUILTIN_CLASS GET_ITER | 212,700 | 1.7% | 65.9% |
| LOAD_FAST CALL_BUILTIN_CLASS | 212,620 | 1.7% | 67.5% |
| FOR_ITER UNPACK_SEQUENCE_TWO_TUPLE | 210,840 | 1.7% | 69.2% |
| LOAD_CONST BINARY_OP | 210,640 | 1.7% | 70.9% |
| LOAD_CONST LOAD_FAST_LOAD_FAST | 210,560 | 1.7% | 72.5% |
| STORE_FAST_STORE_FAST LOAD_FAST | 210,560 | 1.7% | 74.2% |
| BINARY_OP_ADD_INT LOAD_FAST_LOAD_FAST | 210,540 | 1.7% | 75.9% |
| BINARY_OP_MULTIPLY_INT LOAD_CONST | 210,540 | 1.7% | 77.5% |
| RESUME_CHECK LOAD_CONST | 210,540 | 1.7% | 79.2% |
| BINARY_OP_ADD_INT BINARY_OP_MULTIPLY_INT | 210,520 | 1.7% | 80.9% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 210,520 | 1.7% | 82.5% |
| LOAD_FAST LOAD_GLOBAL_MODULE | 210,480 | 1.7% | 84.2% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 210,480 | 1.7% | 85.9% |
| GET_ITER FOR_ITER | 210,040 | 1.7% | 87.5% |
| LOAD_CONST STORE_FAST | 209,920 | 1.7% | 89.2% |
| STORE_FAST_STORE_FAST LOAD_CONST | 209,920 | 1.7% | 90.8% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 209,880 | 1.7% | 92.5% |
| RESUME_CHECK LOAD_FAST | 209,880 | 1.7% | 94.2% |
| LOAD_FAST UNPACK_SEQUENCE_TWO_TUPLE | 209,840 | 1.7% | 95.8% |
| ENTER_EXECUTOR CALL_PY_EXACT_ARGS | 206,820 | 1.6% | 97.5% |
| ENTER_EXECUTOR BINARY_OP | 206,080 | 1.6% | 99.1% |
| BINARY_OP BINARY_OP | 12,400 | 0.1% | 99.2% |
| LOAD_FAST BINARY_OP | 12,360 | 0.1% | 99.3% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 5,480 | 0.0% | 99.3% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 3,480 | 0.0% | 99.3% |
| LOAD_GLOBAL_MODULE LOAD_GLOBAL_MODULE | 3,420 | 0.0% | 99.4% |
| ENTER_EXECUTOR FOR_ITER_RANGE | 3,260 | 0.0% | 99.4% |
| STORE_FAST RETURN_VALUE | 3,200 | 0.0% | 99.4% |
| SWAP STORE_FAST | 3,200 | 0.0% | 99.5% |
| FOR_ITER_RANGE SWAP | 3,200 | 0.0% | 99.5% |
| PUSH_NULL LOAD_FAST_LOAD_FAST | 3,100 | 0.0% | 99.5% |
| LOAD_FAST_LOAD_FAST BUILD_TUPLE | 3,100 | 0.0% | 99.5% |
| STORE_FAST_LOAD_FAST PUSH_NULL | 3,100 | 0.0% | 99.6% |
| FOR_ITER_RANGE STORE_FAST_LOAD_FAST | 3,080 | 0.0% | 99.6% |
| BUILD_TUPLE CALL_PY_EXACT_ARGS | 3,060 | 0.0% | 99.6% |
| GET_ITER LOAD_FAST_AND_CLEAR | 2,780 | 0.0% | 99.6% |
| BUILD_LIST SWAP | 2,780 | 0.0% | 99.6% |
| LOAD_FAST_AND_CLEAR SWAP | 2,780 | 0.0% | 99.7% |
| SWAP BUILD_LIST | 2,780 | 0.0% | 99.7% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 2,780 | 0.0% | 99.7% |
| SWAP FOR_ITER_RANGE | 2,760 | 0.0% | 99.7% |
| CALL_BUILTIN_CLASS CALL_LEN | 2,740 | 0.0% | 99.8% |
| CALL_LEN CALL_BUILTIN_CLASS | 2,740 | 0.0% | 99.8% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 2,300 | 0.0% | 99.8% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 2,240 | 0.0% | 99.8% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 2,080 | 0.0% | 99.8% |
| RETURN_VALUE RETURN_VALUE | 1,680 | 0.0% | 99.8% |
| RETURN_VALUE STORE_FAST | 1,600 | 0.0% | 99.9% |
| RETURN_VALUE CALL_PY_EXACT_ARGS | 1,560 | 0.0% | 99.9% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 1,440 | 0.0% | 99.9% |
| STORE_FAST JUMP_BACKWARD | 1,360 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL_MODULE | 1,140 | 0.0% | 99.9% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 1,140 | 0.0% | 99.9% |
| JUMP_BACKWARD FOR_ITER | 1,020 | 0.0% | 99.9% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 800 | 0.0% | 99.9% |
| JUMP_BACKWARD FOR_ITER_RANGE | 660 | 0.0% | 99.9% |
| FOR_ITER_RANGE STORE_FAST | 420 | 0.0% | 99.9% |
| FOR_ITER FOR_ITER | 400 | 0.0% | 99.9% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 400 | 0.0% | 99.9% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 400 | 0.0% | 99.9% |
| LIST_APPEND JUMP_BACKWARD | 340 | 0.0% | 99.9% |
| LOAD_FAST CALL | 280 | 0.0% | 99.9% |
| PUSH_NULL CALL | 240 | 0.0% | 99.9% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 240 | 0.0% | 99.9% |
| STORE_FAST LOAD_GLOBAL | 240 | 0.0% | 99.9% |
| LOAD_ATTR_MODULE PUSH_NULL | 180 | 0.0% | 99.9% |
| PUSH_NULL LOAD_FAST | 160 | 0.0% | 100.0% |
| CALL GET_ITER | 160 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_FAST | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 160 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_MULTIPLY_FLOAT | 140 | 0.0% | 100.0% |
| CALL CALL_PY_EXACT_ARGS | 140 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 120 | 0.0% | 100.0% |
| CALL CALL | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| FOR_ITER UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_INT | 100 | 0.0% | 100.0% |
| CALL STORE_FAST | 100 | 0.0% | 100.0% |
| JUMP_BACKWARD ENTER_EXECUTOR | 100 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 212,700 | 99.9% |
| CALL | 160 | 0.1% |
| LOAD_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 210,040 | 98.6% |
| LOAD_FAST_AND_CLEAR | 2,780 | 1.3% |
| FOR_ITER_RANGE | 120 | 0.1% |


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
| CALL | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| NOP | 80 | 100.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_LOAD_FAST | 3,100 | 88.6% |
| LOAD_ATTR_MODULE | 180 | 5.1% |
| LOAD_DEREF | 160 | 4.6% |
| LOAD_ATTR | 60 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,100 | 88.6% |
| CALL | 240 | 6.9% |
| LOAD_FAST | 160 | 4.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 416,660 | 49.7% |
| LOAD_FAST | 416,000 | 49.7% |
| STORE_FAST | 3,200 | 0.4% |
| RETURN_VALUE | 1,680 | 0.2% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 416,640 | 49.7% |
| LIST_APPEND | 416,000 | 49.7% |
| RETURN_VALUE | 1,680 | 0.2% |
| STORE_FAST | 1,600 | 0.2% |
| CALL_PY_EXACT_ARGS | 1,560 | 0.2% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 416,640 | 33.0% |
| BINARY_OP_MULTIPLY_FLOAT | 403,220 | 32.0% |
| LOAD_CONST | 210,640 | 16.7% |
| ENTER_EXECUTOR | 206,080 | 16.3% |
| BINARY_OP | 12,400 | 1.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 416,660 | 33.0% |
| LOAD_FAST | 416,640 | 33.0% |
| STORE_FAST | 414,040 | 32.8% |
| BINARY_OP | 12,400 | 1.0% |
| BINARY_OP_ADD_FLOAT | 1,440 | 0.1% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,780 | 94.6% |
| LOAD_CONST | 80 | 2.7% |
| LOAD_FAST | 80 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,780 | 94.6% |
| LOAD_DEREF | 80 | 2.7% |
| LOAD_GLOBAL | 40 | 1.4% |
| LOAD_GLOBAL_MODULE | 40 | 1.4% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 3,100 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,060 | 98.7% |
| CALL | 40 | 1.3% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 280 | 29.2% |
| PUSH_NULL | 240 | 25.0% |
| CALL | 120 | 12.5% |
| LOAD_FAST_CHECK | 80 | 8.3% |
| LOAD_FAST_LOAD_FAST | 80 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 160 | 16.7% |
| CALL_PY_EXACT_ARGS | 140 | 14.6% |
| CALL | 120 | 12.5% |
| CALL_BUILTIN_CLASS | 120 | 12.5% |
| STORE_FAST | 100 | 10.4% |


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

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 80 | 100.0% |


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
| STORE_FAST | 416,480 | 50.0% |
| LIST_APPEND | 415,660 | 49.9% |
| JUMP_BACKWARD | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 416,000 | 50.0% |
| CALL_PY_EXACT_ARGS | 206,820 | 24.9% |
| BINARY_OP | 206,080 | 24.8% |
| FOR_ITER_RANGE | 3,260 | 0.4% |
| JUMP_BACKWARD | 80 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 210,040 | 99.3% |
| JUMP_BACKWARD | 1,020 | 0.5% |
| FOR_ITER | 400 | 0.2% |
| SWAP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 210,840 | 99.7% |
| FOR_ITER | 400 | 0.2% |
| UNPACK_SEQUENCE | 120 | 0.1% |
| FOR_ITER_RANGE | 60 | 0.0% |
| STORE_FAST | 40 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,360 | 76.4% |
| LIST_APPEND | 340 | 19.1% |
| ENTER_EXECUTOR | 80 | 4.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 1,020 | 57.3% |
| FOR_ITER_RANGE | 660 | 37.1% |
| ENTER_EXECUTOR | 100 | 5.6% |


</details>

### LIST_APPEND

<details>
<summary> Successors and predecessors for LIST_APPEND </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 416,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 415,660 | 99.9% |
| JUMP_BACKWARD | 340 | 0.1% |


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
| LOAD_GLOBAL | 60 | 50.0% |
| LOAD_GLOBAL_MODULE | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 60 | 50.0% |
| LOAD_ATTR_MODULE | 60 | 50.0% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 627,160 | 49.8% |
| BINARY_OP_MULTIPLY_INT | 210,540 | 16.7% |
| RESUME_CHECK | 210,540 | 16.7% |
| STORE_FAST_STORE_FAST | 209,920 | 16.7% |
| STORE_FAST | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 627,120 | 49.8% |
| BINARY_OP | 210,640 | 16.7% |
| LOAD_FAST_LOAD_FAST | 210,560 | 16.7% |
| STORE_FAST | 209,920 | 16.7% |
| BUILD_LIST | 80 | 0.0% |


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
| RETURN_VALUE | 416,640 | 22.1% |
| BINARY_OP | 416,640 | 22.1% |
| ENTER_EXECUTOR | 416,000 | 22.1% |
| LOAD_GLOBAL_BUILTIN | 212,760 | 11.3% |
| STORE_FAST_STORE_FAST | 210,560 | 11.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 416,600 | 22.1% |
| RETURN_VALUE | 416,000 | 22.1% |
| BINARY_OP_MULTIPLY_FLOAT | 405,160 | 21.5% |
| CALL_BUILTIN_CLASS | 212,620 | 11.3% |
| LOAD_GLOBAL_MODULE | 210,480 | 11.2% |


</details>

### LOAD_FAST_AND_CLEAR

<details>
<summary> Successors and predecessors for LOAD_FAST_AND_CLEAR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,780 | 100.0% |


</details>

### LOAD_FAST_CHECK

<details>
<summary> Successors and predecessors for LOAD_FAST_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 100.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 210,560 | 33.1% |
| BINARY_OP_ADD_INT | 210,540 | 33.1% |
| LOAD_GLOBAL_MODULE | 210,520 | 33.1% |
| PUSH_NULL | 3,100 | 0.5% |
| STORE_FAST | 400 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 421,040 | 66.2% |
| CALL_PY_EXACT_ARGS | 210,480 | 33.1% |
| BUILD_TUPLE | 3,100 | 0.5% |
| LOAD_FAST | 800 | 0.1% |
| BINARY_OP | 80 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 30.0% |
| LOAD_GLOBAL | 100 | 12.5% |
| LOAD_FAST | 80 | 10.0% |
| RESUME | 60 | 7.5% |
| LOAD_GLOBAL_MODULE | 60 | 7.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 240 | 30.0% |
| LOAD_FAST | 160 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 160 | 20.0% |
| LOAD_GLOBAL | 100 | 12.5% |
| LOAD_ATTR | 60 | 7.5% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 414,040 | 65.4% |
| LOAD_CONST | 209,920 | 33.2% |
| BINARY_OP_ADD_FLOAT | 3,480 | 0.5% |
| SWAP | 3,200 | 0.5% |
| RETURN_VALUE | 1,600 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 416,480 | 65.8% |
| LOAD_GLOBAL_BUILTIN | 209,880 | 33.2% |
| RETURN_VALUE | 3,200 | 0.5% |
| JUMP_BACKWARD | 1,360 | 0.2% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.2% |


</details>

### STORE_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 3,080 | 99.4% |
| FOR_ITER | 20 | 0.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 3,100 | 100.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TWO_TUPLE | 420,780 | 100.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |
| COPY | 80 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 210,560 | 50.0% |
| LOAD_CONST | 209,920 | 49.9% |
| LOAD_FAST_LOAD_FAST | 400 | 0.1% |
| LOAD_GLOBAL | 40 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 3,200 | 36.5% |
| BUILD_LIST | 2,780 | 31.7% |
| LOAD_FAST_AND_CLEAR | 2,780 | 31.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,200 | 36.5% |
| BUILD_LIST | 2,780 | 31.7% |
| FOR_ITER_RANGE | 2,760 | 31.5% |
| FOR_ITER | 20 | 0.2% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 120 | 60.0% |
| LOAD_FAST | 80 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 100 | 50.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 100 | 50.0% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 57.1% |
| CALL_FUNCTION_EX | 20 | 14.3% |
| COPY_FREE_VARS | 20 | 14.3% |
| CALL_PY_EXACT_ARGS | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 60 | 42.9% |
| LOAD_FAST | 40 | 28.6% |
| LOAD_CONST | 20 | 14.3% |
| LOAD_DEREF | 20 | 14.3% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 2,080 | 59.1% |
| BINARY_OP | 1,440 | 40.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,480 | 98.9% |
| BINARY_OP | 40 | 1.1% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 627,120 | 42.8% |
| LOAD_FAST_LOAD_FAST | 421,040 | 28.7% |
| LOAD_FAST | 416,600 | 28.4% |
| BINARY_OP | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 627,160 | 42.8% |
| BINARY_OP | 416,640 | 28.4% |
| LOAD_FAST_LOAD_FAST | 210,540 | 14.4% |
| BINARY_OP_MULTIPLY_INT | 210,520 | 14.4% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 405,160 | 100.0% |
| BINARY_OP | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 403,220 | 99.5% |
| BINARY_OP_ADD_FLOAT | 2,080 | 0.5% |


</details>

### BINARY_OP_MULTIPLY_INT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 210,520 | 100.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 210,540 | 100.0% |


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
| LOAD_FAST | 212,620 | 98.7% |
| CALL_LEN | 2,740 | 1.3% |
| CALL | 120 | 0.1% |
| LOAD_CONST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 212,700 | 98.7% |
| CALL_LEN | 2,740 | 1.3% |
| STORE_FAST | 60 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,740 | 99.3% |
| CALL | 20 | 0.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,740 | 99.3% |
| CALL | 20 | 0.7% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 210,480 | 49.6% |
| ENTER_EXECUTOR | 206,820 | 48.7% |
| BUILD_TUPLE | 3,060 | 0.7% |
| LOAD_FAST | 2,240 | 0.5% |
| RETURN_VALUE | 1,560 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 424,280 | 100.0% |
| CALL_PY_EXACT_ARGS | 60 | 0.0% |
| RESUME | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,260 | 47.5% |
| SWAP | 2,760 | 40.2% |
| JUMP_BACKWARD | 660 | 9.6% |
| GET_ITER | 120 | 1.7% |
| FOR_ITER | 60 | 0.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 3,200 | 46.6% |
| STORE_FAST_LOAD_FAST | 3,080 | 44.9% |
| STORE_FAST | 420 | 6.1% |
| LOAD_CONST | 80 | 1.2% |
| LOAD_GLOBAL | 40 | 0.6% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 66.7% |
| LOAD_ATTR | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 209,880 | 96.1% |
| LOAD_GLOBAL_BUILTIN | 5,480 | 2.5% |
| RESUME_CHECK | 2,780 | 1.3% |
| LOAD_GLOBAL | 160 | 0.1% |
| STORE_FAST_STORE_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 212,760 | 97.4% |
| LOAD_GLOBAL_BUILTIN | 5,480 | 2.5% |
| LOAD_CONST | 60 | 0.0% |
| LOAD_GLOBAL | 40 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 210,480 | 97.2% |
| LOAD_GLOBAL_MODULE | 3,420 | 1.6% |
| STORE_FAST | 1,140 | 0.5% |
| RESUME_CHECK | 1,140 | 0.5% |
| LOAD_GLOBAL | 240 | 0.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 210,520 | 97.2% |
| LOAD_GLOBAL_MODULE | 3,420 | 1.6% |
| LOAD_FAST | 2,300 | 1.1% |
| LOAD_ATTR_MODULE | 120 | 0.1% |
| BINARY_OP | 60 | 0.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 424,280 | 100.0% |
| CALL | 60 | 0.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 210,540 | 49.6% |
| LOAD_FAST | 209,880 | 49.4% |
| LOAD_GLOBAL_BUILTIN | 2,780 | 0.7% |
| LOAD_GLOBAL_MODULE | 1,140 | 0.3% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER | 210,840 | 50.1% |
| LOAD_FAST | 209,840 | 49.9% |
| UNPACK_SEQUENCE | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 420,780 | 100.0% |


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
|     deferred | 1,259,560 | 37.6% |
|          hit | 2,078,860 | 62.1% |
|         miss | 5,420 | 0.2% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 360 | 18.2% |
| Failure | 1,620 | 81.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add different types | 520 | 32.1% |
| multiply different types | 500 | 30.9% |
| floor divide | 300 | 18.5% |
| true divide different types | 300 | 18.5% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 540 | 0.1% |
|          hit | 638,940 | 99.3% |
|         miss | 3,700 | 0.6% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 81.0% |
| Failure | 80 | 19.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 75.0% |
| class no vectorcall | 20 | 25.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 211,020 | 96.6% |
|          hit | 6,860 | 3.1% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 13.0% |
| Failure | 400 | 87.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| enumerate | 340 | 85.0% |
| zip | 60 | 15.0% |


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 60 | 20.0% |
|          hit | 180 | 60.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> specialization stats for LOAD_GLOBAL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 400 | 0.1% |
|          hit | 434,880 | 99.8% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 400 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 100 | 0.0% |
|          hit | 420,780 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 100 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 7,159,820 | 56.6% |
| Not specialized | 1,475,100 | 11.7% |
| Specialized hits | 4,004,960 | 31.7% |
| Specialized misses | 9,120 | 0.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 1,259,560 | 85.6% |
| FOR_ITER | 211,020 | 14.3% |
| CALL | 540 | 0.0% |
| LOAD_GLOBAL | 400 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| BINARY_OP_INPLACE_ADD_UNICODE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 3,700 | 40.6% |
| BINARY_OP_MULTIPLY_FLOAT | 3,180 | 34.9% |
| BINARY_OP_ADD_FLOAT | 2,240 | 24.6% |
| GET_ITER | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| BUILD_LIST | 0 | 0.0% |
| BUILD_TUPLE | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 424,600 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 54,497,020 | 12,834.9% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 81,940,240 | 27.6% |
| Frees to freelist | 81,943,500 |  |
| Allocations | 214,503,820 | 72.4% |
| Allocations to 512 bytes | 214,500,460 | 72.4% |
| Allocations to 4 kbytes | 3,360 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 214,503,580 |  |
| New values | 0 |  |
| Interpreter increfs | 325,210,960 | 75.1% |
| Interpreter decrefs | 674,493,640 | 92.4% |
| Increfs | 108,080,900 | 24.9% |
| Decrefs | 55,238,660 | 7.6% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 36 |  |
| Method cache misses | 24 |  |
| Method cache collisions | 24 |  |
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

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 100 |  |
| Traces created | 100 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 40 | 40.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 832,240 |  |
| Uops executed | 3,293,740,220 | 3,957.68 |

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
| <= 32 | 0 | 0.0% |
| <= 64 | 20 | 20.0% |
| <= 128 | 80 | 80.0% |


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
| <= 16 | 0 | 0.0% |
| <= 32 | 20 | 20.0% |
| <= 64 | 40 | 40.0% |
| <= 128 | 40 | 40.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 3,260 | 0.4% |
| <= 8 | 0 | 0.0% |
| <= 16 | 206,400 | 24.8% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 206,500 | 24.8% |
| <= 256 | 0 | 0.0% |
| <= 512 | 0 | 0.0% |
| <= 1,024 | 0 | 0.0% |
| <= 2,048 | 0 | 0.0% |
| <= 4,096 | 80 | 0.0% |
| <= 8,192 | 416,000 | 50.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 620,448,680 | 18.8% | 18.8% |  |
| LOAD_FAST | 486,124,920 | 14.8% | 33.6% |  |
| _GUARD_BOTH_INT | 322,804,480 | 9.8% | 43.4% |  |
| _BINARY_OP_ADD_INT | 268,935,040 | 8.2% | 51.6% |  |
| LOAD_CONST | 215,477,760 | 6.5% | 58.1% |  |
| _CHECK_VALIDITY | 162,652,720 | 4.9% | 63.0% |  |
| STORE_FAST | 162,473,800 | 4.9% | 68.0% |  |
| _BINARY_OP | 134,158,400 | 4.1% | 72.0% |  |
| _GUARD_BOTH_FLOAT | 80,535,040 | 2.4% | 74.5% |  |
| _FOR_ITER_TIER_TWO | 54,295,520 | 1.6% | 76.1% |  |
| _CHECK_FUNCTION_EXACT_ARGS | 54,283,180 | 1.6% | 77.8% | 0.4% |
| _CHECK_PEP_523 | 54,283,180 | 1.6% | 79.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 54,085,520 | 1.6% | 81.1% |  |
| _GUARD_GLOBALS_VERSION | 54,078,880 | 1.6% | 82.7% |  |
| RESUME_CHECK | 54,076,360 | 1.6% | 84.4% |  |
| _CHECK_STACK_SPACE | 54,076,360 | 1.6% | 86.0% |  |
| _INIT_CALL_PY_EXACT_ARGS | 54,076,360 | 1.6% | 87.6% |  |
| _PUSH_FRAME | 54,076,360 | 1.6% | 89.3% |  |
| _SAVE_RETURN_OFFSET | 54,076,360 | 1.6% | 90.9% |  |
| _LOAD_GLOBAL_MODULE | 53,871,540 | 1.6% | 92.6% |  |
| _BINARY_OP_MULTIPLY_INT | 53,869,440 | 1.6% | 94.2% |  |
| _BINARY_OP_ADD_FLOAT | 53,683,360 | 1.6% | 95.8% |  |
| _JUMP_TO_TOP | 53,673,360 | 1.6% | 97.5% |  |
| _POP_FRAME | 53,663,360 | 1.6% | 99.1% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 26,851,680 | 0.8% | 99.9% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 416,580 | 0.0% | 99.9% | 0.8% |
| _ITER_CHECK_RANGE | 416,580 | 0.0% | 99.9% |  |
| _ITER_NEXT_RANGE | 413,320 | 0.0% | 99.9% |  |
| PUSH_NULL | 412,900 | 0.0% | 100.0% |  |
| BUILD_TUPLE | 412,900 | 0.0% | 100.0% |  |
| _GUARD_BUILTINS_VERSION | 207,340 | 0.0% | 100.0% |  |
| _LOAD_GLOBAL_BUILTINS | 207,340 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 206,920 | 0.0% | 100.0% |  |
| GET_ITER | 206,500 | 0.0% | 100.0% |  |
| _EXIT_TRACE | 206,080 | 0.0% | 100.0% |  |
| SWAP | 840 | 0.0% | 100.0% |  |
| BUILD_LIST | 420 | 0.0% | 100.0% |  |
| LOAD_FAST_AND_CLEAR | 420 | 0.0% | 100.0% |  |
| CALL_LEN | 420 | 0.0% | 100.0% |  |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>


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
Stats gathered on: 2023-11-16
