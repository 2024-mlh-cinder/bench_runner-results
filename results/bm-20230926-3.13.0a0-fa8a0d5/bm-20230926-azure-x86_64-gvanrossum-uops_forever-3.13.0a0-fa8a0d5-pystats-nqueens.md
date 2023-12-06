
# Pystats results

- benchmark: nqueens
- fork: gvanrossum
- ref: uops-forever
- commit hash: fa8a0d5
- commit date: 2023-09-26T21:50:08-07:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| POP_TOP | 51,823,200 | 12.8% | 12.8% |  |
| RESUME_CHECK | 47,111,580 | 11.6% | 24.4% |  |
| INTERPRETER_EXIT | 44,692,260 | 11.0% | 35.4% |  |
| ENTER_EXECUTOR | 44,559,620 | 11.0% | 46.4% |  |
| YIELD_VALUE | 42,146,160 | 10.4% | 56.8% |  |
| LOAD_FAST | 29,665,460 | 7.3% | 64.2% |  |
| LOAD_FAST_LOAD_FAST | 12,096,180 | 3.0% | 67.1% |  |
| LOAD_GLOBAL_BUILTIN | 7,511,760 | 1.9% | 69.0% |  |
| LOAD_CONST | 7,385,100 | 1.8% | 70.8% |  |
| STORE_FAST | 7,385,060 | 1.8% | 72.6% |  |
| LOAD_DEREF | 4,971,020 | 1.2% | 73.9% |  |
| RETURN_CONST | 4,965,360 | 1.2% | 75.1% |  |
| BINARY_SUBSCR_TUPLE_INT | 4,965,320 | 1.2% | 76.3% |  |
| RETURN_GENERATOR | 4,965,300 | 1.2% | 77.5% |  |
| GET_ITER | 4,965,300 | 1.2% | 78.8% |  |
| COPY_FREE_VARS | 4,965,240 | 1.2% | 80.0% |  |
| CALL_PY_EXACT_ARGS | 4,965,240 | 1.2% | 81.2% |  |
| SET_FUNCTION_ATTRIBUTE | 4,965,180 | 1.2% | 82.4% |  |
| MAKE_FUNCTION | 4,965,180 | 1.2% | 83.7% |  |
| BUILD_TUPLE | 4,965,180 | 1.2% | 84.9% |  |
| POP_JUMP_IF_FALSE | 4,838,520 | 1.2% | 86.1% |  |
| SWAP | 4,838,460 | 1.2% | 87.3% |  |
| BINARY_SUBSCR_LIST_INT | 4,838,400 | 1.2% | 88.5% |  |
| UNARY_NEGATIVE | 4,838,280 | 1.2% | 89.7% |  |
| CALL_BUILTIN_CLASS | 2,546,460 | 0.6% | 90.3% |  |
| COMPARE_OP_INT | 2,546,100 | 0.6% | 90.9% |  |
| FOR_ITER_RANGE | 2,546,040 | 0.6% | 91.5% |  |
| CALL_LEN | 2,546,040 | 0.6% | 92.2% |  |
| JUMP_FORWARD | 2,424,660 | 0.6% | 92.8% |  |
| BINARY_SUBSCR | 2,419,820 | 0.6% | 93.4% |  |
| STORE_SUBSCR | 2,419,740 | 0.6% | 94.0% |  |
| BINARY_OP_ADD_INT | 2,419,440 | 0.6% | 94.6% |  |
| JUMP_BACKWARD | 2,419,380 | 0.6% | 95.2% |  |
| FOR_ITER_LIST | 2,419,360 | 0.6% | 95.8% |  |
| COPY | 2,419,320 | 0.6% | 96.4% |  |
| BINARY_SLICE | 2,419,320 | 0.6% | 97.0% |  |
| STORE_SUBSCR_LIST_INT | 2,419,260 | 0.6% | 97.5% |  |
| STORE_DEREF | 2,419,260 | 0.6% | 98.1% |  |
| FOR_ITER_GEN | 2,419,260 | 0.6% | 98.7% |  |
| CALL_TUPLE_1 | 2,419,260 | 0.6% | 99.3% |  |
| TO_BOOL_INT | 2,419,200 | 0.6% | 99.9% |  |
| BINARY_OP_SUBTRACT_INT | 126,960 | 0.0% | 100.0% |  |
| POP_JUMP_IF_TRUE | 126,780 | 0.0% | 100.0% |  |
| CALL | 560 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 280 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 220 | 0.0% | 100.0% |  |
| BINARY_OP | 140 | 0.0% | 100.0% |  |
| MAKE_CELL | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
| STORE_SLICE | 60 | 0.0% | 100.0% |  |
| RETURN_VALUE | 60 | 0.0% | 100.0% |  |
| POP_JUMP_IF_NOT_NONE | 60 | 0.0% | 100.0% |  |
| NOP | 60 | 0.0% | 100.0% |  |
| LOAD_ATTR | 60 | 0.0% | 100.0% |  |
| END_FOR | 60 | 0.0% | 100.0% |  |
| CALL_PY_WITH_DEFAULTS | 60 | 0.0% | 100.0% |  |
| CALL_FUNCTION_EX | 60 | 0.0% | 100.0% |  |
| BUILD_SLICE | 60 | 0.0% | 100.0% |  |
| BINARY_OP_SUBTRACT_FLOAT | 60 | 0.0% | 100.0% |  |
| TO_BOOL | 20 | 0.0% | 100.0% |  |
| COMPARE_OP | 20 | 0.0% | 100.0% |  |


