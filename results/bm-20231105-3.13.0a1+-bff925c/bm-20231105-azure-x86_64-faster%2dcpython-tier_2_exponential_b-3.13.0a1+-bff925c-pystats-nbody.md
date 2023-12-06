
# Pystats results

- benchmark: nbody
- fork: faster-cpython
- ref: tier-2-exponential-backoff
- commit hash: bff925c
- commit date: 2023-11-05T04:03:22+00:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 275,215,160 | 23.7% | 23.7% |  |
| SWAP | 201,601,440 | 17.4% | 41.1% |  |
| COPY | 172,802,000 | 14.9% | 56.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 100,808,480 | 8.7% | 64.7% |  |
| STORE_SUBSCR_LIST_INT | 100,800,720 | 8.7% | 73.4% |  |
| LOAD_CONST | 86,402,820 | 7.4% | 80.8% |  |
| BINARY_SUBSCR_LIST_INT | 86,400,820 | 7.4% | 88.3% |  |
| BINARY_OP_ADD_FLOAT | 52,803,860 | 4.6% | 92.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 48,004,500 | 4.1% | 97.0% |  |
| ENTER_EXECUTOR | 19,199,600 | 1.7% | 98.6% |  |
| STORE_FAST | 9,613,120 | 0.8% | 99.4% |  |
| UNPACK_SEQUENCE_TUPLE | 1,603,080 | 0.1% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 1,603,020 | 0.1% | 99.7% |  |
| FOR_ITER_LIST | 1,602,180 | 0.1% | 99.9% |  |
| GET_ITER | 1,600,940 | 0.1% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 6,920 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 5,120 | 0.0% | 100.0% |  |
| BINARY_OP | 4,620 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 2,000 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,060 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 680 | 0.0% | 100.0% |  |
| CALL | 540 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 500 | 0.0% | 100.0% |  |
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
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 100,805,780 | 8.7% | 8.7% |
| SWAP SWAP | 100,800,720 | 8.7% | 17.4% |
| SWAP STORE_SUBSCR_LIST_INT | 100,800,360 | 8.7% | 26.1% |
| LOAD_FAST LOAD_FAST | 86,405,640 | 7.4% | 33.5% |
| LOAD_FAST LOAD_CONST | 86,401,240 | 7.4% | 41.0% |
| COPY COPY | 86,401,000 | 7.4% | 48.4% |
| LOAD_CONST COPY | 86,401,000 | 7.4% | 55.9% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 86,400,820 | 7.4% | 63.3% |
| COPY BINARY_SUBSCR_LIST_INT | 86,400,640 | 7.4% | 70.8% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 83,200,340 | 7.2% | 77.9% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 52,803,240 | 4.6% | 82.5% |
| BINARY_OP_ADD_FLOAT SWAP | 52,800,600 | 4.6% | 87.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 48,000,720 | 4.1% | 91.2% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 47,999,940 | 4.1% | 95.3% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 17,599,600 | 1.5% | 96.8% |
| ENTER_EXECUTOR LOAD_FAST | 15,999,960 | 1.4% | 98.2% |
| STORE_FAST STORE_FAST | 4,801,920 | 0.4% | 98.6% |
| STORE_FAST LOAD_FAST | 3,202,700 | 0.3% | 98.9% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 1,600,900 | 0.1% | 99.0% |
| LOAD_FAST GET_ITER | 1,600,860 | 0.1% | 99.2% |
| STORE_FAST UNPACK_SEQUENCE_LIST | 1,600,840 | 0.1% | 99.3% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TUPLE | 1,600,840 | 0.1% | 99.4% |
| GET_ITER FOR_ITER_LIST | 1,600,680 | 0.1% | 99.6% |
| UNPACK_SEQUENCE_LIST STORE_FAST | 1,600,600 | 0.1% | 99.7% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 1,599,680 | 0.1% | 99.9% |
| ENTER_EXECUTOR STORE_FAST | 1,599,620 | 0.1% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 5,120 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 4,500 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 3,060 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 2,520 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_LIST STORE_FAST_STORE_FAST | 2,420 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST | 2,280 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,060 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE UNPACK_SEQUENCE_LIST | 2,040 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT STORE_FAST | 1,920 | 0.0% | 100.0% |
| LOAD_CONST BINARY_OP | 1,500 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 1,400 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 1,260 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 1,200 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_MULTIPLY_FLOAT | 1,140 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_CONST | 1,060 | 0.0% | 100.0% |
| STORE_FAST UNPACK_SEQUENCE_TUPLE | 1,020 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 1,020 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 1,020 | 0.0% | 100.0% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 1,020 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE UNPACK_SEQUENCE_TUPLE | 1,020 | 0.0% | 100.0% |
| STORE_FAST JUMP_BACKWARD | 960 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP | 880 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 840 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 680 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 620 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 600 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT JUMP_BACKWARD | 600 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 420 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 420 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 380 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 380 | 0.0% | 100.0% |
| COPY BINARY_SUBSCR | 360 | 0.0% | 100.0% |
| SWAP STORE_SUBSCR | 360 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT BINARY_OP_MULTIPLY_FLOAT | 360 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP | 360 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 340 | 0.0% | 100.0% |
| BINARY_OP LOAD_FAST | 320 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 320 | 0.0% | 100.0% |
| BINARY_OP STORE_FAST | 280 | 0.0% | 100.0% |
| ENTER_EXECUTOR JUMP_BACKWARD | 260 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| STORE_SUBSCR STORE_SUBSCR_LIST_INT | 240 | 0.0% | 100.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 240 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 200 | 0.0% | 100.0% |
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
| FOR_ITER_LIST LOAD_FAST | 160 | 0.0% | 100.0% |
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
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 120 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |
| CALL STORE_FAST | 100 | 0.0% | 100.0% |


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
| LOAD_FAST | 1,600,860 | 100.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,600,680 | 100.0% |
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
| LOAD_CONST | 1,500 | 32.5% |
| BINARY_OP | 1,260 | 27.3% |
| LOAD_FAST | 880 | 19.0% |
| LOAD_FAST_LOAD_FAST | 600 | 13.0% |
| BINARY_OP_MULTIPLY_FLOAT | 360 | 7.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 1,260 | 27.3% |
| BINARY_OP_MULTIPLY_FLOAT | 1,140 | 24.7% |
| BINARY_OP_SUBTRACT_FLOAT | 680 | 14.7% |
| BINARY_OP_ADD_FLOAT | 620 | 13.4% |
| LOAD_FAST | 320 | 6.9% |


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
| COPY | 86,401,000 | 50.0% |
| LOAD_CONST | 86,401,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 86,401,000 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 86,400,640 | 50.0% |
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
| STORE_SUBSCR_LIST_INT | 17,599,600 | 91.7% |
| ENTER_EXECUTOR | 1,599,680 | 8.3% |
| STORE_FAST | 200 | 0.0% |
| JUMP_BACKWARD | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 15,999,960 | 83.3% |
| ENTER_EXECUTOR | 1,599,680 | 8.3% |
| STORE_FAST | 1,599,620 | 8.3% |
| JUMP_BACKWARD | 260 | 0.0% |
| RETURN_CONST | 80 | 0.0% |


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
| STORE_FAST | 960 | 48.0% |
| STORE_SUBSCR_LIST_INT | 600 | 30.0% |
| ENTER_EXECUTOR | 260 | 13.0% |
| POP_TOP | 80 | 4.0% |
| FOR_ITER_LIST | 60 | 3.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,400 | 70.0% |
| FOR_ITER_RANGE | 340 | 17.0% |
| FOR_ITER | 140 | 7.0% |
| ENTER_EXECUTOR | 120 | 6.0% |


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
| LOAD_FAST | 86,401,240 | 100.0% |
| BINARY_OP_ADD_FLOAT | 1,060 | 0.0% |
| BINARY_OP_MULTIPLY_FLOAT | 380 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 86,401,000 | 100.0% |
| BINARY_OP | 1,500 | 0.0% |
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
| LOAD_FAST | 86,405,640 | 31.4% |
| BINARY_SUBSCR_LIST_INT | 86,400,820 | 31.4% |
| STORE_SUBSCR_LIST_INT | 83,200,340 | 30.2% |
| ENTER_EXECUTOR | 15,999,960 | 5.8% |
| STORE_FAST | 3,202,700 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 100,805,780 | 36.6% |
| LOAD_FAST | 86,405,640 | 31.4% |
| LOAD_CONST | 86,401,240 | 31.4% |
| GET_ITER | 1,600,860 | 0.6% |
| BINARY_OP | 880 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 5,120 | 74.0% |
| BINARY_OP_MULTIPLY_FLOAT | 840 | 12.1% |
| BINARY_OP_ADD_FLOAT | 420 | 6.1% |
| STORE_FAST_STORE_FAST | 320 | 4.6% |
| STORE_SUBSCR_LIST_INT | 120 | 1.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_SUBTRACT_FLOAT | 3,060 | 44.2% |
| LOAD_FAST | 2,060 | 29.8% |
| BINARY_OP_MULTIPLY_FLOAT | 1,200 | 17.3% |
| BINARY_OP | 600 | 8.7% |


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
| ENTER_EXECUTOR | 80 | 50.0% |
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
| STORE_FAST | 4,801,920 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 1,600,900 | 16.7% |
| UNPACK_SEQUENCE_LIST | 1,600,600 | 16.7% |
| ENTER_EXECUTOR | 1,599,620 | 16.6% |
| BINARY_OP_SUBTRACT_FLOAT | 4,500 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,801,920 | 50.0% |
| LOAD_FAST | 3,202,700 | 33.3% |
| UNPACK_SEQUENCE_LIST | 1,600,840 | 16.7% |
| LOAD_FAST_LOAD_FAST | 5,120 | 0.1% |
| UNPACK_SEQUENCE_TUPLE | 1,020 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,520 | 49.2% |
| UNPACK_SEQUENCE_LIST | 2,420 | 47.3% |
| UNPACK_SEQUENCE | 120 | 2.3% |
| UNPACK_SEQUENCE_TUPLE | 60 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 2,520 | 49.2% |
| STORE_FAST | 2,280 | 44.5% |
| LOAD_FAST_LOAD_FAST | 320 | 6.2% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 100,800,720 | 50.0% |
| BINARY_OP_ADD_FLOAT | 52,800,600 | 26.2% |
| BINARY_OP_SUBTRACT_FLOAT | 47,999,940 | 23.8% |
| BINARY_OP | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 100,800,720 | 50.0% |
| STORE_SUBSCR_LIST_INT | 100,800,360 | 50.0% |
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
| BINARY_OP_MULTIPLY_FLOAT | 52,803,240 | 100.0% |
| BINARY_OP | 620 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 52,800,600 | 100.0% |
| LOAD_CONST | 1,060 | 0.0% |
| LOAD_FAST | 1,020 | 0.0% |
| LOAD_FAST_LOAD_FAST | 420 | 0.0% |
| STORE_FAST | 380 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 100,805,780 | 100.0% |
| LOAD_FAST_LOAD_FAST | 1,200 | 0.0% |
| BINARY_OP | 1,140 | 0.0% |
| BINARY_OP_ADD_FLOAT | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 52,803,240 | 52.4% |
| BINARY_OP_SUBTRACT_FLOAT | 48,000,720 | 47.6% |
| STORE_FAST | 1,920 | 0.0% |
| LOAD_FAST | 1,020 | 0.0% |
| LOAD_FAST_LOAD_FAST | 840 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 48,000,720 | 100.0% |
| LOAD_FAST_LOAD_FAST | 3,060 | 0.0% |
| BINARY_OP | 680 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 47,999,940 | 100.0% |
| STORE_FAST | 4,500 | 0.0% |
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
| COPY | 86,400,640 | 100.0% |
| BINARY_SUBSCR | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 86,400,820 | 100.0% |


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
| GET_ITER | 1,600,680 | 99.9% |
| JUMP_BACKWARD | 1,400 | 0.1% |
| FOR_ITER | 100 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,600,840 | 99.9% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,020 | 0.1% |
| LOAD_FAST | 160 | 0.0% |
| UNPACK_SEQUENCE | 100 | 0.0% |
| JUMP_BACKWARD | 60 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 340 | 68.0% |
| GET_ITER | 120 | 24.0% |
| FOR_ITER | 40 | 8.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 420 | 84.0% |
| LOAD_GLOBAL | 40 | 8.0% |
| LOAD_GLOBAL_MODULE | 40 | 8.0% |


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
| SWAP | 100,800,360 | 100.0% |
| STORE_SUBSCR | 240 | 0.0% |
| LOAD_CONST | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 83,200,340 | 82.5% |
| ENTER_EXECUTOR | 17,599,600 | 17.5% |
| JUMP_BACKWARD | 600 | 0.0% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,600,840 | 99.9% |
| UNPACK_SEQUENCE_TUPLE | 2,040 | 0.1% |
| UNPACK_SEQUENCE | 140 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,600,600 | 99.8% |
| STORE_FAST_STORE_FAST | 2,420 | 0.2% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,600,840 | 99.9% |
| STORE_FAST | 1,020 | 0.1% |
| UNPACK_SEQUENCE_TWO_TUPLE | 1,020 | 0.1% |
| UNPACK_SEQUENCE | 160 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,600,900 | 99.9% |
| UNPACK_SEQUENCE_LIST | 2,040 | 0.1% |
| UNPACK_SEQUENCE | 80 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,020 | 96.2% |
| UNPACK_SEQUENCE | 40 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,020 | 96.2% |
| UNPACK_SEQUENCE | 40 | 3.8% |


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
|     deferred | 3,240 | 0.0% |
|          hit | 201,616,840 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 1,060 | 76.8% |
| Failure | 320 | 23.2% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide float | 180 | 56.2% |
| power | 140 | 43.8% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 200 | 0.0% |
|          hit | 86,400,880 | 100.0% |

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
|          hit | 1,602,680 | 100.0% |

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
|          hit | 100,800,720 | 100.0% |

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
|          hit | 3,207,160 | 100.0% |

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
| Basic | 766,451,300 | 66.1% |
| Not specialized | 7,520 | 0.0% |
| Specialized hits | 393,629,800 | 33.9% |
| Specialized misses | 0 | 0.0% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 3,240 | 67.8% |
| CALL | 360 | 7.5% |
| UNPACK_SEQUENCE | 340 | 7.1% |
| STORE_SUBSCR | 240 | 5.0% |
| BINARY_SUBSCR | 200 | 4.2% |
| LOAD_GLOBAL | 200 | 4.2% |
| FOR_ITER | 140 | 2.9% |
| LOAD_ATTR | 60 | 1.3% |
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
| Interpreter increfs | 1,206,472,100 | 99.7% |
| Interpreter decrefs | 1,478,474,080 | 100.0% |
| Increfs | 3,202,820 | 0.3% |
| Decrefs | 1,160 | 0.0% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 39 |  |
| Method cache misses | 21 |  |
| Method cache collisions | 21 |  |
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
| Trace too long | 40 | 33.3% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |
| Traces executed | 19,199,600 |  |
| Uops executed | 1,960,040,500 | 102.09 |

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
| <= 64 | 20 | 16.7% |
| <= 128 | 100 | 83.3% |


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
| <= 64 | 40 | 33.3% |
| <= 128 | 80 | 66.7% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,600,060 | 8.3% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 15,999,340 | 83.3% |
| <= 256 | 120 | 0.0% |
| <= 512 | 1,599,960 | 8.3% |
| <= 1,024 | 120 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 430,410,740 | 22.0% | 22.0% |  |
| LOAD_FAST | 360,007,000 | 18.4% | 40.3% |  |
| STORE_FAST | 288,007,520 | 14.7% | 55.0% |  |
| _GUARD_BOTH_FLOAT | 214,406,180 | 10.9% | 66.0% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 115,201,800 | 5.9% | 71.8% |  |
| COPY | 67,198,000 | 3.4% | 75.3% |  |
| _BINARY_OP_ADD_FLOAT | 51,201,480 | 2.6% | 77.9% |  |
| LOAD_CONST | 49,599,900 | 2.5% | 80.4% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 48,002,900 | 2.4% | 82.9% |  |
| UNPACK_SEQUENCE_LIST | 38,401,240 | 2.0% | 84.8% |  |
| UNPACK_SEQUENCE_TUPLE | 38,401,240 | 2.0% | 86.8% |  |
| SWAP | 38,398,560 | 2.0% | 88.7% |  |
| BINARY_SUBSCR_LIST_INT | 33,599,000 | 1.7% | 90.4% |  |
| _POP_JUMP_IF_TRUE | 27,200,620 | 1.4% | 91.8% |  |
| _ITER_CHECK_LIST | 25,600,920 | 1.3% | 93.1% |  |
| _IS_ITER_EXHAUSTED_LIST | 25,600,920 | 1.3% | 94.4% |  |
| _ITER_NEXT_LIST | 22,400,740 | 1.1% | 95.6% |  |
| _EXIT_TRACE | 19,199,600 | 1.0% | 96.6% |  |
| STORE_SUBSCR_LIST_INT | 19,199,280 | 1.0% | 97.6% |  |
| _BINARY_OP | 16,002,060 | 0.8% | 98.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 16,000,500 | 0.8% | 99.2% |  |
| _JUMP_TO_TOP | 6,401,400 | 0.3% | 99.5% |  |
| POP_TOP | 3,200,260 | 0.2% | 99.7% |  |
| _ITER_CHECK_RANGE | 1,599,700 | 0.1% | 99.8% |  |
| _IS_ITER_EXHAUSTED_RANGE | 1,599,700 | 0.1% | 99.8% |  |
| GET_ITER | 1,599,620 | 0.1% | 99.9% |  |
| _ITER_NEXT_RANGE | 1,599,620 | 0.1% | 100.0% |  |


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
Stats gathered on: 2023-11-08
