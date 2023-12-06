
# Pystats results

- benchmark: unpack_sequence
- fork: python
- ref: main
- commit hash: c829975
- commit date: 2023-09-18T20:09:59+03:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| STORE_FAST_STORE_FAST | 983,040,000 | 71.3% | 71.3% |  |
| LOAD_FAST | 196,608,600 | 14.3% | 85.6% |  |
| UNPACK_SEQUENCE_TUPLE | 98,328,000 | 7.1% | 92.7% | 1.3% |
| UNPACK_SEQUENCE_LIST | 98,328,000 | 7.1% | 99.8% | 1.3% |
| EXTENDED_ARG | 983,160 | 0.1% | 99.9% |  |
| STORE_FAST | 492,000 | 0.0% | 99.9% |  |
| FOR_ITER_RANGE | 491,640 | 0.0% | 100.0% |  |
| JUMP_BACKWARD | 491,520 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 520 | 0.0% | 100.0% |  |
| CALL | 520 | 0.0% | 100.0% |  |
| PUSH_NULL | 420 | 0.0% | 100.0% |  |
| RETURN_VALUE | 360 | 0.0% | 100.0% |  |
| RESUME_CHECK | 360 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_BUILTIN | 360 | 0.0% | 100.0% |  |
| CALL_BUILTIN_CLASS | 300 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 280 | 0.0% | 100.0% |  |
| CALL_PY_EXACT_ARGS | 240 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 200 | 0.0% | 100.0% |  |
| LOAD_FAST_LOAD_FAST | 180 | 0.0% | 100.0% |  |
| LOAD_DEREF | 180 | 0.0% | 100.0% |  |
| LOAD_CONST | 120 | 0.0% | 100.0% |  |
| GET_ITER | 120 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 120 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% | 100.0% |  |
| POP_TOP | 60 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LIST_EXTEND | 60 | 0.0% | 100.0% |  |
| COPY_FREE_VARS | 60 | 0.0% | 100.0% |  |
| CALL_TUPLE_1 | 60 | 0.0% | 100.0% |  |
| CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |  |
| BUILD_LIST | 60 | 0.0% | 100.0% |  |
| BINARY_OP_ADD_FLOAT | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 40 | 0.0% | 100.0% |  |
| BINARY_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| STORE_FAST_STORE_FAST STORE_FAST_STORE_FAST | 786,432,000 | 57.0% | 57.0% |
| STORE_FAST_STORE_FAST LOAD_FAST | 196,116,480 | 14.2% | 71.3% |
| UNPACK_SEQUENCE_TUPLE STORE_FAST_STORE_FAST | 98,304,000 | 7.1% | 78.4% |
| UNPACK_SEQUENCE_LIST STORE_FAST_STORE_FAST | 98,304,000 | 7.1% | 85.5% |
| LOAD_FAST UNPACK_SEQUENCE_TUPLE | 98,304,000 | 7.1% | 92.7% |
| LOAD_FAST UNPACK_SEQUENCE_LIST | 98,304,000 | 7.1% | 99.8% |
| STORE_FAST LOAD_FAST | 491,640 | 0.0% | 99.8% |
| EXTENDED_ARG FOR_ITER_RANGE | 491,640 | 0.0% | 99.9% |
| STORE_FAST_STORE_FAST EXTENDED_ARG | 491,520 | 0.0% | 99.9% |
| JUMP_BACKWARD EXTENDED_ARG | 491,520 | 0.0% | 99.9% |
| FOR_ITER_RANGE STORE_FAST | 491,520 | 0.0% | 100.0% |
| EXTENDED_ARG JUMP_BACKWARD | 491,520 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_TUPLE UNPACK_SEQUENCE_LIST | 24,000 | 0.0% | 100.0% |
| UNPACK_SEQUENCE_LIST UNPACK_SEQUENCE_TUPLE | 24,000 | 0.0% | 100.0% |
| PUSH_NULL CALL | 300 | 0.0% | 100.0% |
| LOAD_ATTR_MODULE PUSH_NULL | 280 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR_MODULE | 260 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_MODULE | 240 | 0.0% | 100.0% |
| CALL_PY_EXACT_ARGS RESUME_CHECK | 240 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 200 | 0.0% | 100.0% |
| RETURN_VALUE RETURN_VALUE | 180 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 180 | 0.0% | 100.0% |
| RETURN_VALUE STORE_FAST | 120 | 0.0% | 100.0% |
| PUSH_NULL LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST_LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_CONST | 120 | 0.0% | 100.0% |
| LOAD_FAST GET_ITER | 120 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |
| LOAD_FAST BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% | 100.0% |
| LOAD_DEREF PUSH_NULL | 120 | 0.0% | 100.0% |
| GET_ITER EXTENDED_ARG | 120 | 0.0% | 100.0% |
| FOR_ITER_RANGE LOAD_GLOBAL_MODULE | 120 | 0.0% | 100.0% |
| CALL STORE_FAST | 120 | 0.0% | 100.0% |
| CALL LOAD_FAST | 120 | 0.0% | 100.0% |
| BINARY_OP_SUBTRACT_FLOAT RETURN_VALUE | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_MODULE | 100 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 80 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST CALL_PY_EXACT_ARGS | 80 | 0.0% | 100.0% |
| LOAD_FAST CALL_PY_EXACT_ARGS | 80 | 0.0% | 100.0% |
| LOAD_CONST CALL_BUILTIN_CLASS | 80 | 0.0% | 100.0% |
| CALL CALL_PY_EXACT_ARGS | 80 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL | 60 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_DEREF | 60 | 0.0% | 100.0% |
| POP_TOP NOP | 60 | 0.0% | 100.0% |
| NOP LOAD_DEREF | 60 | 0.0% | 100.0% |
| LOAD_FAST CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| LOAD_FAST BUILD_LIST | 60 | 0.0% | 100.0% |
| LOAD_DEREF LIST_EXTEND | 60 | 0.0% | 100.0% |
| LIST_EXTEND CALL_INTRINSIC_1 | 60 | 0.0% | 100.0% |
| COPY_FREE_VARS RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_TUPLE_1 STORE_FAST | 60 | 0.0% | 100.0% |
| CALL_INTRINSIC_1 CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX RESUME_CHECK | 60 | 0.0% | 100.0% |
| CALL_FUNCTION_EX COPY_FREE_VARS | 60 | 0.0% | 100.0% |
| CALL POP_TOP | 60 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 60 | 0.0% | 100.0% |
| CALL CALL | 60 | 0.0% | 100.0% |
| BUILD_LIST LOAD_DEREF | 60 | 0.0% | 100.0% |
| BINARY_OP_ADD_FLOAT RETURN_VALUE | 60 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_MODULE | 40 | 0.0% | 100.0% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL | 40 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST CALL | 40 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP_ADD_FLOAT | 40 | 0.0% | 100.0% |
| LOAD_FAST CALL | 40 | 0.0% | 100.0% |
| LOAD_CONST CALL | 40 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_TUPLE_1 | 40 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_BUILTIN_CLASS | 40 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL | 40 | 0.0% | 100.0% |
| RETURN_VALUE LOAD_GLOBAL_MODULE | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_ATTR | 20 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST BINARY_OP | 20 | 0.0% | 100.0% |
| LOAD_ATTR PUSH_NULL | 20 | 0.0% | 100.0% |
| LOAD_ATTR LOAD_ATTR_MODULE | 20 | 0.0% | 100.0% |
| CALL CALL_TUPLE_1 | 20 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP_ADD_FLOAT | 20 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 120 | 100.0% |


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
| LOAD_ATTR_MODULE | 280 | 66.7% |
| LOAD_DEREF | 120 | 28.6% |
| LOAD_ATTR | 20 | 4.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 300 | 71.4% |
| LOAD_FAST | 120 | 28.6% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 180 | 50.0% |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 33.3% |
| BINARY_OP_ADD_FLOAT | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 180 | 50.0% |
| STORE_FAST | 120 | 33.3% |
| LOAD_GLOBAL | 40 | 11.1% |
| LOAD_GLOBAL_MODULE | 20 | 5.6% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_FLOAT | 20 | 100.0% |


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
| PUSH_NULL | 300 | 57.7% |
| CALL | 60 | 11.5% |
| LOAD_FAST_LOAD_FAST | 40 | 7.7% |
| LOAD_FAST | 40 | 7.7% |
| LOAD_CONST | 40 | 7.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 120 | 23.1% |
| LOAD_FAST | 120 | 23.1% |
| CALL_PY_EXACT_ARGS | 80 | 15.4% |
| POP_TOP | 60 | 11.5% |
| CALL_BUILTIN_CLASS | 60 | 11.5% |


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

