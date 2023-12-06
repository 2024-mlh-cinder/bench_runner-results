
# Pystats results

- benchmark: nqueens
- fork: mdboom
- ref: collect-tier2-stats
- commit hash: 9e1c90d
- commit date: 2023-10-03T12:01:22-04:00

## Execution counts

<details>
<summary> execution counts for all instructions </summary>

|Name | Count | Self | Cumulative | Miss ratio | 
|---|---:|---:|---:|---:|
| POP_TOP | 51,823,200 | 11.1% | 11.1% |  |
| RESUME_CHECK | 47,111,580 | 10.1% | 21.3% |  |
| ENTER_EXECUTOR | 46,297,280 | 9.9% | 31.2% |  |
| INTERPRETER_EXIT | 44,692,260 | 9.6% | 40.8% |  |
| YIELD_VALUE | 42,146,160 | 9.1% | 49.9% |  |
| LOAD_FAST | 32,084,600 | 6.9% | 56.7% |  |
| LOAD_FAST_LOAD_FAST | 26,985,720 | 5.8% | 62.5% |  |
| LOAD_CONST | 18,799,320 | 4.0% | 66.6% |  |
| BINARY_OP_ADD_INT | 8,995,380 | 1.9% | 68.5% |  |
| BINARY_SLICE | 8,995,260 | 1.9% | 70.4% |  |
| LOAD_GLOBAL_BUILTIN | 7,511,760 | 1.6% | 72.1% |  |
| STORE_FAST | 7,385,060 | 1.6% | 73.6% |  |
| STORE_SUBSCR_LIST_INT | 6,576,060 | 1.4% | 75.1% |  |
| LOAD_DEREF | 4,971,020 | 1.1% | 76.1% |  |
| RETURN_CONST | 4,965,360 | 1.1% | 77.2% |  |
| BINARY_SUBSCR_TUPLE_INT | 4,965,320 | 1.1% | 78.3% |  |
| RETURN_GENERATOR | 4,965,300 | 1.1% | 79.3% |  |
| GET_ITER | 4,965,300 | 1.1% | 80.4% |  |
| COPY_FREE_VARS | 4,965,240 | 1.1% | 81.5% |  |
| CALL_PY_EXACT_ARGS | 4,965,240 | 1.1% | 82.5% |  |
| SET_FUNCTION_ATTRIBUTE | 4,965,180 | 1.1% | 83.6% |  |
| MAKE_FUNCTION | 4,965,180 | 1.1% | 84.7% |  |
| BUILD_TUPLE | 4,965,180 | 1.1% | 85.7% |  |
| POP_JUMP_IF_FALSE | 4,838,520 | 1.0% | 86.8% |  |
| SWAP | 4,838,460 | 1.0% | 87.8% |  |
| BINARY_SUBSCR_LIST_INT | 4,838,400 | 1.0% | 88.8% |  |
| UNARY_NEGATIVE | 4,838,280 | 1.0% | 89.9% |  |
| BINARY_OP_SUBTRACT_INT | 4,283,760 | 0.9% | 90.8% |  |
| BINARY_OP | 4,157,960 | 0.9% | 91.7% |  |
| STORE_SLICE | 4,156,860 | 0.9% | 92.6% |  |
| CALL_BUILTIN_CLASS | 2,546,460 | 0.5% | 93.1% |  |
| COMPARE_OP_INT | 2,546,100 | 0.5% | 93.7% |  |
| FOR_ITER_RANGE | 2,546,040 | 0.5% | 94.2% |  |
| CALL_LEN | 2,546,040 | 0.5% | 94.8% |  |
| JUMP_FORWARD | 2,424,660 | 0.5% | 95.3% |  |
| BINARY_SUBSCR | 2,419,820 | 0.5% | 95.8% |  |
| STORE_SUBSCR | 2,419,740 | 0.5% | 96.3% |  |
| JUMP_BACKWARD | 2,419,380 | 0.5% | 96.9% |  |
| FOR_ITER_LIST | 2,419,360 | 0.5% | 97.4% |  |
| COPY | 2,419,320 | 0.5% | 97.9% |  |
| STORE_DEREF | 2,419,260 | 0.5% | 98.4% |  |
| FOR_ITER_GEN | 2,419,260 | 0.5% | 98.9% |  |
| CALL_TUPLE_1 | 2,419,260 | 0.5% | 99.5% |  |
| TO_BOOL_INT | 2,419,200 | 0.5% | 100.0% |  |
| POP_JUMP_IF_TRUE | 126,780 | 0.0% | 100.0% |  |
| CALL | 560 | 0.0% | 100.0% |  |
| PUSH_NULL | 300 | 0.0% | 100.0% |  |
| LOAD_GLOBAL | 280 | 0.0% | 100.0% |  |
| LOAD_GLOBAL_MODULE | 220 | 0.0% | 100.0% |  |
| MAKE_CELL | 120 | 0.0% | 100.0% |  |
| LOAD_ATTR_MODULE | 100 | 0.0% | 100.0% |  |
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
| RESUME_CHECK POP_TOP | 42,146,160 | 9.1% | 9.1% |
| CACHE RESUME_CHECK | 39,727,020 | 8.5% | 17.6% |
| YIELD_VALUE INTERPRETER_EXIT | 39,726,960 | 8.5% | 26.1% |
| POP_TOP ENTER_EXECUTOR | 39,721,260 | 8.5% | 34.7% |
| ENTER_EXECUTOR YIELD_VALUE | 34,756,120 | 7.5% | 42.1% |
| LOAD_FAST_LOAD_FAST STORE_SUBSCR_LIST_INT | 6,576,000 | 1.4% | 43.5% |
| LOAD_GLOBAL_BUILTIN LOAD_FAST | 4,965,420 | 1.1% | 44.6% |
| STORE_FAST LOAD_DEREF | 4,965,380 | 1.1% | 45.7% |
| LOAD_FAST BINARY_SUBSCR_TUPLE_INT | 4,965,320 | 1.1% | 46.7% |
| LOAD_DEREF LOAD_FAST | 4,965,320 | 1.1% | 47.8% |
| RETURN_CONST INTERPRETER_EXIT | 4,965,300 | 1.1% | 48.9% |
| POP_TOP RESUME_CHECK | 4,965,300 | 1.1% | 49.9% |
| CACHE POP_TOP | 4,965,240 | 1.1% | 51.0% |
| ENTER_EXECUTOR RETURN_CONST | 4,965,220 | 1.1% | 52.1% |
| SET_FUNCTION_ATTRIBUTE LOAD_FAST | 4,965,180 | 1.1% | 53.1% |
| RESUME_CHECK LOAD_FAST | 4,965,180 | 1.1% | 54.2% |
| MAKE_FUNCTION SET_FUNCTION_ATTRIBUTE | 4,965,180 | 1.1% | 55.3% |
| LOAD_FAST BUILD_TUPLE | 4,965,180 | 1.1% | 56.3% |
| LOAD_CONST MAKE_FUNCTION | 4,965,180 | 1.1% | 57.4% |
| COPY_FREE_VARS RETURN_GENERATOR | 4,965,180 | 1.1% | 58.5% |
| CALL_PY_EXACT_ARGS COPY_FREE_VARS | 4,965,180 | 1.1% | 59.5% |
| BUILD_TUPLE LOAD_CONST | 4,965,180 | 1.1% | 60.6% |
| GET_ITER CALL_PY_EXACT_ARGS | 4,965,160 | 1.1% | 61.7% |
| LOAD_FAST LOAD_CONST | 4,838,520 | 1.0% | 62.7% |
| LOAD_CONST BINARY_OP_ADD_INT | 4,838,480 | 1.0% | 63.7% |
| LOAD_FAST_LOAD_FAST BINARY_SUBSCR_LIST_INT | 4,838,340 | 1.0% | 64.8% |
| LOAD_FAST_LOAD_FAST UNARY_NEGATIVE | 4,838,280 | 1.0% | 65.8% |
| LOAD_FAST_LOAD_FAST LOAD_CONST | 4,156,920 | 0.9% | 66.7% |
| LOAD_FAST_LOAD_FAST BINARY_OP_SUBTRACT_INT | 4,156,900 | 0.9% | 67.6% |
| STORE_SUBSCR_LIST_INT ENTER_EXECUTOR | 4,156,860 | 0.9% | 68.5% |
| STORE_SLICE LOAD_FAST_LOAD_FAST | 4,156,860 | 0.9% | 69.4% |
| LOAD_CONST STORE_SLICE | 4,156,860 | 0.9% | 70.3% |
| BINARY_SLICE BINARY_OP | 4,156,860 | 0.9% | 71.2% |
| BINARY_OP_SUBTRACT_INT LOAD_FAST_LOAD_FAST | 4,156,860 | 0.9% | 72.1% |
| BINARY_OP_ADD_INT BINARY_SLICE | 4,156,860 | 0.9% | 73.0% |
| BINARY_OP LOAD_FAST_LOAD_FAST | 4,156,860 | 0.9% | 73.9% |
| LOAD_GLOBAL_BUILTIN LOAD_GLOBAL_BUILTIN | 2,546,120 | 0.5% | 74.4% |
| FOR_ITER_RANGE STORE_FAST | 2,546,040 | 0.5% | 75.0% |
| RETURN_GENERATOR CALL_BUILTIN_CLASS | 2,546,020 | 0.5% | 75.5% |
| LOAD_FAST GET_ITER | 2,545,980 | 0.5% | 76.0% |
| LOAD_FAST FOR_ITER_RANGE | 2,545,980 | 0.5% | 76.6% |
| CALL_BUILTIN_CLASS CALL_LEN | 2,545,980 | 0.5% | 77.1% |
| BINARY_SUBSCR_TUPLE_INT LOAD_FAST | 2,545,980 | 0.5% | 77.7% |
| FOR_ITER_LIST STORE_FAST | 2,419,340 | 0.5% | 78.2% |
| BINARY_SUBSCR_TUPLE_INT YIELD_VALUE | 2,419,340 | 0.5% | 78.7% |
| COMPARE_OP_INT POP_JUMP_IF_FALSE | 2,419,320 | 0.5% | 79.2% |
| YIELD_VALUE STORE_DEREF | 2,419,200 | 0.5% | 79.8% |
| TO_BOOL_INT POP_JUMP_IF_FALSE | 2,419,200 | 0.5% | 80.3% |
| SWAP COPY | 2,419,200 | 0.5% | 80.8% |
| STORE_SUBSCR_LIST_INT LOAD_FAST_LOAD_FAST | 2,419,200 | 0.5% | 81.3% |
| STORE_FAST LOAD_FAST_LOAD_FAST | 2,419,200 | 0.5% | 81.8% |
| STORE_DEREF LOAD_FAST | 2,419,200 | 0.5% | 82.4% |
| LOAD_FAST_LOAD_FAST LOAD_FAST | 2,419,200 | 0.5% | 82.9% |
| LOAD_FAST LOAD_GLOBAL_BUILTIN | 2,419,200 | 0.5% | 83.4% |
| LOAD_FAST FOR_ITER_LIST | 2,419,200 | 0.5% | 83.9% |
| LOAD_FAST BINARY_SLICE | 2,419,200 | 0.5% | 84.4% |
| LOAD_FAST BINARY_OP_ADD_INT | 2,419,200 | 0.5% | 85.0% |
| LOAD_CONST LOAD_FAST | 2,419,200 | 0.5% | 85.5% |
| LOAD_CONST BINARY_SLICE | 2,419,200 | 0.5% | 86.0% |
| JUMP_BACKWARD FOR_ITER_GEN | 2,419,200 | 0.5% | 86.5% |
| FOR_ITER_GEN RESUME_CHECK | 2,419,200 | 0.5% | 87.0% |
| COPY COMPARE_OP_INT | 2,419,200 | 0.5% | 87.6% |
| CALL_TUPLE_1 YIELD_VALUE | 2,419,200 | 0.5% | 88.1% |
| CALL_LEN SWAP | 2,419,200 | 0.5% | 88.6% |
| BINARY_SLICE LOAD_FAST_LOAD_FAST | 2,419,200 | 0.5% | 89.1% |
| BINARY_SLICE GET_ITER | 2,419,200 | 0.5% | 89.6% |
| BINARY_OP_ADD_INT YIELD_VALUE | 2,419,200 | 0.5% | 90.2% |
| BINARY_OP_ADD_INT LOAD_CONST | 2,419,200 | 0.5% | 90.7% |
| RETURN_GENERATOR CALL_TUPLE_1 | 2,419,180 | 0.5% | 91.2% |
| LOAD_FAST TO_BOOL_INT | 2,419,180 | 0.5% | 91.7% |
| UNARY_NEGATIVE STORE_SUBSCR | 2,419,140 | 0.5% | 92.2% |
| UNARY_NEGATIVE BINARY_SUBSCR | 2,419,140 | 0.5% | 92.8% |
| SWAP LOAD_FAST_LOAD_FAST | 2,419,140 | 0.5% | 93.3% |
| STORE_SUBSCR LOAD_GLOBAL_BUILTIN | 2,419,140 | 0.5% | 93.8% |
| POP_TOP POP_TOP | 2,419,140 | 0.5% | 94.3% |
| POP_TOP JUMP_FORWARD | 2,419,140 | 0.5% | 94.8% |
| POP_JUMP_IF_FALSE ENTER_EXECUTOR | 2,419,140 | 0.5% | 95.4% |
| JUMP_FORWARD LOAD_FAST | 2,419,140 | 0.5% | 95.9% |
| ENTER_EXECUTOR LOAD_FAST_LOAD_FAST | 2,419,140 | 0.5% | 96.4% |
| ENTER_EXECUTOR LOAD_CONST | 2,419,140 | 0.5% | 96.9% |
| BINARY_SUBSCR_LIST_INT SWAP | 2,419,140 | 0.5% | 97.4% |
| BINARY_SUBSCR_LIST_INT STORE_FAST | 2,419,140 | 0.5% | 98.0% |
| BINARY_SUBSCR LOAD_FAST_LOAD_FAST | 2,419,140 | 0.5% | 98.5% |
| POP_TOP JUMP_BACKWARD | 2,298,120 | 0.5% | 99.0% |
| POP_JUMP_IF_FALSE POP_TOP | 2,292,420 | 0.5% | 99.5% |
| ENTER_EXECUTOR BINARY_OP_ADD_INT | 1,737,660 | 0.4% | 99.8% |
| POP_JUMP_IF_FALSE LOAD_GLOBAL_BUILTIN | 126,840 | 0.0% | 99.9% |
| LOAD_FAST BINARY_OP_SUBTRACT_INT | 126,780 | 0.0% | 99.9% |
| COMPARE_OP_INT POP_JUMP_IF_TRUE | 126,780 | 0.0% | 99.9% |
| CALL_LEN COMPARE_OP_INT | 126,780 | 0.0% | 99.9% |
| BINARY_OP_SUBTRACT_INT YIELD_VALUE | 126,780 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE JUMP_BACKWARD | 121,260 | 0.0% | 100.0% |
| POP_JUMP_IF_TRUE JUMP_FORWARD | 5,520 | 0.0% | 100.0% |
| LOAD_DEREF YIELD_VALUE | 5,520 | 0.0% | 100.0% |
| JUMP_FORWARD LOAD_DEREF | 5,520 | 0.0% | 100.0% |
| BINARY_OP BINARY_OP | 1,020 | 0.0% | 100.0% |
| BINARY_SUBSCR BINARY_SUBSCR | 620 | 0.0% | 100.0% |
| STORE_SUBSCR STORE_SUBSCR | 600 | 0.0% | 100.0% |
| STORE_FAST LOAD_FAST | 240 | 0.0% | 100.0% |
| PUSH_NULL CALL | 240 | 0.0% | 100.0% |