</details>

## Pair counts

<details>
<summary> Pair counts for top 100 pairs </summary>

|Pair | Count | Self | Cumulative | 
|---|---:|---:|---:|
| RESUME_CHECK POP_TOP | 42,146,160 | 10.4% | 10.4% |
| CACHE RESUME_CHECK | 39,727,020 | 9.8% | 20.2% |
| YIELD_VALUE INTERPRETER_EXIT | 39,726,960 | 9.8% | 30.0% |
| POP_TOP ENTER_EXECUTOR | 39,721,260 | 9.8% | 39.8% |
| ENTER_EXECUTOR YIELD_VALUE | 34,756,120 | 8.6% | 48.4% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,965,420 | 1.2% | 49.6% |
| STORE_FAST LOAD_DEREF | 4,965,380 | 1.2% | 50.8% |
| LOAD_FAST BINARY_SUBSCR_TUPLE_INT | 4,965,320 | 1.2% | 52.1% |
| LOAD_DEREF LOAD_FAST | 4,965,320 | 1.2% | 53.3% |
| RETURN_CONST INTERPRETER_EXIT | 4,965,300 | 1.2% | 54.5% |
| POP_TOP RESUME_CHECK | 4,965,300 | 1.2% | 55.7% |
| CACHE POP_TOP | 4,965,240 | 1.2% | 57.0% |
| ENTER_EXECUTOR RETURN_CONST | 4,965,220 | 1.2% | 58.2% |
| SET_FUNCTION_ATTRIBUTE LOAD_FAST | 4,965,180 | 1.2% | 59.4% |
| RESUME_CHECK LOAD_FAST | 4,965,180 | 1.2% | 60.6% |
| MAKE_FUNCTION SET_FUNCTION_ATTRIBUTE | 4,965,180 | 1.2% | 61.9% |
| LOAD_FAST BUILD_TUPLE | 4,965,180 | 1.2% | 63.1% |
| LOAD_CONST MAKE_FUNCTION | 4,965,180 | 1.2% | 64.3% |
| COPY_FREE_VARS RETURN_GENERATOR | 4,965,180 | 1.2% | 65.5% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 4,965,180 | 1.2% | 66.8% |
| BUILD_TUPLE LOAD_CONST | 4,965,180 | 1.2% | 68.0% |
| GET_ITER CALL_PY_EXACT_ARGS | 4,965,160 | 1.2% | 69.2% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 4,838,340 | 1.2% | 70.4% |
| LOAD_FAST_LOAD_FAST UNARY_NEGATIVE | 4,838,280 | 1.2% | 71.6% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 2,546,120 | 0.6% | 72.2% |
| FOR_ITER_RANGE STORE_FAST | 2,546,040 | 0.6% | 72.9% |
| RETURN_GENERATOR CALL_BUILTIN_CLASS | 2,546,020 | 0.6% | 73.5% |
| LOAD_FAST GET_ITER | 2,545,980 | 0.6% | 74.1% |
| LOAD_FAST FOR_ITER_RANGE | 2,545,980 | 0.6% | 74.7% |
| CALL_BUILTIN_CLASS CALL_LEN | 2,545,980 | 0.6% | 75.4% |
| BINARY_SUBSCR_TUPLE_INT LOAD_FAST | 2,545,980 | 0.6% | 76.0% |
| LOAD_FAST LOAD_CONST | 2,419,380 | 0.6% | 76.6% |
| FOR_ITER_LIST STORE_FAST | 2,419,340 | 0.6% | 77.2% |
| BINARY_SUBSCR_TUPLE_INT YIELD_VALUE | 2,419,340 | 0.6% | 77.8% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,419,320 | 0.6% | 78.4% |
| YIELD_VALUE STORE_DEREF | 2,419,200 | 0.6% | 79.0% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,419,200 | 0.6% | 79.6% |
| SWAP COPY | 2,419,200 | 0.6% | 80.2% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 2,419,200 | 0.6% | 80.8% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 2,419,200 | 0.6% | 81.4% |
| STORE_DEREF LOAD_FAST | 2,419,200 | 0.6% | 82.0% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 2,419,200 | 0.6% | 82.6% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 2,419,200 | 0.6% | 83.2% |
| LOAD_FAST FOR_ITER_LIST | 2,419,200 | 0.6% | 83.8% |
| LOAD_FAST BINARY_SLICE | 2,419,200 | 0.6% | 84.3% |
| LOAD_FAST BINARY_OP_ADD_INT | 2,419,200 | 0.6% | 84.9% |
| LOAD_CONST LOAD_FAST | 2,419,200 | 0.6% | 85.5% |
| JUMP_BACKWARD FOR_ITER_GEN | 2,419,200 | 0.6% | 86.1% |
| FOR_ITER_GEN RESUME_CHECK | 2,419,200 | 0.6% | 86.7% |
| COPY COMPARE_OP_INT | 2,419,200 | 0.6% | 87.3% |
| CALL_TUPLE_1 YIELD_VALUE | 2,419,200 | 0.6% | 87.9% |
| CALL_LEN SWAP | 2,419,200 | 0.6% | 88.5% |
| BINARY_SLICE GET_ITER | 2,419,200 | 0.6% | 89.1% |
| BINARY_OP_ADD_INT YIELD_VALUE | 2,419,200 | 0.6% | 89.7% |
| RETURN_GENERATOR CALL_TUPLE_1 | 2,419,180 | 0.6% | 90.3% |
| LOAD_FAST TO_BOOL_INT | 2,419,180 | 0.6% | 90.9% |
| UNARY_NEGATIVE STORE_SUBSCR | 2,419,140 | 0.6% | 91.5% |
| UNARY_NEGATIVE BINARY_SUBSCR | 2,419,140 | 0.6% | 92.1% |
| SWAP LOAD_FAST_LOAD_FAST | 2,419,140 | 0.6% | 92.7% |
| STORE_SUBSCR LOAD_GLOBAL_BUILTIN | 2,419,140 | 0.6% | 93.3% |
| POP_TOP POP_TOP | 2,419,140 | 0.6% | 93.9% |
| POP_TOP JUMP_FORWARD | 2,419,140 | 0.6% | 94.5% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 2,419,140 | 0.6% | 95.1% |
| JUMP_FORWARD LOAD_FAST | 2,419,140 | 0.6% | 95.7% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 2,419,140 | 0.6% | 96.3% |
| ENTER_EXECUTOR ENTER_EXECUTOR | 2,419,140 | 0.6% | 96.9% |
| BINARY_SUBSCR_LIST_INT SWAP | 2,419,140 | 0.6% | 97.5% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 2,419,140 | 0.6% | 98.1% |
| BINARY_SUBSCR LOAD_FAST_LOAD_FAST | 2,419,140 | 0.6% | 98.7% |
| POP_TOP JUMP_BACKWARD | 2,298,120 | 0.6% | 99.2% |
| POP_JUMP_IF_FALSE POP_TOP | 2,292,420 | 0.6% | 99.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 126,840 | 0.0% | 99.8% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 126,780 | 0.0% | 99.9% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 126,780 | 0.0% | 99.9% |
| CALL_LEN COMPARE_OP_INT | 126,780 | 0.0% | 99.9% |
| BINARY_OP_SUBTRACT_INT YIELD_VALUE | 126,780 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 121,260 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE JUMP_FORWARD | 5,520 | 0.0% | 100.0% |
| LOAD_DEREF YIELD_VALUE | 5,520 | 0.0% | 100.0% |
| JUMP_FORWARD LOAD_DEREF | 5,520 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR | 620 | 0.0% | 100.0% |
| STORE_SUBSCR STORE_SUBSCR | 600 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 240 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |
| LOAD_CONST BINARY_OP_ADD_INT | 200 | 0.0% | 100.0% |
| LOAD_GLOBAL LOAD_GLOBAL_BUILTIN | 180 | 0.0% | 100.0% |
| LOAD_FAST PUSH_NULL | 180 | 0.0% | 100.0% |
| JUMP_BACKWARD FOR_ITER_LIST | 160 | 0.0% | 100.0% |
| LOAD_FAST CALL_BUILTIN_CLASS | 140 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS CALL_BUILTIN_CLASS | 140 | 0.0% | 100.0% |
| STORE_FAST LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| RESUME_CHECK LOAD_GLOBAL_BUILTIN | 120 | 0.0% | 100.0% |
| POP_TOP LOAD_FAST | 120 | 0.0% | 100.0% |
| MAKE_CELL RETURN_GENERATOR | 120 | 0.0% | 100.0% |
| LOAD_GLOBAL_MODULE LOAD_FAST | 120 | 0.0% | 100.0% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 120 | 0.0% | 100.0% |
| LOAD_CONST LOAD_CONST | 120 | 0.0% | 100.0% |
| CALL_BUILTIN_CLASS STORE_FAST | 120 | 0.0% | 100.0% |
| CALL POP_TOP | 120 | 0.0% | 100.0% |
| CALL CALL_BUILTIN_CLASS | 120 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,419,200 | 100.0% |
| LOAD_CONST | 60 | 0.0% |
| BINARY_OP_ADD_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 2,419,200 | 100.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| BINARY_OP | 60 | 0.0% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 100.0% |


