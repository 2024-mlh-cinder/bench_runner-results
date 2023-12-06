
# Pystats results

- benchmark: nbody
- fork: gvanrossum
- ref: for-iter-uop
- commit hash: 5c5d8bd
- commit date: 2023-11-15T16:14:17-08:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 368,012,600 | 25.6% | 25.6% |  |
| SWAP | 214,401,040 | 14.9% | 40.5% |  |
| COPY | 201,601,560 | 14.0% | 54.6% |  |
| BINARY_OP_MULTIPLY_FLOAT | 140,806,940 | 9.8% | 64.4% |  |
| STORE_SUBSCR_LIST_INT | 107,200,520 | 7.5% | 71.8% |  |
| LOAD_CONST | 102,402,280 | 7.1% | 79.0% |  |
| BINARY_SUBSCR_LIST_INT | 100,800,600 | 7.0% | 86.0% |  |
| BINARY_OP_ADD_FLOAT | 60,803,440 | 4.2% | 90.2% |  |
| STORE_FAST | 56,013,300 | 3.9% | 94.1% |  |
| BINARY_OP_SUBTRACT_FLOAT | 48,005,900 | 3.3% | 97.4% |  |
| ENTER_EXECUTOR | 25,600,440 | 1.8% | 99.2% |  |
| FOR_ITER_LIST | 4,802,480 | 0.3% | 99.6% |  |
| BINARY_OP | 1,606,000 | 0.1% | 99.7% |  |
| UNPACK_SEQUENCE_TUPLE | 1,603,260 | 0.1% | 99.8% |  |
| UNPACK_SEQUENCE_LIST | 1,603,200 | 0.1% | 99.9% |  |
| GET_ITER | 1,600,960 | 0.1% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 7,280 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 5,400 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 2,120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,120 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 680 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 600 | 0.0% | 100.0% |  |
| CALL | 540 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 480 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 480 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 400 | 0.0% | 100.0% |  |
| POP_TOP | 400 | 0.0% | 100.0% |  |
| PUSH_NULL | 400 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 400 | 0.0% | 100.0% |  |
| RESUME_CHECK | 380 | 0.0% | 100.0% |  |
| RETURN_VALUE | 320 | 0.0% | 100.0% |  |
| FOR_ITER | 280 | 0.0% | 100.0% |  |
| LOAD_DEREF | 240 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 240 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 180 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 160 | 0.0% | 100.0% |  |
| RETURN_CONST | 160 | 0.0% | 100.0% |  |
| LOAD_ATTR | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |  |
| RESUME | 100 | 0.0% | 100.0% |  |
| NOP | 80 | 0.0% | 100.0% |  |
| BUILD_LIST | 80 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 80 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 80 | 0.0% | 100.0% |  |
| LIST_EXTEND | 80 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 60 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 132,804,780 | 9.2% | 9.2% |
| LOAD_FAST LOAD_FAST | 132,804,280 | 9.2% | 18.5% |
| SWAP SWAP | 107,200,520 | 7.5% | 25.9% |
| SWAP STORE_SUBSCR_LIST_INT | 107,200,160 | 7.5% | 33.4% |
| LOAD_FAST LOAD_CONST | 100,801,020 | 7.0% | 40.4% |
| COPY COPY | 100,800,780 | 7.0% | 47.4% |
| LOAD_CONST COPY | 100,800,780 | 7.0% | 54.5% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 100,800,600 | 7.0% | 61.5% |
| COPY BINARY_SUBSCR_LIST_INT | 100,800,420 | 7.0% | 68.5% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 83,200,380 | 5.8% | 74.3% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 59,203,200 | 4.1% | 78.4% |
| BINARY_OP_ADD_FLOAT SWAP | 59,200,400 | 4.1% | 82.5% |
| STORE_FAST LOAD_FAST | 49,601,160 | 3.5% | 86.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 48,000,780 | 3.3% | 89.3% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 47,999,940 | 3.3% | 92.6% |
| BINARY_OP_MULTIPLY_FLOAT STORE_FAST | 33,600,240 | 2.3% | 95.0% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 23,999,320 | 1.7% | 96.7% |
| ENTER_EXECUTOR STORE_FAST | 14,399,700 | 1.0% | 97.7% |
| ENTER_EXECUTOR BINARY_OP_MULTIPLY_FLOAT | 6,399,740 | 0.4% | 98.1% |
| STORE_FAST STORE_FAST | 4,802,040 | 0.3% | 98.4% |
| ENTER_EXECUTOR FOR_ITER_LIST | 3,200,180 | 0.2% | 98.7% |
| LOAD_CONST BINARY_OP | 1,601,180 | 0.1% | 98.8% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 1,600,960 | 0.1% | 98.9% |
| STORE_FAST UNPACK_SEQUENCE_LIST | 1,600,900 | 0.1% | 99.0% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TUPLE | 1,600,900 | 0.1% | 99.1% |
| LOAD_FAST GET_ITER | 1,600,880 | 0.1% | 99.2% |
| BINARY_OP BINARY_OP_MULTIPLY_FLOAT | 1,600,780 | 0.1% | 99.3% |
| BINARY_OP_ADD_FLOAT LOAD_CONST | 1,600,720 | 0.1% | 99.4% |
| GET_ITER FOR_ITER_LIST | 1,600,700 | 0.1% | 99.6% |
| UNPACK_SEQUENCE_LIST STORE_FAST | 1,600,640 | 0.1% | 99.7% |
| FOR_ITER_LIST LOAD_FAST | 1,600,400 | 0.1% | 99.8% |
| FOR_ITER_LIST ENTER_EXECUTOR | 1,599,660 | 0.1% | 99.9% |
| ENTER_EXECUTOR BINARY_OP_ADD_FLOAT | 1,599,600 | 0.1% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 5,900 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 5,400 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 3,240 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 2,660 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_LIST STORE_FAST_STORE_FAST | 2,560 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST | 2,400 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,180 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE UNPACK_SEQUENCE_LIST | 2,160 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 1,840 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 1,820 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 1,500 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 1,340 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 1,260 | 0.0% | 100.0% |
| ENTER_EXECUTOR BINARY_OP | 1,140 | 0.0% | 100.0% |
| STORE_FAST UNPACK_SEQUENCE_TUPLE | 1,080 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 1,080 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 1,080 | 0.0% | 100.0% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 1,080 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE UNPACK_SEQUENCE_TUPLE | 1,080 | 0.0% | 100.0% |
| STORE_FAST JUMP_BACKWARD | 1,020 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 880 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 880 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 640 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 640 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 600 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 440 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 440 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 400 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 400 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT BINARY_OP_MULTIPLY_FLOAT | 380 | 0.0% | 100.0% |
| COPY BINARY_SUBSCR | 360 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 360 | 0.0% | 100.0% |
| SWAP STORE_SUBSCR | 360 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP | 360 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 340 | 0.0% | 100.0% |
| FOR_ITER_LIST JUMP_BACKWARD | 340 | 0.0% | 100.0% |
| BINARY_OP LOAD_FAST | 320 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 280 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| STORE_SUBSCR STORE_SUBSCR_LIST_INT | 240 | 0.0% | 100.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 240 | 0.0% | 100.0% |
| STORE_FAST UNPACK_SEQUENCE | 200 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST | 200 | 0.0% | 100.0% |
| BINARY_SUBSCR LOAD_FAST | 180 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR_LIST_INT | 180 | 0.0% | 100.0% |
| BINARY_OP SWAP | 180 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 180 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 160 | 0.0% | 100.0% |
| RETURN_VALUE POP_TOP | 160 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 160 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 160 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 160 | 0.0% | 100.0% |
| RETURN_CONST POP_TOP | 160 | 0.0% | 100.0% |
| UNPACK_SEQUENCE UNPACK_SEQUENCE_TUPLE | 160 | 0.0% | 100.0% |
| GET_ITER FOR_ITER | 140 | 0.0% | 100.0% |
| STORE_SUBSCR LOAD_FAST | 140 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER | 140 | 0.0% | 100.0% |
| UNPACK_SEQUENCE UNPACK_SEQUENCE_LIST | 140 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 120 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL | 120 | 0.0% | 100.0% |
| JUMP_BACKWARD ENTER_EXECUTOR | 120 | 0.0% | 100.0% |
| LOAD_CONST STORE_SUBSCR | 120 | 0.0% | 100.0% |
| LOAD_CONST STORE_SUBSCR_LIST_INT | 120 | 0.0% | 100.0% |
| LOAD_FAST CALL | 120 | 0.0% | 100.0% |
| UNPACK_SEQUENCE STORE_FAST_STORE_FAST | 120 | 0.0% | 100.0% |
| UNPACK_SEQUENCE UNPACK_SEQUENCE | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 120 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 360 | 90.0% |
| LOAD_FAST | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 45.0% |
| BINARY_SUBSCR_LIST_INT | 180 | 45.0% |
| CALL | 20 | 5.0% |
| BINARY_SUBSCR_DICT | 20 | 5.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,600,880 | 100.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,600,700 | 100.0% |
| FOR_ITER | 140 | 0.0% |
| FOR_ITER_RANGE | 120 | 0.0% |


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
| RETURN_VALUE | 160 | 40.0% |
| RETURN_CONST | 160 | 40.0% |
| CALL | 80 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 120 | 30.0% |
| NOP | 80 | 20.0% |
| JUMP_BACKWARD | 80 | 20.0% |
| LOAD_GLOBAL_MODULE | 80 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 10.0% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 180 | 45.0% |
| LOAD_DEREF | 160 | 40.0% |
| LOAD_ATTR | 60 | 15.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 60.0% |
| LOAD_FAST | 160 | 40.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 160 | 50.0% |
| RETURN_VALUE | 80 | 25.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 18.8% |
| BINARY_OP | 20 | 6.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 160 | 50.0% |
| RETURN_VALUE | 80 | 25.0% |
| LOAD_GLOBAL | 40 | 12.5% |
| LOAD_GLOBAL_MODULE | 40 | 12.5% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 360 | 75.0% |
| LOAD_CONST | 120 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 240 | 50.0% |
| LOAD_FAST | 140 | 29.2% |
| JUMP_BACKWARD | 40 | 8.3% |
| LOAD_FAST_LOAD_FAST | 40 | 8.3% |
| RETURN_CONST | 20 | 4.2% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 1,601,180 | 99.7% |
| BINARY_OP | 1,820 | 0.1% |
| ENTER_EXECUTOR | 1,140 | 0.1% |
| LOAD_FAST | 880 | 0.1% |
| LOAD_FAST_LOAD_FAST | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 1,600,780 | 99.7% |
| BINARY_OP_SUBTRACT_FLOAT | 1,840 | 0.1% |
| BINARY_OP | 1,820 | 0.1% |
| BINARY_OP_ADD_FLOAT | 640 | 0.0% |
| LOAD_FAST | 320 | 0.0% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 80 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 44.4% |
| LOAD_FAST | 120 | 22.2% |
| CALL | 60 | 11.1% |
| LOAD_GLOBAL | 40 | 7.4% |
| LOAD_GLOBAL_MODULE | 40 | 7.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 100 | 18.5% |
| POP_TOP | 80 | 14.8% |
| LOAD_FAST | 80 | 14.8% |
| CALL_PY_WITH_DEFAULTS | 80 | 14.8% |
| CALL | 60 | 11.1% |


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
| COPY | 100,800,780 | 50.0% |
| LOAD_CONST | 100,800,780 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 100,800,780 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 100,800,420 | 50.0% |
| BINARY_SUBSCR | 360 | 0.0% |


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
| STORE_SUBSCR_LIST_INT | 23,999,320 | 93.7% |
| FOR_ITER_LIST | 1,599,660 | 6.2% |
| STORE_FAST | 1,340 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 14,399,700 | 56.2% |
| BINARY_OP_MULTIPLY_FLOAT | 6,399,740 | 25.0% |
| FOR_ITER_LIST | 3,200,180 | 12.5% |
| BINARY_OP_ADD_FLOAT | 1,599,600 | 6.2% |
| BINARY_OP | 1,140 | 0.0% |