### EXTENDED_ARG

<details>
<summary> Successors and predecessors for EXTENDED_ARG </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 491,520 | 50.0% |
| JUMP_BACKWARD | 491,520 | 50.0% |
| GET_ITER | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 491,640 | 50.0% |
| JUMP_BACKWARD | 491,520 | 50.0% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 491,520 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 491,520 | 100.0% |


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
| LOAD_GLOBAL_BUILTIN | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 80 | 66.7% |
| CALL | 40 | 33.3% |


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
| STORE_FAST_STORE_FAST | 196,116,480 | 99.7% |
| STORE_FAST | 491,640 | 0.3% |
| PUSH_NULL | 120 | 0.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 98,304,000 | 50.0% |
| UNPACK_SEQUENCE_LIST | 98,304,000 | 50.0% |
| GET_ITER | 120 | 0.0% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 120 | 0.0% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 120 | 66.7% |
| STORE_FAST | 60 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 80 | 44.4% |
| CALL | 40 | 22.2% |
| BINARY_OP_ADD_FLOAT | 40 | 22.2% |
| BINARY_OP | 20 | 11.1% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 30.0% |
| RESUME_CHECK | 60 | 30.0% |
| RETURN_VALUE | 40 | 20.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 100 | 50.0% |
| LOAD_GLOBAL_BUILTIN | 80 | 40.0% |
| LOAD_ATTR | 20 | 10.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 491,520 | 99.9% |
| CALL_BUILTIN_CLASS | 180 | 0.0% |
| RETURN_VALUE | 120 | 0.0% |
| CALL | 120 | 0.0% |
| CALL_TUPLE_1 | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 491,640 | 99.9% |
| LOAD_GLOBAL_MODULE | 240 | 0.0% |
| LOAD_GLOBAL | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |


</details>

### STORE_FAST_STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST_STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 786,432,000 | 80.0% |
| UNPACK_SEQUENCE_TUPLE | 98,304,000 | 10.0% |
| UNPACK_SEQUENCE_LIST | 98,304,000 | 10.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 786,432,000 | 80.0% |
| LOAD_FAST | 196,116,480 | 20.0% |
| EXTENDED_ARG | 491,520 | 0.1% |


</details>

### BINARY_OP_ADD_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 40 | 66.7% |
| BINARY_OP | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_FLOAT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_FLOAT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_VALUE | 120 | 100.0% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 40.0% |
| LOAD_CONST | 80 | 26.7% |
| CALL | 60 | 20.0% |
| CALL_BUILTIN_CLASS | 40 | 13.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 180 | 60.0% |
| CALL_TUPLE_1 | 40 | 13.3% |
| CALL_BUILTIN_CLASS | 40 | 13.3% |
| CALL | 40 | 13.3% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 80 | 33.3% |
| LOAD_FAST | 80 | 33.3% |
| CALL | 80 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 240 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 100.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| EXTENDED_ARG | 491,640 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 491,520 | 100.0% |
| LOAD_GLOBAL_MODULE | 120 | 0.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 260 | 92.9% |
| LOAD_ATTR | 20 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 280 | 100.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 200 | 55.6% |
| LOAD_GLOBAL_BUILTIN | 80 | 22.2% |
| LOAD_GLOBAL | 80 | 22.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 33.3% |
| LOAD_CONST | 120 | 33.3% |
| LOAD_GLOBAL_BUILTIN | 80 | 22.2% |
| LOAD_GLOBAL | 40 | 11.1% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 240 | 46.2% |
| FOR_ITER_RANGE | 120 | 23.1% |
| LOAD_GLOBAL | 100 | 19.2% |
| RESUME_CHECK | 40 | 7.7% |
| RETURN_VALUE | 20 | 3.8% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 260 | 50.0% |
| LOAD_FAST_LOAD_FAST | 120 | 23.1% |
| LOAD_FAST | 120 | 23.1% |
| LOAD_ATTR | 20 | 3.8% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 240 | 66.7% |
| COPY_FREE_VARS | 60 | 16.7% |
| CALL_FUNCTION_EX | 60 | 16.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 200 | 55.6% |
| LOAD_GLOBAL | 60 | 16.7% |
| LOAD_DEREF | 60 | 16.7% |
| LOAD_GLOBAL_MODULE | 40 | 11.1% |