</details>

### CACHE

<details>
<summary> Successors and predecessors for CACHE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 39,727,020 | 88.9% |
| POP_TOP | 4,965,240 | 11.1% |


</details>

### BINARY_SUBSCR

<details>
<summary> Successors and predecessors for BINARY_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNARY_NEGATIVE | 2,419,140 | 100.0% |
| BINARY_SUBSCR | 620 | 0.0% |
| BUILD_SLICE | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,419,140 | 100.0% |
| BINARY_SUBSCR | 620 | 0.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### END_FOR

<details>
<summary> Successors and predecessors for END_FOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_CONST | 60 | 100.0% |


</details>

### GET_ITER

<details>
<summary> Successors and predecessors for GET_ITER </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,545,980 | 51.3% |
| BINARY_SLICE | 2,419,200 | 48.7% |
| RETURN_GENERATOR | 60 | 0.0% |
| CALL_BUILTIN_CLASS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,965,160 | 100.0% |
| FOR_ITER_RANGE | 60 | 0.0% |
| FOR_ITER_GEN | 60 | 0.0% |
| CALL | 20 | 0.0% |


</details>

### INTERPRETER_EXIT

<details>
<summary> Successors and predecessors for INTERPRETER_EXIT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 39,726,960 | 88.9% |
| RETURN_CONST | 4,965,300 | 11.1% |