</details>

### FOR_ITER

<details>
<summary> Successors and predecessors for FOR_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 140 | 50.0% |
| JUMP_BACKWARD | 140 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE | 100 | 35.7% |
| FOR_ITER_LIST | 100 | 35.7% |
| STORE_FAST | 40 | 14.3% |
| FOR_ITER_RANGE | 40 | 14.3% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,020 | 48.1% |
| STORE_SUBSCR_LIST_INT | 640 | 30.2% |
| FOR_ITER_LIST | 340 | 16.0% |
| POP_TOP | 80 | 3.8% |
| STORE_SUBSCR | 40 | 1.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,500 | 70.8% |
| FOR_ITER_RANGE | 360 | 17.0% |
| FOR_ITER | 140 | 6.6% |
| ENTER_EXECUTOR | 120 | 5.7% |


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
| LOAD_FAST | 100,801,020 | 98.4% |
| BINARY_OP_ADD_FLOAT | 1,600,720 | 1.6% |
| BINARY_OP_MULTIPLY_FLOAT | 400 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 100,800,780 | 98.4% |
| BINARY_OP | 1,601,180 | 1.6% |
| STORE_SUBSCR | 120 | 0.0% |
| STORE_SUBSCR_LIST_INT | 120 | 0.0% |
| LOAD_FAST | 80 | 0.0% |


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
| LOAD_FAST | 132,804,280 | 36.1% |
| BINARY_SUBSCR_LIST_INT | 100,800,600 | 27.4% |
| STORE_SUBSCR_LIST_INT | 83,200,380 | 22.6% |
| STORE_FAST | 49,601,160 | 13.5% |
| FOR_ITER_LIST | 1,600,400 | 0.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 132,804,780 | 36.1% |
| LOAD_FAST | 132,804,280 | 36.1% |
| LOAD_CONST | 100,801,020 | 27.4% |
| GET_ITER | 1,600,880 | 0.4% |
| BINARY_OP | 880 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,400 | 74.2% |
| BINARY_OP_MULTIPLY_FLOAT | 880 | 12.1% |
| BINARY_OP_ADD_FLOAT | 440 | 6.0% |
| STORE_FAST_STORE_FAST | 340 | 4.7% |
| STORE_SUBSCR_LIST_INT | 120 | 1.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 3,240 | 44.5% |
| LOAD_FAST | 2,180 | 29.9% |
| BINARY_OP_MULTIPLY_FLOAT | 1,260 | 17.3% |
| BINARY_OP | 600 | 8.2% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 30.0% |
| STORE_FAST | 80 | 20.0% |
| RETURN_VALUE | 40 | 10.0% |
| RESUME | 40 | 10.0% |
| FOR_ITER_RANGE | 40 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 40.0% |
| LOAD_ATTR | 60 | 15.0% |
| LOAD_FAST | 60 | 15.0% |
| CALL | 40 | 10.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 10.0% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 80 | 50.0% |
| STORE_SUBSCR_LIST_INT | 60 | 37.5% |
| STORE_SUBSCR | 20 | 12.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 160 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 33,600,240 | 60.0% |
| ENTER_EXECUTOR | 14,399,700 | 25.7% |
| STORE_FAST | 4,802,040 | 8.6% |
| UNPACK_SEQUENCE_TUPLE | 1,600,960 | 2.9% |
| UNPACK_SEQUENCE_LIST | 1,600,640 | 2.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 49,601,160 | 88.6% |
| STORE_FAST | 4,802,040 | 8.6% |
| UNPACK_SEQUENCE_LIST | 1,600,900 | 2.9% |
| LOAD_FAST_LOAD_FAST | 5,400 | 0.0% |
| ENTER_EXECUTOR | 1,340 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,660 | 49.3% |
| UNPACK_SEQUENCE_LIST | 2,560 | 47.4% |
| UNPACK_SEQUENCE | 120 | 2.2% |
| UNPACK_SEQUENCE_TUPLE | 60 | 1.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,660 | 49.3% |
| STORE_FAST | 2,400 | 44.4% |
| LOAD_FAST_LOAD_FAST | 340 | 6.3% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 107,200,520 | 50.0% |
| BINARY_OP_ADD_FLOAT | 59,200,400 | 27.6% |
| BINARY_OP_SUBTRACT_FLOAT | 47,999,940 | 22.4% |
| BINARY_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 107,200,520 | 50.0% |
| STORE_SUBSCR_LIST_INT | 107,200,160 | 50.0% |
| STORE_SUBSCR | 360 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 200 | 29.4% |
| UNPACK_SEQUENCE | 120 | 17.6% |
| FOR_ITER | 100 | 14.7% |
| FOR_ITER_LIST | 100 | 14.7% |
| UNPACK_SEQUENCE_TUPLE | 80 | 11.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 160 | 23.5% |
| UNPACK_SEQUENCE_LIST | 140 | 20.6% |
| STORE_FAST_STORE_FAST | 120 | 17.6% |
| UNPACK_SEQUENCE | 120 | 17.6% |
| STORE_FAST | 100 | 14.7% |


