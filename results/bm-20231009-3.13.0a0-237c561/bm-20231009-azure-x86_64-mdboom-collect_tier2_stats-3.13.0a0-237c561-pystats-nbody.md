
# Pystats results

- benchmark: nbody
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 237c561
- commit date: 2023-10-09T13:50:19-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 206,404,340 | 23.7% | 23.7% |  |
| SWAP | 151,200,000 | 17.4% | 41.1% |  |
| COPY | 129,600,000 | 14.9% | 56.0% |  |
| BINARY_OP_MULTIPLY_FLOAT | 75,602,440 | 8.7% | 64.7% |  |
| STORE_SUBSCR_LIST_INT | 75,600,180 | 8.7% | 73.4% |  |
| LOAD_CONST | 64,800,640 | 7.4% | 80.8% |  |
| BINARY_SUBSCR_LIST_INT | 64,800,000 | 7.4% | 88.3% |  |
| BINARY_OP_ADD_FLOAT | 39,601,020 | 4.6% | 92.8% |  |
| BINARY_OP_SUBTRACT_FLOAT | 36,001,440 | 4.1% | 97.0% |  |
| ENTER_EXECUTOR | 14,400,240 | 1.7% | 98.6% |  |
| STORE_FAST | 7,203,720 | 0.8% | 99.4% |  |
| UNPACK_SEQUENCE_TUPLE | 1,200,880 | 0.1% | 99.6% |  |
| UNPACK_SEQUENCE_LIST | 1,200,820 | 0.1% | 99.7% |  |
| FOR_ITER_LIST | 1,200,700 | 0.1% | 99.9% |  |
| GET_ITER | 1,200,480 | 0.1% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 1,980 | 0.0% | 100.0% |  |
| STORE_FAST_STORE_FAST | 1,260 | 0.0% | 100.0% |  |
| BINARY_OP | 800 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 460 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 440 | 0.0% | 100.0% |  |
| CALL | 360 | 0.0% | 100.0% |  |
| RESUME_CHECK | 360 | 0.0% | 100.0% |  |
| POP_TOP | 300 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| RETURN_VALUE | 240 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 220 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 180 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| RETURN_CONST | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 20 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 75,601,800 | 8.7% | 8.7% |
| SWAP SWAP | 75,600,000 | 8.7% | 17.4% |
| SWAP STORE_SUBSCR_LIST_INT | 75,600,000 | 8.7% | 26.1% |
| LOAD_FAST LOAD_FAST | 64,801,340 | 7.4% | 33.5% |
| LOAD_FAST LOAD_CONST | 64,800,180 | 7.4% | 41.0% |
| COPY COPY | 64,800,000 | 7.4% | 48.4% |
| COPY BINARY_SUBSCR_LIST_INT | 64,800,000 | 7.4% | 55.9% |
| LOAD_CONST COPY | 64,800,000 | 7.4% | 63.3% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 64,800,000 | 7.4% | 70.8% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 62,400,000 | 7.2% | 77.9% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 39,600,800 | 4.6% | 82.5% |
| BINARY_OP_ADD_FLOAT SWAP | 39,600,000 | 4.6% | 87.0% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 36,000,720 | 4.1% | 91.2% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 36,000,000 | 4.1% | 95.3% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 13,200,000 | 1.5% | 96.8% |
| ENTER_EXECUTOR LOAD_FAST | 12,000,240 | 1.4% | 98.2% |
| STORE_FAST STORE_FAST | 3,600,660 | 0.4% | 98.6% |
| STORE_FAST LOAD_FAST | 2,400,460 | 0.3% | 98.9% |
| STORE_FAST UNPACK_SEQUENCE_LIST | 1,200,460 | 0.1% | 99.0% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TUPLE | 1,200,460 | 0.1% | 99.2% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 1,200,460 | 0.1% | 99.3% |
| LOAD_FAST GET_ITER | 1,200,420 | 0.1% | 99.4% |
| GET_ITER FOR_ITER_LIST | 1,200,360 | 0.1% | 99.6% |
| UNPACK_SEQUENCE_LIST STORE_FAST | 1,200,220 | 0.1% | 99.7% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 1,200,000 | 0.1% | 99.9% |
| ENTER_EXECUTOR STORE_FAST | 1,199,940 | 0.1% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 1,380 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 1,260 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 900 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 600 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_LIST STORE_FAST_STORE_FAST | 600 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 540 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST | 420 | 0.0% | 100.0% |
| LOAD_CONST BINARY_OP | 400 | 0.0% | 100.0% |
| STORE_FAST JUMP_BACKWARD | 380 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 360 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE UNPACK_SEQUENCE_LIST | 360 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 340 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 280 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 280 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 240 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 240 | 0.0% | 100.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 240 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 220 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 220 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT BINARY_OP_MULTIPLY_FLOAT | 220 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 220 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 200 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 200 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| BINARY_OP LOAD_FAST | 180 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 180 | 0.0% | 100.0% |
| STORE_FAST UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_CONST | 180 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT STORE_FAST | 180 | 0.0% | 100.0% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST | 180 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 160 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 140 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 120 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| RETURN_VALUE POP_TOP | 120 | 0.0% | 100.0% |
| LOAD_CONST STORE_SUBSCR_LIST_INT | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 120 | 0.0% | 100.0% |
| RETURN_CONST POP_TOP | 120 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 120 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| CALL CALL_PY_WITH_DEFAULTS | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL_PY_WITH_DEFAULTS | 80 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| STORE_SUBSCR STORE_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_MULTIPLY_FLOAT | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| CALL CALL | 60 | 0.0% | 100.0% |
| CALL LOAD_FAST | 60 | 0.0% | 100.0% |
| CALL STORE_FAST | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| ENTER_EXECUTOR RETURN_CONST | 60 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_RANGE | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 60 | 0.0% | 100.0% |
| LOAD_CONST STORE_SUBSCR | 60 | 0.0% | 100.0% |
| LOAD_CONST LOAD_FAST | 60 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_DICT | 20 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200,420 | 100.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,200,360 | 100.0% |
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
| RETURN_VALUE | 120 | 40.0% |
| RETURN_CONST | 120 | 40.0% |
| CALL | 60 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 26.7% |
| NOP | 60 | 20.0% |
| JUMP_BACKWARD | 60 | 20.0% |
| LOAD_GLOBAL | 60 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 13.3% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 160 | 53.3% |
| LOAD_DEREF | 120 | 40.0% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 180 | 60.0% |
| LOAD_FAST | 120 | 40.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 50.0% |
| RETURN_VALUE | 60 | 25.0% |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 25.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 50.0% |
| RETURN_VALUE | 60 | 25.0% |
| LOAD_GLOBAL | 40 | 16.7% |
| LOAD_GLOBAL_MODULE | 20 | 8.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 60 | 100.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 400 | 50.0% |
| BINARY_OP | 200 | 25.0% |
| LOAD_FAST_LOAD_FAST | 180 | 22.5% |
| LOAD_FAST | 20 | 2.5% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 220 | 27.5% |
| BINARY_OP | 200 | 25.0% |
| LOAD_FAST | 180 | 22.5% |
| BINARY_OP_SUBTRACT_FLOAT | 140 | 17.5% |
| BINARY_OP_MULTIPLY_FLOAT | 60 | 7.5% |