|Successors | Count | Percentage | 
|---|---:|---:|


</details>

### MAKE_FUNCTION

<details>
<summary> Successors and predecessors for MAKE_FUNCTION </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,965,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SET_FUNCTION_ATTRIBUTE | 4,965,180 | 100.0% |


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
| RESUME_CHECK | 42,146,160 | 81.3% |
| CACHE | 4,965,240 | 9.6% |
| POP_TOP | 2,419,140 | 4.7% |
| POP_JUMP_IF_FALSE | 2,292,420 | 4.4% |
| CALL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 39,721,260 | 76.6% |
| RESUME_CHECK | 4,965,300 | 9.6% |
| POP_TOP | 2,419,140 | 4.7% |
| JUMP_FORWARD | 2,419,140 | 4.7% |
| JUMP_BACKWARD | 2,298,120 | 4.4% |


</details>

### PUSH_NULL

<details>
<summary> Successors and predecessors for PUSH_NULL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 180 | 60.0% |
| LOAD_DEREF | 60 | 20.0% |
| LOAD_ATTR_MODULE | 40 | 13.3% |
| LOAD_ATTR | 20 | 6.7% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL | 240 | 80.0% |
| LOAD_FAST | 60 | 20.0% |


</details>

### RETURN_GENERATOR

<details>
<summary> Successors and predecessors for RETURN_GENERATOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 4,965,180 | 100.0% |
| MAKE_CELL | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,546,020 | 51.3% |
| CALL_TUPLE_1 | 2,419,180 | 48.7% |
| GET_ITER | 60 | 0.0% |
| CALL | 40 | 0.0% |


</details>

### RETURN_VALUE

<details>
<summary> Successors and predecessors for RETURN_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 40 | 66.7% |
| LOAD_GLOBAL_MODULE | 20 | 33.3% |


</details>

### STORE_SUBSCR

<details>
<summary> Successors and predecessors for STORE_SUBSCR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| UNARY_NEGATIVE | 2,419,140 | 100.0% |
| STORE_SUBSCR | 600 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,419,140 | 100.0% |
| STORE_SUBSCR | 600 | 0.0% |


</details>

### TO_BOOL

<details>
<summary> Successors and predecessors for TO_BOOL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| TO_BOOL_INT | 20 | 100.0% |


</details>

### UNARY_NEGATIVE

<details>
<summary> Successors and predecessors for UNARY_NEGATIVE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,838,280 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR | 2,419,140 | 50.0% |
| BINARY_SUBSCR | 2,419,140 | 50.0% |


</details>

### BINARY_OP

<details>
<summary> Successors and predecessors for BINARY_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 60 | 42.9% |
| LOAD_CONST | 40 | 28.6% |
| LOAD_FAST_LOAD_FAST | 20 | 14.3% |
| LOAD_FAST | 20 | 14.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 60 | 42.9% |
| BINARY_OP_ADD_INT | 40 | 28.6% |
| BINARY_OP_SUBTRACT_INT | 20 | 14.3% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 14.3% |


</details>

### BUILD_SLICE

<details>
<summary> Successors and predecessors for BUILD_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR | 60 | 100.0% |


</details>

### BUILD_TUPLE

<details>
<summary> Successors and predecessors for BUILD_TUPLE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,965,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,965,180 | 100.0% |


</details>

### CALL

<details>
<summary> Successors and predecessors for CALL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| PUSH_NULL | 240 | 42.9% |
| LOAD_FAST | 100 | 17.9% |
| CALL | 80 | 14.3% |
| RETURN_GENERATOR | 40 | 7.1% |
| CALL_BUILTIN_CLASS | 40 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 120 | 21.4% |
| CALL_BUILTIN_CLASS | 120 | 21.4% |
| CALL | 80 | 14.3% |
| STORE_FAST | 60 | 10.7% |
| LOAD_FAST | 60 | 10.7% |


</details>

### CALL_FUNCTION_EX

<details>
<summary> Successors and predecessors for CALL_FUNCTION_EX </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 60 | 100.0% |


</details>

### COMPARE_OP

<details>
<summary> Successors and predecessors for COMPARE_OP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 20 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 20 | 100.0% |


</details>

### COPY