</details>

### RESUME

<details>
<summary> Successors and predecessors for RESUME </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 60 | 60.0% |
| CALL_FUNCTION_EX | 20 | 20.0% |
| COPY_FREE_VARS | 20 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 40.0% |
| LOAD_GLOBAL | 40 | 40.0% |
| LOAD_DEREF | 20 | 20.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 59,203,200 | 97.4% |
| ENTER_EXECUTOR | 1,599,600 | 2.6% |
| BINARY_OP | 640 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 59,200,400 | 97.4% |
| LOAD_CONST | 1,600,720 | 2.6% |
| LOAD_FAST | 1,080 | 0.0% |
| LOAD_FAST_LOAD_FAST | 440 | 0.0% |
| STORE_FAST | 400 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 132,804,780 | 94.3% |
| ENTER_EXECUTOR | 6,399,740 | 4.5% |
| BINARY_OP | 1,600,780 | 1.1% |
| LOAD_FAST_LOAD_FAST | 1,260 | 0.0% |
| BINARY_OP_ADD_FLOAT | 380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 59,203,200 | 42.0% |
| BINARY_OP_SUBTRACT_FLOAT | 48,000,780 | 34.1% |
| STORE_FAST | 33,600,240 | 23.9% |
| LOAD_FAST | 1,080 | 0.0% |
| LOAD_FAST_LOAD_FAST | 880 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 48,000,780 | 100.0% |
| LOAD_FAST_LOAD_FAST | 3,240 | 0.0% |
| BINARY_OP | 1,840 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 47,999,940 | 100.0% |
| STORE_FAST | 5,900 | 0.0% |
| RETURN_VALUE | 60 | 0.0% |