</details>

### BUILD_LIST

<details>
<summary> Successors and predecessors for BUILD_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 60 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 180 | 50.0% |
| CALL | 60 | 16.7% |
| LOAD_FAST | 60 | 16.7% |
| LOAD_GLOBAL_MODULE | 40 | 11.1% |
| BINARY_SUBSCR_DICT | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 80 | 22.2% |
| POP_TOP | 60 | 16.7% |
| CALL | 60 | 16.7% |
| LOAD_FAST | 60 | 16.7% |
| STORE_FAST | 60 | 16.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_INTRINSIC_1 | 60 | 50.0% |
| LOAD_FAST | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 50.0% |
| RESUME_CHECK | 60 | 50.0% |


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
| COPY | 64,800,000 | 50.0% |
| LOAD_CONST | 64,800,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 64,800,000 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 64,800,000 | 50.0% |


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
| STORE_SUBSCR_LIST_INT | 13,200,000 | 91.7% |
| ENTER_EXECUTOR | 1,200,000 | 8.3% |
| STORE_FAST | 200 | 0.0% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,000,240 | 83.3% |
| ENTER_EXECUTOR | 1,200,000 | 8.3% |
| STORE_FAST | 1,199,940 | 8.3% |
| RETURN_CONST | 60 | 0.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 380 | 86.4% |
| POP_TOP | 60 | 13.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 340 | 77.3% |
| FOR_ITER_RANGE | 60 | 13.6% |
| ENTER_EXECUTOR | 40 | 9.1% |


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
| LOAD_FAST | 64,800,180 | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT | 220 | 0.0% |
| BINARY_OP_ADD_FLOAT | 180 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 64,800,000 | 100.0% |
| BINARY_OP | 400 | 0.0% |
| STORE_SUBSCR_LIST_INT | 120 | 0.0% |
| STORE_SUBSCR | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| NOP | 60 | 33.3% |
| BUILD_LIST | 60 | 33.3% |
| RESUME_CHECK | 60 | 33.3% |

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
| LOAD_FAST | 64,801,340 | 31.4% |
| BINARY_SUBSCR_LIST_INT | 64,800,000 | 31.4% |
| STORE_SUBSCR_LIST_INT | 62,400,000 | 30.2% |
| ENTER_EXECUTOR | 12,000,240 | 5.8% |
| STORE_FAST | 2,400,460 | 1.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 75,601,800 | 36.6% |
| LOAD_FAST | 64,801,340 | 31.4% |
| LOAD_CONST | 64,800,180 | 31.4% |
| GET_ITER | 1,200,420 | 0.6% |
| RETURN_VALUE | 120 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,260 | 63.6% |
| STORE_FAST_STORE_FAST | 240 | 12.1% |
| BINARY_OP_MULTIPLY_FLOAT | 240 | 12.1% |
| BINARY_OP_ADD_FLOAT | 120 | 6.1% |
| STORE_SUBSCR_LIST_INT | 120 | 6.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 900 | 45.5% |
| BINARY_OP_SUBTRACT_FLOAT | 540 | 27.3% |
| BINARY_OP_MULTIPLY_FLOAT | 360 | 18.2% |
| BINARY_OP | 180 | 9.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 27.3% |
| RETURN_VALUE | 40 | 18.2% |
| STORE_FAST | 40 | 18.2% |
| RESUME_CHECK | 40 | 18.2% |
| FOR_ITER_RANGE | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 160 | 72.7% |
| LOAD_GLOBAL_BUILTIN | 40 | 18.2% |
| LOAD_ATTR | 20 | 9.1% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 60 | 50.0% |
| STORE_SUBSCR_LIST_INT | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,600,660 | 50.0% |
| UNPACK_SEQUENCE_TUPLE | 1,200,460 | 16.7% |
| UNPACK_SEQUENCE_LIST | 1,200,220 | 16.7% |
| ENTER_EXECUTOR | 1,199,940 | 16.7% |
| BINARY_OP_SUBTRACT_FLOAT | 1,380 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 3,600,660 | 50.0% |
| LOAD_FAST | 2,400,460 | 33.3% |
| UNPACK_SEQUENCE_LIST | 1,200,460 | 16.7% |
| LOAD_FAST_LOAD_FAST | 1,260 | 0.0% |
| JUMP_BACKWARD | 380 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 600 | 47.6% |
| UNPACK_SEQUENCE_LIST | 600 | 47.6% |
| UNPACK_SEQUENCE_TUPLE | 60 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 600 | 47.6% |
| STORE_FAST | 420 | 33.3% |
| LOAD_FAST_LOAD_FAST | 240 | 19.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 75,600,000 | 50.0% |
| BINARY_OP_ADD_FLOAT | 39,600,000 | 26.2% |
| BINARY_OP_SUBTRACT_FLOAT | 36,000,000 | 23.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 75,600,000 | 50.0% |
| STORE_SUBSCR_LIST_INT | 75,600,000 | 50.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 20 | 100.0% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 39,600,800 | 100.0% |
| BINARY_OP | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 39,600,000 | 100.0% |
| LOAD_FAST | 280 | 0.0% |
| STORE_FAST | 220 | 0.0% |
| BINARY_OP_MULTIPLY_FLOAT | 220 | 0.0% |
| LOAD_CONST | 180 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 75,601,800 | 100.0% |
| LOAD_FAST_LOAD_FAST | 360 | 0.0% |
| BINARY_OP_ADD_FLOAT | 220 | 0.0% |
| BINARY_OP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 39,600,800 | 52.4% |
| BINARY_OP_SUBTRACT_FLOAT | 36,000,720 | 47.6% |
| LOAD_FAST | 280 | 0.0% |
| LOAD_FAST_LOAD_FAST | 240 | 0.0% |
| LOAD_CONST | 220 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 36,000,720 | 100.0% |
| LOAD_FAST_LOAD_FAST | 540 | 0.0% |
| BINARY_OP | 140 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 36,000,000 | 100.0% |
| STORE_FAST | 1,380 | 0.0% |
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
| COPY | 64,800,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 64,800,000 | 100.0% |


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
| GET_ITER | 1,200,360 | 100.0% |
| JUMP_BACKWARD | 340 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,200,460 | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 120 | 66.7% |
| JUMP_BACKWARD | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 66.7% |
| LOAD_GLOBAL_MODULE | 40 | 22.2% |
| LOAD_GLOBAL | 20 | 11.1% |


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
| LOAD_GLOBAL | 160 | 34.8% |
| POP_TOP | 80 | 17.4% |
| STORE_FAST | 80 | 17.4% |
| FOR_ITER_RANGE | 40 | 8.7% |
| LOAD_GLOBAL_MODULE | 40 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 100 | 21.7% |
| CALL_PY_WITH_DEFAULTS | 80 | 17.4% |
| LOAD_ATTR | 60 | 13.0% |
| LOAD_CONST | 60 | 13.0% |
| LOAD_FAST | 60 | 13.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 240 | 66.7% |
| CALL_FUNCTION_EX | 60 | 16.7% |
| COPY_FREE_VARS | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 50.0% |
| LOAD_DEREF | 60 | 16.7% |
| LOAD_GLOBAL | 40 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 40 | 11.1% |
| LOAD_GLOBAL_MODULE | 40 | 11.1% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 75,600,000 | 100.0% |
| LOAD_CONST | 120 | 0.0% |
| STORE_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 62,400,000 | 82.5% |
| ENTER_EXECUTOR | 13,200,000 | 17.5% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| RETURN_CONST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200,460 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 360 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200,220 | 100.0% |
| STORE_FAST_STORE_FAST | 600 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 1,200,460 | 100.0% |
| STORE_FAST | 180 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% |
| LOAD_FAST | 40 | 0.0% |
| UNPACK_SEQUENCE | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 1,200,460 | 100.0% |
| UNPACK_SEQUENCE_LIST | 360 | 0.0% |
| STORE_FAST_STORE_FAST | 60 | 0.0% |