</details>

## Predecessor/Successor Pairs

<details>
<summary> Top 5 predecessors and successors of each opcode </summary>

### BINARY_SLICE

<details>
<summary> Successors and predecessors for BINARY_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP_ADD_INT | 4,156,860 | 46.2% |
| LOAD_FAST | 2,419,200 | 26.9% |
| LOAD_CONST | 2,419,200 | 26.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_OP | 4,156,860 | 46.2% |
| LOAD_FAST_LOAD_FAST | 2,419,200 | 26.9% |
| GET_ITER | 2,419,200 | 26.9% |


</details>

### STORE_SLICE

<details>
<summary> Successors and predecessors for STORE_SLICE </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| LOAD_CONST | 4,156,860 | 100.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,156,860 | 100.0% |


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
| BINARY_SLICE | 4,156,860 | 100.0% |
| BINARY_OP | 1,020 | 0.0% |
| LOAD_CONST | 40 | 0.0% |
| LOAD_FAST_LOAD_FAST | 20 | 0.0% |
| LOAD_FAST | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,156,860 | 100.0% |
| BINARY_OP | 1,020 | 0.0% |
| BINARY_OP_ADD_INT | 40 | 0.0% |
| BINARY_OP_SUBTRACT_INT | 20 | 0.0% |
| BINARY_OP_SUBTRACT_FLOAT | 20 | 0.0% |


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
| POP_TOP | 39,721,260 | 85.8% |
| STORE_SUBSCR_LIST_INT | 4,156,860 | 9.0% |
| POP_JUMP_IF_FALSE | 2,419,140 | 5.2% |
| JUMP_BACKWARD | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| YIELD_VALUE | 34,756,120 | 75.1% |
| RETURN_CONST | 4,965,220 | 10.7% |
| LOAD_FAST_LOAD_FAST | 2,419,140 | 5.2% |
| LOAD_CONST | 2,419,140 | 5.2% |
| BINARY_OP_ADD_INT | 1,737,660 | 3.8% |


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
| BUILD_TUPLE | 4,965,180 | 26.4% |
| LOAD_FAST | 4,838,520 | 25.7% |
| LOAD_FAST_LOAD_FAST | 4,156,920 | 22.1% |
| BINARY_OP_ADD_INT | 2,419,200 | 12.9% |
| ENTER_EXECUTOR | 2,419,140 | 12.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| MAKE_FUNCTION | 4,965,180 | 26.4% |
| BINARY_OP_ADD_INT | 4,838,480 | 25.7% |
| STORE_SLICE | 4,156,860 | 22.1% |
| LOAD_FAST | 2,419,200 | 12.9% |
| BINARY_SLICE | 2,419,200 | 12.9% |


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
| LOAD_GLOBAL_BUILTIN | 4,965,420 | 15.5% |
| LOAD_DEREF | 4,965,320 | 15.5% |
| SET_FUNCTION_ATTRIBUTE | 4,965,180 | 15.5% |
| RESUME_CHECK | 4,965,180 | 15.5% |
| BINARY_SUBSCR_TUPLE_INT | 2,545,980 | 7.9% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SUBSCR_TUPLE_INT | 4,965,320 | 15.5% |
| BUILD_TUPLE | 4,965,180 | 15.5% |
| LOAD_CONST | 4,838,520 | 15.1% |
| GET_ITER | 2,545,980 | 7.9% |
| FOR_ITER_RANGE | 2,545,980 | 7.9% |