</details>

### BINARY_SUBSCR_DICT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_DICT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| BINARY_SUBSCR | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 40 | 66.7% |
| CALL | 20 | 33.3% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 100,800,420 | 100.0% |
| BINARY_SUBSCR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,800,600 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80 | 66.7% |
| CALL | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 60 | 50.0% |
| STORE_FAST | 60 | 50.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL | 80 | 33.3% |
| LOAD_GLOBAL_MODULE | 80 | 33.3% |
| LOAD_FAST | 40 | 16.7% |
| BINARY_SUBSCR_DICT | 40 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 100.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 3,200,180 | 66.6% |
| GET_ITER | 1,600,700 | 33.3% |
| JUMP_BACKWARD | 1,500 | 0.0% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,600,900 | 33.3% |
| LOAD_FAST | 1,600,400 | 33.3% |
| ENTER_EXECUTOR | 1,599,660 | 33.3% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,080 | 0.0% |
| JUMP_BACKWARD | 340 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 360 | 60.0% |
| GET_ITER | 120 | 20.0% |
| ENTER_EXECUTOR | 80 | 13.3% |
| FOR_ITER | 40 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 440 | 73.3% |
| RETURN_CONST | 80 | 13.3% |
| LOAD_GLOBAL | 40 | 6.7% |
| LOAD_GLOBAL_MODULE | 40 | 6.7% |


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
| POP_TOP | 40 | 33.3% |
| LOAD_GLOBAL | 40 | 33.3% |
| RESUME_CHECK | 40 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 160 | 33.3% |
| POP_TOP | 80 | 16.7% |
| STORE_FAST | 80 | 16.7% |
| RETURN_VALUE | 40 | 8.3% |
| FOR_ITER_RANGE | 40 | 8.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 120 | 25.0% |
| CALL_PY_WITH_DEFAULTS | 80 | 16.7% |
| LOAD_ATTR | 60 | 12.5% |
| LOAD_CONST | 60 | 12.5% |
| LOAD_FAST | 60 | 12.5% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 240 | 63.2% |
| CALL_FUNCTION_EX | 60 | 15.8% |
| COPY_FREE_VARS | 60 | 15.8% |
| CALL | 20 | 5.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 200 | 52.6% |
| LOAD_DEREF | 60 | 15.8% |
| LOAD_GLOBAL | 40 | 10.5% |
| LOAD_GLOBAL_BUILTIN | 40 | 10.5% |
| LOAD_GLOBAL_MODULE | 40 | 10.5% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 107,200,160 | 100.0% |
| STORE_SUBSCR | 240 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83,200,380 | 77.6% |
| ENTER_EXECUTOR | 23,999,320 | 22.4% |
| JUMP_BACKWARD | 640 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,600,900 | 99.9% |
| UNPACK_SEQUENCE_TUPLE | 2,160 | 0.1% |
| UNPACK_SEQUENCE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,600,640 | 99.8% |
| STORE_FAST_STORE_FAST | 2,560 | 0.2% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,600,900 | 99.9% |
| STORE_FAST | 1,080 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,080 | 0.1% |
| UNPACK_SEQUENCE | 160 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,600,960 | 99.9% |
| UNPACK_SEQUENCE_LIST | 2,160 | 0.1% |
| UNPACK_SEQUENCE | 80 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,080 | 96.4% |
| UNPACK_SEQUENCE | 40 | 3.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,080 | 96.4% |
| UNPACK_SEQUENCE | 40 | 3.6% |


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
|     deferred | 1,604,080 | 0.6% |
|          hit | 249,616,280 | 99.4% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,060 | 55.2% |
| Failure | 860 | 44.8% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| power | 640 | 74.4% |
| true divide float | 220 | 25.6% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 100,800,660 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 360 | 40.0% |
|          hit | 360 | 40.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 120 | 66.7% |
| Failure | 60 | 33.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 140 | 0.0% |
|          hit | 4,803,080 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 140 | 100.0% |
| Failure | 0 | 0.0% |


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
|     deferred | 200 | 20.0% |
|          hit | 600 | 60.0% |

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
|     deferred | 240 | 0.0% |
|          hit | 107,200,520 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 340 | 0.0% |
|          hit | 3,207,580 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 340 | 100.0% |
| Failure | 0 | 0.0% |


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 969,649,160 | 67.5% |
| Not specialized | 1,608,900 | 0.1% |
| Specialized hits | 465,629,640 | 32.4% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 1,604,080 | 99.9% |
| CALL | 360 | 0.0% |
| UNPACK_SEQUENCE | 340 | 0.0% |
| STORE_SUBSCR | 240 | 0.0% |
| BINARY_SUBSCR | 200 | 0.0% |
| LOAD_GLOBAL | 200 | 0.0% |
| FOR_ITER | 140 | 0.0% |
| LOAD_ATTR | 60 | 0.0% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 0 | 0.0% |
| Calls to Python functions inlined | 480 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 160 | 33.3% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 240 | 50.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 264,019,220 | 98.2% |
| Frees to freelist | 264,019,380 |  |
| Allocations | 4,781,380 | 1.8% |
| Allocations to 512 bytes | 4,781,260 | 1.8% |
| Allocations to 4 kbytes | 120 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 4,780,660 |  |
| New values | 0 |  |
| Interpreter increfs | 1,212,872,880 | 99.7% |
| Interpreter decrefs | 1,484,874,920 | 100.0% |
| Increfs | 3,202,880 | 0.3% |
| Decrefs | 1,160 | 0.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 43 |  |
| Method cache misses | 17 |  |
| Method cache collisions | 17 |  |
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
| Optimization attempts | 120 |  |
| Traces created | 120 | 100.0% |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 80 | 66.7% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 25,600,440 |  |
| Uops executed | 1,227,229,480 | 47.94 |

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
| <= 64 | 0 | 0.0% |
| <= 128 | 120 | 100.0% |


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
| <= 32 | 0 | 0.0% |
| <= 64 | 120 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 3,200,060 | 12.5% |
| <= 4 | 80 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 22,400,180 | 87.5% |
| <= 128 | 40 | 0.0% |
| <= 256 | 80 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 267,208,840 | 21.8% | 21.8% |  |
| STORE_FAST | 241,606,780 | 19.7% | 41.5% |  |
| _GUARD_BOTH_FLOAT | 166,406,740 | 13.6% | 55.0% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 75,203,340 | 6.1% | 61.1% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 48,001,500 | 3.9% | 65.1% |  |
| _BINARY_OP_ADD_FLOAT | 43,201,900 | 3.5% | 68.6% |  |
| UNPACK_SEQUENCE_LIST | 38,401,060 | 3.1% | 71.7% |  |
| UNPACK_SEQUENCE_TUPLE | 38,401,060 | 3.1% | 74.8% |  |
| COPY | 38,398,440 | 3.1% | 78.0% |  |
| LOAD_CONST | 33,600,440 | 2.7% | 80.7% |  |
| _SET_IP | 30,399,980 | 2.5% | 83.2% |  |
| _GUARD_NOT_EXHAUSTED_LIST | 25,600,800 | 2.1% | 85.3% | 12.5% |
| _ITER_CHECK_LIST | 25,600,800 | 2.1% | 87.4% |  |
| SWAP | 25,598,960 | 2.1% | 89.4% |  |
| _ITER_NEXT_LIST | 22,400,620 | 1.8% | 91.3% |  |
| _EXIT_TRACE | 22,400,180 | 1.8% | 93.1% |  |
| BINARY_SUBSCR_LIST_INT | 19,199,220 | 1.6% | 94.7% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 16,000,440 | 1.3% | 96.0% |  |
| _CHECK_VALIDITY | 15,998,680 | 1.3% | 97.3% |  |
| _BINARY_OP | 14,401,220 | 1.2% | 98.4% |  |
| STORE_SUBSCR_LIST_INT | 12,799,480 | 1.0% | 99.5% |  |
| _GUARD_NOT_EXHAUSTED_RANGE | 1,599,680 | 0.1% | 99.6% | 0.0% |
| _ITER_CHECK_RANGE | 1,599,680 | 0.1% | 99.7% |  |
| GET_ITER | 1,599,600 | 0.1% | 99.9% |  |
| _ITER_NEXT_RANGE | 1,599,600 | 0.1% | 100.0% |  |
| _JUMP_TO_TOP | 440 | 0.0% | 100.0% |  |


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