<details>
<summary> Successors and predecessors for COPY </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,419,200 | 100.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,419,200 | 100.0% |
| COPY | 60 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 60 | 0.0% |


</details>

### COPY_FREE_VARS

<details>
<summary> Successors and predecessors for COPY_FREE_VARS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_EXACT_ARGS | 4,965,180 | 100.0% |
| CALL_FUNCTION_EX | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 4,965,180 | 100.0% |
| RESUME_CHECK | 60 | 0.0% |


</details>

### ENTER_EXECUTOR

<details>
<summary> Successors and predecessors for ENTER_EXECUTOR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 39,721,260 | 89.1% |
| POP_JUMP_IF_FALSE | 2,419,140 | 5.4% |
| ENTER_EXECUTOR | 2,419,140 | 5.4% |
| STORE_SUBSCR_LIST_INT | 60 | 0.0% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 34,756,120 | 78.0% |
| RETURN_CONST | 4,965,220 | 11.1% |
| LOAD_FAST_LOAD_FAST | 2,419,140 | 5.4% |
| ENTER_EXECUTOR | 2,419,140 | 5.4% |


</details>

### JUMP_BACKWARD

<details>
<summary> Successors and predecessors for JUMP_BACKWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,298,120 | 95.0% |
| POP_JUMP_IF_TRUE | 121,260 | 5.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_GEN | 2,419,200 | 100.0% |
| FOR_ITER_LIST | 160 | 0.0% |
| ENTER_EXECUTOR | 20 | 0.0% |


</details>

### JUMP_FORWARD

<details>
<summary> Successors and predecessors for JUMP_FORWARD </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 2,419,140 | 99.8% |
| POP_JUMP_IF_TRUE | 5,520 | 0.2% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,419,140 | 99.8% |
| LOAD_DEREF | 5,520 | 0.2% |


</details>

### LOAD_ATTR

<details>
<summary> Successors and predecessors for LOAD_ATTR </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 40 | 66.7% |
| LOAD_GLOBAL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_ATTR_MODULE | 40 | 66.7% |
| PUSH_NULL | 20 | 33.3% |


</details>

### LOAD_CONST

<details>
<summary> Successors and predecessors for LOAD_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BUILD_TUPLE | 4,965,180 | 67.2% |
| LOAD_FAST | 2,419,380 | 32.8% |
| LOAD_FAST_LOAD_FAST | 120 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| BINARY_SUBSCR_LIST_INT | 120 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,965,180 | 67.2% |
| LOAD_FAST | 2,419,200 | 32.8% |
| BINARY_OP_ADD_INT | 200 | 0.0% |
| LOAD_CONST | 120 | 0.0% |
| COMPARE_OP_INT | 100 | 0.0% |


</details>

### LOAD_DEREF

<details>
<summary> Successors and predecessors for LOAD_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 4,965,380 | 99.9% |
| JUMP_FORWARD | 5,520 | 0.1% |
| NOP | 60 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,965,320 | 99.9% |
| YIELD_VALUE | 5,520 | 0.1% |
| STORE_FAST | 60 | 0.0% |
| PUSH_NULL | 60 | 0.0% |
| CALL_LEN | 40 | 0.0% |


</details>

### LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 4,965,420 | 16.7% |
| LOAD_DEREF | 4,965,320 | 16.7% |
| SET_FUNCTION_ATTRIBUTE | 4,965,180 | 16.7% |
| RESUME_CHECK | 4,965,180 | 16.7% |
| BINARY_SUBSCR_TUPLE_INT | 2,545,980 | 8.6% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 4,965,320 | 16.7% |
| BUILD_TUPLE | 4,965,180 | 16.7% |
| GET_ITER | 2,545,980 | 8.6% |
| FOR_ITER_RANGE | 2,545,980 | 8.6% |
| LOAD_CONST | 2,419,380 | 8.2% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 2,419,200 | 20.0% |
| STORE_FAST | 2,419,200 | 20.0% |
| SWAP | 2,419,140 | 20.0% |
| ENTER_EXECUTOR | 2,419,140 | 20.0% |
| BINARY_SUBSCR | 2,419,140 | 20.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_LIST_INT | 4,838,340 | 40.0% |
| UNARY_NEGATIVE | 4,838,280 | 40.0% |
| STORE_SUBSCR_LIST_INT | 2,419,200 | 20.0% |
| LOAD_CONST | 120 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 100 | 0.0% |


</details>

### LOAD_GLOBAL

<details>
<summary> Successors and predecessors for LOAD_GLOBAL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 80 | 28.6% |
| RESUME_CHECK | 80 | 28.6% |
| LOAD_GLOBAL_BUILTIN | 60 | 21.4% |
| RETURN_VALUE | 40 | 14.3% |
| STORE_DEREF | 20 | 7.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 180 | 64.3% |
| LOAD_GLOBAL_MODULE | 80 | 28.6% |
| LOAD_ATTR | 20 | 7.1% |


</details>

### MAKE_CELL

<details>
<summary> Successors and predecessors for MAKE_CELL </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_PY_WITH_DEFAULTS | 60 | 50.0% |
| CALL_PY_EXACT_ARGS | 60 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 120 | 100.0% |


