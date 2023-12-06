
# Pystats results

- benchmark: nbody
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| LOAD_FAST | 350,404,880 | 27.2% | 27.2% |  |
| SWAP | 170,400,000 | 13.2% | 40.4% |  |
| COPY | 160,800,000 | 12.5% | 52.8% |  |
| BINARY_OP_MULTIPLY_FLOAT | 157,206,400 | 12.2% | 65.0% |  |
| LOAD_CONST | 92,401,660 | 7.2% | 72.2% |  |
| STORE_SUBSCR_LIST_INT | 85,200,180 | 6.6% | 78.8% |  |
| BINARY_SUBSCR_LIST_INT | 80,400,000 | 6.2% | 85.0% |  |
| BINARY_OP_ADD_FLOAT | 73,203,440 | 5.7% | 90.7% |  |
| STORE_FAST | 44,404,940 | 3.4% | 94.1% |  |
| BINARY_OP_SUBTRACT_FLOAT | 37,202,460 | 2.9% | 97.0% |  |
| ENTER_EXECUTOR | 19,201,700 | 1.5% | 98.5% |  |
| BINARY_OP | 12,005,920 | 0.9% | 99.4% |  |
| LOAD_FAST_LOAD_FAST | 2,405,100 | 0.2% | 99.6% |  |
| UNPACK_SEQUENCE_TUPLE | 1,200,880 | 0.1% | 99.7% |  |
| UNPACK_SEQUENCE_LIST | 1,200,820 | 0.1% | 99.8% |  |
| FOR_ITER_LIST | 1,200,700 | 0.1% | 99.9% |  |
| GET_ITER | 1,200,480 | 0.1% | 100.0% |  |
| STORE_FAST_STORE_FAST | 1,260 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 460 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 440 | 0.0% | 100.0% |  |
| RESUME_CHECK | 360 | 0.0% | 100.0% |  |
| CALL | 360 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| POP_TOP | 300 | 0.0% | 100.0% |  |
| RETURN_VALUE | 240 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 220 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| FOR_ITER_RANGE | 180 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 160 | 0.0% | 100.0% |  |
| RETURN_CONST | 120 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR | 80 | 0.0% | 100.0% |  |
| STORE_SUBSCR | 60 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_SUBSCR_DICT | 60 | 0.0% | 100.0% |  |
| UNPACK_SEQUENCE | 20 | 0.0% | 100.0% |  |
| BINARY_SUBSCR | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 140,402,580 | 10.9% | 10.9% |
| LOAD_FAST LOAD_FAST | 128,401,100 | 10.0% | 20.8% |
| SWAP SWAP | 85,200,000 | 6.6% | 27.4% |
| SWAP STORE_SUBSCR_LIST_INT | 85,200,000 | 6.6% | 34.0% |
| LOAD_FAST LOAD_CONST | 80,400,180 | 6.2% | 40.3% |
| LOAD_CONST COPY | 80,400,000 | 6.2% | 46.5% |
| COPY COPY | 80,400,000 | 6.2% | 52.7% |
| COPY BINARY_SUBSCR_LIST_INT | 80,400,000 | 6.2% | 59.0% |
| BINARY_SUBSCR_LIST_INT LOAD_FAST | 80,400,000 | 6.2% | 65.2% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_ADD_FLOAT | 73,202,840 | 5.7% | 70.9% |
| STORE_SUBSCR_LIST_INT LOAD_FAST | 67,200,000 | 5.2% | 76.1% |
| BINARY_OP_ADD_FLOAT SWAP | 49,200,000 | 3.8% | 79.9% |
| STORE_FAST LOAD_FAST | 37,200,340 | 2.9% | 82.8% |
| BINARY_OP_MULTIPLY_FLOAT BINARY_OP_SUBTRACT_FLOAT | 36,000,720 | 2.8% | 85.6% |
| BINARY_OP_SUBTRACT_FLOAT SWAP | 36,000,000 | 2.8% | 88.4% |
| BINARY_OP_MULTIPLY_FLOAT STORE_FAST | 36,000,000 | 2.8% | 91.2% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 18,000,000 | 1.4% | 92.6% |
| LOAD_CONST BINARY_OP | 12,001,420 | 0.9% | 93.5% |
| ENTER_EXECUTOR LOAD_FAST | 12,001,320 | 0.9% | 94.4% |
| BINARY_OP_ADD_FLOAT LOAD_CONST | 12,001,200 | 0.9% | 95.3% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST | 12,000,220 | 0.9% | 96.3% |
| BINARY_OP_ADD_FLOAT LOAD_FAST | 12,000,220 | 0.9% | 97.2% |
| BINARY_OP BINARY_OP_MULTIPLY_FLOAT | 12,000,000 | 0.9% | 98.1% |
| ENTER_EXECUTOR BINARY_OP_MULTIPLY_FLOAT | 4,800,000 | 0.4% | 98.5% |
| STORE_FAST STORE_FAST | 3,600,660 | 0.3% | 98.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 2,401,140 | 0.2% | 99.0% |
| BINARY_OP_SUBTRACT_FLOAT STORE_FAST | 1,202,400 | 0.1% | 99.1% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 1,200,840 | 0.1% | 99.2% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 1,200,480 | 0.1% | 99.3% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST | 1,200,460 | 0.1% | 99.3% |
| STORE_FAST UNPACK_SEQUENCE_LIST | 1,200,460 | 0.1% | 99.4% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TUPLE | 1,200,460 | 0.1% | 99.5% |
| LOAD_FAST GET_ITER | 1,200,420 | 0.1% | 99.6% |
| GET_ITER FOR_ITER_LIST | 1,200,360 | 0.1% | 99.7% |
| UNPACK_SEQUENCE_LIST STORE_FAST | 1,200,220 | 0.1% | 99.8% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 1,200,000 | 0.1% | 99.9% |
| ENTER_EXECUTOR STORE_FAST | 1,199,940 | 0.1% | 100.0% |
| BINARY_OP BINARY_OP | 4,300 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_MULTIPLY_FLOAT | 3,600 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_FAST_LOAD_FAST | 2,400 | 0.0% | 100.0% |
| STORE_FAST ENTER_EXECUTOR | 1,660 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_SUBTRACT_FLOAT | 1,220 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT LOAD_FAST_LOAD_FAST | 1,200 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_LIST STORE_FAST_STORE_FAST | 600 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 600 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT STORE_FAST | 600 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST STORE_FAST | 420 | 0.0% | 100.0% |
| STORE_FAST JUMP_BACKWARD | 380 | 0.0% | 100.0% |
| ENTER_EXECUTOR BINARY_OP_ADD_FLOAT | 380 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE UNPACK_SEQUENCE_LIST | 360 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 340 | 0.0% | 100.0% |
| STORE_FAST_STORE_FAST LOAD_FAST_LOAD_FAST | 240 | 0.0% | 100.0% |
| CALL_PY_WITH_DEFAULTS RESUME_CHECK | 240 | 0.0% | 100.0% |
| BINARY_OP_MULTIPLY_FLOAT LOAD_CONST | 220 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT BINARY_OP_MULTIPLY_FLOAT | 220 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 220 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TWO_TUPLE UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |
| STORE_FAST UNPACK_SEQUENCE_TUPLE | 180 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_FAST | 180 | 0.0% | 100.0% |
| PUSH_NULL CALL | 180 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 180 | 0.0% | 100.0% |
| FOR_ITER_LIST UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% | 100.0% |
| BINARY_OP LOAD_FAST | 180 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 160 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 160 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |
| RETURN_VALUE POP_TOP | 120 | 0.0% | 100.0% |
| RETURN_CONST POP_TOP | 120 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_FAST RETURN_VALUE | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| LOAD_CONST STORE_SUBSCR_LIST_INT | 120 | 0.0% | 100.0% |
| GET_ITER FOR_ITER_RANGE | 120 | 0.0% | 100.0% |
| FOR_ITER_RANGE STORE_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL_MODULE | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE CALL_PY_WITH_DEFAULTS | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| CALL CALL_PY_WITH_DEFAULTS | 80 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 60 | 0.0% | 100.0% |
| STORE_SUBSCR_LIST_INT RETURN_CONST | 60 | 0.0% | 100.0% |
| STORE_SUBSCR STORE_SUBSCR_LIST_INT | 60 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| POP_TOP LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| POP_TOP JUMP_BACKWARD | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_CONST | 60 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LOAD_CONST STORE_SUBSCR | 60 | 0.0% | 100.0% |
| LOAD_CONST LOAD_FAST | 60 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 60 | 0.0% | 100.0% |


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
| LOAD_GLOBAL | 60 | 20.0% |
| JUMP_BACKWARD | 60 | 20.0% |
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
| LOAD_CONST | 12,001,420 | 100.0% |
| BINARY_OP | 4,300 | 0.0% |
| LOAD_FAST_LOAD_FAST | 180 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 12,000,000 | 100.0% |
| BINARY_OP | 4,300 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 1,220 | 0.0% |
| BINARY_OP_ADD_FLOAT | 220 | 0.0% |
| LOAD_FAST | 180 | 0.0% |


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
| LOAD_FAST | 60 | 16.7% |
| CALL | 60 | 16.7% |
| LOAD_GLOBAL_MODULE | 40 | 11.1% |
| BINARY_SUBSCR_DICT | 20 | 5.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 80 | 22.2% |
| STORE_FAST | 60 | 16.7% |
| POP_TOP | 60 | 16.7% |
| LOAD_FAST | 60 | 16.7% |
| CALL | 60 | 16.7% |


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
| LOAD_CONST | 80,400,000 | 50.0% |
| COPY | 80,400,000 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80,400,000 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 80,400,000 | 50.0% |


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
| STORE_SUBSCR_LIST_INT | 18,000,000 | 93.7% |
| ENTER_EXECUTOR | 1,200,000 | 6.2% |
| STORE_FAST | 1,660 | 0.0% |
| JUMP_BACKWARD | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 12,001,320 | 62.5% |
| BINARY_OP_MULTIPLY_FLOAT | 4,800,000 | 25.0% |
| ENTER_EXECUTOR | 1,200,000 | 6.2% |
| STORE_FAST | 1,199,940 | 6.2% |
| BINARY_OP_ADD_FLOAT | 380 | 0.0% |


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
| LOAD_FAST | 80,400,180 | 87.0% |
| BINARY_OP_ADD_FLOAT | 12,001,200 | 13.0% |
| BINARY_OP_MULTIPLY_FLOAT | 220 | 0.0% |
| LOAD_GLOBAL_MODULE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 80,400,000 | 87.0% |
| BINARY_OP | 12,001,420 | 13.0% |
| STORE_SUBSCR_LIST_INT | 120 | 0.0% |
| STORE_SUBSCR | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


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
| LOAD_FAST | 128,401,100 | 36.6% |
| BINARY_SUBSCR_LIST_INT | 80,400,000 | 22.9% |
| STORE_SUBSCR_LIST_INT | 67,200,000 | 19.2% |
| STORE_FAST | 37,200,340 | 10.6% |
| ENTER_EXECUTOR | 12,001,320 | 3.4% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 140,402,580 | 40.1% |
| LOAD_FAST | 128,401,100 | 36.6% |
| LOAD_CONST | 80,400,180 | 22.9% |
| GET_ITER | 1,200,420 | 0.3% |
| RETURN_VALUE | 120 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,401,140 | 99.8% |
| BINARY_OP_MULTIPLY_FLOAT | 2,400 | 0.1% |
| BINARY_OP_ADD_FLOAT | 1,200 | 0.0% |
| STORE_FAST_STORE_FAST | 240 | 0.0% |
| STORE_SUBSCR_LIST_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 1,200,840 | 49.9% |
| BINARY_OP_SUBTRACT_FLOAT | 1,200,480 | 49.9% |
| BINARY_OP_MULTIPLY_FLOAT | 3,600 | 0.1% |
| BINARY_OP | 180 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 60 | 27.3% |
| STORE_FAST | 40 | 18.2% |
| RETURN_VALUE | 40 | 18.2% |
| RESUME_CHECK | 40 | 18.2% |
| LOAD_GLOBAL_MODULE | 20 | 9.1% |

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
| STORE_SUBSCR_LIST_INT | 60 | 50.0% |
| ENTER_EXECUTOR | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 100.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 36,000,000 | 81.1% |
| STORE_FAST | 3,600,660 | 8.1% |
| BINARY_OP_SUBTRACT_FLOAT | 1,202,400 | 2.7% |
| UNPACK_SEQUENCE_TUPLE | 1,200,460 | 2.7% |
| UNPACK_SEQUENCE_LIST | 1,200,220 | 2.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 37,200,340 | 83.8% |
| STORE_FAST | 3,600,660 | 8.1% |
| LOAD_FAST_LOAD_FAST | 2,401,140 | 5.4% |
| UNPACK_SEQUENCE_LIST | 1,200,460 | 2.7% |
| ENTER_EXECUTOR | 1,660 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_LIST | 600 | 47.6% |
| STORE_FAST_STORE_FAST | 600 | 47.6% |
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
| SWAP | 85,200,000 | 50.0% |
| BINARY_OP_ADD_FLOAT | 49,200,000 | 28.9% |
| BINARY_OP_SUBTRACT_FLOAT | 36,000,000 | 21.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 85,200,000 | 50.0% |
| STORE_SUBSCR_LIST_INT | 85,200,000 | 50.0% |


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
| BINARY_OP_MULTIPLY_FLOAT | 73,202,840 | 100.0% |
| ENTER_EXECUTOR | 380 | 0.0% |
| BINARY_OP | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 49,200,000 | 67.2% |
| LOAD_CONST | 12,001,200 | 16.4% |
| LOAD_FAST | 12,000,220 | 16.4% |
| LOAD_FAST_LOAD_FAST | 1,200 | 0.0% |
| STORE_FAST | 600 | 0.0% |