</details>

### UNPACK_SEQUENCE_TWO_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TWO_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_LIST | 180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 180 | 100.0% |


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
|     deferred | 700 | 0.0% |
|          hit | 151,204,900 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 20.0% |
| Failure | 80 | 80.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| true divide float | 80 | 100.0% |


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 64,800,060 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 180 | 25.0% |
|          hit | 360 | 50.0% |

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
|          hit | 1,200,880 | 100.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> specialization stats for JUMP_BACKWARD family </summary>


</details>

### LOAD_ATTR

<details>
<summary> specialization stats for LOAD_ATTR family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|     deferred | 20 | 8.3% |
|          hit | 160 | 66.7% |

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
|     deferred | 20 | 2.5% |
|          hit | 580 | 72.5% |

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
|          hit | 75,600,180 | 100.0% |

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---:|---:|
|          hit | 2,401,880 | 100.0% |

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
| Basic | 574,814,220 | 66.1% |
| Not specialized | 2,000 | 0.0% |
| Specialized | 295,209,360 | 33.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 700 | 76.1% |
| CALL | 180 | 19.6% |
| LOAD_ATTR | 20 | 2.2% |
| LOAD_GLOBAL | 20 | 2.2% |
| BINARY_SLICE | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| BINARY_SUBSCR | 0 | 0.0% |
| GET_ITER | 0 | 0.0% |
| NOP | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |


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
| Calls to Python functions inlined | 360 | 100.0% |
| Calls via PyEval_EvalFrame (total) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (vector) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 120 | 33.3% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frame objects created | 0 | 0.0% |
| Frames pushed | 360 | 100.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 198,014,440 | 98.2% |
| Frees to freelist | 198,014,460 |  |
| Allocations | 3,585,360 | 1.8% |
| Allocations to 512 bytes | 3,585,320 | 1.8% |
| Allocations to 4 kbytes | 40 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 3,585,240 |  |
| New values | 0 |  |
| Interpreter increfs | 358,817,120 | 39.5% |
| Interpreter decrefs | 453,620,780 | 40.9% |
| Increfs | 548,439,100 | 60.5% |
| Decrefs | 655,235,080 | 59.1% |
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
| 0 | 0 | 0 | 0 |
| 1 | 0 | 0 | 0 |
| 2 | 0 | 0 | 0 |