</details>

### POP_JUMP_IF_FALSE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_FALSE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 2,419,320 | 50.0% |
| TO_BOOL_INT | 2,419,200 | 50.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 2,419,140 | 50.0% |
| POP_TOP | 2,292,420 | 47.4% |
| LOAD_GLOBAL_BUILTIN | 126,840 | 2.6% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_FAST | 60 | 0.0% |


</details>

### POP_JUMP_IF_NOT_NONE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_NOT_NONE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 60 | 100.0% |


</details>

### POP_JUMP_IF_TRUE

<details>
<summary> Successors and predecessors for POP_JUMP_IF_TRUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COMPARE_OP_INT | 126,780 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 121,260 | 95.6% |
| JUMP_FORWARD | 5,520 | 4.4% |


</details>

### RETURN_CONST

<details>
<summary> Successors and predecessors for RETURN_CONST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,965,220 | 100.0% |
| POP_TOP | 60 | 0.0% |
| END_FOR | 60 | 0.0% |
| FOR_ITER_LIST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 4,965,300 | 100.0% |
| END_FOR | 60 | 0.0% |


</details>

### SET_FUNCTION_ATTRIBUTE

<details>
<summary> Successors and predecessors for SET_FUNCTION_ATTRIBUTE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,965,180 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,965,180 | 100.0% |


</details>

### STORE_DEREF

<details>
<summary> Successors and predecessors for STORE_DEREF </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 2,419,200 | 100.0% |
| CALL_TUPLE_1 | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,419,200 | 100.0% |
| LOAD_GLOBAL_BUILTIN | 40 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |


</details>

### STORE_FAST

<details>
<summary> Successors and predecessors for STORE_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| FOR_ITER_RANGE | 2,546,040 | 34.5% |
| FOR_ITER_LIST | 2,419,340 | 32.8% |
| BINARY_SUBSCR_LIST_INT | 2,419,140 | 32.8% |
| CALL_BUILTIN_CLASS | 120 | 0.0% |
| LOAD_FAST | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_DEREF | 4,965,380 | 67.2% |
| LOAD_FAST_LOAD_FAST | 2,419,200 | 32.8% |
| LOAD_FAST | 240 | 0.0% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |


</details>

### SWAP

<details>
<summary> Successors and predecessors for SWAP </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 2,419,200 | 50.0% |
| BINARY_SUBSCR_LIST_INT | 2,419,140 | 50.0% |
| SWAP | 60 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,419,200 | 50.0% |
| LOAD_FAST_LOAD_FAST | 2,419,140 | 50.0% |
| SWAP | 60 | 0.0% |
| STORE_SUBSCR_LIST_INT | 60 | 0.0% |


</details>

### YIELD_VALUE

<details>
<summary> Successors and predecessors for YIELD_VALUE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 34,756,120 | 82.5% |
| BINARY_SUBSCR_TUPLE_INT | 2,419,340 | 5.7% |
| CALL_TUPLE_1 | 2,419,200 | 5.7% |
| BINARY_OP_ADD_INT | 2,419,200 | 5.7% |
| BINARY_OP_SUBTRACT_INT | 126,780 | 0.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| INTERPRETER_EXIT | 39,726,960 | 94.3% |
| STORE_DEREF | 2,419,200 | 5.7% |


</details>

### BINARY_OP_ADD_INT

<details>
<summary> Successors and predecessors for BINARY_OP_ADD_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,419,200 | 100.0% |
| LOAD_CONST | 200 | 0.0% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 2,419,200 | 100.0% |
| LOAD_FAST | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |
| BINARY_SLICE | 60 | 0.0% |
| CALL_BUILTIN_CLASS | 40 | 0.0% |


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
| STORE_FAST | 60 | 100.0% |


</details>

### BINARY_OP_SUBTRACT_INT

<details>
<summary> Successors and predecessors for BINARY_OP_SUBTRACT_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 126,780 | 99.9% |
| LOAD_FAST_LOAD_FAST | 100 | 0.1% |
| LOAD_CONST | 60 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 126,780 | 99.9% |
| SWAP | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### BINARY_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,838,340 | 100.0% |
| COPY | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,419,140 | 50.0% |
| STORE_FAST | 2,419,140 | 50.0% |
| LOAD_CONST | 120 | 0.0% |


</details>

### BINARY_SUBSCR_TUPLE_INT

<details>
<summary> Successors and predecessors for BINARY_SUBSCR_TUPLE_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,965,320 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,545,980 | 51.3% |
| YIELD_VALUE | 2,419,340 | 48.7% |


</details>

### CALL_BUILTIN_CLASS

<details>
<summary> Successors and predecessors for CALL_BUILTIN_CLASS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 2,546,020 | 100.0% |
| LOAD_FAST | 140 | 0.0% |
| CALL_BUILTIN_CLASS | 140 | 0.0% |
| CALL | 120 | 0.0% |
| BINARY_OP_ADD_INT | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| CALL_LEN | 2,545,980 | 100.0% |
| CALL_BUILTIN_CLASS | 140 | 0.0% |
| STORE_FAST | 120 | 0.0% |
| POP_TOP | 60 | 0.0% |
| LOAD_CONST | 60 | 0.0% |