</details>

### BINARY_OP_MULTIPLY_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_MULTIPLY_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 140,402,580 | 89.3% |
| BINARY_OP | 12,000,000 | 7.6% |
| ENTER_EXECUTOR | 4,800,000 | 3.1% |
| LOAD_FAST_LOAD_FAST | 3,600 | 0.0% |
| BINARY_OP_ADD_FLOAT | 220 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 73,202,840 | 46.6% |
| BINARY_OP_SUBTRACT_FLOAT | 36,000,720 | 22.9% |
| STORE_FAST | 36,000,000 | 22.9% |
| LOAD_FAST | 12,000,220 | 7.6% |
| LOAD_FAST_LOAD_FAST | 2,400 | 0.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_MULTIPLY_FLOAT | 36,000,720 | 96.8% |
| LOAD_FAST_LOAD_FAST | 1,200,480 | 3.2% |
| BINARY_OP | 1,220 | 0.0% |
| LOAD_FAST | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 36,000,000 | 96.8% |
| STORE_FAST | 1,202,400 | 3.2% |
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
| COPY | 80,400,000 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 80,400,000 | 100.0% |


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
| STORE_FAST | 60 | 50.0% |
| GET_ITER | 60 | 50.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 80 | 33.3% |
| CALL | 80 | 33.3% |
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
| RESUME_CHECK | 40 | 33.3% |
| POP_TOP | 40 | 33.3% |
| LOAD_GLOBAL | 40 | 33.3% |

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
| STORE_FAST | 80 | 17.4% |
| POP_TOP | 80 | 17.4% |
| RESUME_CHECK | 40 | 8.7% |
| LOAD_GLOBAL_MODULE | 40 | 8.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 100 | 21.7% |
| CALL_PY_WITH_DEFAULTS | 80 | 17.4% |
| LOAD_FAST | 60 | 13.0% |
| LOAD_CONST | 60 | 13.0% |
| LOAD_ATTR | 60 | 13.0% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 240 | 66.7% |
| COPY_FREE_VARS | 60 | 16.7% |
| CALL_FUNCTION_EX | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 50.0% |
| LOAD_DEREF | 60 | 16.7% |
| LOAD_GLOBAL_MODULE | 40 | 11.1% |
| LOAD_GLOBAL_BUILTIN | 40 | 11.1% |
| LOAD_GLOBAL | 40 | 11.1% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 85,200,000 | 100.0% |
| LOAD_CONST | 120 | 0.0% |
| STORE_SUBSCR | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 67,200,000 | 78.9% |
| ENTER_EXECUTOR | 18,000,000 | 21.1% |
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
| UNPACK_SEQUENCE_TWO_TUPLE | 180 | 0.0% |
| STORE_FAST | 180 | 0.0% |
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

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     80400060 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |     85200180 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 60 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |     12002800 | 4.3% |
|          hit |    267612300 | 95.7% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 0.6% |
| Failure | 3,100 | 99.4% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| power | 2,980 | 96.1% |
| true divide float | 120 | 3.9% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          180 | 25.0% |
|          hit |          360 | 50.0% |