</details>

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 40 |  |
| Traces created | 40 | 100.0% |
| Traces executed | 14,400,240 |  |
| Uops executed | 1,470,105,320 | 102.09 |
| Trace stack overflow | 0 | 0.0% |
| Trace stack underflow | 0 | 0.0% |
| Trace too long | 0 | 0.0% |
| Trace too short | 0 | 0.0% |
| Inner loop found | 0 | 0.0% |
| Recursive call | 0 | 0.0% |

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
| <= 64 | 20 | 50.0% |
| <= 128 | 20 | 50.0% |


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
| <= 64 | 40 | 100.0% |


</details>

### Trace run length histogram

<details>
<summary> trace run length histogram </summary>

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 1,200,060 | 8.3% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 0 | 0.0% |
| <= 128 | 11,999,940 | 83.3% |
| <= 256 | 120 | 0.0% |
| <= 512 | 1,200,000 | 8.3% |
| <= 1,024 | 120 | 0.0% |


</details>

### Uop execution stats

<details>
<summary> uop execution stats </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| _SET_IP | 322,825,020 | 22.0% | 22.0% |  |
| LOAD_FAST | 270,018,700 | 18.4% | 40.3% |  |
| STORE_FAST | 216,016,920 | 14.7% | 55.0% |  |
| _GUARD_BOTH_FLOAT | 160,813,160 | 10.9% | 66.0% |  |
| _BINARY_OP_MULTIPLY_FLOAT | 86,405,660 | 5.9% | 71.8% |  |
| COPY | 50,400,000 | 3.4% | 75.3% |  |
| _BINARY_OP_ADD_FLOAT | 38,403,180 | 2.6% | 77.9% |  |
| LOAD_CONST | 37,201,400 | 2.5% | 80.4% |  |
| _BINARY_OP_SUBTRACT_FLOAT | 36,004,320 | 2.4% | 82.9% |  |
| UNPACK_SEQUENCE_LIST | 28,802,480 | 2.0% | 84.8% |  |
| UNPACK_SEQUENCE_TUPLE | 28,802,480 | 2.0% | 86.8% |  |
| SWAP | 28,800,000 | 2.0% | 88.7% |  |
| BINARY_SUBSCR_LIST_INT | 25,200,000 | 1.7% | 90.4% |  |
| _POP_JUMP_IF_TRUE | 20,401,700 | 1.4% | 91.8% |  |
| _ITER_CHECK_LIST | 19,201,700 | 1.3% | 93.1% |  |
| _IS_ITER_EXHAUSTED_LIST | 19,201,700 | 1.3% | 94.4% |  |
| _ITER_NEXT_LIST | 16,801,460 | 1.1% | 95.6% |  |
| _EXIT_TRACE | 14,400,240 | 1.0% | 96.6% |  |
| STORE_SUBSCR_LIST_INT | 14,400,000 | 1.0% | 97.6% |  |
| BINARY_OP | 12,002,480 | 0.8% | 98.4% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,001,020 | 0.8% | 99.2% |  |
| _JUMP_TO_TOP | 4,801,520 | 0.3% | 99.5% |  |
| POP_TOP | 2,400,300 | 0.2% | 99.7% |  |
| _ITER_CHECK_RANGE | 1,200,000 | 0.1% | 99.8% |  |
| _IS_ITER_EXHAUSTED_RANGE | 1,200,000 | 0.1% | 99.8% |  |
| GET_ITER | 1,199,940 | 0.1% | 99.9% |  |
| _ITER_NEXT_RANGE | 1,199,940 | 0.1% | 100.0% |  |


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
Stats gathered on: 2023-10-09