</details>

### LOAD_FAST_LOAD_FAST

<details>
<summary> Successors and predecessors for LOAD_FAST_LOAD_FAST </summary>

|Predecessors | Count | Percentage | 
|---|---:|---:|
| STORE_SLICE | 4,156,860 | 15.4% |
| BINARY_OP_SUBTRACT_INT | 4,156,860 | 15.4% |
| BINARY_OP | 4,156,860 | 15.4% |
| STORE_SUBSCR_LIST_INT | 2,419,200 | 9.0% |
| STORE_FAST | 2,419,200 | 9.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| STORE_SUBSCR_LIST_INT | 6,576,000 | 24.4% |
| BINARY_SUBSCR_LIST_INT | 4,838,340 | 17.9% |
| UNARY_NEGATIVE | 4,838,280 | 17.9% |
| LOAD_CONST | 4,156,920 | 15.4% |
| BINARY_OP_SUBTRACT_INT | 4,156,900 | 15.4% |


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
| LOAD_CONST | 4,838,480 | 53.8% |
| LOAD_FAST | 2,419,200 | 26.9% |
| ENTER_EXECUTOR | 1,737,660 | 19.3% |
| BINARY_OP | 40 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| BINARY_SLICE | 4,156,860 | 46.2% |
| YIELD_VALUE | 2,419,200 | 26.9% |
| LOAD_CONST | 2,419,200 | 26.9% |
| LOAD_FAST | 60 | 0.0% |
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
| LOAD_FAST_LOAD_FAST | 4,156,900 | 97.0% |
| LOAD_FAST | 126,780 | 3.0% |
| LOAD_CONST | 60 | 0.0% |
| BINARY_OP | 20 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| LOAD_FAST_LOAD_FAST | 4,156,860 | 97.0% |
| YIELD_VALUE | 126,780 | 3.0% |
| SWAP | 60 | 0.0% |
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
| LOAD_FAST_LOAD_FAST | 6,576,000 | 100.0% |
| SWAP | 60 | 0.0% |