</details>

### CALL_LEN

<details>
<summary> Successors and predecessors for CALL_LEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CALL_BUILTIN_CLASS | 2,545,980 | 100.0% |
| LOAD_DEREF | 40 | 0.0% |
| CALL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| SWAP | 2,419,200 | 95.0% |
| COMPARE_OP_INT | 126,780 | 5.0% |
| STORE_FAST | 60 | 0.0% |


</details>

### CALL_PY_EXACT_ARGS

<details>
<summary> Successors and predecessors for CALL_PY_EXACT_ARGS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| GET_ITER | 4,965,160 | 100.0% |
| LOAD_FAST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| COPY_FREE_VARS | 4,965,180 | 100.0% |
| MAKE_CELL | 60 | 0.0% |


</details>

### CALL_PY_WITH_DEFAULTS

<details>
<summary> Successors and predecessors for CALL_PY_WITH_DEFAULTS </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 40 | 66.7% |
| CALL | 20 | 33.3% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_CELL | 60 | 100.0% |


</details>

### CALL_TUPLE_1

<details>
<summary> Successors and predecessors for CALL_TUPLE_1 </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| RETURN_GENERATOR | 2,419,180 | 100.0% |
| LOAD_FAST | 40 | 0.0% |
| CALL | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 2,419,200 | 100.0% |
| STORE_DEREF | 60 | 0.0% |


</details>

### COMPARE_OP_INT

<details>
<summary> Successors and predecessors for COMPARE_OP_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| COPY | 2,419,200 | 95.0% |
| CALL_LEN | 126,780 | 5.0% |
| LOAD_CONST | 100 | 0.0% |
| COMPARE_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,419,320 | 95.0% |
| POP_JUMP_IF_TRUE | 126,780 | 5.0% |


</details>

### FOR_ITER_GEN

<details>
<summary> Successors and predecessors for FOR_ITER_GEN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| JUMP_BACKWARD | 2,419,200 | 100.0% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| RESUME_CHECK | 2,419,200 | 100.0% |
| POP_TOP | 60 | 0.0% |


</details>

### FOR_ITER_LIST

<details>
<summary> Successors and predecessors for FOR_ITER_LIST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,419,200 | 100.0% |
| JUMP_BACKWARD | 160 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,419,340 | 100.0% |
| RETURN_CONST | 20 | 0.0% |


</details>

### FOR_ITER_RANGE

<details>
<summary> Successors and predecessors for FOR_ITER_RANGE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,545,980 | 100.0% |
| GET_ITER | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 2,546,040 | 100.0% |


</details>

### LOAD_ATTR_MODULE

<details>
<summary> Successors and predecessors for LOAD_ATTR_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_MODULE | 60 | 60.0% |
| LOAD_ATTR | 40 | 40.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_FAST | 60 | 60.0% |
| PUSH_NULL | 40 | 40.0% |


</details>

### LOAD_GLOBAL_BUILTIN

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_BUILTIN </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL_BUILTIN | 2,546,120 | 33.9% |
| LOAD_FAST | 2,419,200 | 32.2% |
| STORE_SUBSCR | 2,419,140 | 32.2% |
| POP_JUMP_IF_FALSE | 126,840 | 1.7% |
| LOAD_GLOBAL | 180 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 4,965,420 | 66.1% |
| LOAD_GLOBAL_BUILTIN | 2,546,120 | 33.9% |
| LOAD_GLOBAL | 60 | 0.0% |
| LOAD_FAST_LOAD_FAST | 60 | 0.0% |
| LOAD_DEREF | 60 | 0.0% |


</details>

### LOAD_GLOBAL_MODULE

<details>
<summary> Successors and predecessors for LOAD_GLOBAL_MODULE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_GLOBAL | 80 | 36.4% |
| STORE_FAST | 40 | 18.2% |
| RESUME_CHECK | 40 | 18.2% |
| LOAD_GLOBAL_BUILTIN | 40 | 18.2% |
| RETURN_VALUE | 20 | 9.1% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 120 | 54.5% |
| LOAD_ATTR_MODULE | 60 | 27.3% |
| LOAD_ATTR | 40 | 18.2% |


</details>

### RESUME_CHECK

<details>
<summary> Successors and predecessors for RESUME_CHECK </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| CACHE | 39,727,020 | 84.3% |
| POP_TOP | 4,965,300 | 10.5% |
| FOR_ITER_GEN | 2,419,200 | 5.1% |
| COPY_FREE_VARS | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_TOP | 42,146,160 | 89.5% |
| LOAD_FAST | 4,965,180 | 10.5% |
| LOAD_GLOBAL_BUILTIN | 120 | 0.0% |
| LOAD_GLOBAL | 80 | 0.0% |
| LOAD_GLOBAL_MODULE | 40 | 0.0% |


</details>

### STORE_SUBSCR_LIST_INT

<details>
<summary> Successors and predecessors for STORE_SUBSCR_LIST_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,419,200 | 100.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 2,419,200 | 100.0% |
| ENTER_EXECUTOR | 60 | 0.0% |