</details>

### UNPACK_SEQUENCE_LIST

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,304,000 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 24,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 98,304,000 | 100.0% |
| UNPACK_SEQUENCE_TUPLE | 24,000 | 0.0% |


</details>

### UNPACK_SEQUENCE_TUPLE

<details>
<summary> Successors and predecessors for UNPACK_SEQUENCE_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 98,304,000 | 100.0% |
| UNPACK_SEQUENCE_LIST | 24,000 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST_STORE_FAST | 98,304,000 | 100.0% |
| UNPACK_SEQUENCE_LIST | 24,000 | 0.0% |


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
|          hit |          180 | 90.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          300 | 26.8% |
|          hit |          600 | 53.6% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 160 | 72.7% |
| Failure | 60 | 27.3% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 100.0% |


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |       491640 | 100.0% |


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
| specialization.deferred |           20 | 6.2% |
|          hit |          280 | 87.5% |

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
| specialization.deferred |           20 | 1.9% |
|          hit |          880 | 81.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 180 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### UNPACK_SEQUENCE

<details>
<summary> specialization stats for UNPACK_SEQUENCE family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deopt |        48000 | 0.0% |
|          hit |    194112000 | 98.7% |
|         miss |      2544000 | 1.3% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 48,000 | 100.0% |
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
| Basic | 1,181,125,620 | 85.7% |
| Not specialized | 3,036,300 | 0.2% |
| Specialized | 194,605,940 | 14.1% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| CALL | 300 | 88.2% |
| LOAD_GLOBAL | 20 | 5.9% |
| LOAD_ATTR | 20 | 5.9% |
| UNPACK_SEQUENCE_TUPLE | 0 | 0.0% |
| UNPACK_SEQUENCE_LIST | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| TO_BOOL | 0 | 0.0% |
| STORE_SUBSCR | 0 | 0.0% |
| STORE_SLICE | 0 | 0.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |


</details>

### Misses by instruction

<details>
<summary> misses by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| UNPACK_SEQUENCE_TUPLE | 1,272,000 | 50.0% |
| UNPACK_SEQUENCE_LIST | 1,272,000 | 50.0% |
| STORE_FAST_STORE_FAST | 0 | 0.0% |
| STORE_FAST | 0 | 0.0% |
| RETURN_VALUE | 0 | 0.0% |
| RESUME_CHECK | 0 | 0.0% |
| PUSH_NULL | 0 | 0.0% |
| POP_TOP | 0 | 0.0% |
| NOP | 0 | 0.0% |
| LOAD_GLOBAL_MODULE | 0 | 0.0% |


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
| Allocations from freelist | 440 | 0.0% |
| Frees to freelist | 480 |  |
| Allocations | 2,957,500 | 100.0% |
| Allocations to 512 bytes | 2,957,500 | 100.0% |
| Allocations to 4 kbytes | 0 | 0.0% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 2,957,400 |  |
| New values | 0 |  |
| Interpreter increfs | 196,610,560 | 98.7% |
| Interpreter decrefs | 199,568,040 | 98.8% |
| Increfs | 2,496,220 | 1.3% |
| Decrefs | 2,496,500 | 1.2% |
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
Stats gathered on: 2023-09-18