|Successors | Count | Percentage | 
|---|---:|---:|
| ENTER_EXECUTOR | 4,156,860 | 63.2% |
| LOAD_FAST_LOAD_FAST | 2,419,200 | 36.8% |


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
| specialization.deferred |      2419200 | 19.8% |
|          hit |      9803720 | 80.2% |

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
| specialization.deferred |      2419140 | 26.9% |
|          hit |      6576060 | 73.1% |

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
| specialization.deferred |      4156860 | 23.8% |
|          hit |     13279200 | 76.2% |

#### Specialization attempts

| | Count | Ratio | 
|---|---:|---:|
| Success | 80 | 7.3% |
| Failure | 1,020 | 92.7% |

|Failure kind | Count | Ratio | 
|---|---:|---:|
| add other | 1,020 | 100.0% |


</details>

### CALL

<details>
<summary> specialization stats for CALL family </summary>

|Kind | Count | Ratio | 
|---|---|---|
| specialization.deferred |          240 | 0.0% |
|          hit |     12477060 | 100.0% |

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
|          hit |      2546100 | 100.0% |

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
|          hit |      7511980 | 100.0% |

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
| Basic | 326,882,060 | 70.2% |
| Not specialized | 29,535,320 | 6.3% |
| Specialized | 109,109,660 | 23.4% |