</details>

### TO_BOOL_INT

<details>
<summary> Successors and predecessors for TO_BOOL_INT </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST | 2,419,180 | 100.0% |
| TO_BOOL | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| POP_JUMP_IF_FALSE | 2,419,200 | 100.0% |


</details>


</details>

## Specialization stats

<details>
<summary> specialization stats by family </summary>

### BINARY_SLICE

<details>
<summary> specialization stats for BINARY_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### STORE_SLICE

<details>
<summary> specialization stats for STORE_SLICE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>

### BINARY_SUBSCR

<details>
<summary> specialization stats for BINARY_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2419200 | 4.0% |
|          hit |     57711720 | 96.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 620 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 600 | 96.8% |
| list slice | 20 | 3.2% |


</details>

### STORE_SUBSCR

<details>
<summary> specialization stats for STORE_SUBSCR family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |      2419140 | 15.5% |
|          hit |     13152000 | 84.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 0 | 0.0% |
| Failure | 600 | 100.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| out of range | 600 | 100.0% |


</details>

### TO_BOOL

<details>
<summary> specialization stats for TO_BOOL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      2419200 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### BINARY_OP

<details>
<summary> specialization stats for BINARY_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |           60 | 0.0% |
|          hit |     39414660 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          240 | 0.0% |
|          hit |     17315340 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 240 | 75.0% |
| Failure | 80 | 25.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| cfunc noargs | 60 | 75.0% |
| other | 20 | 25.0% |


</details>

### COMPARE_OP

<details>
<summary> specialization stats for COMPARE_OP family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      9122040 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 20 | 100.0% |
| Failure | 0 | 0.0% |

|Failure kind | Count | Ratio | 
|---|---:|---:|


</details>

### FOR_ITER

<details>
<summary> specialization stats for FOR_ITER family </summary>

|Kind | Count | Ratio | 
|---|---|---|
|          hit |      7384660 | 100.0% |


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
| specialization.deferred |           20 | 12.5% |
|          hit |          100 | 62.5% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 40 | 100.0% |
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
|          hit |     12350260 | 100.0% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 260 | 100.0% |
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

### POP_JUMP_IF_TRUE

<details>
<summary> specialization stats for POP_JUMP_IF_TRUE family </summary>

|Kind | Count | Ratio | 
|---|---|---|


</details>


</details>

## Specialization effectiveness

<details>
<summary> specialization effectiveness </summary>

|Instructions | Count | Ratio | 
|---|---:|---:|
| Basic | 296,421,500 | 73.1% |
| Not specialized | 14,644,760 | 3.6% |
| Specialized | 94,220,120 | 23.2% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_SUBSCR | 2,419,200 | 50.0% |
| STORE_SUBSCR | 2,419,140 | 50.0% |
| CALL | 240 | 0.0% |
| BINARY_OP | 60 | 0.0% |
| LOAD_GLOBAL | 20 | 0.0% |
| LOAD_ATTR | 20 | 0.0% |
| YIELD_VALUE | 0 | 0.0% |
| UNPACK_SEQUENCE | 0 | 0.0% |
| UNARY_NEGATIVE | 0 | 0.0% |
| TO_BOOL_INT | 0 | 0.0% |


</details>


</details>

## Call stats

<details>
<summary> Inlined calls and frame stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Calls to PyEval_EvalDefault | 44,692,260 | 85.8% |
| Calls to Python functions inlined | 7,384,620 | 14.2% |
| Calls via PyEval_EvalFrame (total) | 44,692,260 | 85.8% |
| Calls via PyEval_EvalFrame (vector) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (generator) | 44,692,200 | 85.8% |
| Calls via PyEval_EvalFrame (legacy) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function vectorcall) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (build class) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (slot) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (function ex) | 60 | 0.0% |
| Calls via PyEval_EvalFrame (api) | 0 | 0.0% |
| Calls via PyEval_EvalFrame (method) | 0 | 0.0% |
| Frames pushed | 4,965,420 | 9.5% |
| Frame objects created | 0 | 0.0% |


</details>

## Object stats

<details>
<summary> allocations, frees and dict materializatons </summary>

| | Count | Ratio | 
|---|---:|---:|
| Allocations from freelist | 19,855,180 | 32.1% |
| Frees to freelist | 19,855,320 |  |
| Allocations | 41,985,340 | 67.9% |
| Allocations to 512 bytes | 39,615,160 | 64.1% |
| Allocations to 4 kbytes | 2,370,180 | 3.8% |
| Allocations over 4 kbytes | 0 | 0.0% |
| Frees | 41,985,120 |  |
| New values | 0 |  |
| Interpreter increfs | 98,930,300 | 46.8% |
| Interpreter decrefs | 71,555,580 | 26.2% |
| Increfs | 112,342,300 | 53.2% |
| Decrefs | 201,606,300 | 73.8% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 19 |  |
| Method cache misses | 1 |  |
| Method cache collisions | 1 |  |
| Method cache dunder hits | 4,838,460 |  |
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
Stats gathered on: 2023-09-27