#### Specialization attempts

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
|---|---|---|
|          hit |      1200880 | 100.0% |


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
| specialization.deferred |           20 | 2.5% |
|          hit |          580 | 72.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 200 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2401880 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 841,221,580 | 65.2% |
| Not specialized | 12,007,120 | 0.9% |
| Specialized | 436,816,760 | 33.9% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 12,002,800 | 100.0% |
| CALL | 180 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_LIST | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| SWAP | 0 | 0.0% |


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
| Frames pushed | 360 | 100.0% |
| Frame objects created | 0 | 0.0% |


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
| Interpreter increfs | 555,626,380 | 60.9% |
| Interpreter decrefs | 736,837,560 | 66.2% |
| Increfs | 356,431,300 | 39.1% |
| Decrefs | 376,819,760 | 33.8% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 19 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 1 |  |
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
| Optimization attempts | 40 |  |
| Traces created | 40 | 100.0% |
| Traces executed | 19,201,700 |  |
| Uops executed | 782,469,900 | 40 |
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
| <= 64 | 40 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 40 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 2,400,280 | 12.5% |
| <= 16 | 0 | 0.0% |
| <= 32 | 0 | 0.0% |
| <= 64 | 16,801,400 | 87.5% |
| <= 128 | 0 | 0.0% |
| <= 256 | 20 | 0.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST | 178,815,700 | 22.9% | 22.9% |
| _SET_IP | 169,215,520 | 21.6% | 44.5% |
| LOAD_FAST | 121,211,920 | 15.5% | 60.0% |
| _GUARD_BOTH_FLOAT | 44,405,760 | 5.7% | 65.6% |
| _BINARY_OP_SUBTRACT_FLOAT | 34,803,300 | 4.4% | 70.1% |
| UNPACK_SEQUENCE_TUPLE | 28,802,480 | 3.7% | 73.8% |
| UNPACK_SEQUENCE_LIST | 28,802,480 | 3.7% | 77.5% |
| _POP_JUMP_IF_TRUE | 20,401,700 | 2.6% | 80.1% |
| _ITER_CHECK_LIST | 19,201,700 | 2.5% | 82.5% |
| _IS_ITER_EXHAUSTED_LIST | 19,201,700 | 2.5% | 85.0% |
| _EXIT_TRACE | 19,201,700 | 2.5% | 87.4% |
| COPY | 19,200,000 | 2.5% | 89.9% |
| _ITER_NEXT_LIST | 16,801,460 | 2.1% | 92.0% |
| UNPACK_SEQUENCE_TWO_TUPLE | 12,001,020 | 1.5% | 93.6% |
| LOAD_CONST | 9,600,380 | 1.2% | 94.8% |
| SWAP | 9,600,000 | 1.2% | 96.0% |
| BINARY_SUBSCR_LIST_INT | 9,600,000 | 1.2% | 97.2% |
| _BINARY_OP_MULTIPLY_FLOAT | 4,801,700 | 0.6% | 97.9% |
| _BINARY_OP_ADD_FLOAT | 4,800,760 | 0.6% | 98.5% |
| STORE_SUBSCR_LIST_INT | 4,800,000 | 0.6% | 99.1% |
| POP_TOP | 2,400,300 | 0.3% | 99.4% |
| _ITER_CHECK_RANGE | 1,200,000 | 0.2% | 99.5% |
| _IS_ITER_EXHAUSTED_RANGE | 1,200,000 | 0.2% | 99.7% |
| _ITER_NEXT_RANGE | 1,199,940 | 0.2% | 99.8% |
| GET_ITER | 1,199,940 | 0.2% | 100.0% |
| BINARY_OP | 380 | 0.0% | 100.0% |
| _JUMP_TO_TOP | 60 | 0.0% | 100.0% |


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