### Deferred by instruction

<details>
<summary> deferred by instruction </summary>

|Name | Count | Ratio | 
|---|---:|---:|
| BINARY_OP | 4,156,860 | 46.2% |
| BINARY_SUBSCR | 2,419,200 | 26.9% |
| STORE_SUBSCR | 2,419,140 | 26.9% |
| CALL | 240 | 0.0% |
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
| Interpreter increfs | 111,400,700 | 52.3% |
| Interpreter decrefs | 109,648,260 | 39.9% |
| Increfs | 101,609,560 | 47.7% |
| Decrefs | 165,251,280 | 60.1% |
| Materialize dict (on request) | 0 |  |
| Materialize dict (new key) | 0 |  |
| Materialize dict (too big) | 0 |  |
| Materialize dict (str subclass) | 0 |  |
| Dematerialize dict | 0 |  |
| Method cache hits | 15 |  |
| Method cache misses | 5 |  |
| Method cache collisions | 5 |  |
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

## Optimization (Tier 2) stats

<details>
<summary> statistics about the Tier 2 optimizer </summary>

### Overall stats

<details>
<summary> overall stats </summary>

| | Count | Ratio | 
|---|---:|---:|
| Optimization attempts | 142,320 |  |
| Traces created | 20 | 0.0% |
| Traces executed | 46,297,280 |  |
| Uops executed | 818,866,700 | 17 |
| Trace stack overflow | 0 |  |
| Trace stack underflow | 0 |  |
| Trace too long | 0 |  |
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
| <= 32 | 20 | 100.0% |

**Optimized trace length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 0 | 0.0% |
| <= 16 | 20 | 100.0% |

**Trace run length histogram**

|Range | Count | Ratio | 
|---|---:|---:|
| <= 1 | 0 | 0.0% |
| <= 2 | 0 | 0.0% |
| <= 4 | 0 | 0.0% |
| <= 8 | 4,965,220 | 10.7% |
| <= 16 | 16,934,260 | 36.6% |
| <= 32 | 20,241,000 | 43.7% |
| <= 64 | 4,156,800 | 9.0% |

### Uop stats

<details>
<summary> uop stats </summary>

|Uop | Count | Self | Cumulative | 
|---|---:|---:|---:|
| _SET_IP | 228,379,380 | 27.9% | 27.9% |
| LOAD_FAST | 94,827,460 | 11.6% | 39.5% |
| _POP_JUMP_IF_TRUE | 46,297,280 | 5.7% | 45.1% |
| _EXIT_TRACE | 46,297,280 | 5.7% | 50.8% |
| STORE_FAST | 41,332,060 | 5.0% | 55.8% |
| LOAD_DEREF | 34,756,120 | 4.2% | 60.1% |
| BINARY_SUBSCR_TUPLE_INT | 34,756,120 | 4.2% | 64.3% |
| _ITER_CHECK_RANGE | 26,943,840 | 3.3% | 67.6% |
| _IS_ITER_EXHAUSTED_RANGE | 26,943,840 | 3.3% | 70.9% |
| _GUARD_BOTH_INT | 26,135,460 | 3.2% | 74.1% |
| _ITER_NEXT_RANGE | 24,397,800 | 3.0% | 77.1% |
| _ITER_CHECK_LIST | 19,353,440 | 2.4% | 79.4% |
| _IS_ITER_EXHAUSTED_LIST | 19,353,440 | 2.4% | 81.8% |
| _BINARY_OP_ADD_INT | 18,672,060 | 2.3% | 84.1% |
| LOAD_CONST | 18,364,860 | 2.2% | 86.3% |
| _ITER_NEXT_LIST | 16,934,260 | 2.1% | 88.4% |
| SWAP | 13,151,880 | 1.6% | 90.0% |
| COPY | 13,151,880 | 1.6% | 91.6% |
| BINARY_SUBSCR_LIST_INT | 13,151,880 | 1.6% | 93.2% |
| _BINARY_OP_SUBTRACT_INT | 7,463,400 | 0.9% | 94.1% |
| _POP_JUMP_IF_FALSE | 6,575,940 | 0.8% | 94.9% |
| STORE_SUBSCR_LIST_INT | 6,575,940 | 0.8% | 95.7% |
| COMPARE_OP_INT | 6,575,940 | 0.8% | 96.5% |
| POP_TOP | 4,965,220 | 0.6% | 97.1% |
| _LOAD_GLOBAL_BUILTINS | 4,838,280 | 0.6% | 97.7% |
| _GUARD_GLOBALS_VERSION | 4,838,280 | 0.6% | 98.3% |
| _GUARD_BUILTINS_VERSION | 4,838,280 | 0.6% | 98.9% |
| CALL_BUILTIN_CLASS | 4,838,280 | 0.6% | 99.5% |
| GET_ITER | 2,419,140 | 0.3% | 99.8% |
| BINARY_SLICE | 1,737,660 | 0.2% | 100.0% |


</details>

### Unsupported opcodes

<details>
<summary> unsupported opcodes </summary>

|Opcode | Count | 
|---|---|
| FOR_ITER_GEN | 142,300 |
| YIELD_VALUE | 20 |


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
